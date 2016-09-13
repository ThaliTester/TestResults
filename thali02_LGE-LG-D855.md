#### Test 82914073b4ce5c2_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-13 15:13:20.939  2219  2219 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
09-13 15:13:20.945  2219  2219 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
--------- beginning of system
09-13 15:13:46.095  1032  1090 W ProcessCpuTracker: Skipping unknown process pid 6833
,09-13 15:13:47.408  6838  6838 D AndroidRuntime: 
09-13 15:13:47.408  6838  6838 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 15:13:47.411  6838  6838 D AndroidRuntime: CheckJNI is OFF
09-13 15:13:47.536  6838  6838 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 15:13:47.541  1032  1948 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 15:13:47.551  1966  1981 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 15:13:47.554  1032  1948 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 15:13:47.555  1032  1948 D ActivityManager: setTaskToReturnTo : TaskRecord{1e39de81 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 15:13:47.555  1032  1948 D ActivityManager: setTaskToReturnTo : TaskRecord{1e39de81 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 15:13:47.556  1032  1948 D WindowStateEx: AppWindowTokenEx init.. 
09-13 15:13:47.557   335   411 E GBMv2   : DFP En is all cleared set to be enabled
09-13 15:13:47.576  1032  1948 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6853 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 15:13:47.580  6838  6838 D AndroidRuntime: Shutting down VM
09-13 15:13:47.625  1966  1981 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 15:13:47.625  1966  1981 D SplitWindowPolicy: topRunningActivity=ActivityInfo{a641069 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 15:13:47.628  1966  1983 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 15:13:47.628  1966  1983 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3d12aee co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 15:13:47.703  6853  6853 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-13 15:13:47.770  6853  6853 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-13 15:13:47.777  6853  6853 I LibraryLoader: Loading: webviewchromium
09-13 15:13:47.780  6853  6853 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8749-8753)
09-13 15:13:47.781  6853  6853 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 15:13:47.797  6853  6853 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37329eff}
09-13 15:13:47.798  6853  6853 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 15:13:47.798  6853  6853 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 15:13:47.807  6853  6853 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 15:13:47.810  6853  6853 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 15:13:47.831  6853  6853 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 15:13:47.832  6853  6853 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,09-13 15:13:47.832  6853  6853 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-13 15:13:47.837   318  1383 V AudioPolicyService: registerClient() client 0xb0410140, uid 10118
09-13 15:13:47.842  1032  1094 D BluetoothManagerService: Message: 20
09-13 15:13:47.842  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ce25f03:true
09-13 15:13:47.851  6853  6853 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 15:13:47.851  6853  6853 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 15:13:47.851  6853  6853 I Adreno-EGL: Build Date: 12/12/14 금
09-13 15:13:47.851  6853  6853 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 15:13:47.851  6853  6853 I Adreno-EGL: Remote Branch: 
09-13 15:13:47.851  6853  6853 I Adreno-EGL: Local Patches: 
09-13 15:13:47.851  6853  6853 I Adreno-EGL: Reconstruct Branch: 
,09-13 15:13:47.969  6853  6899 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-13 15:13:47.974  6853  6853 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-13 15:13:47.991  6853  6853 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 15:13:47.995  6853  6853 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 15:13:47.998  6853  6853 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 15:13:48.001  6853  6853 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 15:13:48.001  6853  6853 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-13 15:13:48.013  6853  6853 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 15:13:48.020  6853  6853 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 15:13:48.020  6853  6853 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 15:13:48.052  6853  6915 D OpenGLRenderer: Render dirty regions requested: true
09-13 15:13:48.052  6853  6915 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 15:13:48.057  6853  6915 D OpenGLRenderer: Enabling debug mode 0
09-13 15:13:48.064  6853  6853 D Atlas   : Validating map...
,09-13 15:13:48.071  1032  1943 D SplitWindow: check instance of lgWin Window{10f73be5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 15:13:48.148  6853  6913 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:13:48.148  6853  6913 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:13:48.183  6853  6853 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d271dda time:169155
,09-13 15:13:48.183  1032  1095 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +558ms (total +624ms)
09-13 15:13:48.185  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19353b26 u0 com.test.thalitest/.MainActivity t6} time:169157
09-13 15:13:48.334  6853  6853 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 15:13:48.334  6853  6853 I chromium: 
,09-13 15:13:48.402  6853  6853 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 15:13:48.505  6853  6913 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 15:13:48.505  6853  6913 I chromium: 
,09-13 15:13:48.648  6853  6929 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,09-13 15:13:48.668  6853  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 15:13:48.668  6853  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 15:13:48.668  6853  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 15:13:48.668  6853  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 15:13:48.668  6853  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 15:13:48.669  6853  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16305b7e added. We now have 1 listener(s)
,09-13 15:13:48.674  1032  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:13:48.679  6853  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-13 15:13:48.680  6853  6929 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:13:48.682  6853  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:48.682  6853  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 15:13:48.693  6853  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6eb5ff5 added. We now have 1 listener(s)
09-13 15:13:48.694  6853  6929 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:48.700  1032  1542 D WifiService: New client listening to asynchronous messages
,09-13 15:13:48.704  6853  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:13:48.704  6853  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 15:13:48.704  6853  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 15:13:48.704  6853  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 15:13:48.705  6853  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 15:13:48.709  6853  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:13:48.710  1032  1611 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:13:48.713  6853  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,09-13 15:13:48.723  6853  6929 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 15:13:48.724  6853  6929 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:48.724  6853  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:48.724  6853  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:13:48.724  6853  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:48.724  6853  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:48.724  6853  6929 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:48.724  6853  6929 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:13:48.724  6853  6929 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:13:48.724  6853  6929 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 15:13:48.724  6853  6929 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:13:48.727  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:48.729  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:48.730  6853  6929 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 15:13:48.767  6853  6853 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 15:13:48.782   335   413 E GBMv2   : DFP En is all cleared set to be enabled
09-13 15:13:48.782   335   413 E GBMv2   : Set value is all cleared set the max
09-13 15:13:48.782   335   413 I GBMv2   : DFP Enabled. Ignore VFP set
,09-13 15:13:49.520  6853  6932 W jxcore-log: Initializing JXcore engine
09-13 15:13:49.520  6853  6932 W jxcore-log: JXcore engine is ready
,09-13 15:13:49.596  6932  6932 W Thread-812: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9950]" dev="sockfs" ino=9950 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-13 15:13:49.596  6932  6932 W Thread-812: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2864 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-13 15:13:49.596  6932  6932 W Thread-812: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7725]" dev="sockfs" ino=7725 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-13 15:13:49.596  6932  6932 W Thread-812: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,09-13 15:13:49.596  6932  6932 W Thread-812: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33317]" dev="sockfs" ino=33317 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-13 15:13:49.622  6853  6932 W jxcore-log: Starting JXcore engine
,09-13 15:13:49.724  6853  6932 W jxcore-log: Platform android
09-13 15:13:49.724  6853  6932 W jxcore-log: 
09-13 15:13:49.724  6853  6932 W jxcore-log: Process ARCH arm
09-13 15:13:49.724  6853  6932 W jxcore-log: 
,09-13 15:13:50.047  6853  6932 I jxcore-log: JXcore Cordova bridge is ready!
09-13 15:13:50.047  6853  6932 I jxcore-log: 
09-13 15:13:50.048  6853  6932 W jxcore-log: JXcore engine is started
,09-13 15:13:50.057  6853  6929 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 15:13:50.064  6853  6853 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 15:13:59.569  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 15:13:59.569  6853  6932 I jxcore-log: 
,09-13 15:13:59.572  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 15:13:59.572  6853  6932 I jxcore-log: 
09-13 15:13:59.578  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:59.578  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:59.578  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:13:59.578  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:59.578  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:59.578  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:59.578  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:13:59.578  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:13:59.581  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:13:59.584  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 15:13:59.584  6853  6932 I jxcore-log: 
09-13 15:13:59.586  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 15:13:59.586  6853  6932 I jxcore-log: 
09-13 15:14:00.060  1579  1579 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-13 15:14:00.061  1579  1579 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 15:14:00.061  1579  1579 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-13 15:14:00.061  1579  1579 I [SystemUI]Clock: called onTimeUpdated()
,09-13 15:14:00.065  1579  1579 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 15:14:00.065  1579  1579 I [SystemUI]DateView: called onTimeUpdated()
09-13 15:14:00.067  1579  1579 I [SystemUI]DateView: called onTimeUpdated()
09-13 15:14:00.069  1579  1579 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 15:14:00.088  6853  6932 D executeNativeTests: Running unit tests
,09-13 15:14:00.163  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:00.163  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce added. We now have 2 listener(s)
09-13 15:14:00.163  1032  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:00.165  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:14:00.165  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:00.165  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:00.165  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:00.165  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef added. We now have 2 listener(s)
09-13 15:14:00.165  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:14:00.167  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:14:00.169  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:00.173  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:00.173  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.173  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:00.173  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:00.173  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:00.173  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:00.173  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:00.173  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:00.175  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:14:00.175  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:14:00.179  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.180  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.181  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 15:14:00.181  6853  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 15:14:00.181  6853  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 15:14:00.185  6853  6932 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 15:14:00.187  6853  6932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 15:14:00.188  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 15:14:00.188  6853  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:14:00.188  6853  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:14:00.189  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:14:00.192  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.192  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.192  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.192  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.193  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:00.193  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:00.193  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce removed from the list
09-13 15:14:00.193  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.193  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef removed from the list
09-13 15:14:00.193  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.195  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.196  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.196  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.197  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.197  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.197  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.197  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.198  6853  6932 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 15:14:00.199  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.199  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.199  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.199  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.199  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.199  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.199  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.199  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.199  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the li,st
09-13 15:14:00.199  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.199  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.199  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.199  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.199  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.200  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.200  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.200  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.200  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410],
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
09-13 15:14:00.204  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 15:14:00.204  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.205  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.205  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.206  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.206  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.206  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:14:00.206  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.206  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.206  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.206  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.206  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.206  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.206  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:14:00.206  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.208  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.208  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.208  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.208  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.208  6853  6932 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 15:14:00.210  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:00.214  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:00.214  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.214  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:00.214  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:00.214  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:00.214  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:00.214  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:00.214  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:00.215  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:00.215  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:14:00.216  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.216  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:14:00.216  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:14:00.216  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:14:00.216  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:00.216  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:14:00.217  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.219  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 15:14:00.220  1032  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 15:14:00.225  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 15:14:00.231  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 15:14:00.234  6853  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 15:14:00.236  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:14:00.236  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:00.237  6853  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 15:14:00.237  6853  6932 I io.jxcore.node.ConnectionHelper: start: OK
09-13 15:14:00.241  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.242  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.242  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.242  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.242  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.242  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:00.242  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.242  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.242  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.242  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.242  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.242  6853  6932 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 15:14:00.243  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:14:00.246  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:00.246  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.246  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:00.246  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:00.246  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:00.246  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:00.246  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:00.246  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:00.247  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:00.248  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:14:00.248  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:14:00.248  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:14:00.248  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:14:00.248  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:00.248  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:14:00.249  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.250  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.253  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:14:00.253  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:00.254  6853  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 15:14:00.255  6853  6932 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 15:14:00.257  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.257  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.257  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.257  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.257  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.257  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:00.258  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.258  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.258  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.258  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.258  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.258  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.258  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.259  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.259  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.260  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.260  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 15:14:00.260  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.261  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.261  6853  6932 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 15:14:00.262  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:00.264  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:00.264  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.264  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:00.264  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:00.264  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:00.264  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:00.264  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:00.264  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:00.265  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:00.266  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:14:00.267  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:14:00.267  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:14:00.267  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:14:00.267  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:00.267  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:14:00.267  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.270  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.271  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:14:00.272  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:00.273  6853  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 15:14:00.273  6853  6932 I io.jxcore.node.ConnectionHelper: start: OK
09-13 15:14:00.273  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.273  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.273  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.274  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.274  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.274  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.274  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.274  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.274  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:00.274  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.274  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.274  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.274  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.274  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.275  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.275  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 list,ener(s) left
09-13 15:14:00.275  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.275  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.276  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.276  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.276  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.276  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.276  6853  6932 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 15:14:00.277  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.277  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.277  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.277  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.277  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.277  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.277  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.277  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.277  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.277  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.278  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.278  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.278  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.278  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.279  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.279  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.279  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.279  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.280  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.280  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.282  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 15:14:00.282  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.282  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.282  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.283  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.283  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.283  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.283  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.283  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.283  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.283  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.283  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.283  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.283  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.283  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.284  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.284  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.285  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.285  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.285  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.285  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.285  6853  6932 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 15:14:00.286  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.286  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.286  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.286  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.286  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.286  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.287  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.287  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.287  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.287  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.287  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.287  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.287  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.287  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.288  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.288  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.289  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.289  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.289  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.289  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.290  6853  6932 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 15:14:00.290  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.290  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.290  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.291  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.291  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.291  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.291  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.291  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.291  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.292  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.292  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.292  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.292  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.292  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.293  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.293  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.293  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.294  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.294  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.294  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.294  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 15:14:00.296  6853  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 15:14:00.296  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 15:14:00.296  6853  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:14:00.296  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 15:14:00.296  6853  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 15:14:00.296  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.297  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.297  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.297  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.297  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.297  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.297  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.297  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.297  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.297  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.297  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.297  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.297  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.297  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.298  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.298  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.299  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.299  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.299  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.299  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.300  6853  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:14:00.301  6853  6932 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 15:14:00.301  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 15:14:00.308  6853  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:14:00.308  6853  6932 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 15:14:00.309  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 15:14:00.309  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 15:14:00.309  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 15:14:00.309  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 15:14:00.309  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 15:14:00.309  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 15:14:00.309  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 15:14:00.309  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 15:14:00.309  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 15:14:00.310  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 15:14:00.310  6853  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 15:14:00.311  6853  6932 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 15:14:00.311  6853  6932 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 15:14:00.311  6853  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:14:00.311  6853  6932 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 15:14:00.311  6853  6932 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 15:14:00.311  6853  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:14:00.311  6853  6932 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 15:14:00.311  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 15:14:00.313  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 15:14:00.314  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 15:14:00.314  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 15:14:00.315  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 15:14:00.315  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 15:14:00.315  6853  6932 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 15:14:00.315  6853  6932 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:14:00.315  6853  6932 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 15:14:00.316  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.316  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.316  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.317  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.317  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.317  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.318  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 15:14:00.318  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.318  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.318  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.319  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.319  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.319  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.319  6853  6933 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 876)
09-13 15:14:00.320  6853  6934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 876
09-13 15:14:00.320  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.320  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.321  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.321  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.322  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.322  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.322  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.322  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.323  6853  6932 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 15:14:00.323  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.324  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.324  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.327  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.327  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.327  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.327  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.327  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.328  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.328  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.328  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.328  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.328  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.328  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.329  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.329  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.330  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.330  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.330  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.330  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.332  6853  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 15:14:00.333  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.333  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.333  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.333  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.333  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.333  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.333  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.333  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.333  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.333  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.333  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.333  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.333  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.334  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.335  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.335  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.335  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.335  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.335  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.335  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.336  6853  6932 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 15:14:00.337  6853  6932 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 15:14:00.338  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 15:14:00.338  6853  6932 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 15:14:00.338  6853  6932 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 15:14:00.338  6853  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 15:14:00.338  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 15:14:00.338  6853  6932 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 15:14:00.338  6853  6932 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 15:14:00.338  6853  6932 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 15:14:00.338  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 15:14:00.338  6853  6932 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-13 15:14:00.338  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.338  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.338  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.342  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.342  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.342  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.342  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.342  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.342  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.342  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.342  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.342  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.342  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.342  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.347  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.347  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.348  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.348  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.348  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.348  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.348  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.349  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.349  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.349  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.349  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.349  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.349  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.349  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.349  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.349  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.349  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.349  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.349  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.349  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.349  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.349  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.349  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.349  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.350  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.350  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.350  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.351  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.351  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.351  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.351  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.351  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.351  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.351  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.351  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.352  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.352  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.352  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.352  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.352  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.353  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.354  6853  6932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 15:14:00.354  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:00.355  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 15:14:00.356  6853  6932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 15:14:00.356  6853  6932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 15:14:00.357  6853  6853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 15:14:00.364  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 15:14:00.364  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:14:00.367  1032  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:00.367  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.367  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 15:14:00.368  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 15:14:00.368  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 15:14:00.368  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.368  6853  6932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 15:14:00.368  6853  6935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:00.368  6853  6853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 15:14:00.368  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.368  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.368  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:14:00.368  6853  6932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:14:00.369  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:14:00.369  4263  4283 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-13 15:14:00.370  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:14:00.370  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:00.370  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:00.371  6853  6932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:14:00.371  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.371  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.372  6853  6932 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:14:00.373  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.373  6853  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:14:00.373  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.373  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.373  6853  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:14:00.373  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.373  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.373  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.373  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.373  6853  6853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:14:00.373  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.373  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.373  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.373  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.373  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.373  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.373  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.373  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.374  6853  6935 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 15:14:00.374  6853  6935 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 15:14:00.374  6853  6935 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 15:14:00.375  6853  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 15:14:00.376  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.376  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.376  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.376  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.377  6853  6932 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 15:14:00.378  6853  6932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 15:14:00.378  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 15:14:00.379  6853  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:14:00.379  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.379  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.379  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.380  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.380  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.380  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.380  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.380  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.380  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.380  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.380  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.380  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.380  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.380  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.383  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.383  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.383  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.383  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
,09-13 15:14:00.384  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:00.385  1032  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:00.386  1032  2070 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:00.388  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.388  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.388  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.389  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.389  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.389  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.389  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.389  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.389  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.389  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.389  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.389  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.389  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.389  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.398  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.398  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.398  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.398  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.399  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:00.399  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:00.399  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:00.399  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:00.399  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.399  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.400  6853  6932 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f856ce not in the list
09-13 15:14:00.400  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.400  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.400  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:00.400  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.400  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.400  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:00.400  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:00.400  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:00.400  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:00.400  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:00.400  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83e9ef not in the list
09-13 15:14:00.402  6853  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 15:14:00.402  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 15:14:00.402  6853  6932 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 15:14:00.402  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 15:14:00.402  6853  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 15:14:00.402  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 15:14:00.404  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 15:14:00.404  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 15:14:00.405  6853  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 15:14:00.405  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 15:14:00.405  6853  6932 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 15:14:00.405  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 15:14:00.405  6853  6932 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 15:14:00.405  6853  6932 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 15:14:00.406  6853  6932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 15:14:00.406  6853  6932 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 15:14:00.417  6853  6932 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 15:14:00.417  6853  6932 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 15:14:00.417  6853  6932 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 15:14:00.418  6853  6932 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 15:14:00.419  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:00.419  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25288f94 added. We now have 2 listener(s)
09-13 15:14:00.419  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:00.421  6853  6932 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 15:14:00.422  1032  1574 D WifiServiceImplEx: setWifiEnabled: true pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 15:14:00.423  1032  1574 D WifiService: setWifiEnabled: true pid=6853, uid=10118
09-13 15:14:00.423  1032  1574 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 15:14:00.424  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:00.424  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e7c6a3d added. We now have 3 listener(s)
09-13 15:14:00.424  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:00.429  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:00.429  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b860232 added. We now have 4 listener(s)
09-13 15:14:00.429  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:00.431  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:00.431  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11665b83 added. We now have 5 listener(s)
09-13 15:14:00.431  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:14:00.434  1032  1574 D WifiServiceImplEx: setWifiEnabled: false pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 15:14:00.434  1032  1574 D WifiService: setWifiEnabled: false pid=6853, uid=10118
09-13 15:14:00.434  1032  1574 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 15:14:00.445  1032  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 15:14:00.446  1032  1982 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3569b3c mBinding = false
09-13 15:14:00.446  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-13 15:14:00.447  1032  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 15:14:00.448  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,09-13 15:14:00.448  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 15:14:00.448  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 15:14:00.448  1032  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 15:14:00.449  1032  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 15:14:00.449  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 15:14:00.449  1032  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 15:14:00.449  1032  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 15:14:00.450  1032  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 15:14:00.451  1032  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 15:14:00.451  1032  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 15:14:00.453  6853  6933 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-13 15:14:00.453  6853  6933 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:00.454  4263  4282 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:00.454  4263  4430 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
09-13 15:14:00.457  1032  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 15:14:00.458  1032  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.458  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.458  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 15:14:00.458  2726  2726 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 15:14:00.459  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 15:14:00.459  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 15:14:00.460  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 15:14:00.460  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 15:14:00.460  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 15:14:00.460  1032  1536 D WifiNative-wlan0: SET ps 1: returned true
,09-13 15:14:00.461  1032  2859 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.461  1032  1094 D BluetoothManagerService: Message: 2
,09-13 15:14:00.462  1032  1094 D BluetoothManagerService: Sending off request.
09-13 15:14:00.462  4263  4387 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 15:14:00.463  4263  4338 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 15:14:00.463  4263  4338 D BluetoothAdapterProperties: Setting state to 13
09-13 15:14:00.463  4263  4338 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 15:14:00.463  4263  4338 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 15:14:00.464  4263  4338 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 15:14:00.465  4263  4345 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:14:00.465   314   891 D CommandListener: Clearing all IP addresses on wlan0
09-13 15:14:00.466  4263  4338 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 15:14:00.467  4263  4338 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 15:14:00.468  4263  4575 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:00.469  4263  4571 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 15:14:00.469  4263  4571 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:00.469  4263  4571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 15:14:00.469  4263  4571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 15:14:00.469  4263  4571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 15:14:00.469  4263  4571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 15:14:00.469  4263  4571 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 15:14:00.469  4263  4571 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 15:14:00.469  4263  4638 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:00.470  4263  4640 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:00.470  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 15:14:00.470  4263  4430 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 15:14:00.471  4263  4643 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:00.476  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.476  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:00.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:00.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:00.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:00.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:00.476  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:00.476  6853  6853 V io.jxcore.node.ConnectivityMoni,tor:     - active network type is Wi-Fi: true
,09-13 15:14:00.477  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.477  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:00.480  1032  1094 D BluetoothManagerService: Message: 60
09-13 15:14:00.480  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 15:14:00.480  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 15:14:00.481  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 15:14:00.482  4263  4430 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 15:14:00.483  6853  6933 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 876)
09-13 15:14:00.488  1032  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 15:14:00.488  1032  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-13 15:14:00.512  1032  1996 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,09-13 15:14:00.517  1032  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-5ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.517  1032  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-5ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.517  1032  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 15:14:00.518  1032  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.518  1032  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-13 15:14:00.525  1032  1090 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6948 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-13 15:14:00.528  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:14:00.531  1032  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:00.532  1032  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.532  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.532  1032  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2fa07fb5
09-13 15:14:00.532  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:00.533  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:00.533  1579  1579 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 15:14:00.534  4263  4263 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:00.534  4263  4263 D BluetoothMapService: STATE_TURNING_OFF
09-13 15:14:00.534  4263  4263 V BluetoothMapService: Handler(): got msg=4
09-13 15:14:00.534  4263  4263 D BluetoothMapService: MAP Service closeService in
09-13 15:14:00.534  4263  4263 D BluetoothMapMasInstance: MAP Service shutdown
09-13 15:14:00.534  4263  4263 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 15:14:00.534  4263  4263 V BluetoothMapService: MAP Service closeService out
09-13 15:14:00.535  4263  4263 V BtOppService: Receiver DISABLED_ACTION 
09-13 15:14:00.535  4263  4263 I BtOppRfcommListener: stopping Accept Thread
09-13 15:14:00.535  4263  4263 V BtOppRfcommListener: close mBtServerSocket
09-13 15:14:00.535  4263  4263 V BtOppRfcommListener: waiting for thread to terminate
09-13 15:14:00.535  4263  4638 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 15:14:00.536  4263  4263 V BtOppRfcommListener: done waiting for thread to terminate
09-13 15:14:00.539  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.539  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:00.539  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.539  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:00.539  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:00.539  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:00.539  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:00.539  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:00.539  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:00.539  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.539  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:00.540  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.540  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:00.540  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.540  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NO,T_SUPPORTED
09-13 15:14:00.540  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:00.540  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:00.540  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:00.540  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:00.540  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:00.541  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.541  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:00.541  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:14:00.542  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.542  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:00.543  1032  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:00.543  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:00.543  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:00.543  1032  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 15:14:00.544  1032  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:00.544  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:00.544  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:00.559  1032  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 15:14:00.559  1032  1543 D DSQN    : disableDataServiceNotify
09-13 15:14:00.559  1032  1543 D DSQN    : stop dsqn bin
09-13 15:14:00.559   314  6965 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 15:14:00.560  1032  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-13 15:14:00.561  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 15:14:00.566  1032  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 15:14:00.566  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:00.566  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:00.567  1032  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:00.567  1032  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 15:14:00.568  1032  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.568  1032  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.568  1032  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 15:14:00.568  1579  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 15:14:00.569  1032  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 15:14:00.569  1032  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 15:14:00.569  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 15:14:00.590  1032  1090 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6971 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 15:14:00.592  4263  4263 V BtOppService: onDestroy
09-13 15:14:00.593  1032  1535 D LGWifiP2pService: P2pDisablingState
09-13 15:14:00.593  1032  1535 D LGWifiP2pService: P2pDisablingState{ when=-61ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.593  1032  1535 D LGWifiP2pService: p2p socket connection lost
09-13 15:14:00.593  1032  1535 D LGWifiP2pService: P2pDisabledState
09-13 15:14:00.593  1032  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 15:14:00.594  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 15:14:00.594  2726  2726 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 15:14:00.594  1032  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.594  1032  1535 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.594  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 15:14:00.594  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 15:14:00.594  1032  1536 D WifiNative-wlan0: SET ps 1: returned true
09-13 15:14:00.594   314   891 D CommandListener: Clearing all IP addresses on wlan0
09-13 15:14:00.596  1032  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:00.596  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 15:14:00.597  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 15:14:00.598  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 15:14:00.600  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:00.601  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:00.601  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 15:14:00.601  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 15:14:00.601  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:00.601  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:00.601  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 15:14:00.601  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 15:14:00.601  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-13 15:14:00.602  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 15:14:00.602  1032  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.602  1966  1966 D WfdsService: WifiP2pState is changed : false
09-13 15:14:00.602  1966  2314 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 15:14:00.602  1966  2314 D WfdsService: Set the WFDS Monitor: false
09-13 15:14:00.602  1032  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.602  1966  2314 D WfdsMonitor: WFDS Monitor is stopped
09-13 15:14:00.602  1966  2314 D WfdsService: STATE : WfdsDisabledState - enter
09-13 15:14:00.602  1966  2315 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 15:14:00.603  1966  2776 D CtrlSupplicant: Received on exit socket, terminate
09-13 15:14:00.603  1966  2776 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 15:14:00.603  1966  2776 D WfdsMonitor: Event [CTRL-EVENT-TER,MINATING  - connection closed]
09-13 15:14:00.603  1966  2776 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 15:14:00.603  1966  2314 W WfdsService: DefaultState - msg [9445378] is not handled
,09-13 15:14:00.607  1032  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 15:14:00.608  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:00.609  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:00.609  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 15:14:00.609  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 15:14:00.609  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 15:14:00.609  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 15:14:00.610  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:00.611  4263  4263 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 15:14:00.611  1032  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:00.611  1032  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:00.611  1032  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:00.613  1032  1543 D NetworkManagementService: Removing idletimer
09-13 15:14:00.613  1032  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:00.613  1032  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 15:14:00.614  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:00.614  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 15:14:00.614  1877  1877 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:00.614  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 15:14:00.615  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:00.617  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.617  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:00.617  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.617  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:00.617  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:00.617  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:00.617  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:00.617  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:00.617  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:00.617  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:00.617  1032  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 15:14:00.618  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 15:14:00.618  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 15:14:00.618  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 15:14:00.618  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 15:14:00.622  1032  1536 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 15:14:00.622  1032  1536 D WifiNative-p2p0: TERMINATE: returned true
09-13 15:14:00.622  1032  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 15:14:00.622  1032  1536 E WifiStateMachine: useWiFiOffloading() : false
09-13 15:14:00.622  1032  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 15:14:00.628  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 15:14:00.629  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:00.629  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:00.629  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 15:14:00.630  1032  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:00.630  1032  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:00.631  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-13 15:14:00.633  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 15:14:00.633  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:00.633  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 15:14:00.639  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.639  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:00.639  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.639  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:00.639  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:00.639  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:00.639  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:00.639  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:00.639  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:00.639  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.639  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:00.644  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.644  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:00.644  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:00.644  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:00.644  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:00.644  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:00.644  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:00.644  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:00.644  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:14:00.645  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:00.645  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:00.647  6971  6971 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:14:00.648  6971  6971 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 15:14:00.648  6971  6971 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 15:14:00.648  6971  6971 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 15:14:00.649  6971  6971 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 15:14:00.650  6971  6971 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 15:14:00.652  1579  1579 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 15:14:00.653  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:00.653  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:00.665  1579  1579 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 15:14:00.666  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:00.666  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:00.666  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 15:14:00.666  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:00.667  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 15:14:00.677  1032  2859 D DhcpStateMachine: StoppedState
09-13 15:14:00.677  1032  2859 D DhcpStateMachine: StoppedState{ when=-82ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:00.678  1032  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 15:14:00.678  1032  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 15:14:00.683  6948  6948 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 15:14:00.683  6948  6948 W LG Account v2.2: No ProfileInfo entries
09-13 15:14:00.683  6948  6948 I LG Account v2.2: isEnabled: false
09-13 15:14:00.683  6948  6948 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 15:14:00.684  6948  6948 I Feature : [Lifetracker]Country: EU
09-13 15:14:00.684  6948  6948 I Feature : [Lifetracker]Operator: OPEN
09-13 15:14:00.684  6948  6948 I Feature : [Lifetracker]Ranking support: false
09-13 15:14:00.684  6948  6948 I Feature : [Lifetracker]Comfort support: false
09-13 15:14:00.684  6948  6948 I Feature : [Lifetracker]Accessory: true
09-13 15:14:00.684  6948  6948 I Feature : [Lifetracker]Health device: true
09-13 15:14:00.684  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:00.684  6948  6948 I Feature : [Lifetracker]Extra Pedometer: false
09-13 15:14:00.684  6948  6948 I Feature : [Lifetracker]Blood glucose device: false
09-13 15:14:00.684  6948  6948 I Feature : [Lifetracker]Device Number: 3
,09-13 15:14:00.691  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:00.728  1032  1996 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6993 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 15:14:00.729  1032  1996 I ActivityManager: Killing 6204:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-13 15:14:00.732  2726  2726 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 15:14:00.732  2726  2726 I wpa_supplicant: monitor socket send errors count : 1
09-13 15:14:00.732  2726  2726 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1966-2\x00 that cannot receive messages
09-13 15:14:00.733  1032  2757 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 15:14:00.733  1032  2757 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 15:14:00.770  1032  1047 W libprocessgroup: failed to open /acct/uid_10014/pid_6204/cgroup.procs: No such file or directory
,09-13 15:14:00.800  2726  2726 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 15:14:00.801  2726  2726 W wpa_supplicant: USIM:  scard_deinit function
09-13 15:14:00.802  1032  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 15:14:00.802  1032  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 15:14:00.802  1032  2757 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 15:14:00.802  1032  2757 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 15:14:00.802  1032  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:00.802  1032  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 15:14:00.804  1032  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=181763
09-13 15:14:00.805  1032  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=181763
09-13 15:14:00.805  1032  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=181764  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 15:14:00.806  1032  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=181764  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 15:14:00.807  1032  1094 D Tethering: InitialState.processMessage what=4
09-13 15:14:00.811  1032  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:00.811  1032  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:00.813  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 15:14:00.827  6971  6971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 15:14:00.831  4263  4263 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 15:14:00.832  4263  4263 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:00.832  4263  4263 V BluetoothPbapReceiver: ***********state = 13
09-13 15:14:00.834  4263  4263 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 15:14:00.834  1032  1094 D BluetoothManagerService: Message: 20
09-13 15:14:00.834  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b1edf27:true
09-13 15:14:00.838  4263  4263 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:00.838  4263  4263 V BluetoothPbapService: state: 13
09-13 15:14:00.838  4263  4263 V BluetoothPbapService: Pbap Service closeService in
,09-13 15:14:00.840  6993  6993 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 15:14:00.841  4263  4263 V BluetoothPbapService: successfully stopped pbap service
09-13 15:14:00.841  4263  4263 V BluetoothPbapService: Pbap Service closeService out
09-13 15:14:00.841  4263  4263 V BluetoothPbapService: Pbap Service onDestroy
09-13 15:14:00.841  4263  4263 V BluetoothPbapService: Pbap Service closeService in
09-13 15:14:00.841  4263  4263 V BluetoothPbapService: Pbap Service closeService out
09-13 15:14:00.841  4263  4263 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 15:14:00.841  2262  2262 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 15:14:00.844  1032  1094 D BluetoothManagerService: Message: 30
09-13 15:14:00.847  6993  6993 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-13 15:14:00.847  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 15:14:00.849  1032  1094 D BluetoothManagerService: Message: 30
09-13 15:14:00.854  6971  6971 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 15:14:00.855  6971  6971 D BluetoothMap: Create BluetoothMap proxy object
09-13 15:14:00.856  1032  1094 D BluetoothManagerService: Message: 30
09-13 15:14:00.857  1032  1048 I ActivityManager: Killing 6287:com.android.defcontainer/u0a4 (adj 15): empty #17
09-13 15:14:00.874  6853  6853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 15:14:00.880  1032  2349 W libprocessgroup: failed to open /acct/uid_10004/pid_6287/cgroup.procs: No such file or directory
09-13 15:14:00.882  1032  1094 D BluetoothManagerService: Message: 30
09-13 15:14:00.883  6971  6971 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-13 15:14:00.884  6971  6971 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-13 15:14:00.893  2726  2726 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 15:14:00.893  1032  2757 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 15:14:00.893  1032  2757 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 15:14:00.893  1032  2757 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 15:14:00.894  6971  6971 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-13 15:14:00.894  1032  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-13 15:14:00.899  6971  6971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-13 15:14:00.908  6971  6971 D DockEventReceiver: finishStartingService: stopping service
09-13 15:14:00.909  6971  6971 D BluetoothInputDevice: Proxy object connected
,09-13 15:14:00.910  6971  6971 D HidProfile: Bluetooth service connected
09-13 15:14:00.922  6971  6971 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 15:14:00.924  6971  6971 D PanProfile: Bluetooth service connected
,09-13 15:14:00.938  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:00.977  6971  6971 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:00.978  6971  6971 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:00.995  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:00.995  6971  6971 D BluetoothMap: Proxy object connected
09-13 15:14:00.996  1032  1536 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 15:14:00.996  6971  6971 D MapProfile: Bluetooth service connected
09-13 15:14:00.996  1032  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 15:14:00.996  1032  1536 E WifiStateMachine: useWiFiOffloading() : false
09-13 15:14:00.996  1032  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 15:14:00.996  6971  6971 D BluetoothMap: getConnectedDevices()
09-13 15:14:00.997  6971  6971 D BluetoothMap: Bluetooth is Not enabled
09-13 15:14:00.997  6971  6971 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 15:14:01.001  6971  6971 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 15:14:01.010  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:01.010  1966  1966 D WfdsService: Supplicant Connection state is changed : false
09-13 15:14:01.012  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 15:14:01.012  1966  2314 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 15:14:01.012  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:01.012  1966  2314 D WfdsService: Set the WFDS Monitor: false
09-13 15:14:01.012  1966  2314 D WfdsMonitor: WFDS Monitor is stopped
09-13 15:14:01.013  6971  6971 D BluetoothPermissionRequest: onReceive
09-13 15:14:01.013  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:01.014  2481  2481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:01.017  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,09-13 15:14:01.019  1032  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 15:14:01.019  1032  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 15:14:01.022  6971  6971 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 15:14:01.033  1032  2038 I ActivityManager: Killing 6430:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-13 15:14:01.038  6971  6971 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 15:14:01.068  1032  1598 W libprocessgroup: failed to open /acct/uid_10008/pid_6430/cgroup.procs: No such file or directory
,09-13 15:14:01.071  4263  4263 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 15:14:01.071  4263  4263 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 15:14:01.072  4263  4263 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-13 15:14:01.158  1032  2038 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7025 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-13 15:14:01.158  4263  4263 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:01.158  4263  4263 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 15:14:01.161  4263  4263 V BluetoothFtpService: Ftp Service onStartCommand
09-13 15:14:01.161  4263  4263 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:01.161  4263  4263 V BluetoothFtpService: Ftp Service closeService
09-13 15:14:01.162  4263  4263 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,09-13 15:14:01.165  4263  4263 V BluetoothFtpService: successfully stopped ftp service
09-13 15:14:01.166  4263  4263 V BluetoothFtpService: Ftp Service onDestroy
09-13 15:14:01.166  4263  4263 V BluetoothFtpService: Ftp Service closeService
09-13 15:14:01.174  4263  4263 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 15:14:01.175  4263  4263 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 15:14:01.175  4263  4263 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 15:14:01.175  4263  4263 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:01.175  4263  4263 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 15:14:01.175  4263  4263 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-13 15:14:01.176  4263  4263 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:01.177  4263  4263 V BluetoothSapService: state: 13
09-13 15:14:01.177  4263  4263 V BluetoothSapService: Stopping SAP server process
09-13 15:14:01.179  4263  4263 V BluetoothSapService: Sap Service closeSapService in
09-13 15:14:01.179  4263  4263 V BluetoothSapService: Close listen Socket : 
09-13 15:14:01.180  4263  4263 V BluetoothSapService: Close rfcomm Socket : 
09-13 15:14:01.180  4263  4263 V BluetoothSapService: Close sapd  Socket : 
09-13 15:14:01.226  1032  1943 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7042 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 15:14:01.227  4263  4263 V BluetoothSapService: Sap Service closeSapService out
,09-13 15:14:01.228  4263  4263 V BluetoothSapService: Sap Service onDestroy
09-13 15:14:01.228  4263  4263 V BluetoothSapService: Sap Service closeSapService in
09-13 15:14:01.228  4263  4263 V BluetoothSapService: Close listen Socket : 
09-13 15:14:01.228  4263  4263 V BluetoothSapService: Close rfcomm Socket : 
09-13 15:14:01.229  4263  4263 V BluetoothSapService: Close sapd  Socket : 
09-13 15:14:01.237  4263  4263 V BluetoothSapService: Sap Service closeSapService out
09-13 15:14:01.259  7025  7025 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 15:14:01.287  7042  7042 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 15:14:01.294  7025  7025 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-13 15:14:01.305  1032  1948 I ActivityManager: Killing 6477:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-13 15:14:01.330  7025  7025 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-13 15:14:01.331  7025  7025 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,09-13 15:14:01.331  7025  7025 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 15:14:01.331  7025  7025 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 15:14:01.332  7025  7025 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 15:14:01.334  7025  7025 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 15:14:01.339  7025  7025 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-13 15:14:01.358  1032  1943 W libprocessgroup: failed to open /acct/uid_10011/pid_6477/cgroup.procs: No such file or directory
,09-13 15:14:01.375  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 15:14:01.381  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:01.410  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 15:14:01.412  7025  7025 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-13 15:14:01.415  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:01.418  7025  7025 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-13 15:14:01.420  6993  6993 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 15:14:01.420  6993  6993 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 15:14:01.420  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 15:14:01.426  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:01.436  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 15:14:01.445  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:01.446  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 15:14:01.449  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 15:14:01.454  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:01.460  6993  6993 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 15:14:01.461  6993  6993 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 15:14:01.461  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 15:14:01.465  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:01.476  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:01.485  4263  4430 W bt-btif : ag scb idx 1 not allocated
09-13 15:14:01.485  4263  4430 E bt-btif : BTA AG is already disabled, ignoring ...
,09-13 15:14:01.485  4263  4345 D bt_hci_bdroid: cleanup
09-13 15:14:01.485  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 15:14:01.485  4263  4430 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:14:01.485  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-13 15:14:01.485  4263  4430 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:14:01.485  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 15:14:01.485  4263  4430 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:14:01.485  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 15:14:01.485  4263  4430 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:14:01.485  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 15:14:01.486  4263  4430 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 15:14:01.486  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 15:14:01.486  4263  4430 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:14:01.486  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 15:14:01.486  4263  4534 I bt_userial_mct: exiting userial_read_thread
09-13 15:14:01.486  4263  4430 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:14:01.486  4263  4534 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 15:14:01.486  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 15:14:01.486  4263  4430 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:14:01.486  4263  4430 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 15:14:01.486  4263  4430 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:14:01.486  4263  4430 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 15:14:01.486  4263  4345 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 15:14:01.487  4263  4432 I bt_lpm  : LPM is already off!!!
09-13 15:14:01.487  4263  4432 I bt_vendor: hw_epilog_process
09-13 15:14:01.488  4263  4345 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 15:14:01.488  4263  4345 D bt_userial_mct: userial_close
09-13 15:14:01.488  4263  4345 E bt_userial_mct: pthread_join() FAILED result:3
09-13 15:14:01.488  4263  4345 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 15:14:01.494  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 15:14:01.494  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:01.497  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 15:14:01.567  4263  4345 D bt_hci_bdroid: set_power 0
09-13 15:14:01.567  4263  4345 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 15:14:01.567  4263  4345 I bt_vendor: bluetooth satus is on
09-13 15:14:01.567  4263  4345 I bt_vendor: bt-vendor : resetting BT status
09-13 15:14:01.567  4263  4345 I bt_vendor: Starting hciattach daemon
09-13 15:14:01.567  4263  4345 I bt_vendor: try to set false
09-13 15:14:01.569  4263  4345 I bt_vendor: Starting hciattach daemon
09-13 15:14:01.569  4263  4345 I bt_vendor: try to set false
09-13 15:14:01.570  4263  4345 I bt_vendor: cleanup
09-13 15:14:01.571  4263  4430 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 15:14:01.571  4263  4345 I GKI_LINUX: GKI_exit_task 0 done
09-13 15:14:01.571  4263  4345 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-13 15:14:01.573  1032  1597 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7063 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-13 15:14:01.573  4263  4338 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 15:14:01.586  4263  4263 D HeadsetService: Received stop request...Stopping profile...
,09-13 15:14:01.588  4263  4263 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 15:14:01.588  4263  4263 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 15:14:01.588  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253994cc
09-13 15:14:01.588  4263  4370 D HeadsetStateMachine: Exit Disconnected: -1
09-13 15:14:01.590  1877  1877 D BluetoothHeadset: Proxy object disconnected
09-13 15:14:01.590  1877  1877 D BluetoothHeadset: Proxy object disconnected
09-13 15:14:01.590  4263  4263 D A2dpService: Received stop request...Stopping profile...
09-13 15:14:01.590  1877  1877 D BluetoothHeadset: Proxy object disconnected
09-13 15:14:01.591  4263  4413 D A2dpStateMachine: Exit Disconnected: -1
09-13 15:14:01.591  4263  4263 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 15:14:01.593  4263  4263 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 15:14:01.593  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-13 15:14:01.593  4263  4263 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 15:14:01.593  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 15:14:01.593  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253994cc
09-13 15:14:01.594  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-13 15:14:01.594  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 15:14:01.595  4263  4263 D HeadsetStateMachine: Unbinding service...
09-13 15:14:01.596  4263  4263 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 15:14:01.596  4263  4263 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 15:14:01.596  4263  4263 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 15:14:01.596  4263  4263 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 15:14:01.596  4263  4263 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 15:14:01.596  4263  4263 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 15:14:01.596  4263  4263 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 15:14:01.597  4263  4263 D HidService: Received stop request...Stopping profile...
09-13 15:14:01.597  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253994cc
09-13 15:14:01.598  4263  4263 I BluetoothA2dpServiceJni: cleanupNative
,09-13 15:14:01.598  4263  4414 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 15:14:01.600  6971  6971 D BluetoothInputDevice: Proxy object disconnected
09-13 15:14:01.600  6971  6971 D HidProfile: Bluetooth service disconnected
,09-13 15:14:01.600  4263  4263 I GKI_LINUX: GKI_exit_task 2 done
09-13 15:14:01.601  4263  4263 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 15:14:01.601  4263  4263 D HealthService: Received stop request...Stopping profile...
09-13 15:14:01.601  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253994cc
09-13 15:14:01.603  4263  4263 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 15:14:01.603  4263  4263 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 15:14:01.603  4263  4338 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 15:14:01.604  4263  4263 D PanService: Received stop request...Stopping profile...
09-13 15:14:01.605  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253994cc
09-13 15:14:01.606  6971  6971 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 15:14:01.606  4263  4263 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 15:14:01.606  6971  6971 D PanProfile: Bluetooth service disconnected
09-13 15:14:01.606  4263  4263 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 15:14:01.606  4263  4263 D BtGatt.GattService: stop()
09-13 15:14:01.606  4263  4263 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 15:14:01.607  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253994cc
09-13 15:14:01.608  4263  4263 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-13 15:14:01.608  4263  4263 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 15:14:01.608  4263  4263 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 15:14:01.609  4263  4263 D BluetoothMapService: Received stop request...Stopping profile...
09-13 15:14:01.609  4263  4263 D BluetoothMapService: stop()
09-13 15:14:01.610  4263  4263 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 15:14:01.610  4263  4263 D BluetoothMapEmailAppObserver: removeReceiver()
,09-13 15:14:01.612  4263  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253994cc
09-13 15:14:01.613  4263  4263 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 15:14:01.613  4263  4263 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 15:14:01.614  4263  4263 V BluetoothMapService: Handler(): got msg=4
09-13 15:14:01.614  4263  4263 D BluetoothMapService: MAP Service closeService in
09-13 15:14:01.614  4263  4263 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 15:14:01.614  4263  4263 V BluetoothMapService: MAP Service closeService out
09-13 15:14:01.615  4263  4263 D BluetoothMapService: cleanup()
09-13 15:14:01.615  4263  4263 D BluetoothMapService: MAP Service closeService in
09-13 15:14:01.615  4263  4263 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 15:14:01.615  4263  4263 V BluetoothMapService: MAP Service closeService out
09-13 15:14:01.616  4263  4338 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 15:14:01.616  4263  4338 D BluetoothAdapterProperties: Setting state to 10
09-13 15:14:01.616  4263  4338 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 15:14:01.616  1032  1094 D BluetoothManagerService: Message: 60
09-13 15:14:01.616  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 15:14:01.616  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-13 15:14:01.616  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 15:14:01.617  4263  4338 I BluetoothAdapterState: Entering OffState
09-13 15:14:01.617  1877  1892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:14:01.618  6971  6987 D BluetoothPan: onBluetoothStateChange on: false
09-13 15:14:01.619  6971  6988 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 15:14:01.619  6971  6987 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 15:14:01.620  6971  6988 D BluetoothMap: onBluetoothStateChange: up=false
09-13 15:14:01.623  6971  6971 D BluetoothMap: Proxy object disconnected
09-13 15:14:01.623  6971  6971 D MapProfile: Bluetooth service disconnected
09-13 15:14:01.623  1877  4366 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 15:14:01.624  1877  2531 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:14:01.624  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:14:01.625  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-13 15:14:01.625  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-13 15:14:01.627  1032  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-13 15:14:01.628  1032  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-13 15:14:01.628  1032  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3569b3c mBinding = false
09-13 15:14:01.628  1032  1094 D BluetoothManagerService: Sending unbind request.
09-13 15:14:01.631  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 15:14:01.635  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:01.637  1579  1579 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-13 15:14:01.638  1966  2195 D LGBluetoothAPIService: Message: 2
09-13 15:14:01.638  1966  2195 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3d37fb8f mBinding = false
09-13 15:14:01.639  1966  2195 D LGBluetoothAPIService: Sending unbind request.
09-13 15:14:01.639  4263  4345 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-13 15:14:01.640  4263  4263 I GKI_LINUX: GKI_exit_task 1 done
09-13 15:14:01.640  4263  4263 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-13 15:14:01.641  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:01.641  4263  4263 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 15:14:01.641  4263  4263 I art     : --- WEIRD: removing null entry 246
09-13 15:14:01.641  4263  4263 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-13 15:14:01.641  4263  4263 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-13 15:14:01.641  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:01.648  6971  6971 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 15:14:01.649  4263  4263 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-13 15:14:01.649  6971  6971 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 15:14:01.649  6971  6971 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 15:14:01.652  1579  1579 D BluetoothAdapter: 181984118: getState() :  mService = null. Returning STATE_OFF
09-13 15:14:01.652  1579  1579 D BluetoothAdapter: 181984118: getState() :  mService = null. Returning STATE_OFF
,09-13 15:14:01.660  4263  4263 I art     : System.exit called, status: 0
09-13 15:14:01.660  4263  4263 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 15:14:01.663  6971  6971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 15:14:01.679  6971  6971 D DockEventReceiver: finishStartingService: stopping service
09-13 15:14:01.694   318   318 V AudioFlinger: 4263 died, releasing its sessions
09-13 15:14:01.694   318   318 V AudioFlinger:  pid 1877 @ 0
,09-13 15:14:01.694   318   318 V AudioFlinger:  pid 3168 @ 1
,09-13 15:14:01.694   318   318 V AudioFlinger:  pid 3168 @ 2
09-13 15:14:01.695  6971  6971 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-13 15:14:01.737  1032  1048 I ActivityManager: Process com.android.bluetooth (pid 4263) has died
09-13 15:14:01.738  1032  1048 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-13 15:14:01.743  2262  2262 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 15:14:01.754  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 15:14:01.759  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 15:14:01.764  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:01.764  6971  6971 D BluetoothPermissionRequest: onReceive
09-13 15:14:01.767  6971  6971 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-13 15:14:01.767  6971  6971 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 15:14:01.770  6971  6971 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 15:14:01.813  1032  1943 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7101 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-13 15:14:01.824  7063  7098 W FormManager: Network not available. Please check & try again.
09-13 15:14:01.837  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 15:14:01.837  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-13 15:14:01.839  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 15:14:01.839  6971  6971 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 15:14:01.840  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 15:14:01.847  7063  7100 V FormManager: Network unavailable.
09-13 15:14:01.851  6971  6971 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 15:14:01.852  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 15:14:01.852  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 15:14:01.852  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 15:14:01.852  6971  6971 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 15:14:01.853  6971  6971 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 15:14:01.853  7063  7100 V FormManager: Network unavailable.
,09-13 15:14:01.856  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 15:14:01.857  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 15:14:01.858   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 462us total 41.420ms
09-13 15:14:01.859  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:01.861  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:01.870  6993  6993 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 15:14:01.870  6993  6993 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 15:14:01.870  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 15:14:01.878  4728  7121 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 15:14:01.879   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 19.806ms
09-13 15:14:01.880  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 15:14:01.887  4728  7122 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 15:14:01.888  4728  7122 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 15:14:01.892  7101  7101 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-13 15:14:01.892  7101  7101 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 15:14:01.893  7101  7101 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-13 15:14:01.893  7063  7125 V FormManager: Network unavailable.
09-13 15:14:01.893  7101  7101 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 15:14:01.896  7063  7124 W FormManager: Network not available. Please check & try again.
09-13 15:14:01.896  7063  7125 V FormManager: Network unavailable.
09-13 15:14:01.896  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:01.898   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 18.391ms
09-13 15:14:01.902  1032  1574 I ActivityManager: Killing 6003:com.android.contacts/u0a19 (adj 15): empty #17
,09-13 15:14:01.912  7101  7101 D BluetoothAdapterApp: Loading JNI Library
09-13 15:14:01.939  7101  7101 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2c99355d Instance Count = 1
,09-13 15:14:02.012  1032  2350 W libprocessgroup: failed to open /acct/uid_10019/pid_6003/cgroup.procs: No such file or directory
,09-13 15:14:02.023  7101  7101 D BluetoothAdapterApp: onCreate
09-13 15:14:02.041  7025  7025 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 15:14:02.043  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 15:14:02.043  7025  7025 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-13 15:14:02.061  7101  7101 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-13 15:14:02.062  7101  7101 D ProfileConfigQcom: Adding HeadsetService
09-13 15:14:02.062  7101  7101 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-13 15:14:02.063  7101  7101 D ProfileConfigQcom: Adding A2dpService
09-13 15:14:02.063  7101  7101 D ProfileConfigQcom: [BTUI] HidService is supported
09-13 15:14:02.064  7101  7101 D ProfileConfigQcom: Adding HidService
,09-13 15:14:02.065  7101  7101 D ProfileConfigQcom: [BTUI] HealthService is supported
,09-13 15:14:02.065  7101  7101 D ProfileConfigQcom: Adding HealthService
,09-13 15:14:02.066  7101  7101 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-13 15:14:02.068  7101  7101 D ProfileConfigQcom: [BTUI] PanService is supported
09-13 15:14:02.068  7101  7101 D ProfileConfigQcom: Adding PanService
09-13 15:14:02.069  7101  7101 D ProfileConfigQcom: [BTUI] GattService is supported
09-13 15:14:02.069  7101  7101 D ProfileConfigQcom: Adding GattService
09-13 15:14:02.070  7101  7101 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-13 15:14:02.070  7101  7101 D ProfileConfigQcom: Adding BluetoothMapService
09-13 15:14:02.071  7101  7101 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-13 15:14:02.075  7101  7101 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 15:14:02.080  7025  7025 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:02.081  7025  7025 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:02.087  6971  6971 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 15:14:02.089  7025  7025 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 15:14:02.090  7025  7025 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 15:14:02.090  7025  7025 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-13 15:14:02.090  7025  7025 V SoundPool: doLoad: loading sample sampleID=1
09-13 15:14:02.090  7025  7025 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 15:14:02.091  7025  7129 V SoundPool: Start decode
09-13 15:14:02.091  7025  7129 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-13 15:14:02.092   318   318 V MediaPlayerService: decode(22, 10857164, 17813)
09-13 15:14:02.092   318   318 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-13 15:14:02.092   318   318 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 15:14:02.092   318   318 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 15:14:02.092   318   318 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 15:14:02.092   318   318 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-13 15:14:02.092   318   318 V MediaPlayerService: player type = 3
09-13 15:14:02.092   318   318 V AwesomePlayer: AwesomePlayer create()
09-13 15:14:02.093   318   318 V AwesomePlayer: reset_l() 
09-13 15:14:02.093   318   318 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:02.093   318   318 V AwesomePlayer: setAudioSink() 
09-13 15:14:02.093   318   318 V AwesomePlayer: reset_l() 
09-13 15:14:02.094   318   318 V AudioCache: notify(0xb1432440, 8, 0, 0)
09-13 15:14:02.094   318   318 V AudioCache: ignored
09-13 15:14:02.094   318   318 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:02.094   318   318 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 15:14:02.094   318   318 V AwesomePlayer: setDataSource_l dataSource
09-13 15:14:02.094   318   318 V LGParserOSAL: SniffLGParser start
09-13 15:14:02.094   318   318 V LGParserOSAL: MainType:5, SubType=0
09-13 15:14:02.094   318   318 V LGParserOSAL: #### check Mime : application/ogg
09-13 15:14:02.094   318   318 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 15:14:02.094   318   318 E MediaExtractor: Use LGExtractor :application/ogg 
,09-13 15:14:02.095  6745  6745 D UEI.SmartControl: QS Service created
09-13 15:14:02.098  7101  7101 V LGMDMManagerInternal: Create singleton instance
09-13 15:14:02.099  7025  7025 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 15:14:02.100  7025  7025 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 15:14:02.101  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-13 15:14:02.107  6745  6745 I UEI.SmartControl: Service initServices...
09-13 15:14:02.108  6745  6745 D UEI.SmartControl: QS start get config
09-13 15:14:02.115  7025  7025 V LGMDMManager: Create singleton instance
09-13 15:14:02.137   318   318 V LGParserOSAL: supported mime: application/ogg
09-13 15:14:02.137   318   318 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 15:14:02.137   318   318 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 15:14:02.137   318   318 V AwesomePlayer: mBitrate = -1 bits/sec
09-13 15:14:02.137   318   318 V AwesomePlayer: AudioTrack Setting
09-13 15:14:02.137   318   318 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 15:14:02.138   318   318 V AwesomePlayer: setAudioSource() 
09-13 15:14:02.138   318   318 V MediaPlayerService: prepare
09-13 15:14:02.138   318   318 V AwesomePlayer: prepareAsync_l() 
09-13 15:14:02.138   318   318 V MediaPlayerService: wait for prepare
09-13 15:14:02.138   318  7130 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 15:14:02.138   318  7130 V AwesomePlayer: initAudioDecoder() 
09-13 15:14:02.138   318  7130 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 15:14:02.138   318  7130 V AudioSystem: isOffloadSupported()
09-13 15:14:02.138   318  7130 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 15:14:02.138   318  7130 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 15:14:02.138   318  7130 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 15:14:02.138   318  7130 V AwesomePlayer: getUseOffload() = 0 
09-13 15:14:02.138   318  7130 V OMXCodec: OMXCodec::Create
09-13 15:14:02.138   318  7130 V OMXCodec: findMatchingCodecs()
09-13 15:14:02.138   318  7130 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 15:14:02.138   318  7130 V OMXCodec: matchingCodecs.size()=1
09-13 15:14:02.138   318  7130 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-13 15:14:02.140   318  7130 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 15:14:02.140   318  7130 V LGCodecAdapter: LG Codec Adapter start
09-13 15:14:02.140   318  7130 V OMXCodec: OMXCodec Createtor
09-13 15:14:02.140   318  7130 V OMXCodec: setComponentRole
09-13 15:14:02.140   318  7130 V OMXCodec: configureCodec protected=0
09-13 15:14:02.140   318  7130 V LGCodecAdapter: called getLGCodecSpecificData
09-13 15:14:02.140   318  7130 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 15:14:02.140   318  7130 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 15:14:02.140   318  7130 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 15:14:02.140   318  7130 V LGCodecOSAL: Not support LGCodec
09-13 15:14:02.140   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 15:14:02.140   318  7130 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 15:14:02.140   318  7130 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 15:14:02.140   318  7130 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 15:14:02.140   318  7130 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 15:14:02.140   318  7130 V AudioSystem: isOffloadSupported()
09-13 15:14:02.140   318  7130 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 15:14:02.140   318  7130 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 15:14:02.140   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 15:14:02.140   318  7130 V OMXCodec: init()
09-13 15:14:02.140   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-13 15:14:02.140   318  7130 V OMXCodec: allocateBuffers
09-13 15:14:02.140   318  7130 V OMXCodec: allocateBuffersOnPort portIndex=0
09-13 15:14:02.140   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 15:14:02.140   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
09-13 15:14:02.141   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
09-13 15:14:02.141   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-13 15:14:02.141   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-13 15:14:02.141   318  7130 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 15:14:02.141   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 15:14:02.141   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-13 15:14:02.141   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
09-13 15:14:02.141   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-13 15:14:02.141   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-13 15:14:02.141   318  7130 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 15:14:02.143   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 15:14:02.143   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 15:14:02.143   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 15:14:02.143   318  7130 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 15:14:02.143   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 15:14:02.143   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 15:14:02.143   31,8  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 15:14:02.143   318  7130 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 15:14:02.143   318  7130 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 15:14:02.143   318  7130 V AudioCache: notify(0xb1432440, 5, 0, 0)
09-13 15:14:02.143   318  7130 V AudioCache: ignored
09-13 15:14:02.143   318  7130 V AudioCache: notify(0xb1432440, 1, 0, 0)
09-13 15:14:02.143   318  7130 V AudioCache: prepared
09-13 15:14:02.143   318   318 V AudioCache: wait - success
09-13 15:14:02.143   318   318 V MediaPlayerService: start
09-13 15:14:02.143   318   318 V AwesomePlayer: play_l() 
09-13 15:14:02.143   318   318 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 15:14:02.143   318   318 V AwesomePlayer: createAudioPlayer_l
09-13 15:14:02.143   318   318 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 15:14:02.143   318   318 V AwesomePlayer: startAudioPlayer_l() 
09-13 15:14:02.143   318   318 D AudioPlayer: start of Playback, useOffload 0
09-13 15:14:02.143   318   318 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 15:14:02.143   318   318 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 15:14:02.146   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 15:14:02.146   318  7132 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 15:14:02.147   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 15:14:02.147   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
,09-13 15:14:02.147   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
09-13 15:14:02.147   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
09-13 15:14:02.147   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ff420 on output port
09-13 15:14:02.147   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 15:14:02.147   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 15:14:02.148   318   318 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-13 15:14:02.149   318   318 V AudioCache: notify(0xb1432440, 6, 0, 0)
09-13 15:14:02.149   318   318 V AudioCache: ignored
09-13 15:14:02.149   318   318 V MediaPlayerService: wait for playback complete
09-13 15:14:02.149   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.149   318  7133 V AudioCache: memcpy(0xaf004000, 0xb16a7000, 4096)
09-13 15:14:02.150   318  7133 V AudioCache: write(0xb16a7000, 4096)
,09-13 15:14:02.150   318  7133 V AudioCache: memcpy(0xaf005000, 0xb16a7000, 4096)
09-13 15:14:02.150   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.150   318  7133 V AudioCache: memcpy(0xaf006000, 0xb16a7000, 4096)
09-13 15:14:02.151   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.151   318  7133 V AudioCache: memcpy(0xaf007000, 0xb16a7000, 4096)
,09-13 15:14:02.152   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.152   318  7133 V AudioCache: memcpy(0xaf008000, 0xb16a7000, 4096)
09-13 15:14:02.152   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.152   318  7133 V AudioCache: memcpy(0xaf009000, 0xb16a7000, 4096)
09-13 15:14:02.157   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.157   318  7133 V AudioCache: memcpy(0xaf00a000, 0xb16a7000, 4096)
09-13 15:14:02.158   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.158   318  7133 V AudioCache: memcpy(0xaf00b000, 0xb16a7000, 4096)
09-13 15:14:02.158   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.158   318  7133 V AudioCache: memcpy(0xaf00c000, 0xb16a7000, 4096)
09-13 15:14:02.159   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.159   318  7133 V AudioCache: memcpy(0xaf00d000, 0xb16a7000, 4096)
09-13 15:14:02.159   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.159   318  7133 V AudioCache: memcpy(0xaf00e000, 0xb16a7000, 4096)
09-13 15:14:02.160   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.160   318  7133 V AudioCache: memcpy(0xaf00f000, 0xb16a7000, 4096)
09-13 15:14:02.160   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.160   318  7133 V AudioCache: memcpy(0xaf010000, 0xb16a7000, 4096)
09-13 15:14:02.161   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.161   318  7133 V AudioCache: memcpy(0xaf011000, 0xb16a7000, 4096)
09-13 15:14:02.161   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.161   318  7133 V AudioCache: memcpy(0xaf012000, 0xb16a7000, 4096)
09-13 15:14:02.161   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.161   318  7133 V AudioCache: memcpy(0xaf013000, 0xb16a7000, 4096)
09-13 15:14:02.162   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.162   318  7133 V AudioCache: memcpy(0xaf014000, 0xb16a7000, 4096)
09-13 15:14:02.162   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.162   318  7133 V AudioCache: memcpy(0xaf015000, 0xb16a7000, 4096)
09-13 15:14:02.163   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.163   318  7133 V AudioCache: memcpy(0xaf016000, 0xb16a7000, 4096)
09-13 15:14:02.163   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.163   318  7133 V AudioCache: memcpy(0xaf017000, 0xb16a7000, 4096)
09-13 15:14:02.164   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.164   318  7133 V AudioCache: memcpy(0xaf018000, 0xb16a7000, 4096)
09-13 15:14:02.164   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.164   318  7133 V AudioCache: memcpy(0xaf019000, 0xb16a7000, 4096)
09-13 15:14:02.165   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.165   318  7133 V AudioCache: memcpy(0xaf01a000, 0xb16a7000, 4096)
09-13 15:14:02.165   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.165   318  7133 V AudioCache: memcpy(0xaf01b000, 0xb16a7000, 4096)
09-13 15:14:02.165   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.165   318  7133 V AudioCache: memcpy(0xaf01c000, 0xb16a7000, 4096)
09-13 15:14:02.166   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.166   318  7133 V AudioCache: memcpy(0xaf01d000, 0xb16a7000, 4096)
09-13 15:14:02.166   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.166   318  7133 V AudioCache: memcpy(0xaf01e000, 0xb16a7000, 4096)
09-13 15:14:02.167   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.167   318  7133 V AudioCache: memcpy(0xaf01f000, 0xb16a7000, 4096)
09-13 15:14:02.167   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.167   318  7133 V AudioCache: memcpy(0xaf020000, 0xb16a7000, 4096)
09-13 15:14:02.168   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.168   318  7133 V AudioCache: memcpy(0xaf021000, 0xb16a7000, 4096)
09-13 15:14:02.168   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.168   318  7133 V AudioCache: mem,cpy(0xaf022000, 0xb16a7000, 4096)
,09-13 15:14:02.169   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.169   318  7133 V AudioCache: memcpy(0xaf023000, 0xb16a7000, 4096)
09-13 15:14:02.169   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.169   318  7133 V AudioCache: memcpy(0xaf024000, 0xb16a7000, 4096)
09-13 15:14:02.170   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.170   318  7133 V AudioCache: memcpy(0xaf025000, 0xb16a7000, 4096)
09-13 15:14:02.170   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.170   318  7133 V AudioCache: memcpy(0xaf026000, 0xb16a7000, 4096)
09-13 15:14:02.170   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.170   318  7133 V AudioCache: memcpy(0xaf027000, 0xb16a7000, 4096)
09-13 15:14:02.171   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.171   318  7133 V AudioCache: memcpy(0xaf028000, 0xb16a7000, 4096)
09-13 15:14:02.171   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.171   318  7133 V AudioCache: memcpy(0xaf029000, 0xb16a7000, 4096)
09-13 15:14:02.172   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.172   318  7133 V AudioCache: memcpy(0xaf02a000, 0xb16a7000, 4096)
09-13 15:14:02.173   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.173   318  7133 V AudioCache: memcpy(0xaf02b000, 0xb16a7000, 4096)
09-13 15:14:02.173   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.173   318  7133 V AudioCache: memcpy(0xaf02c000, 0xb16a7000, 4096)
09-13 15:14:02.174   318  7133 V AudioCache: write(0xb16a7000, 4096)
,09-13 15:14:02.174   318  7133 V AudioCache: memcpy(0xaf02d000, 0xb16a7000, 4096)
09-13 15:14:02.174   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.174   318  7133 V AudioCache: memcpy(0xaf02e000, 0xb16a7000, 4096)
09-13 15:14:02.174   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.174   318  7133 V AudioCache: memcpy(0xaf02f000, 0xb16a7000, 4096)
09-13 15:14:02.174   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.174   318  7133 V AudioCache: memcpy(0xaf030000, 0xb16a7000, 4096)
09-13 15:14:02.175   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.175   318  7133 V AudioCache: memcpy(0xaf031000, 0xb16a7000, 4096)
09-13 15:14:02.175   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.175   318  7133 V AudioCache: memcpy(0xaf032000, 0xb16a7000, 4096)
09-13 15:14:02.176   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.176   318  7133 V AudioCache: memcpy(0xaf033000, 0xb16a7000, 4096)
09-13 15:14:02.176   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.176   318  7133 V AudioCache: memcpy(0xaf034000, 0xb16a7000, 4096)
09-13 15:14:02.176   318  7133 V AudioCache: write(0xb16a7000, 4096)
09-13 15:14:02.176   318  7133 V AudioCache: memcpy(0xaf035000, 0xb16a7000, 4096)
09-13 15:14:02.176   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-13 15:14:02.176   318  7133 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 15:14:02.176   318  7133 V AwesomePlayer: postAudioEOS() 
09-13 15:14:02.176   318  7133 V AudioCache: write(0xb16a7000, 280)
09-13 15:14:02.177   318  7133 V AudioCache: memcpy(0xaf036000, 0xb16a7000, 280)
09-13 15:14:02.178   318  7130 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 15:14:02.178   318  7130 V AwesomePlayer: onStreamDone
09-13 15:14:02.178   318  7130 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 15:14:02.178   318  7130 V AudioCache: notify(0xb1432440, 2, 0, 0)
09-13 15:14:02.178   318  7130 V AudioCache: playback complete
09-13 15:14:02.178   318  7130 V AwesomePlayer: pause_l() 
09-13 15:14:02.178   318  7130 V AudioCache: notify(0xb1432440, 7, 0, 0)
09-13 15:14:02.178   318  7130 V AudioCache: ignored
09-13 15:14:02.178   318  7130 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:02.178   318  7130 D AudioPlayer: Pause Playback at 1068125
09-13 15:14:02.178   318   318 V AudioCache: wait - success
09-13 15:14:02.178   318   318 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 15:14:02.179   318   318 V AwesomePlayer: reset_l() 
09-13 15:14:02.179   318   318 V AudioCache: notify(0xb1432440, 8, 0, 0)
09-13 15:14:02.179   318   318 V AudioCache: ignored
09-13 15:14:02.179   318   318 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:02.179   318   318 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-13 15:14:02.179   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 15:14:02.179   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 15:14:02.179   318   318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 15:14:02.179   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 15:14:02.179   318  7,132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57ff420 on port 1
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-13 15:14:02.179   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:02.180   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 15:14:02.180   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 15:14:02.180   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 15:14:02.180   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 15:14:02.180   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-13 15:14:02.180   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 15:14:02.180   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 15:14:02.180   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 15:14:02.180   318   318 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-13 15:14:02.181   318   318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-13 15:14:02.181   318   318 D AudioPlayer: AudioPlayer releasing audio source
09-13 15:14:02.181   318   318 D AudioPlayer: AudioPlayer done releasing audio source
09-13 15:14:02.181   318   318 V AwesomePlayer: reset_l() 
09-13 15:14:02.181   318   318 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:02.181   318   318 V AwesomePlayer: ~AwesomePlayer call
09-13 15:14:02.181   318   318 V AwesomePlayer: reset_l() 
09-13 15:14:02.181   318   318 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:02.181  7025  7129 V SoundPool: close(31)
09-13 15:14:02.181  7025  7129 V SoundPool: pointer = 0x9fe88000, size = 205080, sampleRate = 48000, numChannels = 2
,09-13 15:14:02.185  7101  7101 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:02.189  7101  7101 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 15:14:02.189  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 15:14:02.189  7101  7101 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 15:14:02.189  7101  7101 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 15:14:02.190  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 15:14:02.190  7101  7101 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:02.190  7101  7101 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 15:14:02.194  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3495
09-13 15:14:02.197  7042  7042 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-13 15:14:02.381  6745  6745 I UEI.SmartControl: Supports setup maps: true
,09-13 15:14:02.383  6745  6745 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 15:14:02.383  6745  6745 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-13 15:14:02.383  6745  6745 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 15:14:02.383  6745  6745 I UEI.SmartControl: ### init IR Blaster...
09-13 15:14:02.386  6745  6745 D serial_port: Configuring serial port
09-13 15:14:02.387  6745  6745 E UEI.SmartControl: UEIBLaster setting for 616
09-13 15:14:02.387  6745  6745 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 15:14:02.387  6745  6745 I UEI.SmartControl: configuring settings for MAXQ616
09-13 15:14:02.387  6745  6745 I UEI.SmartControl: Get version...
09-13 15:14:02.401  6745  7135 D UEI.SmartControl: serial port data available: 21
,09-13 15:14:02.427  6745  6745 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 15:14:02.427  6745  6745 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-13 15:14:02.427  6745  6745 I UEI.SmartControl: QS saving settings...
,09-13 15:14:02.430  6745  6745 D UEI.SmartControl: IR Blaster version: 25672567
09-13 15:14:02.444  6745  7135 D UEI.SmartControl: serial port data available: 4
,09-13 15:14:02.474  6745  7141 I UEI.SmartControl: Device manager: loading config....
,09-13 15:14:02.481  6745  7141 D UEI.SmartControl: ----------- loading internal config...
09-13 15:14:02.481  6745  6745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 15:14:02.483  6745  6745 E UEI.SmartControl: Services init done
09-13 15:14:02.483  6745  6745 D UEI.SmartControl: QS Service init finished
09-13 15:14:02.485  6745  6745 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 15:14:02.485  6745  6745 D UEI.SmartControl: QS Service version code: 201091
09-13 15:14:02.486  6745  6745 D UEI.SmartControl: Service requested: Control
,09-13 15:14:02.489  6745  7141 E UEI.SmartControl: Loading SETTINGS...
09-13 15:14:02.491  6745  6745 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 15:14:02.493  7025  7025 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 15:14:02.494  6745  6761 I UEI.SmartControl: ------ IControl API: 11
09-13 15:14:02.494  6745  6761 D UEI.SmartControl: File observer start...
09-13 15:14:02.495  6745  6761 E UEI.SmartControl: IR Port is disabled: false
09-13 15:14:02.495  6745  6761 D UEI.SmartControl: Starting file observer...
09-13 15:14:02.495  6745  6745 D UEI.SmartControl: Internal service binding...
09-13 15:14:02.496  6745  6761 I UEI.SmartControl: Registering callback...
09-13 15:14:02.498  6745  6760 I UEI.SmartControl: ------ IControl API: 19
,09-13 15:14:02.500  6745  7141 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 15:14:02.502  6745  6760 I UEI.SmartControl: Registering Services Ready callback...
09-13 15:14:02.514  6745  7140 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 15:14:02.516  7025  7040 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 15:14:02.517  6745  7140 D UEI.SmartControl: -----service ready thread exits
09-13 15:14:02.518  7025  7127 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 15:14:02.518  7025  7127 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,09-13 15:14:02.519  7025  7025 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 15:14:02.520  7025  7025 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 15:14:02.520  6745  6761 I UEI.SmartControl: ------ IControl API: 8
09-13 15:14:02.523  7025  7025 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 15:14:02.524  7025  7025 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 15:14:02.525  7025  7025 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 15:14:02.525  7025  7025 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 15:14:02.527  7025  7025 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 15:14:02.528  7025  7025 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,09-13 15:14:02.532  7025  7025 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-13 15:14:02.535  7025  7025 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 15:14:02.537  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 15:14:02.539  7025  7025 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 15:14:02.540  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 15:14:02.542  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-13 15:14:02.546  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-13 15:14:02.548  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,09-13 15:14:02.551  7025  7025 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473772442550]
09-13 15:14:02.560  7025  7025 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-13 15:14:02.562  1032  2038 I ActivityManager: Killing 6536:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-13 15:14:02.590  7025  7143 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-13 15:14:02.651  1032  2038 I ActivityManager: Killing 6504:com.lge.email/u0a23 (adj 15): empty #18
,09-13 15:14:02.720  1032  2023 W libprocessgroup: failed to open /acct/uid_10027/pid_6536/cgroup.procs: No such file or directory
,09-13 15:14:02.730  1032  1982 W libprocessgroup: failed to open /acct/uid_10023/pid_6504/cgroup.procs: No such file or directory
09-13 15:14:02.734  7025  7025 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-13 15:14:02.738  7025  7025 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 15:14:02.738  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-13 15:14:02.738  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-13 15:14:02.739  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-13 15:14:02.739  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-13 15:14:02.739  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-13 15:14:02.749  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-13 15:14:03.546  1032  1943 D WifiServiceImplEx: setWifiEnabled: true pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 15:14:03.555  1032  1943 D WifiService: setWifiEnabled: true pid=6853, uid=10118
09-13 15:14:03.555  1032  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 15:14:03.575  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 15:14:03.575  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 15:14:03.575  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,09-13 15:14:03.580  1032  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 15:14:03.580  1032  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 15:14:03.583  1032  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 15:14:03.583  1032  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 15:14:03.583  1032  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 15:14:03.583  1032  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 15:14:03.583  1032  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 15:14:03.583  1032  1536 E WifiHW  : unknown target_country: EU , set to default
09-13 15:14:03.583  1032  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 15:14:03.583  1032  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 15:14:03.583  1032  1536 I WifiUtil: gEnableBmps=1
09-13 15:14:03.597  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:14:03.605  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-13 15:14:03.614  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:03.618  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:03.620  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:03.625  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-13 15:14:03.626  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:03.635  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:03.640  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:03.641  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 15:14:03.644  6384  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 15:14:03.655  5785  5785 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 15:14:03.664  5785  5785 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 15:14:03.689  2262  2262 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:14:03.751  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:14:03.760  1032  1598 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7164 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-13 15:14:03.768  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 15:14:03.768  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 15:14:03.831  7164  7164 I AppUp4:AppBoxCP: onCreate
,09-13 15:14:03.832  7164  7164 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-13 15:14:03.841  7164  7164 I AppUp4:DB:  setFingerPrint start
,09-13 15:14:03.842  7164  7164 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-13 15:14:03.851  7164  7164 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-13 15:14:03.851  7164  7164 I AppUp4:DB:  SDK version = 21
09-13 15:14:03.851  7164  7164 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-13 15:14:03.855  7164  7164 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-13 15:14:03.856  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 15:14:03.856  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:03.859  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 15:14:03.859  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 15:14:03.866  7164  7164 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 15:14:03.920  7164  7164 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 15:14:03.920  7164  7164 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:03.932  7164  7164 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37329eff
09-13 15:14:03.932  7164  7164 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 15:14:03.933  7164  7164 D AppUp4:CustFacade: isPhone : true
09-13 15:14:03.934  7164  7164 D AppUp4:CustModeStarterReceiver: begin check event
09-13 15:14:03.935  7164  7164 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-13 15:14:03.936  7164  7164 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-13 15:14:03.938  7164  7185 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-13 15:14:03.938  7164  7185 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-13 15:14:03.938  7164  7185 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-13 15:14:03.944  1032  2349 I ActivityManager: Killing 6611:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-13 15:14:04.004  1032  1597 W libprocessgroup: failed to open /acct/uid_10061/pid_6611/cgroup.procs: No such file or directory
09-13 15:14:04.005  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:04.006  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 15:14:04.009  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 15:14:04.021  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 15:14:04.030  4728  7188 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 15:14:04.039  4728  7190 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:04.040  4728  7190 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 15:14:04.104  1032  1996 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7193 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 15:14:04.186  7193  7193 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:14:04.186  7193  7193 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 15:14:04.191  7193  7193 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 15:14:04.192  7193  7193 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 15:14:04.288  7193  7193 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 15:14:04.303  7193  7193 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-13 15:14:04.360  7193  7193 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 15:14:04.380  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 15:14:04.386  1032  1094 D Tethering: InitialState.processMessage what=4
09-13 15:14:04.390  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 15:14:04.391   314   891 D SoftapController: Softap fwReload - Ok
09-13 15:14:04.392  1032  1536 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (804ms)
09-13 15:14:04.395   314   891 D CommandListener: Setting iface cfg
09-13 15:14:04.395   314   891 D CommandListener: Trying to bring down wlan0
09-13 15:14:04.396   314   891 D CommandListener: Clearing all IP addresses on wlan0
09-13 15:14:04.400  1032  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-13 15:14:04.402  1032  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 15:14:04.402  1032  1536 E WifiStateMachine: useWiFiOffloading() : false
09-13 15:14:04.402  1032  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 15:14:04.396  7218  7218 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:04.405  1032  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 15:14:04.405  1032  1536 D WifiMonitor: connecting to supplicant
09-13 15:14:04.396  7218  7218 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:04.411  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 15:14:04.412  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:04.414  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 15:14:04.415  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:04.416  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:04.436  7193  7193 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:04.436  7193  7193 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:04.442  7218  7218 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-13 15:14:04.474  7218  7218 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 15:14:04.474  7218  7218 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-13 15:14:04.550  7193  7193 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 15:14:04.560  7218  7218 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 15:14:04.581  3168  3168 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-13 15:14:04.581  3168  3168 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:04.581  3168  3168 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 15:14:04.582  7193  7193 I HubEmail: JNI_OnLoad()
09-13 15:14:04.582  7193  7193 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 15:14:04.582  7193  7193 I HubEmail: registerNatives()
09-13 15:14:04.582  7193  7193 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 15:14:04.582  7193  7193 I HubEmail: registerNativeMethods()
09-13 15:14:04.582  7193  7193 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 15:14:04.583  7193  7193 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-13 15:14:04.631  1032  1996 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7232 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-13 15:14:04.637  7218  7218 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-13 15:14:04.641  7193  7231 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:04.642  7063  7228 W FormManager: Network not available. Please check & try again.
09-13 15:14:04.643  7218  7218 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-13 15:14:04.646  1032  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 15:14:04.647  1032  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 15:14:04.647  1032  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 15:14:04.648  1032  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 15:14:04.648  1032  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:04.649  1032  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:04.649  1032  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:04.649  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,09-13 15:14:04.649  7063  7230 V FormManager: Network unavailable.
09-13 15:14:04.649  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 15:14:04.649  1032  7243 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 15:14:04.649  1032  7243 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 15:14:04.650  1032  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:04.650  1032  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 15:14:04.650  1032  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 15:14:04.651  1032  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 15:14:04.651  1032  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 15:14:04.651  1032  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 15:14:04.652  1032  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 15:14:04.652  1032  1536 E WifiStateMachine: useWiFiOffloading() : false
09-13 15:14:04.652  1032  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 15:14:04.652  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:04.652  7063  7230 V FormManager: Network unavailable.
09-13 15:14:04.652  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 15:14:04.652  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:04.652  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:04.652  1032  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 15:14:04.652  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 15:14:04.652  1032  1536 D WifiNative-wlan0: SET update_config 1: returned true
09-13 15:14:04.652  1032  1536 D WifiConfigStore: Loading config and enabling all networks 
09-13 15:14:04.653  1032  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 15:14:04.653  1032  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 15:14:04.653  1966  1966 D WfdService: Waiting for WifiP2p enabling
09-13 15:14:04.653  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:04.655  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 15:14:04.655  1032  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 15:14:04.656  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:04.656  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:04.656  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:04.656  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:04.656  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:04.656  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:04.656  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:04.656  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:04.656  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:04.656  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:04.656  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:04.657  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:04.657  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:04.657  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:04.657  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:04.657  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:04.657  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:04.657  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:04.657  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:04.657  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:04.657  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple adv,ertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:14:04.657  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:04.660  1032  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 15:14:04.661  1032  2070 I ActivityManager: Killing 6653:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-13 15:14:04.669  1032  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 15:14:04.669  1032  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 15:14:04.708  1032  1536 D WifiStateMachine: enableVerboseLogging : level 2
09-13 15:14:04.708  1032  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,09-13 15:14:04.708  1032  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 15:14:04.708  1032  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,09-13 15:14:04.709  1032  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 15:14:04.709  1032  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 15:14:04.709  1032  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 15:14:04.709  1032  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 15:14:04.710  1032  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 15:14:04.710  1032  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 15:14:04.710  1032  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 15:14:04.710  1032  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 15:14:04.711  1032  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 15:14:04.711  1032  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 15:14:04.711  1032  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 15:14:04.711  1032  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 15:14:04.712  1032  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 15:14:04.712  1032  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 15:14:04.712  1032  1536 D WifiNative-HAL: Setting external_sim to 1
09-13 15:14:04.712  1032  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
,09-13 15:14:04.712  1966  1966 D WfdsService: Supplicant Connection state is changed : true
09-13 15:14:04.712  1032  1982 W libprocessgroup: failed to open /acct/uid_10080/pid_6653/cgroup.procs: No such file or directory
,09-13 15:14:04.712  1966  2314 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 15:14:04.712  1966  2314 D WfdsService: Set the WFDS Monitor: true
09-13 15:14:04.712  1966  2314 D WfdsMonitor: WfdsMonitorThread create
09-13 15:14:04.713  1032  1536 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 15:14:04.713  1966  2314 D WfdsMonitor: WFDS Monitor is created and started
09-13 15:14:04.713  1032  1536 I WifiNative-HAL: startHal
09-13 15:14:04.713  1966  2314 D WfdsService: WiFi: Supplicant connection re-established
09-13 15:14:04.713  1032  1536 D wifi    : setting scan oui 0xaf574220
09-13 15:14:04.713  1032  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 15:14:04.713  1032  1536 I WifiNative-HAL: startHal
09-13 15:14:04.713  1032  1536 D wifi    : setting scan oui 0xaf574220
09-13 15:14:04.713  1032  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 15:14:04.714  1032  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 15:14:04.714  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 15:14:04.714  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 15:14:04.715  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 15:14:04.715  1966  7251 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 15:14:04.715  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 15:14:04.715  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 15:14:04.715  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 15:14:04.715  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 15:14:04.715  1966  7251 E CtrlSupplicant: Succeed to open control connection
09-13 15:14:04.715  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 15:14:04.716  1966  7251 E CtrlSupplicant: Succeed to open monitor connection
09-13 15:14:04.716  1966  7251 D WfdsMonitor: Supplicant connection established
09-13 15:14:04.716  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 15:14:04.716  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 15:14:04.716  1966  2314 D WfdsService: Connected to the supplicant for wfds
09-13 15:14:04.716  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 15:14:04.716  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 15:14:04.716  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 15:14:04.716  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 15:14:04.717  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 15:14:04.717  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 15:14:04.717  7218  7218 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 15:14:04.717  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 15:14:04.717  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 15:14:04.717  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 15:14:04.718  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 15:14:04.719  1032  1536 E WifiNative: : [185,676,922 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 15:14:04.719  1032  1536 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 15:14:04.719  1032  1536 D WifiNative-wlan0: RECONNECT: returned true
09-13 15:14:04.719  1032  1536 D WifiNative-wlan0: doString: [STATUS]
09-13 15:14:04.720  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 15:14:04.720  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 15:14:04.721  1032  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_de,vice_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 15:14:04.721  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 15:14:04.721  1032  1536 D WifiNative-wlan0: SET ps 1: returned true
09-13 15:14:04.721  1032  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.723   314   891 D CommandListener: Setting iface cfg
09-13 15:14:04.723   314   891 D CommandListener: Trying to bring up p2p0
09-13 15:14:04.723  1032  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 15:14:04.723  1032  1535 D LGWifiP2pService: P2pEnablingState
09-13 15:14:04.723  1032  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.723  1032  1535 D LGWifiP2pService: P2p socket connection successful
09-13 15:14:04.724  1032  1535 D LGWifiP2pService: P2pEnabledState
,09-13 15:14:04.726  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2,
09-13 15:14:04.726  1966  1966 D WfdsService: WifiP2pState is changed : true,
,09-13 15:14:04.726  1966  2314 D WfdsService: Receive the WFDS_ENABLE Method
09-13 15:14:04.727  1966  2314 D WfdsService: Set the WFDS Monitor: true
09-13 15:14:04.727  1966  2314 D WfdsService: Connected to the supplicant for wfds
09-13 15:14:04.727  1966  2314 D WfdsJNI : doCommand: WFDS_SET TRUE
,09-13 15:14:04.727  7218  7218 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 15:14:04.728  1966  2314 D WfdsService: selectPreferredScanChannel [36]
09-13 15:14:04.728  1966  2314 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,09-13 15:14:04.729  1032  1535 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 15:14:04.729  1032  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 15:14:04.730  1032  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 15:14:04.730  1032  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 15:14:04.730  1032  1535 D WifiNative-p2p0: SET device_name G3: returned true,
09-13 15:14:04.731  1032  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 15:14:04.732  1966  1966 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 15:14:04.732  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 15:14:04.732  1032  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0,
09-13 15:14:04.732  1032  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.732  1032  1555 I WifiNative-HAL: startHal
09-13 15:14:04.732  1032  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf574220
,09-13 15:14:04.732  1032  1555 D wifi    : failed to get capabilities : -3
09-13 15:14:04.732  1032  1555 E WifiScanningService: could not get scan capabilities
09-13 15:14:04.732  1032  1032 D RttService: SCAN_AVAILABLE : 3
09-13 15:14:04.732  1032  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
,09-13 15:14:04.732  1032  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.732  1032  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 15:14:04.733  1032  1535 D LGWifiP2pService: before postfix = G3
09-13 15:14:04.733  1032  1535 D WifiServerServiceExt: postfix byte check : 2
,09-13 15:14:04.733  1032  1535 D LGWifiP2pService: after postfix = G3
09-13 15:14:04.733  1032  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 15:14:04.733  1966  1966 D WfdsService: isConnected: false
09-13 15:14:04.733  1032  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 15:14:04.733  1032  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
,09-13 15:14:04.733  1032  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 15:14:04.733  1032  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 15:14:04.733  1032  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 15:14:04.733  1032  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
,09-13 15:14:04.734  1032  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 15:14:04.734  1032  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 15:14:04.734  1032  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 15:14:04.734  1032  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,09-13 15:14:04.734  1032  1535 D WifiNative-HAL: p2pGetDeviceAddress
09-13 15:14:04.734  1032  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 15:14:04.734  1032  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 15:14:04.734  1032  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1,
09-13 15:14:04.735  7218  7218 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 15:14:04.735  1032  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 15:14:04.736  1032  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 15:14:04.736  1032  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
,09-13 15:14:04.736  1032  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 15:14:04.736  1966  1966 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 15:14:04.736  1966  1966 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 15:14:04.737  1966  1966 D WfdsService: Update P2p Interface State: 3
09-13 15:14:04.737  1032  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 15:14:04.737  1032  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,09-13 15:14:04.738  1032  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 15:14:04.738  1032  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 15:14:04.738  7218  7218 E wpa_supplicant: disconnect_rssi_lvl: -100
,09-13 15:14:04.738  1032  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 15:14:04.738  1032  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 15:14:04.739  1032  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 15:14:04.739  1032  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 15:14:04.740  1032  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 15:14:04.740  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 15:14:04.740  1032  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 15:14:04.740  1032  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 15:14:04.762  1032  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
,09-13 15:14:04.762  1032  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 15:14:04.762  1032  1535 D LGWifiP2pService: InactiveState
09-13 15:14:04.762  1032  1535 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.762  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,09-13 15:14:04.762  1032  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 15:14:04.763  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 15:14:04.764  7218  7218 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:04.764  1032  7243 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 15:14:04.764  1032  7243 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:04.764  1032  7243 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:04.764  1032  7243 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:04.765  1966  7251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 15:14:04.765  7218  7218 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 15:14:04.765  7218  7218 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.765  1966  7251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:04.766  1032  7243 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:04.766  1032  7243 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.766  1032  7243 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.766  1032  7243 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.766  1032  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 15:14:04.766  1032  1535 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.766  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.766  7218  7218 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.766  1032  1535 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.767  1966  7251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:04.767  1032  1535 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.767  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.767  1032  1535 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.767  1032  7243 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:04.767  1032  1535 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.767  1032  7243 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.767  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.767  1032  1535 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.767  1966  2314 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 15:14:04.767  1032  1535 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.767  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.767  1032  1535 D LGWifiP2pService: DefaultState{ when=-,5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.768  1032  7243 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.768  1032  1032 E WifiServerServiceExt: No p2p device connected
09-13 15:14:04.768  1032  7243 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.768  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 15:14:04.769  7218  7218 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:04.769  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 15:14:04.769  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:04.770  1032  7243 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:04.770  1032  7243 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:04.770  7218  7218 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 15:14:04.770  7218  7218 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.770  1032  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 15:14:04.770  1032  7243 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:04.770  1032  7243 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.771  1032  7243 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.771  1032  7243 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.771  1032  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 15:14:04.771  1032  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 15:14:04.771  7218  7218 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.771  1032  7243 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:04.771  1032  7243 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.771  1032  7243 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:04.771  1032  7243 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-13 15:14:04.771  1032  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 15:14:04.771  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 15:14:04.771  1032  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.772  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:04.772  1966  7251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:04.772  1966  7251 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:04.772  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 15:14:04.772  7218  7218 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 15:14:04.772  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,09-13 15:14:04.772  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 15:14:04.772  1032  7243 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 15:14:04.772  1032  7243 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 15:14:04.773  1032  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 15:14:04.773  1032  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 15:14:04.774  1032  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 15:14:04.774  1032  1536 D WifiNative-wlan0: doBoolean: SCAN
09-13 15:14:04.774  1032  1536 D WifiNative-wlan0: SCAN: returned false
,09-13 15:14:04.775  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=185733  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-13 15:14:04.776  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=185735  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING,
09-13 15:14:04.776  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:04.776  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:04.777  1032  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE,
09-13 15:14:04.778  1032  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 15:14:04.778  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 15:14:04.778  1032  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 15:14:04.778  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:04.778  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 15:14:04.779  1032  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 15:14:04.779  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 15:14:04.779  1032  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 15:14:04.780  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:04.780  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 15:14:04.795  7232  7232 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 15:14:04.795  7232  7232 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:04.801  7232  7232 D PhoneMonitor: Register our PhoneStateListener
09-13 15:14:04.812  7232  7232 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 15:14:04.814  7232  7232 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 15:14:04.826  7232  7232 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-13 15:14:04.827  7232  7232 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-13 15:14:04.828  7232  7232 D TelephonyAutoProfiling: [parse] Load xml
09-13 15:14:04.831  7232  7232 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
,09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-13 15:14:04.831  7232  7232 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-13 15:14:04.831  7232  7232 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-13 15:14:04.840  7232  7232 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-13 15:14:04.854  1032  1048 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7254 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:14:04.855  1032  1048 I ActivityManager: Killing 6674:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-13 15:14:04.919  1032  1948 W libprocessgroup: failed to open /acct/uid_10097/pid_6674/cgroup.procs: No such file or directory
09-13 15:14:05.027  1032  2350 I art     : Explicit concurrent mark sweep GC freed 78461(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.223ms total 113.724ms
,09-13 15:14:05.250  1032  1048 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7275 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-13 15:14:05.255  1032  1048 I ActivityManager: Killing 6707:com.lge.eula/1000 (adj 15): empty #17
09-13 15:14:05.293  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 15:14:05.293  1032  7243 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 15:14:05.293  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 15:14:05.293  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-13 15:14:05.293  1032  7243 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,09-13 15:14:05.294  7218  7218 E wpa_supplicant: USIM:  scard_init function
09-13 15:14:05.295  7218  7218 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-13 15:14:05.297  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 15:14:05.297  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 15:14:05.297  1032  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-13 15:14:05.299  1032  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-13 15:14:05.300  1032  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-13 15:14:05.301  1032  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-13 15:14:05.302  1032  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 15:14:05.311  1032  1948 W libprocessgroup: failed to open /acct/uid_1000/pid_6707/cgroup.procs: No such file or directory
,09-13 15:14:05.322  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=186281  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 15:14:05.331  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:05.332  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 15:14:05.333  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:05.333  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.333  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.333  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 15:14:05.336  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=186295  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 15:14:05.344  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.344  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.344  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-13 15:14:05.345  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:05.345  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 15:14:05.353  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:05.354  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:05.355  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:05.415  7218  7218 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 15:14:05.420  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,09-13 15:14:05.420  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 15:14:05.420  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 15:14:05.420  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 15:14:05.420  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:05.420  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 15:14:05.423  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=186381  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 15:14:05.424  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=186383  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 15:14:05.426  1032  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186384
09-13 15:14:05.426  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:05.426  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 15:14:05.427  7218  7218 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 15:14:05.427  7218  7218 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 15:14:05.427  1032  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186385
09-13 15:14:05.427  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 15:14:05.428  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 15:14:05.428  1032  7243 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 15:14:05.428  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 15:14:05.428  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 15:14:05.429  1032  7243 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 15:14:05.430  1032  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186388
09-13 15:14:05.431  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186390
09-13 15:14:05.433  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:05.433  1032  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=186391
09-13 15:14:05.433  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 15:14:05.435  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=186393  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-13 15:14:05.449  1032  1982 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7292 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:14:05.450  1032  1982 I ActivityManager: Killing 5600:com.lge.bnr/1000 (adj 15): empty #17
09-13 15:14:05.499  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 15:14:05.499  1032  1996 W libprocessgroup: failed to open /acct/uid_1000/pid_5600/cgroup.procs: No such file or directory
09-13 15:14:05.511  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=186469  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 15:14:05.513  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=186471  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 15:14:05.514  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=186472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 15:14:05.515  1032  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=186474
09-13 15:14:05.516  1032  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=186475
09-13 15:14:05.517  1032  1536 D WifiNative-wlan0: doString: [STATUS]
09-13 15:14:05.518  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:05.518  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 15:14:05.518  1032  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-13 15:14:05.523  1032  1536 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 15:14:05.536  7292  7292 I art     : Almond Protected OAT
,09-13 15:14:05.548  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:05.548  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 15:14:05.550  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:05.551  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.552  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.552  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 15:14:05.558  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.558  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.558  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 15:14:05.558  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:05.558  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 15:14:05.570  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:05.570  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 15:14:05.571  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:05.592  7292  7292 D WeatherApplication: removeAccount
,09-13 15:14:05.593  7292  7292 D WeatherApplication: Account.length = 0
09-13 15:14:05.593  7292  7292 E WeatherApplication: OPERATOR:OPEN
09-13 15:14:05.594  1032  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:05.594  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 15:14:05.594  1032  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:05.599  7292  7292 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:5
09-13 15:14:05.603  7292  7292 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 15:14:05.603  7292  7292 D Weather.Utils: 2 : All the weather widget is gone.
09-13 15:14:05.605  7292  7292 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-13 15:14:05.609  7292  7292 D WeatherAncestor: connectivity changed - connection : true
09-13 15:14:05.610  7292  7292 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-13 15:14:05.624  7292  7292 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 15:14:05.624  7292  7292 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-13 15:14:05.627  7292  7292 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-13 15:14:05.649  7292  7292 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 15:14:05.649  7292  7292 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:5
,09-13 15:14:05.701  1032  1943 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7310 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:14:05.702  1032  1943 I ActivityManager: Killing 2219:com.lge.music/u0a34 (adj 15): empty #17
,09-13 15:14:05.723   318  1384 V AudioFlinger: 2219 died, releasing its sessions
09-13 15:14:05.723   318  1384 V AudioFlinger:  pid 1877 @ 0
09-13 15:14:05.723   318  1384 V AudioFlinger:  pid 3168 @ 1
09-13 15:14:05.723   318  1384 V AudioFlinger:  pid 3168 @ 2
,09-13 15:14:05.809  1032  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 15:14:05.810  1032  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-13 15:14:05.810  1032  1048 W libprocessgroup: failed to open /acct/uid_10034/pid_2219/cgroup.procs: No such file or directory
,09-13 15:14:05.835  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:05.835  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 15:14:05.838  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.839  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.839  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 15:14:05.841  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:05.841  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.841  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.842  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 15:14:05.846  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:05.846  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:05.849  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:05.852  1032  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 15:14:05.852  1032  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:14:05.852  1032  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 15:14:05.853  1032  1543 D ConnectivityService: Got NetworkAgent Messenger
09-13 15:14:05.853  1032  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 15:14:05.853  1032  1543 D ConnectivityService: NetworkAgent connected
09-13 15:14:05.854  1032  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 15:14:05.854  1032  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 15:14:05.860  1032  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 15:14:05.861  1032  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 15:14:05.861  1032  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 15:14:05.861  1032  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 15:14:05.861  1032  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 15:14:05.866  1032  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-13 15:14:05.869   314   891 D CommandListener: Setting iface cfg
09-13 15:14:05.873  1032  1536 E WifiStateMachine: Start Dhcp Watchdog 2
09-13 15:14:05.874  1032  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=186832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:05.875  1032  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=186833  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:05.875  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=186834  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:05.876  1032  7328 D DhcpStateMachine: StoppedState
09-13 15:14:05.876  1032  7328 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:05.876  1032  7328 D DhcpStateMachine: WaitBeforeStartState
09-13 15:14:05.877  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:05.878  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 15:14:05.879  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:05.879  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 15:14:05.881  1032  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=186839  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-13 15:14:05.881  1032  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=186840  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:05.882  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=186840  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:05.883  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:05.883  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:05.884  1032  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:05.885  1032  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:05.885  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:05.886  1032  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:05.886  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 15:14:05.887  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 15:14:05.888  1032  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 15:14:05.888  1032  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 15:14:05.889  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 15:14:05.889  1032  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 15:14:05.890  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:140487] from screen [on:0 period:598663362] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 15:14:05.891  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:598663363] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 15:14:05.891  1032  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 15:14:05.895  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 15:14:05.897  1032  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-13 15:14:05.898  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:05.898  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:05.899  1032  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:05.899  1032  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:05.899  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:05.900  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:05.901  1032  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 15:14:05.902  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:05.902  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 15:14:05.902  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=115,0,0
09-13 15:14:05.903  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=115,0,0
09-13 15:14:05.903  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 15:14:05.903  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 15:14:05.904  1032  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 15:14:05.904  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 15:14:05.904  1032  1536 D WifiNative-wlan0: SET ps 0: returned true
09-13 15:14:05.904  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 15:14:05.905  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 15:14:05.905  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 15:14:05.905  1032  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 15:14:05.905  1032  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 15:14:05.905  1032  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3147c9bf target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:05.905  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3147c9bf target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:05.905  1032  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 15:14:05.905  1032  7328 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:05.905  1032  7328 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 15:14:05.906   314   891 D CommandListener: Setting iface cfg
09-13 15:14:05.907   314   891 D CommandListener: Trying to bring up wlan0
,09-13 15:14:05.910  1032  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 15:14:05.911  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:05.911  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 15:14:05.912  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 15:14:05.913  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
,09-13 15:14:05.913  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 15:14:05.913  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 15:14:05.913  1032  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:05.913  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:05.914  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 15:14:05.914  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 15:14:05.914  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 15:14:05.914  1032  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 15:14:05.914  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 15:14:05.932  1032  1536 D WifiNative-wlan0: SET ps 1: returned true
09-13 15:14:05.933  1032  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,09-13 15:14:05.933  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:05.934  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:05.934  1032  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:05.935  1032  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:05.936  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:05.936  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:05.938  1032  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 15:14:05.938  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 15:14:05.939  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 15:14:05.939  1032  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 15:14:05.940  1032  1543 D ConnectivityService: ignoring duplicate network state non-change
,09-13 15:14:05.944  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:05.944  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:05.945  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:05.949  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.949  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.949  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 15:14:05.951  1032  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 15:14:05.952  1032  1543 D ConnectivityService: Adding iface wlan0 to network 101
09-13 15:14:05.955  1032  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 15:14:05.966  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.967  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.967  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 15:14:05.967  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-13 15:14:05.969  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:05.969  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:05.972  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 15:14:05.972  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:05.975  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:05.975  1579  1579 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 15:14:05.975  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:05.978  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.979  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.979  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 15:14:05.979  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-13 15:14:05.985  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.985  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:05.986  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 15:14:05.988   278   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 15:14:05.988   278   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 15:14:05.988   278   456 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 15:14:05.989  7310  7335 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 15:14:05.992   278   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 15:14:05.992   278   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 15:14:05.992   278   456 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 15:14:05.993  1032  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 15:14:05.993  1032  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-13 15:14:05.994  1032  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 15:14:05.995  7310  7335 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 15:14:05.995   314   891 E Netd    : netlink response contains error (File exists)
09-13 15:14:05.996  1032  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-13 15:14:05.997  1032  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 15:14:05.997  1032  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-13 15:14:05.997  1032  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 15:14:05.998  1032  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 15:14:05.999  1032  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 15:14:05.999  1032  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 15:14:06.000  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.000  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 15:14:06.000  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.000  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 15:14:06.002  1032  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 15:14:06.002  1032  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:06.002   314  7341 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 15:14:06.002  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:06.002  1032  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:06.002  1032  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 15:14:06.002  1579  1579 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 15:14:06.002  1032  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 15:14:06.003  1032  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 15:14:06.003  1032  1543 D ConnectivityService: currentScore = 0, newScore = 20
09-13 15:14:06.003  1032  1543 D ConnectivityService:    accepting network in place of null
09-13 15:14:06.003  1032  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.003  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.003  1032  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.003  1032  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:06.004  1877  1877 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.004  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 15:14:06.005  1032  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 15:14:06.005  1032  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 15:14:06.005  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 15:14:06.005  1032  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:06.005  1032  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 15:14:06.006  1032  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 15:14:06.007  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 15:14:06.007  1032  1543 D ConnectivityService: validation of new default Network = false
,09-13 15:14:06.007  1032  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 15:14:06.007  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 15:14:06.007  1032  1543 D DSQN    : enableDataServiceNotify 
09-13 15:14:06.007  1032  1543 D DSQN    : start dsqn bin
09-13 15:14:06.007  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 15:14:06.007  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 15:14:06.015  1032  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 15:14:06.015  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.015  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:06.015  1032  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:06.016  1579  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 15:14:06.006  7342  7342 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:06.006  7342  7342 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:06.020  1032  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 15:14:06.029  7342  7342 E DSQN    : DSQN ssw
,09-13 15:14:06.039   278   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 15:14:06.039   278   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 15:14:06.039   278   456 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 15:14:06.042  7310  7344 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 15:14:06.045   278   456 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 15:14:06.045   278   456 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 15:14:06.045   278   456 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 15:14:06.045  7310  7344 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 15:14:06.046  1579  1579 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 15:14:06.047  1839  7348 I CheckinService: active receiver: enabled
09-13 15:14:06.048  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.048  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 15:14:06.061  1839  7348 I CheckinService: Preparing to send checkin request
09-13 15:14:06.062  1839  7348 I EventLogService: Accumulating logs since 1473772301647
09-13 15:14:06.064   314  7341 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 15:14:06.099   314  7341 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 15:14:06.105  1839  7348 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-13 15:14:06.107  1032  7328 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 15:14:06.107  1032  7328 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 15:14:06.107  1032  7328 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 15:14:06.106  7353  7353 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:06.106  7353  7353 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 15:14:06.116  7353  7353 I dhcpcd  : version 5.5.6 starting
09-13 15:14:06.118  7353  7353 E dhcpcd  : get_duid: m
09-13 15:14:06.118  7353  7353 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 15:14:06.118  7353  7353 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 15:14:06.124   314   890 D LGDataListener: argv[0]=dsqncommand
09-13 15:14:06.124   314   890 D LGDataListener: argv[1]=wlan0
09-13 15:14:06.124   314   890 D LGDataListener: argv[2]=1
09-13 15:14:06.124   314   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 15:14:06.124  1032  1092 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 15:14:06.124  1032  1092 D DSQN    : start to monitor internet connection
,09-13 15:14:06.151  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 13:14:06 GMT], X-Android-Received-Millis=[1473772446151], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473772446123]}
09-13 15:14:06.151  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 15:14:06.151  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-13 15:14:06.152  1032  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-13 15:14:06.152  1032  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 15:14:06.152  1032  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:06.152  1032  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:06.152  1032  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 15:14:06.152  1032  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-13 15:14:06.152  1032  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 15:14:06.152  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.152  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:06.153  1032  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:06.153  1032  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.153  1579  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 15:14:06.153  1032  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.153  1032  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:06.153  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 15:14:06.154  1877  1877 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.154  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 15:14:06.175  7353  7353 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 15:14:06.175  7353  7353 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 15:14:06.175  7353  7353 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 15:14:06.175  7353  7353 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 15:14:06.175  7353  7353 D dhcpcd  : wlan0: sending REQUEST (xid 0xfa44829e), next in 4.87 seconds
,09-13 15:14:06.194  1032  2350 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7374 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-13 15:14:06.203  1579  1579 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-13 15:14:06.204  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.205  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.209  7353  7353 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 15:14:06.220  7310  7310 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 15:14:06.228  7310  7310 I LibraryLoader: Loading: webviewchromium
09-13 15:14:06.231  7310  7310 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7200-7204)
09-13 15:14:06.232  7310  7310 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 15:14:06.235  7374  7374 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 15:14:06.235  7374  7374 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 15:14:06.237  7353  7353 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 15:14:06.237  7353  7353 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 15:14:06.238  7353  7353 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 15:14:06.238  7353  7353 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 15:14:06.238  7353  7353 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 15:14:06.238  7353  7353 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 15:14:06.238  7353  7353 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 15:14:06.238  7353  7353 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 15:14:06.238  7310  7310 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ce93da6}
09-13 15:14:06.247  7310  7310 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 15:14:06.248  7310  7310 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 15:14:06.257  7310  7310 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 15:14:06.258  7374  7374 I MultiDex: VM with version 2.1.0 has multidex support
09-13 15:14:06.258  7374  7374 I MultiDex: install
09-13 15:14:06.258  7374  7374 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-13 15:14:06.265  7374  7374 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-13 15:14:06.259  7310  7310 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 15:14:06.291  7310  7310 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-13 15:14:06.292  7310  7310 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-13 15:14:06.292  7310  7310 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-13 15:14:06.293   318  1383 V AudioPolicyService: registerClient() client 0xb558aa60, uid 10093
09-13 15:14:06.295  7310  7403 W AudioManagerAndroid: Requires BLUETOOTH permission
09-13 15:14:06.310  7310  7310 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 15:14:06.310  7310  7310 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 15:14:06.310  7310  7310 I Adreno-EGL: Build Date: 12/12/14 금
09-13 15:14:06.310  7310  7310 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 15:14:06.310  7310  7310 I Adreno-EGL: Remote Branch: 
09-13 15:14:06.310  7310  7310 I Adreno-EGL: Local Patches: 
09-13 15:14:06.310  7310  7310 I Adreno-EGL: Reconstruct Branch: 
,09-13 15:14:06.371  7310  7310 I NSApplication: Starting up...
,09-13 15:14:06.420  1032  2349 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7429 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-13 15:14:06.422  1032  2349 I ActivityManager: Killing 6572:com.android.vending/u0a44 (adj 15): empty #17
09-13 15:14:06.470  7374  7390 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 15:14:06.470  7374  7390 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 15:14:06.491  1032  1982 W libprocessgroup: failed to open /acct/uid_10044/pid_6572/cgroup.procs: No such file or directory
,09-13 15:14:06.509  1032  7328 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-13 15:14:06.510  1032  7328 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-13 15:14:06.511  1032  7328 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 15:14:06.511  1032  7328 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 15:14:06.511  1032  7328 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 15:14:06.511  1032  7328 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 15:14:06.511  1032  7328 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 15:14:06.511  1032  7328 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 15:14:06.511  1032  7328 D DhcpStateMachine: RunningState
09-13 15:14:06.543  7429  7429 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 15:14:06.584  1032  1943 D WifiServiceImplEx: setWifiEnabled: false pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 15:14:06.584  1032  1943 D WifiService: setWifiEnabled: false pid=6853, uid=10118
09-13 15:14:06.584  1032  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 15:14:06.609  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 15:14:06.609  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 15:14:06.609  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 15:14:06.609  1032  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,09-13 15:14:06.609  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 15:14:06.609  1032  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 15:14:06.610  1032  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 15:14:06.610  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 15:14:06.610  1032  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 15:14:06.610  1032  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 15:14:06.610  1032  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 15:14:06.611  1032  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 15:14:06.611  1032  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 15:14:06.624  1032  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 15:14:06.624  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 15:14:06.624  1032  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.624  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.624  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-13 15:14:06.624  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 15:14:06.624  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 15:14:06.625  1032  1536 D WifiNative-wlan0: SET ps 1: returned true
09-13 15:14:06.625   314   891 D CommandListener: Clearing all IP addresses on wlan0
09-13 15:14:06.625  1032  7328 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.641  1032  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 15:14:06.641  1032  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-13 15:14:06.642  1032  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:06.643  1032  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.643  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.643  1032  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2fa07fb5
09-13 15:14:06.643  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 15:14:06.644  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:06.644  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:06.645  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:06.645  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:06.645  1032  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 15:14:06.645  1032  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:06.646  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:06.646  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:06.647  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 15:14:06.648  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.651  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:06.652  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:06.652  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 15:14:06.652  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 15:14:06.652  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:06.652  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:06.652  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 15:14:06.652  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 15:14:06.652  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-13 15:14:06.652  1032  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.652  1032  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.653  1032  1535 D LGWifiP2pService: P2pDisablingState
09-13 15:14:06.653  1032  1535 D LGWifiP2pService: P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.653  1032  1535 D LGWifiP2pService: p2p socket connection lost
09-13 15:14:06.653  1032  1535 D LGWifiP2pService: P2pDisabledState
,09-13 15:14:06.654  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 15:14:06.655  1032  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 15:14:06.656  1032  1535 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.656  1032  1535 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.656  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 15:14:06.657  7218  7218 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 15:14:06.657  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 15:14:06.657  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 15:14:06.658  1032  1536 D WifiNative-wlan0: SET ps 1: returned true
09-13 15:14:06.660  1966  1966 D WfdsService: WifiP2pState is changed : false
09-13 15:14:06.660  1966  2314 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 15:14:06.660  1966  2314 D WfdsService: Set the WFDS Monitor: false
09-13 15:14:06.661  1966  2314 D WfdsMonitor: WFDS Monitor is stopped
09-13 15:14:06.661  1966  2314 D WfdsService: STATE : WfdsDisabledState - enter
09-13 15:14:06.661  1966  7251 D CtrlSupplicant: Received on exit socket, terminate
09-13 15:14:06.661  1966  7251 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 15:14:06.661  1966  7251 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 15:14:06.661  1966  7251 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 15:14:06.661  1966  2315 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 15:14:06.661  1966  2314 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 15:14:06.664  7448  7448 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 15:14:06.669  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:06.669  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:06.670  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.679   314   891 D CommandListener: Clearing all IP addresses on wlan0
09-13 15:14:06.680  1032  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 15:14:06.680  1032  1543 D DSQN    : disableDataServiceNotify
09-13 15:14:06.680  1032  1543 D DSQN    : stop dsqn bin
09-13 15:14:06.681  1032  1536 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 15:14:06.681  1032  1536 D WifiNative-p2p0: TERMINATE: returned true
,09-13 15:14:06.682  1032  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 15:14:06.682  1032  1536 E WifiStateMachine: useWiFiOffloading() : false
09-13 15:14:06.682  1032  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 15:14:06.682  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 15:14:06.684  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:06.684  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:06.684  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 15:14:06.687  1032  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 15:14:06.688  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.688  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:06.688  1032  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:06.688  1032  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 15:14:06.689  1032  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 15:14:06.689  1032  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 15:14:06.689  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 15:14:06.690  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 15:14:06.690  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 15:14:06.690  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:06.690  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:06.690  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 15:14:06.690  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 15:14:06.690  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.690  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.690  1032  7327 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 15:14:06.690  1579  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 15:14:06.691  1032  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:06.691  1032  1543 D ConnectivityService: sendStickyBroadcast: action=and,roid.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 15:14:06.691  1032  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 15:14:06.692  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:06.692  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:06.692  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:06.692  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:06.692  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:06.692  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:06.692  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:06.692  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:06.692  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:06.692  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:06.692  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:06.692  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.693  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 15:14:06.694  1032  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:06.694  1032  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.694  1032  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 15:14:06.694  1032  1543 D NetworkManagementService: Removing idletimer
09-13 15:14:06.694  1032  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:06.694  1032  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 15:14:06.694  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 15:14:06.694  1877  1877 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.695  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 15:14:06.695  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 15:14:06.695  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 15:14:06.695  1032  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:06.695  1032  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:06.695  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:06.695  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:06.695  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:06.695  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:06.695  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:06.695  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:06.695  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:06.695  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:06.695  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:06.695  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:06.695  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:06.696  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.698  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 15:14:06.698  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 15:14:06.698  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 15:14:06.698  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 15:14:06.698  1032  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-13 15:14:06.720  7448  7448 I dex2oat : dex2oat took 55.566ms (threads: 4)
09-13 15:14:06.727  1579  1579 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 15:14:06.728  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.728  7374  7390 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 15:14:06.728  7374  7390 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 15:14:06.728  7374  7390 I Adreno-EGL: Build Date: 12/12/14 금
09-13 15:14:06.728  7374  7390 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 15:14:06.728  7374  7390 I Adreno-EGL: Remote Branch: 
09-13 15:14:06.728  7374  7390 I Adreno-EGL: Local Patches: 
09-13 15:14:06.728  7374  7390 I Adreno-EGL: Reconstruct Branch: 
09-13 15:14:06.729  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 15:14:06.743  1579  1579 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 15:14:06.744  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 15:14:06.745  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:06.788  7218  7218 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 15:14:06.789  7218  7218 I wpa_supplicant: monitor socket send errors count : 1
09-13 15:14:06.789  7218  7218 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1966-4\x00 that cannot receive messages
09-13 15:14:06.790  1032  7243 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 15:14:06.790  1032  7243 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-13 15:14:06.796  7374  7390 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 15:14:06.796  7374  7390 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 15:14:06.796  7374  7390 I Adreno-EGL: Build Date: 12/12/14 금
09-13 15:14:06.796  7374  7390 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 15:14:06.796  7374  7390 I Adreno-EGL: Remote Branch: 
09-13 15:14:06.796  7374  7390 I Adreno-EGL: Local Patches: 
09-13 15:14:06.796  7374  7390 I Adreno-EGL: Reconstruct Branch: 
09-13 15:14:06.811  7218  7218 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 15:14:06.811  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 15:14:06.811  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 15:14:06.811  1032  7243 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 15:14:06.811  1032  7243 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 15:14:06.812  1032  1094 D Tethering: InitialState.processMessage what=4
09-13 15:14:06.812  1032  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=187770
09-13 15:14:06.812  7218  7218 W wpa_supplicant: USIM:  scard_deinit function
09-13 15:14:06.812  1032  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=187771
09-13 15:14:06.812  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:06.812  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 15:14:06.813  1032  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=187772  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 15:14:06.813  1032  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=187772  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 15:14:06.814  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 15:14:06.817  1032  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:06.818  1032  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:06.828  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 15:14:06.831  1032  7328 D DhcpStateMachine: StoppedState
09-13 15:14:06.831  1032  7328 D DhcpStateMachine: StoppedState{ when=-174ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:06.833  6384  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 15:14:06.834  1032  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 15:14:06.835  1032  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 15:14:06.842  2262  2262 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:14:06.851  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 15:14:06.851  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:06.851  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 15:14:06.851  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 15:14:06.853  7164  7164 I AppUp4:CustModeStarterReceiver: onReceive
09-13 15:14:06.857  7164  7164 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37329eff
09-13 15:14:06.857  7164  7164 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 15:14:06.857  7164  7164 D AppUp4:CustFacade: isPhone : true
09-13 15:14:06.857  7164  7164 D AppUp4:CustModeStarterReceiver: begin check event
09-13 15:14:06.858  7164  7164 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 15:14:06.863  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:06.863  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 15:14:06.864  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 15:14:06.866  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:06.872  4728  7472 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 15:14:06.874  7193  7193 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 15:14:06.891  7193  7476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 15:14:06.893  7063  7475 W FormManager: Network not available. Please check & try again.
09-13 15:14:06.897  3168  3168 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 15:14:06.898  7063  7477 V FormManager: Network unavailable.
09-13 15:14:06.898  3168  3168 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:06.898  3168  3168 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 15:14:06.901  7063  7477 V FormManager: Network unavailable.
09-13 15:14:06.906  7232  7232 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 15:14:06.906  7232  7232 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 15:14:06.911  4728  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:06.911  4728  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 15:14:06.916  7292  7292 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:6
09-13 15:14:06.921  7292  7292 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 15:14:06.921  7292  7292 D Weather.Utils: 2 : All the weather widget is gone.
,09-13 15:14:06.923  7292  7292 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 15:14:06.923  7292  7292 D WeatherAncestor: connectivity changed - connection : true
09-13 15:14:06.924  7292  7292 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6a2b315
09-13 15:14:06.924  7292  7292 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 15:14:06.924  7292  7292 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 15:14:06.924  7292  7292 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 15:14:06.924  7292  7292 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 15:14:06.924  7292  7292 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:6
09-13 15:14:06.938  7218  7218 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 15:14:06.938  1032  7243 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 15:14:06.938  1032  7243 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 15:14:06.938  1032  7243 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 15:14:06.939  1032  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-13 15:14:06.940  7374  7390 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 15:14:06.940  7374  7390 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 15:14:06.940  7374  7390 I Adreno-EGL: Build Date: 12/12/14 금
09-13 15:14:06.940  7374  7390 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 15:14:06.940  7374  7390 I Adreno-EGL: Remote Branch: 
09-13 15:14:06.940  7374  7390 I Adreno-EGL: Local Patches: 
09-13 15:14:06.940  7374  7390 I Adreno-EGL: Reconstruct Branch: 
09-13 15:14:06.941  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 15:14:06.941  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 15:14:06.941  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 15:14:06.941  6971  6971 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 15:14:06.941  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 15:14:06.942  6971  6971 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 15:14:06.942  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 15:14:06.942  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 15:14:06.942  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 15:14:06.942  6971  6971 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 15:14:06.942  6971  6971 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 15:14:06.948  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 15:14:06.952  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 15:14:06.954  7063  7480 W FormManager: Network not available. Please check & try again.
09-13 15:14:06.955  7063  7481 V FormManager: Network unavailable.
,09-13 15:14:06.957  7063  7481 V FormManager: Network unavailable.
09-13 15:14:06.958  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:06.970  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 15:14:06.973  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 15:14:06.975  7063  7483 W FormManager: Network not available. Please check & try again.
09-13 15:14:06.977  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:06.981  7063  7484 V FormManager: Network unavailable.
09-13 15:14:06.983  7063  7484 V FormManager: Network unavailable.
,09-13 15:14:06.989  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 15:14:06.989  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 15:14:06.990  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:06.992  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:06.994  4728  7485 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 15:14:06.997  4728  7486 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 15:14:06.997  4728  7486 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 15:14:07.015  1032  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 15:14:07.041  1032  1611 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7487 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-13 15:14:07.044  1032  1536 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 15:14:07.045  1032  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 15:14:07.045  1032  1536 E WifiStateMachine: useWiFiOffloading() : false
09-13 15:14:07.045  1032  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 15:14:07.045  1966  1966 D WfdsService: Supplicant Connection state is changed : false
09-13 15:14:07.045  1966  2314 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 15:14:07.045  1966  2314 D WfdsService: Set the WFDS Monitor: false
09-13 15:14:07.045  1966  2314 D WfdsMonitor: WFDS Monitor is stopped
09-13 15:14:07.047  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 15:14:07.048  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:07.050  2481  2481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:07.055  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 15:14:07.055  1032  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 15:14:07.055  1032  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 15:14:07.056  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:07.056  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:07.056  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:07.056  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:07.056  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:07.056  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:07.056  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:07.056  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:07.056  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:07.057  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:07.058  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:07.058  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:07.058  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:07.058  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:07.058  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:07.058  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:07.058  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:07.058  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:14:07.084   314  7505 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 15:14:07.085  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 15:14:07.086  1839  7348 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,09-13 15:14:07.098  1839  7348 I CheckinService: active receiver: disabled
,09-13 15:14:07.170  7487  7487 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-13 15:14:07.170  7487  7487 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-13 15:14:07.176  7487  7487 V [BNRBootReceiver]: Boot Receiver Return
09-13 15:14:07.177  7487  7487 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-13 15:14:07.183  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.197  1032  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=331883151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,09-13 15:14:07.208  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.221  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 15:14:07.236  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.237  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 15:14:07.240  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 15:14:07.246  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 15:14:07.253  6971  6971 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-13 15:14:07.261  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.282  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.284  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
09-13 15:14:07.292  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.313  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 15:14:07.314  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:07.320  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 15:14:07.324  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.333  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.339  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.346  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.346  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:07.347  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 15:14:07.351  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.359  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.365  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.376  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 15:14:07.377  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:07.378  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 15:14:07.381  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.388  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.396  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.406  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.406  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:07.407  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 15:14:07.416  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.427  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.435  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.445  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.446  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 15:14:07.446  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 15:14:07.451  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 15:14:07.461  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.473  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.476  6745  7142 D UEI.SmartControl: Internal timer expired: 4
09-13 15:14:07.476  6745  7142 D UEI.SmartControl: unbind internal service
09-13 15:14:07.488  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.488  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 15:14:07.489  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 15:14:07.498  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.516  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.528  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.545  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.545  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 15:14:07.552  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 15:14:07.560  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.572  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.583  6745  7136 D serial_port: close(fd = 24)
09-13 15:14:07.583  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.589  6745  7136 I UEI.SmartControl: Serial port is closed.
,09-13 15:14:07.597  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.597  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:07.599  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 15:14:07.604  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 15:14:07.609  6993  6993 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 15:14:07.619  1032  1542 D WifiService: New client listening to asynchronous messages
,09-13 15:14:07.620  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 15:14:07.629  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.636  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.645  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 15:14:07.645  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:07.647  7025  7025 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 15:14:07.648  7025  7025 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 15:14:07.648  7025  7025 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-13 15:14:07.653  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 15:14:07.661  6993  6993 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 15:14:07.663  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 15:14:07.668  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 15:14:07.677  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.686  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 15:14:07.687  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:07.688  7025  7025 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 15:14:07.689  7025  7025 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 15:14:07.690  7025  7025 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 15:14:07.693  1032  1996 I ActivityManager: Killing 6948:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-13 15:14:07.731  1032  2023 W libprocessgroup: failed to open /acct/uid_10037/pid_6948/cgroup.procs: No such file or directory
,09-13 15:14:07.739  2262  2262 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-13 15:14:07.756  2262  2262 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-13 15:14:07.757  2262  2262 D c       : Getting all permits...
09-13 15:14:07.757  2262  2262 D a       : Opening database...
,09-13 15:14:07.764  2262  2262 D a       : Opening database auth.proximity.permit_store...
09-13 15:14:07.765  2262  2262 D a       : Closing database...
09-13 15:14:07.780  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 15:14:07.788  6993  6993 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 15:14:07.788  6993  6993 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 15:14:07.788  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 15:14:07.792  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.800  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 15:14:07.809  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.809  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:07.812  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 15:14:07.816  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.819  6993  6993 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 15:14:07.819  6993  6993 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 15:14:07.819  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 15:14:07.823  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.830  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.843  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.843  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 15:14:07.845  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 15:14:07.850  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:07.855  6993  6993 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-13 15:14:07.855  6993  6993 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 15:14:07.855  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 15:14:07.859  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:07.869  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.877  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:07.878  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:07.880  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 15:14:07.890  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 15:14:07.896  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:14:07.901  7063  7514 W FormManager: Network not available. Please check & try again.
,09-13 15:14:07.903  7063  7515 V FormManager: Network unavailable.
09-13 15:14:07.907  7063  7515 V FormManager: Network unavailable.
,09-13 15:14:07.908  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.930  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 15:14:07.930  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 15:14:07.932  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 15:14:07.935  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:07.942  4728  7516 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 15:14:07.948  4728  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 15:14:07.948  6993  6993 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 15:14:07.948  4728  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 15:14:07.948  6993  6993 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 15:14:07.948  6993  6993 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 15:14:07.955  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 15:14:07.961  7063  7519 W FormManager: Network not available. Please check & try again.
,09-13 15:14:07.964  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:07.964  7063  7520 V FormManager: Network unavailable.
09-13 15:14:07.976  7063  7520 V FormManager: Network unavailable.
,09-13 15:14:07.989  2262  2262 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-13 15:14:08.009  7025  7025 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-13 15:14:08.009  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3495
09-13 15:14:08.010  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=331883151 [*alarm*], flags=0x0
,09-13 15:14:08.900  1032  1536 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:598666372] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 15:14:08.903  1032  1536 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:598666374] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 15:14:09.008  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:14:09.028  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:09.029  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-13 15:14:09.036  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:09.041  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:09.047  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 15:14:09.048  6384  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 15:14:09.063  5785  5785 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-13 15:14:09.087  2262  2262 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:14:09.119  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 15:14:09.119  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:09.119  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 15:14:09.119  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 15:14:09.126  7164  7164 I AppUp4:CustModeStarterReceiver: onReceive
09-13 15:14:09.130  7164  7164 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37329eff
09-13 15:14:09.130  7164  7164 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 15:14:09.130  7164  7164 D AppUp4:CustFacade: isPhone : true
09-13 15:14:09.131  7164  7164 D AppUp4:CustModeStarterReceiver: begin check event
09-13 15:14:09.131  7164  7164 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 15:14:09.136  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:09.137  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 15:14:09.142  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:09.148  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:09.157  7193  7193 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 15:14:09.182  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 15:14:09.183  4728  7541 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 15:14:09.188  4728  7549 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:09.188  4728  7549 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 15:14:09.232  7193  7553 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 15:14:09.238  3168  3168 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-13 15:14:09.238  3168  3168 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:09.238  3168  3168 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 15:14:09.238  3168  3168 D PhoneState: setPdpRejectCasuse : false
09-13 15:14:09.242  7232  7232 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 15:14:09.242  7232  7232 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 15:14:09.255  7292  7292 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:9
,09-13 15:14:09.258  7063  7555 W FormManager: Network not available. Please check & try again.
,09-13 15:14:09.258  7292  7292 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 15:14:09.258  7292  7292 D Weather.Utils: 2 : All the weather widget is gone.
09-13 15:14:09.258  7292  7292 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 15:14:09.259  7292  7292 D WeatherAncestor: connectivity changed - connection : true
09-13 15:14:09.259  7292  7292 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6a2b315
09-13 15:14:09.259  7063  7556 V FormManager: Network unavailable.
09-13 15:14:09.260  7292  7292 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 15:14:09.260  7292  7292 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 15:14:09.260  7292  7292 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 15:14:09.260  7292  7292 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 15:14:09.260  7292  7292 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:9
09-13 15:14:09.273  7063  7556 V FormManager: Network unavailable.
,09-13 15:14:09.611  1032  1948 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 15:14:09.612  1032  1948 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-13 15:14:09.659  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 15:14:09.659  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 15:14:09.660  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 15:14:09.662  1032  1094 D BluetoothManagerService: Message: 1
09-13 15:14:09.662  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-13 15:14:09.690  1032  1094 D BluetoothManagerService: Message: 20
09-13 15:14:09.690  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ec8c595:true
,09-13 15:14:09.693  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:09.698  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:09.701  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-13 15:14:09.704  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:09.708  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:09.710  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:09.713  7101  7101 D BluetoothAdapterState: make
09-13 15:14:09.718  7101  7101 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-13 15:14:09.719  7101  7101 I bluedroid-qcom: init
,09-13 15:14:09.723  7101  7571 I BluetoothAdapterState: Entering OffState
09-13 15:14:09.723  7101  7101 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 15:14:09.723  7101  7101 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 15:14:09.724  7101  7101 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 15:14:09.724  7101  7101 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 15:14:09.724  7101  7101 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-13 15:14:09.725  7101  7101 I bluedroid-qcom: get_profile_interface socket
09-13 15:14:09.725  7101  7101 I bluedroid-qcom: get_profile_interface map_client
09-13 15:14:09.727  7101  7575 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-13 15:14:09.729  7101  7575 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 15:14:09.726  7574  7574 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:09.726  7574  7574 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:09.747  7574  7574 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-13 15:14:09.747  7574  7574 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-13 15:14:09.747  7574  7574 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-13 15:14:09.751  7574  7574 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-13 15:14:09.753  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 15:14:09.755  6384  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 15:14:09.759  7574  7574 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-13 15:14:09.759  7574  7574 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-13 15:14:09.761  1032  1094 D Tethering: MasterInitialState.processMessage what=3
,09-13 15:14:09.764  5785  5785 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-13 15:14:09.769  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 15:14:09.769  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 15:14:09.770  7101  7575 D BluetoothAdapterProperties: Name is: G3
09-13 15:14:09.774  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:09.778  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:09.784  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-13 15:14:09.784  1032  1094 D BluetoothManagerService: Message: 40
09-13 15:14:09.784  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-13 15:14:09.785  7101  7118 I bluedroid-qcom: config_hci_snoop_log
09-13 15:14:09.785  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-13 15:14:09.785  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-13 15:14:09.793  7101  7571 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 15:14:09.793  7101  7571 D BluetoothAdapterProperties: Setting state to 11
09-13 15:14:09.793  7101  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-13 15:14:09.799  1032  1094 D BluetoothManagerService: Message: 60
09-13 15:14:09.799  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 15:14:09.800  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 15:14:09.803  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:09.805  1579  1579 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 15:14:09.809  7101  7571 I LGBluetoothServiceJni: classInitNative: succeeds
,09-13 15:14:09.818  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:09.820  6971  6971 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 15:14:09.821  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:09.827  7101  7571 D BluetoothBondStateMachine: make
,09-13 15:14:09.830  7101  7101 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 15:14:09.830  7101  7571 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:09.830  7101  7571 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-13 15:14:09.830  7101  7571 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:09.830  7101  7571 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 15:14:09.830  7101  7101 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:14:09.831  7101  7101 V BluetoothPbapReceiver: ***********state = 11
,09-13 15:14:09.831  7101  7571 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 15:14:09.832  7101  7586 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 15:14:09.834  7101  7571 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:09.836  2262  2262 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 15:14:09.843  7101  7101 D HeadsetService: Received start request. Starting profile...
09-13 15:14:09.843  7101  7101 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 15:14:09.844  7101  7101 D LGBluetoothHfpAdapter: Version 1.6
09-13 15:14:09.844  7101  7571 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 15:14:09.850  7101  7101 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 15:14:09.851  7101  7101 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 15:14:09.851  7101  7101 D HeadsetStateMachine: make
09-13 15:14:09.891  7101  7101 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:09.891  7101  7101 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:09.896  1032  1611 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7596 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-13 15:14:09.901  7101  7101 D HeadsetStateMachine: max_hf_connections = 1
09-13 15:14:09.901  7101  7101 I bluedroid-qcom: get_profile_interface handsfree
09-13 15:14:09.901  5785  5785 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-13 15:14:09.903  7101  7571 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:09.903  7101  7101 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-13 15:14:09.903   318  1383 V AudioPolicyService: registerClient() client 0xb558a720, uid 1002
09-13 15:14:09.904   318   318 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-13 15:14:09.904   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 15:14:09.904   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
,09-13 15:14:09.904  7101  7101 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 15:14:09.906   318  1384 V AudioFlinger: registerClient() client 0xb1433640, pid 7101
09-13 15:14:09.906   318  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:09.906   318  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:09.907  7101  7101 V ToneGenerator: Create Track: 0xb4928080
09-13 15:14:09.907  7101  7101 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-13 15:14:09.907  7101  7101 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-13 15:14:09.907  1032  2350 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:09.907  1032  2350 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:09.907  1877  4379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:09.907  1877  4379 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:09.907   318   318 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 15:14:09.907   318   318 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-13 15:14:09.907   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 15:14:09.907   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 15:14:09.907  7101  7101 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 15:14:09.907  1579  3197 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,09-13 15:14:09.907  1579  3197 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:09.907  7101  7587 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,09-13 15:14:09.907  3168  5298 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:09.907  3168  5298 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:09.907  7101  7587 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
,09-13 15:14:09.908   318  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:09.908   318  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:09.908  7101  7118 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:09.908  7101  7118 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-13 15:14:09.908  1032  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:09.908  1032  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:09.908  1579  1595 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:09.908  1579  1595 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:09.908  1877  1892 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:09.908  1877  1892 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:09.908  3168  3183 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:09.908  3168  3183 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:09.908   318  1383 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 15:14:09.909   318   318 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 15:14:09.909   318   318 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-13 15:14:09.909   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 15:14:09.909   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 15:14:09.909  7101  7101 V AudioSystem: getLatency() output 2, latency 50
09-13 15:14:09.909  7101  7101 V AudioSystem: getFrameCount() output 2, frameCount 960
09-13 15:14:09.909  7101  7101 V AudioTrack: createTrack_l() output 2 afLatency 50
09-13 15:14:09.910   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 15:14:09.910   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 15:14:09.910   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 15:14:09.910   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 15:14:09.910   318  1383 V AudioFlinger: createTrack() lSessionId: 22
09-13 15:14:09.911  7101  7101 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-13 15:14:09.913   318   318 V AudioFlinger: acquiring 22 from 7101, for 7101
09-13 15:14:09.913   318   318 V AudioFlinger:  added new entry for 22
09-13 15:14:09.913  7101  7101 V ToneGenerator: ToneGenerator INIT OK, time: 190886
09-13 15:14:09.913  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:09.914  7101  7593 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 15:14:09.914  7101  7593 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 15:14:09.914  7101  7593 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 15:14:09.914  7101  7593 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 15:14:09.915   318  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7101
09-13 15:14:09.915   318  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 15:14:09.915   318  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 15:14:09.915   318  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 15:14:09.915   318  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 15:14:09.915   318  1383 V voice   : voice_set_parameters: exit with code(0)
09-13 15:14:09.915   318  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 15:14:09.915   318  1383 V msm8,974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 15:14:09.915  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:09.915   318  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 15:14:09.915   318  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 15:14:09.915   318  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 15:14:09.915   318  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 15:14:09.915  7101  7593 V ToneGenerator: ToneGenerator destructor
09-13 15:14:09.915  7101  7593 V ToneGenerator: stopTone
09-13 15:14:09.915  7101  7593 V ToneGenerator: Delete Track: 0xb4928080
09-13 15:14:09.917  7101  7101 D A2dpService: Received start request. Starting profile...
09-13 15:14:09.917  7101  7593 V AudioTrack: ~AudioTrack, releasing session id from 7101 on behalf of 7101
09-13 15:14:09.918  7101  7101 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 15:14:09.918   318  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
09-13 15:14:09.918   318  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-13 15:14:09.918   318  1384 V AudioFlinger: PlaybackThread::Track destructor
09-13 15:14:09.918   318  1257 V AudioPolicyService: AudioCommandThread() waking up
09-13 15:14:09.918   318  1257 V AudioPolicyService: AudioCommandThread() processing release output 2
09-13 15:14:09.918   318  1384 V AudioFlinger: removeClient_l() pid 7101, calling pid 318
09-13 15:14:09.918   318  1257 V AudioPolicyManager: releaseOutput() 2
09-13 15:14:09.918   318  1257 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 15:14:09.918   318  1384 V AudioFlinger: releasing 22 from 7101 for 7101
09-13 15:14:09.918   318  1384 V AudioFlinger:  decremented refcount to 0
09-13 15:14:09.918   318  1384 V AudioFlinger: purging stale effects
09-13 15:14:09.919  7101  7101 V Avrcp   : make
09-13 15:14:09.919  7101  7101 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 15:14:09.919  7101  7101 I bluedroid-qcom: get_profile_interface avrcp
09-13 15:14:09.920  7101  7571 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:09.922   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 26.224ms
09-13 15:14:09.927  7101  7101 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 15:14:09.928  7101  7571 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:09.929  7101  7101 E AudioManager: No RCC entry present to update
09-13 15:14:09.929  7101  7101 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 15:14:09.930  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:09.931  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:09.931  7101  7101 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-13 15:14:09.931  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:09.932  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 15:14:09.932  7101  7101 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 15:14:09.936  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 15:14:09.936  7101  7571 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:09.941   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 18.220ms
,09-13 15:14:09.959   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 352us total 16.561ms
,09-13 15:14:09.976  7101  7571 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:09.990  2262  2262 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:14:09.998  7101  7571 V LGMDMManager: Create singleton instance
09-13 15:14:10.000  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 15:14:10.000  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:10.001  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 15:14:10.001  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 15:14:10.001  7101  7571 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 15:14:10.002  7164  7164 I AppUp4:CustModeStarterReceiver: onReceive
09-13 15:14:10.004  7164  7164 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37329eff
09-13 15:14:10.004  7164  7164 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 15:14:10.004  7164  7164 D AppUp4:CustFacade: isPhone : true
09-13 15:14:10.005  7164  7164 D AppUp4:CustModeStarterReceiver: begin check event
09-13 15:14:10.005  7164  7164 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-13 15:14:10.009  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:10.009  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 15:14:10.010  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:10.012  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:10.017  1032  2023 V SIM_STK : Menu title from STK is T-Mobile
09-13 15:14:10.017  1032  2023 V SIM_STK : Menu title from STK is T-Mobile
09-13 15:14:10.017  7193  7193 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-13 15:14:10.017  4728  7616 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 15:14:10.022  4728  7618 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:10.023  4728  7618 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 15:14:10.024  7596  7596 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 15:14:10.024  7596  7596 W LG Account v2.2: No ProfileInfo entries
09-13 15:14:10.024  7596  7596 I LG Account v2.2: isEnabled: false
09-13 15:14:10.024  7596  7596 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 15:14:10.024  7596  7596 I Feature : [Lifetracker]Country: EU
09-13 15:14:10.024  7596  7596 I Feature : [Lifetracker]Operator: OPEN
09-13 15:14:10.024  7596  7596 I Feature : [Lifetracker]Ranking support: false
09-13 15:14:10.025  7596  7596 I Feature : [Lifetracker]Comfort support: false
09-13 15:14:10.025  7596  7596 I Feature : [Lifetracker]Accessory: true
09-13 15:14:10.025  7596  7596 I Feature : [Lifetracker]Health device: true
09-13 15:14:10.025  7596  7596 I Feature : [Lifetracker]Extra Pedometer: false
09-13 15:14:10.025  7596  7596 I Feature : [Lifetracker]Blood glucose device: false
09-13 15:14:10.025  7596  7596 I Feature : [Lifetracker]Device Number: 3
09-13 15:14:10.034  6971  6971 D BluetoothPermissionRequest: onReceive
,09-13 15:14:10.036  7193  7620 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:10.040  6971  6971 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 15:14:10.044  3168  3168 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 15:14:10.044  3168  3168 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:10.045  3168  3168 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 15:14:10.047  7232  7232 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 15:14:10.047  7232  7232 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 15:14:10.051  7063  7623 W FormManager: Network not available. Please check & try again.
09-13 15:14:10.052  7063  7624 V FormManager: Network unavailable.
09-13 15:14:10.054  7063  7624 V FormManager: Network unavailable.
09-13 15:14:10.063  7292  7292 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:10
,09-13 15:14:10.064  7292  7292 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 15:14:10.064  7292  7292 D Weather.Utils: 2 : All the weather widget is gone.
09-13 15:14:10.064  7292  7292 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 15:14:10.065  7292  7292 D WeatherAncestor: connectivity changed - connection : true
09-13 15:14:10.065  7292  7292 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6a2b315
09-13 15:14:10.065  7292  7292 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 15:14:10.065  7292  7292 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 15:14:10.065  7292  7292 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 15:14:10.065  7292  7292 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 15:14:10.065  7292  7292 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:10
09-13 15:14:10.072  1032  1996 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 15:14:10.077  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-13 15:14:10.079  6384  6384 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 15:14:10.080  6384  6992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 15:14:10.080  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 15:14:10.081  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 15:14:10.081  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 15:14:10.081  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 15:14:10.081  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 15:14:10.081  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 15:14:10.081  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 15:14:10.081  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 15:14:10.081  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 15:14:10.081  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 15:14:10.081  7101  7101 I BluetoothA2dpServiceJni: classInitNative
09-13 15:14:10.081  7101  7101 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 15:14:10.081  7101  7101 D A2dpStateMachine: make
09-13 15:14:10.082  7101  7101 I bluedroid-qcom: get_profile_interface a2dp
09-13 15:14:10.082  7101  7627 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 15:14:10.084  7101  7101 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-13 15:14:10.084  7101  7101 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 15:14:10.084  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:10.084  7101  7101 D HeadsetStateMachine: Proxy object connected
09-13 15:14:10.085  7101  7626 D A2dpStateMachine: Enter Disconnected: -2
09-13 15:14:10.085  7101  7101 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 15:14:10.085  7101  7101 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 15:14:10.086  7101  7101 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 15:14:10.088  7101  7101 D HidService: Received start request. Starting profile...
09-13 15:14:10.088  7101  7101 I bluedroid-qcom: get_profile_interface hidhost
09-13 15:14:10.088  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
,09-13 15:14:10.090  2262  2262 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:10.091  7101  7101 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:10.091  7101  7593 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 15:14:10.091  7101  7101 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 15:14:10.091  7101  7593 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 15:14:10.091  7101  7593 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 15:14:10.092  7101  7101 D HealthService: Received start request. Starting profile...
09-13 15:14:10.093  7101  7101 I bluedroid-qcom: get_profile_interface health
09-13 15:14:10.093  7101  7101 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-13 15:14:10.094  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:10.094  7101  7101 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 15:14:10.095  7101  7101 D PanService: Received start request. Starting profile...
09-13 15:14:10.095  7101  7101 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-13 15:14:10.095  7101  7101 I bluedroid-qcom: get_profile_interface pan
09-13 15:14:10.099  7101  7101 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-13 15:14:10.099  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:10.100  7101  7101 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-13 15:14:10.102  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 15:14:10.102  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:10.102  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 15:14:10.103  7164  7164 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 15:14:10.103  7101  7101 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 15:14:10.103  7101  7101 D BtGatt.GattService: Received start request. Starting profile...
09-13 15:14:10.103  7101  7101 D BtGatt.GattService: start()
09-13 15:14:10.103  7101  7101 I bluedroid-qcom: get_profile_interface gatt
09-13 15:14:10.103  7101  7101 D BtGatt.AdvertiseManager: advertise manager created
,09-13 15:14:10.104  7164  7164 I AppUp4:CustModeStarterReceiver: onReceive
09-13 15:14:10.106  7164  7164 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37329eff
09-13 15:14:10.106  7164  7164 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 15:14:10.106  7164  7164 D AppUp4:CustFacade: isPhone : true
09-13 15:14:10.106  7164  7164 D AppUp4:CustModeStarterReceiver: begin check event
09-13 15:14:10.106  7164  7164 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 15:14:10.111  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:10.111  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 15:14:10.112  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:10.114  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:10.118  4728  7633 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 15:14:10.118  7193  7193 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 15:14:10.119  4728  7634 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:10.120  4728  7634 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 15:14:10.132  3168  3168 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 15:14:10.132  3168  3168 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:10.133  3168  3168 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 15:14:10.134  7193  7635 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:10.135  7232  7232 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 15:14:10.135  7232  7232 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 15:14:10.136  7063  7637 W FormManager: Network not available. Please check & try again.
09-13 15:14:10.146  7063  7638 V FormManager: Network unavailable.
09-13 15:14:10.146  7292  7292 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:10
,09-13 15:14:10.149  7292  7292 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 15:14:10.149  7292  7292 D Weather.Utils: 2 : All the weather widget is gone.
09-13 15:14:10.149  7063  7638 V FormManager: Network unavailable.
09-13 15:14:10.149  7292  7292 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 15:14:10.149  7292  7292 D WeatherAncestor: connectivity changed - connection : true
09-13 15:14:10.149  7292  7292 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@6a2b315
09-13 15:14:10.150  7292  7292 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 15:14:10.150  7292  7292 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 15:14:10.150  7292  7292 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 15:14:10.150  7292  7292 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 15:14:10.150  7292  7292 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:10
09-13 15:14:10.185  1032  1048 I art     : Explicit concurrent mark sweep GC freed 130274(6MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.410ms total 79.424ms
,09-13 15:14:10.188  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:10.189  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:10.189  7101  7101 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 15:14:10.190  7101  7101 V BluetoothMapService: BluetoothMapBinder()
09-13 15:14:10.190  7101  7101 D BluetoothMapService: Received start request. Starting profile...
09-13 15:14:10.190  7101  7101 D BluetoothMapService: start()
09-13 15:14:10.192  7101  7101 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 15:14:10.192  7101  7101 D BluetoothMapEmailAppObserver: createReceiver()
09-13 15:14:10.193  7101  7101 D BluetoothMapEmailAppObserver: initObservers()
09-13 15:14:10.193  7101  7101 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 15:14:10.198  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
,09-13 15:14:10.200  7101  7101 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:10.202  7101  7101 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:10.205  7101  7101 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:10.205  7101  7101 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 15:14:10.207  7101  7101 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:10.208  7101  7101 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 15:14:10.209  7101  7101 V BluetoothMapService: Handler(): got msg=1
09-13 15:14:10.209  7101  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 15:14:10.209  7101  7571 I bluedroid-qcom: enable
,09-13 15:14:10.209  7101  7571 I bt_hci_bdroid: init
09-13 15:14:10.209  7101  7641 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 15:14:10.209  7101  7641 I bt-btu  : btu_task pending for preload complete event
,09-13 15:14:10.210  7101  7571 I bt_vendor: bt-vendor : init
09-13 15:14:10.206  7644  7644 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:10.206  7644  7644 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:10.210  7101  7571 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 15:14:10.210  7101  7571 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-13 15:14:10.210  7101  7571 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 15:14:10.210  7101  7571 D bt_userial_mct: userial_init
09-13 15:14:10.210  7101  7571 D bt_hci_bdroid: set_power 1
09-13 15:14:10.210  7101  7571 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 15:14:10.210  7101  7571 I bt_vendor: Starting hciattach daemon
09-13 15:14:10.210  7101  7571 I bt_vendor: try to set true
09-13 15:14:10.210  7101  7101 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.217  7101  7101 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 15:14:10.218  7101  7101 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 15:14:10.218  7101  7101 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 15:14:10.218  7101  7101 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.218  7101  7101 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 15:14:10.225  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 15:14:10.290  7651  7651 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 15:14:10.298  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 15:14:10.316  7654  7654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 15:14:10.326  7655  7655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-13 15:14:10.340  7656  7656 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 15:14:10.360  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-13 15:14:10.380  7659  7659 I libmdmdetect: ESOC framework not supported
,09-13 15:14:10.381  7659  7659 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 15:14:10.389  7659  7659 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 15:14:10.389  7659  7659 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 15:14:10.389  7659  7659 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 15:14:10.389  7659  7659 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 15:14:10.390  7659  7659 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 15:14:10.390  7659  7659 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 15:14:10.390  7659  7659 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 15:14:10.431  7659  7660 E QC-QMI  : qmi_client [7659] 14: failed to locate client data
,09-13 15:14:10.433   465   465 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 15:14:10.434   465   465 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-13 15:14:10.469  7664  7664 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 15:14:10.495  7668  7668 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 15:14:10.515  7101  7571 I bt_vendor: bluetooth satus is on
09-13 15:14:10.515  7101  7571 D bt_hci_bdroid: preload
09-13 15:14:10.516  7101  7643 D bt_userial_mct: userial_open(port:0)
09-13 15:14:10.516  7101  7643 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-13 15:14:10.519  7101  7643 I bt_vendor: Done intiailizing UART
09-13 15:14:10.520  7101  7643 I bt_vendor: Done intiailizing UART
09-13 15:14:10.520  7101  7643 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-13 15:14:10.520  7101  7643 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 15:14:10.520  7101  7641 I bt-btu  : btu_task received preload complete event
09-13 15:14:10.520  7101  7670 D bt_userial_mct: Entering userial_read_thread()
09-13 15:14:10.521  7101  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 15:14:10.521  7101  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 15:14:10.523  7101  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 15:14:10.527  7101  7641 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 15:14:10.527  7101  7641 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 15:14:10.528  7101  7641 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 15:14:10.590  1032  1090 W ProcessCpuTracker: Skipping unknown process pid 7581
,09-13 15:14:10.590  1032  1090 W ProcessCpuTracker: Skipping unknown process pid 7582
09-13 15:14:10.591  1032  1090 W ProcessCpuTracker: Skipping unknown process pid 7585
09-13 15:14:10.593  1032  1090 W ProcessCpuTracker: Skipping unknown process pid 7625
09-13 15:14:10.594  1032  1090 W ProcessCpuTracker: Skipping unknown process pid 7665
09-13 15:14:10.598  7101  7641 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 15:14:10.598  7101  7641 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa019e061 
09-13 15:14:10.598  7101  7641 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa019e061 
09-13 15:14:10.634  7101  7575 E bt-btif : Calling BTA_HhEnable
,09-13 15:14:10.634  7101  7575 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 15:14:10.634  7101  7575 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 15:14:10.637  7101  7575 D BluetoothAdapterProperties: Name is: G3
09-13 15:14:10.639  7101  7575 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:14:10.639  7101  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 15:14:10.639  7101  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 15:14:10.639  7101  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 15:14:10.639  7101  7575 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:14:10.640  7101  7575 D bt_hci_bdroid: postload
09-13 15:14:10.640  7101  7643 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 15:14:10.641  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 15:14:10.641  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 15:14:10.641  7101  7575 D bte_conf: Device ID record 1 : primary
09-13 15:14:10.641  7101  7575 D bte_conf:   vendorId            = 00c4
09-13 15:14:10.641  7101  7575 D bte_conf:   vendorIdSource      = 0001
09-13 15:14:10.641  7101  7575 D bte_conf:   product             = 13a1
09-13 15:14:10.641  7101  7575 D bte_conf:   version             = 1000
09-13 15:14:10.641  7101  7575 D bte_conf:   clientExecutableURL = 
09-13 15:14:10.641  7101  7575 D bte_conf:   serviceDescription  = 
09-13 15:14:10.641  7101  7575 D bte_conf:   documentationURL    = 
09-13 15:14:10.642  7101  7575 D bte_conf: bte_load_did_conf no section named DID2.
09-13 15:14:10.645  7101  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 15:14:10.645  7101  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 15:14:10.645  7101  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 15:14:10.646  7672  7672 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:10.646  7672  7672 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:10.652  7101  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 15:14:10.652  7101  7571 D BluetoothAdapterProperties: ScanMode =  20
09-13 15:14:10.653  7101  7571 D BluetoothAdapterProperties: State =  11
09-13 15:14:10.653  7101  7571 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 15:14:10.653  7101  7571 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 15:14:10.654  7101  7571 D BluetoothAdapterProperties: Setting state to 12
09-13 15:14:10.654  7101  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 15:14:10.655  7101  7575 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 15:14:10.656  7101  7575 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 15:14:10.663  7101  7643 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 15:14:10.668  7101  7571 I BluetoothAdapterState: Entering On State
09-13 15:14:10.665  1032  1094 D BluetoothManagerService: Message: 60
09-13 15:14:10.669  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 15:14:10.670  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-13 15:14:10.670  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 15:14:10.671  7101  7643 D bt_hci_bdroid: Used up Tx Cmd credits
,09-13 15:14:10.675  7101  7643 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 15:14:10.676  7101  7670 E bt_mct  : hci lib postload completed
09-13 15:14:10.682  7101  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:10.682  1032  1032 D BluetoothA2dp: Proxy object connected
09-13 15:14:10.682  7101  7641 W bt-smp  : Plain text(LSB ~ MSB) = 4b 0d 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:10.682  7101  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = 83 57 19 02 b0 f6 3e ad 94 69 81 b4 e2 a4 52 20 
09-13 15:14:10.682  7101  7641 W bt-btm  : Stopping oneshot timer
09-13 15:14:10.684  7101  7571 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 15:14:10.684  7101  7571 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 15:14:10.684  7101  7571 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 15:14:10.685  7101  7571 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 15:14:10.686  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:10.686  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:10.686  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:10.686  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:10.686  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:10.686  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:10.686  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:10.686  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:10.690  1877  1892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 15:14:10.695  7101  7575 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:14:10.695  7101  7575 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 15:14:10.699  1877  1877 D BluetoothHeadset: Proxy object connected
09-13 15:14:10.700  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:10.703  6971  6988 D BluetoothPan: onBluetoothStateChange on: true
09-13 15:14:10.703  6971  6988 D BluetoothPan: onBluetoothStateChange call bindService
,09-13 15:14:10.713  6971  6971 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 15:14:10.713  6971  6971 D PanProfile: Bluetooth service connected
09-13 15:14:10.715  6971  6987 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 15:14:10.720  7101  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:10.720  7101  7641 W bt-smp  : Plain text(LSB ~ MSB) = ca 87 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:10.720  7101  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = 64 35 06 8e 2f 48 c5 97 93 d5 cd be a5 60 21 db 
09-13 15:14:10.721  7101  7641 W bt-btm  : Stopping oneshot timer
09-13 15:14:10.724  7101  7571 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 15:14:10.730  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:10.730  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:10.730  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:10.730  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:10.730  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:10.730  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:10.730  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:10.730  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:10.734  7685  7685 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 15:14:10.735  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:10.739  6971  7081 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 15:14:10.742  6971  6971 D BluetoothInputDevice: Proxy object connected
09-13 15:14:10.742  6971  6971 D HidProfile: Bluetooth service connected
09-13 15:14:10.742  6971  6987 D BluetoothMap: onBluetoothStateChange: up=true
09-13 15:14:10.746  6971  6971 D BluetoothMap: Proxy object connected
09-13 15:14:10.746  6971  6971 D MapProfile: Bluetooth service connected
09-13 15:14:10.746  6971  6971 D BluetoothMap: getConnectedDevices()
09-13 15:14:10.747  1877  2531 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:14:10.747  7101  7117 V BluetoothMapService: getConnectedDevices()
09-13 15:14:10.749  1877  1877 D BluetoothHeadset: Proxy object connected
09-13 15:14:10.749  1877  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:14:10.750  7101  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:10.750  7101  7641 W bt-smp  : Plain text(LSB ~ MSB) = ac 32 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:10.750  7101  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = 14 f5 e9 65 aa c7 f1 e4 05 20 07 48 2e da 96 e4 
09-13 15:14:10.750  7101  7641 W bt-btm  : Stopping oneshot timer
09-13 15:14:10.752  1877  1877 D BluetoothHeadset: Proxy object connected
09-13 15:14:10.752  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:14:10.752  1032  1032 D BluetoothHeadset: Proxy object connected
,09-13 15:14:10.755  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-13 15:14:10.755  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 15:14:10.755  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 15:14:10.755  1032  1094 D BluetoothManagerService: Message: 40
09-13 15:14:10.756  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-13 15:14:10.756  1579  1579 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 15:14:10.758  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.758  1966  2195 D LGBluetoothAPIService: Message: 1
09-13 15:14:10.758  1966  2195 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 15:14:10.758  7101  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:10.758  7101  7641 W bt-smp  : Plain text(LSB ~ MSB) = 40 7c 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:10.758  7101  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = 11 c4 c2 db 8e 67 0e 6f 4b 86 38 a6 7f f6 58 94 
,09-13 15:14:10.759  7101  7641 W bt-btm  : Stopping oneshot timer
09-13 15:14:10.762  1966  2195 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 15:14:10.763  7101  7101 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.763  7101  7101 D BluetoothMapService: STATE_ON
09-13 15:14:10.766  6971  6971 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 15:14:10.766  7101  7101 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 15:14:10.767  7101  7101 V BluetoothMapService: Handler(): got msg=1
09-13 15:14:10.767  7101  7101 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 15:14:10.768  7101  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:10.768  7101  7641 W bt-smp  : Plain text(LSB ~ MSB) = 72 e0 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:10.768  7101  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = 83 f2 e9 25 92 9d 31 0e 15 3c 96 a8 88 e4 15 10 
09-13 15:14:10.768  7101  7641 W bt-btm  : Stopping oneshot timer
09-13 15:14:10.768  7101  7101 D LGBluetoothAPIServer: [BTUI] onBind()
,09-13 15:14:10.771  1032  1094 D BluetoothManagerService: Message: 30
09-13 15:14:10.771  1966  1966 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 15:14:10.772  1966  2195 D LGBluetoothAPIService: Message: 100
,09-13 15:14:10.772  1966  2195 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 15:14:10.773  6853  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 15:14:10.774  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:10.776  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:10.777  7101  7688 D BluetoothMapMasInstance: MAS initSocket()
09-13 15:14:10.777  6971  6971 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-13 15:14:10.777  7101  7688 D BluetoothMapMasInstance:   masId = 00
09-13 15:14:10.777  7101  7688 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 15:14:10.777  7101  7688 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 15:14:10.777  7101  7688 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 15:14:10.779  1032  1611 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:10.780  7101  7688 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:10.781  1032  1094 D BluetoothManagerService: Message: 30
,09-13 15:14:10.783  7101  7575 D BluetoothAdapterProperties: Scan Mode:21
09-13 15:14:10.783  7101  7575 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 15:14:10.785  7101  7688 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-13 15:14:10.785  7101  7688 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 15:14:10.785  7101  7688 D BluetoothMapMasInstance: Accepting socket connection...
09-13 15:14:10.786  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:10.788  6971  6971 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 15:14:10.790  6971  6971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 15:14:10.792  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:10.794  6971  6971 D BluetoothA2dp: Proxy object connected
09-13 15:14:10.795  6971  6971 D A2dpProfile: Bluetooth service connected
,09-13 15:14:10.795  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:10.796  7101  7101 V BluetoothPbapService: Pbap Service onCreate
09-13 15:14:10.796  7101  7101 V BluetoothPbapService: Starting PBAP service
09-13 15:14:10.796  6971  6971 D BluetoothHeadset: Proxy object connected
09-13 15:14:10.797  7101  7101 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 15:14:10.797  7101  7101 V BluetoothPbapService: Pbap Service onBind
09-13 15:14:10.798  7101  7101 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.799  6971  6971 D HeadsetProfile: Bluetooth service connected
09-13 15:14:10.799  7101  7101 V BluetoothPbapService: state: 12
09-13 15:14:10.799  7101  7101 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 15:14:10.799  7101  7101 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.799  7101  7101 V BluetoothPbapReceiver: ***********state = 12
09-13 15:14:10.800  7101  7101 V BluetoothPbapService: Handler(): got msg=1
09-13 15:14:10.801  7101  7101 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 15:14:10.802  2262  2262 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 15:14:10.802  2262  2262 D c       : Getting all permits...
09-13 15:14:10.802  2262  2262 D a       : Opening database...
09-13 15:14:10.803  7101  7691 V BluetoothPbapService: Pbap Service initSocket
09-13 15:14:10.803  1032  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:10.804  7101  7691 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:10.805  7101  7691 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-13 15:14:10.805  7101  7691 V BluetoothPbapService: Succeed to create listening socket 
09-13 15:14:10.805  7101  7691 V BluetoothPbapService: Accepting socket connection...
,09-13 15:14:10.806  6971  6971 D DockEventReceiver: finishStartingService: stopping service
09-13 15:14:10.808  6971  6971 D BluetoothPbap: Proxy object connected
09-13 15:14:10.808  2262  2262 D a       : Opening database auth.proximity.permit_store...
09-13 15:14:10.808  6971  6971 D PbapServerProfile: Bluetooth service connected
09-13 15:14:10.812  2262  2262 D a       : Closing database...
09-13 15:14:10.821  6971  6971 D BluetoothPermissionRequest: onReceive
,09-13 15:14:10.823  6971  6971 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 15:14:10.825  6971  6971 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 15:14:10.828  7101  7101 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 15:14:10.830  7101  7101 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 15:14:10.836  7101  7101 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-13 15:14:10.864  7101  7101 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-13 15:14:10.864  7101  7101 V BtOppService: onCreate
,09-13 15:14:10.873  7101  7101 V BluetoothOppNotification: send message
09-13 15:14:10.876  7101  7101 V BtOppService: Starting RfcommListener
09-13 15:14:10.883  7101  7101 D BluetoothOppPreference: Dumping Names:  
09-13 15:14:10.883  7101  7101 D BluetoothOppPreference: {}
09-13 15:14:10.883  7101  7101 D BluetoothOppPreference: Dumping Channels:  
09-13 15:14:10.883  7101  7101 D BluetoothOppPreference: {}
09-13 15:14:10.884  7101  7101 V BtOppService: onStartCommand
,09-13 15:14:10.885  7101  7699 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 15:14:10.889  7101  7101 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.889  7101  7101 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 15:14:10.892  7101  7101 V BluetoothOppNotification: new notify threadi!
09-13 15:14:10.893  7101  7101 V BluetoothOppNotification: send delay message
09-13 15:14:10.893  7101  7699 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-13 15:14:10.893  7101  7101 V BtOppService: start RfcommListener
09-13 15:14:10.894  7101  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 15:14:10.895  7101  7696 V BtOppService: Deleted complete outbound shares, number =  0
09-13 15:14:10.896  7101  7101 V BtOppService: RfcommListener started
09-13 15:14:10.898  7101  7696 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 15:14:10.898  7101  7696 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,09-13 15:14:10.900  7101  7701 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 15:14:10.901  1032  1611 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:10.901  7101  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14588706 on behalf of 
09-13 15:14:10.904  7101  7701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:10.905  7101  7701 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-13 15:14:10.906  7101  7701 V BtOppRfcommListener: Started RFCOMM listener....
09-13 15:14:10.906  7101  7701 I BtOppRfcommListener: Accept thread started.
09-13 15:14:10.906  7101  7701 V BtOppRfcommListener: Accepting connection...
09-13 15:14:10.907  7101  7700 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 15:14:10.908  7101  7696 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@177981c7 on behalf of 
09-13 15:14:10.910  7101  7699 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b3113f4 on behalf of 
,09-13 15:14:10.913  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:10.913  7101  7101 V BluetoothFtpService: Ftp Service onCreate
09-13 15:14:10.913  7101  7101 I BluetoothFtpService: Ftp Service onCreate
09-13 15:14:10.914  7101  7101 V BluetoothFtpService: Ftp Service onStartCommand
09-13 15:14:10.914  7101  7101 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.914  7101  7101 V BluetoothFtpService: Starting Listening on sockets
09-13 15:14:10.914  7101  7101 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 15:14:10.914  7101  7101 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 15:14:10.914  7101  7101 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 15:14:10.914  7101  7101 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.915  7101  7101 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 15:14:10.915  7101  7101 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 15:14:10.915  7101  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 15:14:10.917  7101  7699 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 15:14:10.917  7101  7101 V BtOppService: ContentObserver received notification
09-13 15:14:10.918  7101  7101 V BtOppService: ContentObserver received notification
09-13 15:14:10.918  7101  7699 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 15:14:10.918  7101  7101 V BluetoothFtpService: Handler(): got msg=1
09-13 15:14:10.918  7101  7101 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 15:14:10.918  7101  7101 V BluetoothFtpService: Ftp Service initSocket
09-13 15:14:10.919  7101  7699 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19660d92 on behalf of 
09-13 15:14:10.921  7101  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39827363 on behalf of 
09-13 15:14:10.921  7101  7699 V BluetoothOppNotification: update too frequent, put in queue
09-13 15:14:10.921  7101  7700 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 15:14:10.922  7101  7699 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 15:14:10.922  7101  7699 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-13 15:14:10.923  7101  7700 V BluetoothOppNotification: outbound notification was removed.
09-13 15:14:10.923  7101  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 15:14:10.925  7101  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d457b60 on behalf of 
09-13 15:14:10.925  7101  7700 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 15:14:10.926  1032  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:10.927  7101  7699 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e6cf819 on behalf of 
09-13 15:14:10.927  7101  7700 V BluetoothOppNotification: inbound notification was removed.
09-13 15:14:10.928  7101  7101 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:10.928  7101  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 15:14:10.928  7101  7699 V BluetoothOppNotification: update too frequent, put in queue
09-13 15:14:10.928  7101  7101 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
09-13 15:14:10.929  7101  7101 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 15:14:10.929  7101  7699 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 15:14:10.930  7101  7702 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-13 15:14:10.931  7101  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@345370de on behalf of 
09-13 15:14:10.943  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:10.943  7101  7101 V BluetoothSapService: Sap Service onCreate
09-13 15:14:10.945  7101  7101 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:10.945  7101  7101 V BluetoothSapService: state: 12
09-13 15:14:10.945  7101  7101 V BluetoothSapService: Starting SAP server process
,09-13 15:14:10.948  7101  7101 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 15:14:10.946  7703  7703 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:10.946  7703  7703 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:10.951  7101  7704 V BluetoothSapService: Sap Service initRfcommSocket
09-13 15:14:10.951  1032  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:10.952  7101  7704 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:10.953  7101  7704 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-13 15:14:10.953  7101  7704 V BluetoothSapService: Succeed to create listening socket 
09-13 15:14:10.953  7101  7704 V BluetoothSapService: Accepting socket connection...
09-13 15:14:10.966  7703  7703 V BT_SAP  : Event pipe created
09-13 15:14:10.966  7703  7703 V BT_SAP  : create_server_socket qcom.sap.server
09-13 15:14:10.966  7703  7703 V BT_SAP  : created socket fd 6
,09-13 15:14:11.047  7310  7339 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-13 15:14:11.658  1032  1535 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 15:14:11.658  1032  1535 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 15:14:11.686  1032  1536 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 15:14:11.693  1032  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 15:14:11.842  1032  2070 I ActivityManager: Killing 7487:com.lge.bnr/1000 (adj 15): empty #17
,09-13 15:14:11.879  1032  1597 W libprocessgroup: failed to open /acct/uid_1000/pid_7487/cgroup.procs: No such file or directory
,09-13 15:14:11.894  7101  7101 V BluetoothOppNotification: new notify threadi!
09-13 15:14:11.894  7101  7101 V BluetoothOppNotification: send delay message
,09-13 15:14:11.898  7101  7716 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 15:14:11.899  7101  7716 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e21bcea on behalf of 
09-13 15:14:11.900  7101  7716 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 15:14:11.901  7101  7716 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 15:14:11.904  7101  7716 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e8ebdb on behalf of 
09-13 15:14:11.905  7101  7716 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-13 15:14:11.909  7101  7716 V BluetoothOppNotification: outbound notification was removed.
09-13 15:14:11.909  7101  7716 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 15:14:11.911  7101  7716 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b6b5678 on behalf of 
09-13 15:14:11.911  7101  7716 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 15:14:11.913  7101  7716 V BluetoothOppNotification: inbound notification was removed.
09-13 15:14:11.913  7101  7716 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 15:14:11.914  7101  7716 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19dc9151 on behalf of 
09-13 15:14:12.044  1032  1982 I ActivityManager: Killing 6993:com.lge.sync/1000 (adj 15): empty #17
,09-13 15:14:12.069  1032  1542 D WifiService: Client connection lost with reason: 4
,09-13 15:14:12.079  1032  2070 W libprocessgroup: failed to open /acct/uid_1000/pid_6993/cgroup.procs: No such file or directory
,09-13 15:14:12.682  1032  1948 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:12.682  1032  1948 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@99b86b1 mBinding = false
,09-13 15:14:12.715  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 15:14:12.715  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 15:14:12.716  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 15:14:12.716  1032  1094 D BluetoothManagerService: Message: 2
09-13 15:14:12.717  1032  1094 D BluetoothManagerService: Sending off request.
09-13 15:14:12.718  7101  7687 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 15:14:12.719  7101  7571 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 15:14:12.719  7101  7571 D BluetoothAdapterProperties: Setting state to 13
09-13 15:14:12.719  7101  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 15:14:12.720  7101  7571 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 15:14:12.720  7101  7571 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 15:14:12.722  7101  7575 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:14:12.723  7101  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 15:14:12.725  7101  7688 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 15:14:12.725  7101  7688 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:12.725  7101  7688 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 15:14:12.725  7101  7688 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 15:14:12.725  7101  7688 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 15:14:12.725  7101  7688 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 15:14:12.725  7101  7688 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 15:14:12.725  7101  7688 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,09-13 15:14:12.729  7101  7691 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:12.730  7101  7701 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:12.730  7101  7702 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:12.731  7101  7704 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:14:12.732  7101  7571 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 15:14:12.734  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 15:14:12.734  7101  7641 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 15:14:12.740  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 15:14:12.740  7101  7641 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-13 15:14:12.751  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:12.751  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:12.751  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:12.751  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:12.751  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:12.751  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:12.751  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:12.751  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:12.751  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:12.752  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:12.753  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:14:12.758  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-13 15:14:12.758  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:12.758  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:12.758  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:12.758  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:12.758  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:14:12.758  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:12.758  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:12.758  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:12.759  6853  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:14:12.759  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:12.761  1032  1094 D BluetoothManagerService: Message: 60
09-13 15:14:12.761  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 15:14:12.761  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 15:14:12.764  1579  1579 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 15:14:12.767  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:14:12.773  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:12.775  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:12.778  7101  7101 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:12.778  7101  7101 D BluetoothMapService: STATE_TURNING_OFF
09-13 15:14:12.778  7101  7101 V BluetoothMapService: Handler(): got msg=4
09-13 15:14:12.779  7101  7101 D BluetoothMapService: MAP Service closeService in
09-13 15:14:12.779  7101  7101 D BluetoothMapMasInstance: MAP Service shutdown
09-13 15:14:12.779  7101  7101 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 15:14:12.779  7101  7101 V BluetoothMapService: MAP Service closeService out
09-13 15:14:12.781  7101  7101 V BtOppService: Receiver DISABLED_ACTION 
09-13 15:14:12.782  7101  7101 I BtOppRfcommListener: stopping Accept Thread
09-13 15:14:12.782  7101  7101 V BtOppRfcommListener: close mBtServerSocket
,09-13 15:14:12.784  7101  7701 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 15:14:12.785  7101  7101 V BtOppRfcommListener: waiting for thread to terminate
09-13 15:14:12.785  7101  7101 V BtOppRfcommListener: done waiting for thread to terminate
09-13 15:14:12.792  6971  6971 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-13 15:14:12.799  6971  6971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 15:14:12.802  7101  7101 V BtOppService: onDestroy
09-13 15:14:12.803  7101  7101 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 15:14:12.809  7101  7101 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 15:14:12.809  7101  7101 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:12.809  7101  7101 V BluetoothPbapReceiver: ***********state = 13
09-13 15:14:12.811  7101  7101 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-13 15:14:12.814  7101  7101 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:12.814  7101  7101 V BluetoothPbapService: state: 13
09-13 15:14:12.814  7101  7101 V BluetoothPbapService: Pbap Service closeService in
09-13 15:14:12.818  2262  2262 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 15:14:12.819  7101  7101 V BluetoothPbapService: successfully stopped pbap service
09-13 15:14:12.819  7101  7101 V BluetoothPbapService: Pbap Service closeService out
09-13 15:14:12.820  7101  7101 V BluetoothPbapService: Pbap Service onDestroy
09-13 15:14:12.820  7101  7101 V BluetoothPbapService: Pbap Service closeService in
09-13 15:14:12.820  7101  7101 V BluetoothPbapService: Pbap Service closeService out
09-13 15:14:12.820  7101  7101 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 15:14:12.834  6971  6971 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:14:12.846  6971  6971 D BluetoothPbap: Proxy object disconnected
,09-13 15:14:12.846  6971  6971 D PbapServerProfile: Bluetooth service disconnected
,09-13 15:14:12.859  6971  6971 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 15:14:12.866  6971  6971 D BluetoothPermissionRequest: onReceive
09-13 15:14:12.866  6971  6971 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 15:14:12.872  6971  6971 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 15:14:12.876  7101  7101 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 15:14:12.876  7101  7101 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 15:14:12.878  7101  7101 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-13 15:14:12.881  7101  7101 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:12.882  7101  7101 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 15:14:12.883  7101  7101 V BluetoothFtpService: Ftp Service onStartCommand
09-13 15:14:12.883  7101  7101 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:12.883  7101  7101 V BluetoothFtpService: Ftp Service closeService
09-13 15:14:12.883  7101  7101 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 15:14:12.887  7101  7101 V BluetoothFtpService: successfully stopped ftp service
09-13 15:14:12.887  7101  7101 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 15:14:12.887  7101  7101 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 15:14:12.887  7101  7101 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 15:14:12.888  7101  7101 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:12.888  7101  7101 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 15:14:12.888  7101  7101 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 15:14:12.889  7101  7101 V BluetoothFtpService: Ftp Service onDestroy
09-13 15:14:12.889  7101  7101 V BluetoothFtpService: Ftp Service closeService
,09-13 15:14:12.899  7101  7101 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:12.899  7101  7101 V BluetoothSapService: state: 13
09-13 15:14:12.899  7101  7101 V BluetoothSapService: Stopping SAP server process
09-13 15:14:12.901  7101  7101 V BluetoothSapService: Sap Service closeSapService in
09-13 15:14:12.901  7101  7101 V BluetoothSapService: Close listen Socket : 
09-13 15:14:12.902  7101  7101 V BluetoothSapService: Close rfcomm Socket : 
09-13 15:14:12.902  7101  7101 V BluetoothSapService: Close sapd  Socket : 
09-13 15:14:12.904  7101  7101 V BluetoothSapService: Sap Service closeSapService out
09-13 15:14:12.904  7101  7101 V BluetoothSapService: Sap Service onDestroy
09-13 15:14:12.904  7101  7101 V BluetoothSapService: Sap Service closeSapService in
09-13 15:14:12.904  7101  7101 V BluetoothSapService: Close listen Socket : 
09-13 15:14:12.904  7101  7101 V BluetoothSapService: Close rfcomm Socket : 
09-13 15:14:12.904  7101  7101 V BluetoothSapService: Close sapd  Socket : 
,09-13 15:14:12.905  7101  7101 V BluetoothSapService: Sap Service closeSapService out
,09-13 15:14:13.644  7101  7575 D bt_hci_bdroid: cleanup
,09-13 15:14:13.652  7101  7643 I bt_lpm  : LPM is already off!!!
09-13 15:14:13.653  7101  7670 I bt_userial_mct: exiting userial_read_thread
09-13 15:14:13.653  7101  7670 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 15:14:13.655  7101  7641 W bt-btif : ag scb idx 1 not allocated
09-13 15:14:13.655  7101  7641 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 15:14:13.655  7101  7641 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:14:13.656  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 15:14:13.656  7101  7641 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:14:13.656  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 15:14:13.656  7101  7641 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:14:13.656  7101  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-13 15:14:13.656  7101  7641 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:14:13.656  7101  7641 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif,
09-13 15:14:13.659  7101  7575 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 15:14:13.659  7101  7643 I bt_vendor: hw_epilog_process
09-13 15:14:13.660  7101  7575 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 15:14:13.660  7101  7575 D bt_userial_mct: userial_close
,09-13 15:14:13.660  7101  7575 E bt_userial_mct: pthread_join() FAILED result:3
09-13 15:14:13.660  7101  7575 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 15:14:13.668  7101  7575 D bt_hci_bdroid: set_power 0
09-13 15:14:13.668  7101  7575 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 15:14:13.668  7101  7575 I bt_vendor: bluetooth satus is on,
09-13 15:14:13.668  7101  7575 I bt_vendor: bt-vendor : resetting BT status
09-13 15:14:13.668  7101  7575 I bt_vendor: Starting hciattach daemon
09-13 15:14:13.668  7101  7575 I bt_vendor: try to set false
,09-13 15:14:13.678  7101  7575 I bt_vendor: Starting hciattach daemon
09-13 15:14:13.678  7101  7575 I bt_vendor: try to set false
09-13 15:14:13.679  7101  7575 I bt_vendor: cleanup
09-13 15:14:13.680  7101  7641 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 15:14:13.680  7101  7575 I GKI_LINUX: GKI_exit_task 0 done
09-13 15:14:13.680  7101  7575 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 15:14:13.682  7101  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-13 15:14:13.691  7101  7571 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 15:14:13.692  7101  7101 D HeadsetService: Received stop request...Stopping profile...
09-13 15:14:13.693  7101  7101 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 15:14:13.693  7101  7101 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 15:14:13.693  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:13.696  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-13 15:14:13.696  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-13 15:14:13.699  7101  7593 D HeadsetStateMachine: Exit Disconnected: -1
09-13 15:14:13.700  1877  1877 D BluetoothHeadset: Proxy object disconnected
09-13 15:14:13.702  1877  1877 D BluetoothHeadset: Proxy object disconnected
09-13 15:14:13.702  1877  1877 D BluetoothHeadset: Proxy object disconnected
09-13 15:14:13.704  7101  7101 D A2dpService: Received stop request...Stopping profile...
09-13 15:14:13.704  7101  7626 D A2dpStateMachine: Exit Disconnected: -1
09-13 15:14:13.706  7101  7101 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 15:14:13.708  7101  7101 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 15:14:13.708  7101  7101 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 15:14:13.708  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
,09-13 15:14:13.713  7101  7101 D HidService: Received stop request...Stopping profile...
09-13 15:14:13.713  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:13.713  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-13 15:14:13.713  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 15:14:13.715  7101  7101 D HealthService: Received stop request...Stopping profile...
09-13 15:14:13.716  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:13.719  7101  7101 D PanService: Received stop request...Stopping profile...
09-13 15:14:13.720  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
,09-13 15:14:13.723  7101  7101 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 15:14:13.724  7101  7101 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 15:14:13.724  7101  7101 D BtGatt.GattService: stop()
09-13 15:14:13.724  7101  7101 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 15:14:13.725  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:13.726  7101  7101 D BluetoothMapService: Received stop request...Stopping profile...
09-13 15:14:13.726  7101  7101 D BluetoothMapService: stop()
09-13 15:14:13.727  7101  7101 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 15:14:13.727  7101  7101 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 15:14:13.729  7101  7101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6a2b315
09-13 15:14:13.730  7101  7101 D HeadsetStateMachine: Unbinding service...
09-13 15:14:13.731  7101  7101 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 15:14:13.731  7101  7101 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 15:14:13.731  7101  7101 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 15:14:13.731  7101  7101 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 15:14:13.731  7101  7101 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 15:14:13.731  7101  7101 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 15:14:13.731  7101  7101 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 15:14:13.732  7101  7101 I BluetoothA2dpServiceJni: cleanupNative
,09-13 15:14:13.734  7101  7627 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 15:14:13.735  7101  7101 I GKI_LINUX: GKI_exit_task 2 done
09-13 15:14:13.735  7101  7101 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 15:14:13.736  7101  7101 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 15:14:13.736  7101  7101 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 15:14:13.736  7101  7101 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 15:14:13.736  7101  7101 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 15:14:13.736  7101  7101 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 15:14:13.737  7101  7101 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 15:14:13.737  7101  7101 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 15:14:13.740  7101  7101 V BluetoothMapService: Handler(): got msg=4
09-13 15:14:13.740  7101  7101 D BluetoothMapService: MAP Service closeService in
09-13 15:14:13.740  7101  7101 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 15:14:13.740  7101  7101 V BluetoothMapService: MAP Service closeService out
09-13 15:14:13.743  7101  7571 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 15:14:13.743  7101  7571 D BluetoothAdapterProperties: Setting state to 10
09-13 15:14:13.743  7101  7571 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 15:14:13.743  7101  7101 D BluetoothMapService: cleanup()
09-13 15:14:13.743  7101  7101 D BluetoothMapService: MAP Service closeService in
09-13 15:14:13.744  7101  7101 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 15:14:13.744  7101  7101 V BluetoothMapService: MAP Service closeService out
,09-13 15:14:13.748  1032  1094 D BluetoothManagerService: Message: 60
09-13 15:14:13.748  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 15:14:13.748  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-13 15:14:13.748  7101  7571 I BluetoothAdapterState: Entering OffState
09-13 15:14:13.749  6971  7081 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 15:14:13.750  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 15:14:13.750  1877  1892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:14:13.751  6971  7081 D BluetoothPan: onBluetoothStateChange on: false
09-13 15:14:13.751  6971  7081 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:14:13.752  6971  7081 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 15:14:13.754  6971  7081 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 15:14:13.754  6971  7081 D BluetoothMap: onBluetoothStateChange: up=false
09-13 15:14:13.755  1877  2531 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:14:13.755  1877  4379 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 15:14:13.758  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 15:14:13.759  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-13 15:14:13.759  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-13 15:14:13.760  1032  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-13 15:14:13.760  1032  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-13 15:14:13.761  1032  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@99b86b1 mBinding = false
09-13 15:14:13.761  1032  1094 D BluetoothManagerService: Sending unbind request.
09-13 15:14:13.766  7101  7575 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-13 15:14:13.768  7101  7101 I GKI_LINUX: GKI_exit_task 1 done
09-13 15:14:13.768  7101  7101 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-13 15:14:13.768  7101  7101 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 15:14:13.768  7101  7101 I art     : --- WEIRD: removing null entry 248
09-13 15:14:13.768  7101  7101 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-13 15:14:13.768  7101  7101 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,09-13 15:14:13.771  7101  7101 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-13 15:14:13.772  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 15:14:13.774  7101  7101 I art     : System.exit called, status: 0
09-13 15:14:13.774  7101  7101 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 15:14:13.793   318  1383 V AudioFlinger: 7101 died, releasing its sessions
09-13 15:14:13.793   318  1383 V AudioFlinger:  pid 1877 @ 0
09-13 15:14:13.793   318  1383 V AudioFlinger:  pid 3168 @ 1
09-13 15:14:13.793   318  1383 V AudioFlinger:  pid 3168 @ 2
,09-13 15:14:13.797  1966  1966 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-13 15:14:13.804  1966  2195 D LGBluetoothAPIService: Message: 101
09-13 15:14:13.804  6971  6971 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-13 15:14:13.804  1966  2195 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-13 15:14:13.805  1966  2195 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-13 15:14:13.805  1966  2195 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-13 15:14:13.938  1032  2023 I ActivityManager: Process com.android.bluetooth (pid 7101) has died
09-13 15:14:13.938  1032  2023 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-13 15:14:13.939  1032  2023 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-13 15:14:13.950  6971  6971 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 15:14:13.950  6971  6971 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 15:14:13.951  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:13.952  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:13.952  1966  2195 D LGBluetoothAPIService: Message: 2
09-13 15:14:13.952  1966  2195 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-13 15:14:13.953  1579  1579 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 15:14:13.955  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:13.962  1579  1579 D BluetoothAdapter: 181984118: getState() :  mService = null. Returning STATE_OFF
09-13 15:14:13.962  1579  1579 D BluetoothAdapter: 181984118: getState() :  mService = null. Returning STATE_OFF
09-13 15:14:13.962  6971  6971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 15:14:14.044  1032  2350 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7762 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-13 15:14:14.047  6971  6971 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:14:14.130  7762  7762 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-13 15:14:14.131  7762  7762 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 15:14:14.131  7762  7762 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-13 15:14:14.133  7762  7762 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 15:14:14.155  7762  7762 D BluetoothAdapterApp: Loading JNI Library
,09-13 15:14:14.193  7762  7762 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2c99355d Instance Count = 1
,09-13 15:14:14.200  7762  7762 D BluetoothAdapterApp: onCreate
09-13 15:14:14.226  7762  7762 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-13 15:14:14.226  7762  7762 D ProfileConfigQcom: Adding HeadsetService
09-13 15:14:14.226  7762  7762 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-13 15:14:14.227  7762  7762 D ProfileConfigQcom: Adding A2dpService
09-13 15:14:14.227  7762  7762 D ProfileConfigQcom: [BTUI] HidService is supported
09-13 15:14:14.227  7762  7762 D ProfileConfigQcom: Adding HidService
09-13 15:14:14.228  7762  7762 D ProfileConfigQcom: [BTUI] HealthService is supported
09-13 15:14:14.228  7762  7762 D ProfileConfigQcom: Adding HealthService
,09-13 15:14:14.228  7762  7762 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-13 15:14:14.229  7762  7762 D ProfileConfigQcom: [BTUI] PanService is supported
09-13 15:14:14.229  7762  7762 D ProfileConfigQcom: Adding PanService
09-13 15:14:14.230  7762  7762 D ProfileConfigQcom: [BTUI] GattService is supported
09-13 15:14:14.230  7762  7762 D ProfileConfigQcom: Adding GattService
09-13 15:14:14.231  7762  7762 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,09-13 15:14:14.231  7762  7762 D ProfileConfigQcom: Adding BluetoothMapService
09-13 15:14:14.231  7762  7762 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-13 15:14:14.232  7762  7762 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 15:14:14.233  7762  7762 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:14.234  7762  7762 V BluetoothPbapReceiver: ***********state = 10
09-13 15:14:14.236  7762  7762 V LGMDMManagerInternal: Create singleton instance
09-13 15:14:14.353  2262  2262 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:14:14.356  7762  7762 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 15:14:14.357  7762  7762 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 15:14:14.359  1966  1966 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 15:14:14.359  1966  2195 D LGBluetoothAPIService: Message: 100
09-13 15:14:14.359  1966  2195 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 15:14:14.359  6971  6971 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 15:14:14.371  6971  6971 D BluetoothPermissionRequest: onReceive
,09-13 15:14:14.374  6971  6971 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 15:14:14.374  6971  6971 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 15:14:14.377  6971  6971 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 15:14:14.381  7762  7762 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 15:14:14.387  7762  7762 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:14:14.390  7762  7762 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-13 15:14:14.391  7762  7762 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 15:14:14.391  7762  7762 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 15:14:14.393  7762  7762 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:14.393  7762  7762 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 15:14:14.396  7042  7042 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-13 15:14:15.798  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:15.798  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:14:16.136  1579  1579 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 15:14:16.221  1032  1090 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7791 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-13 15:14:16.228  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 15:14:16.241  1579  1579 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 15:14:16.244  1579  1579 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-13 15:14:16.301  1032  1433 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 15:14:16.315  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 15:14:16.322  7791  7791 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 15:14:16.326  1032  1032 D administrator: Handling package changes for user 0
09-13 15:14:16.398  7791  7791 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:16.399  7791  7791 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:16.431  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-13 15:14:16.431  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-13 15:14:16.460  1032  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 15:14:16.464  1032  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 15:14:16.470  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 15:14:16.470  2481  2481 V GmsNetworkLocationProvi: DISABLE
09-13 15:14:16.491  1032  1089 D LocationProviderProxy: applying state to connected service
09-13 15:14:16.494  2481  2481 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-13 15:14:16.527  7791  7837 I Babel   : MmsConfig: mnc/mcc: 0/0
09-13 15:14:16.527  7791  7837 I Babel   : MmsConfig.loadMmsSettings
09-13 15:14:16.535  7791  7837 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 15:14:16.535  7791  7837 I Babel   : MmsConfig.loadFromDatabase
,09-13 15:14:16.562  7791  7791 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 15:14:16.570  7791  7837 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-13 15:14:16.570  7791  7835 W AudioCapabilities: Unsupported mime audio/evrc
09-13 15:14:16.570  7791  7837 I Babel   : MmsConfig.loadFromResources
09-13 15:14:16.572  7791  7835 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 15:14:16.572  7791  7837 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-13 15:14:16.572  7791  7837 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-13 15:14:16.573  7791  7835 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 15:14:16.588  7791  7835 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-13 15:14:16.590  7791  7835 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 15:14:16.591  7791  7835 W AudioCapabilities: Unsupported mime audio/evrc
09-13 15:14:16.596  1839  7839 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-13 15:14:16.596  1839  7839 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-13 15:14:16.601  7164  7164 I AppUp4:CustModeStarterReceiver: onReceive
09-13 15:14:16.605  7791  7835 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-13 15:14:16.606  7164  7164 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37329eff
09-13 15:14:16.607  7164  7164 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 15:14:16.607  7164  7164 D AppUp4:CustFacade: isPhone : true
09-13 15:14:16.607  7164  7164 D AppUp4:CustModeStarterReceiver: begin check event
09-13 15:14:16.607  7164  7164 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-13 15:14:16.608  7791  7835 W VideoCapabilities: Unsupported mime video/divx
09-13 15:14:16.610  1839  5183 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-13 15:14:16.612  7791  7835 W VideoCapabilities: Unsupported mime video/divx311
09-13 15:14:16.614  7791  7835 W VideoCapabilities: Unsupported mime video/divx4
09-13 15:14:16.624  7791  7835 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-13 15:14:16.642  7791  7835 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 15:14:16.649  1032  1574 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7842 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-13 15:14:16.654  1032  1574 I ActivityManager: Killing 6745:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-13 15:14:16.656  7791  7835 W AudioCapabilities: Unsupported mime audio/eac3
,09-13 15:14:16.658  7791  7835 W AudioCapabilities: Unsupported mime audio/ac3
,09-13 15:14:16.659  7791  7835 W AudioCapabilities: Unsupported mime audio/g726
09-13 15:14:16.660  7791  7835 W AudioCapabilities: Unsupported mime audio/wma-voice
09-13 15:14:16.661  7791  7835 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-13 15:14:16.662  7791  7835 W AudioCapabilities: Unsupported mime audio/adpcm
09-13 15:14:16.664  7791  7835 W VideoCapabilities: Unsupported mime video/theora
09-13 15:14:16.666  7791  7835 W VideoCapabilities: Unsupported mime video/mjpg
09-13 15:14:16.669  7025  7025 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-13 15:14:16.669  7025  7025 W System.err: android.os.DeadObjectException
09-13 15:14:16.670  7025  7025 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 15:14:16.670  7025  7025 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 15:14:16.670  7025  7025 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,09-13 15:14:16.670  7025  7025 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,09-13 15:14:16.671  7025  7025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 15:14:16.671  7025  7025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 15:14:16.671  7025  7025 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,09-13 15:14:16.671  7025  7025 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 15:14:16.671  7025  7025 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,09-13 15:14:16.671  7025  7025 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 15:14:16.672  7025  7025 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:14:16.672  7025  7025 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:14:16.672  7025  7025 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 15:14:16.672  7025  7025 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 15:14:16.673  7025  7025 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,09-13 15:14:16.673  7025  7025 W System.err: android.os.DeadObjectException
09-13 15:14:16.673  7025  7025 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 15:14:16.673  7025  7025 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 15:14:16.673  7025  7025 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,09-13 15:14:16.673  7025  7025 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-13 15:14:16.673  7025  7025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 15:14:16.674  7025  7025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,09-13 15:14:16.674  7025  7025 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 15:14:16.674  7025  7025 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 15:14:16.674  7025  7025 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 15:14:16.674  7025  7025 W System.err: 	,at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 15:14:16.674  7025  7025 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:14:16.674  7025  7025 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,09-13 15:14:16.674  7025  7025 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 15:14:16.674  7025  7025 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 15:14:16.674  7025  7025 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-13 15:14:16.674  7025  7025 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-13 15:14:16.932  1032  1048 W libprocessgroup: failed to open /acct/uid_1000/pid_6745/cgroup.procs: No such file or directory
,09-13 15:14:16.932  1032  1048 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-13 15:14:16.935  7025  7025 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-13 15:14:16.935  7025  7025 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 15:14:16.958  7842  7842 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:14:16.959  7842  7842 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 15:14:16.959  7842  7842 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 15:14:16.962  7842  7842 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 15:14:16.962  7842  7842 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-13 15:14:16.966  1032  2110 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7862 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 15:14:16.966  7025  7025 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-13 15:14:17.022  7862  7862 D UEI.SmartControl: Quickset Services start...
09-13 15:14:17.023  7862  7862 I UEI.SmartControl: Manufacture = LGE
09-13 15:14:17.023  7862  7862 D UEI.SmartControl: Id = LGNevo
09-13 15:14:17.024  7862  7862 D UEI.SmartControl: File observer start...
,09-13 15:14:17.028  7862  7862 E UEI.SmartControl: IR Port is disabled: false
09-13 15:14:17.028  7862  7862 D UEI.SmartControl: Starting file observer...
09-13 15:14:17.028  7862  7862 D UEI.SmartControl: Extracting JNI libs...
09-13 15:14:17.028  7862  7862 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-13 15:14:17.046  7842  7842 I SystemConfig: BUILD Country: EU
09-13 15:14:17.046  7842  7842 I SystemConfig: BUILD Operator: OPEN
,09-13 15:14:17.075  7862  7862 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-13 15:14:17.075  7862  7862 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-13 15:14:17.075  7862  7862 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-13 15:14:17.094  7862  7862 I UEI.SmartControl: --- Selecting new region: 6
09-13 15:14:17.095  7862  7862 I UEI.SmartControl: Model = LG-D855
,09-13 15:14:17.096  7862  7862 D UEI.SmartControl: QS Service created
09-13 15:14:17.100  1032  1598 I ActivityManager: Killing 7025:com.lge.qremote/u0a112 (adj 15): empty #17
09-13 15:14:17.105  7862  7862 I UEI.SmartControl: Service initServices...
,09-13 15:14:17.108  7862  7862 D UEI.SmartControl: QS start get config
,09-13 15:14:17.134  7862  7862 D UEI.SmartControl: Loading JNI Libs...
,09-13 15:14:17.172  1032  1048 W libprocessgroup: failed to open /acct/uid_10112/pid_7025/cgroup.procs: No such file or directory
,09-13 15:14:17.230  1032  1598 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7889 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-13 15:14:17.240  7842  7887 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 15:14:17.241  7842  7887 I SystemConfig: existFile = false
09-13 15:14:17.241  7842  7887 I SystemConfig: canReadFile = false
09-13 15:14:17.241  7842  7887 I SystemConfig: systemFeature RCS result false
09-13 15:14:17.241  7842  7887 D SystemConfig: refreshRcsSupport() :false
,09-13 15:14:17.285  7889  7889 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 15:14:17.285  7889  7889 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 15:14:17.286  7889  7889 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 15:14:17.286  7889  7889 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 15:14:17.379  7889  7889 I AppConfig: Total System Memory = 2995761152
,09-13 15:14:17.389  7889  7889 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,09-13 15:14:17.439  7862  7862 I UEI.SmartControl: Supports setup maps: true
,09-13 15:14:17.442  7862  7862 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 15:14:17.442  7862  7862 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 15:14:17.442  7862  7862 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 15:14:17.442  7862  7862 I UEI.SmartControl: ### init IR Blaster...
09-13 15:14:17.446  7862  7862 D serial_port: Configuring serial port
09-13 15:14:17.449  7862  7862 E UEI.SmartControl: UEIBLaster setting for 616
09-13 15:14:17.449  7862  7862 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 15:14:17.450  7862  7862 I UEI.SmartControl: configuring settings for MAXQ616
09-13 15:14:17.450  7862  7862 I UEI.SmartControl: Get version...
09-13 15:14:17.466  7862  7908 D UEI.SmartControl: serial port data available: 21
,09-13 15:14:17.493  7862  7862 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 15:14:17.493  7862  7862 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 15:14:17.493  7862  7862 I UEI.SmartControl: QS saving settings...
09-13 15:14:17.494  7862  7862 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 15:14:17.499  1032  1574 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7909 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:14:17.500  1032  1574 I ActivityManager: Killing 7193:com.lge.email/u0a23 (adj 15): empty #17
09-13 15:14:17.512  7862  7908 D UEI.SmartControl: serial port data available: 4
,09-13 15:14:17.550  7862  7931 I UEI.SmartControl: Device manager: loading config....
,09-13 15:14:17.550  7862  7862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 15:14:17.551  7862  7931 D UEI.SmartControl: ----------- loading internal config...
09-13 15:14:17.558  7862  7931 E UEI.SmartControl: Loading SETTINGS...
09-13 15:14:17.564  7862  7931 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-13 15:14:17.570  1032  2110 W libprocessgroup: failed to open /acct/uid_10023/pid_7193/cgroup.procs: No such file or directory
09-13 15:14:17.575  7862  7862 E UEI.SmartControl: Services init done
09-13 15:14:17.575  7862  7862 D UEI.SmartControl: QS Service init finished
09-13 15:14:17.576  7862  7862 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 15:14:17.576  7862  7862 D UEI.SmartControl: QS Service version code: 201091
09-13 15:14:17.577  7862  7862 D UEI.SmartControl: Service requested: Control
09-13 15:14:17.579  7862  7862 D UEI.SmartControl: Service.onUnbind: IControl
,09-13 15:14:17.580  7862  7862 D UEI.SmartControl: Service.onDestroy
,09-13 15:14:17.580  7862  7862 D UEI.SmartControl: Lock is in USE false
09-13 15:14:17.581  7862  7862 D UEI.SmartControl: unbind internal service
09-13 15:14:17.583  7862  7862 D serial_port: close(fd = 25)
09-13 15:14:17.587  7862  7862 I UEI.SmartControl: Serial port is closed.
09-13 15:14:17.587  7862  7862 I UEI.SmartControl: Serial port is closed.
09-13 15:14:17.587  7862  7862 D UEI.SmartControl: Blaster closed
09-13 15:14:17.587  7862  7862 D UEI.SmartControl: Shut down QS...
09-13 15:14:17.587  7862  7862 D UEI.SmartControl: Stopping QS lib
09-13 15:14:17.587  7862  7862 D UEI.SmartControl: QS lib stop result = true
09-13 15:14:17.587  7862  7862 D UEI.SmartControl: Stopped QS lib
09-13 15:14:17.588  7862  7862 D UEI.SmartControl: Stopped file observer...
09-13 15:14:17.588  7862  7930 I UEI.SmartControl: Notify AllClients services are ready: 11
09-13 15:14:17.588  7862  7862 D UEI.SmartControl: QS shutdown complete
09-13 15:14:17.588  7862  7930 D UEI.SmartControl: -----service ready thread exits
09-13 15:14:17.588  7862  7862 D UEI.SmartControl: QS Service created
09-13 15:14:17.603  7862  7862 I UEI.SmartControl: Service initServices...
,09-13 15:14:17.604  7862  7862 D UEI.SmartControl: QS start get config
09-13 15:14:17.744  7909  7909 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-13 15:14:17.822  1032  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d9cb6c1 type 2 when 198780 com.google.android.gms} when 198780
09-13 15:14:17.826  7909  7909 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:17.826  7909  7909 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:17.872  7909  7909 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-13 15:14:17.887  7909  7909 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 15:14:17.888  7909  7909 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 15:14:17.901  7909  7909 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-13 15:14:17.901  7909  7909 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-13 15:14:17.921  1032  1597 I ActivityManager: Killing 7063:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-13 15:14:17.926  7862  7862 I UEI.SmartControl: Supports setup maps: true
09-13 15:14:17.932  7862  7862 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 15:14:17.932  7862  7862 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 15:14:17.932  7862  7862 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 15:14:17.932  7862  7862 I UEI.SmartControl: ### init IR Blaster...
,09-13 15:14:17.936  7862  7862 D serial_port: Configuring serial port
09-13 15:14:17.936  7862  7862 E UEI.SmartControl: UEIBLaster setting for 616
09-13 15:14:17.936  7862  7862 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 15:14:17.936  7862  7862 I UEI.SmartControl: configuring settings for MAXQ616
09-13 15:14:17.936  7862  7862 I UEI.SmartControl: Get version...
09-13 15:14:17.952  7862  7961 D UEI.SmartControl: serial port data available: 21
,09-13 15:14:17.960  1032  1574 W libprocessgroup: failed to open /acct/uid_10026/pid_7063/cgroup.procs: No such file or directory
09-13 15:14:17.969  5021  7962 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-13 15:14:17.970  2835  2933 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-13 15:14:17.974  2835  2933 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3e042630 on behalf of 7909
09-13 15:14:17.978  7862  7862 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 15:14:17.978  7862  7862 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 15:14:17.978  7862  7862 I UEI.SmartControl: QS saving settings...
09-13 15:14:17.979  7862  7862 D UEI.SmartControl: IR Blaster version: 25672567
09-13 15:14:17.996  7862  7961 D UEI.SmartControl: serial port data available: 4
,09-13 15:14:18.026  7862  7965 I UEI.SmartControl: Device manager: loading config....
,09-13 15:14:18.027  7862  7965 D UEI.SmartControl: ----------- loading internal config...
09-13 15:14:18.028  7862  7862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 15:14:18.038  7862  7965 E UEI.SmartControl: Loading SETTINGS...
09-13 15:14:18.046  1032  2070 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7967 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-13 15:14:18.051  7862  7965 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 15:14:18.055  7862  7862 E UEI.SmartControl: Services init done
09-13 15:14:18.055  7862  7862 D UEI.SmartControl: QS Service init finished
,09-13 15:14:18.056  7862  7862 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 15:14:18.056  7862  7862 D UEI.SmartControl: QS Service version code: 201091
09-13 15:14:18.057  7862  7862 D UEI.SmartControl: Service requested: Control
09-13 15:14:18.058  1032  1996 I ActivityManager: Killing 6384:com.wsandroid.suite.lge/1000 (adj 15): empty #17
09-13 15:14:18.065  7862  7964 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 15:14:18.065  7862  7964 D UEI.SmartControl: -----service ready thread exits
,09-13 15:14:18.102  7862  7862 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@299c2c1b that was originally bound here
09-13 15:14:18.102  7862  7862 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@299c2c1b that was originally bound here
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 15:14:18.102  7862  7862 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 15:14:18.103  1032  1611 W libprocessgroup: failed to open /acct/uid_1000/pid_6384/cgroup.procs: No such file or directory
,09-13 15:14:18.112  7862  7862 D UEI.SmartControl: Internal service binding...
09-13 15:14:18.125  7909  7909 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-13 15:14:18.144  7909  7909 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-13 15:14:18.155  7967  7967 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-13 15:14:18.179  7967  7967 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-13 15:14:18.179  7967  7967 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,09-13 15:14:18.179  7967  7967 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-13 15:14:18.179  7967  7967 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 15:14:18.179  7967  7967 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-13 15:14:18.179  7967  7967 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-13 15:14:18.198   314  7989 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 15:14:18.199  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 15:14:18.208  1032  1982 I ActivityManager: Killing 7232:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-13 15:14:18.328  1032  2038 W libprocessgroup: failed to open /acct/uid_10046/pid_7232/cgroup.procs: No such file or directory
,09-13 15:14:18.580  7862  7933 D UEI.SmartControl: Internal timer expired: 2
,09-13 15:14:18.589  1032  2110 I art     : Explicit concurrent mark sweep GC freed 29046(1381KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.931ms total 144.615ms
09-13 15:14:18.666  1032  1943 V SIM_STK : Menu title from STK is T-Mobile
,09-13 15:14:18.681  5021  7962 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 712 ms] updated apps [took 712 ms] 
09-13 15:14:18.815  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:14:18.816  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38ca6d39 added. We now have 6 listener(s)
09-13 15:14:18.816  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:18.820  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:18.820  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e8e0f7e added. We now have 7 listener(s)
09-13 15:14:18.820  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:14:18.824  6853  6932 I System.out: IsBluetoothEnabled
09-13 15:14:18.829  1032  2070 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:18.829  1032  2070 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-13 15:14:18.830  1032  1094 D BluetoothManagerService: Message: 2
09-13 15:14:18.835  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:18.839  1032  2110 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:18.839  1032  2110 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-13 15:14:18.859  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 15:14:18.859  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 15:14:18.859  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 15:14:18.861  1032  1094 D BluetoothManagerService: Message: 1
09-13 15:14:18.861  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-13 15:14:18.895  1032  1094 D BluetoothManagerService: Message: 20
09-13 15:14:18.895  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@299d9669:true
09-13 15:14:18.895  7762  7762 D BluetoothAdapterState: make
,09-13 15:14:18.902  7762  7762 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-13 15:14:18.903  7762  7999 I BluetoothAdapterState: Entering OffState
09-13 15:14:18.903  7762  7762 I bluedroid-qcom: init
09-13 15:14:18.904  7762  7762 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 15:14:18.905  7762  7762 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 15:14:18.905  7762  7762 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 15:14:18.905  7762  7762 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 15:14:18.906  7762  7762 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-13 15:14:18.907  7762  7762 I bluedroid-qcom: get_profile_interface socket
09-13 15:14:18.907  7762  7762 I bluedroid-qcom: get_profile_interface map_client
09-13 15:14:18.910  7762  8002 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-13 15:14:18.906  8003  8003 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:18.918  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-13 15:14:18.919  1032  1094 D BluetoothManagerService: Message: 40
09-13 15:14:18.919  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-13 15:14:18.920  7762  7782 I bluedroid-qcom: config_hci_snoop_log
09-13 15:14:18.922  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-13 15:14:18.922  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-13 15:14:18.923  7762  8002 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 15:14:18.906  8003  8003 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:18.934  8003  8003 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-13 15:14:18.934  8003  8003 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-13 15:14:18.934  8003  8003 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-13 15:14:18.936  8003  8003 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-13 15:14:18.943  8003  8003 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-13 15:14:18.943  8003  8003 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-13 15:14:18.949  7762  7999 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-13 15:14:18.954  7762  8002 D BluetoothAdapterProperties: Name is: G3
09-13 15:14:18.954  7762  7999 D BluetoothAdapterProperties: Setting state to 11
09-13 15:14:18.954  7762  7999 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 15:14:18.955  1032  1094 D BluetoothManagerService: Message: 60
09-13 15:14:18.955  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 15:14:18.955  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 15:14:18.956  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 15:14:18.956  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 15:14:18.960  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:18.961  1579  1579 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-13 15:14:18.967  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:18.969  7762  7999 I LGBluetoothServiceJni: classInitNative: succeeds
09-13 15:14:18.973  6971  6971 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 15:14:18.982  7762  7762 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 15:14:18.982  7762  7762 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:18.982  7762  7762 V BluetoothPbapReceiver: ***********state = 11
,09-13 15:14:18.989  2262  2262 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 15:14:19.003  7762  7999 D BluetoothBondStateMachine: make
,09-13 15:14:19.012  7762  7999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:19.012  7762  7999 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-13 15:14:19.012  7762  7999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:19.012  7762  7999 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 15:14:19.012  7762  7999 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 15:14:19.015  7762  8008 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 15:14:19.019  6971  6971 D BluetoothPermissionRequest: onReceive
09-13 15:14:19.023  6971  6971 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 15:14:19.031  7762  7762 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:14:19.039  7762  7762 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 15:14:19.039  7762  7762 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 15:14:19.039  7762  7762 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 15:14:19.039  7762  7762 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:19.039  7762  7762 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 15:14:19.040  7762  7999 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:19.050  7762  7762 D HeadsetService: Received start request. Starting profile...
09-13 15:14:19.051  7762  7762 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 15:14:19.051  7762  7762 D LGBluetoothHfpAdapter: Version 1.6
09-13 15:14:19.054  7762  7762 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 15:14:19.055  7762  7762 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 15:14:19.056  7762  7762 D HeadsetStateMachine: make
,09-13 15:14:19.095  7762  7762 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:19.096  7762  7762 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:19.104  7762  7999 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:19.110  7762  7762 D HeadsetStateMachine: max_hf_connections = 1
09-13 15:14:19.110  7762  7762 I bluedroid-qcom: get_profile_interface handsfree
09-13 15:14:19.112  7762  7762 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,09-13 15:14:19.115   318   318 V AudioPolicyService: registerClient() client 0xb558a920, uid 1002
09-13 15:14:19.115   318  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-13 15:14:19.115   318  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 15:14:19.115   318  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 15:14:19.115  7762  7762 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 15:14:19.116   318  1384 V AudioFlinger: registerClient() client 0xb55815f8, pid 7762
09-13 15:14:19.116   318  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:19.116   318  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:19.121  1877  4367 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:19.121  1877  4367 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:19.121  3168  3183 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:19.121  3168  3183 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:19.121   318  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:19.121   318  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:19.122  1877  4366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:19.122  1877  4366 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:19.122  3168  3184 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:19.122  3168  3184 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:19.122  7762  7782 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:19.122  7762  7762 V ToneGenerator: Create Track: 0xb4928080
09-13 15:14:19.122  7762  7762 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-13 15:14:19.122  7762  7762 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-13 15:14:19.122   318  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 15:14:19.122   318  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-13 15:14:19.122   318  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 15:14:19.122   318  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 15:14:19.122  7762  7762 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-13 15:14:19.123   318   318 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 15:14:19.123   318  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-13 15:14:19.123   318  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-13 15:14:19.123   318  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-13 15:14:19.123   318  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-13 15:14:19.123  7762  7762 V AudioSystem: getLatency() output 2, latency 50
09-13 15:14:19.123  7762  7782 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-13 15:14:19.123  7762  7782 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,09-13 15:14:19.123  7762  7782 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-13 15:14:19.124  1032  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:19.124  1032  1943 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:19.125  1579  1599 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-13 15:14:19.125  1579  1599 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-13 15:14:19.125  1579  1599 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:19.125  1579  1599 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:19.125  7762  7762 V AudioSystem: getFrameCount() output 2, frameCount 960
09-13 15:14:19.125  7762  7762 V AudioTrack: createTrack_l() output 2 afLatency 50
09-13 15:14:19.125  1032  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-13 15:14:19.125  1032  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-13 15:14:19.127   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 15:14:19.127   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 15:14:19.127   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-13 15:14:19.128   318  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-13 15:14:19.128   318  1383 V AudioFlinger: createTrack() lSessionId: 23
09-13 15:14:19.130  7762  7762 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-13 15:14:19.131   318  1383 V AudioFlinger: acquiring 23 from 7762, for 7762
09-13 15:14:19.131   318  1383 V AudioFlinger:  added new entry for 23
09-13 15:14:19.132  7762  7762 V ToneGenerator: ToneGenerator INIT OK, time: 200104
09-13 15:14:19.132  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:19.136  7762  8009 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 15:14:19.136  7762  8009 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 15:14:19.136  7762  8009 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 15:14:19.136  7762  8009 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 15:14:19.136   318  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7762
09-13 15:14:19.137   318  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 15:14:19.137   318  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 15:14:19.137   318  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 15:14:19.137   318  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 15:14:19.137   318  1384 V voice   : voice_set_parameters: exit with code(0)
09-13 15:14:19.137   318  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 15:14:19.137   318  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 15:14:19.137   318  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 15:14:19.137   318  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 15:14:19.137   318  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 15:14:19.137   318  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 15:14:19.137  7762  8009 V ToneGenerator: ToneGenerator destructor
09-13 15:14:19.137  7762  8009 V ToneGenerator: stopTone
09-13 15:14:19.137  7762  8009 V ToneGenerator: Delete Track: 0xb4928080
09-13 15:14:19.139   318   318 V AudioPolicyService: AudioCommandThread() adding release output 2
09-13 15:14:19.139   318   318 V AudioPolicyService: inserting command: 6 at in,dex 0, num commands 0
09-13 15:14:19.139   318  1257 V AudioPolicyService: AudioCommandThread() waking up
09-13 15:14:19.139   318  1257 V AudioPolicyService: AudioCommandThread() processing release output 2
09-13 15:14:19.139   318  1257 V AudioPolicyManager: releaseOutput() 2
09-13 15:14:19.139   318  1257 V AudioPolicyService: AudioCommandThread() going to sleep
09-13 15:14:19.139   318   318 V AudioFlinger: PlaybackThread::Track destructor
09-13 15:14:19.139   318   318 V AudioFlinger: removeClient_l() pid 7762, calling pid 318
09-13 15:14:19.139  7762  8009 V AudioTrack: ~AudioTrack, releasing session id from 7762 on behalf of 7762
09-13 15:14:19.139   318   318 V AudioFlinger: releasing 23 from 7762 for 7762
09-13 15:14:19.139   318   318 V AudioFlinger:  decremented refcount to 0
09-13 15:14:19.139   318   318 V AudioFlinger: purging stale effects
,09-13 15:14:19.146  7762  7999 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:19.152  7762  7999 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:19.157  1032  2070 W Process : Unable to open /proc/8018/status
,09-13 15:14:19.157  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:19.158  7762  7762 D HeadsetStateMachine: Proxy object connected
09-13 15:14:19.158  7762  7762 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 15:14:19.159  7762  7762 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 15:14:19.159  7762  7999 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:19.163  7762  7762 D A2dpService: Received start request. Starting profile...
09-13 15:14:19.164  7762  7762 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 15:14:19.165  7762  7762 V Avrcp   : make
09-13 15:14:19.165  7762  7762 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 15:14:19.165  7762  7762 I bluedroid-qcom: get_profile_interface avrcp
09-13 15:14:19.166  7762  7999 E BluetoothAdapterService: File transfer profiles supported!!
09-13 15:14:19.173  7762  7999 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 15:14:19.184  7762  7999 V LGMDMManager: Create singleton instance
09-13 15:14:19.186  7762  7999 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 15:14:19.186  7762  7762 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 15:14:19.189  7762  7762 E AudioManager: No RCC entry present to update
09-13 15:14:19.189  7762  7762 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 15:14:19.191  7762  7762 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,09-13 15:14:19.193  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 15:14:19.193  7762  7762 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 15:14:19.195  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 15:14:19.289  1032  1597 V SIM_STK : Menu title from STK is T-Mobile
09-13 15:14:19.289  1032  1597 V SIM_STK : Menu title from STK is T-Mobile
,09-13 15:14:19.367  1032  2350 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-13 15:14:19.377  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 15:14:19.380  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 15:14:19.381  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 15:14:19.381  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 15:14:19.381  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 15:14:19.381  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 15:14:19.381  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 15:14:19.381  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,09-13 15:14:19.381  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 15:14:19.381  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 15:14:19.381  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 15:14:19.381  7762  7762 I BluetoothA2dpServiceJni: classInitNative
09-13 15:14:19.382  7762  7762 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 15:14:19.382  7762  7762 D A2dpStateMachine: make
09-13 15:14:19.384  7762  7762 I bluedroid-qcom: get_profile_interface a2dp
09-13 15:14:19.385  7762  8032 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-13 15:14:19.387  7762  7762 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-13 15:14:19.388  7762  7762 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,09-13 15:14:19.389  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:19.389  7762  8031 D A2dpStateMachine: Enter Disconnected: -2
09-13 15:14:19.389  7762  8009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 15:14:19.390  7762  8009 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 15:14:19.390  7762  8009 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 15:14:19.391  7762  7762 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 15:14:19.392  7762  7762 D HidService: Received start request. Starting profile...
09-13 15:14:19.392  7762  7762 I bluedroid-qcom: get_profile_interface hidhost
09-13 15:14:19.392  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:19.393  7762  7762 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 15:14:19.394  7762  7762 D HealthService: Received start request. Starting profile...
09-13 15:14:19.397  7762  7762 I bluedroid-qcom: get_profile_interface health
09-13 15:14:19.397  7762  7762 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-13 15:14:19.397  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
,09-13 15:14:19.403  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:19.404  7762  7762 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 15:14:19.405  7762  7762 D PanService: Received start request. Starting profile...
09-13 15:14:19.405  7762  7762 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 15:14:19.405  7762  7762 I bluedroid-qcom: get_profile_interface pan
09-13 15:14:19.413  7762  7762 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-13 15:14:19.413  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
,09-13 15:14:19.416  7762  7762 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-13 15:14:19.433  7762  7762 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 15:14:19.434  7762  7762 D BtGatt.GattService: Received start request. Starting profile...
09-13 15:14:19.434  7762  7762 D BtGatt.GattService: start()
09-13 15:14:19.434  7762  7762 I bluedroid-qcom: get_profile_interface gatt
09-13 15:14:19.435  7762  7762 D BtGatt.AdvertiseManager: advertise manager created
09-13 15:14:19.448  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
,09-13 15:14:19.453  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:19.454  7762  7762 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 15:14:19.456  7762  7762 V BluetoothMapService: BluetoothMapBinder()
09-13 15:14:19.458  7762  7762 D BluetoothMapService: Received start request. Starting profile...
09-13 15:14:19.458  7762  7762 D BluetoothMapService: start()
09-13 15:14:19.463  7762  7762 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-13 15:14:19.463  7762  7762 D BluetoothMapEmailAppObserver: createReceiver()
09-13 15:14:19.464  7762  7762 D BluetoothMapEmailAppObserver: initObservers()
,09-13 15:14:19.465  7762  7762 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 15:14:19.487  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
,09-13 15:14:19.495  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:19.499  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:19.502  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:19.502  7762  7762 V PanService: [BTUI] SIM Extra State :ABSENT
,09-13 15:14:19.506  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 15:14:19.509  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 15:14:19.509  7762  7762 V BluetoothMapService: Handler(): got msg=1
09-13 15:14:19.510  7762  7999 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 15:14:19.510  7762  7999 I bluedroid-qcom: enable
09-13 15:14:19.510  7762  8046 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 15:14:19.510  7762  8046 I bt-btu  : btu_task pending for preload complete event
09-13 15:14:19.510  7762  7999 I bt_hci_bdroid: init
09-13 15:14:19.512  7762  7999 I bt_vendor: bt-vendor : init
09-13 15:14:19.512  7762  7999 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 15:14:19.512  7762  7999 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 15:14:19.512  7762  7999 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 15:14:19.512  7762  7999 D bt_userial_mct: userial_init
09-13 15:14:19.512  7762  7999 D bt_hci_bdroid: set_power 1
09-13 15:14:19.512  7762  7999 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 15:14:19.512  7762  7999 I bt_vendor: Starting hciattach daemon
09-13 15:14:19.512  7762  7999 I bt_vendor: try to set true
09-13 15:14:19.506  8049  8049 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 15:14:19.516  8049  8049 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 15:14:19.542  8050  8050 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 15:14:19.628  8056  8056 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 15:14:19.640  8057  8057 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 15:14:19.665  8059  8059 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 15:14:19.678  8060  8060 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-13 15:14:19.690  8061  8061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 15:14:19.703  8062  8062 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-13 15:14:19.745  8064  8064 I libmdmdetect: ESOC framework not supported
09-13 15:14:19.746  8064  8064 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 15:14:19.754  8064  8064 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-13 15:14:19.755  8064  8064 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 15:14:19.755  8064  8064 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 15:14:19.755  8064  8064 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 15:14:19.755  8064  8064 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 15:14:19.755  8064  8064 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 15:14:19.755  8064  8064 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 15:14:19.795  8064  8065 E QC-QMI  : qmi_client [8064] 15: failed to locate client data
,09-13 15:14:19.796   465   465 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 15:14:19.797   465   465 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-13 15:14:19.844  8066  8066 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 15:14:19.859  8067  8067 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 15:14:19.918  7762  7999 I bt_vendor: bluetooth satus is on
,09-13 15:14:19.918  7762  7999 D bt_hci_bdroid: preload
,09-13 15:14:19.919  7762  8048 D bt_userial_mct: userial_open(port:0)
09-13 15:14:19.919  7762  8048 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-13 15:14:19.924  7762  8048 I bt_vendor: Done intiailizing UART
,09-13 15:14:19.928  7762  8048 I bt_vendor: Done intiailizing UART
,09-13 15:14:19.929  7762  8048 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-13 15:14:19.929  7762  8048 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 15:14:19.929  7762  8046 I bt-btu  : btu_task received preload complete event
,09-13 15:14:19.931  7762  8046 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 15:14:19.932  7762  8046 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,09-13 15:14:19.946  7762  8046 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-13 15:14:19.959  7762  8069 D bt_userial_mct: Entering userial_read_thread()
,09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_A2D,
09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_GAP
,09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_PAN
,09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_GATT,
09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_SMP
,09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 15:14:19.963  7762  8046 I         : BTE_InitTraceLevels -- TRC_BTIF,
09-13 15:14:20.063  7762  8046 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-13 15:14:20.063  7762  8046 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa019e061 
09-13 15:14:20.063  7762  8046 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa019e061 
,09-13 15:14:20.115  7762  8002 E bt-btif : Calling BTA_HhEnable
,09-13 15:14:20.115  7762  8002 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-13 15:14:20.124  7762  8046 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-13 15:14:20.124  7762  8046 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 15:14:20.124  7762  8046 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 15:14:20.125  7762  8046 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 15:14:20.125  7762  8046 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 15:14:20.126  7762  8002 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 15:14:20.131  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-13 15:14:20.139  7762  8002 D BluetoothAdapterProperties: Name is: G3
09-13 15:14:20.141  7762  8002 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:14:20.141  7762  8002 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:14:20.141  7762  8002 D bt_hci_bdroid: postload
09-13 15:14:20.142  7762  8048 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 15:14:20.142  7762  8046 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 15:14:20.143  7762  8048 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 15:14:20.143  7762  8002 D bte_conf: Device ID record 1 : primary
09-13 15:14:20.144  7762  8048 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 15:14:20.144  7762  8048 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 15:14:20.143  7762  8002 D bte_conf:   vendorId            = 00c4
09-13 15:14:20.144  7762  8002 D bte_conf:   vendorIdSource      = 0001
09-13 15:14:20.144  7762  8002 D bte_conf:   product             = 13a1
09-13 15:14:20.144  7762  8002 D bte_conf:   version             = 1000
09-13 15:14:20.144  7762  8002 D bte_conf:   clientExecutableURL = 
09-13 15:14:20.144  7762  8002 D bte_conf:   serviceDescription  = 
09-13 15:14:20.144  7762  8002 D bte_conf:   documentationURL    = 
09-13 15:14:20.144  7762  8002 D bte_conf: bte_load_did_conf no section named DID2.
09-13 15:14:20.147  7762  7999 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 15:14:20.148  7762  7999 D BluetoothAdapterProperties: ScanMode =  20
09-13 15:14:20.148  7762  7999 D BluetoothAdapterProperties: State =  11
09-13 15:14:20.148  7762  7999 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 15:14:20.148  7762  7999 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 15:14:20.148  7762  7999 D BluetoothAdapterProperties: Setting state to 12
09-13 15:14:20.148  7762  7999 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 15:14:20.151  7762  8002 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 15:14:20.151  7762  8002 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-13 15:14:20.156  8074  8074 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:20.156  8074  8074 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:20.176  1032  1094 D BluetoothManagerService: Message: 60
09-13 15:14:20.176  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 15:14:20.176  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-13 15:14:20.179  7762  8046 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:20.179  7762  8046 W bt-smp  : Plain text(LSB ~ MSB) = 18 47 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:20.180  7762  8046 W bt-smp  : Encrypted text(LSB ~ MSB) = 4d da c0 76 b0 52 cb 30 95 01 b4 db c7 e8 59 6c 
09-13 15:14:20.180  7762  8048 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 15:14:20.180  7762  8046 W bt-btm  : Stopping oneshot timer
09-13 15:14:20.181  7762  7999 I BluetoothAdapterState: Entering On State
09-13 15:14:20.183  7762  8069 E bt_mct  : hci lib postload completed
09-13 15:14:20.184  7762  7999 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 15:14:20.184  7762  7999 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 15:14:20.186  7762  7999 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 15:14:20.188  7762  7999 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-13 15:14:20.194  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 15:14:20.227  7762  8046 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:20.227  7762  8046 W bt-smp  : Plain text(LSB ~ MSB) = e4 89 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:20.227  7762  8046 W bt-smp  : Encrypted text(LSB ~ MSB) = d6 21 89 78 72 32 52 3e 3c 50 64 d5 fb d7 fb 13 
,09-13 15:14:20.230  7762  8046 W bt-btm  : Stopping oneshot timer
09-13 15:14:20.232  7762  7999 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 15:14:20.233  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:20.233  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:20.233  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:20.233  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:14:20.233  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:20.233  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:20.233  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:20.233  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:20.242  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:14:20.247  7762  8046 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:20.247  7762  8046 W bt-smp  : Plain text(LSB ~ MSB) = 0f 41 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:20.247  7762  8046 W bt-smp  : Encrypted text(LSB ~ MSB) = 37 77 c9 c3 58 16 ef 40 c0 04 de c3 3d 1b 90 59 
09-13 15:14:20.248  7762  8046 W bt-btm  : Stopping oneshot timer
09-13 15:14:20.248  7762  8002 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:14:20.248  7762  8002 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 15:14:20.253  6971  6987 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 15:14:20.266  7762  8046 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:20.266  7762  8046 W bt-smp  : Plain text(LSB ~ MSB) = 2e 58 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:20.266  7762  8046 W bt-smp  : Encrypted text(LSB ~ MSB) = 88 54 01 e1 5e 44 81 8f 9a 23 d2 a8 cb 55 5d fc 
09-13 15:14:20.266  7762  8046 W bt-btm  : Stopping oneshot timer
,09-13 15:14:20.278  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 15:14:20.279  6971  6971 D BluetoothA2dp: Proxy object connected
09-13 15:14:20.279  6971  6971 D A2dpProfile: Bluetooth service connected
09-13 15:14:20.280  1032  1032 D BluetoothA2dp: Proxy object connected
,09-13 15:14:20.283  1877  2531 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:14:20.290  6971  7081 D BluetoothPan: onBluetoothStateChange on: true
09-13 15:14:20.290  6971  7081 D BluetoothPan: onBluetoothStateChange call bindService
09-13 15:14:20.290  1877  1877 D BluetoothHeadset: Proxy object connected
09-13 15:14:20.292  6971  6987 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 15:14:20.293  7762  8046 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 15:14:20.293  7762  8046 W bt-smp  : Plain text(LSB ~ MSB) = 8c b3 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 15:14:20.293  7762  8046 W bt-smp  : Encrypted text(LSB ~ MSB) = ae 42 38 46 86 53 8c 84 c5 ef d0 20 ed 9d 02 11 
09-13 15:14:20.293  7762  8046 W bt-btm  : Stopping oneshot timer
09-13 15:14:20.297  6971  6988 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 15:14:20.298  8079  8079 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 15:14:20.299  6971  7081 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 15:14:20.301  6971  6971 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 15:14:20.301  6971  6971 D PanProfile: Bluetooth service connected
09-13 15:14:20.303  6971  6988 D BluetoothMap: onBluetoothStateChange: up=true
09-13 15:14:20.303  6971  6971 D BluetoothHeadset: Proxy object connected
09-13 15:14:20.303  6971  6971 D HeadsetProfile: Bluetooth service connected
09-13 15:14:20.305  1877  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:14:20.306  6971  6971 D BluetoothInputDevice: Proxy object connected
09-13 15:14:20.306  6971  6971 D HidProfile: Bluetooth service connected
,09-13 15:14:20.308  1877  4366 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:14:20.308  1877  1877 D BluetoothHeadset: Proxy object connected
09-13 15:14:20.310  1877  1877 D BluetoothHeadset: Proxy object connected
09-13 15:14:20.310  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 15:14:20.310  6971  6971 D BluetoothMap: Proxy object connected
09-13 15:14:20.310  6971  6971 D MapProfile: Bluetooth service connected
09-13 15:14:20.310  6971  6971 D BluetoothMap: getConnectedDevices()
09-13 15:14:20.311  1032  1032 D BluetoothHeadset: Proxy object connected
09-13 15:14:20.311  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 15:14:20.312  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 15:14:20.312  7762  8007 V BluetoothMapService: getConnectedDevices()
09-13 15:14:20.313  1966  1966 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:20.313  1966  2195 D LGBluetoothAPIService: Message: 1
09-13 15:14:20.313  1966  2195 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 15:14:20.313  1966  2195 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-13 15:14:20.314  1966  2195 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-13 15:14:20.314  1579  1579 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 15:14:20.317  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:20.323  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-13 15:14:20.323  1032  1094 D BluetoothManagerService: Message: 40
09-13 15:14:20.323  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,09-13 15:14:20.328  7762  7762 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:20.328  7762  7762 D BluetoothMapService: STATE_ON
09-13 15:14:20.343  6971  6971 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 15:14:20.345  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:20.345  6971  6971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 15:14:20.345  7762  7762 V BluetoothPbapService: Pbap Service onCreate
09-13 15:14:20.345  7762  7762 V BluetoothPbapService: Starting PBAP service
,09-13 15:14:20.348  7762  7762 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 15:14:20.348  7762  7762 V BluetoothPbapService: Pbap Service onBind
09-13 15:14:20.350  7762  7762 V BluetoothMapService: Handler(): got msg=1
09-13 15:14:20.350  7762  7762 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 15:14:20.351  7762  7762 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:20.351  7762  7762 V BluetoothPbapService: state: 12
09-13 15:14:20.351  7762  7762 V BluetoothPbapService: Handler(): got msg=1
09-13 15:14:20.352  7762  7762 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 15:14:20.353  7762  7762 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 15:14:20.353  7762  7762 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:20.353  7762  7762 V BluetoothPbapReceiver: ***********state = 12
09-13 15:14:20.354  7762  8099 V BluetoothPbapService: Pbap Service initSocket
09-13 15:14:20.355  7762  8098 D BluetoothMapMasInstance: MAS initSocket()
09-13 15:14:20.355  7762  8098 D BluetoothMapMasInstance:   masId = 00
09-13 15:14:20.355  7762  8098 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 15:14:20.355  7762  8098 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 15:14:20.355  7762  8098 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 15:14:20.357  1032  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 15:14:20.358  6971  6971 D DockEventReceiver: finishStartingService: stopping service
09-13 15:14:20.360  6971  6971 D BluetoothPbap: Proxy object connected
09-13 15:14:20.360  6971  6971 D PbapServerProfile: Bluetooth service connected
09-13 15:14:20.360  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:20.361  2262  2262 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 15:14:20.361  7762  8099 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:20.361  7762  8098 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:20.361  2262  2262 D c       : Getting all permits...
09-13 15:14:20.361  2262  2262 D a       : Opening database...
09-13 15:14:20.364  7762  8099 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-13 15:14:20.364  7762  8098 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-13 15:14:20.364  7762  8099 V BluetoothPbapService: Succeed to create listening socket 
09-13 15:14:20.364  7762  8098 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 15:14:20.365  7762  8099 V BluetoothPbapService: Accepting socket connection...
09-13 15:14:20.365  7762  8098 D BluetoothMapMasInstance: Accepting socket connection...
09-13 15:14:20.365  7762  8002 D BluetoothAdapterProperties: Scan Mode:21
09-13 15:14:20.365  7762  8002 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 15:14:20.366  2262  2262 D a       : Opening database auth.proximity.permit_store...
09-13 15:14:20.369  2262  2262 D a       : Closing database...
09-13 15:14:20.369  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:20.378  6971  6971 D BluetoothPermissionRequest: onReceive
09-13 15:14:20.380  6971  6971 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 15:14:20.381  6971  6971 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 15:14:20.384  7762  7762 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 15:14:20.385  7762  7762 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 15:14:20.391  7762  7762 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-13 15:14:20.404  7762  7762 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 15:14:20.404  7762  7762 V BtOppService: onCreate
,09-13 15:14:20.408  7762  7762 V BluetoothOppNotification: send message
09-13 15:14:20.410  7762  7762 V BtOppService: Starting RfcommListener
09-13 15:14:20.414  7762  7762 D BluetoothOppPreference: Dumping Names:  
09-13 15:14:20.414  7762  7762 D BluetoothOppPreference: {}
09-13 15:14:20.414  7762  7762 D BluetoothOppPreference: Dumping Channels:  
09-13 15:14:20.414  7762  7762 D BluetoothOppPreference: {}
09-13 15:14:20.417  7762  7762 V BtOppService: onStartCommand
,09-13 15:14:20.421  7762  8107 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 15:14:20.422  7762  7762 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:14:20.423  7762  7762 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 15:14:20.425  7762  8107 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 15:14:20.427  7762  8104 V BtOppService: Deleted complete outbound shares, number =  0
09-13 15:14:20.427  7762  7762 V BluetoothOppNotification: new notify threadi!
09-13 15:14:20.427  7762  7762 V BluetoothOppNotification: send delay message
09-13 15:14:20.428  7762  7762 V BtOppService: start RfcommListener
09-13 15:14:20.428  7762  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14588706 on behalf of 
09-13 15:14:20.429  7762  8107 V BluetoothOppNotification: update too frequent, put in queue
09-13 15:14:20.430  7762  8104 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 15:14:20.430  7762  7762 V BtOppService: RfcommListener started
,09-13 15:14:20.431  7762  8104 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 15:14:20.432  7762  8107 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 15:14:20.433  7762  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 15:14:20.433  7762  8104 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@177981c7 on behalf of 
09-13 15:14:20.433  7762  8109 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 15:14:20.434  1032  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:20.435  7762  8109 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:20.435  7762  8109 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-13 15:14:20.436  7762  8109 V BtOppRfcommListener: Started RFCOMM listener....
09-13 15:14:20.436  7762  8109 I BtOppRfcommListener: Accept thread started.
09-13 15:14:20.436  7762  8109 V BtOppRfcommListener: Accepting connection...
09-13 15:14:20.438  7762  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b3113f4 on behalf of 
09-13 15:14:20.439  7762  8108 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 15:14:20.440  7762  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 15:14:20.441  7762  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ab2071d on behalf of 
09-13 15:14:20.441  7762  8108 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 15:14:20.442  7762  8108 V BluetoothOppNotification: outbound notification was removed.
09-13 15:14:20.442  7762  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-13 15:14:20.443  7762  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19660d92 on behalf of 
09-13 15:14:20.444  7762  8108 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 15:14:20.445  7762  8108 V BluetoothOppNotification: inbound notification was removed.
09-13 15:14:20.446  7762  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 15:14:20.447  7762  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39827363 on behalf of 
09-13 15:14:20.449  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:20.449  7762  7762 V BluetoothFtpService: Ftp Service onCreate
09-13 15:14:20.449  7762  7762 I BluetoothFtpService: Ftp Service onCreate
09-13 15:14:20.450  7762  7762 V BluetoothFtpService: Ftp Service onStartCommand
09-13 15:14:20.450  7762  7762 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:20.450  7762  7762 V BluetoothFtpService: Starting Listening on sockets
09-13 15:14:20.450  7762  7762 V BtOppService: ContentObserver received notification
09-13 15:14:20.450  7762  7762 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 15:14:20.451  7762  7762 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 15:14:20.451  7762  7762 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 15:14:20.451  7762  7762 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:20.451  7762  7762 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 15:14:20.451  7762  7762 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 15:14:20.451  7762  8110 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 15:14:20.451  7762  8110 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 15:14:20.452  7762  8110 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e6cf819 on behalf of 
09-13 15:14:20.452  7762  7762 V BtOppService: ContentObserver received notification
09-13 15:14:20.452  7762  7762 V BluetoothFtpService: Handler(): got msg=1
09-13 15:14:20.453  7762  7762 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 15:14:20.453  7762  7762 V BluetoothFtpService: Ftp Service initSocket
,09-13 15:14:20.456  1032  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 15:14:20.457  7762  7762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:14:20.457  7762  8110 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 15:14:20.457  7762  8110 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 15:14:20.458  7762  8110 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@345370de on behalf of 
09-13 15:14:20.459  7762  7762 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-13 15:14:20.459  7762  7762 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 15:14:20.459  7762  8110 V BluetoothOppNotification: update too frequent, put in queue
09-13 15:14:20.460  7762  8111 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-13 15:14:20.467  7762  8110 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-13 15:14:20.473  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d14d62a
09-13 15:14:20.474  7762  7762 V BluetoothSapService: Sap Service onCreate
,09-13 15:14:20.475  7762  7762 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:14:20.475  7762  7762 V BluetoothSapService: state: 12
09-13 15:14:20.476  7762  7762 V BluetoothSapService: Starting SAP server process
09-13 15:14:20.477  7762  7762 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 15:14:20.476  8112  8112 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:20.476  8112  8112 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:20.479  7762  8113 V BluetoothSapService: Sap Service initRfcommSocket
09-13 15:14:20.480  1032  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 15:14:20.482  7762  8113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:14:20.483  7762  8113 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-13 15:14:20.483  7762  8113 V BluetoothSapService: Succeed to create listening socket 
09-13 15:14:20.483  7762  8113 V BluetoothSapService: Accepting socket connection...
09-13 15:14:20.486  8112  8112 V BT_SAP  : Event pipe created
,09-13 15:14:20.486  8112  8112 V BT_SAP  : create_server_socket qcom.sap.server
09-13 15:14:20.486  8112  8112 V BT_SAP  : created socket fd 6
09-13 15:14:20.876  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-13 15:14:20.876  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:20.876  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,09-13 15:14:20.876  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-13 15:14:20.876  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:20.876  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:20.876  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:20.876  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:14:20.892  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:20.894  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:20.895  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34a92cdf added. We now have 8 listener(s)
09-13 15:14:20.895  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:14:20.902  1032  2038 D WifiServiceImplEx: setWifiEnabled: false pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 15:14:20.902  1032  2038 D WifiService: setWifiEnabled: false pid=6853, uid=10118
09-13 15:14:20.902  1032  2038 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 15:14:20.908  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:20.912  1032  1996 D WifiServiceImplEx: setWifiEnabled: true pid=6853, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 15:14:20.913  1032  1996 D WifiService: setWifiEnabled: true pid=6853, uid=10118
09-13 15:14:20.913  1032  1996 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 15:14:20.929  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 15:14:20.929  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 15:14:20.929  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,09-13 15:14:20.934  1032  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 15:14:20.934  1032  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 15:14:20.936  1032  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 15:14:20.936  1032  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 15:14:20.937  1032  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 15:14:20.937  1032  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 15:14:20.937  1032  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 15:14:20.937  1032  1536 E WifiHW  : unknown target_country: EU , set to default
09-13 15:14:20.937  1032  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 15:14:20.937  1032  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 15:14:20.937  1032  1536 I WifiUtil: gEnableBmps=1
,09-13 15:14:21.429  7762  7762 V BluetoothOppNotification: new notify threadi!
09-13 15:14:21.429  7762  7762 V BluetoothOppNotification: send delay message
,09-13 15:14:21.435  7762  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-13 15:14:21.445  7762  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e21bcea on behalf of 
09-13 15:14:21.446  7762  8132 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-13 15:14:21.456  7762  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 15:14:21.466  7762  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e8ebdb on behalf of 
09-13 15:14:21.466  7762  8132 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-13 15:14:21.505   314   891 D SoftapController: Softap fwReload - Ok
,09-13 15:14:21.509  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 15:14:21.509  1032  1094 D Tethering: InitialState.processMessage what=4
09-13 15:14:21.512  1032  1536 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (570ms)
09-13 15:14:21.528   314   891 D CommandListener: Setting iface cfg
09-13 15:14:21.528   314   891 D CommandListener: Trying to bring down wlan0
,09-13 15:14:21.531   314   891 D CommandListener: Clearing all IP addresses on wlan0
,09-13 15:14:21.533  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 15:14:21.533  1032  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 15:14:21.550  1032  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 15:14:21.550  1032  1536 E WifiStateMachine: useWiFiOffloading() : false
09-13 15:14:21.550  1032  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 15:14:21.555  1032  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 15:14:21.555  1032  1536 D WifiMonitor: connecting to supplicant
09-13 15:14:21.546  8134  8134 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:21.546  8134  8134 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:21.574  7762  8132 V BluetoothOppNotification: outbound notification was removed.
09-13 15:14:21.575  7762  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 15:14:21.576  7762  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b6b5678 on behalf of 
09-13 15:14:21.576  7762  8132 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-13 15:14:21.579  7762  8132 V BluetoothOppNotification: inbound notification was removed.
09-13 15:14:21.579  7762  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 15:14:21.588  8134  8134 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 15:14:21.588  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:21.589  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 15:14:21.589  7762  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19dc9151 on behalf of 
,09-13 15:14:21.594  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:21.596  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 15:14:21.597  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 15:14:21.597  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 15:14:21.597  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 15:14:21.597  6971  6971 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 15:14:21.598  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 15:14:21.599  6971  6971 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 15:14:21.599  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 15:14:21.599  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 15:14:21.599  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 15:14:21.599  6971  6971 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 15:14:21.599  6971  6971 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 15:14:21.601  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 15:14:21.601  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 15:14:21.601  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 15:14:21.601  6971  6971 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 15:14:21.602  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 15:14:21.602  6971  6971 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 15:14:21.602  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 15:14:21.602  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 15:14:21.603  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 15:14:21.603  6971  6971 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 15:14:21.603  6971  6971 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 15:14:21.621  8134  8134 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 15:14:21.621  8134  8134 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-13 15:14:21.650  1032  2350 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8153 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-13 15:14:21.665  8134  8134 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 15:14:21.702  8134  8134 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 15:14:21.708  1032  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 15:14:21.709  1032  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 15:14:21.710  1032  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 15:14:21.710  1032  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 15:14:21.710  1032  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:21.711  1032  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:21.711  1032  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 15:14:21.711  1032  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 15:14:21.712  1032  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 15:14:21.712  1032  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 15:14:21.712  1032  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 15:14:21.715  1032  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 15:14:21.715  1032  1536 E WifiStateMachine: useWiFiOffloading() : false
09-13 15:14:21.715  1032  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 15:14:21.715  1032  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 15:14:21.715  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:21.715  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:21.715  1032  1536 D WifiNative-wlan0: SET update_config 1: returned true
09-13 15:14:21.716  1032  1536 D WifiConfigStore: Loading config and enabling all networks 
09-13 15:14:21.716  1032  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 15:14:21.716  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:21.716  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:21.716  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 15:14:21.716  1032  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 15:14:21.718  1966  1966 D WfdService: Waiting for WifiP2p enabling
09-13 15:14:21.718  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:21.721  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 15:14:21.721  1032  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 15:14:21.722  1032  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 15:14:21.726  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:21.726  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:21.726  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:21.726  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:21.726  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:21.726  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:21.726  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:21.726  6853  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:21.728  6853  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:14:21.731  1032  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 15:14:21.732  1032  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-13 15:14:21.748  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 15:14:21.748  8134  8134 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-13 15:14:21.750  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 15:14:21.750  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 15:14:21.750  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 15:14:21.750  1032  8170 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 15:14:21.750  1032  8170 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 15:14:21.761  1032  2070 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8175 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 15:14:21.763  1032  1536 D WifiStateMachine: enableVerboseLogging : level 2
09-13 15:14:21.763  1032  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,09-13 15:14:21.763  1032  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 15:14:21.763  1032  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 15:14:21.764  1032  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 15:14:21.764  1032  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 15:14:21.764  1032  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 15:14:21.764  1032  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 15:14:21.764  1032  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 15:14:21.764  1032  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 15:14:21.765  1032  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 15:14:21.765  1032  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 15:14:21.765  1032  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 15:14:21.765  1032  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 15:14:21.765  1032  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 15:14:21.766  8153  8173 W FormManager: Network not available. Please check & try again.
09-13 15:14:21.767  1966  1966 D WfdsService: Supplicant Connection state is changed : true
09-13 15:14:21.767  1032  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 15:14:21.767  1032  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 15:14:21.767  1966  2314 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 15:14:21.767  1966  2314 D WfdsService: Set the WFDS Monitor: true
09-13 15:14:21.767  1966  2314 D WfdsMonitor: WfdsMonitorThread create
09-13 15:14:21.767  1032  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 15:14:21.767  1032  1536 D WifiNative-HAL: Setting external_sim to 1
09-13 15:14:21.767  1032  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 15:14:21.767  1966  2314 D WfdsMonitor: WFDS Monitor is created and started
09-13 15:14:21.768  1966  2314 D WfdsService: WiFi: Supplicant connection re-established
09-13 15:14:21.768  1032  1536 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 15:14:21.768  1032  1536 I WifiNative-HAL: startHal
09-13 15:14:21.768  1032  1536 D wifi    : setting scan oui 0xaf574220
09-13 15:14:21.768  1032  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 15:14:21.768  1032  1536 I WifiNative-HAL: startHal
09-13 15:14:21.768  1032  1536 D wifi    : setting scan oui 0xaf574220
09-13 15:14:21.768  1966  8186 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 15:14:21.769  1032  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 15:14:21.769  1966  8186 E CtrlSupplicant: Succeed to open control connection
09-13 15:14:21.769  1032  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 15:14:21.769  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 15:14:21.769  1966  8186 E CtrlSupplicant: Succeed to open monitor connection
09-13 15:14:21.769  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 15:14:21.769  1966  8186 D WfdsMonitor: Supplicant connection established
09-13 15:14:21.769  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 15:14:21.769  1966  2314 D WfdsService: Connected to the supplicant for wfds
09-13 15:14:21.770  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 15:14:21.770  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 15:14:21.770  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 15:14:21.770  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 15:14:21.770  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 15:14:21.770  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 15:14:2,1.770  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 15:14:21.771  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 15:14:21.771  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 15:14:21.771  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 15:14:21.771  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 15:14:21.771  7791  7791 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:21.772  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 15:14:21.772  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 15:14:21.772  8134  8134 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 15:14:21.772  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 15:14:21.772  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 15:14:21.772  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 15:14:21.772  1032  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 15:14:21.773  1032  1536 E WifiNative: : [202,731,665 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 15:14:21.773  1032  1536 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 15:14:21.774  1032  1536 D WifiNative-wlan0: RECONNECT: returned true
09-13 15:14:21.774  1032  1536 D WifiNative-wlan0: doString: [STATUS]
09-13 15:14:21.774  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 15:14:21.774  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 15:14:21.775  1032  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 15:14:21.775  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 1
,09-13 15:14:21.780  1032  1536 D WifiNative-wlan0: SET ps 1: returned true
09-13 15:14:21.780  1032  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.780  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 15:14:21.781  1032  1032 D RttService: SCAN_AVAILABLE : 3
09-13 15:14:21.781  1032  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.781  1032  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.781  1032  1555 I WifiNative-HAL: startHal
09-13 15:14:21.781  1032  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf574220
09-13 15:14:21.781  1032  1555 D wifi    : failed to get capabilities : -3
09-13 15:14:21.781  1032  1555 E WifiScanningService: could not get scan capabilities
09-13 15:14:21.781  1032  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 15:14:21.781  1032  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 15:14:21.782  1032  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 15:14:21.782  1032  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 15:14:21.782   314   891 D CommandListener: Setting iface cfg
09-13 15:14:21.782   314   891 D CommandListener: Trying to bring up p2p0
09-13 15:14:21.782  8153  8174 V FormManager: Network unavailable.
09-13 15:14:21.783  1032  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 15:14:21.783  1032  1535 D LGWifiP2pService: P2pEnablingState
09-13 15:14:21.783  1032  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 15:14:21.783  1032  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.783  1032  1535 D LGWifiP2pService: P2p socket connection successful
09-13 15:14:21.783  1032  1535 D LGWifiP2pService: P2pEnabledState
09-13 15:14:21.783  1032  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 15:14:21.783  1032  1535 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 15:14:21.783  1032  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 15:14:21.783  1032  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 15:14:21.784  8134  8134 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 15:14:21.784  1966  1966 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 15:14:21.784  1966  1966 D WfdsService: WifiP2pState is changed : true
09-13 15:14:21.784  1966  2314 D WfdsService: Receive the WFDS_ENABLE Method
09-13 15:14:21.784  1966  2314 D WfdsService: Set the WFDS Monitor: true
09-13 15:14:21.784  1966  2314 D WfdsService: Connected to the supplicant for wfds
09-13 15:14:21.784  1032  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 15:14:21.784  1966  2314 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 15:14:21.784  8134  8134 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 15:14:21.784  1032  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 15:14:21.785  1032  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 15:14:21.785  1032  1535 D WifiNative-p2p0: SET device_name G3: returned true
09-13 15:14:21.785  1032  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 15:14:21.785  1032  1535 D LGWifiP2pService: before postfix = G3
09-13 15:14:21.785  1032  1535 D WifiServerServiceExt: postfix byte check : 2
09-13 15:14:21.785  1032  1535 D LGWifiP2pService: after postfix = G3
09-13 15:14:21.785  1032  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 15:14:21.785  1966  2314 D WfdsService: selectPreferredScanChannel [36]
09-13 15:14:21.785  1966  2314 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 15:14:21.7,86  1966  1966 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 15:14:21.786  1966  1966 D WfdsService: isConnected: false
09-13 15:14:21.788  1032  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
,09-13 15:14:21.788  1032  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 15:14:21.789  1032  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 15:14:21.789  1032  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 15:14:21.790  1032  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
,09-13 15:14:21.790  1032  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 15:14:21.790  8134  8134 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 15:14:21.790  1032  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 15:14:21.790  1032  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 15:14:21.790  1032  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 15:14:21.790  1032  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 15:14:21.791  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=202749  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 15:14:21.791  1032  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 15:14:21.791  1032  1535 D WifiNative-HAL: p2pGetDeviceAddress
09-13 15:14:21.791  1032  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 15:14:21.792  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=202751  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 15:14:21.793  1032  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 15:14:21.793  1032  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 15:14:21.793  1032  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 15:14:21.793  1032  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 15:14:21.793  1032  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 15:14:21.794  1032  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 15:14:21.794  1032  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 15:14:21.794  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:21.794  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:21.794  1032  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 15:14:21.794  1032  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 15:14:21.795  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:21.795  1032  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 15:14:21.796  1032  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 15:14:21.796  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 15:14:21.796  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:21.796  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:21.796  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 15:14:21.797  1966  1966 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 15:14:21.797  1966  1966 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 15:14:21.797  1966  1966 D WfdsService: Update P2p Interface State: 3
09-13 15:14:21.800  8153  8174 V FormManager: Network unavailable.
,09-13 15:14:21.804  1032  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 15:14:21.804  1032  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 15:14:21.804  1032  1535 D LGWifiP2pService: InactiveState
09-13 15:14:21.804  1032  1535 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.804  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.804  1032  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 15:14:21.805  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 15:14:21.805  8134  8134 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:21.805  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 15:14:21.805  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:21.805  1032  8170 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:21.805  1032  8170 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:21.806  8134  8134 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 15:14:21.806  8134  8134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.806  1032  8170 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:21.806  1966  8186 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:21.806  1032  8170 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.806  1032  8170 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.806  1032  8170 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.806  8134  8134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.806  1966  8186 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:21.806  1032  8170 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:21.806  1032  8170 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.806  1032  8170 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.806  1032  8170 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.809  1032  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 15:14:21.809  1032  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 15:14:21.809  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 15:14:21.809  1032  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 15:14:21.810  8134  8134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:21.810  1032  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 15:14:21.810  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 15:14:21.810  1032  8170 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 15:14:21.810  1032  8170 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:21.810  1032  8170 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:21.810  1032  8170 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 15:14:21.810  1966  8186 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE in,it=USER type=COUNTRY alpha2=CZ]
09-13 15:14:21.810  8134  8134 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 15:14:21.810  8134  8134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.810  1966  8186 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:21.811  1032  8170 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:21.811  1032  8170 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.811  1032  8170 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.811  1032  8170 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.811  8134  8134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.811  1032  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1966  8186 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: InactiveState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.812  1032  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.813  1032  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.813  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.813  1032  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:21.813  1032  8170 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 15:14:21.813  1032  8170 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.813  1032  8170 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 15:14:21.813  1032  8170 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-13 15:14:21.813  1032  1032 E WifiServerServiceExt: No p2p device connected
09-13 15:14:21.813  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 15:14:21.814  8134  8134 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 15:14:21.814  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 15:14:21.814  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 15:14:21.814  1032  8170 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 15:14:21.815  1032  8170 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 15:14:21.815  1966  2314 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 15:14:21.815  1032  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 15:14:21.815  1032  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 15:14:21.815  1032  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 15:14:21.815  1032  1536 D WifiNative-wlan0: doBoolean: SCAN
09-13 15:14:21.815  1032  1536 D WifiNative-wlan0: SCAN: returned false
09-13 15:14:21.816  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=202775  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 15:14:21.818  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:21.818  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:21.819  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:21.819  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:21.819  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 15:14:21.819  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:21.819  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=202778  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 15:14:21.820  1032  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 15:14:21.821  1032  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 15:14:21.821  1032  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 15:14:21.822  1032  1597 I ActivityManager: Killing 7254:com.android.chrome/u0a57 (adj 15): empty #17
09-13 15:14:21.822  1032  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 15:14:21.822  1032  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 15:14:21.841  8175  8175 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 15:14:21.852  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:21.852  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 15:14:21.854  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:14:21.856  1032  1047 W libprocessgroup: failed to open /acct/uid_10057/pid_7254/cgroup.procs: No such file or directory
09-13 15:14:21.857  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:21.857  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 15:14:21.862  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:21.863  1032  1574 I ActivityManager: Killing 7275:com.lge.drmservice/u0a62 (adj 15): empty #17
09-13 15:14:21.898  1032  2349 W libprocessgroup: failed to open /acct/uid_10062/pid_7275/cgroup.procs: No such file or directory
,09-13 15:14:21.917  8175  8175 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 15:14:21.921  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 15:14:21.928  8153  8197 W FormManager: Network not available. Please check & try again.
,09-13 15:14:21.933  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:21.948  8153  8198 V FormManager: Network unavailable.
,09-13 15:14:21.953  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:14:21.953  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:21.953  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:21.953  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:21.953  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:21.953  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:14:21.953  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:14:21.953  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:14:21.954  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:14:21.960  6853  6932 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 15:14:21.961  6853  6932 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 15:14:21.964  8153  8198 V FormManager: Network unavailable.
09-13 15:14:21.966  6853  6932 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@593fbc9 Bundle[{}]
09-13 15:14:21.967  6853  6932 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 15:14:21.967  6853  6932 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 15:14:21.968  6853  6932 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 15:14:21.968  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 15:14:21.969  6853  6932 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 15:14:21.969  4728  4728 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 15:14:21.971  6853  6932 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 15:14:21.971  6853  6932 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 15:14:21.973  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 15:14:21.981  6853  6932 I System.out: Running OutgoingSocketThread
09-13 15:14:21.981  4728  4728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 15:14:21.983  6853  8199 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 906)
09-13 15:14:21.985  6853  8199 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56557
09-13 15:14:21.985  6853  8199 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 15:14:21.991  4728  8200 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 15:14:21.994  4728  8201 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 15:14:21.995  4728  8201 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 15:14:22.037  7862  7873 E UEI.SmartControl: file observer is disposed!
,09-13 15:14:22.042  1032  2038 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8202 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-13 15:14:22.200  8202  8202 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 15:14:22.201  8202  8202 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-13 15:14:22.210  8202  8202 V [BNRBootReceiver]: Boot Receiver Return
09-13 15:14:22.211  8202  8202 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-13 15:14:22.292  1032  1943 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8223 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 15:14:22.293  1032  1943 I ActivityManager: Killing 7292:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-13 15:14:22.311   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 20.092ms
,09-13 15:14:22.332   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 19.851ms
,09-13 15:14:22.351   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 18.685ms
,09-13 15:14:22.400  8134  8134 E wpa_supplicant: USIM:  scard_init function
09-13 15:14:22.400  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 15:14:22.400  8134  8134 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 15:14:22.400  1032  8170 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 15:14:22.401  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 15:14:22.401  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
09-13 15:14:22.401  1032  8170 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 15:14:22.401  1032  1598 W libprocessgroup: failed to open /acct/uid_10085/pid_7292/cgroup.procs: No such file or directory
09-13 15:14:22.401  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 15:14:22.401  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 15:14:22.402  1032  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 15:14:22.402  1032  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 15:14:22.403  1032  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 15:14:22.403  1032  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 15:14:22.404  1032  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-13 15:14:22.411  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=203369  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 15:14:22.414  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:22.414  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:22.415  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.415  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.415  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 15:14:22.416  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.416  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=203374  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 15:14:22.417  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:22.417  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 15:14:22.435  8223  8223 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 15:14:22.459  8223  8223 D PluginManager: init()
,09-13 15:14:22.514  8134  8134 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 15:14:22.518  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 15:14:22.518  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 15:14:22.519  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 15:14:22.519  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 15:14:22.519  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:22.519  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-13 15:14:22.521  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=203479  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 15:14:22.523  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=203481  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 15:14:22.524  1032  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203483
09-13 15:14:22.525  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 15:14:22.525  1032  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203484
09-13 15:14:22.526  1032  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203485
09-13 15:14:22.528  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203486
,09-13 15:14:22.529  1032  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203487
09-13 15:14:22.529  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=203488  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-13 15:14:22.531  8134  8134 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 15:14:22.532  8134  8134 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 15:14:22.532  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:22.532  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:22.535  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.535  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:22.536  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 15:14:22.536  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.536  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.536  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 15:14:22.536  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 15:14:22.536  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 15:14:22.536  1032  8170 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 15:14:22.536  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 15:14:22.537  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 15:14:22.537  1032  8170 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 15:14:22.538  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:22.538  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 15:14:22.540  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=203498  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 15:14:22.541  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.541  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.541  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 15:14:22.542  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:22.542  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,09-13 15:14:22.545  1032  1536 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:22.545  1032  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:22.546  1032  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:22.546  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:22.546  1032  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 15:14:22.548  1032  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=203506  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 15:14:22.549  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=203507  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 15:14:22.549  1032  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=203508
09-13 15:14:22.550  1032  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=203508
09-13 15:14:22.550  1032  1536 D WifiNative-wlan0: doString: [STATUS]
09-13 15:14:22.551  1032  8170 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 15:14:22.551  1032  8170 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 15:14:22.551  1032  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 15:14:22.553  1032  1536 I WifiServiceExtension: setVHTCapabilityType  : false
,09-13 15:14:22.555  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:22.555  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:22.556  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.557  1032  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,09-13 15:14:22.557  1032  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-13 15:14:22.560  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.560  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.560  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 15:14:22.564  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.565  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.565  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 15:14:22.568  1032  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 15:14:22.569  1032  1543 D ConnectivityService: Got NetworkAgent Messenger
09-13 15:14:22.569  1032  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 15:14:22.569  1032  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 15:14:22.569  1032  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 15:14:22.569  1032  1543 D ConnectivityService: NetworkAgent connected
09-13 15:14:22.569  1032  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 15:14:22.569  1032  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-13 15:14:22.574  1032  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 15:14:22.574  1032  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 15:14:22.575  1032  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 15:14:22.575  1032  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 15:14:22.575  1032  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 15:14:22.576  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:22.576  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:22.576  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.579  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 15:14:22.579  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:22.580  1032  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 15:14:22.580  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.581   314   891 D CommandListener: Setting iface cfg
,09-13 15:14:22.584  1032  1536 E WifiStateMachine: Start Dhcp Watchdog 3
09-13 15:14:22.585  1032  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=203543  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:22.585  1032  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=203544  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:22.586  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=203544  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:22.586  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:22.586  1032  8247 D DhcpStateMachine: StoppedState
09-13 15:14:22.587  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 15:14:22.587  1032  8247 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:22.587  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:22.587  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 15:14:22.588  1032  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=203547  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:22.589  1032  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=203547  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:22.589  1032  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=203548  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 15:14:22.590  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13687] from screen [on:0 period:598680062] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 15:14:22.587  1032  8247 D DhcpStateMachine: WaitBeforeStartState
09-13 15:14:22.591  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:598680063] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 15:14:22.591  1032  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 15:14:22.596  1032  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-13 15:14:22.596  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.596  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.596  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.597  1032  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 15:14:22.598  1032  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.599  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.599  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.600  1032  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 15:14:22.600  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:22.600  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 15:14:22.601  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=123,0,0
09-13 15:14:22.601  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=123,0,0
09-13 15:14:22.601  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 15:14:22.602  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 15:14:22.602  1032  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 15:14:22.602  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 15:14:22.603  1032  1536 D WifiNative-wlan0: SET ps 0: returned true
09-13 15:14:22.603  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 15:14:22.603  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 15:14:22.603  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 15:14:22.604  1032  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 15:14:22.604  1032  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 15:14:22.604  1032  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1515c296 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:22.604  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1515c296 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:22.604  1032  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 15:14:22.604  1032  8247 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:22.604  1032  8247 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 15:14:22.605   314   891 D CommandListener: Setting iface cfg
09-13 15:14:22.605   314   891 D CommandListener: Trying to bring up wlan0
09-13 15:14:22.605  1032  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 15:14:22.606  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 15:14:22.606  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 15:14:22.606  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 15:14:22.606  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.607  1032  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.607  1032  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.607  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.608  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 15:14:22.608  1032  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 15:14:22.608  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 15:14:22.610  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 15:14:22.610  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 15:14:22.610  1032  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:22.610  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 15:14:22.610  1032  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:22.610  1032  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 15:14:22.610  1032  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 15:14:22.610  8134  8134 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 15:14:22.611  1032  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 15:14:22.611  1032  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 15:14:22.629  1032  1536 D WifiNative-wlan0: SET ps 1: returned true
09-13 15:14:22.629  1032  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 15:14:22.630  1032  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 15:14:22.630  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 15:14:22.630  1032  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 15:14:22.630  1032  1543 D ConnectivityService: ignoring duplicate network state non-change
,09-13 15:14:22.632  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:22.632  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:22.634  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.634  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.634  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 15:14:22.634  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.637  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.638  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.638  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 15:14:22.638  1032  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 15:14:22.638  1032  1543 D ConnectivityService: Adding iface wlan0 to network 102
09-13 15:14:22.640  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 15:14:22.642  1966  1966 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-13 15:14:22.645  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.645  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.645  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 15:14:22.646  1032  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 15:14:22.647  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 15:14:22.648  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.648  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:22.648  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 15:14:22.655  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:22.655  1579  1579 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 15:14:22.656  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 15:14:22.659  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:22.659  1579  1579 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 15:14:22.659  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.662  1579  1579 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:14:22.662  1579  1579 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 15:14:22.662  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.669  1032  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 15:14:22.669  1032  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-13 15:14:22.670  1032  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-13 15:14:22.671   314   891 E Netd    : netlink response contains error (File exists)
09-13 15:14:22.671  1032  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-13 15:14:22.672  1032  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 15:14:22.672  1032  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-13 15:14:22.672  1032  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-13 15:14:22.673  1032  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 15:14:22.673  1032  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 15:14:22.673  1032  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 15:14:22.673  1032  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,09-13 15:14:22.673  1032  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:22.673  1032  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:22.673  1032  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 15:14:22.673  1032  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:22.673  1032  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 15:14:22.673  1032  1543 D ConnectivityService: currentScore = 0, newScore = 20
09-13 15:14:22.673  1032  1543 D ConnectivityService:    accepting network in place of null
09-13 15:14:22.673  1032  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:22.673  1032  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:22.673  1032  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:22.674  1032  8246 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:22.674  1032  8246 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 15:14:22.674  1032  8246 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:14:22.674  1032  8246 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 15:14:22.675  1877  1877 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:22.675   314  8251 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 15:14:22.676  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 15:14:22.676  1032  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 15:14:22.676  1032  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-13 15:14:22.677  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 15:14:22.677  1032  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 15:14:22.677  1032  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 15:14:22.678  1032  1032 D LocSvc_java: Sending msg: ,4 arg1:1 arg2:1
09-13 15:14:22.678  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 15:14:22.678  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 15:14:22.678  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 15:14:22.678  1032  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 15:14:22.679  1032  1543 D ConnectivityService: validation of new default Network = false
09-13 15:14:22.679  1032  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 15:14:22.679  1032  1543 D DSQN    : enableDataServiceNotify 
09-13 15:14:22.679  1032  1543 D DSQN    : start dsqn bin
,09-13 15:14:22.687  1032  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 15:14:22.687  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:22.687  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:22.687  1032  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 15:14:22.688  1032  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:22.688  1579  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 15:14:22.686  8252  8252 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:22.686  8252  8252 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:22.700  8252  8252 E DSQN    : DSQN ssw
,09-13 15:14:22.705  1579  1579 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 15:14:22.706  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.707  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.727   314  8251 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-13 15:14:22.763   314  8251 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 15:14:22.791   314   890 D LGDataListener: argv[0]=dsqncommand
09-13 15:14:22.791   314   890 D LGDataListener: argv[1]=wlan0
09-13 15:14:22.791   314   890 D LGDataListener: argv[2]=1
09-13 15:14:22.791   314   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 15:14:22.792  1032  1092 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 15:14:22.792  1032  1092 D DSQN    : start to monitor internet connection
,09-13 15:14:22.807  1032  8247 D DhcpStateMachine: DHCPV4 request on wlan0
,09-13 15:14:22.809  1032  8247 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 15:14:22.809  1032  8247 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-13 15:14:22.818  1032  8246 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 13:14:22 GMT], X-Android-Received-Millis=[1473772462817], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473772462790]}
09-13 15:14:22.806  8258  8258 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:22.818  1032  8246 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 15:14:22.819  1032  8246 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 15:14:22.806  8258  8258 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6503 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 15:14:22.820  1032  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 15:14:22.820  1032  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 15:14:22.821  1032  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:22.821  1032  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:22.821  1032  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 15:14:22.821  1032  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 15:14:22.821  1032  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 15:14:22.822  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:22.822  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 15:14:22.823  1032  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:22.824  1579  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 15:14:22.824  1032  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:22.824  8258  8258 I dhcpcd  : version 5.5.6 starting
09-13 15:14:22.824  1032  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 15:14:22.825  1032  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:22.825  8258  8258 E dhcpcd  : get_duid: m
09-13 15:14:22.825  8258  8258 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 15:14:22.825  8258  8258 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 15:14:22.825  1032  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:14:22.826  1877  1877 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:22.826  1877  1877 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 15:14:22.862  8223  8223 W ExternalStrings: load override strings
09-13 15:14:22.862  8223  8223 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 15:14:22.862  8223  8223 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-13 15:14:22.864  8223  8223 D StatusProvider: onCreate
09-13 15:14:22.869  1579  1579 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 15:14:22.870  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.870  1579  1579 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 15:14:22.904  8258  8258 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 15:14:22.904  8258  8258 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 15:14:22.904  8258  8258 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 15:14:22.904  8258  8258 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 15:14:22.905  8258  8258 D dhcpcd  : wlan0: sending REQUEST (xid 0x358763b), next in 3.87 seconds
,09-13 15:14:22.921  8223  8223 V Signer  : override build config not found
09-13 15:14:22.921  8223  8223 D Signer  : value of property debug is false
,09-13 15:14:22.950  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,09-13 15:14:22.950  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,09-13 15:14:22.951  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-13 15:14:22.951  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,09-13 15:14:22.951  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-13 15:14:22.951  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,09-13 15:14:22.951  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-13 15:14:22.952  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,09-13 15:14:22.952  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-13 15:14:22.952  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,09-13 15:14:22.952  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
,09-13 15:14:22.952  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,09-13 15:14:22.952  8223  8223 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.,
,09-13 15:14:22.960  8258  8258 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 15:14:22.962  8223  8223 V LGMDMManager: Create singleton instance
09-13 15:14:22.985  6853  6932 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 907)
09-13 15:14:22.985  6853  6932 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 907)
,09-13 15:14:22.996  6853  6932 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 912)
,09-13 15:14:22.997  8258  8258 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 15:14:22.997  8258  8258 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 15:14:22.998  6853  6932 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 15:14:22.998  8258  8258 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 15:14:22.998  6853  6932 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 913)
09-13 15:14:22.998  8258  8258 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 15:14:22.999  8258  8258 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-13 15:14:22.999  8258  8258 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 15:14:23.000  8258  8258 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 15:14:23.000  8258  8258 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-13 15:14:23.000  8223  8223 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-13 15:14:23.011  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.011  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2e3d2c added. We now have 2 listener(s)
09-13 15:14:23.012  1032  1598 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.021  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:14:23.021  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.021  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.022  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.022  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155ba3f5 added. We now have 9 listener(s)
09-13 15:14:23.022  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:23.023  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:14:23.026  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:14:23.027  7862  7966 D UEI.SmartControl: Internal timer expired: 3
09-13 15:14:23.028  7862  7966 D UEI.SmartControl: unbind internal service
09-13 15:14:23.032  7862  7862 D UEI.SmartControl: Service.onUnbind: IControl
09-13 15:14:23.033  7862  7862 D UEI.SmartControl: Service.onDestroy
09-13 15:14:23.033  7862  7862 D UEI.SmartControl: Lock is in USE false
09-13 15:14:23.033  7862  7862 D UEI.SmartControl: unbind internal service
09-13 15:14:23.033  7862  7862 D serial_port: close(fd = 24)
09-13 15:14:23.035  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:23.035  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:23.035  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:23.035  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:23.035  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:23.035  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.035  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:23.035  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:23.036  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.036  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:14:23.036  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.036  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@221db7fb added. We now have 3 listener(s)
09-13 15:14:23.037  1032  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.039  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:14:23.043  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:23.043  7862  7862 I UEI.SmartControl: Serial port is closed.
09-13 15:14:23.043  7862  7862 I UEI.SmartControl: Serial port is closed.
,09-13 15:14:23.043  7862  7862 D UEI.SmartControl: Blaster closed
,09-13 15:14:23.043  7862  7862 D UEI.SmartControl: Shut down QS...
09-13 15:14:23.043  7862  7862 D UEI.SmartControl: Stopping QS lib
09-13 15:14:23.043  7862  7862 D UEI.SmartControl: QS lib stop result = true
09-13 15:14:23.044  7862  7862 D UEI.SmartControl: Stopped QS lib
09-13 15:14:23.044  7862  7862 D UEI.SmartControl: QS shutdown complete
09-13 15:14:23.046  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:14:23.046  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.046  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.047  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.047  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bd80018 added. We now have 10 listener(s)
09-13 15:14:23.047  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:23.048  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:23.048  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:23.048  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:23.048  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.048  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.048  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:23.048  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.048  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2e3d2c removed from the list
09-13 15:14:23.048  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.048  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155ba3f5 removed from the list
09-13 15:14:23.048  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:23.048  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.049  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.049  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.049  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:23.049  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.049  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.049  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155ba3f5 not in the list
09-13 15:14:23.04,9  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.049  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.050  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.050  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:23.050  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.050  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bd80018 removed from the list
09-13 15:14:23.050  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.050  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.050  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.050  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.050  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@221db7fb removed from the list
09-13 15:14:23.051  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.051  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@158f8a71 added. We now have 2 listener(s)
09-13 15:14:23.051  1032  2070 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.054  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:14:23.054  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.054  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.054  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.054  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eb29056 added. We now have 9 listener(s)
09-13 15:14:23.054  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:14:23.055  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:14:23.057  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:14:23.061  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:23.061  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:23.061  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:23.061  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:23.061  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:23.061  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.061  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:23.061  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:23.063  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.063  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:14:23.064  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.064  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285905c4 added. We now have 3 listener(s)
09-13 15:14:23.065  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:23.065  1032  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.066  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:23.069  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:14:23.069  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.069  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.069  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.069  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7415cad added. We now have 10 listener(s)
09-13 15:14:23.069  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:23.069  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:14:23.069  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:14:23.069  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:14:23.069  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:23.069  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:14:23.071  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 15:14:23.072  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 fore,groundUser=0
,09-13 15:14:23.079  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 15:14:23.080  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 15:14:23.081  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:14:23.082  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:23.083  6853  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 15:14:23.083  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:23.084  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:23.085  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:23.085  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:23.085  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:23.085  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.085  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.085  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:23.085  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.085  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@158f8a71 removed from the list
09-13 15:14:23.085  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.085  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eb29056 removed from the list
09-13 15:14:23.085  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:23.085  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.086  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:14:23.086  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.088  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:23.088  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.088  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.088  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eb29056 not in the list
09-13 15:14:23.088  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.088  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.089  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.090  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:23.090  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:23.090  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:23.090  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.090  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7415cad removed from the list
09-13 15:14:23.090  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.090  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.090  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.090  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.090  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285905c4 removed from the list
09-13 15:14:23.091  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.091  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c2ba30 added. We now have 2 listener(s)
09-13 15:14:23.091  1032  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.093  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:23.094  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:14:23.094  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.094  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.094  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.094  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c416a9 added. We now have 9 listener(s)
09-13 15:14:23.094  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: ,New listener added - the number of listeners is now 1
09-13 15:14:23.094  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:14:23.096  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:23.100  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 15:14:23.100  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:23.100  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:23.100  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:23.100  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:23.100  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:23.100  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.100  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:23.100  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:14:23.102  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.102  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:14:23.102  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 15:14:23.102  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.102  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dd0bcf added. We now have 3 listener(s)
09-13 15:14:23.103  1032  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.104  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:23.105  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:23.106  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:14:23.106  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.106  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.106  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.106  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d1495c added. We now have 10 listener(s)
09-13 15:14:23.106  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:23.106  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:14:23.107  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:14:23.107  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:14:23.107  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:14:23.107  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:14:23.107  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:14:23.110  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:23.112  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 15:14:23.112  1032  1598 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.117  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 15:14:23.117  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 15:14:23.119  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:14:23.119  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:23.120  6853  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 15:14:23.120  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:23.120  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:23.120  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:23.120  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.120  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.121  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:23.121  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.121  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c2ba30 removed from the list
,09-13 15:14:23.121  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.121  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c416a9 removed from the list
09-13 15:14:23.121  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:23.121  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.121  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.121  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.125  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:23.125  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.125  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.125  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c416a9 not in the list
09-13 15:14:23.125  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.126  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:14:23.127  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.128  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:23.128  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:23.128  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:23.128  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.128  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d1495c removed from the list
09-13 15:14:23.128  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.128  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.128  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.128  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.128  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dd0bcf removed from the list
09-13 15:14:23.129  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.129  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c895eb added. We now have 2 listener(s)
09-13 15:14:23.155  1032  1982 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8288 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-13 15:14:23.156  1032  1982 I ActivityManager: Killing 7310:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-13 15:14:23.216  1032  8247 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-13 15:14:23.217  1032  8247 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 15:14:23.217  1032  8247 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 15:14:23.217  1032  8247 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 15:14:23.217  1032  8247 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 15:14:23.217  1032  8247 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 15:14:23.217  1032  8247 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 15:14:23.217  1032  8247 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 15:14:23.218  1032  8247 D DhcpStateMachine: RunningState
09-13 15:14:23.224  8223  8276 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-13 15:14:23.403  1032  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 15:14:23.404  1032  2349 W libprocessgroup: failed to open /acct/uid_10093/pid_7310/cgroup.procs: No such file or directory
09-13 15:14:23.413  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:14:23.414  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.414  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.414  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.414  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d79f48 added. We now have 9 listener(s)
09-13 15:14:23.414  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:23.417  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:14:23.427  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:23.436  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:23.436  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:23.436  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:23.436  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:23.436  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:23.436  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.436  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:23.436  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:14:23.440  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.441  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:14:23.443  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.443  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eadbb06 added. We now have 3 listener(s)
09-13 15:14:23.443  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.445  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:23.448  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:23.451  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-13 15:14:23.451  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.451  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.452  8288  8288 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 15:14:23.452  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.452  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b98a5c7 added. We now have 10 listener(s)
09-13 15:14:23.452  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:23.452  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:14:23.452  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:14:23.452  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:14:23.452  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:23.452  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 15:14:23.463  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 15:14:23.463  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.469  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 15:14:23.470  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 15:14:23.472  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:14:23.472  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:14:23.474  6853  6932 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 15:14:23.476  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:23.476  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:23.476  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:23.477  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.477  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.477  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:23.477  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.477  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c895eb removed from the list
09-13 15:14:23.477  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.477  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d79f48 removed from the list
09-13 15:14:23.477  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:23.477  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.478  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.478  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.479  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:23.479  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.479  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.479  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d79f48 not in the list
09-13 15:14:23.479  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.479  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.480  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.481  6853  6932 D BluetoothLeScanner: could not find callback wrapper
09-13 15:14:23.481  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:14:23.481  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:23.481  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.481  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b98a5c7 removed from the list
09-13 15:14:23.481  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.481  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-,13 15:14:23.481  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.481  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.481  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eadbb06 removed from the list
09-13 15:14:23.482  8288  8288 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-13 15:14:23.482  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.482  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25da8192 added. We now have 2 listener(s)
09-13 15:14:23.482  1032  1948 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.485  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 15:14:23.485  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.485  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.485  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.485  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6fd763 added. We now have 9 listener(s)
09-13 15:14:23.485  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:23.486  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:14:23.490  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:14:23.493  6853  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:14:23.493  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:14:23.493  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 15:14:23.493  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:14:23.493  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:14:23.493  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.493  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:14:23.493  6853  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:14:23.495  6853  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:14:23.495  6853  6932 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:14:23.495  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:14:23.495  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25f2fc19 added. We now have 3 listener(s)
09-13 15:14:23.495  1032  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 15:14:23.498  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:23.499  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-13 15:14:23.499  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:14:23.499  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:14:23.499  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:14:23.499  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59b24de added. We now have 10 listener(s)
09-13 15:14:23.499  6853  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:14:23.499  6853  6932 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:14:23.500  6853  6932 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:14:23.500  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:23.500  6853  6932 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:14:23.500  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.500  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.500  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:14:23.500  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.500  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25da8192 removed from the list
09-13 15:14:23.500  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.500  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6fd763 removed from the list
09-13 15:14:23.500  6853  6932 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:14:23.500  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.501  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.501  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.502  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:14:23.502  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.502  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.502  6853  6932 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6fd763 not in the list
09-13 15:14:23.502  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.502  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.503  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:14:23.503  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManag,er: stopAdvertising
09-13 15:14:23.503  6853  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:14:23.503  6853  6932 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59b24de removed from the list
09-13 15:14:23.503  6853  6932 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:14:23.503  6853  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:14:23.503  6853  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:14:23.503  6853  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:14:23.503  6853  6932 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25f2fc19 removed from the list
09-13 15:14:23.504  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 15:14:23.505  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 15:14:23.505  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 15:14:23.505  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:14:23.505  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 15:14:23.505  6853  6932 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 15:14:23.516  6853  8313 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 920, name: My test thread name)
09-13 15:14:23.516  6853  8313 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 920, thread name: My test thread name)
09-13 15:14:23.516  6853  8313 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 920, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 15:14:23.520  6853  8314 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 922, name: My test thread name)
09-13 15:14:23.521  6853  8314 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 922, thread name: My test thread name)
09-13 15:14:23.521  6853  8314 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 922, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-13 15:14:23.522  8288  8288 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-13 15:14:23.522  8288  8288 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 15:14:23.522  8288  8288 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 15:14:23.523  8288  8288 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 15:14:23.523  6853  6932 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-13 15:14:23.523  6853  6932 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-13 15:14:23.523  6853  6932 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-13 15:14:23.523  6853  6932 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-13 15:14:23.523  6853  6932 D com.test.thalitest.ThaliTestRunner: Total duration: 23362 ms
09-13 15:14:23.523  8288  8288 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 15:14:23.525  6853  6932 I jxcore-log: *Native tests were executed*
09-13 15:14:23.525  6853  6932 I jxcore-log: 
09-13 15:14:23.525  6853  6932 I jxcore-log: Total number of executed tests:  80
09-13 15:14:23.525  6853  6932 I jxcore-log: 
09-13 15:14:23.525  6853  6932 I jxcore-log: Number of passed tests:  80
09-13 15:14:23.525  6853  6932 I jxcore-log: 
09-13 15:14:23.525  8288  8288 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 15:14:23.525  6853  6932 I jxcore-log: Number of failed tests:  0
09-13 15:14:23.525  6853  6932 I jxcore-log: 
09-13 15:14:23.526  6853  6932 I jxcore-log: Number of ignored tests:  0
09-13 15:14:23.526  6853  6932 I jxcore-log: 
09-13 15:14:23.526  6853  6932 I jxcore-log: Total duration:  23362
09-13 15:14:23.526  6853  6932 I jxcore-log: 
09-13 15:14:23.526  6853  6932 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 15:14:23.526  6853  6932 I jxcore-log: 
09-13 15:14:23.530  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.530  6853  6932 I jxcore-log: 
,09-13 15:14:23.532  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.532  6853  6932 I jxcore-log: 
09-13 15:14:23.533  8288  8288 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-13 15:14:23.534  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.534  6853  6932 I jxcore-log: 
09-13 15:14:23.535  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.535  6853  6932 I jxcore-log: 
09-13 15:14:23.536  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.536  6853  6932 I jxcore-log: 
,09-13 15:14:23.538  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.538  6853  6932 I jxcore-log: 
09-13 15:14:23.540  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.540  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:14:23.540  6853  6932 I jxcore-log: 
09-13 15:14:23.541  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:23.542  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:14:23.542  6853  6932 I jxcore-log: 
09-13 15:14:23.543  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.543  6853  6932 I jxcore-log: 
09-13 15:14:23.544  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.544  6853  6932 I jxcore-log: 
09-13 15:14:23.545  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 15:14:23.545  6853  6932 I jxcore-log: 
09-13 15:14:23.546  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:14:23.546  6853  6932 I jxcore-log: 
09-13 15:14:23.546  6853  6853 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 15:14:23.547  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:14:23.547  6853  6932 I jxcore-log: 
09-13 15:14:23.548  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.548  6853  6932 I jxcore-log: 
09-13 15:14:23.548  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.548  6853  6932 I jxcore-log: 
09-13 15:14:23.549  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.549  6853  6932 I jxcore-log: 
09-13 15:14:23.550  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.550  6853  6932 I jxcore-log: 
09-13 15:14:23.550  8288  8288 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 15:14:23.550  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.550  6853  6932 I jxcore-log: 
09-13 15:14:23.551  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.551  6853  6932 I jxcore-log: 
09-13 15:14:23.551  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.551  6853  6932 I jxcore-log: 
09-13 15:14:23.552  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'androi,d.net.wifi.STATE_CHANGE'.
09-13 15:14:23.552  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:14:23.552  6853  6932 I jxcore-log: 
09-13 15:14:23.552  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 15:14:23.553  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:14:23.553  6853  6932 I jxcore-log: 
09-13 15:14:23.553  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:14:23.553  6853  6932 I jxcore-log: 
09-13 15:14:23.554  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.554  6853  6932 I jxcore-log: 
09-13 15:14:23.554  8288  8288 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-13 15:14:23.554  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.554  6853  6932 I jxcore-log: 
09-13 15:14:23.555  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.555  6853  6932 I jxcore-log: 
09-13 15:14:23.556  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.556  6853  6932 I jxcore-log: 
09-13 15:14:23.556  6853  6932 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:14:23.556  6853  6932 I jxcore-log: 
09-13 15:14:23.556  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 15:14:23.559  8288  8288 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-13 15:14:23.561  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:23.566  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.566  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:23.566  8223  8276 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:23.567  8223  8276 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 15:14:23.567  8288  8288 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 15:14:23.569  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-13 15:14:23.573  6971  6971 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 15:14:23.575  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:23.576  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-13 15:14:23.581  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:23.588  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:23.593  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.593  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 15:14:23.594  8288  8288 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 15:14:23.595  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 15:14:23.596  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 15:14:23.596  6971  6971 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 15:14:23.596  6971  6971 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 15:14:23.596  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 15:14:23.597  6971  6971 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 15:14:23.597  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 15:14:23.597  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 15:14:23.597  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 15:14:23.597  6971  6971 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 15:14:23.597  6971  6971 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 15:14:23.598  6971  6971 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 15:14:23.600  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:23.600  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 15:14:23.605  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:23.609  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:23.614  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.614  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:23.614  8288  8288 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 15:14:23.616  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:23.616  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 15:14:23.626  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:23.636  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:23.641  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.641  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:23.642  8288  8288 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 15:14:23.644  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:23.644  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 15:14:23.648  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 15:14:23.653  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:23.658  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.658  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:23.659  8288  8288 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 15:14:23.662  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:23.662  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 15:14:23.667  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 15:14:23.672  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 15:14:23.677  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.678  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:23.678  8288  8288 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 15:14:23.685  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 15:14:23.685  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 15:14:23.689  8223  8276 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-13 15:14:23.710  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:23.718  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:23.725  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.725  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 15:14:23.728  8223  8276 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-13 15:14:23.733  8223  8276 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-13 15:14:23.734  8223  8276 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-13 15:14:23.734  8223  8276 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-13 15:14:23.734  8223  8276 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-13 15:14:23.735  8223  8276 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-13 15:14:23.735  8288  8288 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 15:14:23.738  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 15:14:23.738  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 15:14:23.741  8223  8276 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-13 15:14:23.744  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 15:14:23.744  8223  8276 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-13 15:14:23.750  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 15:14:23.756  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.757  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:23.758  8288  8288 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 15:14:23.761  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:23.761  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-13 15:14:23.765  8175  8175 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 15:14:23.768  8175  8175 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 15:14:23.771  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 15:14:23.776  8319  8319 D AndroidRuntime: 
09-13 15:14:23.776  8319  8319 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 15:14:23.776  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:23.778  8319  8319 D AndroidRuntime: CheckJNI is OFF
09-13 15:14:23.782  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.783  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:23.784  8288  8288 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 15:14:23.785  8288  8288 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 15:14:23.785  8288  8288 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 15:14:23.789  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:23.789  8223  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-13 15:14:23.791  8175  8175 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 15:14:23.791  8175  8175 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 15:14:23.793  6971  6971 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 15:14:23.800  6971  6971 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 15:14:23.805  8288  8288 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 15:14:23.805  8288  8288 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 15:14:23.806  8288  8288 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 15:14:23.806  8288  8288 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 15:14:23.807  8288  8288 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 15:14:23.809  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,09-13 15:14:23.814  8288  8288 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 15:14:23.815  8288  8288 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-13 15:14:23.815  8288  8288 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-13 15:14:23.850  8288  8288 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:23.850  8288  8288 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 15:14:23.856  8288  8288 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 15:14:23.857  8288  8288 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 15:14:23.857  8288  8288 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-13 15:14:23.857  8288  8288 V SoundPool: doLoad: loading sample sampleID=1
09-13 15:14:23.857  8288  8338 V SoundPool: Start decode
09-13 15:14:23.857  8288  8288 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 15:14:23.857  8288  8338 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-13 15:14:23.858   318  1384 V MediaPlayerService: decode(22, 10857164, 17813)
09-13 15:14:23.858   318  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-13 15:14:23.858   318  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 15:14:23.858   318  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 15:14:23.858   318  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 15:14:23.858   318  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-13 15:14:23.859   318  1384 V MediaPlayerService: player type = 3
09-13 15:14:23.859   318  1384 V AwesomePlayer: AwesomePlayer create()
09-13 15:14:23.859   318  1384 V AwesomePlayer: reset_l() 
09-13 15:14:23.859   318  1384 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:23.860   318  1384 V AwesomePlayer: setAudioSink() 
09-13 15:14:23.860   318  1384 V AwesomePlayer: reset_l() 
09-13 15:14:23.860   318  1384 V AudioCache: notify(0xb1432400, 8, 0, 0)
09-13 15:14:23.860   318  1384 V AudioCache: ignored
09-13 15:14:23.860   318  1384 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:23.860  8288  8288 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 15:14:23.860   318  1384 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 15:14:23.860   318  1384 V AwesomePlayer: setDataSource_l dataSource
09-13 15:14:23.860   318  1384 V LGParserOSAL: SniffLGParser start
09-13 15:14:23.860   318  1384 V LGParserOSAL: MainType:5, SubType=0
09-13 15:14:23.860   318  1384 V LGParserOSAL: #### check Mime : application/ogg
09-13 15:14:23.860   318  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 15:14:23.860   318  1384 E MediaExtractor: Use LGExtractor :application/ogg 
09-13 15:14:23.861  7862  7862 D UEI.SmartControl: QS Service created
09-13 15:14:23.867  8288  8288 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 15:14:23.868  8288  8288 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-13 15:14:23.874  7862  7862 I UEI.SmartControl: Service initServices...
09-13 15:14:23.874  7862  7862 D UEI.SmartControl: QS start get config
09-13 15:14:23.879  8319  8319 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-13 15:14:23.883  8288  8288 V LGMDMManager: Create singleton instance
,09-13 15:14:23.897  1032  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-13 15:14:23.898  1032  1090 I ActivityManager: Killing 6853:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-13 15:14:23.922  8288  8288 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-13 15:14:23.929   318  1384 V LGParserOSAL: supported mime: application/ogg
09-13 15:14:23.929   318  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 15:14:23.929   318  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 15:14:23.929   318  1384 V AwesomePlayer: mBitrate = -1 bits/sec
09-13 15:14:23.929   318  1384 V AwesomePlayer: AudioTrack Setting
09-13 15:14:23.929   318  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 15:14:23.929   318  1384 V AwesomePlayer: setAudioSource() 
09-13 15:14:23.929   318  1384 V MediaPlayerService: prepare
09-13 15:14:23.929   318  1384 V AwesomePlayer: prepareAsync_l() 
09-13 15:14:23.929   318  1384 V MediaPlayerService: wait for prepare
09-13 15:14:23.929   318  8341 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 15:14:23.929   318  8341 V AwesomePlayer: initAudioDecoder() 
09-13 15:14:23.929   318  8341 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 15:14:23.929   318  8341 V AudioSystem: isOffloadSupported()
09-13 15:14:23.929   318  8341 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 15:14:23.929   318  8341 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 15:14:23.929   318  8341 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 15:14:23.929   318  8341 V AwesomePlayer: getUseOffload() = 0 
09-13 15:14:23.929   318  8341 V OMXCodec: OMXCodec::Create
09-13 15:14:23.929   318  8341 V OMXCodec: findMatchingCodecs()
09-13 15:14:23.929   318  8341 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 15:14:23.929   318  8341 V OMXCodec: matchingCodecs.size()=1
09-13 15:14:23.930   318  8341 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 15:14:23.931   318  8341 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 15:14:23.931   318  8341 V LGCodecAdapter: LG Codec Adapter start
09-13 15:14:23.931   318  8341 V OMXCodec: OMXCodec Createtor
09-13 15:14:23.931   318  8341 V OMXCodec: setComponentRole
09-13 15:14:23.931   318  8341 V OMXCodec: configureCodec protected=0
09-13 15:14:23.931   318  8341 V LGCodecAdapter: called getLGCodecSpecificData
09-13 15:14:23.931   318  8341 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 15:14:23.931   318  8341 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 15:14:23.931   318  8341 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 15:14:23.931   318  8341 V LGCodecOSAL: Not support LGCodec
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 15:14:23.931   318  8341 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 15:14:23.931   318  8341 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 15:14:23.931   318  8341 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 15:14:23.931   318  8341 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 15:14:23.931   318  8341 V AudioSystem: isOffloadSupported()
09-13 15:14:23.931   318  8341 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 15:14:23.931   318  8341 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 15:14:23.931   318  8341 V OMXCodec: init()
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
09-13 15:14:23.931   318  8341 V OMXCodec: allocateBuffers
09-13 15:14:23.931   318  8341 V OMXCodec: allocateBuffersOnPort portIndex=0
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
09-13 15:14:23.931   318  8341 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
09-13 15:14:23.931   318  8341 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
09-13 15:14:23.932   318  8341 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 15:14:23.932   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 15:14:23.932   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 15:14:23.932   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 15:14:23.932   318  8341 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 15:14:23.932   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 15:14:23.932   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 15:14:23.932   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 15:14:23.932   318  8341 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 15:14:23.932   318  8341 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 15:14:23.932   318  8341 V AudioCache: notify(0xb1432400, 5, 0, 0)
09-13 15:14:23.932   318  8341 V AudioCache: ignored
09-13 15:14:23.932   318  8341 V AudioCache: notify(0xb1432400, 1, 0, 0)
09-13 15:14:23.932   318  8341 V AudioCache: prepared
09-13 15:14:23.932   318  1384 V AudioCache: wait - success
09-13 15:14:23.932   318  1384 V MediaPlayerService: start
09-13 15:14:23.932   318  1384 V AwesomePlayer: play_l() 
09-13 15:14:23.932   318  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 15:14:23.933   318  1384 V AwesomePlayer: createAudioPlayer_l
09-13 15:14:23.933   318  1384 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 15:14:23.933   318  1384 V AwesomePlayer: startAudioPlayer_l() 
,09-13 15:14:23.933   318  1384 D AudioPlayer: start of Playback, useOffload 0
09-13 15:14:23.933   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 15:14:23.933   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 15:14:23.935   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 15:14:23.935   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 15:14:23.935   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 15:14:23.935   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 15:14:23.935   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 15:14:23.935   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
,09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 15:14:23.936   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 15:14:23.937   318  8343 V OMXCodec: allocateBuffersOnPort portIndex=1
,09-13 15:14:23.937   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 15:14:23.937   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
09-13 15:14:23.937   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
09-13 15:14:23.937   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
09-13 15:14:23.937   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fe20 on output port
09-13 15:14:23.937   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 15:14:23.937   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 15:14:23.938   318  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
,09-13 15:14:23.940   318  1384 V AudioCache: notify(0xb1432400, 6, 0, 0)
09-13 15:14:23.940   318  1384 V AudioCache: ignored
09-13 15:14:23.940   318  1384 V MediaPlayerService: wait for playback complete
09-13 15:14:23.941   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.941   318  8344 V AudioCache: memcpy(0xac200000, 0xb57c8000, 4096)
09-13 15:14:23.944   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.944   318  8344 V AudioCache: memcpy(0xac201000, 0xb57c8000, 4096)
09-13 15:14:23.945   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.945   318  8344 V AudioCache: memcpy(0xac202000, 0xb57c8000, 4096)
09-13 15:14:23.945   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.946   318  8344 V AudioCache: memcpy(0xac203000, 0xb57c8000, 4096)
09-13 15:14:23.946   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.946   318  8344 V AudioCache: memcpy(0xac204000, 0xb57c8000, 4096)
09-13 15:14:23.947   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.947   318  8344 V AudioCache: memcpy(0xac205000, 0xb57c8000, 4096)
09-13 15:14:23.948   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.948   318  8344 V AudioCache: memcpy(0xac206000, 0xb57c8000, 4096)
09-13 15:14:23.948  1032  2350 I WindowState: WIN DEATH: Window{10f73be5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 15:14:23.948  1032  1542 D WifiService: Client connection lost with reason: 4
09-13 15:14:23.949   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.949   318  8344 V AudioCache: memcpy(0xac207000, 0xb57c8000, 4096)
09-13 15:14:23.949   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.949   318  8344 V AudioCache: memcpy(0xac208000, 0xb57c8000, 4096)
09-13 15:14:23.950   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.950   318  8344 V AudioCache: memcpy(0xac209000, 0xb57c8000, 4096)
09-13 15:14:23.953   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.953   318  8344 V AudioCache: memcpy(0xac20a000, 0xb57c8000, 4096)
,09-13 15:14:23.954   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.954   318  8344 V AudioCache: memcpy(0xac20b000, 0xb57c8000, 4096)
09-13 15:14:23.955  1032  2350 D InputDispatcher: Window went away: Window{10f73be5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 15:14:23.955   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.955   318  8344 V AudioCache: memcpy(0xac20c000, 0xb57c8000, 4096)
09-13 15:14:23.956   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.956   318  8344 V AudioCache: memcpy(0xac20d000, 0xb57c8000, 4096)
09-13 15:14:23.956   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.956   318  8344 V AudioCache: memcpy(0xac20e000, 0xb57c8000, 4096)
09-13 15:14:23.957   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.957   318  8344 V AudioCache: memcpy(0xac20f000, 0xb57c8000, 4096)
09-13 15:14:23.957   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.957   318  8344 V AudioCache: memcpy(0xac210000, 0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: memcpy(0xac211000, 0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: memcpy(0xac212000, 0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: memcpy(0xac213000, 0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: memcpy(0xac214000, 0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.958   318  8344 V AudioCache: memcpy(0xac215000, 0xb57c8000, 4096)
09-13 15:14:23.959   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.959   318  8344 V AudioCache: memcpy(0xac216000, 0xb57c8000, 4096)
09-13 15:14:23.959   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.959   318  8344 V AudioCache: memcpy(0xac217000, 0xb57c8000, 4096)
09-13 15:14:23.959   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.959   318  8344 V AudioCache: memcpy(0xac218000, 0xb57c8000, 4096)
09-13 15:14:23.960   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.960   318  8344 V AudioCache: memcpy(0xac219000, 0xb57c8000, 4096)
09-13 15:14:23.966   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.967   318  8344 V AudioCache: memcpy(0xac21a000, 0xb57c8000, 4096)
09-13 15:14:23.967   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.967   318  8344 V AudioCache: memcpy(0xac21b000, 0xb57c8000, 4096)
,09-13 15:14:23.969   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.969   318  8344 V AudioCache: memcpy(0xac21c000, 0xb57c8000, 4096)
09-13 15:14:23.970   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.970   318  8344 V AudioCache: memcpy(0xac21d000, 0xb57c8000, 4096)
09-13 15:14:23.970   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.970   318  8344 V AudioCache: memcpy(0xac21e000, 0xb57c8000, 4096)
09-13 15:14:23.971   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.971   318  8344 V AudioCache: memcpy(0xac21f000, 0xb57c8000, 4096)
09-13 15:14:23.971   318  8344 V AudioCache: write(0xb57c8000, 4096)
,09-13 15:14:23.971   318  8344 V AudioCache: memcpy(0xac220000, 0xb57c8000, 4096)
09-13 15:14:23.971   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.971   318  8344 V AudioCache: memcpy(0xac221000, 0xb57c8000, 4096)
09-13 15:14:23.972   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.972   318  8344 V AudioCache: memcpy(0xac222000, 0xb57c8000, 4096)
09-13 15:14:23.972   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.972   318  8344 V AudioCache: memcpy(0xac223000, 0xb57c8000, 4096)
09-13 15:14:23.973   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.973   318  8344 V AudioCache: memcpy(0xac224000, 0xb57c8000, 4096)
09-13 15:14:23.973   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.973   318  8344 V AudioCache: memcpy(0xac225000, 0xb57c8000, 4096)
09-13 15:14:23.974   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.974   318  8344 V AudioCache: memcpy(0xac226000, 0xb57c8000, 4096)
09-13 15:14:23.974   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.974   318  8344 V AudioCache: memcpy(0xac227000, 0xb57c8000, 4096)
09-13 15:14:23.975   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.975   318  8344 V AudioCache: memcpy(0xac228000, 0xb57c8000, 4096)
09-13 15:14:23.975   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.975   318  8344 V AudioCache: memcpy(0xac229000, 0xb57c8000, 4096)
09-13 15:14:23.976   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.976   318  8344 V AudioCache: memcpy(0xac22a000, 0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: memcpy(0xac22b000, 0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: memcpy(0xac22c000, 0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: memcpy(0xac22d000, 0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: memcpy(0xac22e000, 0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.984   318  8344 V AudioCache: memcpy(0xac22f000, 0xb57c8000, 4096)
09-13 15:14:23.985   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.985   318  8344 V AudioCache: memcpy(0xac230000, 0xb57c8000, 4096)
09-13 15:14:23.985   318  8344 V AudioCache: write(0xb57c8000, 4096)
09-13 15:14:23.985   318  8344 V AudioCache: memcpy(0xac231000, 0xb57c8000, 4096)
09-13 15:14:23.985   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-13 15:14:23.985   318  8344 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 15:14:23.985   318  8344 V AwesomePlayer: postAudioEOS() 
09-13 15:14:23.985   318  8344 V AudioCache: write(0xb57c8000, 280)
09-13 15:14:23.985   318  8344 V AudioCache: memcpy(0xac232000, 0xb57c8000, 280)
,09-13 15:14:23.988   318  8341 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 15:14:23.988   318  8341 V AwesomePlayer: onStreamDone
09-13 15:14:23.988   318  8341 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 15:14:23.988   318  8341 V AudioCache: notify(0xb1432400, 2, 0, 0)
09-13 15:14:23.988   318  8341 V AudioCache: playback complete
09-13 15:14:23.988   318  8341 V AwesomePlayer: pause_l() 
09-13 15:14:23.988   318  8341 V AudioCache: notify(0xb1432400, 7, 0, 0)
09-13 15:14:23.988   318  1384 V AudioCache: wait - success
09-13 15:14:23.988   318  8341 V AudioCache: ignored
09-13 15:14:23.988   318  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 15:14:23.988   318  8341 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:23.988   318  8341 D AudioPlayer: Pause Playback at 1068125
09-13 15:14:23.988   318  1384 V AwesomePlayer: reset_l() 
09-13 15:14:23.988   318  1384 V AudioCache: notify(0xb1432400, 8, 0, 0)
09-13 15:14:23.988   318  1384 V AudioCache: ignored
09-13 15:14:23.989   318  1384 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:23.989   318  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-13 15:14:23.989   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 15:14:23.989   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 15:14:23.989   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 15:14:23.989   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 15:14:23.989  8288  8288 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fe20 on port 1
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 15:14:23.989   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 15:14:23.989   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-13 15:14:23.989   318  8343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 15:14:23.989   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 15:14:23.989   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 15:14:23.989   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-13 15:14:23.990   318  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-13 15:14:23.990   318  1384 D AudioPlayer: AudioPlayer releasing audio source
09-13 15:14:23.990   318  1384 D AudioPlayer: AudioPlayer done releasing audio source
09-13 15:14:23.990   318  1384 V AwesomePlayer: reset_l() 
09-13 15:14:23.990   318  1384 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:23.990   318  1384 V AwesomePlayer: ~AwesomePlayer call
09-13 15:14:23.990   318  1384 V AwesomePlayer: reset_l() 
,09-13 15:14:23.991   318  1384 V AwesomePlayer: cancelPlayerEvents
09-13 15:14:23.991  8288  8338 V SoundPool: close(31)
09-13 15:14:23.991  8288  8338 V SoundPool: pointer = 0x9fe8c000, size = 205080, sampleRate = 48000, numChannels = 2
09-13 15:14:24.181  1032  1090 I ActivityManager:   Force finishing activity ActivityRecord{19353b26 u0 com.test.thalitest/.MainActivity t6}
,09-13 15:14:24.199  7862  7862 I UEI.SmartControl: Supports setup maps: true
09-13 15:14:24.204   335   411 E GBMv2   : DFP En is all cleared set to be enabled
09-13 15:14:24.204  1032  1611 W ActivityManager: Spurious death for ProcessRecord{27e8e9e8 6853:com.test.thalitest/u0a118}, curProc for 6853: null
,09-13 15:14:24.204  1032  1108 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-13 15:14:24.205  1032  1108 I ActivityManager:   Force finishing activity ActivityRecord{19353b26 u0 com.test.thalitest/.MainActivity t6 f}
09-13 15:14:24.205  1032  1108 W ActivityManager: Duplicate finish request for ActivityRecord{19353b26 u0 com.test.thalitest/.MainActivity t6 f}
09-13 15:14:24.214  7862  7862 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 15:14:24.214  7862  7862 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 15:14:24.214  7862  7862 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 15:14:24.214  7862  7862 I UEI.SmartControl: ### init IR Blaster...
,09-13 15:14:24.220  1966  3466 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-13 15:14:24.221  1966  3466 D SplitWindowPolicy: topRunningActivity=ActivityInfo{212907fa co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 15:14:24.222  8288  8288 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3774
09-13 15:14:24.222  1966  1981 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-13 15:14:24.223  1966  1981 D SplitWindowPolicy: topRunningActivity=ActivityInfo{442c1ab co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 15:14:24.226  7862  7862 D serial_port: Configuring serial port
09-13 15:14:24.226  7862  7862 E UEI.SmartControl: UEIBLaster setting for 616
09-13 15:14:24.226  7862  7862 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 15:14:24.226  7862  7862 I UEI.SmartControl: configuring settings for MAXQ616
09-13 15:14:24.226  7862  7862 I UEI.SmartControl: Get version...
09-13 15:14:24.231  2039  2039 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 15:14:24.235  1032  1433 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 15:14:24.235  3750  3750 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-13 15:14:24.238  1579  1579 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-13 15:14:24.239  2481  2589 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 15:14:24.241  2093  2093 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,09-13 15:14:24.242  2093  2093 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 15:14:24.243  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-13 15:14:24.243  2093  2189 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-13 15:14:24.244  7762  7762 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 15:14:24.244  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 15:14:24.247  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.247  1579  1579 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-13 15:14:24.261  4906  4906 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 15:14:24.261  4906  4906 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 15:14:24.261  4906  4906 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 15:14:24.261  4906  4906 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 15:14:24.261  4906  4906 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 15:14:24.261  4906  4906 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 15:14:24.261  4906  4906 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 15:14:24.261  4906  4906 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 15:14:24.261  4906  4906 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:14:24.261  4906  4906 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:14:24.262  4906  4906 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 15:14:24.262  4906  4906 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-13 15:14:24.265  5021  5021 I art     : Explicit concurrent mark sweep GC freed 8206(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 758us total 52.398ms
09-13 15:14:24.271  7862  8345 D UEI.SmartControl: serial port data available: 21
09-13 15:14:24.273  1032  1996 V SIM_STK : Menu title from STK is T-Mobile
,09-13 15:14:24.277  1032  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
09-13 15:14:24.297  7862  7862 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-13 15:14:24.297  7862  7862 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 15:14:24.297  7862  7862 I UEI.SmartControl: QS saving settings...
09-13 15:14:24.298  7862  7862 D UEI.SmartControl: IR Blaster version: 25672567
09-13 15:14:24.300  2093  2093 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-13 15:14:24.302  1929  1929 D ActionManagerService: notifyUserLog: 1000003
09-13 15:14:24.302  3750  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 15:14:24.319  7862  8345 D UEI.SmartControl: serial port data available: 4
09-13 15:14:24.321  2093  2093 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-13 15:14:24.322  2093  2093 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-13 15:14:24.323  2093  2093 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-13 15:14:24.326  1929  1929 D ActionManagerService: notifyUserLog: 1000004
09-13 15:14:24.327  3750  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,09-13 15:14:24.327  2093  2093 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 15:14:24.329  3750  4926 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , expire_time: 0
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , display: false
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , animation: false }
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , expire_time: 0
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , display: false
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , animation: false }
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , expire_time: 0
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , display: false
09-13 15:14:24.332  2093  2093 I GBoardWebViewUtils: , animation: false }
09-13 15:14:24.332  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.336  2093  8348 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-13 15:14:24.348  1579  1579 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 15:14:24.348  1579  1579 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,09-13 15:14:24.355  7862  7862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 15:14:24.357  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.360  7862  7862 E UEI.SmartControl: Services init done
09-13 15:14:24.360  7862  7862 D UEI.SmartControl: QS Service init finished
,09-13 15:14:24.362  7862  8350 I UEI.SmartControl: Device manager: loading config....
09-13 15:14:24.363  7862  8350 D UEI.SmartControl: ----------- loading internal config...
09-13 15:14:24.364  1579  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 15:14:24.364  1579  1650 D KeyguardModel: createShortcutInfo...
09-13 15:14:24.365  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.371  1032  1032 I art     : Explicit concurrent mark sweep GC freed 79645(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.672ms total 152.240ms
,09-13 15:14:24.374  1032  1108 I art     : WaitForGcToComplete blocked for 40.729ms for cause Explicit
09-13 15:14:24.376  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 15:14:24.377  2093  2093 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-13 15:14:24.379  7862  7862 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 15:14:24.379  7862  7862 D UEI.SmartControl: QS Service version code: 201091
09-13 15:14:24.379  7862  7862 D UEI.SmartControl: Service requested: Control
09-13 15:14:24.380  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.383  1579  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 15:14:24.383  1579  1650 D KeyguardModel: createShortcutInfo...
09-13 15:14:24.386  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.387  7862  8350 E UEI.SmartControl: Loading SETTINGS...
09-13 15:14:24.387  1579  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,09-13 15:14:24.387  1579  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:14:24.388  1579  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 15:14:24.388  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.389  1579  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 15:14:24.390  1579  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 15:14:24.390  1579  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 15:14:24.390  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.391  7862  7862 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 15:14:24.394  1579  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 15:14:24.394  1579  1650 D KeyguardModel: createShortcutInfo...
09-13 15:14:24.398  1895  1895 D SplitUIManager: split_name #11 / not available #0
09-13 15:14:24.398  1579  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 15:14:24.398  1579  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 15:14:24.398  1895  1895 D SplitUIService: removed split : 
09-13 15:14:24.401  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.402  1032  1048 V SIM_STK : Menu title from STK is T-Mobile
09-13 15:14:24.402  1032  1048 V SIM_STK : Menu title from STK is T-Mobile
,09-13 15:14:24.408  1579  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 15:14:24.408  1579  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 15:14:24.410  1579  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 15:14:24.410  1579  1650 D KeyguardModel: createShortcutInfo...
09-13 15:14:24.418  1579  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:14:24.418  1579  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 15:14:24.418  1579  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 15:14:24.418  1579  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-13 15:14:24.421  1579  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 15:14:24.422  1579  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 15:14:24.422  1579  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 15:14:24.422  1579  1650 D KeyguardModel: createShortcutInfo...
09-13 15:14:24.423  8288  8288 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 15:14:24.424  7862  7877 I UEI.SmartControl: ------ IControl API: 11
09-13 15:14:24.424  7862  7877 D UEI.SmartControl: File observer start...
09-13 15:14:24.424  7862  7877 E UEI.SmartControl: IR Port is disabled: false
09-13 15:14:24.424  7862  7877 D UEI.SmartControl: Starting file observer...
09-13 15:14:24.425  7862  7877 I UEI.SmartControl: Registering callback...
09-13 15:14:24.425  7862  7878 I UEI.SmartControl: ------ IControl API: 19
09-13 15:14:24.426  7862  7878 I UEI.SmartControl: Registering Services Ready callback...
09-13 15:14:24.428  7862  8350 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 15:14:24.436  1032  1032 D administrator: Handling package changes for user 0
,09-13 15:14:24.438  7862  7862 D UEI.SmartControl: Internal service binding...
09-13 15:14:24.438  1032  1536 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:24.438  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 15:14:24.439  1032  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:24.439  1032  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:24.439  1032  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:24.439  1032  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:24.439  1032  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 15:14:24.440  1032  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-13 15:14:24.440  1032  1543 D ConnectivityService: identical MTU - not setting
09-13 15:14:24.440  1032  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 15:14:24.440  1032  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 15:14:24.440  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:14:24.440  1032  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:24.440  1032  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 15:14:24.441  1579  1810 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-13 15:14:24.452  1032  1574 V SIM_STK : Menu title from STK is T-Mobile
,09-13 15:14:24.456  1032  1982 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 15:14:24.457  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 15:14:24.459  1579  1579 D KeyguardModel: handleShortcutListChanged...
09-13 15:14:24.459  1579  1579 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 15:14:24.459  2093  2093 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-13 15:14:24.463  8223  8223 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 15:14:24.465  7862  8349 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 15:14:24.465  7862  8349 D UEI.SmartControl: -----service ready thread exits
09-13 15:14:24.465  1895  1895 D SplitUIManager: split_name #11 / not available #0
09-13 15:14:24.465  1895  1895 I SplitUIService: split app #11
09-13 15:14:24.466  8288  8304 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 15:14:24.468  1579  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 15:14:24.468  1579  1650 D KeyguardModel: createShortcutInfo...
,09-13 15:14:24.470  1839  1839 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-13 15:14:24.472  1579  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 15:14:24.472  1579  1650 D KeyguardModel: createShortcutInfo...
09-13 15:14:24.473  1579  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 15:14:24.473  1579  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 15:14:24.474  1579  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 15:14:24.474  1579  1650 D KeyguardModel: createShortcutInfo...
09-13 15:14:24.478  2262  2262 I ConfigService: onCreate
09-13 15:14:24.478  2262  2262 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-13 15:14:24.479  1579  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 15:14:24.479  1579  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 15:14:24.480  1839  1839 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-13 15:14:24.480  1579  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 15:14:24.480  1579  1650 D KeyguardModel: createShortcutInfo...
09-13 15:14:24.481  1579  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 15:14:24.481  1579  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 15:14:24.483  1579  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 15:14:24.483  1579  1650 D KeyguardModel: createShortcutInfo...
09-13 15:14:24.483  8288  8336 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 15:14:24.483  8288  8336 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 15:14:24.491  2262  2262 I ConfigService: onBind returning update interface
09-13 15:14:24.492  2262  2262 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 15:14:24.492  2262  2262 I ConfigService: onBind returning config service
,09-13 15:14:24.496  2093  2107 I art     : Background partial concurrent mark sweep GC freed 7021(319KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 14.143ms total 54.425ms
09-13 15:14:24.499  2262  2262 I ConfigService: onDestroy
09-13 15:14:24.507  1579  1579 D KeyguardModel: handleShortcutListChanged...
09-13 15:14:24.507  1579  1579 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-13 15:14:24.512  1839  8355 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-13 15:14:24.515  8288  8288 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 15:14:24.516  8288  8288 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 15:14:24.517  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 15:14:24.518  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 15:14:24.518  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 15:14:24.519  1032  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-13 15:14:24.519  7862  7877 I UEI.SmartControl: ------ IControl API: 8
09-13 15:14:24.520  8288  8288 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 15:14:24.521  8288  8288 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 15:14:24.521  3280  8358 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-13 15:14:24.521   328   405 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-13 15:14:24.535  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-13 15:14:24.539  5823  8361 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-13 15:14:24.540  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 15:14:24.542  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 15:14:24.543  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 15:14:24.544  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 15:14:24.545  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 15:14:24.547  8288  8288 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 15:14:24.548  8288  8288 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 15:14:24.553  1839  8363 I PeopleContactsSync: CP2 sync disabled
,09-13 15:14:24.559  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{145e290a u0 com.lge.launcher2/.Launcher t5} time:205532
,09-13 15:14:24.568  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 15:14:24.568  2093  2271 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,09-13 15:14:24.568  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 15:14:24.568  2093  2271 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 15:14:24.571  1839  5183 I Icing   : doRemovePackageData com.test.thalitest
09-13 15:14:24.572  8288  8288 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 15:14:24.572  8288  8288 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 15:14:24.573  1839  8362 W GmsApplication: Using Auth Proxy for data requests.
09-13 15:14:24.573  8288  8288 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-13 15:14:24.574  8288  8288 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-13 15:14:24.574  7164  7164 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-13 15:14:24.585  1032  2023 I ActivityManager: Killing 7374:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-13 15:14:24.601  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-13 15:14:24.602  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 15:14:24.602  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 15:14:24.612  2093  2093 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,09-13 15:14:24.613  2262  2283 I art     : Explicit concurrent mark sweep GC freed 7148(424KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 777us total 35.835ms
09-13 15:14:24.646  1032  1108 I art     : Explicit concurrent mark sweep GC freed 13666(853KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.698ms total 269.695ms
,09-13 15:14:24.689  2633  2633 D [Concierge]Service: onStartCommand(). Type : 8
09-13 15:14:24.689  2633  2633 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 15:14:24.689  1032  1574 W libprocessgroup: failed to open /acct/uid_10005/pid_7374/cgroup.procs: No such file or directory
09-13 15:14:24.691  2633  2633 D [Concierge]Service: Update widget ID : 11
09-13 15:14:24.691  2093  2093 D [Concierge]WidgetView: change position of spinner
,09-13 15:14:24.692  2093  2093 I [Concierge]WidgetView: initWebView(). Time : 1473772464692
09-13 15:14:24.694  2633  2633 D [Concierge]Service: onStartCommand(). Type : 0
09-13 15:14:24.698  2149  8368 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 15:14:24.707  8319  8319 D AndroidRuntime: Shutting down VM
,09-13 15:14:24.710  1032  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:14:24.714  1032  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 15:14:24.725  1032  2070 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8369 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 15:14:24.727  1839  8362 W GmsApplication: Using Auth Proxy for data requests.
,09-13 15:14:24.756  1032  1108 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8386 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-13 15:14:24.759  2093  2093 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 673184210
09-13 15:14:24.759  2093  2093 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 15:14:24.759  2093  2093 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 15:14:24.762  2093  2093 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@e465752
09-13 15:14:24.762  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-13 15:14:24.764  2093  2093 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 15:14:24.764  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 15:14:24.769  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-13 15:14:24.770  2093  2093 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-13 15:14:24.770  2093  2093 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 15:14:24.770  2093  2093 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473772287095, New one : 1473772464692
09-13 15:14:24.770  2093  2093 D [Concierge]WidgetView: Unregister all receivers
09-13 15:14:24.770  2093  2093 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-13 15:14:24.771  2093  2093 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 15:14:24.772  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 15:14:24.775  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 15:14:24.776  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-13 15:14:24.777  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-13 15:14:24.778  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-13 15:14:24.779  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-13 15:14:24.787  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 15:14:24.788  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 15:14:24.788  8369  8369 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:14:24.788  8369  8369 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 15:14:24.789  8369  8369 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 15:14:24.789  8369  8369 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 15:14:24.819  1032  2110 I ActivityManager: Killing 7791:com.google.android.talk/u0a72 (adj 15): empty #17
,09-13 15:14:24.839  2093  2093 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 15:14:24.846  2093  2093 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 15:14:24.846  2093  2093 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,09-13 15:14:24.848  2093  2093 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 15:14:24.867  2093  2093 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@391bf9af time:205839
,09-13 15:14:24.929  1579  1579 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-13 15:14:24.929  1579  1579 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-13 15:14:24.930  1032  2023 W libprocessgroup: failed to open /acct/uid_10072/pid_7791/cgroup.procs: No such file or directory
09-13 15:14:24.932  1032  1542 D WifiController: battery changed pluggedType: 2
09-13 15:14:24.932  1579  1579 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
09-13 15:14:24.933  1579  1579 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-13 15:14:24.933  8369  8369 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-13 15:14:24.933  1579  1579 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-13 15:14:24.934  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:24.934  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:14:24.934  1966  2169 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-13 15:14:24.934  1966  2169 D LEDHandler: Battery Level Remaining: 100%
09-13 15:14:24.935  1966  2169 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
09-13 15:14:24.935  7762  8009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 15:14:24.935  8202  8202 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-13 15:14:24.941  8369  8369 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-13 15:14:24.960  8369  8369 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 15:14:24.978  2093  2093 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-13 15:14:24.982  8369  8369 D LgDataFeature: LgDataFeature() Constructor: none
09-13 15:14:24.982  8369  8369 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 15:14:25.015  2093  2889 I GBoardtInterface: onReloaded()
,09-13 15:14:25.017  2093  2093 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-13 15:14:25.018  3750  4926 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 15:14:25.019  3750  3768 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 15:14:25.025  1929  1929 D ActionManagerService: notifyUserLog: 1000001
09-13 15:14:25.026  3750  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 15:14:25.026  3750  4933 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,09-13 15:14:25.028  1929  1929 D ActionManagerService: notifyUserLog: 1000001
09-13 15:14:25.030  3750  4933 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 15:14:25.030  3750  4933 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 15:14:25.030  3750  4933 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-13 15:14:25.030  3750  4926 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 15:14:25.030  3750  4933 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-13 15:14:25.032  2093  2093 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-13 15:14:25.032  2093  2093 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-13 15:14:25.033  2093  2093 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-13 15:14:25.033  2093  2093 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 15:14:25.035  2093  2093 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-13 15:14:25.035  2093  2093 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 15:14:25.045  8369  8369 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
