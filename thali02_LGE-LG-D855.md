#### Test 846487404bc066c_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-13 11:58:00.076  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-13 11:58:00.077  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 11:58:00.077  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-13 11:58:00.077  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,09-13 11:58:00.091  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 11:58:00.091  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
09-13 11:58:00.092  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
09-13 11:58:00.093  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 11:58:00.406  6693  6693 D AndroidRuntime: 
09-13 11:58:00.406  6693  6693 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 11:58:00.413  6693  6693 D AndroidRuntime: CheckJNI is OFF
09-13 11:58:00.613  6693  6693 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 11:58:00.624  1035  1649 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 11:58:00.639  1940  1956 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 11:58:00.645  1035  1649 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 11:58:00.647  1035  1649 D ActivityManager: setTaskToReturnTo : TaskRecord{849f4d0 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 11:58:00.647  1035  1649 D ActivityManager: setTaskToReturnTo : TaskRecord{849f4d0 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 11:58:00.649  1035  1649 D WindowStateEx: AppWindowTokenEx init.. 
09-13 11:58:00.649   341   367 E GBMv2   : DFP En is all cleared set to be enabled
09-13 11:58:00.678  1035  1649 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6708 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 11:58:00.681  6693  6693 D AndroidRuntime: Shutting down VM
09-13 11:58:00.754  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 11:58:00.755  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{39fa1121 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 11:58:00.757  1940  3372 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 11:58:00.757  1940  3372 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1378946 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 11:58:00.825  6708  6708 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-13 11:58:00.938  6708  6708 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 11:58:00.949  6708  6708 I LibraryLoader: Loading: webviewchromium
,09-13 11:58:00.953  6708  6708 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3830-3834)
09-13 11:58:00.953  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 11:58:00.972  6708  6708 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {218cf877}
,09-13 11:58:00.973  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 11:58:00.974  6708  6708 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 11:58:00.984  6708  6708 I BrowserStartupController: Initializing chromium process, renderers=0
,09-13 11:58:00.985  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 11:58:01.002  6708  6708 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 11:58:01.003  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-13 11:58:01.003  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,09-13 11:58:01.005   317  1397 V AudioPolicyService: registerClient() client 0xb558a7c0, uid 10118
09-13 11:58:01.010  1035  1111 D BluetoothManagerService: Message: 20
09-13 11:58:01.010  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@700eada:true
09-13 11:58:01.033  6708  6708 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 11:58:01.033  6708  6708 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 11:58:01.033  6708  6708 I Adreno-EGL: Build Date: 12/12/14 금
09-13 11:58:01.033  6708  6708 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 11:58:01.033  6708  6708 I Adreno-EGL: Remote Branch: 
09-13 11:58:01.033  6708  6708 I Adreno-EGL: Local Patches: 
09-13 11:58:01.033  6708  6708 I Adreno-EGL: Reconstruct Branch: 
,09-13 11:58:01.109  6708  6749 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
09-13 11:58:01.111  6708  6708 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,09-13 11:58:01.126  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 11:58:01.130  6708  6708 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 11:58:01.133  6708  6708 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 11:58:01.135  6708  6708 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 11:58:01.135  6708  6708 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-13 11:58:01.149  6708  6708 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 11:58:01.155  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 11:58:01.155  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 11:58:01.188  6708  6761 D OpenGLRenderer: Render dirty regions requested: true
09-13 11:58:01.188  6708  6761 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 11:58:01.212  6708  6761 D OpenGLRenderer: Enabling debug mode 0
,09-13 11:58:01.228  6708  6708 D Atlas   : Validating map...
,09-13 11:58:01.234  1035  1880 D SplitWindow: check instance of lgWin Window{29c256c4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 11:58:01.291  6708  6759 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:01.291  6708  6759 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:01.353  1035  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +599ms (total +702ms)
,09-13 11:58:01.353  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{38f4ccc9 u0 com.test.thalitest/.MainActivity t6} time:174235
,09-13 11:58:01.362  6708  6708 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d3ca5b2 time:174244
09-13 11:58:01.474  6708  6708 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 11:58:01.474  6708  6708 I chromium: 
,09-13 11:58:01.546  6708  6708 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 11:58:01.634  6708  6759 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 11:58:01.634  6708  6759 I chromium: 
,09-13 11:58:01.768  6708  6775 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,09-13 11:58:01.788  6708  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 11:58:01.788  6708  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 11:58:01.788  6708  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 11:58:01.788  6708  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 11:58:01.788  6708  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 11:58:01.789  6708  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfdbd6 added. We now have 1 listener(s)
09-13 11:58:01.797  1035  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 11:58:01.801  6708  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-13 11:58:01.803  6708  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:01.805  6708  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:01.805  6708  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 11:58:01.814  6708  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e9be2d added. We now have 1 listener(s)
09-13 11:58:01.814  6708  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:58:01.819  1035  1441 D WifiService: New client listening to asynchronous messages
09-13 11:58:01.823  6708  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:58:01.823  6708  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 11:58:01.823  6708  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 11:58:01.823  6708  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 11:58:01.824  6708  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 11:58:01.828  6708  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:58:01.833  1035  1696 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:01.834  6708  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-13 11:58:01.845  6708  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-13 11:58:01.845  6708  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:01.845  6708  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:01.845  6708  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:01.845  6708  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:01.845  6708  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:01.845  6708  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:01.845  6708  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:01.845  6708  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:01.847  6708  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 11:58:01.847  6708  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:01.849  6708  6775 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 11:58:01.852  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:01.854  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:01.919  6708  6708 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 11:58:02.004   341   372 E GBMv2   : DFP En is all cleared set to be enabled
09-13 11:58:02.004   341   372 E GBMv2   : Set value is all cleared set the max
09-13 11:58:02.004   341   372 I GBMv2   : DFP Enabled. Ignore VFP set
,09-13 11:58:02.944  6708  6778 W jxcore-log: Initializing JXcore engine
09-13 11:58:02.944  6708  6778 W jxcore-log: JXcore engine is ready
,09-13 11:58:03.046  6778  6778 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8430]" dev="sockfs" ino=8430 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-13 11:58:03.046  6778  6778 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-13 11:58:03.046  6778  6778 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7550]" dev="sockfs" ino=7550 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 11:58:03.046  6778  6778 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-13 11:58:03.046  6778  6778 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31907]" dev="sockfs" ino=31907 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-13 11:58:03.087  6708  6778 W jxcore-log: Starting JXcore engine
,09-13 11:58:03.250  6708  6778 W jxcore-log: Platform android
09-13 11:58:03.250  6708  6778 W jxcore-log: 
09-13 11:58:03.250  6708  6778 W jxcore-log: Process ARCH arm
09-13 11:58:03.250  6708  6778 W jxcore-log: 
,09-13 11:58:03.627  6708  6778 I jxcore-log: JXcore Cordova bridge is ready!
09-13 11:58:03.627  6708  6778 I jxcore-log: 
09-13 11:58:03.627  6708  6778 W jxcore-log: JXcore engine is started
,09-13 11:58:03.633  6708  6775 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 11:58:03.637  6708  6708 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 11:58:14.197  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 11:58:14.197  6708  6778 I jxcore-log: 
,09-13 11:58:14.200  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 11:58:14.200  6708  6778 I jxcore-log: 
09-13 11:58:14.204  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:14.204  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:14.204  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:14.204  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:14.204  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:14.204  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.204  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:14.204  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:14.207  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.210  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 11:58:14.210  6708  6778 I jxcore-log: 
,09-13 11:58:14.212  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 11:58:14.212  6708  6778 I jxcore-log: 
,09-13 11:58:14.710  6708  6778 D executeNativeTests: Running unit tests
,09-13 11:58:14.794  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:14.794  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd added. We now have 2 listener(s)
09-13 11:58:14.795  1035  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 11:58:14.797  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:14.797  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:14.797  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:14.797  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:14.797  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 added. We now have 2 listener(s)
09-13 11:58:14.797  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:14.797  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:58:14.800  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:14.803  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:14.803  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:14.803  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:14.803  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:14.803  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:14.803  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.803  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:14.803  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:14.805  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.805  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:14.806  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:14.808  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:14.810  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 11:58:14.810  6708  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:58:14.810  6708  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:58:14.812  6708  6778 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 11:58:14.813  6708  6778 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 11:58:14.813  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 11:58:14.813  6708  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:58:14.813  6708  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:58:14.814  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.814  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.814  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.815  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.815  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.815  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:14.815  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:14.815  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd removed from the list
09-13 11:58:14.815  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.815  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 removed from the list
09-13 11:58:14.815  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.815  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.816  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.816  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.817  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.817  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:14.817  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.817  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.819  6708  6778 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 11:58:14.819  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.819  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.819  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.820  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.820  6708  6778 W org.thaliprojec,t.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.820  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.820  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:14.820  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.820  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.820  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.820  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.820  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.820  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.820  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.821  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.821  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:14.821  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.821  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410],
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 11:58:14.825  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 11:58:14.826  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 11:58:14.826  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
09-13 11:58:14.826  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.826  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.826  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.826  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.826  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.826  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:58:14.826  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:14.826  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.826  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.826  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.826  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.826  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.826  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 11:58:14.826  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.827  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.827  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:14.827  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.827  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.827  6708  6778 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 11:58:14.829  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:14.833  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:14.833  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:14.833  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:14.833  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:14.833  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:14.833  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.833  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:14.833  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
09-13 11:58:14.833  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.833  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:14.835  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:14.835  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:58:14.836  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:58:14.836  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:58:14.836  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:58:14.836  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:14.836  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:58:14.841  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 11:58:14.841  1035  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:14.844  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:58:14.848  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
09-13 11:58:14.849  6708  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 11:58:14.851  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:58:14.851  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:14.852  6708  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 11:58:14.853  6708  6778 I io.jxcore.node.ConnectionHelper: start: OK
09-13 11:58:14.855  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:58:14.855  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.855  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.855  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.855  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.855  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:14.855  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
,09-13 11:58:14.855  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.855  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.855  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.855  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:58:14.856  6708  6778 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 11:58:14.857  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:14.859  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:14.859  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:14.859  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:14.859  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:14.859  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:14.859  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.859  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:14.859  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:58:14.860  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.860  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:14.862  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:14.862  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:58:14.862  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:58:14.862  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:58:14.862  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:14.862  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:58:14.864  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:14.866  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:58:14.866  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:14.867  6708  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 11:58:14.867  6708  6778 I io.jxcore.node.ConnectionHelper: start: OK
09-13 11:58:14.869  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.869  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.869  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.869  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.869  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.869  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:14.869  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:14.869  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.869  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.869  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.869  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.870  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.870  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.870  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.870  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:58:14.874  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:14.874  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:14.874  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.874  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.875  6708  6778 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 11:58:14.948  1035  1895 I art     : Explicit concurrent mark sweep GC freed 32409(1513KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.341ms total 71.964ms
,09-13 11:58:14.949  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:14.951  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:14.951  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:14.951  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:14.951  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:14.951  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:14.951  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.951  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:14.951  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:14.952  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:14.952  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:14.952  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:58:14.952  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:58:14.952  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:58:14.952  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:14.952  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:58:14.955  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:14.956  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:14.959  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:58:14.960  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:58:14.961  6708  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 11:58:14.961  6708  6778 I io.jxcore.node.ConnectionHelper: start: OK
09-13 11:58:14.962  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.962  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.962  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.963  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.964  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.964  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.965  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.965  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.965  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:14.966  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:14.966  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.966  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.966  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.966  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.968  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.968  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.969  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.969  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:14.970  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:14.970  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:14.970  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.970  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.971  6708  6778 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 11:58:14.971  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.971  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.971  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, s,kipping...
09-13 11:58:14.971  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.971  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.971  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.971  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:14.971  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.971  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.971  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.971  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.971  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.971  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.971  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.972  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.972  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:14.973  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:14.973  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:14.973  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.973  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.974  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 11:58:14.974  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.974  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.974  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.975  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.975  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.975  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.975  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:14.975  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.975  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.975  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.975  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.975  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.975  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.975  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.976  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.976  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:14.976  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:14.976  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:14.976  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.976  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.977  6708  6778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 11:58:14.977  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.977  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.977  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.978  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.978  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.978  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.978  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:14.978  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.978  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.978  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.978  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.978  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.978  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.978  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.979  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.979  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:14.980  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:14.980  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:14.980  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.980  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.981  6708  6778 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 11:58:14.981  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.981  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.981  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.981  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.981  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.981  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.981  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:14.981  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.981  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.981  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.981  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.981  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.982  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.982  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.983  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.983  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:14.983  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:14.983  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:14.983  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.983  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.984  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 11:58:14.985  6708  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:58:14.985  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 11:58:14.985  6708  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:58:14.985  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 11:58:14.985  6708  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:58:14.985  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:14.986  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:14.986  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:14.986  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:14.986  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.986  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.986  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:14.986  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.986  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.986  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:14.986  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.986  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.986  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:14.986  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:14.988  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:14.988  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:14.989  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:14.989  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:14.989  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:14.989  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:14.992  6708  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:58:14.992  6708  6778 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 11:58:14.992  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 11:58:14.997  6708  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:58:14.997  6708  6778 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 11:58:14.997  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 11:58:14.998  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 11:58:14.999  6708  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 11:58:14.999  6708  6778 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 11:58:14.999  6708  6778 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 11:58:14.999  6708  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:58:14.999  6708  6778 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 11:58:14.999  6708  6778 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 11:58:14.999  6708  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:58:14.999  6708  6778 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 11:58:14.999  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 11:58:15.003  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 11:58:15.005  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 11:58:15.005  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 11:58:15.006  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 11:58:15.006  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 11:58:15.006  6708  6778 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 11:58:15.007  6708  6778 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:58:15.007  6708  6778 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 11:58:15.007  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:15.007  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:15.007  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:15.007  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.007  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.007  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.008  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 11:58:15.009  6708  6795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 837)
09-13 11:58:15.018  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.018  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.018  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.018  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.018  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.018  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.018  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.018  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.019  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:15.019  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:15.020  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:15.020  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:15.020  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.020  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.021  6708  6778 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 11:58:15.021  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:15.021  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:15.021  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:15.022  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.022  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.022  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.022  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.022  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.022  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.022  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.022  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.022  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.022  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.022  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.024  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:15.024  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:15.024  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:15.024  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:15.024  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.024  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.025  6708  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 11:58:15.025  6708  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 837
09-13 11:58:15.026  6708  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 837)
09-13 11:58:15.026  6708  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 837)
09-13 11:58:15.029  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:15.029  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:15.029  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:15.029  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.029  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.029  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.029  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.029  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.029  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.029  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.029  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.029  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.029  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.030  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.030  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:15.030  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:15.031  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:15.031  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:15.031  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.031  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.032  6708  6778 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 11:58:15.032  6708  6778 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 11:58:15.032  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 11:58:15.032  6708  6778 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 11:58:15.032  6708  6778 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 11:58:15.032  6708  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 11:58:15.032  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 11:58:15.033  6708  6778 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 11:58:15.033  6708  6778 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 11:58:15.033  6708  6778 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 11:58:15.033  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 11:58:15.033  6708  6778 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 11:58:15.033  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:15.033  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:15.033  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:15.034  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.034  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.034  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.034  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.034  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.034  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.034  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.034  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.034  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.034  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.034  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.036  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:15.036  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:15.037  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:15.037  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:15.037  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.037  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.038  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.038  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.038  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.038  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.038  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.038  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.038  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.038  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.038  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.039  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.039  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.039  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.039  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.039  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.039  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.039  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:15.039  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:15.039  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:15.040  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.040  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.040  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.040  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.040  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.040  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.040  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.040  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.040  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.040  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.040  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.041  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:15.041  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:15.042  6708  6778 D BluetoothLeScanner: could not find callback wrapper
,09-13 11:58:15.042  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:15.042  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.042  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.044  6708  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 11:58:15.044  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:15.045  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 11:58:15.045  6708  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 11:58:15.046  6708  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 11:58:15.046  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 11:58:15.047  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 11:58:15.047  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:58:15.047  1035  1880 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:15.048  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.048  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 11:58:15.048  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 11:58:15.048  6708  6797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:15.048  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 11:58:15.048  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.048  6708  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 11:58:15.049  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 11:58:15.049  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.049  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.049  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:58:15.049  6708  6778 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 11:58:15.049  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:58:15.050  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:58:15.051  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:15.051  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:15.051  6708  6778 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:58:15.051  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.051  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.052  3853  3976 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 m,Fd=82
09-13 11:58:15.053  6708  6778 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:58:15.053  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:58:15.053  6708  6797 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 11:58:15.053  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:58:15.053  6708  6708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:58:15.053  6708  6797 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 11:58:15.054  6708  6797 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 11:58:15.054  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.054  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:15.054  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:15.054  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:15.055  6708  6708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 11:58:15.055  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.055  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.055  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.055  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.055  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.055  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.055  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.056  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.056  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.056  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.056  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:58:15.057  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:15.057  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:15.057  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.057  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
,09-13 11:58:15.060  6708  6778 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 11:58:15.060  6708  6778 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 11:58:15.060  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 11:58:15.060  6708  6778 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:58:15.060  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:15.061  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:15.061  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:15.061  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.061  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.061  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.061  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.061  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.061  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.061  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.061  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.061  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.061  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.061  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.063  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:15.063  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:15.063  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.064  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.066  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:15.066  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:15.067  1035  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:15.068  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:15.068  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:15.0,68  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:15.068  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.068  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.068  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.069  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list
09-13 11:58:15.069  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.069  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.069  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.069  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.069  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.069  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.069  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.071  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:15.071  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:15.071  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.071  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
,09-13 11:58:15.072  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-13 11:58:15.072  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:15.072  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:15.072  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:15.072  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:58:15.072  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.072  6708  6778 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b052fbd not in the list,
09-13 11:58:15.073  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.073  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list,
09-13 11:58:15.073  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:15.073  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 11:58:15.073  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.073  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:15.073  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:15.074  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:58:15.074  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:15.074  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:15.074  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef19b2 not in the list
09-13 11:58:15.076  6708  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-13 11:58:15.076  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 11:58:15.077  6708  6778 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 11:58:15.077  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 11:58:15.077  6708  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 11:58:15.077  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 11:58:15.079  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
09-13 11:58:15.080  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 11:58:15.080  6708  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 11:58:15.081  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 11:58:15.081  6708  6778 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 11:58:15.081  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-13 11:58:15.081  6708  6778 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 11:58:15.081  6708  6778 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 11:58:15.082  6708  6778 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 11:58:15.082  6708  6778 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 11:58:15.083  6708  6778 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 11:58:15.083  6708  6778 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 11:58:15.083  6708  6778 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 11:58:15.083  6708  6778 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 11:58:15.084  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:15.084  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29d4697b added. We now have 2 listener(s)
09-13 11:58:15.085  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:15.086  6708  6778 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 11:58:15.088  1035  2002 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 11:58:15.088  1035  2002 D WifiService: setWifiEnabled: true pid=6708, uid=10118
09-13 11:58:15.088  1035  2002 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 11:58:15.090  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:15.090  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17b69398 added. We now have 3 listener(s)
09-13 11:58:15.090  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:15.094  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:58:15.095  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@394557f1 added. We now have 4 listener(s)
09-13 11:58:15.095  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:15.097  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:15.097  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38b80fd6 added. We now have 5 listener(s)
09-13 11:58:15.097  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:15.099  1035  1649 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 11:58:15.099  1035  1649 D WifiService: setWifiEnabled: false pid=6708, uid=10118
09-13 11:58:15.099  1035  1649 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:58:15.110  1035  1391 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 11:58:15.111  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 11:58:15.111  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 11:58:15.111  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 11:58:15.111  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 11:58:15.111  1035  1391 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 11:58:15.112  1035  1391 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 11:58:15.112  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 11:58:15.112  1035  1391 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 11:58:15.113  1035  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:58:15.113  1035  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 11:58:15.113  1035  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:15.114  1035  1052 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@303703b7 mBinding = false
09-13 11:58:15.115  1035  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 11:58:15.115  1035  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 11:58:15.132  1035  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 11:58:15.133  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 11:58:15.133  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.133  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.133  2714  2714 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 11:58:15.133  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 11:58:15.133  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 11:58:15.134  1035  1391 D WifiNative-wlan0: SET ps 1: returned true
,09-13 11:58:15.135  1035  2867 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.138  1035  1111 D BluetoothManagerService: Message: 2
09-13 11:58:15.139   312   894 D CommandListener: Clearing all IP addresses on wlan0
09-13 11:58:15.139  1035  1111 D BluetoothManagerService: Sending off request.
09-13 11:58:15.140  3853  3870 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 11:58:15.140  3853  3948 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 11:58:15.140  3853  3948 D BluetoothAdapterProperties: Setting state to 13
09-13 11:58:15.140  3853  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 11:58:15.141  3853  3948 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 11:58:15.141  3853  3948 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 11:58:15.145  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 11:58:15.145  3853  3954 D BluetoothAdapterProperties: Scan Mode:20
09-13 11:58:15.145  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 11:58:15.145  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-13 11:58:15.147  3853  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 11:58:15.148  3853  3948 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 11:58:15.149  3853  4235 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:15.149  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 11:58:15.151  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:15.152  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:15.152  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:15.152  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:15.152  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:15.152  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:15.152  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:15.152  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:15.152  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:15.152  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:15.152  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:15.156  1035  1111 D BluetoothManagerService: Message: 60
09-13 11:58:15.156  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 11:58:15.156  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 11:58:15.160  3853  4306 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:15.161  3853  4047 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 11:58:15.163  3853  4311 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:15.163  3853  4309 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 11:58:15.164  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 11:58:15.165  3853  4047 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-13 11:58:15.179  1035  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 11:58:15.179  3853  4233 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 11:58:15.179  3853  4233 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:15.179  3853  4233 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 11:58:15.179  3853  4233 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 11:58:15.179  3853  4233 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 11:58:15.179  3853  4233 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 11:58:15.179  3853  4233 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 11:58:15.179  3853  4233 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 11:58:15.179  1035  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-13 11:58:15.202  1035  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6801 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 11:58:15.205  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:15.213  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:15.213  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:15.213  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:15.213  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:15.213  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:15.213  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:15.213  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:15.213  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:15.213  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:15.214  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:15.214  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:15.214  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:15.215  1035  1985 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-13 11:58:15.215  1035  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.215  1035  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.215  1035  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 11:58:15.216  1035  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.216  1035  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-13 11:58:15.217  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:15.217  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-13 11:58:15.219  3853  3853 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:15.219  3853  3853 D BluetoothMapService: STATE_TURNING_OFF
09-13 11:58:15.219  3853  3853 V BluetoothMapService: Handler(): got msg=4
09-13 11:58:15.219  3853  3853 D BluetoothMapService: MAP Service closeService in
09-13 11:58:15.219  3853  3853 D BluetoothMapMasInstance: MAP Service shutdown
09-13 11:58:15.219  3853  3853 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 11:58:15.220  3853  3853 V BluetoothMapService: MAP Service closeService out
09-13 11:58:15.220  3853  3853 V BtOppService: Receiver DISABLED_ACTION 
09-13 11:58:15.220  3853  3853 I BtOppRfcommListener: stopping Accept Thread
09-13 11:58:15.220  3853  3853 V BtOppRfcommListener: close mBtServerSocket
09-13 11:58:15.220  3853  4306 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 11:58:15.221  3853  3853 V BtOppRfcommListener: waiting for thread to terminate
09-13 11:58:15.222  3853  3853 V BtOppRfcommListener: done waiting for thread to terminate
09-13 11:58:15.260  1035  1444 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 11:58:15.260   312  6832 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 11:58:15.260  1035  1444 D DSQN    : disableDataServiceNotify
,09-13 11:58:15.260  1035  1444 D DSQN    : stop dsqn bin
09-13 11:58:15.261  1035  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-13 11:58:15.261  1035  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6827 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 11:58:15.261  1035  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 11:58:15.263  6708  6795 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-13 11:58:15.263  6708  6795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 837)
09-13 11:58:15.264  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:15.264  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:15.264  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:15.264  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:15.264  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:15.264  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:15.264  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:15.264  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:15.264  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:15.264  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 11:58:15.264  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:15.264  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:15.265  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:15.266  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:15.268  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:15.268  1035  1444 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 11:58:15.268  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 11:58:15.268  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:15.268  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 11:58:15.269  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:15.269  1035  1444 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:15.269  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:15.269  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 11:58:15.269  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 11:58:15.269  1602  2078 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 11:58:15.269  1035  1444 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 11:58:15.270  1035  1444 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 11:58:15.270  1035  1444 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 11:58:15.270  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 11:58:15.270  1035  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.270  1035  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.270  1035  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 11:58:15.271  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:15.271  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:15.271  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 11:58:15.272  3853  3853 V BtOppService: onDestroy
09-13 11:58:15.273  1035  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:15.273  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.273  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.273  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:15.273  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2ea895ed
09-13 11:58:15.273  1035  1390 D LGWifiP2pService: P2pDisablingState
09-13 11:58:15.273  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 11:58:15.273  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.273  1035  1390 D LGWifiP2pService: p2p socket connection lost
09-13 11:58:15.274  1035  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:15.274  1035  1390 D LGWifiP2pService: P2pDisabledState
09-13 11:58:15.274  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 11:58:15.274  1035  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:15.274  1035  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 11:58:15.274  1035  1444 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:15.274  1035  1444 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:15.274  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:15.275  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:15.275  1035  1391 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 11:58:15.276  1035  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:15.276  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:15.277  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:15.277  1035  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 11:58:15.277  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 11:58:15.277  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.277  1035  1390 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.278  2714  2714 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 11:58:15.278  1035  1444 D NetworkManagementService: Removing idletimer
09-13 11:58:15.279  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:15.279  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 11:58:15.279  1035  1444 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:15.279  1035  1444 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 11:58:15.280  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 11:58:15.280  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 11:58:15.280  1035  1391 D WifiNative-wlan0: SET ps 1: returned true
09-13 11:58:15.280   312   894 D CommandListener: Clearing all IP addresses on wlan0
09-13 11:58:15.282  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:15.282  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:15.283  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:15.285  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:15.285  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:15.285  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:15.286  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-13 11:58:15.288  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 11:58:15.289  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-13 11:58:15.289  1035  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.289  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,09-13 11:58:15.289  1940  1940 D WfdsService: WifiP2pState is changed : false
09-13 11:58:15.289  1940  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 11:58:15.289  1940  2296 D WfdsService: Set the WFDS Monitor: false
09-13 11:58:15.290  1940  2296 D WfdsMonitor: WFDS Monitor is stopped
09-13 11:58:15.290  1940  2296 D WfdsService: STATE : WfdsDisabledState - enter
09-13 11:58:15.290  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 11:58:15.291  1035  1556 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.291  1940  2778 D CtrlSupplicant: Received on exit socket, terminate
09-13 11:58:15.291  1940  2778 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 11:58:15.291  1940  2778 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 11:58:15.291  1940  2778 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 11:58:15.291  1035  1391 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 11:58:15.292  1940  2299 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 11:58:15.292  1940  2296 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 11:58:15.292  1035  1391 D WifiNative-p2p0: TERMINATE: returned true
09-13 11:58:15.292  3853  3853 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 11:58:15.292  1035  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 11:58:15.292  1035  1391 E WifiStateMachine: useWiFiOffloading() : false
09-13 11:58:15.292  1035  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 11:58:15.292  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 11:58:15.293  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 11:58:15.293  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 11:58:15.293  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 11:58:15.293  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 11:58:15.293  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 11:58:15.293  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 11:58:15.293  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 11:58:15.293  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 11:58:15.294  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:15.294  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:15.294  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 11:58:15.296  1035  1391 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:15.296  1035  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:15.299  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 11:58:15.299  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-13 11:58:15.299  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:58:15.299  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:15.299  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:15.299  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:15.299  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:15.299  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:15.299  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:15.299  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:15.299  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:15.300  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:15.300  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:15.302  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:15.302  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:15.302  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:15.302  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:15.302  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:15.302  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:15.302  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:15.302  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:15.302  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:15.303  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:15.303  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:15.304  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:15.304  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 11:58:15.324  6827  6827 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 11:58:15.324  6827  6827 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 11:58:15.324  6827  6827 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 11:58:15.324  6827  6827 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 11:58:15.325  6827  6827 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-13 11:58:15.325  6827  6827 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 11:58:15.327  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 11:58:15.328  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:15.329  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 11:58:15.341  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 11:58:15.342  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:15.342  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:15.343  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 11:58:15.343  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:15.344  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:15.344  1035  2867 D DhcpStateMachine: StoppedState
09-13 11:58:15.345  1035  2867 D DhcpStateMachine: StoppedState{ when=-64ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:15.346  1035  1391 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 11:58:15.346  1035  1391 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 11:58:15.359  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 11:58:15.389  6801  6801 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 11:58:15.389  2714  2714 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 11:58:15.389  2714  2714 I wpa_supplicant: monitor socket send errors count : 1
09-13 11:58:15.389  2714  2714 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-2\x00 that cannot receive messages
09-13 11:58:15.389  6801  6801 W LG Account v2.2: No ProfileInfo entries
09-13 11:58:15.389  6801  6801 I LG Account v2.2: isEnabled: false
09-13 11:58:15.389  6801  6801 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 11:58:15.389  6801  6801 I Feature : [Lifetracker]Country: EU
09-13 11:58:15.390  6801  6801 I Feature : [Lifetracker]Operator: OPEN
09-13 11:58:15.390  6801  6801 I Feature : [Lifetracker]Ranking support: false
09-13 11:58:15.390  6801  6801 I Feature : [Lifetracker]Comfort support: false
09-13 11:58:15.390  6801  6801 I Feature : [Lifetracker]Accessory: true
09-13 11:58:15.390  6801  6801 I Feature : [Lifetracker]Health device: true
09-13 11:58:15.390  6801  6801 I Feature : [Lifetracker]Extra Pedometer: false
09-13 11:58:15.390  6801  6801 I Feature : [Lifetracker]Blood glucose device: false
09-13 11:58:15.390  6801  6801 I Feature : [Lifetracker]Device Number: 3
09-13 11:58:15.390  1035  2777 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 11:58:15.390  1035  2777 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-13 11:58:15.396  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:15.400  6827  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 11:58:15.427  2714  2714 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 11:58:15.428  1035  2777 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 11:58:15.428  2714  2714 W wpa_supplicant: USIM:  scard_deinit function
09-13 11:58:15.428  1035  2777 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 11:58:15.428  1035  1111 D Tethering: InitialState.processMessage what=4
,09-13 11:58:15.428  1035  2777 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 11:58:15.430  1035  2777 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 11:58:15.430  1035  2777 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 11:58:15.430  1035  2777 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 11:58:15.430  1035  1895 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6849 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 11:58:15.431  1035  1391 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188300
09-13 11:58:15.431  1035  1391 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=188300
09-13 11:58:15.431  1035  1391 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=188301  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 11:58:15.432  1035  1391 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=188301  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 11:58:15.432  1035  1895 I ActivityManager: Killing 6155:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-13 11:58:15.462  2714  2714 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 11:58:15.463  1035  2777 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 11:58:15.463  1035  2777 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 11:58:15.463  1035  2777 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 11:58:15.464  1035  1391 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-13 11:58:15.481  1035  1575 W libprocessgroup: failed to open /acct/uid_10014/pid_6155/cgroup.procs: No such file or directory
,09-13 11:58:15.487  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 11:58:15.489  3853  3853 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 11:58:15.490  3853  3853 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:15.490  3853  3853 V BluetoothPbapReceiver: ***********state = 13
09-13 11:58:15.492  3853  3853 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 11:58:15.495  3853  3853 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:15.495  3853  3853 V BluetoothPbapService: state: 13
09-13 11:58:15.495  1035  1111 D BluetoothManagerService: Message: 20
09-13 11:58:15.495  3853  3853 V BluetoothPbapService: Pbap Service closeService in
,09-13 11:58:15.495  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17d7ca8e:true
09-13 11:58:15.496  3853  3853 V BluetoothPbapService: successfully stopped pbap service
09-13 11:58:15.497  3853  3853 V BluetoothPbapService: Pbap Service closeService out
09-13 11:58:15.497  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 11:58:15.497  3853  3853 V BluetoothPbapService: Pbap Service onDestroy
09-13 11:58:15.497  3853  3853 V BluetoothPbapService: Pbap Service closeService in
09-13 11:58:15.497  3853  3853 V BluetoothPbapService: Pbap Service closeService out
09-13 11:58:15.497  3853  3853 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 11:58:15.519  1035  1111 D BluetoothManagerService: Message: 30
,09-13 11:58:15.523  1035  1111 D BluetoothManagerService: Message: 30
09-13 11:58:15.525  6827  6827 D LocalBluetoothProfileManager: Adding local MAP profile
09-13 11:58:15.526  6827  6827 D BluetoothMap: Create BluetoothMap proxy object
09-13 11:58:15.527  1035  1111 D BluetoothManagerService: Message: 30
09-13 11:58:15.530  1035  1111 D BluetoothManagerService: Message: 30
09-13 11:58:15.531  6827  6827 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-13 11:58:15.532  6849  6849 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 11:58:15.532  6827  6827 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-13 11:58:15.535  6849  6849 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 11:58:15.536  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:15.537  1035  1880 I ActivityManager: Killing 6265:com.android.defcontainer/u0a4 (adj 15): empty #17
09-13 11:58:15.553  6708  6708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:58:15.555  1035  2031 W libprocessgroup: failed to open /acct/uid_10004/pid_6265/cgroup.procs: No such file or directory
,09-13 11:58:15.556  6827  6827 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-13 11:58:15.559  6827  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-13 11:58:15.567  1940  1940 D WfdsService: Supplicant Connection state is changed : false
09-13 11:58:15.567  1035  1391 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 11:58:15.567  1035  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 11:58:15.567  1035  1391 E WifiStateMachine: useWiFiOffloading() : false
09-13 11:58:15.567  1035  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 11:58:15.567  1940  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 11:58:15.567  1940  2296 D WfdsService: Set the WFDS Monitor: false
09-13 11:58:15.567  1940  2296 D WfdsMonitor: WFDS Monitor is stopped
09-13 11:58:15.568  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:15.569  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 11:58:15.570  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 11:58:15.571  1035  1403 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 11:58:15.571  1035  1403 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 11:58:15.571  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:15.572  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:15.572  6827  6827 D DockEventReceiver: finishStartingService: stopping service
09-13 11:58:15.573  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:15.582  6827  6827 D BluetoothInputDevice: Proxy object connected
,09-13 11:58:15.583  6827  6827 D HidProfile: Bluetooth service connected
09-13 11:58:15.584  6827  6827 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 11:58:15.585  6827  6827 D PanProfile: Bluetooth service connected
09-13 11:58:15.586  6827  6827 D BluetoothMap: Proxy object connected
09-13 11:58:15.586  6827  6827 D MapProfile: Bluetooth service connected
09-13 11:58:15.586  6827  6827 D BluetoothMap: getConnectedDevices()
09-13 11:58:15.587  6827  6827 D BluetoothMap: Bluetooth is Not enabled
09-13 11:58:15.598  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:15.633  6827  6827 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:15.633  6827  6827 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:15.643  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:15.644  6827  6827 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 11:58:15.647  6827  6827 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 11:58:15.653  6827  6827 D BluetoothPermissionRequest: onReceive
09-13 11:58:15.656  6827  6827 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 11:58:15.667  6827  6827 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 11:58:15.669  1035  1051 I ActivityManager: Killing 6453:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-13 11:58:15.728  3853  3853 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 11:58:15.728  3853  3853 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-13 11:58:15.730  3853  3853 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 11:58:15.730  1035  2028 W libprocessgroup: failed to open /acct/uid_10008/pid_6453/cgroup.procs: No such file or directory
,09-13 11:58:15.747  3853  3853 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:15.748  3853  3853 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-13 11:58:15.751  3853  3853 V BluetoothFtpService: Ftp Service onStartCommand
09-13 11:58:15.752  3853  3853 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:15.752  3853  3853 V BluetoothFtpService: Ftp Service closeService
09-13 11:58:15.753  3853  3853 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 11:58:15.779  1035  1391 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
,09-13 11:58:15.780  1035  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-13 11:58:15.849  1035  1958 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6880 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-13 11:58:15.851  3853  3853 V BluetoothFtpService: successfully stopped ftp service
09-13 11:58:15.851  3853  3853 V BluetoothFtpService: Ftp Service onDestroy
09-13 11:58:15.851  3853  3853 V BluetoothFtpService: Ftp Service closeService
09-13 11:58:15.857  3853  3853 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 11:58:15.857  3853  3853 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 11:58:15.857  3853  3853 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 11:58:15.857  3853  3853 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:15.857  3853  3853 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 11:58:15.857  3853  3853 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 11:58:15.859  3853  3853 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:15.859  3853  3853 V BluetoothSapService: state: 13
09-13 11:58:15.859  3853  3853 V BluetoothSapService: Stopping SAP server process
09-13 11:58:15.861  3853  3853 V BluetoothSapService: Sap Service closeSapService in
09-13 11:58:15.861  3853  3853 V BluetoothSapService: Close listen Socket : 
09-13 11:58:15.861  3853  3853 V BluetoothSapService: Close rfcomm Socket : 
09-13 11:58:15.861  3853  3853 V BluetoothSapService: Close sapd  Socket : 
,09-13 11:58:15.867   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 20.724ms
09-13 11:58:15.887   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 19.335ms
,09-13 11:58:15.906   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 18.283ms
,09-13 11:58:15.951  1035  1052 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6897 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 11:58:15.953  3853  3853 V BluetoothSapService: Sap Service closeSapService out
09-13 11:58:15.954  3853  3853 V BluetoothSapService: Sap Service onDestroy
09-13 11:58:15.954  3853  3853 V BluetoothSapService: Sap Service closeSapService in
09-13 11:58:15.954  3853  3853 V BluetoothSapService: Close listen Socket : 
09-13 11:58:15.954  3853  3853 V BluetoothSapService: Close rfcomm Socket : 
09-13 11:58:15.954  3853  3853 V BluetoothSapService: Close sapd  Socket : 
09-13 11:58:15.955  3853  3853 V BluetoothSapService: Sap Service closeSapService out
,09-13 11:58:15.994  6880  6880 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 11:58:16.011  6897  6897 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 11:58:16.024  6880  6880 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-13 11:58:16.028  1035  1985 I ActivityManager: Killing 5948:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-13 11:58:16.061  1035  1957 W libprocessgroup: failed to open /acct/uid_10011/pid_5948/cgroup.procs: No such file or directory
,09-13 11:58:16.104  6880  6880 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-13 11:58:16.104  6880  6880 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 11:58:16.105  6880  6880 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 11:58:16.105  6880  6880 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,09-13 11:58:16.106  6880  6880 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 11:58:16.107  6880  6880 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 11:58:16.113  6880  6880 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-13 11:58:16.121  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:16.128  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:16.155  6880  6880 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 11:58:16.160  6880  6880 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-13 11:58:16.160  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:16.164  6880  6880 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-13 11:58:16.166  3853  4047 W bt-btif : ag scb idx 1 not allocated
09-13 11:58:16.166  3853  4047 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 11:58:16.166  3853  3954 D bt_hci_bdroid: cleanup
09-13 11:58:16.166  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:16.166  3853  4047 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:58:16.167  3853  4221 I bt_userial_mct: exiting userial_read_thread
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 11:58:16.167  3853  4221 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 11:58:16.167  3853  4047 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 11:58:16.167  3853  4047 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 11:58:16.167  3853  4049 I bt_lpm  : LPM is already off!!!
09-13 11:58:16.168  3853  3954 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 11:58:16.168  3853  4049 I bt_vendor: hw_epilog_process
09-13 11:58:16.169  3853  3954 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 11:58:16.169  3853  3954 D bt_userial_mct: userial_close
,09-13 11:58:16.169  3853  3954 E bt_userial_mct: pthread_join() FAILED result:3
09-13 11:58:16.169  3853  3954 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 11:58:16.169  6849  6849 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 11:58:16.169  6849  6849 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 11:58:16.169  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 11:58:16.179  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:16.190  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:16.201  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:16.202  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:16.206  6880  6880 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 11:58:16.212  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:16.220  6849  6849 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 11:58:16.220  6849  6849 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 11:58:16.221  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 11:58:16.226  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:16.233  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:16.241  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:16.242  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:16.245  6880  6880 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 11:58:16.248  3853  3954 D bt_hci_bdroid: set_power 0
09-13 11:58:16.248  3853  3954 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 11:58:16.248  3853  3954 I bt_vendor: bluetooth satus is on
09-13 11:58:16.248  3853  3954 I bt_vendor: bt-vendor : resetting BT status
09-13 11:58:16.248  3853  3954 I bt_vendor: Starting hciattach daemon
09-13 11:58:16.248  3853  3954 I bt_vendor: try to set false
09-13 11:58:16.249  3853  3954 I bt_vendor: Starting hciattach daemon
09-13 11:58:16.249  3853  3954 I bt_vendor: try to set false
09-13 11:58:16.250  3853  3954 I bt_vendor: cleanup
09-13 11:58:16.251  3853  4047 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 11:58:16.251  3853  3954 I GKI_LINUX: GKI_exit_task 0 done
09-13 11:58:16.251  3853  3954 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 11:58:16.252  3853  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 11:58:16.297  1035  2028 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6918 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-13 11:58:16.306  3853  3853 D HeadsetService: Received stop request...Stopping profile...
09-13 11:58:16.309  3853  3853 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 11:58:16.309  3853  3853 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 11:58:16.310  3853  3853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fc43ce4
09-13 11:58:16.310  3853  3979 D HeadsetStateMachine: Exit Disconnected: -1
09-13 11:58:16.312  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-13 11:58:16.312  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 11:58:16.312  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-13 11:58:16.312  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-13 11:58:16.313  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-13 11:58:16.314  3853  3948 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-13 11:58:16.316  3853  3853 D A2dpService: Received stop request...Stopping profile...
09-13 11:58:16.316  3853  4011 D A2dpStateMachine: Exit Disconnected: -1
09-13 11:58:16.318  3853  3853 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 11:58:16.320  3853  3853 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 11:58:16.320  3853  3853 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 11:58:16.320  3853  3853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fc43ce4
09-13 11:58:16.324  3853  3853 D HidService: Received stop request...Stopping profile...
09-13 11:58:16.324  3853  3853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fc43ce4
,09-13 11:58:16.325  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-13 11:58:16.325  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 11:58:16.329  3853  3853 D HealthService: Received stop request...Stopping profile...
09-13 11:58:16.329  3853  3853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fc43ce4
09-13 11:58:16.329  6827  6827 D BluetoothInputDevice: Proxy object disconnected
09-13 11:58:16.329  6827  6827 D HidProfile: Bluetooth service disconnected
09-13 11:58:16.331  3853  3853 D PanService: Received stop request...Stopping profile...
09-13 11:58:16.332  3853  3853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fc43ce4
09-13 11:58:16.333  3853  3853 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 11:58:16.333  6827  6827 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 11:58:16.334  6827  6827 D PanProfile: Bluetooth service disconnected
09-13 11:58:16.334  3853  3853 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 11:58:16.334  3853  3853 D BtGatt.GattService: stop()
09-13 11:58:16.334  3853  3853 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 11:58:16.335  3853  3853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fc43ce4
09-13 11:58:16.336  3853  3853 D HeadsetStateMachine: Unbinding service...
,09-13 11:58:16.337  3853  3853 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 11:58:16.337  3853  3853 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 11:58:16.337  3853  3853 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 11:58:16.337  3853  3853 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 11:58:16.337  3853  3853 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 11:58:16.337  3853  3853 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 11:58:16.337  3853  3853 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-13 11:58:16.338  3853  3853 D BluetoothMapService: Received stop request...Stopping profile...
09-13 11:58:16.338  3853  3853 D BluetoothMapService: stop()
09-13 11:58:16.339  3853  3853 D BluetoothMapEmailAppObserver: deinitObservers()
,09-13 11:58:16.339  3853  3853 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 11:58:16.340  3853  3853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fc43ce4
09-13 11:58:16.342  3853  3853 I BluetoothA2dpServiceJni: cleanupNative
09-13 11:58:16.342  6827  6827 D BluetoothMap: Proxy object disconnected
09-13 11:58:16.342  6827  6827 D MapProfile: Bluetooth service disconnected
09-13 11:58:16.342  3853  4012 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 11:58:16.343  3853  3853 I GKI_LINUX: GKI_exit_task 2 done
09-13 11:58:16.343  3853  3853 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 11:58:16.343  3853  3853 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 11:58:16.343  3853  3853 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 11:58:16.343  3853  3853 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 11:58:16.343  3853  3853 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 11:58:16.343  3853  3853 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 11:58:16.343  3853  3853 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 11:58:16.344  3853  3853 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 11:58:16.344  3853  3853 V BluetoothMapService: Handler(): got msg=4
09-13 11:58:16.344  3853  3853 D BluetoothMapService: MAP Service closeService in
09-13 11:58:16.345  3853  3853 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 11:58:16.345  3853  3853 V BluetoothMapService: MAP Service closeService out
09-13 11:58:16.345  3853  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 11:58:16.345  3853  3948 D BluetoothAdapterProperties: Setting state to 10
09-13 11:58:16.345  3853  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 11:58:16.346  1035  1111 D BluetoothManagerService: Message: 60
09-13 11:58:16.346  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 11:58:16.346  3853  3853 D BluetoothMapService: cleanup()
09-13 11:58:16.346  3853  3853 D BluetoothMapService: MAP Service closeService in
09-13 11:58:16.346  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-13 11:58:16.346  3853  3853 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 11:58:16.346  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:58:16.346  3853  3853 V BluetoothMapService: MAP Service closeService out
09-13 11:58:16.347  3853  3948 I BluetoothAdapterState: Entering OffState
09-13 11:58:16.347  1851  2441 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:58:16.347  6827  6934 D BluetoothPan: onBluetoothStateChange on: false
09-13 11:58:16.348  1851  4399 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:58:16.349  6827  6844 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 11:58:16.349  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:58:16.349  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:58:16.350  6827  6843 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 11:58:16.350  6827  6934 D BluetoothMap: onBluetoothStateChange: up=false
09-13 11:58:16.351  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-13 11:58:16.351  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-13 11:58:16.354  1035  1111 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-13 11:58:16.354  1035  1111 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-13 11:58:16.354  1035  1111 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@303703b7 mBinding = false
09-13 11:58:16.355  1035  1111 D BluetoothManagerService: Sending unbind request.
09-13 11:58:16.364  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-13 11:58:16.366  3853  3954 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-13 11:58:16.367  3853  3853 I GKI_LINUX: GKI_exit_task 1 done
09-13 11:58:16.367  3853  3853 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-13 11:58:16.368  3853  3853 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 11:58:16.368  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:16.368  3853  3853 I art     : --- WEIRD: removing null entry 246
09-13 11:58:16.368  3853  3853 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-13 11:58:16.368  3853  3853 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-13 11:58:16.369  1940  2094 D LGBluetoothAPIService: Message: 2
09-13 11:58:16.369  1940  2094 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@229cf707 mBinding = false
09-13 11:58:16.369  1940  2094 D LGBluetoothAPIService: Sending unbind request.
09-13 11:58:16.370  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 11:58:16.371  6827  6827 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 11:58:16.372  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:16.373  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:16.374  3853  3853 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-13 11:58:16.374  6827  6827 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 11:58:16.375  6827  6827 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 11:58:16.376  1602  1602 D BluetoothAdapter: 526956796: getState() :  mService = null. Returning STATE_OFF
09-13 11:58:16.376  1602  1602 D BluetoothAdapter: 526956796: getState() :  mService = null. Returning STATE_OFF
09-13 11:58:16.377  3853  3853 I art     : System.exit called, status: 0
09-13 11:58:16.377  3853  3853 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 11:58:16.379  6827  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 11:58:16.387  6827  6827 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:58:16.399   317   317 V AudioFlinger: 3853 died, releasing its sessions
09-13 11:58:16.399   317   317 V AudioFlinger:  pid 1851 @ 0
09-13 11:58:16.399   317   317 V AudioFlinger:  pid 3453 @ 1
09-13 11:58:16.399   317   317 V AudioFlinger:  pid 3453 @ 2
09-13 11:58:16.400  6827  6827 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-13 11:58:16.479  1035  1052 I ActivityManager: Process com.android.bluetooth (pid 3853) has died
09-13 11:58:16.479  1035  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-13 11:58:16.492  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 11:58:16.509  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 11:58:16.535  1035  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=240715448, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
09-13 11:58:16.536  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 11:58:16.537  1035  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{12ba6169 type 2 when 189396 com.google.android.gms} when 189396
,09-13 11:58:16.550  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:16.555  6827  6827 D BluetoothPermissionRequest: onReceive
,09-13 11:58:16.557  6827  6827 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 11:58:16.558  6827  6827 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 11:58:16.563  6827  6827 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 11:58:16.612  1035  1051 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6947 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-13 11:58:16.629  6918  6945 W FormManager: Network not available. Please check & try again.
,09-13 11:58:16.642  6918  6946 V FormManager: Network unavailable.
,09-13 11:58:16.645  6918  6946 V FormManager: Network unavailable.
09-13 11:58:16.650  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-13 11:58:16.650  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 11:58:16.650  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 11:58:16.650  6827  6827 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 11:58:16.651  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 11:58:16.660  6827  6827 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 11:58:16.660  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 11:58:16.660  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 11:58:16.660  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 11:58:16.660  6827  6827 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 11:58:16.660  6827  6827 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 11:58:16.664  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 11:58:16.664  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 11:58:16.666  1035  1895 I ActivityManager: Killing 5973:com.android.contacts/u0a19 (adj 15): empty #17
09-13 11:58:16.667  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 11:58:16.702  1035  1958 W libprocessgroup: failed to open /acct/uid_10019/pid_5973/cgroup.procs: No such file or directory
09-13 11:58:16.709  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 11:58:16.716  4287  6967 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 11:58:16.718  6849  6849 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 11:58:16.718  6849  6849 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 11:58:16.719  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:16.722  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 11:58:16.725  4287  6968 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 11:58:16.725  4287  6968 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 11:58:16.726  6947  6947 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-13 11:58:16.727  6947  6947 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 11:58:16.728  6947  6947 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-13 11:58:16.729  6918  6970 W FormManager: Network not available. Please check & try again.
09-13 11:58:16.731  6947  6947 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 11:58:16.734  6918  6971 V FormManager: Network unavailable.
09-13 11:58:16.736  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:16.736  6918  6971 V FormManager: Network unavailable.
,09-13 11:58:16.753  6947  6947 D BluetoothAdapterApp: Loading JNI Library
09-13 11:58:16.753  6880  6880 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-13 11:58:16.754  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 11:58:16.754  6880  6880 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-13 11:58:16.789  6947  6947 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@35de895 Instance Count = 1
,09-13 11:58:16.793  6880  6880 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:16.793  6880  6880 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 11:58:16.795  6947  6947 D BluetoothAdapterApp: onCreate
09-13 11:58:16.802  6880  6880 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,09-13 11:58:16.804  6880  6880 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 11:58:16.804  6880  6880 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-13 11:58:16.804  6880  6880 V SoundPool: doLoad: loading sample sampleID=1
09-13 11:58:16.804  6880  6880 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 11:58:16.809  6880  6974 V SoundPool: Start decode
09-13 11:58:16.809  6880  6974 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-13 11:58:16.810   317  2174 V MediaPlayerService: decode(23, 10857164, 17813)
09-13 11:58:16.810   317  2174 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-13 11:58:16.810   317  2174 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 11:58:16.810   317  2174 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 11:58:16.810   317  2174 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 11:58:16.811   317  2174 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-13 11:58:16.811   317  2174 V MediaPlayerService: player type = 3
09-13 11:58:16.811   317  2174 V AwesomePlayer: AwesomePlayer create()
09-13 11:58:16.811   317  2174 V AwesomePlayer: reset_l() 
09-13 11:58:16.811   317  2174 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:16.811   317  2174 V AwesomePlayer: setAudioSink() 
09-13 11:58:16.811   317  2174 V AwesomePlayer: reset_l() 
09-13 11:58:16.811   317  2174 V AudioCache: notify(0xb16a67c0, 8, 0, 0)
09-13 11:58:16.811   317  2174 V AudioCache: ignored
09-13 11:58:16.812   317  2174 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:16.812   317  2174 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 11:58:16.812   317  2174 V AwesomePlayer: setDataSource_l dataSource
09-13 11:58:16.812   317  2174 V LGParserOSAL: SniffLGParser start
09-13 11:58:16.812   317  2174 V LGParserOSAL: MainType:5, SubType=0
09-13 11:58:16.812   317  2174 V LGParserOSAL: #### check Mime : application/ogg
09-13 11:58:16.812   317  2174 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 11:58:16.812   317  2174 E MediaExtractor: Use LGExtractor :application/ogg 
09-13 11:58:16.812  6591  6591 D UEI.SmartControl: QS Service created
09-13 11:58:16.813  6880  6880 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 11:58:16.816  6880  6880 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 11:58:16.817  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 11:58:16.827  6591  6591 I UEI.SmartControl: Service initServices...
,09-13 11:58:16.828  6591  6591 D UEI.SmartControl: QS start get config
,09-13 11:58:16.837  6947  6947 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-13 11:58:16.838  6947  6947 D ProfileConfigQcom: Adding HeadsetService
09-13 11:58:16.839  6947  6947 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-13 11:58:16.839  6947  6947 D ProfileConfigQcom: Adding A2dpService
09-13 11:58:16.840  6947  6947 D ProfileConfigQcom: [BTUI] HidService is supported
09-13 11:58:16.840  6947  6947 D ProfileConfigQcom: Adding HidService
,09-13 11:58:16.840  6947  6947 D ProfileConfigQcom: [BTUI] HealthService is supported
09-13 11:58:16.840  6947  6947 D ProfileConfigQcom: Adding HealthService
09-13 11:58:16.841  6947  6947 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-13 11:58:16.841  6947  6947 D ProfileConfigQcom: [BTUI] PanService is supported
,09-13 11:58:16.842  6947  6947 D ProfileConfigQcom: Adding PanService
09-13 11:58:16.842  6947  6947 D ProfileConfigQcom: [BTUI] GattService is supported
09-13 11:58:16.842  6947  6947 D ProfileConfigQcom: Adding GattService
09-13 11:58:16.842  6947  6947 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-13 11:58:16.842  6947  6947 D ProfileConfigQcom: Adding BluetoothMapService
09-13 11:58:16.843  6947  6947 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-13 11:58:16.845  6947  6947 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 11:58:16.848  6880  6880 V LGMDMManager: Create singleton instance
09-13 11:58:16.851  6827  6827 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 11:58:16.854  6947  6947 V LGMDMManagerInternal: Create singleton instance
09-13 11:58:16.859   317  2174 V LGParserOSAL: supported mime: application/ogg
09-13 11:58:16.859   317  2174 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 11:58:16.859   317  2174 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 11:58:16.859   317  2174 V AwesomePlayer: mBitrate = -1 bits/sec
,09-13 11:58:16.859   317  2174 V AwesomePlayer: AudioTrack Setting
09-13 11:58:16.859   317  2174 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 11:58:16.859   317  2174 V AwesomePlayer: setAudioSource() 
09-13 11:58:16.859   317  2174 V MediaPlayerService: prepare
09-13 11:58:16.859   317  2174 V AwesomePlayer: prepareAsync_l() 
09-13 11:58:16.859   317  2174 V MediaPlayerService: wait for prepare
,09-13 11:58:16.860   317  6976 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 11:58:16.860   317  6976 V AwesomePlayer: initAudioDecoder() 
09-13 11:58:16.860   317  6976 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 11:58:16.860   317  6976 V AudioSystem: isOffloadSupported()
09-13 11:58:16.860   317  6976 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 11:58:16.860   317  6976 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 11:58:16.860   317  6976 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 11:58:16.860   317  6976 V AwesomePlayer: getUseOffload() = 0 
09-13 11:58:16.860   317  6976 V OMXCodec: OMXCodec::Create
09-13 11:58:16.860   317  6976 V OMXCodec: findMatchingCodecs()
09-13 11:58:16.860   317  6976 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 11:58:16.860   317  6976 V OMXCodec: matchingCodecs.size()=1
09-13 11:58:16.860   317  6976 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 11:58:16.862   317  6976 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 11:58:16.862   317  6976 V LGCodecAdapter: LG Codec Adapter start
09-13 11:58:16.862   317  6976 V OMXCodec: OMXCodec Createtor
09-13 11:58:16.862   317  6976 V OMXCodec: setComponentRole
09-13 11:58:16.862   317  6976 V OMXCodec: configureCodec protected=0
09-13 11:58:16.862   317  6976 V LGCodecAdapter: called getLGCodecSpecificData
09-13 11:58:16.862   317  6976 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 11:58:16.862   317  6976 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 11:58:16.862   317  6976 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 11:58:16.862   317  6976 V LGCodecOSAL: Not support LGCodec
09-13 11:58:16.863   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 11:58:16.863   317  6976 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 11:58:16.863   317  6976 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 11:58:16.863   317  6976 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 11:58:16.863   317  6976 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 11:58:16.863   317  6976 V AudioSystem: isOffloadSupported()
09-13 11:58:16.863   317  6976 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 11:58:16.863   317  6976 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 11:58:16.863   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 11:58:16.863   317  6976 V OMXCodec: init()
09-13 11:58:16.863   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-13 11:58:16.863   317  6976 V OMXCodec: allocateBuffers
09-13 11:58:16.863   317  6976 V OMXCodec: allocateBuffersOnPort portIndex=0
09-13 11:58:16.863   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 11:58:16.863   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
09-13 11:58:16.864   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-13 11:58:16.864   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-13 11:58:16.864   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-13 11:58:16.864   31,7  6976 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 11:58:16.864   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 11:58:16.864   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-13 11:58:16.864   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-13 11:58:16.864   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-13 11:58:16.864   317  6976 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
09-13 11:58:16.864   317  6976 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 11:58:16.864   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 11:58:16.864   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 11:58:16.865   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 11:58:16.865   317  6976 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 11:58:16.865   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 11:58:16.865   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 11:58:16.865   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 11:58:16.865   317  6976 V OMXCodec: init() mAsyncCompletion wait free! 
,09-13 11:58:16.865   317  6976 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 11:58:16.865   317  6976 V AudioCache: notify(0xb16a67c0, 5, 0, 0)
09-13 11:58:16.865   317  6976 V AudioCache: ignored
09-13 11:58:16.865   317  6976 V AudioCache: notify(0xb16a67c0, 1, 0, 0)
09-13 11:58:16.865   317  6976 V AudioCache: prepared
09-13 11:58:16.865   317  2174 V AudioCache: wait - success
09-13 11:58:16.865   317  2174 V MediaPlayerService: start
09-13 11:58:16.865   317  2174 V AwesomePlayer: play_l() 
09-13 11:58:16.865   317  2174 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 11:58:16.865   317  2174 V AwesomePlayer: createAudioPlayer_l
09-13 11:58:16.865   317  2174 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 11:58:16.865   317  2174 V AwesomePlayer: startAudioPlayer_l() 
09-13 11:58:16.865   317  2174 D AudioPlayer: start of Playback, useOffload 0
09-13 11:58:16.865   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,09-13 11:58:16.865   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 11:58:16.867   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 11:58:16.867   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 11:58:16.867   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
,09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,09-13 11:58:16.868   317  6978 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-13 11:58:16.868   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-13 11:58:16.869   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
09-13 11:58:16.869   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 11:58:16.869   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 11:58:16.869   317  2174 V AudioCache: open(48000, 2, 0x0, 1, 4)
,09-13 11:58:16.870   317  2174 V AudioCache: notify(0xb16a67c0, 6, 0, 0)
09-13 11:58:16.870   317  2174 V AudioCache: ignored
09-13 11:58:16.870   317  2174 V MediaPlayerService: wait for playback complete
09-13 11:58:16.871   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.871   317  6979 V AudioCache: memcpy(0xaf004000, 0xb178a000, 4096)
09-13 11:58:16.872   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.872   317  6979 V AudioCache: memcpy(0xaf005000, 0xb178a000, 4096)
09-13 11:58:16.873   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.873   317  6979 V AudioCache: memcpy(0xaf006000, 0xb178a000, 4096)
,09-13 11:58:16.874   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.874   317  6979 V AudioCache: memcpy(0xaf007000, 0xb178a000, 4096)
,09-13 11:58:16.884   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.884   317  6979 V AudioCache: memcpy(0xaf008000, 0xb178a000, 4096)
09-13 11:58:16.885   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.885   317  6979 V AudioCache: memcpy(0xaf009000, 0xb178a000, 4096)
09-13 11:58:16.885   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.885   317  6979 V AudioCache: memcpy(0xaf00a000, 0xb178a000, 4096)
,09-13 11:58:16.886   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.886   317  6979 V AudioCache: memcpy(0xaf00b000, 0xb178a000, 4096)
09-13 11:58:16.887   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.887   317  6979 V AudioCache: memcpy(0xaf00c000, 0xb178a000, 4096)
,09-13 11:58:16.888   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.888   317  6979 V AudioCache: memcpy(0xaf00d000, 0xb178a000, 4096)
09-13 11:58:16.889   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.889   317  6979 V AudioCache: memcpy(0xaf00e000, 0xb178a000, 4096)
09-13 11:58:16.889   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.889   317  6979 V AudioCache: memcpy(0xaf00f000, 0xb178a000, 4096)
09-13 11:58:16.890   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.890   317  6979 V AudioCache: memcpy(0xaf010000, 0xb178a000, 4096)
09-13 11:58:16.891   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.891   317  6979 V AudioCache: memcpy(0xaf011000, 0xb178a000, 4096)
09-13 11:58:16.891   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.891   317  6979 V AudioCache: memcpy(0xaf012000, 0xb178a000, 4096)
09-13 11:58:16.892   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.892   317  6979 V AudioCache: memcpy(0xaf013000, 0xb178a000, 4096)
09-13 11:58:16.892   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.892   317  6979 V AudioCache: memcpy(0xaf014000, 0xb178a000, 4096)
09-13 11:58:16.893   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.893   317  6979 V AudioCache: memcpy(0xaf015000, 0xb178a000, 4096)
09-13 11:58:16.893   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.893   317  6979 V AudioCache: memcpy(0xaf016000, 0xb178a000, 4096)
09-13 11:58:16.894   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.894   317  6979 V AudioCache: memcpy(0xaf017000, 0xb178a000, 4096)
09-13 11:58:16.894   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.894   317  6979 V AudioCache: memcpy(0xaf018000, 0xb178a000, 4096)
09-13 11:58:16.895   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.895   317  6979 V AudioCache: memcpy(0xaf019000, 0xb178a000, 4096)
09-13 11:58:16.896   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.896   317  6979 V AudioCache: memcpy(0xaf01a000, 0xb178a000, 4096)
09-13 11:58:16.896   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.896   317  6979 V AudioCache: memcpy(0xaf01b000, 0xb178a000, 4096)
09-13 11:58:16.897   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.897   317  6979 V AudioCache: memcpy(0xaf01c000, 0xb178a000, 4096)
09-13 11:58:16.897   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.897   317  6979 V AudioCache: memcpy(0xaf01d000, 0xb178a000, 4096)
09-13 11:58:16.900   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.900   317  6979 V AudioCache: memcpy(0xaf01e000, 0xb178a000, 4096)
09-13 11:58:16.900   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.900   317  6979 V AudioCache: memcpy(0xaf01f000, 0xb178a000, 4096)
09-13 11:58:16.901   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.901   317  6979 V AudioCache: memcpy(0xaf020000, 0xb178a000, 4096)
09-13 11:58:16.901   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.901   317  6979 V AudioCache: memcpy(0xaf021000, 0xb178a000, 4096)
09-13 11:58:16.902   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.902   317  6979 V AudioCache: memcpy(0xaf022000, 0xb178a000, 4096)
09-13 11:58:16.902   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.902   317  6979 V AudioCache: memcpy(0xaf023000, 0xb178a000, 4096)
09-13 11:58:16.903   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.903   317  6979 V AudioCache: memcpy(0xaf024000, 0xb178a000, 4096)
09-13 11:58:16.903   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.903   317  6979 V AudioCache: memcpy(0xaf025000, 0xb178a000, 4096)
09-13 11:58:16.904   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.904   317  6979 V AudioCache: memcpy(0xaf026000, 0xb178a000, 4096)
09-13 11:58:16.904   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.904   317  6979 V AudioCache: mem,cpy(0xaf027000, 0xb178a000, 4096)
09-13 11:58:16.905   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.905   317  6979 V AudioCache: memcpy(0xaf028000, 0xb178a000, 4096)
09-13 11:58:16.905   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.905   317  6979 V AudioCache: memcpy(0xaf029000, 0xb178a000, 4096)
09-13 11:58:16.906   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.906   317  6979 V AudioCache: memcpy(0xaf02a000, 0xb178a000, 4096)
09-13 11:58:16.907   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.907   317  6979 V AudioCache: memcpy(0xaf02b000, 0xb178a000, 4096)
09-13 11:58:16.907   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.907   317  6979 V AudioCache: memcpy(0xaf02c000, 0xb178a000, 4096)
09-13 11:58:16.908   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.908   317  6979 V AudioCache: memcpy(0xaf02d000, 0xb178a000, 4096)
09-13 11:58:16.908   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.908   317  6979 V AudioCache: memcpy(0xaf02e000, 0xb178a000, 4096)
09-13 11:58:16.909   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.909   317  6979 V AudioCache: memcpy(0xaf02f000, 0xb178a000, 4096)
09-13 11:58:16.909   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.909   317  6979 V AudioCache: memcpy(0xaf030000, 0xb178a000, 4096)
,09-13 11:58:16.914   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.914   317  6979 V AudioCache: memcpy(0xaf031000, 0xb178a000, 4096)
09-13 11:58:16.914   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.914   317  6979 V AudioCache: memcpy(0xaf032000, 0xb178a000, 4096)
09-13 11:58:16.915   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.915   317  6979 V AudioCache: memcpy(0xaf033000, 0xb178a000, 4096)
09-13 11:58:16.915   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.915   317  6979 V AudioCache: memcpy(0xaf034000, 0xb178a000, 4096)
09-13 11:58:16.916   317  6979 V AudioCache: write(0xb178a000, 4096)
09-13 11:58:16.916   317  6979 V AudioCache: memcpy(0xaf035000, 0xb178a000, 4096)
09-13 11:58:16.916   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-13 11:58:16.916   317  6979 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 11:58:16.916   317  6979 V AwesomePlayer: postAudioEOS() 
09-13 11:58:16.916   317  6979 V AudioCache: write(0xb178a000, 280)
09-13 11:58:16.916   317  6979 V AudioCache: memcpy(0xaf036000, 0xb178a000, 280)
09-13 11:58:16.918   317  6976 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 11:58:16.918   317  6976 V AwesomePlayer: onStreamDone
09-13 11:58:16.918   317  6976 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 11:58:16.918   317  6976 V AudioCache: notify(0xb16a67c0, 2, 0, 0)
09-13 11:58:16.918   317  6976 V AudioCache: playback complete
09-13 11:58:16.918   317  2174 V AudioCache: wait - success
09-13 11:58:16.918   317  2174 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 11:58:16.918   317  6976 V AwesomePlayer: pause_l() 
09-13 11:58:16.918   317  6976 V AudioCache: notify(0xb16a67c0, 7, 0, 0)
09-13 11:58:16.918   317  6976 V AudioCache: ignored
09-13 11:58:16.918   317  6976 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:16.918   317  6976 D AudioPlayer: Pause Playback at 1068125
09-13 11:58:16.919   317  2174 V AwesomePlayer: reset_l() 
09-13 11:58:16.919   317  2174 V AudioCache: notify(0xb16a67c0, 8, 0, 0)
09-13 11:58:16.919   317  2174 V AudioCache: ignored
09-13 11:58:16.919   317  2174 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:16.919   317  2174 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-13 11:58:16.919   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 11:58:16.919   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 11:58:16.919   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 11:58:16.919   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 11:58:16.919   317  6978 V OMXCod,ec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
09-13 11:58:16.919   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 11:58:16.920   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 11:58:16.920   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 11:58:16.920   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-13 11:58:16.920   317  6978 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 11:58:16.920   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 11:58:16.920   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 11:58:16.920   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-13 11:58:16.921   317  2174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,09-13 11:58:16.921   317  2174 D AudioPlayer: AudioPlayer releasing audio source
09-13 11:58:16.921   317  2174 D AudioPlayer: AudioPlayer done releasing audio source
09-13 11:58:16.921   317  2174 V AwesomePlayer: reset_l() 
09-13 11:58:16.921   317  2174 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:16.921   317  2174 V AwesomePlayer: ~AwesomePlayer call
09-13 11:58:16.921   317  2174 V AwesomePlayer: reset_l() 
09-13 11:58:16.921   317  2174 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:16.922  6880  6974 V SoundPool: close(31)
09-13 11:58:16.922  6880  6974 V SoundPool: pointer = 0xa0034000, size = 205080, sampleRate = 48000, numChannels = 2
09-13 11:58:16.931  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 11:58:16.932  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 11:58:16.934  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6465
,09-13 11:58:16.938  6947  6947 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:16.940   312  6981 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 11:58:16.941  1035  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 11:58:16.942  6947  6947 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 11:58:16.942  6947  6947 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 11:58:16.942  6947  6947 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 11:58:16.944  6947  6947 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:16.944  6947  6947 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 11:58:16.951  6897  6897 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-13 11:58:16.978  2599  2599 D [Concierge]Service: onStartCommand(). Type : 9
,09-13 11:58:17.017  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=240715448 [*alarm*], flags=0x0
,09-13 11:58:17.196  6591  6591 I UEI.SmartControl: Supports setup maps: true
,09-13 11:58:17.199  6591  6591 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 11:58:17.199  6591  6591 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 11:58:17.200  6591  6591 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 11:58:17.200  6591  6591 I UEI.SmartControl: ### init IR Blaster...
09-13 11:58:17.203  6591  6591 D serial_port: Configuring serial port
09-13 11:58:17.203  6591  6591 E UEI.SmartControl: UEIBLaster setting for 616
09-13 11:58:17.204  6591  6591 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 11:58:17.204  6591  6591 I UEI.SmartControl: configuring settings for MAXQ616
09-13 11:58:17.204  6591  6591 I UEI.SmartControl: Get version...
09-13 11:58:17.220  6591  6986 D UEI.SmartControl: serial port data available: 21
,09-13 11:58:17.248  6591  6591 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-13 11:58:17.249  6591  6591 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 11:58:17.249  6591  6591 I UEI.SmartControl: QS saving settings...
,09-13 11:58:17.251  6591  6591 D UEI.SmartControl: IR Blaster version: 25672567
09-13 11:58:17.270  6591  6986 D UEI.SmartControl: serial port data available: 4
,09-13 11:58:17.304  6591  6591 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-13 11:58:17.310  6591  6992 I UEI.SmartControl: Device manager: loading config....
09-13 11:58:17.311  6591  6992 D UEI.SmartControl: ----------- loading internal config...
09-13 11:58:17.311  6591  6591 E UEI.SmartControl: Services init done
09-13 11:58:17.311  6591  6591 D UEI.SmartControl: QS Service init finished
09-13 11:58:17.313  6591  6591 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 11:58:17.313  6591  6591 D UEI.SmartControl: QS Service version code: 201091
09-13 11:58:17.314  6591  6591 D UEI.SmartControl: Service requested: Control
09-13 11:58:17.330  6591  6591 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-13 11:58:17.335  6880  6880 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 11:58:17.337  6591  6607 I UEI.SmartControl: ------ IControl API: 11
09-13 11:58:17.337  6591  6607 D UEI.SmartControl: File observer start...
09-13 11:58:17.337  6591  6607 E UEI.SmartControl: IR Port is disabled: false
09-13 11:58:17.337  6591  6607 D UEI.SmartControl: Starting file observer...
09-13 11:58:17.339  6591  6607 I UEI.SmartControl: Registering callback...
09-13 11:58:17.340  6591  6591 D UEI.SmartControl: Internal service binding...
09-13 11:58:17.340  6591  6606 I UEI.SmartControl: ------ IControl API: 19
09-13 11:58:17.341  6591  6606 I UEI.SmartControl: Registering Services Ready callback...
09-13 11:58:17.341  6591  6992 E UEI.SmartControl: Loading SETTINGS...
09-13 11:58:17.346  6591  6992 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-13 11:58:17.366  6591  6991 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-13 11:58:17.368  6880  6896 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 11:58:17.369  6880  6972 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 11:58:17.369  6880  6972 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 11:58:17.370  6880  6880 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 11:58:17.370  6880  6880 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 11:58:17.370  6591  6607 I UEI.SmartControl: ------ IControl API: 8
09-13 11:58:17.371  6591  6991 D UEI.SmartControl: -----service ready thread exits
09-13 11:58:17.373  6880  6880 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 11:58:17.373  6880  6880 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 11:58:17.373  6880  6880 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 11:58:17.373  6880  6880 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 11:58:17.374  6880  6880 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 11:58:17.375  6880  6880 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 11:58:17.379  6880  6880 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-13 11:58:17.384  6880  6880 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 11:58:17.384  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 11:58:17.385  6880  6880 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 11:58:17.385  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 11:58:17.386  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 11:58:17.387  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-13 11:58:17.388  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-13 11:58:17.390  6880  6880 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473760697389]
09-13 11:58:17.398  6880  6880 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-13 11:58:17.402  1035  1696 I ActivityManager: Killing 5995:com.android.gallery3d/u0a27 (adj 15): empty #17
09-13 11:58:17.438  6880  6997 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-13 11:58:17.443  1035  1696 I ActivityManager: Killing 6493:com.lge.email/u0a23 (adj 15): empty #18
09-13 11:58:17.479  1035  2028 W libprocessgroup: failed to open /acct/uid_10027/pid_5995/cgroup.procs: No such file or directory
,09-13 11:58:17.485  1035  1575 W libprocessgroup: failed to open /acct/uid_10023/pid_6493/cgroup.procs: No such file or directory
09-13 11:58:17.493  6880  6880 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-13 11:58:17.498  6880  6880 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 11:58:17.499  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-13 11:58:17.499  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-13 11:58:17.500  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-13 11:58:17.500  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-13 11:58:17.501  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-13 11:58:17.513  6880  6880 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-13 11:58:18.220  1035  2031 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 11:58:18.221  1035  2031 D WifiService: setWifiEnabled: true pid=6708, uid=10118
09-13 11:58:18.221  1035  2031 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:58:18.248  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-13 11:58:18.250  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 11:58:18.250  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 11:58:18.252  1035  1391 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 11:58:18.252  1035  1391 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 11:58:18.254  1035  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 11:58:18.254  1035  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 11:58:18.255  1035  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 11:58:18.255  1035  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 11:58:18.255  1035  1391 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 11:58:18.255  1035  1391 E WifiHW  : unknown target_country: EU , set to default
09-13 11:58:18.255  1035  1391 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 11:58:18.255  1035  1391 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 11:58:18.255  1035  1391 I WifiUtil: gEnableBmps=1
09-13 11:58:18.276  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:18.284  1035  1111 D Tethering: MasterInitialState.processMessage what=3
09-13 11:58:18.289  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:58:18.296  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:18.297  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:18.302  1035  1111 D Tethering: MasterInitialState.processMessage what=3
,09-13 11:58:18.305  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:18.316  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:58:18.319  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 11:58:18.322  6396  6848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 11:58:18.326  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:18.337  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 11:58:18.346  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-13 11:58:18.366  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:18.427  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:18.443  1035  1051 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7012 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-13 11:58:18.448  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:18.448  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 11:58:18.519  7012  7012 I AppUp4:AppBoxCP: onCreate
,09-13 11:58:18.520  7012  7012 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-13 11:58:18.531  7012  7012 I AppUp4:DB:  setFingerPrint start
,09-13 11:58:18.531  7012  7012 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-13 11:58:18.540  7012  7012 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-13 11:58:18.540  7012  7012 I AppUp4:DB:  SDK version = 21
09-13 11:58:18.540  7012  7012 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-13 11:58:18.542  7012  7012 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-13 11:58:18.544  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 11:58:18.544  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:18.547  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 11:58:18.547  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 11:58:18.554  7012  7012 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 11:58:18.608  7012  7012 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:18.608  7012  7012 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:18.618  7012  7012 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@218cf877
09-13 11:58:18.618  7012  7012 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 11:58:18.618  7012  7012 D AppUp4:CustFacade: isPhone : true
09-13 11:58:18.619  7012  7012 D AppUp4:CustModeStarterReceiver: begin check event
09-13 11:58:18.620  7012  7012 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-13 11:58:18.620  7012  7012 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-13 11:58:18.621  7012  7033 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-13 11:58:18.621  7012  7033 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-13 11:58:18.621  7012  7033 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-13 11:58:18.629  1035  1917 I ActivityManager: Killing 6056:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-13 11:58:18.700  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:18.700  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 11:58:18.703  1035  1880 W libprocessgroup: failed to open /acct/uid_10080/pid_6056/cgroup.procs: No such file or directory
,09-13 11:58:18.707  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 11:58:18.711  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:18.719  4287  7035 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 11:58:18.727  4287  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:18.729  4287  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 11:58:18.793  1035  1649 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7040 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 11:58:18.874  7040  7040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 11:58:18.874  7040  7040 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 11:58:18.876  7040  7040 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 11:58:18.877  7040  7040 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 11:58:18.992  7040  7040 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 11:58:19.022  7040  7040 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-13 11:58:19.084  7040  7040 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 11:58:19.123  7040  7040 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:19.124  7040  7040 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:19.139  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 11:58:19.139  1035  1111 D Tethering: InitialState.processMessage what=4
09-13 11:58:19.140  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 11:58:19.145   312   894 D SoftapController: Softap fwReload - Ok
,09-13 11:58:19.149  1035  1391 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (887ms)
09-13 11:58:19.152   312   894 D CommandListener: Setting iface cfg
09-13 11:58:19.152   312   894 D CommandListener: Trying to bring down wlan0
09-13 11:58:19.160   312   894 D CommandListener: Clearing all IP addresses on wlan0
,09-13 11:58:19.163  1035  1391 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 11:58:19.156  7067  7067 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:19.190  7067  7067 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 11:58:19.156  7067  7067 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 11:58:19.224  7067  7067 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 11:58:19.224  7067  7067 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-13 11:58:19.253  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 11:58:19.264  1035  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 11:58:19.264  1035  1391 E WifiStateMachine: useWiFiOffloading() : false
09-13 11:58:19.264  1035  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 11:58:19.264  1035  1391 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 11:58:19.264  1035  1391 D WifiMonitor: connecting to supplicant
,09-13 11:58:19.266  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 11:58:19.267  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 11:58:19.268  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:19.269  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:19.270  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:19.286  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 11:58:19.286  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:19.287  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-13 11:58:19.295  7040  7040 I HubEmail: JNI_OnLoad()
09-13 11:58:19.295  7040  7040 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 11:58:19.295  7040  7040 I HubEmail: registerNatives()
09-13 11:58:19.295  7040  7040 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 11:58:19.295  7040  7040 I HubEmail: registerNativeMethods()
09-13 11:58:19.295  7040  7040 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 11:58:19.295  7040  7040 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-13 11:58:19.299  7067  7067 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 11:58:19.330  1035  1895 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7080 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-13 11:58:19.334  6918  7077 W FormManager: Network not available. Please check & try again.
09-13 11:58:19.338  6918  7078 V FormManager: Network unavailable.
09-13 11:58:19.339  7040  7079 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:19.341  6918  7078 V FormManager: Network unavailable.
09-13 11:58:19.346  1035  1052 I ActivityManager: Killing 6525:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-13 11:58:19.362  7067  7067 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 11:58:19.372  1035  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 11:58:19.372  1035  1391 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 11:58:19.373  1035  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 11:58:19.373  1035  1391 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 11:58:19.374  1035  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-13 11:58:19.374  1035  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:19.375  1035  1391 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 11:58:19.375  1035  1391 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 11:58:19.375  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-13 11:58:19.375  1035  7097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-13 11:58:19.375  1035  7097 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 11:58:19.376  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 11:58:19.376  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 11:58:19.376  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 11:58:19.376  1035  7097 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 11:58:19.376  1035  7097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 11:58:19.376  1035  1391 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 11:58:19.376  1035  1391 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 11:58:19.376  1035  1391 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-13 11:58:19.409  1035  2031 W libprocessgroup: failed to open /acct/uid_10061/pid_6525/cgroup.procs: No such file or directory
09-13 11:58:19.413  1035  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 11:58:19.413  1035  1391 E WifiStateMachine: useWiFiOffloading() : false
09-13 11:58:19.413  1035  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 11:58:19.414  1035  1391 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 11:58:19.414  1035  1391 D WifiNative-wlan0: SET update_config 1: returned true
09-13 11:58:19.414  1035  1391 D WifiConfigStore: Loading config and enabling all networks 
09-13 11:58:19.414  1035  1391 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 11:58:19.415  1035  1391 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 11:58:19.416  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:19.417  1940  1940 D WfdService: Waiting for WifiP2p enabling
09-13 11:58:19.418  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:19.419  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:19.419  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:19.419  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:19.419  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-13 11:58:19.420  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 11:58:19.420  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:19.421  1035  1403 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,09-13 11:58:19.421  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:19.421  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:19.421  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:19.421  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:19.421  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:19.421  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:19.421  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:19.421  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:19.421  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:19.421  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:19.424  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:19.424  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:19.424  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:19.424  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:19.424  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:19.424  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:19.424  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:19.424  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:19.424  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:58:19.424  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:19.425  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:19.427  1035  1391 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-13 11:58:19.440  1035  1391 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-13 11:58:19.440  1035  1391 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-13 11:58:19.441  1035  1391 D WifiStateMachine: enableVerboseLogging : level 2
09-13 11:58:19.441  1035  1391 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 11:58:19.441  1035  1391 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 11:58:19.441  1035  1391 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 11:58:19.442  1035  1391 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 11:58:19.442  1035  1391 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 11:58:19.442  1035  1391 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 11:58:19.442  1035  1391 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 11:58:19.443  1035  1391 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 11:58:19.443  1035  1391 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 11:58:19.443  1035  1391 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 11:58:19.444  1035  1391 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 11:58:19.444  1035  1391 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 11:58:19.444  1035  1391 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 11:58:19.445  1035  1391 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 11:58:19.445  1035  1391 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 11:58:19.445  1035  1391 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 11:58:19.446  1940  1940 D WfdsService: Supplicant Connection state is changed : true
09-13 11:58:19.446  1035  1391 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 11:58:19.446  1035  1391 D WifiNative-HAL: Setting external_sim to 1
09-13 11:58:19.446  1035  1391 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 11:58:19.446  1940  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 11:58:19.446  1940  2296 D WfdsService: Set the WFDS Monitor: true
09-13 11:58:19.446  1940  2296 D WfdsMonitor: WfdsMonitorThread create
09-13 11:58:19.446  1940  2296 D WfdsMonitor: WFDS Monitor is created and started
09-13 11:58:19.446  1940  2296 D WfdsService: WiFi: Supplicant connection re-established
,09-13 11:58:19.447  1035  1391 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 11:58:19.447  1035  1391 I WifiNative-HAL: startHal
09-13 11:58:19.447  1035  1391 D wifi    : setting scan oui 0xaf6f9300
09-13 11:58:19.447  1035  1391 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 11:58:19.447  1035  1391 I WifiNative-HAL: startHal
09-13 11:58:19.447  1940  7099 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 11:58:19.447  1035  1391 D wifi    : setting scan oui 0xaf6f9300
09-13 11:58:19.447  1035  1391 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 11:58:19.448  1940  7099 E CtrlSupplicant: Succeed to open control connection
09-13 11:58:19.448  1035  1391 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 11:58:19.448  1940  7099 E CtrlSupplicant: Succeed to open monitor connection
09-13 11:58:19.448  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 11:58:19.448  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 11:58:19.449  1940  7099 D WfdsMonitor: Supplicant connection established
09-13 11:58:19.449  1940  2296 D WfdsService: Connected to the supplicant for wfds
09-13 11:58:19.449  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 11:58:19.449  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 11:58:19.449  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 11:58:19.450  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 11:58:19.450  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 11:58:19.450  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 11:58:19.450  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 11:58:19.450  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 11:58:19.450  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 11:58:19.450  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 11:58:19.450  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 11:58:19.451  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 11:58:19.451  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 11:58:19.451  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 11:58:19.451  7067  7067 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 11:58:19.451  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 11:58:19.451  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 11:58:19.452  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 11:58:19.452  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 11:58:19.453  1035  1391 E WifiNative: : [192,321,725 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 11:58:19.453  1035  1391 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 11:58:19.453  1035  1391 D WifiNative-wlan0: RECONNECT: returned true
09-13 11:58:19.453  1035  1391 D WifiNative-wlan0: doString: [STATUS]
09-13 11:58:19.454  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 11:58:19.454  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 11:58:19.454  1035  1391 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 11:58:19.454  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 11:58:19.455  1035  1391 D WifiNative-wlan0: SET ps 1: returned true
09-13 11:58:19.455  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 11:58:19.457   312   894 D CommandListener: Setting iface cfg
09-13 11:58:19.457   312   894 D CommandListener: Trying to bring up p2p0
09-13 11:58:19.458  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 11:58:19.458  1035  1390 D LGWifiP2pService: P2pEnablingState
09-13 11:58:19.458  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.458  1035  1390 D LGWifiP2pService: P2p socket connection successful
09-13 11:58:19.458  1035  1390 D LGWifiP2pService: P2pEnabledState
09-13 11:58:19.459  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 11:58:19.459  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 11:58:19.459  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-13 11:58:19.459  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.459  1035  1556 I WifiNative-HAL: startHal
09-13 11:58:19.459  1035  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.459  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf6f9300
09-13 11:58:19.459  1035  1556 D wifi    : failed to get capabilities : -3
09-13 11:58:19.459  1035  1556 E WifiScanningService: could not get scan capabilities
09-13 11:58:19.460  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 11:58:19.460  1940  1940 D WfdsService: WifiP2pState is changed : true
09-13 11:58:19.460  1940  2296 D WfdsService: Receive the WFDS_ENABLE Method
09-13 11:58:19.460  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 11:58:19.460  1940  2296 D WfdsService: Set the WFDS Monitor: true
09-13 11:58:19.460  1940  2296 D WfdsService: Connected to the supplicant for wfds
09-13 11:58:19.460  1940  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 11:58:19.461  7067  7067 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 11:58:19.461  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 11:58:19.461  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 11:58:19.461  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 11:58:19.461  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
09-13 11:58:19.462  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 11:58:19.462  1035  1390 D LGWifiP2pService: before postfix = G3
09-13 11:58:19.462  1035  1390 D WifiServerServiceExt: postfix byte check : 2
09-13 11:58:19.462  1035  1390 D LGWifiP2pService: after postfix = G3
09-13 11:58:19.462  1940  1940 D WfdsService: isConnected: false
09-13 11:58:19.462  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 11:58:19.462  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 11:58:19.462  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 11:58:19.463  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 11:58:19.463  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 11:58:19.463  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 11:58:19.463  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 11:58:19.464  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 11:58:19.464  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
09-13 11:58:19.464  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 11:58:19.465  1035  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 11:58:19.465  1940  2296 D WfdsService: selectPreferredScanChannel [36]
09-13 11:58:19.465  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 11:58:19.465  1940  2296 D WfdsService: STATE :, WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 11:58:19.465  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 11:58:19.465  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 11:58:19.466  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 11:58:19.466  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 11:58:19.466  1940  1940 D WfdsService: Update P2p Interface State: 3
09-13 11:58:19.466  1035  1391 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 11:58:19.466  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 11:58:19.466  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 11:58:19.467  1035  1391 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 11:58:19.467  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 11:58:19.467  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 11:58:19.467  1035  1391 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 11:58:19.467  1035  1391 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 11:58:19.468  1035  1391 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 11:58:19.468  1035  1391 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 11:58:19.469  1035  1391 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 11:58:19.469  1035  1391 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,09-13 11:58:19.486  7067  7067 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 11:58:19.487  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 11:58:19.487  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 11:58:19.487  1035  1391 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,09-13 11:58:19.487  1035  1390 D LGWifiP2pService: InactiveState
09-13 11:58:19.487  1035  1390 D LGWifiP2pService: InactiveState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.487  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.487  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,09-13 11:58:19.488  1035  1391 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 11:58:19.488  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 11:58:19.489  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:19.489  1035  7097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 11:58:19.489  1035  7097 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:19.489  1035  7097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:19.489  1035  7097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:19.489  7067  7067 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 11:58:19.489  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.489  1035  1391 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 11:58:19.489  1035  1391 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 11:58:19.489  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.490  1940  7099 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.490  1940  7099 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:19.490  7067  7067 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.490  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.490  1035  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.491  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.491  1035  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.491  1035  1391 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 11:58:19.491  1940  2296 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 11:58:19.491  1035  7097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:19.491  1035  1035 E WifiServerServiceExt: No p2p device connected
09-13 11:58:19.491  1035  7097 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.491  1035  7097 E WifiMonitor: handleEve,nt 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.491  1035  7097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.491  1035  7097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:19.491  1940  7099 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:19.491  1035  7097 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.491  1035  1391 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 11:58:19.491  1035  7097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.491  1035  7097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.491  1035  1391 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 11:58:19.491  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 11:58:19.492  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 11:58:19.492  7080  7080 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:19.492  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:19.492  7080  7080 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 11:58:19.493  7067  7067 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 11:58:19.493  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.493  1035  1391 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 11:58:19.494  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.494  1035  1391 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 11:58:19.494  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.494  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:19.494  1940  7099 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:19.494  1940  7099 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:19.494  1035  1391 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 11:58:19.494  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,09-13 11:58:19.495  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:19.495  1035  7097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:19.495  1035  7097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:19.495  1035  7097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:19.495  1035  7097 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.495  1035  7097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-13 11:58:19.495  1035  7097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.495  1035  1391 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 11:58:19.495  1035  7097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:19.495  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 11:58:19.495  1035  7097 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.495  1035  7097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-13 11:58:19.495  1035  7097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:19.495  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 11:58:19.495  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 11:58:19.495  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 11:58:19.495  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 11:58:19.495  1035  7097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 11:58:19.495  1035  7097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-13 11:58:19.496  7080  7080 D PhoneMonitor: Register our PhoneStateListener
09-13 11:58:19.496  1035  1391 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 11:58:19.496  1035  1391 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 11:58:19.496  1035  1391 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 11:58:19.496  1035  1391 D WifiNative-wlan0: doBoolean: SCAN
09-13 11:58:19.497  1035  1391 D WifiNative-wlan0: SCAN: returned false
09-13 11:58:19.497  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=192367  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 11:58:19.500  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 11:58:19.500  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:19.501  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 11:58:19.503  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:19.503  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:19.503  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 11:58:19.503  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=192373  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 11:58:19.504  1035  1391 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:19.504  1035  1391 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:19.505  1035  1391 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:19.505  1035  1391 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:19.506  1035  1391 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:19.506  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:19.507  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 11:58:19.516  7080  7080 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 11:58:19.518  7080  7080 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 11:58:19.532  7080  7080 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-13 11:58:19.533  7080  7080 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-13 11:58:19.533  7080  7080 D TelephonyAutoProfiling: [parse] Load xml
09-13 11:58:19.536  7080  7080 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-13 11:58:19.536  7080  7080 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-13 11:58:19.536  7080  7080 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-13 11:58:19.544  7080  7080 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-13 11:58:19.562  1035  1957 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7102 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 11:58:19.563  1035  1957 I ActivityManager: Killing 6087:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-13 11:58:19.619  1035  2031 W libprocessgroup: failed to open /acct/uid_10097/pid_6087/cgroup.procs: No such file or directory
,09-13 11:58:19.841  1035  2031 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7123 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-13 11:58:19.844  1035  2031 I ActivityManager: Killing 6557:com.lge.eula/1000 (adj 15): empty #17
09-13 11:58:19.890  1035  1985 W libprocessgroup: failed to open /acct/uid_1000/pid_6557/cgroup.procs: No such file or directory
,09-13 11:58:20.003  1035  1985 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7140 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 11:58:20.005  1035  1985 I ActivityManager: Killing 6574:com.lge.bnr/1000 (adj 15): empty #17
09-13 11:58:20.010  7067  7067 E wpa_supplicant: USIM:  scard_init function
09-13 11:58:20.011  7067  7067 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 11:58:20.013  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 11:58:20.013  1035  7097 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 11:58:20.013  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 11:58:20.013  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-13 11:58:20.013  1035  7097 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 11:58:20.013  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 11:58:20.013  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 11:58:20.015  1035  1391 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 11:58:20.015  1035  1391 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 11:58:20.015  1035  1391 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 11:58:20.016  1035  1391 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
09-13 11:58:20.016  1035  1391 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-13 11:58:20.069  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6574/cgroup.procs: No such file or directory
09-13 11:58:20.070  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=192939  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 11:58:20.078  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=192947  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 11:58:20.083  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.084  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.084  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 11:58:20.084  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.084  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:20.088  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.088  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.088  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.088  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-13 11:58:20.092  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-13 11:58:20.092  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 11:58:20.098  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.098  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:20.100  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.123  7067  7067 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 11:58:20.123  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 11:58:20.123  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 11:58:20.123  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 11:58:20.123  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 11:58:20.125  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 11:58:20.125  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-13 11:58:20.127  1035  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 11:58:20.127  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=192996  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 11:58:20.127  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=192997  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 11:58:20.128  1035  1391 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192998
09-13 11:58:20.130  1035  1391 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192999
09-13 11:58:20.130  1035  1391 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=192999
09-13 11:58:20.131  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-13 11:58:20.131  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 11:58:20.131  7067  7067 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 11:58:20.132  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 11:58:20.132  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 11:58:20.132  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 11:58:20.133  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193002
09-13 11:58:20.133  1035  1391 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=193003
09-13 11:58:20.134  1035  7097 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 11:58:20.134  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 11:58:20.134  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 11:58:20.134  1035  7097 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 11:58:20.135  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=193004  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 11:58:20.135  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 11:58:20.135  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 11:58:20.137  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.137  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:20.138  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.138  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.138  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-13 11:58:20.140  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.145  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.145  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.145  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 11:58:20.147  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=193016  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 11:58:20.147  1035  1391 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:20.147  7140  7140 I art     : Almond Protected OAT
09-13 11:58:20.148  1035  1391 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:20.148  1035  1391 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:20.149  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:20.149  1035  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:20.150  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=193019  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 11:58:20.151  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=193020  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 11:58:20.151  1035  1391 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193021
09-13 11:58:20.152  1035  1391 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=193022
09-13 11:58:20.153  1035  1391 D WifiNative-wlan0: doString: [STATUS]
09-13 11:58:20.154  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 11:58:20.154  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 11:58:20.154  1035  1391 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 11:58:20.156  1035  1391 I WifiServiceExtension: setVHTCapabilityType  : false
,09-13 11:58:20.162  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.162  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:20.163  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.164  1035  1391 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 11:58:20.165  1035  1391 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-13 11:58:20.174  1035  1391 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 11:58:20.175  1035  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:58:20.175  1035  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 11:58:20.175  1035  1444 D ConnectivityService: Got NetworkAgent Messenger
09-13 11:58:20.175  1035  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 11:58:20.175  1035  1444 D ConnectivityService: NetworkAgent connected
09-13 11:58:20.175  1035  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 11:58:20.175  1035  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-13 11:58:20.193  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:20.193  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,09-13 11:58:20.203  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.203  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:20.204  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.206  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.206  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 11:58:20.206  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 11:58:20.207  1035  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 11:58:20.207  1035  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:58:20.207  1035  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 11:58:20.208  1035  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 11:58:20.208  1035  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-13 11:58:20.221  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.221  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.221  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 11:58:20.224  7140  7140 D WeatherApplication: removeAccount
09-13 11:58:20.225  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.225  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 11:58:20.225  7140  7140 D WeatherApplication: Account.length = 0
09-13 11:58:20.226  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.227  7140  7140 E WeatherApplication: OPERATOR:OPEN
09-13 11:58:20.232  7140  7140 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:20
09-13 11:58:20.235  7140  7140 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 11:58:20.235  7140  7140 D Weather.Utils: 2 : All the weather widget is gone.
09-13 11:58:20.237  7140  7140 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-13 11:58:20.240  7140  7140 D WeatherAncestor: connectivity changed - connection : true
09-13 11:58:20.241  7140  7140 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-13 11:58:20.250  7140  7140 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-13 11:58:20.250  7140  7140 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 11:58:20.250  7140  7140 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-13 11:58:20.271  7140  7140 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 11:58:20.271  7140  7140 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:20
,09-13 11:58:20.274  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 11:58:20.275  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.275  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.317  1035  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 11:58:20.321   312   894 D CommandListener: Setting iface cfg
,09-13 11:58:20.334  1035  1957 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7165 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 11:58:20.337  1035  1957 I ActivityManager: Killing 2155:com.lge.music/u0a34 (adj 15): empty #17
09-13 11:58:20.362   317   317 V AudioFlinger: 2155 died, releasing its sessions
09-13 11:58:20.362   317   317 V AudioFlinger:  pid 1851 @ 0
09-13 11:58:20.362   317   317 V AudioFlinger:  pid 3453 @ 1
09-13 11:58:20.362   317   317 V AudioFlinger:  pid 3453 @ 2
,09-13 11:58:20.379  1035  1958 W libprocessgroup: failed to open /acct/uid_10034/pid_2155/cgroup.procs: No such file or directory
,09-13 11:58:20.382  1035  1391 E WifiStateMachine: Start Dhcp Watchdog 2
09-13 11:58:20.382  1035  7164 D DhcpStateMachine: StoppedState
09-13 11:58:20.383  1035  7164 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.383  1035  7164 D DhcpStateMachine: WaitBeforeStartState
09-13 11:58:20.383  1035  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=193252  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:20.383  1035  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=193252  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:20.383  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=193253  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:20.384  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:20.384  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 11:58:20.384  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:20.384  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 11:58:20.385  1035  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=193254  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:20.385  1035  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=193255  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:20.386  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=193255  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:20.386  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:147131] from screen [on:0 period:586917858] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 11:58:20.387  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:586917859] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 11:58:20.387  1035  1391 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 11:58:20.390  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 11:58:20.393  1035  1444 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-13 11:58:20.393  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 11:58:20.394  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 11:58:20.394  1035  1391 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 11:58:20.394  1035  1391 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 11:58:20.394  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 11:58:20.395  1035  1391 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 11:58:20.395  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.395  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.396  1035  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.396  1035  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.396  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.396  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.397  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
09-13 11:58:20.397  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
09-13 11:58:20.397  1035  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 11:58:20.397  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 11:58:20.398  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 11:58:20.398  1035  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 11:58:20.398  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 11:58:20.399  1035  1391 D WifiNative-wlan0: SET ps 0: returned true
09-13 11:58:20.399  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 11:58:20.399  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 11:58:20.399  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 11:58:20.399  1035  1391 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 11:58:20.399  1035  1391 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 11:58:20.399  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26fd3a74 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.399  1035  1391 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 11:58:20.399  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26fd3a74 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.399  1035  7164 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.399  1035  7164 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 11:58:20.400   312   894 D CommandListener: Setting iface cfg
09-13 11:58:20.401   312   894 D CommandListener: Trying to bring up wlan0
09-13 11:58:20.401  1035  1391 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 11:58:20.402  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:20.402  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 11:58:20.403  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:20.403  1035  1035 D WifiServerServiceExt: setSupplican,tStateCOMPLETED
,09-13 11:58:20.403  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.404  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.404  1035  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.404  1035  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.404  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.405  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:20.405  1035  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 11:58:20.405  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 11:58:20.406  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 11:58:20.406  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 11:58:20.406  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.406  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 11:58:20.406  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.406  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 11:58:20.406  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 11:58:20.406  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 11:58:20.406  1035  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 11:58:20.406  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 11:58:20.424  1035  1391 D WifiNative-wlan0: SET ps 1: returned true
,09-13 11:58:20.425  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-13 11:58:20.425  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 11:58:20.425  1035  1391 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 11:58:20.426  1035  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 11:58:20.426  1035  1444 D ConnectivityService: ignoring duplicate network state non-change
09-13 11:58:20.427  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.427  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:20.428  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.428  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.428  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.428  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 11:58:20.429  1035  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 11:58:20.430  1035  1444 D ConnectivityService: Adding iface wlan0 to network 101
09-13 11:58:20.431  1035  1391 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 11:58:20.433  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.433  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.433  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 11:58:20.434  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 11:58:20.434  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 11:58:20.436  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.436  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.436  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 11:58:20.436  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 11:58:20.439  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.439  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:20.439  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-13 11:58:20.447  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.447  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:20.448  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.450  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.450  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 11:58:20.450  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.452  1035  1444 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 11:58:20.452  1035  1444 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-13 11:58:20.453  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:20.453  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 11:58:20.453  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.453  1035  1444 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 11:58:20.454   312   894 E Netd    : netlink response contains error (File exists)
09-13 11:58:20.454  1035  1444 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 11:58:20.455  1035  1444 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 11:58:20.455  1035  1444 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-13 11:58:20.455  1035  1444 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 11:58:20.456  1035  1444 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 11:58:20.456  1035  1444 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 11:58:20.456  1035  1444 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 11:58:20.457  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.457  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 11:58:20.457  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:20.457  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 11:58:20.458  1035  1444 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 11:58:20.459  1035  1444 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:20.459  1035  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:20.459  1035  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 11:58:20.459  1035  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:20.459  1035  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 11:58:20.459  1035  1444 D ConnectivityService: currentScore = 0, newScore = 20
09-13 11:58:20.459  1035  1444 D ConnectivityService:    accepting network in place of null
09-13 11:58:20.459  1035  1444 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:20.459  1035  1391 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:20.459  1035  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:20.460  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:,20.460   312  7186 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 11:58:20.461  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 11:58:20.461  1035  1444 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 11:58:20.461  1035  1444 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 11:58:20.461  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 11:58:20.461  1035  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:20.461  1035  1444 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 11:58:20.462  1035  1444 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 11:58:20.463  1035  1444 D ConnectivityService: validation of new default Network = false
09-13 11:58:20.463  1035  1444 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 11:58:20.463  1035  1444 D DSQN    : enableDataServiceNotify 
09-13 11:58:20.463  1035  1444 D DSQN    : start dsqn bin
09-13 11:58:20.463  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 11:58:20.463  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 11:58:20.463  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 11:58:20.463  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-13 11:58:20.469  1035  1444 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 11:58:20.470  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:20.470  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:20.470  1035  1444 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:20.470  1602  2078 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 11:58:20.466  7187  7187 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:20.466  7187  7187 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:20.477  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-13 11:58:20.485  7187  7187 E DSQN    : DSQN ssw
,09-13 11:58:20.491  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 11:58:20.492  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.493  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.497   279   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 11:58:20.497   279   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 11:58:20.497   279   426 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 11:58:20.497  1816  7189 I CheckinService: active receiver: enabled
09-13 11:58:20.498  7165  7193 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 11:58:20.499   279   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 11:58:20.499   279   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 11:58:20.499   279   426 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 11:58:20.499  7165  7193 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 11:58:20.504  1816  7189 I CheckinService: Preparing to send checkin request
09-13 11:58:20.504  1816  7189 I EventLogService: Accumulating logs since 1473760565246
,09-13 11:58:20.507   279   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 11:58:20.507   279   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 11:58:20.507   279   426 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 11:58:20.508  7165  7195 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 11:58:20.521   312  7186 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-13 11:58:20.521   279   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 11:58:20.521   279   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 11:58:20.521   279   426 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 11:58:20.521  7165  7195 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 11:58:20.531  1816  7189 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-13 11:58:20.553   312  7186 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 11:58:20.577   312   893 D LGDataListener: argv[0]=dsqncommand
09-13 11:58:20.577   312   893 D LGDataListener: argv[1]=wlan0
09-13 11:58:20.577   312   893 D LGDataListener: argv[2]=1
,09-13 11:58:20.577   312   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,09-13 11:58:20.578  1035  1109 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 11:58:20.578  1035  1109 D DSQN    : start to monitor internet connection
09-13 11:58:20.598  1035  1880 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7213 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-13 11:58:20.600  1035  7164 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 11:58:20.601  1035  7164 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 11:58:20.601  1035  7164 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 11:58:20.596  7220  7220 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 11:58:20.607  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 09:58:20 GMT], X-Android-Received-Millis=[1473760700607], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473760700576]}
09-13 11:58:20.608  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 11:58:20.608  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 11:58:20.608  7220  7220 I dhcpcd  : version 5.5.6 starting
09-13 11:58:20.608  1035  1444 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-13 11:58:20.608  1035  1444 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 11:58:20.609  1035  1444 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:20.609  1035  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:20.609  1035  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 11:58:20.609  1035  1444 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-13 11:58:20.609  1035  1444 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 11:58:20.609  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:20.609  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:20.609  7220  7220 E dhcpcd  : get_duid: m
09-13 11:58:20.609  7220  7220 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 11:58:20.609  7220  7220 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 11:58:20.596  7220  7220 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:20.610  1035  1444 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:20.610  1602  2078 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 11:58:20.610  1035  1444 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:20.611  1035  1391 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:20.611  1035  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:20.611   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 12.261ms
09-13 11:58:20.612  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 11:58:20.613  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:20.613  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 11:58:20.621   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 9.692ms
,09-13 11:58:20.631   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 203us total 9.502ms
,09-13 11:58:20.660  7220  7220 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-13 11:58:20.660  7220  7220 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 11:58:20.660  7220  7220 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 11:58:20.661  7220  7220 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 11:58:20.661  7220  7220 D dhcpcd  : wlan0: sending REQUEST (xid 0x48d23a93), next in 4.58 seconds
09-13 11:58:20.662  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 11:58:20.663  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.663  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:20.675  7213  7213 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-13 11:58:20.676  7213  7213 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 11:58:20.688  7220  7220 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 11:58:20.702  7213  7213 I MultiDex: VM with version 2.1.0 has multidex support
09-13 11:58:20.702  7213  7213 I MultiDex: install
09-13 11:58:20.702  7213  7213 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 11:58:20.709  7165  7165 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-13 11:58:20.712  7213  7213 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-13 11:58:20.716  7165  7165 I LibraryLoader: Loading: webviewchromium
,09-13 11:58:20.718  7165  7165 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3597-3599)
09-13 11:58:20.718  7165  7165 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 11:58:20.718  7220  7220 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 11:58:20.718  7220  7220 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 11:58:20.718  7220  7220 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 11:58:20.718  7220  7220 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 11:58:20.718  7220  7220 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 11:58:20.719  7220  7220 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 11:58:20.719  7220  7220 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 11:58:20.719  7220  7220 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 11:58:20.721  7165  7165 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bcb6afe}
09-13 11:58:20.722  7165  7165 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 11:58:20.723  7165  7165 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 11:58:20.731  7165  7165 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 11:58:20.732  7165  7165 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 11:58:20.751  7165  7165 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 11:58:20.752  7165  7165 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-13 11:58:20.752  7165  7165 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-13 11:58:20.764  7165  7165 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 11:58:20.764  7165  7165 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 11:58:20.764  7165  7165 I Adreno-EGL: Build Date: 12/12/14 금
09-13 11:58:20.764  7165  7165 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 11:58:20.764  7165  7165 I Adreno-EGL: Remote Branch: 
09-13 11:58:20.764  7165  7165 I Adreno-EGL: Local Patches: 
09-13 11:58:20.764  7165  7165 I Adreno-EGL: Reconstruct Branch: 
,09-13 11:58:20.769   317  1398 V AudioPolicyService: registerClient() client 0xb558ada0, uid 10093
09-13 11:58:20.770  7165  7247 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 11:58:20.952  1035  1575 I art     : Explicit concurrent mark sweep GC freed 104342(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.879ms total 127.506ms
,09-13 11:58:20.969  7165  7165 I NSApplication: Starting up...
,09-13 11:58:21.002  1035  7164 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-13 11:58:21.004  1035  7164 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 11:58:21.008  1035  7164 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 11:58:21.008  1035  7164 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 11:58:21.008  1035  7164 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 11:58:21.008  1035  7164 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 11:58:21.008  1035  7164 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 11:58:21.008  1035  7164 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 11:58:21.009  1035  7164 D DhcpStateMachine: RunningState
09-13 11:58:21.038  1035  2028 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7279 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-13 11:58:21.040  1035  2028 I ActivityManager: Killing 6018:com.android.vending/u0a44 (adj 15): empty #17
,09-13 11:58:21.086  7213  7235 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 11:58:21.086  7213  7235 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:21.101  1035  1052 W libprocessgroup: failed to open /acct/uid_10044/pid_6018/cgroup.procs: No such file or directory
,09-13 11:58:21.128  7279  7279 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 11:58:21.254  1035  2031 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 11:58:21.255  1035  2031 D WifiService: setWifiEnabled: false pid=6708, uid=10118
09-13 11:58:21.255  1035  2031 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:58:21.275  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 11:58:21.275  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 11:58:21.275  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 11:58:21.277  1035  1391 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,09-13 11:58:21.278  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 11:58:21.279  1035  1391 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 11:58:21.279  1035  1391 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 11:58:21.280  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 11:58:21.280  1035  1391 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 11:58:21.280  1035  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:58:21.280  1035  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 11:58:21.280  1035  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 11:58:21.280  1035  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 11:58:21.297  1035  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 11:58:21.297  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,09-13 11:58:21.297  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.297  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 11:58:21.297  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.297  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 11:58:21.297  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 11:58:21.298  1035  1391 D WifiNative-wlan0: SET ps 1: returned true
09-13 11:58:21.298  1035  7164 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.298   312   894 D CommandListener: Clearing all IP addresses on wlan0
09-13 11:58:21.325  1035  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 11:58:21.325  1035  1444 D ConnectivityService: ignoring duplicate network state non-change
09-13 11:58:21.325  1035  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-13 11:58:21.326  1035  1035 D WifiHS20: hidePasspointNotification off =false
,09-13 11:58:21.328  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:21.328  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:21.328  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 11:58:21.328  1035  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:21.329  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:21.329  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:21.329  1035  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:21.329  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 11:58:21.330  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:21.330  1035  1391 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 11:58:21.330  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 11:58:21.331  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:21.331  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:21.331  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 11:58:21.331  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 11:58:21.331  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-13 11:58:21.331  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.331  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:21.331  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:21.331  1035  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.332  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:21.332  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 11:58:21.333  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:21.334  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:21.334  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:21.338  1035  1390 D LGWifiP2pService: InactiveState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.338  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.338  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2ea895ed
09-13 11:58:21.339  1035  1390 D LGWifiP2pService: P2pDisablingState
09-13 11:58:21.339  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.339  1035  1390 D LGWifiP2pService: p2p socket connection lost
09-13 11:58:21.339  1035  1390 D LGWifiP2pService: P2pDisabledState
,09-13 11:58:21.341  1035  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 11:58:21.341  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 11:58:21.341  7067  7067 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 11:58:21.341  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.341  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.342  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 11:58:21.342  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 11:58:21.342  1035  1391 D WifiNative-wlan0: SET ps 1: returned true
09-13 11:58:21.350  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 11:58:21.350  1940  1940 D WfdsService: WifiP2pState is changed : false
,09-13 11:58:21.354  1940  2296 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 11:58:21.354  1940  2296 D WfdsService: Set the WFDS Monitor: false
09-13 11:58:21.354  1940  2296 D WfdsMonitor: WFDS Monitor is stopped
09-13 11:58:21.354  1940  2296 D WfdsService: STATE : WfdsDisabledState - enter
09-13 11:58:21.354  1940  7099 D CtrlSupplicant: Received on exit socket, terminate
09-13 11:58:21.354  1940  7099 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 11:58:21.354  1940  7099 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 11:58:21.355  1940  7099 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 11:58:21.355  1940  2299 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 11:58:21.355  1940  2296 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 11:58:21.377   312   894 D CommandListener: Clearing all IP addresses on wlan0
,09-13 11:58:21.378  1035  1444 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 11:58:21.378  1035  1444 D DSQN    : disableDataServiceNotify
09-13 11:58:21.378  1035  1444 D DSQN    : stop dsqn bin
09-13 11:58:21.380  1035  1391 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 11:58:21.380  1035  1391 D WifiNative-p2p0: TERMINATE: returned true
09-13 11:58:21.380  1035  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 11:58:21.380  1035  1391 E WifiStateMachine: useWiFiOffloading() : false
09-13 11:58:21.380  1035  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 11:58:21.384  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 11:58:21.384  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:21.384  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:21.385  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 11:58:21.386  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 11:58:21.387  1035  1444 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 11:58:21.387  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:21.387  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:21.387  1035  1444 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:21.390  1035  1444 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 11:58:21.390  1035  1444 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 11:58:21.390  1035  1444 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 11:58:21.390  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-13 11:58:21.391  7307  7307 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-13 11:58:21.392  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 11:58:21.392  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:21.392  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 11:58:21.393  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 11:58:21.393  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:21.393  1035  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:21.393  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 11:58:21.394  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.394  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.394  1035  7157 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 11:58:21.394  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:21.395  1602  2078 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 11:58:21.396  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:21.398  1035  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:21.398  1035  1444 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:21.398  1035  1444 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:21.398  1035  1391 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:21.398  1035  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:21.398  1035  1444 D NetworkManagementService: Removing idletimer
09-13 11:58:21.398  1035  1444 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:21.398  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 11:58:21.399  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 11:58:21.399  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 11:58:21.399  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 11:58:21.399  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 11:58:21.399  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INT,ERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:21.399  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 11:58:21.399  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:21.399  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:21.399  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:21.399  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:21.399  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:21.399  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:21.399  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:21.399  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:21.399  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:21.399  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:21.399  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:21.400  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:21.400  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:21.400  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:21.400  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:21.400  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:21.400  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:21.400  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:21.400  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:21.400  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:21.400  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:21.400  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:21.400  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 11:58:21.401  6396  6848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 11:58:21.401  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 11:58:21.402  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 11:58:21.402  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 11:58:21.402  1035  10,35 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 11:58:21.402  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 11:58:21.427  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:21.438  7307  7307 I dex2oat : dex2oat took 47.598ms (threads: 4)
09-13 11:58:21.439  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 11:58:21.439  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:21.439  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 11:58:21.439  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 11:58:21.441  7012  7012 I AppUp4:CustModeStarterReceiver: onReceive
09-13 11:58:21.445  7012  7012 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@218cf877
09-13 11:58:21.445  7012  7012 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 11:58:21.445  7012  7012 D AppUp4:CustFacade: isPhone : true
09-13 11:58:21.446  7012  7012 D AppUp4:CustModeStarterReceiver: begin check event
09-13 11:58:21.446  7012  7012 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 11:58:21.449  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 11:58:21.449  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:21.449  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:21.450  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 11:58:21.450  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:21.451  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 11:58:21.453  7213  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 11:58:21.453  7213  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 11:58:21.453  7213  7235 I Adreno-EGL: Build Date: 12/12/14 금
09-13 11:58:21.453  7213  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 11:58:21.453  7213  7235 I Adreno-EGL: Remote Branch: 
09-13 11:58:21.453  7213  7235 I Adreno-EGL: Local Patches: 
09-13 11:58:21.453  7213  7235 I Adreno-EGL: Reconstruct Branch: 
09-13 11:58:21.454  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:21.459  4287  7319 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 11:58:21.460  4287  7320 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:21.460  4287  7320 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 11:58:21.460  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 11:58:21.469  7067  7067 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 11:58:21.469  7067  7067 I wpa_supplicant: monitor socket send errors count : 1
09-13 11:58:21.469  7067  7067 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-4\x00 that cannot receive messages
,09-13 11:58:21.470  1035  1444 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-13 11:58:21.471  1035  7097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 11:58:21.471  1035  7097 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 11:58:21.480  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 11:58:21.481  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:21.481  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 11:58:21.485  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 11:58:21.485  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:21.485  7040  7321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:21.486  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 11:58:21.488  7080  7080 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 11:58:21.488  7080  7080 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 11:58:21.492  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 11:58:21.492  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 11:58:21.492  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 11:58:21.492  1035  7097 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 11:58:21.492  1035  7097 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 11:58:21.493  1035  1391 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194362
09-13 11:58:21.493  1035  1391 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=194362
,09-13 11:58:21.493  7067  7067 W wpa_supplicant: USIM:  scard_deinit function
09-13 11:58:21.494  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 11:58:21.494  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 11:58:21.494  1035  1391 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=194363  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 11:58:21.495  1035  1391 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=194364  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 11:58:21.497  1035  1111 D Tethering: InitialState.processMessage what=4
09-13 11:58:21.497  6918  7324 W FormManager: Network not available. Please check & try again.
09-13 11:58:21.498  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 11:58:21.499  1035  1391 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:21.499  1035  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:21.501  6918  7325 V FormManager: Network unavailable.
09-13 11:58:21.502  7140  7140 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:21
09-13 11:58:21.502  1035  7164 D DhcpStateMachine: StoppedState
09-13 11:58:21.502  1035  7164 D DhcpStateMachine: StoppedState{ when=-160ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:21.503  1035  1391 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 11:58:21.503  1035  1391 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 11:58:21.505  7140  7140 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 11:58:21.505  7140  7140 D Weather.Utils: 2 : All the weather widget is gone.
09-13 11:58:21.506  6918  7325 V FormManager: Network unavailable.
,09-13 11:58:21.506  7140  7140 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 11:58:21.506  7140  7140 D WeatherAncestor: connectivity changed - connection : true
09-13 11:58:21.506  7140  7140 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d73954d
09-13 11:58:21.507  7140  7140 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 11:58:21.507  7140  7140 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 11:58:21.507  7140  7140 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 11:58:21.507  7140  7140 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 11:58:21.507  7140  7140 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:21
09-13 11:58:21.526  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 11:58:21.527  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 11:58:21.527  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 11:58:21.527  6827  6827 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 11:58:21.527  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-13 11:58:21.528  6827  6827 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 11:58:21.528  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 11:58:21.528  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 11:58:21.528  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 11:58:21.528  6827  6827 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 11:58:21.528  6827  6827 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 11:58:21.530  7213  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 11:58:21.530  7213  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 11:58:21.530  7213  7235 I Adreno-EGL: Build Date: 12/12/14 금
09-13 11:58:21.530  7213  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 11:58:21.530  7213  7235 I Adreno-EGL: Remote Branch: 
09-13 11:58:21.530  7213  7235 I Adreno-EGL: Local Patches: 
09-13 11:58:21.530  7213  7235 I Adreno-EGL: Reconstruct Branch: 
09-13 11:58:21.533  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:21.536  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 11:58:21.537  6918  7328 W FormManager: Network not available. Please check & try again.
09-13 11:58:21.538  6918  7329 V FormManager: Network unavailable.
,09-13 11:58:21.541  6918  7329 V FormManager: Network unavailable.
09-13 11:58:21.545  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:21.555  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 11:58:21.558  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 11:58:21.561  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:21.561  6918  7331 W FormManager: Network not available. Please check & try again.
09-13 11:58:21.565  6918  7332 V FormManager: Network unavailable.
09-13 11:58:21.567  6918  7332 V FormManager: Network unavailable.
,09-13 11:58:21.574  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-13 11:58:21.574  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 11:58:21.575  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:21.577  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:21.580  4287  7333 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 11:58:21.582  4287  7334 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 11:58:21.582  4287  7334 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 11:58:21.586  7213  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 11:58:21.586  7213  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 11:58:21.586  7213  7235 I Adreno-EGL: Build Date: 12/12/14 금
09-13 11:58:21.586  7213  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 11:58:21.586  7213  7235 I Adreno-EGL: Remote Branch: 
09-13 11:58:21.586  7213  7235 I Adreno-EGL: Local Patches: 
09-13 11:58:21.586  7213  7235 I Adreno-EGL: Reconstruct Branch: 
09-13 11:58:21.619  7067  7067 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 11:58:21.619  1035  7097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 11:58:21.619  1035  7097 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 11:58:21.619  1035  7097 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 11:58:21.620  1035  1391 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,09-13 11:58:21.636  1035  1958 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7335 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-13 11:58:21.675   312  7353 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 11:58:21.676  1035  1109 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 11:58:21.677  1816  7189 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-13 11:58:21.685  1816  7189 I CheckinService: active receiver: disabled
,09-13 11:58:21.721  1035  1391 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 11:58:21.721  1035  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 11:58:21.721  1035  1391 E WifiStateMachine: useWiFiOffloading() : false
09-13 11:58:21.721  1035  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 11:58:21.722  1940  1940 D WfdsService: Supplicant Connection state is changed : false
09-13 11:58:21.722  1940  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 11:58:21.722  1940  2296 D WfdsService: Set the WFDS Monitor: false
,09-13 11:58:21.722  1940  2296 D WfdsMonitor: WFDS Monitor is stopped
,09-13 11:58:21.723  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:21.724  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 11:58:21.724  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:21.724  1035  1403 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 11:58:21.724  1035  1403 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 11:58:21.725  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 11:58:21.725  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:21.725  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:21.725  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:21.725  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:21.725  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:21.725  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:21.725  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:21.725  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:21.725  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:21.726  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:21.745  7335  7335 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 11:58:21.745  7335  7335 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-13 11:58:21.752  7335  7335 V [BNRBootReceiver]: Boot Receiver Return
09-13 11:58:21.753  7335  7335 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-13 11:58:21.755  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:21.759  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:21.766  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:21.780  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:21.781  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:21.782  6880  6880 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 11:58:21.785  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 11:58:21.788  6827  6827 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 11:58:21.795  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 11:58:21.802  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:21.810  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:21.822  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:21.823  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:21.826  6880  6880 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 11:58:21.832  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:21.842  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:21.855  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:21.866  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:21.867  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:21.868  6880  6880 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:21.878  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:21.894  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:21.915  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:21.935  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:21.936  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:21.937  6880  6880 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:21.948  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:21.966  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:21.976  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:21.986  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:21.987  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:21.988  6880  6880 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:21.996  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:22.010  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:22.024  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:22.041  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:22.042  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:22.043  6880  6880 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 11:58:22.051  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 11:58:22.069  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:22.082  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:22.096  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:22.096  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:22.097  6880  6880 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:22.113  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 11:58:22.139  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:22.152  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:22.166  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:22.167  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:22.176  6880  6880 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 11:58:22.184  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:22.199  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:22.213  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:22.227  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:22.229  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:22.231  6880  6880 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:22.244  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 11:58:22.253  6849  6849 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 11:58:22.264  1035  1441 D WifiService: New client listening to asynchronous messages
09-13 11:58:22.264  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 11:58:22.271  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:22.278  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:22.290  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:22.291  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:22.293  6880  6880 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 11:58:22.295  6880  6880 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 11:58:22.296  6880  6880 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 11:58:22.302  6591  6993 D UEI.SmartControl: Internal timer expired: 4
09-13 11:58:22.302  6591  6993 D UEI.SmartControl: unbind internal service
,09-13 11:58:22.306  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:22.315  6849  6849 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 11:58:22.318  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 11:58:22.328  6591  6987 D serial_port: close(fd = 24)
09-13 11:58:22.330  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:22.334  6591  6987 I UEI.SmartControl: Serial port is closed.
,09-13 11:58:22.347  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:22.363  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:22.364  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:22.365  6880  6880 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 11:58:22.367  6880  6880 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-13 11:58:22.368  6880  6880 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-13 11:58:22.376  1035  1895 I ActivityManager: Killing 6801:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-13 11:58:22.437  1035  1958 W libprocessgroup: failed to open /acct/uid_10037/pid_6801/cgroup.procs: No such file or directory
,09-13 11:58:22.448  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-13 11:58:22.463  2175  2175 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-13 11:58:22.464  2175  2175 D c       : Getting all permits...
,09-13 11:58:22.464  2175  2175 D a       : Opening database...
09-13 11:58:22.470  2175  2175 D a       : Opening database auth.proximity.permit_store...
09-13 11:58:22.472  2175  2175 D a       : Closing database...
09-13 11:58:22.498  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 11:58:22.504  6849  6849 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 11:58:22.504  6849  6849 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 11:58:22.504  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:22.509  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:22.521  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:22.533  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:22.533  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:22.537  6880  6880 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 11:58:22.541  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:22.548  6849  6849 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 11:58:22.549  6849  6849 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 11:58:22.549  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:22.558  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:22.571  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:22.582  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:22.582  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:22.587  6880  6880 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 11:58:22.600  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 11:58:22.610  6849  6849 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 11:58:22.610  6849  6849 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 11:58:22.610  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:22.616  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:22.627  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:22.639  6880  6880 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:22.639  6880  6880 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:22.643  6880  6880 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 11:58:22.653  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 11:58:22.657  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 11:58:22.661  6918  7362 W FormManager: Network not available. Please check & try again.
09-13 11:58:22.665  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:22.669  6918  7363 V FormManager: Network unavailable.
,09-13 11:58:22.675  6918  7363 V FormManager: Network unavailable.
09-13 11:58:22.685  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-13 11:58:22.703  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 11:58:22.703  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 11:58:22.705  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 11:58:22.710  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:22.716  4287  7364 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 11:58:22.719  4287  7365 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 11:58:22.720  4287  7365 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 11:58:22.723  6849  6849 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 11:58:22.724  6849  6849 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 11:58:22.724  6849  6849 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:22.727  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 11:58:22.737  6918  7367 W FormManager: Network not available. Please check & try again.
09-13 11:58:22.739  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:22.739  6918  7368 V FormManager: Network unavailable.
09-13 11:58:22.746  6918  7368 V FormManager: Network unavailable.
,09-13 11:58:23.396  1035  1391 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:586920868] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 11:58:23.405  1035  1391 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:586920876] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 11:58:23.464  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:23.481  1035  1111 D Tethering: MasterInitialState.processMessage what=3
09-13 11:58:23.488  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:58:23.491  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:23.500  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 11:58:23.504  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:23.506  6396  6848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 11:58:23.522  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 11:58:23.539  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:23.574  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 11:58:23.583  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 11:58:23.583  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:23.583  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 11:58:23.583  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 11:58:23.586  7012  7012 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 11:58:23.592  7012  7012 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@218cf877
09-13 11:58:23.592  7012  7012 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 11:58:23.592  7012  7012 D AppUp4:CustFacade: isPhone : true
09-13 11:58:23.594  7012  7012 D AppUp4:CustModeStarterReceiver: begin check event
09-13 11:58:23.594  7012  7012 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 11:58:23.599  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:23.599  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 11:58:23.600  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 11:58:23.606  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:23.613  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 11:58:23.639  4287  7387 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 11:58:23.649  7040  7388 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:23.652  4287  7390 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:23.652  4287  7390 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 11:58:23.653  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 11:58:23.653  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:23.654  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 11:58:23.654  3453  3453 D PhoneState: setPdpRejectCasuse : false
09-13 11:58:23.659  7080  7080 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 11:58:23.660  7080  7080 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 11:58:23.660  6918  7395 W FormManager: Network not available. Please check & try again.
09-13 11:58:23.671  7140  7140 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:23
,09-13 11:58:23.673  7140  7140 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 11:58:23.673  7140  7140 D Weather.Utils: 2 : All the weather widget is gone.
09-13 11:58:23.674  7140  7140 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 11:58:23.674  7140  7140 D WeatherAncestor: connectivity changed - connection : true
09-13 11:58:23.675  7140  7140 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d73954d
09-13 11:58:23.676  7140  7140 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 11:58:23.676  7140  7140 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 11:58:23.676  7140  7140 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 11:58:23.676  7140  7140 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 11:58:23.676  7140  7140 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:23
09-13 11:58:23.685  6918  7396 V FormManager: Network unavailable.
,09-13 11:58:23.692  6918  7396 V FormManager: Network unavailable.
09-13 11:58:24.275  1035  1895 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:24.276  1035  1895 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-13 11:58:24.312  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 11:58:24.313  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 11:58:24.313  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 11:58:24.314  1035  1111 D BluetoothManagerService: Message: 1
09-13 11:58:24.314  1035  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-13 11:58:24.341  1035  1111 D BluetoothManagerService: Message: 20
09-13 11:58:24.341  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ab016a0:true
,09-13 11:58:24.345  6947  6947 D BluetoothAdapterState: make
09-13 11:58:24.351  6947  6947 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-13 11:58:24.351  6947  6947 I bluedroid-qcom: init
09-13 11:58:24.352  6947  7407 I BluetoothAdapterState: Entering OffState
09-13 11:58:24.353  6947  6947 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 11:58:24.353  6947  6947 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 11:58:24.353  6947  6947 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 11:58:24.353  6947  6947 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 11:58:24.353  6947  6947 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-13 11:58:24.356  6947  6947 I bluedroid-qcom: get_profile_interface socket
09-13 11:58:24.357  6947  6947 I bluedroid-qcom: get_profile_interface map_client
,09-13 11:58:24.360  6947  7411 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-13 11:58:24.356  7410  7410 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:24.366  6947  7411 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 11:58:24.356  7410  7410 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:24.375  7410  7410 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-13 11:58:24.375  7410  7410 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-13 11:58:24.375  7410  7410 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-13 11:58:24.381  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-13 11:58:24.381  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 11:58:24.381  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 11:58:24.383  1035  1111 D BluetoothManagerService: Message: 40
09-13 11:58:24.383  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-13 11:58:24.384  6947  6964 I bluedroid-qcom: config_hci_snoop_log
09-13 11:58:24.385  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-13 11:58:24.385  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-13 11:58:24.386  7410  7410 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-13 11:58:24.392  6947  7407 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-13 11:58:24.394  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.398  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.403  7410  7410 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-13 11:58:24.403  7410  7410 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-13 11:58:24.410  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:58:24.418  1035  1111 D Tethering: MasterInitialState.processMessage what=3
09-13 11:58:24.418  1035  1111 D Tethering: MasterInitialState.processMessage what=3
09-13 11:58:24.419  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:24.419  6947  7411 D BluetoothAdapterProperties: Name is: G3
09-13 11:58:24.419  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.423  6947  7407 D BluetoothAdapterProperties: Setting state to 11
09-13 11:58:24.423  6947  7407 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-13 11:58:24.427  1035  1111 D BluetoothManagerService: Message: 60
09-13 11:58:24.427  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 11:58:24.427  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 11:58:24.431  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 11:58:24.435  6396  6848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 11:58:24.443  6947  7407 I LGBluetoothServiceJni: classInitNative: succeeds
09-13 11:58:24.450  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:58:24.453  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:24.461  6947  7407 D BluetoothBondStateMachine: make
09-13 11:58:24.463  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 11:58:24.463  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 11:58:24.466  6947  7407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.466  6947  7407 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-13 11:58:24.466  6947  7407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.466  6947  7407 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 11:58:24.467  6947  7407 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 11:58:24.467  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:24.469  6827  6827 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 11:58:24.469  6947  7422 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 11:58:24.472  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:24.474  6947  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-13 11:58:24.476  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 11:58:24.486  6947  6947 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 11:58:24.487  6947  6947 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:24.487  6947  6947 V BluetoothPbapReceiver: ***********state = 11
09-13 11:58:24.490  6947  7407 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 11:58:24.493  6947  6947 D HeadsetService: Received start request. Starting profile...
09-13 11:58:24.493  6947  6947 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 11:58:24.493  6947  6947 D LGBluetoothHfpAdapter: Version 1.6
09-13 11:58:24.497  6947  6947 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 11:58:24.498  6947  6947 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 11:58:24.499  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 11:58:24.500  6947  6947 D HeadsetStateMachine: make
09-13 11:58:24.504  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 11:58:24.509  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.542  6947  6947 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:24.542  6947  6947 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:24.562  1035  1880 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7431 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 11:58:24.565  6947  6947 D HeadsetStateMachine: max_hf_connections = 1
09-13 11:58:24.565  6947  6947 I bluedroid-qcom: get_profile_interface handsfree
09-13 11:58:24.568  6947  6947 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-13 11:58:24.569   317  2174 V AudioPolicyService: registerClient() client 0xb04105a0, uid 1002
09-13 11:58:24.569  6947  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-13 11:58:24.569   317   317 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-13 11:58:24.569   317   317 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 11:58:24.569   317   317 V AudioPolicyManagerEx: getOutput() returns output 2
,09-13 11:58:24.570  6947  6947 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 11:58:24.571   317  1398 V AudioFlinger: registerClient() client 0xb102fc10, pid 6947
09-13 11:58:24.571   317  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:24.571   317  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 11:58:24.571  6947  6947 V ToneGenerator: Create Track: 0xb4928a80
09-13 11:58:24.572   317  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:24.572   317  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 11:58:24.572  1035  1575 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:24.572  1035  1575 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 11:58:24.572  1035  1575 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:24.572  1035  1575 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 11:58:24.572  1602  3307 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:24.572  1602  3307 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 11:58:24.572  1602  3307 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:24.572  1602  3307 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 11:58:24.572  1851  2441 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:24.572  1851  2441 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 11:58:24.572  1851  2441 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:24.572  1851  2441 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 11:58:24.573  6947  6964 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:24.573  6947  6964 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-13 11:58:24.573  6947  6964 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:24.573  6947  6964 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-13 11:58:24.573  3453  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:24.573  3453  3468 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 11:58:24.573  6947  6947 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-13 11:58:24.573  6947  6947 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-13 11:58:24.573  3453  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:24.573  3453  3468 V AudioSystem: ioConfigChanged() opening already existing output! 2
,09-13 11:58:24.573  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:24.573   317  2172 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
,09-13 11:58:24.573  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:24.573   317  2172 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-13 11:58:24.573   317  2172 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 11:58:24.573   317  2172 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 11:58:24.574   317  2174 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 11:58:24.574   317   317 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
,09-13 11:58:24.574   317   317 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-13 11:58:24.574   317   317 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 11:58:24.574   317   317 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 11:58:24.575  6947  6947 V AudioSystem: getLatency() output 2, latency 50
09-13 11:58:24.575  6947  6947 V AudioSystem: getFrameCount() output 2, frameCount 960
09-13 11:58:24.575  6947  6947 V AudioTrack: createTrack_l() output 2 afLatency 50
,09-13 11:58:24.575   317  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 11:58:24.575   317  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 11:58:24.575   317  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 11:58:24.575   317  1397 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 11:58:24.575   317  1397 V AudioFlinger: createTrack() lSessionId: 20
09-13 11:58:24.578  6947  6947 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-13 11:58:24.579   317  1397 V AudioFlinger: acquiring 20 from 6947, for 6947
,09-13 11:58:24.579   317  1397 V AudioFlinger:  added new entry for 20
09-13 11:58:24.579  6947  6947 V ToneGenerator: ToneGenerator INIT OK, time: 197461
09-13 11:58:24.579  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.580  6947  7425 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 11:58:24.581  6947  7425 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,09-13 11:58:24.581  6947  7425 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 11:58:24.581  6947  7425 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 11:58:24.582   317  1398 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6947
09-13 11:58:24.583  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.583  6947  6947 D HeadsetStateMachine: Proxy object connected
,09-13 11:58:24.585  6947  6947 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 11:58:24.585  6947  6947 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 11:58:24.587  6947  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-13 11:58:24.587   317  1398 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 11:58:24.587   317  1398 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 11:58:24.587   317  1398 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 11:58:24.587   317  1398 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 11:58:24.587   317  1398 V voice   : voice_set_parameters: exit with code(0)
09-13 11:58:24.587   317  1398 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 11:58:24.589   317  1398 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 11:58:24.589  6947  6947 D A2dpService: Received start request. Starting profile...
09-13 11:58:24.589   317  1398 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 11:58:24.589   317  1398 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 11:58:24.590   317  1398 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 11:58:24.590   317  1398 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 11:58:24.590  6947  6947 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 11:58:24.591  6947  7425 V ToneGenerator: ToneGenerator destructor
09-13 11:58:24.591  6947  7425 V ToneGenerator: stopTone
09-13 11:58:24.591  6947  7425 V ToneGenerator: Delete Track: 0xb4928a80
09-13 11:58:24.592  6947  6947 V Avrcp   : make
09-13 11:58:24.592  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.593  6947  6947 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 11:58:24.593  6947  6947 I bluedroid-qcom: get_profile_interface avrcp
09-13 11:58:24.593  6947  7425 V AudioTrack: ~AudioTrack, releasing session id from 6947 on behalf of 6947
09-13 11:58:24.594   317   317 V AudioFlinger: releasing 20 from 6947 for 6947
09-13 11:58:24.594   317   317 V AudioFlinger:  decremented refcount to 0
09-13 11:58:24.594   317   317 V AudioFlinger: purging stale effects
09-13 11:58:24.594   317   317 V AudioPolicyService: AudioCommandThread() adding release output 2
09-13 11:58:24.594   317   317 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-13 11:58:24.594   317   317 V AudioFlinger: PlaybackThread::Track destructor
09-13 11:58:24.594   317  1268 V AudioPolicyService: AudioCommandThread() waking up
09-13 11:58:24.594   317   317 V AudioFlinger: removeClient_l() pid 6947, calling pid 317
09-13 11:58:24.594   317  1268 V AudioPolicyService: AudioCommandThread() processing release output 2
09-13 11:58:24.594   317  1268 V AudioPolicyManager: releaseOutput() 2
09-13 11:58:24.594   317  1268 V AudioPolicyService: AudioCommandThread() going to sleep
,09-13 11:58:24.603  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 11:58:24.603  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.603  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 11:58:24.604  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 11:58:24.605  7012  7012 I AppUp4:CustModeStarterReceiver: onReceive
09-13 11:58:24.606  6947  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-13 11:58:24.607  6947  6947 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 11:58:24.609  6947  6947 E AudioManager: No RCC entry present to update
09-13 11:58:24.609  6947  6947 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 11:58:24.612  6947  7407 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 11:58:24.613  6947  6947 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-13 11:58:24.614  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 11:58:24.614  6947  6947 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 11:58:24.619  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 11:58:24.620  7012  7012 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@218cf877
09-13 11:58:24.620  7012  7012 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 11:58:24.620  7012  7012 D AppUp4:CustFacade: isPhone : true
09-13 11:58:24.620  7012  7012 D AppUp4:CustModeStarterReceiver: begin check event
09-13 11:58:24.621  7012  7012 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 11:58:24.622  6947  7407 E BluetoothAdapterService: File transfer profiles supported!!
09-13 11:58:24.671  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.671  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 11:58:24.672  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 11:58:24.698  6947  7407 V LGMDMManager: Create singleton instance
,09-13 11:58:24.700  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:24.703  6947  7407 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 11:58:24.714  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 11:58:24.719  4287  7453 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.719  4287  7453 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 11:58:24.720  4287  7452 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 11:58:24.737  7040  7454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 11:58:24.739  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 11:58:24.739  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.739  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 11:58:24.741  1035  1895 V SIM_STK : Menu title from STK is T-Mobile
09-13 11:58:24.741  1035  1895 V SIM_STK : Menu title from STK is T-Mobile
09-13 11:58:24.744  7080  7080 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 11:58:24.745  7080  7080 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 11:58:24.756  7140  7140 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:24
,09-13 11:58:24.757  7431  7431 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 11:58:24.757  7431  7431 W LG Account v2.2: No ProfileInfo entries
09-13 11:58:24.758  7431  7431 I LG Account v2.2: isEnabled: false
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]Country: EU
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]Operator: OPEN
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]Ranking support: false
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]Comfort support: false
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]Accessory: true
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]Health device: true
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]Extra Pedometer: false
09-13 11:58:24.758  6918  7457 W FormManager: Network not available. Please check & try again.
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]Blood glucose device: false
09-13 11:58:24.758  7431  7431 I Feature : [Lifetracker]Device Number: 3
09-13 11:58:24.761  7140  7140 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 11:58:24.761  7140  7140 D Weather.Utils: 2 : All the weather widget is gone.
09-13 11:58:24.763  7140  7140 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 11:58:24.763  7140  7140 D WeatherAncestor: connectivity changed - connection : true
09-13 11:58:24.763  7140  7140 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d73954d
09-13 11:58:24.763  7140  7140 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 11:58:24.763  7140  7140 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 11:58:24.763  7140  7140 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 11:58:24.763  7140  7140 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 11:58:24.763  7140  7140 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:24
09-13 11:58:24.765  6827  6827 D BluetoothPermissionRequest: onReceive
09-13 11:58:24.766  6918  7460 V FormManager: Network unavailable.
09-13 11:58:24.768  6827  6827 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 11:58:24.769  6918  7460 V FormManager: Network unavailable.
,09-13 11:58:24.787  6396  6396 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 11:58:24.791  6396  6848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 11:58:24.802  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:58:24.809  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 11:58:24.809  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.809  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 11:58:24.809  7012  7012 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 11:58:24.812  1035  1985 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 11:58:24.812  7012  7012 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 11:58:24.815  7012  7012 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@218cf877
,09-13 11:58:24.815  7012  7012 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 11:58:24.815  7012  7012 D AppUp4:CustFacade: isPhone : true
09-13 11:58:24.815  7012  7012 D AppUp4:CustModeStarterReceiver: begin check event
09-13 11:58:24.816  7012  7012 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 11:58:24.817  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 11:58:24.819  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.819  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 11:58:24.820  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 11:58:24.820  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 11:58:24.821  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 11:58:24.821  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 11:58:24.821  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:24.821  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 11:58:24.821  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 11:58:24.821  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 11:58:24.821  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 11:58:24.821  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 11:58:24.821  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 11:58:24.821  6947  6947 I BluetoothA2dpServiceJni: classInitNative
09-13 11:58:24.821  6947  6947 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 11:58:24.821  6947  6947 D A2dpStateMachine: make
09-13 11:58:24.823  6947  6947 I bluedroid-qcom: get_profile_interface a2dp
09-13 11:58:24.823  6947  7462 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 11:58:24.823  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:24.825  6947  6947 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-13 11:58:24.826  6947  6947 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 11:58:24.826  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.827  6947  6947 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 11:58:24.827  4287  7464 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 11:58:24.829  6947  7461 D A2dpStateMachine: Enter Disconnected: -2
09-13 11:58:24.830  6947  6947 D HidService: Received start request. Starting profile...
09-13 11:58:24.830  6947  6947 I bluedroid-qcom: get_profile_interface hidhost
09-13 11:58:24.831  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.831  7040  7040 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 11:58:24.835  4287  7465 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.835  4287  7465 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 11:58:24.836  6947  6947 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 11:58:24.837  6947  6947 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 11:58:24.838  6947  7425 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 11:58:24.838  6947  7425 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 11:58:24.839  6947  7425 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-13 11:58:24.840  6947  6947 D HealthService: Received start request. Starting profile...
09-13 11:58:24.841  6947  6947 I bluedroid-qcom: get_profile_interface health
09-13 11:58:24.841  6947  6947 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-13 11:58:24.841  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.842  6947  6947 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 11:58:24.843  6947  6947 D PanService: Received start request. Starting profile...
09-13 11:58:24.843  6947  6947 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 11:58:24.843  6947  6947 I bluedroid-qcom: get_profile_interface pan
09-13 11:58:24.847  3453  3453 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 11:58:24.847  3453  3453 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:24.847  3453  3453 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 11:58:24.848  6947  6947 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-13 11:58:24.848  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.849  6947  6947 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-13 11:58:24.850  7080  7080 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 11:58:24.851  7080  7080 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 11:58:24.852  6947  6947 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 11:58:24.852  6947  6947 D BtGatt.GattService: Received start request. Starting profile...
09-13 11:58:24.852  6947  6947 D BtGatt.GattService: start()
09-13 11:58:24.852  6947  6947 I bluedroid-qcom: get_profile_interface gatt
09-13 11:58:24.853  6947  6947 D BtGatt.AdvertiseManager: advertise manager created
09-13 11:58:24.859  7040  7469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:24.859  6918  7472 V FormManager: Network unavailable.
09-13 11:58:24.860  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.861  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.861  6947  6947 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 11:58:24.862  6947  6947 V BluetoothMapService: BluetoothMapBinder()
,09-13 11:58:24.863  6947  6947 D BluetoothMapService: Received start request. Starting profile...
09-13 11:58:24.863  6947  6947 D BluetoothMapService: start()
09-13 11:58:24.868  6918  7471 W FormManager: Network not available. Please check & try again.
09-13 11:58:24.870  6947  6947 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 11:58:24.870  6947  6947 D BluetoothMapEmailAppObserver: createReceiver()
09-13 11:58:24.871  7140  7140 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:24
09-13 11:58:24.872  6947  6947 D BluetoothMapEmailAppObserver: initObservers()
09-13 11:58:24.872  6947  6947 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 11:58:24.873  7140  7140 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-13 11:58:24.873  7140  7140 D Weather.Utils: 2 : All the weather widget is gone.
09-13 11:58:24.874  7140  7140 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 11:58:24.874  7140  7140 D WeatherAncestor: connectivity changed - connection : true
09-13 11:58:24.874  7140  7140 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d73954d
09-13 11:58:24.875  7140  7140 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 11:58:24.875  7140  7140 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 11:58:24.875  7140  7140 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 11:58:24.875  7140  7140 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 11:58:24.875  7140  7140 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:24
09-13 11:58:24.875  6918  7472 V FormManager: Network unavailable.
09-13 11:58:24.879  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:24.883  6947  6947 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 11:58:24.886  6947  6947 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 11:58:24.889  6947  6947 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 11:58:24.893  6947  6947 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 11:58:24.893  6947  6947 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 11:58:24.896  6947  6947 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 11:58:24.896  6947  6947 V BluetoothMapService: Handler(): got msg=1
09-13 11:58:24.897  6947  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 11:58:24.897  6947  7407 I bluedroid-qcom: enable
09-13 11:58:24.897  6947  7407 I bt_hci_bdroid: init
09-13 11:58:24.899  6947  7476 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 11:58:24.900  6947  7407 I bt_vendor: bt-vendor : init
09-13 11:58:24.900  6947  7407 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 11:58:24.900  6947  7407 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 11:58:24.900  6947  7407 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 11:58:24.900  6947  7407 D bt_userial_mct: userial_init
09-13 11:58:24.900  6947  7476 I bt-btu  : btu_task pending for preload complete event
09-13 11:58:24.901  6947  7407 D bt_hci_bdroid: set_power 1
09-13 11:58:24.901  6947  7407 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 11:58:24.901  6947  7407 I bt_vendor: Starting hciattach daemon
09-13 11:58:24.901  6947  7407 I bt_vendor: try to set true
09-13 11:58:24.901  6947  6947 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 11:58:24.896  7479  7479 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:24.896  7479  7479 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:24.904  6947  6947 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 11:58:24.904  6947  6947 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 11:58:24.904  6947  6947 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 11:58:24.905  6947  6947 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:24.905  6947  6947 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 11:58:24.927  7480  7480 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 11:58:25.031  7486  7486 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 11:58:25.045  7487  7487 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 11:58:25.072  7489  7489 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 11:58:25.088  7490  7490 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-13 11:58:25.113  7491  7491 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 11:58:25.128  7492  7492 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-13 11:58:25.155  7494  7494 I libmdmdetect: ESOC framework not supported
,09-13 11:58:25.156  7494  7494 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 11:58:25.165  7494  7494 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 11:58:25.165  7494  7494 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 11:58:25.165  7494  7494 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,09-13 11:58:25.165  7494  7494 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 11:58:25.165  7494  7494 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 11:58:25.165  7494  7494 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 11:58:25.165  7494  7494 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 11:58:25.208  7494  7496 E QC-QMI  : qmi_client [7494] 14: failed to locate client data
09-13 11:58:25.211   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 11:58:25.211   481   481 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-13 11:58:25.259  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 11:58:25.272  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 11:58:25.309  6947  7407 I bt_vendor: bluetooth satus is on
,09-13 11:58:25.309  6947  7407 D bt_hci_bdroid: preload
09-13 11:58:25.309  6947  7478 D bt_userial_mct: userial_open(port:0)
09-13 11:58:25.309  6947  7478 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-13 11:58:25.314  6947  7478 I bt_vendor: Done intiailizing UART
09-13 11:58:25.317  6947  7478 I bt_vendor: Done intiailizing UART
09-13 11:58:25.317  6947  7478 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-13 11:58:25.317  6947  7478 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 11:58:25.318  6947  7506 D bt_userial_mct: Entering userial_read_thread()
09-13 11:58:25.318  6947  7476 I bt-btu  : btu_task received preload complete event
09-13 11:58:25.318  6947  7476 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 11:58:25.319  6947  7476 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 11:58:25.326  6947  7476 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-13 11:58:25.332  6947  7476 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_A2D
,09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_GAP
,09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_PAN,
09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_SMP,
09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-13 11:58:25.333  6947  7476 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 11:58:25.396  6947  7476 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-13 11:58:25.396  6947  7476 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01bd061 
,09-13 11:58:25.396  6947  7476 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01bd061 
,09-13 11:58:25.439  6947  7411 E bt-btif : Calling BTA_HhEnable
09-13 11:58:25.439  6947  7411 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 11:58:25.440  6947  7411 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-13 11:58:25.443  6947  7476 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 11:58:25.443  6947  7476 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 11:58:25.443  6947  7476 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 11:58:25.443  6947  7476 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 11:58:25.443  6947  7476 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 11:58:25.444  6947  7411 D BluetoothAdapterProperties: Name is: G3
09-13 11:58:25.445  6947  7411 D BluetoothAdapterProperties: Scan Mode:20
09-13 11:58:25.446  6947  7411 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 11:58:25.446  6947  7411 D bt_hci_bdroid: postload
09-13 11:58:25.446  6947  7478 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 11:58:25.447  6947  7478 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 11:58:25.448  6947  7478 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 11:58:25.448  6947  7478 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 11:58:25.448  6947  7476 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 11:58:25.448  6947  7411 D bte_conf: Device ID record 1 : primary
09-13 11:58:25.449  6947  7478 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 11:58:25.449  6947  7411 D bte_conf:   vendorId            = 00c4
09-13 11:58:25.449  6947  7411 D bte_conf:   vendorIdSource      = 0001
09-13 11:58:25.449  6947  7411 D bte_conf:   product             = 13a1
09-13 11:58:25.449  6947  7411 D bte_conf:   version             = 1000
09-13 11:58:25.449  6947  7411 D bte_conf:   clientExecutableURL = 
09-13 11:58:25.449  6947  7411 D bte_conf:   serviceDescription  = 
09-13 11:58:25.449  6947  7411 D bte_conf:   documentationURL    = 
09-13 11:58:25.449  6947  7411 D bte_conf: bte_load_did_conf no section named DID2.
09-13 11:58:25.450  6947  7506 E bt_mct  : hci lib postload completed
09-13 11:58:25.453  6947  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 11:58:25.453  6947  7407 D BluetoothAdapterProperties: ScanMode =  20
09-13 11:58:25.453  6947  7407 D BluetoothAdapterProperties: State =  11
09-13 11:58:25.454  6947  7407 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 11:58:25.454  6947  7407 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 11:58:25.454  6947  7407 D BluetoothAdapterProperties: Setting state to 12
09-13 11:58:25.454  6947  7407 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 11:58:25.462  1035  1111 D BluetoothManagerService: Message: 60
09-13 11:58:25.462  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 11:58:25.462  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-13 11:58:25.462  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:58:25.456  7511  7511 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:25.465  6947  7407 I BluetoothAdapterState: Entering On State
09-13 11:58:25.456  7511  7511 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:25.469  6947  7476 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:25.469  6947  7476 W bt-smp  : Plain text(LSB ~ MSB) = e4 6d 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:25.469  6947  7476 W bt-smp  : Encrypted text(LSB ~ MSB) = 5e 22 73 03 9c 56 53 11 9a cd 70 60 0e bb 4c c6 
,09-13 11:58:25.473  6947  7476 W bt-btm  : Stopping oneshot timer
09-13 11:58:25.473  6947  7411 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 11:58:25.474  6947  7411 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 11:58:25.487  6947  7407 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 11:58:25.487  6947  7407 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 11:58:25.487  6947  7407 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-13 11:58:25.492  6947  7407 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 11:58:25.499  1035  1035 D BluetoothHeadset: Proxy object connected
09-13 11:58:25.503  1851  4398 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 11:58:25.514  6947  7476 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:25.514  6947  7476 W bt-smp  : Plain text(LSB ~ MSB) = 5c 61 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:25.514  6947  7476 W bt-smp  : Encrypted text(LSB ~ MSB) = 65 cd 96 4e ff ce 87 9e eb ac c3 d4 78 d4 9a 54 
09-13 11:58:25.515  6947  7476 W bt-btm  : Stopping oneshot timer
09-13 11:58:25.516  6947  7407 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-13 11:58:25.528  6947  7411 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 11:58:25.529  6947  7411 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-13 11:58:25.531  1851  1851 D BluetoothHeadset: Proxy object connected
09-13 11:58:25.536  6947  7476 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:25.536  6947  7476 W bt-smp  : Plain text(LSB ~ MSB) = 6f b1 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:25.536  6947  7476 W bt-smp  : Encrypted text(LSB ~ MSB) = 65 cb 75 1e d1 ce 83 4a 97 8e 1a e7 b1 d5 86 ef 
09-13 11:58:25.536  6947  7476 W bt-btm  : Stopping oneshot timer
09-13 11:58:25.576  7516  7516 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-13 11:58:25.591  6947  7476 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:25.591  6947  7476 W bt-smp  : Plain text(LSB ~ MSB) = 7a 09 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:25.591  6947  7476 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 91 fc b9 2b 3b a9 03 78 bb 47 fc 1e 13 2a 4f 
09-13 11:58:25.591  6947  7476 W bt-btm  : Stopping oneshot timer
09-13 11:58:25.595  6827  6844 D BluetoothPan: onBluetoothStateChange on: true
09-13 11:58:25.595  6827  6844 D BluetoothPan: onBluetoothStateChange call bindService
,09-13 11:58:25.609  1851  2441 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 11:58:25.612  1851  1851 D BluetoothHeadset: Proxy object connected
09-13 11:58:25.612  6827  6844 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 11:58:25.613  6947  7476 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:25.613  6947  7476 W bt-smp  : Plain text(LSB ~ MSB) = 96 53 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:25.613  6947  7476 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 7a 04 54 89 4d f4 73 24 c2 3c 88 d4 e4 88 9a 
09-13 11:58:25.613  6947  7476 W bt-btm  : Stopping oneshot timer
09-13 11:58:25.614  6827  6827 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 11:58:25.614  6827  6827 D PanProfile: Bluetooth service connected
09-13 11:58:25.615  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 11:58:25.616  1851  2718 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:58:25.618  1035  1035 D BluetoothA2dp: Proxy object connected
09-13 11:58:25.622  1851  1851 D BluetoothHeadset: Proxy object connected
09-13 11:58:25.622  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7413
09-13 11:58:25.623  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7414
09-13 11:58:25.623  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7420
09-13 11:58:25.623  6827  6843 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 11:58:25.624  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7423
09-13 11:58:25.625  1035  1092 W ProcessCpuTracker: Skipping unknown process pid 7507
09-13 11:58:25.626  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 11:58:25.626  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,09-13 11:58:25.631  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:25.631  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:25.631  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:25.631  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:25.631  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:25.631  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:25.631  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:25.631  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:25.634  6827  6844 D BluetoothMap: onBluetoothStateChange: up=true
09-13 11:58:25.638  1035  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,09-13 11:58:25.638  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 11:58:25.641  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:25.642  1940  2094 D LGBluetoothAPIService: Message: 1
09-13 11:58:25.642  1940  2094 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 11:58:25.642  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:25.644  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 11:58:25.648  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:25.648  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:25.648  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:25.648  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:25.648  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:25.648  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:25.648  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:25.648  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:25.650  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:25.651  6827  6827 D BluetoothInputDevice: Proxy object connected
09-13 11:58:25.651  6827  6827 D HidProfile: Bluetooth service connected
09-13 11:58:25.654  6708  6708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 11:58:25.660  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:58:25.665  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:25.665  1940  2094 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 11:58:25.669  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-13 11:58:25.669  1035  1111 D BluetoothManagerService: Message: 40
09-13 11:58:25.669  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-13 11:58:25.673  6947  6947 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:25.673  6947  6947 D BluetoothMapService: STATE_ON
09-13 11:58:25.673  6827  6827 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-13 11:58:25.674  6947  6947 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 11:58:25.675  6947  6947 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 11:58:25.676  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 11:58:25.676  1940  2094 D LGBluetoothAPIService: Message: 100
09-13 11:58:25.676  1940  2094 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 11:58:25.678  1035  1111 D BluetoothManagerService: Message: 30
09-13 11:58:25.686  6827  6827 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 11:58:25.691  7165  7196 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-13 11:58:25.692  1035  1111 D BluetoothManagerService: Message: 30
09-13 11:58:25.693  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:25.693  6947  6947 V BluetoothPbapService: Pbap Service onCreate
09-13 11:58:25.693  6947  6947 V BluetoothPbapService: Starting PBAP service
09-13 11:58:25.695  6947  6947 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 11:58:25.695  6947  6947 V BluetoothPbapService: Pbap Service onBind
09-13 11:58:25.696  6947  6947 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:25.696  6947  6947 V BluetoothPbapService: state: 12
09-13 11:58:25.696  6947  6947 V BluetoothMapService: Handler(): got msg=1
09-13 11:58:25.697  6947  6947 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 11:58:25.697  6947  6947 V BluetoothPbapService: Handler(): got msg=1
09-13 11:58:25.697  6827  6827 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 11:58:25.698  6947  6947 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 11:58:25.698  6947  7538 D BluetoothMapMasInstance: MAS initSocket()
09-13 11:58:25.699  6947  7538 D BluetoothMapMasInstance:   masId = 00
09-13 11:58:25.699  6947  7538 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 11:58:25.699  6947  7538 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 11:58:25.699  6947  7538 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 11:58:25.699  6827  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 11:58:25.701  6947  7539 V BluetoothPbapService: Pbap Service initSocket
,09-13 11:58:25.702  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 11:58:25.702  1035  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:25.702  6827  6827 D BluetoothMap: Proxy object connected
09-13 11:58:25.702  6827  6827 D MapProfile: Bluetooth service connected
09-13 11:58:25.702  6827  6827 D BluetoothMap: getConnectedDevices()
09-13 11:58:25.704  6947  6947 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 11:58:25.704  6947  6947 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:25.704  6947  6947 V BluetoothPbapReceiver: ***********state = 12
09-13 11:58:25.704  6947  6965 V BluetoothMapService: getConnectedDevices()
09-13 11:58:25.705  6947  7538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:25.706  6827  6827 D BluetoothA2dp: Proxy object connected
09-13 11:58:25.706  6947  7539 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:25.707  6827  6827 D A2dpProfile: Bluetooth service connected
09-13 11:58:25.708  6947  7538 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-13 11:58:25.708  6947  7538 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 11:58:25.708  6947  7538 D BluetoothMapMasInstance: Accepting socket connection...
09-13 11:58:25.709  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 11:58:25.709  2175  2175 D c       : Getting all permits...
09-13 11:58:25.709  2175  2175 D a       : Opening database...
,09-13 11:58:25.710  6947  7411 D BluetoothAdapterProperties: Scan Mode:21
,09-13 11:58:25.710  6947  7411 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 11:58:25.712  6827  6827 D BluetoothHeadset: Proxy object connected
09-13 11:58:25.712  6947  7539 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-13 11:58:25.713  6947  7539 V BluetoothPbapService: Succeed to create listening socket 
09-13 11:58:25.713  6947  7539 V BluetoothPbapService: Accepting socket connection...
09-13 11:58:25.713  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:25.713  2175  2175 D a       : Opening database auth.proximity.permit_store...
09-13 11:58:25.714  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:25.714  2175  2175 D a       : Closing database...
09-13 11:58:25.714  6827  6827 D HeadsetProfile: Bluetooth service connected
09-13 11:58:25.719  6827  6827 D BluetoothPbap: Proxy object connected
09-13 11:58:25.719  6827  6827 D PbapServerProfile: Bluetooth service connected
09-13 11:58:25.726  6827  6827 D DockEventReceiver: finishStartingService: stopping service
09-13 11:58:25.730  6827  6827 D BluetoothPermissionRequest: onReceive
,09-13 11:58:25.732  6827  6827 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 11:58:25.735  6827  6827 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 11:58:25.738  6947  6947 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 11:58:25.740  6947  6947 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 11:58:25.745  6947  6947 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-13 11:58:25.763  6947  6947 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-13 11:58:25.763  6947  6947 V BtOppService: onCreate
09-13 11:58:25.767  6947  6947 V BluetoothOppNotification: send message
09-13 11:58:25.771  6947  6947 V BtOppService: Starting RfcommListener
09-13 11:58:25.779  6947  6947 D BluetoothOppPreference: Dumping Names:  
09-13 11:58:25.779  6947  6947 D BluetoothOppPreference: {}
,09-13 11:58:25.779  6947  6947 D BluetoothOppPreference: Dumping Channels:  
09-13 11:58:25.779  6947  6947 D BluetoothOppPreference: {}
09-13 11:58:25.782  6947  6947 V BtOppService: onStartCommand
09-13 11:58:25.783  6947  7547 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 11:58:25.789  6947  6947 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:25.789  6947  6947 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 11:58:25.792  6947  7547 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-13 11:58:25.795  6947  7544 V BtOppService: Deleted complete outbound shares, number =  0
09-13 11:58:25.795  6947  6947 V BluetoothOppNotification: new notify threadi!
09-13 11:58:25.797  6947  6947 V BluetoothOppNotification: send delay message
09-13 11:58:25.798  6947  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1dac405e on behalf of 
09-13 11:58:25.798  6947  6947 V BtOppService: start RfcommListener
09-13 11:58:25.800  6947  7544 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 11:58:25.803  6947  7544 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 11:58:25.804  6947  6947 V BtOppService: RfcommListener started
,09-13 11:58:25.805  6947  7544 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4a83c3f on behalf of 
,09-13 11:58:25.809  6947  7549 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 11:58:25.811  1035  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:25.812  6947  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 11:58:25.813  6947  7549 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:25.815  6947  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15b7090c on behalf of 
09-13 11:58:25.815  6947  7549 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-13 11:58:25.815  6947  7547 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 11:58:25.816  6947  7547 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 11:58:25.816  6947  7549 V BtOppRfcommListener: Started RFCOMM listener....
09-13 11:58:25.816  6947  7549 I BtOppRfcommListener: Accept thread started.
09-13 11:58:25.816  6947  7549 V BtOppRfcommListener: Accepting connection...
09-13 11:58:25.818  6947  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ef8b255 on behalf of 
,09-13 11:58:25.818  6947  7548 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 11:58:25.820  6947  7547 V BluetoothOppNotification: update too frequent, put in queue
09-13 11:58:25.821  6947  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 11:58:25.821  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:25.822  6947  6947 V BluetoothFtpService: Ftp Service onCreate
09-13 11:58:25.822  6947  6947 I BluetoothFtpService: Ftp Service onCreate
09-13 11:58:25.822  6947  6947 V BluetoothFtpService: Ftp Service onStartCommand
09-13 11:58:25.822  6947  6947 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:25.822  6947  6947 V BluetoothFtpService: Starting Listening on sockets
09-13 11:58:25.823  6947  6947 V BtOppService: ContentObserver received notification
09-13 11:58:25.823  6947  6947 V BtOppService: ContentObserver received notification
09-13 11:58:25.823  6947  6947 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 11:58:25.823  6947  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16ee5d5b on behalf of 
09-13 11:58:25.823  6947  6947 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 11:58:25.823  6947  6947 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 11:58:25.823  6947  6947 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:25.823  6947  7547 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 11:58:25.823  6947  6947 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 11:58:25.823  6947  6947 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-13 11:58:25.824  6947  7547 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 11:58:25.824  6947  7548 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 11:58:25.826  6947  6947 V BluetoothFtpService: Handler(): got msg=1
09-13 11:58:25.826  6947  7548 V BluetoothOppNotification: outbound notification was removed.
09-13 11:58:25.826  6947  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 11:58:25.828  6947  6947 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 11:58:25.828  6947  6947 V BluetoothFtpService: Ftp Service initSocket
09-13 11:58:25.829  6947  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3351a9f8 on behalf of 
09-13 11:58:25.829  6947  7547 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@295f1ed1 on behalf of 
09-13 11:58:25.830  6947  7547 V BluetoothOppNotification: update too frequent, put in queue
09-13 11:58:25.831  6947  7548 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 11:58:25.832  6947  7547 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 11:58:25.832  1035  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 11:58:25.834  6947  6947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:25.834  6947  7548 V BluetoothOppNotification: inbound notification was removed.
09-13 11:58:25.834  6947  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 11:58:25.836  6947  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f89fd36 on behalf of 
09-13 11:58:25.841  6947  6947 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-13 11:58:25.841  6947  6947 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 11:58:25.843  6947  7550 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-13 11:58:25.860  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:25.860  6947  6947 V BluetoothSapService: Sap Service onCreate
,09-13 11:58:25.862  6947  6947 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:25.862  6947  6947 V BluetoothSapService: state: 12
09-13 11:58:25.862  6947  6947 V BluetoothSapService: Starting SAP server process
09-13 11:58:25.865  6947  6947 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 11:58:25.856  7551  7551 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:25.856  7551  7551 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:25.867  6947  7552 V BluetoothSapService: Sap Service initRfcommSocket
09-13 11:58:25.867  1035  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:25.868  6947  7552 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:25.871  6947  7552 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-13 11:58:25.872  6947  7552 V BluetoothSapService: Succeed to create listening socket 
09-13 11:58:25.872  6947  7552 V BluetoothSapService: Accepting socket connection...
09-13 11:58:25.878  7551  7551 V BT_SAP  : Event pipe created
09-13 11:58:25.878  7551  7551 V BT_SAP  : create_server_socket qcom.sap.server
09-13 11:58:25.878  7551  7551 V BT_SAP  : created socket fd 6
,09-13 11:58:26.344  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 11:58:26.344  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 11:58:26.384  1035  1391 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 11:58:26.385  1035  1391 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 11:58:26.411  1035  1051 I ActivityManager: Killing 7335:com.lge.bnr/1000 (adj 15): empty #17
,09-13 11:58:26.442  1035  1696 W libprocessgroup: failed to open /acct/uid_1000/pid_7335/cgroup.procs: No such file or directory
,09-13 11:58:26.668  1035  1895 I ActivityManager: Killing 6591:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-13 11:58:26.692  6880  6880 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-13 11:58:26.692  6880  6880 W System.err: android.os.DeadObjectException
09-13 11:58:26.692  6880  6880 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 11:58:26.692  6880  6880 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 11:58:26.692  6880  6880 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-13 11:58:26.693  6880  6880 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-13 11:58:26.693  6880  6880 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 11:58:26.693  6880  6880 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 11:58:26.693  6880  6880 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 11:58:26.693  6880  6880 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 11:58:26.693  6880  6880 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 11:58:26.693  6880  6880 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 11:58:26.693  6880  6880 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:58:26.693  6880  6880 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 11:58:26.693  6880  6880 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 11:58:26.693  6880  6880 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-13 11:58:26.698  6880  6880 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,09-13 11:58:26.698  6880  6880 W System.err: android.os.DeadObjectException
09-13 11:58:26.698  6880  6880 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 11:58:26.698  6880  6880 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 11:58:26.698  6880  6880 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,09-13 11:58:26.698  6880  6880 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-13 11:58:26.699  6880  6880 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 11:58:26.699  6880  6880 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 11:58:26.699  6880  6880 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 11:58:26.699  6880  6880 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,09-13 11:58:26.699  6880  6880 W System.err: ,	at android.os.Looper.loop(Looper.java:135)
,09-13 11:58:26.699  6880  6880 W System.err: ,	at android.app.ActivityThread.main(ActivityThread.java:5274)
,09-13 11:58:26.699  6880  6880 W System.err: 	,at java.lang.reflect.Method.invoke(Native Method)
,09-13 11:58:26.699  6880  6880 W System.err: ,	at java.lang.reflect.Method.invoke(Method.java:372)
,09-13 11:58:26.699  6880  6880 W System.err: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 11:58:26.699  6880  6880 W System.err: ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 11:58:26.699  6880  6880 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-13 11:58:26.699  6880  6880 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-13 11:58:26.727  1035  1957 W libprocessgroup: failed to open /acct/uid_1000/pid_6591/cgroup.procs: No such file or directory
,09-13 11:58:26.750  1035  1957 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-13 11:58:26.757  6880  6880 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-13 11:58:26.757  6880  6880 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-13 11:58:26.797  6947  6947 V BluetoothOppNotification: new notify threadi!
09-13 11:58:26.797  6947  6947 V BluetoothOppNotification: send delay message
,09-13 11:58:26.817  1035  1051 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7563 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 11:58:26.878  6880  6880 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-13 11:58:26.888  6947  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 11:58:26.917  6947  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2670b6c2 on behalf of 
09-13 11:58:26.917  6947  7562 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-13 11:58:26.920  6947  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 11:58:26.922  6947  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11b91cd3 on behalf of 
09-13 11:58:26.923  6947  7562 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 11:58:26.925  6947  7562 V BluetoothOppNotification: outbound notification was removed.
09-13 11:58:26.925  6947  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 11:58:26.927  6947  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10cbc010 on behalf of 
09-13 11:58:26.928  6947  7562 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-13 11:58:26.933  6947  7562 V BluetoothOppNotification: inbound notification was removed.
09-13 11:58:26.933  6947  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 11:58:26.934  6947  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17a5d709 on behalf of 
09-13 11:58:27.023  1035  2031 I art     : Explicit concurrent mark sweep GC freed 92896(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.378ms total 163.833ms
,09-13 11:58:27.058  7563  7563 D UEI.SmartControl: Quickset Services start...
,09-13 11:58:27.060  7563  7563 I UEI.SmartControl: Manufacture = LGE
09-13 11:58:27.060  7563  7563 D UEI.SmartControl: Id = LGNevo
09-13 11:58:27.062  7563  7563 D UEI.SmartControl: File observer start...
,09-13 11:58:27.063  7563  7563 E UEI.SmartControl: IR Port is disabled: false
09-13 11:58:27.063  7563  7563 D UEI.SmartControl: Starting file observer...
09-13 11:58:27.064  7563  7563 D UEI.SmartControl: Extracting JNI libs...
09-13 11:58:27.064  7563  7563 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-13 11:58:27.139  7563  7563 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-13 11:58:27.139  7563  7563 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-13 11:58:27.139  7563  7563 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-13 11:58:27.165  7563  7563 I UEI.SmartControl: --- Selecting new region: 6
,09-13 11:58:27.167  7563  7563 I UEI.SmartControl: Model = LG-D855
09-13 11:58:27.169  7563  7563 D UEI.SmartControl: QS Service created
09-13 11:58:27.180  7563  7563 I UEI.SmartControl: Service initServices...
09-13 11:58:27.183  7563  7563 D UEI.SmartControl: QS start get config
,09-13 11:58:27.218  7563  7563 D UEI.SmartControl: Loading JNI Libs...
,09-13 11:58:27.331  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:27.331  1035  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1674fbbb mBinding = false
,09-13 11:58:27.356  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 11:58:27.357  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 11:58:27.358  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-13 11:58:27.362  1035  1111 D BluetoothManagerService: Message: 2
09-13 11:58:27.362  1035  1111 D BluetoothManagerService: Sending off request.
09-13 11:58:27.363  6947  6964 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 11:58:27.364  6947  7407 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 11:58:27.365  6947  7407 D BluetoothAdapterProperties: Setting state to 13
09-13 11:58:27.365  6947  7407 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 11:58:27.366  6947  7407 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 11:58:27.366  6947  7407 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 11:58:27.369  6947  7411 D BluetoothAdapterProperties: Scan Mode:20
09-13 11:58:27.371  1035  1111 D BluetoothManagerService: Message: 60
09-13 11:58:27.371  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 11:58:27.371  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 11:58:27.372  6947  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 11:58:27.372  6947  7407 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 11:58:27.373  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 11:58:27.375  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 11:58:27.379  6947  7552 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:27.380  6947  7538 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 11:58:27.380  6947  7538 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:27.380  6947  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 11:58:27.380  6947  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 11:58:27.380  6947  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 11:58:27.380  6947  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 11:58:27.380  6947  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 11:58:27.380  6947  7538 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 11:58:27.380  6947  7550 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:27.381  6947  7549 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:27.381  6947  7539 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:58:27.381  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 11:58:27.382  6947  7476 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 11:58:27.383  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 11:58:27.383  6947  7476 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 11:58:27.385  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:27.385  6947  6947 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:27.385  6947  6947 D BluetoothMapService: STATE_TURNING_OFF
09-13 11:58:27.386  6947  6947 V BluetoothMapService: Handler(): got msg=4
09-13 11:58:27.386  6947  6947 D BluetoothMapService: MAP Service closeService in
09-13 11:58:27.386  6947  6947 D BluetoothMapMasInstance: MAP Service shutdown
09-13 11:58:27.386  6947  6947 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 11:58:27.386  6947  6947 V BluetoothMapService: MAP Service closeService out
09-13 11:58:27.386  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:27.386  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:27.386  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:27.386  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:27.386  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:27.386  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:27.386  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:27.386  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:27.387  6827  6827 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-13 11:58:27.389  6947  6947 V BtOppService: Receiver DISABLED_ACTION 
09-13 11:58:27.389  6947  6947 I BtOppRfcommListener: stopping Accept Thread
09-13 11:58:27.389  6947  6947 V BtOppRfcommListener: close mBtServerSocket
09-13 11:58:27.390  6947  7549 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 11:58:27.390  6947  6947 V BtOppRfcommListener: waiting for thread to terminate
,09-13 11:58:27.390  6947  6947 V BtOppRfcommListener: done waiting for thread to terminate
09-13 11:58:27.393  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:27.393  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:27.398  6947  6947 V BtOppService: onDestroy
09-13 11:58:27.400  6947  6947 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 11:58:27.401  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:27.401  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:27.401  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:27.401  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:27.401  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:27.401  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:58:27.401  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:27.401  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:27.401  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:58:27.405  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:58:27.405  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:27.406  6827  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 11:58:27.408  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:27.409  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:27.415  6947  6947 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 11:58:27.415  6947  6947 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:27.415  6947  6947 V BluetoothPbapReceiver: ***********state = 13
,09-13 11:58:27.417  6947  6947 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 11:58:27.419  6947  6947 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:27.419  6947  6947 V BluetoothPbapService: state: 13
09-13 11:58:27.419  6947  6947 V BluetoothPbapService: Pbap Service closeService in
09-13 11:58:27.421  6947  6947 V BluetoothPbapService: successfully stopped pbap service
09-13 11:58:27.421  6947  6947 V BluetoothPbapService: Pbap Service closeService out
09-13 11:58:27.421  6827  6827 D DockEventReceiver: finishStartingService: stopping service
09-13 11:58:27.421  6947  6947 V BluetoothPbapService: Pbap Service onDestroy
09-13 11:58:27.421  6947  6947 V BluetoothPbapService: Pbap Service closeService in
09-13 11:58:27.421  6947  6947 V BluetoothPbapService: Pbap Service closeService out
09-13 11:58:27.421  6947  6947 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 11:58:27.422  6827  6827 D BluetoothPbap: Proxy object disconnected
09-13 11:58:27.422  6827  6827 D PbapServerProfile: Bluetooth service disconnected
09-13 11:58:27.423  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 11:58:27.437  6827  6827 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 11:58:27.445  6827  6827 D BluetoothPermissionRequest: onReceive
09-13 11:58:27.445  6827  6827 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 11:58:27.456  6827  6827 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 11:58:27.462  6947  6947 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 11:58:27.462  6947  6947 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-13 11:58:27.463  6947  6947 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 11:58:27.468  6947  6947 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:27.468  6947  6947 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 11:58:27.469  6947  6947 V BluetoothFtpService: Ftp Service onStartCommand
09-13 11:58:27.469  6947  6947 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:27.469  6947  6947 V BluetoothFtpService: Ftp Service closeService
09-13 11:58:27.469  6947  6947 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 11:58:27.472  6947  6947 V BluetoothFtpService: successfully stopped ftp service
09-13 11:58:27.473  6947  6947 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 11:58:27.473  6947  6947 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 11:58:27.473  6947  6947 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 11:58:27.473  6947  6947 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:27.473  6947  6947 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 11:58:27.473  6947  6947 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 11:58:27.474  6947  6947 V BluetoothFtpService: Ftp Service onDestroy
09-13 11:58:27.474  6947  6947 V BluetoothFtpService: Ftp Service closeService
,09-13 11:58:27.478  6947  6947 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:27.478  6947  6947 V BluetoothSapService: state: 13
09-13 11:58:27.479  6947  6947 V BluetoothSapService: Stopping SAP server process
09-13 11:58:27.480  6947  6947 V BluetoothSapService: Sap Service closeSapService in
09-13 11:58:27.480  6947  6947 V BluetoothSapService: Close listen Socket : 
09-13 11:58:27.480  6947  6947 V BluetoothSapService: Close rfcomm Socket : 
09-13 11:58:27.480  6947  6947 V BluetoothSapService: Close sapd  Socket : 
09-13 11:58:27.485  6947  6947 V BluetoothSapService: Sap Service closeSapService out
09-13 11:58:27.485  6947  6947 V BluetoothSapService: Sap Service onDestroy
09-13 11:58:27.485  6947  6947 V BluetoothSapService: Sap Service closeSapService in
09-13 11:58:27.485  6947  6947 V BluetoothSapService: Close listen Socket : 
09-13 11:58:27.485  6947  6947 V BluetoothSapService: Close rfcomm Socket : 
09-13 11:58:27.485  6947  6947 V BluetoothSapService: Close sapd  Socket : 
09-13 11:58:27.486  6947  6947 V BluetoothSapService: Sap Service closeSapService out
,09-13 11:58:27.681  7563  7563 I UEI.SmartControl: Supports setup maps: true
,09-13 11:58:27.684  7563  7563 D UEI.SmartControl: QS start statue = true Error code = 0
,09-13 11:58:27.685  7563  7563 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 11:58:27.685  7563  7563 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,09-13 11:58:27.685  7563  7563 I UEI.SmartControl: ### init IR Blaster...
09-13 11:58:27.690  7563  7563 D serial_port: Configuring serial port
09-13 11:58:27.694  7563  7563 E UEI.SmartControl: UEIBLaster setting for 616
09-13 11:58:27.694  7563  7563 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 11:58:27.694  7563  7563 I UEI.SmartControl: configuring settings for MAXQ616
09-13 11:58:27.694  7563  7563 I UEI.SmartControl: Get version...
09-13 11:58:27.712  7563  7617 D UEI.SmartControl: serial port data available: 21
,09-13 11:58:27.745  7563  7563 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 11:58:27.745  7563  7563 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 11:58:27.745  7563  7563 I UEI.SmartControl: QS saving settings...
09-13 11:58:27.747  7563  7563 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 11:58:27.765  7563  7617 D UEI.SmartControl: serial port data available: 4
,09-13 11:58:27.810  7563  7563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-13 11:58:27.820  7563  7563 E UEI.SmartControl: Services init done
,09-13 11:58:27.820  7563  7563 D UEI.SmartControl: QS Service init finished
09-13 11:58:27.824  7563  7626 I UEI.SmartControl: Device manager: loading config....
09-13 11:58:27.825  7563  7626 D UEI.SmartControl: ----------- loading internal config...
,09-13 11:58:27.832  7563  7563 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 11:58:27.833  7563  7563 D UEI.SmartControl: QS Service version code: 201091
09-13 11:58:27.834  7563  7563 D UEI.SmartControl: Service requested: Control
09-13 11:58:27.842  7563  7626 E UEI.SmartControl: Loading SETTINGS...
,09-13 11:58:27.849  7563  7563 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 11:58:27.852  1035  1895 I ActivityManager: Killing 6880:com.lge.qremote/u0a112 (adj 15): empty #17
09-13 11:58:27.855  7563  7626 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 11:58:27.882  7563  7625 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 11:58:27.882  7563  7625 D UEI.SmartControl: -----service ready thread exits
,09-13 11:58:27.889  1035  1649 W libprocessgroup: failed to open /acct/uid_10112/pid_6880/cgroup.procs: No such file or directory
,09-13 11:58:27.890  7563  7563 D UEI.SmartControl: Internal service binding...
09-13 11:58:28.344  6947  7411 D bt_hci_bdroid: cleanup
,09-13 11:58:28.352  6947  7478 I bt_lpm  : LPM is already off!!!
09-13 11:58:28.353  6947  7506 I bt_userial_mct: exiting userial_read_thread
09-13 11:58:28.353  6947  7506 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 11:58:28.354  6947  7476 W bt-btif : ag scb idx 1 not allocated
09-13 11:58:28.355  6947  7476 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 11:58:28.355  6947  7476 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:58:28.356  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 11:58:28.356  6947  7476 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:58:28.356  6947  7476 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 11:58:28.356  6947  7476 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 11:58:28.356  6947  7476 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 11:58:28.360  6947  7411 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 11:58:28.360  6947  7478 I bt_vendor: hw_epilog_process
09-13 11:58:28.361  6947  7411 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 11:58:28.361  6947  7411 D bt_userial_mct: userial_close
09-13 11:58:28.361  6947  7411 E bt_userial_mct: pthread_join() FAILED result:3
09-13 11:58:28.361  6947  7411 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-13 11:58:28.369  6947  7411 D bt_hci_bdroid: set_power 0
09-13 11:58:28.369  6947  7411 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 11:58:28.369  6947  7411 I bt_vendor: bluetooth satus is on
09-13 11:58:28.369  6947  7411 I bt_vendor: bt-vendor : resetting BT status
09-13 11:58:28.369  6947  7411 I bt_vendor: Starting hciattach daemon
09-13 11:58:28.369  6947  7411 I bt_vendor: try to set false
,09-13 11:58:28.377  6947  7411 I bt_vendor: Starting hciattach daemon
09-13 11:58:28.377  6947  7411 I bt_vendor: try to set false
09-13 11:58:28.378  6947  7411 I bt_vendor: cleanup
09-13 11:58:28.380  6947  7476 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 11:58:28.380  6947  7411 I GKI_LINUX: GKI_exit_task 0 done
09-13 11:58:28.380  6947  7411 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 11:58:28.381  6947  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 11:58:28.386  6947  6947 D HeadsetService: Received stop request...Stopping profile...
,09-13 11:58:28.390  6947  7425 D HeadsetStateMachine: Exit Disconnected: -1
09-13 11:58:28.393  6947  6947 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 11:58:28.393  6947  6947 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 11:58:28.393  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:28.397  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-13 11:58:28.397  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-13 11:58:28.397  1851  1851 D BluetoothHeadset: Proxy object disconnected
09-13 11:58:28.397  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-13 11:58:28.397  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 11:58:28.400  6947  6947 D A2dpService: Received stop request...Stopping profile...
,09-13 11:58:28.402  6947  7461 D A2dpStateMachine: Exit Disconnected: -1
09-13 11:58:28.405  6947  7407 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 11:58:28.406  6947  6947 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 11:58:28.408  6947  6947 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 11:58:28.408  6947  6947 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 11:58:28.408  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:28.410  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-13 11:58:28.410  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 11:58:28.411  6947  6947 D HidService: Received stop request...Stopping profile...
09-13 11:58:28.411  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:28.413  6947  6947 D HealthService: Received stop request...Stopping profile...
09-13 11:58:28.413  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
,09-13 11:58:28.417  6947  6947 D HeadsetStateMachine: Unbinding service...
09-13 11:58:28.419  6947  6947 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 11:58:28.419  6947  6947 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 11:58:28.419  6947  6947 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 11:58:28.419  6947  6947 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 11:58:28.419  6947  6947 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 11:58:28.419  6947  6947 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 11:58:28.419  6947  6947 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 11:58:28.421  6947  6947 D PanService: Received stop request...Stopping profile...
09-13 11:58:28.421  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:28.422  6947  6947 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 11:58:28.423  6947  6947 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 11:58:28.423  6947  6947 D BtGatt.GattService: stop()
09-13 11:58:28.423  6947  6947 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 11:58:28.425  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
,09-13 11:58:28.429  6947  6947 D BluetoothMapService: Received stop request...Stopping profile...
09-13 11:58:28.429  6947  6947 D BluetoothMapService: stop()
09-13 11:58:28.431  6947  6947 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 11:58:28.431  6947  6947 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 11:58:28.432  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d73954d
09-13 11:58:28.433  6947  6947 I BluetoothA2dpServiceJni: cleanupNative
09-13 11:58:28.433  6947  7462 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 11:58:28.433  6947  6947 I GKI_LINUX: GKI_exit_task 2 done
09-13 11:58:28.433  6947  6947 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 11:58:28.434  6947  6947 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 11:58:28.434  6947  6947 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 11:58:28.434  6947  6947 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 11:58:28.435  6947  6947 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 11:58:28.435  6947  6947 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 11:58:28.435  6947  6947 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 11:58:28.435  6947  6947 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 11:58:28.438  6947  6947 V BluetoothMapService: Handler(): got msg=4
09-13 11:58:28.438  6947  6947 D BluetoothMapService: MAP Service closeService in
09-13 11:58:28.438  6947  6947 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 11:58:28.439  6947  6947 V BluetoothMapService: MAP Service closeService out
,09-13 11:58:28.443  6947  7407 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 11:58:28.443  6947  7407 D BluetoothAdapterProperties: Setting state to 10
09-13 11:58:28.443  6947  7407 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 11:58:28.444  6947  6947 D BluetoothMapService: cleanup()
09-13 11:58:28.444  6947  6947 D BluetoothMapService: MAP Service closeService in
09-13 11:58:28.445  6947  6947 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 11:58:28.445  6947  6947 V BluetoothMapService: MAP Service closeService out
09-13 11:58:28.447  1035  1111 D BluetoothManagerService: Message: 60
09-13 11:58:28.447  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 11:58:28.447  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-13 11:58:28.448  6947  7407 I BluetoothAdapterState: Entering OffState
09-13 11:58:28.448  6827  6844 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:58:28.449  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:58:28.449  1851  4399 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:58:28.450  6827  6844 D BluetoothPan: onBluetoothStateChange on: false
09-13 11:58:28.451  1851  2718 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:58:28.453  6827  6844 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 11:58:28.454  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:58:28.454  6827  6844 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:58:28.456  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:58:28.456  6827  6844 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 11:58:28.457  6827  6844 D BluetoothMap: onBluetoothStateChange: up=false
09-13 11:58:28.458  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-13 11:58:28.458  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-13 11:58:28.460  1035  1111 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-13 11:58:28.460  1035  1111 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-13 11:58:28.460  1035  1111 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1674fbbb mBinding = false
09-13 11:58:28.461  1035  1111 D BluetoothManagerService: Sending unbind request.
09-13 11:58:28.465  6947  7411 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-13 11:58:28.468  6947  6947 I GKI_LINUX: GKI_exit_task 1 done
09-13 11:58:28.468  6947  6947 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-13 11:58:28.469  6947  6947 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 11:58:28.469  6947  6947 I art     : --- WEIRD: removing null entry 248
09-13 11:58:28.470  6947  6947 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-13 11:58:28.470  6947  6947 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-13 11:58:28.471  6947  6947 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-13 11:58:28.472  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 11:58:28.474  6947  6947 I art     : System.exit called, status: 0
09-13 11:58:28.474  6947  6947 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 11:58:28.493   317  1398 V AudioFlinger: 6947 died, releasing its sessions
09-13 11:58:28.494   317  1398 V AudioFlinger:  pid 1851 @ 0
09-13 11:58:28.494   317  1398 V AudioFlinger:  pid 3453 @ 1
09-13 11:58:28.494   317  1398 V AudioFlinger:  pid 3453 @ 2
,09-13 11:58:28.497  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-13 11:58:28.498  1940  2094 D LGBluetoothAPIService: Message: 101
,09-13 11:58:28.501  6827  6827 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-13 11:58:28.507  1940  2094 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-13 11:58:28.507  1940  2094 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-13 11:58:28.507  1940  2094 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,09-13 11:58:28.605  1035  2002 I ActivityManager: Process com.android.bluetooth (pid 6947) has died
09-13 11:58:28.605  1035  2002 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
,09-13 11:58:28.606  1035  2002 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,09-13 11:58:28.619  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:28.619  1940  2094 D LGBluetoothAPIService: Message: 2
09-13 11:58:28.620  1940  2094 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-13 11:58:28.620  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 11:58:28.622  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:58:28.630  6827  6827 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 11:58:28.630  6827  6827 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 11:58:28.631  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:28.631  1602  1602 D BluetoothAdapter: 526956796: getState() :  mService = null. Returning STATE_OFF
09-13 11:58:28.631  1602  1602 D BluetoothAdapter: 526956796: getState() :  mService = null. Returning STATE_OFF
09-13 11:58:28.636  6827  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 11:58:28.688  1035  2028 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7649 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-13 11:58:28.690  6827  6827 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:58:28.791  7649  7649 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-13 11:58:28.792  7649  7649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 11:58:28.792  7649  7649 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-13 11:58:28.793  7649  7649 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 11:58:28.814  7649  7649 D BluetoothAdapterApp: Loading JNI Library
,09-13 11:58:28.851  7649  7649 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@35de895 Instance Count = 1
,09-13 11:58:28.857  7649  7649 D BluetoothAdapterApp: onCreate
09-13 11:58:28.882  7649  7649 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-13 11:58:28.883  7649  7649 D ProfileConfigQcom: Adding HeadsetService
,09-13 11:58:28.883  7649  7649 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-13 11:58:28.883  7649  7649 D ProfileConfigQcom: Adding A2dpService
,09-13 11:58:28.883  7649  7649 D ProfileConfigQcom: [BTUI] HidService is supported
09-13 11:58:28.883  7649  7649 D ProfileConfigQcom: Adding HidService
09-13 11:58:28.884  7649  7649 D ProfileConfigQcom: [BTUI] HealthService is supported
09-13 11:58:28.884  7649  7649 D ProfileConfigQcom: Adding HealthService
09-13 11:58:28.884  7649  7649 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-13 11:58:28.885  7649  7649 D ProfileConfigQcom: [BTUI] PanService is supported
09-13 11:58:28.886  7649  7649 D ProfileConfigQcom: Adding PanService
09-13 11:58:28.886  7649  7649 D ProfileConfigQcom: [BTUI] GattService is supported
09-13 11:58:28.886  7649  7649 D ProfileConfigQcom: Adding GattService
09-13 11:58:28.886  7649  7649 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-13 11:58:28.886  7649  7649 D ProfileConfigQcom: Adding BluetoothMapService
09-13 11:58:28.887  7649  7649 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-13 11:58:28.888  7649  7649 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 11:58:28.889  7649  7649 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:28.889  7649  7649 V BluetoothPbapReceiver: ***********state = 10
,09-13 11:58:28.891  7649  7649 V LGMDMManagerInternal: Create singleton instance
09-13 11:58:29.003  7649  7649 D LGBluetoothAPIServer: [BTUI] onCreate()
,09-13 11:58:29.004  7649  7649 D LGBluetoothAPIServer: [BTUI] onBind()
,09-13 11:58:29.007  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 11:58:29.008  1940  2094 D LGBluetoothAPIService: Message: 100
09-13 11:58:29.008  1940  2094 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 11:58:29.009  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 11:58:29.025  6827  6827 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 11:58:29.026  6827  6827 D BluetoothPermissionRequest: onReceive
,09-13 11:58:29.029  6827  6827 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 11:58:29.029  6827  6827 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 11:58:29.031  6827  6827 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 11:58:29.036  7649  7649 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 11:58:29.040  7649  7649 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 11:58:29.044  7649  7649 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-13 11:58:29.044  7649  7649 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-13 11:58:29.045  7649  7649 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 11:58:29.046  7649  7649 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:29.046  7649  7649 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 11:58:29.049  6897  6897 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-13 11:58:30.362  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:58:30.363  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-13 11:58:30.561  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 11:58:30.619  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 11:58:30.656  1035  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7678 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-13 11:58:30.705  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-13 11:58:30.721  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 11:58:30.724  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-13 11:58:30.737  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 11:58:30.756  7678  7678 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 11:58:30.762  1035  1035 D administrator: Handling package changes for user 0
09-13 11:58:30.853  7678  7678 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:30.853  7678  7678 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:30.861  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-13 11:58:30.861  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 11:58:30.894  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 11:58:30.899  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 11:58:30.907  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-13 11:58:30.909  2454  2454 V GmsNetworkLocationProvi: DISABLE
,09-13 11:58:30.941  2454  2454 E GCoreFlp: Bound FusedProviderService with LocationManager
09-13 11:58:30.968  7678  7723 I Babel   : MmsConfig: mnc/mcc: 0/0
09-13 11:58:30.968  7678  7723 I Babel   : MmsConfig.loadMmsSettings
,09-13 11:58:30.970  7678  7723 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 11:58:30.970  7678  7723 I Babel   : MmsConfig.loadFromDatabase
09-13 11:58:30.981  7678  7723 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-13 11:58:30.981  7678  7723 I Babel   : MmsConfig.loadFromResources
09-13 11:58:30.983  7678  7723 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-13 11:58:30.984  7678  7723 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-13 11:58:31.002  7678  7678 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:31.004  7678  7721 W AudioCapabilities: Unsupported mime audio/evrc
09-13 11:58:31.005  7678  7721 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 11:58:31.007  7678  7721 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 11:58:31.018  7678  7721 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-13 11:58:31.020  7678  7721 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 11:58:31.020  1816  7726 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-13 11:58:31.021  1816  7726 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-13 11:58:31.022  7678  7721 W AudioCapabilities: Unsupported mime audio/evrc
09-13 11:58:31.026  7012  7012 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 11:58:31.029  1816  4722 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-13 11:58:31.031  7012  7012 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@218cf877
09-13 11:58:31.031  7012  7012 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 11:58:31.031  7012  7012 D AppUp4:CustFacade: isPhone : true
09-13 11:58:31.031  7012  7012 D AppUp4:CustModeStarterReceiver: begin check event
09-13 11:58:31.031  7012  7012 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-13 11:58:31.049  7678  7721 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-13 11:58:31.051  7678  7721 W VideoCapabilities: Unsupported mime video/divx
09-13 11:58:31.055  7678  7721 W VideoCapabilities: Unsupported mime video/divx311
09-13 11:58:31.055  1035  1880 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7729 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-13 11:58:31.057  7678  7721 W VideoCapabilities: Unsupported mime video/divx4
09-13 11:58:31.058  1035  1091 D LocationProviderProxy: applying state to connected service
09-13 11:58:31.062  1035  1696 I ActivityManager: Killing 6849:com.lge.sync/1000 (adj 15): empty #17
,09-13 11:58:31.074  1035  1441 D WifiService: Client connection lost with reason: 4
09-13 11:58:31.077  7678  7721 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-13 11:58:31.088  7678  7721 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-13 11:58:31.091  7678  7721 W AudioCapabilities: Unsupported mime audio/eac3
,09-13 11:58:31.092  7678  7721 W AudioCapabilities: Unsupported mime audio/ac3
,09-13 11:58:31.092  7678  7721 W AudioCapabilities: Unsupported mime audio/g726
09-13 11:58:31.093  7678  7721 W AudioCapabilities: Unsupported mime audio/wma-voice
09-13 11:58:31.094  7678  7721 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-13 11:58:31.095  7678  7721 W AudioCapabilities: Unsupported mime audio/adpcm
09-13 11:58:31.096  7678  7721 W VideoCapabilities: Unsupported mime video/theora
09-13 11:58:31.097  7678  7721 W VideoCapabilities: Unsupported mime video/mjpg
09-13 11:58:31.201  1035  1649 W libprocessgroup: failed to open /acct/uid_1000/pid_6849/cgroup.procs: No such file or directory
,09-13 11:58:31.249  7729  7729 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 11:58:31.252  7729  7729 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 11:58:31.252  7729  7729 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 11:58:31.254  7729  7729 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 11:58:31.254  7729  7729 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 11:58:31.335  7729  7729 I SystemConfig: BUILD Country: EU
09-13 11:58:31.335  7729  7729 I SystemConfig: BUILD Operator: OPEN
,09-13 11:58:31.380  1035  1880 I ActivityManager: Killing 7040:com.lge.email/u0a23 (adj 15): empty #17
,09-13 11:58:31.523  1035  1880 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7752 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-13 11:58:31.526  1035  1649 W libprocessgroup: failed to open /acct/uid_10023/pid_7040/cgroup.procs: No such file or directory
09-13 11:58:31.538  7729  7750 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 11:58:31.538  7729  7750 I SystemConfig: existFile = false
,09-13 11:58:31.538  7729  7750 I SystemConfig: canReadFile = false
09-13 11:58:31.539  7729  7750 I SystemConfig: systemFeature RCS result false
09-13 11:58:31.539  7729  7750 D SystemConfig: refreshRcsSupport() :false
,09-13 11:58:31.575  7752  7752 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 11:58:31.576  7752  7752 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 11:58:31.576  7752  7752 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 11:58:31.576  7752  7752 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 11:58:31.675  7752  7752 I AppConfig: Total System Memory = 2995761152
,09-13 11:58:31.685  7752  7752 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-13 11:58:31.780  1035  1696 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7771 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 11:58:31.781  1035  1696 I ActivityManager: Killing 6918:com.lge.formmanager/u0a26 (adj 15): empty #17
09-13 11:58:31.860  1035  1957 W libprocessgroup: failed to open /acct/uid_10026/pid_6918/cgroup.procs: No such file or directory
,09-13 11:58:32.088  7771  7771 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-13 11:58:32.187  7771  7771 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:32.187  7771  7771 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:32.268  7771  7771 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-13 11:58:32.291  7771  7771 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 11:58:32.293  7771  7771 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 11:58:32.314  7771  7771 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 11:58:32.314  7771  7771 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-13 11:58:32.333  1035  1895 I ActivityManager: Killing 6396:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-13 11:58:32.373  1035  1922 W libprocessgroup: failed to open /acct/uid_1000/pid_6396/cgroup.procs: No such file or directory
,09-13 11:58:32.381  4575  7811 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-13 11:58:32.424  1035  1649 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7812 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-13 11:58:32.438  2848  6189 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-13 11:58:32.452  2848  6189 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3eb1c36b on behalf of 7771
,09-13 11:58:32.466  7771  7771 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-13 11:58:32.494  7771  7771 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-13 11:58:32.511  7812  7812 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-13 11:58:32.530  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-13 11:58:32.530  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-13 11:58:32.530  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-13 11:58:32.530  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 11:58:32.530  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-13 11:58:32.530  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-13 11:58:32.552  1035  1880 I ActivityManager: Killing 7080:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-13 11:58:32.644  1035  1575 W libprocessgroup: failed to open /acct/uid_10046/pid_7080/cgroup.procs: No such file or directory
,09-13 11:58:32.806  7563  7627 D UEI.SmartControl: Internal timer expired: 1
09-13 11:58:32.806  7563  7627 D UEI.SmartControl: unbind internal service
,09-13 11:58:32.813  7563  7563 D UEI.SmartControl: Service.onUnbind: IControl
09-13 11:58:32.814  7563  7563 D UEI.SmartControl: Service.onDestroy
09-13 11:58:32.814  7563  7563 D UEI.SmartControl: Lock is in USE false
09-13 11:58:32.814  7563  7563 D UEI.SmartControl: unbind internal service
09-13 11:58:32.817  7563  7563 D serial_port: close(fd = 25)
09-13 11:58:32.821  7563  7563 I UEI.SmartControl: Serial port is closed.
,09-13 11:58:32.829  7563  7563 I UEI.SmartControl: Serial port is closed.
09-13 11:58:32.829  7563  7563 D UEI.SmartControl: Blaster closed
09-13 11:58:32.830  7563  7563 D UEI.SmartControl: Shut down QS...
09-13 11:58:32.830  7563  7563 D UEI.SmartControl: Stopping QS lib
09-13 11:58:32.830  7563  7563 D UEI.SmartControl: QS lib stop result = true
09-13 11:58:32.830  7563  7563 D UEI.SmartControl: Stopped QS lib
09-13 11:58:32.831  7563  7563 D UEI.SmartControl: Stopped file observer...
09-13 11:58:32.831  7563  7563 D UEI.SmartControl: QS shutdown complete
09-13 11:58:32.867  1035  1917 V SIM_STK : Menu title from STK is T-Mobile
,09-13 11:58:32.896  4575  7811 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 515 ms] updated apps [took 515 ms] 
,09-13 11:58:33.383  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:58:33.383  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24d5144 added. We now have 6 listener(s)
09-13 11:58:33.383  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:58:33.401  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:33.401  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2846822d added. We now have 7 listener(s)
09-13 11:58:33.401  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:33.403  6708  6778 I System.out: IsBluetoothEnabled
09-13 11:58:33.409  1035  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:33.409  1035  1575 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,09-13 11:58:33.412  1035  1111 D BluetoothManagerService: Message: 2
09-13 11:58:33.416  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:33.416  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:33.416  1035  1051 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-13 11:58:33.435  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 11:58:33.435  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 11:58:33.435  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 11:58:33.436  1035  1111 D BluetoothManagerService: Message: 1
09-13 11:58:33.436  1035  1111 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-13 11:58:33.462  1035  1111 D BluetoothManagerService: Message: 20
09-13 11:58:33.462  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34331fb1:true
,09-13 11:58:33.466  7649  7649 D BluetoothAdapterState: make
09-13 11:58:33.471  7649  7649 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-13 11:58:33.471  7649  7649 I bluedroid-qcom: init
09-13 11:58:33.472  7649  7857 I BluetoothAdapterState: Entering OffState
09-13 11:58:33.473  7649  7649 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 11:58:33.473  7649  7649 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 11:58:33.473  7649  7649 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 11:58:33.473  7649  7649 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 11:58:33.473  7649  7649 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-13 11:58:33.475  7649  7649 I bluedroid-qcom: get_profile_interface socket
09-13 11:58:33.475  7649  7649 I bluedroid-qcom: get_profile_interface map_client
,09-13 11:58:33.479  7649  7861 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-13 11:58:33.476  7860  7860 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:33.476  7860  7860 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:33.490  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-13 11:58:33.493  1035  1111 D BluetoothManagerService: Message: 40
09-13 11:58:33.493  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-13 11:58:33.494  7649  7667 I bluedroid-qcom: config_hci_snoop_log
09-13 11:58:33.495  1035  1111 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-13 11:58:33.495  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-13 11:58:33.498  7649  7861 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 11:58:33.500  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-13 11:58:33.500  7860  7860 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-13 11:58:33.500  7860  7860 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-13 11:58:33.501  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 11:58:33.502  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 11:58:33.502  7649  7861 D BluetoothAdapterProperties: Name is: G3
,09-13 11:58:33.505  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-13 11:58:33.511  7860  7860 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-13 11:58:33.511  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-13 11:58:33.515  7649  7857 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 11:58:33.515  7649  7857 D BluetoothAdapterProperties: Setting state to 11
09-13 11:58:33.515  7649  7857 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-13 11:58:33.519  7649  7857 I LGBluetoothServiceJni: classInitNative: succeeds
09-13 11:58:33.523  1035  1111 D BluetoothManagerService: Message: 60
09-13 11:58:33.523  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 11:58:33.523  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 11:58:33.527  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 11:58:33.532  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 11:58:33.534  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:33.536  6827  6827 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 11:58:33.542  7649  7649 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 11:58:33.542  7649  7649 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:33.542  7649  7649 V BluetoothPbapReceiver: ***********state = 11
,09-13 11:58:33.560  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:58:33.569  7649  7857 D BluetoothBondStateMachine: make
09-13 11:58:33.572  7649  7875 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 11:58:33.573  7649  7857 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
09-13 11:58:33.573  7649  7857 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-13 11:58:33.573  7649  7857 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
09-13 11:58:33.573  7649  7857 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 11:58:33.574  7649  7857 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 11:58:33.578  7649  7857 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 11:58:33.587  7649  7857 E BluetoothAdapterService: File transfer profiles supported!!
09-13 11:58:33.589  7649  7649 D HeadsetService: Received start request. Starting profile...
09-13 11:58:33.589  7649  7649 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 11:58:33.590  7649  7649 D LGBluetoothHfpAdapter: Version 1.6
,09-13 11:58:33.594  7649  7649 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 11:58:33.594  6827  6827 D BluetoothPermissionRequest: onReceive
09-13 11:58:33.595  7649  7649 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 11:58:33.595  7649  7857 E BluetoothAdapterService: File transfer profiles supported!!
09-13 11:58:33.595  7649  7649 D HeadsetStateMachine: make
09-13 11:58:33.599  6827  6827 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 11:58:33.603  7649  7857 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 11:58:33.611  7649  7857 E BluetoothAdapterService: File transfer profiles supported!!
09-13 11:58:33.615  7649  7857 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 11:58:33.621  7649  7857 E BluetoothAdapterService: File transfer profiles supported!!
09-13 11:58:33.635  7649  7857 V LGMDMManager: Create singleton instance
09-13 11:58:33.636  7649  7649 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 11:58:33.636  7649  7649 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 11:58:33.637  7649  7857 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 11:58:33.641  7649  7649 D HeadsetStateMachine: max_hf_connections = 1
09-13 11:58:33.642  7649  7649 I bluedroid-qcom: get_profile_interface handsfree
09-13 11:58:33.644  7649  7649 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-13 11:58:33.644   317  1397 V AudioPolicyService: registerClient() client 0xb0403180, uid 1002
09-13 11:58:33.645   317  2174 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-13 11:58:33.645   317  2174 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 11:58:33.645   317  2174 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 11:58:33.645  7649  7649 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 11:58:33.645   317  2172 V AudioFlinger: registerClient() client 0xb102fb68, pid 7649
09-13 11:58:33.646   317  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:33.646   317  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 11:58:33.646  1602  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:33.646  1602  1625 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 11:58:33.646  1851  1866 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:33.646  1851  1866 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 11:58:33.646  3453  3469 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:33.646  3453  3469 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 11:58:33.646  1035  1895 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:33.646  1035  1895 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 11:58:33.647   317  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:33.647   317  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 11:58:33.647  1602  2193 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:33.647  1602  2193 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 11:58:33.647  1851  4398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:33.647  1851  4398 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-13 11:58:33.647  3453  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:33.647  3453  3468 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 11:58:33.647  7649  7667 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 11:58:33.647  7649  7667 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-13 11:58:33.647  7649  7667 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:33.647  7649  7667 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-13 11:58:33.647  1035  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 11:58:33.647  1035  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 11:58:33.648  7649  7649 V ToneGenerator: Create Track: 0xb4928a80
09-13 11:58:33.648  7649  7649 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-13 11:58:33.648  7649  7649 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-13 11:58:33.648   317  1398 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 11:58:33.648   317  1398 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-13 11:58:33.648   317  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 11:58:33.648   317  1398 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 11:58:33.648   317  1397 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 11:58:33.649   317  2174 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 11:58:33.649   317  2174 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-13 11:58:33.649   317  2174 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 11:58:33.649   317  2174 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 11:58:33.649  7649  7649 V AudioSystem: getLatency() output 2, latency 50
09-13 11:58:33.649  7649  7649 V AudioSystem: getFrameCount() output 2, frameCount 960
09-13 11:58:33.649  7649  7649 V AudioTrack: createTrack_l() output 2 afLatency 50
09-13 11:58:33.649   317  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 11:58:33.649   317  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 11:58:33.649   317  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 11:58:33.649   317  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 11:58:33.649   317  2172 V AudioFlinger: createTrack() lSessionId: 21
09-13 11:58:33.651  7649  7649 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-13 11:58:33.651   317  2172 V AudioFlinger: acquiring 21 from 7649, for 7649
09-13 11:58:33.651   317  2172 V AudioFlinger:  added new entry for 21
09-13 11:58:33.652  7649  7649 V ToneGenerator: ToneGenerator INIT OK, time: 206533
09-13 11:58:33.652  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
09-13 11:58:33.653  7649  7879 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 11:58:33.653  7649  7879 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 11:58:33.653  7649  7879 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 11:58:33.654  7649  7879 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 11:58:33.655  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
09-13 11:58:33.656   317  1398 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7649
09-13 ,11:58:33.657   317  1398 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 11:58:33.657   317  1398 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 11:58:33.657   317  1398 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 11:58:33.657   317  1398 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 11:58:33.657   317  1398 V voice   : voice_set_parameters: exit with code(0)
09-13 11:58:33.657   317  1398 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 11:58:33.657   317  1398 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 11:58:33.658   317  1398 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 11:58:33.658   317  1398 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 11:58:33.658   317  1398 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 11:58:33.658   317  1398 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 11:58:33.658  7649  7879 V ToneGenerator: ToneGenerator destructor
09-13 11:58:33.658  7649  7879 V ToneGenerator: stopTone
09-13 11:58:33.658  7649  7879 V ToneGenerator: Delete Track: 0xb4928a80
09-13 11:58:33.658  7649  7649 D A2dpService: Received start request. Starting profile...
09-13 11:58:33.658  7649  7879 V AudioTrack: ~AudioTrack, releasing session id from 7649 on behalf of 7649
09-13 11:58:33.659   317  2174 V AudioPolicyService: AudioCommandThread() adding release output 2
09-13 11:58:33.659   317   317 V AudioFlinger: releasing 21 from 7649 for 7649
09-13 11:58:33.659   317   317 V AudioFlinger:  decremented refcount to 0
09-13 11:58:33.659   317  2174 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-13 11:58:33.659   317   317 V AudioFlinger: purging stale effects
09-13 11:58:33.659   317  2174 V AudioFlinger: PlaybackThread::Track destructor
09-13 11:58:33.659   317  1268 V AudioPolicyService: AudioCommandThread() waking up
09-13 11:58:33.659   317  2174 V AudioFlinger: removeClient_l() pid 7649, calling pid 317
09-13 11:58:33.659   317  1268 V AudioPolicyService: AudioCommandThread() processing release output 2
09-13 11:58:33.659   317  1268 V AudioPolicyManager: releaseOutput() 2
09-13 11:58:33.659   317  1268 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 11:58:33.659  7649  7649 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 11:58:33.660  7649  7649 V Avrcp   : make
09-13 11:58:33.661  7649  7649 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 11:58:33.661  7649  7649 I bluedroid-qcom: get_profile_interface avrcp
09-13 11:58:33.670  7649  7649 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 11:58:33.672  7649  7649 E AudioManager: No RCC entry present to update
09-13 11:58:33.672  7649  7649 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 11:58:33.676  7649  7649 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-13 11:58:33.677  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 11:58:33.677  7649  7649 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-13 11:58:33.682  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 11:58:33.848  1035  1922 V SIM_STK : Menu title from STK is T-Mobile
,09-13 11:58:33.848  1035  1922 V SIM_STK : Menu title from STK is T-Mobile
,09-13 11:58:33.987  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-13 11:58:34.000  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 11:58:34.006  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 11:58:34.007  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 11:58:34.007  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,09-13 11:58:34.012  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 11:58:34.012  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 11:58:34.013  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 11:58:34.013  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 11:58:34.013  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 11:58:34.013  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 11:58:34.013  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 11:58:34.015  7649  7649 I BluetoothA2dpServiceJni: classInitNative
09-13 11:58:34.015  7649  7649 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 11:58:34.016  7649  7649 D A2dpStateMachine: make
09-13 11:58:34.019  7649  7649 I bluedroid-qcom: get_profile_interface a2dp
09-13 11:58:34.019  7649  7891 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 11:58:34.025  7649  7649 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-13 11:58:34.025  7649  7649 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 11:58:34.027  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
,09-13 11:58:34.031  7649  7890 D A2dpStateMachine: Enter Disconnected: -2
09-13 11:58:34.031  7649  7649 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 11:58:34.034  7649  7649 D HidService: Received start request. Starting profile...
09-13 11:58:34.034  7649  7649 I bluedroid-qcom: get_profile_interface hidhost
09-13 11:58:34.035  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
09-13 11:58:34.039  7649  7649 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 11:58:34.044  7649  7649 D HealthService: Received start request. Starting profile...
,09-13 11:58:34.049  7649  7649 I bluedroid-qcom: get_profile_interface health
09-13 11:58:34.050  7649  7649 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-13 11:58:34.050  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
09-13 11:58:34.052  7649  7649 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 11:58:34.057  7649  7649 D PanService: Received start request. Starting profile...
,09-13 11:58:34.058  7649  7649 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 11:58:34.058  7649  7649 I bluedroid-qcom: get_profile_interface pan
09-13 11:58:34.071  7649  7649 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-13 11:58:34.071  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
,09-13 11:58:34.073  7649  7649 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-13 11:58:34.080  7649  7649 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 11:58:34.080  7649  7649 D BtGatt.GattService: Received start request. Starting profile...
09-13 11:58:34.080  7649  7649 D BtGatt.GattService: start()
09-13 11:58:34.080  7649  7649 I bluedroid-qcom: get_profile_interface gatt
09-13 11:58:34.081  7649  7649 D BtGatt.AdvertiseManager: advertise manager created
09-13 11:58:34.087  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
,09-13 11:58:34.090  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
,09-13 11:58:34.090  7649  7649 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 11:58:34.091  7649  7649 V BluetoothMapService: BluetoothMapBinder()
09-13 11:58:34.092  7649  7649 D BluetoothMapService: Received start request. Starting profile...
09-13 11:58:34.092  7649  7649 D BluetoothMapService: start()
09-13 11:58:34.096  7649  7649 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 11:58:34.096  7649  7649 D BluetoothMapEmailAppObserver: createReceiver()
09-13 11:58:34.097  7649  7649 D BluetoothMapEmailAppObserver: initObservers()
09-13 11:58:34.097  7649  7649 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 11:58:34.107  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
09-13 11:58:34.108  7649  7649 D HeadsetStateMachine: Proxy object connected
09-13 11:58:34.109  7649  7649 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 11:58:34.109  7649  7649 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-13 11:58:34.114  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 11:58:34.115  7649  7879 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 11:58:34.115  7649  7879 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 11:58:34.116  7649  7879 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 11:58:34.119  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 11:58:34.122  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 11:58:34.124  7649  7649 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:34.129  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 11:58:34.130  7649  7649 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 11:58:34.133  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 11:58:34.137  7649  7649 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 11:58:34.137  7649  7649 V BluetoothMapService: Handler(): got msg=1
,09-13 11:58:34.139  7649  7649 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 11:58:34.139  7649  7649 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 11:58:34.139  7649  7649 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 11:58:34.139  7649  7649 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:34.139  7649  7649 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 11:58:34.140  7649  7857 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 11:58:34.140  7649  7857 I bluedroid-qcom: enable
09-13 11:58:34.140  7649  7857 I bt_hci_bdroid: init
09-13 11:58:34.144  7649  7857 I bt_vendor: bt-vendor : init
09-13 11:58:34.144  7649  7857 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 11:58:34.144  7649  7857 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 11:58:34.144  7649  7857 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 11:58:34.144  7649  7857 D bt_userial_mct: userial_init
09-13 11:58:34.144  7649  7857 D bt_hci_bdroid: set_power 1
09-13 11:58:34.144  7649  7857 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 11:58:34.144  7649  7857 I bt_vendor: Starting hciattach daemon
09-13 11:58:34.145  7649  7857 I bt_vendor: try to set true
09-13 11:58:34.136  7901  7901 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:34.148  7649  7898 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 11:58:34.148  7649  7898 I bt-btu  : btu_task pending for preload complete event
,09-13 11:58:34.146  7901  7901 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:34.171  7902  7902 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 11:58:34.246  7908  7908 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 11:58:34.259  7909  7909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 11:58:34.285  7911  7911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 11:58:34.298  7912  7912 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-13 11:58:34.310  7913  7913 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-13 11:58:34.323  7914  7914 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-13 11:58:34.347  7916  7916 I libmdmdetect: ESOC framework not supported
,09-13 11:58:34.355  7916  7916 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 11:58:34.367  7916  7916 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 11:58:34.367  7916  7916 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 11:58:34.367  7916  7916 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 11:58:34.367  7916  7916 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 11:58:34.367  7916  7916 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 11:58:34.368  7916  7916 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 11:58:34.368  7916  7916 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-13 11:58:34.416  7916  7917 E QC-QMI  : qmi_client [7916] 15: failed to locate client data
09-13 11:58:34.417   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,09-13 11:58:34.417   481   481 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-13 11:58:34.471  7918  7918 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 11:58:34.485  7919  7919 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 11:58:34.499  7649  7857 I bt_vendor: bluetooth satus is on
09-13 11:58:34.499  7649  7857 D bt_hci_bdroid: preload
,09-13 11:58:34.499  7649  7900 D bt_userial_mct: userial_open(port:0)
09-13 11:58:34.499  7649  7900 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-13 11:58:34.503  7649  7900 I bt_vendor: Done intiailizing UART
09-13 11:58:34.504  7649  7900 I bt_vendor: Done intiailizing UART
09-13 11:58:34.504  7649  7900 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-13 11:58:34.504  7649  7900 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 11:58:34.504  7649  7921 D bt_userial_mct: Entering userial_read_thread()
09-13 11:58:34.504  7649  7898 I bt-btu  : btu_task received preload complete event
09-13 11:58:34.505  7649  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 11:58:34.505  7649  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 11:58:34.509  7649  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-13 11:58:34.516  7649  7898 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 11:58:34.516  7649  7898 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 11:58:34.516  7649  7898 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 11:58:34.516  7649  7898 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 11:58:34.516  7649  7898 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 11:58:34.516  7649  7898 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 11:58:34.516  7649  7898 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 11:58:34.517  7649  7898 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 11:58:34.517  7649  7898 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 11:58:34.517  7649  7898 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 11:58:34.517  7649  7898 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 11:58:34.517  7649  7898 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 11:58:34.517  7649  7898 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 11:58:34.517  7649  7898 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 11:58:34.517  7649  7898 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 11:58:34.517  7649  7898 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 11:58:34.604  7649  7898 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 11:58:34.604  7649  7898 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01bd061 
09-13 11:58:34.604  7649  7898 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01bd061 
,09-13 11:58:34.664  7649  7861 E bt-btif : Calling BTA_HhEnable
,09-13 11:58:34.664  7649  7861 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 11:58:34.665  7649  7861 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-13 11:58:34.674  7649  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 11:58:34.674  7649  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 11:58:34.674  7649  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 11:58:34.674  7649  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 11:58:34.674  7649  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 11:58:34.678  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 11:58:34.679  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 11:58:34.681  7649  7861 D BluetoothAdapterProperties: Name is: G3
09-13 11:58:34.689  7649  7861 D BluetoothAdapterProperties: Scan Mode:20
09-13 11:58:34.690  7649  7861 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 11:58:34.690  7649  7861 D bt_hci_bdroid: postload
,09-13 11:58:34.692  7649  7900 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 11:58:34.693  7649  7898 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 11:58:34.694  7649  7861 D bte_conf: Device ID record 1 : primary
09-13 11:58:34.694  7649  7861 D bte_conf:   vendorId            = 00c4
09-13 11:58:34.694  7649  7861 D bte_conf:   vendorIdSource      = 0001
09-13 11:58:34.694  7649  7861 D bte_conf:   product             = 13a1
09-13 11:58:34.694  7649  7861 D bte_conf:   version             = 1000
09-13 11:58:34.694  7649  7861 D bte_conf:   clientExecutableURL = 
09-13 11:58:34.694  7649  7861 D bte_conf:   serviceDescription  = 
09-13 11:58:34.694  7649  7861 D bte_conf:   documentationURL    = 
09-13 11:58:34.694  7649  7861 D bte_conf: bte_load_did_conf no section named DID2.
09-13 11:58:34.697  7649  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:34.697  7649  7898 W bt-smp  : Plain text(LSB ~ MSB) = 9f 77 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:34.697  7649  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 ea d2 45 63 6c f4 00 67 7c 35 1f 66 91 8e 01 
09-13 11:58:34.699  7649  7900 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 11:58:34.699  7649  7898 W bt-btm  : Stopping oneshot timer
09-13 11:58:34.700  7649  7857 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 11:58:34.700  7649  7857 D BluetoothAdapterProperties: ScanMode =  20
09-13 11:58:34.700  7649  7857 D BluetoothAdapterProperties: State =  11
09-13 11:58:34.700  7649  7857 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 11:58:34.700  7649  7857 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 11:58:34.701  7649  7857 D BluetoothAdapterProperties: Setting state to 12
09-13 11:58:34.696  7926  7926 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 11:58:34.701  7649  7857 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 11:58:34.707  7649  7861 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 11:58:34.696  7926  7926 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:34.711  1035  1111 D BluetoothManagerService: Message: 60
09-13 11:58:34.711  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 11:58:34.711  1035  1111 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-13 11:58:34.713  7649  7900 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 11:58:34.714  7649  7861 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 11:58:34.723  7649  7900 D bt_hci_bdroid: Used up Tx Cmd credits
,09-13 11:58:34.727  7649  7921 E bt_mct  : hci lib postload completed
09-13 11:58:34.739  7649  7857 I BluetoothAdapterState: Entering On State
,09-13 11:58:34.750  7649  7857 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 11:58:34.750  7649  7857 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 11:58:34.750  7649  7857 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 11:58:34.751  7649  7857 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 11:58:34.768  7649  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:34.768  7649  7898 W bt-smp  : Plain text(LSB ~ MSB) = 42 56 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:34.768  7649  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f 1b 26 ac 02 bf 8c db f1 9c 91 5c ec 96 3b e1 
,09-13 11:58:34.771  7649  7898 W bt-btm  : Stopping oneshot timer
09-13 11:58:34.773  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:34.773  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:34.773  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:34.773  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:34.773  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:34.773  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:34.773  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:34.773  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:34.773  7649  7861 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 11:58:34.773  7649  7861 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 11:58:34.775  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:34.780  6827  6843 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 11:58:34.784  7649  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:34.784  7649  7898 W bt-smp  : Plain text(LSB ~ MSB) = 2e ee 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:34.784  7649  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 89 1c 9e 2a 1e 31 98 ec 35 ac 5e f5 4e 1a e6 46 
09-13 11:58:34.784  7649  7898 W bt-btm  : Stopping oneshot timer
,09-13 11:58:34.791  7649  7857 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 11:58:34.801  1035  1111 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 11:58:34.808  7649  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:34.808  7649  7898 W bt-smp  : Plain text(LSB ~ MSB) = 9c a4 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:34.808  7649  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 db 83 68 96 a7 2d ab 7f 47 fc 2e ed 53 e3 21 
09-13 11:58:34.809  7649  7898 W bt-btm  : Stopping oneshot timer
09-13 11:58:34.816  1035  1035 D BluetoothHeadset: Proxy object connected
,09-13 11:58:34.828  7649  7898 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 11:58:34.829  7649  7898 W bt-smp  : Plain text(LSB ~ MSB) = 86 54 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 11:58:34.829  7649  7898 W bt-smp  : Encrypted text(LSB ~ MSB) = 47 c5 91 17 82 5c c7 e8 f4 c2 e1 55 79 f0 97 7e 
09-13 11:58:34.829  7649  7898 W bt-btm  : Stopping oneshot timer
,09-13 11:58:34.832  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:58:34.835  7931  7931 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 11:58:34.840  6827  6827 D BluetoothA2dp: Proxy object connected
09-13 11:58:34.840  6827  6827 D A2dpProfile: Bluetooth service connected
09-13 11:58:34.843  1851  1851 D BluetoothHeadset: Proxy object connected
,09-13 11:58:34.848  6827  6843 D BluetoothPan: onBluetoothStateChange on: true
,09-13 11:58:34.848  6827  6843 D BluetoothPan: onBluetoothStateChange call bindService
09-13 11:58:34.860  1851  2718 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:58:34.862  6827  6827 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 11:58:34.862  6827  6827 D PanProfile: Bluetooth service connected
,09-13 11:58:34.862  1851  1851 D BluetoothHeadset: Proxy object connected
09-13 11:58:34.864  6827  6934 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 11:58:34.866  1035  1111 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 11:58:34.866  1035  1035 D BluetoothA2dp: Proxy object connected
09-13 11:58:34.866  6827  6843 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:58:34.868  1851  4398 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:58:34.868  6827  6827 D BluetoothHeadset: Proxy object connected
09-13 11:58:34.868  6827  6827 D HeadsetProfile: Bluetooth service connected
09-13 11:58:34.870  1851  1851 D BluetoothHeadset: Proxy object connected
09-13 11:58:34.870  6827  6934 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 11:58:34.873  6827  6843 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 11:58:34.876  6827  6827 D BluetoothInputDevice: Proxy object connected
,09-13 11:58:34.876  6827  6827 D HidProfile: Bluetooth service connected
09-13 11:58:34.878  1035  1111 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 11:58:34.878  1035  1111 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 11:58:34.879  6827  6827 D BluetoothMap: Proxy object connected
09-13 11:58:34.879  6827  6827 D MapProfile: Bluetooth service connected
09-13 11:58:34.879  6827  6827 D BluetoothMap: getConnectedDevices()
09-13 11:58:34.880  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-13 11:58:34.880  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:34.881  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 11:58:34.881  1940  2094 D LGBluetoothAPIService: Message: 1
09-13 11:58:34.881  1940  2094 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 11:58:34.881  1940  2094 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-13 11:58:34.881  1940  2094 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-13 11:58:34.882  7649  7667 V BluetoothMapService: getConnectedDevices()
09-13 11:58:34.886  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:34.887  1035  1111 D BluetoothManagerService: Message: 40
09-13 11:58:34.887  1035  1111 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,09-13 11:58:34.889  7649  7649 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 11:58:34.890  7649  7649 D BluetoothMapService: STATE_ON
09-13 11:58:34.895  6827  6827 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 11:58:34.897  6827  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 11:58:34.906  6827  6827 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:58:34.910  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
09-13 11:58:34.911  7649  7649 V BluetoothPbapService: Pbap Service onCreate
09-13 11:58:34.911  7649  7649 V BluetoothPbapService: Starting PBAP service
09-13 11:58:34.912  7649  7649 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 11:58:34.912  7649  7649 V BluetoothPbapService: Pbap Service onBind
09-13 11:58:34.913  7649  7649 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:34.913  7649  7649 V BluetoothPbapService: state: 12
09-13 11:58:34.914  6827  6827 D BluetoothPbap: Proxy object connected
09-13 11:58:34.914  6827  6827 D PbapServerProfile: Bluetooth service connected
09-13 11:58:34.914  7649  7649 V BluetoothMapService: Handler(): got msg=1
09-13 11:58:34.914  7649  7649 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 11:58:34.915  7649  7649 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 11:58:34.915  7649  7649 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:34.915  7649  7649 V BluetoothPbapReceiver: ***********state = 12
09-13 11:58:34.916  7649  7950 D BluetoothMapMasInstance: MAS initSocket()
09-13 11:58:34.916  7649  7649 V BluetoothPbapService: Handler(): got msg=1
09-13 11:58:34.917  7649  7649 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 11:58:34.918  7649  7950 D BluetoothMapMasInstance:   masId = 00
09-13 11:58:34.918  7649  7950 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 11:58:34.918  7649  7950 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 11:58:34.918  7649  7950 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 11:58:34.918  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 11:58:34.918  7649  7951 V BluetoothPbapService: Pbap Service initSocket
09-13 11:58:34.919  2175  2175 D c       : Getting all permits...
09-13 11:58:34.919  2175  2175 D a       : Opening database...
09-13 11:58:34.920  1035  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 11:58:34.920  1035  1958 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:34.923  7649  7950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:34.923  7649  7951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:34.924  2175  2175 D a       : Opening database auth.proximity.permit_store...
09-13 11:58:34.925  7649  7951 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-13 11:58:34.925  7649  7951 V BluetoothPbapService: Succeed to create listening socket 
09-13 11:58:34.925  7649  7951 V BluetoothPbapService: Accepting socket connection...
09-13 11:58:34.925  2175  2175 D a       : Closing database...
09-13 11:58:34.925  7649  7861 D BluetoothAdapterProperties: Scan Mode:21
09-13 11:58:34.925  7649  7861 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 11:58:34.926  7649  7950 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-13 11:58:34.926  7649  7950 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 11:58:34.926  7649  7950 D BluetoothMapMasInstance: Accepting socket connection...
09-13 11:58:34.930  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:34.939  6827  6827 D BluetoothPermissionRequest: onReceive
,09-13 11:58:34.941  6827  6827 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-13 11:58:34.943  6827  6827 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 11:58:34.946  7649  7649 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 11:58:34.947  7649  7649 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 11:58:34.953  7649  7649 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-13 11:58:34.973  7649  7649 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-13 11:58:34.974  7649  7649 V BtOppService: onCreate
,09-13 11:58:34.978  7649  7649 V BluetoothOppNotification: send message
09-13 11:58:34.982  7649  7649 V BtOppService: Starting RfcommListener
09-13 11:58:34.988  7649  7649 D BluetoothOppPreference: Dumping Names:  
,09-13 11:58:34.989  7649  7649 D BluetoothOppPreference: {}
,09-13 11:58:34.989  7649  7649 D BluetoothOppPreference: Dumping Channels:  
09-13 11:58:34.989  7649  7649 D BluetoothOppPreference: {}
09-13 11:58:34.990  7649  7649 V BtOppService: onStartCommand
09-13 11:58:34.990  7649  7955 V BtOppService: Deleted complete outbound shares, number =  0
09-13 11:58:34.993  7649  7955 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 11:58:34.994  7649  7955 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 11:58:34.994  7649  7958 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 11:58:34.995  7649  7955 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1dac405e on behalf of 
09-13 11:58:34.995  7649  7958 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 11:58:34.996  7649  7649 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:34.996  7649  7649 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 11:58:35.000  7649  7958 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4a83c3f on behalf of 
09-13 11:58:35.000  7649  7649 V BluetoothOppNotification: new notify threadi!
09-13 11:58:35.002  7649  7649 V BluetoothOppNotification: send delay message
,09-13 11:58:35.003  7649  7649 V BtOppService: start RfcommListener
09-13 11:58:35.004  7649  7958 V BluetoothOppNotification: update too frequent, put in queue
09-13 11:58:35.004  7649  7959 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 11:58:35.007  7649  7959 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15b7090c on behalf of 
09-13 11:58:35.007  7649  7958 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 11:58:35.008  7649  7959 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 11:58:35.010  7649  7959 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 11:58:35.011  7649  7649 V BtOppService: RfcommListener started
09-13 11:58:35.012  7649  7649 V BtOppService: ContentObserver received notification
09-13 11:58:35.012  7649  7960 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 11:58:35.013  7649  7649 V BtOppService: ContentObserver received notification
09-13 11:58:35.013  1035  1917 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:35.014  7649  7961 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,09-13 11:58:35.014  7649  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 11:58:35.014  7649  7960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:35.016  7649  7960 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-13 11:58:35.016  7649  7960 V BtOppRfcommListener: Started RFCOMM listener....
09-13 11:58:35.016  7649  7960 I BtOppRfcommListener: Accept thread started.
09-13 11:58:35.016  7649  7960 V BtOppRfcommListener: Accepting connection...
09-13 11:58:35.032  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
,09-13 11:58:35.032  7649  7649 V BluetoothFtpService: Ftp Service onCreate
09-13 11:58:35.032  7649  7649 I BluetoothFtpService: Ftp Service onCreate
09-13 11:58:35.032  7649  7649 V BluetoothFtpService: Ftp Service onStartCommand
09-13 11:58:35.032  7649  7649 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:35.032  7649  7649 V BluetoothFtpService: Starting Listening on sockets
09-13 11:58:35.033  7649  7649 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 11:58:35.033  7649  7649 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 11:58:35.033  7649  7649 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 11:58:35.033  7649  7649 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:35.033  7649  7649 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 11:58:35.033  7649  7649 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 11:58:35.035  7649  7649 V BluetoothFtpService: Handler(): got msg=1
09-13 11:58:35.036  7649  7649 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 11:58:35.036  7649  7649 V BluetoothFtpService: Ftp Service initSocket
09-13 11:58:35.038  1035  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:35.039  7649  7649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:35.043  7649  7649 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-13 11:58:35.043  7649  7649 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-13 11:58:35.045  7649  7962 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-13 11:58:35.058  7649  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38423802
09-13 11:58:35.058  7649  7649 V BluetoothSapService: Sap Service onCreate
09-13 11:58:35.060  7649  7649 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:58:35.060  7649  7649 V BluetoothSapService: state: 12
09-13 11:58:35.061  7649  7649 V BluetoothSapService: Starting SAP server process
09-13 11:58:35.062  7649  7649 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 11:58:35.063  7649  7964 V BluetoothSapService: Sap Service initRfcommSocket
09-13 11:58:35.064  1035  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:35.056  7963  7963 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:35.056  7963  7963 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:35.065  7649  7964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:58:35.066  7649  7964 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-13 11:58:35.066  7649  7964 V BluetoothSapService: Succeed to create listening socket 
09-13 11:58:35.066  7649  7964 V BluetoothSapService: Accepting socket connection...
,09-13 11:58:35.076  7963  7963 V BT_SAP  : Event pipe created
09-13 11:58:35.076  7963  7963 V BT_SAP  : create_server_socket qcom.sap.server
09-13 11:58:35.076  7963  7963 V BT_SAP  : created socket fd 6
09-13 11:58:35.129  1035  1922 I art     : Explicit concurrent mark sweep GC freed 27869(1368KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.854ms total 117.022ms
,09-13 11:58:35.129  7649  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@295f1ed1 on behalf of 
09-13 11:58:35.130  7649  7961 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 11:58:35.131  7649  7959 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f89fd36 on behalf of 
09-13 11:58:35.131  7649  7959 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 11:58:35.135  7649  7959 V BluetoothOppNotification: outbound notification was removed.
09-13 11:58:35.135  7649  7959 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 11:58:35.139  7649  7959 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26ab7437 on behalf of 
09-13 11:58:35.140  7649  7959 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 11:58:35.142  7649  7959 V BluetoothOppNotification: inbound notification was removed.
09-13 11:58:35.142  7649  7959 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-13 11:58:35.143  7649  7959 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@df36da4 on behalf of 
09-13 11:58:35.471  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:35.471  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:35.471  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:35.471  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:58:35.471  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:35.471  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:35.471  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:35.471  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:58:35.480  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:35.483  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:35.483  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d7d5362 added. We now have 8 listener(s)
09-13 11:58:35.483  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:35.486  1035  1649 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 11:58:35.486  1035  1649 D WifiService: setWifiEnabled: false pid=6708, uid=10118
09-13 11:58:35.486  1035  1649 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:58:35.493  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:35.494  1035  1880 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 11:58:35.494  1035  1880 D WifiService: setWifiEnabled: true pid=6708, uid=10118
09-13 11:58:35.494  1035  1880 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:58:35.517  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-13 11:58:35.518  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 11:58:35.518  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 11:58:35.520  1035  1391 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 11:58:35.520  1035  1391 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-13 11:58:35.523  1035  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 11:58:35.523  1035  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 11:58:35.523  1035  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 11:58:35.523  1035  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-13 11:58:35.523  1035  1391 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 11:58:35.523  1035  1391 E WifiHW  : unknown target_country: EU , set to default
09-13 11:58:35.523  1035  1391 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,09-13 11:58:35.523  1035  1391 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 11:58:35.523  1035  1391 I WifiUtil: gEnableBmps=1
09-13 11:58:36.008  7649  7649 V BluetoothOppNotification: new notify threadi!
,09-13 11:58:36.021  7649  7649 V BluetoothOppNotification: send delay message
09-13 11:58:36.023  7649  7984 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 11:58:36.025  7649  7984 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ce5d70d on behalf of 
09-13 11:58:36.026  7649  7984 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 11:58:36.027  7649  7984 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 11:58:36.028  7649  7984 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2670b6c2 on behalf of 
09-13 11:58:36.029  7649  7984 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-13 11:58:36.032  7649  7984 V BluetoothOppNotification: outbound notification was removed.
09-13 11:58:36.032  7649  7984 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 11:58:36.033  7649  7984 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11b91cd3 on behalf of 
09-13 11:58:36.035  7649  7984 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 11:58:36.037  7649  7984 V BluetoothOppNotification: inbound notification was removed.
09-13 11:58:36.038  7649  7984 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 11:58:36.039  7649  7984 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10cbc010 on behalf of 
09-13 11:58:36.084   312   894 D SoftapController: Softap fwReload - Ok
,09-13 11:58:36.094  1035  1391 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (564ms)
09-13 11:58:36.099   312   894 D CommandListener: Setting iface cfg
09-13 11:58:36.100   312   894 D CommandListener: Trying to bring down wlan0
,09-13 11:58:36.104   312   894 D CommandListener: Clearing all IP addresses on wlan0
09-13 11:58:36.110  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 11:58:36.110  1035  1111 D Tethering: InitialState.processMessage what=4
09-13 11:58:36.111  1035  1111 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 11:58:36.135  1035  1391 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-13 11:58:36.146  7986  7986 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 11:58:36.156  1035  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 11:58:36.156  1035  1391 E WifiStateMachine: useWiFiOffloading() : false
09-13 11:58:36.156  1035  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 11:58:36.160  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 11:58:36.166  7986  7986 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 11:58:36.181  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-13 11:58:36.185  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:36.195  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:58:36.205  1035  1391 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 11:58:36.205  1035  1391 D WifiMonitor: connecting to supplicant
09-13 11:58:36.214  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 11:58:36.215  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 11:58:36.216  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 11:58:36.216  6827  6827 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 11:58:36.217  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-13 11:58:36.219  6827  6827 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 11:58:36.220  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 11:58:36.220  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 11:58:36.220  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 11:58:36.220  6827  6827 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 11:58:36.220  6827  6827 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 11:58:36.230  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 11:58:36.230  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 11:58:36.230  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 11:58:36.230  6827  6827 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 11:58:36.231  7986  7986 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 11:58:36.232  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 11:58:36.232  6827  6827 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 11:58:36.232  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 11:58:36.232  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 11:58:36.232  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 11:58:36.232  6827  6827 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 11:58:36.233  6827  6827 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 11:58:36.267  7986  7986 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 11:58:36.267  7986  7986 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-13 11:58:36.278  1035  1922 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8005 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-13 11:58:36.294   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 21.125ms
,09-13 11:58:36.313   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 18.684ms
,09-13 11:58:36.330   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 16.383ms
,09-13 11:58:36.357  7986  7986 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 11:58:36.371  1035  1917 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8026 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 11:58:36.374  8005  8024 W FormManager: Network not available. Please check & try again.
09-13 11:58:36.380  8005  8025 V FormManager: Network unavailable.
09-13 11:58:36.381  8005  8025 V FormManager: Network unavailable.
09-13 11:58:36.392  1035  1649 I ActivityManager: Killing 7102:com.android.chrome/u0a57 (adj 15): empty #17
,09-13 11:58:36.400  7986  7986 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 11:58:36.406  1035  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-13 11:58:36.406  1035  1391 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 11:58:36.406  1035  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 11:58:36.407  1035  1391 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 11:58:36.407  1035  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:36.408  1035  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:36.408  1035  1391 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 11:58:36.408  1035  1391 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 11:58:36.409  1035  1391 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 11:58:36.409  1035  1391 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 11:58:36.409  1035  1391 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 11:58:36.419  8026  8026 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:36.419  7986  7986 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 11:58:36.420  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 11:58:36.420  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 11:58:36.420  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 11:58:36.420  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 11:58:36.420  1035  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 11:58:36.420  1035  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,09-13 11:58:36.429  1035  1575 W libprocessgroup: failed to open /acct/uid_10057/pid_7102/cgroup.procs: No such file or directory
09-13 11:58:36.431  1035  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 11:58:36.431  1035  1391 E WifiStateMachine: useWiFiOffloading() : false
09-13 11:58:36.431  1035  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 11:58:36.431  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:36.431  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:36.431  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:36.431  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:36.431  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 11:58:36.433  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 11:58:36.433  1035  1391 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 11:58:36.434  1035  1391 D WifiNative-wlan0: SET update_config 1: returned true
09-13 11:58:36.434  1035  1391 D WifiConfigStore: Loading config and enabling all networks 
09-13 11:58:36.434  1035  1391 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 11:58:36.434  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 11:58:36.434  1035  1391 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 11:58:36.436  1940  1940 D WfdService: Waiting for WifiP2p enabling
09-13 11:58:36.437  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 11:58:36.437  1035  1403 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 11:58:36.439  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:36.439  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:36.439  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:36.439  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:36.439  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:36.439  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:36.439  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:36.439  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:36.439  1035  1391 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 11:58:36.441  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:36.441  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:36.442  1035  1575 I ActivityManager: Killing 7123:com.lge.drmservice/u0a62 (adj 15): empty #17
09-13 11:58:36.446  1035  1391 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 11:58:36.446  1035  1391 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 11:58:36.470  1035  1391 D WifiStateMachine: enableVerboseLogging : level 2
09-13 11:58:36.470  1035  1391 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 11:58:36.471  1035  1880 W libprocessgroup: failed to open /acct/uid_10062/pid_7123/cgroup.procs: No such file or directory
09-13 11:58:36.471  1035  1391 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 11:58:36.471  1035  1391 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,09-13 11:58:36.472  1035  1391 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 11:58:36.472  1035  1391 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 11:58:36.472  1035  1391 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 11:58:36.472  1035  1391 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 11:58:36.473  1035  1391 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 11:58:36.473  1035  1391 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 11:58:36.473  1035  1391 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 11:58:36.473  1035  1391 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 11:58:36.474  1035  1391 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 11:58:36.474  1035  1391 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 11:58:36.474  1035  1391 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 11:58:36.475  1035  1391 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 11:58:36.475  1035  1391 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 11:58:36.475  1940  1940 D WfdsService: Supplicant Connection state is changed : true
09-13 11:58:36.475  1035  1391 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 11:58:36.475  1035  1391 D WifiNative-HAL: Setting external_sim to 1
09-13 11:58:36.475  1035  1391 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 11:58:36.475  1940  2296 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 11:58:36.475  1940  2296 D WfdsService: Set the WFDS Monitor: true
09-13 11:58:36.475  1940  2296 D WfdsMonitor: WfdsMonitorThread create
09-13 11:58:36.475  1940  2296 D WfdsMonitor: WFDS Monitor is created and started
09-13 11:58:36.475  1940  2296 D WfdsService: WiFi: Supplicant connection re-established
09-13 11:58:36.476  1035  1391 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 11:58:36.476  1035  1391 I WifiNative-HAL: startHal
09-13 11:58:36.476  1035  1391 D wifi    : setting scan oui 0xaf6f9300
09-13 11:58:36.476  1035  1391 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 11:58:36.476  1035  1391 I WifiNative-HAL: startHal
09-13 11:58:36.476  1035  1391 D wifi    : setting scan oui 0xaf6f9300
09-13 11:58:36.476  1940  8047 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 11:58:36.476  1035  1391 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 11:58:36.477  1940  8047 E CtrlSupplicant: Succeed to open control connection
09-13 11:58:36.477  1035  1391 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 11:58:36.477  1940  8047 E CtrlSupplicant: Succeed to open monitor connection
09-13 11:58:36.477  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 11:58:36.477  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 11:58:36.477  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 11:58:36.478  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 11:58:36.478  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 11:58:36.478  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 11:58:36.478  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 11:58:36.478  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 11:58:36.478  1940  8047 D WfdsMonitor: Supplicant connection established
09-13 11:58:36.479  1940  2296 D WfdsService: Connected to the supplicant for wfds
09-13 11:58:36.479  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 11:58:36.479  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 11:58:36.479  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 11:58:36.479  7678  7678 W Settings: Setting airplane_mode_on has moved from android.provider.Settin,gs.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:36.479  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 11:58:36.479  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 11:58:36.480  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 11:58:36.480  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 11:58:36.480  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 11:58:36.480  7986  7986 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 11:58:36.481  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 11:58:36.481  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 11:58:36.481  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 11:58:36.481  1035  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 11:58:36.482  1035  1391 E WifiNative: : [209,351,317 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 11:58:36.482  1035  1391 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 11:58:36.483  1035  1391 D WifiNative-wlan0: RECONNECT: returned true
09-13 11:58:36.483  1035  1391 D WifiNative-wlan0: doString: [STATUS]
09-13 11:58:36.484  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 11:58:36.484  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 11:58:36.484  1035  1391 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 11:58:36.484  8026  8026 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:36.484  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 11:58:36.485  1035  1391 D WifiNative-wlan0: SET ps 1: returned true
09-13 11:58:36.485  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.486  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 11:58:36.487  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 11:58:36.487  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-13 11:58:36.487  1035  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.487  1035  1556 I WifiNative-HAL: startHal
09-13 11:58:36.487  1035  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf6f9300
09-13 11:58:36.487  1035  1556 D wifi    : failed to get capabilities : -3
09-13 11:58:36.487  1035  1556 E WifiScanningService: could not get scan capabilities
09-13 11:58:36.487  1035  1391 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 11:58:36.487  1035  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.488  1035  1391 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 11:58:36.488   312   894 D CommandListener: Setting iface cfg
09-13 11:58:36.488   312   894 D CommandListener: Trying to bring up p2p0
09-13 11:58:36.488  1035  1391 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 11:58:36.488  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 11:58:36.488  1035  1390 D LGWifiP2pService: P2pEnablingState
09-13 11:58:36.488  1035  1391 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 11:58:36.488  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.488  1035  1390 D LGWifiP2pService: P2p socket connection successful
09-13 11:58:36.488  1035  1390 D LGWifiP2pService: P2pEnabledState
09-13 11:58:36.489  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 11:58:36.489  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=209358  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 11:58:36.489  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 11:58:36.490  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=209359  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 11:58:36.490  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 11:58:36.490  1940  1940 D WfdsService: WifiP2pState is changed : true
09-13 11:58:36.490  1035  1391 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 11:58:36.490  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 11:58:36.491  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 11:58:36.491  1035  1391 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 11:58:36.491  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 11:58:36.491  1940  1940 D WfdsService: isConnected: false
09-13 11:58:36.491  1035  1391 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 11:58:36.491  1035  1391 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 11:58:36.491  7986  7986 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 11:58:36.491  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
09-13 11:58:36.491  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 11:58:36.492  1035  1390 D LGWifiP2pService: before postfix = G3
09-13 11:58:36.492  1940  2296 D WfdsService: Receive the WFDS_ENABLE Method
09-13 11:58:36.492  1035  1390 D WifiServerServiceExt: postfix byte check : 2
09-13 11:58:36.492  1940  2296 D WfdsService: Set the WFDS Monitor: true
09-13 11:58:36.492  1035  1390 D LGWifiP2pService: after postfix = G3
09-13 11:58:36.492  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 11:58:36.492  1940  2296 D WfdsService: Connected to the supplicant for wfds
09-13 11:58:36.492  1940  2296 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 11:58:36.492  7986  7986 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 11:58:36.492  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:36.492  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:36.492  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 11:58:36.492  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 11:58:36.493  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:36.493  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 11:58:36.493  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 11:58:36.493  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:36.493  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 11:58:36.493  1940  2296 D WfdsService: selectPreferredScanChannel [36]
09-13 11:58:36.493  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 11:58:36.493  1940  2296 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 11:58:36.493  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 11:58:36.493  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 11:58:36.493  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
09-13 11:58:36.494  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 
09-13 11:58:36.494  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:36.497  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 11:58:36.497  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 11:58:36.497  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:36.498  1940  1940 D WfdsService: Update P2p Interface State: 3
09-13 11:58:36.498  1035  1390 D LGWifiP2pService: DeviceAddress: 
09-13 11:58:36.498  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 11:58:36.498  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 11:58:36.498  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 11:58:36.499  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 11:58:36.499  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 11:58:36.499  1035  1391 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 11:58:36.500  1035  1391 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 11:58:36.500  1035  1391 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 11:58:36.500  1035  1391 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 11:58:36.500  7986  7986 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 11:58:36.501  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 11:58:36.501  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 11:58:36.502  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 11:58:36.502  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 11:58:36.502  1035  1390 D LGWifiP2pService: InactiveState
09-13 11:58:36.503  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.503  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.503  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 11:58:36.509  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-13 11:58:36.510  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:36.510  7986  7986 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 11:58:36.510  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.511  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.511  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 11:58:36.512  4287  4287 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 11:58:36.512  8005  8050 V FormManager: Network unavailable.
09-13 11:58:36.512  1940  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 11:58:36.512  1940  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:36.512  1940  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:36.513  1035  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 11:58:36.513  1035  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:36.513  1035  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:36.513  1035  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:36.513  1035  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:36.513  1035  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.513  1035  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.513  1035  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.513  1035  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:36.513  1035  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.513  1035  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.513  1035  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.514  8005  8050 V FormManager: Network unavailable.
09-13 11:58:36.515  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:36.516  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 11:58:36.516  1035  1390 D LGWifiP2pService: InactiveState{ when=-13ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.516  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.516  1035  1390 D LGWifiP2pService: DefaultState{ when=-13ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.516  1035  1390 D LGWifiP2pService: InactiveState{ when=-14ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.516  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.516  1035  1390 D LGWifiP2pService: DefaultState{ when=-14ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.516  1035  1391 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 11:58:36.517  1035  1391 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 11:58:36.517  1940  2296 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 11:58:36.517  1035  1391 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 11:58:36.517  1035  1390 D LGWifiP2pService: InactiveState{ when=-15ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.517  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 11:58:36.517  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.517  1035  1390 D LGWifiP2pService: DefaultState{ when=-15ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.517  1035  1390 D LGWifiP2pService: InactiveState{ when=-15ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.517  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.517  1035  1390 D LGWifiP2pService: DefaultState{ when=-15ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.518  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 11:58:36.518  1035  1035 E WifiServerServiceExt: No p2p device connected
09-13 11:58:36.518  7986  7986 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:36.518  4287  4287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 11:58:36.518  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 11:58:36.518  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:36.519  1035  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:36.519  1035  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 11:58:36.519  7986  7986 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 11:58:36.519  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.519  8005  8049 W FormManager: Network not available. Please check & try again.
09-13 11:58:36.519  1940  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:36.519  1035  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:36.519  1035  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.519  1035  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.519  1035  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.519  7986  7986 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.520  1940  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:36.520  1035  8044 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 11:58:36.520  1035  8044 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.520  1035  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.520  1035  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 11:58:36.522  1035  1391 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 11:58:36.522  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.522  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:36.523  1035  1391 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 11:58:36.523  1035  1391 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 11:58:36.523  1035  1391 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 11:58:36.523  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 11:58:36.524  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 11:58:36.524  7986  7986 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 11:58:36.524  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 11:58:36.524  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 11:58:36.524  1035  8044 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 11:58:36.524  1035  8044 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 11:58:36.524  4287  8051 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 11:58:36.525  4287  8052 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 11:58:36.526  4287  8052 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 11:58:36.528  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:58:36.528  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:36.528  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:36.528  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:36.528  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:36.528  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:58:36.528  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:58:36.528  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:58:36.528  1035  1391 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 11:58:36.528  1035  1391 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 11:58:36.529  1035  1391 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 11:58:36.529  1035  1391 D WifiNative-wlan0: doBoolean: SCAN
09-13 11:58:36.529  1035  1391 D WifiNative-wlan0: SCAN: returned false
09-13 11:58:36.529  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:58:36.529  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=209398  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 11:58:36.535  6708  6778 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 11:58:36.535  6708  6778 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 11:58:36.537  6708  6778 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f21c881 Bundle[{}]
09-13 11:58:36.538  6708  6778 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 11:58:36.538  6708  6778 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 11:58:36.539  6708  6778 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 11:58:36.540  6708  6778 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 11:58:36.540  6708  6778 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 11:58:36.541  6708  6778 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 11:58:36.546  6708  6778 I System.out: Running OutgoingSocketThread
09-13 11:58:36.549  6708  8053 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 867)
09-13 11:58:36.550  6708  8053 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 33421
09-13 11:58:36.550  6708  8053 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 11:58:36.559  1035  1895 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8054 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-13 11:58:36.564  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:36.564  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:36.564  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:36.564  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:36.564  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 11:58:36.565  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=209434  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 11:58:36.565  1035  1391 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:36.565  1035  1391 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:36.566  1035  1391 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:36.566  1035  1391 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:36.567  1035  1391 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 11:58:36.567  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:36.567  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:36.568  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 11:58:36.569  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:36.570  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-13 11:58:36.648  8054  8054 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 11:58:36.648  8054  8054 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-13 11:58:36.656  8054  8054 V [BNRBootReceiver]: Boot Receiver Return
,09-13 11:58:36.657  8054  8054 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-13 11:58:36.741  1035  1575 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8072 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 11:58:36.743  1035  1575 I ActivityManager: Killing 7140:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-13 11:58:36.799  1035  1985 W libprocessgroup: failed to open /acct/uid_10085/pid_7140/cgroup.procs: No such file or directory
,09-13 11:58:36.836  8072  8072 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 11:58:36.868  8072  8072 D PluginManager: init()
,09-13 11:58:37.004  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 11:58:37.004  1035  8044 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 11:58:37.004  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 11:58:37.004  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-13 11:58:37.004  1035  8044 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 11:58:37.004  7986  7986 E wpa_supplicant: USIM:  scard_init function
09-13 11:58:37.005  7986  7986 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-13 11:58:37.008  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 11:58:37.008  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 11:58:37.011  1035  1391 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 11:58:37.012  1035  1391 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 11:58:37.013  1035  1391 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 11:58:37.014  1035  1391 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 11:58:37.014  1035  1391 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 11:58:37.018  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=209887  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 11:58:37.020  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=209889  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 11:58:37.024  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:37.024  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:37.026  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.027  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.028  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.028  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 11:58:37.030  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:37.030  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 11:58:37.125  7986  7986 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 11:58:37.131  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 11:58:37.131  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 11:58:37.131  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 11:58:37.131  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 11:58:37.132  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 11:58:37.132  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 11:58:37.135  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=210004  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 11:58:37.136  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=210005  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 11:58:37.138  1035  1391 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210007
09-13 11:58:37.144  1035  1391 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210014
09-13 11:58:37.144  1035  1111 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 11:58:37.145  1035  1391 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210014
09-13 11:58:37.145  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210014
09-13 11:58:37.146  1035  1391 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=210015
09-13 11:58:37.146  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=210016  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-13 11:58:37.151  7986  7986 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 11:58:37.151  7986  7986 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 11:58:37.155  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 11:58:37.155  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 11:58:37.155  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,09-13 11:58:37.155  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 11:58:37.155  1035  8044 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 11:58:37.155  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 11:58:37.155  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 11:58:37.155  1035  8044 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 11:58:37.155  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 11:58:37.155  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 11:58:37.158  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.158  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.158  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 11:58:37.161  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:37.161  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:37.166  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.166  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.166  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 11:58:37.166  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.167  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=210036  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 11:58:37.168  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:37.168  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 11:58:37.168  1035  1391 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:37.168  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:37.168  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:37.169  1035  1391 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:37.169  1035  1391 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:37.169  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:37.170  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.170  1035  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 11:58:37.171  1035  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=210041  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 11:58:37.172  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVE,NT 60 0 rt=210041  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 11:58:37.173  1035  1391 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=210042
09-13 11:58:37.173  1035  1391 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=210043
09-13 11:58:37.174  1035  1391 D WifiNative-wlan0: doString: [STATUS]
09-13 11:58:37.174  1035  8044 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 11:58:37.174  1035  8044 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 11:58:37.174  1035  1391 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 11:58:37.177  1035  1391 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 11:58:37.183  1035  1391 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 11:58:37.183  1035  1391 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-13 11:58:37.190  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:37.190  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:37.191  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.191  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.192  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.192  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-13 11:58:37.195  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.195  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.195  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 11:58:37.198  1035  1391 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 11:58:37.198  1035  1444 D ConnectivityService: Got NetworkAgent Messenger
09-13 11:58:37.198  1035  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:58:37.198  1035  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 11:58:37.198  1035  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 11:58:37.198  1035  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 11:58:37.198  1035  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 11:58:37.198  1035  1444 D ConnectivityService: NetworkAgent connected
09-13 11:58:37.205  1035  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 11:58:37.205  1035  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:58:37.205  1035  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 11:58:37.206  1035  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 11:58:37.206  1035  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 11:58:37.209  1035  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-13 11:58:37.211  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:37.211  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:37.212   312   894 D CommandListener: Setting iface cfg
09-13 11:58:37.212  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.216  1035  1391 E WifiStateMachine: Start Dhcp Watchdog 3
09-13 11:58:37.217  1035  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=210086  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:37.217  1035  8093 D DhcpStateMachine: StoppedState
09-13 11:58:37.217  1035  8093 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:37.217  1035  8093 D DhcpStateMachine: WaitBeforeStartState
09-13 11:58:37.217  1035  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=210086  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:37.218  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=210087  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:37.218  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:37.219  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 11:58:37.220  1035  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=210089  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:37.220  1035  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=210089  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:37.221  1035  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=210090  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 11:58:37.221  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:37.221  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 11:58:37.222  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13816] from screen [on:0 period:586934694] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 11:58:37.223  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:586934695] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 11:58:37.223  1035  1391 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 11:58:37.228  1035  1444 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-13 11:58:37.229  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:37.229  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:37.229  1035  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:37.230  1035  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:37.230  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:37.231  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 11:58:37.232  1035  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 11:58:37.232  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
09-13 11:58:37.233  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
09-13 11:58:37.233  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 11:58:37.233  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.233  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 11:58:37.234  1035  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 11:58:37.234  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 11:58:37.234  1035  1391 D WifiNative-wlan0: SET ps 0: returned true
09-13 11:58:37.235  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 11:58:37.235  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 11:58:37.235  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 11:58:37.235  1035  1391 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 11:58:37.235  1035  1391 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 11:58:37.235  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1717c93e target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:37.235  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1717c93e target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:37.236  1035  1391 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 11:58:37.236  1035  8093 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:37.236  1035  8093 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 11:58:37.237   312   894 D CommandListener: Setting iface cfg
09-13 11:58:37.237   312   894 D CommandListener: Trying to bring up wlan0
09-13 11:58:37.239  1035  1391 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 11:58:37.240  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:37.240  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 11:58:37.241  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 11:58:37.241  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-13 11:58:37.242  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 11:58:37.242  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 11:58:37.242  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 11:58:37.242  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:37.242  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:37.243  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 11:58:37.243  1035  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,09-13 11:58:37.243  1035  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 11:58:37.243  7986  7986 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 11:58:37.244  1035  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 11:58:37.244  1035  1391 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 11:58:37.261  1035  1391 D WifiNative-wlan0: SET ps 1: returned true
09-13 11:58:37.262  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:37.263  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:37.263  1035  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:37.263  1035  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:37.264  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:37.264  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:37.265  1035  1391 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 11:58:37.265  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 11:58:37.265  1035  1391 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 11:58:37.266  1035  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-13 11:58:37.266  1035  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 11:58:37.266  1035  1444 D ConnectivityService: ignoring duplicate network state non-change
,09-13 11:58:37.270  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:37.271  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 11:58:37.272  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.274  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.274  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.274  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 11:58:37.281  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.281  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 11:58:37.281  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 11:58:37.286  1035  1391 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 11:58:37.287  1035  1444 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 11:58:37.288  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 11:58:37.288  1035  1444 D ConnectivityService: Adding iface wlan0 to network 102
09-13 11:58:37.290  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 11:58:37.293  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.293  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.293  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 11:58:37.293  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-13 11:58:37.300  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.300  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:58:37.300  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 11:58:37.308  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:37.308  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 11:58:37.309  1035  1444 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 11:58:37.309  1035  1444 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-13 11:58:37.310  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.311  1035  1444 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-13 11:58:37.311   312   894 E Netd    : netlink response contains error (File exists)
09-13 11:58:37.312  1035  1444 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-13 11:58:37.312  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:37.312  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 11:58:37.312  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.313  1035  1444 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 11:58:37.313  1035  1444 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-13 11:58:37.313  1035  1444 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-13 11:58:37.314  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 11:58:37.314  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 11:58:37.314  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.314  1035  1444 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 11:58:37.317  1035  1444 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 11:58:37.317  1035  1444 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 11:58:37.318  1035  8092 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 11:58:37.318  1035  8092 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 11:58:37.318  1035  8092 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 11:58:37.318  1035  8092 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 11:58:37.319  1035  1444 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 11:58:37.319  1035  1444 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:37.319  1035  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:37.319  1035  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,09-13 11:58:37.320  1035  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:37.320  1035  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 11:58:37.320  1035  1444 D ConnectivityService: currentScore = 0, newScore = 20
09-13 11:58:37.320  1035  1444 D ConnectivityService:    accepting network in place of null
09-13 11:58:37.320  1035  1444 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:37.320  1035  1391 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:37.321  1035  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:37.321   312  8097 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 11:58:37.323  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:37.323  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-13 11:58:37.324  1035  1444 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 11:58:37.325  1035  1444 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-13 11:58:37.325  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 11:58:37.325  1035  1444 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 11:58:37.325  1035  1444 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 11:58:37.325  1035  1444 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 11:58:37.326  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 11:58:37.327  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 11:58:37.327  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 11:58:37.327  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 11:58:37.328  1035  1444 D ConnectivityService: validation of new default Network = false
09-13 11:58:37.328  1035  1444 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 11:58:37.328  1035  1444 D DSQN    : enableDataServiceNotify 
09-13 11:58:37.329  1035  1444 D DSQN    : start dsqn bin
09-13 11:58:37.333  1035  1444 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 11:58:37.333  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:37.333  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 11:58:37.334  1035  1444 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:37.336  1602  2078 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 11:58:37.337  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 11:58:37.336  8102  8102 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:37.336  8102  8102 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:37.350  8102  8102 E DSQN    : DSQN ssw
,09-13 11:58:37.359  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 11:58:37.360  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.361  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.386  8072  8072 W ExternalStrings: load override strings
09-13 11:58:37.386  8072  8072 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 11:58:37.386  8072  8072 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-13 11:58:37.388  8072  8072 D StatusProvider: onCreate
,09-13 11:58:37.410   312  8097 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-13 11:58:37.438  1035  8093 D DhcpStateMachine: DHCPV4 request on wlan0
,09-13 11:58:37.439  1035  8093 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 11:58:37.439  1035  8093 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-13 11:58:37.441  8072  8072 V Signer  : override build config not found
,09-13 11:58:37.442  8072  8072 D Signer  : value of property debug is false
09-13 11:58:37.436  8107  8107 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 11:58:37.436  8107  8107 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 11:58:37.447   312  8097 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 11:58:37.467  8107  8107 I dhcpcd  : version 5.5.6 starting
09-13 11:58:37.471  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-13 11:58:37.471  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-13 11:58:37.471  8107  8107 E dhcpcd  : get_duid: m
09-13 11:58:37.471  8107  8107 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 11:58:37.471  8107  8107 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 11:58:37.471  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,09-13 11:58:37.477  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-13 11:58:37.477  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-13 11:58:37.477  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-13 11:58:37.478  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-13 11:58:37.478  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-13 11:58:37.478  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-13 11:58:37.478  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-13 11:58:37.479  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-13 11:58:37.479  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-13 11:58:37.479  8072  8072 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-13 11:58:37.483   312   893 D LGDataListener: argv[0]=dsqncommand
09-13 11:58:37.483   312   893 D LGDataListener: argv[1]=wlan0
09-13 11:58:37.483   312   893 D LGDataListener: argv[2]=1
09-13 11:58:37.483   312   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 11:58:37.484  1035  1109 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 11:58:37.484  1035  1109 D DSQN    : start to monitor internet connection
09-13 11:58:37.486  8072  8072 V LGMDMManager: Create singleton instance
,09-13 11:58:37.510  1035  8092 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 09:58:37 GMT], X-Android-Received-Millis=[1473760717510], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473760717482]}
09-13 11:58:37.510  1035  8092 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 11:58:37.510  1035  8092 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 11:58:37.510  1035  1444 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 11:58:37.510  1035  1444 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 11:58:37.511  1035  1444 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:37.511  1035  1444 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:37.511  1035  1444 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 11:58:37.511  1035  1444 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,09-13 11:58:37.511  1035  1444 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 11:58:37.511  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:37.511  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:37.511  1035  1444 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:37.512  1035  1444 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:37.512  1602  2078 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 11:58:37.512  1035  1444 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 11:58:37.512  1035  1391 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:37.512  1035  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 11:58:37.513  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:37.513  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 11:58:37.530  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-13 11:58:37.531  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.532  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 11:58:37.535  8072  8072 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-13 11:58:37.548  6708  6778 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 868)
09-13 11:58:37.548  6708  6778 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 868)
09-13 11:58:37.550  8107  8107 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 11:58:37.550  8107  8107 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 11:58:37.550  8107  8107 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 11:58:37.550  8107  8107 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 11:58:37.550  8107  8107 D dhcpcd  : wlan0: sending REQUEST (xid 0x8ff51601), next in 4.67 seconds
,09-13 11:58:37.554  6708  6778 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 873)
09-13 11:58:37.555  6708  6778 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 11:58:37.555  6708  6778 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 874)
09-13 11:58:37.559  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:37.559  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d908cf3 added. We now have 2 listener(s)
09-13 11:58:37.559  1035  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:37.562  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:37.562  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:37.562  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:37.562  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:37.562  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38703db0 added. We now have 9 listener(s)
09-13 11:58:37.562  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:37.562  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 11:58:37.564  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:37.567  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:37.567  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:37.567  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:37.567  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:37.567  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:37.567  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:37.567  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:37.567  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:37.568  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:37.569  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:37.569  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:37.569  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286143ae added. We now have 3 listener(s)
09-13 11:58:37.569  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:37.571  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:37.572  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:37.572  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:37.572  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:37.572  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:37.573  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9d054f added. We now have 10 listener(s)
09-13 11:58:37.573  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:37.573  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:37.573  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:37.573  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:37.573  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:37.573  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.573  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:37.573  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:37.573  6708,  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d908cf3 removed from the list
09-13 11:58:37.573  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.573  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38703db0 removed from the list
09-13 11:58:37.574  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:37.574  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:37.574  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.574  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.574  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.575  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:37.575  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:37.575  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.575  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38703db0 not in the list
09-13 11:58:37.575  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.575  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.576  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:37.576  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:37.576  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.576  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9d054f removed from the list
09-13 11:58:37.576  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:58:37.576  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.576  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.576  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:37.576  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286143ae removed from the list
09-13 11:58:37.577  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:58:37.577  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@169384dc added. We now have 2 listener(s)
09-13 11:58:37.577  1035  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 11:58:37.580  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-13 11:58:37.580  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:37.580  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:37.580  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:37.581  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d72c9e5 added. We now have 9 listener(s)
09-13 11:58:37.581  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:37.581  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:58:37.584  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:37.587  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:37.587  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:37.587  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:37.587  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-13 11:58:37.587  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:37.587  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:37.587  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:37.587  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:37.589  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:37.589  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:37.589  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:37.589  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@124ea76b added. We now have 3 listener(s)
09-13 11:58:37.590  1035  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:37.591  8107  8107 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 11:58:37.592  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:37.592  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:37.592  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:37.592  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:37.592  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a4212c8 added. We now have 10 listener(s)
09-13 11:58:37.592  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:37.592  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:58:37.592  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:58:37.592  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:58:37.592  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:37.592  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:37.592  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:58:37.597  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:37.598  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 11:58:37.598  1035  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:37.600  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 11:58:37.601  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:37.602  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 11:58:37.603  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:58:37.605  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:58:37.606  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:37.607  6708  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 11:58:37.607  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:37.607  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:37.609  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:37.609  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:37.609  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:37.609  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:37.609  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.609  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:37.609  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:37.609  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@169384dc removed from the list
09-13 11:58:37.609  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.609  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d72c9e5 removed from the list
09-13 11:58:37.610  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:37.610  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.612  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 11:58:37.612  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.612  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.613  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:37.613  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:37.613  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.613  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d72c9e5 not in the list
09-13 11:58:37.613  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.614  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.615  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:58:37.616  6708  6778 D BluetoothLeScanner: could not find callback wrapper
,09-13 11:58:37.616  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:37.616  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:37.616  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.616  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a4212c8 removed from the list
09-13 11:58:37.616  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:37.616  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.616  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.616  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:37.616  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@124ea76b removed from the list
09-13 11:58:37.617  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:37.617  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:37.617  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392e4f47 added. We now have 2 listener(s)
09-13 11:58:37.618  8107  8107 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 11:58:37.618  8107  8107 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 11:58:37.618  8107  8107 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 11:58:37.619  8107  8107 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 11:58:37.619  8107  8107 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 11:58:37.619  8107  8107 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 11:58:37.619  8107  8107 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 11:58:37.619  8107  8107 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 11:58:37.619  1035  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:37.622  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:37.622  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:37.622  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:37.622  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:37.622  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc99374 added. We now have 9 listener(s)
09-13 11:58:37.622  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:37.622  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:58:37.624  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:37.629  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
0,9-13 11:58:37.629  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:37.629  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:37.629  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:37.629  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:37.629  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:37.629  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:37.629  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:58:37.631  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:37.631  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:37.631  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:37.631  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca55912 added. We now have 3 listener(s)
09-13 11:58:37.633  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:37.635  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:37.672  1035  2002 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8127 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-13 11:58:37.672  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 11:58:37.674  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:37.674  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:37.674  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:37.674  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:37.674  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@397698e3 added. We now have 10 listener(s)
09-13 11:58:37.674  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:37.675  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:58:37.675  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:58:37.675  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:58:37.675  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:58:37.675  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:37.675  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:58:37.675  1035  2002 I ActivityManager: Killing 7165:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-13 11:58:37.764  8072  8118 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-13 11:58:37.849  1035  8093 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-13 11:58:37.852  1035  8093 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-13 11:58:37.852  1035  8093 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 11:58:37.852  1035  8093 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 11:58:37.852  1035  8093 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 11:58:37.852  1035  8093 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 11:58:37.852  1035  8093 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 11:58:37.852  1035  8093 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 11:58:37.853  1035  8093 D DhcpStateMachine: RunningState
09-13 11:58:37.902  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 11:58:37.919  1035  1649 W libprocessgroup: failed to open /acct/uid_10093/pid_7165/cgroup.procs: No such file or directory
,09-13 11:58:37.929  1035  1985 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:37.935  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:58:37.938  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 11:58:37.940  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 11:58:37.941  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:37.943  6708  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 11:58:37.943  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:37.943  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:37.943  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:37.944  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:37.944  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.944  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:37.944  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:37.944  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392e4f47 removed from the list
09-13 11:58:37.944  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.944  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc99374 removed from the list
09-13 11:58:37.944  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:37.944  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.945  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.945  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.945  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:37.946  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:37.946  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.946  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc99374 not in the list
09-13 11:58:37.946  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.946  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.947  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:37.947  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:37.948  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:37.948  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:37.948  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.948  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@397698e3 removed from the list
09-13 11:58:37.948  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:37.948  6708  6778 W org.thaliproject.p2p.btco,nnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.948  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.948  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:37.948  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca55912 removed from the list
09-13 11:58:37.949  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:37.949  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fbf45e added. We now have 2 listener(s)
09-13 11:58:37.950  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:37.954  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:37.954  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:37.954  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:37.955  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:37.955  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6fe03f added. We now have 9 listener(s)
09-13 11:58:37.955  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:37.955  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 11:58:37.958  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-13 11:58:37.959  8127  8127 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 11:58:37.964  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:37.964  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:37.964  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:37.964  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:37.964  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:37.964  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:37.964  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:37.964  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:37.966  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-13 11:58:37.966  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:37.966  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:37.966  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3082f655 added. We now have 3 listener(s)
09-13 11:58:37.967  1035  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 11:58:37.969  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:37.969  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:37.969  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:37.969  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:37.969  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:37.969  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@298ef86a added. We now have 10 listener(s)
09-13 11:58:37.969  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:37.970  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:58:37.970  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:58:37.970  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:58:37.970  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:37.970  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:58:37.972  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:37.973  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 11:58:37.973  1035  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:37.979  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 11:58:37.980  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:58:37.981  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:58:37.982  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:37.984  6708  6778 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 11:58:37.985  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:37.985  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:37.985  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:37.985  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:37.985  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.985  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:58:37.985  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:37.985  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fbf45e removed from the list
09-13 11:58:37.985  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.986  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6fe03f removed from the list
09-13 11:58:37.986  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:37.986  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.986  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.986  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.987  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:37.987  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:37.988  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:58:37.988  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6fe03f not in the list
09-13 11:58:37.988  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.988  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:37.989  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:37.989  6708  6778 D BluetoothLeScanner: could not find callback wrapper
09-13 11:58:37.989  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:58:37.990  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:37.990  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:37.990  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@298ef86a removed from the list
09-13 11:58:37.990  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:37.990  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:37.990  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:58:37.990  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:37.990  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3082f655 removed from the list
09-13 11:58:37.991  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:37.991  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1349a2d1 added. We now have 2 listener(s)
09-13 11:58:37.992  1035  1895 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 11:58:37.996  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 11:58:37.996  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:37.996  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:37.996  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:37.996  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249c3136 added. We now have 9 listener(s)
09-13 11:58:37.996  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:58:37.997  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:58:37.999  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:58:38.002  6708  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:58:38.002  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:58:38.002  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 11:58:38.002  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:58:38.002  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:58:38.002  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:38.002  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:58:38.002  6708  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:58:38.003  6708  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:58:38.003  6708  6778 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:58:38.003  8127  8127 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-13 11:58:38.003  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:58:38.003  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1db2c1a4 added. We now have 3 listener(s)
09-13 11:58:38.003  1035  2002 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 11:58:38.005  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:38.006  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-13 11:58:38.006  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:58:38.006  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:58:38.006  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:58:38.006  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f49b0d added. We now have 10 listener(s)
09-13 11:58:38.006  6708  6778 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:58:38.007  6708  6778 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:58:38.007  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:58:38.007  6708  6778 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:58:38.007  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:38.007  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:38.007  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:58:38.007  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:38.007  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1349a2d1 removed from the list
09-13 11:58:38.007  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:38.007  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249c3136 removed from the list
,09-13 11:58:38.007  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:58:38.007  6708  6778 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:58:38.007  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:38.008  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:38.008  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:38.009  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:38.009  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:38.009  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:38.009  6708  6778 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249c3136 not in the list
09-13 11:58:38.009  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:38.009  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:38.009  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:58:38.009  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:58:38.009  6708  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:58:38.009  6708  6778 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f49b0d removed from the list
09-13 11:58:38.009  6708  6778 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:58:38.009  6708  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:58:38.009  6708  6778 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:58:38.010  6708  6778 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:58:38.010  6708  6778 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1db2c1a4 removed from the list
09-13 11:58:38.010  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 11:58:38.010  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 11:58:38.011  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 11:58:38.011  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:58:38.011  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 11:58:38.011  6708  6778 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operatio,n: Should start/stop everything
09-13 11:58:38.021  6708  8167 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 881, name: My test thread name)
09-13 11:58:38.021  6708  8167 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 881, thread name: My test thread name)
09-13 11:58:38.022  6708  8167 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 881, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-13 11:58:38.026  6708  8168 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 883, name: My test thread name)
09-13 11:58:38.026  6708  8168 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 883, thread name: My test thread name)
09-13 11:58:38.026  6708  8168 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 883, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 11:58:38.029  6708  6778 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-13 11:58:38.029  6708  6778 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-13 11:58:38.029  6708  6778 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-13 11:58:38.029  6708  6778 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-13 11:58:38.030  6708  6778 D com.test.thalitest.ThaliTestRunner: Total duration: 23237 ms
,09-13 11:58:38.032  6708  6778 I jxcore-log: *Native tests were executed*
09-13 11:58:38.032  6708  6778 I jxcore-log: 
09-13 11:58:38.032  6708  6778 I jxcore-log: Total number of executed tests:  80
09-13 11:58:38.032  6708  6778 I jxcore-log: 
09-13 11:58:38.032  6708  6778 I jxcore-log: Number of passed tests:  80
09-13 11:58:38.032  6708  6778 I jxcore-log: 
09-13 11:58:38.033  6708  6778 I jxcore-log: Number of failed tests:  0
09-13 11:58:38.033  6708  6778 I jxcore-log: 
09-13 11:58:38.033  6708  6778 I jxcore-log: Number of ignored tests:  0
09-13 11:58:38.033  6708  6778 I jxcore-log: 
09-13 11:58:38.034  6708  6778 I jxcore-log: Total duration:  23237
09-13 11:58:38.034  6708  6778 I jxcore-log: 
,09-13 11:58:38.034  6708  6778 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 11:58:38.034  6708  6778 I jxcore-log: 
09-13 11:58:38.038  8127  8127 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-13 11:58:38.038  8127  8127 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 11:58:38.038  8127  8127 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 11:58:38.039  8127  8127 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 11:58:38.039  8127  8127 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 11:58:38.040  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.040  6708  6778 I jxcore-log: 
09-13 11:58:38.041  8127  8127 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 11:58:38.042  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.042  6708  6778 I jxcore-log: 
09-13 11:58:38.043  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.043  6708  6778 I jxcore-log: 
09-13 11:58:38.044  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.044  6708  6778 I jxcore-log: 
09-13 11:58:38.044  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.044  6708  6778 I jxcore-log: 
09-13 11:58:38.046  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.046  6708  6778 I jxcore-log: 
09-13 11:58:38.046  8127  8127 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-13 11:58:38.048  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:58:38.048  6708  6778 I jxcore-log: 
09-13 11:58:38.050  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:58:38.050  6708  6778 I jxcore-log: 
09-13 11:58:38.050  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.050  6708  6778 I jxcore-log: 
09-13 11:58:38.051  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.051  6708  6778 I jxcore-log: 
09-13 11:58:38.052  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:58:38.052  6708  6778 I jxcore-log: 
09-13 11:58:38.053  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:58:38.053  6708  6778 I jxcore-log: 
09-13 11:58:38.053  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:58:38.053  6708  6778 I jxcore-log: 
09-13 11:58:38.054  6708  6708 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 11:58:38.054  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.054  6708  6778 I jxcore-log: 
09-13 11:58:38.055  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.055  6708  6778 I jxcore-log: 
09-13 11:58:38.055  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.055  6708  6778 I jxcore-log: 
09-13 11:58:38.056  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.056  6708  6778 I jxcore-log: 
09-13 11:58:38.056  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.056  6708  6778 I jxcore-log: 
09-13 11:58:38.056  8072  8118 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:38.057  8072  8118 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 11:58:38.057  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.057  6708  6778 I jxcore-log: 
09-13 11:58:38.057  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.057  6708  6778 I jxcore-log: 
09-13 11:58:38.058  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:58:38.058  6708  6778 I jxcore-log: 
,09-13 11:58:38.059  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 11:58:38.059  6708  6778 I jxcore-log: 
09-13 11:58:38.059  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 11:58:38.059  6708  6778 I jxcore-log: 
09-13 11:58:38.059  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.059  6708  6778 I jxcore-log: 
09-13 11:58:38.060  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.060  6708  6778 I jxcore-log: 
09-13 11:58:38.060  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.060  6708  6778 I jxcore-log: 
09-13 11:58:38.061  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.061  6708  6778 I jxcore-log: 
09-13 11:58:38.061  6708  6778 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:58:38.061  6708  6778 I jxcore-log: 
09-13 11:58:38.062  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.066  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:38.074  8127  8127 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 11:58:38.075  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.076  8127  8127 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-13 11:58:38.077  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 11:58:38.078  8127  8127 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-13 11:58:38.081  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:38.085  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:38.090  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.090  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:38.091  8127  8127 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 11:58:38.092  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-13 11:58:38.094  6827  6827 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 11:58:38.096  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.096  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 11:58:38.100  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:38.104  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:38.108  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.109  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:38.110  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:38.111  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-13 11:58:38.111  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 11:58:38.111  6827  6827 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 11:58:38.111  6827  6827 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 11:58:38.112  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 11:58:38.112  6827  6827 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 11:58:38.112  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 11:58:38.112  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 11:58:38.112  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 11:58:38.112  6827  6827 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 11:58:38.112  6827  6827 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 11:58:38.112  6827  6827 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 11:58:38.115  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.116  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-13 11:58:38.128  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:38.132  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:38.139  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.140  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:38.140  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 11:58:38.143  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.143  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 11:58:38.148  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 11:58:38.152  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:38.157  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.157  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:38.158  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:38.160  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.161  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 11:58:38.162  8072  8118 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-13 11:58:38.169  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:38.176  8072  8118 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-13 11:58:38.177  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:38.183  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.183  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:38.184  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:38.188  8072  8118 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-13 11:58:38.189  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.189  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-13 11:58:38.190  8072  8118 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-13 11:58:38.190  8072  8118 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-13 11:58:38.191  8072  8118 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-13 11:58:38.191  8072  8118 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-13 11:58:38.196  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:38.201  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:38.206  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.207  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:38.207  8072  8118 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-13 11:58:38.207  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:38.209  8072  8118 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-13 11:58:38.216  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 11:58:38.216  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.229  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:38.235  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:38.241  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.241  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:38.248  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 11:58:38.253  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 11:58:38.254  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.260  8172  8172 D AndroidRuntime: 
09-13 11:58:38.260  8172  8172 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 11:58:38.262  8172  8172 D AndroidRuntime: CheckJNI is OFF
09-13 11:58:38.262  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 11:58:38.270  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 11:58:38.278  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.278  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:38.279  8127  8127 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 11:58:38.283  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.283  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 11:58:38.286  8026  8026 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-13 11:58:38.291  8026  8026 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:38.295  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:38.305  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:38.312  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 11:58:38.312  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 11:58:38.313  8127  8127 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 11:58:38.314  8127  8127 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 11:58:38.314  8127  8127 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 11:58:38.318  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.318  8072  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 11:58:38.322  8026  8026 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 11:58:38.322  8026  8026 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 11:58:38.326  6827  6827 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 11:58:38.332  6827  6827 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 11:58:38.340  8127  8127 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 11:58:38.340  8127  8127 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 11:58:38.341  8127  8127 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 11:58:38.341  8127  8127 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 11:58:38.341  8127  8127 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 11:58:38.346  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.386  8127  8127 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-13 11:58:38.387  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 11:58:38.388  8127  8127 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-13 11:58:38.419  8172  8172 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 11:58:38.429  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-13 11:58:38.429  1035  1092 I ActivityManager: Killing 6708:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-13 11:58:38.435  8127  8127 D LgDataFeature: LgDataFeature() Constructor: none
09-13 11:58:38.436  8127  8127 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:38.494  1035  1051 I WindowState: WIN DEATH: Window{29c256c4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 11:58:38.495  1035  1441 D WifiService: Client connection lost with reason: 4
,09-13 11:58:38.500  1035  1391 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-13 11:58:38.500  1035  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:38.501  1035  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:38.502  1035  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:38.502  1035  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:38.503  1035  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 11:58:38.504  1035  1444 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-13 11:58:38.504  1035  1444 D ConnectivityService: identical MTU - not setting
09-13 11:58:38.504  1035  1444 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 11:58:38.504  1035  1444 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 11:58:38.504  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 11:58:38.504  1035  1444 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:38.504  1035  1444 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 11:58:38.505  1602  2078 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-13 11:58:38.506  1035  1051 D InputDispatcher: Window went away: Window{29c256c4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 11:58:38.534  8127  8127 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 11:58:38.536  8127  8127 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 11:58:38.536  8127  8127 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-13 11:58:38.536  8127  8127 V SoundPool: doLoad: loading sample sampleID=1
09-13 11:58:38.537  8127  8194 V SoundPool: Start decode
09-13 11:58:38.537  8127  8194 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-13 11:58:38.537   317  1397 V MediaPlayerService: decode(23, 10857164, 17813)
09-13 11:58:38.537   317  1397 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-13 11:58:38.537   317  1397 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 11:58:38.537   317  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 11:58:38.537   317  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 11:58:38.537   317  1397 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-13 11:58:38.537   317  1397 V MediaPlayerService: player type = 3
09-13 11:58:38.537   317  1397 V AwesomePlayer: AwesomePlayer create()
09-13 11:58:38.538   317  1397 V AwesomePlayer: reset_l() 
09-13 11:58:38.538   317  1397 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:38.538   317  1397 V AwesomePlayer: setAudioSink() 
09-13 11:58:38.538  8127  8127 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 11:58:38.538   317  1397 V AwesomePlayer: reset_l() 
09-13 11:58:38.538   317  1397 V AudioCache: notify(0xb1432340, 8, 0, 0)
09-13 11:58:38.538   317  1397 V AudioCache: ignored
09-13 11:58:38.538   317  1397 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:38.538   317  1397 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 11:58:38.538   317  1397 V AwesomePlayer: setDataSource_l dataSource
09-13 11:58:38.538   317  1397 V LGParserOSAL: SniffLGParser start
09-13 11:58:38.538   317  1397 V LGParserOSAL: MainType:5, SubType=0
09-13 11:58:38.538   317  1397 V LGParserOSAL: #### check Mime : application/ogg
09-13 11:58:38.538   317  1397 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 11:58:38.538   317  1397 E MediaExtractor: Use LGExtractor :application/ogg 
09-13 11:58:38.583   317  1397 V LGParserOSAL: supported mime: application/ogg
09-13 11:58:38.583   317  1397 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 11:58:38.583   317  1397 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 11:58:38.583   317  1397 V AwesomePlayer: mBitrate = -1 bits/sec
09-13 11:58:38.583   317  1397 V AwesomePlayer: AudioTrack Setting
09-13 11:58:38.583   317  1397 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 11:58:38.583   317  1397 V AwesomePlayer: setAudioSource() 
09-13 11:58:38.583   317  1397 V MediaPlayerService: prepare
09-13 11:58:38.583   317  1397 V AwesomePlayer: prepareAsync_l() 
09-13 11:58:38.583   317  1397 V MediaPlayerService: wait for prepare
,09-13 11:58:38.583   317  8198 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 11:58:38.583   317  8198 V AwesomePlayer: initAudioDecoder() 
09-13 11:58:38.583   317  8198 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 11:58:38.583   317  8198 V AudioSystem: isOffloadSupported()
09-13 11:58:38.584   317  8198 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 11:58:38.584   317  8198 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 11:58:38.584   317  8198 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 11:58:38.584   317  8198 V AwesomePlayer: getUseOffload() = 0 
09-13 11:58:38.584   317  8198 V OMXCodec: OMXCodec::Create
09-13 11:58:38.584   317  8198 V OMXCodec: findMatchingCodecs()
09-13 11:58:38.584   317  8198 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 11:58:38.584   317  8198 V OMXCodec: matchingCodecs.size()=1
09-13 11:58:38.584   317  8198 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 11:58:38.588   317  8198 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 11:58:38.588   317  8198 V LGCodecAdapter: LG Codec Adapter start
,09-13 11:58:38.588   317  8198 V OMXCodec: OMXCodec Createtor
09-13 11:58:38.588   317  8198 V OMXCodec: setComponentRole
09-13 11:58:38.588   317  8198 V OMXCodec: configureCodec protected=0
09-13 11:58:38.588   317  8198 V LGCodecAdapter: called getLGCodecSpecificData
09-13 11:58:38.588   317  8198 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 11:58:38.588   317  8198 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 11:58:38.588   317  8198 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 11:58:38.588   317  8198 V LGCodecOSAL: Not support LGCodec
09-13 11:58:38.588   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 11:58:38.589   317  8198 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 11:58:38.589   317  8198 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 11:58:38.589   317  8198 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 11:58:38.589   317  8198 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 11:58:38.589   317  8198 V AudioSystem: isOffloadSupported()
09-13 11:58:38.589   317  8198 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 11:58:38.589   317  8198 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 11:58:38.589   317  8198 V OMXCodec: init()
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-13 11:58:38.589   317  8198 V OMXCodec: allocateBuffers
09-13 11:58:38.589   317  8198 V OMXCodec: allocateBuffersOnPort portIndex=0
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-13 11:58:38.589   317  8198 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-13 11:58:38.589   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-13 11:58:38.590   317  8198 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
09-13 11:58:38.590   317  8198 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 11:58:38.590   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 11:58:38.590   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 11:58:38.590   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 11:58:38.590   317  8198 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 11:58:38.590   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 11:58:38.590   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 11:58:38.590   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 11:58:38.590   317  8198 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 11:58:38.59,0   317  8198 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 11:58:38.590   317  8198 V AudioCache: notify(0xb1432340, 5, 0, 0)
09-13 11:58:38.590   317  8198 V AudioCache: ignored
09-13 11:58:38.590   317  8198 V AudioCache: notify(0xb1432340, 1, 0, 0)
09-13 11:58:38.590   317  8198 V AudioCache: prepared
09-13 11:58:38.590   317  1397 V AudioCache: wait - success
09-13 11:58:38.590   317  1397 V MediaPlayerService: start
09-13 11:58:38.590   317  1397 V AwesomePlayer: play_l() 
09-13 11:58:38.590   317  1397 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 11:58:38.590   317  1397 V AwesomePlayer: createAudioPlayer_l
09-13 11:58:38.590   317  1397 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 11:58:38.590   317  1397 V AwesomePlayer: startAudioPlayer_l() 
09-13 11:58:38.590   317  1397 D AudioPlayer: start of Playback, useOffload 0
09-13 11:58:38.590   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 11:58:38.590   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 11:58:38.592   317  8200 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-13 11:58:38.592   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57fc650 on output port
09-13 11:58:38.593   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 11:58:38.593   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 11:58:38.593   317  1397 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-13 11:58:38.594   317  1397 V AudioCache: notify(0xb1432340, 6, 0, 0)
09-13 11:58:38.594   317  1397 V AudioCache: ignored
09-13 11:58:38.594   317  1397 V MediaPlayerService: wait for playback complete
,09-13 11:58:38.596   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.596   317  8201 V AudioCache: memcpy(0xabf08000, 0xb1472000, 4096)
09-13 11:58:38.598   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.598   317  8201 V AudioCache: memcpy(0xabf09000, 0xb1472000, 4096)
09-13 11:58:38.600   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.600   317  8201 V AudioCache: memcpy(0xabf0a000, 0xb1472000, 4096)
09-13 11:58:38.600   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.600   317  8201 V AudioCache: memcpy(0xabf0b000, 0xb1472000, 4096)
09-13 11:58:38.601   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.601   317  8201 V AudioCache: memcpy(0xabf0c000, 0xb1472000, 4096)
,09-13 11:58:38.602   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.602   317  8201 V AudioCache: memcpy(0xabf0d000, 0xb1472000, 4096)
09-13 11:58:38.602   317  8201 V AudioCache: write(0xb1472000, 4096)
,09-13 11:58:38.602   317  8201 V AudioCache: memcpy(0xabf0e000, 0xb1472000, 4096)
09-13 11:58:38.602   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.602   317  8201 V AudioCache: memcpy(0xabf0f000, 0xb1472000, 4096)
09-13 11:58:38.603   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.603   317  8201 V AudioCache: memcpy(0xabf10000, 0xb1472000, 4096)
09-13 11:58:38.603   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.604   317  8201 V AudioCache: memcpy(0xabf11000, 0xb1472000, 4096)
09-13 11:58:38.604   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.604   317  8201 V AudioCache: memcpy(0xabf12000, 0xb1472000, 4096)
09-13 11:58:38.604   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.604   317  8201 V AudioCache: memcpy(0xabf13000, 0xb1472000, 4096)
09-13 11:58:38.605   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.605   317  8201 V AudioCache: memcpy(0xabf14000, 0xb1472000, 4096)
09-13 11:58:38.606   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.606   317  8201 V AudioCache: memcpy(0xabf15000, 0xb1472000, 4096)
09-13 11:58:38.606   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.606   317  8201 V AudioCache: memcpy(0xabf16000, 0xb1472000, 4096)
09-13 11:58:38.607   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.607   317  8201 V AudioCache: memcpy(0xabf17000, 0xb1472000, 4096)
09-13 11:58:38.608   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.608   317  8201 V AudioCache: memcpy(0xabf18000, 0xb1472000, 4096)
09-13 11:58:38.608   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.609   317  8201 V AudioCache: memcpy(0xabf19000, 0xb1472000, 4096)
09-13 11:58:38.609   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.609   317  8201 V AudioCache: memcpy(0xabf1a000, 0xb1472000, 4096)
09-13 11:58:38.609   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.609   317  8201 V AudioCache: memcpy(0xabf1b000, 0xb1472000, 4096)
09-13 11:58:38.610   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.610   317  8201 V AudioCache: memcpy(0xabf1c000, 0xb1472000, 4096)
09-13 11:58:38.611   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.611   317  8201 V AudioCache: memcpy(0xabf1d000, 0xb1472000, 4096)
09-13 11:58:38.612   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.612   317  8201 V AudioCache: memcpy(0xabf1e000, 0xb1472000, 4096)
09-13 11:58:38.613   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.613   317  8201 V AudioCache: memcpy(0xabf1f000, 0xb1472000, 4096)
,09-13 11:58:38.613   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.613   317  8201 V AudioCache: memcpy(0xabf20000, 0xb1472000, 4096)
09-13 11:58:38.614   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.614   317  8201 V AudioCache: memcpy(0xabf21000, 0xb1472000, 4096)
09-13 11:58:38.614   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.614   317  8201 V AudioCache: memcpy(0xabf22000, 0xb1472000, 4096)
09-13 11:58:38.615   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.615   317  8201 V AudioCache: memcpy(0xabf23000, 0xb1472000, 4096)
,09-13 11:58:38.615   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.615   317  8201 V AudioCache: memcpy(0xabf24000, 0xb1472000, 4096)
09-13 11:58:38.616   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.616   317  8201 V AudioCache: memcpy(0xabf25000, 0xb1472000, 4096)
09-13 11:58:38.616   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.616   317  8201 V AudioCache: memcpy(0xabf26000, 0xb1472000, 4096)
09-13 11:58:38.617   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.617   317  8201 V AudioCache: memcpy(0xabf27000, 0xb1472000, 4096)
09-13 11:58:38.617   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.617   317  8201 V AudioCache: memcpy(0xabf28000, 0xb1472000, 4096)
09-13 11:58:38.618   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.618   317  8201 V AudioCache: memcpy(0xabf29000, 0xb1472000, 4096)
09-13 11:58:38.618   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.618   317  8201 V AudioCache: memcpy(0xabf2a000, 0xb1472000, 4096)
09-13 11:58:38.619   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.619   317  8201 V AudioCache: memcpy(0xabf2b000, 0xb1472000, 4096)
09-13 11:58:38.619   317  8201 V AudioCache: write(0xb1472000, 4096)
,09-13 11:58:38.619   317  8201 V AudioCache: memcpy(0xabf2c000, 0xb1472000, 4096)
09-13 11:58:38.620   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.620   317  8201 V AudioCache: memcpy(0xabf2d000, 0xb1472000, 4096)
09-13 11:58:38.620   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.620   317  8201 V AudioCache: memcpy(0xabf2e000, 0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: memcpy(0xabf2f000, 0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: memcpy(0xabf30000, 0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: memcpy(0xabf31000, 0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: memcpy(0xabf32000, 0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.621   317  8201 V AudioCache: memcpy(0xabf33000, 0xb1472000, 4096)
09-13 11:58:38.623   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.623   317  8201 V AudioCache: memcpy(0xabf34000, 0xb1472000, 4096)
09-13 11:58:38.623   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.623   317  8201 V AudioCache: memcpy(0xabf35000, 0xb1472000, 4096)
09-13 11:58:38.623   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.623   317  8201 V AudioCache: memcpy(0xabf36000, 0xb1472000, 4096)
09-13 11:58:38.623   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.623   317  8201 V AudioCache: memcpy(0xabf37000, 0xb1472000, 4096)
09-13 11:58:38.624   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-13 11:58:38.624   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.624   317  8201 V AudioCache: memcpy(0xabf38000, 0xb1472000, 4096)
09-13 11:58:38.624   317  8201 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 11:58:38.624   317  8201 V AudioCache: write(0xb1472000, 4096)
09-13 11:58:38.624   317  8201 V AudioCache: memcpy(0xabf39000, 0xb1472000, 4096)
09-13 11:58:38.624   317  8201 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 11:58:38.625   317  8201 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 11:58:38.625   317  8201 V AwesomePlayer: postAudioEOS() 
09-13 11:58:38.625   317  8201 V AudioCache: write(0xb1472000, 280)
09-13 11:58:38.625   317  8201 V AudioCache: memcpy(0xabf3a000, 0xb1472000, 280)
,09-13 11:58:38.626   317  8198 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 11:58:38.626   317  8198 V AwesomePlayer: onStreamDone
,09-13 11:58:38.626   317  8198 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 11:58:38.626   317  8198 V AudioCache: notify(0xb1432340, 2, 0, 0)
09-13 11:58:38.626   317  8198 V AudioCache: playback complete
09-13 11:58:38.626   317  8198 V AwesomePlayer: pause_l() 
09-13 11:58:38.626   317  8198 V AudioCache: notify(0xb1432340, 7, 0, 0)
,09-13 11:58:38.626   317  8198 V AudioCache: ignored
09-13 11:58:38.626   317  8198 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:38.626   317  1397 V AudioCache: wait - success
09-13 11:58:38.626   317  1397 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 11:58:38.626   317  8198 D AudioPlayer: Pause Playback at 1068125,
09-13 11:58:38.626   317  1397 V AwesomePlayer: reset_l() 
09-13 11:58:38.627   317  1397 V AudioCache: notify(0xb1432340, 8, 0, 0)
09-13 11:58:38.627   317  1397 V AudioCache: ignored
09-13 11:58:38.627   317  1397 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:38.627   317  1397 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0,
09-13 11:58:38.627   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 11:58:38.627   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 11:58:38.627   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 11:58:38.627   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
,09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
,09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57fc650 on port 1
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
,09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 11:58:38.627   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 11:58:38.627   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
,09-13 11:58:38.627   317  8200 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 11:58:38.627   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 11:58:38.627   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 11:58:38.628   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-13 11:58:38.628   317  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-13 11:58:38.628   317  1397 D AudioPlayer: AudioPlayer releasing audio source
,09-13 11:58:38.628   317  1397 D AudioPlayer: AudioPlayer done releasing audio source
09-13 11:58:38.628   317  1397 V AwesomePlayer: reset_l() 
09-13 11:58:38.628   317  1397 V AwesomePlayer: cancelPlayerEvents
09-13 11:58:38.628   317  1397 V AwesomePlayer: ~AwesomePlayer call
09-13 11:58:38.629   317  1397 V AwesomePlayer: reset_l() 
09-13 11:58:38.629   317  1397 V AwesomePlayer: cancelPlayerEvents
,09-13 11:58:38.629  8127  8194 V SoundPool: close(31)
09-13 11:58:38.629  8127  8194 V SoundPool: pointer = 0xa0034000, size = 205080, sampleRate = 48000, numChannels = 2
09-13 11:58:38.642  1035  1092 I ActivityManager:   Force finishing activity ActivityRecord{38f4ccc9 u0 com.test.thalitest/.MainActivity t6}
,09-13 11:58:38.665   341   367 E GBMv2   : DFP En is all cleared set to be enabled
,09-13 11:58:38.666  1035  1922 W ActivityManager: Spurious death for ProcessRecord{22aa7de4 6708:com.test.thalitest/u0a118}, curProc for 6708: null
09-13 11:58:38.668  1035  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-13 11:58:38.672  1035  1124 I ActivityManager:   Force finishing activity ActivityRecord{38f4ccc9 u0 com.test.thalitest/.MainActivity t6 f}
09-13 11:58:38.673  1035  1124 W ActivityManager: Duplicate finish request for ActivityRecord{38f4ccc9 u0 com.test.thalitest/.MainActivity t6 f}
,09-13 11:58:38.701  7563  7563 D UEI.SmartControl: QS Service created
09-13 11:58:38.702  1940  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-13 11:58:38.702  1940  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3d2f3d2 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 11:58:38.703  1940  3372 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-13 11:58:38.703  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-13 11:58:38.704  1940  3372 D SplitWindowPolicy: topRunningActivity=ActivityInfo{d87fca3 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 11:58:38.705  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 11:58:38.706  8127  8127 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-13 11:58:38.708  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-13 11:58:38.709  2032  2072 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-13 11:58:38.711  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-13 11:58:38.712  8127  8127 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 11:58:38.712  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-13 11:58:38.723  2454  2633 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 11:58:38.725  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 11:58:38.726  7649  7649 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 11:58:38.726  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 11:58:38.728  3796  3796 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-13 11:58:38.728  8127  8127 V LGMDMManager: Create singleton instance
09-13 11:58:38.734  1035  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 11:58:38.767  7563  7563 I UEI.SmartControl: Service initServices...
09-13 11:58:38.767  7563  7563 D UEI.SmartControl: QS start get config
,09-13 11:58:38.777  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-13 11:58:38.778  1904  1904 D ActionManagerService: notifyUserLog: 1000003
09-13 11:58:38.779  3796  4458 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 11:58:38.779  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-13 11:58:38.779  1035  1917 V SIM_STK : Menu title from STK is T-Mobile
09-13 11:58:38.780  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-13 11:58:38.789  4464  4464 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 11:58:38.789  4464  4464 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 11:58:38.789  4464  4464 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 11:58:38.789  4464  4464 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 11:58:38.790  4464  4464 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 11:58:38.790  4464  4464 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 11:58:38.790  4464  4464 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 11:58:38.790  4464  4464 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 11:58:38.790  4464  4464 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:58:38.790  4464  4464 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 11:58:38.790  4464  4464 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 11:58:38.790  4464  4464 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-13 11:58:38.800  4575  4575 I art     : Explicit concurrent mark sweep GC freed 8209(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 477us total 83.672ms
09-13 11:58:38.809  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-13 11:58:38.810  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-13 11:58:38.811  1602  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 11:58:38.811  1602  1664 D KeyguardModel: createShortcutInfo...
09-13 11:58:38.812  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 11:58:38.813  1904  1904 D ActionManagerService: notifyUserLog: 1000004
09-13 11:58:38.813  3796  4458 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-13 11:58:38.814  3796  3814 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 11:58:38.818  1602  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 11:58:38.818  1602  1664 D KeyguardModel: createShortcutInfo...
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , display: false
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , animation: false }
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , display: false
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , animation: false }
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , expire_time: 0
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , display: false
09-13 11:58:38.844  2032  2032 I GBoardWebViewUtils: , animation: false }
,09-13 11:58:38.849  1602  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 11:58:38.850  1602  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 11:58:38.850  1602  1664 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 11:58:38.851  1602  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 11:58:38.851  1602  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 11:58:38.851  1602  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 11:58:38.856  2032  8207 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-13 11:58:38.856  1868  1868 D SplitUIManager: split_name #11 / not available #0
09-13 11:58:38.856  1868  1868 D SplitUIService: removed split : 
09-13 11:58:38.856  1602  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 11:58:38.856  1602  1664 D KeyguardModel: createShortcutInfo...
,09-13 11:58:38.862  1602  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 11:58:38.862  1602  1664 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 11:58:38.863  1602  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 11:58:38.863  1602  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 11:58:38.867  1602  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 11:58:38.867  1602  1664 D KeyguardModel: createShortcutInfo...
09-13 11:58:38.868  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 11:58:38.869  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-13 11:58:38.869  1035  1052 V SIM_STK : Menu title from STK is T-Mobile
09-13 11:58:38.869  1035  1052 V SIM_STK : Menu title from STK is T-Mobile
09-13 11:58:38.869  1035  1035 D administrator: Handling package changes for user 0
,09-13 11:58:38.878  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 11:58:38.881  1602  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 11:58:38.881  1602  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 11:58:38.881  1602  1664 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 11:58:38.881  1602  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 11:58:38.881  1602  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 11:58:38.882  1602  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 11:58:38.885  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 11:58:38.885  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-13 11:58:38.888  1868  1868 D SplitUIManager: split_name #11 / not available #0
09-13 11:58:38.888  1868  1868 I SplitUIService: split app #11
09-13 11:58:38.889  1602  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 11:58:38.889  1602  1664 D KeyguardModel: createShortcutInfo...
09-13 11:58:38.892  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 11:58:38.896  1602  1602 D KeyguardModel: handleShortcutListChanged...
09-13 11:58:38.896  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-13 11:58:38.909  1602  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 11:58:38.909  1602  1664 D KeyguardModel: createShortcutInfo...
09-13 11:58:38.911  1602  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 11:58:38.911  1602  1664 D KeyguardModel: createShortcutInfo...
09-13 11:58:38.912  1602  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 11:58:38.912  1602  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 11:58:38.913  8127  8127 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9670
09-13 11:58:38.917  1035  2002 V SIM_STK : Menu title from STK is T-Mobile
09-13 11:58:38.921  1602  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 11:58:38.921  1602  1664 D KeyguardModel: createShortcutInfo...
09-13 11:58:38.922  1602  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 11:58:38.922  1602  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 11:58:38.924  1602  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,09-13 11:58:38.924  1602  1664 D KeyguardModel: createShortcutInfo...
09-13 11:58:38.925  1602  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 11:58:38.925  1602  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 11:58:38.926  1602  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 11:58:38.926  1602  1664 D KeyguardModel: createShortcutInfo...
09-13 11:58:38.933  2032  2047 I art     : Background sticky concurrent mark sweep GC freed 2772(151KB) AllocSpace objects, 3(176KB) LOS objects, 0% free, 80MB/80MB, paused 9.859ms total 14.277ms
09-13 11:58:38.937  1035  1575 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 11:58:38.937  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 11:58:38.937  7649  7649 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 11:58:38.941  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
09-13 11:58:38.941  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 11:58:38.943  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.945  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.947  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.948  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.949  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-13 11:58:38.950  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.955  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 11:58:38.958  1602  1602 D KeyguardModel: handleShortcutListChanged...
09-13 11:58:38.958  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 11:58:38.984  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 11:58:38.987  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 11:58:39.001  8072  8072 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 11:58:39.004  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-13 11:58:39.014  2175  2175 I ConfigService: onCreate
09-13 11:58:39.014  2175  2175 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,09-13 11:58:39.018  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-13 11:58:39.020  2175  2175 I ConfigService: onBind returning update interface
09-13 11:58:39.021  2175  2175 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 11:58:39.021  2175  2175 I ConfigService: onBind returning config service
09-13 11:58:39.024  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-13 11:58:39.026  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 11:58:39.028  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 11:58:39.030  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 11:58:39.031  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 11:58:39.032  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 11:58:39.038   331   412 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-13 11:58:39.038  3200  8212 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-13 11:58:39.041  2175  2175 I ConfigService: onDestroy
,09-13 11:58:39.048  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{147a81ff u0 com.lge.launcher2/.Launcher t5} time:211929
09-13 11:58:39.049  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 11:58:39.049  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 11:58:39.050  2032  2106 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-13 11:58:39.050  2032  2106 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 11:58:39.064  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,09-13 11:58:39.065  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 11:58:39.065  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 11:58:39.067  1816  8213 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-13 11:58:39.072  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-13 11:58:39.073  2599  2599 D [Concierge]Service: onStartCommand(). Type : 8
09-13 11:58:39.073  2599  2599 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 11:58:39.076  2032  2032 D [Concierge]WidgetView: change position of spinner
09-13 11:58:39.077  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1473760719077
09-13 11:58:39.078  2599  2599 D [Concierge]Service: Update widget ID : 11
09-13 11:58:39.078  2599  2599 D [Concierge]Service: onStartCommand(). Type : 0
,09-13 11:58:39.080  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 11:58:39.081  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 11:58:39.081  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 11:58:39.082  1035  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-13 11:58:39.104  5873  8221 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-13 11:58:39.111  1816  8222 I PeopleContactsSync: CP2 sync disabled
09-13 11:58:39.120  1816  4722 I Icing   : doRemovePackageData com.test.thalitest
,09-13 11:58:39.125  7012  7012 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-13 11:58:39.143  1035  1124 I art     : Explicit concurrent mark sweep GC freed 84525(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 4.101ms total 324.488ms
,09-13 11:58:39.146  1816  8220 W GmsApplication: Using Auth Proxy for data requests.
09-13 11:58:39.150  1816  8220 W GmsApplication: Using Auth Proxy for data requests.
09-13 11:58:39.152  2364  8225 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 11:58:39.169  1035  1575 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8226 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 11:58:39.242  8172  8172 D AndroidRuntime: Shutting down VM
09-13 11:58:39.242  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 527808682
,09-13 11:58:39.244  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 11:58:39.244  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 11:58:39.248  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3081462a
09-13 11:58:39.248  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-13 11:58:39.249  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 11:58:39.249  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 11:58:39.256  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-13 11:58:39.256  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-13 11:58:39.268  1035  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8243 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-13 11:58:39.273  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473760534994, New one : 1473760719077
09-13 11:58:39.273  2032  2032 D [Concierge]WidgetView: Unregister all receivers
09-13 11:58:39.273  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 11:58:39.274  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-13 11:58:39.274  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 11:58:39.276  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 11:58:39.278  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-13 11:58:39.281  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-13 11:58:39.282  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-13 11:58:39.284  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-13 11:58:39.290  8226  8226 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 11:58:39.290  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 11:58:39.290  8226  8226 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 11:58:39.291  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 11:58:39.291  8226  8226 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 11:58:39.291  8226  8226 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 11:58:39.309  2175  2199 I art     : Explicit concurrent mark sweep GC freed 6979(403KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 2.115ms total 19.041ms
,09-13 11:58:39.322  7563  7563 I UEI.SmartControl: Supports setup maps: true
09-13 11:58:39.324  7563  7563 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 11:58:39.324  7563  7563 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 11:58:39.324  7563  7563 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 11:58:39.324  7563  7563 I UEI.SmartControl: ### init IR Blaster...
,09-13 11:58:39.327  7563  7563 D serial_port: Configuring serial port
09-13 11:58:39.328  7563  7563 E UEI.SmartControl: UEIBLaster setting for 616
09-13 11:58:39.328  7563  7563 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 11:58:39.328  7563  7563 I UEI.SmartControl: configuring settings for MAXQ616
09-13 11:58:39.328  7563  7563 I UEI.SmartControl: Get version...
09-13 11:58:39.336  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-13 11:58:39.344  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 11:58:39.344  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-13 11:58:39.345  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 11:58:39.349  7563  8260 D UEI.SmartControl: serial port data available: 21
,09-13 11:58:39.365  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@198bd927 time:212247
,09-13 11:58:39.375  7563  7563 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 11:58:39.375  7563  7563 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 11:58:39.375  7563  7563 I UEI.SmartControl: QS saving settings...
09-13 11:58:39.375  7563  7563 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 11:58:39.391  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 11:58:39.392  7563  8260 D UEI.SmartControl: serial port data available: 4
,09-13 11:58:39.397  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-13 11:58:39.400  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 11:58:39.404  8226  8226 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 11:58:39.412  8226  8226 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-13 11:58:39.418  7563  8266 I UEI.SmartControl: Device manager: loading config....
09-13 11:58:39.418  7563  8266 D UEI.SmartControl: ----------- loading internal config...
09-13 11:58:39.419  7563  7563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 11:58:39.420  7563  7563 E UEI.SmartControl: Services init done
09-13 11:58:39.420  7563  7563 D UEI.SmartControl: QS Service init finished
,09-13 11:58:39.420  7563  7563 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 11:58:39.420  7563  7563 D UEI.SmartControl: QS Service version code: 201091
09-13 11:58:39.420  7563  7563 D UEI.SmartControl: Service requested: Control
09-13 11:58:39.421  7563  8266 E UEI.SmartControl: Loading SETTINGS...
09-13 11:58:39.424  7563  8266 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 11:58:39.425  7563  7563 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 11:58:39.426  7563  7563 D UEI.SmartControl: Internal service binding...
09-13 11:58:39.427  8127  8127 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 11:58:39.427  7563  7578 I UEI.SmartControl: ------ IControl API: 11
09-13 11:58:39.427  7563  7578 D UEI.SmartControl: File observer start...
09-13 11:58:39.427  7563  7578 E UEI.SmartControl: IR Port is disabled: false
09-13 11:58:39.427  7563  7578 D UEI.SmartControl: Starting file observer...
09-13 11:58:39.429  7563  7578 I UEI.SmartControl: Registering callback...
09-13 11:58:39.430  7563  7579 I UEI.SmartControl: ------ IControl API: 19
09-13 11:58:39.430  7563  7579 I UEI.SmartControl: Registering Services Ready callback...
09-13 11:58:39.430  7563  7579 I UEI.SmartControl: Notify client services are ready...
09-13 11:58:39.431  8127  8145 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 11:58:39.431  8127  8192 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 11:58:39.431  8127  8192 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,09-13 11:58:39.433  8127  8127 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 11:58:39.433  8127  8127 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 11:58:39.433  7563  7578 I UEI.SmartControl: ------ IControl API: 8
09-13 11:58:39.434  8127  8127 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 11:58:39.434  8127  8127 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 11:58:39.434  8127  8127 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 11:58:39.434  8127  8127 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 11:58:39.435  8127  8127 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 11:58:39.435  8127  8127 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 11:58:39.436  8127  8127 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-13 11:58:39.436  8127  8127 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-13 11:58:39.436  8226  8226 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 11:58:39.437  1035  1922 I ActivityManager: Killing 7678:com.google.android.talk/u0a72 (adj 15): empty #17
09-13 11:58:39.438  7563  8265 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 11:58:39.438  8127  8146 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 11:58:39.438  7563  8265 D UEI.SmartControl: -----service ready thread exits
09-13 11:58:39.439  8127  8192 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 11:58:39.439  8127  8192 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 11:58:39.439  8127  8127 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
09-13 11:58:39.499  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-13 11:58:39.528  1035  1922 I ActivityManager: Killing 7213:com.google.android.gms.unstable/u0a5 (adj 15): empty #18
,09-13 11:58:39.534  2032  2903 I GBoardtInterface: onReloaded()
09-13 11:58:39.535  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-13 11:58:39.559  1035  2028 W libprocessgroup: failed to open /acct/uid_10072/pid_7678/cgroup.procs: No such file or directory
,09-13 11:58:39.561  1035  1917 W libprocessgroup: failed to open /acct/uid_10005/pid_7213/cgroup.procs: No such file or directory
09-13 11:58:39.562  3796  3814 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 11:58:39.564  3796  3815 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 11:58:39.569  1904  1904 D ActionManagerService: notifyUserLog: 1000001
09-13 11:58:39.570  3796  4458 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 11:58:39.570  3796  4458 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,09-13 11:58:39.573  1904  1904 D ActionManagerService: notifyUserLog: 1000001
09-13 11:58:39.574  3796  4458 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 11:58:39.574  3796  4458 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 11:58:39.574  3796  4458 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-13 11:58:39.575  3796  4458 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-13 11:58:39.575  3796  3814 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 11:58:39.577  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-13 11:58:39.577  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-13 11:58:39.579  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-13 11:58:39.579  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 11:58:39.581  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-13 11:58:39.581  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 11:58:39.585  8226  8226 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 11:58:39.585  8226  8226 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 11:58:39.637  8226  8226 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
