#### Test 834526170a57107_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-31 15:56:00.105  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-31 15:56:00.105  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
08-31 15:56:00.105  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-31 15:56:00.106  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
,08-31 15:56:00.119  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-31 15:56:00.119  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-31 15:56:00.121  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-31 15:56:00.123  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 15:56:00.405  6673  6673 D AndroidRuntime: 
08-31 15:56:00.405  6673  6673 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 15:56:00.408  6673  6673 D AndroidRuntime: CheckJNI is OFF
08-31 15:56:00.533  6673  6673 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 15:56:00.538  1035  1716 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 15:56:00.548  1925  1941 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 15:56:00.551  1035  1716 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 15:56:00.553  1035  1716 D ActivityManager: setTaskToReturnTo : TaskRecord{1fd72ea2 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 15:56:00.553  1035  1716 D ActivityManager: setTaskToReturnTo : TaskRecord{1fd72ea2 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 15:56:00.554  1035  1716 D WindowStateEx: AppWindowTokenEx init.. 
08-31 15:56:00.555   329   356 E GBMv2   : DFP En is all cleared set to be enabled
08-31 15:56:00.589  1035  1716 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6692 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 15:56:00.590  6673  6673 D AndroidRuntime: Shutting down VM
08-31 15:56:00.654  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 15:56:00.654  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{393f71cb co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 15:56:00.656  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 15:56:00.656  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b17da8 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 15:56:00.726  6692  6692 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-31 15:56:00.827  6692  6692 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 15:56:00.837  6692  6692 I LibraryLoader: Loading: webviewchromium
08-31 15:56:00.841  6692  6692 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6051-6056)
,08-31 15:56:00.842  6692  6692 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:56:00.861  6692  6692 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d7530b1}
,08-31 15:56:00.862  6692  6692 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:56:00.863  6692  6692 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 15:56:00.874  6692  6692 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 15:56:00.876  6692  6692 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:56:00.888  6692  6692 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-31 15:56:00.888  6692  6692 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-31 15:56:00.889  6692  6692 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-31 15:56:00.900  6692  6692 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:56:00.900  6692  6692 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:56:00.900  6692  6692 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:56:00.900  6692  6692 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:56:00.900  6692  6692 I Adreno-EGL: Remote Branch: 
08-31 15:56:00.900  6692  6692 I Adreno-EGL: Local Patches: 
08-31 15:56:00.900  6692  6692 I Adreno-EGL: Reconstruct Branch: 
,08-31 15:56:00.906   313  1766 V AudioPolicyService: registerClient() client 0xb04104c0, uid 10118
08-31 15:56:00.911  1035  1117 D BluetoothManagerService: Message: 20
08-31 15:56:00.911  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@347c861c:true
08-31 15:56:00.991  6692  6729 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-31 15:56:00.998  6692  6692 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-31 15:56:01.017  6692  6692 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:56:01.022  6692  6692 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 15:56:01.026  6692  6692 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 15:56:01.029  6692  6692 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 15:56:01.029  6692  6692 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-31 15:56:01.043  6692  6692 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 15:56:01.051  6692  6692 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:56:01.051  6692  6692 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:56:01.096  6692  6741 D OpenGLRenderer: Render dirty regions requested: true
08-31 15:56:01.096  6692  6741 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 15:56:01.101  6692  6741 D OpenGLRenderer: Enabling debug mode 0
08-31 15:56:01.110  6692  6692 D Atlas   : Validating map...
,08-31 15:56:01.115  1035  2035 D SplitWindow: check instance of lgWin Window{24f77876 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 15:56:01.192  6692  6739 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:56:01.192  6692  6739 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:01.241  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +588ms (total +685ms)
08-31 15:56:01.241  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12206733 u0 com.test.thalitest/.MainActivity t6} time:196457
,08-31 15:56:01.249  6692  6692 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@213a4334 time:196465
08-31 15:56:01.367  6692  6692 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 15:56:01.367  6692  6692 I chromium: 
,08-31 15:56:01.387  6692  6692 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 15:56:01.488  6692  6739 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 15:56:01.488  6692  6739 I chromium: 
,08-31 15:56:01.568   329   358 E GBMv2   : DFP En is all cleared set to be enabled
08-31 15:56:01.569   329   358 E GBMv2   : Set value is all cleared set the max
08-31 15:56:01.569   329   358 I GBMv2   : DFP Enabled. Ignore VFP set
,08-31 15:56:01.646  6692  6755 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-31 15:56:01.666  6692  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 15:56:01.666  6692  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 15:56:01.666  6692  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 15:56:01.666  6692  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 15:56:01.666  6692  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 15:56:01.667  6692  6755 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35c961b8 added. We now have 1 listener(s)
,08-31 15:56:01.673  1035  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:01.678  6692  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-31 15:56:01.680  6692  6755 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:01.681  6692  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:01.681  6692  6755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 15:56:01.689  6692  6755 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9015ef7 added. We now have 1 listener(s)
08-31 15:56:01.690  6692  6755 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:56:01.697  1035  1526 D WifiService: New client listening to asynchronous messages
08-31 15:56:01.701  6692  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:56:01.701  6692  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 15:56:01.703  6692  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 15:56:01.703  6692  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 15:56:01.703  6692  6755 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 15:56:01.709  6692  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:01.709  1035  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:01.710  6692  6755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-31 15:56:01.720  6692  6755 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-31 15:56:01.720  6692  6755 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:01.720  6692  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:01.720  6692  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:01.720  6692  6755 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:01.720  6692  6755 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:01.720  6692  6755 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:01.720  6692  6755 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:01.720  6692  6755 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:01.720  6692  6755 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 15:56:01.721  6692  6755 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:56:01.725  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:01.727  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:01.727  6692  6755 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 15:56:01.762  6692  6692 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 15:56:02.489  6692  6758 W jxcore-log: Initializing JXcore engine
08-31 15:56:02.489  6692  6758 W jxcore-log: JXcore engine is ready
,08-31 15:56:02.515  6758  6758 W Thread-777: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[6080]" dev="sockfs" ino=6080 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-31 15:56:02.515  6758  6758 W Thread-777: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-31 15:56:02.515  6758  6758 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7543]" dev="sockfs" ino=7543 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 15:56:02.515  6758  6758 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 15:56:02.515  6758  6758 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32925]" dev="sockfs" ino=32925 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-31 15:56:02.563  6692  6758 W jxcore-log: Starting JXcore engine
,08-31 15:56:02.727  6692  6758 W jxcore-log: Platform android
08-31 15:56:02.727  6692  6758 W jxcore-log: 
08-31 15:56:02.728  6692  6758 W jxcore-log: Process ARCH arm
08-31 15:56:02.728  6692  6758 W jxcore-log: 
,08-31 15:56:03.027  6692  6758 I jxcore-log: JXcore Cordova bridge is ready!
08-31 15:56:03.027  6692  6758 I jxcore-log: 
08-31 15:56:03.028  6692  6758 W jxcore-log: JXcore engine is started
,08-31 15:56:03.034  6692  6755 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 15:56:03.037  6692  6692 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 15:56:12.621  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 15:56:12.621  6692  6758 I jxcore-log: 
,08-31 15:56:12.624  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 15:56:12.624  6692  6758 I jxcore-log: 
08-31 15:56:12.629  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:12.629  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:12.629  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:12.629  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:12.629  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:12.629  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:12.629  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:12.629  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:12.631  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:12.633  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 15:56:12.633  6692  6758 I jxcore-log: 
08-31 15:56:12.635  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 15:56:12.635  6692  6758 I jxcore-log: 
,08-31 15:56:13.136  6692  6758 D executeNativeTests: Running unit tests
,08-31 15:56:13.220  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 15:56:13.220  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 added. We now have 2 listener(s)
08-31 15:56:13.220  1035  1639 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:56:13.222  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:13.222  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:13.222  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:13.223  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:13.223  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 added. We now have 2 listener(s)
08-31 15:56:13.223  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:13.223  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:56:13.226  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:56:13.230  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:13.230  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.230  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.230  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:13.230  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:13.230  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.230  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:13.230  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:13.231  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.231  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:56:13.233  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.235  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.241  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:56:13.244  6692  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:56:13.244  6692  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 15:56:13.246  6692  6758 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 15:56:13.247  6692  6758 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 15:56:13.247  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:56:13.247  6692  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:56:13.247  6692  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:56:13.247  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.248  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.248  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:56:13.249  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.249  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.249  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:13.249  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:13.249  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 removed from the list
08-31 15:56:13.249  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.249  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 removed from the list
08-31 15:56:13.249  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.249  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.252  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.252  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.253  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.253  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.253  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.253  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.254  6692  6758 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 15:56:13.254  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.254  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.255  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.255  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-31 15:56:13.255  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.255  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.255  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.255  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.255  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.255  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.255  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.255  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.255  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.255  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:56:13.255  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.255  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.255  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.255  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
,08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 15:56:13.259  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Pee,r: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 15:56:13.260  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.260  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.260  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.260  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.260  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.260  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.260  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.260  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.260  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.260  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.260  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.260  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.260  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.260  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.261  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.261  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.261  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:56:13.261  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.262  6692  6758 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:56:13.263  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:13.267  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:13.267  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.267  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.267  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:13.267  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:13.267  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.267  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:13.267  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:13.268  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.268  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:56:13.269  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.269  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:56:13.270  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 15:56:13.270  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.270  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:56:13.270  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:13.270  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:56:13.273  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 15:56:13.273  1035  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-31 15:56:13.277  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 15:56:13.281  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 15:56:13.283  6692  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 15:56:13.284  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:56:13.284  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:13.285  6692  6758 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-31 15:56:13.285  6692  6758 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:56:13.288  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.288  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.288  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.288  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.288  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.288  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:13.288  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.288  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.288  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.288  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.288  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.288  6692  6758 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:56:13.289  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:13.291  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:13.291  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.291  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.291  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:13.291  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:13.291  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.291  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:13.291  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:13.293  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.293  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:56:13.294  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.294  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:56:13.295  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:56:13.295  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:56:13.295  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:13.295  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirect,Manager: bind: Binding a new listener
08-31 15:56:13.296  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.298  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:56:13.298  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:13.299  6692  6758 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:56:13.299  6692  6758 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:56:13.300  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.300  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.300  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.300  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.300  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.300  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:13.300  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.300  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.300  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.300  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.300  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.301  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.301  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.301  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.301  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.302  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.303  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.303  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.303  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.303  6692  6758 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:56:13.305  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:13.306  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:13.306  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.306  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.306  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:13.306  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:13.306  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.306  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:13.306  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:13.307  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.307  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:56:13.308  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.309  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:56:13.309  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:56:13.309  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:56:13.309  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:13.309  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:56:13.314  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.381  1035  1978 I art     : Explicit concurrent mark sweep GC freed 31160(1474KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.997ms total 71.600ms
08-31 15:56:13.384  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:56:13.384  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:56:13.386  6692  6758 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:56:13.386  6692  6758 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:56:13.386  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.386  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.386  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.387  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.387  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.387  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.387  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.387  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.387  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:13.387  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.387  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.387  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.387  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.387  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.389  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.389  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.390  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.390  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.391  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.391  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.391  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.391  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.391  6692  6758 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 15:56:13.392  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.392  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.392  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, sk,ipping...
08-31 15:56:13.392  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.392  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.392  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.392  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.392  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.392  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.392  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.392  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.392  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.392  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.392  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.393  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.393  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.393  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.393  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.393  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.393  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.394  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 15:56:13.394  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.394  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.394  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.394  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.394  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.394  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.395  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.395  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.395  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.395  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.395  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bl,uetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.395  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.395  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.395  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.397  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.397  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.401  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.401  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.401  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.401  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.401  6692  6758 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 15:56:13.401  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.401  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.401  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.402  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.402  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.402  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.402  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.402  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.402  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.402  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.402  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.402  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.402  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.402  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.403  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.403  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.404  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.404  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.404  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.404  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.404  6692  6758 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 15:56:13.404  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.404  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.404  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.404  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.404  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.405  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.405  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.405  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.405  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.405  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.405  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.405  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.405  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.405  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.405  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.405  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.405  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.405  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.405  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.405  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.406  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:56:13.407  6692  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:56:13.407  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:56:13.407  6692  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:56:13.407  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:56:13.407  6692  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:56:13.407  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.407  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.407  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.407  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.407  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.407  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.407  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.407  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.407  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.407  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.407  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.407  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.407  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.407  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.408  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.408  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.408  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.408  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.408  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.408  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.409  6692  6758 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:56:13.409  6692  6758 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 15:56:13.409  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 15:56:13.411  6692  6758 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:56:13.411  6692  6758 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 15:56:13.411  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 15:56:13.412  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 15:56:13.412  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 15:56:13.412  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:56:13.412  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 15:56:13.412  6692  6758 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 15:56:13.412  6692  6758 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:56:13.412  6692  6758 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 15:56:13.414  6692  6758 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:56:13.414  6692  6758 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:56:13.415  6692  6758 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 15:56:13.416  6692  6758 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:56:13.416  6692  6758 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:56:13.416  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 15:56:13.417  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 15:56:13.417  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 15:56:13.417  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 15:56:13.418  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 15:56:13.418  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 15:56:13.418  6692  6758 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 15:56:13.418  6692  6758 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:56:13.419  6692  6758 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 15:56:13.420  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.420  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.420  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.420  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.420  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.420  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:56:13.420  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 15:56:13.420  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.420  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.420  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.420  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.420  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.421  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.421  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.421  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.422  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.422  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.422  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.422  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.422  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.422  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.422  6692  6758 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 15:56:13.423  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.423  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.423  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.427  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.427  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.427  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.427  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.427  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.427  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.427  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.427  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.427  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.427  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.427  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.428  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.428  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.428  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.428  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.428  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.428  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.428  6692  6758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 15:56:13.429  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.429  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.429  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.430  6692  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
08-31 15:56:13.436  6692  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
08-31 15:56:13.436  6692  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 841)
08-31 15:56:13.436  6692  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 841)
08-31 15:56:13.438  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.438  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.438  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.438  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.438  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.438  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.438  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.438  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.438  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.438  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.438  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.439  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.439  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.440  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.440  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.440  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.440  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.440  6692  6758 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 15:56:13.440  6692  6758 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 15:56:13.440  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:56:13.440  6692  6758 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 15:56:13.440  6692  6758 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:56:13.441  6692  6758 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 15:56:13.441  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:56:13.441  6692  6758 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 15:56:13.441  6692  6758 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:56:13.441  6692  6758 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 15:56:13.441  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:56:13.441  6692  6758 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 15:56:13.441  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.441  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.441  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.441  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.441  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.441  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.441  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.441  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.441  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.441  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.442  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.442  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.442  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.442  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.442  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.442  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.443  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.443  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.443  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.443  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.443  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.443  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.443  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.443  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.443  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.443  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.443  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.443  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.443  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.443  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.443  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.444  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.444  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.444  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.444  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.444  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.444  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.444  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.444  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.444  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.444  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.444  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.444  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.445  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.445  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.445  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.445  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.445  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.445  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.446  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.446  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.446  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.446  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.446  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.446  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.448  6692  6758 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 15:56:13.448  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:56:13.451  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 15:56:13.464  6692  6758 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 15:56:13.464  6692  6758 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 15:56:13.465  6692  6692 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 15:56:13.465  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 15:56:13.465  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:56:13.466  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.466  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 15:56:13.466  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 15:56:13.466  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 15:56:13.466  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.466  6692  6758 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 15:56:13.466  6692  6692 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 15:56:13.466  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.466  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.466  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:56:13.466  6692  6758 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:56:13.466  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 15:56:13.466  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 15:56:13.467  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:13.467  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:13.467  6692  6758 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 15:56:13.467  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.467  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.467  6692  6758 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:56:13.468  6692  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:56:13.468  6692  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:56:13.468  6692  6692 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:56:13.468  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.468  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.468  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.468  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.468  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.468  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.468  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.468  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.468  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.468  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.468  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.468  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.468  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.468  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.468  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.469  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.469  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.469  6692  6758 I org.thaliproject.p2p.btconnectorlib.Discover,yManager: dispose
08-31 15:56:13.469  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.469  6692  6758 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 15:56:13.470  6692  6761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 15:56:13.470  6692  6761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 15:56:13.471  6692  6758 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 15:56:13.471  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:56:13.472  6692  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:56:13.472  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.472  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.472  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.472  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.472  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.472  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.472  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.472  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.472  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.472  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.472  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.472  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.472  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.472  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.472  6692  6692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 15:56:13.473  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.473  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.473  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.473  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.475  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15,:56:13.476  1035  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:13.476  1035  1716 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:13.477  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.477  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.477  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.477  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.477  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.477  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.477  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.477  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.477  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.477  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.477  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.477  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.477  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.477  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.478  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.478  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.478  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.478  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.478  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:13.478  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:13.478  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:13.478  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:13.478  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.479  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.479  6692  6758 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc5a88 not in the list
08-31 15:56:13.479  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.479  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.479  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:13.479  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.479  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.479  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:13.479  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:13.479  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:13.479  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:13.479  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:13.479  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f82c21 not in the list
08-31 15:56:13.480  6692  6758 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 15:56:13.480  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:56:13.480  6692  6758 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 15:56:13.480  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:56:13.480  6692  6758 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 15:56:13.480  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:56:13.481  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 15:56:13.482  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 15:56:13.482  6692  6758 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 15:56:13.482  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:56:13.482  6692  6758 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 15:56:13.482  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:56:13.482  6692  6758 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 15:56:13.482  6692  6758 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 15:56:13.483  6692  6758 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 15:56:13.483  6692  6758 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 15:56:13.483  6692  6758 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 15:56:13.483  6692  6758 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 15:56:13.483  6692  6758 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 15:56:13.483  6692  6758 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 15:56:13.484  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:13.484  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ec4da1e added. We now have 2 listener(s)
08-31 15:56:13.484  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:13.485  6692  6758 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 15:56:13.486  1035  2035 D WifiServiceImplEx: setWifiEnabled: true pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:56:13.487  1035  2035 D WifiService: setWifiEnabled: true pid=6692, uid=10118
08-31 15:56:13.487  1035  2035 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 15:56:13.494  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:13.494  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@257a32ff added. We now have 3 listener(s)
08-31 15:56:13.494  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:13.506  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:13.506  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20cb98cc added. We now have 4 listener(s)
08-31 15:56:13.506  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:13.507  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:13.507  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39066715 added. We now have 5 listener(s)
08-31 15:56:13.507  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:13.509  1035  2035 D WifiServiceImplEx: setWifiEnabled: false pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:56:13.509  1035  2035 D WifiService: setWifiEnabled: false pid=6692, uid=10118
08-31 15:56:13.509  1035  2035 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:56:13.518  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:56:13.518  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:56:13.518  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 15:56:13.519  1035  1521 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 15:56:13.519  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 15:56:13.519  1035  1521 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 15:56:13.520  1035  1521 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 15:56:13.520  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 15:56:13.520  1035  1521 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 15:56:13.520  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:56:13.520  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 15:56:13.520  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:13.521  1035  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@75ad9f1 mBinding = false
08-31 15:56:13.522  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 15:56:13.522  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 15:56:13.529  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 15:56:13.529  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 15:56:13.529  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.529  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.530  2699  2699 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 15:56:13.530  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 15:56:13.530  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:56:13.530  6692  6759 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-31 15:56:13.531  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:56:13.531   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:56:13.531  1035  2844 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:56:13.538  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:56:13.538  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:56:13.538  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 15:56:13.539  1035  1117 D BluetoothManagerService: Message: 2
08-31 15:56:13.539  6692  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
08-31 15:56:13.541  1035  1117 D BluetoothManagerService: Sending off request.
08-31 15:56:13.541  3850  3868 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 15:56:13.545  3850  3927 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 15:56:13.545  3850  3927 D BluetoothAdapterProperties: Setting state to 13
08-31 15:56:13.545  3850  3927 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 15:56:13.546  3850  3927 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 15:56:13.546  3850  3927 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 15:56:13.546  1035  1117 D BluetoothManagerService: Message: 60
08-31 15:56:13.546  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 15:56:13.548  1035  1639 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-31 15:56:13.548  1035  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.548  1035  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.548  1035  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 15:56:13.548  1035  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.548  1035  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-31 15:56:13.551  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 15:56:13.552  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:13.554  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:13.555  3850  3850 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:13.555  3850  3850 D BluetoothMapService: STATE_TURNING_OFF
08-31 15:56:13.555  3850  3850 V BluetoothMapService: Handler(): got msg=4
08-31 15:56:13.555  3850  3850 D BluetoothMapService: MAP Service closeService in
08-31 15:56:13.555  3850  3850 D BluetoothMapMasInstance: MAP Service shutdown
08-31 15:56:13.556  3850  4129 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 15:56:13.556  3850  4129 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:13.556  3850  4129 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 15:56:13.556  3850  4129 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 15:56:13.556  3850  4129 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 15:56:13.556  3850  4129 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 15:56:13.556  3850  4129 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 15:56:13.556  3850  4129 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 15:56:13.558  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:56:13.560  3850  3850 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:56:13.560  3850  3850 V BluetoothMapService: MAP Service closeService out
08-31 15:56:13.560  3850  3850 V BtOppService: Receiver DISABLED_ACTION 
08-31 15:56:13.560  3850  3850 I BtOppRfcommListener: stopping Accept Thread
08-31 15:56:13.560  3850  3850 V BtOppRfcommListener: close mBtServerSocket
08-31 15:56:13.560  3850  4183 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:13.560  3850  4183 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 15:56:13.561  3850  3850 V BtOppRfcommListener: waiting for thread to terminate
08-31 15:56:13.561  3850  3850 V BtOppRfcommListener: done waiting for thread to terminate
08-31 15:56:13.561  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.561  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:13.561  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.561  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.561  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:13.561  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:13.561  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.561  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:13.561  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:13.562  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for m,ultiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.562  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:13.562  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:56:13.564  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.566  1035  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 15:56:13.566  1035  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-31 15:56:13.578  1035  1113 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6777 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 15:56:13.581  3850  3930 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:56:13.582  3850  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 15:56:13.582  3850  3927 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 15:56:13.583  3850  4188 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:13.584  3850  4130 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:13.584  3850  3850 V BtOppService: onDestroy
08-31 15:56:13.584  3850  4186 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:13.585  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 15:56:13.585  3850  4010 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 15:56:13.586  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 15:56:13.586  3850  4010 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 15:56:13.588  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.588  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:13.588  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.588  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.588  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:13.588  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:13.588  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:13.588  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:13.588  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:13.588  3850  3850 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 15:56:13.589  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.589  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:56:13.590  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.591  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:13.591  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.591  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.591  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:13.591  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:13.591  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:13.591  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:13.591  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:13.591  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.591  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:13.591  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-31 15:56:13.594  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 15:56:13.595  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:13.595  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:13.595  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:56:13.595  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-31 15:56:13.595  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.595  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:13.595  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.595  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.595  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:13.595  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:13.595  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:13.595  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:13.595  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:13.595  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:13.595  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:13.595  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:56:13.596  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 15:56:13.596  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-31 15:56:13.596  1035  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMa,chine$SmHandler }
08-31 15:56:13.596  1035  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.597  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.598  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:13.598  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:13.599  1035  1520 D LGWifiP2pService: InactiveState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.599  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.599  1035  1520 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@a23a0b7
08-31 15:56:13.600  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:13.600  1035  1521 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 15:56:13.600  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:13.601  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:13.601  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 15:56:13.606  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.618  1035  1113 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6796 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-31 15:56:13.618  1035  1520 D LGWifiP2pService: P2pDisablingState
08-31 15:56:13.618  1035  1520 D LGWifiP2pService: P2pDisablingState{ when=-20ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.619  1035  1520 D LGWifiP2pService: p2p socket connection lost
08-31 15:56:13.619  1035  1520 D LGWifiP2pService: P2pDisabledState
08-31 15:56:13.620  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 15:56:13.620  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 15:56:13.620  2699  2699 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 15:56:13.620  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.620  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 15:56:13.620  1035  1520 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.620  1925  1925 D WfdsService: WifiP2pState is changed : false
08-31 15:56:13.620  1925  2306 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 15:56:13.620  1925  2306 D WfdsService: Set the WFDS Monitor: false
08-31 15:56:13.620  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 15:56:13.620  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:56:13.620  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:56:13.622  1925  2306 D WfdsMonitor: WFDS Monitor is stopped
08-31 15:56:13.622  1925  2749 D CtrlSupplicant: Received on exit socket, terminate
08-31 15:56:13.622  1925  2306 D WfdsService: STATE : WfdsDisabledState - enter
08-31 15:56:13.622  1925  2749 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 15:56:13.622  1925  2749 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 15:56:13.622  1925  2749 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 15:56:13.622  1925  2306 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 15:56:13.624  1925  2310 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 15:56:13.635  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:13.635  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 15:56:13.637  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:13.638   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:56:13.638  1035  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 15:56:13.638  1035  1527 D DSQN    : disableDataServiceNotify
08-31 15:56:13.638  1035  1527 D DSQN    : stop dsqn bin
08-31 15:56:13.638   309  6814 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 15:56:13.639  1035  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-31 15:56:13.639  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 15:56:13.640  1035  1521 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 15:56:13.640  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-31 15:56:13.640  1035  1521 D WifiNative-p2p0: TERMINATE: returned true
08-31 15:56:13.640  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:56:13.640  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:56:13.640  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:56:13.642  1035  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 15:56:13.642  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:13.643  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:13.643  1035  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:13.643  1035  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 15:56:13.643  1035  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.643  1035  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.643  1035  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 15:56:13.643  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:13.643  1035  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 15:56:13.643  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:13.643  1035  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 15:56:13.643  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:56:13.643  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 15:56:13.644  1035  15,27 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:13.644  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 15:56:13.644  1035  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:13.644  1035  1527 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:13.644  1035  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:13.645  1586  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 15:56:13.645  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:13.645  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 15:56:13.645  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 15:56:13.645  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 15:56:13.645  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 15:56:13.645  1035  1527 D NetworkManagementService: Removing idletimer
08-31 15:56:13.646  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 15:56:13.646  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 15:56:13.646  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 15:56:13.646  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 15:56:13.646  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 15:56:13.646  1035  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:13.646  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 15:56:13.647  1035  1527 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 15:56:13.647  1035  1521 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:13.647  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:13.648  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 15:56:13.648  1035  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 15:56:13.648  1035  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 15:56:13.648  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:13.648  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 15:56:13.654  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.654  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:13.654  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.654  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.654  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:13.654  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:13.654  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:13.654  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:13.654  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:13.660  6777  6777 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:56:13.660  6777  6777 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 15:56:13.660  6777  6777 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:56:13.660  6777  6777 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-31 15:56:13.661  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:13.661  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:13.661  6777  6777 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 15:56:13.662  6777  6777 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 15:56:13.662  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.662  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:13.663  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.663  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:13.663  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:13.663  6692  6692 V io.jxcore.node.ConnectivityMo,nitor:     - is Wi-Fi Direct supported: true
08-31 15:56:13.663  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:13.663  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:13.663  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:13.663  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:13.663  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:13.663  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:56:13.665  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:13.665  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:13.670  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 15:56:13.670  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:13.673  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:56:13.686  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:56:13.687  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:13.687  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:56:13.700  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:56:13.700  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:13.701  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:13.701  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:13.726  6796  6796 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 15:56:13.726  6796  6796 W LG Account v2.2: No ProfileInfo entries
08-31 15:56:13.727  6796  6796 I LG Account v2.2: isEnabled: false
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]Country: EU
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]Operator: OPEN
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]Ranking support: false
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]Comfort support: false
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]Accessory: true
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]Health device: true
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]Extra Pedometer: false
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]Blood glucose device: false
08-31 15:56:13.727  6796  6796 I Feature : [Lifetracker]Device Number: 3
08-31 15:56:13.733  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:56:13.740  1035  2844 D DhcpStateMachine: StoppedState
,08-31 15:56:13.740  1035  2844 D DhcpStateMachine: StoppedState{ when=-119ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:13.758  2699  2699 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 15:56:13.758  2699  2699 I wpa_supplicant: monitor socket send errors count : 1
08-31 15:56:13.758  2699  2699 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-2\x00 that cannot receive messages
,08-31 15:56:13.762  1035  2744 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 15:56:13.762  1035  2744 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 15:56:13.762  6777  6777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 15:56:13.768  1035  1639 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6819 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 15:56:13.769  1035  1639 I ActivityManager: Killing 6205:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-31 15:56:13.783   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 12.726ms
,08-31 15:56:13.798   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 13.756ms
,08-31 15:56:13.799  2699  2699 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:56:13.800  1035  2744 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 15:56:13.800  1035  2744 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:56:13.800  1035  2744 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:56:13.800  2699  2699 W wpa_supplicant: USIM:  scard_deinit function
08-31 15:56:13.800  1035  2744 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 15:56:13.801  1035  1117 D Tethering: InitialState.processMessage what=4
08-31 15:56:13.802  1035  1521 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=209005
08-31 15:56:13.802  1035  1521 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=209006
08-31 15:56:13.803  1035  2744 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:13.804  1035  2744 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:13.804  1035  1521 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=209007  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 15:56:13.805  1035  1521 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=209008  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 15:56:13.820   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 434us total 21.337ms
,08-31 15:56:13.856  2699  2699 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-31 15:56:13.856  1035  2744 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 15:56:13.857  1035  2744 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 15:56:13.857  1035  2744 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 15:56:13.859  1035  1521 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-31 15:56:13.867  1035  1906 W libprocessgroup: failed to open /acct/uid_10014/pid_6205/cgroup.procs: No such file or directory
08-31 15:56:13.871  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 15:56:13.879  1035  1117 D BluetoothManagerService: Message: 20
08-31 15:56:13.879  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2201c7b0:true
08-31 15:56:13.885  3850  3850 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:56:13.886  3850  3850 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:13.886  3850  3850 V BluetoothPbapReceiver: ***********state = 13
,08-31 15:56:13.888  3850  3850 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 15:56:13.893  3850  3850 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:13.893  3850  3850 V BluetoothPbapService: state: 13
08-31 15:56:13.893  3850  3850 V BluetoothPbapService: Pbap Service closeService in
08-31 15:56:13.894  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:56:13.896  3850  3850 V BluetoothPbapService: successfully stopped pbap service
08-31 15:56:13.896  3850  3850 V BluetoothPbapService: Pbap Service closeService out
08-31 15:56:13.897  3850  3850 V BluetoothPbapService: Pbap Service onDestroy
08-31 15:56:13.897  3850  3850 V BluetoothPbapService: Pbap Service closeService in
08-31 15:56:13.897  3850  3850 V BluetoothPbapService: Pbap Service closeService out
08-31 15:56:13.897  3850  3850 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 15:56:13.902  1035  1117 D BluetoothManagerService: Message: 30
,08-31 15:56:13.908  1035  1117 D BluetoothManagerService: Message: 30
08-31 15:56:13.911  6777  6777 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 15:56:13.912  6777  6777 D BluetoothMap: Create BluetoothMap proxy object
08-31 15:56:13.913  1035  1117 D BluetoothManagerService: Message: 30
,08-31 15:56:13.918  1035  1117 D BluetoothManagerService: Message: 30
08-31 15:56:13.920  6777  6777 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 15:56:13.921  6777  6777 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-31 15:56:13.936  6777  6777 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-31 15:56:13.939  6777  6777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-31 15:56:13.947  6819  6819 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-31 15:56:13.951  6777  6777 D DockEventReceiver: finishStartingService: stopping service
08-31 15:56:13.952  6777  6777 D BluetoothInputDevice: Proxy object connected
08-31 15:56:13.953  6777  6777 D HidProfile: Bluetooth service connected
08-31 15:56:13.953  6819  6819 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:56:13.954  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:13.956  1035  1051 I ActivityManager: Killing 6296:com.android.defcontainer/u0a4 (adj 15): empty #17
08-31 15:56:13.965  6777  6777 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 15:56:13.966  6777  6777 D PanProfile: Bluetooth service connected
08-31 15:56:13.967  6777  6777 D BluetoothMap: Proxy object connected
08-31 15:56:13.968  6777  6777 D MapProfile: Bluetooth service connected
08-31 15:56:13.968  6777  6777 D BluetoothMap: getConnectedDevices()
08-31 15:56:13.969  6692  6692 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-31 15:56:13.970  6777  6777 D BluetoothMap: Bluetooth is Not enabled
08-31 15:56:13.970  6777  6777 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 15:56:13.986  1035  1521 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 15:56:13.986  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:56:13.986  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:56:13.986  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:56:13.986  1925  1925 D WfdsService: Supplicant Connection state is changed : false
,08-31 15:56:13.987  1925  2306 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-31 15:56:13.987  1925  2306 D WfdsService: Set the WFDS Monitor: false
08-31 15:56:13.987  1925  2306 D WfdsMonitor: WFDS Monitor is stopped
08-31 15:56:13.989  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 15:56:13.989  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:13.991  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:13.995  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.996  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:13.997  1035  1639 W libprocessgroup: failed to open /acct/uid_10004/pid_6296/cgroup.procs: No such file or directory
08-31 15:56:14.000  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 15:56:14.000  1035  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 15:56:14.000  1035  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-31 15:56:14.009  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:56:14.048  6777  6777 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:56:14.048  6777  6777 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:56:14.060  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:56:14.063  6777  6777 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 15:56:14.069  6777  6777 D BluetoothPermissionRequest: onReceive
08-31 15:56:14.072  6777  6777 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 15:56:14.081  1035  1050 I ActivityManager: Killing 6432:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-31 15:56:14.087  6777  6777 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 15:56:14.139  3850  3850 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-31 15:56:14.139  3850  3850 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 15:56:14.141  3850  3850 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 15:56:14.143  1035  1559 W libprocessgroup: failed to open /acct/uid_10008/pid_6432/cgroup.procs: No such file or directory
08-31 15:56:14.191  1035  1521 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
08-31 15:56:14.192  1035  1521 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 15:56:14.194  1035  1521 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:14.195  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 15:56:14.220  1035  1906 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6851 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-31 15:56:14.222  3850  3850 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:14.222  3850  3850 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-31 15:56:14.227  3850  3850 V BluetoothFtpService: Ftp Service onStartCommand
08-31 15:56:14.227  3850  3850 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:14.227  3850  3850 V BluetoothFtpService: Ftp Service closeService
08-31 15:56:14.227  3850  3850 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 15:56:14.228  3850  3850 V BluetoothFtpService: successfully stopped ftp service
08-31 15:56:14.229  3850  3850 V BluetoothFtpService: Ftp Service onDestroy
08-31 15:56:14.229  3850  3850 V BluetoothFtpService: Ftp Service closeService
08-31 15:56:14.232  3850  3850 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:56:14.232  3850  3850 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:56:14.232  3850  3850 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:56:14.232  3850  3850 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:14.232  3850  3850 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 15:56:14.232  3850  3850 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 15:56:14.234  3850  3850 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:14.235  3850  3850 V BluetoothSapService: state: 13
08-31 15:56:14.235  3850  3850 V BluetoothSapService: Stopping SAP server process
,08-31 15:56:14.238  3850  3850 V BluetoothSapService: Sap Service closeSapService in
08-31 15:56:14.238  3850  3850 V BluetoothSapService: Close listen Socket : 
08-31 15:56:14.238  3850  3850 V BluetoothSapService: Close rfcomm Socket : 
08-31 15:56:14.238  3850  3850 V BluetoothSapService: Close sapd  Socket : 
08-31 15:56:14.287  1035  1959 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6868 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 15:56:14.288  3850  3850 V BluetoothSapService: Sap Service closeSapService out
08-31 15:56:14.288  3850  3850 V BluetoothSapService: Sap Service onDestroy
08-31 15:56:14.288  3850  3850 V BluetoothSapService: Sap Service closeSapService in
08-31 15:56:14.288  3850  3850 V BluetoothSapService: Close listen Socket : 
08-31 15:56:14.288  3850  3850 V BluetoothSapService: Close rfcomm Socket : 
08-31 15:56:14.288  3850  3850 V BluetoothSapService: Close sapd  Socket : 
08-31 15:56:14.297  3850  3850 V BluetoothSapService: Sap Service closeSapService out
08-31 15:56:14.318  6851  6851 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 15:56:14.343  6868  6868 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 15:56:14.349  6851  6851 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-31 15:56:14.359  1035  1050 I ActivityManager: Killing 5993:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-31 15:56:14.386  6851  6851 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-31 15:56:14.386  6851  6851 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 15:56:14.387  6851  6851 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 15:56:14.387  6851  6851 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 15:56:14.388  6851  6851 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 15:56:14.389  6851  6851 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 15:56:14.396  6851  6851 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 15:56:14.408  1035  1978 W libprocessgroup: failed to open /acct/uid_10011/pid_5993/cgroup.procs: No such file or directory
,08-31 15:56:14.431  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:56:14.437  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:14.457  6851  6851 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:56:14.460  6851  6851 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-31 15:56:14.462  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:14.464  6851  6851 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 15:56:14.471  6819  6819 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 15:56:14.471  6819  6819 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:56:14.471  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:56:14.477  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:14.486  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:56:14.501  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:14.502  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 15:56:14.506  6851  6851 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:56:14.512  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:14.519  6819  6819 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 15:56:14.520  6819  6819 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:56:14.520  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:56:14.525  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:14.533  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:14.543  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:56:14.544  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:14.547  6851  6851 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:56:14.592  3850  3930 D bt_hci_bdroid: cleanup
,08-31 15:56:14.593  3850  4012 I bt_lpm  : LPM is already off!!!
08-31 15:56:14.594  3850  4114 I bt_userial_mct: exiting userial_read_thread
08-31 15:56:14.594  3850  4114 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 15:56:14.594  3850  4010 W bt-btif : ag scb idx 1 not allocated
08-31 15:56:14.594  3850  4010 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 15:56:14.594  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:14.594  3850  4010 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:56:14.594  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:14.595  3850  4010 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:56:14.595  3850  4010 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 15:56:14.596  3850  3930 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 15:56:14.596  3850  4012 I bt_vendor: hw_epilog_process
08-31 15:56:14.597  3850  3930 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 15:56:14.598  3850  3930 D bt_userial_mct: userial_close
08-31 15:56:14.598  3850  3930 E bt_userial_mct: pthread_join() FAILED result:3
08-31 15:56:14.598  3850  3930 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 15:56:14.610  1035  1716 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6889 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-31 15:56:14.664  3850  3930 D bt_hci_bdroid: set_power 0
08-31 15:56:14.664  3850  3930 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-31 15:56:14.665  3850  3930 I bt_vendor: bluetooth satus is on
08-31 15:56:14.665  3850  3930 I bt_vendor: bt-vendor : resetting BT status
08-31 15:56:14.665  3850  3930 I bt_vendor: Starting hciattach daemon
08-31 15:56:14.665  3850  3930 I bt_vendor: try to set false
08-31 15:56:14.667  3850  3930 I bt_vendor: Starting hciattach daemon
08-31 15:56:14.667  3850  3930 I bt_vendor: try to set false
08-31 15:56:14.669  3850  3930 I bt_vendor: cleanup
08-31 15:56:14.670  3850  4010 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 15:56:14.670  3850  3930 I GKI_LINUX: GKI_exit_task 0 done
08-31 15:56:14.670  3850  3930 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 15:56:14.673  3850  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 15:56:14.677  3850  3850 D HeadsetService: Received stop request...Stopping profile...
,08-31 15:56:14.679  3850  3850 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 15:56:14.679  3850  3850 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:56:14.679  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29a1d996
08-31 15:56:14.680  3850  3963 D HeadsetStateMachine: Exit Disconnected: -1
08-31 15:56:14.683  3850  3850 D A2dpService: Received stop request...Stopping profile...
08-31 15:56:14.683  3850  3993 D A2dpStateMachine: Exit Disconnected: -1
08-31 15:56:14.684  3850  3850 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 15:56:14.685  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-31 15:56:14.685  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-31 15:56:14.685  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-31 15:56:14.685  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-31 15:56:14.685  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 15:56:14.687  3850  3927 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 15:56:14.688  3850  3850 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 15:56:14.688  3850  3850 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:56:14.688  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29a1d996
08-31 15:56:14.689  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-31 15:56:14.689  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 15:56:14.691  3850  3850 D HidService: Received stop request...Stopping profile...
08-31 15:56:14.691  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29a1d996
08-31 15:56:14.693  3850  3850 D HealthService: Received stop request...Stopping profile...
08-31 15:56:14.693  6777  6777 D BluetoothInputDevice: Proxy object disconnected
08-31 15:56:14.693  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29a1d996
08-31 15:56:14.694  6777  6777 D HidProfile: Bluetooth service disconnected
08-31 15:56:14.695  3850  3850 D PanService: Received stop request...Stopping profile...
,08-31 15:56:14.695  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29a1d996
08-31 15:56:14.696  6777  6777 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 15:56:14.696  6777  6777 D PanProfile: Bluetooth service disconnected
08-31 15:56:14.697  3850  3850 D HeadsetStateMachine: Unbinding service...
08-31 15:56:14.698  3850  3850 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:56:14.699  3850  3850 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:56:14.699  3850  3850 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:56:14.699  3850  3850 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:56:14.699  3850  3850 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 15:56:14.699  3850  3850 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:56:14.699  3850  3850 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 15:56:14.699  3850  3850 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:56:14.700  3850  3850 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 15:56:14.700  3850  3850 D BtGatt.GattService: stop()
08-31 15:56:14.700  3850  3850 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 15:56:14.701  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29a1d996
08-31 15:56:14.703  3850  3850 D BluetoothMapService: Received stop request...Stopping profile...
08-31 15:56:14.703  3850  3850 D BluetoothMapService: stop()
08-31 15:56:14.704  3850  3850 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 15:56:14.704  3850  3850 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 15:56:14.705  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29a1d996
,08-31 15:56:14.706  3850  3850 I BluetoothA2dpServiceJni: cleanupNative
08-31 15:56:14.706  3850  3994 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 15:56:14.707  3850  3850 I GKI_LINUX: GKI_exit_task 2 done
08-31 15:56:14.707  3850  3850 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 15:56:14.707  3850  3850 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:56:14.707  3850  3850 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 15:56:14.707  3850  3850 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 15:56:14.707  3850  3850 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:56:14.707  6777  6777 D BluetoothMap: Proxy object disconnected
08-31 15:56:14.707  3850  3850 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:56:14.707  6777  6777 D MapProfile: Bluetooth service disconnected
08-31 15:56:14.708  3850  3850 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 15:56:14.708  3850  3850 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 15:56:14.709  3850  3850 V BluetoothMapService: Handler(): got msg=4
08-31 15:56:14.709  3850  3850 D BluetoothMapService: MAP Service closeService in
08-31 15:56:14.709  3850  3850 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:56:14.709  3850  3850 V BluetoothMapService: MAP Service closeService out
08-31 15:56:14.709  3850  3850 D BluetoothMapService: cleanup()
08-31 15:56:14.709  3850  3850 D BluetoothMapService: MAP Service closeService in
08-31 15:56:14.709  3850  3850 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:56:14.709  3850  3850 V BluetoothMapService: MAP Service closeService out
08-31 15:56:14.709  3850  3927 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 15:56:14.709  3850  3927 D BluetoothAdapterProperties: Setting state to 10
08-31 15:56:14.709  3850  3927 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 15:56:14.710  1035  1117 D BluetoothManagerService: Message: 60
08-31 15:56:14.710  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 15:56:14.710  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-31 15:56:14.710  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:56:14.710  3850  3927 I BluetoothAdapterState: Entering OffState
08-31 15:56:14.712  6777  6794 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:56:14.713  6777  6808 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 15:56:14.713  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:56:14.714  6777  6794 D BluetoothMap: onBluetoothStateChange: up=false
08-31 15:56:14.715  1836  3964 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:56:14.715  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:56:14.716  6777  6808 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:56:14.716  1836  2425 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:56:14.718  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 15:56:14.718  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 15:56:14.720  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 15:56:14.720  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 15:56:14.720  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@75ad9f1 mBinding = false
08-31 15:56:14.721  1035  1117 D BluetoothManagerService: Sending unbind request.
08-31 15:56:14.724  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 15:56:14.727  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:14.728  1925  2126 D LGBluetoothAPIService: Message: 2
08-31 15:56:14.728  1925  2126 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@11cbe0c1 mBinding = false
08-31 15:56:14.728  1925  2126 D LGBluetoothAPIService: Sending unbind request.
08-31 15:56:14.729  3850  3930 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 15:56:14.730  3850  3850 I GKI_LINUX: GKI_exit_task 1 done
08-31 15:56:14.730  3850  3850 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 15:56:14.730  3850  3850 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 15:56:14.730  3850  3850 I art     : --- WEIRD: removing null entry 246
,08-31 15:56:14.732  3850  3850 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-31 15:56:14.732  3850  3850 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 15:56:14.732  3850  3850 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 15:56:14.733  6777  6777 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 15:56:14.734  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:56:14.735  6777  6777 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 15:56:14.735  6777  6777 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 15:56:14.736  3850  3850 I art     : System.exit called, status: 0
08-31 15:56:14.736  3850  3850 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 15:56:14.738  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:14.739  1586  1586 D BluetoothAdapter: 422573929: getState() :  mService = null. Returning STATE_OFF
08-31 15:56:14.739  1586  1586 D BluetoothAdapter: 422573929: getState() :  mService = null. Returning STATE_OFF
08-31 15:56:14.741  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:14.743  6777  6777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 15:56:14.751  6777  6777 D DockEventReceiver: finishStartingService: stopping service
08-31 15:56:14.760  6777  6777 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-31 15:56:14.761   313  1370 V AudioFlinger: 3850 died, releasing its sessions
08-31 15:56:14.761   313  1370 V AudioFlinger:  pid 1836 @ 0
,08-31 15:56:14.761   313  1370 V AudioFlinger:  pid 3439 @ 1
08-31 15:56:14.761   313  1370 V AudioFlinger:  pid 3439 @ 2
08-31 15:56:14.845  1035  1639 I ActivityManager: Process com.android.bluetooth (pid 3850) has died
08-31 15:56:14.845  1035  1639 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-31 15:56:14.862  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:56:14.874  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:56:14.883  6889  6914 W FormManager: Network not available. Please check & try again.
,08-31 15:56:14.891  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:56:14.918  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:14.919  6889  6915 V FormManager: Network unavailable.
08-31 15:56:14.928  6777  6777 D BluetoothPermissionRequest: onReceive
,08-31 15:56:14.932  6777  6777 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-31 15:56:14.933  6777  6777 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 15:56:14.933  6889  6915 V FormManager: Network unavailable.
08-31 15:56:14.936  6777  6777 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:56:15.001  1035  1995 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6918 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 15:56:15.013  1035  1870 I ActivityManager: Killing 6016:com.android.contacts/u0a19 (adj 15): empty #17
08-31 15:56:15.078  1035  1051 W libprocessgroup: failed to open /acct/uid_10019/pid_6016/cgroup.procs: No such file or directory
,08-31 15:56:15.107  6918  6918 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 15:56:15.108  6918  6918 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 15:56:15.108  6918  6918 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 15:56:15.109  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 15:56:15.109  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:56:15.109  6918  6918 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 15:56:15.110  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:56:15.110  6777  6777 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 15:56:15.111  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 15:56:15.121  6777  6777 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:56:15.121  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 15:56:15.121  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:56:15.121  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:56:15.122  6777  6777 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 15:56:15.122  6777  6777 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-31 15:56:15.125  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:56:15.126  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:56:15.128  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:15.130  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:15.136  6918  6918 D BluetoothAdapterApp: Loading JNI Library
08-31 15:56:15.138  4292  6937 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 15:56:15.140  6819  6819 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-31 15:56:15.140  6819  6819 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:56:15.140  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:15.144  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:56:15.151  6889  6940 W FormManager: Network not available. Please check & try again.
08-31 15:56:15.153  4292  6939 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:56:15.153  6889  6941 V FormManager: Network unavailable.
08-31 15:56:15.154  4292  6939 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:56:15.157  6889  6941 V FormManager: Network unavailable.
,08-31 15:56:15.160  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:15.177  6918  6918 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2ff0151f Instance Count = 1
,08-31 15:56:15.180  6851  6851 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 15:56:15.181  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 15:56:15.181  6851  6851 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-31 15:56:15.181  6918  6918 D BluetoothAdapterApp: onCreate
08-31 15:56:15.206  6918  6918 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 15:56:15.206  6918  6918 D ProfileConfigQcom: Adding HeadsetService
08-31 15:56:15.206  6918  6918 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 15:56:15.206  6918  6918 D ProfileConfigQcom: Adding A2dpService
08-31 15:56:15.207  6918  6918 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 15:56:15.207  6918  6918 D ProfileConfigQcom: Adding HidService
08-31 15:56:15.207  6918  6918 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 15:56:15.207  6918  6918 D ProfileConfigQcom: Adding HealthService
08-31 15:56:15.208  6918  6918 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-31 15:56:15.209  6918  6918 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 15:56:15.209  6918  6918 D ProfileConfigQcom: Adding PanService
08-31 15:56:15.209  6918  6918 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 15:56:15.209  6918  6918 D ProfileConfigQcom: Adding GattService
08-31 15:56:15.210  6918  6918 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 15:56:15.210  6918  6918 D ProfileConfigQcom: Adding BluetoothMapService
08-31 15:56:15.210  6918  6918 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 15:56:15.212  6918  6918 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 15:56:15.218  6777  6777 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 15:56:15.220  6918  6918 V LGMDMManagerInternal: Create singleton instance
08-31 15:56:15.220  6851  6851 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:15.220  6851  6851 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:15.230  6851  6851 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 15:56:15.231  6851  6851 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 15:56:15.231  6851  6851 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 15:56:15.231  6851  6851 V SoundPool: doLoad: loading sample sampleID=1
08-31 15:56:15.231  6851  6851 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 15:56:15.235  6851  6945 V SoundPool: Start decode
08-31 15:56:15.235  6851  6945 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 15:56:15.237   313  1370 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 15:56:15.237   313  1370 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 15:56:15.237   313  1370 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 15:56:15.237   313  1370 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 15:56:15.237   313  1370 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 15:56:15.237   313  1370 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 15:56:15.237   313  1370 V MediaPlayerService: player type = 3
08-31 15:56:15.238   313  1370 V AwesomePlayer: AwesomePlayer create()
,08-31 15:56:15.240   313  1370 V AwesomePlayer: reset_l() 
08-31 15:56:15.240   313  1370 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:15.240   313  1370 V AwesomePlayer: setAudioSink() 
08-31 15:56:15.240   313  1370 V AwesomePlayer: reset_l() 
08-31 15:56:15.240   313  1370 V AudioCache: notify(0xb5474880, 8, 0, 0)
08-31 15:56:15.240   313  1370 V AudioCache: ignored
08-31 15:56:15.240   313  1370 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:15.240   313  1370 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 15:56:15.240   313  1370 V AwesomePlayer: setDataSource_l dataSource
08-31 15:56:15.241   313  1370 V LGParserOSAL: SniffLGParser start
08-31 15:56:15.241   313  1370 V LGParserOSAL: MainType:5, SubType=0
08-31 15:56:15.241   313  1370 V LGParserOSAL: #### check Mime : application/ogg
08-31 15:56:15.241   313  1370 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 15:56:15.241   313  1370 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 15:56:15.244  6851  6851 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 15:56:15.246  6588  6588 D UEI.SmartControl: QS Service created
08-31 15:56:15.248  6851  6851 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 15:56:15.249  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 15:56:15.258  6588  6588 I UEI.SmartControl: Service initServices...
08-31 15:56:15.258  6588  6588 D UEI.SmartControl: QS start get config
,08-31 15:56:15.273  6851  6851 V LGMDMManager: Create singleton instance
,08-31 15:56:15.300  6918  6918 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:15.301   313  1370 V LGParserOSAL: supported mime: application/ogg
08-31 15:56:15.301   313  1370 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 15:56:15.301   313  1370 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 15:56:15.301   313  1370 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 15:56:15.301   313  1370 V AwesomePlayer: AudioTrack Setting
08-31 15:56:15.301   313  1370 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 15:56:15.301   313  1370 V AwesomePlayer: setAudioSource() 
08-31 15:56:15.301   313  1370 V MediaPlayerService: prepare
08-31 15:56:15.301   313  1370 V AwesomePlayer: prepareAsync_l() 
08-31 15:56:15.301   313  1370 V MediaPlayerService: wait for prepare
08-31 15:56:15.301   313  6946 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 15:56:15.301   313  6946 V AwesomePlayer: initAudioDecoder() 
08-31 15:56:15.301   313  6946 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 15:56:15.301   313  6946 V AudioSystem: isOffloadSupported()
08-31 15:56:15.301   313  6946 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 15:56:15.301   313  6946 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 15:56:15.301   313  6946 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 15:56:15.301   313  6946 V AwesomePlayer: getUseOffload() = 0 
08-31 15:56:15.301   313  6946 V OMXCodec: OMXCodec::Create
08-31 15:56:15.301   313  6946 V OMXCodec: findMatchingCodecs()
08-31 15:56:15.301   313  6946 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 15:56:15.301   313  6946 V OMXCodec: matchingCodecs.size()=1
08-31 15:56:15.301   313  6946 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 15:56:15.303  6918  6918 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:56:15.303   313  6946 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 15:56:15.303   313  6946 V LGCodecAdapter: LG Codec Adapter start
08-31 15:56:15.303   313  6946 V OMXCodec: OMXCodec Createtor
08-31 15:56:15.303   313  6946 V OMXCodec: setComponentRole
08-31 15:56:15.303   313  6946 V OMXCodec: configureCodec protected=0
08-31 15:56:15.303   313  6946 V LGCodecAdapter: called getLGCodecSpecificData
08-31 15:56:15.303   313  6946 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 15:56:15.303   313  6946 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 15:56:15.303  6918  6918 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:56:15.303   313  6946 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 15:56:15.303   313  6946 V LGCodecOSAL: Not support LGCodec
08-31 15:56:15.303   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 15:56:15.303   313  6946 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 15:56:15.303   313  6946 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 15:56:15.303  6918  6918 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:56:15.303   313  6946 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 15:56:15.303   313  6946 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 15:56:15.303   313  6946 V AudioSystem: isOffloadSupported()
08-31 15:56:15.304   313  6946 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1,, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 15:56:15.304   313  6946 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 15:56:15.304   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 15:56:15.304   313  6946 V OMXCodec: init()
08-31 15:56:15.304   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 15:56:15.304   313  6946 V OMXCodec: allocateBuffers
08-31 15:56:15.304   313  6946 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 15:56:15.304   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 15:56:15.304   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-31 15:56:15.304   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-31 15:56:15.304   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-31 15:56:15.304   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-31 15:56:15.304   313  6946 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 15:56:15.304   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 15:56:15.304   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-31 15:56:15.304  6918  6918 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:15.305  6918  6918 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 15:56:15.305   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-31 15:56:15.306   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-31 15:56:15.306   313  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fce0 on output port
08-31 15:56:15.306   313  6946 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 15:56:15.308   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 15:56:15.308   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 15:56:15.309   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 15:56:15.309   313  6946 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 15:56:15.309   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 15:56:15.309   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 15:56:15.309   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,08-31 15:56:15.309   313  6946 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 15:56:15.309   313  6946 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 15:56:15.309   313  6946 V AudioCache: notify(0xb5474880, 5, 0, 0)
08-31 15:56:15.309   313  6946 V AudioCache: ignored
08-31 15:56:15.309   313  6946 V AudioCache: notify(0xb5474880, 1, 0, 0)
08-31 15:56:15.309   313  6946 V AudioCache: prepared
08-31 15:56:15.309   313  1370 V AudioCache: wait - success
,08-31 15:56:15.309   313  1370 V MediaPlayerService: start
08-31 15:56:15.309   313  1370 V AwesomePlayer: play_l() 
08-31 15:56:15.309   313  1370 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 15:56:15.309   313  1370 V AwesomePlayer: createAudioPlayer_l
08-31 15:56:15.309   313  1370 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 15:56:15.309   313  1370 V AwesomePlayer: startAudioPlayer_l() 
08-31 15:56:15.309   313  1370 D AudioPlayer: start of Playback, useOffload 0
08-31 15:56:15.310   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 15:56:15.310   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-31 15:56:15.313   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:15.314   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049056
08-31 15:56:15.314   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:15.314   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 15:56:15.314   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 15:56:15.314   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 15:56:15.314   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 15:56:15.314   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 15:56:15.314   313  6948 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 15:56:15.314   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 15:56:15.315   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-31 15:56:15.315   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-31 15:56:15.315   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-31 15:56:15.315   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on output port
08-31 15:56:15.315   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 15:56:15.315   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 15:56:15.316  6868  6868 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-31 15:56:15.317   313  1370 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 15:56:15.318   313  1370 V AudioCache: notify(0xb5474880, 6, 0, 0)
08-31 15:56:15.318   313  1370 V AudioCache: ignored
08-31 15:56:15.318   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.318   313  6950 V AudioCache: memcpy(0xaf006000, 0x,b57c0000, 4096)
08-31 15:56:15.318   313  1370 V MediaPlayerService: wait for playback complete
08-31 15:56:15.319   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.319   313  6950 V AudioCache: memcpy(0xaf007000, 0xb57c0000, 4096)
08-31 15:56:15.319   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.319   313  6950 V AudioCache: memcpy(0xaf008000, 0xb57c0000, 4096)
08-31 15:56:15.321   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.321   313  6950 V AudioCache: memcpy(0xaf009000, 0xb57c0000, 4096)
08-31 15:56:15.321   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.321   313  6950 V AudioCache: memcpy(0xaf00a000, 0xb57c0000, 4096)
08-31 15:56:15.321   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.321   313  6950 V AudioCache: memcpy(0xaf00b000, 0xb57c0000, 4096)
08-31 15:56:15.321   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.321   313  6950 V AudioCache: memcpy(0xaf00c000, 0xb57c0000, 4096)
08-31 15:56:15.322   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.322   313  6950 V AudioCache: memcpy(0xaf00d000, 0xb57c0000, 4096)
08-31 15:56:15.323   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.323   313  6950 V AudioCache: memcpy(0xaf00e000, 0xb57c0000, 4096)
08-31 15:56:15.323   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.323   313  6950 V AudioCache: memcpy(0xaf00f000, 0xb57c0000, 4096)
08-31 15:56:15.323   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.323   313  6950 V AudioCache: memcpy(0xaf010000, 0xb57c0000, 4096)
08-31 15:56:15.323   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.323   313  6950 V AudioCache: memcpy(0xaf011000, 0xb57c0000, 4096)
08-31 15:56:15.324   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.324   313  6950 V AudioCache: memcpy(0xaf012000, 0xb57c0000, 4096)
,08-31 15:56:15.325   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.325   313  6950 V AudioCache: memcpy(0xaf013000, 0xb57c0000, 4096)
08-31 15:56:15.325   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.325   313  6950 V AudioCache: memcpy(0xaf014000, 0xb57c0000, 4096)
08-31 15:56:15.325   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.325   313  6950 V AudioCache: memcpy(0xaf015000, 0xb57c0000, 4096)
08-31 15:56:15.325   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.325   313  6950 V AudioCache: memcpy(0xaf016000, 0xb57c0000, 4096)
08-31 15:56:15.326   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.326   313  6950 V AudioCache: memcpy(0xaf017000, 0xb57c0000, 4096)
08-31 15:56:15.326   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.326   313  6950 V AudioCache: memcpy(0xaf018000, 0xb57c0000, 4096)
08-31 15:56:15.326   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.326   313  6950 V AudioCache: memcpy(0xaf019000, 0xb57c0000, 4096)
08-31 15:56:15.327   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.327   313  6950 V AudioCache: memcpy(0xaf01a000, 0xb57c0000, 4096)
08-31 15:56:15.327   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.327   313  6950 V AudioCache: memcpy(0xaf01b000, 0xb57c0000, 4096)
08-31 15:56:15.328   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.328   313  6950 V AudioCache: memcpy(0xaf01c000, 0xb57c0000, 4096)
08-31 15:56:15.328   313  6950 V AudioCache: write(0xb57c0000, 4096)
,08-31 15:56:15.328   313  6950 V AudioCache: memcpy(0xaf01d000, 0xb57c0000, 4096)
08-31 15:56:15.329   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.329   313  6950 V AudioCache: memcpy(0xaf01e000, 0xb57c0000, 4096)
08-31 15:56:15.329   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.329   313  6950 V AudioCache: memcpy(0xaf01f000, 0xb57c0000, 4096)
08-31 15:56:15.330   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.330   313  6950 V AudioCache: memcpy(0xaf020000, 0xb57c0000, 4096)
08-31 15:56:15.330   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.330   313  6950 V AudioCache: memcpy(0xaf021000, 0xb57c0000, 4096)
08-31 15:56:15.331   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.331   313  6950 V AudioCache: memcpy(0xaf022000, 0xb57c0000, 4096)
08-31 15:56:15.331   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.331   313  6950 V AudioCache: memcpy(0xaf023000, 0xb57c0000, 4096)
08-31 15:56:15.332   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.332   313  6950 V AudioCache: memcpy(0xaf024000, 0xb57c0000, 4096)
08-31 15:56:15.332   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.332   313  6950 V AudioCache: memcpy(0xaf025000, 0xb57c0000, 4096)
08-31 15:56:15.333   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.333   313  6950 V AudioCache: memcpy(0xaf026000, 0xb57c0000, 4096)
08-31 15:56:15.333   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.333   313  6950 V AudioCache: memcpy(0xaf027000, 0xb57c0000, 4096)
08-31 15:56:15.334   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.334   313  6950 V AudioCache: memcpy(0xaf028000, 0xb57c0000, 4096)
08-31 15:56:15.335   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.335   313  6950 V AudioCache: memcpy(0xaf029000, 0xb57c0000, 4096)
08-31 15:56:15.335   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.335   313  6950 V AudioCache: memcpy(0xaf02a000, 0xb57c0000, 4096)
08-31 15:56:15.336   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.336   313  6950 V AudioCache: memcpy(0xaf02b000, 0xb57c0000, 4096)
08-31 15:56:15.336   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.336   313  6950 V AudioCache: memcpy(0xaf02c000, 0xb57c0000, 4096)
,08-31 15:56:15.337   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.337   313  6950 V AudioCache: memcpy(0xaf02d000, 0xb57c0000, 4096)
08-31 15:56:15.337   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.337   313  6950 V AudioCache: memcpy(0xaf02e000, 0xb57c0000, 4096)
08-31 15:56:15.338   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.338   313  6950 V AudioCache: memcpy(0xaf02f000, 0xb57c0000, 4096)
08-31 15:56:15.338   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.338   313  6950 V AudioCache: memcpy(0xaf030000, 0xb57c0000, 4096)
08-31 15:56:15.339   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.339   313  6950 V AudioCache: memcpy(0xaf031000, 0xb57c0000, 4096)
08-31 15:56:15.340   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.340   313  6950 V AudioCache: memcpy(0xaf032000, 0xb57c0000, 4096)
08-31 15:56:15.340   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.340   313  6950 V AudioCache: memcpy(0xaf033000, 0xb57c0000, 4096)
08-31 15:56:15.341   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.341   313  6950 V AudioCache: memcpy(0xaf034000, 0xb57c0000, 4096)
08-31 15:56:15.341   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.341   313  6950 V AudioCache: memcpy(0xaf035000, 0xb57c0000, 4096)
08-31 15:56:15.342   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.342   313  6950 V AudioCache: memcpy(0xaf036000, 0xb57c0000, 4096)
08-31 15:56:15.342  1035  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=844029868, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-31 15:56:15.342  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3e288a1a type 2 when 210545 com.google.android.gms} when 210545
08-31 15:56:15.342   313  6950 V AudioCache: write(0xb57c0000, 4096)
08-31 15:56:15.342   313  6950 V AudioCache: memcpy(0xaf037000, 0xb57c0000, 4096)
08-31 15:56:15.342   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 15:56:15.343   313  6950 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 15:56:15.343   313  6950 V AwesomePlayer: postAudioEOS() 
08-31 15:56:15.343   313  6950 V AudioCache: write(0xb57c0000, 280)
08-31 15:56:15.343   313  6950 V AudioCache: memcpy(0xaf038000, 0xb57c0000, 280)
08-31 15:56:15.344   313  6946 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 15:56:15.344   313  6946 V AwesomePlayer: onStreamDone
08-31 15:56:15.344   313  6946 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 15:56:15.344   313  6946 V AudioCache: notify(0xb5474880, 2, 0, 0)
08-31 15:56:15.344   313  6946 V AudioCache: playback complete
08-31 15:56:15.344   313  6946 V AwesomePlayer: pause_l() 
08-31 15:56:15.344   313  6946 V AudioCache: notify(0xb5474880, 7, 0, 0)
08-31 15:56:15.344   313  6946 V AudioCache: ignored
08-31 15:56:15.344   313  6946 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:15.345   313  1370 V AudioCache: wait - success
08-31 15:56:15.345   313  1370 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 15:56:15.345   313  6946 D AudioPlayer: Pause Playback at 1068125
08-31 15:56:15.345   313  1370 V AwesomePlayer: reset_l() 
08-31 15:56:15.345   313  1370 V AudioCache: notify(0xb5474880, 8, 0, 0)
08-31 15:56:15.345   313  1370 V AudioCache: ignored
08-31 15:56:15.345   313  1370 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:15.345   313  1370 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 15:56:15.345   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 15:56:15.345   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 15:56:15.345   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 15:56:15.345   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wa,it lock!!
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 1
08-31 15:56:15.345   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 15:56:15.346   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 15:56:15.346   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 15:56:15.346   313  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 15:56:15.346   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 15:56:15.346   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 15:56:15.346   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 15:56:15.347   313  1370 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-31 15:56:15.347   313  1370 D AudioPlayer: AudioPlayer releasing audio source
08-31 15:56:15.347   313  1370 D AudioPlayer: AudioPlayer done releasing audio source
08-31 15:56:15.347   313  1370 V AwesomePlayer: reset_l() 
08-31 15:56:15.347   313  1370 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:15.347   313  1370 V AwesomePlayer: ~AwesomePlayer call
,08-31 15:56:15.347   313  1370 V AwesomePlayer: reset_l() 
08-31 15:56:15.347   313  1370 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:15.347  6851  6945 V SoundPool: close(31)
08-31 15:56:15.347  6851  6945 V SoundPool: pointer = 0x9ffdf000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 15:56:15.360  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-31 15:56:15.363  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-31 15:56:15.366  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4418
08-31 15:56:15.371   309  6952 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 15:56:15.371  2560  2560 D [Concierge]Service: onStartCommand(). Type : 9
08-31 15:56:15.371  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-31 15:56:15.408  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=844029868 [*alarm*], flags=0x0
,08-31 15:56:15.539  6588  6588 I UEI.SmartControl: Supports setup maps: true
,08-31 15:56:15.542  6588  6588 D UEI.SmartControl: QS start statue = true Error code = 0
,08-31 15:56:15.542  6588  6588 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 15:56:15.542  6588  6588 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 15:56:15.542  6588  6588 I UEI.SmartControl: ### init IR Blaster...
08-31 15:56:15.545  6588  6588 D serial_port: Configuring serial port
08-31 15:56:15.546  6588  6588 E UEI.SmartControl: UEIBLaster setting for 616
08-31 15:56:15.546  6588  6588 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 15:56:15.546  6588  6588 I UEI.SmartControl: configuring settings for MAXQ616
08-31 15:56:15.546  6588  6588 I UEI.SmartControl: Get version...
08-31 15:56:15.565  6588  6953 D UEI.SmartControl: serial port data available: 21
,08-31 15:56:15.591  6588  6588 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 15:56:15.591  6588  6588 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 15:56:15.592  6588  6588 I UEI.SmartControl: QS saving settings...
08-31 15:56:15.595  6588  6588 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 15:56:15.611  6588  6953 D UEI.SmartControl: serial port data available: 4
,08-31 15:56:15.640  6588  6959 I UEI.SmartControl: Device manager: loading config....
,08-31 15:56:15.641  6588  6959 D UEI.SmartControl: ----------- loading internal config...
08-31 15:56:15.641  6588  6588 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 15:56:15.645  6588  6588 E UEI.SmartControl: Services init done
08-31 15:56:15.645  6588  6588 D UEI.SmartControl: QS Service init finished
08-31 15:56:15.646  6588  6588 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 15:56:15.646  6588  6588 D UEI.SmartControl: QS Service version code: 201091
08-31 15:56:15.648  6588  6588 D UEI.SmartControl: Service requested: Control
08-31 15:56:15.651  6588  6959 E UEI.SmartControl: Loading SETTINGS...
,08-31 15:56:15.653  6588  6588 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 15:56:15.658  6588  6588 D UEI.SmartControl: Internal service binding...
08-31 15:56:15.659  6851  6851 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 15:56:15.661  6588  6604 I UEI.SmartControl: ------ IControl API: 11
08-31 15:56:15.662  6588  6604 D UEI.SmartControl: File observer start...
08-31 15:56:15.663  6588  6604 E UEI.SmartControl: IR Port is disabled: false
08-31 15:56:15.663  6588  6604 D UEI.SmartControl: Starting file observer...
08-31 15:56:15.664  6588  6959 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 15:56:15.666  6588  6604 I UEI.SmartControl: Registering callback...
08-31 15:56:15.668  6588  6603 I UEI.SmartControl: ------ IControl API: 19
08-31 15:56:15.670  6588  6603 I UEI.SmartControl: Registering Services Ready callback...
,08-31 15:56:15.679  6588  6958 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 15:56:15.680  6851  6866 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 15:56:15.680  6588  6958 D UEI.SmartControl: -----service ready thread exits
08-31 15:56:15.681  6851  6943 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 15:56:15.682  6851  6943 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 15:56:15.683  6851  6851 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 15:56:15.684  6851  6851 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 15:56:15.685  6588  6604 I UEI.SmartControl: ------ IControl API: 8
08-31 15:56:15.688  6851  6851 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 15:56:15.689  6851  6851 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 15:56:15.690  6851  6851 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 15:56:15.691  6851  6851 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-31 15:56:15.693  6851  6851 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 15:56:15.694  6851  6851 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-31 15:56:15.697  6851  6851 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 15:56:15.704  6851  6851 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-31 15:56:15.706  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 15:56:15.708  6851  6851 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 15:56:15.708  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 15:56:15.711  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 15:56:15.713  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 15:56:15.715  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 15:56:15.718  6851  6851 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472651775716]
,08-31 15:56:15.724  6851  6851 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 15:56:15.726  1035  1924 I ActivityManager: Killing 6041:com.android.gallery3d/u0a27 (adj 15): empty #17
08-31 15:56:15.762  6851  6961 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 15:56:15.765  1035  1924 I ActivityManager: Killing 6485:com.lge.email/u0a23 (adj 15): empty #18
,08-31 15:56:15.822  1035  2035 W libprocessgroup: failed to open /acct/uid_10027/pid_6041/cgroup.procs: No such file or directory
,08-31 15:56:15.837  1035  2013 W libprocessgroup: failed to open /acct/uid_10023/pid_6485/cgroup.procs: No such file or directory
,08-31 15:56:15.840  6851  6851 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-31 15:56:15.845  6851  6851 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 15:56:15.846  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 15:56:15.847  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 15:56:15.848  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 15:56:15.848  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-31 15:56:15.849  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 15:56:15.862  6851  6851 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 15:56:16.579  1035  1639 D WifiServiceImplEx: setWifiEnabled: true pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:56:16.581  1035  1639 D WifiService: setWifiEnabled: true pid=6692, uid=10118
08-31 15:56:16.581  1035  1639 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:56:16.612  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:56:16.612  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:56:16.612  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-31 15:56:16.616  1035  1521 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 15:56:16.616  1035  1521 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 15:56:16.619  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 15:56:16.619  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 15:56:16.619  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 15:56:16.619  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 15:56:16.619  1035  1521 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 15:56:16.619  1035  1521 E WifiHW  : unknown target_country: EU , set to default
08-31 15:56:16.619  1035  1521 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 15:56:16.619  1035  1521 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 15:56:16.619  1035  1521 I WifiUtil: gEnableBmps=1
08-31 15:56:16.646  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:56:16.653  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-31 15:56:16.661  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:56:16.665  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:16.666  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:16.673  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-31 15:56:16.683  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:16.685  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:56:16.687  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:16.689  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 15:56:16.692  6393  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 15:56:16.704  5756  5756 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 15:56:16.713  5756  5756 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 15:56:16.736  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:56:16.771  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:56:16.822  1035  2013 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6983 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-31 15:56:16.830  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:16.831  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 15:56:16.894  6983  6983 I AppUp4:AppBoxCP: onCreate
,08-31 15:56:16.895  6983  6983 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-31 15:56:16.918  6983  6983 I AppUp4:DB:  setFingerPrint start
08-31 15:56:16.919  6983  6983 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-31 15:56:16.944  6983  6983 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 15:56:16.944  6983  6983 I AppUp4:DB:  SDK version = 21
,08-31 15:56:16.944  6983  6983 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-31 15:56:16.947  6983  6983 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-31 15:56:16.950  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 15:56:16.950  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:16.953  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 15:56:16.954  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 15:56:16.963  6983  6983 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 15:56:17.029  6983  6983 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:17.029  6983  6983 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:17.042  6983  6983 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d7530b1
08-31 15:56:17.042  6983  6983 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 15:56:17.042  6983  6983 D AppUp4:CustFacade: isPhone : true
08-31 15:56:17.043  6983  6983 D AppUp4:CustModeStarterReceiver: begin check event
08-31 15:56:17.045  6983  6983 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-31 15:56:17.045  6983  6983 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-31 15:56:17.047  6983  7002 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-31 15:56:17.048  6983  7002 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 15:56:17.048  6983  7002 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-31 15:56:17.054  1035  1978 I ActivityManager: Killing 6517:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-31 15:56:17.179  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:17.179  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 15:56:17.181  1035  1942 W libprocessgroup: failed to open /acct/uid_10061/pid_6517/cgroup.procs: No such file or directory
08-31 15:56:17.185  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:17.193  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 15:56:17.211  4292  7016 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:56:17.218  4292  7018 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:17.218  4292  7018 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:56:17.243  1035  1906 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7019 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 15:56:17.317  7019  7019 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:56:17.318  7019  7019 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:56:17.319  7019  7019 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 15:56:17.320  7019  7019 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 15:56:17.370   309   893 D SoftapController: Softap fwReload - Ok
,08-31 15:56:17.373  1035  1521 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (748ms)
08-31 15:56:17.381  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 15:56:17.381   309   893 D CommandListener: Setting iface cfg
08-31 15:56:17.381   309   893 D CommandListener: Trying to bring down wlan0
,08-31 15:56:17.382   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:56:17.384  1035  1521 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-31 15:56:17.390  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:56:17.390  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:56:17.390  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:56:17.385  7037  7037 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:17.385  7037  7037 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 15:56:17.397  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 15:56:17.404  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:17.405  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 15:56:17.407  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:17.416  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:56:17.425  1035  1521 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 15:56:17.425  1035  1521 D WifiMonitor: connecting to supplicant
08-31 15:56:17.436  7037  7037 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 15:56:17.476  7037  7037 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 15:56:17.477  7037  7037 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-31 15:56:17.482  1035  1117 D Tethering: InitialState.processMessage what=4
08-31 15:56:17.483  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 15:56:17.511  7019  7019 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-31 15:56:17.523  7019  7019 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-31 15:56:17.559  7019  7019 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 15:56:17.581  7037  7037 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 15:56:17.597  7019  7019 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:56:17.597  7019  7019 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:56:17.617  7037  7037 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 15:56:17.623  7037  7037 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 15:56:17.625  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 15:56:17.625  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 15:56:17.626  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 15:56:17.626  1035  1521 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 15:56:17.627  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:17.627  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:17.628  1035  7052 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 15:56:17.628  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:17.628  1035  7052 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 15:56:17.628  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:17.629  1035  1521 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 15:56:17.629  1035  1521 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 15:56:17.630  7037  7037 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 15:56:17.630  1035  1521 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 15:56:17.630  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 15:56:17.630  1035  1521 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 15:56:17.630  1035  1521 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 15:56:17.630  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 15:56:17.631  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 15:56:17.631  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:56:17.631  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:56:17.631  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:56:17.631  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 15:56:17.631  1035  7052 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 15:56:17.631  1035  7052 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 15:56:17.631  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:17.631  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:17.632  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:17.632  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:17.632  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-31 15:56:17.639  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:17.639  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-31 15:56:17.641  1035  1521 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 15:56:17.642  1035  1521 D WifiNative-wlan0: SET update_config 1: returned true
08-31 15:56:17.642  1035  1521 D WifiConfigStore: Loading config and enabling all networks 
08-31 15:56:17.642  1035  1521 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 15:56:17.643  1035  1521 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 15:56:17.644  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:17.644  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:17.644  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:17.644  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:17.644  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:17.644  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:17.644  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:17.644  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:17.644  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:17.644  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:17.644  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:17.648  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:17.648  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:17.648  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:17.648  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:17.648  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:17.648  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:17.648  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:17.648  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:17.648  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:17.648  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:17.648  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:17.649  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 15:56:17.650  1035  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-31 15:56:17.659  1035  1521 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 15:56:17.671  1035  1521 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 15:56:17.671  1035  1521 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 15:56:17.672  1035  1521 D WifiStateMachine: enableVerboseLogging : level 2
08-31 15:56:17.672  1035  1521 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 15:56:17.672  1035  1521 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 15:56:17.672  1035  1521 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 15:56:17.673  1035  1521 D WifiNative-wlan0: SET manufacturer LGE: returned true
,08-31 15:56:17.673  1035  1521 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 15:56:17.673  1035  1521 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 15:56:17.673  1035  1521 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 15:56:17.674  1035  1521 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 15:56:17.674  1035  1521 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 15:56:17.674  1035  1521 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 15:56:17.674  1035  1521 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 15:56:17.674  1035  1521 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 15:56:17.675  1035  1521 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 15:56:17.675  1035  1521 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 15:56:17.675  1035  1521 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:56:17.675  1035  1521 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 15:56:17.676  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-31 15:56:17.676  1925  2306 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 15:56:17.676  1925  2306 D WfdsService: Set the WFDS Monitor: true
08-31 15:56:17.676  1925  2306 D WfdsMonitor: WfdsMonitorThread create
08-31 15:56:17.676  1035  1521 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 15:56:17.676  1035  1521 D WifiNative-HAL: Setting external_sim to 1
08-31 15:56:17.676  1035  1521 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 15:56:17.676  1925  2306 D WfdsMonitor: WFDS Monitor is created and started
08-31 15:56:17.676  1925  2306 D WfdsService: WiFi: Supplicant connection re-established
08-31 15:56:17.676  1035  1521 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 15:56:17.677  1035  1521 I WifiNative-HAL: startHal
08-31 15:56:17.677  1035  1521 D wifi    : setting scan oui 0xaf6e21e0
08-31 15:56:17.677  1035  1521 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:56:17.677  1035  1521 I WifiNative-HAL: startHal
08-31 15:56:17.677  1035  1521 D wifi    : setting scan oui 0xaf6e21e0
08-31 15:56:17.677  1925  7055 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 15:56:17.677  1035  1521 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 15:56:17.678  1925  7055 E CtrlSupplicant: Succeed to open control connection
08-31 15:56:17.678  1925  7055 E CtrlSupplicant: Succeed to open monitor connection
08-31 15:56:17.678  1035  1521 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 15:56:17.678  1925  7055 D WfdsMonitor: Supplicant connection established
08-31 15:56:17.678  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 15:56:17.678  1925  2306 D WfdsService: Connected to the supplicant for wfds
08-31 15:56:17.678  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 15:56:17.679  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 15:56:17.679  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 15:56:17.679  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 15:56:17.680  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 15:56:17.680  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 15:56:17.680  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 15:56:17.680  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 15:56:17.680  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 15:56:17.680  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 15:56:17.681  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 15:56:17.681  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 15:56:17.681  7,037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 15:56:17.681  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 15:56:17.681  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 15:56:17.682  7037  7037 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 15:56:17.682  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 15:56:17.682  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 15:56:17.682  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 15:56:17.683  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 15:56:17.684  1035  1521 E WifiNative: : [212,886,492 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
,08-31 15:56:17.684  1035  1521 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 15:56:17.684  1035  1521 D WifiNative-wlan0: RECONNECT: returned true
08-31 15:56:17.685  1035  1521 D WifiNative-wlan0: doString: [STATUS]
08-31 15:56:17.685  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 15:56:17.685  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 15:56:17.686  1035  1521 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 15:56:17.686  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:56:17.686  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:56:17.686  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.688   309   893 D CommandListener: Setting iface cfg
08-31 15:56:17.688   309   893 D CommandListener: Trying to bring up p2p0
08-31 15:56:17.688  1035  1520 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 15:56:17.688  1035  1520 D LGWifiP2pService: P2pEnablingState
08-31 15:56:17.689  1035  1520 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:56:17.689  1035  1520 D LGWifiP2pService: P2p socket connection successful
08-31 15:56:17.689  1035  1520 D LGWifiP2pService: P2pEnabledState
08-31 15:56:17.689  1035  1520 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 15:56:17.690  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 15:56:17.690  1925  1925 D WfdsService: WifiP2pState is changed : true
08-31 15:56:17.690  1925  2306 D WfdsService: Receive the WFDS_ENABLE Method
08-31 15:56:17.690  1925  2306 D WfdsService: Set the WFDS Monitor: true
08-31 15:56:17.690  1925  2306 D WfdsService: Connected to the supplicant for wfds
08-31 15:56:17.690  1925  2306 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 15:56:17.690  7037  7037 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 15:56:17.690  1925  2306 D WfdsService: selectPreferredScanChannel [36]
08-31 15:56:17.690  1925  2306 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 15:56:17.691  1035  1520 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 15:56:17.691  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 15:56:17.691  1035  1520 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 15:56:17.692  1035  1520 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 15:56:17.692  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-31 15:56:17.692  1035  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.692  1035  1540 I WifiNative-HAL: startHal
08-31 15:56:17.692  1035  1541 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.692  1035  1520 D WifiNative-p2p0: SET device_name G3: returned true
08-31 15:56:17.692  1035  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf6e21e0
08-31 15:56:17.692  1035  1540 D wifi    : failed to get capabilities : -3
08-31 15:56:17.692  1035  1540 E WifiScanningService: could not get scan capabilities
08-31 15:56:17.692  1035  1520 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 15:56:17.693  1035  1520 D LGWifiP2pService: before postfix = G3
08-31 15:56:17.693  1035  1520 D WifiServerServiceExt: postfix byte check : 2
08-31 15:56:17.693  1035  1520 D LGWifiP2pService: after postfix = G3
08-31 15:56:17.693  1035  1520 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 15:56:17.693  1035  1520 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 15:56:17.693  1035  1520 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 15:56:17.693  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 15:56:17.694  1035  1520 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 15:56:17.694  1035  1520 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 15:56:17.694  1925  1925 D WfdsService: isConnected: false
08-31 15:56:17.694  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 15:56:17.694  1035  1520 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 15:56:17.694  1035  1520 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 15:56:17.695  1035  1521 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 15:56:17.695  1035  1520 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 15:56:17.695  1035  1520 D WifiNative-HAL: p2pGetDeviceAddress
08-31 15:56:17.695  1035  1521 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 15:56:17.695  1035  1520 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 15:56:17.695  1035  1521 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 15:56:17.696  1035  1520 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 15:56:17.696  1035  1520 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 15:56:17,.696  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=212899  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 15:56:17.696  1035  1520 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 15:56:17.696  1035  1520 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 15:56:17.697  1035  1520 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 15:56:17.697  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 15:56:17.697  1035  1520 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 15:56:17.697  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 15:56:17.697  1925  1925 D WfdsService: Update P2p Interface State: 3
08-31 15:56:17.697  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=212900  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 15:56:17.697  1035  1520 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 15:56:17.697  1035  1520 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 15:56:17.698  1035  1521 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 15:56:17.698  1035  1521 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 15:56:17.698  1035  1521 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 15:56:17.699  1035  1521 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 15:56:17.699  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:17.699  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:17.700  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:17.700  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:17.700  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 15:56:17.701  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:56:17.709  7037  7037 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 15:56:17.709  1035  1520 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 15:56:17.709  1035  1520 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 15:56:17.709  1035  1520 D LGWifiP2pService: InactiveState
08-31 15:56:17.709  1035  1520 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.709  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.709  1035  1520 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 15:56:17.710  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 15:56:17.710  1035  1520 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 15:56:17.710  1035  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.710  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.710  7037  7037 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:17.711  1925  7055 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:56:17.711  1035  7052 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:56:17.711  1035  7052 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:17.711  1035  7052 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:17.711  1035  7052 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:17.711  7037  7037 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 15:56:17.711  7037  7037 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.711  1035  1520 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.712  7037  7037 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.712  1035  1521 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 15:56:17.713  1925  7055 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:17.713  1035  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.713  1925  7055 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:17.713  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.713  1035  7052 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:17.713  1035  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.713  1035  7052 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 15:56:17.713  1035  7052 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.713  1035  7052 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 15:56:17.713  1035  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.713  1035  7052 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:17.713  1035  7052 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.713  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.713  1035  7052 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.713  1035  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.713  1035  7052 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.713  1035  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.713  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.713  1035  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.713  1035  1521 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 15:56:17.714  1035  1035 E WifiServerServiceExt: No p2p device connected
08-31 15:56:17.714  1035  1521 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 15:56:17.714  1035  1521 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 15:56:17.714  7037  7037 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 15:56:17.714  1925  2306 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 15:56:17.715  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 15:56:17.716  1035  1521 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 15:56:17.716  1035  1521 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 15:56:17.716  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 15:56:17.717  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 15:56:17.717  7037  7037 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:17.718  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:56:17.718  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:17.718  1035  7052 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:17.718  1035  7052 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:17.718  7037  7037 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 15:56:17.718  7037  7037 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.718  1925  7055 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:17.719  1035  7052 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:17.719  1035  7052 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.719  1035  7052 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.719  1035  7052 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.719  1035  1521 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 15:56:17.719  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.719  7037  7037 I wpa_supplicant: p2p0,: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.719  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:17.719  1925  7055 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:17.719  1035  7052 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:17.719  1035  7052 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.719  1035  7052 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.719  1035  7052 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:17.720  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:56:17.720  1035  1521 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:56:17.720  1035  1521 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:56:17.720  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 15:56:17.721  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 15:56:17.721  7037  7037 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:56:17.721  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 15:56:17.721  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:56:17.721  1035  7052 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:56:17.721  1035  7052 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:56:17.721  1035  1521 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 15:56:17.721  1035  1521 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 15:56:17.722  1035  1521 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 15:56:17.722  1035  1521 D WifiNative-wlan0: doBoolean: SCAN
08-31 15:56:17.722  1035  1521 D WifiNative-wlan0: SCAN: returned false
08-31 15:56:17.723  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=212926  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 15:56:17.723  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=212927  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 15:56:17.724  1035  1521 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:56:17.724  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:17.724  1035  1521 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:56:17.725  1035  1521 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:56:17.725  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:17.725  1035  1521 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:56:17.726  1035  1521 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:56:17.727  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:17.727  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:17.727  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:17.727  1035  1035 D WifiOffDe,layIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 15:56:17.728  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:17.728  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 15:56:17.729  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:17.729  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 15:56:17.750  7019  7019 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 15:56:17.778  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 15:56:17.778  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:17.778  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 15:56:17.780  6889  7057 W FormManager: Network not available. Please check & try again.
08-31 15:56:17.781  6889  7058 V FormManager: Network unavailable.
08-31 15:56:17.784  7019  7019 I HubEmail: JNI_OnLoad()
08-31 15:56:17.784  7019  7019 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 15:56:17.784  7019  7019 I HubEmail: registerNatives()
08-31 15:56:17.784  7019  7019 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 15:56:17.784  7019  7019 I HubEmail: registerNativeMethods()
08-31 15:56:17.784  7019  7019 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 15:56:17.785  7019  7019 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-31 15:56:17.822  1035  2035 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7061 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 15:56:17.828  6889  7058 V FormManager: Network unavailable.
08-31 15:56:17.830  7019  7060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:17.841  1035  1051 I ActivityManager: Killing 6101:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-31 15:56:17.885  1035  1559 W libprocessgroup: failed to open /acct/uid_10080/pid_6101/cgroup.procs: No such file or directory
,08-31 15:56:17.952  7061  7061 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:17.952  7061  7061 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:17.957  7061  7061 D PhoneMonitor: Register our PhoneStateListener
08-31 15:56:17.976  7061  7061 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-31 15:56:17.978  7061  7061 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 15:56:17.992  7061  7061 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-31 15:56:17.994  7061  7061 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-31 15:56:17.996  7061  7061 D TelephonyAutoProfiling: [parse] Load xml
08-31 15:56:18.009  7061  7061 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 15:56:18.009  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,08-31 15:56:18.009  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
,08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-31 15:56:18.010  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 15:56:18.011  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 15:56:18.011  7061  7061 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 15:56:18.011  7061  7061 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-31 15:56:18.017  7061  7061 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-31 15:56:18.050  1035  1559 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7080 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 15:56:18.051  1035  1559 I ActivityManager: Killing 6121:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-31 15:56:18.106  1035  2013 W libprocessgroup: failed to open /acct/uid_10097/pid_6121/cgroup.procs: No such file or directory
,08-31 15:56:18.240  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 15:56:18.241  1035  7052 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-31 15:56:18.241  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-31 15:56:18.241  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-31 15:56:18.241  1035  7052 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 15:56:18.241  7037  7037 E wpa_supplicant: USIM:  scard_init function
08-31 15:56:18.242  1035  1521 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 15:56:18.242  1035  1521 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 15:56:18.242  7037  7037 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-31 15:56:18.243  1035  1521 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 15:56:18.244  1035  1521 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 15:56:18.245  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 15:56:18.245  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 15:56:18.246  1035  1521 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 15:56:18.260  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=213464  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 15:56:18.263  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=213466  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 15:56:18.265  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:18.265  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:18.266  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.269  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.269  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.269  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 15:56:18.270  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:18.270  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 15:56:18.352  1035  1871 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7101 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-31 15:56:18.362  7037  7037 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 15:56:18.363  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 15:56:18.364  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 15:56:18.364  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 15:56:18.364  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 15:56:18.364  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:18.364  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:18.365  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=213569  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 15:56:18.366  1035  1871 I ActivityManager: Killing 6550:com.lge.eula/1000 (adj 15): empty #17
,08-31 15:56:18.371  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=213569  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 15:56:18.372  1035  1521 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213575
08-31 15:56:18.372  1035  1521 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213576
08-31 15:56:18.373  1035  1521 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213576
08-31 15:56:18.376  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213577
08-31 15:56:18.377  1035  1521 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=213580
08-31 15:56:18.377  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=213580  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 15:56:18.378  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:18.378  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:18.378  7037  7037 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:56:18.378  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 15:56:18.378  7037  7037 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 15:56:18.378  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:56:18.378  1035  7052 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:56:18.378  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 15:56:18.378  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 15:56:18.378  1035  7052 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-31 15:56:18.380  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:18.380  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:18.416  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 15:56:18.416  1035  1870 W libprocessgroup: failed to open /acct/uid_1000/pid_6550/cgroup.procs: No such file or directory
08-31 15:56:18.425  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:18.425  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:18.425  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=213629  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 15:56:18.427  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:56:18.427  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.427  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 15:56:18.431  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.432  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.432  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.432  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 15:56:18.433  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=213636  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 15:56:18.434  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=213637  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-31 15:56:18.434  1035  1521 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=213637
08-31 15:56:18.436  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:18.436  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 15:56:18.437  1035  1521 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=213640
08-31 15:56:18.437  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:18.437  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 15:56:18.437  1035  1521 D WifiNative-wlan0: doString: [STATUS]
08-31 15:56:18.438  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:18.438  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:18.438  1035  1521 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 15:56:18.439  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.440  1035  1521 I WifiServiceExtension: setVHTCapabilityType  : false
,08-31 15:56:18.448  1035  1521 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 15:56:18.448  1035  1521 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-31 15:56:18.452  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.452  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.452  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 15:56:18.454  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:18.454  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 15:56:18.457  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.459  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.459  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.459  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 15:56:18.460  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:18.460  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:18.461  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.464  1035  1521 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 15:56:18.464  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:56:18.464  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 15:56:18.464  1035  1527 D ConnectivityService: Got NetworkAgent Messenger
08-31 15:56:18.465  1035  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 15:56:18.465  1035  1527 D ConnectivityService: NetworkAgent connected
08-31 15:56:18.465  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 15:56:18.465  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 15:56:18.470  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 15:56:18.470  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:56:18.470  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-31 15:56:18.470  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 15:56:18.470  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 15:56:18.474  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 15:56:18.476   309   893 D CommandListener: Setting iface cfg
08-31 15:56:18.479  1035  1521 E WifiStateMachine: Start Dhcp Watchdog 2
08-31 15:56:18.479  1035  7124 D DhcpStateMachine: StoppedState
08-31 15:56:18.480  1035  7124 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.480  1035  7124 D DhcpStateMachine: WaitBeforeStartState
08-31 15:56:18.480  1035  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=213683  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:18.480  1035  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=213684  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:18.481  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=213684  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:18.481  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:18.482  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:18.482  1035  1521 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:18.483  1035  1521 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:18.483  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:18.483  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 15:56:18.531  1035  2035 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7125 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 15:56:18.532  1035  2035 I ActivityManager: Killing 6567:com.lge.bnr/1000 (adj 15): empty #17
,08-31 15:56:18.576  1035  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_6567/cgroup.procs: No such file or directory
,08-31 15:56:18.584  1035  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=213787  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:18.585  1035  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=213788  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:18.585  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=213788  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:18.586  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:168146] from screen [on:0 period:-522003942] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 15:56:18.587  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-522003941] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 15:56:18.587  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 15:56:18.591  1035  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-31 15:56:18.591  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.591  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.592  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.592  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 15:56:18.592  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.593  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.593  1035  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 15:56:18.594  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=101,0,0
08-31 15:56:18.594  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=101,0,0
08-31 15:56:18.594  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 15:56:18.594  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 15:56:18.595  1035  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 15:56:18.595  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 15:56:18.595  1035  1521 D WifiNative-wlan0: SET ps 0: returned true
08-31 15:56:18.595  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 15:56:18.595  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 15:56:18.595  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 15:56:18.596  1035  1521 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 15:56:18.596  1035  1521 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 15:56:18.596  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@293e30a6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.596  1035  1521 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 15:56:18.596  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@293e30a6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.596  1035  7124 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.596  1035  7124 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 15:56:18.596   309   893 D CommandListener: Setting iface cfg
08-31 15:56:18.597   309   893 D CommandListener: Trying to bring up wlan0
08-31 15:56:18.598  1035  1521 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 15:56:18.599  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.599  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.599  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.600  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.600  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.601  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:18.601  1035  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 15:56:18.602  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 15:56:18.602  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 15:56:18.602  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 15:56:18.602  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 15:56:18.602  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.603  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.603  1035  1521 D WifiNative-wlan0,: DRIVER BTCOEXMODE 2: returned true
08-31 15:56:18.603  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 15:56:18.603  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 15:56:18.603  1035  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 15:56:18.603  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:56:18.610  7125  7125 I art     : Almond Protected OAT
08-31 15:56:18.619  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.619  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.619  1035  1520 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.622  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:56:18.622  1035  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 15:56:18.623  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 15:56:18.623  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 15:56:18.623  1035  1521 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 15:56:18.623  1035  1527 D ConnectivityService: ignoring duplicate network state non-change
08-31 15:56:18.624  1035  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 15:56:18.625  1035  1527 D ConnectivityService: Adding iface wlan0 to network 101
08-31 15:56:18.627  1035  1521 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 15:56:18.631  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:18.631  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-31 15:56:18.633  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.638  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:18.638  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:18.640  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.640  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.640  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 15:56:18.640  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.645  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.645  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.645  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 15:56:18.647  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 15:56:18.647  1035  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 15:56:18.647  1035  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-31 15:56:18.648  1035  1521 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 15:56:18.648  1035  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-31 15:56:18.648  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 15:56:18.649   309   893 E Netd    : netlink response contains error (File exists)
08-31 15:56:18.649  1035  1521 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 15:56:18.649  1035  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-31 15:56:18.649  1035  1521 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 15:56:18.649  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 15:56:18.649  1035  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 15:56:18.649  1035  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-31 15:56:18.650  1035  1527 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-31 15:56:18.650  1035  1521 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 15:56:18.650  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-31 15:56:18.653  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.653  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.653  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 15:56:18.654  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 15:56:18.658  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.658  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:18.658  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 15:56:18.658  1035  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 15:56:18.658  1035  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 15:56:18.658  1035  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-31 15:56:18.658  1035  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 15:56:18.659  1035  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:18.659  1035  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:18.659  1035  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 15:56:18.659  1035  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:18.659  1035  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 15:56:18.659  1035  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-31 15:56:18.659  1035  1527 D ConnectivityService:    accepting network in place of null
08-31 15:56:18.659  1035  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:18.659  1035  1521 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:18.659  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:18.660  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:18.660  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 15:56:18.660  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:56:18.660  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 15:56:18.660  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:18.660  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:18.661  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:18.661   309  7146 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 15:56:18.662  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 15:56:18.663  1035  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 15:56:18.663  1035  1527 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 15:56:18.663  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 15:56:18.663  1035  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:18.663  1035  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 15:56:18.663  1035  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 15:56:18.666  1035  1527 D ConnectivityService: validation of new default Network = false
08-31 15:56:18.666  1035  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 15:56:18.666  1035  1527 D DSQN    : enableDataServiceNotify 
08-31 15:56:18.666  1035  1527 D DSQN    : start dsqn bin
08-31 15:56:18.666  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.668  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 15:56:18.669  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 15:56:18.669  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 15:56:18.669  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 15:56:18.670  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:18.670  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 15:56:18.670  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.673  1035  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 15:56:18.673  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 15:56:18.673  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:18.674  1035  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:18.674  1586  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 15:56:18.655  7147  7147 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:18.655  7147  7147 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:18.679  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:18.679  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 15:56:18.679  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:56:18.688  7147  7147 E DSQN    : DSQN ssw
08-31 15:56:18.693  1035  1519 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-31 15:56:18.702  7125  7125 D WeatherApplication: removeAccount
08-31 15:56:18.706  7125  7125 D WeatherApplication: Account.length = 0
08-31 15:56:18.706  7125  7125 E WeatherApplication: OPERATOR:OPEN
08-31 15:56:18.707  1800  7151 I CheckinService: active receiver: enabled
08-31 15:56:18.710  7125  7125 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:18
,08-31 15:56:18.716  1800  7151 I CheckinService: Preparing to send checkin request
08-31 15:56:18.716  1800  7151 I EventLogService: Accumulating logs since 1472651622594
08-31 15:56:18.717  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:56:18.718  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.718  7125  7125 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 15:56:18.718  7125  7125 D Weather.Utils: 2 : All the weather widget is gone.
08-31 15:56:18.718  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:18.719  7125  7125 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 15:56:18.721  7125  7125 D WeatherAncestor: connectivity changed - connection : true
08-31 15:56:18.722  7125  7125 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-31 15:56:18.728  7125  7125 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 15:56:18.728  7125  7125 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 15:56:18.728  7125  7125 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-31 15:56:18.741  1800  7151 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-31 15:56:18.743  7125  7125 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 15:56:18.743  7125  7125 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:18
08-31 15:56:18.773  1035  1995 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7154 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 15:56:18.774  1035  1995 I ActivityManager: Killing 2110:com.lge.music/u0a34 (adj 15): empty #17
08-31 15:56:18.788   343   343 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 300us total 13.736ms
,08-31 15:56:18.798  1035  7124 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 15:56:18.802   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 255us total 12.924ms
,08-31 15:56:18.802  1035  7124 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 15:56:18.802  1035  7124 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-31 15:56:18.795  7171  7171 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:18.795  7171  7171 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:18.814  7171  7171 I dhcpcd  : version 5.5.6 starting
08-31 15:56:18.817  7171  7171 E dhcpcd  : get_duid: m
08-31 15:56:18.817  7171  7171 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 15:56:18.817  7171  7171 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-31 15:56:18.819   313  1766 V AudioFlinger: 2110 died, releasing its sessions
08-31 15:56:18.819   313  1766 V AudioFlinger:  pid 1836 @ 0
08-31 15:56:18.819   313  1766 V AudioFlinger:  pid 3439 @ 1
08-31 15:56:18.819   313  1766 V AudioFlinger:  pid 3439 @ 2
08-31 15:56:18.820   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 228us total 17.695ms
,08-31 15:56:18.870  7171  7171 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 15:56:18.870  7171  7171 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 15:56:18.870  7171  7171 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 15:56:18.871  7171  7171 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 15:56:18.871  7171  7171 D dhcpcd  : wlan0: sending REQUEST (xid 0xeec5022c), next in 3.76 seconds
08-31 15:56:18.873  1035  1716 W libprocessgroup: failed to open /acct/uid_10034/pid_2110/cgroup.procs: No such file or directory
,08-31 15:56:18.928  7171  7171 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-31 15:56:18.963  7171  7171 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 15:56:18.963  7171  7171 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 15:56:18.963  7171  7171 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 15:56:18.964  7171  7171 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-31 15:56:18.964  7171  7171 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 15:56:18.965  7171  7171 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 15:56:18.965  7171  7171 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 15:56:18.965  7171  7171 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 15:56:18.976   279   477 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 15:56:18.976   279   477 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 15:56:18.976   279   477 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 15:56:18.978  7154  7179 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-31 15:56:18.988  1035  2035 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7184 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-31 15:56:18.988   279   477 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 15:56:18.988   279   477 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 15:56:18.988   279   477 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 15:56:18.989  7154  7179 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 15:56:19.001   279   477 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-31 15:56:19.001   279   477 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 15:56:19.001   279   477 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 15:56:19.004  7154  7196 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 15:56:19.009   279   477 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 15:56:19.009   279   477 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 15:56:19.009   279   477 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 15:56:19.009  7154  7196 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 15:56:19.019   309  7146 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-31 15:56:19.044  7184  7184 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-31 15:56:19.044  7184  7184 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 15:56:19.075  7184  7184 I MultiDex: VM with version 2.1.0 has multidex support
08-31 15:56:19.075  7184  7184 I MultiDex: install
08-31 15:56:19.075  7184  7184 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 15:56:19.085  7184  7184 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-31 15:56:19.191  7154  7154 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 15:56:19.205  1035  7124 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 15:56:19.207  1035  7124 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-31 15:56:19.208  1035  7124 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 15:56:19.208  1035  7124 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 15:56:19.209  1035  7124 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-31 15:56:19.209  1035  7124 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 15:56:19.209  1035  7124 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 15:56:19.209  1035  7124 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-31 15:56:19.209  1035  7124 D DhcpStateMachine: RunningState
08-31 15:56:19.211  7154  7154 I LibraryLoader: Loading: webviewchromium
,08-31 15:56:19.214  7154  7154 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4426-4429)
08-31 15:56:19.214  7154  7154 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:56:19.223  7154  7154 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1dd25ea0},
,08-31 15:56:19.227  7154  7154 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 15:56:19.228  7154  7154 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 15:56:19.250  7154  7154 I BrowserStartupController: Initializing chromium process, renderers=0
,08-31 15:56:19.252  7154  7154 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:56:19.268  7154  7154 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 15:56:19.269  7154  7154 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-31 15:56:19.269  7154  7154 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-31 15:56:19.275   313  1369 V AudioPolicyService: registerClient() client 0xb04107c0, uid 10093
08-31 15:56:19.276  7154  7242 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 15:56:19.297   309  7146 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-31 15:56:19.299  7154  7154 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:56:19.299  7154  7154 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:56:19.299  7154  7154 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:56:19.299  7154  7154 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:56:19.299  7154  7154 I Adreno-EGL: Remote Branch: 
08-31 15:56:19.299  7154  7154 I Adreno-EGL: Local Patches: 
08-31 15:56:19.299  7154  7154 I Adreno-EGL: Reconstruct Branch: 
,08-31 15:56:19.430  7184  7204 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:19.431  7184  7204 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:19.469  1035  1639 I art     : Explicit concurrent mark sweep GC freed 101336(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.473ms total 99.609ms
,08-31 15:56:19.492   309   892 D LGDataListener: argv[0]=dsqncommand
08-31 15:56:19.492   309   892 D LGDataListener: argv[1]=wlan0
08-31 15:56:19.492   309   892 D LGDataListener: argv[2]=1
08-31 15:56:19.492   309   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-31 15:56:19.493  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
,08-31 15:56:19.493  1035  1115 D DSQN    : start to monitor internet connection
08-31 15:56:19.501  7154  7154 I NSApplication: Starting up...
08-31 15:56:19.541  7258  7258 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 15:56:19.566  1035  1521 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:19.566  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:19.567  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:19.567  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:19.567  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:19.567  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 15:56:19.568  1035  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-31 15:56:19.568  1035  1527 D ConnectivityService: identical MTU - not setting
08-31 15:56:19.568  1035  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 15:56:19.568  1035  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 15:56:19.568  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.568  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:19.568  1035  1527 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:19.570  1586  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 15:56:19.582  1035  1559 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7264 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 15:56:19.583  1035  1995 I ActivityManager: Killing 6063:com.android.vending/u0a44 (adj 15): empty #17
08-31 15:56:19.596  7258  7258 I dex2oat : dex2oat took 55.321ms (threads: 4)
,08-31 15:56:19.607  7184  7204 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:56:19.607  7184  7204 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:56:19.607  7184  7204 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:56:19.607  7184  7204 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:56:19.607  7184  7204 I Adreno-EGL: Remote Branch: 
08-31 15:56:19.607  7184  7204 I Adreno-EGL: Local Patches: 
08-31 15:56:19.607  7184  7204 I Adreno-EGL: Reconstruct Branch: 
,08-31 15:56:19.673  1035  1527 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 15:56:19.679  7184  7204 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:56:19.679  7184  7204 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:56:19.679  7184  7204 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:56:19.679  7184  7204 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:56:19.679  7184  7204 I Adreno-EGL: Remote Branch: 
08-31 15:56:19.679  7184  7204 I Adreno-EGL: Local Patches: 
08-31 15:56:19.679  7184  7204 I Adreno-EGL: Reconstruct Branch: 
08-31 15:56:19.713  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 13:56:19 GMT], X-Android-Received-Millis=[1472651779712], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472651779491]}
,08-31 15:56:19.714  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 15:56:19.714  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 15:56:19.714  1035  1527 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-31 15:56:19.714  1035  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 15:56:19.714  1035  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:19.714  1035  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:19.714  1035  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 15:56:19.714  1035  1527 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-31 15:56:19.714  1035  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 15:56:19.714  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.714  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:19.715  1035  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:19.715  1035  1527 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.715  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 15:56:19.716  1586  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 15:56:19.716  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.716  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 15:56:19.725  1035  1521 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.725  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:19.726  1035  1639 W libprocessgroup: failed to open /acct/uid_10044/pid_6063/cgroup.procs: No such file or directory
,08-31 15:56:19.735  1035  1716 D WifiServiceImplEx: setWifiEnabled: false pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:56:19.735  1035  1716 D WifiService: setWifiEnabled: false pid=6692, uid=10118
08-31 15:56:19.735  1035  1716 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 15:56:19.755  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:56:19.756  1035  1521 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-31 15:56:19.756  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:56:19.756  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 15:56:19.756  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 15:56:19.756  1035  1521 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 15:56:19.757  1035  1521 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 15:56:19.758  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 15:56:19.758  1035  1521 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 15:56:19.758  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:56:19.758  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 15:56:19.759  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 15:56:19.759  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 15:56:19.765  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:56:19.766  7184  7204 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:56:19.766  7184  7204 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:56:19.766  7184  7204 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:56:19.766  7184  7204 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:56:19.766  7184  7204 I Adreno-EGL: Remote Branch: 
08-31 15:56:19.766  7184  7204 I Adreno-EGL: Local Patches: 
08-31 15:56:19.766  7184  7204 I Adreno-EGL: Reconstruct Branch: 
08-31 15:56:19.766  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:19.767  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:19.770  7264  7264 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:56:19.775  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 15:56:19.775  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-31 15:56:19.775  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.775  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.775  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 15:56:19.775  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 15:56:19.775  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:56:19.775  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:56:19.776  1035  7124 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.780   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:56:19.805  1035  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 15:56:19.805  1035  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-31 15:56:19.805  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.806  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.806  1035  1520 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@a23a0b7
,08-31 15:56:19.807  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:19.807  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:19.808  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 15:56:19.808  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:19.817  1035  1520 D LGWifiP2pService: P2pDisablingState
08-31 15:56:19.817  1035  1520 D LGWifiP2pService: P2pDisablingState{ when=-11ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.817  1035  1520 D LGWifiP2pService: p2p socket connection lost
08-31 15:56:19.817  1035  1520 D LGWifiP2pService: P2pDisabledState
08-31 15:56:19.817  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 15:56:19.817  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:19.818  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:19.818  1035  1521 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 15:56:19.818  1035  1521 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 15:56:19.818  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 15:56:19.818  7037  7037 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 15:56:19.818  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.818  1035  1520 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.818  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-31 15:56:19.819  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:19.819  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:19.819  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:56:19.819  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-31 15:56:19.819  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:19.819  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:19.819  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:56:19.819  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 15:56:19.819  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-31 15:56:19.819  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 15:56:19.819  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:56:19.819  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 15:56:19.820  1925  1925 D WfdsService: WifiP2pState is changed : false
08-31 15:56:19.820  1925  2306 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 15:56:19.820  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:56:19.820  1925  2306 D WfdsService: Set the WFDS Monitor: false
08-31 15:56:19.820  1035  1541 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:56:19.821  1035  1540 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.825  1925  2306 D WfdsMonitor: WFDS Monitor is stopped
08-31 15:56:19.825  1925  2306 D WfdsService: STATE : WfdsDisabledState - enter
08-31 15:56:19.825  1925  7055 D CtrlSupplicant: Received on exit socket, terminate
08-31 15:56:19.825  1925  7055 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 15:56:19.825  1925  7055 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 15:56:19.825  1925  7055 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 15:56:19.826  1925  2310 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 15:56:19.826  1925  2306 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 15:56:19.830  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:19.830  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:19.830  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:56:19.845   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:56:19.845  1035  1527 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 15:56:19.845  1035  1527 D DSQN    : disableDataServiceNotify
08-31 15:56:19.845  1035  1527 D DSQN    : stop dsqn bin
,08-31 15:56:19.848  1035  1521 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 15:56:19.848  1035  1521 D WifiNative-p2p0: TERMINATE: returned true
08-31 15:56:19.848  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:56:19.848  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:56:19.848  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:56:19.849  1035  1035 D WifiHS20: hidePasspointNotification off =false
,08-31 15:56:19.849  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:19.849  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:19.849  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:56:19.850  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 15:56:19.850  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:19.851  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 15:56:19.851  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:19.852  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 15:56:19.852  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 15:56:19.852  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:19.852  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:19.852  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:19.852  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:19.852  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:19.852  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:19.852  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:19.852  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:19.852  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:19.852  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:19.852  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:19.852  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:19.853  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:19.853  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:19.853  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:19.853  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:19.853  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:19.853  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:19.853  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:19.853  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:19.853  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:19.853  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for, multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:19.853  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:19.854  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:19.854  1035  1527 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 15:56:19.854  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.854  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:19.854  1035  1527 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:19.854  1035  1527 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 15:56:19.855  1035  1527 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 15:56:19.855  1035  1527 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 15:56:19.855  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.855  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 15:56:19.855  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.855  1035  7123 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 15:56:19.855  1586  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 15:56:19.855  1035  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:19.855  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 15:56:19.856  1035  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 15:56:19.856  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 15:56:19.857  1035  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:19.857  1035  1527 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.857  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 15:56:19.857  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 15:56:19.857  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 15:56:19.857  1035  1527 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.857  1035  1519 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 15:56:19.859  1035  1527 D NetworkManagementService: Removing idletimer
08-31 15:56:19.859  1035  1527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:19.860  1035  1527 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 15:56:19.860  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.860  1035  1521 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:19.860  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:19.860  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 15:56:19.860  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 15:56:19.860  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 15:56:19.861  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 15:56:19.861  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-31 15:56:19.883  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:56:19.884  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:19.884  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:56:19.894  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:56:19.895  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:19.895  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:19.936  7037  7037 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 15:56:19.936  7037  7037 I wpa_supplicant: monitor socket send errors count : 1
08-31 15:56:19.936  7037  7037 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-4\x00 that cannot receive messages
08-31 15:56:19.938  1035  7052 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 15:56:19.938  1035  7052 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 15:56:19.961  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-31 15:56:19.964  7037  7037 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:56:19.965  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 15:56:19.965  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:56:19.965  1035  7052 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 15:56:19.965  1035  7052 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 15:56:19.965  1035  1521 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=215169
08-31 15:56:19.966  1035  1521 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=215169
08-31 15:56:19.966  7037  7037 W wpa_supplicant: USIM:  scard_deinit function
,08-31 15:56:19.966  1035  1117 D Tethering: InitialState.processMessage what=4
08-31 15:56:19.967  6393  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 15:56:19.967  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:19.967  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:19.967  1035  1521 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=215171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 15:56:19.968  1035  1521 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=215171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 15:56:19.969  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:56:19.970  1035  1521 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:19.970  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 15:56:19.980  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:19.982  1035  7124 D DhcpStateMachine: StoppedState
08-31 15:56:19.982  1035  7124 D DhcpStateMachine: StoppedState{ when=-162ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:19.984  1035  1521 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 15:56:19.984  1035  1521 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 15:56:19.987  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 15:56:19.987  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:19.987  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 15:56:19.987  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 15:56:19.990  6983  6983 I AppUp4:CustModeStarterReceiver: onReceive
08-31 15:56:19.994  6983  6983 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d7530b1
08-31 15:56:19.994  6983  6983 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 15:56:19.994  6983  6983 D AppUp4:CustFacade: isPhone : true
08-31 15:56:19.995  6983  6983 D AppUp4:CustModeStarterReceiver: begin check event
08-31 15:56:19.995  6983  6983 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 15:56:19.997  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:19.997  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:56:19.998  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:20.001  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 15:56:20.004  4292  7300 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:56:20.007  7019  7019 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 15:56:20.008  4292  7301 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:20.008  4292  7301 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:56:20.020  6889  7304 W FormManager: Network not available. Please check & try again.
08-31 15:56:20.022  7019  7302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:56:20.027  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 15:56:20.027  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:20.027  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 15:56:20.029  7061  7061 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 15:56:20.029  7061  7061 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 15:56:20.030  6889  7305 V FormManager: Network unavailable.
08-31 15:56:20.038  6889  7305 V FormManager: Network unavailable.
,08-31 15:56:20.042   309  7308 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 15:56:20.042  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 15:56:20.042  1800  7151 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-31 15:56:20.045  7037  7037 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 15:56:20.045  1035  7052 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 15:56:20.045  1035  7052 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 15:56:20.046  1035  7052 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 15:56:20.046  1035  1521 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-31 15:56:20.047  7125  7125 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:20
08-31 15:56:20.049  1800  7151 I CheckinService: active receiver: disabled
,08-31 15:56:20.067  7125  7125 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 15:56:20.067  7125  7125 D Weather.Utils: 2 : All the weather widget is gone.
08-31 15:56:20.068  7125  7125 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 15:56:20.068  7125  7125 D WeatherAncestor: connectivity changed - connection : true
08-31 15:56:20.068  7125  7125 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a398917
08-31 15:56:20.069  7125  7125 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 15:56:20.069  7125  7125 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 15:56:20.069  7125  7125 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 15:56:20.069  7125  7125 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 15:56:20.069  7125  7125 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:20
08-31 15:56:20.088  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-31 15:56:20.089  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:56:20.089  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:56:20.089  6777  6777 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 15:56:20.089  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 15:56:20.090  6777  6777 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:56:20.090  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 15:56:20.090  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:56:20.090  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:56:20.090  6777  6777 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 15:56:20.090  6777  6777 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 15:56:20.096  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:20.100  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:56:20.102  6889  7310 W FormManager: Network not available. Please check & try again.
08-31 15:56:20.104  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:20.110  6889  7311 V FormManager: Network unavailable.
08-31 15:56:20.113  6889  7311 V FormManager: Network unavailable.
,08-31 15:56:20.119  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:20.119  6889  7312 W FormManager: Network not available. Please check & try again.
08-31 15:56:20.121  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 15:56:20.126  6889  7313 V FormManager: Network unavailable.
08-31 15:56:20.126  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:56:20.132  6889  7313 V FormManager: Network unavailable.
08-31 15:56:20.138  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 15:56:20.139  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:56:20.140  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:20.142  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:20.149  4292  7314 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 15:56:20.151  4292  7315 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:56:20.151  4292  7315 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:56:20.205  1035  1871 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7316 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-31 15:56:20.208  1035  1521 D WifiOffDelayIfNotUsed: stopMonitoring
,08-31 15:56:20.209  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:56:20.209  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:56:20.209  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-31 15:56:20.210  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-31 15:56:20.211  1925  2306 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 15:56:20.211  1925  2306 D WfdsService: Set the WFDS Monitor: false
08-31 15:56:20.211  1925  2306 D WfdsMonitor: WFDS Monitor is stopped
08-31 15:56:20.212  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 15:56:20.213  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:20.213  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:20.213  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:20.213  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:20.213  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:20.213  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:20.213  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:20.213  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:20.213  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:20.214  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 15:56:20.214  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:20.215  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:20.215  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:20.215  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:20.215  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:20.215  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:20.215  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:20.215  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:20.215  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:20.215  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:20.215  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:20.216  1035  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 15:56:20.216  1035  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-31 15:56:20.333  7316  7316 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 15:56:20.334  7316  7316 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-31 15:56:20.346  7316  7316 V [BNRBootReceiver]: Boot Receiver Return
08-31 15:56:20.347  7316  7316 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 15:56:20.351  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:56:20.366  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.379  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:20.397  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:56:20.398  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.401  6851  6851 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:56:20.410  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:20.428  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.442  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:20.451  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:20.451  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.454  6851  6851 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 15:56:20.461  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-31 15:56:20.468  6777  6777 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 15:56:20.476  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:20.492  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.499  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:20.508  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:20.509  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.509  6851  6851 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:56:20.516  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:20.527  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.535  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:20.546  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:20.546  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.547  6851  6851 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:56:20.553  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:20.565  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.574  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:20.584  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:56:20.585  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.586  6851  6851 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:56:20.594  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:20.607  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.614  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:20.622  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:56:20.623  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.624  6851  6851 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:56:20.631  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:20.641  6588  6960 D UEI.SmartControl: Internal timer expired: 2
08-31 15:56:20.641  6588  6960 D UEI.SmartControl: unbind internal service
,08-31 15:56:20.641  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.649  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:56:20.656  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:20.656  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.656  6851  6851 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:56:20.665  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:20.680  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.687  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:56:20.697  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:20.697  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 15:56:20.701  6851  6851 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:56:20.707  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:20.720  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.722  6588  6954 D serial_port: close(fd = 24)
,08-31 15:56:20.727  6588  6954 I UEI.SmartControl: Serial port is closed.
08-31 15:56:20.730  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:56:20.740  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:20.741  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.743  6851  6851 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:56:20.750  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:20.759  6819  6819 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 15:56:20.771  1035  1526 D WifiService: New client listening to asynchronous messages
08-31 15:56:20.772  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:20.778  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.788  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:56:20.799  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:20.799  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.801  6851  6851 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-31 15:56:20.802  6851  6851 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 15:56:20.803  6851  6851 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 15:56:20.811  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:56:20.821  6819  6819 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 15:56:20.824  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:20.831  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:20.842  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:20.854  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:20.855  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:20.856  6851  6851 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-31 15:56:20.857  6851  6851 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-31 15:56:20.858  6851  6851 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 15:56:20.863  1035  1959 I ActivityManager: Killing 6796:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-31 15:56:20.962  1035  1978 W libprocessgroup: failed to open /acct/uid_10037/pid_6796/cgroup.procs: No such file or directory
08-31 15:56:20.963  2203  2203 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-31 15:56:20.993  2203  2203 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-31 15:56:20.995  2203  2203 D c       : Getting all permits...
08-31 15:56:20.996  2203  2203 D a       : Opening database...
08-31 15:56:21.002  2203  2203 D a       : Opening database auth.proximity.permit_store...
08-31 15:56:21.003  2203  2203 D a       : Closing database...
08-31 15:56:21.019  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:56:21.028  6819  6819 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 15:56:21.029  6819  6819 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:56:21.029  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:21.037  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:21.046  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:21.059  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:21.060  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 15:56:21.068  6851  6851 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:56:21.077  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:56:21.084  6819  6819 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 15:56:21.084  6819  6819 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:56:21.084  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:21.094  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:21.106  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:21.118  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:21.118  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 15:56:21.122  6851  6851 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:56:21.129  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:21.140  6819  6819 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 15:56:21.140  6819  6819 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:56:21.140  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:56:21.149  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:21.159  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:21.171  6851  6851 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:21.172  6851  6851 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 15:56:21.176  6851  6851 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:56:21.192  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:56:21.198  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:56:21.211  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:21.213  6889  7341 W FormManager: Network not available. Please check & try again.
08-31 15:56:21.235  6889  7342 V FormManager: Network unavailable.
,08-31 15:56:21.249  2203  2203 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-31 15:56:21.253  6889  7342 V FormManager: Network unavailable.
08-31 15:56:21.286  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 15:56:21.287  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:56:21.291  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:21.297  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:21.310  4292  7343 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:56:21.316  4292  7344 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:56:21.317  4292  7344 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:56:21.319  6819  6819 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 15:56:21.320  6819  6819 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 15:56:21.320  6819  6819 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:21.328  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:56:21.337  6889  7346 W FormManager: Network not available. Please check & try again.
08-31 15:56:21.339  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:21.348  6889  7347 V FormManager: Network unavailable.
,08-31 15:56:21.353  6889  7347 V FormManager: Network unavailable.
08-31 15:56:21.594  1035  1521 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-522000935] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 15:56:21.603  1035  1521 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-522000925] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 15:56:21.665  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:56:21.678  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-31 15:56:21.697  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:56:21.701  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:21.705  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:21.707  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 15:56:21.709  6393  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 15:56:21.720  5756  5756 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 15:56:21.743  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:56:21.769  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 15:56:21.769  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:21.769  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 15:56:21.769  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 15:56:21.774  6983  6983 I AppUp4:CustModeStarterReceiver: onReceive
08-31 15:56:21.777  6983  6983 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d7530b1
08-31 15:56:21.777  6983  6983 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 15:56:21.777  6983  6983 D AppUp4:CustFacade: isPhone : true
08-31 15:56:21.778  6983  6983 D AppUp4:CustModeStarterReceiver: begin check event
08-31 15:56:21.778  6983  6983 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 15:56:21.782  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:21.783  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:56:21.784  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 15:56:21.790  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:21.797  7019  7019 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 15:56:21.821  4292  7356 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:56:21.827  7019  7355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:21.835  4292  7357 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:21.836  4292  7357 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 15:56:21.846  6889  7359 V FormManager: Network unavailable.
08-31 15:56:21.849  6889  7358 W FormManager: Network not available. Please check & try again.
,08-31 15:56:21.851  6889  7359 V FormManager: Network unavailable.,
08-31 15:56:21.867  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 15:56:21.872  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-31 15:56:21.872  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:21.872  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = true
08-31 15:56:21.872  3439  3439 D PhoneState: setPdpRejectCasuse : false
08-31 15:56:21.876  7061  7061 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 15:56:21.876  7061  7061 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 15:56:21.888  7125  7125 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:21
,08-31 15:56:21.891  7125  7125 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 15:56:21.891  7125  7125 D Weather.Utils: 2 : All the weather widget is gone.
08-31 15:56:21.891  7125  7125 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 15:56:21.891  7125  7125 D WeatherAncestor: connectivity changed - connection : true
08-31 15:56:21.891  7125  7125 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a398917
08-31 15:56:21.892  7125  7125 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 15:56:21.892  7125  7125 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 15:56:21.892  7125  7125 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 15:56:21.892  7125  7125 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 15:56:21.892  7125  7125 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:21
08-31 15:56:22.758  1035  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:22.759  1035  1906 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 15:56:22.788  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:56:22.788  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:56:22.788  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-31 15:56:22.791  1035  1117 D BluetoothManagerService: Message: 1
08-31 15:56:22.791  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-31 15:56:22.819  1035  1117 D BluetoothManagerService: Message: 20
08-31 15:56:22.819  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@867f366:true
,08-31 15:56:22.823  6918  6918 D BluetoothAdapterState: make
08-31 15:56:22.828  6918  6918 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 15:56:22.828  6918  6918 I bluedroid-qcom: init
08-31 15:56:22.829  6918  7387 I BluetoothAdapterState: Entering OffState
08-31 15:56:22.829  6918  6918 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 15:56:22.830  6918  6918 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 15:56:22.830  6918  6918 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 15:56:22.830  6918  6918 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 15:56:22.830  6918  6918 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 15:56:22.831  6918  6918 I bluedroid-qcom: get_profile_interface socket
08-31 15:56:22.831  6918  6918 I bluedroid-qcom: get_profile_interface map_client
,08-31 15:56:22.836  6918  7391 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 15:56:22.825  7390  7390 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:22.840  6918  7391 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 15:56:22.825  7390  7390 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:22.850  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 15:56:22.850  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 15:56:22.851  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-31 15:56:22.853  1035  1117 D BluetoothManagerService: Message: 40
08-31 15:56:22.854  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 15:56:22.856  7390  7390 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 15:56:22.856  7390  7390 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 15:56:22.856  7390  7390 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-31 15:56:22.857  6918  6933 I bluedroid-qcom: config_hci_snoop_log
08-31 15:56:22.858  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:22.859  7390  7390 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 15:56:22.863  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:56:22.868  7390  7390 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 15:56:22.868  7390  7390 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 15:56:22.873  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:22.874  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 15:56:22.874  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 15:56:22.877  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:56:22.893  6918  7387 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-31 15:56:22.896  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:22.896  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-31 15:56:22.896  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-31 15:56:22.897  6918  7391 D BluetoothAdapterProperties: Name is: G3
08-31 15:56:22.898  6918  7387 D BluetoothAdapterProperties: Setting state to 11
08-31 15:56:22.898  6918  7387 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 15:56:22.899  1035  1117 D BluetoothManagerService: Message: 60
08-31 15:56:22.899  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 15:56:22.899  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 15:56:22.900  6918  7387 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 15:56:22.916  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:22.917  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-31 15:56:22.924  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:22.927  6918  7387 D BluetoothBondStateMachine: make
08-31 15:56:22.929  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:22.932  6918  7406 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 15:56:22.932  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:22.933  6918  7387 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:22.933  6918  7387 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 15:56:22.934  6918  7387 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:22.934  6918  7387 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 15:56:22.934  6918  7387 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 15:56:22.935  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:22.938  6918  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:22.938  6777  6777 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 15:56:22.941  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 15:56:22.943  6393  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 15:56:22.951  6918  6918 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:56:22.951  6918  6918 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:22.952  6918  6918 V BluetoothPbapReceiver: ***********state = 11
08-31 15:56:22.954  5756  5756 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 15:56:22.959  6918  7387 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:56:22.960  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:22.962  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:56:22.962  6918  6918 D HeadsetService: Received start request. Starting profile...
08-31 15:56:22.962  6918  6918 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 15:56:22.962  6918  6918 D LGBluetoothHfpAdapter: Version 1.6
08-31 15:56:22.964  5756  5756 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 15:56:22.965  6918  6918 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 15:56:22.967  6918  6918 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 15:56:22.967  6918  6918 D HeadsetStateMachine: make
08-31 15:56:22.969  6918  7387 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:56:22.998  6918  6918 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:22.998  6918  6918 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:23.014  1035  1050 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7411 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 15:56:23.018  6918  6918 D HeadsetStateMachine: max_hf_connections = 1
08-31 15:56:23.018  6918  6918 I bluedroid-qcom: get_profile_interface handsfree
08-31 15:56:23.021  6918  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:23.023  6918  6918 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 15:56:23.023   313  1766 V AudioPolicyService: registerClient() client 0xb558a600, uid 1002
08-31 15:56:23.024   313  1369 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 15:56:23.024   313  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:56:23.024   313  1369 V AudioPolicyManagerEx: getOutput() returns output 2
,08-31 15:56:23.024  6918  6918 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 15:56:23.024   313   313 V AudioFlinger: registerClient() client 0xb55815c8, pid 6918
08-31 15:56:23.025   313  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:23.025   313  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:56:23.025  1035  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:23.025  1035  1870 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:56:23.025  1836  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:23.025  3439  3454 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:23.025  1836  1852 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:56:23.025  3439  3454 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:56:23.025  6918  6933 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:23.025  1586  1605 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:23.025  1586  1605 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:56:23.026   313  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:23.026   313  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:23.026  1836  3964 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:23.026  1836  3964 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:23.026  1586  2522 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:23.026  1586  2522 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:23.026  6918  6918 V ToneGenerator: Create Track: 0xb4928a80
08-31 15:56:23.026  6918  6918 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 15:56:23.026  6918  6918 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 15:56:23.026  6918  6933 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 15:56:23.026  6918  6933 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-31 15:56:23.026  6918  6933 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 15:56:23.027   313  1766 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 15:56:23.027   313  1766 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 15:56:23.027   313  1766 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:56:23.027   313  1766 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:56:23.027  1035  1639 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:23.027  1035  1639 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:23.028  3439  3455 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:23.028  3439  3455 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:23.028   313  1369 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 15:56:23.029   313   313 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 15:56:23.029   313   313 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 15:56:23.029   313   313 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:56:23.029   313   313 V AudioPolicyManagerEx: getOutput() returns output 2
,08-31 15:56:23.029  6918  6918 V AudioSystem: getLatency() output 2, latency 50
08-31 15:56:23.029  6918  6918 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 15:56:23.029  6918  6918 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 15:56:23.029   313  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 15:56:23.029   313  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 15:56:23.029   313  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 15:56:23.029   313  1370 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 15:56:23.029   313  1370 V AudioFlinger: createTrack() lSessionId: 22
08-31 15:56:23.030  6918  6918 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 15:56:23.031   313  1370 V AudioFlinger: acquiring 22 from 6918, for 6918
08-31 15:56:23.031   313  1370 V AudioFlinger:  added new entry for 22
08-31 15:56:23.031  6918  6918 V ToneGenerator: ToneGenerator INIT OK, time: 218246
08-31 15:56:23.031  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.032  6918  7409 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 15:56:23.032  6918  7409 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:56:23.032  6918  7409 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:56:23.032  6918  7409 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 15:56:23.033   313   313 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6918
08-31 15:56:23.033   313   313 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 15:56:23.033   313   313 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 15:56:23.033   313   313 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 15:56:23.033   313   313 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 15:56:23.033   313   313 V voice   : voice_set_parameters: exit with code(0)
08-31 15:56:23.033   313   313 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 15:56:23.033   313   313 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 15:56:23.033   313   313 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 15:56:23.033   313   313 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 15:56:23.033   313   313 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 15:56:23.033   313   313 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 15:56:23.033  6918  7409 V ToneGenerator: ToneGenerator destructor
08-31 15:56:23.033  6918  7409 V ToneGenerator: stopTone
08-31 15:56:23.033  6918  7409 V ToneGenerator: Delete Track: 0xb4928a80
08-31 15:56:23.037  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.037  6918  7409 V AudioTrack: ~AudioTrack, releasing session id from 6918 on behalf of 6918
08-31 15:56:23.037   313  1369 V AudioFlinger: releasing 22 from 6918 for 6918
08-31 15:56:23.037   313  1369 V AudioFlinger:  decremented refcount to 0
08-31 15:56:23.037   313  1369 V AudioFlinger: purging stale effects
08-31 15:56:23.037   313  1369 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 15:56:23.037  6918  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:23.038   313  1369 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 15:56:23.038   313  1369 V AudioFlinger: PlaybackThread::Track destructor
08-31 15:56:23.038   313  1274 V AudioPolicyService: AudioCommandThread() waking up
08-31 15:56:23.038   313  1369 V AudioFlinger:, removeClient_l() pid 6918, calling pid 313
08-31 15:56:23.038   313  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 15:56:23.038   313  1274 V AudioPolicyManager: releaseOutput() 2
08-31 15:56:23.038   313  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 15:56:23.039  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:23.039  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:23.040  6918  6918 D A2dpService: Received start request. Starting profile...
08-31 15:56:23.040  6918  6918 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 15:56:23.041  6918  6918 V Avrcp   : make
08-31 15:56:23.042  6918  6918 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 15:56:23.042  6918  6918 I bluedroid-qcom: get_profile_interface avrcp
,08-31 15:56:23.047  6918  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:23.050  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.053  6918  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:23.055  6918  6918 V AudioManager: registerRemoteController: size of Media player list: 0
,08-31 15:56:23.057  6918  6918 E AudioManager: No RCC entry present to update
08-31 15:56:23.057  6918  6918 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 15:56:23.061  6918  6918 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 15:56:23.062  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 15:56:23.062  6918  6918 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 15:56:23.065  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 15:56:23.066  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 15:56:23.066  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.066  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 15:56:23.066  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 15:56:23.077  6918  7387 V LGMDMManager: Create singleton instance
08-31 15:56:23.079  6918  7387 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 15:56:23.123  6983  6983 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 15:56:23.144  6983  6983 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d7530b1
08-31 15:56:23.144  6983  6983 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 15:56:23.144  6983  6983 D AppUp4:CustFacade: isPhone : true
08-31 15:56:23.145  6983  6983 D AppUp4:CustModeStarterReceiver: begin check event
08-31 15:56:23.145  6983  6983 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 15:56:23.149  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.149  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:56:23.151  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:23.153  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 15:56:23.169  4292  7433 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:56:23.174  7019  7019 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 15:56:23.185  4292  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.185  4292  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 15:56:23.186  1035  2013 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:56:23.186  1035  2013 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:56:23.205  7019  7435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:56:23.209  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 15:56:23.209  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.209  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 15:56:23.209  6889  7437 W FormManager: Network not available. Please check & try again.
08-31 15:56:23.212  7061  7061 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 15:56:23.212  7061  7061 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 15:56:23.222  6889  7438 V FormManager: Network unavailable.
,08-31 15:56:23.227  7125  7125 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:23
08-31 15:56:23.229  6889  7438 V FormManager: Network unavailable.
08-31 15:56:23.233  7125  7125 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 15:56:23.233  7125  7125 D Weather.Utils: 2 : All the weather widget is gone.
08-31 15:56:23.234  7411  7411 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-31 15:56:23.234  7411  7411 W LG Account v2.2: No ProfileInfo entries
08-31 15:56:23.234  7411  7411 I LG Account v2.2: isEnabled: false
08-31 15:56:23.234  7411  7411 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 15:56:23.235  7125  7125 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 15:56:23.235  7411  7411 I Feature : [Lifetracker]Country: EU
08-31 15:56:23.235  7411  7411 I Feature : [Lifetracker]Operator: OPEN
08-31 15:56:23.235  7411  7411 I Feature : [Lifetracker]Ranking support: false
08-31 15:56:23.235  7125  7125 D WeatherAncestor: connectivity changed - connection : true
08-31 15:56:23.235  7411  7411 I Feature : [Lifetracker]Comfort support: false
08-31 15:56:23.235  7125  7125 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a398917
08-31 15:56:23.235  7411  7411 I Feature : [Lifetracker]Accessory: true
08-31 15:56:23.235  7411  7411 I Feature : [Lifetracker]Health device: true
08-31 15:56:23.235  7411  7411 I Feature : [Lifetracker]Extra Pedometer: false
08-31 15:56:23.235  7411  7411 I Feature : [Lifetracker]Blood glucose device: false
08-31 15:56:23.235  7411  7411 I Feature : [Lifetracker]Device Number: 3
08-31 15:56:23.236  7125  7125 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 15:56:23.238  7125  7125 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 15:56:23.238  7125  7125 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 15:56:23.238  7125  7125 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 15:56:23.238  7125  7125 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:23
08-31 15:56:23.240  1035  1559 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 15:56:23.244  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 15:56:23.247  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 15:56:23.248  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 15:56:23.248  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 15:56:23.248  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 15:56:23.248  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:56:23.248  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 15:56:23.248  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 15:56:23.248  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 15:56:23.248  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:56:23.248  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 15:56:23.248  6777  6777 D BluetoothPermissionRequest: onReceive
08-31 15:56:23.248  6918  6918 I BluetoothA2dpServiceJni: classInitNative
08-31 15:56:23.248  6918  6918 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:56:23.248  6918  6918 D A2dpStateMachine: make
,08-31 15:56:23.250  6918  6918 I bluedroid-qcom: get_profile_interface a2dp
08-31 15:56:23.250  6918  7443 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 15:56:23.251  6918  6918 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:56:23.251  6918  6918 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 15:56:23.252  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.252  6918  7442 D A2dpStateMachine: Enter Disconnected: -2
08-31 15:56:23.252  6918  6918 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 15:56:23.253  6918  6918 D HeadsetStateMachine: Proxy object connected
08-31 15:56:23.254  6918  6918 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 15:56:23.254  6918  6918 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 15:56:23.255  6777  6777 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:56:23.255  6918  6918 D HidService: Received start request. Starting profile...
08-31 15:56:23.255  6918  6918 I bluedroid-qcom: get_profile_interface hidhost
08-31 15:56:23.255  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.255  6918  6918 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:56:23.257  6918  6918 D HealthService: Received start request. Starting profile...
08-31 15:56:23.258  6918  6918 I bluedroid-qcom: get_profile_interface health
08-31 15:56:23.258  6918  6918 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:56:23.258  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.261  6918  6918 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:56:23.262  6918  7409 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 15:56:23.262  6918  6918 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 15:56:23.263  6918  6918 D PanService: Received start request. Starting profile...
,08-31 15:56:23.263  6918  6918 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 15:56:23.263  6918  6918 I bluedroid-qcom: get_profile_interface pan
08-31 15:56:23.264  6918  7409 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 15:56:23.264  6918  7409 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 15:56:23.268  6918  6918 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 15:56:23.268  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.268  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 15:56:23.269  6918  6918 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 15:56:23.270  6393  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 15:56:23.272  6918  6918 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:56:23.272  6918  6918 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:56:23.272  6918  6918 D BtGatt.GattService: start()
08-31 15:56:23.272  6918  6918 I bluedroid-qcom: get_profile_interface gatt
08-31 15:56:23.272  6918  6918 D BtGatt.AdvertiseManager: advertise manager created
08-31 15:56:23.277  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.278  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.278  6918  6918 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 15:56:23.279  6918  6918 V BluetoothMapService: BluetoothMapBinder()
08-31 15:56:23.279  6918  6918 D BluetoothMapService: Received start request. Starting profile...
08-31 15:56:23.279  6918  6918 D BluetoothMapService: start()
,08-31 15:56:23.282  6918  6918 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 15:56:23.282  6918  6918 D BluetoothMapEmailAppObserver: createReceiver()
08-31 15:56:23.283  6918  6918 D BluetoothMapEmailAppObserver: initObservers()
08-31 15:56:23.283  6918  6918 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 15:56:23.284  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.288  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.291  6918  6918 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 15:56:23.293  6918  6918 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:56:23.295  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 15:56:23.295  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.295  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 15:56:23.295  6983  6983 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 15:56:23.297  6918  6918 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:56:23.297  6918  6918 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 15:56:23.297  6983  6983 I AppUp4:CustModeStarterReceiver: onReceive
08-31 15:56:23.299  6918  6918 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:56:23.300  6983  6983 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d7530b1
08-31 15:56:23.300  6983  6983 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 15:56:23.300  6983  6983 D AppUp4:CustFacade: isPhone : true
08-31 15:56:23.301  6983  6983 D AppUp4:CustModeStarterReceiver: begin check event
08-31 15:56:23.301  6983  6983 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 15:56:23.301  6918  6918 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 15:56:23.301  6918  6918 V BluetoothMapService: Handler(): got msg=1
08-31 15:56:23.302  6918  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 15:56:23.302  6918  7387 I bluedroid-qcom: enable
08-31 15:56:23.303  6918  7387 I bt_hci_bdroid: init
08-31 15:56:23.303  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.303  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:56:23.304  6918  7387 I bt_vendor: bt-vendor : init
08-31 15:56:23.304  6918  7387 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 15:56:23.304  6918  7387 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 15:56:23.304  6918  7387 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 15:56:23.304  6918  7387 D bt_userial_mct: userial_init
08-31 15:56:23.304  6918  7450 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 15:56:23.304  6918  7387 D bt_hci_bdroid: set_power 1
08-31 15:56:23.304  6918  7387 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 15:56:23.304  6918  7387 I bt_vendor: Starting hciattach daemon
08-31 15:56:23.304  6918  7387 I bt_vendor: try to set true
08-31 15:56:23.305  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:23.306  6918  7450 I bt-btu  : btu_task pending for preload complete event
,08-31 15:56:23.295  7453  7453 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:23.295  7453  7453 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:23.309  6918  6918 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:23.309  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:23.310  6918  6918 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:56:23.310  6918  6918 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:56:23.311  6918  6918 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:56:23.311  6918  6918 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:56:23.311  6918  6918 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 15:56:23.315  4292  7454 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 15:56:23.316  7019  7019 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 15:56:23.326  4292  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.327  4292  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:56:23.328  7019  7457 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:56:23.332  3439  3439 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 15:56:23.332  3439  3439 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:23.332  7456  7456 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
08-31 15:56:23.332  3439  3439 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 15:56:23.334  7061  7061 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 15:56:23.334  7061  7061 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 15:56:23.342  7125  7125 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:23
,08-31 15:56:23.343  7125  7125 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 15:56:23.343  7125  7125 D Weather.Utils: 2 : All the weather widget is gone.
08-31 15:56:23.343  7125  7125 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 15:56:23.343  7125  7125 D WeatherAncestor: connectivity changed - connection : true
08-31 15:56:23.343  7125  7125 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a398917
08-31 15:56:23.344  7125  7125 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 15:56:23.344  7125  7125 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 15:56:23.344  7125  7125 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 15:56:23.344  7125  7125 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 15:56:23.344  7125  7125 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:56:23
08-31 15:56:23.352  6889  7462 V FormManager: Network unavailable.
08-31 15:56:23.365  6889  7462 V FormManager: Network unavailable.
,08-31 15:56:23.368  6889  7461 W FormManager: Network not available. Please check & try again.
08-31 15:56:23.388  7467  7467 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 15:56:23.400  7468  7468 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 15:56:23.423  7470  7470 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 15:56:23.446  7471  7471 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 15:56:23.462  7472  7472 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 15:56:23.475  7473  7473 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 15:56:23.499  7475  7475 I libmdmdetect: ESOC framework not supported
08-31 15:56:23.500  7475  7475 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 15:56:23.510  7475  7475 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 15:56:23.510  7475  7475 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 15:56:23.511  7475  7475 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 15:56:23.511  7475  7475 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 15:56:23.511  7475  7475 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 15:56:23.511  7475  7475 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 15:56:23.511  7475  7475 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 15:56:23.565  7475  7476 E QC-QMI  : qmi_client [7475] 14: failed to locate client data
,08-31 15:56:23.565   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 15:56:23.566   479   479 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-31 15:56:23.612  7477  7477 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 15:56:23.629  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 15:56:23.650  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7400
08-31 15:56:23.651  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7403
08-31 15:56:23.654  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7453
08-31 15:56:23.654  1035  1113 W ProcessCpuTracker: Skipping unknown process pid 7477
,08-31 15:56:23.656  6918  7387 I bt_vendor: bluetooth satus is on
08-31 15:56:23.656  6918  7387 D bt_hci_bdroid: preload
08-31 15:56:23.657  6918  7452 D bt_userial_mct: userial_open(port:0)
08-31 15:56:23.657  6918  7452 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 15:56:23.660  6918  7452 I bt_vendor: Done intiailizing UART
08-31 15:56:23.661  6918  7452 I bt_vendor: Done intiailizing UART
08-31 15:56:23.661  6918  7452 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 15:56:23.661  6918  7452 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 15:56:23.661  6918  7483 D bt_userial_mct: Entering userial_read_thread()
08-31 15:56:23.662  6918  7450 I bt-btu  : btu_task received preload complete event
08-31 15:56:23.662  6918  7450 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 15:56:23.662  6918  7450 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 15:56:23.665  6918  7450 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 15:56:23.668  6918  7450 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 15:56:23.718  6918  7450 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 15:56:23.718  6918  7450 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ed061 ,
08-31 15:56:23.718  6918  7450 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ed061 
,08-31 15:56:23.739  6918  7391 E bt-btif : Calling BTA_HhEnable
08-31 15:56:23.739  6918  7391 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 15:56:23.739  6918  7450 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-31 15:56:23.740  6918  7391 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 15:56:23.740  6918  7450 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 15:56:23.740  6918  7450 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 15:56:23.740  6918  7450 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 15:56:23.740  6918  7450 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 15:56:23.742  6918  7391 D BluetoothAdapterProperties: Name is: G3
08-31 15:56:23.745  6918  7391 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:56:23.745  6918  7391 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:56:23.746  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 15:56:23.746  6918  7391 D bt_hci_bdroid: postload
08-31 15:56:23.746  6918  7452 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:56:23.747  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 15:56:23.747  6918  7391 D bte_conf: Device ID record 1 : primary
08-31 15:56:23.747  6918  7391 D bte_conf:   vendorId            = 00c4
08-31 15:56:23.747  6918  7391 D bte_conf:   vendorIdSource      = 0001
08-31 15:56:23.748  6918  7391 D bte_conf:   product             = 13a1
08-31 15:56:23.748  6918  7391 D bte_conf:   version             = 1000
08-31 15:56:23.748  6918  7391 D bte_conf:   clientExecutableURL = 
08-31 15:56:23.748  6918  7391 D bte_conf:   serviceDescription  = 
08-31 15:56:23.748  6918  7391 D bte_conf:   documentationURL    = 
08-31 15:56:23.748  6918  7391 D bte_conf: bte_load_did_conf no section named DID2.
08-31 15:56:23.751  6918  7450 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 15:56:23.752  6918  7452 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:56:23.752  6918  7452 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:56:23.752  6918  7452 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:56:23.753  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:56:23.745  7485  7485 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:23.745  7485  7485 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 15:56:23.760  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:23.762  6918  7483 E bt_mct  : hci lib postload completed
08-31 15:56:23.763  6918  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 15:56:23.763  6918  7387 D BluetoothAdapterProperties: ScanMode =  20
08-31 15:56:23.764  6918  7387 D BluetoothAdapterProperties: State =  11
08-31 15:56:23.764  6918  7387 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 15:56:23.765  6918  7387 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 15:56:23.765  6918  7387 D BluetoothAdapterProperties: Setting state to 12
08-31 15:56:23.765  6918  7387 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 15:56:23.766  1035  1117 D BluetoothManagerService: Message: 60
08-31 15:56:23.766  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 15:56:23.766  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-31 15:56:23.766  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:56:23.767  6918  7387 I BluetoothAdapterState: Entering On State
08-31 15:56:23.770  6918  7391 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 15:56:23.770  6918  7391 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 15:56:23.773  1035  1035 D BluetoothHeadset: Proxy object connected
08-31 15:56:23.773  6777  6794 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 15:56:23.783  6918  7387 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 15:56:23.784  6918  7387 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
,08-31 15:56:23.784  6918  7387 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 15:56:23.784  6918  7450 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:23.784  6918  7450 W bt-smp  : Plain text(LSB ~ MSB) = cd 1a 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:23.784  6918  7450 W bt-smp  : Encrypted text(LSB ~ MSB) = 4a da 2b 0d c6 36 bc 9f 24 77 c0 9e 42 2a d0 75 
08-31 15:56:23.784  6918  7450 W bt-btm  : Stopping oneshot timer
08-31 15:56:23.787  6918  7387 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 15:56:23.790  6777  6808 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 15:56:23.793  1836  2449 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:56:23.794  6777  6777 D BluetoothInputDevice: Proxy object connected
08-31 15:56:23.794  6777  6777 D HidProfile: Bluetooth service connected
08-31 15:56:23.796  1836  1836 D BluetoothHeadset: Proxy object connected
08-31 15:56:23.796  6918  7391 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:56:23.796  6918  7391 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-31 15:56:23.799  6777  6808 D BluetoothMap: onBluetoothStateChange: up=true
08-31 15:56:23.802  1836  2425 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:56:23.803  6918  7450 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:23.803  6918  7450 W bt-smp  : Plain text(LSB ~ MSB) = 81 4c 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:23.803  6918  7450 W bt-smp  : Encrypted text(LSB ~ MSB) = ca 7b ac 75 54 1f a0 ad 43 05 99 15 7f 56 13 ca 
08-31 15:56:23.803  6918  7450 W bt-btm  : Stopping oneshot timer
08-31 15:56:23.805  6777  6777 D BluetoothMap: Proxy object connected
08-31 15:56:23.805  6777  6777 D MapProfile: Bluetooth service connected
08-31 15:56:23.805  6777  6777 D BluetoothMap: getConnectedDevices()
08-31 15:56:23.806  6918  6933 V BluetoothMapService: getConnectedDevices()
08-31 15:56:23.807  1836  1836 D BluetoothHeadset: Proxy object connected
08-31 15:56:23.808  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:56:23.808  6777  6808 D BluetoothPan: onBluetoothStateChange on: true
08-31 15:56:23.809  6777  6808 D BluetoothPan: onBluetoothStateChange call bindService
,08-31 15:56:23.812  1035  1035 D BluetoothA2dp: Proxy object connected
08-31 15:56:23.815  6918  7450 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:23.815  6918  7450 W bt-smp  : Plain text(LSB ~ MSB) = 3c 23 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:23.815  6918  7450 W bt-smp  : Encrypted text(LSB ~ MSB) = 05 db 7c 51 0c 17 8a 24 12 5d cb 12 32 59 d9 a9 
08-31 15:56:23.815  6918  7450 W bt-btm  : Stopping oneshot timer
08-31 15:56:23.816  1836  3965 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:56:23.817  6918  7387 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 15:56:23.817  6777  6777 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:56:23.817  6777  6777 D PanProfile: Bluetooth service connected
08-31 15:56:23.819  1836  1836 D BluetoothHeadset: Proxy object connected
08-31 15:56:23.820  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 15:56:23.820  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 15:56:23.822  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-31 15:56:23.823  1035  1117 D BluetoothManagerService: Message: 40
,08-31 15:56:23.823  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 15:56:23.824  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:23.824  1925  2126 D LGBluetoothAPIService: Message: 1
08-31 15:56:23.824  1925  2126 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 15:56:23.824  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:56:23.831  6692  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 15:56:23.835  7491  7491 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 15:56:23.835  6918  7450 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:23.835  6918  7450 W bt-smp  : Plain text(LSB ~ MSB) = 25 18 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:23.835  6918  7450 W bt-smp  : Encrypted text(LSB ~ MSB) = ad 29 0b 0a 80 18 b5 27 3d e0 67 0c 22 bf ef 5d 
08-31 15:56:23.835  6918  7450 W bt-btm  : Stopping oneshot timer
08-31 15:56:23.837  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:23.837  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:23.837  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:23.837  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:23.837  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:23.837  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:23.837  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:23.837  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:56:23.839  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:23.843  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:23.843  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:23.843  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:23.843  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:23.843  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:23.843  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:23.843  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:23.843  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:23.845  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:23.847  6918  7450 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:23.847  6918  7450 W bt-smp  : Plain text(LSB ~ MSB) = 64 d0 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:23.847  6918  7450 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e f2 30 18 37 2d d3 cc 49 5c a5 4f 6e b9 fe 3a 
08-31 15:56:23.847  6918  7450 W bt-btm  : Stopping oneshot timer
,08-31 15:56:23.849  6918  6918 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:23.849  6918  6918 D BluetoothMapService: STATE_ON
08-31 15:56:23.850  6777  6777 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 15:56:23.852  6918  6918 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 15:56:23.853  6918  6918 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 15:56:23.853  1035  1117 D BluetoothManagerService: Message: 30
08-31 15:56:23.854  1925  2126 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 15:56:23.854  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 15:56:23.854  1925  2126 D LGBluetoothAPIService: Message: 100
08-31 15:56:23.854  1925  2126 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 15:56:23.856  6777  6777 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 15:56:23.862  1035  1117 D BluetoothManagerService: Message: 30
,08-31 15:56:23.869  6777  6777 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 15:56:23.871  6777  6777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 15:56:23.873  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.873  6918  6918 V BluetoothPbapService: Pbap Service onCreate
08-31 15:56:23.873  6918  6918 V BluetoothPbapService: Starting PBAP service
08-31 15:56:23.875  6777  6777 D BluetoothA2dp: Proxy object connected
08-31 15:56:23.875  6918  6918 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 15:56:23.875  6918  6918 V BluetoothPbapService: Pbap Service onBind
08-31 15:56:23.877  6777  6777 D A2dpProfile: Bluetooth service connected
,08-31 15:56:23.881  6918  6918 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:23.881  6918  6918 V BluetoothPbapService: state: 12
08-31 15:56:23.881  6918  6918 V BluetoothMapService: Handler(): got msg=1
08-31 15:56:23.882  6918  6918 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 15:56:23.882  6918  6918 V BluetoothPbapService: Handler(): got msg=1
08-31 15:56:23.883  6777  6777 D BluetoothHeadset: Proxy object connected
08-31 15:56:23.884  6777  6777 D HeadsetProfile: Bluetooth service connected
08-31 15:56:23.884  6918  6918 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 15:56:23.885  6918  6918 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:56:23.885  6918  7497 D BluetoothMapMasInstance: MAS initSocket()
08-31 15:56:23.885  6918  6918 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:23.885  6918  6918 V BluetoothPbapReceiver: ***********state = 12
08-31 15:56:23.886  6918  7497 D BluetoothMapMasInstance:   masId = 00
08-31 15:56:23.886  6918  7497 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 15:56:23.886  6918  7497 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 15:56:23.886  6918  7497 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 15:56:23.888  6918  7498 V BluetoothPbapService: Pbap Service initSocket
08-31 15:56:23.889  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:56:23.889  1035  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:23.890  1035  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:23.890  2203  2203 D c       : Getting all permits...
08-31 15:56:23.890  2203  2203 D a       : Opening database...
08-31 15:56:23.892  6918  7497 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:23.894  6918  7391 D BluetoothAdapterProperties: Scan Mode:21
08-31 15:56:23.894  6918  7391 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-31 15:56:23.894  6918  7497 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 15:56:23.895  6918  7497 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 15:56:23.895  6918  7497 D BluetoothMapMasInstance: Accepting socket connection...
08-31 15:56:23.895  2203  2203 D a       : Opening database auth.proximity.permit_store...
08-31 15:56:23.896  6918  7498 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:23.897  2203  2203 D a       : Closing database...
08-31 15:56:23.897  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:23.899  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:23.900  6918  7498 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 15:56:23.900  6918  7498 V BluetoothPbapService: Succeed to create listening socket 
08-31 15:56:23.900  6918  7498 V BluetoothPbapService: Accepting socket connection...
08-31 15:56:23.907  6777  6777 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:56:23.908  6777  6777 D BluetoothPbap: Proxy object connected
08-31 15:56:23.909  6777  6777 D PbapServerProfile: Bluetooth service connected
08-31 15:56:23.913  6777  6777 D BluetoothPermissionRequest: onReceive
08-31 15:56:23.915  6777  6777 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 15:56:23.917  6777  6777 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:56:23.921  6918  6918 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-31 15:56:23.922  6918  6918 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 15:56:23.929  6918  6918 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-31 15:56:23.950  6918  6918 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 15:56:23.950  6918  6918 V BtOppService: onCreate
08-31 15:56:23.954  6918  6918 V BluetoothOppNotification: send message
08-31 15:56:23.957  6918  6918 V BtOppService: Starting RfcommListener
08-31 15:56:23.961  6918  6918 D BluetoothOppPreference: Dumping Names:  
08-31 15:56:23.961  6918  6918 D BluetoothOppPreference: {}
08-31 15:56:23.961  6918  6918 D BluetoothOppPreference: Dumping Channels:  
08-31 15:56:23.961  6918  6918 D BluetoothOppPreference: {}
08-31 15:56:23.962  6918  6918 V BtOppService: onStartCommand
08-31 15:56:23.965  6918  6918 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:23.965  6918  6918 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 15:56:23.966  6918  7506 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-31 15:56:23.969  6918  6918 V BluetoothOppNotification: new notify threadi!
08-31 15:56:23.975  6918  6918 V BluetoothOppNotification: send delay message
08-31 15:56:23.975  6918  7506 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 15:56:23.975  6918  6918 V BtOppService: start RfcommListener
08-31 15:56:23.976  6918  7503 V BtOppService: Deleted complete outbound shares, number =  0
,08-31 15:56:23.977  6918  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 15:56:23.979  6918  6918 V BtOppService: RfcommListener started
08-31 15:56:23.981  6918  7506 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b51ad00 on behalf of 
08-31 15:56:23.982  6918  7503 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 15:56:23.983  6918  7503 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 15:56:23.984  6918  7503 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@327cd939 on behalf of 
08-31 15:56:23.985  6918  7508 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 15:56:23.985  6918  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@46e0b7e on behalf of 
08-31 15:56:23.986  1035  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:23.987  6918  7508 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:23.989  6918  7508 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-31 15:56:23.989  6918  7508 V BtOppRfcommListener: Started RFCOMM listener....
,08-31 15:56:23.989  6918  7508 I BtOppRfcommListener: Accept thread started.
08-31 15:56:23.989  6918  7508 V BtOppRfcommListener: Accepting connection...
08-31 15:56:23.993  6918  7506 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-31 15:56:23.994  6918  7507 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 15:56:23.998  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:23.998  6918  6918 V BluetoothFtpService: Ftp Service onCreate
08-31 15:56:23.998  6918  6918 I BluetoothFtpService: Ftp Service onCreate
08-31 15:56:23.998  6918  6918 V BluetoothFtpService: Ftp Service onStartCommand
08-31 15:56:23.999  6918  6918 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:23.999  6918  6918 V BluetoothFtpService: Starting Listening on sockets
08-31 15:56:24.000  6918  6918 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-31 15:56:24.000  6918  6918 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:56:24.000  6918  6918 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:56:24.000  6918  6918 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:24.000  6918  6918 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 15:56:24.000  6918  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 15:56:24.000  6918  6918 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 15:56:24.002  6918  6918 V BtOppService: ContentObserver received notification
08-31 15:56:24.003  7154  7187 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-31 15:56:24.004  6918  6918 V BtOppService: ContentObserver received notification
08-31 15:56:24.004  6918  6918 V BluetoothFtpService: Handler(): got msg=1
08-31 15:56:24.005  6918  6918 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 15:56:24.005  6918  7511 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 15:56:24.005  6918  6918 V BluetoothFtpService: Ftp Service initSocket
08-31 15:56:24.005  6918  7511 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 15:56:24.005  6918  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19a4992c on behalf of 
08-31 15:56:24.006  6918  7511 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35c8cff5 on behalf of 
,08-31 15:56:24.007  6918  7511 V BluetoothOppNotification: update too frequent, put in queue
08-31 15:56:24.007  6918  7507 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 15:56:24.010  6918  7507 V BluetoothOppNotification: outbound notification was removed.
08-31 15:56:24.010  6918  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 15:56:24.010  6918  7511 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 15:56:24.011  1035  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:24.012  6918  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@225b618a on behalf of 
08-31 15:56:24.012  6918  7507 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 15:56:24.013  6918  6918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:24.014  6918  7507 V BluetoothOppNotification: inbound notification was removed.
08-31 15:56:24.014  6918  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 15:56:24.015  6918  6918 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 15:56:24.016  6918  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@335cc3fb on behalf of 
,08-31 15:56:24.016  6918  7513 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 15:56:24.035  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:24.035  6918  6918 V BluetoothSapService: Sap Service onCreate
08-31 15:56:24.037  6918  6918 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:24.037  6918  6918 V BluetoothSapService: state: 12
08-31 15:56:24.037  6918  6918 V BluetoothSapService: Starting SAP server process
,08-31 15:56:24.040  6918  6918 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 15:56:24.025  7514  7514 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:24.025  7514  7514 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:24.041  6918  7515 V BluetoothSapService: Sap Service initRfcommSocket
08-31 15:56:24.042  1035  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:24.043  6918  7515 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:24.044  6918  7515 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 15:56:24.044  6918  7515 V BluetoothSapService: Succeed to create listening socket 
08-31 15:56:24.044  6918  7515 V BluetoothSapService: Accepting socket connection...
08-31 15:56:24.053  7514  7514 V BT_SAP  : Event pipe created
08-31 15:56:24.053  7514  7514 V BT_SAP  : create_server_socket qcom.sap.server
08-31 15:56:24.054  7514  7514 V BT_SAP  : created socket fd 6
,08-31 15:56:24.822  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:24.822  1035  1520 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:56:24.849  1035  1521 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 15:56:24.860  1035  1521 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-31 15:56:24.977  6918  6918 V BluetoothOppNotification: new notify threadi!
,08-31 15:56:24.980  6918  6918 V BluetoothOppNotification: send delay message
08-31 15:56:24.983  6918  7525 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 15:56:24.986  1035  1051 I ActivityManager: Killing 7316:com.lge.bnr/1000 (adj 15): empty #17
08-31 15:56:25.003  6918  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36a9a4d7 on behalf of 
08-31 15:56:25.003  6918  7525 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 15:56:25.009  6918  7525 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 15:56:25.010  6918  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bbee1c4 on behalf of 
08-31 15:56:25.011  6918  7525 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 15:56:25.012  6918  7525 V BluetoothOppNotification: outbound notification was removed.
08-31 15:56:25.013  6918  7525 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 15:56:25.014  6918  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@aa808ad on behalf of 
08-31 15:56:25.014  6918  7525 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-31 15:56:25.018  6918  7525 V BluetoothOppNotification: inbound notification was removed.
08-31 15:56:25.019  6918  7525 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 15:56:25.055  1035  1978 W libprocessgroup: failed to open /acct/uid_1000/pid_7316/cgroup.procs: No such file or directory
,08-31 15:56:25.083  1035  1995 I ActivityManager: Killing 6588:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-31 15:56:25.183  1035  1559 I art     : Explicit concurrent mark sweep GC freed 97781(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.410ms total 156.853ms
,08-31 15:56:25.186  6918  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1efe97e2 on behalf of 
08-31 15:56:25.194  6851  6851 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-31 15:56:25.196  6851  6851 W System.err: android.os.DeadObjectException
,08-31 15:56:25.196  6851  6851 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 15:56:25.196  6851  6851 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-31 15:56:25.196  6851  6851 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 15:56:25.196  6851  6851 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 15:56:25.196  6851  6851 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 15:56:25.196  6851  6851 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 15:56:25.196  6851  6851 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:56:25.196  6851  6851 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:56:25.196  6851  6851 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-31 15:56:25.196  6851  6851 W System.err: ,	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-31 15:56:25.196  6851  6851 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:56:25.196  6851  6851 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:56:25.196  6851  6851 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-31 15:56:25.196  6851  6851 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704),
08-31 15:56:25.196  6851  6851 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 15:56:25.196  6851  6851 W System.err: android.os.DeadObjectException
08-31 15:56:25.197  6851  6851 W System.err: ,	at android.os.BinderProxy.transactNative(Native Method)
08-31 15:56:25.197  6851  6851 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 15:56:25.197  6851  6851 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 15:56:25.197  6851  6851 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-31 15:56:25.197  6851  6851 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 15:56:25.197  6851  6851 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 15:56:25.197  6851  6851 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:56:25.197  6851  6851 W System.err: ,	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:56:25.197  6851  6851 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 15:56:25.197  6851  6851 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 15:56:25.197  6851  6851 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:56:25.197  6851  6851 W System.err: ,	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:56:25.197  6851  6851 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 15:56:25.197  6851  6851 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 15:56:25.197  6851  6851 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,08-31 15:56:25.197  6851  6851 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-31 15:56:25.296  1035  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_6588/cgroup.procs: No such file or directory
08-31 15:56:25.297  1035  1906 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-31 15:56:25.326  6851  6851 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 15:56:25.326  6851  6851 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-31 15:56:25.383  1035  1051 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7526 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 15:56:25.383  6851  6851 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 15:56:25.461  7526  7526 D UEI.SmartControl: Quickset Services start...
08-31 15:56:25.463  7526  7526 I UEI.SmartControl: Manufacture = LGE
08-31 15:56:25.464  7526  7526 D UEI.SmartControl: Id = LGNevo
,08-31 15:56:25.468  7526  7526 D UEI.SmartControl: File observer start...
08-31 15:56:25.469  7526  7526 E UEI.SmartControl: IR Port is disabled: false
08-31 15:56:25.469  7526  7526 D UEI.SmartControl: Starting file observer...
08-31 15:56:25.469  7526  7526 D UEI.SmartControl: Extracting JNI libs...
08-31 15:56:25.469  7526  7526 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 15:56:25.582  7526  7526 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 15:56:25.582  7526  7526 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 15:56:25.582  7526  7526 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 15:56:25.622  7526  7526 I UEI.SmartControl: --- Selecting new region: 6
,08-31 15:56:25.625  7526  7526 I UEI.SmartControl: Model = LG-D855
,08-31 15:56:25.627  7526  7526 D UEI.SmartControl: QS Service created
08-31 15:56:25.643  7526  7526 I UEI.SmartControl: Service initServices...
08-31 15:56:25.647  7526  7526 D UEI.SmartControl: QS start get config
,08-31 15:56:25.702  7526  7526 D UEI.SmartControl: Loading JNI Libs...
,08-31 15:56:25.808  1035  1716 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:56:25.808  1035  1716 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2cbd299 mBinding = false
,08-31 15:56:25.834  1035  1117 D BluetoothManagerService: Message: 2
,08-31 15:56:25.838  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:56:25.838  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:56:25.838  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 15:56:25.838  1035  1117 D BluetoothManagerService: Sending off request.
08-31 15:56:25.841  6918  7492 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 15:56:25.841  6918  7387 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 15:56:25.841  6918  7387 D BluetoothAdapterProperties: Setting state to 13
08-31 15:56:25.841  6918  7387 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 15:56:25.842  6918  7387 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 15:56:25.842  6918  7387 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 15:56:25.845  6918  7391 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:56:25.845  6918  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 15:56:25.847  6918  7498 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:25.847  6918  7508 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:25.847  6918  7513 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:25.848  6918  7515 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:25.848  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 15:56:25.848  6918  7450 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 15:56:25.850  6918  7497 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 15:56:25.850  6918  7497 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:56:25.850  6918  7497 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 15:56:25.850  6918  7497 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 15:56:25.850  6918  7497 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 15:56:25.850  6918  7497 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 15:56:25.850  6918  7497 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 15:56:25.850  6918  7497 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 15:56:25.851  6918  7387 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 15:56:25.853  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:25.853  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:25.855  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:25.855  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:25.855  6918  7450 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:56:25.855  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:25.855  6918  7450 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:56:25.855  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:25.855  6918  7450 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:56:25.855  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 15:56:25.855  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 15:56:25.855  6918  7450 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 15:56:25.856  1035  1117 D BluetoothManagerService: Message: 60
08-31 15:56:25.856  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 15:56:25.856  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 15:56:25.857  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:25.857  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:25.857  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:25.857  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:25.857  6692  6692 V io.jxco,re.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:25.857  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:25.857  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:25.857  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:25.857  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:25.858  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:56:25.859  6918  6918 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:25.860  6918  6918 D BluetoothMapService: STATE_TURNING_OFF
08-31 15:56:25.860  6777  6777 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-31 15:56:25.860  6918  6918 V BluetoothMapService: Handler(): got msg=4
08-31 15:56:25.860  6918  6918 D BluetoothMapService: MAP Service closeService in
08-31 15:56:25.860  6918  6918 D BluetoothMapMasInstance: MAP Service shutdown
08-31 15:56:25.860  6918  6918 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:56:25.860  6918  6918 V BluetoothMapService: MAP Service closeService out
08-31 15:56:25.860  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:25.860  6918  6918 V BtOppService: Receiver DISABLED_ACTION 
08-31 15:56:25.860  6918  6918 I BtOppRfcommListener: stopping Accept Thread
08-31 15:56:25.861  6918  6918 V BtOppRfcommListener: close mBtServerSocket
08-31 15:56:25.861  6918  6918 V BtOppRfcommListener: waiting for thread to terminate
08-31 15:56:25.861  6918  7508 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 15:56:25.861  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:25.861  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:25.861  6918  6918 V BtOppRfcommListener: done waiting for thread to terminate
08-31 15:56:25.862  6777  6777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 15:56:25.867  6918  6918 V BtOppService: onDestroy
,08-31 15:56:25.871  6918  6918 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-31 15:56:25.871  6918  6918 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:56:25.871  6918  6918 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:25.871  6918  6918 V BluetoothPbapReceiver: ***********state = 13
08-31 15:56:25.872  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:25.872  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:25.872  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:25.872  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:25.872  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:25.872  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:56:25.872  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:25.872  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:25.872  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:56:25.873  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:56:25.873  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:25.873  6918  6918 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 15:56:25.875  6918  6918 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:25.875  6918  6918 V BluetoothPbapService: state: 13
08-31 15:56:25.876  6918  6918 V BluetoothPbapService: Pbap Service closeService in
08-31 15:56:25.876  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:56:25.876  6918  6918 V BluetoothPbapService: successfully stopped pbap service
08-31 15:56:25.876  6918  6918 V BluetoothPbapService: Pbap Service closeService out
08-31 15:56:25.877  6918  6918 V BluetoothPbapService: Pbap Service onDestroy
08-31 15:56:25.877  6918  6918 V BluetoothPbapService: Pbap Service closeService in
08-31 15:56:25.877  6918  6918 V BluetoothPbapService: Pbap Service closeService out
08-31 15:56:25.877  6918  6918 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 15:56:25.878  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:25.878  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:25.880  6777  6777 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:56:25.880  6777  6777 D BluetoothPbap: Proxy object disconnected
08-31 15:56:25.881  6777  6777 D PbapServerProfile: Bluetooth service disconnected
,08-31 15:56:25.888  6777  6777 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 15:56:25.890  6777  6777 D BluetoothPermissionRequest: onReceive
08-31 15:56:25.890  6777  6777 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 15:56:25.894  6777  6777 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 15:56:25.896  6918  6918 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 15:56:25.896  6918  6918 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 15:56:25.896  6918  6918 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 15:56:25.898  6918  6918 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:25.899  6918  6918 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 15:56:25.899  6918  6918 V BluetoothFtpService: Ftp Service onStartCommand
08-31 15:56:25.899  6918  6918 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:25.899  6918  6918 V BluetoothFtpService: Ftp Service closeService
08-31 15:56:25.900  6918  6918 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 15:56:25.902  6918  6918 V BluetoothFtpService: successfully stopped ftp service
08-31 15:56:25.903  6918  6918 V BluetoothFtpService: Ftp Service onDestroy
08-31 15:56:25.903  6918  6918 V BluetoothFtpService: Ftp Service closeService
08-31 15:56:25.904  6918  6918 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:56:25.904  6918  6918 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:56:25.904  6918  6918 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:56:25.904  6918  6918 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:25.904  6918  6918 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 15:56:25.904  6918  6918 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 15:56:25.905  6918  6918 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:25.905  6918  6918 V BluetoothSapService: state: 13
08-31 15:56:25.905  6918  6918 V BluetoothSapService: Stopping SAP server process
08-31 15:56:25.905  6918  6918 V BluetoothSapService: Sap Service closeSapService in
08-31 15:56:25.905  6918  6918 V BluetoothSapService: Close listen Socket : 
08-31 15:56:25.906  6918  6918 V BluetoothSapService: Close rfcomm Socket : 
08-31 15:56:25.906  6918  6918 V BluetoothSapService: Close sapd  Socket : 
,08-31 15:56:25.912  6918  6918 V BluetoothSapService: Sap Service closeSapService out
08-31 15:56:25.912  6918  6918 V BluetoothSapService: Sap Service onDestroy
08-31 15:56:25.912  6918  6918 V BluetoothSapService: Sap Service closeSapService in
08-31 15:56:25.912  6918  6918 V BluetoothSapService: Close listen Socket : 
08-31 15:56:25.912  6918  6918 V BluetoothSapService: Close rfcomm Socket : 
08-31 15:56:25.912  6918  6918 V BluetoothSapService: Close sapd  Socket : 
08-31 15:56:25.915  6918  6918 V BluetoothSapService: Sap Service closeSapService out
08-31 15:56:26.163  7526  7526 I UEI.SmartControl: Supports setup maps: true
,08-31 15:56:26.168  7526  7526 D UEI.SmartControl: QS start statue = true Error code = 0
,08-31 15:56:26.168  7526  7526 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 15:56:26.168  7526  7526 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 15:56:26.168  7526  7526 I UEI.SmartControl: ### init IR Blaster...
,08-31 15:56:26.174  7526  7526 D serial_port: Configuring serial port
08-31 15:56:26.187  7526  7526 E UEI.SmartControl: UEIBLaster setting for 616
08-31 15:56:26.188  7526  7526 I UEI.SmartControl: Setting serial record hearder size = 2
,08-31 15:56:26.190  7526  7526 I UEI.SmartControl: configuring settings for MAXQ616
08-31 15:56:26.191  7526  7526 I UEI.SmartControl: Get version...
,08-31 15:56:26.211  7526  7567 D UEI.SmartControl: serial port data available: 21
,08-31 15:56:26.241  7526  7526 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-31 15:56:26.241  7526  7526 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 15:56:26.242  7526  7526 I UEI.SmartControl: QS saving settings...
,08-31 15:56:26.246  7526  7526 D UEI.SmartControl: IR Blaster version: 25672567
08-31 15:56:26.270  7526  7567 D UEI.SmartControl: serial port data available: 4
,08-31 15:56:26.307  7526  7576 I UEI.SmartControl: Device manager: loading config....
08-31 15:56:26.308  7526  7576 D UEI.SmartControl: ----------- loading internal config...
,08-31 15:56:26.317  7526  7526 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 15:56:26.320  7526  7526 E UEI.SmartControl: Services init done
08-31 15:56:26.321  7526  7526 D UEI.SmartControl: QS Service init finished
08-31 15:56:26.322  7526  7526 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 15:56:26.322  7526  7526 D UEI.SmartControl: QS Service version code: 201091
08-31 15:56:26.323  7526  7526 D UEI.SmartControl: Service requested: Control
08-31 15:56:26.328  7526  7526 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-31 15:56:26.334  1035  2016 I ActivityManager: Killing 6851:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 15:56:26.336  7526  7576 E UEI.SmartControl: Loading SETTINGS...
08-31 15:56:26.344  7526  7576 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-31 15:56:26.368  7526  7575 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 15:56:26.369  7526  7575 D UEI.SmartControl: -----service ready thread exits
,08-31 15:56:26.389  1035  1050 W libprocessgroup: failed to open /acct/uid_10112/pid_6851/cgroup.procs: No such file or directory
,08-31 15:56:26.397  7526  7526 D UEI.SmartControl: Internal service binding...
,08-31 15:56:26.758  6918  7391 D bt_hci_bdroid: cleanup
,08-31 15:56:26.766  6918  7452 I bt_lpm  : LPM is already off!!!
,08-31 15:56:26.767  6918  7450 W bt-btif : ag scb idx 1 not allocated
08-31 15:56:26.767  6918  7450 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 15:56:26.767  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:26.767  6918  7450 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:56:26.767  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:26.767  6918  7450 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:56:26.767  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:26.767  6918  7450 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:56:26.768  6918  7483 I bt_userial_mct: exiting userial_read_thread
08-31 15:56:26.768  6918  7483 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 15:56:26.768  6918  7450 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:56:26.768  6918  7450 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 15:56:26.769  6918  7391 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 15:56:26.769  6918  7452 I bt_vendor: hw_epilog_process
08-31 15:56:26.770  6918  7391 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 15:56:26.770  6918  7391 D bt_userial_mct: userial_close
08-31 15:56:26.770  6918  7391 E bt_userial_mct: pthread_join() FAILED result:3
08-31 15:56:26.770  6918  7391 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 15:56:26.775  6918  7391 D bt_hci_bdroid: set_power 0
08-31 15:56:26.775  6918  7391 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 15:56:26.775  6918  7391 I bt_vendor: bluetooth satus is on
08-31 15:56:26.775  6918  7391 I bt_vendor: bt-vendor : resetting BT status
08-31 15:56:26.775  6918  7391 I bt_vendor: Starting hciattach daemon
08-31 15:56:26.775  6918  7391 I bt_vendor: try to set false
08-31 15:56:26.779  6918  7391 I bt_vendor: Starting hciattach daemon
08-31 15:56:26.779  6918  7391 I bt_vendor: try to set false
,08-31 15:56:26.785  6918  7391 I bt_vendor: cleanup
08-31 15:56:26.785  6918  7450 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 15:56:26.786  6918  7391 I GKI_LINUX: GKI_exit_task 0 done
08-31 15:56:26.786  6918  7391 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 15:56:26.788  6918  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 15:56:26.795  6918  6918 D HeadsetService: Received stop request...Stopping profile...
,08-31 15:56:26.799  6918  6918 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 15:56:26.799  6918  6918 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:56:26.799  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:26.800  6918  7409 D HeadsetStateMachine: Exit Disconnected: -1
08-31 15:56:26.803  6918  7387 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 15:56:26.804  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-31 15:56:26.804  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-31 15:56:26.804  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-31 15:56:26.805  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-31 15:56:26.805  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 15:56:26.806  6918  6918 D A2dpService: Received stop request...Stopping profile...
08-31 15:56:26.806  6918  7442 D A2dpStateMachine: Exit Disconnected: -1
08-31 15:56:26.809  1035  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{30afcd6a type 2 when 222011 android} when 222011
,08-31 15:56:26.813  6918  6918 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 15:56:26.815  6918  6918 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 15:56:26.815  6918  6918 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:56:26.815  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:26.818  6918  6918 D HidService: Received stop request...Stopping profile...
08-31 15:56:26.818  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:26.835  6777  6777 D BluetoothA2dp: Proxy object disconnected
08-31 15:56:26.835  6777  6777 D A2dpProfile: Bluetooth service disconnected
08-31 15:56:26.835  6777  6777 D BluetoothHeadset: Proxy object disconnected
08-31 15:56:26.835  6777  6777 D HeadsetProfile: Bluetooth service disconnected
,08-31 15:56:26.863  1035  1035 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7579 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-31 15:56:26.876  6918  6918 D HealthService: Received stop request...Stopping profile...
08-31 15:56:26.876  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
,08-31 15:56:26.882  6918  6918 D PanService: Received stop request...Stopping profile...
08-31 15:56:26.882  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:26.884  6918  6918 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:56:26.885  6918  6918 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 15:56:26.885  6918  6918 D BtGatt.GattService: stop()
08-31 15:56:26.885  6918  6918 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 15:56:26.886  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:26.887  6918  6918 D BluetoothMapService: Received stop request...Stopping profile...
08-31 15:56:26.887  6918  6918 D BluetoothMapService: stop()
08-31 15:56:26.887  6918  6918 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 15:56:26.887  6918  6918 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 15:56:26.888  6918  6918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
,08-31 15:56:26.892  6918  6918 D HeadsetStateMachine: Unbinding service...
08-31 15:56:26.892  6918  6918 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:56:26.892  6918  6918 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:56:26.892  6918  6918 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:56:26.892  6918  6918 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:56:26.893  6918  6918 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 15:56:26.893  6918  6918 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:56:26.893  6918  6918 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 15:56:26.893  6918  6918 I BluetoothA2dpServiceJni: cleanupNative
08-31 15:56:26.893  6918  7443 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 15:56:26.894  6918  6918 I GKI_LINUX: GKI_exit_task 2 done
08-31 15:56:26.894  6918  6918 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 15:56:26.894  6918  6918 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:56:26.894  6918  6918 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 15:56:26.894  6918  6918 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 15:56:26.895  6918  6918 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:56:26.895  6918  6918 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:56:26.895  6918  6918 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 15:56:26.895  6918  6918 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 15:56:26.897  6918  6918 V BluetoothMapService: Handler(): got msg=4
08-31 15:56:26.897  6918  6918 D BluetoothMapService: MAP Service closeService in
08-31 15:56:26.897  6918  6918 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:56:26.897  6918  6918 V BluetoothMapService: MAP Service closeService out
08-31 15:56:26.898  6918  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 15:56:26.898  6918  7387 D BluetoothAdapterProperties: Setting state to 10
08-31 15:56:26.898  6918  7387 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 15:56:26.899  6918  6918 D BluetoothMapService: cleanup()
08-31 15:56:26.899  6918  6918 D BluetoothMapService: MAP Service closeService in
08-31 15:56:26.899  6918  6918 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 15:56:26.899  6918  6918 V BluetoothMapService: MAP Service closeService out
08-31 15:56:26.900  1035  1117 D BluetoothManagerService: Message: 60
08-31 15:56:26.900  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 15:56:26.900  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-31 15:56:26.900  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:56:26.904  6918  7387 I BluetoothAdapterState: Entering OffState
08-31 15:56:26.907  6777  6794 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:56:26.909  6777  6808 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:56:26.910  6777  7490 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 15:56:26.912  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:56:26.913  6777  6794 D BluetoothMap: onBluetoothStateChange: up=false
08-31 15:56:26.915  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-31 15:56:26.915  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 15:56:26.922  1836  3965 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:56:26.922  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:56:26.922  6777  7490 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:56:26.923  6777  6794 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:56:26.923  6777  6777 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 15:56:26.923  6777  6777 D PanProfile: Bluetooth service disconnected
08-31 15:56:26.924  1836  3964 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:56:26.924  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 15:56:26.924  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-31 15:56:26.927  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 15:56:26.927  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 15:56:26.927  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2cbd299 mBinding = false
08-31 15:56:26.928  1035  1117 D BluetoothManagerService: Sending unbind request.
08-31 15:56:26.931  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 15:56:26.934  6918  7391 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 15:56:26.936  6918  6918 I GKI_LINUX: GKI_exit_task 1 done
08-31 15:56:26.936  6918  6918 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 15:56:26.936  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:26.936  6918  6918 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 15:56:26.936  1925  2126 D LGBluetoothAPIService: Message: 2
08-31 15:56:26.936  6918  6918 I art     : --- WEIRD: removing null entry 248
,08-31 15:56:26.936  1925  2126 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@88fb066 mBinding = false
08-31 15:56:26.936  1925  2126 D LGBluetoothAPIService: Sending unbind request.
08-31 15:56:26.936  6918  6918 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-31 15:56:26.936  6918  6918 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 15:56:26.937  6777  6777 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 15:56:26.937  6777  6777 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-31 15:56:26.943  6918  6918 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 15:56:26.944  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:26.944  6777  6777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 15:56:26.945  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:56:26.945  6918  6918 I art     : System.exit called, status: 0
08-31 15:56:26.945  6918  6918 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 15:56:26.947  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:26.949  1586  1586 D BluetoothAdapter: 422573929: getState() :  mService = null. Returning STATE_OFF
08-31 15:56:26.949  1586  1586 D BluetoothAdapter: 422573929: getState() :  mService = null. Returning STATE_OFF
,08-31 15:56:26.953  6777  6777 D DockEventReceiver: finishStartingService: stopping service
08-31 15:56:26.966   313  1369 V AudioFlinger: 6918 died, releasing its sessions
08-31 15:56:26.966   313  1369 V AudioFlinger:  pid 1836 @ 0
08-31 15:56:26.966   313  1369 V AudioFlinger:  pid 3439 @ 1
08-31 15:56:26.966   313  1369 V AudioFlinger:  pid 3439 @ 2
08-31 15:56:26.966  6777  6777 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-31 15:56:26.983  7579  7579 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 15:56:26.985  1035  1559 I ActivityManager: Process com.android.bluetooth (pid 6918) has died
,08-31 15:56:26.985  1035  1559 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-31 15:56:26.988  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:56:26.998  6777  6777 D BluetoothPermissionRequest: onReceive
,08-31 15:56:27.000  6777  6777 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-31 15:56:27.000  6777  6777 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 15:56:27.002  6777  6777 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:56:27.051  1035  1959 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7615 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 15:56:27.056  7579  7579 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-31 15:56:27.091  7579  7579 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-31 15:56:27.092  7579  7579 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 15:56:27.092  7579  7579 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 15:56:27.092  7579  7579 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-31 15:56:27.092  7579  7579 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 15:56:27.094  7579  7579 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 15:56:27.096  7615  7615 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 15:56:27.097  7615  7615 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:56:27.097  7615  7615 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 15:56:27.098  7615  7615 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 15:56:27.098  7579  7579 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 15:56:27.105  7579  7579 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-31 15:56:27.105  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4418
08-31 15:56:27.107  7579  7579 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-31 15:56:27.110  7579  7579 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 15:56:27.111  7579  7579 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-31 15:56:27.111  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 15:56:27.112  7579  7579 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-31 15:56:27.116  7615  7615 D BluetoothAdapterApp: Loading JNI Library
08-31 15:56:27.137  7579  7579 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:27.137  7579  7579 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:27.143  7579  7579 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 15:56:27.147  7579  7579 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 15:56:27.147  7579  7579 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 15:56:27.147  7579  7579 V SoundPool: doLoad: loading sample sampleID=1
08-31 15:56:27.147  7579  7636 V SoundPool: Start decode
08-31 15:56:27.147  7579  7636 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 15:56:27.148   313  1369 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 15:56:27.148   313  1369 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 15:56:27.148   313  1369 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 15:56:27.148   313  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 15:56:27.148   313  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 15:56:27.148   313  1369 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 15:56:27.148   313  1369 V MediaPlayerService: player type = 3
08-31 15:56:27.148   313  1369 V AwesomePlayer: AwesomePlayer create()
,08-31 15:56:27.148  7615  7615 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2ff0151f Instance Count = 1
08-31 15:56:27.148   313  1369 V AwesomePlayer: reset_l() 
08-31 15:56:27.148   313  1369 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:27.148   313  1369 V AwesomePlayer: setAudioSink() 
08-31 15:56:27.148   313  1369 V AwesomePlayer: reset_l() 
08-31 15:56:27.148   313  1369 V AudioCache: notify(0xb1432180, 8, 0, 0)
08-31 15:56:27.148   313  1369 V AudioCache: ignored
08-31 15:56:27.148   313  1369 V AwesomePlayer: cancelPlayerEvents
,08-31 15:56:27.148   313  1369 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 15:56:27.148   313  1369 V AwesomePlayer: setDataSource_l dataSource
08-31 15:56:27.148   313  1369 V LGParserOSAL: SniffLGParser start
08-31 15:56:27.148   313  1369 V LGParserOSAL: MainType:5, SubType=0
08-31 15:56:27.148   313  1369 V LGParserOSAL: #### check Mime : application/ogg
08-31 15:56:27.148   313  1369 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 15:56:27.148   313  1369 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 15:56:27.148  7579  7579 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 15:56:27.156  7615  7615 D BluetoothAdapterApp: onCreate
08-31 15:56:27.158  7579  7579 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 15:56:27.164  7579  7579 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-31 15:56:27.165  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-31 15:56:27.175  7615  7615 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 15:56:27.175  7615  7615 D ProfileConfigQcom: Adding HeadsetService
08-31 15:56:27.176  7615  7615 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 15:56:27.176  7615  7615 D ProfileConfigQcom: Adding A2dpService
08-31 15:56:27.176  7615  7615 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 15:56:27.176  7615  7615 D ProfileConfigQcom: Adding HidService
08-31 15:56:27.176  7615  7615 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 15:56:27.177  7615  7615 D ProfileConfigQcom: Adding HealthService
08-31 15:56:27.177  7615  7615 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 15:56:27.177   313  1369 V LGParserOSAL: supported mime: application/ogg
08-31 15:56:27.177   313  1369 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 15:56:27.177   313  1369 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 15:56:27.177   313  1369 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 15:56:27.177   313  1369 V AwesomePlayer: AudioTrack Setting
08-31 15:56:27.177   313  1369 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 15:56:27.177   313  1369 V AwesomePlayer: setAudioSource() 
08-31 15:56:27.177   313  1369 V MediaPlayerService: prepare
08-31 15:56:27.177  7615  7615 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 15:56:27.177   313  1369 V AwesomePlayer: prepareAsync_l() 
08-31 15:56:27.177   313  1369 V MediaPlayerService: wait for prepare
08-31 15:56:27.177  7615  7615 D ProfileConfigQcom: Adding PanService
08-31 15:56:27.178  7615  7615 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 15:56:27.178  7615  7615 D ProfileConfigQcom: Adding GattService
08-31 15:56:27.178   313  7638 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 15:56:27.178   313  7638 V AwesomePlayer: initAudioDecoder() 
08-31 15:56:27.178   313  7638 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 15:56:27.178  7615  7615 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 15:56:27.178   313  7638 V AudioSystem: isOffloadSupported()
08-31 15:56:27.178   313  7638 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 15:56:27.178  7615  7615 D ProfileConfigQcom: Adding BluetoothMapService
08-31 15:56:27.178   313  7638 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 15:56:27.178   313  7638 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 15:56:27.178   313  7638 V AwesomePlayer: getUseOffload() = 0 
08-31 15:56:27.178   313  7638 V OMXCodec: OMXCodec::Create
08-31 15:56:27.178   313  7638 V OMXCodec: findMatchingCodecs()
08-31 15:56:27.178  7615  7615 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 15:56:27.179   313  7638 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 15:56:27.179   313  7638 V OMXCodec: matchingCodecs.size()=1
08-31 15:56:27.179   313  7638 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 15:56:27.180  7615  7615 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 15:56:27.183   313  7638 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 15:56:27.183   313  7638 V LGCodecAdapter: LG Codec Adapter start
08-31 15:56:27.183   313  7638 V OMXCodec: OMXCodec Createtor
08-31 15:56:27.183   313  7638 V OMXCodec: setComponentRole
08-31 15:56:27.183   313  7638 V OMXCodec: configureCodec protected=0
,08-31 15:56:27.183   313  7638 V LGCodecAdapter: called getLGCodecSpecificData
08-31 15:56:27.183   313  7638 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 15:56:27.183   313  7638 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 15:56:27.184   313  7638 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 15:56:27.184   313  7638 V LGCodecOSAL: Not support LGCodec
08-31 15:56:27.184   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 15:56:27.184   313  7638 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 15:56:27.184   313  7638 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
,08-31 15:56:27.184   313  7638 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 15:56:27.184   313  7638 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 15:56:27.185  6777  6777 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 15:56:27.185   313  7638 V AudioSystem: isOffloadSupported()
08-31 15:56:27.185   313  7638 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 15:56:27.185   313  7638 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 15:56:27.185   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 15:56:27.185   313  7638 V OMXCodec: init()
08-31 15:56:27.185   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 15:56:27.185   313  7638 V OMXCodec: allocateBuffers
,08-31 15:56:27.185   313  7638 V OMXCodec: allocateBuffersOnPort portIndex=0,
,08-31 15:56:27.185   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 15:56:27.185   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-31 15:56:27.185   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-31 15:56:27.185   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-31 15:56:27.185   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-31 15:56:27.185   313  7638 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 15:56:27.185   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 15:56:27.185   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
,08-31 15:56:27.186   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-31 15:56:27.186   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-31 15:56:27.186   313  7638 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fdd0 on output port
08-31 15:56:27.186   313  7638 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 15:56:27.186  7615  7615 V LGMDMManagerInternal: Create singleton instance
08-31 15:56:27.190  7579  7579 V LGMDMManager: Create singleton instance
08-31 15:56:27.191   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 15:56:27.191   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 15:56:27.191   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 15:56:27.191   313  7638 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-31 15:56:27.191   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 15:56:27.191   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 15:56:27.191   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 15:56:27.191   313  7638 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 15:56:27.191   313  7638 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 15:56:27.191   313  7638 V AudioCache: notify(0xb1432180, 5, 0, 0)
08-31 15:56:27.191   313  7638 V AudioCache: ignored
08-31 15:56:27.191   313  7638 V AudioCache: notify(0xb1432180, 1, 0, 0)
08-31 15:56:27.191   313  7638 V AudioCache: prepared
08-31 15:56:27.191   313  1369 V AudioCache: wait - success
08-31 15:56:27.192   313  1369 V MediaPlayerService: start
08-31 15:56:27.192   313  1369 V AwesomePlayer: play_l() 
08-31 15:56:27.192   313  1369 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0,
08-31 15:56:27.192   313  1369 V AwesomePlayer: createAudioPlayer_l
08-31 15:56:27.192   313  1369 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 15:56:27.192   313  1369 V AwesomePlayer: startAudioPlayer_l() 
08-31 15:56:27.192   313  1369 D AudioPlayer: start of Playback, useOffload 0
08-31 15:56:27.192   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 15:56:27.192   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049296
08-31 15:56:27.194   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 15:56:27.195   313  7640 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1784150 on output port
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 15:56:27.195   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 15:56:27.196   313  1369 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 15:56:27.196   313  1369 V AudioCache: notify(0xb1432180, 6, 0, 0)
,08-31 15:56:27.196   313  1369 V AudioCache: ignored
08-31 15:56:27.196   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.196   313  7641 V AudioCache: memcpy(0xaf006000, 0xb57ca000, 4096)
08-31 15:56:27.196   313  1369 V MediaPlayerService: wait for playback complete
08-31 15:56:27.197   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.197   313  7641 V AudioCache: memcpy(0xaf007000, 0xb57ca000, 4096)
08-31 15:56:27.197   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.197   313  7641 V AudioCache: memcpy(0xaf008000, 0xb57ca000, 4096)
08-31 15:56:27.197   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.197   313  7641 V AudioCache: memcpy(0xaf009000, 0xb57ca000, 4096)
08-31 15:56:27.197   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.197   313  7641 V AudioCache: memcpy(0xaf00a000, 0xb57ca000, 4096)
,08-31 15:56:27.198   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.198   313  7641 V AudioCache: memcpy(0xaf00b000, 0xb57ca000, 4096)
08-31 15:56:27.198   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.198   313  7641 V AudioCache: memcpy(0xaf00c000, 0xb57ca000, 4096)
08-31 15:56:27.198   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.198   313  7641 V AudioCache: memcpy(0xaf00d000, 0xb57ca000, 4096)
08-31 15:56:27.198   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.198   313  7641 V AudioCache: memcpy(0xaf00e000, 0xb57ca000, 4096)
08-31 15:56:27.199   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.199   313  7641 V AudioCache: memcpy(0xaf00f000, 0xb57ca000, 4096)
08-31 15:56:27.199   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.199   313  7641 V AudioCache: memcpy(0xaf010000, 0xb57ca000, 4096)
,08-31 15:56:27.201   313  7641 V AudioCache: write(0xb57ca000, 4096)
,08-31 15:56:27.201   313  7641 V AudioCache: memcpy(0xaf011000, 0xb57ca000, 4096)
08-31 15:56:27.202   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.202   313  7641 V AudioCache: memcpy(0xaf012000, 0xb57ca000, 4096)
08-31 15:56:27.202   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.202   313  7641 V AudioCache: memcpy(0xaf013000, 0xb57ca000, 4096)
08-31 15:56:27.203   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.203   313  7641 V AudioCache: memcpy(0xaf014000, 0xb57ca000, 4096)
08-31 15:56:27.203   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.203   313  7641 V AudioCache: memcpy(0xaf015000, 0xb57ca000, 4096)
08-31 15:56:27.204   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.204   313  7641 V AudioCache: memcpy(0xaf016000, 0xb57ca000, 4096)
08-31 15:56:27.205   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.205   313  7641 V AudioCache: memcpy(0xaf017000, 0xb57ca000, 4096)
08-31 15:56:27.206   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.206   313  7641 V AudioCache: memcpy(0xaf018000, 0xb57ca000, 4096)
08-31 15:56:27.206   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.206   313  7641 V AudioCache: memcpy(0xaf019000, 0xb57ca000, 4096)
08-31 15:56:27.207   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.207   313  7641 V AudioCache: memcpy(0xaf01a000, 0xb57ca000, 4096)
08-31 15:56:27.208   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.208   313  7641 V AudioCache: memcpy(0xaf01b000, 0xb57ca000, 4096)
08-31 15:56:27.208   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.208   313  7641 V AudioCache: memcpy(0xaf01c000, 0xb57ca000, 4096)
08-31 15:56:27.209   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.209   313  7641 V AudioCache: memcpy(0xaf01d000, 0xb57ca000, 4096)
08-31 15:56:27.209   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.209   313  7641 V AudioCache: memcpy(0xaf01e000, 0xb57ca000, 4096)
08-31 15:56:27.210   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.210   313  7641 V AudioCache: memcpy(0xaf01f000, 0xb57ca000, 4096)
08-31 15:56:27.210   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.210   313  7641 V AudioCache: memcpy(0xaf020000, 0xb57ca000, 4096)
08-31 15:56:27.211   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.211   313  7641 V AudioCache: memcpy(0xaf021000, 0xb57ca000, 4096)
08-31 15:56:27.211   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.211   313  7641 V AudioCache: memcpy(0xaf022000, 0xb57ca000, 4096)
08-31 15:56:27.211   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.211   313  7641 V AudioCache: memcpy(0xaf023000, 0xb57ca000, 4096)
08-31 15:56:27.212   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.212   313  7641 V AudioCache: memcpy(0xaf024000, 0xb57ca000, 4096)
08-31 15:56:27.213   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.213   313  7641 V AudioCache: memcpy(0xaf025000, 0xb57ca000, 4096)
08-31 15:56:27.213   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.213   313  7641 V AudioCache: memcpy(0xaf026000, 0xb57ca000, 4096)
08-31 15:56:27.214   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.214   313  7641 V AudioCache: memcpy(0xaf027000, 0xb57ca000, 4096)
08-31 15:56:27.214   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.214   313  7641 V AudioCache: memcpy(0xaf028000, 0xb57ca000, 4096)
08-31 15:56:27.214   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.214   313  7641 V AudioCache: memcpy(0xaf029000, 0xb57ca000, 4096)
08-31 15:56:27.216   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.216   313  7641 V AudioCache: memcpy(0xaf02a000, 0xb57ca000, 4096)
08-31 15:56:27.216   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.216   313  7641 V AudioCache: memcpy(0xaf02b000, 0xb57ca000, 4096)
08-31 15:56:27.216   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.216   313  7641 V AudioCache: memcpy(0xaf02c000, 0xb57ca000, 4096)
08-31 15:56:27.216   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.216   313  7641 V AudioCache: memcpy(0xaf02d000, 0xb57ca000, 4096)
08-31 15:56:27.217   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.217   313  7641 V AudioCache: memcpy(0xaf02e000, 0xb57ca000, 4096)
08-31 15:56:27.217   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.217   313  7641 V AudioCache: memcpy(0xaf02f000, 0xb57ca000, 4096)
08-31 15:56:27.217   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.217   313  7641 V AudioCache: memcpy(0xaf030000, 0xb57ca000, 4096)
08-31 15:56:27.217   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.218   313  7641 V AudioCache: memcpy(0xaf031000, 0xb57ca000, 4096)
08-31 15:56:27.219   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.219   313  7641 V AudioCache: memcpy(0xaf032000, 0xb57ca000, 4096)
08-31 15:56:27.219   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.219   313  7641 V AudioCache: memcpy(0xaf033000, 0xb57ca000, 4096)
08-31 15:56:27.219   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.219   313  7641 V AudioCache: memcpy(0xaf034000, 0xb57ca000, 4096)
08-31 15:56:27.219   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.219   313  7641 V AudioCache: memcpy(0xaf035000, 0xb57ca000, 4096)
08-31 15:56:27.220   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 15:56:27.220   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.220   313  7641 V AudioCache: memcpy(0xaf036000, 0xb57ca000, 4096)
08-31 15:56:27.220   313  7641 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 15:56:27.220   313  7641 V AudioCache: write(0xb57ca000, 4096)
08-31 15:56:27.220   313  7641 V AudioCache: memcpy(0xaf037000, 0xb57ca000, 4096)
08-31 15:56:27.220   313  7641 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 15:56:27.220   313  7641 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 15:56:27.220   313  7641 V AwesomePlayer: postAudioEOS() 
08-31 15:56:27.220   313  7641 V AudioCache: write(0xb57ca000, 280)
08-31 15:56:27.220   313  7641 V AudioCache: memcpy(0xaf038000, 0xb57ca000, 280)
08-31 15:56:27.222   313  7638 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 15:56:27.222   313  7638 V AwesomePlayer: onStreamDone
08-31 15:56:27.222   313  7638 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 15:56:27.222   313  7638 V AudioCache: notify(0xb1432180, 2, 0, 0)
08-31 15:56:27.222   313  7638 V AudioCache: playback complete
08-31 15:56:27.222   313  7638 V AwesomePlayer: pause_l() 
08-31 15:56:27.222   313  7638 V AudioCache: notify(0xb1432180, 7, 0, 0)
08-31 15:56:27.222   313  7638 V AudioCache: ignored
08-31 15:56:27.222   313  7638 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:27.222   313  7638 D AudioPlayer: Pause Playback at 1068125
,08-31 15:56:27.222   313  1369 V AudioCache: wait - success
08-31 15:56:27.222   313  1369 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 15:56:27.222   313  1369 V AwesomePlayer: reset_l() 
08-31 15:56:27.222   313  1369 V AudioCache: notify(0xb1432180, 8, 0, 0)
08-31 15:56:27.222   313  1369 V AudioCache: ignored
08-31 15:56:27.222   313  1369 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:27.222   313  1369 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 15:56:27.222   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 15:56:27.222   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 15:56:27.222   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 15:56:27.222   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 15:56:27.222   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 15:56:27.222   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 15:56:27.222   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 15:56:27.222   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-31 15:56:27.222   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 15:56:27.222   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-31 15:56:27.222   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1784150 on port 1
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 15:56:27.223   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 15:56:27.223   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 15:56:27.223   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 15:56:27.224   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 15:56:27.224   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 15:56:27.224   313  7640 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 15:56:27.224   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 15:56:27.224   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 15:56:27.224   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 15:56:27.225   313  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-31 15:56:27.225   313  1369 D AudioPlayer: AudioPlayer releasing audio source
08-31 15:56:27.225   313  1369 D AudioPla,yer: AudioPlayer done releasing audio source
08-31 15:56:27.225   313  1369 V AwesomePlayer: reset_l() 
08-31 15:56:27.226   313  1369 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:27.226   313  1369 V AwesomePlayer: ~AwesomePlayer call
08-31 15:56:27.226   313  1369 V AwesomePlayer: reset_l() 
08-31 15:56:27.226   313  1369 V AwesomePlayer: cancelPlayerEvents
08-31 15:56:27.226  7579  7636 V SoundPool: close(31)
08-31 15:56:27.226  7579  7636 V SoundPool: pointer = 0x9ffdf000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 15:56:27.240  7615  7615 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:56:27.242  7615  7615 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:56:27.242  7615  7615 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:56:27.242  7615  7615 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:56:27.243  7615  7615 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:27.243  7615  7615 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 15:56:27.245  6868  6868 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-31 15:56:27.259  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-31 15:56:27.259  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 15:56:27.261  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6127
,08-31 15:56:27.262  7579  7579 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 15:56:27.263  7526  7541 I UEI.SmartControl: ------ IControl API: 11
08-31 15:56:27.264  7526  7541 I UEI.SmartControl: Registering callback...
08-31 15:56:27.264  7526  7542 I UEI.SmartControl: ------ IControl API: 19
08-31 15:56:27.265  7526  7542 I UEI.SmartControl: Registering Services Ready callback...
08-31 15:56:27.265  7526  7542 I UEI.SmartControl: Notify client services are ready...
08-31 15:56:27.266  7579  7610 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 15:56:27.267  7579  7634 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 15:56:27.267  7579  7634 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 15:56:27.268  7579  7579 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 15:56:27.269  7579  7579 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 15:56:27.269  7526  7541 I UEI.SmartControl: ------ IControl API: 8
08-31 15:56:27.270  7579  7579 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 15:56:27.270  7579  7579 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 15:56:27.270  7579  7579 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 15:56:27.271  7579  7579 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 15:56:27.271  7579  7579 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 15:56:27.271  7579  7579 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-31 15:56:27.273  7579  7579 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-31 15:56:27.274  7579  7579 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 15:56:27.275  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 15:56:27.275  7579  7579 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 15:56:27.275  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 15:56:27.276  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 15:56:27.277  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 15:56:27.277  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 15:56:27.278  7579  7579 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472651787278]
08-31 15:56:27.280  7579  7579 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 15:56:27.282  1035  1995 I ActivityManager: Killing 6983:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-31 15:56:27.309  7579  7642 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 15:56:27.315  1035  1995 I ActivityManager: Killing 6819:com.lge.sync/1000 (adj 15): empty #18
08-31 15:56:27.329  1035  1526 D WifiService: Client connection lost with reason: 4
,08-31 15:56:27.346  1035  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_6983/cgroup.procs: No such file or directory
,08-31 15:56:27.358  1035  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_6819/cgroup.procs: No such file or directory
08-31 15:56:27.363  7579  7579 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-31 15:56:27.365  7579  7579 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 15:56:27.365  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 15:56:27.366  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 15:56:27.366  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 15:56:27.366  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-31 15:56:27.367  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 15:56:27.377  7579  7579 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 15:56:28.798  1035  1413 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 15:56:28.803  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-31 15:56:28.845  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:28.845  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:56:28.887  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 15:56:28.890  1035  1035 D administrator: Handling package changes for user 0
08-31 15:56:28.916  1035  1113 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7652 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 15:56:28.938  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 15:56:28.942  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-31 15:56:28.964  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 15:56:28.990  7652  7652 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 15:56:29.019  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-31 15:56:29.020  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 15:56:29.066  7652  7652 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:29.066  7652  7652 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:29.085  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 15:56:29.091  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-31 15:56:29.097  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 15:56:29.099  2489  2489 V GmsNetworkLocationProvi: DISABLE
08-31 15:56:29.122  2489  2489 E GCoreFlp: Bound FusedProviderService with LocationManager
08-31 15:56:29.122  1035  1112 D LocationProviderProxy: applying state to connected service
,08-31 15:56:29.180  7652  7697 I Babel   : MmsConfig: mnc/mcc: 0/0
08-31 15:56:29.180  7652  7697 I Babel   : MmsConfig.loadMmsSettings
08-31 15:56:29.184  7652  7697 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 15:56:29.184  7652  7697 I Babel   : MmsConfig.loadFromDatabase
,08-31 15:56:29.203  7652  7697 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-31 15:56:29.203  7652  7697 I Babel   : MmsConfig.loadFromResources
08-31 15:56:29.208  7652  7697 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-31 15:56:29.209  7652  7697 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-31 15:56:29.217  7652  7652 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:56:29.249  7652  7696 W AudioCapabilities: Unsupported mime audio/evrc
08-31 15:56:29.250  7652  7696 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 15:56:29.251  1800  7700 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-31 15:56:29.251  1800  7700 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-31 15:56:29.255  7652  7696 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 15:56:29.269  7652  7696 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-31 15:56:29.271  7652  7696 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 15:56:29.272  7652  7696 W AudioCapabilities: Unsupported mime audio/evrc
08-31 15:56:29.278  7652  7696 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 15:56:29.280  7652  7696 W VideoCapabilities: Unsupported mime video/divx
08-31 15:56:29.281  7652  7696 W VideoCapabilities: Unsupported mime video/divx311
08-31 15:56:29.282  7652  7696 W VideoCapabilities: Unsupported mime video/divx4
08-31 15:56:29.285  1035  1639 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7703 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-31 15:56:29.287  7652  7696 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-31 15:56:29.293  1035  2013 I ActivityManager: Killing 7019:com.lge.email/u0a23 (adj 15): empty #17
,08-31 15:56:29.321  7652  7696 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 15:56:29.325  7652  7696 W AudioCapabilities: Unsupported mime audio/eac3
,08-31 15:56:29.326  7652  7696 W AudioCapabilities: Unsupported mime audio/ac3
08-31 15:56:29.327  7652  7696 W AudioCapabilities: Unsupported mime audio/g726
08-31 15:56:29.328  7652  7696 W AudioCapabilities: Unsupported mime audio/wma-voice
08-31 15:56:29.329  7652  7696 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 15:56:29.330  7652  7696 W AudioCapabilities: Unsupported mime audio/adpcm
08-31 15:56:29.331  7652  7696 W VideoCapabilities: Unsupported mime video/theora
08-31 15:56:29.333  7652  7696 W VideoCapabilities: Unsupported mime video/mjpg
,08-31 15:56:29.389  1035  2035 W libprocessgroup: failed to open /acct/uid_10023/pid_7019/cgroup.procs: No such file or directory
08-31 15:56:29.399  1800  4737 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-31 15:56:29.412  7703  7703 I AppUp4:AppBoxCP: onCreate
,08-31 15:56:29.413  7703  7703 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-31 15:56:29.418  7703  7703 I AppUp4:DB:  setFingerPrint start
08-31 15:56:29.418  7703  7703 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-31 15:56:29.423  7703  7703 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 15:56:29.423  7703  7703 I AppUp4:DB:  SDK version = 21
08-31 15:56:29.423  7703  7703 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-31 15:56:29.424  7703  7703 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-31 15:56:29.428  7703  7703 I AppUp4:CustModeStarterReceiver: onReceive
08-31 15:56:29.460  7703  7703 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:56:29.460  7703  7703 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:56:29.467  7703  7703 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2b68daca
08-31 15:56:29.467  7703  7703 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 15:56:29.467  7703  7703 D AppUp4:CustFacade: isPhone : true
08-31 15:56:29.467  7703  7703 D AppUp4:CustModeStarterReceiver: begin check event
08-31 15:56:29.467  7703  7703 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-31 15:56:29.519  1035  1978 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7723 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-31 15:56:29.520  1035  1978 I ActivityManager: Killing 6889:com.lge.formmanager/u0a26 (adj 15): empty #17
08-31 15:56:29.606  1035  1639 W libprocessgroup: failed to open /acct/uid_10026/pid_6889/cgroup.procs: No such file or directory
,08-31 15:56:29.649  7723  7723 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 15:56:29.649  7723  7723 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:56:29.650  7723  7723 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 15:56:29.652  7723  7723 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-31 15:56:29.653  7723  7723 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 15:56:29.751  7723  7723 I SystemConfig: BUILD Country: EU
08-31 15:56:29.751  7723  7723 I SystemConfig: BUILD Operator: OPEN
,08-31 15:56:29.843  1035  1639 I ActivityManager: Killing 6393:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-31 15:56:29.865  1035  1527 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-31 15:56:29.889  1035  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_6393/cgroup.procs: No such file or directory
,08-31 15:56:29.897  7723  7743 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-31 15:56:29.897  7723  7743 I SystemConfig: existFile = false
08-31 15:56:29.897  7723  7743 I SystemConfig: canReadFile = false
08-31 15:56:29.898  7723  7743 I SystemConfig: systemFeature RCS result false
08-31 15:56:29.898  7723  7743 D SystemConfig: refreshRcsSupport() :false
08-31 15:56:29.953  1035  1639 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7745 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-31 15:56:29.978   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 22.576ms
,08-31 15:56:29.999   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 19.093ms
,08-31 15:56:30.016  7745  7745 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 15:56:30.017  7745  7745 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 15:56:30.017  7745  7745 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 15:56:30.017  7745  7745 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 15:56:30.018   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 378us total 18.892ms
08-31 15:56:30.123  7745  7745 I AppConfig: Total System Memory = 2995761152
,08-31 15:56:30.134  7745  7745 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-31 15:56:30.233  1035  1871 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7764 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 15:56:30.236  1035  1871 I ActivityManager: Killing 7061:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-31 15:56:30.286  1035  1050 W libprocessgroup: failed to open /acct/uid_10046/pid_7061/cgroup.procs: No such file or directory
,08-31 15:56:30.506  7764  7764 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-31 15:56:30.634  7764  7764 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:30.634  7764  7764 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:30.672  1035  1362 V AlarmManager: RTC_WAKEUP set : Alarm{3a9e2f3a type 0 when 1472651790042 com.google.android.gms} when 1472651790042
08-31 15:56:30.687  7764  7764 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-31 15:56:30.708  7764  7764 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 15:56:30.709  7764  7764 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 15:56:30.742  7764  7764 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 15:56:30.743  7764  7764 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-31 15:56:30.774  1035  1050 I ActivityManager: Killing 7080:com.android.chrome/u0a57 (adj 15): empty #17
,08-31 15:56:30.869  1035  1995 W libprocessgroup: failed to open /acct/uid_10057/pid_7080/cgroup.procs: No such file or directory
,08-31 15:56:30.878  3515  4439 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-31 15:56:30.884  3515  4439 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f78fb85 on behalf of 7764
,08-31 15:56:30.888  4594  7804 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-31 15:56:30.931  1035  1716 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7805 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-31 15:56:30.957  7764  7764 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-31 15:56:30.984  7764  7764 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-31 15:56:31.013  7805  7805 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-31 15:56:31.033  7805  7805 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-31 15:56:31.033  7805  7805 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-31 15:56:31.033  7805  7805 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-31 15:56:31.033  7805  7805 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-31 15:56:31.033  7805  7805 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-31 15:56:31.033  7805  7805 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-31 15:56:31.051  1035  1995 I ActivityManager: Killing 7101:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-31 15:56:31.069  1035  1716 W libprocessgroup: failed to open /acct/uid_10062/pid_7101/cgroup.procs: No such file or directory
,08-31 15:56:31.072  1800  7837 I CheckinService: active receiver: enabled
,08-31 15:56:31.091  2203  2203 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-31 15:56:31.152  1035  1871 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7839 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 15:56:31.260  1035  1959 V SIM_STK : Menu title from STK is T-Mobile
,08-31 15:56:31.273  4594  7804 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 384 ms] updated apps [took 384 ms] 
,08-31 15:56:31.290  7839  7839 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:31.290  7839  7839 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 15:56:31.293  7839  7839 D PhoneMonitor: Register our PhoneStateListener
08-31 15:56:31.303  7526  7577 D UEI.SmartControl: Internal timer expired: 1
08-31 15:56:31.303  7526  7577 D UEI.SmartControl: unbind internal service
,08-31 15:56:31.317  1035  1051 I ActivityManager: Killing 7125:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-31 15:56:31.332  7839  7839 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-31 15:56:31.334  7839  7839 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-31 15:56:31.335  7839  7839 D TelephonyAutoProfiling: [parse] Load xml
08-31 15:56:31.338  7839  7839 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 15:56:31.338  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 15:56:31.338  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 15:56:31.338  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 15:56:31.338  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 15:56:31.338  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 15:56:31.338  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 15:56:31.338  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 15:56:31.338  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 15:56:31.338  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 15:56:31.339  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 15:56:31.339  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 15:56:31.339  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
,08-31 15:56:31.339  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 15:56:31.339  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 15:56:31.339  7839  7839 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 15:56:31.339  7839  7839 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-31 15:56:31.349  7839  7839 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-31 15:56:31.366  1035  1906 W libprocessgroup: failed to open /acct/uid_10085/pid_7125/cgroup.procs: No such file or directory
,08-31 15:56:31.519  7526  7571 D serial_port: close(fd = 25)
,08-31 15:56:31.525  7526  7571 I UEI.SmartControl: Serial port is closed.
,08-31 15:56:31.941  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:56:31.942  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36c9001b added. We now have 6 listener(s)
,08-31 15:56:31.942  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:56:31.957  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:31.958  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17f75b8 added. We now have 7 listener(s)
08-31 15:56:31.958  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:31.958  6692  6758 I System.out: IsBluetoothEnabled
08-31 15:56:31.959  1035  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:31.959  1035  1559 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-31 15:56:31.960  1035  1117 D BluetoothManagerService: Message: 2
08-31 15:56:31.965  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:56:31.967  1035  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:31.967  1035  1942 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-31 15:56:31.985  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:56:31.986  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:56:31.986  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-31 15:56:31.989  1035  1117 D BluetoothManagerService: Message: 1
08-31 15:56:31.989  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-31 15:56:32.020  1035  1117 D BluetoothManagerService: Message: 20
08-31 15:56:32.021  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b94dfaf:true
,08-31 15:56:32.024  7615  7615 D BluetoothAdapterState: make
08-31 15:56:32.028  7615  7615 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 15:56:32.029  7615  7615 I bluedroid-qcom: init
08-31 15:56:32.030  7615  7870 I BluetoothAdapterState: Entering OffState
08-31 15:56:32.030  7615  7615 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 15:56:32.030  7615  7615 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 15:56:32.030  7615  7615 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 15:56:32.030  7615  7615 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 15:56:32.031  7615  7615 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 15:56:32.032  7615  7615 I bluedroid-qcom: get_profile_interface socket
08-31 15:56:32.032  7615  7615 I bluedroid-qcom: get_profile_interface map_client
,08-31 15:56:32.037  7615  7874 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 15:56:32.039  7615  7874 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 15:56:32.025  7873  7873 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:32.025  7873  7873 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:32.047  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 15:56:32.048  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-31 15:56:32.056  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 15:56:32.056  1035  1117 D BluetoothManagerService: Message: 40
08-31 15:56:32.056  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 15:56:32.057  7615  7631 I bluedroid-qcom: config_hci_snoop_log
08-31 15:56:32.058  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 15:56:32.058  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 15:56:32.059  7873  7873 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 15:56:32.059  7873  7873 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 15:56:32.059  7873  7873 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-31 15:56:32.062  7873  7873 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-31 15:56:32.067  7615  7874 D BluetoothAdapterProperties: Name is: G3
08-31 15:56:32.069  7873  7873 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 15:56:32.069  7873  7873 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 15:56:32.073  7615  7870 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-31 15:56:32.074  7615  7870 D BluetoothAdapterProperties: Setting state to 11
08-31 15:56:32.074  7615  7870 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 15:56:32.078  7615  7870 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 15:56:32.083  1035  1117 D BluetoothManagerService: Message: 60
08-31 15:56:32.083  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 15:56:32.083  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 15:56:32.087  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:56:32.090  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:56:32.093  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:32.106  6777  6777 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-31 15:56:32.114  7615  7870 D BluetoothBondStateMachine: make
08-31 15:56:32.116  7615  7615 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:56:32.117  7615  7615 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:32.117  7615  7615 V BluetoothPbapReceiver: ***********state = 11
08-31 15:56:32.121  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:56:32.121  7615  7870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:32.121  7615  7870 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 15:56:32.121  7615  7870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:32.122  7615  7870 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 15:56:32.123  7615  7870 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 15:56:32.126  7615  7887 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 15:56:32.131  7615  7870 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:32.138  6777  6777 D BluetoothPermissionRequest: onReceive
,08-31 15:56:32.139  7615  7615 D HeadsetService: Received start request. Starting profile...
08-31 15:56:32.140  7615  7870 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:32.140  7615  7615 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 15:56:32.140  7615  7615 D LGBluetoothHfpAdapter: Version 1.6
08-31 15:56:32.143  7615  7615 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 15:56:32.144  6777  6777 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:56:32.144  7615  7615 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 15:56:32.145  7615  7615 D HeadsetStateMachine: make
08-31 15:56:32.147  7615  7870 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:32.152  7615  7870 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:56:32.158  7615  7870 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:32.162  7615  7870 E BluetoothAdapterService: File transfer profiles supported!!
08-31 15:56:32.166  7615  7870 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 15:56:32.179  7615  7615 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:32.180  7615  7615 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:56:32.180  7615  7870 V LGMDMManager: Create singleton instance
,08-31 15:56:32.182  7615  7870 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 15:56:32.184  7615  7615 D HeadsetStateMachine: max_hf_connections = 1
08-31 15:56:32.184  7615  7615 I bluedroid-qcom: get_profile_interface handsfree
08-31 15:56:32.186  7615  7615 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 15:56:32.187   313  1369 V AudioPolicyService: registerClient() client 0xb0410180, uid 1002
08-31 15:56:32.187   313  1370 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 15:56:32.187   313  1370 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:56:32.187   313  1370 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:56:32.187  7615  7615 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 15:56:32.187   313  1766 V AudioFlinger: registerClient() client 0xb1433658, pid 7615
08-31 15:56:32.188   313  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:32.188   313  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:32.188  7615  7615 V ToneGenerator: Create Track: 0xb4928080
08-31 15:56:32.188  7615  7615 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 15:56:32.188  7615  7615 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 15:56:32.188   313  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:32.188   313  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:56:32.188   313  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 15:56:32.188   313  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 15:56:32.188   313  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:56:32.188   313  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:56:32.188  7615  7631 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:32.188  7615  7631 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 15:56:32.188  7615  7631 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:32.188  7615  7631 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 15:56:32.189   313  1370 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 15:56:32.189  1035  1559 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:32.189  1035  1559 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:32.189  1035  1559 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:32.189  1035  1559 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:56:32.189  1836  3964 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:32.189  1836  3964 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:32.189   313  1766 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 15:56:32.189   313  1766 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 15:56:32.189  1586  2522 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:32.189   313  1766 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 15:56:32.189  1836  3964 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:32.189  1586  2522 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:32.189   313  1766 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 15:56:32.189  1836  3964 V AudioSystem: ioConfigChanged() opening already existing output!, 2
08-31 15:56:32.189  1586  2522 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:32.189  1586  2522 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:56:32.190  7615  7615 V AudioSystem: getLatency() output 2, latency 50
08-31 15:56:32.190  7615  7615 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 15:56:32.190  7615  7615 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 15:56:32.190  3439  3454 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 15:56:32.190  3439  3454 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 15:56:32.190  3439  3454 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 15:56:32.190  3439  3454 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 15:56:32.190   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 15:56:32.190   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 15:56:32.190   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 15:56:32.190   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 15:56:32.190   313   313 V AudioFlinger: createTrack() lSessionId: 23
08-31 15:56:32.191  7615  7615 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 15:56:32.191   313  1369 V AudioFlinger: acquiring 23 from 7615, for 7615
08-31 15:56:32.191   313  1369 V AudioFlinger:  added new entry for 23
08-31 15:56:32.191  7615  7615 V ToneGenerator: ToneGenerator INIT OK, time: 227407
08-31 15:56:32.191  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:32.192  7615  7890 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 15:56:32.192  7615  7890 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 15:56:32.192  7615  7890 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 15:56:32.192  7615  7890 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 15:56:32.193   313  1370 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7615
08-31 15:56:32.193   313  1370 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 15:56:32.193   313  1370 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 15:56:32.193   313  1370 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 15:56:32.193   313  1370 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 15:56:32.193   313  1370 V voice   : voice_set_parameters: exit with code(0)
08-31 15:56:32.193   313  1370 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
,08-31 15:56:32.193   313  1370 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 15:56:32.193   313  1370 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 15:56:32.193   313  1370 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 15:56:32.193   313  1370 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 15:56:32.193   313  1370 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 15:56:32.194  7615  7890 V ToneGenerator: ToneGenerator destructor
08-31 15:56:32.194  7615  7890 V ToneGenerator: stopTone
08-31 15:56:32.194  7615  7890 V ToneGenerator: Delete Track: 0xb4928080
08-31 15:56:32.195  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
,08-31 15:56:32.196  7615  7890 V AudioTrack: ~AudioTrack, releasing session id from 7615 on behalf of 7615
,08-31 15:56:32.196   313  1369 V AudioFlinger: releasing 23 from 7615 for 7615
08-31 15:56:32.196   313  1369 V AudioFlinger:  decremented refcount to 0
08-31 15:56:32.196   313  1369 V AudioFlinger: purging stale effects
,08-31 15:56:32.196   313  1369 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 15:56:32.196   313  1369 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 15:56:32.197  7615  7615 D A2dpService: Received start request. Starting profile...
08-31 15:56:32.197   313  1274 V AudioPolicyService: AudioCommandThread() waking up
08-31 15:56:32.197   313  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 15:56:32.197   313  1274 V AudioPolicyManager: releaseOutput() 2
08-31 15:56:32.197   313  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 15:56:32.197   313  1369 V AudioFlinger: PlaybackThread::Track destructor
08-31 15:56:32.197   313  1369 V AudioFlinger: removeClient_l() pid 7615, calling pid 313
08-31 15:56:32.197  7615  7615 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 15:56:32.199  7615  7615 V Avrcp   : make
08-31 15:56:32.200  7615  7615 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 15:56:32.200  7615  7615 I bluedroid-qcom: get_profile_interface avrcp
08-31 15:56:32.208  7615  7615 V AudioManager: registerRemoteController: size of Media player list: 0
,08-31 15:56:32.210  7615  7615 E AudioManager: No RCC entry present to update
08-31 15:56:32.210  7615  7615 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 15:56:32.214  7615  7615 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 15:56:32.215  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 15:56:32.215  7615  7615 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 15:56:32.219  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 15:56:32.309  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:56:32.309  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-31 15:56:32.432  1035  2013 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 15:56:32.442  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-31 15:56:32.447  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 15:56:32.447  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 15:56:32.447  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 15:56:32.447  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 15:56:32.448  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:56:32.448  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
,08-31 15:56:32.448  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 15:56:32.448  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 15:56:32.448  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:56:32.448  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 15:56:32.450  7615  7615 I BluetoothA2dpServiceJni: classInitNative
08-31 15:56:32.450  7615  7615 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:56:32.450  7615  7615 D A2dpStateMachine: make
08-31 15:56:32.451  7615  7615 I bluedroid-qcom: get_profile_interface a2dp
08-31 15:56:32.451  7615  7901 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-31 15:56:32.457  7615  7615 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:56:32.457  7615  7615 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 15:56:32.460  7615  7900 D A2dpStateMachine: Enter Disconnected: -2
08-31 15:56:32.460  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:32.463  7615  7615 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 15:56:32.467  7615  7615 D HidService: Received start request. Starting profile...
08-31 15:56:32.467  7615  7615 I bluedroid-qcom: get_profile_interface hidhost
08-31 15:56:32.467  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
,08-31 15:56:32.467  7615  7615 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:56:32.469  7615  7615 D HealthService: Received start request. Starting profile...
,08-31 15:56:32.473  7615  7615 I bluedroid-qcom: get_profile_interface health
08-31 15:56:32.473  7615  7615 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:56:32.474  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:32.476  7615  7615 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 15:56:32.481  7615  7615 D PanService: Received start request. Starting profile...
,08-31 15:56:32.482  7615  7615 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 15:56:32.482  7615  7615 I bluedroid-qcom: get_profile_interface pan
,08-31 15:56:32.665  1035  2035 I art     : Explicit concurrent mark sweep GC freed 28533(1429KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.328ms total 171.357ms
,08-31 15:56:32.666  7615  7615 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 15:56:32.666  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:32.667  7615  7615 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 15:56:32.673  7615  7615 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:56:32.674  7615  7615 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:56:32.674  7615  7615 D BtGatt.GattService: start()
08-31 15:56:32.674  7615  7615 I bluedroid-qcom: get_profile_interface gatt
08-31 15:56:32.674  7615  7615 D BtGatt.AdvertiseManager: advertise manager created
08-31 15:56:32.683  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
,08-31 15:56:32.684  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:32.685  7615  7615 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 15:56:32.686  7615  7615 V BluetoothMapService: BluetoothMapBinder()
08-31 15:56:32.687  7615  7615 D BluetoothMapService: Received start request. Starting profile...
08-31 15:56:32.687  7615  7615 D BluetoothMapService: start()
08-31 15:56:32.690  7615  7615 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 15:56:32.690  7615  7615 D BluetoothMapEmailAppObserver: createReceiver()
08-31 15:56:32.691  7615  7615 D BluetoothMapEmailAppObserver: initObservers()
08-31 15:56:32.692  7615  7615 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 15:56:32.700  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:32.700  7615  7615 D HeadsetStateMachine: Proxy object connected
,08-31 15:56:32.701  7615  7615 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 15:56:32.701  7615  7615 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 15:56:32.703  7615  7890 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 15:56:32.703  7615  7890 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 15:56:32.703  7615  7890 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 15:56:32.707  7615  7615 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:56:32.710  7615  7615 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:56:32.712  7615  7615 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:32.715  7615  7615 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 15:56:32.718  7615  7615 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:56:32.721  7615  7615 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 15:56:32.722  7615  7615 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 15:56:32.725  7615  7615 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 15:56:32.725  7615  7615 V BluetoothMapService: Handler(): got msg=1
08-31 15:56:32.726  7615  7615 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:56:32.726  7615  7615 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:56:32.726  7615  7615 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:56:32.726  7615  7615 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:32.726  7615  7615 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 15:56:32.726  7615  7870 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 15:56:32.727  7615  7870 I bluedroid-qcom: enable
08-31 15:56:32.727  7615  7870 I bt_hci_bdroid: init
08-31 15:56:32.729  7615  7909 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 15:56:32.729  7615  7909 I bt-btu  : btu_task pending for preload complete event
08-31 15:56:32.732  7615  7870 I bt_vendor: bt-vendor : init
08-31 15:56:32.732  7615  7870 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 15:56:32.732  7615  7870 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 15:56:32.732  7615  7870 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 15:56:32.732  7615  7870 D bt_userial_mct: userial_init
08-31 15:56:32.733  7615  7870 D bt_hci_bdroid: set_power 1
08-31 15:56:32.733  7615  7870 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 15:56:32.733  7615  7870 I bt_vendor: Starting hciattach daemon
08-31 15:56:32.733  7615  7870 I bt_vendor: try to set true
,08-31 15:56:32.725  7912  7912 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:32.725  7912  7912 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:32.771  7913  7913 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 15:56:32.880  7919  7919 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 15:56:32.893  7920  7920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-31 15:56:32.924  7922  7922 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 15:56:32.947  7923  7923 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 15:56:32.960  7924  7924 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 15:56:32.974  7925  7925 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 15:56:32.998  7927  7927 I libmdmdetect: ESOC framework not supported
,08-31 15:56:33.000  7927  7927 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 15:56:33.013  7927  7927 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 15:56:33.013  7927  7927 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 15:56:33.013  7927  7927 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 15:56:33.013  7927  7927 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 15:56:33.013  7927  7927 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 15:56:33.013  7927  7927 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 15:56:33.013  7927  7927 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 15:56:33.056  7927  7928 E QC-QMI  : qmi_client [7927] 15: failed to locate client data
,08-31 15:56:33.057   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 15:56:33.057   479   479 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-31 15:56:33.116  7935  7935 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 15:56:33.131  7936  7936 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 15:56:33.187  7615  7870 I bt_vendor: bluetooth satus is on
,08-31 15:56:33.188  7615  7870 D bt_hci_bdroid: preload
08-31 15:56:33.193  7615  7911 D bt_userial_mct: userial_open(port:0)
,08-31 15:56:33.194  7615  7911 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 15:56:33.203  7615  7911 I bt_vendor: Done intiailizing UART
08-31 15:56:33.209  7615  7911 I bt_vendor: Done intiailizing UART
08-31 15:56:33.209  7615  7911 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 15:56:33.210  7615  7911 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-31 15:56:33.211  7615  7909 I bt-btu  : btu_task received preload complete event
,08-31 15:56:33.211  7615  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-31 15:56:33.212  7615  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 15:56:33.214  7615  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 15:56:33.216  7615  7938 D bt_userial_mct: Entering userial_read_thread()
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_AVRC,
,08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_A2D,
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_BTM,
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_SDP,
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_SMP
,08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 15:56:33.218  7615  7909 I         : BTE_InitTraceLevels -- TRC_BTIF,
08-31 15:56:33.329  7615  7909 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-31 15:56:33.329  7615  7909 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ed061 
08-31 15:56:33.329  7615  7909 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ed061 
,08-31 15:56:33.384  7615  7874 E bt-btif : Calling BTA_HhEnable
08-31 15:56:33.384  7615  7874 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-31 15:56:33.389  7615  7874 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 15:56:33.392  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 15:56:33.393  7615  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 15:56:33.393  7615  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-31 15:56:33.393  7615  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 15:56:33.393  7615  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 15:56:33.394  7615  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 15:56:33.396  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 15:56:33.396  7615  7874 D BluetoothAdapterProperties: Name is: G3
08-31 15:56:33.399  7615  7874 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:56:33.399  7615  7874 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:56:33.400  7615  7874 D bt_hci_bdroid: postload
,08-31 15:56:33.406  7615  7911 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:56:33.407  7615  7911 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:56:33.407  7615  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 15:56:33.408  7615  7874 D bte_conf: Device ID record 1 : primary
08-31 15:56:33.408  7615  7874 D bte_conf:   vendorId            = 00c4
08-31 15:56:33.408  7615  7874 D bte_conf:   vendorIdSource      = 0001
08-31 15:56:33.408  7615  7874 D bte_conf:   product             = 13a1
08-31 15:56:33.408  7615  7874 D bte_conf:   version             = 1000
08-31 15:56:33.408  7615  7874 D bte_conf:   clientExecutableURL = 
08-31 15:56:33.408  7615  7874 D bte_conf:   serviceDescription  = 
08-31 15:56:33.408  7615  7874 D bte_conf:   documentationURL    = 
08-31 15:56:33.408  7615  7874 D bte_conf: bte_load_did_conf no section named DID2.
08-31 15:56:33.411  7615  7911 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 15:56:33.412  7615  7870 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 15:56:33.412  7615  7870 D BluetoothAdapterProperties: ScanMode =  20
08-31 15:56:33.412  7615  7870 D BluetoothAdapterProperties: State =  11
08-31 15:56:33.412  7615  7870 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 15:56:33.413  7615  7870 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 15:56:33.413  7615  7870 D BluetoothAdapterProperties: Setting state to 12
08-31 15:56:33.413  7615  7870 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 15:56:33.413  7615  7874 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 15:56:33.416  7615  7911 D bt_hci_bdroid: Used up Tx Cmd credits
,08-31 15:56:33.405  7940  7940 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:33.421  1035  1117 D BluetoothManagerService: Message: 60
08-31 15:56:33.421  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 15:56:33.421  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-31 15:56:33.421  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:56:33.423  7615  7938 E bt_mct  : hci lib postload completed
08-31 15:56:33.405  7940  7940 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:33.428  7615  7874 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 15:56:33.435  7615  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:33.435  7615  7909 W bt-smp  : Plain text(LSB ~ MSB) = dd 58 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:33.435  7615  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = 00 db 2f 4a 51 dd 6d b6 27 10 9a 06 81 40 54 8d 
08-31 15:56:33.435  7615  7909 W bt-btm  : Stopping oneshot timer
08-31 15:56:33.437  7615  7870 I BluetoothAdapterState: Entering On State
08-31 15:56:33.459  7615  7874 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:56:33.460  7615  7874 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-31 15:56:33.469  7615  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:33.469  7615  7909 W bt-smp  : Plain text(LSB ~ MSB) = a2 57 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:33.469  7615  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = c0 6d 90 84 58 7a 26 af 54 20 40 37 c9 74 64 1a 
08-31 15:56:33.470  7615  7909 W bt-btm  : Stopping oneshot timer
08-31 15:56:33.471  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:33.471  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:33.471  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:33.471  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:33.471  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:33.471  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:33.471  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:33.471  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:33.479  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:56:33.484  6777  6808 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:56:33.494  7615  7870 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 15:56:33.494  7615  7870 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 15:56:33.494  7615  7870 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-31 15:56:33.497  7615  7870 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 15:56:33.497  7615  7870 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 15:56:33.498  7615  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:33.498  7615  7909 W bt-smp  : Plain text(LSB ~ MSB) = 7a 9e 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:33.498  7615  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = 76 a2 aa 2f 43 19 45 8b d1 cd 98 ef 2c eb 6a d6 
08-31 15:56:33.498  7615  7909 W bt-btm  : Stopping oneshot timer
08-31 15:56:33.498  1035  1035 D BluetoothHeadset: Proxy object connected
08-31 15:56:33.508  6777  7490 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 15:56:33.523  7615  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:33.523  7615  7909 W bt-smp  : Plain text(LSB ~ MSB) = 4f d0 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:33.523  7615  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = 79 ad fb 11 75 d5 a5 27 fc fc 2a 36 3f ca 6f 04 
,08-31 15:56:33.526  7615  7909 W bt-btm  : Stopping oneshot timer
08-31 15:56:33.531  6777  6794 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 15:56:33.539  7615  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 15:56:33.539  7615  7909 W bt-smp  : Plain text(LSB ~ MSB) = c4 bd 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 15:56:33.539  7615  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = f2 ba e9 71 7c b5 87 9e 5a 3f 57 54 bd f9 83 58 
08-31 15:56:33.540  7615  7909 W bt-btm  : Stopping oneshot timer
,08-31 15:56:33.549  1836  3965 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:56:33.554  6777  6777 D BluetoothA2dp: Proxy object connected
08-31 15:56:33.554  6777  6777 D A2dpProfile: Bluetooth service connected
,08-31 15:56:33.560  1836  1836 D BluetoothHeadset: Proxy object connected
08-31 15:56:33.561  7958  7958 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 15:56:33.562  6777  7490 D BluetoothMap: onBluetoothStateChange: up=true
08-31 15:56:33.563  6777  6777 D BluetoothInputDevice: Proxy object connected
08-31 15:56:33.563  6777  6777 D HidProfile: Bluetooth service connected
08-31 15:56:33.565  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:56:33.566  6777  6777 D BluetoothMap: Proxy object connected
08-31 15:56:33.566  6777  6777 D MapProfile: Bluetooth service connected
,08-31 15:56:33.566  6777  6777 D BluetoothMap: getConnectedDevices()
08-31 15:56:33.567  7615  7632 V BluetoothMapService: getConnectedDevices()
,08-31 15:56:33.568  1836  1836 D BluetoothHeadset: Proxy object connected
08-31 15:56:33.569  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:56:33.569  1035  1035 D BluetoothA2dp: Proxy object connected
08-31 15:56:33.569  6777  6808 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:56:33.571  6777  6777 D BluetoothHeadset: Proxy object connected
08-31 15:56:33.571  6777  6777 D HeadsetProfile: Bluetooth service connected
08-31 15:56:33.571  6777  6794 D BluetoothPan: onBluetoothStateChange on: true
08-31 15:56:33.571  6777  6794 D BluetoothPan: onBluetoothStateChange call bindService
08-31 15:56:33.573  1836  2449 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:56:33.573  6777  6777 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:56:33.574  6777  6777 D PanProfile: Bluetooth service connected
08-31 15:56:33.574  1836  1836 D BluetoothHeadset: Proxy object connected
08-31 15:56:33.575  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 15:56:33.575  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 15:56:33.576  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 15:56:33.577  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 15:56:33.580  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:33.580  1925  2126 D LGBluetoothAPIService: Message: 1
08-31 15:56:33.580  1925  2126 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 15:56:33.581  1035  1117 D BluetoothManagerService: Message: 40
08-31 15:56:33.581  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-31 15:56:33.584  7615  7615 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:33.584  7615  7615 D BluetoothMapService: STATE_ON
08-31 15:56:33.584  7615  7615 V BluetoothMapService: Handler(): got msg=1
08-31 15:56:33.585  7615  7615 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 15:56:33.587  7615  7962 D BluetoothMapMasInstance: MAS initSocket()
08-31 15:56:33.587  7615  7962 D BluetoothMapMasInstance:   masId = 00
08-31 15:56:33.587  7615  7962 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 15:56:33.587  7615  7962 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 15:56:33.587  7615  7962 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 15:56:33.588  1035  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:33.588  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:33.589  7615  7962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:33.589  1925  2126 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 15:56:33.590  7615  7962 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
,08-31 15:56:33.590  7615  7874 D BluetoothAdapterProperties: Scan Mode:21
08-31 15:56:33.591  7615  7874 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 15:56:33.593  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:56:33.595  7615  7962 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 15:56:33.596  7615  7962 D BluetoothMapMasInstance: Accepting socket connection...
08-31 15:56:33.598  6777  6777 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 15:56:33.599  6777  6777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 15:56:33.603  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:33.603  7615  7615 V BluetoothPbapService: Pbap Service onCreate
,08-31 15:56:33.603  7615  7615 V BluetoothPbapService: Starting PBAP service
08-31 15:56:33.604  7615  7615 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 15:56:33.605  7615  7615 V BluetoothPbapService: Pbap Service onBind
08-31 15:56:33.607  7615  7615 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:33.607  7615  7615 V BluetoothPbapService: state: 12
08-31 15:56:33.608  6777  6777 D DockEventReceiver: finishStartingService: stopping service
08-31 15:56:33.608  7615  7615 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 15:56:33.608  6777  6777 D BluetoothPbap: Proxy object connected
08-31 15:56:33.608  7615  7615 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 15:56:33.608  6777  6777 D PbapServerProfile: Bluetooth service connected
08-31 15:56:33.609  7615  7615 V BluetoothPbapService: Handler(): got msg=1
08-31 15:56:33.610  7615  7615 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 15:56:33.610  7615  7615 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 15:56:33.610  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 15:56:33.610  7615  7615 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:33.610  1925  2126 D LGBluetoothAPIService: Message: 100
08-31 15:56:33.610  1925  2126 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 15:56:33.610  7615  7615 V BluetoothPbapReceiver: ***********state = 12
08-31 15:56:33.613  7615  7965 V BluetoothPbapService: Pbap Service initSocket
08-31 15:56:33.614  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:56:33.614  1035  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:33.614  2203  2203 D c       : Getting all permits...
08-31 15:56:33.614  2203  2203 D a       : Opening database...
08-31 15:56:33.615  7615  7965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:33.618  2203  2203 D a       : Opening database auth.proximity.permit_store...
,08-31 15:56:33.619  2203  2203 D a       : Closing database...
08-31 15:56:33.625  7615  7965 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 15:56:33.626  7615  7965 V BluetoothPbapService: Succeed to create listening socket 
08-31 15:56:33.626  7615  7965 V BluetoothPbapService: Accepting socket connection...
08-31 15:56:33.630  6777  6777 D BluetoothPermissionRequest: onReceive
,08-31 15:56:33.632  6777  6777 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 15:56:33.634  6777  6777 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 15:56:33.637  7615  7615 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 15:56:33.638  7615  7615 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 15:56:33.643  7615  7615 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-31 15:56:33.658  7615  7615 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 15:56:33.658  7615  7615 V BtOppService: onCreate
08-31 15:56:33.661  7615  7615 V BluetoothOppNotification: send message
08-31 15:56:33.663  7615  7615 V BtOppService: Starting RfcommListener
08-31 15:56:33.666  7615  7615 D BluetoothOppPreference: Dumping Names:  
08-31 15:56:33.666  7615  7615 D BluetoothOppPreference: {}
08-31 15:56:33.666  7615  7615 D BluetoothOppPreference: Dumping Channels:  
08-31 15:56:33.666  7615  7615 D BluetoothOppPreference: {}
08-31 15:56:33.667  7615  7615 V BtOppService: onStartCommand
08-31 15:56:33.668  7615  7972 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 15:56:33.669  7615  7615 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:33.669  7615  7615 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 15:56:33.671  7615  7615 V BluetoothOppNotification: new notify threadi!
,08-31 15:56:33.671  7615  7615 V BluetoothOppNotification: send delay message
08-31 15:56:33.672  7615  7615 V BtOppService: start RfcommListener
08-31 15:56:33.675  7615  7615 V BtOppService: RfcommListener started
08-31 15:56:33.676  7615  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 15:56:33.676  7615  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 15:56:33.677  7615  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b51ad00 on behalf of 
,08-31 15:56:33.678  7615  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@327cd939 on behalf of 
08-31 15:56:33.678  7615  7973 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 15:56:33.679  7615  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 15:56:33.680  7615  7972 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 15:56:33.680  7615  7969 V BtOppService: Deleted complete outbound shares, number =  0
,08-31 15:56:33.682  7615  7969 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 15:56:33.683  7615  7969 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 15:56:33.684  7615  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@46e0b7e on behalf of 
08-31 15:56:33.684  7615  7973 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 15:56:33.685  7615  7969 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bcf78df on behalf of 
08-31 15:56:33.686  7615  7973 V BluetoothOppNotification: outbound notification was removed.
08-31 15:56:33.686  7615  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 15:56:33.687  7615  7974 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 15:56:33.687  1035  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:33.688  7615  7974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:33.688  7615  7974 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-31 15:56:33.689  7615  7974 V BtOppRfcommListener: Started RFCOMM listener....
08-31 15:56:33.689  7615  7974 I BtOppRfcommListener: Accept thread started.
08-31 15:56:33.689  7615  7974 V BtOppRfcommListener: Accepting connection...
08-31 15:56:33.690  7615  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19a4992c on behalf of 
08-31 15:56:33.690  7615  7973 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 15:56:33.691  7615  7973 V BluetoothOppNotification: inbound notification was removed.
08-31 15:56:33.691  7615  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 15:56:33.693  7615  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35c8cff5 on behalf of 
08-31 15:56:33.698  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:33.698  7615  7615 V BluetoothFtpService: Ftp Service onCreate
08-31 15:56:33.698  7615  7615 I BluetoothFtpService: Ftp Service onCreate
08-31 15:56:33.698  7615  7615 V BluetoothFtpService: Ftp Service onStartCommand
08-31 15:56:33.698  7615  7615 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:33.699  7615  7615 V BluetoothFtpService: Starting Listening on sockets
08-31 15:56:33.699  7615  7615 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 15:56:33.699  7615  7615 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 15:56:33.699  7615  7615 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 15:56:33.699  7615  7615 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:33.699  7615  7615 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 15:56:33.699  7615  7615 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-31 15:56:33.701  7615  7615 V BtOppService: ContentObserver received notification
08-31 15:56:33.701  7615  7615 V BtOppService: ContentObserver received notification
08-31 15:56:33.702  7615  7615 V BluetoothFtpService: Handler(): got msg=1
08-31 15:56:33.702  7615  7615 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 15:56:33.702  7615  7615 V BluetoothFtpService: Ftp Service initSocket
08-31 15:56:33.704  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:56:33.705  7615  7976 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 15:56:33.705  7615  7976 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 15:56:33.706  7615  7976 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@335cc3fb on behalf of 
08-31 15:56:33.707  7615  7615 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:33.707  7615  7976 V BluetoothOppNotification: update too frequent, put in queue
08-31 15:56:33.708  7615  7976 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 15:56:33.708  7615  7615 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-31 15:56:33.708  7615  7615 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 15:56:33.709  7615  7977 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-31 15:56:33.721  7615  7615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a398917
08-31 15:56:33.721  7615  7615 V BluetoothSapService: Sap Service onCreate
,08-31 15:56:33.723  7615  7615 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:56:33.723  7615  7615 V BluetoothSapService: state: 12
08-31 15:56:33.723  7615  7615 V BluetoothSapService: Starting SAP server process
,08-31 15:56:33.715  7978  7978 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 15:56:33.715  7978  7978 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:33.727  7615  7615 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 15:56:33.728  7615  7979 V BluetoothSapService: Sap Service initRfcommSocket
08-31 15:56:33.728  1035  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:33.729  7615  7979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:56:33.730  7615  7979 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 15:56:33.730  7615  7979 V BluetoothSapService: Succeed to create listening socket 
08-31 15:56:33.731  7615  7979 V BluetoothSapService: Accepting socket connection...
08-31 15:56:33.737  7978  7978 V BT_SAP  : Event pipe created
08-31 15:56:33.737  7978  7978 V BT_SAP  : create_server_socket qcom.sap.server
08-31 15:56:33.737  7978  7978 V BT_SAP  : created socket fd 6
,08-31 15:56:34.018  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:34.018  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:34.018  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:34.018  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:56:34.018  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:34.018  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:34.018  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:34.018  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:56:34.022  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:34.024  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:34.024  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d735f91 added. We now have 8 listener(s)
08-31 15:56:34.024  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:34.034  1035  2035 D WifiServiceImplEx: setWifiEnabled: false pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:56:34.035  1035  2035 D WifiService: setWifiEnabled: false pid=6692, uid=10118
08-31 15:56:34.035  1035  2035 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:56:34.042  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:34.043  1035  2013 D WifiServiceImplEx: setWifiEnabled: true pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 15:56:34.044  1035  2013 D WifiService: setWifiEnabled: true pid=6692, uid=10118
08-31 15:56:34.044  1035  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 15:56:34.057  1035  1521 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 15:56:34.057  1035  1521 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-31 15:56:34.062  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 15:56:34.062  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 15:56:34.062  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 15:56:34.062  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 15:56:34.062  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 15:56:34.063  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 15:56:34.063  1035  1521 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 15:56:34.063  1035  1521 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 15:56:34.063  1035  1521 E WifiHW  : unknown target_country: EU , set to default
08-31 15:56:34.063  1035  1521 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 15:56:34.063  1035  1521 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 15:56:34.063  1035  1521 I WifiUtil: gEnableBmps=1
08-31 15:56:34.641   309   893 D SoftapController: Softap fwReload - Ok
,08-31 15:56:34.759  7615  7615 V BluetoothOppNotification: new notify threadi!
,08-31 15:56:34.760  7615  7615 V BluetoothOppNotification: send delay message
08-31 15:56:34.765  7615  8007 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-31 15:56:34.769  7615  8007 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36a9a4d7 on behalf of 
08-31 15:56:34.770  7615  8007 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 15:56:34.774  7615  8007 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 15:56:34.775  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:56:34.775  1035  1117 D Tethering: InitialState.processMessage what=4
08-31 15:56:34.777  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 15:56:34.777  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:56:34.777  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:56:34.777  6777  6777 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 15:56:34.778  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:56:34.778  1035  1521 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (707ms)
08-31 15:56:34.780   309   893 D CommandListener: Setting iface cfg
08-31 15:56:34.780   309   893 D CommandListener: Trying to bring down wlan0
08-31 15:56:34.781   309   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:56:34.783  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-31 15:56:34.785  6777  6777 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:56:34.785  1035  1521 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-31 15:56:34.786  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 15:56:34.786  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:56:34.786  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:56:34.786  6777  6777 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 15:56:34.786  6777  6777 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 15:56:34.788  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:56:34.788  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:56:34.788  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:56:34.775  8016  8016 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:34.789  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 15:56:34.789  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:56:34.789  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:56:34.789  6777  6777 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 15:56:34.789  1035  1521 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 15:56:34.789  1035  1521 D WifiMonitor: connecting to supplicant
08-31 15:56:34.791  7615  8007 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bbee1c4 on behalf of 
08-31 15:56:34.791  7615  8007 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 15:56:34.793  7615  8007 V BluetoothOppNotification: outbound notification was removed.
08-31 15:56:34.793  7615  8007 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 15:56:34.794  7615  8007 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@aa808ad on behalf of 
08-31 15:56:34.795  7615  8007 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-31 15:56:34.804  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 15:56:34.804  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:34.775  8016  8016 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:34.805  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 15:56:34.808  7615  8007 V BluetoothOppNotification: inbound notification was removed.
08-31 15:56:34.808  7615  8007 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-31 15:56:34.810  7615  8007 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1efe97e2 on behalf of 
08-31 15:56:34.811  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:34.812  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 15:56:34.812  6777  6777 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:56:34.812  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 15:56:34.812  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:56:34.813  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:56:34.813  6777  6777 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 15:56:34.813  6777  6777 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 15:56:34.814  8016  8016 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 15:56:34.848  8016  8016 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 15:56:34.849  8016  8016 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 15:56:34.852  1035  1906 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8018 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-31 15:56:34.882  8016  8016 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 15:56:34.929  8016  8016 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 15:56:34.939  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 15:56:34.939  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 15:56:34.940  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-31 15:56:34.941  1035  1521 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 15:56:34.941  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:34.942  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:34.943  1035  1521 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:34.943  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:34.944  1035  1521 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 15:56:34.944  1035  1521 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 15:56:34.945  1035  1521 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 15:56:34.945  1035  1521 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 15:56:34.945  1035  1521 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 15:56:34.956  8016  8016 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 15:56:34.956  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 15:56:34.956  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 15:56:34.956  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 15:56:34.956  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 15:56:34.956  1035  8037 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 15:56:34.956  1035  8037 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-31 15:56:35.008  1035  2013 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8040 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 15:56:35.010  1035  1521 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 15:56:35.010  1035  1521 E WifiStateMachine: useWiFiOffloading() : false
08-31 15:56:35.010  1035  1521 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 15:56:35.011  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.011  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.011  1035  1521 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 15:56:35.012  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.014  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.015  8018  8038 W FormManager: Network not available. Please check & try again.
08-31 15:56:35.016  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-31 15:56:35.016  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 15:56:35.019  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 15:56:35.020  1035  1525 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 15:56:35.020  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.022  1035  1521 D WifiNative-wlan0: SET update_config 1: returned true
08-31 15:56:35.022  1035  1521 D WifiConfigStore: Loading config and enabling all networks 
08-31 15:56:35.022  1035  1521 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 15:56:35.023  1035  1521 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-31 15:56:35.030  1035  1521 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 15:56:35.031  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:35.031  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:35.031  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:35.031  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:35.031  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:35.031  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:35.031  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:35.031  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:35.037  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:56:35.038  1035  1521 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 15:56:35.038  1035  1521 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 15:56:35.038  8018  8039 V FormManager: Network unavailable.
08-31 15:56:35.039  1035  1521 D WifiStateMachine: enableVerboseLogging : level 2
08-31 15:56:35.039  1035  1521 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 15:56:35.040  1035  1521 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 15:56:35.040  1035  1521 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 15:56:35.040  1035  1521 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 15:56:35.040  1035  1521 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 15:56:35.041  1035  1521 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 15:56:35.041  1035  1521 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 15:56:35.041  8018  8039 V FormManager: Network unavailable.
08-31 15:56:35.041  1035  1521 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 15:56:35.041  1035  1521 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 15:56:35.041  1035  1521 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 15:56:35.041  1035  1521 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 15:56:35.042  1035  1521 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 15:56:35.042  1035  1521 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 15:56:35.042  1035  1521 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 15:56:35.044  1035  1521 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:56:35.044  1035  1521 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 15:56:35.044  1035  1521 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 15:56:35.044  1035  1521 D WifiNative-HAL: Setting external_sim to 1
08-31 15:56:35.044  1035  1521 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 15:56:35.045  1035  1521 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 15:56:35.045  1035  1521 I WifiNative-HAL: startHal
08-31 15:56:35.045  1035  1521 D wifi    : setting scan oui 0xaf6e21e0
08-31 15:56:35.045  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-31 15:56:35.045  1925  2306 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 15:56:35.045  1925  2306 D WfdsService: Set the WFDS Monitor: true
08-31 15:56:35.045  1925  2306 D WfdsMonitor: WfdsMonitorThread create
08-31 15:56:35.045  1035  1521 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:56:35.045  1035  1521 I WifiNative-HAL: startHal
08-31 15:56:35.045  1035  1521 D wifi    : setting scan oui 0xaf6e21e0
08-31 15:56:35.045  1925  2306 D WfdsMonitor: WFDS Monitor is created and started
08-31 15:56:35.045  1925  2306 D WfdsService: WiFi: Supplicant connection re-established
08-31 15:56:35.045  1035  1521 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 15:56:35.047  1035  1521 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 15:56:35.047  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 15:56:35.047  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 15:56:35.047  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 15:56:35.047  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 15:56:35.048  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 15:56:35.048  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 15:56:35.048  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 15:56:35.048  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-3,1 15:56:35.049  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 15:56:35.049  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 15:56:35.049  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 15:56:35.049  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 15:56:35.049  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 15:56:35.049  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 15:56:35.050  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 15:56:35.050  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 15:56:35.050  8016  8016 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 15:56:35.050  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 15:56:35.050  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 15:56:35.051  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 15:56:35.051  1035  1521 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 15:56:35.052  1035  1521 E WifiNative: : [230,254,739 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 15:56:35.052  1035  1521 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 15:56:35.052  1035  1521 D WifiNative-wlan0: RECONNECT: returned true
08-31 15:56:35.052  1035  1521 D WifiNative-wlan0: doString: [STATUS]
08-31 15:56:35.053  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 15:56:35.053  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 15:56:35.053  1035  1521 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 15:56:35.053  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:56:35.053  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:56:35.054  1035  1520 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.054  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 15:56:35.055  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-31 15:56:35.055  1035  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.055  1035  1540 I WifiNative-HAL: startHal
08-31 15:56:35.055  1035  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf6e21e0
08-31 15:56:35.055  1035  1540 D wifi    : failed to get capabilities : -3
08-31 15:56:35.055  1035  1540 E WifiScanningService: could not get scan capabilities
08-31 15:56:35.056   309   893 D CommandListener: Setting iface cfg
08-31 15:56:35.056   309   893 D CommandListener: Trying to bring up p2p0
08-31 15:56:35.056  1925  8058 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-31 15:56:35.056  1925  8058 E CtrlSupplicant: Succeed to open control connection
08-31 15:56:35.056  1035  1520 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 15:56:35.056  1035  1520 D LGWifiP2pService: P2pEnablingState
08-31 15:56:35.056  1035  1520 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.057  1925  8058 E CtrlSupplicant: Succeed to open monitor connection
08-31 15:56:35.057  1035  1520 D LGWifiP2pService: P2p socket connection successful
08-31 15:56:35.057  1035  1520 D LGWifiP2pService: P2pEnabledState
08-31 15:56:35.057  1035  1541 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.057  1035  1520 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 15:56:35.058  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 15:56:35.058  1925  1925 D WfdsService: WifiP2pState is changed : true
08-31 15:56:35.058  1925  2306 D WfdsService: Receive the WFDS_ENABLE Method
08-31 15:56:35.058  1925  2306 D WfdsService: Set the WFDS Monitor: true
08-31 15:56:35.058  1925  2306 D WfdsService: Connected to the supplicant for wfds
08-31 15:56:35.058  1925  2306 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 15:56:35.058  8016  8016 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 15:56:35.058  1925  8058 D WfdsMonitor: Supplicant connection established
08-31 15:56:35.058  1925  2306 D WfdsService: selectPreferredScanChannel [36]
08-31 15:56:35.058  1925  2306 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 15:56:35.059  1925  2306 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-31 15:56:35.062  1035  1520 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 15:56:35.062  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 15:56:35.062  1035  1520 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 15:56:35.062  1925  1925 D WfdsService: isConnected: false
08-31 15:56:35.063  7652  7652 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.064  1035  1520 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 15:56:35.065  1035  1520 D WifiNative-p2p0: SET device_name G3: returned true
08-31 15:56:35.065  1035  1520 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 15:56:35.065  1035  1520 D LGWifiP2pService: before postfix = G3
08-31 15:56:35.065  1035  1520 D WifiServerServiceExt: postfix byte check : 2
08-31 15:56:35.065  1035  1520 D LGWifiP2pService: after postfix = G3
08-31 15:56:35.065  1035  1520 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 15:56:35.065  1035  1520 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 15:56:35.066  1035  1520 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 15:56:35.066  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 15:56:35.066  1035  1520 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 15:56:35.066  1035  1520 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 15:56:35.066  1035  1521 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 15:56:35.067  1035  1521 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
,08-31 15:56:35.067  1035  1520 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 15:56:35.067  1035  1520 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 15:56:35.067  1035  1521 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 15:56:35.067  1035  1520 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 15:56:35.067  1035  1520 D WifiNative-HAL: p2pGetDeviceAddress
08-31 15:56:35.067  1035  1520 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 15:56:35.067  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=230271  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 15:56:35.071  1035  1520 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 15:56:35.071  1035  1520 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 15:56:35.071  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=230275  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 15:56:35.072  1035  1521 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 15:56:35.072  1035  1521 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 15:56:35.073  1035  1521 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 15:56:35.073  1035  1521 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 15:56:35.073  8016  8016 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 15:56:35.073  1035  1521 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 15:56:35.074  1035  1520 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 15:56:35.074  1035  1521 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 15:56:35.074  1035  1520 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 15:56:35.074  1035  1520 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 15:56:35.074  1035  1520 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 15:56:35.074  1035  1521 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 15:56:35.074  1035  1521 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 15:56:35.074  8016  8016 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 15:56:35.074  1035  1520 D WifiNative-p2p0:    returned OK
08-31 15:56:35.075  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 15:56:35.075  1035  1520 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 15:56:35.075  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:56:35.075  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:35.075  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:35.075  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:35.075  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:35.075  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:56:35.075  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:56:35.075  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:56:35.075  1035  1521 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 15:56:35.075  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 15:56:35.075  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 15:56:35.075  1925  1925 D WfdsService: Update P2p Interface State: 3
08-31 15:56:35.076  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:35.076  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:35.076  ,1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.076  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.076  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 15:56:35.077  1035  1521 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 15:56:35.077  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 15:56:35.077  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.077  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:56:35.081  6692  6758 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 15:56:35.082  6692  6758 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 15:56:35.083  6692  6758 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ff9522b Bundle[{}]
08-31 15:56:35.084  6692  6758 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 15:56:35.085  6692  6758 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 15:56:35.085  1035  1520 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 15:56:35.085  1035  1520 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 15:56:35.085  1035  1520 D LGWifiP2pService: InactiveState
08-31 15:56:35.085  1035  1520 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.085  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.085  1035  1520 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 15:56:35.085  6692  6758 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 15:56:35.085  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 15:56:35.086  8016  8016 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:35.086  1035  8037 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:56:35.086  1035  8037 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:35.086  1035  8037 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:35.086  1035  8037 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:35.086  8016  8016 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 15:56:35.087  8016  8016 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.087  6692  6758 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 15:56:35.087  1035  8037 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:35.087  1035  8037 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.087  1035  8037 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.087  1035  8037 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.087  1035  1520 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 15:56:35.087  6692  6758 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 15:56:35.087  1035  1520 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.087  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.087  8016  8016 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.087  1035  1520 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.087  1035  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:56:35.087  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.087  1035  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.088  6692  6758 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 15:56:35.088  1035  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.088  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.088  1035  1520 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.088  1925  8058 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:56:35.088  1925  8058 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:35.088  1925  8058 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:35.088  1925  2306 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 15:56:35.088  1035  1520 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.088  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.088  1035  8037 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:35.088  1035  8037 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.088  1035  1520 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.088  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 15:56:35.089  8016  8016 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:35.089  1035  1035 E WifiServerServiceExt: No p2p device connected
08-31 15:56:35.090  8016  8016 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 15:56:35.090  8016  8016 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.090  1035  1521 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 15:56:35.090  1035  1521 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:56:35.090  8016  8016 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.090  1035  1521 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:56:35.091  1035  1521 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 15:56:35.091  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 15:56:35.091  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 15:56:35.091  1035  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.091  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.091  8016  8016 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:56:35.091  1925  8058 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:35.091  1925  8058 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:35.092  1035  1521 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 15:56:35.092  1035  1521 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 15:56:35.092  1035  1521 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 15:56:35.092  6692  6758 I System.out: Running OutgoingSocketThread
08-31 15:56:35.092  1035,  1521 D WifiNative-wlan0: doBoolean: SCAN
08-31 15:56:35.092  1035  8037 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.092  1035  8037 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.092  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 15:56:35.092  1035  1521 D WifiNative-wlan0: SCAN: returned false
08-31 15:56:35.092  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:35.092  1035  8037 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:35.093  1035  8037 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 15:56:35.093  1035  8037 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:35.093  1035  8037 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.093  1035  8037 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.093  1035  8037 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.093  1035  8037 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 15:56:35.093  1035  8037 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.093  1035  8037 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.093  1035  8037 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 15:56:35.093  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 15:56:35.093  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:56:35.093  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=230296  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 15:56:35.093  1035  8037 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:56:35.093  1035  8037 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 15:56:35.094  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=230297  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 15:56:35.094  6692  8060 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 871)
08-31 15:56:35.094  1035  1521 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-31 15:56:35.096  6692  8060 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 33857
08-31 15:56:35.096  6692  8060 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 15:56:35.096  1035  1521 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:56:35.096  1035  1521 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:56:35.096  1035  1521 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:56:35.097  1035  1521 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 15:56:35.098  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.098  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.098  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 15:56:35.098  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:35.098  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:35.099  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:35.099  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 15:56:35.099  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.100  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:35.100  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 15:56:35.114  8040  8040 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:56:35.117  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 15:56:35.121  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:35.122  1035  2016 I ActivityManager: Killing 7154:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-31 15:56:35.271  1035  1942 W libprocessgroup: failed to open /acct/uid_10093/pid_7154/cgroup.procs: No such file or directory
,08-31 15:56:35.307  8040  8040 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 15:56:35.328  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:56:35.334  8018  8064 W FormManager: Network not available. Please check & try again.
08-31 15:56:35.339  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:35.346  8018  8065 V FormManager: Network unavailable.
,08-31 15:56:35.351  8018  8065 V FormManager: Network unavailable.
08-31 15:56:35.366  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 15:56:35.367  4292  4292 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 15:56:35.369  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:35.371  4292  4292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 15:56:35.378  4292  8066 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 15:56:35.380  4292  8067 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 15:56:35.380  4292  8067 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 15:56:35.420  1035  2035 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8068 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 15:56:35.531  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 15:56:35.531  1035  8037 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 15:56:35.531  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 15:56:35.531  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-31 15:56:35.531  1035  8037 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 15:56:35.532  1035  1521 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-31 15:56:35.532  8016  8016 E wpa_supplicant: USIM:  scard_init function
08-31 15:56:35.532  1035  1521 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-31 15:56:35.532  1035  1521 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-31 15:56:35.533  8016  8016 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-31 15:56:35.533  1035  1521 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-31 15:56:35.533  1035  1521 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 15:56:35.538  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 15:56:35.538  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 15:56:35.547  8068  8068 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 15:56:35.547  8068  8068 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-31 15:56:35.553  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=230756  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 15:56:35.557  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=230760  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 15:56:35.558  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:35.558  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:35.560  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.560  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.560  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 15:56:35.561  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.561  8068  8068 V [BNRBootReceiver]: Boot Receiver Return
08-31 15:56:35.562  8068  8068 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 15:56:35.562  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:35.562  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-31 15:56:35.642  1035  1959 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 15:56:35.643  1035  1959 I ActivityManager: Killing 7184:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-31 15:56:35.716  1035  2035 W libprocessgroup: failed to open /acct/uid_10005/pid_7184/cgroup.procs: No such file or directory
,08-31 15:56:35.744  8089  8089 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 15:56:35.768  8089  8089 D PluginManager: init()
,08-31 15:56:35.818  8016  8016 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 15:56:35.818  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 15:56:35.818  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-31 15:56:35.824  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 15:56:35.824  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 15:56:35.825  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:35.825  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:35.825  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 15:56:35.827  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=231030  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 15:56:35.829  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=231032  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 15:56:35.831  1035  1521 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231034
08-31 15:56:35.832  1035  1521 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231035
08-31 15:56:35.833  1035  1521 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231036
08-31 15:56:35.834  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231037
08-31 15:56:35.835  1035  1521 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231039
08-31 15:56:35.836  1035  1521 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=231039  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-31 15:56:35.840  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.840  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:35.840  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.840  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 15:56:35.840  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:35.842  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.842  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.842  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 15:56:35.843  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=231046  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 15:56:35.843  1035  1521 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:35.844  1035  1521 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:35.845  1035  1521 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:35.846  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:35.846  8016  8016 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:56:35.846  8016  8016 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 15:56:35.846  1035  1521 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 15:56:35.847  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:35.847  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:35.848  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 15:56:35.848  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:56:35.848  1035  8037 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:56:35.848  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 15:56:35.848  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 15:56:35.848  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:35.848  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 15:56:35.849  1035  8037 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 15:56:35.849  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:35.849  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:35.849  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.850  1035  1521 E WifiStateMachine:  Disconn,ectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=231053  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 15:56:35.850  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=231054  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-31 15:56:35.851  1035  1521 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=231054
08-31 15:56:35.851  1035  1521 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=231055
08-31 15:56:35.852  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:35.852  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:35.852  1035  1521 D WifiNative-wlan0: doString: [STATUS]
08-31 15:56:35.853  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:35.853  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 15:56:35.853  1035  8037 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 15:56:35.853  1035  8037 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 15:56:35.854  1035  1521 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 15:56:35.857  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.858  1035  1521 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 15:56:35.864  1035  1521 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 15:56:35.864  1035  1521 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 15:56:35.871  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.871  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.871  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 15:56:35.873  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.873  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.873  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 15:56:35.874  1035  1521 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 15:56:35.874  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:56:35.874  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 15:56:35.874  1035  1527 D ConnectivityService: Got NetworkAgent Messenger
08-31 15:56:35.875  1035  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 15:56:35.875  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 15:56:35.875  1035  1527 D ConnectivityService: NetworkAgent connected
08-31 15:56:35.875  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 15:56:35.876  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:35.876  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:35.877  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:56:35.879  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 15:56:35.879  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:35.880  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.882  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 15:56:35.882  1035  1521 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:56:35.882  1035  1521 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 15:56:35.882  1035  1521 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 15:56:35.882  1035  1521 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 15:56:35.886  1035  1521 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 15:56:35.888   309   893 D CommandListener: Setting iface cfg
08-31 15:56:35.891  1035  1521 E WifiStateMachine: Start Dhcp Watchdog 3
08-31 15:56:35.891  1035  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=231094  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:35.892  1035  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=231095  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:35.892  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=231095  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:35.893  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:35.893  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 15:56:35.893  1035  1521 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=231096  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:35.894  1035  1521 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=231097  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:35.894  1035  1521 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=231097  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 15:56:35.895  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14291] from screen [on:0 period:-521986633] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 15:56:35.896  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-521986632] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 15:56:35.896  1035  1521 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 15:56:35.897  1035  8107 D DhcpStateMachine: StoppedState
08-31 15:56:35.897  1035  8107 D DhcpStateMachine: StoppedState{ when=-6ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.897  1035  8107 D DhcpStateMachine: WaitBeforeStartState
,08-31 15:56:35.901  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.902  1035  1527 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-31 15:56:35.902  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.903  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.903  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.903  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.904  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.904  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.905  1035  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 15:56:35.906  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:35.906  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 15:56:35.907  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 15:56:35.907  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 15:56:35.908  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
08-31 15:56:35.908  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
08-31 15:56:35.908  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 15:56:35.909  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 15:56:35.909  1035  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 15:56:35.909  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 15:56:35.910  1035  1521 D WifiNative-wlan0: SET ps 0: returned true
08-31 15:56:35.910  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 15:56:35.910  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 15:56:35.910  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 15:56:35.910  1035  1520 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@121cb0d3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.910  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@121cb0d3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.911  1035  8107 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.911  1035  8107 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 15:56:35.912  1035  1521 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 15:56:35.912  1035  1521 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 15:56:35.912  1035  1521 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-31 15:56:35.913   309   893 D CommandListener: Setting iface cfg
,08-31 15:56:35.914   309   893 D CommandListener: Trying to bring up wlan0
08-31 15:56:35.915  1035  1521 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 15:56:35.916  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 15:56:35.916  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.917  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.918  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.918  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.919  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 15:56:35.919  1035  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 15:56:35.920  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 15:56:35.920  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 15:56:35.921  1035  1520 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.921  1035  1520 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:35.921  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 15:56:35.921  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 15:56:35.922  1035  1521 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 15:56:35.922  1035  1521 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 15:56:35.922  8016  8016 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 15:56:35.922  1035  1521 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 15:56:35.922  1035  1521 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 15:56:35.955  1035  1521 D WifiNative-wlan0: SET ps 1: returned true
08-31 15:56:35.956  1035  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 15:56:35.957  1035  1521 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 15:56:35.957  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 15:56:35.957  1035  1521 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 15:56:35.958  1035  1527 D ConnectivityService: ignoring duplicate network state non-change
,08-31 15:56:35.963  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.963  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.963  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 15:56:35.963  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:35.963  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:35.965  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.968  1035  1527 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 15:56:35.969  1035  1527 D ConnectivityService: Adding iface wlan0 to network 102
08-31 15:56:35.972  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.973  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.973  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-31 15:56:35.976  1035  1521 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 15:56:35.978  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 15:56:35.980  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 15:56:35.984  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.984  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.984  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 15:56:35.984  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:35.984  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 15:56:35.986  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:35.988  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 15:56:35.988  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:35.989  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 15:56:35.989  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 15:56:35.998  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.998  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:56:35.998  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 15:56:36.000  1035  1527 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 15:56:36.000  1035  1527 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-31 15:56:36.002  1035  1527 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-31 15:56:36.003   309   893 E Netd    : netlink response contains error (File exists)
,08-31 15:56:36.003  1035  1527 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-31 15:56:36.004  1035  1527 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 15:56:36.004  1035  1527 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-31 15:56:36.004  1035  1527 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-31 15:56:36.005  1035  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 15:56:36.005  1035  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 15:56:36.005  1035  1527 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 15:56:36.005  1035  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:36.005  1035  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 15:56:36.005  1035  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:56:36.005  1035  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 15:56:36.007  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:56:36.007  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,08-31 15:56:36.007  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:36.008  1035  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 15:56:36.008  1035  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:36.008  1035  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:36.008  1035  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 15:56:36.008  1035  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:36.008  1035  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 15:56:36.008  1035  1527 D ConnectivityService: currentScore = 0, newScore = 20
08-31 15:56:36.008  1035  1527 D ConnectivityService:    accepting network in place of null
08-31 15:56:36.008   309  8117 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 15:56:36.008  1035  1527 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:36.011  1035  1521 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:36.011  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:36.011  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:36.011  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 15:56:36.012  1035  1527 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 15:56:36.012  1035  1527 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 15:56:36.012  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 15:56:36.012  1035  1527 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 15:56:36.012  1035  1527 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 15:56:36.013  1035  1527 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 15:56:36.014  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 15:56:36.014  1035  1527 D ConnectivityService: validation of new default Network = false
08-31 15:56:36.014  1035  1527 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 15:56:36.014  1035  1527 D DSQN    : enableDataServiceNotify 
08-31 15:56:36.014  1035  1527 D DSQN    : start dsqn bin
08-31 15:56:36.015  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 15:56:36.015  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 15:56:36.015  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 15:56:36.023  1035  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 15:56:36.023  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:36.023  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:36.024  1035  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:36.015  8118  8118 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:36.024  1586  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 15:56:36.015  8118  8118 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 15:56:36.033  1035  1519 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 15:56:36.035  8118  8118 E DSQN    : DSQN ssw
,08-31 15:56:36.048  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:56:36.048  1800  8120 I CheckinService: active receiver: enabled
08-31 15:56:36.049  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:36.049  1800  8120 I CheckinService: Preparing to send checkin request
08-31 15:56:36.049  1800  8120 I EventLogService: Accumulating logs since 1472651778716
08-31 15:56:36.049  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:36.080   309  8117 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-31 15:56:36.087  1800  8120 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-31 15:56:36.095  6692  6758 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 872)
08-31 15:56:36.095  6692  6758 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 872)
,08-31 15:56:36.105  6692  6758 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 877)
08-31 15:56:36.108  6692  6758 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 15:56:36.108  6692  6758 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
,08-31 15:56:36.112  1035  8107 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 15:56:36.113  1035  8107 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 15:56:36.113  1035  8107 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 15:56:36.105  8124  8124 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:36.105  8124  8124 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 15:56:36.117  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.117  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c640ef6 added. We now have 2 listener(s)
08-31 15:56:36.117  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.122   309  8117 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-31 15:56:36.123  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-31 15:56:36.124  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.124  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.124  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:56:36.124  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d82f7 added. We now have 9 listener(s)
08-31 15:56:36.125  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:36.125  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:56:36.127  8124  8124 I dhcpcd  : version 5.5.6 starting
08-31 15:56:36.129  8124  8124 E dhcpcd  : get_duid: m
08-31 15:56:36.129  8124  8124 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 15:56:36.129  8124  8124 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 15:56:36.131  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:36.135  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:36.135  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:36.135  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:36.135  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:36.135  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:36.135  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:36.135  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:36.135  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:36.137  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:36.137  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:56:36.137  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.137  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32dd63cd added. We now have 3 listener(s)
08-31 15:56:36.138  1035  1716 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:56:36.139  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.141  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:36.141  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.141  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.141  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:36.141  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a3a2482 added. We now have 10 listener(s)
08-31 15:56:36.141  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:36.141  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:36.141  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:36.141  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:36.141  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.141  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.141  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:36.141  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.141  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c640ef6 removed from the list
08-31 15:56:36.141  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.141  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d82f7 removed from the list
08-31 15:56:36.142  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.142  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:36.142  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.142  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.142  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.143  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:56:36.143  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.143  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.143  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6d82f7 not in the list
08-31 15:56:36.143  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.144  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.144  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.144  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:36.144  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.144  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a3a2482 removed from the list
08-31 15:56:36.144  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.144  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.144  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.144  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.145  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32dd63cd removed from the list
08-31 15:56:36.145  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.145  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@206d5793 added. We now have 2 listener(s)
08-31 15:56:36.146  1035  1716 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.148  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:36.148  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.148  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.148  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:36.148  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2def43d0 added. We now have 9 listener(s)
08-31 15:56:36.148  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:56:36.148  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:56:36.150  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:36.153   309   892 D LGDataListener: argv[0]=dsqncommand
08-31 15:56:36.154   309   892 D LGDataListener: argv[1]=wlan0
08-31 15:56:36.154   309   892 D LGDataListener: argv[2]=1
08-31 15:56:36.154   309   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 15:56:36.154  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-31 15:56:36.154  1035  1115 D DSQN    : start to monitor internet connection
08-31 15:56:36.154  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:36.154  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:36.154  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:36.154  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:36.154  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:36.154  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:36.154  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:36.154  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:36.156  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:36.156  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:56:36.158  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.158  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@236a06ce added. We now have 3 listener(s)
08-31 15:56:36.158  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.158  1035  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.160  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.160  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:36.160  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.160  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.160  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:36.160  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338bd9ef added. We now have 10 listener(s)
08-31 15:56:36.160  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:36.161  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:56:36.161  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertiseme,nts only
08-31 15:56:36.161  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:56:36.161  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:36.161  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:56:36.166  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 15:56:36.166  1035  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 15:56:36.172  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 15:56:36.173  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 15:56:36.175  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:56:36.175  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:36.177  6692  6758 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:56:36.177  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 15:56:36.177  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:36.178  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:36.179  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:36.179  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:36.179  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.179  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.179  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:36.179  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.179  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@206d5793 removed from the list
08-31 15:56:36.179  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.179  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2def43d0 removed from the list
08-31 15:56:36.179  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:36.179  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.179  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.179  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.180  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:36.180  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.180  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.180  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2def43d0 not in the list
08-31 15:56:36.180  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.180  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.180  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.181  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:36.181  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:36.181  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:36.181  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.181  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@338bd9ef removed from the list
08-31 15:56:36.181  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.181  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not e,xist in the list - probably already removed
08-31 15:56:36.181  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.181  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.181  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@236a06ce removed from the list
08-31 15:56:36.182  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.182  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36a3c1da added. We now have 2 listener(s)
08-31 15:56:36.182  1035  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.183  1035  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 13:56:36 GMT], X-Android-Received-Millis=[1472651796182], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472651796153]}
08-31 15:56:36.183  1035  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 15:56:36.183  1035  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 15:56:36.183  1035  1527 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-31 15:56:36.183  1035  1527 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 15:56:36.183  1035  1527 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:36.183  1035  1527 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:36.183  1035  1527 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 15:56:36.183  1035  1527 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-31 15:56:36.183  1035  1527 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 15:56:36.183  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:36.183  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:36.183  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.183  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.183  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:36.183  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:36.184  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3166260b added. We now have 9 listener(s)
08-31 15:56:36.184  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:36.184  1035  1527 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:36.184  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDisco,veryMode: Discovery mode BLE is supported
08-31 15:56:36.184  1035  1527 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:36.184  1035  1527 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 15:56:36.184  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:36.185  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 15:56:36.186  1586  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 15:56:36.186  1035  1521 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:36.186  1035  1521 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:56:36.190  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:36.190  8124  8124 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 15:56:36.191  8124  8124 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 15:56:36.191  8124  8124 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 15:56:36.191  8124  8124 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 15:56:36.191  8124  8124 D dhcpcd  : wlan0: sending REQUEST (xid 0x9ad3fc0c), next in 3.18 seconds
08-31 15:56:36.195  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:36.195  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:36.195  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:36.195  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:36.195  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:36.195  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:36.195  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:36.195  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:36.197  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:36.197  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:56:36.197  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.197  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@329a4f01 added. We now have 3 listener(s)
08-31 15:56:36.198  1035  1639 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.199  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.200  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:36.200  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.200  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.200  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.200  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:36.200  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8c21a6 added. We now have 10 listener(s)
08-31 15:56:36.200  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:36.200  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:56:36.201  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:56:36.201  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:56:36.201  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:56:36.201  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:36.201  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:56:36.205  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 15:56:36.205  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.210  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 15:56:36.211  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 15:56:36.212  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 15:56:36.212  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:56:36.212  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:36.213  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 15:56:36.214  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:36.215  6692  6758 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:56:36.215  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:36.215  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:36.215  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:36.215  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.215  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.216  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:36.216  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.216  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36a3c1da removed from the list
08-31 15:56:36.216  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.216  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3166260b removed from the list
08-31 15:56:36.216  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:36.216  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.216  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.216  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.216  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:36.216  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.217  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.217  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3166260b not in the list
08-31 15:56:36.217  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.217  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.217  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.218  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:36.218  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:36.218  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:36.218  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.218  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8c21a6 removed from the list
08-31 15:56:36.218  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.218  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.218  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.218  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.218  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@329a4f01 removed from the list
08-31 15:56:36.219  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.220  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dbda3d added. We now have 2 listener(s)
,08-31 15:56:36.224  1035  1716 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.227  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:36.228  8124  8124 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-31 15:56:36.228  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.228  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.228  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:36.228  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d48b232 added. We now have 9 listener(s)
08-31 15:56:36.228  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:36.228  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:56:36.262  1035  1639 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8133 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-31 15:56:36.265  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:56:36.272  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:36.272  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:36.272  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:36.272  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:36.272  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:36.272  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:36.272  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:36.272  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:36.275  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 15:56:36.275  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:56:36.275  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.275  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39834100 added. We now have 3 listener(s)
08-31 15:56:36.276  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.278  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:36.278  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.278  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.278  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:36.278  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0dd39 added. We now have 10 listener(s)
08-31 15:56:36.278  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:36.278  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:56:36.278  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:56:36.278  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:56:36.278  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:36.278  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:56:36.280  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.282  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.282  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 15:56:36.282  1035  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.283  8124  8124 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 15:56:36.283  8124  8124 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 15:56:36.283  8124  8124 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 15:56:36.283  8124  8124 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 15:56:36.284  8124  8124 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 15:56:36.284  8124  8124 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 15:56:36.284  8124  8124 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 15:56:36.284  8124  8124 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 15:56:36.287  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 15:56:36.288  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanS,ettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 15:56:36.290  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:56:36.290  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:36.291  6692  6758 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:56:36.294  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:36.294  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:36.294  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:36.294  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.294  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.294  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:36.294  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.294  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dbda3d removed from the list
08-31 15:56:36.294  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.294  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d48b232 removed from the list
08-31 15:56:36.294  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:36.294  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:56:36.296  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.296  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.297  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:36.297  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.297  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.297  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d48b232 not in the list
08-31 15:56:36.297  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.297  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.298  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.300  6692  6758 D BluetoothLeScanner: could not find callback wrapper
08-31 15:56:36.300  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:56:36.300  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:36.300  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.300  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0dd39 removed from the list
08-31 15:56:36.300  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.300  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.300  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.300  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.300  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39834100 removed from the list
08-31 15:56:36.301  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.301  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5b6d2c added. We now have 2 listener(s)
08-31 15:56:36.301  1035  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.304  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:36.304  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.304  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.304  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:36.304  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3913f5 added. We now have 9 listener(s)
08-31 15:56:36.304  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils,.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:36.305  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:56:36.307  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:56:36.309  6692  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:56:36.309  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:56:36.309  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 15:56:36.309  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:56:36.309  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:56:36.309  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:36.309  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:56:36.309  6692  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:56:36.310  6692  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:56:36.310  6692  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:56:36.310  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:56:36.310  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2150a7fb added. We now have 3 listener(s)
08-31 15:56:36.311  1035  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 15:56:36.311  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.312  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:56:36.313  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 15:56:36.313  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:56:36.313  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:56:36.313  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:56:36.313  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29a83018 added. We now have 10 listener(s)
08-31 15:56:36.313  6692  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:56:36.313  6692  6758 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:56:36.313  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:36.313  6692  6758 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:56:36.314  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.314  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does, not exist in the list - probably already removed
08-31 15:56:36.314  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:56:36.314  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.314  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5b6d2c removed from the list
08-31 15:56:36.314  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.314  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3913f5 removed from the list
08-31 15:56:36.314  6692  6758 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:56:36.314  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.314  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.314  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.318  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:36.318  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.318  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.318  6692  6758 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3913f5 not in the list
08-31 15:56:36.318  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.318  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.321  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:56:36.321  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:56:36.321  6692  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:56:36.321  6692  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29a83018 removed from the list
08-31 15:56:36.321  6692  6758 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:56:36.321  6692  6758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:56:36.321  6692  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:56:36.321  6692  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:56:36.321  6692  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2150a7fb removed from the list
08-31 15:56:36.322  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 15:56:36.322  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 15:56:36.323  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 15:56:36.323  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:56:36.323  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 15:56:36.323  6692  6758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 15:56:36.326  8089  8089 W ExternalStrings: load override strings
08-31 15:56:36.326  8089  8089 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 15:56:36.326  8089  8089 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 15:56:36.327  8089  8089 D StatusProvider: onCreate
08-31 15:56:36.337  6692  8156 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 885, name: My test thread name)
08-31 15:56:36.337  6692  8156 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 885, thread name: My test thread name)
08-31 15:56:36.337  8133  8133 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 15:56:36.337  6692  8156 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 885, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 15:56:36.337  8133  8133 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-31 15:56:36.343  6692  8158 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 887, name: My test thread name)
,08-31 15:56:36.343  6692  8158 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 887, thread name: My test thread name)
08-31 15:56:36.343  6692  8158 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 887, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 15:56:36.345  6692  6758 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 15:56:36.345  6692  6758 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 15:56:36.345  6692  6758 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 15:56:36.345  6692  6758 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 15:56:36.345  6692  6758 D com.test.thalitest.ThaliTestRunner: Total duration: 23128 ms
08-31 15:56:36.346  6692  6758 I jxcore-log: *Native tests were executed*
08-31 15:56:36.346  6692  6758 I jxcore-log: 
08-31 15:56:36.347  6692  6758 I jxcore-log: Total number of executed tests:  80
08-31 15:56:36.347  6692  6758 I jxcore-log: 
08-31 15:56:36.347  6692  6758 I jxcore-log: Number of passed tests:  80
08-31 15:56:36.347  6692  6758 I jxcore-log: 
08-31 15:56:36.347  6692  6758 I jxcore-log: Number of failed tests:  0
08-31 15:56:36.347  6692  6758 I jxcore-log: 
08-31 15:56:36.347  6692  6758 I jxcore-log: Number of ignored tests:  0
08-31 15:56:36.347  6692  6758 I jxcore-log: 
08-31 15:56:36.347  6692  6758 I jxcore-log: Total duration:  23128
08-31 15:56:36.347  6692  6758 I jxcore-log: 
08-31 15:56:36.348  6692  6758 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 15:56:36.348  6692  6758 I jxcore-log: 
08-31 15:56:36.350  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.350  6692  6758 I jxcore-log: 
08-31 15:56:36.352  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.352  6692  6758 I jxcore-log: 
08-31 15:56:36.353  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.353  6692  6758 I jxcore-log: 
08-31 15:56:36.354  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.354  6692  6758 I jxcore-log: 
08-31 15:56:36.360  8133  8133 I MultiDex: VM with version 2.1.0 has multidex support
08-31 15:56:36.360  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.360  6692  6758 I jxcore-log: 
08-31 15:56:36.360  8133  8133 I MultiDex: install
08-31 15:56:36.360  8133  8133 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-31 15:56:36.362  6692  6692 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 15:56:36.364  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:56:36.364  6692  6758 I jxcore-log: 
08-31 15:56:36.368  8133  8133 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-31 15:56:36.372  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:56:36.372  6692  6758 I jxcore-log: 
08-31 15:56:36.373  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.373  6692  6758 I jxcore-log: 
08-31 15:56:36.374  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.374  6692  6758 I jxcore-log: 
08-31 15:56:36.375  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.375  6692  6758 I jxcore-log: 
08-31 15:56:36.376  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 15:56:36.376  6692  6758 I jxcore-log: 
08-31 15:56:36.377  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:56:36.377  6692  6758 I jxcore-log: 
08-31 15:56:36.378  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:56:36.378  6692  6758 I jxcore-log: 
08-31 15:56:36.378  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.378  6692  6758 I jxcore-log: 
08-31 15:56:36.379  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.379  6692  6758 I jxcore-log: 
08-31 15:56:36.385  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.385  6692  6758 I jxcore-log: 
08-31 15:56:36.387  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.387  6692  6758 I jxcore-log: 
08-31 15:56:36.388  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.388  6692  6758 I jxcore-log: 
08-31 15:56:36.388  8089  8089 V Signer  : override build config not found
08-31 15:56:36.388  8089  8089 D Signer  : value of property debug is false
08-31 15:56:36.389  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.389  6692  6758 I jxcore-log: 
08-31 15:56:36.389  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.389  6692  6758 I jxcore-log: 
08-31 15:56:36.390  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:56:36.390  6692  6758 I jxcore-log: 
,08-31 15:56:36.391  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:56:36.391  6692  6758 I jxcore-log: 
08-31 15:56:36.391  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:56:36.391  6692  6758 I jxcore-log: 
08-31 15:56:36.394  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.394  6692  6758 I jxcore-log: 
08-31 15:56:36.395  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.395  6692  6758 I jxcore-log: 
08-31 15:56:36.396  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.396  6692  6758 I jxcore-log: 
08-31 15:56:36.396  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.396  6692  6758 I jxcore-log: 
08-31 15:56:36.397  6692  6758 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:56:36.397  6692  6758 I jxcore-log: 
08-31 15:56:36.414  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-31 15:56:36.414  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-31 15:56:36.415  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-31 15:56:36.416  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-31 15:56:36.416  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-31 15:56:36.416  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-31 15:56:36.416  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-31 15:56:36.417  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-31 15:56:36.417  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-31 15:56:36.417  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-31 15:56:36.417  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-31 15:56:36.417  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-31 15:56:36.417  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-31 15:56:36.426  8089  8089 V LGMDMManager: Create singleton instance
08-31 15:56:36.462  8089  8089 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-31 15:56:36.498  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:56:36.506  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:36.514  1035  8107 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 15:56:36.517  1035  8107 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 15:56:36.517  1035  8107 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 15:56:36.517  1035  8107 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 15:56:36.517  1035  8107 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 15:56:36.517  1035  8107 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 15:56:36.517  1035  8107 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 15:56:36.517  1035  8107 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 15:56:36.517  1035  8107 D DhcpStateMachine: RunningState
08-31 15:56:36.522  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:36.529  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:36.535  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:36.538  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 15:56:36.546  7579  7579 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:56:36.553  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:36.555  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 15:56:36.560  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:56:36.564  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:36.569  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 15:56:36.569  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:36.570  7579  7579 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 15:56:36.573  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-31 15:56:36.576  6777  6777 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 15:56:36.608  8174  8174 D AndroidRuntime: 
08-31 15:56:36.608  8174  8174 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 15:56:36.610  8174  8174 D AndroidRuntime: CheckJNI is OFF
,08-31 15:56:36.645  8133  8152 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 15:56:36.646  8133  8152 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:56:36.675  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:56:36.679  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:36.680  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:56:36.683  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:36.684  8089  8177 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-31 15:56:36.689  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:36.690  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:36.690  7579  7579 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:56:36.693  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 15:56:36.693  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 15:56:36.693  6777  6777 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 15:56:36.693  6777  6777 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-31 15:56:36.693  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 15:56:36.694  6777  6777 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 15:56:36.694  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 15:56:36.694  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 15:56:36.697  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 15:56:36.704  6777  6777 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 15:56:36.704  6777  6777 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 15:56:36.705  6777  6777 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-31 15:56:36.709  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:36.709  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:36.714  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:56:36.718  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 15:56:36.723  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:36.723  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:36.723  7579  7579 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:56:36.727  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:36.729  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:36.734  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:36.738  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:36.743  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:36.743  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:36.743  7579  7579 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:56:36.745  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 15:56:36.745  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:36.749  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:56:36.753  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:36.758  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:36.758  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:36.758  7579  7579 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:56:36.762  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:36.762  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:36.767  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:56:36.771  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:36.776  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:36.776  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:36.776  7579  7579 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 15:56:36.778  8174  8174 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-31 15:56:36.782  8195  8195 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 15:56:36.783  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:36.784  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:36.788  1035  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-31 15:56:36.788  1035  1113 I ActivityManager: Killing 6692:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-31 15:56:36.818  1035  1959 I WindowState: WIN DEATH: Window{24f77876 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 15:56:36.818  1035  1526 D WifiService: Client connection lost with reason: 4
,08-31 15:56:36.821  8195  8195 I dex2oat : dex2oat took 38.410ms (threads: 4)
08-31 15:56:36.825  1035  1959 D InputDispatcher: Window went away: Window{24f77876 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 15:56:36.835  8133  8152 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:56:36.835  8133  8152 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:56:36.835  8133  8152 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:56:36.835  8133  8152 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:56:36.835  8133  8152 I Adreno-EGL: Remote Branch: 
08-31 15:56:36.835  8133  8152 I Adreno-EGL: Local Patches: 
08-31 15:56:36.835  8133  8152 I Adreno-EGL: Reconstruct Branch: 
,08-31 15:56:36.918  8133  8152 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:56:36.918  8133  8152 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:56:36.918  8133  8152 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:56:36.918  8133  8152 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:56:36.918  8133  8152 I Adreno-EGL: Remote Branch: 
08-31 15:56:36.918  8133  8152 I Adreno-EGL: Local Patches: 
08-31 15:56:36.918  8133  8152 I Adreno-EGL: Reconstruct Branch: 
,08-31 15:56:36.967  8133  8152 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 15:56:36.967  8133  8152 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 15:56:36.967  8133  8152 I Adreno-EGL: Build Date: 12/12/14 금
08-31 15:56:36.967  8133  8152 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 15:56:36.967  8133  8152 I Adreno-EGL: Remote Branch: 
08-31 15:56:36.967  8133  8152 I Adreno-EGL: Local Patches: 
08-31 15:56:36.967  8133  8152 I Adreno-EGL: Reconstruct Branch: 
,08-31 15:56:37.058  1035  1113 I ActivityManager:   Force finishing activity ActivityRecord{12206733 u0 com.test.thalitest/.MainActivity t6}
,08-31 15:56:37.111   329   356 E GBMv2   : DFP En is all cleared set to be enabled
,08-31 15:56:37.125  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-31 15:56:37.125  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:56:37.136  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{12206733 u0 com.test.thalitest/.MainActivity t6 f}
08-31 15:56:37.136  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:37.136  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{12206733 u0 com.test.thalitest/.MainActivity t6 f}
,08-31 15:56:37.155  1035  1716 W ActivityManager: Spurious death for ProcessRecord{195b14b3 6692:com.test.thalitest/u0a118}, curProc for 6692: null
08-31 15:56:37.156  2017  2017 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-31 15:56:37.158  2017  2017 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-31 15:56:37.163  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-31 15:56:37.169  3803  3803 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-31 15:56:37.169  1979  1979 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-31 15:56:37.171  7615  7615 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-31 15:56:37.171  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 15:56:37.180  2489  2648 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 15:56:37.181  4481  4481 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 15:56:37.182  4481  4481 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 15:56:37.182  4481  4481 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 15:56:37.182  4481  4481 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 15:56:37.182  4481  4481 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:56:37.182  4481  4481 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:56:37.182  4481  4481 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 15:56:37.182  4481  4481 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-31 15:56:37.183  4481  4481 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:56:37.183  4481  4481 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:56:37.183  4481  4481 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 15:56:37.183  4481  4481 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 15:56:37.212  1035  1413 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 15:56:37.231  4594  4594 I art     : Explicit concurrent mark sweep GC freed 8204(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 740us total 81.998ms
,08-31 15:56:37.249  1035  1959 V SIM_STK : Menu title from STK is T-Mobile
,08-31 15:56:37.263  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-31 15:56:37.266  2017  2108 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-31 15:56:37.269  1035  1035 D administrator: Handling package changes for user 0
08-31 15:56:37.280  1925  3947 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-31 15:56:37.280  1925  3947 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1bf4c7fd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-31 15:56:37.283  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 15:56:37.283  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{26d66cf2 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 15:56:37.293  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-31 15:56:37.293  1889  1889 D ActionManagerService: notifyUserLog: 1000003
08-31 15:56:37.294  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-31 15:56:37.294  3803  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-31 15:56:37.325  1586  1632 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 15:56:37.325  1586  1632 D KeyguardModel: createShortcutInfo...
,08-31 15:56:37.327  2017  2017 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-31 15:56:37.331  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:37.331  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:37.332  1586  1632 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 15:56:37.332  1586  1632 D KeyguardModel: createShortcutInfo...
08-31 15:56:37.336  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-31 15:56:37.336  1853  1853 D SplitUIService: removed split : 
08-31 15:56:37.336  1586  1632 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 15:56:37.336  1586  1632 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 15:56:37.337  1586  1632 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 15:56:37.339  2017  2017 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-31 15:56:37.340  2017  2017 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 15:56:37.342  1889  1889 D ActionManagerService: notifyUserLog: 1000004
08-31 15:56:37.343  3803  4471 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-31 15:56:37.343  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-31 15:56:37.345  7579  7579 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:56:37.345  3803  4458 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 15:56:37.349  1586  1632 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 15:56:37.353  1586  1632 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:56:37.353  1586  1632 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 15:56:37.355  1586  1632 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 15:56:37.355  1586  1632 D KeyguardModel: createShortcutInfo...
08-31 15:56:37.356  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 15:56:37.356  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , display: false
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , animation: false }
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , display: false
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , animation: false }
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , display: false
08-31 15:56:37.356  2017  2017 I GBoardWebViewUtils: , animation: false }
08-31 15:56:37.358  1035  1870 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:56:37.358  1035  1870 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:56:37.358  1586  1632 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 15:56:37.359  1586  1632 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 15:56:37.365  1586  1632 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:56:37.365  1586  1632 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-31 15:56:37.366  1586  1632 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 15:56:37.366  1586  1632 D KeyguardModel: createShortcutInfo...
08-31 15:56:37.369  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-31 15:56:37.369  1853  1853 I SplitUIService: split app #11
08-31 15:56:37.369  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:37.370  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:37.371  1586  1632 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:56:37.371  1586  1632 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 15:56:37.371  1586  1632 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 15:56:37.371  1586  1632 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 15:56:37.371  2017  8216 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 15:56:37.373  1586  1632 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:56:37.374  1586  1632 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 15:56:37.375  1586  1632 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 15:56:37.376  1035  1871 V SIM_STK : Menu title from STK is T-Mobile
08-31 15:56:37.375  1586  1632 D KeyguardModel: createShortcutInfo...
,08-31 15:56:37.381  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:56:37.382  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 15:56:37.382  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-31 15:56:37.386  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:37.389  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-31 15:56:37.389  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 15:56:37.395  1586  1632 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 15:56:37.395  1586  1632 D KeyguardModel: createShortcutInfo...
08-31 15:56:37.397  1586  1632 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 15:56:37.397  1586  1632 D KeyguardModel: createShortcutInfo...
08-31 15:56:37.398  1586  1632 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:56:37.398  1586  1632 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 15:56:37.400  1586  1632 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 15:56:37.400  1586  1632 D KeyguardModel: createShortcutInfo...
08-31 15:56:37.401  1586  1632 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:56:37.401  1586  1632 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-31 15:56:37.405  1586  1632 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 15:56:37.405  1586  1632 D KeyguardModel: createShortcutInfo...
08-31 15:56:37.406  1586  1632 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 15:56:37.406  1586  1632 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 15:56:37.410  1035  1870 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 15:56:37.410  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 15:56:37.410  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 15:56:37.410  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 15:56:37.410  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 15:56:37.410  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 15:56:37.410  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:56:37.411  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 15:56:37.411  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 15:56:37.411  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 15:56:37.411  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 15:56:37.411  7615  7615 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 15:56:37.412  1586  1632 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 15:56:37.412  1586  1632 D KeyguardModel: createShortcutInfo...
08-31 15:56:37.414  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:37.414  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:37.414  7579  7579 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 15:56:37.427  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:37.427  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 15:56:37.454  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-31 15:56:37.455  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-31 15:56:37.455  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 15:56:37.456  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 15:56:37.456  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 15:56:37.457  1035  1561 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-31 15:56:37.459  1035  1112 W InputMethodInfo: Duplicated subtype definition found: , voice
08-31 15:56:37.460  8089  8177 D LgDataFeature: LgDataFeature() Constructor: none
08-31 15:56:37.460  8089  8177 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 15:56:37.461  8040  8040 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 15:56:37.484   323   433 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-31 15:56:37.485  3199  8223 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-31 15:56:37.495   309  8225 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-31 15:56:37.496   309  8225 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-31 15:56:37.500  8040  8040 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:37.503  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 15:56:37.513  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-31 15:56:37.516  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:56:37.518  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 15:56:37.518  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:37.519  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 15:56:37.520  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 15:56:37.521  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-31 15:56:37.526  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:37.526  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:37.527  7579  7579 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 15:56:37.528  7579  7579 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 15:56:37.528  7579  7579 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 15:56:37.532  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 15:56:37.532  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:37.534  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{202105a1 u0 com.lge.launcher2/.Launcher t5} time:232749
,08-31 15:56:37.537  8040  8040 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 15:56:37.537  8040  8040 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 15:56:37.537  2017  2017 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-31 15:56:37.538  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-31 15:56:37.538  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:56:37.540  6777  6777 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 15:56:37.540   309  8225 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-31 15:56:37.543  6777  6777 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 15:56:37.552  2017  2165 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 15:56:37.552  2017  2165 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-31 15:56:37.553  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 15:56:37.554  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 15:56:37.554  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 15:56:37.557  7579  7579 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 15:56:37.557  7579  7579 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 15:56:37.557  7579  7579 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 15:56:37.558  7579  7579 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 15:56:37.558  7579  7579 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 15:56:37.559  1035  1995 I ActivityManager: Killing 7652:com.google.android.talk/u0a72 (adj 15): empty #17
08-31 15:56:37.562  2017  2017 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-31 15:56:37.570  1035  1123 I art     : Explicit concurrent mark sweep GC freed 85216(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 3.170ms total 287.285ms
,08-31 15:56:37.591  8174  8174 D AndroidRuntime: Shutting down VM
,08-31 15:56:37.596  8089  8177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-31 15:56:37.617  1035  1978 W libprocessgroup: failed to open /acct/uid_10072/pid_7652/cgroup.procs: No such file or directory
08-31 15:56:37.617  2560  2560 D [Concierge]Service: onStartCommand(). Type : 8
08-31 15:56:37.617  2560  2560 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-31 15:56:37.618  2560  2560 D [Concierge]Service: Update widget ID : 11
08-31 15:56:37.619  2017  2017 D [Concierge]WidgetView: change position of spinner
08-31 15:56:37.649  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8229 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 15:56:37.650  2203  2203 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-31 15:56:37.651  2017  2017 I [Concierge]WidgetView: initWebView(). Time : 1472651797651
08-31 15:56:37.652  2560  2560 D [Concierge]Service: onStartCommand(). Type : 0
08-31 15:56:37.657  2203  2203 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-31 15:56:37.657  2203  2203 D c       : Getting all permits...
08-31 15:56:37.658  2203  2203 D a       : Opening database...
08-31 15:56:37.659  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:56:37.660  2203  2203 D a       : Opening database auth.proximity.permit_store...
08-31 15:56:37.660  2203  2203 D a       : Closing database...
,08-31 15:56:37.665  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 15:56:37.667  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 15:56:37.671  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 15:56:37.674  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 15:56:37.676  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-31 15:56:37.677  8089  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-31 15:56:37.678  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 15:56:37.679  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 15:56:37.680  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 15:56:37.682  8089  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-31 15:56:37.682  8089  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 15:56:37.682  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 15:56:37.682  8089  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 15:56:37.683  8089  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-31 15:56:37.683  8089  8177 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-31 15:56:37.683  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-31 15:56:37.684  8089  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 15:56:37.685  1800  1800 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-31 15:56:37.686  2017  2017 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 97715052
08-31 15:56:37.686  2017  2017 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-31 15:56:37.686  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-31 15:56:37.689  2017  2017 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1de89df9
,08-31 15:56:37.689  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-31 15:56:37.689  8089  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-31 15:56:37.692  2203  2203 I ConfigService: onCreate
08-31 15:56:37.692  2203  2203 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-31 15:56:37.692  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 15:56:37.692  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:56:37.692  8089  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-31 15:56:37.696  1035  2035 I ActivityManager: Killing 7703:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-31 15:56:37.697  2203  2203 I ConfigService: onBind returning update interface
08-31 15:56:37.698  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 15:56:37.698  2017  2017 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 15:56:37.698  2017  2017 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 15:56:37.707  1800  8120 I CheckinTask: Sending checkin request (7833 bytes)
,08-31 15:56:37.716  1800  1800 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-31 15:56:37.716  2203  2203 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-31 15:56:37.716  2203  2203 I ConfigService: onBind returning config service
08-31 15:56:37.717  2017  2017 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472651592443, New one : 1472651797651
08-31 15:56:37.717  2017  2017 D [Concierge]WidgetView: Unregister all receivers
08-31 15:56:37.717  2017  2017 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 15:56:37.717  1035  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_7703/cgroup.procs: No such file or directory
08-31 15:56:37.717  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-31 15:56:37.718  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:56:37.720  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 15:56:37.721  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 15:56:37.722  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 15:56:37.723  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 15:56:37.724  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-31 15:56:37.725  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:56:37.725  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 15:56:37.730  1800  1800 I ConfigFetchService: service connected
,08-31 15:56:37.736  2203  2203 I ConfigService: onDestroy
,08-31 15:56:37.739  1800  8252 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-31 15:56:37.761  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-31 15:56:37.769  1035  1639 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8255 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-31 15:56:37.771  2017  2017 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 15:56:37.771  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-31 15:56:37.773  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 15:56:37.776  1035  1521 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:37.776  1035  1521 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:37.776  1035  1521 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:37.777  1035  1521 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:37.777  1035  1521 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:37.777  1035  1521 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 15:56:37.778  1035  1527 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-31 15:56:37.778  1035  1527 D ConnectivityService: identical MTU - not setting
08-31 15:56:37.778  1035  1527 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 15:56:37.778  1035  1527 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 15:56:37.778  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:56:37.778  1035  1527 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:37.778  1035  1527 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 15:56:37.778  1586  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 15:56:37.794  2017  2017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17eddde1 time:233009
,08-31 15:56:37.825  5926  8276 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-31 15:56:37.828  1800  8277 I PeopleContactsSync: CP2 sync disabled
08-31 15:56:37.835  1800  4737 I Icing   : doRemovePackageData com.test.thalitest
,08-31 15:56:37.852  2203  2223 I art     : Explicit concurrent mark sweep GC freed 8187(479KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 509us total 17.149ms
,08-31 15:56:37.860  1800  8275 W GmsApplication: Using Auth Proxy for data requests.
08-31 15:56:37.862  1800  8275 W GmsApplication: Using Auth Proxy for data requests.
08-31 15:56:37.871  8255  8255 I AppUp4:AppBoxCP: onCreate
,08-31 15:56:37.871  8255  8255 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-31 15:56:37.876  8255  8255 I AppUp4:DB:  setFingerPrint start
08-31 15:56:37.877  8255  8255 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-31 15:56:37.882  8255  8255 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 15:56:37.882  8255  8255 I AppUp4:DB:  SDK version = 21
08-31 15:56:37.882  8255  8255 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-31 15:56:37.883  8255  8255 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-31 15:56:37.918  8255  8255 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-31 15:56:37.924  1035  1716 I ActivityManager: Killing 7745:com.android.gallery3d/u0a27 (adj 15): empty #17
08-31 15:56:37.956  2017  2017 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-31 15:56:37.990  2017  2851 I GBoardtInterface: onReloaded()

```
