#### Test 797510152cd5224_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-05 09:54:00.064  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 09:54:00.069  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
08-05 09:54:00.076  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 09:54:00.076  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-05 09:54:00.077  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-05 09:54:00.078  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 09:54:17.582  6694  6694 D AndroidRuntime: 
08-05 09:54:17.582  6694  6694 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 09:54:17.588  6694  6694 D AndroidRuntime: CheckJNI is OFF
08-05 09:54:17.710  6694  6694 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 09:54:17.714  1037  1871 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 09:54:17.724  1925  3949 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-05 09:54:17.728  1037  1871 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-05 09:54:17.729  1037  1871 D ActivityManager: setTaskToReturnTo : TaskRecord{81cc8b1 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 09:54:17.729  1037  1871 D ActivityManager: setTaskToReturnTo : TaskRecord{81cc8b1 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 09:54:17.731  1037  1871 D WindowStateEx: AppWindowTokenEx init.. 
08-05 09:54:17.731   376   404 E GBMv2   : DFP En is all cleared set to be enabled
08-05 09:54:17.766  1037  1871 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6709 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 09:54:17.768  6694  6694 D AndroidRuntime: Shutting down VM
08-05 09:54:17.805  1925  3949 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-05 09:54:17.805  1925  3949 D SplitWindowPolicy: topRunningActivity=ActivityInfo{232b7310 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 09:54:17.806  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-05 09:54:17.807  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4ef0e09 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 09:54:17.875  6709  6709 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-05 09:54:17.963  6709  6709 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-05 09:54:17.972  6709  6709 I LibraryLoader: Loading: webviewchromium
,08-05 09:54:17.976  6709  6709 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7956-7960)
08-05 09:54:17.976  6709  6709 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 09:54:18.012  6709  6709 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c457b3e}
,08-05 09:54:18.014  6709  6709 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 09:54:18.015  6709  6709 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 09:54:18.029  6709  6709 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 09:54:18.030  6709  6709 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 09:54:18.048  6709  6709 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 09:54:18.049  6709  6709 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-05 09:54:18.049  6709  6709 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-05 09:54:18.055   322  1387 V AudioPolicyService: registerClient() client 0xb14b7ba0, uid 10118
08-05 09:54:18.059  1037  1119 D BluetoothManagerService: Message: 20
08-05 09:54:18.060  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@96e77b3:true
,08-05 09:54:18.075  6709  6709 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 09:54:18.075  6709  6709 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 09:54:18.075  6709  6709 I Adreno-EGL: Build Date: 12/12/14 금
08-05 09:54:18.075  6709  6709 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 09:54:18.075  6709  6709 I Adreno-EGL: Remote Branch: 
08-05 09:54:18.075  6709  6709 I Adreno-EGL: Local Patches: 
08-05 09:54:18.075  6709  6709 I Adreno-EGL: Reconstruct Branch: 
,08-05 09:54:18.180  6709  6750 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-05 09:54:18.183  6709  6709 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-05 09:54:18.218  6709  6709 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 09:54:18.224  6709  6709 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 09:54:18.227  6709  6709 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 09:54:18.231  6709  6709 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 09:54:18.231  6709  6709 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-05 09:54:18.248  6709  6709 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-05 09:54:18.256  6709  6709 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 09:54:18.256  6709  6709 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 09:54:18.301  6709  6765 D OpenGLRenderer: Render dirty regions requested: true
08-05 09:54:18.301  6709  6765 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 09:54:18.305  1037  1112 W ActivityManager: Activity pause timeout for ActivityRecord{234d9196 u0 com.test.thalitest/.MainActivity t40}
08-05 09:54:18.311  6709  6765 D OpenGLRenderer: Enabling debug mode 0
,08-05 09:54:18.321  6709  6709 D Atlas   : Validating map...
,08-05 09:54:18.325  1037  1052 D SplitWindow: check instance of lgWin Window{3dd23b15 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 09:54:18.371  6709  6763 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 09:54:18.371  6709  6763 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 09:54:18.436  1037  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +632ms (total +704ms)
,08-05 09:54:18.437  6709  6709 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1df7d325 time:308422
08-05 09:54:18.440  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{234d9196 u0 com.test.thalitest/.MainActivity t40} time:308425
08-05 09:54:18.543  6709  6709 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 09:54:18.610  6709  6763 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-05 09:54:18.610  6709  6763 I chromium: 
,08-05 09:54:18.751  6709  6775 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435134592
,08-05 09:54:18.767  6709  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 09:54:18.767  6709  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 09:54:18.767  6709  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 09:54:18.767  6709  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 09:54:18.767  6709  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 09:54:18.767  6709  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16121ed9 added. We now have 1 listener(s)
08-05 09:54:18.771   376   406 E GBMv2   : DFP En is all cleared set to be enabled
08-05 09:54:18.771   376   406 E GBMv2   : Set value is all cleared set the max
08-05 09:54:18.771   376   406 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 09:54:18.777  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:18.778  6709  6709 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-05 09:54:18.778  6709  6709 I chromium: 
08-05 09:54:18.783  6709  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-05 09:54:18.785  6709  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:18.787  6709  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:18.787  6709  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 09:54:18.798  6709  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2070534c added. We now have 1 listener(s)
08-05 09:54:18.798  6709  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 09:54:18.804  1037  1418 D WifiService: New client listening to asynchronous messages
08-05 09:54:18.807  6709  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 09:54:18.808  6709  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 09:54:18.808  6709  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 09:54:18.808  6709  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 09:54:18.808  6709  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 09:54:18.813  6709  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:18.813  1037  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:18.814  6709  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-05 09:54:18.824  6709  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-05 09:54:18.824  6709  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:18.824  6709  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:18.824  6709  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:18.824  6709  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:18.824  6709  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:18.824  6709  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:18.824  6709  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:18.824  6709  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:18.824  6709  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 09:54:18.825  6709  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 09:54:18.828  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:18.828  6709  6775 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 09:54:18.830  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:18.869  6709  6709 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 09:54:19.870  6709  6778 W jxcore-log: Initializing JXcore engine
08-05 09:54:19.870  6709  6778 W jxcore-log: JXcore engine is ready
,08-05 09:54:19.900  6778  6778 W Thread-777: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10551]" dev="sockfs" ino=10551 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-05 09:54:19.900  6778  6778 W Thread-777: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 09:54:19.900  6778  6778 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7497]" dev="sockfs" ino=7497 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 09:54:19.900  6778  6778 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-05 09:54:19.900  6778  6778 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31389]" dev="sockfs" ino=31389 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-05 09:54:19.919  6709  6778 W jxcore-log: Starting JXcore engine
,08-05 09:54:20.089  6709  6778 W jxcore-log: Platform android
08-05 09:54:20.089  6709  6778 W jxcore-log: 
,08-05 09:54:20.089  6709  6778 W jxcore-log: Process ARCH arm
08-05 09:54:20.089  6709  6778 W jxcore-log: 
,08-05 09:54:20.361  6709  6778 I jxcore-log: JXcore Cordova bridge is ready!
08-05 09:54:20.361  6709  6778 I jxcore-log: 
08-05 09:54:20.361  6709  6778 W jxcore-log: JXcore engine is started
,08-05 09:54:20.375  6709  6775 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 09:54:20.384  6709  6709 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 09:54:36.118  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 09:54:36.118  6709  6778 I jxcore-log: 
,08-05 09:54:36.121  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 09:54:36.121  6709  6778 I jxcore-log: 
08-05 09:54:36.127  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:36.127  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.127  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.127  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:36.127  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:36.127  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.127  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:36.127  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:36.131  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 09:54:36.134  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 09:54:36.134  6709  6778 I jxcore-log: 
08-05 09:54:36.135  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 09:54:36.135  6709  6778 I jxcore-log: 
08-05 09:54:36.473  6709  6778 D ExecuteNativeTests: Running unit tests
,08-05 09:54:36.556  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:36.556  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 added. We now have 2 listener(s)
,08-05 09:54:36.556  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 09:54:36.560  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:36.560  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:36.560  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:36.560  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:36.560  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e added. We now have 2 listener(s)
08-05 09:54:36.560  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:36.560  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 09:54:36.563  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:36.566  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:36.566  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.566  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.566  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:36.566  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:36.566  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.566  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:36.566  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:36.568  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.568  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 09:54:36.571  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-05 09:54:36.573  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:36.576  6709  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 09:54:36.576  6709  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 09:54:36.578  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:36.579  6709  6778 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-05 09:54:36.579  6709  6778 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 09:54:36.579  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 09:54:36.579  6709  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 09:54:36.580  6709  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 09:54:36.580  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.581  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.581  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.581  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.581  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.581  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:36.581  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:36.581  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 removed from the list
08-05 09:54:36.581  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.581  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e removed from the list
08-05 09:54:36.581  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.581  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.582  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.582  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.583  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.583  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.583  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.583  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.585  6709  6778 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is n,ot supported
08-05 09:54:36.585  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.585  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.585  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.586  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.586  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.586  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.586  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.586  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.586  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
,08-05 09:54:36.586  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.586  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.586  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-05 09:54:36.586  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.586  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.586  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-05 09:54:36.586  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.586  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.586  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
,08-05 09:54:36.590  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-05 09:54:36.590  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 09:54:36.590  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 09:54:36.590  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-05 09:54:36.590  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 09:54:36.591  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 09:54:36.591  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.591  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.591  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.592  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.592  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.592  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.592  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.592  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.592  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.592  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.592  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.592  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.592  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.592  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.593  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.593  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.593  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.593  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
,08-05 09:54:36.594  6709  6778 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-05 09:54:36.596  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:36.599  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:36.599  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.599  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.599  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:36.599  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:36.599  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.599  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:36.599  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:36.600  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.600  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 09:54:36.601  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:36.602  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 09:54:36.602  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 09:54:36.602  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 09:54:36.602  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 09:54:36.602  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:36.602  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 09:54:36.608  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 09:54:36.609  1037  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:36.614  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 09:54:36.619  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 09:54:36.620  6709  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 09:54:36.621  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 09:54:36.622  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:36.623  6709  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 09:54:36.623  6709  6778 I io.jxcore.node.ConnectionHelper: start: OK
08-05 09:54:36.625  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.625  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 09:54:36.625  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.625  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.625  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.625  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:36.625  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.625  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.625  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
,08-05 09:54:36.625  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.625  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.626  6709  6778 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-05 09:54:36.627  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 09:54:36.630  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:36.630  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.630  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.630  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:36.630  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:36.630  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.630  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:36.630  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:36.631  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.631  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 09:54:36.632  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:36.633  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:36.633  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 09:54:36.633  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 09:54:36.633  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 09:54:36.633  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:36.633  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 09:54:36.636  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 09:54:36.637  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 09:54:36.638  6709  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 09:54:36.638  6709  6778 I io.jxcore.node.ConnectionHelper: start: OK
08-05 09:54:36.639  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.639  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.639  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.639  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.639  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 09:54:36.639  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:36.639  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.640  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.640  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.640  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.640  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.640  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.640  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.641  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.641  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.642  6709  6778 D BluetoothLeScanner: could not find callback wrapper
,08-05 09:54:36.642  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.642  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.642  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.642  6709  6778 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 09:54:36.644  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:36.646  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:36.646  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.646  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.646  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:36.646  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:36.646  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.646  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:36.646  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:36.646  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.646  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 09:54:36.647  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 09:54:36.647  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 09:54:36.647  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 09:54:36.647  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:36.647  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 09:54:36.648  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 09:54:36.650  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-05 09:54:36.651  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 09:54:36.652  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:36.653  6709  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 09:54:36.653  6709  6778 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 09:54:36.653  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.653  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.653  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.654  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.654  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.654  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.654  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.654  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.654  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 09:54:36.654  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.654  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.654  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.654  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.654  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.655  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.655  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.656  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.656  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.656  6709  6778 D BluetoothLeScanner: could not find callback wrapper
,08-05 09:54:36.656  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.656  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.656  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.656  6709  6778 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-05 09:54:36.657  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.657  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.657  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.657  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.657  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.657  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.657  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.657  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 09:54:36.657  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.657  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.657  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.657  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.657  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.657  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.658  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.658  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.658  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.658  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.658  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 09:54:36.658  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.659  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 09:54:36.659  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.659  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.659  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.659  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.659  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.659  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.659  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.659  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 09:54:36.659  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.659  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.659  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.659  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.659  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.659  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.660  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.660  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 09:54:36.661  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.661  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.661  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.661  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.662  6709  6778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 09:54:36.662  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.662  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.662  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.662  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.662  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.662  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.662  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.662  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.662  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.662  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.662  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.663  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.663  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.663  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.663  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.663  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.664  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.664  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.664  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.664  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.665  6709  6778 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-05 09:54:36.665  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.665  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.665  6709  6778 V io.jxcore.node.StartStopOperationHa,ndler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.665  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.665  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.665  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.665  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.665  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.665  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.665  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.665  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.665  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.665  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.665  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.666  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.666  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.667  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.667  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.667  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.667  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.667  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 09:54:36.668  6709  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 09:54:36.668  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 09:54:36.669  6709  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 09:54:36.669  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 09:54:36.669  6709  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 09:54:36.669  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.669  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.669  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.669  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.669  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.669  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.669  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.669  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.669  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.669  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.669  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.669  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.669  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.669  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.670  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.670  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.671  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.671  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.671  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.671  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.673  6709  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 09:54:36.673  6709  6778 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 09:54:36.673  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 09:54:36.680  6709  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 09:54:36.681  6709  6778 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 09:54:36.681  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 09:54:36.682  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 09:54:36.682  6709  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 09:54:36.682  6709  6778 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 09:54:36.682  6709  6778 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-05 09:54:36.682  6709  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 09:54:36.682  6709  6778 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 09:54:36.682  6709  6778 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 09:54:36.682  6709  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 09:54:36.682  6709  6778 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 09:54:36.682  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 09:54:36.686  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-05 09:54:36.690  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-05 09:54:36.690  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 09:54:36.691  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 09:54:36.691  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-05 09:54:36.691  6709  6778 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 09:54:36.691  6709  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 09:54:36.691  6709  6778 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 09:54:36.692  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.692  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.692  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.694  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.694  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.694  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.694  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 09:54:36.695  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.695  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.695  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.695  6709  6784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
08-05 09:54:36.695  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.695  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.695  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.695  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.695  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.696  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.696  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.696  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.696  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.696  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.696  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.697  6709  6778 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 09:54:36.697  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.697  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.697  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.698  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.698  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.698  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.698  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.698  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.698  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.698  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.698  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.698  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.698  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.698  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.701  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.701  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.702  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.702  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.702  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.702  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.702  6709  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-05 09:54:36.703  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.703  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.703  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.703  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.703  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.703  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.703  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.703  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.703  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.703  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.703  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.703  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.703  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.703  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.704  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.704  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.705  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.705  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.705  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.705  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.706  6709  6778 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 09:54:36.706  6709  6778 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 09:54:36.706  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 09:54:36.706  6709  6778 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-05 09:54:36.707  6709  6778 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 09:54:36.707  6709  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 09:54:36.708  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 09:54:36.708  6709  6778 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 09:54:36.708  6709  6785 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
08-05 09:54:36.709  6709  6785 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 841)
08-05 09:54:36.709  6709  6778 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 09:54:36.709  6709  6778 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 09:54:36.709  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 09:54:36.709  6709  6785 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 841)
08-05 09:54:36.709  6709  6778 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 09:54:36.709  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.709  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.709  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.710  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.710  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.710  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.710  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.710  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.710  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.710  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.710  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.710  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.710  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.710  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 09:54:36.711  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.711  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.712  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.712  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.712  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.712  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.713  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.713  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.713  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.713  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.713  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.713  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.713  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.713  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.713  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.713  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.713  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.713  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.713  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.713  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.713  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.713  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.713  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.713  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.714  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.714  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.714  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.714  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.714  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.714  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.714  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.714  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.714  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.714  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.714  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.714  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.714  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.715  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.715  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.715  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.715  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.719  6709  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 09:54:36.719  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:36.720  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 09:54:36.721  6709  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 09:54:36.721  6709  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 09:54:36.721  6709  6709 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 09:54:36.721  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 09:54:36.721  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 09:54:36.722  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:36.722  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.722  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 09:54:36.722  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 09:54:36.722  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 09:54:36.722  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.722  6709  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 09:54:36.723  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.723  6709  6709 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 09:54:36.723  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.723  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 09:54:36.723  6709  6778 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 09:54:36.723  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 09:54:36.723  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 09:54:36.724  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:36.724  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:36.724  6709  6778 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 09:54:36.724  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.724  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.724  6709  6787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:36.725  6709  6778 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 09:54:36.725  3891  6779 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-05 09:54:36.726  6709  6709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 09:54:36.726  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.726  6709  6709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 09:54:36.726  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.726  6709  6787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-05 09:54:36.726  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.726  6709  6709 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 09:54:36.726  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.726  6709  6787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 09:54:36.726  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.726  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.726  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.726  6709  6787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 09:54:36.726  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.726  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.726  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.726  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.726  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.726  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.726  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.726  6709  6709 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 09:54:36.726  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.727  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.727  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.727  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.727  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.728  6709  6778 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 09:54:36.728  6709  6778 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 09:54:36.728  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 09:54:36.728  6709  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 09:54:36.728  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.728  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.728  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.728  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.728  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.728  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.728  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.728  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.728  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.728  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.728  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.728  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.728  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.728  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.729  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.729  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.729  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.729  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.730  1037  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:36.731  1037  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:36.731  1037  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:36.732  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.732  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.732  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.732  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.732  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.732  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.732  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.732  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.732  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.732  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.732  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.732  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.732  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.732  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.735  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.735  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.735  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.735  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.735  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:36.736  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:36.736  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:36.736  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:36.736  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.736  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.736  6709  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4de399 not in the list
08-05 09:54:36.736  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.736  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.736  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:36.736  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.736  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.736  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:36.736  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:36.736  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:36.736  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:36.736  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:36.736  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d8b65e not in the list
08-05 09:54:36.737  6709  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 09:54:36.737  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 09:54:36.738  6709  6778 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-05 09:54:36.738  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 09:54:36.738  6709  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 09:54:36.738  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 09:54:36.740  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 09:54:36.740  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-05 09:54:36.741  6709  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 09:54:36.741  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 09:54:36.741  6709  6778 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-05 09:54:36.741  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 09:54:36.742  6709  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread w,ith ID 2
08-05 09:54:36.742  6709  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 09:54:36.743  6709  6778 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-05 09:54:36.743  6709  6778 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 09:54:36.744  6709  6778 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 09:54:36.744  6709  6778 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-05 09:54:36.744  6709  6778 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 09:54:36.744  6709  6778 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 09:54:36.745  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:36.745  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd77237 added. We now have 2 listener(s)
08-05 09:54:36.745  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:36.747  6709  6778 D BluetoothAdapter: enable(): BT is already enabled..!
08-05 09:54:36.747  1037  1906 D WifiServiceImplEx: setWifiEnabled: true pid=6709, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 09:54:36.748  1037  1906 D WifiService: setWifiEnabled: true pid=6709, uid=10118
08-05 09:54:36.748  1037  1906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 09:54:36.749  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:36.749  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d1293a4 added. We now have 3 listener(s)
08-05 09:54:36.749  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 09:54:36.753  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:36.753  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ebd050d added. We now have 4 listener(s)
08-05 09:54:36.753  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:36.755  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:36.755  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3134cc2 added. We now have 5 listener(s)
08-05 09:54:36.755  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:36.757  1037  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6709, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 09:54:36.757  1037  1052 D WifiService: setWifiEnabled: false pid=6709, uid=10118
08-05 09:54:36.757  1037  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 09:54:36.773  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 09:54:36.774  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 09:54:36.774  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-05 09:54:36.775  1037  1377 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-05 09:54:36.775  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 09:54:36.775  1037  1377 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 09:54:36.775  1037  1377 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 09:54:36.776  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 09:54:36.776  1037  1377 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 09:54:36.776  1037  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 09:54:36.776  1037  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 09:54:36.776  1037  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 09:54:36.776  1037  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 09:54:36.777  1037  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:36.777  1037  1921 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3f84112c mBinding = false
08-05 09:54:36.788  1037  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 09:54:36.788  1037  1376 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.788  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.788  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 09:54:36.788  2694  2694 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 09:54:36.789  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 09:54:36.789  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 09:54:36.789  1037  1377 D WifiNative-wlan0: SET ps 1: returned true
08-05 09:54:36.789  1037  2827 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 09:54:36.791   318   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 09:54:36.807  6709  6784 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-05 09:54:36.807  1037  1906 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-05 09:54:36.808  1037  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.808  1037  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.808  1037  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 09:54:36.808  1037  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.808  1037  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 09:54:36.808  6709  6784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
08-05 09:54:36.811   318  6790 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 09:54:36.811  1037  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-05 09:54:36.812  1037  1117 D DSQN    : Dns fail occured do internet check.
08-05 09:54:36.812  1037  1037 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-05 09:54:36.812  1037  1037 D DSQN    : try Internet connection check
08-05 09:54:36.813  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 09:54:36.813  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 09:54:36.813  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-05 09:54:36.813  1037  1119 D BluetoothManagerService: Message: 2
08-05 09:54:36.814  1037  1119 D BluetoothManagerService: Sending off request.
08-05 09:54:36.814  3891  3909 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 09:54:36.814  3891  3968 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 09:54:36.814  3891  3968 D BluetoothAdapterProperties: Setting state to 13
08-05 09:54:36.814  3891  3968 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 09:54:36.815  3891  3968 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 09:54:36.815  3891  3968 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 09:54:36.815  1037  1119 D BluetoothManagerService: Message: 60
08-05 09:54:36.816  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 09:54:36.816  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 09:54:36.817  3891  3891 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:36.817  3891  3891 D BluetoothMapService: STATE_TURNING_OFF
08-05 09:54:36.817  3891  3891 V BluetoothMapService: Handler(): got msg=4
08-05 09:54:36.818  3891  3891 D BluetoothMapService: MAP Service closeService in
08-05 09:54:36.818  3891  3891 D BluetoothMapMasInstance: MAP Service shutdown
08-05 09:54:36.818  3891  4174 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 09:54:36.818  3891  4174 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:36.818  3891  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 09:54:36.818  3891  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 09:54:36.818  3891  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSo,cket.accept(BluetoothSocket.java:418)
08-05 09:54:36.818  3891  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 09:54:36.818  3891  4174 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 09:54:36.818  3891  4174 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 09:54:36.819  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 09:54:36.819  3891  3891 V BluetoothMapService: MAP Service closeService out
08-05 09:54:36.819  3891  3891 V BtOppService: Receiver DISABLED_ACTION 
08-05 09:54:36.819  3891  3891 I BtOppRfcommListener: stopping Accept Thread
08-05 09:54:36.819  3891  3891 V BtOppRfcommListener: close mBtServerSocket
,08-05 09:54:36.819  3891  3891 V BtOppRfcommListener: waiting for thread to terminate
08-05 09:54:36.821  3891  4210 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:36.821  3891  4210 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 09:54:36.821  3891  3891 V BtOppRfcommListener: done waiting for thread to terminate
08-05 09:54:36.822  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:36.822  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 09:54:36.830  1037  1428 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 09:54:36.831  1037  1428 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-05 09:54:36.834  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.834  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:36.834  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.834  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.834  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:36.834  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:36.834  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.834  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:36.834  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:36.834  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.834  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:36.851  1037  1112 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6796 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 09:54:36.852  1037  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:36.853  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:36.853  1037  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-05 09:54:36.853  1037  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:36.854  1037  1376 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.854  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.854  3891  3891 V BtOppService: onDestroy
08-05 09:54:36.855  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-05 09:54:36.856  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:36.856  1037  1376 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1b373a0c
08-05 09:54:36.859  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.859  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:36.859  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.859  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.859  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:36.859  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:36.859  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:36.859  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:36.859  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:36.859  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.859  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:36.859  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 09:54:36.860  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:36.860  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:36.860  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 09:54:36.860  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:36.861  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-05 09:54:36.862  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-05 09:54:36.863  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:36.863  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:54:36.863  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:36.863  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 09:54:36.864  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 09:54:36.864  1037  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.864  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-05 09:54:36.864  1037  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.868  3891  3891 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 09:54:36.868  1037  1376 D LGWifiP2pService: P2pDisablingState
08-05 09:54:36.868  1037  1376 D LGWifiP2pService: P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.868  1037  1376 D LGWifiP2pService: p2p socket connection lost
08-05 09:54:36.868  1037  1376 D LGWifiP2pService: P2pDisabledState
08-05 09:54:36.869  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 09:54:36.871  1925  1925 D WfdsService: WifiP2pState is changed : false
08-05 09:54:36.871  1925  2321 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 09:54:36.871  1925  2321 D WfdsService: Set the WFDS Monitor: false
08-05 09:54:36.871  1925  2321 D WfdsMonitor: WFDS Monitor is stopped
08-05 09:54:36.871  1925  2321 D WfdsService: STATE : WfdsDisabledState - enter
08-05 09:54:36.872  1925  2733 D CtrlSupplicant: Received on exit socket, terminate
08-05 09:54:36.872  1925  2733 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 09:54:36.872  1925  2733 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 09:54:36.872  1925  2733 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 09:54:36.872  1925  2322 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 09:54:36.872  1925  2321 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 09:54:36.872  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:36.873  1037  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:36.873  1037  1377 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 09:54:36.874  1037  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 09:54:36.874  1037  1376 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.874  1037  1376 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.874  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 09:54:36.874  2694  2694 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 09:54:36.875  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 09:54:36.875  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 09:54:36.876  1037  1377 D WifiNative-wlan0: SET ps 1: returned true
08-05 09:54:36.896   318   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 09:54:36.896  1037  1428 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 09:54:36.896   318  6819 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 09:54:36.896  1037  1428 D DSQN    : disableDataServiceNotify
08-05 09:54:36.897  1037  1428 D DSQN    : stop dsqn bin
08-05 09:54:36.897  1037  6793 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-05 09:54:36.898  1037  6791 D DSQN    : ThreadInternetCheck internet check NOK 
08-05 09:54:36.898  1037  6791 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-05 09:54:,36.898  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 09:54:36.898  1037  1377 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 09:54:36.899  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-05 09:54:36.899  1037  1377 D WifiNative-p2p0: TERMINATE: returned true
08-05 09:54:36.899  1037  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 09:54:36.899  1037  1377 E WifiStateMachine: useWiFiOffloading() : false
08-05 09:54:36.899  1037  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-05 09:54:36.902  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:36.902  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:36.902  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 09:54:36.904  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 09:54:36.905  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 09:54:36.906  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:36.906  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 09:54:36.907  1037  1428 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-05 09:54:36.907  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:36.907  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:36.907  1037  1428 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:36.908  1037  1428 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 09:54:36.908  1037  1428 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 09:54:36.908  1037  1428 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-05 09:54:36.908  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 09:54:36.909  1037  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.909  1037  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.909  1037  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 09:54:36.910  1588  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 09:54:36.910  1037  1428 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:36.910  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 09:54:36.910  1037  1428 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:36.910  1037  1428 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:36.911  1037  1428 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:36.911  1037  1428 D NetworkManagementService: Removing idletimer
08-05 09:54:36.911  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:36.911  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 09:54:36.911  1037  1428 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:36.911  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.911  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:36.911  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.911  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.911  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:36.911  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:36.911  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:36.911  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:36.911  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:36.912  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.912  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 09:54:36.913  1037  1377 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:36.914  1037  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:36.914  1037  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 09:54:36.914  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.914  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:36.914  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.914  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.914  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:36.914  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:36.914  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:36.914  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:36.914  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:36.915  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 09:54:36.915  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.915  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:36.916  1037  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 09:54:36.917  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:36.917  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:36.918  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:36.920  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:36.930  6796  6796 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:54:36.930  6796  6796 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-05 09:54:36.931  6796  6796 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 09:54:36.931  6796  6796 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-05 09:54:36.932  6796  6796 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 09:54:36.933  6796  6796 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 09:54:36.938  1037  1637 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6823 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 09:54:36.959  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:36.959  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:36.965  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 09:54:36.966  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 09:54:36.966  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:36.967  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:36.969  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:36.973  1037  1956 I art     : Explicit concurrent mark sweep GC freed 29982(1575KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.562ms total 172.084ms
08-05 09:54:36.975  1037  1428 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-05 09:54:36.975  3891  3975 D BluetoothAdapterProperties: Scan Mode:20
08-05 09:54:36.975  3891  3968 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 09:54:36.976  3891  4179 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:36.976  3891  3968 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 09:54:36.976  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 09:54:36.977  3891  4219 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:36.977  3891  4217 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:36.978  3891  4054 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 09:54:36.980  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 09:54:36.980  3891  4054 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 09:54:36.980  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 09:54:36.980  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 09:54:36.980  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 09:54:36.980  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 09:54:36.981  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 09:54:36.981  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 09:54:36.981  1037  1037 D LocSvc_java: ignore wifi update if we are not in O,PENING or CLOSING
08-05 09:54:36.982  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.983  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:36.983  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.983  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.983  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:36.983  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:36.983  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:36.983  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:36.983  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 09:54:36.985  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:36.985  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:36.985  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:36.985  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:36.985  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:36.985  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:36.985  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:36.985  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:36.985  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 09:54:36.997  1037  2827 D DhcpStateMachine: StoppedState
08-05 09:54:36.997  1037  2827 D DhcpStateMachine: StoppedState{ when=-121ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:36.998  1037  1377 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 09:54:36.999  1037  1377 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-05 09:54:37.024  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 09:54:37.027  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:37.027  2694  2694 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 09:54:37.027  2694  2694 I wpa_supplicant: monitor socket send errors count : 1
08-05 09:54:37.027  2694  2694 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-2\x00 that cannot receive messages
08-05 09:54:37.028  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:37.028  1037  2726 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 09:54:37.028  1037  2726 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 09:54:37.037  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-05 09:54:37.044  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 09:54:37.045  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:37.045  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:37.046  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 09:54:37.046  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:54:37.047  1037  1052 I ActivityManager: Killing 6221:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-05 09:54:37.049  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 09:54:37.077  2694  2694 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-05 09:54:37.077  1037  1956 W libprocessgroup: failed to open /acct/uid_10014/pid_6221/cgroup.procs: No such file or directory
08-05 09:54:37.077  2694  2694 W wpa_supplicant: USIM:  scard_deinit function
08-05 09:54:37.078  1037  2726 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 09:54:37.078  1037  2726 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 09:54:37.078  1037  2726 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 09:54:37.078  1037  2726 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 09:54:37.078  1037  2726 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 09:54:37.078  1037  2726 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:37.080  1037  1377 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=327051
08-05 09:54:37.080  1037  1377 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=327052
08-05 09:54:37.080  3891  3891 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 09:54:37.080  3891  3891 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:37.081  3891  3891 V BluetoothPbapReceiver: ***********state = 13
08-05 09:54:37.081  1037  1377 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=327052  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 09:54:37.081  1037  1377 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=327052  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 09:54:37.081  1037  1119 D Tethering: InitialState.processMessage what=4
08-05 09:54:37.081  3891  3891 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 09:54:37.082  3891  3891 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:37.082  3891  3891 V BluetoothPbapService: state: 13
08-05 09:54:37.082  3891  3891 V BluetoothPbapService: Pbap Service closeService in
08-05 09:54:37.084  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 09:54:37.090  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:37.115  6796  6796 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 09:54:37.115  6796  6796 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 09:54:37.124  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:37.126  1037  1053 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6846 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-05 09:54:37.131  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 09:54:37.131  1037  1119 D BluetoothManagerService: Message: 20
08-05 09:54:37.131  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3feefcd7:true
08-05 09:54:37.132  1037  1377 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:37.132  3891  3891 V BluetoothPbapService: successfully stopped pbap service
08-05 09:54:37.132  3891  3891 V BluetoothPbapService: Pbap Service closeService out
08-05 09:54:37.133  1037  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-05 09:54:37.133  3891  3891 V BluetoothPbapService: Pbap Service onDestroy
08-05 09:54:37.133  3891  3891 V BluetoothPbapService: Pbap Service closeService in
08-05 09:54:37.133  3891  3891 V BluetoothPbapService: Pbap Service closeService out
08-05 09:54:37.134  3891  3891 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 09:54:37.139  1037  1119 D BluetoothManagerService: Message: 30
08-05 09:54:37.142  1037  1119 D BluetoothManagerService: Message: 30
08-05 09:54:37.144  6796  6796 D LocalBluetoothProfileManager: Adding local MAP profile
08-05 09:54:37.145  6796  6796 D BluetoothMap: Create BluetoothMap proxy object
08-05 09:54:37.145  1037  1119 D BluetoothManagerService: Message: 30
08-05 09:54:37.145   380   380 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 313us total 14.686ms
,08-05 09:54:37.149  1037  1119 D BluetoothManagerService: Message: 30
08-05 09:54:37.150  6796  6796 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-05 09:54:37.151  6796  6796 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-05 09:54:37.159  6796  6796 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-05 09:54:37.160   380   380 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 13.181ms
,08-05 09:54:37.164  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-05 09:54:37.173   380   380 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 11.865ms
,08-05 09:54:37.177  6796  6796 D DockEventReceiver: finishStartingService: stopping service
08-05 09:54:37.186  6796  6796 D BluetoothInputDevice: Proxy object connected
,08-05 09:54:37.187  6796  6796 D HidProfile: Bluetooth service connected
08-05 09:54:37.188  6796  6796 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 09:54:37.188  6796  6796 D PanProfile: Bluetooth service connected
08-05 09:54:37.189  6796  6796 D BluetoothMap: Proxy object connected
08-05 09:54:37.190  6796  6796 D MapProfile: Bluetooth service connected
08-05 09:54:37.190  6796  6796 D BluetoothMap: getConnectedDevices()
08-05 09:54:37.190  6796  6796 D BluetoothMap: Bluetooth is Not enabled
08-05 09:54:37.190  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 09:54:37.196  2694  2694 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 09:54:37.196  1037  2726 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 09:54:37.196  1037  2726 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 09:54:37.196  1037  2726 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 09:54:37.197  1037  1377 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-05 09:54:37.219  1037  1053 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6870 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-05 09:54:37.221  1037  1053 I ActivityManager: Killing 2112:com.lge.music/u0a34 (adj 15): empty #17
,08-05 09:54:37.226  6709  6709 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-05 09:54:37.241   322  2138 V AudioFlinger: 2112 died, releasing its sessions
08-05 09:54:37.241   322  2138 V AudioFlinger:  pid 1836 @ 0
08-05 09:54:37.241   322  2138 V AudioFlinger:  pid 3493 @ 1
08-05 09:54:37.241   322  2138 V AudioFlinger:  pid 3493 @ 2
,08-05 09:54:37.252  6846  6846 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 09:54:37.253  6846  6846 W LG Account v2.2: No ProfileInfo entries
,08-05 09:54:37.253  6846  6846 I LG Account v2.2: isEnabled: false
08-05 09:54:37.253  6846  6846 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 09:54:37.253  6846  6846 I Feature : [Lifetracker]Country: EU
08-05 09:54:37.253  6846  6846 I Feature : [Lifetracker]Operator: OPEN
08-05 09:54:37.253  6846  6846 I Feature : [Lifetracker]Ranking support: false
08-05 09:54:37.253  6846  6846 I Feature : [Lifetracker]Comfort support: false
08-05 09:54:37.253  6846  6846 I Feature : [Lifetracker]Accessory: true
08-05 09:54:37.254  6846  6846 I Feature : [Lifetracker]Health device: true
08-05 09:54:37.254  6846  6846 I Feature : [Lifetracker]Extra Pedometer: false
08-05 09:54:37.254  6846  6846 I Feature : [Lifetracker]Blood glucose device: false
08-05 09:54:37.254  6846  6846 I Feature : [Lifetracker]Device Number: 3
08-05 09:54:37.255  1037  1870 W libprocessgroup: failed to open /acct/uid_10034/pid_2112/cgroup.procs: No such file or directory
,08-05 09:54:37.262  6796  6796 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 09:54:37.267  6796  6796 D BluetoothPermissionRequest: onReceive
08-05 09:54:37.268  6870  6870 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 09:54:37.269  6796  6796 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 09:54:37.278  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 09:54:37.279  1037  1941 I ActivityManager: Killing 6367:com.android.defcontainer/u0a4 (adj 15): empty #17
08-05 09:54:37.308  1037  1906 W libprocessgroup: failed to open /acct/uid_10004/pid_6367/cgroup.procs: No such file or directory
08-05 09:54:37.308  3891  3891 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 09:54:37.309  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 09:54:37.309  1037  1377 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 09:54:37.309  1037  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 09:54:37.309  1037  1377 E WifiStateMachine: useWiFiOffloading() : false
08-05 09:54:37.309  1037  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-05 09:54:37.310  3891  3891 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 09:54:37.310  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-05 09:54:37.310  1925  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 09:54:37.310  1925  2321 D WfdsService: Set the WFDS Monitor: false
08-05 09:54:37.310  1925  2321 D WfdsMonitor: WFDS Monitor is stopped
08-05 09:54:37.312  2487  2487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:37.312  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 09:54:37.312  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:37.313  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 09:54:37.314  1037  1384 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 09:54:37.314  1037  1384 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 09:54:37.315  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:37.316  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:37.316  3891  3891 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 09:54:37.316  6870  6870 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-05 09:54:37.317  3891  3891 V BluetoothFtpService: Ftp Service onStartCommand
08-05 09:54:37.317  3891  3891 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:37.317  3891  3891 V BluetoothFtpService: Ftp Service closeService
08-05 09:54:37.317  3891  3891 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 09:54:37.318  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:37.320  3891  3891 V BluetoothFtpService: successfully stopped ftp service
08-05 09:54:37.320  3891  3891 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 09:54:37.320  3891  3891 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 09:54:37.320  3891  3891 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 09:54:37.320  3891  3891 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:37.320  3891  3891 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 09:54:37.321  3891  3891 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-05 09:54:37.323  3891  3891 V BluetoothFtpService: Ftp Service onDestroy
08-05 09:54:37.323  3891  3891 V BluetoothFtpService: Ftp Service closeService
08-05 09:54:37.355  6870  6870 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-05 09:54:37.355  6870  6870 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-05 09:54:37.356  6870  6870 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-05 09:54:37.356  6870  6870 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-05 09:54:37.357  6870  6870 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 09:54:37.359  6870  6870 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-05 09:54:37.362  1037  1870 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6890 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 09:54:37.363  3891  3891 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:37.363  3891  3891 V BluetoothSapService: state: 13
08-05 09:54:37.363  3891  3891 V BluetoothSapService: Stopping SAP server process
08-05 09:54:37.364  3891  3891 V BluetoothSapService: Sap Service closeSapService in
08-05 09:54:37.365  3891  3891 V BluetoothSapService: Close listen Socket : 
08-05 09:54:37.365  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
08-05 09:54:37.365  3891  3891 V BluetoothSapService: Close sapd  Socket : 
08-05 09:54:37.367  3891  3891 V BluetoothSapService: Sap Service closeSapService out
08-05 09:54:37.367  3891  3891 V BluetoothSapService: Sap Service onDestroy
08-05 09:54:37.367  3891  3891 V BluetoothSapService: Sap Service closeSapService in
08-05 09:54:37.367  3891  3891 V BluetoothSapService: Close listen Socket : 
08-05 09:54:37.367  3891  3891 V BluetoothSapService: Close rfcomm Socket : 
08-05 09:54:37.368  3891  3891 V BluetoothSapService: Close sapd  Socket : 
,08-05 09:54:37.370  6870  6870 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-05 09:54:37.372  3891  3891 V BluetoothSapService: Sap Service closeSapService out
08-05 09:54:37.376  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:37.379  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 09:54:37.399  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 09:54:37.404  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:37.407  6870  6870 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-05 09:54:37.410  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 09:54:37.410  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 09:54:37.410  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 09:54:37.411  6870  6870 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-05 09:54:37.417  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:37.422  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:37.425  6890  6890 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 09:54:37.429  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:37.430  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:37.431  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 09:54:37.433  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 09:54:37.437  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 09:54:37.437  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 09:54:37.437  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:54:37.440  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 09:54:37.445  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:37.450  1037  1941 I ActivityManager: Killing 6479:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-05 09:54:37.479  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:37.480  1037  1871 W libprocessgroup: failed to open /acct/uid_10008/pid_6479/cgroup.procs: No such file or directory
08-05 09:54:37.480  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 09:54:37.484  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 09:54:37.577  1037  1906 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6910 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-05 09:54:37.701  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 09:54:37.710  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 09:54:37.725  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 09:54:37.753  6910  6932 W FormManager: Network not available. Please check & try again.
,08-05 09:54:37.759  6910  6933 V FormManager: Network unavailable.
08-05 09:54:37.766  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 09:54:37.766  6910  6933 V FormManager: Network unavailable.
08-05 09:54:37.766  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 09:54:37.766  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 09:54:37.766  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 09:54:37.767  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 09:54:37.775  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 09:54:37.776  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 09:54:37.776  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 09:54:37.776  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 09:54:37.776  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 09:54:37.776  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-05 09:54:37.781  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 09:54:37.781  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 09:54:37.783  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:37.785  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:37.793  6823  6823 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-05 09:54:37.793  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 09:54:37.793  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:54:37.794  4310  6936 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 09:54:37.798  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 09:54:37.802  4310  6937 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 09:54:37.802  4310  6937 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 09:54:37.805  6910  6939 V FormManager: Network unavailable.
08-05 09:54:37.806  6910  6938 W FormManager: Network not available. Please check & try again.
,08-05 09:54:37.808  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:37.809  6910  6939 V FormManager: Network unavailable.
08-05 09:54:37.816  1037  1956 I ActivityManager: Killing 6027:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-05 09:54:37.848  1037  1637 W libprocessgroup: failed to open /acct/uid_10011/pid_6027/cgroup.procs: No such file or directory
,08-05 09:54:37.866  6870  6870 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-05 09:54:37.867  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 09:54:37.869  6870  6870 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-05 09:54:37.898  1037  1037 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-05 09:54:37.924  6870  6870 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:54:37.924  6870  6870 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 09:54:37.933  6870  6870 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-05 09:54:37.935  6870  6870 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-05 09:54:37.935  6870  6870 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-05 09:54:37.935  6870  6870 V SoundPool: doLoad: loading sample sampleID=1
08-05 09:54:37.936  6870  6870 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 09:54:37.940  6870  6942 V SoundPool: Start decode
08-05 09:54:37.940  6870  6942 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-05 09:54:37.940  6634  6634 D UEI.SmartControl: QS Service created
08-05 09:54:37.942   322  1387 V MediaPlayerService: decode(23, 10857164, 17813)
08-05 09:54:37.942   322  1387 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 09:54:37.942   322  1387 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 09:54:37.942   322  1387 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 09:54:37.942   322  1387 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 09:54:37.942   322  1387 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 09:54:37.942   322  1387 V MediaPlayerService: player type = 3
08-05 09:54:37.942   322  1387 V AwesomePlayer: AwesomePlayer create()
08-05 09:54:37.943   322  1387 V AwesomePlayer: reset_l() 
08-05 09:54:37.943   322  1387 V AwesomePlayer: cancelPlayerEvents
08-05 09:54:37.943   322  1387 V AwesomePlayer: setAudioSink() 
08-05 09:54:37.943   322  1387 V AwesomePlayer: reset_l() 
08-05 09:54:37.943   322  1387 V AudioCache: notify(0xb5474f00, 8, 0, 0)
08-05 09:54:37.943   322  1387 V AudioCache: ignored
08-05 09:54:37.943   322  1387 V AwesomePlayer: cancelPlayerEvents
08-05 09:54:37.943   322  1387 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 09:54:37.943   322  1387 V AwesomePlayer: setDataSource_l dataSource
08-05 09:54:37.943   322  1387 V LGParserOSAL: SniffLGParser start
08-05 09:54:37.943   322  1387 V LGParserOSAL: MainType:5, SubType=0
08-05 09:54:37.943   322  1387 V LGParserOSAL: #### check Mime : application/ogg
,08-05 09:54:37.943   322  1387 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 09:54:37.943   322  1387 E MediaExtractor: Use LGExtractor :application/ogg 
,08-05 09:54:37.957  6870  6870 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 09:54:37.962  6870  6870 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 09:54:37.963  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-05 09:54:37.972  6634  6634 I UEI.SmartControl: Service initServices...
08-05 09:54:37.972  6634  6634 D UEI.SmartControl: QS start get config
,08-05 09:54:37.986  3891  3975 D bt_hci_bdroid: cleanup
08-05 09:54:37.986  3891  4056 I bt_lpm  : LPM is already off!!!
08-05 09:54:37.986  3891  4148 I bt_userial_mct: exiting userial_read_thread
08-05 09:54:37.986  3891  4148 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 09:54:37.987  3891  3975 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 09:54:37.987  3891  4056 I bt_vendor: hw_epilog_process
08-05 09:54:37.987  3891  3975 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 09:54:37.987  3891  3975 D bt_userial_mct: userial_close
08-05 09:54:37.987  3891  3975 E bt_userial_mct: pthread_join() FAILED result:3
08-05 09:54:37.987  3891  3975 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 09:54:37.987  3891  4054 W bt-btif : ag scb idx 1 not allocated
08-05 09:54:37.987  3891  4054 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:37.987  3891  4054 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 09:54:37.988  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:37.988  3891  4054 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 09:54:37.988  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:37.988  3891  4054 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 09:54:37.988  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:37.988  3891  4054 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 09:54:37.988  3891  4054 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:37.988  3891  4054 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 09:54:37.988  3891  4054 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 09:54:37.990  6870  6870 V LGMDMManager: Create singleton instance
08-05 09:54:38.003   322  1387 V LGParserOSAL: supported mime: application/ogg
08-05 09:54:38.003   322  1387 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 09:54:38.003   322  1387 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 09:54:38.003   322  1387 V AwesomePlayer: mBitrate = -1 bits/sec
08-05 09:54:38.003   322  1387 V AwesomePlayer: AudioTrack Setting
08-05 09:54:38.003   322  1387 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 09:54:38.003   322  1387 V AwesomePlayer: setAudioSource() 
08-05 09:54:38.003   322  1387 V MediaPlayerService: prepare
08-05 09:54:38.003   322  1387 V AwesomePlayer: prepareAsync_l() 
08-05 09:54:38.003   322  1387 V MediaPlayerService: wait for prepare
08-05 09:54:38.003   322  6944 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 09:54:38.003   322  6944 V AwesomePlayer: initAudioDecoder() 
08-05 09:54:38.003   322  6944 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 09:54:38.004   322  6944 V AudioSystem: isOffloadSupported()
08-05 09:54:38.004   322  6944 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRat,e=4294967295, duration=1068125 us, has_video=0
08-05 09:54:38.004   322  6944 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 09:54:38.004   322  6944 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 09:54:38.004   322  6944 V AwesomePlayer: getUseOffload() = 0 
08-05 09:54:38.004   322  6944 V OMXCodec: OMXCodec::Create
08-05 09:54:38.004   322  6944 V OMXCodec: findMatchingCodecs()
08-05 09:54:38.004   322  6944 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 09:54:38.004   322  6944 V OMXCodec: matchingCodecs.size()=1
08-05 09:54:38.004   322  6944 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-05 09:54:38.007   322  6944 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 09:54:38.007   322  6944 V LGCodecAdapter: LG Codec Adapter start
08-05 09:54:38.007   322  6944 V OMXCodec: OMXCodec Createtor
08-05 09:54:38.007   322  6944 V OMXCodec: setComponentRole
08-05 09:54:38.007   322  6944 V OMXCodec: configureCodec protected=0
08-05 09:54:38.007   322  6944 V LGCodecAdapter: called getLGCodecSpecificData
08-05 09:54:38.007   322  6944 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-05 09:54:38.007   322  6944 V LGCodecOSAL: Called LGconfigureCodecMETA
08-05 09:54:38.007   322  6944 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 09:54:38.007   322  6944 V LGCodecOSAL: Not support LGCodec
08-05 09:54:38.007   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 09:54:38.007   322  6944 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 09:54:38.007   322  6944 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-05 09:54:38.007   322  6944 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 09:54:38.007   322  6944 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 09:54:38.007   322  6944 V AudioSystem: isOffloadSupported()
08-05 09:54:38.007   322  6944 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 09:54:38.007   322  6944 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 09:54:38.007   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-05 09:54:38.007   322  6944 V OMXCodec: init()
08-05 09:54:38.007   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-05 09:54:38.007   322  6944 V OMXCodec: allocateBuffers
08-05 09:54:38.007   322  6944 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 09:54:38.007   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-05 09:54:38.008   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
08-05 09:54:38.008   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on input port
08-05 09:54:38.008   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b81f0 on input port
08-05 09:54:38.008   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on input port
08-05 09:54:38.008   322  6944 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 09:54:38.008   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 09:54:38.008   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on output port
08-05 09:54:38.008   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on output port
08-05 09:54:38.008   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b89c0 on output port
08-05 09:54:38.008   322  6944 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8a10 on output port
08-05 09:54:38.008   322  6944 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 09:54:38.008   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 09:54:38.008   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 09:54:38.008   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 09:54:38.009   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-05 09:54:38.009   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-05 09:54:38.009   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-05 09:54:38.009   322  6944 V OMXCodec: init() mAsyncCompletion wait free! 
08-05 09:54:38.009   322  6944 V AwesomePlayer: finishAsyncPrepare_l() 
08-05 09:54:38.009   322  6944 V AudioCache: notify(0xb5474f00, 5, 0, 0)
08-05 09:54:38.009   322  6944 V AudioCache: ignored
08-05 09:54:38.009   322  6944 V AudioCache: notify(0xb5474f00, 1, 0, 0)
08-05 09:54:38.009   322  6944 V AudioCache: prepared
08-05 09:54:38.010   322  1387 V AudioCache: wait - success
08-05 09:54:38.011   322  1387 V MediaPlayerService: start
08-05 09:54:38.011   322  1387 V AwesomePlayer: play_l() 
08-05 09:54:38.011   322  1387 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-05 09:54:38.011   322  1387 V AwesomePlayer: createAudioPlayer_l
08-05 09:54:38.011   322  1387 V AwesomePlayer: seekAudioIfNecessary_l() 
08-05 09:54:38.011   322  1387 V AwesomePlayer: startAudioPlayer_l() 
08-05 09:54:38.011   322  1387 D AudioPlayer: start of Playback, useOffload 0
08-05 09:54:38.011   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 09:54:38.012   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 09:54:38.015   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 09:54:38.015   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-05 09:54:38.015   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-05 09:54:38.015   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-05 09:54:38.015   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 09:54:38.015   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 09:54:38.015   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517456
08-05 09:54:38.015   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517616
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517696
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517776
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 09:54:38.016   322  6946 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b89c0 on output port
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on output port
,08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on output port
08-05 09:54:38.016   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on output port
08-05 09:54:38.017   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-05 09:54:38.017   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 09:54:38.019   322  1387 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 09:54:38.025   322  1387 V AudioCache: notify(0xb5474f00, 6, 0, 0)
08-05 09:54:38.025   322  1387 V AudioCache: ignored
08-05 09:54:38.026   322  1387 V MediaPlayerService: wait for playback complete
08-05 09:54:38.027   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.027   322  6947 V AudioCache: memcpy(0xac300000, 0xb57f1000, 4096)
,08-05 09:54:38.030   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.030   322  6947 V AudioCache: memcpy(0xac301000, 0xb57f1000, 4096)
08-05 09:54:38.030   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.030   322  6947 V AudioCache: memcpy(0xac302000, 0xb57f1000, 4096)
08-05 09:54:38.031   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.031   322  6947 V AudioCache: memcpy(0xac303000, 0xb57f1000, 4096)
08-05 09:54:38.032   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.032   322  6947 V AudioCache: memcpy(0xac304000, 0xb57f1000, 4096)
08-05 09:54:38.033   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.033   322  6947 V AudioCache: memcpy(0xac305000, 0xb57f1000, 4096)
08-05 09:54:38.034   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.034   322  6947 V AudioCache: memcpy(0xac306000, 0xb57f1000, 4096)
08-05 09:54:38.035   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.035   322  6947 V AudioCache: memcpy(0xac307000, 0xb57f1000, 4096)
08-05 09:54:38.036   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.036   322  6947 V AudioCache: memcpy(0xac308000, 0xb57f1000, 4096)
08-05 09:54:38.037   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.037   322  6947 V AudioCache: memcpy(0xac309000, 0xb57f1000, 4096)
08-05 09:54:38.038   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.038   322  6947 V AudioCache: memcpy(0xac30a000, 0xb57f1000, 4096)
08-05 09:54:38.038   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.038   322  6947 V AudioCache: memcpy(0xac30b000, 0xb57f1000, 4096)
08-05 09:54:38.039   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.039   322  6947 V AudioCache: memcpy(0xac30c000, 0xb57f1000, 4096)
08-05 09:54:38.042   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.042   322  6947 V AudioCache: memcpy(0xac30d000, 0xb57f1000, 4096)
08-05 09:54:38.042   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.042   322  6947 V AudioCache: memcpy(0xac30e000, 0xb57f1000, 4096)
08-05 09:54:38.042   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.042   322  6947 V AudioCache: memcpy(0xac30f000, 0xb57f1000, 4096)
08-05 09:54:38.043   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.043   322  6947 V AudioCache: memcpy(0xac310000, 0xb57f1000, 4096)
,08-05 09:54:38.047   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.047   322  6947 V AudioCache: memcpy(0xac311000, 0xb57f1000, 4096)
08-05 09:54:38.047   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.047   322  6947 V AudioCache: memcpy(0xac312000, 0xb57f1000, 4096)
08-05 09:54:38.048  1037  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=361482269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
08-05 09:54:38.048  1037  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2c68798d type 2 when 328018 com.google.android.gms} when 328018
08-05 09:54:38.050   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.050   322  6947 V AudioCache: memcpy(0xac313000, 0xb57f1000, 4096)
08-05 09:54:38.052   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.052   322  6947 V AudioCache: memcpy(0xac314000, 0xb57f1000, 4096)
08-05 09:54:38.052   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.052   322  6947 V AudioCache: memcpy(0xac315000, 0xb57f1000, 4096)
08-05 09:54:38.054   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.054   322  6947 V AudioCache: memcpy(0xac316000, 0xb57f1000, 4096)
,08-05 09:54:38.056   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.056   322  6947 V AudioCache: memcpy(0xac317000, 0xb57f1000, 4096)
08-05 09:54:38.056   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.056   322  6947 V AudioCache: memcpy(0xac318000, 0xb57f1000, 4096)
08-05 09:54:38.057   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.057   322  6947 V AudioCache: memcpy(0xac319000, 0xb57f1000, 4096)
08-05 09:54:38.058   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.058   322  6947 V AudioCache: memcpy(0xac31a000, 0xb57f1000, 4096)
08-05 09:54:38.059   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.059   322  6947 V AudioCache: memcpy(0xac31b000, 0xb57f1000, 4096)
08-05 09:54:38.059   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.059   322  6947 V AudioCache: memcpy(0xac31c000, 0xb57f1000, 4096)
08-05 09:54:38.060   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.060   322  6947 V AudioCache: memcpy(0xac31d000, 0xb57f1000, 4096)
08-05 09:54:38.061   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.061   322  6947 V AudioCache: memcpy(0xac31e000, 0xb57f1000, 4096)
08-05 09:54:38.061   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.061   322  6947 V AudioCache: memcpy(0xac31f000, 0xb57f1000, 4096)
08-05 09:54:38.062   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.062   322  6947 V AudioCache: memcpy(0xac320000, 0xb57f1000, 4096)
08-05 09:54:38.063   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.063   322  6947 V AudioCache: memcpy(0xac321000, 0xb57f1000, 4096)
08-05 09:54:38.064   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.064   322  6947 V AudioCache: memcpy(0xac322000, 0xb57f1000, 4096)
08-05 09:54:38.064   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.064   322  6947 V AudioCache: memcpy(0xac323000, 0xb57f1000, 4096)
08-05 09:54:38.065   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.065   322  6947 V AudioCache: memcpy(0xac324000, 0xb57f1000, 4096)
08-05 09:54:38.066   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.066   322  6947 V AudioCache: memcpy(0xac325000, 0xb57f1000, 4096)
08-05 09:54:38.067   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.067   322  6947 V AudioCache: memcpy(0xac326000, 0xb57f1000, 4096)
08-05 09:54:38.068   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.068   322  6947 V AudioCache: memcpy(0xac327000, 0xb57f1000, 4096)
08-05 09:54:38.069   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.069   322  6947 V AudioCache: memcpy(0xac328000, 0xb57f1000, 4096)
08-05 09:54:38.070   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.070   322  6947 V AudioCache: memcpy(0xac329000, 0xb57f1000, 4096)
08-05 09:54:38.070   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.070   322  6947 V AudioCache: memcpy(0xac32a000, 0xb57f1000, 4096)
08-05 09:54:38.071   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.071   322  6947 V AudioCache: memcpy(0xac32b000, 0xb57f1000, 4096)
08-05 09:54:38.072   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.072   322  6947 V AudioCache: memcpy(0xac32c000, 0xb57f1000, 4096)
08-05 09:54:38.073   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.073   322  6947 V AudioCache: memcpy(0xac32d000, 0xb57f1000, 4096)
08-05 09:54:38.073   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.073   322  6947 V AudioCache: memcpy(0xac32e000, 0xb57f1000, 4096)
08-05 09:54:38.074   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.074   322  6947 V AudioCache: memcpy(0xac32f000, 0xb57f1000, 4096)
08-05 09:54:38.075   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.075   322  6947 V AudioCache: memcpy(0xac330000, 0xb57f1000, 4096)
08-05 09:54:38.075   322  6947 V AudioCache: write(0xb57f1000, 4096)
08-05 09:54:38.075   322  6947 V AudioCache: mem,cpy(0xac331000, 0xb57f1000, 4096)
08-05 09:54:38.076   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-05 09:54:38.076   322  6947 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 09:54:38.076   322  6947 V AwesomePlayer: postAudioEOS() 
08-05 09:54:38.076   322  6947 V AudioCache: write(0xb57f1000, 280)
08-05 09:54:38.076   322  6947 V AudioCache: memcpy(0xac332000, 0xb57f1000, 280)
08-05 09:54:38.079   322  6944 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-05 09:54:38.079   322  6944 V AwesomePlayer: onStreamDone
08-05 09:54:38.079   322  6944 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 09:54:38.079   322  6944 V AudioCache: notify(0xb5474f00, 2, 0, 0)
08-05 09:54:38.080   322  6944 V AudioCache: playback complete
08-05 09:54:38.080   322  6944 V AwesomePlayer: pause_l() 
08-05 09:54:38.080   322  6944 V AudioCache: notify(0xb5474f00, 7, 0, 0)
08-05 09:54:38.080   322  6944 V AudioCache: ignored
08-05 09:54:38.080   322  6944 V AwesomePlayer: cancelPlayerEvents
08-05 09:54:38.080   322  6944 D AudioPlayer: Pause Playback at 1068125
08-05 09:54:38.080   322  1387 V AudioCache: wait - success
08-05 09:54:38.080   322  1387 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-05 09:54:38.080   322  1387 V AwesomePlayer: reset_l() 
08-05 09:54:38.080   322  1387 V AudioCache: notify(0xb5474f00, 8, 0, 0)
08-05 09:54:38.080   322  1387 V AudioCache: ignored
08-05 09:54:38.080   322  1387 V AwesomePlayer: cancelPlayerEvents
08-05 09:54:38.080   322  1387 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 09:54:38.080   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 09:54:38.080   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-05 09:54:38.080   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 09:54:38.080   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 09:54:38.082   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 09:54:38.082   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 09:54:38.082   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-05 09:54:38.082   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8240 on port 0
08-05 09:54:38.082   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 09:54:38.083  2579  2579 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b81f0 on port 0
08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 0
08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 1
08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b88d0 on port 1
08-05 09:54:38.084   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 09:54:38.085   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8970 on port 1
08-05 09:54:38.085   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 09:54:38.085   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b89c0 on port 1
08-05 09:54:38.085   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 09:54:38.085   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 09:54:38.092   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 09:54:38.092   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 09:54:38.093   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 09:54:38.093   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 09:54:38.093   322  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 09:54:38.093   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 09:54:38.093   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 09:54:38.094   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 09:54:38.096  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 09:54:38.097  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-05 09:54:38.098   322  1387 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 09:54:38.098   322  1387 D AudioPlayer: AudioPlayer releasing audio source
08-05 09:54:38.098   322  1387 D AudioPlayer: AudioPlayer done releasing audio source
08-05 09:54:38.098   322  1387 V AwesomePlayer: reset_l() 
08-05 09:54:38.098   322  1387 V AwesomePlayer: cancelPlayerEvents
08-05 09:54:38.098   322  1387 V AwesomePlayer: ~AwesomePlayer call
08-05 09:54:38.098   322  1387 V AwesomePlayer: reset_l() 
08-05 09:54:38.098   322  1387 V AwesomePlayer: cancelPlayerEvents
,08-05 09:54:38.098  6870  6942 V SoundPool: close(31)
08-05 09:54:38.098  6870  6942 V SoundPool: pointer = 0x9fe97000, size = 205080, sampleRate = 48000, numChannels = 2
08-05 09:54:38.101  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9381
08-05 09:54:38.106   318  6954 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 09:54:38.107  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 09:54:38.107  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=361482269 [*alarm*], flags=0x0
,08-05 09:54:38.155  3891  3975 D bt_hci_bdroid: set_power 0
08-05 09:54:38.155  3891  3975 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 09:54:38.155  3891  3975 I bt_vendor: bluetooth satus is on
08-05 09:54:38.155  3891  3975 I bt_vendor: bt-vendor : resetting BT status
08-05 09:54:38.155  3891  3975 I bt_vendor: Starting hciattach daemon
08-05 09:54:38.155  3891  3975 I bt_vendor: try to set false
,08-05 09:54:38.157  3891  3975 I bt_vendor: Starting hciattach daemon
08-05 09:54:38.157  3891  3975 I bt_vendor: try to set false
,08-05 09:54:38.158  3891  3975 I bt_vendor: cleanup
08-05 09:54:38.160  3891  4054 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 09:54:38.160  3891  3975 I GKI_LINUX: GKI_exit_task 0 done
08-05 09:54:38.160  3891  3975 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 09:54:38.163  3891  3968 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 09:54:38.166  3891  3891 D HeadsetService: Received stop request...Stopping profile...
08-05 09:54:38.168  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 09:54:38.169  3891  3891 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 09:54:38.169  3891  3993 D HeadsetStateMachine: Exit Disconnected: -1
08-05 09:54:38.169  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5168d9f
08-05 09:54:38.170  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-05 09:54:38.170  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-05 09:54:38.170  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-05 09:54:38.170  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 09:54:38.172  1836  1836 D BluetoothHeadset: Proxy object disconnected
,08-05 09:54:38.176  3891  3891 D A2dpService: Received stop request...Stopping profile...
08-05 09:54:38.176  3891  4039 D A2dpStateMachine: Exit Disconnected: -1
08-05 09:54:38.177  3891  3968 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 09:54:38.177  3891  3891 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 09:54:38.178  3891  3891 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 09:54:38.178  3891  3891 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 09:54:38.178  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5168d9f
08-05 09:54:38.178  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-05 09:54:38.178  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 09:54:38.179  3891  3891 D HidService: Received stop request...Stopping profile...
08-05 09:54:38.179  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5168d9f
08-05 09:54:38.180  6796  6796 D BluetoothInputDevice: Proxy object disconnected
08-05 09:54:38.180  6796  6796 D HidProfile: Bluetooth service disconnected
08-05 09:54:38.181  3891  3891 D HealthService: Received stop request...Stopping profile...
08-05 09:54:38.181  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5168d9f
08-05 09:54:38.181  3891  3891 D HeadsetStateMachine: Unbinding service...
08-05 09:54:38.182  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 09:54:38.182  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 09:54:38.182  3891  3891 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 09:54:38.182  3891  3891 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 09:54:38.182  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 09:54:38.182  3891  3891 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 09:54:38.182  3891  3891 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 09:54:38.183  3891  3891 D PanService: Received stop request...Stopping profile...
08-05 09:54:38.183  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5168d9f
08-05 09:54:38.184  3891  3891 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 09:54:38.184  6796  6796 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 09:54:38.184  6796  6796 D PanProfile: Bluetooth service disconnected
08-05 09:54:38.184  3891  3891 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 09:54:38.184  3891  3891 D BtGatt.GattService: stop()
08-05 09:54:38.184  3891  3891 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 09:54:38.185  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5168d9f
08-05 09:54:38.186  3891  3891 D BluetoothMapService: Received stop request...Stopping profile...
08-05 09:54:38.186  3891  3891 D BluetoothMapService: stop()
,08-05 09:54:38.186  3891  3891 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 09:54:38.186  3891  3891 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 09:54:38.187  3891  3891 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5168d9f
08-05 09:54:38.188  3891  3891 I BluetoothA2dpServiceJni: cleanupNative
08-05 09:54:38.188  3891  4040 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 09:54:38.188  3891  3891 I GKI_LINUX: GKI_exit_task 2 done
08-05 09:54:38.188  3891  3891 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 09:54:38.188  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 09:54:38.188  3891  3891 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 09:54:38.188  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 09:54:38.188  3891  3891 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 09:54:38.188  3891  3891 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 09:54:38.189  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 09:54:38.189  3891  3891 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 09:54:38.189  3891  3891 V BluetoothMapService: Handler(): got msg=4
08-05 09:54:38.189  3891  3891 D BluetoothMapService: MAP Service closeService in
08-05 09:54:38.189  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 09:54:38.190  3891  3891 V BluetoothMapService: MAP Service closeService out
08-05 09:54:38.190  3891  3968 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 09:54:38.190  3891  3968 D BluetoothAdapterProperties: Setting state to 10
08-05 09:54:38.190  3891  3968 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 09:54:38.190  3891  3891 D BluetoothMapService: cleanup()
08-05 09:54:38.190  3891  3891 D BluetoothMapService: MAP Service closeService in
08-05 09:54:38.190  3891  3891 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 09:54:38.190  3891  3891 V BluetoothMapService: MAP Service closeService out
08-05 09:54:38.191  6796  6796 D BluetoothMap: Proxy object disconnected
08-05 09:54:38.191  6796  6796 D MapProfile: Bluetooth service disconnected
08-05 09:54:38.191  1037  1119 D BluetoothManagerService: Message: 60
08-05 09:54:38.191  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 09:54:38.191  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-05 09:54:38.191  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 09:54:38.191  3891  3968 I BluetoothAdapterState: Entering OffState
08-05 09:54:38.192  1836  4437 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 09:54:38.193  6796  6820 D BluetoothPan: onBluetoothStateChange on: false
08-05 09:54:38.193  6796  6817 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 09:54:38.194  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 09:54:38.194  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 09:54:38.195  6796  6820 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 09:54:38.196  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 09:54:38.197  6796  6817 D BluetoothMap: onBluetoothStateChange: up=false
,08-05 09:54:38.205  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 09:54:38.205  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 09:54:38.207  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 09:54:38.208  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 09:54:38.208  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3f84112c mBinding = false
08-05 09:54:38.208  1037  1119 D BluetoothManagerService: Sending unbind request.
,08-05 09:54:38.214  3891  3975 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-05 09:54:38.214  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 09:54:38.214  3891  3891 I GKI_LINUX: GKI_exit_task 1 done
08-05 09:54:38.214  3891  3891 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 09:54:38.215  3891  3891 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 09:54:38.215  3891  3891 I art     : --- WEIRD: removing null entry 246
08-05 09:54:38.215  3891  3891 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-05 09:54:38.215  3891  3891 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 09:54:38.215  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:38.216  1925  2110 D LGBluetoothAPIService: Message: 2
08-05 09:54:38.216  1925  2110 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1405e80e mBinding = false
08-05 09:54:38.216  1925  2110 D LGBluetoothAPIService: Sending unbind request.
08-05 09:54:38.217  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 09:54:38.223  3891  3891 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 09:54:38.225  3891  3891 I art     : System.exit called, status: 0
,08-05 09:54:38.225  3891  3891 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 09:54:38.226  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:38.226  6796  6796 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 09:54:38.227  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 09:54:38.227  6796  6796 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 09:54:38.228  1588  1588 D BluetoothAdapter: 471803030: getState() :  mService = null. Returning STATE_OFF
08-05 09:54:38.228  1588  1588 D BluetoothAdapter: 471803030: getState() :  mService = null. Returning STATE_OFF
08-05 09:54:38.233  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:38.233  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 09:54:38.240  6796  6796 D DockEventReceiver: finishStartingService: stopping service
,08-05 09:54:38.247   322  1388 V AudioFlinger: 3891 died, releasing its sessions
08-05 09:54:38.247   322  1388 V AudioFlinger:  pid 1836 @ 0
08-05 09:54:38.247   322  1388 V AudioFlinger:  pid 3493 @ 1
08-05 09:54:38.247   322  1388 V AudioFlinger:  pid 3493 @ 2
08-05 09:54:38.248  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-05 09:54:38.295  1037  1972 I ActivityManager: Process com.android.bluetooth (pid 3891) has died
,08-05 09:54:38.295  1037  1972 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-05 09:54:38.298  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 09:54:38.312  6796  6796 D BluetoothPermissionRequest: onReceive
,08-05 09:54:38.316  6796  6796 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 09:54:38.316  6796  6796 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 09:54:38.320  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 09:54:38.390  1037  1870 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6958 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 09:54:38.406  6634  6634 I UEI.SmartControl: Supports setup maps: true
,08-05 09:54:38.410  6634  6634 D UEI.SmartControl: QS start statue = true Error code = 0
,08-05 09:54:38.410  6634  6634 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 09:54:38.410  6634  6634 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 09:54:38.410  6634  6634 I UEI.SmartControl: ### init IR Blaster...
08-05 09:54:38.413  6634  6634 D serial_port: Configuring serial port
08-05 09:54:38.414  6634  6634 E UEI.SmartControl: UEIBLaster setting for 616
08-05 09:54:38.414  6634  6634 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 09:54:38.414  6634  6634 I UEI.SmartControl: configuring settings for MAXQ616
08-05 09:54:38.414  6634  6634 I UEI.SmartControl: Get version...
08-05 09:54:38.433  6634  6973 D UEI.SmartControl: serial port data available: 21
,08-05 09:54:38.451  6958  6958 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 09:54:38.451  6958  6958 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 09:54:38.452  6958  6958 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 09:54:38.452  6958  6958 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 09:54:38.459  6634  6634 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-05 09:54:38.459  6634  6634 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 09:54:38.459  6634  6634 I UEI.SmartControl: QS saving settings...
08-05 09:54:38.461  6634  6634 D UEI.SmartControl: IR Blaster version: 25672567
08-05 09:54:38.471  6958  6958 D BluetoothAdapterApp: Loading JNI Library
,08-05 09:54:38.477  6634  6973 D UEI.SmartControl: serial port data available: 4
,08-05 09:54:38.501  6958  6958 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2bfc954 Instance Count = 1
,08-05 09:54:38.509  6634  6634 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 09:54:38.514  6634  6634 E UEI.SmartControl: Services init done
08-05 09:54:38.514  6634  6634 D UEI.SmartControl: QS Service init finished
08-05 09:54:38.514  6634  6981 I UEI.SmartControl: Device manager: loading config....
08-05 09:54:38.516  6958  6958 D BluetoothAdapterApp: onCreate
,08-05 09:54:38.519  6634  6981 D UEI.SmartControl: ----------- loading internal config...
08-05 09:54:38.523  6634  6634 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 09:54:38.523  6634  6634 D UEI.SmartControl: QS Service version code: 201091
08-05 09:54:38.523  6634  6634 D UEI.SmartControl: Service requested: Control
08-05 09:54:38.525  6634  6981 E UEI.SmartControl: Loading SETTINGS...
08-05 09:54:38.529  6634  6634 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 09:54:38.530  6634  6634 D UEI.SmartControl: Internal service binding...
,08-05 09:54:38.531  6870  6870 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 09:54:38.534  6634  6649 I UEI.SmartControl: ------ IControl API: 11
,08-05 09:54:38.534  6634  6649 D UEI.SmartControl: File observer start...
08-05 09:54:38.535  6634  6649 E UEI.SmartControl: IR Port is disabled: false
08-05 09:54:38.535  6634  6649 D UEI.SmartControl: Starting file observer...
08-05 09:54:38.535  6634  6981 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 09:54:38.537  6634  6649 I UEI.SmartControl: Registering callback...
08-05 09:54:38.538  6634  6650 I UEI.SmartControl: ------ IControl API: 19
08-05 09:54:38.539  6634  6650 I UEI.SmartControl: Registering Services Ready callback...
08-05 09:54:38.543  6634  6980 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 09:54:38.543  6958  6958 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 09:54:38.543  6958  6958 D ProfileConfigQcom: Adding HeadsetService
08-05 09:54:38.544  6634  6980 D UEI.SmartControl: -----service ready thread exits
08-05 09:54:38.544  6958  6958 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 09:54:38.544  6958  6958 D ProfileConfigQcom: Adding A2dpService
,08-05 09:54:38.544  6958  6958 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 09:54:38.544  6958  6958 D ProfileConfigQcom: Adding HidService
08-05 09:54:38.545  6958  6958 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 09:54:38.545  6958  6958 D ProfileConfigQcom: Adding HealthService
08-05 09:54:38.545  6958  6958 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 09:54:38.545  6870  6885 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 09:54:38.546  6958  6958 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 09:54:38.546  6958  6958 D ProfileConfigQcom: Adding PanService
08-05 09:54:38.546  6958  6958 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 09:54:38.546  6870  6940 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 09:54:38.547  6958  6958 D ProfileConfigQcom: Adding GattService
08-05 09:54:38.547  6958  6958 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 09:54:38.547  6870  6940 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 09:54:38.547  6958  6958 D ProfileConfigQcom: Adding BluetoothMapService
08-05 09:54:38.547  6958  6958 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 09:54:38.549  6958  6958 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 09:54:38.549  6870  6870 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 09:54:38.550  6870  6870 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 09:54:38.551  6634  6649 I UEI.SmartControl: ------ IControl API: 8
08-05 09:54:38.553  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 09:54:38.556  6958  6958 V LGMDMManagerInternal: Create singleton instance
08-05 09:54:38.556  6870  6870 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 09:54:38.557  6870  6870 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,08-05 09:54:38.557  6870  6870 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 09:54:38.558  6870  6870 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 09:54:38.560  6870  6870 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 09:54:38.560  6870  6870 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 09:54:38.562  6870  6870 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-05 09:54:38.569  6870  6870 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 09:54:38.571  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-05 09:54:38.573  6870  6870 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 09:54:38.574  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 09:54:38.575  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 09:54:38.576  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 09:54:38.576  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 09:54:38.577  6870  6870 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470383678577]
08-05 09:54:38.580  6870  6870 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-05 09:54:38.587  1037  1906 I ActivityManager: Killing 6053:com.android.contacts/u0a19 (adj 15): empty #17
,08-05 09:54:38.611  6870  6984 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 09:54:38.659  1037  1871 W libprocessgroup: failed to open /acct/uid_10019/pid_6053/cgroup.procs: No such file or directory
,08-05 09:54:38.666  6958  6958 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:38.672  6870  6870 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-05 09:54:38.674  6958  6958 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 09:54:38.674  6870  6870 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 09:54:38.675  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 09:54:38.675  6958  6958 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 09:54:38.676  6958  6958 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 09:54:38.676  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 09:54:38.677  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-05 09:54:38.678  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 09:54:38.679  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-05 09:54:38.680  6958  6958 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:38.680  6958  6958 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 09:54:38.698  6890  6890 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-05 09:54:38.704  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-05 09:54:38.706  1037  1972 I ActivityManager: Killing 6524:com.lge.email/u0a23 (adj 15): empty #17
08-05 09:54:38.737  1037  1870 W libprocessgroup: failed to open /acct/uid_10023/pid_6524/cgroup.procs: No such file or directory
,08-05 09:54:39.864  1037  2016 D WifiServiceImplEx: setWifiEnabled: true pid=6709, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-05 09:54:39.873  1037  2016 D WifiService: setWifiEnabled: true pid=6709, uid=10118
08-05 09:54:39.873  1037  2016 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 09:54:39.895  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 09:54:39.895  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 09:54:39.895  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-05 09:54:39.897  1037  1377 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 09:54:39.897  1037  1377 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 09:54:39.899  1037  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 09:54:39.899  1037  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 09:54:39.899  1037  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 09:54:39.900  1037  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 09:54:39.900  1037  1377 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 09:54:39.900  1037  1377 E WifiHW  : unknown target_country: EU , set to default
08-05 09:54:39.900  1037  1377 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 09:54:39.900  1037  1377 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 09:54:39.900  1037  1377 I WifiUtil: gEnableBmps=1
08-05 09:54:39.913  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:39.920  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-05 09:54:39.931  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 09:54:39.935  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:39.936  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:39.941  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-05 09:54:39.951  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 09:54:39.956  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:39.956  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:39.959  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 09:54:39.962  6433  6821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 09:54:39.968  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 09:54:39.981  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 09:54:40.001  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:40.031  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:40.080  1037  1972 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7008 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-05 09:54:40.086  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:40.086  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 09:54:40.179  7008  7008 I AppUp4:AppBoxCP: onCreate
08-05 09:54:40.180  7008  7008 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-05 09:54:40.191  7008  7008 I AppUp4:DB:  setFingerPrint start
,08-05 09:54:40.192  7008  7008 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-05 09:54:40.201  7008  7008 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-05 09:54:40.201  7008  7008 I AppUp4:DB:  SDK version = 21
08-05 09:54:40.201  7008  7008 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-05 09:54:40.204  7008  7008 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-05 09:54:40.206  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 09:54:40.206  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:40.208  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 09:54:40.209  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 09:54:40.217  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 09:54:40.262  7008  7008 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 09:54:40.262  7008  7008 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 09:54:40.271  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c457b3e
08-05 09:54:40.271  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 09:54:40.271  7008  7008 D AppUp4:CustFacade: isPhone : true
08-05 09:54:40.272  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-05 09:54:40.273  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-05 09:54:40.273  7008  7008 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-05 09:54:40.274  7008  7027 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-05 09:54:40.274  7008  7027 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-05 09:54:40.274  7008  7027 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-05 09:54:40.279  1037  1941 I ActivityManager: Killing 6077:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-05 09:54:40.329  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:40.330  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 09:54:40.331  1037  2016 W libprocessgroup: failed to open /acct/uid_10027/pid_6077/cgroup.procs: No such file or directory
08-05 09:54:40.333  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:40.340  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:40.347  4310  7033 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 09:54:40.354  4310  7034 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:40.354  4310  7034 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 09:54:40.398  1037  1560 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7035 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 09:54:40.493  7035  7035 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:54:40.494  7035  7035 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 09:54:40.496  7035  7035 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 09:54:40.496  7035  7035 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 09:54:40.591  7035  7035 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 09:54:40.623  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 09:54:40.624  1037  1119 D Tethering: InitialState.processMessage what=4
08-05 09:54:40.628  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 09:54:40.631   318   895 D SoftapController: Softap fwReload - Ok
08-05 09:54:40.633  1037  1377 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (729ms)
,08-05 09:54:40.640   318   895 D CommandListener: Setting iface cfg
08-05 09:54:40.640   318   895 D CommandListener: Trying to bring down wlan0
08-05 09:54:40.641   318   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 09:54:40.642  7035  7035 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 09:54:40.643  1037  1377 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-05 09:54:40.640  7060  7060 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:40.640  7060  7060 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 09:54:40.671  7060  7060 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 09:54:40.691  7035  7035 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 09:54:40.707  7060  7060 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 09:54:40.707  7060  7060 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-05 09:54:40.732  7035  7035 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 09:54:40.732  7035  7035 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 09:54:40.744  1037  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 09:54:40.744  1037  1377 E WifiStateMachine: useWiFiOffloading() : false
08-05 09:54:40.744  1037  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 09:54:40.744  1037  1377 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 09:54:40.744  1037  1377 D WifiMonitor: connecting to supplicant
08-05 09:54:40.745  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 09:54:40.746  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-05 09:54:40.747  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 09:54:40.750  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:40.751  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:40.776  7060  7060 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 09:54:40.817  7060  7060 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-05 09:54:40.821  7060  7060 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-05 09:54:40.822  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 09:54:40.823  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 09:54:40.823  1037  7069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-05 09:54:40.823  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 09:54:40.823  1037  7069 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 09:54:40.823  1037  1377 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-05 09:54:40.824  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:40.824  1037  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:40.824  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:40.825  1037  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:40.825  1037  1377 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 09:54:40.825  1037  1377 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 09:54:40.826  1037  1377 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 09:54:40.826  1037  1377 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 09:54:40.826  1037  1377 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 09:54:40.827  1037  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 09:54:40.827  1037  1377 E WifiStateMachine: useWiFiOffloading() : false
08-05 09:54:40.827  1037  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 09:54:40.827  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:40.827  7060  7060 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 09:54:40.827  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:40.828  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 09:54:40.828  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:40.828  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:40.828  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 09:54:40.828  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 09:54:40.828  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 09:54:40.828  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 09:54:40.828  1037  7069 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 09:54:40.828  1037  7069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 09:54:40.830  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-05 09:54:40.830  1037  1377 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 09:54:40.830  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:40.830  1037  1377 D WifiNative-wlan0: SET update_config 1: returned true
08-05 09:54:40.830  1037  1377 D WifiConfigStore: Loading config and enabling all networks 
08-05 09:54:40.830  1037  1377 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 09:54:40.831  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:40.831  1037  1377 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-05 09:54:40.831  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:40.831  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:40.831  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:40.831  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:40.831  6709  6709 V io.jxcore.nod,e.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:40.831  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:40.831  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:40.831  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 09:54:40.831  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 09:54:40.831  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:40.831  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:40.831  1037  1384 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 09:54:40.832  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:40.832  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:40.832  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:40.832  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:40.832  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:40.832  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:40.832  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:40.832  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:40.832  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 09:54:40.832  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:40.832  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:40.835  1037  1377 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-05 09:54:40.842  1037  1377 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk,
08-05 09:54:40.842  1037  1377 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 09:54:40.844  1037  1377 D WifiStateMachine: enableVerboseLogging : level 2
08-05 09:54:40.844  1037  1377 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-05 09:54:40.844  1037  1377 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 09:54:40.844  1037  1377 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 09:54:40.845  1037  1377 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 09:54:40.845  1037  1377 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 09:54:40.845  1037  1377 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 09:54:40.845  1037  1377 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 09:54:40.845  1037  1377 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 09:54:40.845  1037  1377 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 09:54:40.845  1037  1377 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 09:54:40.845  1037  1377 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-05 09:54:40.846  1037  1377 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 09:54:40.846  1037  1377 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 09:54:40.846  1037  1377 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 09:54:40.847  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-05 09:54:40.847  1037  1377 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 09:54:40.847  1037  1377 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 09:54:40.847  1925  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 09:54:40.847  1925  2321 D WfdsService: Set the WFDS Monitor: true
08-05 09:54:40.847  1925  2321 D WfdsMonitor: WfdsMonitorThread create
,08-05 09:54:40.847  1925  2321 D WfdsMonitor: WFDS Monitor is created and started
08-05 09:54:40.847  1925  2321 D WfdsService: WiFi: Supplicant connection re-established
08-05 09:54:40.847  1037  1377 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 09:54:40.847  1037  1377 D WifiNative-HAL: Setting external_sim to 1
08-05 09:54:40.847  1037  1377 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 09:54:40.847  1037  1377 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 09:54:40.847  1037  1377 I WifiNative-HAL: startHal
08-05 09:54:40.848  1037  1377 D wifi    : setting scan oui 0xaf68f140
08-05 09:54:40.848  1037  1377 D WifiStateMachine: Setting OUI to DA-A1-19
,08-05 09:54:40.848  1037  1377 I WifiNative-HAL: startHal
08-05 09:54:40.848  1037  1377 D wifi    : setting scan oui 0xaf68f140
08-05 09:54:40.848  1037  1377 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 09:54:40.849  1037  1377 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 09:54:40.849  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 09:54:40.849  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 09:54:40.849  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 09:54:40.849  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-05 09:54:40.849  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 09:54:40.849  1925  7070 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 09:54:40.850  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 09:54:40.850  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 09:54:40.850  1925  7070 E CtrlSupplicant: Succeed to open control connection
08-05 09:54:40.850  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 09:54:40.850  1925  7070 E CtrlSupplicant: Succeed to open monitor connection
08-05 09:54:40.850  1925  7070 D WfdsMonitor: Supplicant connection established
08-05 09:54:40.850  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
,08-05 09:54:40.850  1925  2321 D WfdsService: Connected to the supplicant for wfds
08-05 09:54:40.850  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 09:54:40.850  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 09:54:40.851  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 09:54:40.851  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 09:54:40.851  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 09:54:40.851  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 09:54:40.851  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
,08-05 09:54:40.851  7060  7060 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 09:54:40.851  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 09:54:40.851  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 09:54:40.851  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 09:54:40.852  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 09:54:40.852  1037  1377 E WifiNative: : [330,823,565 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 09:54:40.852  1037  1377 D WifiNative-wlan0: doBoolean: RECONNECT,
08-05 09:54:40.853  1037  1377 D WifiNative-wlan0: RECONNECT: returned true,
,08-05 09:54:40.853  1037  1377 D WifiNative-wlan0: doString: [STATUS]
08-05 09:54:40.853  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 09:54:40.853  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 09:54:40.853  1037  1377 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 09:54:40.853  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 09:54:40.854  1037  1377 D WifiNative-wlan0: SET ps 1: returned true
08-05 09:54:40.854  1037  1376 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.855   318   895 D CommandListener: Setting iface cfg
08-05 09:54:40.855   318   895 D CommandListener: Trying to bring up p2p0
,08-05 09:54:40.856  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 09:54:40.856  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-05 09:54:40.856  1037  1376 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 09:54:40.856  1037  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.856  1037  1376 D LGWifiP2pService: P2pEnablingState
08-05 09:54:40.856  1037  1541 I WifiNative-HAL: startHal
,08-05 09:54:40.856  1037  1376 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 09:54:40.856  1037  1376 D LGWifiP2pService: P2p socket connection successful
08-05 09:54:40.856  1037  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf68f140
08-05 09:54:40.856  1037  1376 D LGWifiP2pService: P2pEnabledState
08-05 09:54:40.856  1037  1541 D wifi    : failed to get capabilities : -3
08-05 09:54:40.856  1037  1541 E WifiScanningService: could not get scan capabilities
08-05 09:54:40.856  1037  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.856  1037  1376 D LGWifiP2pService: sending p2p connection changed broadcast
,08-05 09:54:40.858  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 09:54:40.858  1925  1925 D WfdsService: WifiP2pState is changed : true
08-05 09:54:40.858  1925  2321 D WfdsService: Receive the WFDS_ENABLE Method
08-05 09:54:40.858  1925  2321 D WfdsService: Set the WFDS Monitor: true
08-05 09:54:40.858  1925  2321 D WfdsService: Connected to the supplicant for wfds
08-05 09:54:40.858  1925  2321 D WfdsJNI : doCommand: WFDS_SET TRUE
,08-05 09:54:40.858  7060  7060 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 09:54:40.858  1925  2321 D WfdsService: selectPreferredScanChannel [36]
08-05 09:54:40.858  1925  2321 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 09:54:40.859  1037  1376 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 09:54:40.860  1037  1377 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 09:54:40.860  1037  1377 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 09:54:40.860  1037  1376 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 09:54:40.860  1037  1377 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 09:54:40.861  1037  1377 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,08-05 09:54:40.861  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 09:54:40.861  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=330832  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 09:54:40.861  1925  1925 D WfdsService: isConnected: false
08-05 09:54:40.861  1037  1376 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 09:54:40.861  1037  1376 D WifiNative-p2p0: SET device_name G3: returned true
08-05 09:54:40.861  1037  1376 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 09:54:40.861  1037  1376 D LGWifiP2pService: before postfix = G3
,08-05 09:54:40.861  1037  1376 D WifiServerServiceExt: postfix byte check : 2
08-05 09:54:40.862  1037  1376 D LGWifiP2pService: after postfix = G3
08-05 09:54:40.862  1037  1376 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 09:54:40.862  1037  1376 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 09:54:40.862  1037  1376 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 09:54:40.862  1037  1376 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 09:54:40.862  1037  1376 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,08-05 09:54:40.863  1037  1376 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 09:54:40.863  1037  1376 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 09:54:40.863  1037  1376 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 09:54:40.863  1037  1376 D WifiNative-HAL: p2pGetDeviceAddress
08-05 09:54:40.863  1037  1376 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 09:54:40.864  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:40.864  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 09:54:40.864  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:40.864  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:40.864  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 09:54:40.865  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:40.865  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=330836  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-05 09:54:40.865  1037  1376 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 09:54:40.865  1037  1376 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 09:54:40.866  1037  1376 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 09:54:40.866  1037  1376 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 09:54:40.866  1037  1376 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 09:54:40.866  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 09:54:40.866  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,08-05 09:54:40.866  1037  1376 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 09:54:40.866  1925  1925 D WfdsService: Update P2p Interface State: 3
08-05 09:54:40.866  1037  1376 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 09:54:40.866  1037  1376 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 09:54:40.867  1037  1377 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 09:54:40.867  1037  1377 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 09:54:40.867  1037  1377 E WifiStateMachine:  DriverStartedState what:132106 1 0
,08-05 09:54:40.867  1037  1377 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-05 09:54:40.870  7035  7035 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69),
08-05 09:54:40.874  7060  7060 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 09:54:40.874  1037  1376 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 09:54:40.874  1037  1376 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 09:54:40.874  1037  1376 D LGWifiP2pService: InactiveState
,08-05 09:54:40.874  1037  1376 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.874  1037  1377 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 09:54:40.874  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.874  1037  1376 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 09:54:40.875  1037  1377 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 09:54:40.875  1037  1377 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,08-05 09:54:40.875  1037  1377 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 09:54:40.876  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 09:54:40.876  7060  7060 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:40.877  1925  7070 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 09:54:40.877  1037  7069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-05 09:54:40.877  1037  7069 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:40.877  1037  7069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:40.877  1037  7069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:40.877  7060  7060 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 09:54:40.877  7060  7060 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 09:54:40.877  7060  7060 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.877  1925  7070 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-05 09:54:40.877  1037  7069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:40.877  1037  7069 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.878  1037  1377 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 09:54:40.878  1037  7069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.878  1037  7069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.878  1037  1377 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz,
08-05 09:54:40.878  7060  7060 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.878  1037  1377 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 09:54:40.878  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 09:54:40.878  1925  7070 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:40.878  1037  7069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:40.878  1037  7069 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.878  1037  7069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.878  1037  7069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-05 09:54:40.879  1037  1376 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,08-05 09:54:40.879  1037  1376 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.879  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.880  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 09:54:40.880  7060  7060 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:40.880  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 09:54:40.880  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:40.880  1037  7069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:40.880  1037  7069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:40.880  1037  1376 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.880  7060  7060 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 09:54:40.881  7060  7060 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.881  1037  1376 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.881  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.881  1037  7069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:40.881  1037  1376 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.881  1037  7069 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.881  1037  7069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.881  1037  7069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.881  1037  1376 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.881  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.881  1037  1376 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.881  7060  7060 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.881  1037  1376 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.881  1037  7069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:40.881  1037  7069 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.881  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.881  1037  7069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.881  1037  1376 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.881  1037  7069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:40.881  1925  7070 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:40.881  1925  7070 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:40.882  1037  1377 D WifiNative-wlan0: D,RIVER COUNTRY CZ: returned true
08-05 09:54:40.882  1037  1377 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 09:54:40.882  1037  1377 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 09:54:40.882  1037  1377 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 09:54:40.882  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 09:54:40.882  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 09:54:40.883  7060  7060 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 09:54:40.883  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 09:54:40.883  1037  1037 E WifiServerServiceExt: No p2p device connected
08-05 09:54:40.883  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 09:54:40.883  1037  7069 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 09:54:40.883  1037  7069 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 09:54:40.883  1037  1376 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.883  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:40.883  1037  1377 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 09:54:40.883  1037  1377 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 09:54:40.884  1037  1377 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 09:54:40.884  1037  1377 D WifiNative-wlan0: doBoolean: SCAN
08-05 09:54:40.884  1037  1377 D WifiNative-wlan0: SCAN: returned false
08-05 09:54:40.884  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=330856  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 09:54:40.885  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=330856  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 09:54:40.885  1037  1377 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 09:54:40.886  1037  1377 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 09:54:40.886  1037  1377 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 09:54:40.886  1925  2321 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 09:54:40.886  1037  1377 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-05 09:54:40.886  1037  1377 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 09:54:40.887  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:40.887  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:40.887  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 09:54:40.888  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:40.888  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 09:54:40.887  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:40.888  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:40.889  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 09:54:40.898  3493  3493 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 09:54:40.898  3493  3493 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:40.898  3493  3493 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-05 09:54:40.901  7035  7035 I HubEmail: JNI_OnLoad()
08-05 09:54:40.901  7035  7035 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 09:54:40.901  7035  7035 I HubEmail: registerNatives()
08-05 09:54:40.901  7035  7035 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 09:54:40.901  7035  7035 I HubEmail: registerNativeMethods()
08-05 09:54:40.901  7035  7035 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 09:54:40.902  7035  7035 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-05 09:54:40.924  1037  1972 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7077 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-05 09:54:40.926  6910  7074 W FormManager: Network not available. Please check & try again.
08-05 09:54:40.927  6910  7075 V FormManager: Network unavailable.
08-05 09:54:40.928  7035  7076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:40.930  6910  7075 V FormManager: Network unavailable.
08-05 09:54:40.934  1037  1708 I ActivityManager: Killing 6150:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-05 09:54:40.966  1037  1956 W libprocessgroup: failed to open /acct/uid_10080/pid_6150/cgroup.procs: No such file or directory
,08-05 09:54:41.050  7077  7077 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:54:41.051  7077  7077 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 09:54:41.054  7077  7077 D PhoneMonitor: Register our PhoneStateListener
,08-05 09:54:41.076  7077  7077 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 09:54:41.081  7077  7077 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-05 09:54:41.114  7077  7077 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-05 09:54:41.116  7077  7077 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 09:54:41.116  7077  7077 D TelephonyAutoProfiling: [parse] Load xml
08-05 09:54:41.119  7077  7077 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
,08-05 09:54:41.119  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 09:54:41.120  7077  7077 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
,08-05 09:54:41.120  7077  7077 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-05 09:54:41.126  7077  7077 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-05 09:54:41.163  1037  2016 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7096 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 09:54:41.164  1037  2016 I ActivityManager: Killing 6560:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-05 09:54:41.216  1037  1906 W libprocessgroup: failed to open /acct/uid_10061/pid_6560/cgroup.procs: No such file or directory
,08-05 09:54:41.497  1037  1906 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7117 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-05 09:54:41.499  1037  1906 I ActivityManager: Killing 6181:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-05 09:54:41.547  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 09:54:41.547  1037  7069 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 09:54:41.547  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 09:54:41.547  7060  7060 E wpa_supplicant: USIM:  scard_init function
08-05 09:54:41.547  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-05 09:54:41.547  1037  7069 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 09:54:41.548  7060  7060 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-05 09:54:41.550  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 09:54:41.550  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 09:54:41.552  1037  1377 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 09:54:41.553  1037  1377 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 09:54:41.553  1037  1377 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 09:54:41.553  1037  1377 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-05 09:54:41.553  1037  1377 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 09:54:41.586  1037  1972 W libprocessgroup: failed to open /acct/uid_10097/pid_6181/cgroup.procs: No such file or directory
,08-05 09:54:41.597  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=331568  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 09:54:41.604  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=331575  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 09:54:41.614  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:41.614  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:41.618  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.618  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.618  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.618  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-05 09:54:41.618  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:41.618  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 09:54:41.659  7060  7060 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 09:54:41.662  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 09:54:41.662  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 09:54:41.662  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 09:54:41.663  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 09:54:41.663  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 09:54:41.663  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:41.664  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=331635  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 09:54:41.664  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=331636  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 09:54:41.666  1037  1377 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=331638
08-05 09:54:41.667  1037  1377 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=331638
08-05 09:54:41.667  1037  1377 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=331639
08-05 09:54:41.668  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=331639
08-05 09:54:41.668  1037  1377 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=331640
08-05 09:54:41.669  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 09:54:41.669  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=331640  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 09:54:41.671  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 09:54:41.671  7060  7060 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 09:54:41.671  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:41.671  7060  7060 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 09:54:41.671  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 09:54:41.671  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 09:54:41.672  1037  7069 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 09:54:41.672  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 09:54:41.672  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 09:54:41.672  1037  7069 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 09:54:41.672  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-05 09:54:41.672  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:41.674  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=331645  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-05 09:54:41.678  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.678  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.678  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 09:54:41.680  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:41.680  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:41.682  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.684  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:41.684  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:41.685  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.686  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.686  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.686  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 09:54:41.686  1037  1377 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:41.687  1037  1377 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:41.687  1037  1377 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:41.687  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:41.688  1037  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:41.688  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=331660  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 09:54:41.689  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=331660  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 09:54:41.689  1037  1377 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=331661
08-05 09:54:41.690  1037  1377 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=331661
08-05 09:54:41.690  1037  1377 D WifiNative-wlan0: doString: [STATUS]
08-05 09:54:41.691  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 09:54:41.691  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:41.691  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:41.691  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-05 09:54:41.695  1037  1377 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 09:54:41.697  1037  1377 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 09:54:41.741  1037  1052 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7147 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 09:54:41.743  1037  1052 I ActivityManager: Killing 6596:com.lge.eula/1000 (adj 15): empty #17
08-05 09:54:41.786  1037  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_6596/cgroup.procs: No such file or directory
,08-05 09:54:41.788  1037  1377 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-05 09:54:41.788  1037  1377 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-05 09:54:41.797  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.797  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.797  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 09:54:41.797  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:41.798  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:41.799  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.805  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.805  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.805  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 09:54:41.807  1037  1377 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 09:54:41.807  1037  1428 D ConnectivityService: Got NetworkAgent Messenger
08-05 09:54:41.807  1037  1428 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 09:54:41.807  1037  1428 D ConnectivityService: NetworkAgent connected
08-05 09:54:41.807  1037  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 09:54:41.807  1037  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 09:54:41.808  1037  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 09:54:41.808  1037  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-05 09:54:41.815  1037  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 09:54:41.815  1037  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 09:54:41.815  1037  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 09:54:41.816  1037  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 09:54:41.816  1037  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 09:54:41.819  1037  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 09:54:41.823   318   895 D CommandListener: Setting iface cfg
,08-05 09:54:41.826  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:41.826  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:41.827  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.827  1037  1377 E WifiStateMachine: Start Dhcp Watchdog 2
08-05 09:54:41.828  1037  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=331799  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:41.828  1037  7166 D DhcpStateMachine: StoppedState
08-05 09:54:41.828  1037  7166 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.828  1037  7166 D DhcpStateMachine: WaitBeforeStartState
08-05 09:54:41.828  1037  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=331799  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:41.829  7147  7147 I art     : Almond Protected OAT
08-05 09:54:41.830  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=331801  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:41.831  1037  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=331802  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:41.831  1037  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=331803  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:41.832  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=331803  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:41.833  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:285572] from screen [on:0 period:1504866601] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 09:54:41.834  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1504866602] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 09:54:41.834  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 09:54:41.841  1037  1428 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-05 09:54:41.841  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.842  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.842  1037  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.843  1037  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.843  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.843  1037  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.844  1037  1428 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 09:54:41.845  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=123,0,0
08-05 09:54:41.845  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=123,0,0
08-05 09:54:41.845  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 09:54:41.846  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 09:54:41.848  1037  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 09:54:41.848  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 09:54:41.849  1037  1377 D WifiNative-wlan0: SET ps 0: returned true
08-05 09:54:41.849  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 09:54:41.849  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 09:54:41.849  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:41.849  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-05 09:54:41.850  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 09:54:41.852  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 09:54:41.852  1037  1377 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 09:54:41.852  1037  1377 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-05 09:54:41.852  1037  1376 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3175427c target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.852  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3175427c target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.852  1037  1377 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 09:54:41.852  1037  7166 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.852  1037  7166 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 09:54:41.853   318   895 D CommandListener: Setting iface cfg
08-05 09:54:41.854   318   895 D CommandListener: Trying to bring up wlan0
08-05 09:54:41.855  1037  1377 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 09:54:41.856  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:41.856  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 09:54:41.857  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:41.857  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 09:54:41.858  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.858  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.858  1037  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.859  1037  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.859  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.859  1037  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:41.860  1037  1428 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 09:54:41.860  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 09:54:41.860  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 09:54:41.860  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 09:54:41.860  1037  1376 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.860  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.861  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 09:54:41.861  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 09:54:41.861  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 09:54:41.861  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 09:54:41.861  1037  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 09:54:41.861  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 1
,08-05 09:54:41.869  1037  1376 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.869  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 09:54:41.869  1037  1376 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.878  1037  1377 D WifiNative-wlan0: SET ps 1: returned true
08-05 09:54:41.879  1037  1428 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-05 09:54:41.879  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 09:54:41.880  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 09:54:41.880  1037  1377 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 09:54:41.880  1037  1428 D ConnectivityService: ignoring duplicate network state non-change
08-05 09:54:41.883  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:41.883  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:41.884  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.884  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.884  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 09:54:41.884  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.886  1037  1428 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 09:54:41.887  1037  1428 D ConnectivityService: Adding iface wlan0 to network 101
08-05 09:54:41.888  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.888  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.888  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 09:54:41.890  7147  7147 D WeatherApplication: removeAccount
08-05 09:54:41.890  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 09:54:41.892  7147  7147 D WeatherApplication: Account.length = 0
08-05 09:54:41.892  7147  7147 E WeatherApplication: OPERATOR:OPEN
08-05 09:54:41.893  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 09:54:41.893  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.893  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:54:41.893  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 09:54:41.894  1037  1377 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 09:54:41.896  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 09:54:41.897  7147  7147 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:41
08-05 09:54:41.900  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.901  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:41.901  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 09:54:41.903  7147  7147 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 09:54:41.903  7147  7147 D Weather.Utils: 2 : All the weather widget is gone.
08-05 09:54:41.904  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:41.904  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:41.906  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.908  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:41.908  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 09:54:41.908  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 09:54:41.912  1037  1377 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 09:54:41.912  1037  1428 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 09:54:41.912  1037  1428 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-05 09:54:41.912  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 09:54:41.913  1037  1377 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 09:54:41.913  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:41.914  1037  1377 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 09:54:41.914  1037  1428 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-05 09:54:41.914  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 09:54:41.915  1037  1377 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 09:54:41.915  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 09:54:41.915   318   895 E Netd    : netlink response contains error (File exists)
08-05 09:54:41.915  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.915  1037  1428 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-05 09:54:41.916  1037  1428 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 09:54:41.916  1037  1428 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-05 09:54:41.916  1037  1428 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-05 09:54:41.917  1037  1428 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 09:54:41.917  1037  1428 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 09:54:41.917  1037  1428 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-05 09:54:41.917  1037  1428 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 09:54:41.917  1037  1428 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:41.917  1037  1428 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:41.917  1037  1428 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 09:54:41.918  1037  1428 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:41.918  1037  1428 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 09:54:41.918  1037  1428 D ConnectivityService: currentScore = 0, newScore = 20
08-05 09:54:41.918  1037  1428 D ConnectivityService:    accepting network in place of null
08-05 09:54:41.918  1037  1428 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:41.918  1037  7165 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.918  1037  7165 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 09:54:41.918  1037  7165 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:41.918  1037  716,5 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 09:54:41.919  1037  1377 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:41.919  1037  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:41.920  1037  1428 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 09:54:41.920  1037  1428 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 09:54:41.920  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 09:54:41.923  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:41.923  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-05 09:54:41.924  1037  1428 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:41.924  1037  1428 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 09:54:41.925  1037  1428 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 09:54:41.926  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 09:54:41.926  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 09:54:41.926  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 09:54:41.926  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 09:54:41.926  1037  1428 D ConnectivityService: validation of new default Network = false
08-05 09:54:41.926  1037  1428 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 09:54:41.926  1037  1428 D DSQN    : enableDataServiceNotify 
08-05 09:54:41.926  1037  1428 D DSQN    : start dsqn bin
08-05 09:54:41.927   318  7171 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 09:54:41.928  7147  7147 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 09:54:41.931  7147  7147 D WeatherAncestor: connectivity changed - connection : true
08-05 09:54:41.932  7147  7147 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-05 09:54:41.933  1037  1428 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 09:54:41.933  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:41.933  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:41.920  7172  7172 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:41.934  1037  1428 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:41.920  7172  7172 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:41.934  1588  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-05 09:54:41.945  1037  1375 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-05 09:54:41.946  7172  7172 E DSQN    : DSQN ssw
,08-05 09:54:41.962  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-05 09:54:41.963  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.963  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:41.964  7147  7147 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 09:54:41.964  7147  7147 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 09:54:41.964  7147  7147 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-05 09:54:41.976  1801  7177 I CheckinService: active receiver: enabled
,08-05 09:54:41.979   318  7171 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 09:54:41.995  7147  7147 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 09:54:41.995  7147  7147 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:41
,08-05 09:54:41.997  1801  7177 I CheckinService: Preparing to send checkin request
,08-05 09:54:41.997  1801  7177 I EventLogService: Accumulating logs since 1470383409426
08-05 09:54:42.012   318  7171 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-05 09:54:42.035  1037  1956 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7179 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 09:54:42.036  1037  1956 I ActivityManager: Killing 6613:com.lge.bnr/1000 (adj 15): empty #17
,08-05 09:54:42.051   380   380 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 302us total 13.557ms
,08-05 09:54:42.054  1037  7166 D DhcpStateMachine: DHCPV4 request on wlan0
08-05 09:54:42.055  1037  7166 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 09:54:42.055  1037  7166 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 09:54:42.050  7196  7196 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:42.050  7196  7196 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:42.064   380   380 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 12.418ms
,08-05 09:54:42.067   318   894 D LGDataListener: argv[0]=dsqncommand
08-05 09:54:42.067   318   894 D LGDataListener: argv[1]=wlan0
08-05 09:54:42.067   318   894 D LGDataListener: argv[2]=1
08-05 09:54:42.067   318   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 09:54:42.067  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 09:54:42.067  1037  1117 D DSQN    : start to monitor internet connection
08-05 09:54:42.067  7196  7196 I dhcpcd  : version 5.5.6 starting
08-05 09:54:42.069  7196  7196 E dhcpcd  : get_duid: m
08-05 09:54:42.069  7196  7196 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 09:54:42.069  7196  7196 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-05 09:54:42.079   380   380 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 227us total 12.151ms
,08-05 09:54:42.117  1801  7177 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-05 09:54:42.117  1037  1871 W libprocessgroup: failed to open /acct/uid_1000/pid_6613/cgroup.procs: No such file or directory
08-05 09:54:42.118  7196  7196 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 09:54:42.118  7196  7196 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 09:54:42.118  7196  7196 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 09:54:42.118  7196  7196 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 09:54:42.118  7196  7196 D dhcpcd  : wlan0: sending REQUEST (xid 0x31ac0f00), next in 4.55 seconds
08-05 09:54:42.120  1037  7165 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 07:54:42 GMT], X-Android-Received-Millis=[1470383682119], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470383682065]}
08-05 09:54:42.120  1037  7165 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 09:54:42.120  1037  7165 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 09:54:42.120  1037  1428 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-05 09:54:42.120  1037  1428 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 09:54:42.120  1037  1428 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:42.120  1037  1428 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:42.120  1037  1428 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 09:54:42.120  1037  1428 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 09:54:42.120  1037  1428 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 09:54:42.120  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:42.120  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:42.121  1037  1428 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:42.121  1037  1428 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:42.121  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 09:54:42.121  1037  1377 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:42.121  1037  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:42.121  1588  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 09:54:42.122  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:42.122  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-05 09:54:42.137  7196  7196 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-05 09:54:42.146  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 09:54:42.147  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:42.147  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 09:54:42.155  7196  7196 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 09:54:42.155  7196  7196 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 09:54:42.155  7196  7196 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 09:54:42.155  7196  7196 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 09:54:42.155  7196  7196 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 09:54:42.155  7196  7196 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 09:54:42.155  7196  7196 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 09:54:42.155  7196  7196 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 09:54:42.238   279   412 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 09:54:42.238   279   412 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 09:54:42.238   279   412 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 09:54:42.239  7179  7213 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 09:54:42.240  1037  1708 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7214 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-05 09:54:42.243   279   412 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 09:54:42.243   279   412 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 09:54:42.243   279   412 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 09:54:42.245  7179  7213 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 09:54:42.253   279   412 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 09:54:42.253   279   412 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 09:54:42.253   279   412 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 09:54:42.256  7179  7227 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 09:54:42.258   279   412 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 09:54:42.258   279   412 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 09:54:42.258   279   412 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 09:54:42.265  7179  7227 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-05 09:54:42.294  7214  7214 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-05 09:54:42.295  7214  7214 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-05 09:54:42.317  7214  7214 I MultiDex: VM with version 2.1.0 has multidex support
08-05 09:54:42.317  7214  7214 I MultiDex: install
08-05 09:54:42.317  7214  7214 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-05 09:54:42.324  7214  7214 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-05 09:54:42.458  1037  7166 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-05 09:54:42.459  1037  7166 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 09:54:42.459  1037  7166 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 09:54:42.460  1037  7166 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 09:54:42.460  1037  7166 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-05 09:54:42.460  1037  7166 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 09:54:42.460  1037  7166 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 09:54:42.460  1037  7166 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 09:54:42.460  1037  7166 D DhcpStateMachine: RunningState
,08-05 09:54:42.490  7179  7179 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 09:54:42.499  7179  7179 I LibraryLoader: Loading: webviewchromium
08-05 09:54:42.502  7179  7179 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2483-2487)
08-05 09:54:42.502  7179  7179 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 09:54:42.508  7179  7179 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e777ca1}
08-05 09:54:42.509  7179  7179 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 09:54:42.510  7179  7179 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 09:54:42.520  7179  7179 I BrowserStartupController: Initializing chromium process, renderers=0
08-05 09:54:42.521  7179  7179 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 09:54:42.540   322  1388 V AudioPolicyService: registerClient() client 0xb14b78c0, uid 10093
08-05 09:54:42.540  7179  7269 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-05 09:54:42.546  7179  7179 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 09:54:42.546  7179  7179 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 09:54:42.547  7179  7179 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-05 09:54:42.551  7265  7265 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-05 09:54:42.591  7179  7179 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 09:54:42.591  7179  7179 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 09:54:42.591  7179  7179 I Adreno-EGL: Build Date: 12/12/14 금
08-05 09:54:42.591  7179  7179 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 09:54:42.591  7179  7179 I Adreno-EGL: Remote Branch: 
08-05 09:54:42.591  7179  7179 I Adreno-EGL: Local Patches: 
,08-05 09:54:42.591  7179  7179 I Adreno-EGL: Reconstruct Branch: 
,08-05 09:54:42.625  7265  7265 I dex2oat : dex2oat took 74.007ms (threads: 4)
,08-05 09:54:42.639  7179  7179 I NSApplication: Starting up...
,08-05 09:54:42.656  7214  7236 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 09:54:42.656  7214  7236 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 09:54:42.656  7214  7236 I Adreno-EGL: Build Date: 12/12/14 금
08-05 09:54:42.656  7214  7236 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 09:54:42.656  7214  7236 I Adreno-EGL: Remote Branch: 
08-05 09:54:42.656  7214  7236 I Adreno-EGL: Local Patches: 
08-05 09:54:42.656  7214  7236 I Adreno-EGL: Reconstruct Branch: 
,08-05 09:54:42.684  1037  2015 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7287 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-05 09:54:42.685  1037  2015 I ActivityManager: Killing 6102:com.android.vending/u0a44 (adj 15): empty #17
08-05 09:54:42.759  7214  7236 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 09:54:42.759  7214  7236 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 09:54:42.759  7214  7236 I Adreno-EGL: Build Date: 12/12/14 금
08-05 09:54:42.759  7214  7236 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 09:54:42.759  7214  7236 I Adreno-EGL: Remote Branch: 
08-05 09:54:42.759  7214  7236 I Adreno-EGL: Local Patches: 
08-05 09:54:42.759  7214  7236 I Adreno-EGL: Reconstruct Branch: 
,08-05 09:54:42.928  1037  1906 W libprocessgroup: failed to open /acct/uid_10044/pid_6102/cgroup.procs: No such file or directory
,08-05 09:54:42.935  1037  1428 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-05 09:54:42.940  1037  1871 D WifiServiceImplEx: setWifiEnabled: false pid=6709, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 09:54:42.940  1037  1871 D WifiService: setWifiEnabled: false pid=6709, uid=10118
08-05 09:54:42.940  1037  1871 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 09:54:42.950  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 09:54:42.950  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 09:54:42.950  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-05 09:54:42.951  1037  1377 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 09:54:42.952  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 09:54:42.954  1037  1377 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 09:54:42.955  1037  1377 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 09:54:42.956  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 09:54:42.956  1037  1377 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 09:54:42.956  1037  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 09:54:42.956  1037  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 09:54:42.956  7287  7287 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:54:42.956  1037  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 09:54:42.956  1037  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 09:54:42.962  1037  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 09:54:42.962  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 09:54:42.962  1037  1376 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:42.962  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:42.962  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 09:54:42.963  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 09:54:42.963  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 09:54:42.963  1037  1377 D WifiNative-wlan0: SET ps 1: returned true
08-05 09:54:42.963  1037  7166 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 09:54:42.970   318   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 09:54:42.996  1037  1428 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 09:54:42.996  1037  1428 D ConnectivityService: ignoring duplicate network state non-change
08-05 09:54:42.996  1037  1428 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-05 09:54:42.997  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:42.997  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:42.998  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-05 09:54:42.998  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:42.999  1037  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:42.999  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:42.999  1037  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:43.000  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-05 09:54:43.000  1037  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:43.000  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:43.000  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:43.000  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:43.000  1037  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:43.001  1037  1377 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 09:54:43.001  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 09:54:43.002  1037  1376 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:43.002  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:43.002  1037  1376 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1b373a0c
08-05 09:54:43.002  1037  1376 D LGWifiP2pService: P2pDisablingState
08-05 09:54:43.002  1037  1376 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:43.002  1037  1376 D LGWifiP2pService: p2p socket connection lost
08-05 09:54:43.002  1037  1376 D LGWifiP2pService: P2pDisabledState
08-05 09:54:43.003  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-05 09:54:43.005  1037  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 09:54:43.005  1037  1376 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:43.005  1037  1376 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 09:54:43.006  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 09:54:43.006  7060  7060 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 09:54:43.007  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:43.007  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:43.007  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 09:54:43.007  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 09:54:43.007  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-05 09:54:43.008  1037  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:43.008  1037  1542 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:43.009  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 09:54:43.009  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 09:54:43.009  1037  1377 D WifiNative-wlan0: SET ps 1: returned true
,08-05 09:54:43.013  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 09:54:43.014  1925  1925 D WfdsService: WifiP2pState is changed : false
08-05 09:54:43.014  1925  2321 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 09:54:43.014  1925  2321 D WfdsService: Set the WFDS Monitor: false
08-05 09:54:43.016  1925  2321 D WfdsMonitor: WFDS Monitor is stopped
08-05 09:54:43.016  1925  2321 D WfdsService: STATE : WfdsDisabledState - enter
08-05 09:54:43.016  1925  7070 D CtrlSupplicant: Received on exit socket, terminate
08-05 09:54:43.016  1925  7070 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 09:54:43.016  1925  7070 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 09:54:43.016  1925  7070 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 09:54:43.016  1925  2322 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 09:54:43.017  1925  2321 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 09:54:43.018  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:43.018  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:43.019  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 09:54:43.056  1037  1428 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 09:54:43.056   318   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 09:54:43.056  1037  1428 D DSQN    : disableDataServiceNotify
08-05 09:54:43.056  1037  1428 D DSQN    : stop dsqn bin
,08-05 09:54:43.057  1037  1377 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 09:54:43.058  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-05 09:54:43.058  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:43.058  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:54:43.058  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 09:54:43.059  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 09:54:43.059  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:43.059  1037  1377 D WifiNative-p2p0: TERMINATE: returned true
08-05 09:54:43.059  1037  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 09:54:43.059  1037  1377 E WifiStateMachine: useWiFiOffloading() : false
08-05 09:54:43.059  1037  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 09:54:43.059  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:43.061  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 09:54:43.061  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 09:54:43.061  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:43.061  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 09:54:43.061  1037  1428 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-05 09:54:43.061  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:43.062  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:43.062  1037  1428 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:43.062  1037  1428 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 09:54:43.062  1037  1428 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 09:54:43.062  1037  1428 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 09:54:43.062  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 09:54:43.063  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:43.063  7214  7236 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:54:43.063  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:43.063  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:43.063  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:43.063  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:43.063  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:43.063  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:43.063  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is, connected/connecting to active network: false
08-05 09:54:43.063  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:43.063  1037  1428 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:43.063  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:43.063  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:43.063  7214  7236 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 09:54:43.063  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 09:54:43.063  1037  1428 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:43.063  1037  1428 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:43.063  1037  1428 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:43.063  1037  1428 D NetworkManagementService: Removing idletimer
08-05 09:54:43.063  1037  1428 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:43.064  1588  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 09:54:43.064  1037  7165 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:43.064  1037  7165 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:43.064  1037  7165 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 09:54:43.064  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:43.064  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 09:54:43.064  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:43.064  1037  1377 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:43.064  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:43.064  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:43.064  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:43.064  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:43.064  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:43.064  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:43.064  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:43.064  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:43.064  1037  1377 D WIFI    :   my score=60, my filter=[ Transports,: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:43.064  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:43.064  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:43.065  1037  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 09:54:43.065  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 09:54:43.066  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 09:54:43.066  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 09:54:43.066  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 09:54:43.067  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 09:54:43.067  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 09:54:43.067  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 09:54:43.067  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 09:54:43.068  1037  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 09:54:43.079  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:43.093  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-05 09:54:43.094  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:43.095  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 09:54:43.106  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-05 09:54:43.107  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:43.107  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:43.146  1037  2015 I art     : Explicit concurrent mark sweep GC freed 118622(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.768ms total 103.089ms
,08-05 09:54:43.147  7214  7236 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 09:54:43.147  7214  7236 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 09:54:43.147  7214  7236 I Adreno-EGL: Build Date: 12/12/14 금
08-05 09:54:43.147  7214  7236 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 09:54:43.147  7214  7236 I Adreno-EGL: Remote Branch: 
08-05 09:54:43.147  7214  7236 I Adreno-EGL: Local Patches: 
08-05 09:54:43.147  7214  7236 I Adreno-EGL: Reconstruct Branch: 
08-05 09:54:43.168  7060  7060 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-05 09:54:43.168  7060  7060 I wpa_supplicant: monitor socket send errors count : 1
08-05 09:54:43.168  7060  7060 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-4\x00 that cannot receive messages
08-05 09:54:43.170  1037  7069 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 09:54:43.170  1037  7069 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 09:54:43.172  1037  7166 D DhcpStateMachine: StoppedState
08-05 09:54:43.172  1037  7166 D DhcpStateMachine: StoppedState{ when=-163ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:43.173  1037  1377 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 09:54:43.175  1037  1377 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-05 09:54:43.204  7060  7060 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-05 09:54:43.205  1037  1119 D Tethering: InitialState.processMessage what=4
,08-05 09:54:43.206  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 09:54:43.206  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 09:54:43.206  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 09:54:43.206  1037  7069 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 09:54:43.206  1037  7069 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 09:54:43.207  7060  7060 W wpa_supplicant: USIM:  scard_deinit function
08-05 09:54:43.207  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 09:54:43.207  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:43.207  1037  1377 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:43.208  1037  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:43.209  1037  1377 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=333180
08-05 09:54:43.209  1037  1377 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=333181
08-05 09:54:43.210  1037  1377 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=333181  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 09:54:43.210  1037  1377 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=333182  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 09:54:43.226   318  7316 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-05 09:54:43.227  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 09:54:43.228  1801  7177 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-05 09:54:43.238  1801  7177 I CheckinService: active receiver: disabled
,08-05 09:54:43.294  7060  7060 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 09:54:43.294  1037  7069 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 09:54:43.294  1037  7069 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 09:54:43.295  1037  7069 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-05 09:54:43.296  1037  1377 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-05 09:54:43.337  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 09:54:43.340  6433  6821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 09:54:43.372  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:43.388  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-05 09:54:43.388  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:43.389  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 09:54:43.389  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 09:54:43.391  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 09:54:43.395  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c457b3e
08-05 09:54:43.395  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 09:54:43.395  7008  7008 D AppUp4:CustFacade: isPhone : true
08-05 09:54:43.396  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-05 09:54:43.397  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 09:54:43.400  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:43.401  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 09:54:43.401  1037  1377 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 09:54:43.402  1037  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 09:54:43.402  1037  1377 E WifiStateMachine: useWiFiOffloading() : false
08-05 09:54:43.402  1037  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 09:54:43.402  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:43.403  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-05 09:54:43.403  1925  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 09:54:43.403  1925  2321 D WfdsService: Set the WFDS Monitor: false
08-05 09:54:43.403  1925  2321 D WfdsMonitor: WFDS Monitor is stopped
08-05 09:54:43.403  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-05 09:54:43.405  2487  2487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:54:43.407  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:43.407  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:43.407  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:43.407  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:43.407  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:43.407  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:43.407  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:43.407  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:43.407  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:43.407  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 09:54:43.408  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 09:54:43.408  1037  1384 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 09:54:43.408  1037  1384 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 09:54:43.409  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:43.410  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:43.410  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:43.410  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:43.410  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:43.410  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:43.410  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:43.410  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:43.410  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:43.410  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 09:54:43.418  4310  7326 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 09:54:43.422  4310  7327 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:43.423  4310  7327 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 09:54:43.423  7035  7035 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 09:54:43.444  7035  7328 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:54:43.452  6910  7330 W FormManager: Network not available. Please check & try again.
08-05 09:54:43.457  3493  3493 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 09:54:43.457  3493  3493 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:43.457  3493  3493 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 09:54:43.460  6910  7331 V FormManager: Network unavailable.
,08-05 09:54:43.464  7077  7077 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 09:54:43.464  7077  7077 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 09:54:43.469  6910  7331 V FormManager: Network unavailable.
08-05 09:54:43.477  7147  7147 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:43
08-05 09:54:43.480  7147  7147 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 09:54:43.480  7147  7147 D Weather.Utils: 2 : All the weather widget is gone.
,08-05 09:54:43.482  7147  7147 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 09:54:43.482  7147  7147 D WeatherAncestor: connectivity changed - connection : true
08-05 09:54:43.482  7147  7147 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31baeeec
08-05 09:54:43.483  7147  7147 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 09:54:43.483  7147  7147 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 09:54:43.483  7147  7147 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 09:54:43.483  7147  7147 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 09:54:43.483  7147  7147 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:43
08-05 09:54:43.507  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 09:54:43.507  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 09:54:43.507  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 09:54:43.508  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 09:54:43.508  6634  6982 D UEI.SmartControl: Internal timer expired: 2
08-05 09:54:43.508  6634  6982 D UEI.SmartControl: unbind internal service
08-05 09:54:43.508  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 09:54:43.509  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 09:54:43.509  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 09:54:43.509  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 09:54:43.509  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 09:54:43.509  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 09:54:43.509  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-05 09:54:43.517  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 09:54:43.521  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 09:54:43.525  6910  7334 W FormManager: Network not available. Please check & try again.
08-05 09:54:43.527  6910  7335 V FormManager: Network unavailable.
,08-05 09:54:43.530  6910  7335 V FormManager: Network unavailable.
08-05 09:54:43.534  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 09:54:43.549  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 09:54:43.551  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 09:54:43.557  6910  7337 W FormManager: Network not available. Please check & try again.
08-05 09:54:43.558  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:43.574  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-05 09:54:43.575  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 09:54:43.576  6910  7338 V FormManager: Network unavailable.
08-05 09:54:43.576  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:43.578  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:43.582  6910  7338 V FormManager: Network unavailable.
08-05 09:54:43.584  4310  7339 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 09:54:43.584  6634  6976 D serial_port: close(fd = 24)
08-05 09:54:43.589  4310  7340 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 09:54:43.590  4310  7340 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 09:54:43.590  6634  6976 I UEI.SmartControl: Serial port is closed.
,08-05 09:54:43.638  1037  2015 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7341 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 09:54:43.772  7341  7341 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 09:54:43.773  7341  7341 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-05 09:54:43.782  7341  7341 V [BNRBootReceiver]: Boot Receiver Return
08-05 09:54:43.784  7341  7341 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 09:54:43.787  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:43.796  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:43.804  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 09:54:43.827  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:43.828  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:43.831  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 09:54:43.837  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:43.860  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:43.872  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:43.882  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:43.882  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 09:54:43.885  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 09:54:43.894  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-05 09:54:43.899  6796  6796 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-05 09:54:43.904  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:43.917  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:43.929  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:43.943  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:43.943  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:43.944  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 09:54:43.954  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 09:54:43.963  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:43.970  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:43.980  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:43.980  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 09:54:43.981  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 09:54:43.985  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:44.000  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:44.009  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.016  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:44.017  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 09:54:44.018  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 09:54:44.020  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:44.028  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 09:54:44.035  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 09:54:44.046  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:44.046  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:44.046  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 09:54:44.050  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:44.058  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:44.065  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 09:54:44.073  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 09:54:44.074  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:44.074  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 09:54:44.082  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 09:54:44.096  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:44.103  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.112  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:44.113  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 09:54:44.120  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 09:54:44.126  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:44.142  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:44.151  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.163  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 09:54:44.164  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:44.166  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 09:54:44.175  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:44.182  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-05 09:54:44.195  1037  1418 D WifiService: New client listening to asynchronous messages
,08-05 09:54:44.197  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:54:44.210  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:44.222  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.236  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 09:54:44.236  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:44.238  6870  6870 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 09:54:44.239  6870  6870 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 09:54:44.240  6870  6870 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 09:54:44.249  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 09:54:44.261  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 09:54:44.267  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 09:54:44.275  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:44.287  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.302  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:44.303  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 09:54:44.305  6870  6870 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-05 09:54:44.307  6870  6870 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 09:54:44.308  6870  6870 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 09:54:44.315  1037  2015 I ActivityManager: Killing 6846:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-05 09:54:44.350  1037  2016 W libprocessgroup: failed to open /acct/uid_10037/pid_6846/cgroup.procs: No such file or directory
,08-05 09:54:44.356  2196  2196 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-05 09:54:44.374  2196  2196 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-05 09:54:44.374  2196  2196 D c       : Getting all permits...
08-05 09:54:44.374  2196  2196 D a       : Opening database...
08-05 09:54:44.383  2196  2196 D a       : Opening database auth.proximity.permit_store...
08-05 09:54:44.385  2196  2196 D a       : Closing database...
08-05 09:54:44.410  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 09:54:44.420  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 09:54:44.421  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-05 09:54:44.421  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:54:44.428  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:44.436  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.447  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:44.447  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:44.449  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 09:54:44.453  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:44.459  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 09:54:44.459  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 09:54:44.460  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:54:44.467  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:44.472  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.481  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:44.481  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:44.483  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 09:54:44.487  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:44.492  6823  6823 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 09:54:44.492  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 09:54:44.492  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:54:44.497  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:44.504  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.516  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:54:44.517  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:44.519  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 09:54:44.532  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:54:44.536  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 09:54:44.547  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.558  6910  7367 V FormManager: Network unavailable.
,08-05 09:54:44.563  6910  7366 W FormManager: Network not available. Please check & try again.
08-05 09:54:44.567  6910  7367 V FormManager: Network unavailable.
08-05 09:54:44.577  2196  2196 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-05 09:54:44.597  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-05 09:54:44.597  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 09:54:44.599  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:44.602  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:44.612  6823  6823 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 09:54:44.612  6823  6823 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 09:54:44.612  6823  6823 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:54:44.612  4310  7368 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 09:54:44.615  4310  7369 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 09:54:44.615  4310  7369 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 09:54:44.617  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 09:54:44.627  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:44.639  6910  7371 W FormManager: Network not available. Please check & try again.
,08-05 09:54:44.642  6910  7372 V FormManager: Network unavailable.
08-05 09:54:44.648  6910  7372 V FormManager: Network unavailable.
08-05 09:54:44.844  1037  1377 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1504869612] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 09:54:44.847  1037  1377 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1504869615] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 09:54:44.927  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:44.944  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-05 09:54:44.954  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:44.964  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:44.965  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:44.971  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 09:54:44.978  6433  6821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 09:54:44.988  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 09:54:45.012  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:45.040  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 09:54:45.040  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:45.040  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 09:54:45.040  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-05 09:54:45.047  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive,
08-05 09:54:45.050  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c457b3e
08-05 09:54:45.050  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 09:54:45.050  7008  7008 D AppUp4:CustFacade: isPhone : true
08-05 09:54:45.052  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-05 09:54:45.052  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 09:54:45.063  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:45.063  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 09:54:45.068  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:45.069  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:45.072  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:45.080  7035  7035 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 09:54:45.081  4310  7388 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 09:54:45.086  4310  7389 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:45.087  4310  7389 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 09:54:45.110  7035  7391 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:54:45.118  6910  7397 W FormManager: Network not available. Please check & try again.
08-05 09:54:45.124  3493  3493 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 09:54:45.124  3493  3493 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:45.124  3493  3493 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 09:54:45.124  3493  3493 D PhoneState: setPdpRejectCasuse : false
08-05 09:54:45.128  7077  7077 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 09:54:45.129  7077  7077 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 09:54:45.138  6910  7398 V FormManager: Network unavailable.
,08-05 09:54:45.144  7147  7147 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:45,
08-05 09:54:45.145  6910  7398 V FormManager: Network unavailable.
08-05 09:54:45.146  7147  7147 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 09:54:45.146  7147  7147 D Weather.Utils: 2 : All the weather widget is gone.
08-05 09:54:45.147  7147  7147 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 09:54:45.147  7147  7147 D WeatherAncestor: connectivity changed - connection : true
08-05 09:54:45.147  7147  7147 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31baeeec
08-05 09:54:45.148  7147  7147 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 09:54:45.148  7147  7147 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 09:54:45.148  7147  7147 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 09:54:45.148  7147  7147 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 09:54:45.148  7147  7147 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:45
08-05 09:54:45.866  1037  3563 I LocationManagerService: remove 201ed71c
08-05 09:54:45.867  1037  3563 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-05 09:54:45.867  1037  3563 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 09:54:45.869  1037  3563 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-05 09:54:45.870  1037  3563 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-05 09:54:45.871  1037  3563 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-05 09:54:45.952  1037  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 09:54:45.953  1037  1921 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 09:54:45.981  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 09:54:45.981  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 09:54:45.981  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-05 09:54:45.985  1037  1119 D BluetoothManagerService: Message: 1
08-05 09:54:45.985  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 09:54:46.017  1037  1119 D BluetoothManagerService: Message: 20
08-05 09:54:46.017  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@246e00c5:true
,08-05 09:54:46.022  6958  6958 D BluetoothAdapterState: make
08-05 09:54:46.027  6958  6958 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 09:54:46.027  6958  6958 I bluedroid-qcom: init
08-05 09:54:46.028  6958  7412 I BluetoothAdapterState: Entering OffState
08-05 09:54:46.028  6958  6958 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 09:54:46.029  6958  6958 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 09:54:46.029  6958  6958 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 09:54:46.029  6958  6958 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 09:54:46.029  6958  6958 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 09:54:46.031  6958  6958 I bluedroid-qcom: get_profile_interface socket
08-05 09:54:46.031  6958  6958 I bluedroid-qcom: get_profile_interface map_client
,08-05 09:54:46.037  6958  7416 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 09:54:46.039  6958  7416 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 09:54:46.030  7415  7415 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:46.030  7415  7415 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:46.051  7415  7415 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 09:54:46.051  7415  7415 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 09:54:46.051  7415  7415 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-05 09:54:46.055  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 09:54:46.056  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 09:54:46.058  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 09:54:46.058  1037  1119 D BluetoothManagerService: Message: 40
08-05 09:54:46.058  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 09:54:46.059  6958  6975 I bluedroid-qcom: config_hci_snoop_log
08-05 09:54:46.060  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 09:54:46.060  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 09:54:46.061  7415  7415 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 09:54:46.064  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.070  7415  7415 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 09:54:46.070  7415  7415 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-05 09:54:46.073  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.081  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:46.087  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 09:54:46.099  6958  7412 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-05 09:54:46.101  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-05 09:54:46.102  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-05 09:54:46.102  6958  7416 D BluetoothAdapterProperties: Name is: G3
08-05 09:54:46.104  6958  7412 D BluetoothAdapterProperties: Setting state to 11
08-05 09:54:46.104  6958  7412 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 09:54:46.108  6958  7412 I LGBluetoothServiceJni: classInitNative: succeeds
08-05 09:54:46.116  1037  1119 D BluetoothManagerService: Message: 60
08-05 09:54:46.117  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 09:54:46.117  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-05 09:54:46.127  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 09:54:46.128  6433  6821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 09:54:46.132  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.135  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 09:54:46.137  6958  7412 D BluetoothBondStateMachine: make
,08-05 09:54:46.140  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:46.144  6958  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.144  6958  7412 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 09:54:46.144  6958  7412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.144  6958  7412 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 09:54:46.145  6958  7412 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 09:54:46.145  6958  7429 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-05 09:54:46.155  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:46.160  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-05 09:54:46.160  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:46.161  6958  7412 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:46.162  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 09:54:46.162  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:46.164  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:46.166  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-05 09:54:46.168  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:46.168  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 09:54:46.175  6958  6958 D HeadsetService: Received start request. Starting profile...
08-05 09:54:46.176  6958  6958 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 09:54:46.176  6958  6958 D LGBluetoothHfpAdapter: Version 1.6
08-05 09:54:46.179  6958  6958 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 09:54:46.179  6958  7412 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:46.180  6958  6958 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-05 09:54:46.180  6958  6958 D HeadsetStateMachine: make
08-05 09:54:46.191  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 09:54:46.195  6958  7412 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:46.201  6958  7412 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:46.201  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.210  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 09:54:46.210  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:46.212  6958  7412 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:46.212  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 09:54:46.212  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 09:54:46.214  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
08-05 09:54:46.218  6958  7412 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:46.218  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c457b3e
08-05 09:54:46.218  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 09:54:46.218  7008  7008 D AppUp4:CustFacade: isPhone : true
08-05 09:54:46.219  6958  6958 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:54:46.219  6958  6958 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 09:54:46.220  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-05 09:54:46.220  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 09:54:46.222  6958  7412 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 09:54:46.224  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.224  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 09:54:46.226  6958  6958 D HeadsetStateMachine: max_hf_connections = 1
08-05 09:54:46.226  6958  6958 I bluedroid-qcom: get_profile_interface handsfree
08-05 09:54:46.226  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:46.228  6958  6958 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 09:54:46.228   322  2138 V AudioPolicyService: registerClient() client 0xb558af20, uid 1002
08-05 09:54:46.229  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:46.229   322  1388 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 09:54:46.229   322  1388 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 09:54:46.229   322  1388 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 09:54:46.229  6958  6958 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 09:54:46.229   322   322 V AudioFlinger: registerClient() client 0xb5581c70, pid 6958
08-05 09:54:46.230  6958  6958 V ToneGenerator: Create Track: 0xb4928a80
08-05 09:54:46.230  6958  6958 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 09:54:46.230  6958  6958 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 09:54:46.230   322  2138 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 09:54:46.230   322  2138 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 09:54:46.230   322  2138 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 09:54:46.230   322  2138 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 09:54:46.230  6958  6958 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 09:54:46.231   322   322 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 09:54:46.231   322  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 09:54:46.231   322  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 09:54:46.231   322  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 09:54:46.231   322  1387 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 09:54:46.231   322  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:46.232   322  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 09:54:46.232  1037  1053 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:46.232  1037  1053 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 09:54:46.232  1588  2525 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:46.232  1588  2525 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 09:54:46.232  3493  3512 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:46.232  3493  3512 V AudioSystem: ioConfigChanged() opening a,lready existing output! 2
08-05 09:54:46.232   322  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:46.232   322  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:46.232  1836  2425 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:46.232  1836  2425 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 09:54:46.232  1588  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:46.232  1836  4437 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:46.233  1836  4437 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:46.232  1588  1607 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:46.233  1037  1941 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:46.233  1037  1941 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:46.233  6958  6974 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:46.233  3493  3511 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:46.233  3493  3511 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:46.233  6958  6974 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 09:54:46.233  6958  6974 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:46.233  6958  6974 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 09:54:46.233  6958  6958 V AudioSystem: getLatency() output 2, latency 50
08-05 09:54:46.233  6958  6958 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 09:54:46.233  6958  6958 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 09:54:46.233   322  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 09:54:46.233   322  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 09:54:46.233   322  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 09:54:46.233   322  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 09:54:46.233   322  1388 V AudioFlinger: createTrack() lSessionId: 20
08-05 09:54:46.234  6958  6958 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 09:54:46.234   322   322 V AudioFlinger: acquiring 20 from 6958, for 6958
08-05 09:54:46.234   322   322 V AudioFlinger:  added new entry for 20
08-05 09:54:46.234  6958  6958 V ToneGenerator: ToneGenerator INIT OK, time: 336219
08-05 09:54:46.234  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.235  6958  7435 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 09:54:46.235  6958  7435 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 09:54:46.235  6958  7435 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 09:54:46.235  6958  7435 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 09:54:46.235  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.236   322  1387 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6958
08-05 09:54:46.236   322  1387 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 09:54:46.236   322  1387 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 09:54:46.236   322  1387 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 09:54:46.236  6958  6958 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 09:54:46.236   322  1387 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 09:54:46.236   322  1387 V voice   : voice_set_parameters: exit with code(0)
08-05 09:54:46.236   322  1387 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 09:54:46.236   322  1387 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 09:54:46.236   322  1387 V msm8974_platform: platform_set_parameters: exit with code(0)
,08-05 09:54:46.236   322  1387 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 09:54:46.236   322  1387 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 09:54:46.236   322  1387 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 09:54:46.236  6958  7435 V ToneGenerator: ToneGenerator destructor
08-05 09:54:46.236  6958  7435 V ToneGenerator: stopTone
08-05 09:54:46.236  6958  7435 V ToneGenerator: Delete Track: 0xb4928a80
08-05 09:54:46.237  6958  6958 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:46.237  6958  6958 V BluetoothPbapReceiver: ***********state = 11
08-05 09:54:46.238  6958  7435 V AudioTrack: ~AudioTrack, releasing session id from 6958 on behalf of 6958
08-05 09:54:46.238   322  1388 V AudioFlinger: releasing 20 from 6958 for 6958
08-05 09:54:46.238   322  1388 V AudioFlinger:  decremented refcount to 0
08-05 09:54:46.238   322  1388 V AudioFlinger: purging stale effects
08-05 09:54:46.238   322  1388 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 09:54:46.238   322  1388 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 09:54:46.238   322  1264 V AudioPolicyService: AudioCommandThread() waking up
08-05 09:54:46.238   322  1264 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 09:54:46.238   322  1264 V AudioPolicyManager: releaseOutput() 2
08-05 09:54:46.238   322  1264 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 09:54:46.238   322  1388 V AudioFlinger: PlaybackThread::Track destructor
08-05 09:54:46.238   322  1388 V AudioFlinger: removeClient_l() pid 6958, calling pid 322
08-05 09:54:46.240  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 09:54:46.241  6958  6958 D A2dpService: Received start request. Starting profile...
08-05 09:54:46.242  6958  6958 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 09:54:46.242  4310  7439 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 09:54:46.243  1037  1052 W Process : Unable to open /proc/7438/status
08-05 09:54:46.243  6958  6958 V Avrcp   : make
08-05 09:54:46.243  6958  6958 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 09:54:46.243  6958  6958 I bluedroid-qcom: get_profile_interface avrcp
08-05 09:54:46.248  4310  7440 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.248  4310  7440 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 09:54:46.251  6958  7412 V LGMDMManager: Create singleton instance
08-05 09:54:46.252  6958  7412 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 09:54:46.297  1037  1053 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7441 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-05 09:54:46.305  7035  7035 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 09:54:46.306  6958  6958 V AudioManager: registerRemoteController: size of Media player list: 0
08-05 09:54:46.307  6958  6958 E AudioManager: No RCC entry present to update
08-05 09:54:46.307  6958  6958 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 09:54:46.310  6958  6958 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 09:54:46.310  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 09:54:46.310  6958  6958 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-05 09:54:46.315  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-05 09:54:46.372  7035  7463 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:46.374  6910  7461 W FormManager: Network not available. Please check & try again.
,08-05 09:54:46.375  3493  3493 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 09:54:46.375  3493  3493 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.375  3493  3493 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 09:54:46.380  6910  7462 V FormManager: Network unavailable.
08-05 09:54:46.383  6910  7462 V FormManager: Network unavailable.
08-05 09:54:46.383  7077  7077 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 09:54:46.383  7077  7077 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 09:54:46.393  7147  7147 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:46
,08-05 09:54:46.396  7147  7147 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 09:54:46.396  7147  7147 D Weather.Utils: 2 : All the weather widget is gone.
08-05 09:54:46.397  7147  7147 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 09:54:46.397  7147  7147 D WeatherAncestor: connectivity changed - connection : true
08-05 09:54:46.397  7147  7147 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31baeeec
08-05 09:54:46.398  7147  7147 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 09:54:46.398  7147  7147 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 09:54:46.398  7147  7147 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 09:54:46.398  7147  7147 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 09:54:46.398  7147  7147 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:46
08-05 09:54:46.406  1037  1956 V SIM_STK : Menu title from STK is T-Mobile
08-05 09:54:46.406  1037  1956 V SIM_STK : Menu title from STK is T-Mobile
,08-05 09:54:46.420  7441  7441 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 09:54:46.420  7441  7441 W LG Account v2.2: No ProfileInfo entries
08-05 09:54:46.420  7441  7441 I LG Account v2.2: isEnabled: false
08-05 09:54:46.420  7441  7441 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 09:54:46.420  7441  7441 I Feature : [Lifetracker]Country: EU
08-05 09:54:46.420  7441  7441 I Feature : [Lifetracker]Operator: OPEN
08-05 09:54:46.420  7441  7441 I Feature : [Lifetracker]Ranking support: false
08-05 09:54:46.420  7441  7441 I Feature : [Lifetracker]Comfort support: false
08-05 09:54:46.420  7441  7441 I Feature : [Lifetracker]Accessory: true
08-05 09:54:46.420  7441  7441 I Feature : [Lifetracker]Health device: true
08-05 09:54:46.421  7441  7441 I Feature : [Lifetracker]Extra Pedometer: false
08-05 09:54:46.421  7441  7441 I Feature : [Lifetracker]Blood glucose device: false
08-05 09:54:46.421  7441  7441 I Feature : [Lifetracker]Device Number: 3
08-05 09:54:46.429  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 09:54:46.430  6433  6821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 09:54:46.430  6796  6796 D BluetoothPermissionRequest: onReceive
,08-05 09:54:46.439  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 09:54:46.442  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:54:46.451  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 09:54:46.451  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.451  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 09:54:46.451  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 09:54:46.452  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 09:54:46.454  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c457b3e
08-05 09:54:46.454  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 09:54:46.454  7008  7008 D AppUp4:CustFacade: isPhone : true
08-05 09:54:46.455  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-05 09:54:46.455  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 09:54:46.457  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.457  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 09:54:46.458  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:46.459  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:46.462  4310  7467 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 09:54:46.464  4310  7468 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.464  4310  7468 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 09:54:46.465  7035  7035 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 09:54:46.478  7035  7469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:54:46.481  3493  3493 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 09:54:46.481  3493  3493 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:46.481  3493  3493 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 09:54:46.483  7077  7077 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 09:54:46.483  7077  7077 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 09:54:46.489  6910  7471 W FormManager: Network not available. Please check & try again.
08-05 09:54:46.491  7147  7147 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:46
,08-05 09:54:46.492  1037  1906 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 09:54:46.493  7147  7147 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 09:54:46.493  7147  7147 D Weather.Utils: 2 : All the weather widget is gone.
08-05 09:54:46.493  7147  7147 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-05 09:54:46.494  7147  7147 D WeatherAncestor: connectivity changed - connection : true
08-05 09:54:46.494  7147  7147 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31baeeec
08-05 09:54:46.495  7147  7147 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 09:54:46.495  7147  7147 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 09:54:46.495  7147  7147 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 09:54:46.495  7147  7147 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 09:54:46.495  7147  7147 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:46
08-05 09:54:46.498  6910  7472 V FormManager: Network unavailable.
08-05 09:54:46.499  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 09:54:46.501  6910  7472 V FormManager: Network unavailable.
08-05 09:54:46.502  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 09:54:46.503  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 09:54:46.503  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 09:54:46.503  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 09:54:46.503  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 09:54:46.503  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 09:54:46.503  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 09:54:46.503  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 09:54:46.503  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 09:54:46.503  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 09:54:46.503  6958  6958 I BluetoothA2dpServiceJni: classInitNative
08-05 09:54:46.503  6958  6958 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 09:54:46.503  6958  6958 D A2dpStateMachine: make
,08-05 09:54:46.505  6958  6958 I bluedroid-qcom: get_profile_interface a2dp
08-05 09:54:46.505  6958  7475 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 09:54:46.506  6958  6958 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 09:54:46.506  6958  6958 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 09:54:46.507  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.507  6958  7474 D A2dpStateMachine: Enter Disconnected: -2
08-05 09:54:46.508  6958  6958 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 09:54:46.509  6958  6958 D HidService: Received start request. Starting profile...
08-05 09:54:46.509  6958  6958 I bluedroid-qcom: get_profile_interface hidhost
08-05 09:54:46.509  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.510  6958  6958 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 09:54:46.511  6958  6958 D HealthService: Received start request. Starting profile...
08-05 09:54:46.512  6958  6958 I bluedroid-qcom: get_profile_interface health
08-05 09:54:46.512  6958  6958 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 09:54:46.512  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.513  6958  6958 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 09:54:46.514  6958  6958 D PanService: Received start request. Starting profile...
08-05 09:54:46.514  6958  6958 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 09:54:46.514  6958  6958 I bluedroid-qcom: get_profile_interface pan
08-05 09:54:46.518  6958  6958 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 09:54:46.518  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
,08-05 09:54:46.519  6958  6958 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 09:54:46.523  6958  6958 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 09:54:46.523  6958  6958 D BtGatt.GattService: Received start request. Starting profile...
08-05 09:54:46.523  6958  6958 D BtGatt.GattService: start()
08-05 09:54:46.523  6958  6958 I bluedroid-qcom: get_profile_interface gatt
08-05 09:54:46.523  6958  6958 D BtGatt.AdvertiseManager: advertise manager created
08-05 09:54:46.528  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.528  6958  6958 D HeadsetStateMachine: Proxy object connected
08-05 09:54:46.528  6958  6958 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 09:54:46.529  6958  6958 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 09:54:46.530  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.530  6958  6958 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 09:54:46.531  6958  6958 V BluetoothMapService: BluetoothMapBinder()
,08-05 09:54:46.531  6958  6958 D BluetoothMapService: Received start request. Starting profile...
08-05 09:54:46.531  6958  6958 D BluetoothMapService: start()
08-05 09:54:46.533  6958  6958 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-05 09:54:46.534  6958  6958 D BluetoothMapEmailAppObserver: createReceiver()
08-05 09:54:46.534  6958  6958 D BluetoothMapEmailAppObserver: initObservers()
08-05 09:54:46.534  6958  6958 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 09:54:46.540  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:46.542  6958  6958 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 09:54:46.543  6958  7435 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 09:54:46.543  6958  7435 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 09:54:46.543  6958  7435 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-05 09:54:46.546  6958  6958 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 09:54:46.548  6958  6958 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 09:54:46.550  6958  6958 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 09:54:46.551  6958  6958 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 09:54:46.553  6958  6958 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 09:54:46.556  6958  6958 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 09:54:46.556  6958  6958 V BluetoothMapService: Handler(): got msg=1
08-05 09:54:46.556  6958  7412 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 09:54:46.557  6958  7412 I bluedroid-qcom: enable
08-05 09:54:46.557  6958  7482 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 09:54:46.557  6958  7482 I bt-btu  : btu_task pending for preload complete event
,08-05 09:54:46.558  6958  7412 I bt_hci_bdroid: init
08-05 09:54:46.558  6958  7412 I bt_vendor: bt-vendor : init
08-05 09:54:46.559  6958  7412 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 09:54:46.559  6958  7412 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 09:54:46.559  6958  7412 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 09:54:46.559  6958  7412 D bt_userial_mct: userial_init
,08-05 09:54:46.559  6958  6958 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:46.560  6958  7412 D bt_hci_bdroid: set_power 1
08-05 09:54:46.560  6958  7412 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 09:54:46.560  6958  7412 I bt_vendor: Starting hciattach daemon
08-05 09:54:46.560  6958  7412 I bt_vendor: try to set true
08-05 09:54:46.560  6958  6958 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 09:54:46.560  6958  6958 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 09:54:46.560  6958  6958 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 09:54:46.561  6958  6958 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:46.562  6958  6958 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 09:54:46.550  7485  7485 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:46.550  7485  7485 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:46.583  7486  7486 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 09:54:46.694  7492  7492 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 09:54:46.709  7493  7493 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 09:54:46.749  7495  7495 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 09:54:46.768  7496  7496 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 09:54:46.786  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 09:54:46.799  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-05 09:54:46.822  7503  7503 I libmdmdetect: ESOC framework not supported
08-05 09:54:46.823  7503  7503 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-05 09:54:46.832  7503  7503 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 09:54:46.832  7503  7503 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 09:54:46.832  7503  7503 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 09:54:46.832  7503  7503 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 09:54:46.832  7503  7503 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 09:54:46.832  7503  7503 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 09:54:46.832  7503  7503 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 09:54:46.870  7503  7507 E QC-QMI  : qmi_client [7503] 14: failed to locate client data
,08-05 09:54:46.873   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 09:54:46.874   468   468 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-05 09:54:46.921  7508  7508 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 09:54:46.933  7509  7509 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-05 09:54:46.963  6958  7412 I bt_vendor: bluetooth satus is on
08-05 09:54:46.963  6958  7412 D bt_hci_bdroid: preload
08-05 09:54:46.963  6958  7484 D bt_userial_mct: userial_open(port:0)
08-05 09:54:46.963  6958  7484 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-05 09:54:46.967  6958  7484 I bt_vendor: Done intiailizing UART
08-05 09:54:46.968  6958  7484 I bt_vendor: Done intiailizing UART
08-05 09:54:46.968  6958  7484 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 09:54:46.968  6958  7484 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 09:54:46.968  6958  7511 D bt_userial_mct: Entering userial_read_thread()
08-05 09:54:46.969  6958  7482 I bt-btu  : btu_task received preload complete event
08-05 09:54:46.969  6958  7482 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 09:54:46.969  6958  7482 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 09:54:46.971  6958  7482 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 09:54:46.976  6958  7482 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-05 09:54:47.080  6958  7482 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 09:54:47.080  6958  7482 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a3061 
,08-05 09:54:47.080  6958  7482 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a3061 
,08-05 09:54:47.146  6958  7416 E bt-btif : Calling BTA_HhEnable
,08-05 09:54:47.146  6958  7416 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 09:54:47.147  6958  7416 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 09:54:47.157  6958  7482 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 09:54:47.157  6958  7482 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 09:54:47.157  6958  7482 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 09:54:47.158  6958  7482 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 09:54:47.158  6958  7482 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 09:54:47.159  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 09:54:47.159  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 09:54:47.160  6958  7416 D BluetoothAdapterProperties: Name is: G3
08-05 09:54:47.161  6958  7416 D BluetoothAdapterProperties: Scan Mode:20
08-05 09:54:47.161  6958  7416 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 09:54:47.161  6958  7416 D bt_hci_bdroid: postload
08-05 09:54:47.163  6958  7484 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 09:54:47.163  6958  7482 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-05 09:54:47.166  6958  7416 D bte_conf: Device ID record 1 : primary
08-05 09:54:47.166  6958  7416 D bte_conf:   vendorId            = 00c4
08-05 09:54:47.166  6958  7416 D bte_conf:   vendorIdSource      = 0001
08-05 09:54:47.166  6958  7416 D bte_conf:   product             = 13a1
08-05 09:54:47.166  6958  7416 D bte_conf:   version             = 1000
08-05 09:54:47.166  6958  7416 D bte_conf:   clientExecutableURL = 
08-05 09:54:47.166  6958  7416 D bte_conf:   serviceDescription  = 
08-05 09:54:47.166  6958  7416 D bte_conf:   documentationURL    = 
08-05 09:54:47.166  6958  7416 D bte_conf: bte_load_did_conf no section named DID2.
08-05 09:54:47.170  6958  7412 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 09:54:47.170  6958  7412 D BluetoothAdapterProperties: ScanMode =  20
08-05 09:54:47.170  6958  7412 D BluetoothAdapterProperties: State =  11
08-05 09:54:47.170  6958  7412 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 09:54:47.171  6958  7412 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 09:54:47.171  6958  7412 D BluetoothAdapterProperties: Setting state to 12
08-05 09:54:47.171  6958  7412 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 09:54:47.171  6958  7416 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 09:54:47.172  6958  7416 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 09:54:47.160  7516  7516 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:47.170  7516  7516 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 09:54:47.185  1037  1119 D BluetoothManagerService: Message: 60
08-05 09:54:47.185  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 09:54:47.185  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-05 09:54:47.185  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 09:54:47.195  6958  7412 I BluetoothAdapterState: Entering On State
,08-05 09:54:47.202  6958  7416 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 09:54:47.202  6958  7416 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 09:54:47.203  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 09:54:47.214  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:47.214  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:47.214  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:47.214  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:47.214  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:47.214  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:47.214  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:47.214  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 09:54:47.219  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:47.232  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:47.232  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:47.232  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:47.232  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:47.232  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:47.232  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:47.232  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:47.232  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 09:54:47.238  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:47.245  1037  1037 D BluetoothA2dp: Proxy object connected
,08-05 09:54:47.249  6958  7412 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 09:54:47.249  6958  7412 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 09:54:47.249  6958  7412 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-05 09:54:47.250  6958  7412 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 09:54:47.250  6958  7412 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 09:54:47.261  1836  1836 D BluetoothHeadset: Proxy object connected
,08-05 09:54:47.264  6958  7484 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 09:54:47.298  6958  7484 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 09:54:47.298  6958  7484 D bt_hci_bdroid: Used up Tx Cmd credits
,08-05 09:54:47.301  6958  7484 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 09:54:47.302  6958  7511 E bt_mct  : hci lib postload completed
08-05 09:54:47.307  7521  7521 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-05 09:54:47.308  6796  6820 D BluetoothPan: onBluetoothStateChange on: true
08-05 09:54:47.308  6796  6820 D BluetoothPan: onBluetoothStateChange call bindService
08-05 09:54:47.310  6958  7482 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 09:54:47.310  6958  7482 W bt-smp  : Plain text(LSB ~ MSB) = 45 fb 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:47.310  6958  7482 W bt-smp  : Encrypted text(LSB ~ MSB) = 49 75 a5 1e a2 d5 19 19 4d 9b e5 ec 72 68 2d 21 
08-05 09:54:47.310  6958  7482 W bt-btm  : Stopping oneshot timer
,08-05 09:54:47.313  6796  6817 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 09:54:47.315  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 09:54:47.315  1037  1037 D BluetoothHeadset: Proxy object connected
08-05 09:54:47.315  1836  4437 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 09:54:47.316  6796  6796 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 09:54:47.316  6796  6796 D PanProfile: Bluetooth service connected
08-05 09:54:47.323  1836  1836 D BluetoothHeadset: Proxy object connected
08-05 09:54:47.323  6796  6820 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 09:54:47.326  1836  2425 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 09:54:47.329  1836  1836 D BluetoothHeadset: Proxy object connected
08-05 09:54:47.330  6796  7312 D BluetoothMap: onBluetoothStateChange: up=true
08-05 09:54:47.330  6958  7482 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 09:54:47.330  6958  7482 W bt-smp  : Plain text(LSB ~ MSB) = 54 a8 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:47.330  6958  7482 W bt-smp  : Encrypted text(LSB ~ MSB) = a0 fd 8b af 4c 5d c9 59 33 de 5a 2c d9 a7 54 95 
08-05 09:54:47.330  6958  7482 W bt-btm  : Stopping oneshot timer
08-05 09:54:47.334  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 09:54:47.334  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 09:54:47.333  6796  6796 D BluetoothInputDevice: Proxy object connected
08-05 09:54:47.337  6796  6796 D HidProfile: Bluetooth service connected
08-05 09:54:47.337  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 09:54:47.337  1037  1119 D BluetoothManagerService: Message: 40
08-05 09:54:47.337  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 09:54:47.338  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:47.339  1925  2110 D LGBluetoothAPIService: Message: 1
08-05 09:54:47.339  1925  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-05 09:54:47.342  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 09:54:47.344  6958  7482 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 09:54:47.344  6958  7482 W bt-smp  : Plain text(LSB ~ MSB) = c2 36 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:47.344  6958  7482 W bt-smp  : Encrypted text(LSB ~ MSB) = 5a f4 0b cf c1 97 3a ee 83 c2 b6 25 fc b7 f6 af 
08-05 09:54:47.344  6958  7482 W bt-btm  : Stopping oneshot timer
08-05 09:54:47.347  6709  6709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 09:54:47.350  6796  6796 D BluetoothMap: Proxy object connected
08-05 09:54:47.350  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:47.350  6796  6796 D MapProfile: Bluetooth service connected
08-05 09:54:47.350  6796  6796 D BluetoothMap: getConnectedDevices()
,08-05 09:54:47.352  1925  2110 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-05 09:54:47.354  6958  6958 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:47.354  6958  6958 D BluetoothMapService: STATE_ON
08-05 09:54:47.355  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:47.355  6958  6974 V BluetoothMapService: getConnectedDevices()
08-05 09:54:47.356  6958  6958 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 09:54:47.357  6958  6958 V BluetoothMapService: Handler(): got msg=1
08-05 09:54:47.358  6958  6958 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 09:54:47.358  6796  6796 D LocalBluetoothProfileManager: Adding local A2DP profile
08-05 09:54:47.358  6958  6958 D LGBluetoothAPIServer: [BTUI] onBind()
08-05 09:54:47.359  6958  7539 D BluetoothMapMasInstance: MAS initSocket()
08-05 09:54:47.359  6958  7539 D BluetoothMapMasInstance:   masId = 00
08-05 09:54:47.359  6958  7539 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 09:54:47.359  6958  7539 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 09:54:47.359  6958  7539 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 09:54:47.360  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:47.360  1037  1119 D BluetoothManagerService: Message: 30
08-05 09:54:47.361  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 09:54:47.361  6958  7482 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-05 09:54:47.361  6958  7482 W bt-smp  : Plain text(LSB ~ MSB) = 95 e0 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:47.361  6958  7482 W bt-smp  : Encrypted text(LSB ~ MSB) = f1 cd b3 d6 d9 6a c5 b2 e1 c9 8d bd d6 65 9e 68 
08-05 09:54:47.361  6958  7482 W bt-btm  : Stopping oneshot timer
08-05 09:54:47.361  1925  2110 D LGBluetoothAPIService: Message: 100
08-05 09:54:47.361  1925  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 09:54:47.363  6796  6796 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-05 09:54:47.364  6958  7539 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:47.364  6958  7539 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 09:54:47.366  1037  1119 D BluetoothManagerService: Message: 30
,08-05 09:54:47.368  6958  7539 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 09:54:47.368  6958  7539 D BluetoothMapMasInstance: Accepting socket connection...
08-05 09:54:47.369  6958  7482 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 09:54:47.369  6958  7482 W bt-smp  : Plain text(LSB ~ MSB) = b4 57 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:47.369  6958  7482 W bt-smp  : Encrypted text(LSB ~ MSB) = 34 5b ff a7 16 87 43 39 fb 29 b2 64 61 0a 56 90 
08-05 09:54:47.369  6958  7482 W bt-btm  : Stopping oneshot timer
08-05 09:54:47.372  6958  7416 D BluetoothAdapterProperties: Scan Mode:21
08-05 09:54:47.372  6958  7416 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 09:54:47.375  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:47.376  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:47.377  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 09:54:47.378  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:47.378  6958  6958 V BluetoothPbapService: Pbap Service onCreate
08-05 09:54:47.378  6958  6958 V BluetoothPbapService: Starting PBAP service
08-05 09:54:47.379  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 09:54:47.379  6958  6958 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 09:54:47.379  6958  6958 V BluetoothPbapService: Pbap Service onBind
,08-05 09:54:47.382  6796  6796 D BluetoothA2dp: Proxy object connected
08-05 09:54:47.383  6796  6796 D A2dpProfile: Bluetooth service connected
08-05 09:54:47.383  6958  6958 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:47.383  6958  6958 V BluetoothPbapService: state: 12
08-05 09:54:47.385  6958  6958 V BluetoothPbapService: Handler(): got msg=1
08-05 09:54:47.386  6958  6958 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 09:54:47.386  6958  6958 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 09:54:47.386  6958  6958 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:47.386  6958  6958 V BluetoothPbapReceiver: ***********state = 12
08-05 09:54:47.388  6796  6796 D BluetoothHeadset: Proxy object connected
08-05 09:54:47.388  6958  7542 V BluetoothPbapService: Pbap Service initSocket
08-05 09:54:47.389  1037  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:47.389  6796  6796 D HeadsetProfile: Bluetooth service connected
08-05 09:54:47.389  6958  7542 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:47.389  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 09:54:47.390  2196  2196 D c       : Getting all permits...
08-05 09:54:47.390  2196  2196 D a       : Opening database...
,08-05 09:54:47.392  6958  7542 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 09:54:47.393  6958  7542 V BluetoothPbapService: Succeed to create listening socket 
08-05 09:54:47.393  6958  7542 V BluetoothPbapService: Accepting socket connection...
08-05 09:54:47.393  6796  6796 D DockEventReceiver: finishStartingService: stopping service
08-05 09:54:47.394  6796  6796 D BluetoothPbap: Proxy object connected
08-05 09:54:47.394  6796  6796 D PbapServerProfile: Bluetooth service connected
08-05 09:54:47.395  2196  2196 D a       : Opening database auth.proximity.permit_store...
08-05 09:54:47.395  2196  2196 D a       : Closing database...
08-05 09:54:47.398  7179  7235 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-05 09:54:47.406  6796  6796 D BluetoothPermissionRequest: onReceive
,08-05 09:54:47.407  6796  6796 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 09:54:47.409  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 09:54:47.411  6958  6958 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 09:54:47.412  6958  6958 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 09:54:47.417  6958  6958 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-05 09:54:47.433  6958  6958 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-05 09:54:47.434  6958  6958 V BtOppService: onCreate
,08-05 09:54:47.437  6958  6958 V BluetoothOppNotification: send message
08-05 09:54:47.440  6958  6958 V BtOppService: Starting RfcommListener
08-05 09:54:47.447  6958  6958 D BluetoothOppPreference: Dumping Names:  
08-05 09:54:47.447  6958  6958 D BluetoothOppPreference: {}
08-05 09:54:47.447  6958  6958 D BluetoothOppPreference: Dumping Channels:  
08-05 09:54:47.447  6958  6958 D BluetoothOppPreference: {}
08-05 09:54:47.448  6958  6958 V BtOppService: onStartCommand
,08-05 09:54:47.451  6958  6958 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:47.451  6958  6958 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 09:54:47.457  6958  6958 V BluetoothOppNotification: new notify threadi!
08-05 09:54:47.458  6958  6958 V BluetoothOppNotification: send delay message
08-05 09:54:47.459  6958  7552 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 09:54:47.459  6958  6958 V BtOppService: start RfcommListener
08-05 09:54:47.461  6958  7552 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 09:54:47.462  6958  7549 V BtOppService: Deleted complete outbound shares, number =  0
08-05 09:54:47.464  6958  7549 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 09:54:47.464  6958  7553 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 09:54:47.465  6958  7549 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 09:54:47.466  6958  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@240bdf81 on behalf of 
,08-05 09:54:47.469  6958  7553 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15eda826 on behalf of 
08-05 09:54:47.469  6958  6958 V BtOppService: RfcommListener started
08-05 09:54:47.469  6958  7552 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32d05c67 on behalf of 
08-05 09:54:47.473  6958  7553 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 09:54:47.474  6958  7552 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 09:54:47.478  6958  7553 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-05 09:54:47.479  6958  7554 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 09:54:47.480  1037  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:47.482  6958  7554 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:47.484  6958  7554 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-05 09:54:47.484  6958  7554 V BtOppRfcommListener: Started RFCOMM listener....
08-05 09:54:47.485  6958  7554 I BtOppRfcommListener: Accept thread started.
08-05 09:54:47.485  6958  7554 V BtOppRfcommListener: Accepting connection...
08-05 09:54:47.485  6958  7553 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d88ea14 on behalf of 
08-05 09:54:47.488  6958  7553 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 09:54:47.491  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:47.491  6958  6958 V BluetoothFtpService: Ftp Service onCreate
08-05 09:54:47.492  6958  6958 I BluetoothFtpService: Ftp Service onCreate
08-05 09:54:47.492  6958  6958 V BluetoothFtpService: Ftp Service onStartCommand
08-05 09:54:47.492  6958  6958 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:47.492  6958  6958 V BluetoothFtpService: Starting Listening on sockets
08-05 09:54:47.493  6958  6958 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 09:54:47.493  6958  7553 V BluetoothOppNotification: outbound notification was removed.
08-05 09:54:47.493  6958  6958 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 09:54:47.494  6958  6958 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 09:54:47.494  6958  7553 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 09:54:47.494  6958  6958 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:47.494  6958  6958 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 09:54:47.494  6958  6958 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-05 09:54:47.497  6958  7553 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@367c20b2 on behalf of 
08-05 09:54:47.498  6958  7553 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 09:54:47.505  6958  6958 V BtOppService: ContentObserver received notification
08-05 09:54:47.505  6958  6958 V BtOppService: ContentObserver received notification
08-05 09:54:47.505  6958  6958 V BluetoothFtpService: Handler(): got msg=1
08-05 09:54:47.506  6958  7553 V BluetoothOppNotification: inbound notification was removed.
,08-05 09:54:47.506  6958  7553 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 09:54:47.506  6958  6958 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 09:54:47.507  6958  6958 V BluetoothFtpService: Ftp Service initSocket
,08-05 09:54:47.508  6958  7553 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7c5803 on behalf of 
08-05 09:54:47.514  1037  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:47.515  6958  7555 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 09:54:47.515  6958  6958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:47.515  6958  7555 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 09:54:47.516  6958  7555 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d149380 on behalf of 
08-05 09:54:47.517  6958  6958 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
08-05 09:54:47.517  6958  6958 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 09:54:47.517  6958  7555 V BluetoothOppNotification: update too frequent, put in queue
08-05 09:54:47.518  6958  7555 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-05 09:54:47.521  6958  7556 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-05 09:54:47.533  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:47.534  6958  6958 V BluetoothSapService: Sap Service onCreate
,08-05 09:54:47.536  6958  6958 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:47.536  6958  6958 V BluetoothSapService: state: 12
08-05 09:54:47.536  6958  6958 V BluetoothSapService: Starting SAP server process
,08-05 09:54:47.538  6958  6958 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 09:54:47.539  6958  7558 V BluetoothSapService: Sap Service initRfcommSocket
08-05 09:54:47.530  7557  7557 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:47.540  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:47.530  7557  7557 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:47.541  6958  7558 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:47.542  6958  7558 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-05 09:54:47.542  6958  7558 V BluetoothSapService: Succeed to create listening socket 
08-05 09:54:47.542  6958  7558 V BluetoothSapService: Accepting socket connection...
08-05 09:54:47.552  7557  7557 V BT_SAP  : Event pipe created
08-05 09:54:47.552  7557  7557 V BT_SAP  : create_server_socket qcom.sap.server
08-05 09:54:47.552  7557  7557 V BT_SAP  : created socket fd 6
,08-05 09:54:48.003  1037  1376 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:48.003  1037  1376 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 09:54:48.063  1037  1377 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-05 09:54:48.070  1037  1377 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-05 09:54:48.216  1037  2016 I ActivityManager: Killing 7341:com.lge.bnr/1000 (adj 15): empty #17
,08-05 09:54:48.248  1037  1941 W libprocessgroup: failed to open /acct/uid_1000/pid_7341/cgroup.procs: No such file or directory
,08-05 09:54:48.333  1037  1871 I ActivityManager: Killing 6634:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-05 09:54:48.365  6870  6870 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 09:54:48.365  6870  6870 W System.err: android.os.DeadObjectException
08-05 09:54:48.365  6870  6870 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 09:54:48.366  6870  6870 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 09:54:48.366  6870  6870 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 09:54:48.366  6870  6870 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 09:54:48.366  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 09:54:48.366  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 09:54:48.366  6870  6870 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 09:54:48.366  6870  6870 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 09:54:48.366  6870  6870 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:54:48.366  6870  6870 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:54:48.366  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 09:54:48.366  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 09:54:48.366  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:54:48.366  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 09:54:48.366  6870  6870 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 09:54:48.366  6870  6870 W System.err: android.os.DeadObjectException
08-05 09:54:48.367  6870  6870 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 09:54:48.367  6870  6870 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 09:54:48.367  6870  6870 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 09:54:48.367  6870  6870 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 09:54:48.367  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 09:54:48.367  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,08-05 09:54:48.373  6870  6870 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 09:54:48.373  6870  6870 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 09:54:48.373  6870  6870 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:54:48.373  6870  6870 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:54:48.373  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 09:54:48.373  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 09:54:48.373  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:54:48.373  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 09:54:48.373  6870  6870 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 09:54:48.374  6870  6870 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-05 09:54:48.416  1037  2015 W libprocessgroup: failed to open /acct/uid_1000/pid_6634/cgroup.procs: No such file or directory
,08-05 09:54:48.420  1037  2015 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-05 09:54:48.423  6870  6870 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 09:54:48.423  6870  6870 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 09:54:48.461  1037  2016 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7568 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 09:54:48.463  6958  6958 V BluetoothOppNotification: new notify threadi!
08-05 09:54:48.464  6958  6958 V BluetoothOppNotification: send delay message
08-05 09:54:48.464  6870  6870 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-05 09:54:48.501  6958  7577 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-05 09:54:48.506  6958  7577 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3eef67ac on behalf of 
08-05 09:54:48.508  6958  7577 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 09:54:48.510  6958  7577 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 09:54:48.512  6958  7577 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@188dbc75 on behalf of 
,08-05 09:54:48.518  6958  7577 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 09:54:48.519  6958  7577 V BluetoothOppNotification: outbound notification was removed.
08-05 09:54:48.519  6958  7577 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 09:54:48.521  6958  7577 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b43140a on behalf of 
08-05 09:54:48.521  6958  7577 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 09:54:48.522  6958  7577 V BluetoothOppNotification: inbound notification was removed.
08-05 09:54:48.522  6958  7577 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 09:54:48.522  6958  7577 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1566c47b on behalf of 
08-05 09:54:48.540  7568  7568 D UEI.SmartControl: Quickset Services start...
08-05 09:54:48.542  7568  7568 I UEI.SmartControl: Manufacture = LGE
08-05 09:54:48.542  7568  7568 D UEI.SmartControl: Id = LGNevo
08-05 09:54:48.544  7568  7568 D UEI.SmartControl: File observer start...
,08-05 09:54:48.544  7568  7568 E UEI.SmartControl: IR Port is disabled: false
,08-05 09:54:48.544  7568  7568 D UEI.SmartControl: Starting file observer...
08-05 09:54:48.544  7568  7568 D UEI.SmartControl: Extracting JNI libs...
08-05 09:54:48.544  7568  7568 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-05 09:54:48.606  7568  7568 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 09:54:48.606  7568  7568 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-05 09:54:48.606  7568  7568 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 09:54:48.630  7568  7568 I UEI.SmartControl: --- Selecting new region: 6
,08-05 09:54:48.632  7568  7568 I UEI.SmartControl: Model = LG-D855
,08-05 09:54:48.633  7568  7568 D UEI.SmartControl: QS Service created
,08-05 09:54:48.644  7568  7568 I UEI.SmartControl: Service initServices...
,08-05 09:54:48.647  7568  7568 D UEI.SmartControl: QS start get config
,08-05 09:54:48.692  7568  7568 D UEI.SmartControl: Loading JNI Libs...
,08-05 09:54:48.989  1037  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 09:54:48.989  1037  1994 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@38703ef4 mBinding = false
,08-05 09:54:49.007  1037  1119 D BluetoothManagerService: Message: 2
08-05 09:54:49.008  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 09:54:49.009  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 09:54:49.009  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-05 09:54:49.010  1037  1119 D BluetoothManagerService: Sending off request.
08-05 09:54:49.011  6958  6974 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 09:54:49.011  6958  7412 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 09:54:49.011  6958  7412 D BluetoothAdapterProperties: Setting state to 13
08-05 09:54:49.011  6958  7412 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 09:54:49.012  6958  7412 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 09:54:49.012  6958  7412 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 09:54:49.014  6958  7416 D BluetoothAdapterProperties: Scan Mode:20
08-05 09:54:49.014  6958  7412 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 09:54:49.015  6958  7412 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 09:54:49.015  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 09:54:49.016  6958  7482 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 09:54:49.016  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:49.016  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:49.016  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:49.016  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:49.016  6958  7482 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 09:54:49.016  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:49.016  6958  7482 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 09:54:49.017  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:49.017  6958  7482 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 09:54:49.017  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 09:54:49.017  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 09:54:49.017  6958  7482 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 09:54:49.018  6958  7539 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 09:54:49.018  6958  7539 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:49.018  6958  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 09:54:49.018  6958  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 09:54:49.018  6958  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 09:54:49.018  6958  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 09:54:49.018  6958  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 09:54:49.018  6958  7539 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-05 09:54:49.021  6958  7558 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:49.022  6958  7556 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:49.022  6958  7554 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:49.022  6958  7542 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 09:54:49.024  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:49.024  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:49.024  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:49.024  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:49.024  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:49.024  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:49.024  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:49.024  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:49.024  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 09:54:49.025  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:49.025  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:49.028  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:49.028  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:49.028  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:49.028  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:49.028  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:49.028  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 09:54:49.028  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:49.028  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:49.028  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 09:54:49.029  6709  6709 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 09:54:49.029  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:49.062  1037  1119 D BluetoothManagerService: Message: 60
08-05 09:54:49.062  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 09:54:49.062  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-05 09:54:49.065  6958  6958 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:49.066  6958  6958 D BluetoothMapService: STATE_TURNING_OFF
08-05 09:54:49.066  6958  6958 V BluetoothMapService: Handler(): got msg=4
08-05 09:54:49.066  6958  6958 D BluetoothMapService: MAP Service closeService in
08-05 09:54:49.066  6958  6958 D BluetoothMapMasInstance: MAP Service shutdown
08-05 09:54:49.066  6958  6958 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 09:54:49.066  6958  6958 V BluetoothMapService: MAP Service closeService out
08-05 09:54:49.067  6958  6958 V BtOppService: Receiver DISABLED_ACTION 
08-05 09:54:49.067  6958  6958 I BtOppRfcommListener: stopping Accept Thread
08-05 09:54:49.067  6958  6958 V BtOppRfcommListener: close mBtServerSocket
08-05 09:54:49.067  6958  7554 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-05 09:54:49.068  6958  6958 V BtOppRfcommListener: waiting for thread to terminate
08-05 09:54:49.068  6958  6958 V BtOppRfcommListener: done waiting for thread to terminate
08-05 09:54:49.071  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 09:54:49.078  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:49.079  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 09:54:49.080  7568  7568 I UEI.SmartControl: Supports setup maps: true
08-05 09:54:49.082  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-05 09:54:49.084  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:49.084  7568  7568 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 09:54:49.084  7568  7568 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 09:54:49.085  7568  7568 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 09:54:49.085  7568  7568 I UEI.SmartControl: ### init IR Blaster...
08-05 09:54:49.086  6958  6958 V BtOppService: onDestroy
08-05 09:54:49.087  6958  6958 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 09:54:49.089  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 09:54:49.093  7568  7568 D serial_port: Configuring serial port
08-05 09:54:49.097  7568  7568 E UEI.SmartControl: UEIBLaster setting for 616
08-05 09:54:49.097  7568  7568 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 09:54:49.098  7568  7568 I UEI.SmartControl: configuring settings for MAXQ616
08-05 09:54:49.098  7568  7568 I UEI.SmartControl: Get version...
08-05 09:54:49.115  7568  7618 D UEI.SmartControl: serial port data available: 21
,08-05 09:54:49.142  7568  7568 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 09:54:49.142  7568  7568 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 09:54:49.143  7568  7568 I UEI.SmartControl: QS saving settings...
,08-05 09:54:49.143  7568  7568 D UEI.SmartControl: IR Blaster version: 25672567
08-05 09:54:49.160  7568  7618 D UEI.SmartControl: serial port data available: 4
,08-05 09:54:49.196  7568  7623 I UEI.SmartControl: Device manager: loading config....
,08-05 09:54:49.197  7568  7623 D UEI.SmartControl: ----------- loading internal config...
08-05 09:54:49.199  7568  7568 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 09:54:49.209  7568  7623 E UEI.SmartControl: Loading SETTINGS...
,08-05 09:54:49.216  7568  7623 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 09:54:49.230  1037  1870 I art     : Explicit concurrent mark sweep GC freed 74698(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.228ms total 134.691ms
,08-05 09:54:49.234  7568  7622 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 09:54:49.234  7568  7622 D UEI.SmartControl: -----service ready thread exits
08-05 09:54:49.234  7568  7568 E UEI.SmartControl: Services init done
08-05 09:54:49.234  7568  7568 D UEI.SmartControl: QS Service init finished
08-05 09:54:49.235  7568  7568 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 09:54:49.235  7568  7568 D UEI.SmartControl: QS Service version code: 201091
08-05 09:54:49.235  7568  7568 D UEI.SmartControl: Service requested: Control
08-05 09:54:49.237  6958  6958 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 09:54:49.237  6958  6958 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:49.237  6958  6958 V BluetoothPbapReceiver: ***********state = 13
08-05 09:54:49.238  6958  6958 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 09:54:49.238  7568  7568 D UEI.SmartControl: Internal service binding...
08-05 09:54:49.238  6870  6870 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 09:54:49.239  7568  7585 I UEI.SmartControl: ------ IControl API: 11
08-05 09:54:49.239  7568  7585 I UEI.SmartControl: Registering callback...
08-05 09:54:49.240  7568  7584 I UEI.SmartControl: ------ IControl API: 19
08-05 09:54:49.240  7568  7584 I UEI.SmartControl: Registering Services Ready callback...
08-05 09:54:49.240  7568  7584 I UEI.SmartControl: Notify client services are ready...
08-05 09:54:49.241  6870  6885 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 09:54:49.242  6870  6940 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 09:54:49.242  6870  6940 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 09:54:49.243  6870  6870 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 09:54:49.243  6870  6870 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 09:54:49.243  7568  7585 I UEI.SmartControl: ------ IControl API: 8
,08-05 09:54:49.244  6958  6958 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:49.244  6958  6958 V BluetoothPbapService: state: 13
08-05 09:54:49.244  6958  6958 V BluetoothPbapService: Pbap Service closeService in
08-05 09:54:49.247  6958  6958 V BluetoothPbapService: successfully stopped pbap service
08-05 09:54:49.247  6958  6958 V BluetoothPbapService: Pbap Service closeService out
08-05 09:54:49.248  6958  6958 V BluetoothPbapService: Pbap Service onDestroy
08-05 09:54:49.248  6958  6958 V BluetoothPbapService: Pbap Service closeService in
08-05 09:54:49.248  6796  6796 D DockEventReceiver: finishStartingService: stopping service
08-05 09:54:49.248  6958  6958 V BluetoothPbapService: Pbap Service closeService out
08-05 09:54:49.248  6870  6870 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 09:54:49.249  6870  6870 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 09:54:49.249  6958  6958 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 09:54:49.249  6870  6870 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 09:54:49.249  6870  6870 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 09:54:49.249  6870  6870 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 09:54:49.250  6870  6870 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 09:54:49.250  6796  6796 D BluetoothPbap: Proxy object disconnected
08-05 09:54:49.250  6796  6796 D PbapServerProfile: Bluetooth service disconnected
08-05 09:54:49.254  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 09:54:49.257  6870  6870 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-05 09:54:49.258  6870  6870 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-05 09:54:49.259  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 09:54:49.260  6870  6870 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 09:54:49.260  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 09:54:49.261  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 09:54:49.262  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 09:54:49.262  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 09:54:49.262  6870  6870 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470383689262]
08-05 09:54:49.272  6870  7627 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 09:54:49.277  6870  6870 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-05 09:54:49.278  6870  6870 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 09:54:49.278  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 09:54:49.278  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 09:54:49.278  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 09:54:49.278  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 09:54:49.279  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-05 09:54:49.280  6796  6796 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 09:54:49.280  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-05 09:54:49.287  6796  6796 D BluetoothPermissionRequest: onReceive
08-05 09:54:49.288  6796  6796 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 09:54:49.293  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 09:54:49.297  1037  2015 I ActivityManager: Killing 6823:com.lge.sync/1000 (adj 15): empty #17
,08-05 09:54:49.313  1037  1418 D WifiService: Client connection lost with reason: 4
,08-05 09:54:49.329  1037  1956 W libprocessgroup: failed to open /acct/uid_1000/pid_6823/cgroup.procs: No such file or directory
,08-05 09:54:49.329  6958  6958 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-05 09:54:49.329  6958  6958 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 09:54:49.330  6958  6958 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-05 09:54:49.334  6958  6958 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:49.335  6958  6958 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 09:54:49.335  6958  6958 V BluetoothFtpService: Ftp Service onStartCommand
08-05 09:54:49.335  6958  6958 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 09:54:49.336  6958  6958 V BluetoothFtpService: Ftp Service closeService
08-05 09:54:49.336  6958  6958 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 09:54:49.338  6958  6958 V BluetoothFtpService: successfully stopped ftp service
08-05 09:54:49.338  6958  6958 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 09:54:49.339  6958  6958 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 09:54:49.339  6958  6958 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 09:54:49.339  6958  6958 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:49.339  6958  6958 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 09:54:49.339  6958  6958 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 09:54:49.340  6958  6958 V BluetoothFtpService: Ftp Service onDestroy
08-05 09:54:49.340  6958  6958 V BluetoothFtpService: Ftp Service closeService
08-05 09:54:49.340  6958  6958 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:49.340  6958  6958 V BluetoothSapService: state: 13
08-05 09:54:49.340  6958  6958 V BluetoothSapService: Stopping SAP server process
08-05 09:54:49.341  6958  6958 V BluetoothSapService: Sap Service closeSapService in
08-05 09:54:49.341  6958  6958 V BluetoothSapService: Close listen Socket : 
08-05 09:54:49.341  6958  6958 V BluetoothSapService: Close rfcomm Socket : 
08-05 09:54:49.341  6958  6958 V BluetoothSapService: Close sapd  Socket : 
08-05 09:54:49.345  6958  6958 V BluetoothSapService: Sap Service closeSapService out
08-05 09:54:49.345  6958  6958 V BluetoothSapService: Sap Service onDestroy
08-05 09:54:49.345  6958  6958 V BluetoothSapService: Sap Service closeSapService in
08-05 09:54:49.345  6958  6958 V BluetoothSapService: Close listen Socket : 
08-05 09:54:49.345  6958  6958 V BluetoothSapService: Close rfcomm Socket : 
08-05 09:54:49.345  6958  6958 V BluetoothSapService: Close sapd  Socket : 
08-05 09:54:49.346  6958  6958 V BluetoothSapService: Sap Service closeSapService out
,08-05 09:54:49.981  6958  7416 D bt_hci_bdroid: cleanup
,08-05 09:54:49.989  6958  7484 I bt_lpm  : LPM is already off!!!
08-05 09:54:49.990  6958  7511 I bt_userial_mct: exiting userial_read_thread
08-05 09:54:49.990  6958  7511 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 09:54:49.991  6958  7482 W bt-btif : ag scb idx 1 not allocated
08-05 09:54:49.991  6958  7482 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-05 09:54:49.991  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 09:54:49.992  6958  7482 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-05 09:54:49.992  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 09:54:49.992  6958  7482 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 09:54:49.992  6958  7482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 09:54:49.992  6958  7482 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 09:54:49.992  6958  7482 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 09:54:49.995  6958  7416 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 09:54:49.997  6958  7484 I bt_vendor: hw_epilog_process
08-05 09:54:49.998  6958  7416 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 09:54:49.998  6958  7416 D bt_userial_mct: userial_close
08-05 09:54:49.998  6958  7416 E bt_userial_mct: pthread_join() FAILED result:3
08-05 09:54:49.998  6958  7416 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 09:54:50.006  6958  7416 D bt_hci_bdroid: set_power 0
08-05 09:54:50.006  6958  7416 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 09:54:50.006  6958  7416 I bt_vendor: bluetooth satus is on
08-05 09:54:50.006  6958  7416 I bt_vendor: bt-vendor : resetting BT status
08-05 09:54:50.006  6958  7416 I bt_vendor: Starting hciattach daemon
08-05 09:54:50.006  6958  7416 I bt_vendor: try to set false
,08-05 09:54:50.012  6958  7416 I bt_vendor: Starting hciattach daemon
08-05 09:54:50.014  6958  7416 I bt_vendor: try to set false
08-05 09:54:50.015  6958  7416 I bt_vendor: cleanup
08-05 09:54:50.016  6958  7482 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 09:54:50.016  6958  7416 I GKI_LINUX: GKI_exit_task 0 done
08-05 09:54:50.016  6958  7416 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 09:54:50.018  6958  7412 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 09:54:50.022  6958  6958 D HeadsetService: Received stop request...Stopping profile...
,08-05 09:54:50.026  6958  6958 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 09:54:50.026  6958  6958 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 09:54:50.026  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:50.027  6958  7435 D HeadsetStateMachine: Exit Disconnected: -1
08-05 09:54:50.033  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-05 09:54:50.033  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 09:54:50.035  6958  6958 D A2dpService: Received stop request...Stopping profile...
,08-05 09:54:50.037  6958  7474 D A2dpStateMachine: Exit Disconnected: -1
08-05 09:54:50.040  6958  7412 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 09:54:50.040  6958  6958 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 09:54:50.031  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-05 09:54:50.041  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-05 09:54:50.042  6958  6958 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 09:54:50.042  6958  6958 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 09:54:50.042  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:50.044  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-05 09:54:50.044  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 09:54:50.044  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-05 09:54:50.047  6958  6958 D HidService: Received stop request...Stopping profile...
08-05 09:54:50.047  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
,08-05 09:54:50.051  6958  6958 D HeadsetStateMachine: Unbinding service...
08-05 09:54:50.053  6958  6958 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 09:54:50.053  6958  6958 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 09:54:50.053  6958  6958 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 09:54:50.053  6958  6958 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 09:54:50.053  6958  6958 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 09:54:50.054  6958  6958 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 09:54:50.054  6958  6958 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 09:54:50.055  6958  6958 D HealthService: Received stop request...Stopping profile...
08-05 09:54:50.055  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:50.057  6958  6958 D PanService: Received stop request...Stopping profile...
08-05 09:54:50.058  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:50.059  6958  6958 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 09:54:50.062  6958  6958 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 09:54:50.062  6958  6958 D BtGatt.GattService: stop()
08-05 09:54:50.062  6958  6958 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 09:54:50.063  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:50.066  6958  6958 D BluetoothMapService: Received stop request...Stopping profile...
08-05 09:54:50.066  6958  6958 D BluetoothMapService: stop()
08-05 09:54:50.066  6958  6958 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 09:54:50.067  6958  6958 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 09:54:50.067  6958  6958 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31baeeec
08-05 09:54:50.068  6958  6958 I BluetoothA2dpServiceJni: cleanupNative
08-05 09:54:50.069  6958  7475 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 09:54:50.069  6958  6958 I GKI_LINUX: GKI_exit_task 2 done
08-05 09:54:50.069  6958  6958 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 09:54:50.069  6958  6958 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 09:54:50.070  6958  6958 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 09:54:50.070  6958  6958 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 09:54:50.070  6958  6958 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 09:54:50.070  6958  6958 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 09:54:50.071  6958  6958 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 09:54:50.071  6958  6958 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-05 09:54:50.074  6958  6958 V BluetoothMapService: Handler(): got msg=4
08-05 09:54:50.074  6958  6958 D BluetoothMapService: MAP Service closeService in
08-05 09:54:50.074  6958  6958 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 09:54:50.074  6958  6958 V BluetoothMapService: MAP Service closeService out
08-05 09:54:50.076  6958  7412 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 09:54:50.076  6958  7412 D BluetoothAdapterProperties: Setting state to 10
08-05 09:54:50.076  6958  7412 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 09:54:50.079  1037  1119 D BluetoothManagerService: Message: 60
08-05 09:54:50.079  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 09:54:50.079  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-05 09:54:50.079  6958  7412 I BluetoothAdapterState: Entering OffState
08-05 09:54:50.081  6958  6958 D BluetoothMapService: cleanup()
08-05 09:54:50.081  6958  6958 D BluetoothMapService: MAP Service closeService in
08-05 09:54:50.081  6958  6958 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 09:54:50.081  6958  6958 V BluetoothMapService: MAP Service closeService out
08-05 09:54:50.083  6796  6820 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 09:54:50.087  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 09:54:50.087  1836  2425 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 09:54:50.089  6796  6820 D BluetoothPan: onBluetoothStateChange on: false
08-05 09:54:50.090  6796  6820 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 09:54:50.090  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 09:54:50.090  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 09:54:50.091  6796  6820 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 09:54:50.091  6796  6820 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 09:54:50.092  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 09:54:50.093  6796  6820 D BluetoothMap: onBluetoothStateChange: up=false
08-05 09:54:50.093  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 09:54:50.094  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 09:54:50.096  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 09:54:50.096  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 09:54:50.096  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@38703ef4 mBinding = false
,08-05 09:54:50.098  1037  1119 D BluetoothManagerService: Sending unbind request.
08-05 09:54:50.103  6958  7416 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-05 09:54:50.104  6958  6958 I GKI_LINUX: GKI_exit_task 1 done
08-05 09:54:50.104  6958  6958 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 09:54:50.105  6958  6958 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 09:54:50.105  6958  6958 I art     : --- WEIRD: removing null entry 248
08-05 09:54:50.105  6958  6958 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-05 09:54:50.105  6958  6958 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 09:54:50.106  6958  6958 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 09:54:50.107  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-05 09:54:50.111  6958  6958 I art     : System.exit called, status: 0
08-05 09:54:50.111  6958  6958 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 09:54:50.130   322  1388 V AudioFlinger: 6958 died, releasing its sessions
08-05 09:54:50.130   322  1388 V AudioFlinger:  pid 1836 @ 0
08-05 09:54:50.131   322  1388 V AudioFlinger:  pid 3493 @ 1
08-05 09:54:50.131   322  1388 V AudioFlinger:  pid 3493 @ 2
,08-05 09:54:50.134  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-05 09:54:50.134  1925  2110 D LGBluetoothAPIService: Message: 101
08-05 09:54:50.134  1925  2110 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-05 09:54:50.141  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-05 09:54:50.142  1925  2110 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-05 09:54:50.142  1925  2110 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-05 09:54:50.235  1037  1870 I ActivityManager: Process com.android.bluetooth (pid 6958) has died
,08-05 09:54:50.236  1037  1870 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-05 09:54:50.236  1037  1870 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-05 09:54:50.245  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:50.246  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 09:54:50.247  1925  2110 D LGBluetoothAPIService: Message: 2
08-05 09:54:50.247  1925  2110 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-05 09:54:50.252  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:50.253  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-05 09:54:50.253  6796  6796 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 09:54:50.254  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:50.255  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 09:54:50.262  1588  1588 D BluetoothAdapter: 471803030: getState() :  mService = null. Returning STATE_OFF
,08-05 09:54:50.262  1588  1588 D BluetoothAdapter: 471803030: getState() :  mService = null. Returning STATE_OFF
08-05 09:54:50.341  1037  1941 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7655 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-05 09:54:50.344  6796  6796 D DockEventReceiver: finishStartingService: stopping service
,08-05 09:54:50.438  7655  7655 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-05 09:54:50.438  7655  7655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 09:54:50.439  7655  7655 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 09:54:50.440  7655  7655 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 09:54:50.461  7655  7655 D BluetoothAdapterApp: Loading JNI Library
,08-05 09:54:50.497  7655  7655 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2bfc954 Instance Count = 1
,08-05 09:54:50.504  7655  7655 D BluetoothAdapterApp: onCreate
08-05 09:54:50.529  7655  7655 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 09:54:50.529  7655  7655 D ProfileConfigQcom: Adding HeadsetService
08-05 09:54:50.530  7655  7655 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 09:54:50.530  7655  7655 D ProfileConfigQcom: Adding A2dpService
08-05 09:54:50.530  7655  7655 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 09:54:50.530  7655  7655 D ProfileConfigQcom: Adding HidService
08-05 09:54:50.530  7655  7655 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-05 09:54:50.531  7655  7655 D ProfileConfigQcom: Adding HealthService
08-05 09:54:50.531  7655  7655 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 09:54:50.532  7655  7655 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 09:54:50.532  7655  7655 D ProfileConfigQcom: Adding PanService
08-05 09:54:50.532  7655  7655 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 09:54:50.532  7655  7655 D ProfileConfigQcom: Adding GattService
08-05 09:54:50.533  7655  7655 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 09:54:50.533  7655  7655 D ProfileConfigQcom: Adding BluetoothMapService
08-05 09:54:50.533  7655  7655 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 09:54:50.534  7655  7655 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 09:54:50.535  7655  7655 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:50.535  7655  7655 V BluetoothPbapReceiver: ***********state = 10
08-05 09:54:50.537  7655  7655 V LGMDMManagerInternal: Create singleton instance
08-05 09:54:50.618  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 09:54:50.627  7655  7655 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 09:54:50.627  7655  7655 D LGBluetoothAPIServer: [BTUI] onBind()
08-05 09:54:50.627  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 09:54:50.629  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 09:54:50.629  1925  2110 D LGBluetoothAPIService: Message: 100
08-05 09:54:50.629  1925  2110 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 09:54:50.635  6796  6796 D BluetoothPermissionRequest: onReceive
08-05 09:54:50.636  6796  6796 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 09:54:50.636  6796  6796 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-05 09:54:50.639  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 09:54:50.642  7655  7655 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 09:54:50.645  7655  7655 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:50.647  7655  7655 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 09:54:50.648  7655  7655 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 09:54:50.648  7655  7655 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 09:54:50.649  7655  7655 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:50.650  7655  7655 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-05 09:54:50.654  6890  6890 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-05 09:54:52.008  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 09:54:52.011  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:52.062  1037  1367 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 09:54:52.070  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-05 09:54:52.153  1037  1037 D administrator: Handling package changes for user 0
,08-05 09:54:52.172  1037  1112 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7685 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 09:54:52.180  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-05 09:54:52.181  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-05 09:54:52.205  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 09:54:52.242  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:54:52.261  7685  7685 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 09:54:52.293  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-05 09:54:52.293  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 09:54:52.346  7685  7685 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:54:52.346  7685  7685 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 09:54:52.354  1037  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:54:52.362  1037  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-05 09:54:52.371  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-05 09:54:52.374  2487  2487 V GmsNetworkLocationProvi: DISABLE
08-05 09:54:52.400  1037  1109 D LocationProviderProxy: applying state to connected service
,08-05 09:54:52.403  2487  2487 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-05 09:54:52.449  7685  7729 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 09:54:52.450  7685  7729 I Babel   : MmsConfig.loadMmsSettings
,08-05 09:54:52.453  7685  7729 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 09:54:52.453  7685  7729 I Babel   : MmsConfig.loadFromDatabase
,08-05 09:54:52.466  7685  7729 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 09:54:52.466  7685  7729 I Babel   : MmsConfig.loadFromResources
08-05 09:54:52.478  7685  7729 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-05 09:54:52.480  7685  7729 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 09:54:52.495  7685  7685 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:54:52.498  7685  7728 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 09:54:52.500  7685  7728 W AudioCapabilities: Unsupported mime audio/qcelp
,08-05 09:54:52.501  7685  7728 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 09:54:52.522  7685  7728 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-05 09:54:52.523  1801  7733 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 09:54:52.523  1801  7733 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 09:54:52.523  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 09:54:52.529  7685  7728 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 09:54:52.532  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c457b3e
08-05 09:54:52.532  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 09:54:52.532  7008  7008 D AppUp4:CustFacade: isPhone : true
08-05 09:54:52.534  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-05 09:54:52.533  1801  4786 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-05 09:54:52.534  7008  7008 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 09:54:52.535  7685  7728 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 09:54:52.551  7685  7728 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-05 09:54:52.556  7685  7728 W VideoCapabilities: Unsupported mime video/divx
08-05 09:54:52.558  7685  7728 W VideoCapabilities: Unsupported mime video/divx311
08-05 09:54:52.560  7685  7728 W VideoCapabilities: Unsupported mime video/divx4
08-05 09:54:52.566  7685  7728 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-05 09:54:52.573  1037  1052 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7736 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-05 09:54:52.576  1037  1941 I ActivityManager: Killing 7035:com.lge.email/u0a23 (adj 15): empty #17
08-05 09:54:52.604  7685  7728 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 09:54:52.609  7685  7728 W AudioCapabilities: Unsupported mime audio/eac3
08-05 09:54:52.610  7685  7728 W AudioCapabilities: Unsupported mime audio/ac3
08-05 09:54:52.611  7685  7728 W AudioCapabilities: Unsupported mime audio/g726
08-05 09:54:52.611  7685  7728 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 09:54:52.612  7685  7728 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 09:54:52.613  7685  7728 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 09:54:52.614  7685  7728 W VideoCapabilities: Unsupported mime video/theora
08-05 09:54:52.616  7685  7728 W VideoCapabilities: Unsupported mime video/mjpg
,08-05 09:54:52.656  1037  1870 W libprocessgroup: failed to open /acct/uid_10023/pid_7035/cgroup.procs: No such file or directory
,08-05 09:54:52.696  7736  7736 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:54:52.697  7736  7736 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 09:54:52.697  7736  7736 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 09:54:52.698  7736  7736 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 09:54:52.699  7736  7736 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-05 09:54:52.782  7736  7736 I SystemConfig: BUILD Country: EU
08-05 09:54:52.782  7736  7736 I SystemConfig: BUILD Operator: OPEN
,08-05 09:54:52.826  1037  2015 I ActivityManager: Killing 6910:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-05 09:54:52.970  1037  1972 W libprocessgroup: failed to open /acct/uid_10026/pid_6910/cgroup.procs: No such file or directory
,08-05 09:54:52.979  7736  7754 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-05 09:54:52.979  7736  7754 I SystemConfig: existFile = false
08-05 09:54:52.980  7736  7754 I SystemConfig: canReadFile = false
08-05 09:54:52.980  7736  7754 I SystemConfig: systemFeature RCS result false
08-05 09:54:52.980  7736  7754 D SystemConfig: refreshRcsSupport() :false
08-05 09:54:53.017  1037  2015 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7759 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 09:54:53.069  1037  1428 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-05 09:54:53.089  7759  7759 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:54:53.089  7759  7759 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 09:54:53.089  7759  7759 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 09:54:53.090  7759  7759 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 09:54:53.193  7759  7759 I AppConfig: Total System Memory = 2995761152
,08-05 09:54:53.206  7759  7759 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-05 09:54:53.291  1037  1052 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7778 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 09:54:53.292  1037  1052 I ActivityManager: Killing 6433:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-05 09:54:53.357  1037  1972 W libprocessgroup: failed to open /acct/uid_1000/pid_6433/cgroup.procs: No such file or directory
,08-05 09:54:53.594  7778  7778 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 09:54:53.709  7778  7778 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:54:53.710  7778  7778 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 09:54:53.763  7778  7778 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 09:54:53.786  7778  7778 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 09:54:53.787  7778  7778 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 09:54:53.803  7778  7778 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 09:54:53.804  7778  7778 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-05 09:54:53.837  1037  1941 I ActivityManager: Killing 7077:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-05 09:54:53.894  1037  2016 W libprocessgroup: failed to open /acct/uid_10046/pid_7077/cgroup.procs: No such file or directory
,08-05 09:54:53.906  3532  3957 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 09:54:53.908  3532  3957 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@bdcf302 on behalf of 7778
08-05 09:54:53.918  7778  7778 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-05 09:54:53.927  4609  7819 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-05 09:54:53.941  7778  7778 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-05 09:54:53.972  1037  1921 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7821 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 09:54:54.000   380   380 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 464us total 28.207ms
,08-05 09:54:54.023   380   380 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 22.152ms
,08-05 09:54:54.045   380   380 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 457us total 21.086ms
08-05 09:54:54.092  7821  7821 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-05 09:54:54.121  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 09:54:54.122  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 09:54:54.122  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 09:54:54.122  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 09:54:54.122  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 09:54:54.122  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 09:54:54.146  1037  1921 I ActivityManager: Killing 7096:com.android.chrome/u0a57 (adj 15): empty #17
,08-05 09:54:54.176  1037  2015 W libprocessgroup: failed to open /acct/uid_10057/pid_7096/cgroup.procs: No such file or directory
,08-05 09:54:54.197  7568  7624 D UEI.SmartControl: Internal timer expired: 1
08-05 09:54:54.197  7568  7624 D UEI.SmartControl: unbind internal service
,08-05 09:54:54.399  1037  1870 V SIM_STK : Menu title from STK is T-Mobile
,08-05 09:54:54.420  4609  7819 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 494 ms] updated apps [took 494 ms] 
,08-05 09:54:54.490  7568  7621 D serial_port: close(fd = 25)
,08-05 09:54:54.500  7568  7621 I UEI.SmartControl: Serial port is closed.
,08-05 09:54:55.018  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:55.018  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b74610 added. We now have 6 listener(s)
08-05 09:54:55.018  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 09:54:55.028  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:55.028  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ac1e509 added. We now have 7 listener(s)
08-05 09:54:55.028  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:55.029  6709  6778 I System.out: IsBluetoothEnabled
08-05 09:54:55.030  1037  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:55.030  1037  1941 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-05 09:54:55.031  1037  1119 D BluetoothManagerService: Message: 2
08-05 09:54:55.034  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:55.036  1037  1708 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:55.036  1037  1708 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 09:54:55.054  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 09:54:55.055  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 09:54:55.055  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-05 09:54:55.055  1037  1119 D BluetoothManagerService: Message: 1
08-05 09:54:55.056  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 09:54:55.081  1037  1119 D BluetoothManagerService: Message: 20
08-05 09:54:55.081  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34fc8e12:true
,08-05 09:54:55.085  7655  7655 D BluetoothAdapterState: make
08-05 09:54:55.090  7655  7655 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 09:54:55.090  7655  7655 I bluedroid-qcom: init
08-05 09:54:55.091  7655  7863 I BluetoothAdapterState: Entering OffState
08-05 09:54:55.092  7655  7655 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 09:54:55.092  7655  7655 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 09:54:55.092  7655  7655 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 09:54:55.092  7655  7655 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 09:54:55.092  7655  7655 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 09:54:55.094  7655  7655 I bluedroid-qcom: get_profile_interface socket
08-05 09:54:55.094  7655  7655 I bluedroid-qcom: get_profile_interface map_client
,08-05 09:54:55.098  7655  7867 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 09:54:55.090  7866  7866 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:55.090  7866  7866 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:55.107  7655  7867 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 09:54:55.116  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 09:54:55.116  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 09:54:55.118  7655  7867 D BluetoothAdapterProperties: Name is: G3
08-05 09:54:55.119  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 09:54:55.119  1037  1119 D BluetoothManagerService: Message: 40
08-05 09:54:55.119  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,08-05 09:54:55.122  7866  7866 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 09:54:55.122  7866  7866 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 09:54:55.122  7866  7866 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 09:54:55.123  7655  7671 I bluedroid-qcom: config_hci_snoop_log
08-05 09:54:55.124  7866  7866 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 09:54:55.127  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 09:54:55.127  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 09:54:55.128  7866  7866 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 09:54:55.128  7866  7866 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 09:54:55.137  7655  7863 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 09:54:55.137  7655  7863 D BluetoothAdapterProperties: Setting state to 11
08-05 09:54:55.137  7655  7863 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-05 09:54:55.140  1037  1119 D BluetoothManagerService: Message: 60
08-05 09:54:55.141  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 09:54:55.141  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 09:54:55.142  7655  7863 I LGBluetoothServiceJni: classInitNative: succeeds
08-05 09:54:55.146  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:55.147  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 09:54:55.152  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-05 09:54:55.158  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:55.161  7655  7655 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-05 09:54:55.162  7655  7655 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:55.162  7655  7655 V BluetoothPbapReceiver: ***********state = 11
08-05 09:54:55.177  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 09:54:55.190  7655  7863 D BluetoothBondStateMachine: make
08-05 09:54:55.193  7655  7863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:55.193  7655  7863 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 09:54:55.193  7655  7863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:55.193  7655  7863 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 09:54:55.194  7655  7863 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 09:54:55.195  7655  7879 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-05 09:54:55.200  7655  7863 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:55.203  6796  6796 D BluetoothPermissionRequest: onReceive
08-05 09:54:55.209  7655  7655 D HeadsetService: Received start request. Starting profile...
08-05 09:54:55.210  7655  7655 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 09:54:55.210  7655  7655 D LGBluetoothHfpAdapter: Version 1.6
08-05 09:54:55.213  7655  7655 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-05 09:54:55.213  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 09:54:55.214  7655  7655 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 09:54:55.215  7655  7655 D HeadsetStateMachine: make
08-05 09:54:55.217  7655  7863 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:55.224  7655  7863 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:55.229  7655  7863 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 09:54:55.234  7655  7863 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 09:54:55.238  7655  7863 E BluetoothAdapterService: File transfer profiles supported!!
08-05 09:54:55.242  7655  7863 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 09:54:55.253  7655  7863 V LGMDMManager: Create singleton instance
,08-05 09:54:55.254  7655  7655 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:54:55.254  7655  7655 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 09:54:55.255  7655  7863 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 09:54:55.259  7655  7655 D HeadsetStateMachine: max_hf_connections = 1
08-05 09:54:55.259  7655  7655 I bluedroid-qcom: get_profile_interface handsfree
08-05 09:54:55.261  7655  7655 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 09:54:55.262   322  1388 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 1002
08-05 09:54:55.262   322  1387 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 09:54:55.262   322  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 09:54:55.262   322  1387 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 09:54:55.262  7655  7655 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 09:54:55.262   322   322 V AudioFlinger: registerClient() client 0xb55816b8, pid 7655
08-05 09:54:55.263   322  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:55.263   322  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 09:54:55.263  1037  1941 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:55.263  1037  1941 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 09:54:55.263   322  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:55.263   322  1381 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:55.263  1836  4437 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:55.263  1836  4437 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 09:54:55.263  1836  4437 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:55.263  1836  4437 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:55.263  1037  1560 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:55.263  7655  7672 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:55.263  1037  1560 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:55.263  7655  7672 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 09:54:55.263  7655  7672 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:55.263  7655  7672 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 09:54:55.264  1588  2525 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:55.264  1588  2525 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 09:54:55.264  1588  2525 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:55.264  1588  2525 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:55.264  3493  3512 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 09:54:55.264  3493  3512 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 09:54:55.264  3493  3512 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 09:54:55.264  3493  3512 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 09:54:55.264  7655  7655 V ToneGenerator: Create Track: 0xb4928080
08-05 09:54:55.264  7655  7655 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 09:54:55.264  7655  7655 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 09:54:55.264   322  1388 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 09:54:55.264   322  1388 V AudioPolicyManager: getOutputForAttr() device 2, samplingRat,e 0, format 0, channelMask 3, flags 0
08-05 09:54:55.264   322  1388 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 09:54:55.264   322  1388 V AudioPolicyManagerEx: getOutput() returns output 2
,08-05 09:54:55.265   322  1387 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 09:54:55.265   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 09:54:55.265   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
,08-05 09:54:55.265   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 09:54:55.265   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 09:54:55.265  7655  7655 V AudioSystem: getLatency() output 2, latency 50
08-05 09:54:55.265  7655  7655 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 09:54:55.265  7655  7655 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 09:54:55.269   322  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 09:54:55.269   322  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 09:54:55.269   322  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 09:54:55.269   322  2138 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 09:54:55.269   322  2138 V AudioFlinger: createTrack() lSessionId: 21
08-05 09:54:55.269  7655  7655 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 09:54:55.270   322  1388 V AudioFlinger: acquiring 21 from 7655, for 7655
08-05 09:54:55.270   322  1388 V AudioFlinger:  added new entry for 21
08-05 09:54:55.270  7655  7655 V ToneGenerator: ToneGenerator INIT OK, time: 345255
08-05 09:54:55.270  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:55.271  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:55.273  7655  7881 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 09:54:55.273  7655  7655 D A2dpService: Received start request. Starting profile...
08-05 09:54:55.273  7655  7881 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 09:54:55.274  7655  7881 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 09:54:55.274  7655  7655 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 09:54:55.275  7655  7655 V Avrcp   : make
08-05 09:54:55.276  7655  7655 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 09:54:55.276  7655  7655 I bluedroid-qcom: get_profile_interface avrcp
08-05 09:54:55.277  7655  7881 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 09:54:55.277   322  1387 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7655
08-05 09:54:55.277   322  1387 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 09:54:55.277   322  1387 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 09:54:55.277   322  1387 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 09:54:55.277   322  1387 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 09:54:55.277   322  1387 V voice   : voice_set_parameters: exit with code(0)
08-05 09:54:55.277   322  1387 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 09:54:55.277   322  1387 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 09:54:55.278   322  1387 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 09:54:55.278   322  1387 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
,08-05 09:54:55.278   322  1387 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 09:54:55.278   322  1387 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 09:54:55.278  7655  7881 V ToneGenerator: ToneGenerator destructor
08-05 09:54:55.278  7655  7881 V ToneGenerator: stopTone
08-05 09:54:55.278  7655  7881 V ToneGenerator: Delete Track: 0xb4928080
08-05 09:54:55.278   322   322 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 09:54:55.278   322   322 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 09:54:55.278   322  1264 V AudioPolicyService: AudioCommandThread() waking up
08-05 09:54:55.278   322  1264 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 09:54:55.278   322  1264 V AudioPolicyManager: releaseOutput() 2
08-05 09:54:55.278   322  1264 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 09:54:55.278   322   322 V AudioFlinger: PlaybackThread::Track destructor
08-05 09:54:55.279   322   322 V AudioFlinger: removeClient_l() pid 7655, calling pid 322
08-05 09:54:55.280  7655  7881 V AudioTrack: ~AudioTrack, releasing session id from 7655 on behalf of 7655
08-05 09:54:55.280   322  1387 V AudioFlinger: releasing 21 from 7655 for 7655
08-05 09:54:55.280   322  1387 V AudioFlinger:  decremented refcount to 0
08-05 09:54:55.280   322  1387 V AudioFlinger: purging stale effects
08-05 09:54:55.290  7655  7655 V AudioManager: registerRemoteController: size of Media player list: 0
,08-05 09:54:55.293  7655  7655 E AudioManager: No RCC entry present to update
08-05 09:54:55.293  7655  7655 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 09:54:55.298  7655  7655 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 09:54:55.300  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 09:54:55.301  7655  7655 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 09:54:55.305  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-05 09:54:55.459  1037  1972 V SIM_STK : Menu title from STK is T-Mobile
08-05 09:54:55.459  1037  1972 V SIM_STK : Menu title from STK is T-Mobile
,08-05 09:54:55.591  1037  1921 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 09:54:55.604  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-05 09:54:55.611  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-05 09:54:55.612  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-05 09:54:55.612  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 09:54:55.612  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 09:54:55.612  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 09:54:55.612  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 09:54:55.612  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 09:54:55.612  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 09:54:55.613  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 09:54:55.613  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-05 09:54:55.613  7655  7655 I BluetoothA2dpServiceJni: classInitNative,
08-05 09:54:55.613  7655  7655 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-05 09:54:55.614  7655  7655 D A2dpStateMachine: make
,08-05 09:54:55.615  7655  7655 I bluedroid-qcom: get_profile_interface a2dp
,08-05 09:54:55.615  7655  7890 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting,
,08-05 09:54:55.619  7655  7655 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 09:54:55.619  7655  7655 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 09:54:55.620  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:55.621  7655  7889 D A2dpStateMachine: Enter Disconnected: -2
08-05 09:54:55.621  7655  7655 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 09:54:55.624  7655  7655 D HidService: Received start request. Starting profile...
,08-05 09:54:55.624  7655  7655 I bluedroid-qcom: get_profile_interface hidhost
08-05 09:54:55.624  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:55.625  7655  7655 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 09:54:55.627  7655  7655 D HealthService: Received start request. Starting profile...
08-05 09:54:55.629  7655  7655 I bluedroid-qcom: get_profile_interface health
08-05 09:54:55.629  7655  7655 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 09:54:55.629  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:55.631  7655  7655 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 09:54:55.633  7655  7655 D PanService: Received start request. Starting profile...
08-05 09:54:55.633  7655  7655 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 09:54:55.633  7655  7655 I bluedroid-qcom: get_profile_interface pan
08-05 09:54:55.641  7655  7655 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 09:54:55.642  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:55.643  7655  7655 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-05 09:54:55.650  7655  7655 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 09:54:55.650  7655  7655 D BtGatt.GattService: Received start request. Starting profile...
08-05 09:54:55.651  7655  7655 D BtGatt.GattService: start()
08-05 09:54:55.651  7655  7655 I bluedroid-qcom: get_profile_interface gatt
08-05 09:54:55.651  7655  7655 D BtGatt.AdvertiseManager: advertise manager created
08-05 09:54:55.660  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
,08-05 09:54:55.662  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:55.663  7655  7655 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 09:54:55.664  7655  7655 V BluetoothMapService: BluetoothMapBinder()
08-05 09:54:55.665  7655  7655 D BluetoothMapService: Received start request. Starting profile...
08-05 09:54:55.665  7655  7655 D BluetoothMapService: start()
08-05 09:54:55.668  7655  7655 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 09:54:55.668  7655  7655 D BluetoothMapEmailAppObserver: createReceiver()
08-05 09:54:55.670  7655  7655 D BluetoothMapEmailAppObserver: initObservers()
08-05 09:54:55.670  7655  7655 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 09:54:55.679  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
,08-05 09:54:55.680  7655  7655 D HeadsetStateMachine: Proxy object connected
,08-05 09:54:55.681  7655  7655 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 09:54:55.681  7655  7655 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 09:54:55.686  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 09:54:55.686  7655  7881 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 09:54:55.686  7655  7881 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 09:54:55.687  7655  7881 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 09:54:55.688  7655  7655 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:55.693  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 09:54:55.697  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 09:54:55.700  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 09:54:55.703  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 09:54:55.703  7655  7655 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 09:54:55.706  7655  7655 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 09:54:55.706  7655  7655 V BluetoothMapService: Handler(): got msg=1
,08-05 09:54:55.708  7655  7863 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 09:54:55.708  7655  7863 I bluedroid-qcom: enable
08-05 09:54:55.708  7655  7863 I bt_hci_bdroid: init
08-05 09:54:55.709  7655  7897 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 09:54:55.709  7655  7655 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 09:54:55.710  7655  7863 I bt_vendor: bt-vendor : init
08-05 09:54:55.710  7655  7863 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 09:54:55.710  7655  7863 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 09:54:55.710  7655  7863 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 09:54:55.710  7655  7863 D bt_userial_mct: userial_init
08-05 09:54:55.710  7655  7897 I bt-btu  : btu_task pending for preload complete event
08-05 09:54:55.710  7655  7655 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 09:54:55.710  7655  7655 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 09:54:55.710  7655  7863 D bt_hci_bdroid: set_power 1
08-05 09:54:55.710  7655  7863 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 09:54:55.710  7655  7863 I bt_vendor: Starting hciattach daemon
08-05 09:54:55.710  7655  7863 I bt_vendor: try to set true
08-05 09:54:55.710  7655  7655 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:55.710  7655  7655 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 09:54:55.700  7900  7900 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:55.700  7900  7900 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:55.735  7901  7901 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 09:54:55.799  7907  7907 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 09:54:55.825  7908  7908 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 09:54:55.862  7910  7910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 09:54:55.883  7911  7911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 09:54:55.897  7912  7912 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 09:54:55.909  7913  7913 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-05 09:54:55.948  7915  7915 I libmdmdetect: ESOC framework not supported
,08-05 09:54:55.949  7915  7915 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-05 09:54:55.957  7915  7915 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 09:54:55.957  7915  7915 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 09:54:55.957  7915  7915 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 09:54:55.957  7915  7915 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 09:54:55.957  7915  7915 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 09:54:55.957  7915  7915 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 09:54:55.957  7915  7915 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 09:54:55.998  7915  7916 E QC-QMI  : qmi_client [7915] 15: failed to locate client data
08-05 09:54:55.999   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 09:54:55.999   468   468 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-05 09:54:56.031  7917  7917 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 09:54:56.057  7918  7918 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 09:54:56.115  7655  7863 I bt_vendor: bluetooth satus is on
,08-05 09:54:56.115  7655  7863 D bt_hci_bdroid: preload
08-05 09:54:56.116  7655  7899 D bt_userial_mct: userial_open(port:0)
08-05 09:54:56.116  7655  7899 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-05 09:54:56.122  7655  7899 I bt_vendor: Done intiailizing UART
08-05 09:54:56.126  7655  7899 I bt_vendor: Done intiailizing UART
,08-05 09:54:56.126  7655  7899 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 09:54:56.127  7655  7899 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 09:54:56.128  7655  7897 I bt-btu  : btu_task received preload complete event
,08-05 09:54:56.129  7655  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 09:54:56.129  7655  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 09:54:56.132  7655  7920 D bt_userial_mct: Entering userial_read_thread()
,08-05 09:54:56.137  7655  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-05 09:54:56.141  7655  7897 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 09:54:56.141  7655  7897 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 09:54:56.142  7655  7897 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 09:54:56.201  7655  7897 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 09:54:56.201  7655  7897 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a3061 
08-05 09:54:56.201  7655  7897 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a3061 
,08-05 09:54:56.231  7655  7867 E bt-btif : Calling BTA_HhEnable
08-05 09:54:56.232  7655  7867 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 09:54:56.232  7655  7867 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 09:54:56.238  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 09:54:56.239  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 09:54:56.239  7655  7867 D BluetoothAdapterProperties: Name is: G3
08-05 09:54:56.241  7655  7867 D BluetoothAdapterProperties: Scan Mode:20
08-05 09:54:56.241  7655  7867 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 09:54:56.241  7655  7867 D bt_hci_bdroid: postload
08-05 09:54:56.243  7655  7867 D bte_conf: Device ID record 1 : primary
08-05 09:54:56.243  7655  7867 D bte_conf:   vendorId            = 00c4
08-05 09:54:56.243  7655  7867 D bte_conf:   vendorIdSource      = 0001
08-05 09:54:56.243  7655  7867 D bte_conf:   product             = 13a1
08-05 09:54:56.243  7655  7867 D bte_conf:   version             = 1000
08-05 09:54:56.243  7655  7867 D bte_conf:   clientExecutableURL = 
08-05 09:54:56.243  7655  7867 D bte_conf:   serviceDescription  = 
08-05 09:54:56.243  7655  7867 D bte_conf:   documentationURL    = 
08-05 09:54:56.244  7655  7899 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 09:54:56.244  7655  7867 D bte_conf: bte_load_did_conf no section named DID2.
08-05 09:54:56.246  7655  7899 D bt_hci_bdroid: Used up Tx Cmd credits
,08-05 09:54:56.256  7655  7863 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 09:54:56.256  7655  7863 D BluetoothAdapterProperties: ScanMode =  20
08-05 09:54:56.256  7655  7863 D BluetoothAdapterProperties: State =  11
08-05 09:54:56.256  7655  7863 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 09:54:56.257  7655  7863 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 09:54:56.257  7655  7863 D BluetoothAdapterProperties: Setting state to 12
08-05 09:54:56.257  7655  7863 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 09:54:56.258  7655  7867 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 09:54:56.250  7925  7925 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 09:54:56.260  7925  7925 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:56.268  1037  1119 D BluetoothManagerService: Message: 60
08-05 09:54:56.268  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 09:54:56.268  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-05 09:54:56.269  7655  7920 E bt_mct  : hci lib postload completed
08-05 09:54:56.287  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:56.287  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:56.287  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:56.287  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:56.287  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:56.287  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:56.287  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:56.287  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 09:54:56.297  7655  7863 I BluetoothAdapterState: Entering On State
08-05 09:54:56.302  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 09:54:56.304  7655  7867 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 09:54:56.305  7655  7867 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 09:54:56.316  7655  7863 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 09:54:56.316  7655  7863 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 09:54:56.316  7655  7863 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-05 09:54:56.323  7655  7863 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 09:54:56.323  6796  6817 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 09:54:56.331  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 09:54:56.338  1037  1037 D BluetoothA2dp: Proxy object connected
08-05 09:54:56.345  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 09:54:56.347  7655  7863 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 09:54:56.366  1836  1836 D BluetoothHeadset: Proxy object connected
08-05 09:54:56.366  6796  6796 D BluetoothHeadset: Proxy object connected
08-05 09:54:56.366  6796  6796 D HeadsetProfile: Bluetooth service connected
,08-05 09:54:56.369  7655  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 09:54:56.369  7655  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 09:54:56.369  7655  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 09:54:56.370  7655  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 09:54:56.370  7655  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 09:54:56.370  6796  6817 D BluetoothPan: onBluetoothStateChange on: true
08-05 09:54:56.370  6796  6817 D BluetoothPan: onBluetoothStateChange call bindService
08-05 09:54:56.370  7655  7897 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 09:54:56.370  7655  7867 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 09:54:56.373  6796  6820 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 09:54:56.375  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 09:54:56.376  1037  1037 D BluetoothHeadset: Proxy object connected
08-05 09:54:56.377  1836  4437 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 09:54:56.379  6796  6796 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 09:54:56.379  6796  6796 D PanProfile: Bluetooth service connected
08-05 09:54:56.380  1836  1836 D BluetoothHeadset: Proxy object connected
08-05 09:54:56.380  6796  6817 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 09:54:56.385  7655  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 09:54:56.385  7655  7897 W bt-smp  : Plain text(LSB ~ MSB) = cb e8 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:56.385  7655  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = 69 41 c4 b4 f3 2f 60 17 84 52 38 4f 29 9b 69 19 
08-05 09:54:56.385  7655  7897 W bt-btm  : Stopping oneshot timer
,08-05 09:54:56.388  7939  7939 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-05 09:54:56.389  6796  6796 D BluetoothA2dp: Proxy object connected
08-05 09:54:56.390  6796  6796 D A2dpProfile: Bluetooth service connected
08-05 09:54:56.390  6796  6820 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-05 09:54:56.392  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 09:54:56.393  6796  6796 D BluetoothInputDevice: Proxy object connected
08-05 09:54:56.393  6796  6796 D HidProfile: Bluetooth service connected
08-05 09:54:56.395  1836  1836 D BluetoothHeadset: Proxy object connected
08-05 09:54:56.396  6796  7312 D BluetoothMap: onBluetoothStateChange: up=true
08-05 09:54:56.398  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 09:54:56.398  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 09:54:56.399  6796  6796 D BluetoothMap: Proxy object connected
08-05 09:54:56.399  6796  6796 D MapProfile: Bluetooth service connected
08-05 09:54:56.400  6796  6796 D BluetoothMap: getConnectedDevices()
,08-05 09:54:56.400  7655  7672 V BluetoothMapService: getConnectedDevices()
08-05 09:54:56.401  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 09:54:56.402  1037  1119 D BluetoothManagerService: Message: 40
08-05 09:54:56.402  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 09:54:56.403  7655  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 09:54:56.403  7655  7897 W bt-smp  : Plain text(LSB ~ MSB) = 90 41 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:56.403  7655  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = ed 07 ea 71 e5 3d 51 76 2d 81 d3 a5 30 07 bf b8 
08-05 09:54:56.403  7655  7897 W bt-btm  : Stopping oneshot timer
08-05 09:54:56.405  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 09:54:56.407  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:56.408  1925  2110 D LGBluetoothAPIService: Message: 1
08-05 09:54:56.408  1925  2110 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 09:54:56.408  1925  2110 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-05 09:54:56.408  1925  2110 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-05 09:54:56.408  7655  7655 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:56.408  7655  7655 D BluetoothMapService: STATE_ON
08-05 09:54:56.411  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 09:54:56.417  7655  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 09:54:56.417  7655  7897 W bt-smp  : Plain text(LSB ~ MSB) = d3 2d 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:56.417  7655  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = dc 06 e5 cb 52 da 53 b1 5f 72 7d 6f da 3d bd 77 
08-05 09:54:56.417  7655  7897 W bt-btm  : Stopping oneshot timer
08-05 09:54:56.418  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 09:54:56.419  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 09:54:56.420  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:56.420  7655  7655 V BluetoothPbapService: Pbap Service onCreate
08-05 09:54:56.420  7655  7655 V BluetoothPbapService: Starting PBAP service
08-05 09:54:56.424  7655  7655 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-05 09:54:56.424  6796  6796 D DockEventReceiver: finishStartingService: stopping service
08-05 09:54:56.425  7655  7655 V BluetoothMapService: Handler(): got msg=1
08-05 09:54:56.425  7655  7655 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 09:54:56.426  7655  7655 V BluetoothPbapService: Pbap Service onBind
08-05 09:54:56.426  7655  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 09:54:56.427  7655  7897 W bt-smp  : Plain text(LSB ~ MSB) = c6 67 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:56.427  7655  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = 9a 70 44 31 3d 58 dd 6c c6 aa 46 8f 04 a3 ff fc 
08-05 09:54:56.427  7655  7897 W bt-btm  : Stopping oneshot timer
08-05 09:54:56.427  7655  7946 D BluetoothMapMasInstance: MAS initSocket()
08-05 09:54:56.427  7655  7946 D BluetoothMapMasInstance:   masId = 00
08-05 09:54:56.427  7655  7946 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 09:54:56.427  7655  7946 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 09:54:56.427  7655  7946 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 09:54:56.429  1037  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:56.429  6796  6796 D BluetoothPbap: Proxy object connected
08-05 09:54:56.429  6796  6796 D PbapServerProfile: Bluetooth service connected
08-05 09:54:56.429  7655  7655 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:56.429  7655  7655 V BluetoothPbapService: state: 12
08-05 09:54:56.429  7655  7655 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 09:54:56.429  7655  7655 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:56.430  7655  7655 V BluetoothPbapReceiver: ***********state = 12
08-05 09:54:56.430  7655  7946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:56.431  7655  7946 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 09:54:56.431  7655  7946 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 09:54:56.431  7655  7946 D BluetoothMapMasInstance: Accepting socket connection...
08-05 09:54:56.433  7655  7867 D BluetoothAdapterProperties: Scan Mode:21
08-05 09:54:56.433  7655  7867 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 09:54:56.434  7655  7655 V BluetoothPbapService: Handler(): got msg=1
08-05 09:54:56.435  7655  7655 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 09:54:56.435  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:56.436  7655  7897 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 09:54:56.436  7655  7897 W bt-smp  : Plain text(LSB ~ MSB) = 56 84 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 09:54:56.436  7655  7897 W bt-smp  : Encrypted text(LSB ~ MSB) = aa 04 37 fb 0a a6 8d 3c 44 18 39 28 9a 80 55 88 
08-05 09:54:56.436  7655  7897 W bt-btm  : Stopping oneshot timer
08-05 09:54:56.436  2196  2196 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 09:54:56.436  7655  7948 V BluetoothPbapService: Pbap Service initSocket
08-05 09:54:56.436  2196  2196 D c       : Getting all permits...
08-05 09:54:56.436  2196  2196 D a       : Opening database...
,08-05 09:54:56.437  1037  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:56.439  7655  7948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:56.440  2196  2196 D a       : Opening database auth.proximity.permit_store...
08-05 09:54:56.440  7655  7948 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 09:54:56.440  7655  7948 V BluetoothPbapService: Succeed to create listening socket 
08-05 09:54:56.440  7655  7948 V BluetoothPbapService: Accepting socket connection...
08-05 09:54:56.441  2196  2196 D a       : Closing database...
08-05 09:54:56.453  6796  6796 D BluetoothPermissionRequest: onReceive
,08-05 09:54:56.455  6796  6796 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 09:54:56.456  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 09:54:56.459  7655  7655 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 09:54:56.460  7655  7655 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 09:54:56.465  7655  7655 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-05 09:54:56.483  7655  7655 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-05 09:54:56.483  7655  7655 V BtOppService: onCreate
08-05 09:54:56.487  7655  7655 V BluetoothOppNotification: send message
08-05 09:54:56.489  7655  7655 V BtOppService: Starting RfcommListener
08-05 09:54:56.494  7655  7655 D BluetoothOppPreference: Dumping Names:  
08-05 09:54:56.494  7655  7655 D BluetoothOppPreference: {}
08-05 09:54:56.494  7655  7655 D BluetoothOppPreference: Dumping Channels:  
08-05 09:54:56.494  7655  7655 D BluetoothOppPreference: {}
08-05 09:54:56.495  7655  7655 V BtOppService: onStartCommand
08-05 09:54:56.496  7655  7955 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-05 09:54:56.497  7655  7655 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:56.497  7655  7655 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 09:54:56.499  7655  7655 V BluetoothOppNotification: new notify threadi!
08-05 09:54:56.500  7655  7655 V BluetoothOppNotification: send delay message
08-05 09:54:56.500  7655  7655 V BtOppService: start RfcommListener
08-05 09:54:56.501  7655  7955 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 09:54:56.502  7655  7951 V BtOppService: Deleted complete outbound shares, number =  0
08-05 09:54:56.503  7655  7655 V BtOppService: RfcommListener started
08-05 09:54:56.503  7655  7951 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 09:54:56.503  7655  7957 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 09:54:56.504  7655  7951 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 09:54:56.504  7655  7955 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@240bdf81 on behalf of 
08-05 09:54:56.504  1037  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:56.504  7655  7957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:56.505  7655  7957 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-05 09:54:56.506  7655  7957 V BtOppRfcommListener: Started RFCOMM listener....
08-05 09:54:56.506  7655  7957 I BtOppRfcommListener: Accept thread started.
08-05 09:54:56.506  7655  7957 V BtOppRfcommListener: Accepting connection...
08-05 09:54:56.510  7655  7955 V BluetoothOppNotification: update too frequent, put in queue
,08-05 09:54:56.510  7655  7956 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-05 09:54:56.531  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
,08-05 09:54:56.532  7655  7655 V BluetoothFtpService: Ftp Service onCreate
08-05 09:54:56.532  7655  7655 I BluetoothFtpService: Ftp Service onCreate
,08-05 09:54:56.532  7655  7655 V BluetoothFtpService: Ftp Service onStartCommand
08-05 09:54:56.532  7655  7655 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:56.532  7655  7655 V BluetoothFtpService: Starting Listening on sockets
08-05 09:54:56.533  7655  7655 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 09:54:56.533  7655  7655 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 09:54:56.533  7655  7655 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 09:54:56.533  7655  7655 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:56.533  7655  7655 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 09:54:56.533  7655  7655 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-05 09:54:56.625  1037  2015 I art     : Explicit concurrent mark sweep GC freed 26396(1285KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.011ms total 118.894ms
,08-05 09:54:56.630  7655  7951 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32d05c67 on behalf of 
,08-05 09:54:56.630  7655  7655 V BtOppService: ContentObserver received notification
08-05 09:54:56.630  7655  7655 V BtOppService: ContentObserver received notification
08-05 09:54:56.630  7655  7655 V BluetoothFtpService: Handler(): got msg=1
08-05 09:54:56.630  7655  7956 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d88ea14 on behalf of 
08-05 09:54:56.632  7655  7956 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 09:54:56.632  7655  7655 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 09:54:56.632  7655  7655 V BluetoothFtpService: Ftp Service initSocket
08-05 09:54:56.634  1037  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:56.635  7655  7955 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 09:54:56.635  7655  7955 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 09:54:56.635  7655  7655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:56.636  7655  7955 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a15f2bd on behalf of 
08-05 09:54:56.636  7655  7956 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 09:54:56.637  7655  7955 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 09:54:56.640  7655  7956 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@367c20b2 on behalf of 
08-05 09:54:56.641  7655  7956 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-05 09:54:56.644  7655  7956 V BluetoothOppNotification: outbound notification was removed.
08-05 09:54:56.644  7655  7956 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 09:54:56.647  7655  7655 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-05 09:54:56.647  7655  7956 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7c5803 on behalf of 
08-05 09:54:56.647  7655  7956 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 09:54:56.648  7655  7655 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 09:54:56.648  7655  7956 V BluetoothOppNotification: inbound notification was removed.
08-05 09:54:56.649  7655  7956 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 09:54:56.651  7655  7959 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-05 09:54:56.653  7655  7956 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d149380 on behalf of 
,08-05 09:54:56.660  7655  7655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ebd2b5
08-05 09:54:56.660  7655  7655 V BluetoothSapService: Sap Service onCreate
08-05 09:54:56.663  7655  7655 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 09:54:56.663  7655  7655 V BluetoothSapService: state: 12
08-05 09:54:56.663  7655  7655 V BluetoothSapService: Starting SAP server process
08-05 09:54:56.664  7655  7655 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 09:54:56.660  7961  7961 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:56.660  7961  7961 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 09:54:56.672  7961  7961 V BT_SAP  : Event pipe created
,08-05 09:54:56.672  7961  7961 V BT_SAP  : create_server_socket qcom.sap.server
,08-05 09:54:56.672  7961  7961 V BT_SAP  : created socket fd 6
08-05 09:54:56.672  7655  7962 V BluetoothSapService: Sap Service initRfcommSocket
08-05 09:54:56.673  1037  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:56.675  7655  7962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 09:54:56.677  7655  7962 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-05 09:54:56.677  7655  7962 V BluetoothSapService: Succeed to create listening socket ,
08-05 09:54:56.677  7655  7962 V BluetoothSapService: Accepting socket connection...,
08-05 09:54:57.091  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
,08-05 09:54:57.091  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:57.091  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:57.091  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 09:54:57.091  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:57.091  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:57.091  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:57.091  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 09:54:57.109  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:57.113  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:57.113  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@64d730e added. We now have 8 listener(s)
08-05 09:54:57.113  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 09:54:57.117  1037  2015 D WifiServiceImplEx: setWifiEnabled: false pid=6709, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 09:54:57.118  1037  2015 D WifiService: setWifiEnabled: false pid=6709, uid=10118
08-05 09:54:57.118  1037  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 09:54:57.122  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:57.125  1037  1994 D WifiServiceImplEx: setWifiEnabled: true pid=6709, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 09:54:57.126  1037  1994 D WifiService: setWifiEnabled: true pid=6709, uid=10118
08-05 09:54:57.126  1037  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 09:54:57.145  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 09:54:57.145  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 09:54:57.145  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-05 09:54:57.149  1037  1377 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 09:54:57.149  1037  1377 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 09:54:57.152  1037  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 09:54:57.152  1037  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 09:54:57.152  1037  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 09:54:57.152  1037  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 09:54:57.152  1037  1377 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 09:54:57.152  1037  1377 E WifiHW  : unknown target_country: EU , set to default
08-05 09:54:57.152  1037  1377 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 09:54:57.152  1037  1377 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 09:54:57.152  1037  1377 I WifiUtil: gEnableBmps=1
,08-05 09:54:57.502  7655  7655 V BluetoothOppNotification: new notify threadi!
,08-05 09:54:57.503  7655  7655 V BluetoothOppNotification: send delay message
,08-05 09:54:57.517  7655  7975 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 09:54:57.522  7655  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3eef67ac on behalf of 
08-05 09:54:57.524  7655  7975 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-05 09:54:57.529  7655  7975 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 09:54:57.530  7655  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@188dbc75 on behalf of 
08-05 09:54:57.530  7655  7975 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 09:54:57.534  7655  7975 V BluetoothOppNotification: outbound notification was removed.
08-05 09:54:57.534  7655  7975 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 09:54:57.535  7655  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b43140a on behalf of 
08-05 09:54:57.536  7655  7975 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-05 09:54:57.539  7655  7975 V BluetoothOppNotification: inbound notification was removed.
08-05 09:54:57.540  7655  7975 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 09:54:57.541  7655  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1566c47b on behalf of 
08-05 09:54:57.853   318   895 D SoftapController: Softap fwReload - Ok
,08-05 09:54:57.866  1037  1377 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (710ms)
,08-05 09:54:57.871   318   895 D CommandListener: Setting iface cfg
08-05 09:54:57.871   318   895 D CommandListener: Trying to bring down wlan0
08-05 09:54:57.873  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-05 09:54:57.886   318   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 09:54:57.895  1037  1377 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-05 09:54:57.900  7983  7983 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 09:54:57.900  7983  7983 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:57.915  1037  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 09:54:57.915  1037  1377 E WifiStateMachine: useWiFiOffloading() : false
08-05 09:54:57.915  1037  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 09:54:57.926  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 09:54:57.935  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 09:54:57.954  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 09:54:57.961  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 09:54:57.961  1037  1377 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 09:54:57.962  1037  1377 D WifiMonitor: connecting to supplicant
08-05 09:54:57.963  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 09:54:57.964  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 09:54:57.964  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 09:54:57.964  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 09:54:57.966  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 09:54:57.967  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-05 09:54:57.968  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 09:54:57.968  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 09:54:57.968  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 09:54:57.968  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 09:54:57.968  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 09:54:57.969  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 09:54:57.980  7983  7983 I wpa_supplicant: Successfully initialized wpa_supplicant
08-05 09:54:58.017  7983  7983 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 09:54:58.017  7983  7983 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-05 09:54:58.020  1037  1119 D Tethering: InitialState.processMessage what=4
,08-05 09:54:58.027  1037  1956 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8000 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-05 09:54:58.029  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 09:54:58.095  7983  7983 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 09:54:58.138  7983  7983 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 09:54:58.148  1037  2016 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8023 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 09:54:58.149  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-05 09:54:58.150  7983  7983 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 09:54:58.152  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 09:54:58.152  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 09:54:58.153  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-05 09:54:58.153  1037  1377 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 09:54:58.153  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.154  1037  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.154  1037  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.155  1037  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.155  1037  8032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-05 09:54:58.156  1037  8032 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 09:54:58.156  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 09:54:58.156  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 09:54:58.156  1037  8032 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 09:54:58.156  1037  8032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 09:54:58.156  1037  1377 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 09:54:58.156  1037  1377 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 09:54:58.157  1037  1377 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 09:54:58.157  1037  1377 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 09:54:58.157  1037  1377 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 09:54:58.158  1037  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 09:54:58.158  1037  1377 E WifiStateMachine: useWiFiOffloading() : false
08-05 09:54:58.158  1037  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 09:54:58.158  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.158  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.158  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.158  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.158  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 09:54:58.159  1037  1377 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 09:54:58.159  1037  1377 D WifiNative-wlan0: SET update_config 1: returned true
08-05 09:54:58.159  1037  1377 D WifiConfigStore: Loading config and enabling all networks 
08-05 09:54:58.159  1037  1377 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 09:54:58.160  1037  1377 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-05 09:54:58.162  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-05 09:54:58.162  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:58.163  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 09:54:58.164  1037  1384 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-05 09:54:58.169  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:58.169  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:58.169  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:58.169  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:58.169  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:58.169  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:58.169  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:58.169  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 09:54:58.169  8000  8021 W FormManager: Network not available. Please check & try again.
08-05 09:54:58.171  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:58.172  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:54:58.172  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:58.172  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:58.172  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:58.172  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:58.172  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 09:54:58.172  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 09:54:58.172  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 09:54:58.174  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 09:54:58.176  1037  1377 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-05 09:54:58.182  6709  6778 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-05 09:54:58.183  6709  6778 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-05 09:54:58.185  1037  1377 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 09:54:58.185  6709  6778 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3444bff0 Bundle[{}]
08-05 09:54:58.185  1037  1377 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-05 09:54:58.188  6709  6778 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 09:54:58.188  1037  1377 D WifiStateMachine: enableVerboseLogging : level 2
,08-05 09:54:58.188  1037  1377 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 09:54:58.188  6709  6778 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-05 09:54:58.188  1037  1377 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 09:54:58.188  1037  1377 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 09:54:58.188  6709  6778 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-05 09:54:58.189  1037  1377 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 09:54:58.189  1037  1377 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 09:54:58.189  8000  8022 V FormManager: Network unavailable.
08-05 09:54:58.189  1037  1377 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 09:54:58.189  6709  6778 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-05 09:54:58.189  1037  1377 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 09:54:58.189  1037  1377 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 09:54:58.190  1037  1377 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 09:54:58.190  6709  6778 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 09:54:58.190  1037  1377 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 09:54:58.190  1037  1377 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 09:54:58.190  1037  1377 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 09:54:58.190  1037  1377 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 09:54:58.190  6709  6778 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-05 09:54:58.191  1037  1377 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 09:54:58.191  1037  1377 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 09:54:58.191  1037  1377 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 09:54:58.192  1037  1377 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 09:54:58.192  1037  1377 D WifiNative-HAL: Setting external_sim to 1
08-05 09:54:58.192  1037  1377 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 09:54:58.192  1037  1377 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 09:54:58.193  7685  7685 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.193  1037  1377 I WifiNative-HAL: startHal
08-05 09:54:58.193  1037  1377 D wifi    : setting scan oui 0xaf68f140
08-05 09:54:58.193  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-05 09:54:58.193  1925  2321 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 09:54:58.193  1925  2321 D WfdsService: Set the WFDS Monitor: true
08-05 09:54:58.193  1925  2321 D WfdsMonitor: WfdsMonitorThread create
08-05 09:54:58.193  1925  2321 D WfdsMonitor: WFDS Monitor is created and started
08-05 09:54:58.193  1037  1377 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 09:54:58.193  1925  2321 D WfdsService: WiFi: Supplicant connection re-established
08-05 09:54:58.193  1037  1377 I WifiNative-HAL: startHal
08-05 09:54:58.193  1037  1377 D wifi    : setting scan oui 0xaf68f140
08-05 09:54:58.194  1037  1377 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 09:54:58.194  1037  1377 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 09:54:58.194  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 09:54:58.194  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 09:54:58.195  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,08-05 09:54:58.195  1925  8042 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 09:54:58.195  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 09:54:58.195  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 09:54:58.196  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 09:54:58.196  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 09:54:58.196  1925  8042 E CtrlSupplicant: Succeed to open control connection
08-05 09:54:58.196  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 09:54:58.196  1925  8042 E CtrlSupplicant: Succeed to open monitor connection
08-05 09:54:58.196  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 09:54:58.196  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 09:54:58.196  1925  8042 D WfdsMonitor: Supplicant connection established
08-05 09:54:58.196  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 09:54:58.196  1925  2321 D WfdsService: Connected to the supplicant for wfds
08-05 09:54:58.196  6709  6778 I System.out: Running OutgoingSocketThread
08-05 09:54:58.197  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 09:54:58.197  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 09:54:58.197  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 09:54:58.197  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 09:54:58.197  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 09:54:58.197  7983  7983 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 09:54:58.197  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 09:54:58.197  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 09:54:58.197  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 09:54:58.198  6709  8043 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 871)
08-05 09:54:58.198  1037  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 09:54:58.198  1037  1377 E WifiNative: : [348,169,665 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 09:54:58.199  1037  1377 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 09:54:58.199  1037  1377 D WifiNative-wlan0: RECONNECT: returned true
08-05 09:54:58.199  1037  1377 D WifiNative-wlan0: doString: [STATUS]
08-05 09:54:58.199  6709  8043 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 32997
08-05 09:54:58.199  6709  8043 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-05 09:54:58.200  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 09:54:58.200  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 09:54:58.200  1037  1377 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 09:54:58.200  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 1
,08-05 09:54:58.201  1037  1377 D WifiNative-wlan0: SET ps 1: returned true
,08-05 09:54:58.201  1037  1376 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.201  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 09:54:58.201  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-05 09:54:58.202  1037  1377 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 09:54:58.202  1037  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.202  1037  1541 I WifiNative-HAL: startHal
08-05 09:54:58.202  1037  1541 D wifi    : getting scan capabilities on interface[1] = 0xaf68f140
08-05 09:54:58.202  1037  1541 D wifi    : failed to get capabilities : -3
08-05 09:54:58.202  1037  1541 E WifiScanningService: could not get scan capabilities
08-05 09:54:58.202  1037  1377 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 09:54:58.202  1037  1542 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.202  1037  1377 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 09:54:58.203  1037  1377 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 09:54:58.203  1037  1377 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 09:54:58.203  1037  1377 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 09:54:58.204   318   895 D CommandListener: Setting iface cfg
08-05 09:54:58.204   318   895 D CommandListener: Trying to bring up p2p0
08-05 09:54:58.204  1037  1377 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 09:54:58.204  1037  1377 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 09:54:58.204  1037  1376 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 09:54:58.204  1037  1376 D LGWifiP2pService: P2pEnablingState
08-05 09:54:58.204  7983  7983 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 09:54:58.204  1037  1376 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.204  1037  1376 D LGWifiP2pService: P2p socket connection successful
08-05 09:54:58.204  1037  1376 D LGWifiP2pService: P2pEnabledState
,08-05 09:54:58.204  1037  1376 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 09:54:58.205  8000  8022 V FormManager: Network unavailable.
08-05 09:54:58.206  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 09:54:58.207  1925  1925 D WfdsService: WifiP2pState is changed : true
08-05 09:54:58.207  1925  2321 D WfdsService: Receive the WFDS_ENABLE Method
08-05 09:54:58.207  1925  2321 D WfdsService: Set the WFDS Monitor: true
08-05 09:54:58.207  1925  2321 D WfdsService: Connected to the supplicant for wfds
08-05 09:54:58.207  1925  2321 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 09:54:58.207  1037  1377 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 09:54:58.207  1037  1376 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 09:54:58.207  7983  7983 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 09:54:58.207  1037  1377 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 09:54:58.208  1037  1377 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 09:54:58.208  1037  1376 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 09:54:58.208  1037  1377 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 09:54:58.208  7983  7983 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 09:54:58.208  1037  1376 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 09:54:58.208  1037  1376 D WifiNative-p2p0: SET device_name G3: returned true
08-05 09:54:58.208  1037  1377 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 09:54:58.208  1037  1376 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 09:54:58.208  1037  1376 D LGWifiP2pService: before postfix = G3
08-05 09:54:58.208  1037  1376 D WifiServerServiceExt: postfix byte check : 2
08-05 09:54:58.208  1037  1376 D LGWifiP2pService: after postfix = G3
08-05 09:54:58.208  1037  1376 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 09:54:58.208  1037  1377 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 09:54:58.209  1037  1376 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 09:54:58.209  1037  1376 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 09:54:58.209  1037  1377 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 09:54:58.209  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 09:54:58.209  1037  1376 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 09:54:58.209  1925  2321 D WfdsService: selectPreferredScanChannel [36]
08-05 09:54:58.209  1925  2321 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 09:54:58.210  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 09:54:58.210  7983  7983 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:58.210  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 09:54:58.210  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:58.210  1037  8032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:58.210  1037  8032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:58.211  7983  7983 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 09:54:58.211  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.211  1037  1377 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 09:54:58.211  1925  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:58.211  1037  1377 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 09:54:58.212  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
08-05 09:54:58.212  1037  1377 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 09:54:58.212  1925  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:58.212  1037  1377 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 09:54:58.212  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 09:54:58.212  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 09:54:58.212  7983  7983 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 09:54:58.213  1037  8032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:58.213  1037  8032 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.213  1037  8032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.213  1037  8032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.213  1037  8032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:58.213  1037  8032 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.209  1037  1376 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 09:54:58.213  1037  8032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.213  1037  8032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.213  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 09:54:58.213  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 09:54:58.213  1037  8032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 09:54:58.213  1037  8032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 09:54:58.214  1037  1377 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 09:54:58.214  1037  1377 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 09:54:58.215  1037  1377 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 09:54:58.215  1037  1377 D WifiNative-wlan0: doBoolean: SCAN
08-05 09:54:58.215  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 09:54:58.216  1925  1925 D WfdsService: isConnected: false
,08-05 09:54:58.218  1037  1377 D WifiNative-wlan0: SCAN: returned false
,08-05 09:54:58.219  1037  1376 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 09:54:58.219  1037  1376 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 09:54:58.219  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=348190  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 09:54:58.219  1037  1376 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 09:54:58.219  1037  1376 D WifiNative-HAL: p2pGetDeviceAddress
08-05 09:54:58.219  1037  1376 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 09:54:58.219  1037  1376 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 09:54:58.219  1037  1376 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 09:54:58.220  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=348191  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 09:54:58.220  1037  1376 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 09:54:58.220  1037  1376 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 09:54:58.220  1037  1376 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 09:54:58.220  1037  1376 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 09:54:58.221  1037  1376 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 09:54:58.221  1037  1376 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 09:54:58.221  1037  1377 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 09:54:58.221  1037  1377 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 09:54:58.221  1037  1377 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 09:54:58.222  1037  1377 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 09:54:58.222  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:58.222  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:58.223  1037  1377 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 09:54:58.223  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:58.225  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.225  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.225  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 09:54:58.226  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 09:54:58.226  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 09:54:58.226  1925  1925 D WfdsService: Update P2p Interface State: 3
08-05 09:54:58.227  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:58.227  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 09:54:58.228  1037  1376 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 09:54:58.228  1037  1376 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 09:54:58.228  1037  1376 D LGWifiP2pService: InactiveState
08-05 09:54:58.228  1037  1376 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.228  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.228  1037  1376 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 09:54:58.229,  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 09:54:58.229  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:58.229  1037  8032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 09:54:58.229  1037  8032 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:58.229  1037  8032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:58.229  1037  8032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 09:54:58.230  7983  7983 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 09:54:58.230  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.230  1037  8032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:58.230  1037  8032 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.230  1037  8032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.230  1037  8032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.230  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.231  1037  8032 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:58.231  1037  8032 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.231  1037  8032 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.231  1037  8032 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 09:54:58.231  1037  1376 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 09:54:58.231  1925  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 09:54:58.231  1925  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:58.231  1037  1376 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.231  1925  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 09:54:58.231  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.232  1037  1376 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.232  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.232  1037  1376 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 09:54:58.233  1037  1376 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 09:54:58.233  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.233  1037  1376 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.233  1037  1376 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.233  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.234  1037  1376 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.234  1037  1376 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.234  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.234  1037  1376 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.234  1037  1037 E WifiServerServiceExt: No p2p device connected
08-05 09:54:58.235  1925  2321 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 09:54:58.236  1037  1871 I ActivityManager: Killing 7117:com.lge.drmservice/u0a62 (adj 15): empty #17
08-05 09:54:58.258  8023  8023 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 09:54:58.286  1037  1972 W libprocessgroup: failed to open /acct/uid_10062/pid_7117/cgroup.procs: No such file or directory
,08-05 09:54:58.289  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 09:54:58.295  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:58.296  1037  1708 I ActivityManager: Killing 7147:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-05 09:54:58.341  1037  1053 W libprocessgroup: failed to open /acct/uid_10085/pid_7147/cgroup.procs: No such file or directory
,08-05 09:54:58.357  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-05 09:54:58.358  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 09:54:58.358  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 09:54:58.358  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 09:54:58.359  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 09:54:58.360  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 09:54:58.360  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 09:54:58.360  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 09:54:58.360  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 09:54:58.360  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 09:54:58.361  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 09:54:58.372  8023  8023 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 09:54:58.381  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 09:54:58.393  8000  8047 W FormManager: Network not available. Please check & try again.
08-05 09:54:58.400  8000  8048 V FormManager: Network unavailable.
08-05 09:54:58.400  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 09:54:58.417  8000  8048 V FormManager: Network unavailable.
,08-05 09:54:58.442  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 09:54:58.443  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-05 09:54:58.447  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:58.450  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:54:58.460  4310  8049 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 09:54:58.466  4310  8050 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 09:54:58.466  4310  8050 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 09:54:58.526  1037  1052 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8051 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 09:54:58.609  1037  1365 V AlarmManager: RTC_WAKEUP set : Alarm{2d5946e8 type 0 when 1470383693228 com.google.android.gms} when 1470383693228
08-05 09:54:58.611  1037  1365 V AlarmManager: RTC_WAKEUP set : Alarm{20e1101 type 0 when 1470383698401 android} when 1470383698401
,08-05 09:54:58.666  8051  8051 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 09:54:58.666  8051  8051 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-05 09:54:58.675  8051  8051 V [BNRBootReceiver]: Boot Receiver Return
,08-05 09:54:58.677  8051  8051 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 09:54:58.732  1037  1956 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8072 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 09:54:58.733  1037  1956 I ActivityManager: Killing 7179:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-05 09:54:58.777  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 09:54:58.777  1037  8032 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-05 09:54:58.777  7983  7983 E wpa_supplicant: USIM:  scard_init function
08-05 09:54:58.777  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 09:54:58.777  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-05 09:54:58.777  1037  8032 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 09:54:58.777  7983  7983 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-05 09:54:58.778  1037  1377 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-05 09:54:58.779  1037  1377 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,08-05 09:54:58.780  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 09:54:58.780  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 09:54:58.781  1037  1377 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,08-05 09:54:58.782  1037  1377 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0,
08-05 09:54:58.782  1037  1377 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-05 09:54:58.890  7983  7983 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 09:54:58.893  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 09:54:58.893  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 09:54:58.894  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 09:54:58.894  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 09:54:58.894  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-05 09:54:58.901  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:58.902  1037  1972 W libprocessgroup: failed to open /acct/uid_10093/pid_7179/cgroup.procs: No such file or directory
08-05 09:54:58.911  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=348883  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 09:54:58.914  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 09:54:58.914  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:58.915  7983  7983 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 09:54:58.915  7983  7983 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 09:54:58.915  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 09:54:58.915  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 09:54:58.915  1037  8032 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 09:54:58.915  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 09:54:58.915  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 09:54:58.916  1037  8032 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 09:54:58.917  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 09:54:58.917  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:58.919  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 09:54:58.925  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.925  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:54:58.925  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 09:54:58.928  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:58.928  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:58.929  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:58.930  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=348901  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 09:54:58.931  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=348902  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 09:54:58.931  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=348903  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 09:54:58.932  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.932  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.932  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 09:54:58.932  1037  1377 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348903
08-05 09:54:58.932  1037  1377 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348904
08-05 09:54:58.933  1037  1377 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348904
08-05 09:54:58.933  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348905
08-05 09:54:58.934  1037  1377 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348905
08-05 09:54:58.934  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=348906  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 09:54:58.936  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=348907  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 09:54:58.937  1037  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=348909  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 09:54:58.938  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=348909  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 09:54:58.939  1037  1377 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=348910
08-05 09:54:58.939  1037  1377 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=348911
08-05 09:54:58.939  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.939  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.939  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-05 09:54:58.940  1037  1377 D WifiNative-wlan0: doString: [STATUS]
08-05 09:54:58.940  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.940  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.940  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 09:54:58.940  1037  8032 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 09:54:58.940  1037  8032 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 09:54:58.941  1037  1377 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 09:54:58.942  1037  1377 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 09:54:58.949  1037  1377 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 09:54:58.949  1037  1377 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-05 09:54:58.953  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:58.953  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 09:54:58.956  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.956  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.956  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 09:54:58.964  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.965  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:58.965  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-05 09:54:58.967  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:58.969  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:58.969  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:58.970  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:58.972  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:58.972  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:58.972  1037  1377 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 09:54:58.972  1037  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 09:54:58.973  1037  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 09:54:58.973  1037  1428 D ConnectivityService: Got NetworkAgent Messenger
08-05 09:54:58.973  1037  1428 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 09:54:58.973  1037  1428 D ConnectivityService: NetworkAgent connected
08-05 09:54:58.973  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:58.973  1037  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 09:54:58.973  1037  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 09:54:58.974  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:58.974  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:58.975  8072  8072 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 09:54:58.978  1037  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 09:54:58.978  1037  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 09:54:58.978  1037  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 09:54:58.978  1037  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 09:54:58.979  1037  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 09:54:58.981  1037  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 09:54:58.983  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:58.983   318   895 D CommandListener: Setting iface cfg
08-05 09:54:58.985  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:58.985  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:58.986  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:58.987  1037  1377 E WifiStateMachine: Start Dhcp Watchdog 3
08-05 09:54:58.988  1037  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=348959  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:58.988  1037  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=348960  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-05 09:54:58.989  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=348960  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:58.989  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.990  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.990  1037  1377 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.991  1037  8094 D DhcpStateMachine: StoppedState
08-05 09:54:58.991  1037  1377 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.991  1037  8094 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:58.991  1037  8094 D DhcpStateMachine: WaitBeforeStartState
08-05 09:54:58.991  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.991  1037  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 09:54:58.995  1037  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=348966  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:58.995  1037  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=348967  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:58.996  1037  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=348967  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 09:54:58.997  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14149] from screen [on:0 period:1504883765] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 09:54:58.998  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1504883766] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 09:54:58.998  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 09:54:58.998  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:58.998  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-05 09:54:59.001  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:59.003  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.003  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.003  1037  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.004  1037  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.004  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.004  1037  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.005  1037  1428 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-05 09:54:59.005  1037  1428 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-05 09:54:59.007  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:59.007  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 09:54:59.007  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-05 09:54:59.008  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-05 09:54:59.008  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 09:54:59.008  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 09:54:59.011  1037  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 09:54:59.011  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 09:54:59.013  1037  1377 D WifiNative-wlan0: SET ps 0: returned true
08-05 09:54:59.013  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 09:54:59.013  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 09:54:59.013  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 09:54:59.013  1037  1377 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 09:54:59.014  1037  1377 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 09:54:59.014  1037  1376 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1fc423e1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:59.014  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1fc423e1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:59.014  1037  1377 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 09:54:59.014  1037  8094 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:59.014  1037  8094 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 09:54:59.015   318   895 D CommandListener: Setting iface cfg
08-05 09:54:59.015   318   895 D CommandListener: Trying to bring up wlan0
08-05 09:54:59.016  1037  1377 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 09:54:59.017  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 09:54:59.017  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 09:54:59.017  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.017  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-05 09:54:59.018  1037  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.018  1037  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.019  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.019  1037  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 09:54:59.019  8072  8072 D PluginManager: init()
08-05 09:54:59.020  1037  1428 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-05 09:54:59.020  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 09:54:59.021  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 09:54:59.021  1037  1376 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:59.021  1037  1376 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:59.021  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 09:54:59.022  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 09:54:59.022  1037  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 09:54:59.022  1037  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 09:54:59.022  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 09:54:59.023  1037  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 09:54:59.023  1037  1377 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 09:54:59.039  1037  1377 D WifiNative-wlan0: SET ps 1: returned true
08-05 09:54:59.040  1037  1428 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-05 09:54:59.040  1037  1377 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 09:54:59.040  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 09:54:59.040  1037  1377 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 09:54:59.041  1037  1428 D ConnectivityService: ignoring duplicate network state non-change
,08-05 09:54:59.043  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:59.043  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:59.044  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:59.045  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:59.045  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:59.045  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 09:54:59.047  1037  1428 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 09:54:59.047  1037  1428 D ConnectivityService: Adding iface wlan0 to network 102
08-05 09:54:59.049  1037  1377 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 09:54:59.053  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 09:54:59.054  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:59.054  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:59.055  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 09:54:59.055  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 09:54:59.055  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:59.055  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:59.055  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 09:54:59.055  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-05 09:54:59.061  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:59.061  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:54:59.061  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 09:54:59.064  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:59.064  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 09:54:59.066  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:59.068  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:59.068  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 09:54:59.068  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:59.072  1037  1428 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 09:54:59.072  1037  1428 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-05 09:54:59.073  1037  1428 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-05 09:54:59.073  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:54:59.073  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 09:54:59.074  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:59.074   318   895 E Netd    : netlink response contains error (File exists)
,08-05 09:54:59.074  1037  1428 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-05 09:54:59.075  1037  1428 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 09:54:59.075  1037  1428 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-05 09:54:59.076  1037  1428 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-05 09:54:59.077  1037  1428 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 09:54:59.077  1037  1428 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-05 09:54:59.077  1037  1428 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-05 09:54:59.077  1037  1428 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-05 09:54:59.077  1037  1428 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:59.078  1037  1428 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:59.078  1037  1428 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 09:54:59.078  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 09:54:59.078  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 09:54:59.078  1037  1428 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:59.078  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:54:59.078  1037  1428 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 09:54:59.078  1037  1428 D ConnectivityService: currentScore = 0, newScore = 20
08-05 09:54:59.078  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 09:54:59.078  1037  1428 D ConnectivityService:    accepting network in place of null
08-05 09:54:59.078  1037  1428 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:59.080  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:59.080  1037  1377 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 09:54:59.080  1037  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:59.080  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 09:54:59.081  1037  1428 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 09:54:59.081   318  8100 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 09:54:59.081  1037  1428 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-05 09:54:59.082  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 09:54:59.082  1037  1428 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 09:54:59.082  1037  1428 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 09:54:59.083  1037  1428 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 09:54:59.083  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 09:54:59.084  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 09:54:59.084  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 09:54:59.084  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 09:54:59.085  1037  1428 D ConnectivityService: validation of new default Network = false
08-05 09:54:59.085  1037  1428 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 09:54:59.085  1037  1428 D DSQN    : enableDataServiceNotify 
08-05 09:54:59.085  1037  1428 D DSQN    : start dsqn bin
,08-05 09:54:59.089  1037  1428 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-05 09:54:59.089  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:59.089  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:59.090  1037  1428 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:59.090  1588  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 09:54:59.093  1037  1375 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-05 09:54:59.080  8101  8101 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:59.080  8101  8101 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:59.109  8101  8101 E DSQN    : DSQN ssw
,08-05 09:54:59.117  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 09:54:59.118  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:59.118  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:59.129   318  8100 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-05 09:54:59.161   318  8100 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-05 09:54:59.200  6709  6778 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 872)
08-05 09:54:59.200  6709  6778 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 872)
08-05 09:54:59.209  6709  6778 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 877)
08-05 09:54:59.212  6709  6778 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-05 09:54:59.212  6709  6778 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
08-05 09:54:59.212   318   894 D LGDataListener: argv[0]=dsqncommand
08-05 09:54:59.212   318   894 D LGDataListener: argv[1]=wlan0
08-05 09:54:59.212   318   894 D LGDataListener: argv[2]=1
08-05 09:54:59.212   318   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 09:54:59.213  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 09:54:59.214  1037  1117 D DSQN    : start to monitor internet connection
08-05 09:54:59.216  1037  8094 D DhcpStateMachine: DHCPV4 request on wlan0
08-05 09:54:59.218  1037  8094 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 09:54:59.218  1037  8094 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 09:54:59.218  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.219  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12dc712f added. We now have 2 listener(s)
08-05 09:54:59.219  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.222  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.222  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.222  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.222  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.222  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb2b33c added. We now have 9 listener(s)
08-05 09:54:59.222  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.223  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 09:54:59.220  8107  8107 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:59.220  8107  8107 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 09:54:59.230  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:59.235  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:59.235  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:59.235  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:59.235  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:59.235  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:59.235  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.235  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:59.235  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:59.236  8107  8107 I dhcpcd  : version 5.5.6 starting
08-05 09:54:59.238  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.238  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 09:54:59.238  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.238  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f1b21a added. We now have 3 listener(s)
08-05 09:54:59.238  1037  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.239  8107  8107 E dhcpcd  : get_duid: m
08-05 09:54:59.239  8107  8107 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 09:54:59.239  8107  8107 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-05 09:54:59.248  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.249  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.249  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.249  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.249  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.249  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c48f14b added. We now have 10 listener(s)
08-05 09:54:59.249  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.250  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:59.250  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:59.250  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:59.250  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:59.250  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.250  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:59.250  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.250  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12dc712f removed from the list
08-05 09:54:59.250  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.250  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb2b33c removed from the list
08-05 09:54:59.252  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.252  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:59.252  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.252  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.252  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.253  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.253  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:59.253  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.253  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bb2b33c not in the list
08-05 09:54:59.253  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.253  6709  6778 D org.thaliproject.p2p.btconnec,torlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.254  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:59.254  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.254  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.254  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c48f14b removed from the list
08-05 09:54:59.254  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:59.254  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.254  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.254  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.254  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f1b21a removed from the list
08-05 09:54:59.255  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.255  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f95c728 added. We now have 2 listener(s)
08-05 09:54:59.255  1037  1870 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.257  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.257  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.257  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.257  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.257  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642c41 added. We now have 9 listener(s)
08-05 09:54:59.257  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.257  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 09:54:59.258  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:59.261  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:59.261  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:59.261  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:59.261  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:59.261  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:59.261  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.261  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:59.261  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:5,4:59.262  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.262  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 09:54:59.264  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.265  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.265  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.266  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38b35727 added. We now have 3 listener(s)
08-05 09:54:59.266  1037  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.266  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 07:54:59 GMT], X-Android-Received-Millis=[1470383699265], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470383699211]}
08-05 09:54:59.266  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 09:54:59.266  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 09:54:59.267  1037  1428 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-05 09:54:59.267  1037  1428 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-05 09:54:59.267  1037  1428 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:59.267  1037  1428 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:59.267  1037  1428 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 09:54:59.267  1037  1428 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-05 09:54:59.267  1037  1428 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-05 09:54:59.267  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:59.267  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:59.268  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.268  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.268  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.268  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.268  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18142dd4 added. We now have 10 listener(s)
08-05 09:54:59.268  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.268  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 09:54:59.268  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 09:54:59.268  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 09:54:59.268  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:59.268  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 09:54:59.269  1037  1428 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:54:59.269  1037  1428 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:59.270  1588  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 09:54:59.270  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 09:54:59.270  1037  1377 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:59.271  1037  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:54:59.272  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:54:59.272  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 09:54:59.273  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 09:54:59.274  1037  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.281  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 09:54:59.281  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 09:54:59.283  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 09:54:59.283  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:59.284  6709  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 09:54:59.284  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:59.284  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:59.287  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:59.287  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:59.287  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:59.287  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:59.287  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.287  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:59.287  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.287  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f95c728 removed from the list
08-05 09:54:59.287  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.287  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642c41 removed from the list
08-05 09:54:59.287  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:59.287  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.287  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.287  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.288  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.288  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:59.288  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.288  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6642c41 not in the list
08-05 09:54:59.288  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.288  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 09:54:59.289  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:59.291  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:59.291  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:59.291  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.291  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.291  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18142dd4 removed from the list
08-05 09:54:59.291  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:59.291  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.291  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.291  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.292  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38b35727 removed from the list
08-05 09:54:59.292  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.292  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f743ec3 added. We now have 2 listener(s)
08-05 09:54:59.293  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.293  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 09:54:59.293  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:59.294  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:54:59.295  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.295  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.295  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.295  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.295  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d705340 added. We now have 9 listener(s)
08-05 09:54:59.295  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.296  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 09:54:59.297  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:59.300  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:59.300  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:59.300  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:59.300  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:59.300  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:59.300  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.300  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:59.300  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:59.301  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.301  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 09:54:59.302  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.302  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2782bbbe added. We now have 3 listener(s)
08-05 09:54:59.302  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.303  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.304  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.307  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.307  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.308  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.308  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.308  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ad2041f added. We now have 10 listener(s)
08-05 09:54:59.308  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.308  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 09:54:59.309  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 09:54:59.309  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 09:54:59.309  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 09:54:59.309  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:59.309  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 09:54:59.310  8107  8107 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 09:54:59.311  8107  8107 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 09:54:59.311  8107  8107 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 09:54:59.311  8107  8107 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 09:54:59.311  8107  8107 D dhcpcd  : wlan0: sending REQUEST (xid 0x619c4316), next in 3.62 seconds
08-05 09:54:59.311  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 09:54:59.312  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.315  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 09:54:59.315  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 09:54:59.318  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 09:54:59.318  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:59.319  6709  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 09:54:59.319  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:59.320  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:59.320  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:59.320  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:59.320  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.320  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:59.320  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.320  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f743ec3 removed from the list
08-05 09:54:59.320  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.320  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d705340 removed from the list
08-05 09:54:59.320  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:59.320  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.321  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.321  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.322  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.322  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:59.322  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.322  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d705340 not in the list
08-05 09:54:59.322  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.322  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.323  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:59.323  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:59.323  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:59.323  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.323  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.323  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ad2041f removed from the list
08-05 09:54:59.323  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:59.323  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.323  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.324  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.324  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2782bbbe removed from the list
08-05 09:54:59.324  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.324  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1baad5ca added. We now have 2 listener(s)
08-05 09:54:59.325  1037  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.327  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.327  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.327  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.327  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.327  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@391cc33b added. We now have 9 listener(s)
08-05 09:54:59.327  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.327  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 09:54:59.329  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:59.332  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:59.332  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:59.332  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:59.332  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:59.332  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:59.332  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.332  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:59.332  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 09:54:59.334  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.334  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 09:54:59.334  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.334  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6fa7b1 added. We now have 3 listener(s)
08-05 09:54:59.334  1037  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.335  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.337  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.337  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.337  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.337  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.337  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.337  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b888496 added. We now have 10 listener(s)
08-05 09:54:59.337  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.337  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 09:54:59.337  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 09:54:59.338  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 09:54:59.338  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:59.338  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 09:54:59.340  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 09:54:59.340  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.343  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 09:54:59.344  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 09:54:59.346  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 09:54:59.346  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:59.347  6709  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 09:54:59.349  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:59.349  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:59.349  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:59.349  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:59.349  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.350  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:59.350  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.350  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1baad5ca removed from the list
08-05 09:54:59.350  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.350  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@391cc33b removed from the list
08-05 09:54:59.350  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:59.350  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.350  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.350  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.351  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.351  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:59.351  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.351  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@391cc33b not in the list
08-05 09:54:59.351  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.351  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.352  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:59.352  6709  6778 D BluetoothLeScanner: could not find callback wrapper
08-05 09:54:59.352  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 09:54:59.352  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.352  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.352  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b888496 removed from the list
08-05 09:54:59.352  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:59.352  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.352  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.352  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.352  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6fa7b1 removed from the list
08-05 09:54:59.353  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.353  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d260ded added. We now have 2 listener(s)
08-05 09:54:59.353  1037  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.353  8107  8107 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-05 09:54:59.355  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.356  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.356  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.356  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.356  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13c05422 added. We now have 9 listener(s)
08-05 09:54:59.356  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.356  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 09:54:59.359  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 09:54:59.362  6709  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 09:54:59.362  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:54:59.362  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:54:59.362  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:54:59.362  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:54:59.362  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.362  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:54:59.362  6709  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:54:59.363  6709  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:54:59.363  6709  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 09:54:59.364  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 09:54:59.364  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21df0c70 added. We now have 3 listener(s)
08-05 09:54:59.364  1037  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 09:54:59.365  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.367  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 09:54:59.367  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 09:54:59.367  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 09:54:59.367  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 09:54:59.367  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 09:54:59.367  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30629be9 added. We now have 10 listener(s)
08-05 09:54:59.367  6709  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 09:54:59.367  6709  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 09:54:59.368  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 09:54:59.368  6709  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 09:54:59.368  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 09:54:59.368  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.368  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 09:54:59.368  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.368  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d260ded removed from the list
08-05 09:54:59.368  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.368  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13c05422 removed from the list
08-05 09:54:59.368  6709  6778 D io.jxcore.node.ConnectivityMonitor: stop
08-05 09:54:59.368  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.368  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.368  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.371  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.371  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 09:54:59.371  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.371  6709  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13c05422 not in the list
08-05 09:54:59.371  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.371  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.373  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-05 09:54:59.373  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 09:54:59.373  6709  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 09:54:59.373  6709  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30629be9 removed from the list
08-05 09:54:59.373  6709  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 09:54:59.373  6709  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 09:54:59.373  6709  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 09:54:59.373  6709  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 09:54:59.373  6709  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21df0c70 removed from the list
,08-05 09:54:59.374  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-05 09:54:59.374  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 09:54:59.374  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-05 09:54:59.374  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 09:54:59.375  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 09:54:59.375  6709  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-05 09:54:59.385  6709  8114 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 885, name: My test thread name),
08-05 09:54:59.385  6709  8114 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 885, thread name: My test thread name)
08-05 09:54:59.386  6709  8114 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 885, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 09:54:59.389  6709  8115 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 887, name: My test thread name)
08-05 09:54:59.389  6709  8115 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 887, thread name: My test thread name)
08-05 09:54:59.389  6709  8115 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 887, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 09:54:59.391  6709  6778 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-05 09:54:59.391  6709  6778 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-05 09:54:59.391  6709  6778 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-05 09:54:59.391  6709  6778 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 09:54:59.391  6709  6778 D com.test.thalitest.ThaliTestRunner: Total duration: 22838 ms
08-05 09:54:59.393  6709  6778 I jxcore-log: Total number of executed tests:  80
08-05 09:54:59.393  6709  6778 I jxcore-log: 
08-05 09:54:59.393  6709  6778 I jxcore-log: Number of passed tests:  80
08-05 09:54:59.393  6709  6778 I jxcore-log: 
08-05 09:54:59.393  6709  6778 I jxcore-log: Number of failed tests:  0
08-05 09:54:59.393  6709  6778 I jxcore-log: 
08-05 09:54:59.393  6709  6778 I jxcore-log: Number of ignored tests:  0
08-05 09:54:59.393  6709  6778 I jxcore-log: 
,08-05 09:54:59.393  6709  6778 I jxcore-log: Total duration:  22838
08-05 09:54:59.393  6709  6778 I jxcore-log: 
08-05 09:54:59.395  8107  8107 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 09:54:59.395  8107  8107 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24,
08-05 09:54:59.395  8107  8107 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 09:54:59.395  8107  8107 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 09:54:59.396  8107  8107 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease',
08-05 09:54:59.396  6709  6778 I jxcore-log: Unit Test app is loaded
08-05 09:54:59.396  6709  6778 I jxcore-log: 
,08-05 09:54:59.396  8107  8107 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 09:54:59.396  8107  8107 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 09:54:59.396  8107  8107 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 09:54:59.419  6709  6709 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 09:54:59.420  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.420  6709  6778 I jxcore-log: 
08-05 09:54:59.428  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.428  6709  6778 I jxcore-log: 
08-05 09:54:59.429  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.429  6709  6778 I jxcore-log: 
08-05 09:54:59.430  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.430  6709  6778 I jxcore-log: 
08-05 09:54:59.431  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.431  6709  6778 I jxcore-log: 
08-05 09:54:59.433  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.433  6709  6778 I jxcore-log: 
,08-05 09:54:59.439  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 09:54:59.439  6709  6778 I jxcore-log: 
08-05 09:54:59.441  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.441  6709  6778 I jxcore-log: 
08-05 09:54:59.442  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.442  6709  6778 I jxcore-log: 
08-05 09:54:59.443  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 09:54:59.443  6709  6778 I jxcore-log: 
08-05 09:54:59.444  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 09:54:59.444  6709  6778 I jxcore-log: 
08-05 09:54:59.445  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 09:54:59.445  6709  6778 I jxcore-log: 
08-05 09:54:59.447  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.447  6709  6778 I jxcore-log: 
08-05 09:54:59.448  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.448  6709  6778 I jxcore-log: 
08-05 09:54:59.449  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.449  6709  6778 I jxcore-log: 
08-05 09:54:59.450  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.450  6709  6778 I jxcore-log: 
08-05 09:54:59.451  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.451  6709  6778 I jxcore-log: 
08-05 09:54:59.451  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.451  6709  6778 I jxcore-log: 
08-05 09:54:59.452  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.452  6709  6778 I jxcore-log: 
08-05 09:54:59.453  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 09:54:59.453  6709  6778 I jxcore-log: 
,08-05 09:54:59.456  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 09:54:59.456  6709  6778 I jxcore-log: 
08-05 09:54:59.457  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 09:54:59.457  6709  6778 I jxcore-log: 
08-05 09:54:59.457  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.457  6709  6778 I jxcore-log: 
08-05 09:54:59.458  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.458  6709  6778 I jxcore-log: 
08-05 09:54:59.458  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.458  6709  6778 I jxcore-log: 
08-05 09:54:59.459  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.459  6709  6778 I jxcore-log: 
08-05 09:54:59.459  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:54:59.459  6709  6778 I jxcore-log: 
08-05 09:54:59.461  6709  6778 I jxcore-log: My device name is: LGE-LG-D855
08-05 09:54:59.461  6709  6778 I jxcore-log: 
08-05 09:54:59.468  8072  8072 W ExternalStrings: load override strings
08-05 09:54:59.468  8072  8072 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:54:59.468  8072  8072 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 09:54:59.470  8072  8072 D StatusProvider: onCreate
,08-05 09:54:59.532  8072  8072 V Signer  : override build config not found
,08-05 09:54:59.532  8072  8072 D Signer  : value of property debug is false
08-05 09:54:59.570  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-05 09:54:59.570  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-05 09:54:59.570  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-05 09:54:59.570  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-05 09:54:59.570  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-05 09:54:59.571  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-05 09:54:59.571  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-05 09:54:59.571  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-05 09:54:59.571  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-05 09:54:59.571  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-05 09:54:59.571  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-05 09:54:59.572  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-05 09:54:59.572  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-05 09:54:59.581  8072  8072 V LGMDMManager: Create singleton instance
08-05 09:54:59.627  8072  8072 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-05 09:54:59.627  1037  8094 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-05 09:54:59.630  1037  8094 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 09:54:59.630  1037  8094 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 09:54:59.630  1037  8094 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 09:54:59.630  1037  8094 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-05 09:54:59.630  1037  8094 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 09:54:59.630  1037  8094 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 09:54:59.630  1037  8094 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-05 09:54:59.631  1037  8094 D DhcpStateMachine: RunningState
08-05 09:54:59.671  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:54:59.672  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-05 09:54:59.696  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:54:59.709  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:54:59.719  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 09:54:59.720  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:54:59.724  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 09:54:59.728  1037  1921 I ActivityManager: Killing 7214:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-05 09:54:59.786  8072  8137 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-05 09:54:59.858  1037  1906 W libprocessgroup: failed to open /acct/uid_10005/pid_7214/cgroup.procs: No such file or directory
,08-05 09:54:59.872  1037  1377 E WifiStateMachine:  ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):0 rssi=-45 f=2447 sc=60 link=72 tx=66.0, 0.0, 0.0  rx=55.0 fiv=20000 [on:0 tx:0 rx:0 period:870] from screen [on:0 period:1504884640]
08-05 09:54:59.873  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-45 f=2447 sc=60 link=72 tx=66.0, 0.0, 0.0  rx=55.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1504884641]
08-05 09:54:59.873  1037  1377 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=66.00 rxSuccessRate=55.00 targetRoamBSSID=any RSSI=-45
08-05 09:54:59.882  6870  6870 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-05 09:54:59.883  6870  6870 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9381
,08-05 09:54:59.897  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-05 09:54:59.901  6796  6796 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 09:54:59.903  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 09:54:59.904  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 09:54:59.904  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 09:54:59.904  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 09:54:59.905  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 09:54:59.906  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 09:54:59.906  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 09:54:59.906  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 09:54:59.906  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 09:54:59.907  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 09:54:59.907  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 09:54:59.907  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 09:54:59.907  1801  8143 I CheckinService: active receiver: enabled
,08-05 09:55:00.027  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:55:00.027  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 09:55:00.029  1801  8143 I CheckinService: Preparing to send checkin request
08-05 09:55:00.029  1801  8143 I EventLogService: Accumulating logs since 1470383681998
,08-05 09:55:00.045  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 09:55:00.048  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 09:55:00.048  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 09:55:00.049  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 09:55:00.049  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
08-05 09:55:00.050  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 09:55:00.050  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-05 09:55:00.050  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
,08-05 09:55:00.051  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 09:55:00.055  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 09:55:00.062  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:55:00.062  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:55:00.063  6870  6870 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 09:55:00.075  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 09:55:00.075  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 09:55:00.081  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 09:55:00.082  1801  8143 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-05 09:55:00.094  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:55:00.099  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:55:00.099  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:55:00.100  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 09:55:00.104  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:55:00.104  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-05 09:55:00.110  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 09:55:00.119  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:55:00.125  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:55:00.126  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:55:00.126  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 09:55:00.128  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:55:00.128  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 09:55:00.129  8072  8137 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:55:00.129  8072  8137 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 09:55:00.132  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 09:55:00.139  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 09:55:00.144  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:55:00.144  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:55:00.144  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 09:55:00.146  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:55:00.147  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 09:55:00.152  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:55:00.157  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:55:00.162  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:55:00.162  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:55:00.162  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 09:55:00.164  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:55:00.164  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-05 09:55:00.168  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 09:55:00.172  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:55:00.178  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 09:55:00.178  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:55:00.179  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 09:55:00.185  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 09:55:00.185  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:55:00.193  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:55:00.205  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:55:00.209  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:55:00.209  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:55:00.210  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 09:55:00.229  8072  8137 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-05 09:55:00.240  1037  2016 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8157 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-05 09:55:00.243  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 09:55:00.243  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:55:00.249  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 09:55:00.252  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:55:00.258  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 09:55:00.258  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:55:00.261  6870  6870 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 09:55:00.263  8072  8137 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-05 09:55:00.264  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:55:00.264  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 09:55:00.269  8072  8137 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-05 09:55:00.269  8023  8023 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-05 09:55:00.270  8072  8137 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-05 09:55:00.270  8072  8137 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-05 09:55:00.271  8072  8137 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-05 09:55:00.271  8072  8137 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-05 09:55:00.274  8072  8137 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-05 09:55:00.275  8072  8137 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-05 09:55:00.278  8023  8023 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:55:00.280  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 09:55:00.282  8157  8157 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-05 09:55:00.282  8157  8157 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-05 09:55:00.284  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 09:55:00.288  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:55:00.288  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 09:55:00.288  6870  6870 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 09:55:00.289  6870  6870 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 09:55:00.289  6870  6870 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 09:55:00.293  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 09:55:00.293  8072  8138 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 09:55:00.296  8023  8023 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 09:55:00.296  8023  8023 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 09:55:00.298  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 09:55:00.299  8157  8157 I MultiDex: VM with version 2.1.0 has multidex support
08-05 09:55:00.299  8157  8157 I MultiDex: install
08-05 09:55:00.299  8157  8157 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-05 09:55:00.301  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 09:55:00.309  6870  6870 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 09:55:00.309  6870  6870 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 09:55:00.309  8157  8157 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-05 09:55:00.309  6870  6870 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 09:55:00.311  6870  6870 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 09:55:00.311  6870  6870 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 09:55:00.314  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-05 09:55:00.315  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 09:55:00.318  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 09:55:00.321  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 09:55:00.322  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 09:55:00.323  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 09:55:00.324  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 09:55:00.325  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-05 09:55:00.327  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 09:55:00.329  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 09:55:00.330  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-05 09:55:00.335  2196  2196 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-05 09:55:00.342  2196  2196 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-05 09:55:00.342  2196  2196 D c       : Getting all permits...
08-05 09:55:00.342  2196  2196 D a       : Opening database...
08-05 09:55:00.344  2196  2196 D a       : Opening database auth.proximity.permit_store...
08-05 09:55:00.345  2196  2196 D a       : Closing database...
08-05 09:55:00.578  8181  8181 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-05 09:55:00.654  8181  8181 I dex2oat : dex2oat took 75.794ms (threads: 4)
,08-05 09:55:00.673  8157  8173 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 09:55:00.673  8157  8173 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 09:55:00.673  8157  8173 I Adreno-EGL: Build Date: 12/12/14 금
08-05 09:55:00.673  8157  8173 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 09:55:00.673  8157  8173 I Adreno-EGL: Remote Branch: 
08-05 09:55:00.673  8157  8173 I Adreno-EGL: Local Patches: 
08-05 09:55:00.673  8157  8173 I Adreno-EGL: Reconstruct Branch: 
,08-05 09:55:00.789  8157  8173 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 09:55:00.789  8157  8173 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 09:55:00.789  8157  8173 I Adreno-EGL: Build Date: 12/12/14 금
08-05 09:55:00.789  8157  8173 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 09:55:00.789  8157  8173 I Adreno-EGL: Remote Branch: 
08-05 09:55:00.789  8157  8173 I Adreno-EGL: Local Patches: 
08-05 09:55:00.789  8157  8173 I Adreno-EGL: Reconstruct Branch: 
,08-05 09:55:00.886  1037  1377 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-05 09:55:00.892  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 09:55:00.893  1037  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 09:55:00.895  1037  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 09:55:00.896  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 09:55:00.896  1037  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 09:55:00.897  1037  1428 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-05 09:55:00.897  1037  1428 D ConnectivityService: identical MTU - not setting
08-05 09:55:00.897  1037  1428 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 09:55:00.897  1037  1428 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-05 09:55:00.897  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:55:00.897  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:55:00.898  1037  1428 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:55:00.899  1588  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-05 09:55:01.035  8157  8173 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:55:01.035  8157  8173 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 09:55:01.109  8157  8173 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 09:55:01.109  8157  8173 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 09:55:01.109  8157  8173 I Adreno-EGL: Build Date: 12/12/14 금
08-05 09:55:01.109  8157  8173 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 09:55:01.109  8157  8173 I Adreno-EGL: Remote Branch: 
08-05 09:55:01.109  8157  8173 I Adreno-EGL: Local Patches: 
08-05 09:55:01.109  8157  8173 I Adreno-EGL: Reconstruct Branch: 
,08-05 09:55:01.184   318  8192 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 09:55:01.185   318  8192 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-05 09:55:01.221   318  8192 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-05 09:55:01.389  1801  8143 I CheckinTask: Sending checkin request (7968 bytes)
,08-05 09:55:01.659  1801  8143 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-05 09:55:01.666  1801  8143 I CheckinService: active receiver: disabled
,08-05 09:55:01.691  2196  2196 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-05 09:55:01.699  2196  2196 I GCM     : GCM config loaded
08-05 09:55:01.704   318  8204 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 09:55:01.704   318  8204 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-05 09:55:01.737   318  8204 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-05 09:55:01.740  1037  1941 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8205 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-05 09:55:01.850  8205  8205 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:55:01.850  8205  8205 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 09:55:01.853  8205  8205 D PhoneMonitor: Register our PhoneStateListener
,08-05 09:55:01.874  8205  8205 V SetupWizard: Connected to Gservices successfully
,08-05 09:55:01.878  1037  1994 I ActivityManager: Killing 7685:com.google.android.talk/u0a72 (adj 15): empty #17
08-05 09:55:01.898  8205  8205 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-05 09:55:01.899  8205  8205 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-05 09:55:01.900  8205  8205 D TelephonyAutoProfiling: [parse] Load xml
08-05 09:55:01.904  8205  8205 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 09:55:01.904  8205  8205 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 09:55:01.904  8205  8205 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-05 09:55:01.910  8205  8205 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-05 09:55:01.960  1037  1941 W libprocessgroup: failed to open /acct/uid_10072/pid_7685/cgroup.procs: No such file or directory
,08-05 09:55:02.005  1037  1377 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=66.0, 0.0, 0.0  rx=55.0 bcn=0 [on:0 tx:0 rx:0 period:2132] from screen [on:0 period:1504886773] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 09:55:02.008  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=66.0, 0.0, 0.0  rx=55.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1504886776] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 09:55:02.009  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 09:55:02.014  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 09:55:02.059  1037  1379 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-05 09:55:02.073  2196  8226 D GCM     : Connected
,08-05 09:55:02.084  1037  1428 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 09:55:02.088  1037  1119 D Tethering: MasterInitialState.processMessage what=3
,08-05 09:55:02.093  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:55:02.108  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 09:55:02.112  6709  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 09:55:02.112  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 09:55:02.112  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 09:55:02.112  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 09:55:02.112  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 09:55:02.112  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 09:55:02.112  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 09:55:02.112  6709  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 09:55:02.116  6709  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 09:55:02.118  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-05 09:55:02.123  2196  8226 D GCM     : Message class com.google.e.a.a.q
08-05 09:55:02.137  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 09:55:02.142  8072  8137 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 09:55:02.155  2196  2196 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 09:55:02.163  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 09:55:02.163  6709  6778 I jxcore-log: 
08-05 09:55:02.170  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 09:55:02.170  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 09:55:02.170  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 09:55:02.170  7008  7008 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 09:55:02.176  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 09:55:02.180  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c457b3e
08-05 09:55:02.180  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 09:55:02.180  7008  7008 D AppUp4:CustFacade: isPhone : true
08-05 09:55:02.180  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-05 09:55:02.180  7008  7008 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 09:55:02.183  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 09:55:02.183  4310  4310 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 09:55:02.185  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:55:02.186  1037  1708 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
08-05 09:55:02.187  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:55:02.188  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:55:02.188  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 09:55:02.188  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 09:55:02.188  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-05 09:55:02.190  4310  4310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 09:55:02.193  3532  3532 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-05 09:55:02.196  4310  8234 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 09:55:02.197  3532  3532 V DownloadManager: DownloadService onCreate
08-05 09:55:02.198  4310  8235 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 09:55:02.198  4310  8235 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 09:55:02.199  4310  8234 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-05 09:55:02.202  3532  8236 I DownloadManager: in removeSpuriousFiles
08-05 09:55:02.202  3532  8236 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,08-05 09:55:02.205  3532  8236 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@14aa4413 on behalf of 3532
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-05 09:55:02.206  3532  8236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-05 09:55:02.208  3532  8236 I DownloadManager: in trimDatabase
08-05 09:55:02.208  3532  8236 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-05 09:55:02.209  3532  8236 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@26eef650 on behalf of 3532
08-05 09:55:02.232  1037  1053 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8240 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 09:55:02.236  3532  3532 V DownloadManager: DownloadService onStartCommand
,08-05 09:55:02.236  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 07:55:02 GMT], X-Android-Received-Millis=[1470383702236], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470383702189]}
08-05 09:55:02.237  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 09:55:02.237  1037  8089 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 09:55:02.237  1037  1428 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-05 09:55:02.237  1037  1428 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-05 09:55:02.237  1037  1428 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 09:55:02.237  1037  1428 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:55:02.237  1037  1428 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 09:55:02.237  3532  8237 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-05 09:55:02.237  1037  1428 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-05 09:55:02.237  1037  1428 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-05 09:55:02.237  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 09:55:02.237  1037  1428 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:55:02.238  1037  1428 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 09:55:02.238  1588  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 09:55:02.238  3532  8237 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2feb0e6f on behalf of 3532
08-05 09:55:02.242  4310  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-05 09:55:02.245  3532  8237 V DownloadManager: processing inserted download 1
08-05 09:55:02.246  4310  4310 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-05 09:55:02.246  3532  8237 V DownloadManager: processing inserted download 4
08-05 09:55:02.247  3532  8237 V DownloadManager: processing inserted download 7
08-05 09:55:02.248  4310  4310 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-05 09:55:02.248  3532  8237 V DownloadManager: processing inserted download 8
08-05 09:55:02.248  4310  4310 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-05 09:55:02.249  3532  8237 V DownloadManager: processing inserted download 9
08-05 09:55:02.250  3532  8237 V DownloadManager: processing inserted download 10
08-05 09:55:02.250  3532  8237 V DownloadManager: processing inserted download 11
08-05 09:55:02.251  4310  4310 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-05 09:55:02.251  3532  8237 V DownloadManager: processing inserted download 12
08-05 09:55:02.252  3532  8237 V DownloadManager: processing inserted download 13
08-05 09:55:02.253  3532  8237 V DownloadManager: processing inserted download 14
08-,05 09:55:02.254  3532  8237 V DownloadManager: processing inserted download 16
08-05 09:55:02.259  4310  4310 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-05 09:55:02.263  3532  3532 V DownloadManager: DownloadService onDestroy
,08-05 09:55:02.302  8240  8240 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 09:55:02.302  8240  8240 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 09:55:02.304  8240  8240 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 09:55:02.304  8240  8240 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 09:55:02.374  8240  8240 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 09:55:02.384  8240  8240 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-05 09:55:02.415  8240  8240 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 09:55:02.438  8240  8240 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 09:55:02.439  8240  8240 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 09:55:02.575  8240  8240 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 09:55:02.607  8240  8240 I HubEmail: JNI_OnLoad()
08-05 09:55:02.607  8240  8240 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 09:55:02.607  8240  8240 I HubEmail: registerNatives()
08-05 09:55:02.607  8240  8240 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-05 09:55:02.607  8240  8240 I HubEmail: registerNativeMethods()
08-05 09:55:02.607  8240  8240 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 09:55:02.607  8240  8240 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-05 09:55:02.623  8240  8263 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:55:02.636  3493  3493 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 09:55:02.636  3493  3493 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 09:55:02.636  3493  3493 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 09:55:02.636  3493  3493 D PhoneState: setPdpRejectCasuse : false
,08-05 09:55:02.639  8205  8205 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-05 09:55:02.640  8205  8205 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 09:55:02.658   318  8267 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 09:55:02.658   318  8267 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-05 09:55:02.686  1037  1906 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8268 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 09:55:02.688   318  8267 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-05 09:55:02.768  8000  8264 V FormManager: There are no updated forms. The schedule will be deleted.
,08-05 09:55:02.774  8000  8264 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-05 09:55:02.817  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 09:55:02.817  6709  6778 I jxcore-log: 
08-05 09:55:02.818  1037  1052 I ActivityManager: Killing 7736:com.android.contacts/u0a19 (adj 15): empty #17
,08-05 09:55:02.839  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 09:55:02.839  6709  6778 I jxcore-log: 
,08-05 09:55:02.958  1037  1870 W libprocessgroup: failed to open /acct/uid_10019/pid_7736/cgroup.procs: No such file or directory
,08-05 09:55:03.044  1037  1906 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8286 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-05 09:55:03.045  1037  1906 I ActivityManager: Killing 7759:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-05 09:55:03.187  1037  2015 W libprocessgroup: failed to open /acct/uid_10027/pid_7759/cgroup.procs: No such file or directory
,08-05 09:55:03.266   318  8306 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 09:55:03.269   318  8306 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-05 09:55:03.302   318  8306 D libc-netbsd: res_queryN name = www.google.com succeed
,08-05 09:55:03.310  1037  2015 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8307 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 09:55:03.311  1037  2015 I ActivityManager: Killing 7778:com.android.vending/u0a44 (adj 15): empty #17
08-05 09:55:03.317   318  8310 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 09:55:03.317   318  8310 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 09:55:03.317   318  8310 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-05 09:55:03.406  1037  1053 W libprocessgroup: failed to open /acct/uid_10044/pid_7778/cgroup.procs: No such file or directory
,08-05 09:55:03.429  1037  1380 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-05 09:55:03.450  8307  8307 I art     : Almond Protected OAT
,08-05 09:55:03.510  8307  8307 D WeatherApplication: removeAccount
,08-05 09:55:03.512  8307  8307 D WeatherApplication: Account.length = 0
08-05 09:55:03.512  8307  8307 E WeatherApplication: OPERATOR:OPEN
,08-05 09:55:03.517  8307  8307 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:55:3
08-05 09:55:03.520  8307  8307 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 09:55:03.520  8307  8307 D Weather.Utils: 2 : All the weather widget is gone.
08-05 09:55:03.522  8307  8307 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 09:55:03.524  8307  8307 D WeatherAncestor: connectivity changed - connection : true
08-05 09:55:03.526  8307  8307 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-05 09:55:03.546  8307  8307 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-05 09:55:03.546  8307  8307 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 09:55:03.547  8307  8307 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-05 09:55:03.701  1037  1708 I art     : Explicit concurrent mark sweep GC freed 80269(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.852ms total 126.087ms
,08-05 09:55:03.703  8307  8307 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-05 09:55:03.704  8307  8307 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:55:3
,08-05 09:55:03.728  1037  1972 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8336 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 09:55:03.729  1037  1972 I ActivityManager: Killing 7821:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-05 09:55:03.741   380   380 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 284us total 15.580ms
,08-05 09:55:03.754   380   380 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 247us total 11.694ms
08-05 09:55:03.766   380   380 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 292us total 11.864ms
,08-05 09:55:03.828  1037  1871 W libprocessgroup: failed to open /acct/uid_10080/pid_7821/cgroup.procs: No such file or directory
,08-05 09:55:03.934   279   412 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 09:55:03.934   279   412 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 09:55:03.934   279   412 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 09:55:03.937  8336  8359 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 09:55:03.948   279   412 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 09:55:03.948   279   412 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 09:55:03.949   279   412 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 09:55:03.950  8336  8359 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 09:55:03.973   279   412 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 09:55:03.973   279   412 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 09:55:03.973   279   412 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 09:55:03.984  8336  8363 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 09:55:03.996   279   412 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 09:55:03.996   279   412 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 09:55:03.997   279   412 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 09:55:03.998  8336  8363 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-05 09:55:04.171  8336  8336 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 09:55:04.180  8336  8336 I LibraryLoader: Loading: webviewchromium
08-05 09:55:04.183  8336  8336 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4164-4168)
08-05 09:55:04.183  8336  8336 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 09:55:04.191  8336  8336 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e777ca1}
08-05 09:55:04.194  8336  8336 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 09:55:04.194  8336  8336 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 09:55:04.203  8336  8336 I BrowserStartupController: Initializing chromium process, renderers=0
08-05 09:55:04.204  8336  8336 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 09:55:04.217  8336  8336 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 09:55:04.218  8336  8336 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 09:55:04.218  8336  8336 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-05 09:55:04.226   322   322 V AudioPolicyService: registerClient() client 0xb1427820, uid 10093
08-05 09:55:04.227  8336  8384 W AudioManagerAndroid: Requires BLUETOOTH permission
08-05 09:55:04.243  8336  8336 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 09:55:04.243  8336  8336 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 09:55:04.243  8336  8336 I Adreno-EGL: Build Date: 12/12/14 금
08-05 09:55:04.243  8336  8336 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 09:55:04.243  8336  8336 I Adreno-EGL: Remote Branch: 
08-05 09:55:04.243  8336  8336 I Adreno-EGL: Local Patches: 
08-05 09:55:04.243  8336  8336 I Adreno-EGL: Reconstruct Branch: 
,08-05 09:55:04.314  8336  8336 I NSApplication: Starting up...
,08-05 09:55:04.352  1037  1941 I ActivityManager: Killing 7441:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-05 09:55:04.386  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 09:55:04.386  6709  6778 I jxcore-log: 
,08-05 09:55:04.567  1037  1708 W libprocessgroup: failed to open /acct/uid_10037/pid_7441/cgroup.procs: No such file or directory
,08-05 09:55:04.644  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 09:55:04.644  6709  6778 I jxcore-log: 
,08-05 09:55:04.653  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 09:55:04.653  6709  6778 I jxcore-log: 
,08-05 09:55:04.682  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 09:55:04.682  6709  6778 I jxcore-log: 
,08-05 09:55:04.688  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-05 09:55:04.688  6709  6778 I jxcore-log: 
,08-05 09:55:05.016  1037  1377 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=48.0, 0.0, 0.0  rx=38.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1504889784] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 09:55:05.016  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=48.0, 0.0, 0.0  rx=38.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1504889784] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 09:55:05.016  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 09:55:05.391  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-05 09:55:05.391  6709  6778 I jxcore-log: 
,08-05 09:55:05.406  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
08-05 09:55:05.406  6709  6778 I jxcore-log: 
,08-05 09:55:05.416  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-05 09:55:05.416  6709  6778 I jxcore-log: 
,08-05 09:55:05.424  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-05 09:55:05.424  6709  6778 I jxcore-log: 
,08-05 09:55:05.472  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-05 09:55:05.472  6709  6778 I jxcore-log: 
,08-05 09:55:05.529  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-05 09:55:05.529  6709  6778 I jxcore-log: 
,08-05 09:55:05.536  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-05 09:55:05.536  6709  6778 I jxcore-log: 
,08-05 09:55:05.698  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 09:55:05.698  6709  6778 I jxcore-log: 
,08-05 09:55:05.726  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 09:55:05.726  6709  6778 I jxcore-log: 
,08-05 09:55:05.731  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 09:55:05.731  6709  6778 I jxcore-log: 
,08-05 09:55:05.736  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 09:55:05.736  6709  6778 I jxcore-log: 
08-05 09:55:05.754  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 09:55:05.754  6709  6778 I jxcore-log: 
,08-05 09:55:05.836  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 09:55:05.836  6709  6778 I jxcore-log: 
,08-05 09:55:05.850  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-05 09:55:05.850  6709  6778 I jxcore-log: 
,08-05 09:55:05.879  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-05 09:55:05.879  6709  6778 I jxcore-log: 
,08-05 09:55:05.892  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-05 09:55:05.892  6709  6778 I jxcore-log: 
08-05 09:55:05.909  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-05 09:55:05.909  6709  6778 I jxcore-log: 
,08-05 09:55:05.944  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 09:55:05.944  6709  6778 I jxcore-log: 
,08-05 09:55:05.950  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 09:55:05.950  6709  6778 I jxcore-log: 
08-05 09:55:06.156  6709  6778 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 09:55:06.156  6709  6778 I jxcore-log: 
,08-05 09:55:06.166  6709  6778 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-05 09:55:06.167  6709  6778 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-05 09:55:06.167  6709  6778 I jxcore-log: 
08-05 09:55:06.185  1037  2016 I ActivityManager: Killing 6890:com.lge.settings.easy/1000 (adj 15): empty #17
,08-05 09:55:06.211  6709  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 09:55:06.211  6709  6778 I jxcore-log: 
,08-05 09:55:06.235  1037  1972 W libprocessgroup: failed to open /acct/uid_1000/pid_6890/cgroup.procs: No such file or directory
,08-05 09:55:08.028  1037  1377 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=33.5, 0.0, 0.0  rx=26.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1504892796] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 09:55:08.031  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=33.5, 0.0, 0.0  rx=26.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1504892799] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 09:55:08.031  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 09:55:08.569  1037  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=361482269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-05 09:55:08.595  1037  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{32980efe type 2 when 358536 com.google.android.gms} when 358536
,08-05 09:55:08.605   318  8416 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 09:55:08.606   318  8416 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-05 09:55:08.606   318  8416 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-05 09:55:08.632  2579  2579 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 09:55:08.664  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=361482269 [*alarm*], flags=0x0
,08-05 09:55:08.960  2196  8426 D GCM     : Connected
,08-05 09:55:08.977  8336  8361 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-05 09:55:08.981  2196  8426 D GCM     : Message class com.google.e.a.a.q
08-05 09:55:10.057  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 09:55:10.066  1037  1367 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 09:55:10.094  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 09:55:10.114  1037  1037 D administrator: Handling package changes for user 0
,08-05 09:55:10.189  1037  1112 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8437 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 09:55:10.203  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 09:55:10.207  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-05 09:55:10.324  8437  8437 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 09:55:10.328  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-05 09:55:10.328  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-05 09:55:10.332  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:55:10.394  8437  8437 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:55:10.395  8437  8437 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 09:55:10.407  1037  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 09:55:10.415  1037  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 09:55:10.427  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-05 09:55:10.430  2487  2487 V GmsNetworkLocationProvi: DISABLE
08-05 09:55:10.455  2487  2487 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-05 09:55:10.470  2196  2226 I art     : Explicit concurrent mark sweep GC freed 7624(482KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 692us total 16.092ms
,08-05 09:55:10.517  1037  1109 D LocationProviderProxy: applying state to connected service
,08-05 09:55:10.521  8437  8482 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 09:55:10.521  8437  8482 I Babel   : MmsConfig.loadMmsSettings
08-05 09:55:10.526  8437  8482 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 09:55:10.526  8437  8482 I Babel   : MmsConfig.loadFromDatabase
,08-05 09:55:10.555  8437  8482 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 09:55:10.555  8437  8482 I Babel   : MmsConfig.loadFromResources
,08-05 09:55:10.556  8437  8482 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-05 09:55:10.557  8437  8482 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 09:55:10.558  8437  8480 W AudioCapabilities: Unsupported mime audio/evrc
08-05 09:55:10.559  8437  8480 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 09:55:10.561  8437  8480 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-05 09:55:10.567  8437  8437 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:55:10.573  8437  8480 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-05 09:55:10.574  8437  8480 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 09:55:10.576  8437  8480 W AudioCapabilities: Unsupported mime audio/evrc
08-05 09:55:10.585  8437  8480 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-05 09:55:10.589  8437  8480 W VideoCapabilities: Unsupported mime video/divx
08-05 09:55:10.592  8437  8480 W VideoCapabilities: Unsupported mime video/divx311
08-05 09:55:10.595  8437  8480 W VideoCapabilities: Unsupported mime video/divx4
08-05 09:55:10.599  8437  8480 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-05 09:55:10.602  1801  8485 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 09:55:10.602  1801  8485 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 09:55:10.606  7008  7008 I AppUp4:CustModeStarterReceiver: onReceive
08-05 09:55:10.609  7008  7008 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c457b3e
08-05 09:55:10.609  7008  7008 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 09:55:10.609  7008  7008 D AppUp4:CustFacade: isPhone : true
08-05 09:55:10.610  7008  7008 D AppUp4:CustModeStarterReceiver: begin check event
08-05 09:55:10.610  7008  7008 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-05 09:55:10.621  1801  4786 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-05 09:55:10.629  8437  8480 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 09:55:10.636  8437  8480 W AudioCapabilities: Unsupported mime audio/eac3
08-05 09:55:10.637  8437  8480 W AudioCapabilities: Unsupported mime audio/ac3
08-05 09:55:10.638  8437  8480 W AudioCapabilities: Unsupported mime audio/g726
08-05 09:55:10.639  8437  8480 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 09:55:10.641  8437  8480 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-05 09:55:10.642  8437  8480 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 09:55:10.645  8437  8480 W VideoCapabilities: Unsupported mime video/theora
08-05 09:55:10.647  8437  8480 W VideoCapabilities: Unsupported mime video/mjpg
08-05 09:55:10.655  1037  1956 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8488 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-05 09:55:10.689  1037  1052 I ActivityManager: Killing 8051:com.lge.bnr/1000 (adj 15): empty #17
08-05 09:55:10.693  8488  8488 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:55:10.693  8488  8488 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 09:55:10.694  8488  8488 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 09:55:10.695  8488  8488 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 09:55:10.695  8488  8488 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 09:55:10.859  1037  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_8051/cgroup.procs: No such file or directory
,08-05 09:55:10.928  8488  8488 I SystemConfig: BUILD Country: EU
08-05 09:55:10.928  8488  8488 I SystemConfig: BUILD Operator: OPEN
,08-05 09:55:10.985  1037  1956 I ActivityManager: Killing 8023:com.lge.sync/1000 (adj 15): empty #17
,08-05 09:55:11.048  1037  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_8023/cgroup.procs: No such file or directory
,08-05 09:55:11.052  1037  1377 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=21.2, 0.0, 0.0  rx=16.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1504895820] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 09:55:11.053  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=21.2, 0.0, 0.0  rx=16.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1504895821] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 09:55:11.053  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 09:55:11.063  8488  8510 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-05 09:55:11.066  8488  8510 I SystemConfig: existFile = false
08-05 09:55:11.066  8488  8510 I SystemConfig: canReadFile = false
08-05 09:55:11.067  8488  8510 I SystemConfig: systemFeature RCS result false
08-05 09:55:11.067  8488  8510 D SystemConfig: refreshRcsSupport() :false
08-05 09:55:11.114  1037  1956 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8512 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 09:55:11.129  1588  1588 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 09:55:11.129  1588  1588 I [SystemUI]LGPowerUI: On Skip Timer : true
08-05 09:55:11.134  1925  2078 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 09:55:11.134  1925  2078 D LEDHandler: Battery Level Remaining: 100%
08-05 09:55:11.134  1925  2078 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
08-05 09:55:11.136  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:55:11.136  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 09:55:11.137  1037  1418 D WifiController: battery changed pluggedType: 2
,08-05 09:55:11.139  1588  1588 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
08-05 09:55:11.139  1588  1588 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 09:55:11.140  7655  7881 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 09:55:11.141  1588  1588 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 09:55:11.171  8512  8512 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:55:11.171  8512  8512 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 09:55:11.171  8512  8512 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 09:55:11.172  8512  8512 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 09:55:11.274  8512  8512 I AppConfig: Total System Memory = 2995761152
,08-05 09:55:11.284  8512  8512 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-05 09:55:11.371  1037  2016 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8532 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 09:55:11.373  1037  2016 I ActivityManager: Killing 6796:com.android.settings/1000 (adj 15): empty #17
,08-05 09:55:11.436  1037  2015 W libprocessgroup: failed to open /acct/uid_1000/pid_6796/cgroup.procs: No such file or directory
,08-05 09:55:11.628  8532  8532 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 09:55:11.732  8532  8532 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 09:55:11.732  8532  8532 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 09:55:11.797  8532  8532 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 09:55:11.819  8532  8532 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 09:55:11.820  8532  8532 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 09:55:11.838  8532  8532 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-05 09:55:11.838  8532  8532 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-05 09:55:11.875  1037  1921 I ActivityManager: Killing 7568:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-05 09:55:11.894  6870  6870 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 09:55:11.894  6870  6870 W System.err: android.os.DeadObjectException
08-05 09:55:11.894  6870  6870 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 09:55:11.894  6870  6870 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 09:55:11.894  6870  6870 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 09:55:11.894  6870  6870 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 09:55:11.894  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 09:55:11.894  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 09:55:11.894  6870  6870 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 09:55:11.895  6870  6870 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 09:55:11.895  6870  6870 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:55:11.895  6870  6870 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:55:11.895  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 09:55:11.895  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-05 09:55:11.895  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:55:11.895  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 09:55:11.895  6870  6870 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 09:55:11.895  6870  6870 W System.err: android.os.DeadObjectException
08-05 09:55:11.896  6870  6870 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 09:55:11.896  6870  6870 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 09:55:11.896  6870  6870 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 09:55:11.896  6870  6870 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 09:55:11.896  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 09:55:11.896  6870  6870 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 09:55:11.896  6870  6870 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 09:55:11.896  6870  6870 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 09:55:11.896  6870  6870 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:55:11.896  6870  6870 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:55:11.896  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-05 09:55:11.896  6870  6870 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 09:55:11.896  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:55:11.896  6870  6870 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 09:55:11.896  6870  6870 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 09:55:11.896  6870  6870 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-05 09:55:11.940  1037  1637 W libprocessgroup: failed to open /acct/uid_1000/pid_7568/cgroup.procs: No such file or directory
08-05 09:55:11.941  1037  1637 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-05 09:55:11.955  3532  3547 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-05 09:55:11.960  6870  6870 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 09:55:11.960  6870  6870 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 09:55:11.962  3532  3547 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2231c805 on behalf of 8532
08-05 09:55:11.977  4609  8577 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-05 09:55:12.005  1037  1956 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8578 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 09:55:12.008  6870  6870 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 09:55:12.059  1037  1994 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8602 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 09:55:12.077  8532  8532 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-05 09:55:12.096  8532  8532 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-05 09:55:12.121  8578  8578 D UEI.SmartControl: Quickset Services start...
,08-05 09:55:12.123  8578  8578 I UEI.SmartControl: Manufacture = LGE
08-05 09:55:12.123  8578  8578 D UEI.SmartControl: Id = LGNevo
08-05 09:55:12.124  8578  8578 D UEI.SmartControl: File observer start...
08-05 09:55:12.124  8578  8578 E UEI.SmartControl: IR Port is disabled: false
08-05 09:55:12.124  8578  8578 D UEI.SmartControl: Starting file observer...
08-05 09:55:12.125  8578  8578 D UEI.SmartControl: Extracting JNI libs...
08-05 09:55:12.125  8578  8578 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-05 09:55:12.139  8602  8602 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-05 09:55:12.160  8602  8602 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 09:55:12.160  8602  8602 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 09:55:12.160  8602  8602 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 09:55:12.160  8602  8602 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 09:55:12.160  8602  8602 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 09:55:12.161  8602  8602 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 09:55:12.173  1037  1921 I ActivityManager: Killing 6870:com.lge.qremote/u0a112 (adj 15): empty #17
08-05 09:55:12.185  8578  8578 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 09:55:12.185  8578  8578 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 09:55:12.185  8578  8578 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 09:55:12.205  8578  8578 I UEI.SmartControl: --- Selecting new region: 6
,08-05 09:55:12.206  8578  8578 I UEI.SmartControl: Model = LG-D855
,08-05 09:55:12.207  8578  8578 D UEI.SmartControl: QS Service created
08-05 09:55:12.216  1037  1560 W libprocessgroup: failed to open /acct/uid_10112/pid_6870/cgroup.procs: No such file or directory
08-05 09:55:12.228  8578  8578 I UEI.SmartControl: Service initServices...
,08-05 09:55:12.231  8578  8578 D UEI.SmartControl: QS start get config
,08-05 09:55:12.301  8578  8578 D UEI.SmartControl: Loading JNI Libs...
,08-05 09:55:12.370  1037  1052 V SIM_STK : Menu title from STK is T-Mobile
,08-05 09:55:12.382  4609  8577 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 406 ms] updated apps [took 406 ms] 
,08-05 09:55:12.574  8578  8578 I UEI.SmartControl: Supports setup maps: true
,08-05 09:55:12.578  8578  8578 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 09:55:12.578  8578  8578 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 09:55:12.579  8578  8578 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 09:55:12.579  8578  8578 I UEI.SmartControl: ### init IR Blaster...
08-05 09:55:12.585  8578  8578 D serial_port: Configuring serial port
08-05 09:55:12.597  8578  8578 E UEI.SmartControl: UEIBLaster setting for 616
,08-05 09:55:12.598  8578  8578 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 09:55:12.599  8578  8578 I UEI.SmartControl: configuring settings for MAXQ616
08-05 09:55:12.600  8578  8578 I UEI.SmartControl: Get version...
08-05 09:55:12.617  8578  8627 D UEI.SmartControl: serial port data available: 21
,08-05 09:55:12.649  8578  8578 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 09:55:12.649  8578  8578 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-05 09:55:12.650  8578  8578 I UEI.SmartControl: QS saving settings...
08-05 09:55:12.652  8578  8578 D UEI.SmartControl: IR Blaster version: 25672567
08-05 09:55:12.670  8578  8627 D UEI.SmartControl: serial port data available: 4
,08-05 09:55:12.712  8578  8630 I UEI.SmartControl: Device manager: loading config....
,08-05 09:55:12.716  8578  8630 D UEI.SmartControl: ----------- loading internal config...
08-05 09:55:12.717  8578  8578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 09:55:12.726  8578  8578 E UEI.SmartControl: Services init done
08-05 09:55:12.727  8578  8578 D UEI.SmartControl: QS Service init finished
08-05 09:55:12.729  8578  8578 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 09:55:12.729  8578  8578 D UEI.SmartControl: QS Service version code: 201091
08-05 09:55:12.732  8578  8578 D UEI.SmartControl: Service requested: Control
,08-05 09:55:12.738  8578  8578 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 09:55:12.740  8578  8578 D UEI.SmartControl: Service.onUnbind: IControl
08-05 09:55:12.742  8578  8630 E UEI.SmartControl: Loading SETTINGS...
08-05 09:55:12.745  8578  8578 D UEI.SmartControl: Service.onDestroy
08-05 09:55:12.745  8578  8578 D UEI.SmartControl: Lock is in USE false
08-05 09:55:12.745  8578  8578 D UEI.SmartControl: unbind internal service
,08-05 09:55:12.750  8578  8629 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 09:55:12.751  8578  8629 D UEI.SmartControl: -----service ready thread exits
08-05 09:55:12.751  8578  8578 D serial_port: close(fd = 25)
08-05 09:55:12.754  8578  8578 I UEI.SmartControl: Serial port is closed.
08-05 09:55:12.754  8578  8578 I UEI.SmartControl: Serial port is closed.
08-05 09:55:12.754  8578  8578 D UEI.SmartControl: Blaster closed
08-05 09:55:12.755  8578  8578 D UEI.SmartControl: Shut down QS...
08-05 09:55:12.755  8578  8578 D UEI.SmartControl: Stopping QS lib
08-05 09:55:12.755  8578  8578 D UEI.SmartControl: QS lib stop result = true
08-05 09:55:12.755  8578  8578 D UEI.SmartControl: Stopped QS lib
08-05 09:55:12.755  8578  8578 D UEI.SmartControl: Stopped file observer...
08-05 09:55:12.756  8578  8578 D UEI.SmartControl: QS shutdown complete
08-05 09:55:12.758  8578  8578 D UEI.SmartControl: QS Service created
08-05 09:55:12.758  8578  8630 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-05 09:55:12.773  8578  8578 I UEI.SmartControl: Service initServices...
08-05 09:55:12.773  8578  8578 D UEI.SmartControl: QS start get config
,08-05 09:55:13.210  8578  8578 I UEI.SmartControl: Supports setup maps: true
,08-05 09:55:13.215  8578  8578 D UEI.SmartControl: QS start statue = true Error code = 0
,08-05 09:55:13.216  8578  8578 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 09:55:13.216  8578  8578 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 09:55:13.216  8578  8578 I UEI.SmartControl: ### init IR Blaster...
08-05 09:55:13.220  8578  8578 D serial_port: Configuring serial port
08-05 09:55:13.220  8578  8578 E UEI.SmartControl: UEIBLaster setting for 616
08-05 09:55:13.220  8578  8578 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 09:55:13.220  8578  8578 I UEI.SmartControl: configuring settings for MAXQ616
08-05 09:55:13.220  8578  8578 I UEI.SmartControl: Get version...
08-05 09:55:13.236  8578  8636 D UEI.SmartControl: serial port data available: 21
,08-05 09:55:13.262  8578  8578 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 09:55:13.262  8578  8578 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 09:55:13.263  8578  8578 I UEI.SmartControl: QS saving settings...
,08-05 09:55:13.264  8578  8578 D UEI.SmartControl: IR Blaster version: 25672567
08-05 09:55:13.283  8578  8636 D UEI.SmartControl: serial port data available: 4
,08-05 09:55:13.314  8578  8578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 09:55:13.318  8578  8639 I UEI.SmartControl: Device manager: loading config....
08-05 09:55:13.319  8578  8639 D UEI.SmartControl: ----------- loading internal config...
08-05 09:55:13.322  8578  8578 E UEI.SmartControl: Services init done
08-05 09:55:13.322  8578  8578 D UEI.SmartControl: QS Service init finished
08-05 09:55:13.326  8578  8578 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 09:55:13.326  8578  8578 D UEI.SmartControl: QS Service version code: 201091
08-05 09:55:13.327  8578  8578 D UEI.SmartControl: Service requested: Control
08-05 09:55:13.332  8578  8578 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 09:55:13.333  8578  8639 E UEI.SmartControl: Loading SETTINGS...
,08-05 09:55:13.339  1037  1870 I ActivityManager: Killing 8240:com.lge.email/u0a23 (adj 15): empty #17
08-05 09:55:13.341  8578  8639 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 09:55:13.357  8578  8638 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 09:55:13.357  8578  8638 D UEI.SmartControl: -----service ready thread exits
,08-05 09:55:13.368  1037  1956 W libprocessgroup: failed to open /acct/uid_10023/pid_8240/cgroup.procs: No such file or directory
08-05 09:55:13.370  8578  8578 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@369a0d4a that was originally bound here
08-05 09:55:13.370  8578  8578 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@369a0d4a that was originally bound here
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:55:13.370  8578  8578 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 09:55:13.372  8578  8578 D UEI.SmartControl: Internal service binding...
,08-05 09:55:13.746  8578  8632 D UEI.SmartControl: Internal timer expired: 2
,08-05 09:55:14.073  1037  1377 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=15.1, 0.0, 0.0  rx=12.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1504898841] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 09:55:14.083  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=15.1, 0.0, 0.0  rx=12.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1504898851] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 09:55:14.083  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 09:55:17.104  1037  1377 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=7.6, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1504901872] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 09:55:17.113  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=7.6, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1504901881] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 09:55:17.113  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 09:55:17.141  8578  8594 E UEI.SmartControl: file observer is disposed!
,08-05 09:55:18.314  8578  8640 D UEI.SmartControl: Internal timer expired: 3
,08-05 09:55:18.314  8578  8640 D UEI.SmartControl: unbind internal service
,08-05 09:55:18.337  8578  8578 D UEI.SmartControl: Service.onUnbind: IControl
,08-05 09:55:18.340  8578  8578 D UEI.SmartControl: Service.onDestroy
08-05 09:55:18.340  8578  8578 D UEI.SmartControl: Lock is in USE false
08-05 09:55:18.340  8578  8578 D UEI.SmartControl: unbind internal service
08-05 09:55:18.341  8578  8578 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1050a36d
08-05 09:55:18.341  8578  8578 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-05 09:55:18.341  8578  8578 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-05 09:55:18.341  8578  8578 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-05 09:55:18.341  8578  8578 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-05 09:55:18.341  8578  8578 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-05 09:55:18.341  8578  8578 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-05 09:55:18.342  8578  8578 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-05 09:55:18.342  8578  8578 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-05 09:55:18.342  8578  8578 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 09:55:18.342  8578  8578 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:55:18.342  8578  8578 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:55:18.342  8578  8578 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 09:55:18.342  8578  8578 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 09:55:18.342  8578  8578 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:55:18.342  8578  8578 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 09:55:18.342  8578  8578 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1050a36d
08-05 09:55:18.344  8578  8578 D serial_port: close(fd = 24)
08-05 09:55:18.347  8578  8578 I UEI.SmartControl: Serial port is closed.
08-05 09:55:18.347  8578  8578 I UEI.SmartControl: Serial port is closed.
08-05 09:55:18.347  8578  8578 D UEI.SmartControl: Blaster closed
08-05 09:55:18.347  8578  8578 D UEI.SmartControl: Shut down QS...
08-05 09:55:18.347  8578  8578 D UEI.SmartControl: Stopping QS lib
08-05 09:55:18.347  8578  8578 D UEI.SmartControl: QS lib stop result = true
08-05 09:55:18.347  8578  8578 D UEI.SmartControl: Stopped QS lib
08-05 09:55:18.347  8578  8578 D UEI.SmartControl: QS shutdown complete
08-05 09:55:18.698  1588  1588 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 09:55:18.699  1588  1588 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 09:55:18.725  1037  1418 D WifiController: battery changed pluggedType: 2
,08-05 09:55:18.730  1925  2078 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 09:55:18.730  1925  2078 D LEDHandler: Battery Level Remaining: 100%
08-05 09:55:18.730  1925  2078 D LEDHandler: Battery Temp: 289, mChargingStatus=5, mChargingStop=false
08-05 09:55:18.731  1588  1588 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
08-05 09:55:18.732  1588  1588 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 09:55:18.733  7655  7881 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 09:55:18.735  1588  1588 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 09:55:18.737  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:55:18.737  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 09:55:20.128  1037  1377 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1504904896] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 09:55:20.129  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1504904897] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 09:55:20.129  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 09:55:21.828  1037  1377 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 09:55:21.828  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 09:55:21.829  1037  1377 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 09:55:21.829  1037  1377 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 09:55:21.830  1037  1377 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 09:55:21.830  1037  1377 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-05 09:55:22.230  6709  6778 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-05 09:55:22.230  6709  6778 I jxcore-log: 
,08-05 09:55:22.561  8644  8644 D AndroidRuntime: 
08-05 09:55:22.561  8644  8644 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 09:55:22.568  8644  8644 D AndroidRuntime: CheckJNI is OFF
08-05 09:55:22.690  8644  8644 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 09:55:22.701  1037  1112 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-05 09:55:22.701  1037  1112 I ActivityManager: Killing 6709:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-05 09:55:22.772  1037  2015 I WindowState: WIN DEATH: Window{3dd23b15 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 09:55:22.774  1037  1418 D WifiService: Client connection lost with reason: 4
08-05 09:55:22.781  1037  2015 D InputDispatcher: Window went away: Window{3dd23b15 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 09:55:22.928  1037  1112 I ActivityManager:   Force finishing activity ActivityRecord{234d9196 u0 com.test.thalitest/.MainActivity t40}
,08-05 09:55:22.992   376   404 E GBMv2   : DFP En is all cleared set to be enabled
,08-05 09:55:22.997  1037  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-05 09:55:23.000  1037  1125 I ActivityManager:   Force finishing activity ActivityRecord{234d9196 u0 com.test.thalitest/.MainActivity t40 f}
08-05 09:55:23.001  1037  1125 W ActivityManager: Duplicate finish request for ActivityRecord{234d9196 u0 com.test.thalitest/.MainActivity t40 f}
,08-05 09:55:23.035  1037  1994 W ActivityManager: Spurious death for ProcessRecord{ddc5cf5 6709:com.test.thalitest/u0a118}, curProc for 6709: null
,08-05 09:55:23.036  2017  2017 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-05 09:55:23.037  2017  2017 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-05 09:55:23.048  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-05 09:55:23.049  2017  2111 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-05 09:55:23.050  1925  1940 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-05 09:55:23.050  1925  1940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{724d24b co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 09:55:23.052  1925  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-05 09:55:23.052  1925  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{33c29428 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 09:55:23.059  1889  1889 D ActionManagerService: notifyUserLog: 1000003
08-05 09:55:23.059  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-05 09:55:23.060  3840  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-05 09:55:23.061  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-05 09:55:23.064  1037  1367 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 09:55:23.075  4609  4609 I art     : Explicit concurrent mark sweep GC freed 15464(887KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 2.434ms total 67.945ms
08-05 09:55:23.080  3840  3840 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-05 09:55:23.081  1979  1979 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 09:55:23.082  7655  7655 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-05 09:55:23.082  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 09:55:23.088  2487  2641 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 09:55:23.089  1037  1109 W InputMethodInfo: Duplicated subtype definition found: , voice
08-05 09:55:23.142  4510  4510 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 09:55:23.142  4510  4510 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 09:55:23.142  4510  4510 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 09:55:23.142  4510  4510 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-05 09:55:23.142  4510  4510 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 09:55:23.142  4510  4510 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 09:55:23.142  4510  4510 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:55:23.142  4510  4510 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:55:23.142  4510  4510 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 09:55:23.142  4510  4510 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 09:55:23.142  4510  4510 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:55:23.142  4510  4510 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 09:55:23.144  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-05 09:55:23.148  2017  2017 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-05 09:55:23.149  1037  1377 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1504907916] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 09:55:23.149  2017  2017 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-05 09:55:23.151  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-05 09:55:23.152  2017  2017 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-05 09:55:23.155  1889  1889 D ActionManagerService: notifyUserLog: 1000004
08-05 09:55:23.155  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-05 09:55:23.156  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-05 09:55:23.156  3840  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-05 09:55:23.157  1037  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1504907925] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 09:55:23.157  1037  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 09:55:23.158  3840  4495 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 09:55:23.160  1588  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 09:55:23.160  1588  1651 D KeyguardModel: createShortcutInfo...
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262123
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , display: false
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , animation: false }
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262287
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , display: false
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , animation: false }
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , create_time: 1469801565454
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , display: false
08-05 09:55:23.161  2017  2017 I GBoardWebViewUtils: , animation: false }
08-05 09:55:23.168  1037  1871 V SIM_STK : Menu title from STK is T-Mobile
,08-05 09:55:23.179  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 09:55:23.179  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-05 09:55:23.186  1588  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 09:55:23.186  1588  1651 D KeyguardModel: createShortcutInfo...
,08-05 09:55:23.192  2196  2196 I ConfigService: onCreate
08-05 09:55:23.193  2196  2196 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 09:55:23.196  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-05 09:55:23.197  1588  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 09:55:23.198  1588  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:55:23.198  1588  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 09:55:23.198  1588  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 09:55:23.199  1588  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 09:55:23.199  1588  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 09:55:23.201  2017  8675 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-05 09:55:23.206  2196  2196 I ConfigService: onBind returning update interface
08-05 09:55:23.207  1588  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 09:55:23.207  1588  1651 D KeyguardModel: createShortcutInfo...
,08-05 09:55:23.211  2196  2196 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 09:55:23.211  2196  2196 I ConfigService: onBind returning config service
08-05 09:55:23.212  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-05 09:55:23.213  1853  1853 D SplitUIService: removed split : 
08-05 09:55:23.216  2196  2196 I ConfigService: onDestroy
08-05 09:55:23.217  1588  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 09:55:23.217  1588  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 09:55:23.218  1588  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 09:55:23.219  1588  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 09:55:23.223  1588  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 09:55:23.223  1588  1651 D KeyguardModel: createShortcutInfo...
,08-05 09:55:23.226  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-05 09:55:23.228  1801  8678 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-05 09:55:23.232  1588  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:55:23.232  1588  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 09:55:23.232  1588  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 09:55:23.232  1588  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 09:55:23.237  1588  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 09:55:23.237  1588  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-05 09:55:23.241  1037  1037 I art     : Explicit concurrent mark sweep GC freed 46731(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.443ms total 221.711ms
08-05 09:55:23.243  1037  1125 I art     : WaitForGcToComplete blocked for 196.114ms for cause Explicit
08-05 09:55:23.244  1588  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 09:55:23.244  1588  1651 D KeyguardModel: createShortcutInfo...
08-05 09:55:23.275  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
08-05 09:55:23.275  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
08-05 09:55:23.276  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-05 09:55:23.276  1853  1853 I SplitUIService: split app #11
,08-05 09:55:23.306  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-05 09:55:23.315  1037  1037 D administrator: Handling package changes for user 0
08-05 09:55:23.319  5952  8686 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-05 09:55:23.322  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-05 09:55:23.322  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 09:55:23.328  1037  1972 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 09:55:23.328  1801  8688 I PeopleContactsSync: CP2 sync disabled
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 09:55:23.329  7655  7655 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 09:55:23.330  2017  2017 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-05 09:55:23.331  1588  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 09:55:23.331  1588  1651 D KeyguardModel: createShortcutInfo...
08-05 09:55:23.346  1801  8684 W GmsApplication: Using Auth Proxy for data requests.
,08-05 09:55:23.347  7008  7008 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-05 09:55:23.356  1588  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 09:55:23.356  1588  1651 D KeyguardModel: createShortcutInfo...
08-05 09:55:23.358  1588  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 09:55:23.358  1588  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 09:55:23.360  1588  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 09:55:23.360  1588  1651 D KeyguardModel: createShortcutInfo...
08-05 09:55:23.361  1588  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 09:55:23.362  1588  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 09:55:23.362  1588  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 09:55:23.362  1588  1651 D KeyguardModel: createShortcutInfo...
08-05 09:55:23.363  1037  1052 V SIM_STK : Menu title from STK is T-Mobile
,08-05 09:55:23.366  1588  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 09:55:23.366  1588  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 09:55:23.368  1588  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 09:55:23.368  1588  1651 D KeyguardModel: createShortcutInfo...
08-05 09:55:23.372  1801  4786 I Icing   : doRemovePackageData com.test.thalitest
,08-05 09:55:23.380  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-05 09:55:23.380  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 09:55:23.390  1801  8684 W GmsApplication: Using Auth Proxy for data requests.
,08-05 09:55:23.396  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-05 09:55:23.396  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 09:55:23.396  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 09:55:23.409  1037  1972 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8691 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 09:55:23.411  1037  1563 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-05 09:55:23.415  2325  8690 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-05 09:55:23.432  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-05 09:55:23.435  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:55:23.437  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-05 09:55:23.438  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-05 09:55:23.439  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-05 09:55:23.440  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-05 09:55:23.453  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{653ba40 u0 com.lge.launcher2/.Launcher t39} time:373438
,08-05 09:55:23.459  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-05 09:55:23.460  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:55:23.462  2017  2148 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,08-05 09:55:23.462  2017  2148 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-05 09:55:23.475  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-05 09:55:23.475  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 09:55:23.476  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:55:23.491  2017  2017 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-05 09:55:23.493  8691  8691 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 09:55:23.493  8691  8691 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 09:55:23.493  2579  2579 D [Concierge]Service: onStartCommand(). Type : 8
08-05 09:55:23.493  2579  2579 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-05 09:55:23.494  8691  8691 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 09:55:23.494  8691  8691 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 09:55:23.496  2579  2579 D [Concierge]Service: Update widget ID : 11
08-05 09:55:23.497  2017  2017 D [Concierge]WidgetView: change position of spinner
08-05 09:55:23.499  2017  2017 I [Concierge]WidgetView: initWebView(). Time : 1470383723498
08-05 09:55:23.499  2579  2579 D [Concierge]Service: onStartCommand(). Type : 0
08-05 09:55:23.508  1801  1813 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 09:55:23.509  1801  1813 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 09:55:23.509  1801  1813 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 09:55:23.509  2017  2017 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 593283069
08-05 09:55:23.509  2017  2017 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-05 09:55:23.510  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 09:55:23.512  2017  2017 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@387d6b7d
08-05 09:55:23.512  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-05 09:55:23.513  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 09:55:23.513  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:55:23.514   334   391 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-05 09:55:23.515  3154  8711 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-05 09:55:23.515  1801  8709 I art     : Explicit concurrent mark sweep GC freed 37113(2MB) AllocSpace objects, 29(456KB) LOS objects, 51% free, 30MB/62MB, paused 782us total 32.331ms
,08-05 09:55:23.520  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-05 09:55:23.520  2017  2017 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-05 09:55:23.520  2017  2017 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 09:55:23.521  2017  2017 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470383378004, New one : 1470383723498
08-05 09:55:23.521  2017  2017 D [Concierge]WidgetView: Unregister all receivers
08-05 09:55:23.521  2017  2017 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 09:55:23.522  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:55:23.523  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-05 09:55:23.524  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-05 09:55:23.525  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-05 09:55:23.526  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-05 09:55:23.527  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-05 09:55:23.531  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:55:23.531  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:55:23.560  1037  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 09:55:23.569  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 09:55:23.572  1037  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-05 09:55:23.576  1037  1125 I art     : Explicit concurrent mark sweep GC freed 12263(637KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.561ms total 332.873ms
08-05 09:55:23.577  2017  2017 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-05 09:55:23.577  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-05 09:55:23.579  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 09:55:23.597  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-05 09:55:23.601  2017  2017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3437aae time:373585
08-05 09:55:23.610  8691  8691 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 09:55:23.622  8691  8691 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-05 09:55:23.640  8691  8691 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 09:55:23.651  8644  8644 D AndroidRuntime: Shutting down VM
,08-05 09:55:23.658  8691  8691 D LgDataFeature: LgDataFeature() Constructor: none
08-05 09:55:23.659  8691  8691 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 09:55:23.704  8691  8691 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-05 09:55:23.707  2017  2017 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-05 09:55:23.714  1037  1052 I ActivityManager: Killing 8000:com.lge.formmanager/u0a26 (adj 15): empty #17
08-05 09:55:23.740  2017  2868 I GBoardtInterface: onReloaded()
,08-05 09:55:23.742  2017  2017 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-05 09:55:23.806  1979  1979 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 09:55:23.806  1979  1979 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-05 09:55:23.806  1037  1956 W libprocessgroup: failed to open /acct/uid_10026/pid_8000/cgroup.procs: No such file or directory
,08-05 09:55:23.809  1979  1979 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-05 09:55:23.810  3840  4495 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 09:55:23.813  8072  8072 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-05 09:55:23.815  3840  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 09:55:23.845  1037  1870 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8717 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-05 09:55:23.851  1889  1889 D ActionManagerService: notifyUserLog: 1000001
08-05 09:55:23.852  3840  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 09:55:23.852  3840  4499 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 09:55:23.857  1889  1889 D ActionManagerService: notifyUserLog: 1000001
08-05 09:55:23.858  3840  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 09:55:23.858  3840  4499 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 09:55:23.858  3840  4499 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
,08-05 09:55:23.858  3840  4499 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-05 09:55:23.859  3840  4495 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 09:55:23.861  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-05 09:55:23.861  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-05 09:55:23.863  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-05 09:55:23.863  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 09:55:23.866  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-05 09:55:23.866  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 09:55:23.897  1037  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8737 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-05 09:55:23.946  1037  1871 I ActivityManager: Killing 8205:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-05 09:55:23.968  8717  8717 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:55:23.968  8717  8717 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: Unable to open database for writing.
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 09:55:23.969  8717  8717 E Lifetra,ckerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 09:55:23.969  8717  8717 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-05 09:55:24.026   280   795 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
