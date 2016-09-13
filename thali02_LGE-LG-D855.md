#### Test 836273370459b7a_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-13 16:35:00.084  1590  1590 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-13 16:35:00.085  1590  1590 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 16:35:00.085  1590  1590 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-13 16:35:00.085  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
09-13 16:35:00.100  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 16:35:00.100  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
09-13 16:35:00.102  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
09-13 16:35:00.107  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 16:35:00.386  6797  6797 D AndroidRuntime: 
09-13 16:35:00.386  6797  6797 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 16:35:00.389  6797  6797 D AndroidRuntime: CheckJNI is OFF
09-13 16:35:00.511  6797  6797 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 16:35:00.516  1046  1871 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 16:35:00.526  1927  4252 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 16:35:00.529  1046  1871 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 16:35:00.530  1046  1871 D ActivityManager: setTaskToReturnTo : TaskRecord{20cac243 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 16:35:00.530  1046  1871 D ActivityManager: setTaskToReturnTo : TaskRecord{20cac243 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 16:35:00.532  1046  1871 D WindowStateEx: AppWindowTokenEx init.. 
09-13 16:35:00.532   348   352 E GBMv2   : DFP En is all cleared set to be enabled
09-13 16:35:00.564  1046  1871 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6816 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 16:35:00.565  6797  6797 D AndroidRuntime: Shutting down VM
09-13 16:35:00.626  1927  4252 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 16:35:00.626  1927  4252 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f2b7451 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 16:35:00.627  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 16:35:00.627  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1a9764b6 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 16:35:00.691  6816  6816 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-13 16:35:00.788  6816  6816 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 16:35:00.797  6816  6816 I LibraryLoader: Loading: webviewchromium
09-13 16:35:00.800  6816  6816 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9902-9906)
,09-13 16:35:00.801  6816  6816 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:35:00.818  6816  6816 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {205e3327}
09-13 16:35:00.819  6816  6816 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:35:00.819  6816  6816 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 16:35:00.830  6816  6816 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 16:35:00.831  6816  6816 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 16:35:00.854  6816  6816 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 16:35:00.855  6816  6816 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-13 16:35:00.855  6816  6816 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,09-13 16:35:00.859   327  2120 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
09-13 16:35:00.872  6816  6816 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 16:35:00.872  6816  6816 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 16:35:00.872  6816  6816 I Adreno-EGL: Build Date: 12/12/14 금
09-13 16:35:00.872  6816  6816 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 16:35:00.872  6816  6816 I Adreno-EGL: Remote Branch: 
09-13 16:35:00.872  6816  6816 I Adreno-EGL: Local Patches: 
09-13 16:35:00.872  6816  6816 I Adreno-EGL: Reconstruct Branch: 
,09-13 16:35:00.884  1046  1122 D BluetoothManagerService: Message: 20
09-13 16:35:00.885  1046  1122 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39eed4b5:true
09-13 16:35:00.954  6816  6847 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
09-13 16:35:00.957  6816  6816 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,09-13 16:35:00.977  6816  6816 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:35:00.983  6816  6816 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 16:35:00.987  6816  6816 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 16:35:00.990  6816  6816 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 16:35:00.990  6816  6816 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-13 16:35:01.007  6816  6816 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 16:35:01.014  6816  6816 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 16:35:01.015  6816  6816 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:35:01.054  6816  6859 D OpenGLRenderer: Render dirty regions requested: true
09-13 16:35:01.054  6816  6859 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 16:35:01.066  6816  6859 D OpenGLRenderer: Enabling debug mode 0
,09-13 16:35:01.077  6816  6816 D Atlas   : Validating map...
09-13 16:35:01.081  1046  1873 D SplitWindow: check instance of lgWin Window{23f48087 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 16:35:01.119  6816  6857 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 16:35:01.119  6816  6857 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 16:35:01.182  6816  6816 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d98e022 time:170288
,09-13 16:35:01.205  1046  1123 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +579ms (total +671ms)
09-13 16:35:01.205  1046  1123 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5750c0 u0 com.test.thalitest/.MainActivity t6} time:170311
09-13 16:35:01.326  6816  6816 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 16:35:01.494  6816  6870 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,09-13 16:35:01.512  6816  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 16:35:01.512  6816  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 16:35:01.512  6816  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 16:35:01.512  6816  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 16:35:01.512  6816  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 16:35:01.512  6816  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24bc0b46 added. We now have 1 listener(s)
,09-13 16:35:01.519  1046  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 16:35:01.523  6816  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-13 16:35:01.524  6816  6870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 16:35:01.526  6816  6870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:35:01.527  6816  6870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 16:35:01.538  6816  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@396d885d added. We now have 1 listener(s)
09-13 16:35:01.539  6816  6870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:35:01.547  1046  1531 D WifiService: New client listening to asynchronous messages
09-13 16:35:01.555  6816  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:35:01.556  6816  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 16:35:01.558  6816  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 16:35:01.558  6816  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 16:35:01.558  6816  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 16:35:01.562  6816  6870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:01.563  1046  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:01.564  6816  6870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-13 16:35:01.575  6816  6870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 16:35:01.576  6816  6870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:01.576  6816  6870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:01.576  6816  6870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:01.576  6816  6870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:01.576  6816  6870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:01.576  6816  6870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:01.576  6816  6870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:01.576  6816  6870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:01.576  6816  6870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 16:35:01.576  6816  6870 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:35:01.579  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:01.580  6816  6870 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 16:35:01.586  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:01.632  6816  6857 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 16:35:01.632  6816  6857 I chromium: 
,09-13 16:35:01.686   348   354 E GBMv2   : DFP En is all cleared set to be enabled
09-13 16:35:01.686   348   354 E GBMv2   : Set value is all cleared set the max
09-13 16:35:01.686   348   354 I GBMv2   : DFP Enabled. Ignore VFP set
,09-13 16:35:01.691  6816  6816 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-13 16:35:01.778  6816  6816 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 16:35:01.778  6816  6816 I chromium: 
,09-13 16:35:02.407  6816  6873 W jxcore-log: Initializing JXcore engine
09-13 16:35:02.407  6816  6873 W jxcore-log: JXcore engine is ready
,09-13 16:35:02.439  6873  6873 W Thread-802: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7445]" dev="sockfs" ino=7445 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 16:35:02.439  6873  6873 W Thread-802: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-13 16:35:02.439  6873  6873 W Thread-802: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10401]" dev="sockfs" ino=10401 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 16:35:02.439  6873  6873 W Thread-802: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-13 16:35:02.439  6873  6873 W Thread-802: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33261]" dev="sockfs" ino=33261 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-13 16:35:02.458  6816  6873 W jxcore-log: Starting JXcore engine
09-13 16:35:02.533  6816  6873 W jxcore-log: Platform android
09-13 16:35:02.533  6816  6873 W jxcore-log: 
09-13 16:35:02.533  6816  6873 W jxcore-log: Process ARCH arm
09-13 16:35:02.533  6816  6873 W jxcore-log: 
,09-13 16:35:02.716  6816  6873 I jxcore-log: JXcore Cordova bridge is ready!
09-13 16:35:02.716  6816  6873 I jxcore-log: 
09-13 16:35:02.717  6816  6873 W jxcore-log: JXcore engine is started
,09-13 16:35:02.723  6816  6870 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 16:35:02.726  6816  6816 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 16:35:12.158  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 16:35:12.158  6816  6873 I jxcore-log: 
,09-13 16:35:12.161  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 16:35:12.161  6816  6873 I jxcore-log: 
09-13 16:35:12.164  6816  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:12.164  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:12.164  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:12.164  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:12.164  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:12.164  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:12.164  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:12.164  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:12.167  6816  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:12.169  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 16:35:12.169  6816  6873 I jxcore-log: 
09-13 16:35:12.171  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 16:35:12.171  6816  6873 I jxcore-log: 
,09-13 16:35:12.675  6816  6873 I jxcore-log: Unit Test app is loaded
09-13 16:35:12.675  6816  6873 I jxcore-log: 
,09-13 16:35:12.683  6816  6816 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 16:35:12.691  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:12.691  6816  6873 I jxcore-log: 
,09-13 16:35:12.702  6816  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:35:12.702  6816  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6606a72 added. We now have 2 listener(s)
09-13 16:35:12.703  1046  1613 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:12.705  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 16:35:12.705  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 16:35:12.705  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:35:12.705  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:35:12.705  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da83ec3 added. We now have 2 listener(s)
09-13 16:35:12.705  6816  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:35:12.706  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:35:12.709  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:12.711  6816  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:12.711  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:12.711  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:12.711  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:12.711  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:12.711  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:12.711  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:12.711  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:12.712  6816  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:12.712  6816  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:12.713  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:12.713  6816  6873 D ExecuteNativeTests: Running unit tests
09-13 16:35:12.715  6816  6873 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 16:35:12.716  1046  1872 D WifiServiceImplEx: setWifiEnabled: true pid=6816, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:35:12.716  1046  1872 D WifiService: setWifiEnabled: true pid=6816, uid=10118
09-13 16:35:12.716  1046  1872 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:35:12.717  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:12.720  6816  6873 I System.out: Running UT
09-13 16:35:22.867  6816  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:35:22.867  6816  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 added. We now have 3 listener(s)
,09-13 16:35:22.871  1046  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:22.873  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 16:35:22.873  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:35:22.873  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:35:22.873  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:35:22.873  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 added. We now have 3 listener(s)
09-13 16:35:22.873  6816  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:35:22.874  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:35:22.878  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:22.881  6816  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:22.881  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:22.881  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:22.881  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:22.881  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:22.881  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:22.881  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:22.881  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:35:22.885  6816  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:22.885  6816  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:22.887  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:22.888  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:22.895  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:35:22.899  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:22.899  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:22.899  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:22.902  6816  6873 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 16:35:22.903  6816  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:35:22.903  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:35:22.903  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:22.903  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:22.903  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:22.903  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.904  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.904  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:22.904  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:35:22.904  6816  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 removed from the list
09-13 16:35:22.904  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.904  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 removed from the list
09-13 16:35:22.904  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:22.904  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.906  6816  6873 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 16:35:22.907  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.907  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.907  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.907  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:22.907  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.907  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:22.907  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:22.907  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.907  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release,: 2 listener(s) left
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: P,eer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:35:22.913  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:35:22.914  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-13 16:35:22.921  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:35:22.921  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:35:22.921  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.921  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.921  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.921  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:22.921  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.922  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:22.922  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:22.922  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.922  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.923  6816  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:35:22.926  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:22.929  6816  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:22.929  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:22.929  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:22.929  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:22.929  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:22.929  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:22.929  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:22.929  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:35:22.932  6816  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:22.932  6816  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:22.933  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:22.935  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:22.935  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:22.936  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:22.936  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:22.936  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:22.936  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:22.940  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:35:22.941  1046  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 16:35:22.947  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:35:22.951  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:35:22.955  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 16:35:22.956  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:22.957  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:22.958  6816  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:22.958  6816  6873 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:35:22.959  6816  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 16:35:22.960  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:35:22.960  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 16:35:22.961  6816  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:35:22.961  6816  6873 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 16:35:22.961  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:22.961  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:22.961  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:22.961  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:22.961  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:22.965  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:35:22.968  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:22.970  6816  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:22.970  6816  6873 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:35:22.970  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.970  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.970  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:22.970  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:22.970  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.970  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:22.970  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:22.970  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.971  6816  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:35:22.973  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:22.976  6816  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:22.976  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:22.976  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:22.976  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:22.976  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:22.976  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:22.976  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:22.976  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:22.977  6816  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:22.977  6816  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:35:22.980  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:22.981  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:22.982  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:22.982  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:22.982  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:22.982  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:22.982  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:22.985  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:22.986  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:22.987  6816  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:22.987  6816  6873 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:35:22.987  6816  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 16:35:22.987  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:35:22.987  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 16:35:22.989  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.989  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.989  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:22.989  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:22.989  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.989  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:22.989  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:22.989  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:35:22.992  6816  6873 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 16:35:22.992  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.992  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.993  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.993  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:22.993  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.993  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:22.993  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:22.993  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.993  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.994  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:35:22.994  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.994  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.994  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.994  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:22.994  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.994  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:22.994  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:22.994  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.994  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.995  6816  6873 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 16:35:22.995  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.995  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.995  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.995  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:22.995  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.995  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:22.995  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:22.995  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMan,ager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.995  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.995  6816  6873 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 16:35:22.996  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.996  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.996  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.996  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:22.996  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.996  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:22.996  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:22.996  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.996  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.996  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:35:22.998  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:22.998  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:22.998  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:35:22.998  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:22.998  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:22.999  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:35:22.999  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:22.999  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:22.999  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:22.999  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.999  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.999  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:22.999  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:22.999  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:22.999  6816  6873 D io.jxcore.node.Conne,ctivityMonitor: stop
09-13 16:35:22.999  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:22.999  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:22.999  6816  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:23.000  6816  6873 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:35:23.000  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:35:23.002  6816  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:23.002  6816  6873 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:191,0:1910:1910:1910]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:35:23.002  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:35:23.003  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:35:23.003  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:35:23.003  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:35:23.003  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:35:23.003  6816  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 16:35:23.003  6816  6873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:35:23.003  6816  6873 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 16:35:23.003  6816  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:23.003  6816  6873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:35:23.003  6816  6873 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 16:35:23.003  6816  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:23.003  6816  6873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:35:23.003  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 16:35:23.006  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 16:35:23.007  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 16:35:23.007  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-13 16:35:23.017  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 16:35:23.017  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 16:35:23.017  6816  6873 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 16:35:23.018  6816  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:23.018  6816  6873 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 16:35:23.018  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.018  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.018  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.018  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 16:35:23.018  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.018  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.019  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.019  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.019  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.019  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.020  6816  6873 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 16:35:23.020  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.020  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.020  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.020  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.020  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.020  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.020  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.020  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.020  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.020  6816  6873 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 16:35:23.026  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.026  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.026  6816  6873 D o,rg.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.026  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.026  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.026  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.026  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.026  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.026  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.022  6816  6881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 900
09-13 16:35:23.031  6816  6873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 16:35:23.031  6816  6880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 900)
09-13 16:35:23.031  6816  6880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 900)
09-13 16:35:23.032  6816  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 16:35:23.032  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:35:23.032  6816  6873 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 16:35:23.032  6816  6873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:35:23.032  6816  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 16:35:23.032  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:35:23.032  6816  6873 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 16:35:23.032  6816  6873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:35:23.032  6816  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:35:23.032  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:35:23.032  6816  6873 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 16:35:23.032  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.032  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.032  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.032  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.032  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.032  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.032  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.032  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.032  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.033  6816  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:35:23.036  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:23.038  6816  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:23.038  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:23.038  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:23.038  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:23.038  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:23.038  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:23.038  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:23.038  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:23.041  6816  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:23.041  6816  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:23.042  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:23.043  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:23.043  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:23.043  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:23.043  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:23.043  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:23.043  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:23.046  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:23.047  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:23.048  6816  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:23.048  6816  6873 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:35:23.048  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.048  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.048  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:23.048  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.049  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.049  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.049  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.049  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.051  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.051  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.051  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.051  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.051  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.051  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.051  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.051  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.051  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.052  6816  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:35:23.052  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:35:23.055  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:35:23.056  6816  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:35:23.056  6816  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:35:23.056  6816  6816 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:35:23.056  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:35:23.056  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:35:23.057  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.057  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:35:23.057  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:35:23.057  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:35:23.057  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.057  6816  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:35:23.058  6816  6816 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:35:23.059  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.059  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.059  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:35:23.059  6816  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:35:23.059  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:35:23.059  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:35:23.061  6816  6873 D BluetoothLeScanner: could not find callback wrapper
09-13 16:35:23.061  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:35:23.061  6816  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:35:23.061  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.061  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.061  6816  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:35:23.062  6816  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:35:23.062  6816  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:35:23.062  6816  6816 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:35:23.062  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.062  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.062  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.062  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.063  6816  6873 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 16:35:23.064  6816  6888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:35:23.064  6816  6888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:35:23.065  6816  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:35:23.065  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:35:23.066  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:23.066  6816  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:23.067  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.067  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.067  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.067  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.067  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.067  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.067  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.067  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.067  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.068  6816  6816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:35:23.070  1046  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:23.070  1046  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:23.071  1046  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:23.071  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.071  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.071  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.071  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.071  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.071  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.071  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.071  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.071  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.072  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:23.072  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.072  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.072  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7030c70 not in the list
09-13 16:35:23.072  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:23.072  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38b69be9 not in the list
09-13 16:35:23.072  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:23.072  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:23.072  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:23.076  6816  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 16:35:23.077  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:35:23.077  6816  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 16:35:23.077  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:35:23.078  6816  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 16:35:23.078  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:35:23.080  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:35:23.080  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 16:35:23.081  6816  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 16:35:23.081  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:35:23.081  6816  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 16:35:23.081  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:35:23.081  6816  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 16:35:23.081  6816  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 16:35:23.082  6816  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 16:35:23.082  6816  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 16:35:23.083  6816  6873 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 16:35:23.083  6816  6873 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 16:35:23.083  6816  6873 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 16:35:23.083  6816  6873 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 16:35:23.088  6816  6900 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 16:35:23.089  6816  6900 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 16:35:23.097  6816  6902 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 16:35:23.097  6816  6902 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:35:23.097  6816  6902 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:23.098  6816  6902 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:23.098  6816  6902 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:35:23.098  6816  6900 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 16:35:23.098  6816  6900 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:35:23.099  6816  6900 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:23.099  6816  6906 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 953, name: IncomingSocketThread/Receiver)
09-13 16:35:23.100  6816  6900 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:35:23.101  6816  6905 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 952, name: IncomingSocketThread/Sender)
09-13 16:35:23.102  6816  6900 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 16:35:23.102  6816  6907 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 954, name: OutgoingSocketThread/Sender)
09-13 16:35:23.103  6816  6908 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 955, name: OutgoingSocketThread/Receiver)
09-13 16:35:23.103  6816  6908 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 955, thread name: OutgoingSocketThread/Receiver)
09-13 16:35:23.104  6816  6908 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:35:23.104  6816  6908 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 955, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:35:23.101  6816  6906 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 953, thread name: IncomingSocketThread/Receiver)
09-13 16:35:23.104  6816  6906 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:35:23.104  6816  6906 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 953, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:35:23.563  6816  6816 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:35:23.613  6816  6873 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 16:35:23.618  6816  6873 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 16:35:23.620  6816  6873 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@186723b1 Bundle[{}]
09-13 16:35:23.621  6816  6873 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 16:35:23.621  6816  6873 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 16:35:23.622  6816  6873 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 16:35:23.622  6816  6873 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 16:35:23.623  6816  6873 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 16:35:23.624  6816  6873 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 16:35:23.635  6816  6921 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 16:35:23.635  6816  6921 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:35:24.149  6816  6921 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 16:35:24.149  6816  6921 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:35:24.149  6816  6921 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:24.150  6816  6921 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:24.150  6816  6921 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:35:24.153  6816  6923 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 16:35:24.153  6816  6923 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:35:24.153  6816  6923 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:24.154  6816  6923 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:24.154  6816  6923 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:35:24.156  6816  6926 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 967, name: OutgoingSocketThread/Receiver)
09-13 16:35:24.156  6816  6926 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 967, thread name: OutgoingSocketThread/Receiver)
09-13 16:35:24.157  6816  6926 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:35:24.157  6816  6926 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 967, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:35:24.158  6816  6925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 966, name: OutgoingSocketThread/Sender)
09-13 16:35:24.160  6816  6927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 968, name: IncomingSocketThread/Sender)
09-13 16:35:24.162  6816  6928 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 969, name: IncomingSocketThread/Receiver)
09-13 16:35:24.162  6816  6928 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 969, thread name: IncomingSocketThread/Receiver)
09-13 16:35:24.162  6816  6928 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:35:24.162  6816  6928 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 969, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:35:24.666  6816  6873 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 978)
09-13 16:35:24.667  6816  6873 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 16:35:24.667  6816  6873 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 979)
,09-13 16:35:24.673  6816  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:35:24.674  6816  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c4f7507 added. We now have 3 listener(s)
09-13 16:35:24.674  1046  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:24.677  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 16:35:24.677  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:35:24.677  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:35:24.677  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:35:24.678  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de72634 added. We now have 3 listener(s)
09-13 16:35:24.678  6816  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:35:24.678  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:35:24.682  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:35:24.689  6816  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:24.689  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:24.689  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:24.689  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:24.689  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:24.689  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:24.689  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:24.689  6816  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:24.691  6816  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:24.691  6816  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:24.693  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:24.695  6816  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:35:24.701  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:24.701  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:24.701  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:24.701  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:35:24.701  6816  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c4f7507 removed from the list
09-13 16:35:24.701  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:24.701  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de72634 removed from the list
09-13 16:35:24.701  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:24.701  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:24.703  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:24.703  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:24.703  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:24.703  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:24.703  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:24.708  6816  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:35:24.711  1046  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:24.716  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:35:24.716  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:35:24.718  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:24.719  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:24.720  6816  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 16:35:27.723  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:35:27.723  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 16:35:27.735  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:27.735  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:27.735  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:27.735  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c4f7507 not in the list
09-13 16:35:27.735  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:27.735  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de72634 not in the list
09-13 16:35:27.735  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:27.736  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:27.736  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:27.737  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:35:27.740  6816  6873 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 16:35:27.740  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-13 16:35:27.745  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:35:27.745  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:35:27.745  6816  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:35:27.745  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:27.746  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:35:27.747  6816  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:35:27.747  6816  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:35:27.748  6816  6816 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:35:27.749  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:35:27.749  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:35:27.749  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:27.750  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:27.755  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:35:27.759  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:27.762  6816  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:27.763  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:27.763  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:35:27.763  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:35:27.763  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:35:27.763  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:27.763  6816  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:35:27.763  6816  6816 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:35:27.764  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c4f7507 not in the list
09-13 16:35:27.764  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:27.764  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de72634 not in the list
09-13 16:35:27.764  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:27.764  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:27.764  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:27.765  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:27.765  6816  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:27.765  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:27.765  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:27.765  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:27.767  6816  6930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:35:27.767  6816  6930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:35:27.767  6816  6816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:35:27.774  6816  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:35:27.778  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:27.779  6816  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:30.781  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:30.781  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:30.782  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:30.782  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c4f7507 not in the list
09-13 16:35:30.782  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:30.782  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de72634 not in the list
09-13 16:35:30.782  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:30.782  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:30.782  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:35:30.796  6816  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:30.796  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:30.796  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:30.796  6816  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c4f7507 not in the list
09-13 16:35:30.796  6816  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:30.796  6816  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de72634 not in the list
09-13 16:35:30.796  6816  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:30.796  6816  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:30.796  6816  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:30.797  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 16:35:30.797  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:35:30.797  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 16:35:30.798  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:30.798  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:35:30.798  6816  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 16:35:30.810  6816  6931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 998, name: My test thread name)
,09-13 16:35:32.810  6816  6873 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 998
09-13 16:35:32.810  6816  6873 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 998, name: My test thread name)
,09-13 16:35:32.825  6816  6932 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 999, name: My test thread name)
09-13 16:35:32.826  6816  6932 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 999, thread name: My test thread name)
09-13 16:35:32.826  6816  6932 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 999, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 16:35:32.828  6816  6873 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:35:32.833  6816  6933 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1003, name: My test thread name)
09-13 16:35:32.834  6816  6933 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1003, thread name: My test thread name): Test exception.
09-13 16:35:32.834  6816  6933 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1003, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-13 16:35:32.837  6816  6873 I jxcore-log: Total number of executed tests:  76
09-13 16:35:32.837  6816  6873 I jxcore-log: 
09-13 16:35:32.838  6816  6873 I jxcore-log: Number of passed tests:  76
09-13 16:35:32.838  6816  6873 I jxcore-log: 
09-13 16:35:32.838  6816  6873 I jxcore-log: Number of failed tests:  0
09-13 16:35:32.838  6816  6873 I jxcore-log: 
09-13 16:35:32.839  6816  6873 I jxcore-log: Number of ignored tests:  0
09-13 16:35:32.839  6816  6873 I jxcore-log: 
09-13 16:35:32.839  6816  6873 I jxcore-log: Total duration:  9972
09-13 16:35:32.839  6816  6873 I jxcore-log: 
09-13 16:35:32.841  6816  6873 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 16:35:32.841  6816  6873 I jxcore-log: 
09-13 16:35:32.842  6816  6873 I jxcore-log: My device name is: LGE-LG-D855
09-13 16:35:32.842  6816  6873 I jxcore-log: 
09-13 16:35:32.852  6816  6931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 998, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-13 16:35:32.860  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:32.860  6816  6873 I jxcore-log: 
09-13 16:35:32.862  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:32.862  6816  6873 I jxcore-log: 
09-13 16:35:32.863  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:32.863  6816  6873 I jxcore-log: 
09-13 16:35:32.868  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:32.868  6816  6873 I jxcore-log: 
09-13 16:35:32.869  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:32.869  6816  6873 I jxcore-log: 
,09-13 16:35:32.875  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:35:32.875  6816  6873 I jxcore-log: 
09-13 16:35:32.877  6816  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:32.877  6816  6873 I jxcore-log: 
09-13 16:35:33.220  6934  6934 D AndroidRuntime: 
09-13 16:35:33.220  6934  6934 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 16:35:33.224  6934  6934 D AndroidRuntime: CheckJNI is OFF
09-13 16:35:33.372  6934  6934 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-13 16:35:33.381  1046  1112 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-13 16:35:33.382  1046  1112 I ActivityManager: Killing 6816:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-13 16:35:33.414  1046  1063 I WindowState: WIN DEATH: Window{23f48087 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 16:35:33.415  1046  1531 D WifiService: Client connection lost with reason: 4
,09-13 16:35:33.421  1046  1063 D InputDispatcher: Window went away: Window{23f48087 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 16:35:33.497  1046  1112 I ActivityManager:   Force finishing activity ActivityRecord{5750c0 u0 com.test.thalitest/.MainActivity t6}
,09-13 16:35:33.529   348   352 E GBMv2   : DFP En is all cleared set to be enabled
09-13 16:35:33.529  1046  1871 W ActivityManager: Spurious death for ProcessRecord{17940a44 6816:com.test.thalitest/u0a118}, curProc for 6816: null
09-13 16:35:33.530  1046  1128 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-13 16:35:33.532  1046  1128 I ActivityManager:   Force finishing activity ActivityRecord{5750c0 u0 com.test.thalitest/.MainActivity t6 f}
09-13 16:35:33.533  1046  1128 W ActivityManager: Duplicate finish request for ActivityRecord{5750c0 u0 com.test.thalitest/.MainActivity t6 f}
,09-13 16:35:33.595  4885  4885 I art     : Explicit concurrent mark sweep GC freed 475(32KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 551us total 40.290ms
,09-13 16:35:33.599  2020  2020 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-13 16:35:33.600  2020  2020 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 16:35:33.603  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-13 16:35:33.603  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{de985b7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 16:35:33.604  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-13 16:35:33.604  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-13 16:35:33.605  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35b5e124 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 16:35:33.605  2020  2112 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-13 16:35:33.612  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-13 16:35:33.623  1046  1421 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 16:35:33.629  4147  4147 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 16:35:33.629  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-13 16:35:33.633  1982  1982 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 16:35:33.633  2491  2667 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 16:35:33.664  3776  3776 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-13 16:35:33.683  4773  4773 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 16:35:33.683  4773  4773 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 16:35:33.683  4773  4773 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 16:35:33.683  4773  4773 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 16:35:33.683  4773  4773 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 16:35:33.684  4773  4773 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 16:35:33.684  4773  4773 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 16:35:33.684  4773  4773 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 16:35:33.684  4773  4773 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,09-13 16:35:33.689  4773  4773 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 16:35:33.689  4773  4773 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 16:35:33.690  4773  4773 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 16:35:33.691  1046  1110 W InputMethodInfo: Duplicated subtype definition found: , voice
09-13 16:35:33.693  1892  1892 D ActionManagerService: notifyUserLog: 1000003
09-13 16:35:33.694  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-13 16:35:33.697  3776  4798 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 16:35:33.697  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-13 16:35:33.699  2020  2020 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-13 16:35:33.700  2020  2020 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-13 16:35:33.701  2020  2020 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-13 16:35:33.708  1892  1892 D ActionManagerService: notifyUserLog: 1000004
09-13 16:35:33.708  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 16:35:33.709  3776  4798 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-13 16:35:33.710  3776  4797 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 16:35:33.713  1590  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 16:35:33.713  1590  1646 D KeyguardModel: createShortcutInfo...
,09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , expire_time: 0
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , display: false
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , animation: false }
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , expire_time: 0
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , display: false
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , animation: false }
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , expire_time: 0
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , display: false
09-13 16:35:33.715  2020  2020 I GBoardWebViewUtils: , animation: false }
09-13 16:35:33.720  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 16:35:33.720  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-13 16:35:33.721  1590  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 16:35:33.721  1590  1646 D KeyguardModel: createShortcutInfo...
09-13 16:35:33.724  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-13 16:35:33.725  1854  1854 D SplitUIService: removed split : 
,09-13 16:35:33.732  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 16:35:33.732  1590  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:35:33.732  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 16:35:33.733  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 16:35:33.736  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:33.737  1590  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 16:35:33.737  6362  6362 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 16:35:33.738  2020  6965 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,09-13 16:35:33.756  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-13 16:35:33.758  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 16:35:33.761  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-13 16:35:33.775  1590  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 16:35:33.775  1590  1646 D KeyguardModel: createShortcutInfo...
,09-13 16:35:33.781  2177  2177 I ConfigService: onCreate
09-13 16:35:33.781  2177  2177 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-13 16:35:33.782  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 16:35:33.782  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 16:35:33.784  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-13 16:35:33.788  1046  1945 V SIM_STK : Menu title from STK is T-Mobile
,09-13 16:35:33.791  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:33.791  1590  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 16:35:33.793  1590  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 16:35:33.793  1590  1646 D KeyguardModel: createShortcutInfo...
09-13 16:35:33.796  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-13 16:35:33.796  1854  1854 I SplitUIService: split app #11
09-13 16:35:33.804  1046  1046 I art     : Explicit concurrent mark sweep GC freed 30300(1926KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.112ms total 220.468ms
09-13 16:35:33.804  1046  1128 I art     : WaitForGcToComplete blocked for 198.371ms for cause Explicit
,09-13 16:35:33.809  2177  2177 I ConfigService: onBind returning update interface
09-13 16:35:33.817  2177  2177 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 16:35:33.817  2177  2177 I ConfigService: onBind returning config service
09-13 16:35:33.817  1590  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:35:33.817  1590  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 16:35:33.817  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 16:35:33.817  1590  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 16:35:33.818  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:33.818  1590  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-13 16:35:33.821  2177  2177 I ConfigService: onDestroy
09-13 16:35:33.822  1590  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 16:35:33.822  1590  1646 D KeyguardModel: createShortcutInfo...
09-13 16:35:33.828  1046  1062 V SIM_STK : Menu title from STK is T-Mobile
09-13 16:35:33.828  1046  1062 V SIM_STK : Menu title from STK is T-Mobile
09-13 16:35:33.828  1590  1590 D KeyguardModel: handleShortcutListChanged...
09-13 16:35:33.828  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 16:35:33.835  1802  6971 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-13 16:35:33.836  1590  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 16:35:33.837  1590  1646 D KeyguardModel: createShortcutInfo...
09-13 16:35:33.838  1590  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 16:35:33.838  1590  1646 D KeyguardModel: createShortcutInfo...
09-13 16:35:33.839  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:33.839  1590  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 16:35:33.840  1590  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 16:35:33.840  1590  1646 D KeyguardModel: createShortcutInfo...
09-13 16:35:33.841  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:33.842  1590  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 16:35:33.843  1590  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 16:35:33.843  1590  1646 D KeyguardModel: createShortcutInfo...
09-13 16:35:33.846  1590  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:33.846  1590  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 16:35:33.848  1590  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 16:35:33.848  1590  1646 D KeyguardModel: createShortcutInfo...
,09-13 16:35:33.864  1046  1046 D administrator: Handling package changes for user 0
09-13 16:35:33.870   342   434 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-13 16:35:33.871  3245  6977 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,09-13 16:35:33.878  1046  1873 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 16:35:33.879  1590  1590 D KeyguardModel: handleShortcutListChanged...
09-13 16:35:33.879  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 16:35:33.879  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 16:35:33.879  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 16:35:33.879  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 16:35:33.879  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 16:35:33.880  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 16:35:33.880  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 16:35:33.880  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 16:35:33.880  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 16:35:33.880  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 16:35:33.880  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 16:35:33.880  4147  4147 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 16:35:33.880  6139  6976 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-13 16:35:33.892  1802  6979 I PeopleContactsSync: CP2 sync disabled
,09-13 16:35:33.897  1802  6978 W GmsApplication: Using Auth Proxy for data requests.
09-13 16:35:33.903  1802  6978 W GmsApplication: Using Auth Proxy for data requests.
09-13 16:35:33.904  1802  5075 I Icing   : doRemovePackageData com.test.thalitest
09-13 16:35:33.906  1046  2019 V SIM_STK : Menu title from STK is T-Mobile
,09-13 16:35:33.950  6457  6457 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-13 16:35:33.971  2332  6982 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-13 16:35:33.974  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-13 16:35:33.977  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:35:33.978  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 16:35:33.980  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 16:35:33.981  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 16:35:33.982  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 16:35:33.996  6508  6508 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-13 16:35:34.000  2020  2020 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-13 16:35:34.002  1046  1046 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 16:35:34.002  1046  1046 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 16:35:34.002  1046  1046 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 16:35:34.003  1046  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-13 16:35:34.007  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 16:35:34.007  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:35:34.008  1046  1123 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2854eb5 u0 com.lge.launcher2/.Launcher t5} time:203113
,09-13 16:35:34.014  2020  2150 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,09-13 16:35:34.014  2020  2150 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 16:35:34.016  1046  1128 I art     : Explicit concurrent mark sweep GC freed 6472(397KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 4.014ms total 208.577ms
09-13 16:35:34.028  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,09-13 16:35:34.030  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 16:35:34.031  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:35:34.038  2020  2020 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-13 16:35:34.039  2561  2561 D [Concierge]Service: onStartCommand(). Type : 8
09-13 16:35:34.039  2561  2561 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 16:35:34.041  2020  2020 D [Concierge]WidgetView: change position of spinner
,09-13 16:35:34.043  2561  2561 D [Concierge]Service: Update widget ID : 11
09-13 16:35:34.044  2561  2561 D [Concierge]Service: onStartCommand(). Type : 0
09-13 16:35:34.044  2020  2020 I [Concierge]WidgetView: initWebView(). Time : 1473777334044
09-13 16:35:34.056  1982  1982 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 16:35:34.056  1982  1982 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-13 16:35:34.059  1982  1982 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-13 16:35:34.061  2020  2020 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1057986842
,09-13 16:35:34.062  2020  2020 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 16:35:34.062  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 16:35:34.063  6362  6362 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 16:35:34.065  2020  2020 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1cbe7f8e
09-13 16:35:34.065  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-13 16:35:34.066  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 16:35:34.066  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:35:34.070  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-13 16:35:34.071  2020  2020 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-13 16:35:34.071  2020  2020 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 16:35:34.089  6934  6934 D AndroidRuntime: Shutting down VM
,09-13 16:35:34.093  1046  2019 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6987 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-13 16:35:34.095  2020  2020 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473777159034, New one : 1473777334044
09-13 16:35:34.095  2020  2020 D [Concierge]WidgetView: Unregister all receivers
09-13 16:35:34.095  2020  2020 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 16:35:34.096  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:35:34.097  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 16:35:34.098  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-13 16:35:34.099  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-13 16:35:34.100  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-13 16:35:34.101  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-13 16:35:34.102  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:35:34.102  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 16:35:34.134  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 16:35:34.143  2020  2020 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 16:35:34.143  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-13 16:35:34.144  1046  1110 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:35:34.145  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 16:35:34.148  1046  1110 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-13 16:35:34.162  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-13 16:35:34.165  2020  2020 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@26374fd7 time:203271
09-13 16:35:34.188  6987  6987 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,09-13 16:35:34.189  6987  6987 W LG Account v2.2: No ProfileInfo entries
09-13 16:35:34.189  6987  6987 I LG Account v2.2: isEnabled: false
09-13 16:35:34.189  6987  6987 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 16:35:34.189  6987  6987 I Feature : [Lifetracker]Country: EU
09-13 16:35:34.189  6987  6987 I Feature : [Lifetracker]Operator: OPEN
09-13 16:35:34.189  6987  6987 I Feature : [Lifetracker]Ranking support: false
09-13 16:35:34.189  6987  6987 I Feature : [Lifetracker]Comfort support: false
09-13 16:35:34.189  6987  6987 I Feature : [Lifetracker]Accessory: true
09-13 16:35:34.189  6987  6987 I Feature : [Lifetracker]Health device: true
09-13 16:35:34.190  6987  6987 I Feature : [Lifetracker]Extra Pedometer: false
09-13 16:35:34.190  6987  6987 I Feature : [Lifetracker]Blood glucose device: false
09-13 16:35:34.190  6987  6987 I Feature : [Lifetracker]Device Number: 3
09-13 16:35:34.190  6987  6987 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
09-13 16:35:34.210  1046  1062 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 16:35:34.210  1046  1062 I ActivityManager: Killing 6104:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-13 16:35:34.284  1046  1613 W libprocessgroup: failed to open /acct/uid_10014/pid_6104/cgroup.procs: No such file or directory
,09-13 16:35:34.290  2020  2020 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-13 16:35:34.301  7006  7006 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:35:34.302  7006  7006 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 16:35:34.302  7006  7006 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 16:35:34.302  7006  7006 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,09-13 16:35:34.303  7006  7006 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 16:35:34.303  7006  7006 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 16:35:34.330  2020  2866 I GBoardtInterface: onReloaded()
,09-13 16:35:34.332  2020  2020 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-13 16:35:34.333  3776  4797 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 16:35:34.335  3776  3792 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 16:35:34.340  1892  1892 D ActionManagerService: notifyUserLog: 1000001
09-13 16:35:34.340  3776  4798 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 16:35:34.340  3776  4798 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,09-13 16:35:34.343  1892  1892 D ActionManagerService: notifyUserLog: 1000001
09-13 16:35:34.345  3776  4798 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 16:35:34.345  3776  4798 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 16:35:34.345  3776  4798 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-13 16:35:34.345  3776  4798 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-13 16:35:34.345  3776  4797 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 16:35:34.348  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-13 16:35:34.348  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-13 16:35:34.349  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-13 16:35:34.350  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 16:35:34.352  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-13 16:35:34.352  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,09-13 16:35:34.379  7006  7006 D PackageIntentReceiver: Not supported Hotkey customization function 
,09-13 16:35:34.383  7006  7006 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-13 16:35:34.383  7006  7006 D HideNavigationAppsReceiver: replacing : false
09-13 16:35:34.386  7006  7006 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-13 16:35:34.388  7006  7006 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-13 16:35:34.388  7006  7006 D ButtonCombinationReceiver: replacing : false
,09-13 16:35:34.394  1046  1871 I ActivityManager: Killing 6411:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-13 16:35:34.435  1046  1944 W libprocessgroup: failed to open /acct/uid_10008/pid_6411/cgroup.procs: No such file or directory
,09-13 16:35:34.438  4885  7026 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-13 16:35:34.460  1046  1963 V SIM_STK : Menu title from STK is T-Mobile

```
