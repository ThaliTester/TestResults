#### Test 82728424cc1b7f1_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-25 21:50:00.087  1600  1600 I [SystemUI]Clock: called onTimeUpdated()
08-25 21:50:00.097  1600  1600 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 21:50:00.097  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
08-25 21:50:00.099  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
08-25 21:50:00.101  1600  1600 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 21:50:13.342  6841  6841 D AndroidRuntime: 
08-25 21:50:13.342  6841  6841 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 21:50:13.349  6841  6841 D AndroidRuntime: CheckJNI is OFF
08-25 21:50:13.554  6841  6841 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 21:50:13.565  1034  1573 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 21:50:13.581  1942  3139 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-25 21:50:13.587  1034  1573 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-25 21:50:13.589  1034  1573 D ActivityManager: setTaskToReturnTo : TaskRecord{1730e0f4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 21:50:13.589  1034  1573 D ActivityManager: setTaskToReturnTo : TaskRecord{1730e0f4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 21:50:13.591  1034  1573 D WindowStateEx: AppWindowTokenEx init.. 
08-25 21:50:13.592   337   342 E GBMv2   : DFP En is all cleared set to be enabled
08-25 21:50:13.621  1034  1573 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6856 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 21:50:13.624  6841  6841 D AndroidRuntime: Shutting down VM
08-25 21:50:13.680  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-25 21:50:13.682  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f208fce co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 21:50:13.683  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-25 21:50:13.683  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4022eef co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 21:50:13.760  6856  6856 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-25 21:50:13.865  6856  6856 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 21:50:13.874  6856  6856 I LibraryLoader: Loading: webviewchromium
08-25 21:50:13.877  6856  6856 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 469-473)
08-25 21:50:13.878  6856  6856 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 21:50:13.899  6856  6856 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {53aacac}
,08-25 21:50:13.902  6856  6856 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 21:50:13.902  6856  6856 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 21:50:13.912  6856  6856 I BrowserStartupController: Initializing chromium process, renderers=0
,08-25 21:50:13.914  6856  6856 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 21:50:13.931   310  1382 V AudioPolicyService: registerClient() client 0xb558a400, uid 10118
,08-25 21:50:13.936  1034  1096 D BluetoothManagerService: Message: 20
08-25 21:50:13.936  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1accd5de:true
08-25 21:50:13.937  6856  6856 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-25 21:50:13.939  6856  6856 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-25 21:50:13.942  6856  6856 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-25 21:50:13.961  6856  6856 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 21:50:13.961  6856  6856 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 21:50:13.961  6856  6856 I Adreno-EGL: Build Date: 12/12/14 금
08-25 21:50:13.961  6856  6856 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 21:50:13.961  6856  6856 I Adreno-EGL: Remote Branch: 
08-25 21:50:13.961  6856  6856 I Adreno-EGL: Local Patches: 
08-25 21:50:13.961  6856  6856 I Adreno-EGL: Reconstruct Branch: 
,08-25 21:50:14.049  6856  6895 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-25 21:50:14.054  6856  6856 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-25 21:50:14.073  6856  6856 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 21:50:14.081  6856  6856 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 21:50:14.084  6856  6856 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-25 21:50:14.088  6856  6856 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-25 21:50:14.088  6856  6856 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-25 21:50:14.105  6856  6856 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-25 21:50:14.112  6856  6856 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 21:50:14.112  6856  6856 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 21:50:14.146  6856  6909 D OpenGLRenderer: Render dirty regions requested: true
,08-25 21:50:14.146  6856  6909 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 21:50:14.154  6856  6909 D OpenGLRenderer: Enabling debug mode 0
08-25 21:50:14.163  6856  6856 D Atlas   : Validating map...
,08-25 21:50:14.171  1034  1050 D SplitWindow: check instance of lgWin Window{158ccaa8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 21:50:14.178  1034  1092 W ActivityManager: Activity pause timeout for ActivityRecord{3512501d u0 com.test.thalitest/.MainActivity t6}
,08-25 21:50:14.221  6856  6907 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 21:50:14.221  6856  6907 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 21:50:14.357  1034  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +679ms (total +764ms)
,08-25 21:50:14.358  6856  6856 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1495cb6b time:170954
08-25 21:50:14.360  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3512501d u0 com.test.thalitest/.MainActivity t6} time:170957
08-25 21:50:14.491  6856  6856 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-25 21:50:14.491  6856  6856 I chromium: 
,08-25 21:50:14.537  6856  6856 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 21:50:14.632  6856  6907 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-25 21:50:14.632  6856  6907 I chromium: 
,08-25 21:50:14.775  6856  6923 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435168256
,08-25 21:50:14.789  6856  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 21:50:14.789  6856  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 21:50:14.789  6856  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 21:50:14.789  6856  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 21:50:14.789  6856  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-25 21:50:14.790  6856  6923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecdc43f added. We now have 1 listener(s)
08-25 21:50:14.795  1034  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 21:50:14.798  6856  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-25 21:50:14.801  6856  6923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:14.803  6856  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:14.803  6856  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 21:50:14.811  6856  6923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d612c6a added. We now have 1 listener(s)
08-25 21:50:14.811  6856  6923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:50:14.817  1034  1541 D WifiService: New client listening to asynchronous messages
08-25 21:50:14.822  6856  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 21:50:14.823  6856  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 21:50:14.823  6856  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 21:50:14.823  6856  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 21:50:14.823  6856  6923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 21:50:14.830  6856  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:50:14.831  1034  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:14.833  6856  6923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-25 21:50:14.845  6856  6923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 21:50:14.846  6856  6923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:14.846  6856  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:14.846  6856  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:14.846  6856  6923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:14.846  6856  6923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:14.846  6856  6923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:14.846  6856  6923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:14.846  6856  6923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:14.846  6856  6923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 21:50:14.846  6856  6923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:14.847  6856  6923 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 21:50:14.848  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:14.851  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:14.886  6856  6856 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 21:50:15.245   337   344 E GBMv2   : DFP En is all cleared set to be enabled
08-25 21:50:15.245   337   344 E GBMv2   : Set value is all cleared set the max
08-25 21:50:15.245   337   344 I GBMv2   : DFP Enabled. Ignore VFP set
,08-25 21:50:15.845  6856  6926 W jxcore-log: Initializing JXcore engine
08-25 21:50:15.845  6856  6926 W jxcore-log: JXcore engine is ready
,08-25 21:50:15.921  6926  6926 W Thread-787: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8391]" dev="sockfs" ino=8391 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 21:50:15.921  6926  6926 W Thread-787: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-25 21:50:15.921  6926  6926 W Thread-787: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10484]" dev="sockfs" ino=10484 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 21:50:15.921  6926  6926 W Thread-787: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-25 21:50:15.921  6926  6926 W Thread-787: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32859]" dev="sockfs" ino=32859 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-25 21:50:15.954  6856  6926 W jxcore-log: Starting JXcore engine
,08-25 21:50:16.116  6856  6926 W jxcore-log: Platform android
08-25 21:50:16.116  6856  6926 W jxcore-log: 
,08-25 21:50:16.117  6856  6926 W jxcore-log: Process ARCH arm
08-25 21:50:16.117  6856  6926 W jxcore-log: 
08-25 21:50:16.502  6856  6926 I jxcore-log: JXcore Cordova bridge is ready!
08-25 21:50:16.502  6856  6926 I jxcore-log: 
08-25 21:50:16.502  6856  6926 W jxcore-log: JXcore engine is started
,08-25 21:50:16.514  6856  6923 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-25 21:50:16.519  6856  6856 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 21:50:27.196  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 21:50:27.196  6856  6926 I jxcore-log: 
,08-25 21:50:27.199  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-25 21:50:27.199  6856  6926 I jxcore-log: 
08-25 21:50:27.203  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:27.203  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:27.203  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:27.203  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:27.203  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:27.203  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.203  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:27.203  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:27.205  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.207  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 21:50:27.207  6856  6926 I jxcore-log: 
08-25 21:50:27.209  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 21:50:27.209  6856  6926 I jxcore-log: 
,08-25 21:50:27.710  6856  6926 D executeNativeTests: Running unit tests,
,08-25 21:50:27.792  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 21:50:27.792  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f added. We now have 2 listener(s)
,08-25 21:50:27.793  1034  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:27.795  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:27.795  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:27.795  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:50:27.795  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-25 21:50:27.795  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc added. We now have 2 listener(s)
08-25 21:50:27.795  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:27.796  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 21:50:27.798  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:27.800  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:27.800  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:27.800  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:27.800  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:27.800  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:27.800  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.800  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:27.800  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:50:27.801  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.801  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:27.802  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:27.803  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:27.806  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 21:50:27.806  6856  6926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 21:50:27.806  6856  6926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 21:50:27.808  6856  6926 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 21:50:27.809  6856  6926 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 21:50:27.809  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 21:50:27.809  6856  6926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 21:50:27.809  6856  6926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 21:50:27.809  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.810  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.810  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.811  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:50:27.811  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.811  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:27.811  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:27.811  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f removed from the list
08-25 21:50:27.811  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:50:27.811  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc removed from the list
08-25 21:50:27.811  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.811  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.812  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.812  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.812  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.812  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.812  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.812  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.814  6856  6926 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 21:50:27.814  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.814  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.814  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 21:50:27.815  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:27.815  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.815  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.815  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.815  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.815  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.815  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.815  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.815  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.815  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.815  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.816  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.816  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.816  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.816  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 21:50:27.819  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
0,8-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 21:50:27.820  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 21:50:27.820  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.820  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.820  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.821  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:27.821  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.821  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.821  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.821  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.821  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.821  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.821  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.821  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.821  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.821  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.822  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.822  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.822  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.822  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.822  6856  6926 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 21:50:27.824  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:27.826  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:27.826  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:27.826  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:27.826  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:27.826  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:27.826  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.826  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:27.826  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:27.827  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.827  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:27.829  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:27.829  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:27.830  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:50:27.830  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:50:27.830  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:50:27.830  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:27.830  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 21:50:27.833  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 21:50:27.833  1034  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:27.837  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 21:50:27.841  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 21:50:27.842  6856  6926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 21:50:27.842  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 21:50:27.843  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:27.844  6856  6926 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 21:50:27.844  6856  6926 I io.jxcore.node.ConnectionHelper: start: OK
08-25 21:50:27.846  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.846  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.846  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.846  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:27.846  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.846  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:27.846  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.846  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.846  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.846  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.846  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.847  6856  6926 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 21:50:27.848  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:27.850  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:27.850  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:27.850  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:27.850  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:27.850  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:27.850  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.850  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:27.850  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:27.851  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.851  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:27.852  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:27.853  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:50:27.853  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:50:27.853  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:50:27.853  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:27.853  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 21:50:27.854  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:27.856  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 21:50:27.857  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:27.857  6856  6926 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 21:50:27.858  6856  6926 I io.jxcore.node.ConnectionHelper: start: OK
08-25 21:50:27.859  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.859  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.859  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.859  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:27.859  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.859  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:27.859  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.859  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.859  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.859  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.859  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.859  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.859  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.860  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.860  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.861  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:27.861  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:27.861  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.861  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.862  6856  6926 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 21:50:27.863  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:50:27.865  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:27.865  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:27.865  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:27.865  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:27.865  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:27.865  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.865  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:27.865  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:27.866  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:27.866  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:27.866  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:50:27.866  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:50:27.866  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:50:27.866  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:27.866  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 21:50:27.870  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:27.871  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:27.940  1034  1995 I art     : Explicit concurrent mark sweep GC freed 35714(1640KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.689ms total 73.342ms
08-25 21:50:27.942  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 21:50:27.943  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:27.944  6856  6926 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 21:50:27.944  6856  6926 I io.jxcore.node.ConnectionHelper: start: OK
08-25 21:50:27.944  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.944  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.944  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.944  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.944  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.944  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.945  6856  6926 I org.thaliproject.p2p.btconnectorlib.Connect,ionManager: dispose
08-25 21:50:27.945  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.945  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:27.945  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.945  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:50:27.945  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
,08-25 21:50:27.945  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.945  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 21:50:27.945  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:50:27.945  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:27.946  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:50:27.946  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.946  6856  6926 D BluetoothLeScanner: could not find callback wrapper
,08-25 21:50:27.946  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 21:50:27.946  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:50:27.947  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.947  6856  6926 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported,
08-25 21:50:27.947  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.947  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.947  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.947  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-25 21:50:27.947  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.947  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.947  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.947  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:50:27.947  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.947  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.947  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.947  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.947  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 21:50:27.947  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.955  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.955  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.955  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:27.955  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-25 21:50:27.955  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.955  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.956  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 21:50:27.956  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-25 21:50:27.956  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.956  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.957  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:27.957  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.957  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 21:50:27.957  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.957  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.957  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.957  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.957  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 21:50:27.957  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.957  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.957  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.958  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:50:27.958  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.958  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:27.958  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:27.958  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.958  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
,08-25 21:50:27.958  6856  6926 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 21:50:27.959  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.959  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.959  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.959  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-25 21:50:27.959  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.959  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.959  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.959  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:50:27.959  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.959  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.959  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.959  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:27.959  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.959  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.960  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.960  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.961  6856  6926 D BluetoothLeScanner: could not find callback wrapper,
08-25 21:50:27.961  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:27.961  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.961  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
,08-25 21:50:27.961  6856  6926 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 21:50:27.961  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.961  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.961  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 21:50:27.962  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:27.962  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.962  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.962  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.962  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:50:27.962  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.962  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.962  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.962  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.962  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:50:27.962  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.962  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.962  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.963  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:27.963  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 21:50:27.963  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.963  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.963  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 21:50:27.970  6856  6926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 21:50:27.970  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 21:50:27.970  6856  6926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 21:50:27.970  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 21:50:27.970  6856  6926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 21:50:27.970  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:50:27.970  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.970  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.971  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:27.971  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.971  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:27.971  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.971  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.971  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.971  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.971  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:50:27.971  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.971  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.971  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:27.973  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.973  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:50:27.973  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:27.973  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:27.973  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.973  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.975  6856  6926 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:50:27.975  6856  6926 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 21:50:27.975  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 21:50:27.976  6856  6926 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:50:27.977  6856  6926 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:,1810:1810:1810]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 21:50:27.977  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 21:50:27.977  6856  6926 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 21:50:27.977  6856  6926 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-25 21:50:27.978  6856  6926 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 21:50:27.978  6856  6926 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:50:27.978  6856  6926 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 21:50:27.978  6856  6926 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 21:50:27.978  6856  6926 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:50:27.978  6856  6926 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 21:50:27.978  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-25 21:50:27.981  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 21:50:27.982  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 21:50:27.982  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 21:50:27.983  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 21:50:27.983  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 21:50:27.983  6856  6926 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-25 21:50:27.986  6856  6936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 851)
08-25 21:50:27.989  6856  6926 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:50:27.989  6856  6926 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 21:50:27.990  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.991  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.991  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.991  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:27.991  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.991  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.991  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 21:50:27.993  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.993  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.993  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.993  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.993  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.993  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.994  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.994  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.995  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.995  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:50:27.995  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:27.995  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:27.995  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.995  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.996  6856  6926 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 21:50:27.996  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:27.996  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:27.996  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:27.997  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:27.997  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.997  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.997  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:27.997  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.997  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.997  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:27.997  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.997  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.997  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:27.997  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:27.998  6856  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 851
08-25 21:50:27.998  6856  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 851)
08-25 21:50:27.998  6856  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 851)
08-25 21:50:27.998  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:27.998  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:27.999  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:27.999  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:27.999  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:27.999  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:27.999  6856  6926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged:, State: NOT_STARTED, is discovering: true, is advertising: true
08-25 21:50:28.000  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:28.000  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:28.000  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:28.000  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:28.000  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.000  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.000  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.000  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.000  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.000  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:28.001  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.001  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:28.001  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.001  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.004  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:28.004  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:28.004  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:28.004  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 21:50:28.004  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.004  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.005  6856  6926 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 21:50:28.005  6856  6926 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 21:50:28.005  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
08-25 21:50:28.005  6856  6926 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 21:50:28.005  6856  6926 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 21:50:28.006  6856  6926 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 21:50:28.006  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 21:50:28.006  6856  6926 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 21:50:28.006  6856  6926 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 21:50:28.006  6856  6926 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 21:50:28.006  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 21:50:28.006  6856  6926 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 21:50:28.006  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:28.006  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:28.006  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:28.006  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:28.006  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.006  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.006  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.006  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.006  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.006  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:28.006  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.006  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.007  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.007  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.013  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:28.013  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:28.014  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:28.014  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:28.014  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.014  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.014  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:28.014  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.014  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.014  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.014  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.015  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.015  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:28.015  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.015  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.015  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.015  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.015  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:28.015  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.015  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.015  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.015  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:28.015  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:28.015  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:28.017  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:28.017  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.017  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.017  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.017  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.017  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
,08-25 21:50:28.017  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:28.017  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.017  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.017  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.017  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.018  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:28.018  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:28.019  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:28.019  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:28.019  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.019  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.021  6856  6926 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 21:50:28.021  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:28.024  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 21:50:28.024  6856  6926 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 21:50:28.025  6856  6926 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 21:50:28.025  6856  6856 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 21:50:28.025  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 21:50:28.025  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:50:28.026  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:28.026  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 21:50:28.026  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 21:50:28.026  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 21:50:28.026  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.026  6856  6926 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 21:50:28.027  6856  6856 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 21:50:28.027  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.027  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.027  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:50:28.027  6856  6926 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:50:28.027  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:50:28.027  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:, stopScannerAndAdvertiser
08-25 21:50:28.028  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:28.028  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:28.028  6856  6926 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 21:50:28.028  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.028  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.029  6856  6938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 21:50:28.029  6856  6926 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:50:28.029  6856  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:50:28.029  6856  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:50:28.029  6856  6856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:50:28.029  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.029  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:28.030  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:28.030  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:28.030  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:50:28.030  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.030  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.030  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.030  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.030  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.030  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:28.030  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.030  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.030  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.030  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.031  6856  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 21:50:28.031  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:28.031  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:28.031  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.031  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.031  6856  6856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 21:50:28.031  6856  6926 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 21:50:28.031  6856  6926 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 21:50:28.031  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 21:50:28.033  6856  6926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 21:50:28.033  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:28.033  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:28.033  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:28.033  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:28.033  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.033  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.033  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.033  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.033  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
,08-25 21:50:28.033  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:28.033  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.033  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:28.033  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.033  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.034  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:28.034  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:28.034  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.034  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.035  1034  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:28.036  1034  2210 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:28.036  1034  1730 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:28.037  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:28.037  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:28.037  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:28.037  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:28.037  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.037  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.037  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.037  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.037  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.037  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:28.037  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.037  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.037  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.037  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.039  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:28.039  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:28.039  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.039  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.040  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:28.040  6856  6926 V io.jxcore.node.StartStopOperation: isTargetStat,e: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:28.040  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:28.040  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:28.040  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.040  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.040  6856  6926 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4508d4f not in the list
08-25 21:50:28.040  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.040  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.040  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:28.040  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.040  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.040  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:28.041  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:28.041  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:28.041  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:28.041  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:28.041  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b746cdc not in the list
08-25 21:50:28.042  6856  6926 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 21:50:28.042  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 21:50:28.043  6856  6926 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 21:50:28.043  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 21:50:28.043  6856  6926 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 21:50:28.043  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 21:50:28.045  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-25 21:50:28.045  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 21:50:28.045  6856  6926 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 21:50:28.046  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 21:50:28.046  6856  6926 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 21:50:28.046  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 21:50:28.046  6856  6926 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 21:50:28.046  6856  6926 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 21:50:28.047  6856  6926 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 21:50:28.047  6856  6926 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 21:50:28.047  6856  6926 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 21:50:28.047  6856  6926 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 21:50:28.047  6856  6926 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 21:50:28.047  6856  6926 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 21:50:28.048  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:28.048  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@397d189d added. We now have 2 listener(s)
08-25 21:50:28.048  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:28.056  6856  6926 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 21:50:28.057  1034  1941 D WifiServiceImplEx: setWifiEnabled: true pid=6856, uid=10118, package= com.test.thalitest, App Lable : ThaliTest,
08-25 21:50:28.058  1034  1941 D WifiService: setWifiEnabled: true pid=6856, uid=10118
08-25 21:50:28.058  1034  1941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 21:50:28.059  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:28.059  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e318112 added. We now have 3 listener(s)
08-25 21:50:28.059  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:28.061  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:28.061  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3653a0e3 added. We now have 4 listener(s)
08-25 21:50:28.061  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:50:28.063  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:28.063  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f32dae0 added. We now have 5 listener(s)
08-25 21:50:28.063  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:28.064  1034  1941 D WifiServiceImplEx: setWifiEnabled: false pid=6856, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 21:50:28.064  1034  1941 D WifiService: setWifiEnabled: false pid=6856, uid=10118
08-25 21:50:28.064  1034  1941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 21:50:28.074  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 21:50:28.074  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 21:50:28.075  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 21:50:28.076  1034  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 21:50:28.076  1034  1573 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@227a92ab mBinding = false
08-25 21:50:28.078  1034  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:28.078  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:28.079  1034  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:28.079  1034  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:28.080  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:28.080  1034  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 21:50:28.080  1034  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 21:50:28.080  1034  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 21:50:28.081  1034  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 21:50:28.081  1034  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 21:50:28.085  1034  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 21:50:28.085  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 21:50:28.085  1034  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.085  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.085  2666  2666 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 21:50:28.085  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 21:50:28.085  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 21:50:28.086  1034  1536 D WifiNative-wlan0: SET ps 1: returned true
08-25 21:50:28.086  1034  2812 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.086   304   894 D CommandListener: Clearing all IP addresses on wlan0
,08-25 21:50:28.088  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 21:50:28.089  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 21:50:28.089  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 21:50:28.089  1034  1096 D BluetoothManagerService: Message: 2
08-25 21:50:28.090  1034  1096 D BluetoothManagerService: Sending off request.
08-25 21:50:28.090  3940  3959 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 21:50:28.091  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:28.091  3940  4029 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 21:50:28.091  3940  4029 D BluetoothAdapterProperties: Setting state to 13
08-25 21:50:28.091  3940  4029 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 21:50:28.091  3940  4029 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 21:50:28.091  3940  4029 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 21:50:28.094  1034  1096 D BluetoothManagerService: Message: 60
08-25 21:50:28.094  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 21:50:28.094  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 21:50:28.095  3940  4037 D BluetoothAdapterProperties: Scan Mode:20
08-25 21:50:28.095  3940  4029 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 21:50:28.098  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.098  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:28.098  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:28.098  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:28.098  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:28.098  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:28.098  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:28.098  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:28.098  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:28.098  3940  4343 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:28.098  3940  4344 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:28.099  3940  4286 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 21:50:28.099  3940  4286 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:28.099  3940  4286 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 21:50:28.099  3940  4286 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 21:50:28.099  3940  4286 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 21:50:28.099  3940  4286 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 21:50:28.099  3940  4286 V Blueto,othMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 21:50:28.099  3940  4286 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-25 21:50:28.102  3940  4289 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:28.103  3940  4348 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:28.103  3940  4029 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 21:50:28.113  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 21:50:28.113  3940  4138 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-25 21:50:28.114  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:28.114  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:28.114  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:28.114  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:28.116  3940  4138 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:50:28.116  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:28.116  3940  4138 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:50:28.116  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:28.116  3940  4138 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:50:28.116  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 21:50:28.116  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 21:50:28.116  3940  4138 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 21:50:28.117  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.118  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:28.118  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:28.122  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 21:50:28.122  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-25 21:50:28.124  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:28.138   341   341 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 221us total 10.243ms
08-25 21:50:28.138  1034  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6954 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 21:50:28.144  1034  1535 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.144  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.144  1034  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@23f5112a
08-25 21:50:28.145  1034  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:28.146  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:28.146  1034  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:28.147  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.147   341   341 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 8.965ms
08-25 21:50:28.147  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:28.147  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:28.147  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:28.147  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:28.147  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:28.147  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:28.147  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:28.147  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:28.148  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.148  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:28.149  6856  6936 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-25 21:50:28.149  6856  6936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 851)
08-25 21:50:28.150  3940  3940 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:28.150  3940  3940 D BluetoothMapService: STATE_TURNING_OFF
08-25 21:50:28.151  3940  3940 V BtOppService: Receiver DISABLED_ACTION 
08-25 21:50:28.151  3940  3940 V BluetoothMapService: Handler(): got msg=4
08-25 21:50:28.151  3940  3940 D BluetoothMapService: MAP Service closeService in
08-25 21:50:28.151  3940  3940 D BluetoothMapMasInstance: MAP Service shutdown
08-25 21:50:28.151  3940  3940 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 21:50:28.151  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.151  3940  3940 V BluetoothMapService: MAP Service closeService out
08-25 21:50:28.151  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:28.151  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:28.151  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:28.151  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:28.151  6856  6856 V io.jxcore.node.,ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:28.151  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:28.151  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:28.151  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:28.151  3940  3940 I BtOppRfcommListener: stopping Accept Thread
08-25 21:50:28.151  3940  3940 V BtOppRfcommListener: close mBtServerSocket
08-25 21:50:28.152  3940  3940 V BtOppRfcommListener: waiting for thread to terminate
08-25 21:50:28.152  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.152  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:28.152  3940  4343 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 21:50:28.153  3940  3940 V BtOppRfcommListener: done waiting for thread to terminate
,08-25 21:50:28.157  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:28.157   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.148ms
08-25 21:50:28.157  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 21:50:28.158  1034  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:28.160  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:28.161  1034  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:28.161  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:28.162  1034  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 21:50:28.162  1034  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:28.162  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:28.163  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:28.163  1034  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:28.163  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:28.171  1034  1922 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-25 21:50:28.171  1034  2809 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.171  1034  2809 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.171  1034  2809 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 21:50:28.171  1034  2809 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.171  1034  2809 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-25 21:50:28.184  1034  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6975 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 21:50:28.185  1034  1034 D WifiHS20: hidePasspointNotification off =false
,08-25 21:50:28.187  3940  3940 V BtOppService: onDestroy
08-25 21:50:28.188  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:28.188  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:28.188  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 21:50:28.188  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 21:50:28.188  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 21:50:28.188  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:28.188  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:28.188  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 21:50:28.188  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 21:50:28.188  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-25 21:50:28.188  1034  1554 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.188  1034  1555 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.189  3940  3940 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 21:50:28.190  1034  1535 D LGWifiP2pService: P2pDisablingState
08-25 21:50:28.190  1034  1535 D LGWifiP2pService: P2pDisablingState{ when=-46ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.190  1034  1535 D LGWifiP2pService: p2p socket connection lost
08-25 21:50:28.190  1034  1535 D LGWifiP2pService: P2pDisabledState
08-25 21:50:28.190  1034  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 21:50:28.190  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 21:50:28.190  1034  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.190  1034  1535 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.190  2666  2666 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 21:50:28.191  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 21:50:28.191  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 21:50:28.192  1034  1536 D WifiNative-wlan0: SET ps 1: returned true
08-25 21:50:28.192  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 21:50:28.192  1942  1942 D WfdsService: WifiP2pState is changed : false
08-25 21:50:28.192  1942  2341 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 21:50:28.192  1942  2341 D WfdsService: Set the WFDS Monitor: false
08-25 21:50:28.192   304   894 D CommandListener: Clearing all IP addresses on wlan0
08-25 21:50:28.193  1034  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 21:50:28.193   304  6984 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 21:50:28.193  1034  1543 D DSQN    : disableDataServiceNotify
08-25 21:50:28.193  1034  1543 D DSQN    : stop dsqn bin
08-25 21:50:28.193  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 21:50:28.193  1034  2809 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-25 21:50:28.193  1942  2341 D WfdsMonitor: WFDS Monitor is stopped
08-25 21:50:28.193  1942  2341 D WfdsService: STATE : WfdsDisabledS,tate - enter
08-25 21:50:28.194  1942  2351 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 21:50:28.194  1942  2716 D CtrlSupplicant: Received on exit socket, terminate
08-25 21:50:28.194  1942  2716 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 21:50:28.194  1942  2716 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 21:50:28.194  1942  2716 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 21:50:28.194  1942  2341 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 21:50:28.196  1034  1536 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 21:50:28.197  1034  1536 D WifiNative-p2p0: TERMINATE: returned true
08-25 21:50:28.197  1034  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 21:50:28.197  1034  1536 E WifiStateMachine: useWiFiOffloading() : false
08-25 21:50:28.197  1034  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-25 21:50:28.198  1034  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 21:50:28.199  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:28.199  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:28.199  1034  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:28.199  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 21:50:28.199  1034  2809 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.199  1034  2809 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.199  1034  2809 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 21:50:28.200  1600  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 21:50:28.201  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:28.201  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:28.201  1034  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 21:50:28.201  1034  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 21:50:28.201  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 21:50:28.202  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:28.204  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:28.204  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 21:50:28.204  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:28.204  1034  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:28.204  1034  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:28.204  1034  1543 D NetworkManagementService: Removing idletimer
08-25 21:50:28.205  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:28.205  1034  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_,VPN] ]
08-25 21:50:28.205  1034  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:28.205  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 21:50:28.205  1034  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:28.205  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 21:50:28.206  1034  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 21:50:28.207  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:28.207  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:28.207  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 21:50:28.210  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 21:50:28.210  1034  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 21:50:28.210  1034  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 21:50:28.210  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:28.210  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 21:50:28.210  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 21:50:28.210  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 21:50:28.211  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 21:50:28.211  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 21:50:28.211  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 21:50:28.211  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 21:50:28.211  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 21:50:28.211  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 21:50:28.211  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-25 21:50:28.213  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.213  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:28.213  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:28.213  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:28.213  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:28.213  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:28.213  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:28.213  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:28.213  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:28.213  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.213  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:28.214  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.215  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:28.215  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:28.215  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:28.215  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:28.215  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:28.215  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:28.215  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:28.215  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:28.215  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:28.215  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:28.225  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:28.225  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:28.227  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:28.231  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 21:50:28.231  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:28.232  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:28.233  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:28.247  6975  6975 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:50:28.247  6975  6975 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-25 21:50:28.247  6975  6975 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 21:50:28.247  6975  6975 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-25 21:50:28.248  6975  6975 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 21:50:28.248  6975  6975 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 21:50:28.250  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 21:50:28.251  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:28.251  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:28.263  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 21:50:28.264  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:28.264  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:28.282  6954  6954 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 21:50:28.282  6954  6954 W LG Account v2.2: No ProfileInfo entries
08-25 21:50:28.282  6954  6954 I LG Account v2.2: isEnabled: false
08-25 21:50:28.282  6954  6954 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 21:50:28.282  6954  6954 I Feature : [Lifetracker]Country: EU
08-25 21:50:28.283  6954  6954 I Feature : [Lifetracker]Operator: OPEN
08-25 21:50:28.283  6954  6954 I Feature : [Lifetracker]Ranking support: false
08-25 21:50:28.283  6954  6954 I Feature : [Lifetracker]Comfort support: false
08-25 21:50:28.283  6954  6954 I Feature : [Lifetracker]Accessory: true
,08-25 21:50:28.284  6954  6954 I Feature : [Lifetracker]Health device: true
08-25 21:50:28.284  6954  6954 I Feature : [Lifetracker]Extra Pedometer: false
08-25 21:50:28.284  6954  6954 I Feature : [Lifetracker]Blood glucose device: false
08-25 21:50:28.284  6954  6954 I Feature : [Lifetracker]Device Number: 3
08-25 21:50:28.292  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:28.304  2666  2666 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 21:50:28.304  2666  2666 I wpa_supplicant: monitor socket send errors count : 1
08-25 21:50:28.304  2666  2666 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
08-25 21:50:28.304  1034  2812 D DhcpStateMachine: StoppedState
,08-25 21:50:28.305  1034  2812 D DhcpStateMachine: StoppedState{ when=-112ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:28.305  1034  2709 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 21:50:28.305  1034  2709 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 21:50:28.320  6975  6975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 21:50:28.340  1034  1922 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6997 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 21:50:28.342  1034  1922 I ActivityManager: Killing 6340:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-25 21:50:28.343  2666  2666 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 21:50:28.344  1034  2709 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 21:50:28.344  1034  2709 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 21:50:28.344  1034  2709 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 21:50:28.344  1034  2709 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 21:50:28.345  2666  2666 W wpa_supplicant: USIM:  scard_deinit function
08-25 21:50:28.345  1034  1096 D Tethering: InitialState.processMessage what=4
08-25 21:50:28.346  1034  2709 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:28.346  1034  2709 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 21:50:28.346  1034  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=184929
08-25 21:50:28.347  1034  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=184931
08-25 21:50:28.347  1034  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=184931  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 21:50:28.348  1034  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=184932  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 21:50:28.397  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 21:50:28.397  1034  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-25 21:50:28.397  1034  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 21:50:28.398  1034  1573 W libprocessgroup: failed to open /acct/uid_10014/pid_6340/cgroup.procs: No such file or directory
08-25 21:50:28.400  1034  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:28.400  1034  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:28.401  1034  1096 D BluetoothManagerService: Message: 20
08-25 21:50:28.401  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f06b152:true
08-25 21:50:28.408  3940  3940 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 21:50:28.408  3940  3940 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:28.408  3940  3940 V BluetoothPbapReceiver: ***********state = 13
08-25 21:50:28.409  3940  3940 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-25 21:50:28.415  2666  2666 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-25 21:50:28.415  1034  2709 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 21:50:28.415  1034  2709 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 21:50:28.415  1034  2709 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 21:50:28.417  1034  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-25 21:50:28.420  3940  3940 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:28.420  3940  3940 V BluetoothPbapService: state: 13
08-25 21:50:28.420  3940  3940 V BluetoothPbapService: Pbap Service closeService in
08-25 21:50:28.422  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 21:50:28.423  3940  3940 V BluetoothPbapService: successfully stopped pbap service
08-25 21:50:28.424  3940  3940 V BluetoothPbapService: Pbap Service closeService out
08-25 21:50:28.424  3940  3940 V BluetoothPbapService: Pbap Service onDestroy
08-25 21:50:28.424  3940  3940 V BluetoothPbapService: Pbap Service closeService in
08-25 21:50:28.424  3940  3940 V BluetoothPbapService: Pbap Service closeService out
08-25 21:50:28.424  3940  3940 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 21:50:28.431  1034  1096 D BluetoothManagerService: Message: 30
08-25 21:50:28.437  1034  1096 D BluetoothManagerService: Message: 30
,08-25 21:50:28.440  6975  6975 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 21:50:28.441  6975  6975 D BluetoothMap: Create BluetoothMap proxy object
08-25 21:50:28.442  1034  1096 D BluetoothManagerService: Message: 30
08-25 21:50:28.446  1034  1096 D BluetoothManagerService: Message: 30
08-25 21:50:28.448  6975  6975 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-25 21:50:28.449  6975  6975 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-25 21:50:28.461  6975  6975 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-25 21:50:28.465  6975  6975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-25 21:50:28.473  6975  6975 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:50:28.482  6975  6975 D BluetoothInputDevice: Proxy object connected
08-25 21:50:28.483  6975  6975 D HidProfile: Bluetooth service connected
08-25 21:50:28.484  6975  6975 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:50:28.484  6997  6997 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 21:50:28.485  6975  6975 D PanProfile: Bluetooth service connected
08-25 21:50:28.485  6975  6975 D BluetoothMap: Proxy object connected
08-25 21:50:28.486  6975  6975 D MapProfile: Bluetooth service connected
08-25 21:50:28.486  6975  6975 D BluetoothMap: getConnectedDevices()
,08-25 21:50:28.488  6975  6975 D BluetoothMap: Bluetooth is Not enabled
08-25 21:50:28.488  6975  6975 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 21:50:28.490  6997  6997 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 21:50:28.490  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:28.490  6975  6975 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 21:50:28.492  1034  1886 I ActivityManager: Killing 6456:com.android.defcontainer/u0a4 (adj 15): empty #17
08-25 21:50:28.523  1034  1959 W libprocessgroup: failed to open /acct/uid_10004/pid_6456/cgroup.procs: No such file or directory
,08-25 21:50:28.525  1034  1536 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 21:50:28.525  1034  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 21:50:28.525  1034  1536 E WifiStateMachine: useWiFiOffloading() : false
08-25 21:50:28.525  1034  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 21:50:28.526  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-25 21:50:28.527  1942  2341 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 21:50:28.527  1942  2341 D WfdsService: Set the WFDS Monitor: false
08-25 21:50:28.527  1942  2341 D WfdsMonitor: WFDS Monitor is stopped
08-25 21:50:28.527  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:28.528  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 21:50:28.529  1034  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 21:50:28.529  1034  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 21:50:28.529  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 21:50:28.530  2482  2482 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:28.531  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:28.533  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:28.534  6856  6856 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 21:50:28.534  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 21:50:28.562  6975  6975 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:28.563  6975  6975 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 21:50:28.572  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 21:50:28.574  6975  6975 D BluetoothPermissionRequest: onReceive
08-25 21:50:28.578  6975  6975 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 21:50:28.588  1034  1904 I ActivityManager: Killing 6612:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-25 21:50:28.590  6975  6975 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 21:50:28.628  3940  3940 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 21:50:28.628  3940  3940 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-25 21:50:28.630  3940  3940 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 21:50:28.630  1034  1923 W libprocessgroup: failed to open /acct/uid_10008/pid_6612/cgroup.procs: No such file or directory
08-25 21:50:28.728  1034  1730 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7025 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 21:50:28.731  3940  3940 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:28.731  3940  3940 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 21:50:28.735  3940  3940 V BluetoothFtpService: Ftp Service onStartCommand
08-25 21:50:28.735  3940  3940 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:28.735  3940  3940 V BluetoothFtpService: Ftp Service closeService
08-25 21:50:28.735  3940  3940 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 21:50:28.737  3940  3940 V BluetoothFtpService: successfully stopped ftp service
08-25 21:50:28.737  3940  3940 V BluetoothFtpService: Ftp Service onDestroy
08-25 21:50:28.737  3940  3940 V BluetoothFtpService: Ftp Service closeService
08-25 21:50:28.741  3940  3940 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 21:50:28.741  3940  3940 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 21:50:28.741  3940  3940 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 21:50:28.741  3940  3940 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:28.741  3940  3940 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 21:50:28.741  3940  3940 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-25 21:50:28.743  3940  3940 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:28.743  3940  3940 V BluetoothSapService: state: 13
08-25 21:50:28.743  3940  3940 V BluetoothSapService: Stopping SAP server process
08-25 21:50:28.747  3940  3940 V BluetoothSapService: Sap Service closeSapService in
08-25 21:50:28.747  3940  3940 V BluetoothSapService: Close listen Socket : 
08-25 21:50:28.747  3940  3940 V BluetoothSapService: Close rfcomm Socket : 
08-25 21:50:28.747  3940  3940 V BluetoothSapService: Close sapd  Socket : 
08-25 21:50:28.801  1034  1730 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7045 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 21:50:28.808  3940  3940 V BluetoothSapService: Sap Service closeSapService out
,08-25 21:50:28.808  3940  3940 V BluetoothSapService: Sap Service onDestroy
08-25 21:50:28.808  3940  3940 V BluetoothSapService: Sap Service closeSapService in
08-25 21:50:28.808  3940  3940 V BluetoothSapService: Close listen Socket : 
08-25 21:50:28.808  3940  3940 V BluetoothSapService: Close rfcomm Socket : 
08-25 21:50:28.808  3940  3940 V BluetoothSapService: Close sapd  Socket : 
08-25 21:50:28.809  3940  3940 V BluetoothSapService: Sap Service closeSapService out
08-25 21:50:28.829  7025  7025 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 21:50:28.854  7025  7025 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-25 21:50:28.864  7045  7045 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 21:50:28.879  1034  1977 I ActivityManager: Killing 6152:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-25 21:50:28.887  7025  7025 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 21:50:28.887  7025  7025 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 21:50:28.888  7025  7025 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 21:50:28.888  7025  7025 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 21:50:28.888  7025  7025 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 21:50:28.890  7025  7025 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 21:50:28.894  7025  7025 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-25 21:50:28.918  1034  1573 W libprocessgroup: failed to open /acct/uid_10011/pid_6152/cgroup.procs: No such file or directory
,08-25 21:50:28.927  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:28.932  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 21:50:28.959  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 21:50:28.963  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:28.968  7025  7025 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 21:50:28.969  6997  6997 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 21:50:28.969  6997  6997 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 21:50:28.970  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:28.973  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:28.983  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:28.983  7025  7025 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 21:50:28.995  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:28.995  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 21:50:28.999  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 21:50:29.006  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:29.010  6997  6997 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 21:50:29.010  6997  6997 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-25 21:50:29.010  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:29.014  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 21:50:29.021  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:29.032  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:29.033  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 21:50:29.035  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 21:50:29.107  1034  1959 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7065 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 21:50:29.118  3940  4138 W bt-btif : ag scb idx 1 not allocated
08-25 21:50:29.118  3940  4138 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:50:29.118  3940  4037 D bt_hci_bdroid: cleanup
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:29.118  3940  4138 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:50:29.118  3940  4138 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 21:50:29.119  3940  4161 I bt_lpm  : LPM is already off!!!
08-25 21:50:29.119  3940  4278 I bt_userial_mct: exiting userial_read_thread
08-25 21:50:29.119  3940  4278 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 21:50:29.119  3940  4037 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 21:50:29.120  3940  4161 I bt_vendor: hw_epilog_process
08-25 21:50:29.121  3940  4037 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 21:50:29.121  3940  4037 D bt_userial_mct: userial_close
,08-25 21:50:29.121  3940  4037 E bt_userial_mct: pthread_join() FAILED result:3
,08-25 21:50:29.121  3940  4037 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 21:50:29.184  3940  4037 D bt_hci_bdroid: set_power 0
08-25 21:50:29.184  3940  4037 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 21:50:29.184  3940  4037 I bt_vendor: bluetooth satus is on
08-25 21:50:29.184  3940  4037 I bt_vendor: bt-vendor : resetting BT status
08-25 21:50:29.184  3940  4037 I bt_vendor: Starting hciattach daemon
08-25 21:50:29.184  3940  4037 I bt_vendor: try to set false
,08-25 21:50:29.187  3940  4037 I bt_vendor: Starting hciattach daemon
08-25 21:50:29.187  3940  4037 I bt_vendor: try to set false
08-25 21:50:29.188  3940  4037 I bt_vendor: cleanup
08-25 21:50:29.190  3940  4138 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 21:50:29.190  3940  4037 I GKI_LINUX: GKI_exit_task 0 done
08-25 21:50:29.190  3940  4037 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 21:50:29.194  3940  4029 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 21:50:29.197  3940  3940 D HeadsetService: Received stop request...Stopping profile...
08-25 21:50:29.199  3940  3940 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 21:50:29.199  3940  3940 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 21:50:29.199  3940  3940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13a01d75
,08-25 21:50:29.200  3940  4069 D HeadsetStateMachine: Exit Disconnected: -1
08-25 21:50:29.202  1034  1034 D BluetoothHeadset: Proxy object disconnected
,08-25 21:50:29.202  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 21:50:29.202  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-25 21:50:29.202  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-25 21:50:29.203  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-25 21:50:29.205  3940  3940 D A2dpService: Received stop request...Stopping profile...
,08-25 21:50:29.206  3940  4121 D A2dpStateMachine: Exit Disconnected: -1
08-25 21:50:29.207  3940  3940 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 21:50:29.209  3940  3940 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 21:50:29.210  3940  3940 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 21:50:29.210  3940  3940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13a01d75
08-25 21:50:29.210  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-25 21:50:29.210  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 21:50:29.211  3940  3940 D HeadsetStateMachine: Unbinding service...
08-25 21:50:29.212  3940  3940 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 21:50:29.212  3940  3940 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-25 21:50:29.212  3940  3940 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 21:50:29.212  3940  3940 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 21:50:29.212  3940  3940 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 21:50:29.212  3940  3940 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 21:50:29.212  3940  3940 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 21:50:29.212  3940  3940 D HidService: Received stop request...Stopping profile...
08-25 21:50:29.212  3940  3940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13a01d75
08-25 21:50:29.213  3940  4029 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 21:50:29.215  3940  3940 D HealthService: Received stop request...Stopping profile...
08-25 21:50:29.215  6975  6975 D BluetoothInputDevice: Proxy object disconnected
08-25 21:50:29.215  3940  3940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13a01d75
08-25 21:50:29.216  6975  6975 D HidProfile: Bluetooth service disconnected
08-25 21:50:29.217  3940  3940 D PanService: Received stop request...Stopping profile...
08-25 21:50:29.217  3940  3940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13a01d75
08-25 21:50:29.218  3940  3940 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 21:50:29.219  3940  3940 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 21:50:29.219  3940  3940 D BtGatt.GattService: stop()
08-25 21:50:29.219  6975  6975 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 21:50:29.219  6975  6975 D PanProfile: Bluetooth service disconnected
08-25 21:50:29.219  3940  3940 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 21:50:29.220  3940  3940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13a01d75
08-25 21:50:29.221  3940  3940 D BluetoothMapService: Received stop request...Stopping profile...
08-25 21:50:29.221  3940  3940 D BluetoothMapService: stop()
08-25 21:50:29.221  3940  3940 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 21:50:29.222  3940  3940 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 21:50:29.222  3940  3940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13a01d75
08-25 21:50:29.223  3940  3940 I BluetoothA2dpServiceJni: cleanupNative
08-25 21:50:29.223  3940  4122 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 21:50:29.224  3940  3940 I GKI_LINUX: GKI_exit_task 2 done
08-25 21:50:29.224  3940  3940 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 21:50:29.224  6975  6975 D BluetoothMap: Proxy object disconnected
08-25 21:50:29.224  3940  3940 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 21:50:29.224  3940  3940 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 21:50:29.225  3940  3940 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-25 21:50:29.225  3940  3940 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 21:50:29.225  3940  3940 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 21:50:29.225  3940  3940 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 21:50:29.225  3940  3940 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 21:50:29.226  3940  3940 V BluetoothMapService: Handler(): got msg=4
08-25 21:50:29.226  3940  3940 D BluetoothMapService: MAP Service closeService in
08-25 21:50:29.226  3940  3940 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 21:50:29.226  3940  3940 V BluetoothMapService: MAP Service closeService out
08-25 21:50:29.227  3940  4029 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 21:50:29.227  3940  4029 D BluetoothAdapterProperties: Setting state to 10
08-25 21:50:29.227  3940  4029 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 21:50:29.227  3940  3940 D BluetoothMapService: cleanup()
08-25 21:50:29.227  3940  3940 D BluetoothMapService: MAP Service closeService in
08-25 21:50:29.227  3940  3940 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 21:50:29.227  3940  3940 V BluetoothMapService: MAP Service closeService out
08-25 21:50:29.228  1034  1096 D BluetoothManagerService: Message: 60
08-25 21:50:29.228  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 21:50:29.228  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-25 21:50:29.228  3940  4029 I BluetoothAdapterState: Entering OffState
08-25 21:50:29.228  6975  6992 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 21:50:29.230  6975  6991 D BluetoothMap: onBluetoothStateChange: up=false
08-25 21:50:29.230  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 21:50:29.231  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:50:29.231  1851  3552 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:50:29.231  6975  6975 D MapProfile: Bluetooth service disconnected
08-25 21:50:29.232  1851  2395 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:50:29.232  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:50:29.233  6975  6992 D BluetoothPan: onBluetoothStateChange on: false
08-25 21:50:29.233  6975  6991 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 21:50:29.235  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 21:50:29.235  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 21:50:29.237  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 21:50:29.237  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 21:50:29.237  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@227a92ab mBinding = false
08-25 21:50:29.238  1034  1096 D BluetoothManagerService: Sending unbind request.
08-25 21:50:29.239  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 21:50:29.242  6975  6975 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 21:50:29.243  6975  6975 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-25 21:50:29.243  6975  6975 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 21:50:29.244  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:29.244  1942  2137 D LGBluetoothAPIService: Message: 2
08-25 21:50:29.244  1942  2137 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1b14fdfc mBinding = false
08-25 21:50:29.244  1942  2137 D LGBluetoothAPIService: Sending unbind request.
08-25 21:50:29.246  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 21:50:29.247  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:29.248  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:29.252  6975  6975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 21:50:29.257  1600  1600 D BluetoothAdapter: 327454893: getState() :  mService = null. Returning STATE_OFF
08-25 21:50:29.257  1600  1600 D BluetoothAdapter: 327454893: getState() :  mService = null. Returning STATE_OFF
,08-25 21:50:29.258  3940  4037 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 21:50:29.258  3940  3940 I GKI_LINUX: GKI_exit_task 1 done
08-25 21:50:29.258  3940  3940 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 21:50:29.259  3940  3940 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 21:50:29.259  3940  3940 I art     : --- WEIRD: removing null entry 246
08-25 21:50:29.259  3940  3940 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-25 21:50:29.259  3940  3940 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 21:50:29.260  3940  3940 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 21:50:29.261  6975  6975 D DockEventReceiver: finishStartingService: stopping service
08-25 21:50:29.262  3940  3940 I art     : System.exit called, status: 0
08-25 21:50:29.262  3940  3940 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 21:50:29.281  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 21:50:29.284  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 21:50:29.285   310  1754 V AudioFlinger: 3940 died, releasing its sessions
08-25 21:50:29.286   310  1754 V AudioFlinger:  pid 1851 @ 0
08-25 21:50:29.286   310  1754 V AudioFlinger:  pid 3460 @ 1
08-25 21:50:29.286   310  1754 V AudioFlinger:  pid 3460 @ 2
08-25 21:50:29.290  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:29.291  6975  6975 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-25 21:50:29.323  1034  2033 I ActivityManager: Process com.android.bluetooth (pid 3940) has died
08-25 21:50:29.324  1034  2033 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-25 21:50:29.332  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 21:50:29.339  7065  7087 W FormManager: Network not available. Please check & try again.
,08-25 21:50:29.349  7065  7088 V FormManager: Network unavailable.
08-25 21:50:29.355  6975  6975 D BluetoothPermissionRequest: onReceive
,08-25 21:50:29.360  6975  6975 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 21:50:29.360  6975  6975 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 21:50:29.361  7065  7088 V FormManager: Network unavailable.
08-25 21:50:29.364  6975  6975 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 21:50:29.433  1034  1051 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7094 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-25 21:50:29.448  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-25 21:50:29.449  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 21:50:29.449  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-25 21:50:29.450  6975  6975 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 21:50:29.451  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 21:50:29.474  6975  6975 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 21:50:29.475  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 21:50:29.475  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 21:50:29.475  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 21:50:29.475  6975  6975 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 21:50:29.475  6975  6975 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-25 21:50:29.480  1034  1922 I ActivityManager: Killing 6175:com.android.contacts/u0a19 (adj 15): empty #17
,08-25 21:50:29.558  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 21:50:29.559  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 21:50:29.560  1034  1730 W libprocessgroup: failed to open /acct/uid_10019/pid_6175/cgroup.procs: No such file or directory
08-25 21:50:29.570  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 21:50:29.586  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 21:50:29.596  4386  7116 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 21:50:29.601  6997  6997 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 21:50:29.601  6997  6997 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 21:50:29.602  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:29.603  7094  7094 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 21:50:29.604  7094  7094 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 21:50:29.604  7094  7094 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-25 21:50:29.605  7094  7094 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 21:50:29.606  4386  7117 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 21:50:29.606  4386  7117 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 21:50:29.607  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:50:29.619  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:29.628  7065  7119 W FormManager: Network not available. Please check & try again.
08-25 21:50:29.631  7094  7094 D BluetoothAdapterApp: Loading JNI Library
,08-25 21:50:29.641  7025  7025 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 21:50:29.641  7065  7120 V FormManager: Network unavailable.
08-25 21:50:29.642  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 21:50:29.642  7025  7025 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 21:50:29.646  7065  7120 V FormManager: Network unavailable.
,08-25 21:50:29.667  7094  7094 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3214cdb2 Instance Count = 1
,08-25 21:50:29.673  7094  7094 D BluetoothAdapterApp: onCreate
08-25 21:50:29.697  7025  7025 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:29.697  7025  7025 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 21:50:29.705  7025  7025 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 21:50:29.706  7025  7025 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
08-25 21:50:29.706  7025  7025 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
08-25 21:50:29.706  7025  7025 V SoundPool: doLoad: loading sample sampleID=1
08-25 21:50:29.707  7025  7129 V SoundPool: Start decode
08-25 21:50:29.707  7025  7129 V MediaPlayer[Native]: decode(30, 10857164, 17813)
08-25 21:50:29.707  7025  7025 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 21:50:29.708   310  1382 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 21:50:29.708   310  1382 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 21:50:29.708   310  1382 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 21:50:29.708   310  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 21:50:29.708   310  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 21:50:29.708   310  1382 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 21:50:29.708   310  1382 V MediaPlayerService: player type = 3
,08-25 21:50:29.708   310  1382 V AwesomePlayer: AwesomePlayer create()
08-25 21:50:29.709   310  1382 V AwesomePlayer: reset_l() 
08-25 21:50:29.709   310  1382 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:29.709   310  1382 V AwesomePlayer: setAudioSink() 
08-25 21:50:29.709   310  1382 V AwesomePlayer: reset_l() 
08-25 21:50:29.709   310  1382 V AudioCache: notify(0xb0409540, 8, 0, 0)
08-25 21:50:29.709   310  1382 V AudioCache: ignored
08-25 21:50:29.709   310  1382 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:29.709   310  1382 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 21:50:29.709   310  1382 V AwesomePlayer: setDataSource_l dataSource
08-25 21:50:29.709   310  1382 V LGParserOSAL: SniffLGParser start
08-25 21:50:29.709  7094  7094 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 21:50:29.709   310  1382 V LGParserOSAL: MainType:5, SubType=0
08-25 21:50:29.709   310  1382 V LGParserOSAL: #### check Mime : application/ogg
08-25 21:50:29.709   310  1382 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 21:50:29.709   310  1382 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 21:50:29.710  7094  7094 D ProfileConfigQcom: Adding HeadsetService
08-25 21:50:29.710  7094  7094 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 21:50:29.710  7094  7094 D ProfileConfigQcom: Adding A2dpService
08-25 21:50:29.710  7094  7094 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 21:50:29.710  7094  7094 D ProfileConfigQcom: Adding HidService
08-25 21:50:29.711  7094  7094 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 21:50:29.712  7094  7094 D ProfileConfigQcom: Adding HealthService
,08-25 21:50:29.712  7094  7094 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 21:50:29.713  7094  7094 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 21:50:29.713  7094  7094 D ProfileConfigQcom: Adding PanService
08-25 21:50:29.714  7094  7094 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 21:50:29.714  6789  6789 D UEI.SmartControl: QS Service created
08-25 21:50:29.714  7094  7094 D ProfileConfigQcom: Adding GattService
08-25 21:50:29.714  7094  7094 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 21:50:29.714  7094  7094 D ProfileConfigQcom: Adding BluetoothMapService
08-25 21:50:29.714  7094  7094 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 21:50:29.716  7094  7094 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 21:50:29.720  6975  6975 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 21:50:29.720  7025  7025 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 21:50:29.722  7025  7025 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 21:50:29.722  7094  7094 V LGMDMManagerInternal: Create singleton instance
08-25 21:50:29.722  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 21:50:29.731  6789  6789 I UEI.SmartControl: Service initServices...
08-25 21:50:29.731  6789  6789 D UEI.SmartControl: QS start get config
,08-25 21:50:29.735  7025  7025 V LGMDMManager: Create singleton instance
08-25 21:50:29.758   310  1382 V LGParserOSAL: supported mime: application/ogg
08-25 21:50:29.758   310  1382 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 21:50:29.758   310  1382 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 21:50:29.758   310  1382 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 21:50:29.758   310  1382 V AwesomePlayer: AudioTrack Setting
08-25 21:50:29.758   310  1382 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 21:50:29.758   310  1382 V AwesomePlayer: setAudioSource() 
08-25 21:50:29.758   310  1382 V MediaPlayerService: prepare
08-25 21:50:29.758   310  1382 V AwesomePlayer: prepareAsync_l() 
08-25 21:50:29.759   310  1382 V MediaPlayerService: wait for prepare
08-25 21:50:29.759   310  7131 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 21:50:29.759   310  7131 V AwesomePlayer: initAudioDecoder() 
08-25 21:50:29.759   310  7131 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 21:50:29.759   310  7131 V AudioSystem: isOffloadSupported()
08-25 21:50:29.759   310  7131 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 21:50:29.759   310  7131 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 21:50:29.759   310  7131 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 21:50:29.759   310  7131 V AwesomePlayer: getUseOffload() = 0 
08-25 21:50:29.759   310  7131 V OMXCodec: OMXCodec::Create
08-25 21:50:29.759   310  7131 V OMXCodec: findMatchingCodecs()
08-25 21:50:29.759   310  7131 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 21:50:29.759   310  7131 V OMXCodec: matchingCodecs.size()=1
08-25 21:50:29.759   310  7131 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 21:50:29.760   310  7131 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 21:50:29.760   310  7131 V LGCodecAdapter: LG Codec Adapter start
08-25 21:50:29.760   310  7131 V OMXCodec: OMXCodec Createtor
08-25 21:50:29.760   310  7131 V OMXCodec: setComponentRole
08-25 21:50:29.760   310  7131 V OMXCodec: configureCodec protected=0
08-25 21:50:29.760   310  7131 V LGCodecAdapter: called getLGCodecSpecificData
08-25 21:50:29.760   310  7131 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 21:50:29.760   310  7131 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 21:50:29.760   310  7131 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 21:50:29.760   310  7131 V LGCodecOSAL: Not support LGCodec
08-25 21:50:29.760   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 21:50:29.760   310  7131 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 21:50:29.760   310  7131 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 21:50:29.760   310  7131 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 21:50:29.760   310  7131 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 21:50:29.760   310  7131 V AudioSystem: isOffloadSupported()
08-25 21:50:29.760   310  7131 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 21:50:29.760   310  7131 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 21:50:29.760   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 21:50:29.760   310  7131 V OMXCodec: init()
,08-25 21:50:29.760   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 21:50:29.760   310  7131 V OMXCodec: allocateBuffers
08-25 21:50:29.760   310  7131 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 21:50:29.760   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 21:50:29.761   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-25 21:50:29.761   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-25 21:50:29.761   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-25 21:50:29.761   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-25 21:50:29.761   310  7131 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 21:50:29.761   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 21:50:29.761   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-25 21:50:29.761   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-25 21:50:29.761   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 21:50:29.761   310  7131 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
08-25 21:50:29.761   310  7131 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 21:50:29.763   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 21:50:29.763   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 21:50:29.764   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 21:50:29.764   310  7131 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 21:50:29.764   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 21:50:29.764   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 21:50:29.764   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 21:50:29.764   310  7131 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 21:50:29.764   310  7131 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 21:50:29.764   310  7131 V AudioCache: notify(0xb0409540, 5, 0, 0)
08-25 21:50:29.764   310  7131 V AudioCache: ignored
08-25 21:50:29.764   310  7131 V AudioCache: notify(0xb0409540, 1, 0, 0)
08-25 21:50:29.764   310  7131 V AudioCache: prepared
08-25 21:50:29.764   310  1382 V AudioCache: wait - success
08-25 21:50:29.764   310  1382 V MediaPlayerService: start
08-25 21:50:29.764   310  1382 V AwesomePlayer: play_l() 
08-25 21:50:29.764   310  1382 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 21:50:29.764   310  1382 V AwesomePlayer: createAudioPlayer_l
08-25 21:50:29.764   310  1382 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 21:50:29.764   310  1382 V AwesomePlayer: startAudioPlayer_l() 
,08-25 21:50:29.764   310  1382 D AudioPlayer: start of Playback, useOffload 0
08-25 21:50:29.764   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 21:50:29.764   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 21:50:29.765   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 21:50:29.765   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 21:50:29.765   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
,08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 21:50:29.766   310  7133 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14341a0 on output port
08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-25 21:50:29.766   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 21:50:29.767   310  1382 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 21:50:29.767   310  1382 V AudioCache: notify(0xb0409540, 6, 0, 0)
08-25 21:50:29.767   310  1382 V AudioCache: ignored
08-25 21:50:29.768   310  1382 V MediaPlayerService: wait for playback complete
,08-25 21:50:29.768   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.768   310  7134 V AudioCache: memcpy(0xaf006000, 0xb57c6000, 4096)
08-25 21:50:29.770   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.770   310  7134 V AudioCache: memcpy(0xaf007000, 0xb57c6000, 4096)
08-25 21:50:29.770   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.770   310  7134 V AudioCache: memcpy(0xaf008000, 0xb57c6000, 4096)
08-25 21:50:29.771   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.771   310  7134 V AudioCache: memcpy(0xaf009000, 0xb57c6000, 4096)
08-25 21:50:29.771   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.771   310  7134 V AudioCache: memcpy(0xaf00a000, 0xb57c6000, 4096)
08-25 21:50:29.771   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.771   310  7134 V AudioCache: memcpy(0xaf00b000, 0xb57c6000, 4096)
08-25 21:50:29.772   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.772   310  7134 V AudioCache: memcpy(0xaf00c000, 0xb57c6000, 4096)
08-25 21:50:29.772   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.772   310  7134 V AudioCache: memcpy(0xaf00d000, 0xb57c6000, 4096)
08-25 21:50:29.773   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.773   310  7134 V AudioCache: memcpy(0xaf00e000, 0xb57c6000, 4096)
08-25 21:50:29.773   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.773   310  7134 V AudioCache: memcpy(0xaf00f000, 0xb57c6000, 4096)
08-25 21:50:29.773   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.773   310  7134 V AudioCache: memcpy(0xaf010000, 0xb57c6000, 4096)
08-25 21:50:29.774   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.774   310  7134 V AudioCache: memcpy(0xaf011000, 0xb57c6000, 4096)
08-25 21:50:29.774   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.774   310  7134 V AudioCache: memcpy(0xaf012000, 0xb57c6000, 4096)
08-25 21:50:29.775   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.775   310  7134 V AudioCache: memcpy(0xaf013000, 0xb57c6000, 4096)
08-25 21:50:29.775   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.775   310  7134 V AudioCache: memcpy(0xaf014000, 0xb57c6000, 4096)
08-25 21:50:29.776   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.776   310  7134 V AudioCache: memcpy(0xaf015000, 0xb57c6000, 4096)
08-25 21:50:29.776   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.776   310  7134 V AudioCache: memcpy(0xaf016000, 0xb57c6000, 4096)
,08-25 21:50:29.777   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.777   310  7134 V AudioCache: memcpy(0xaf017000, 0xb57c6000, 4096)
08-25 21:50:29.777   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.777   310  7134 V AudioCache: memcpy(0xaf018000, 0xb57c6000, 4096)
08-25 21:50:29.777   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.778   310  7134 V AudioCache: memcpy(0xaf019000, 0xb57c6000, 4096)
08-25 21:50:29.778   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.778   310  7134 V AudioCache: memcpy(0xaf01a000, 0xb57c6000, 4096)
08-25 21:50:29.778   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.778   310  7134 V AudioCache: memcpy(0xaf01b000, 0xb57c6000, 4096)
08-25 21:50:29.779   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.779   310  7134 V AudioCache: memcpy(0xaf01c000, 0xb57c6000, 4096)
08-25 21:50:29.779   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.779   310  7134 V AudioCache: memcpy(0xaf01d000, 0xb57c6000, 4096)
08-25 21:50:29.779   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.779   310  7134 V AudioCache: memcpy(0xaf01e000, 0xb57c6000, 4096)
08-25 21:50:29.779   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.779   310  7134 V AudioCache: memcpy(0xaf01f000, 0xb57c6000, 4096)
08-25 21:50:29.780   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.780   310  7134 V AudioCache: memcpy(0xaf020000, 0xb57c6000, 4096)
08-25 21:50:29.780   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.780   310  7134 V AudioCache: memcpy(0xaf021000, 0xb57c6000, 4096)
08-25 21:50:29.780   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.780   310  7134 V AudioCache: memcpy(0xaf022000, 0xb57c6000, 4096)
08-25 21:50:29.780   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.780   310  7134 V AudioCache: memcpy(0xaf023000, 0xb57c6000, 4096)
08-25 21:50:29.782   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.782   310  7134 V AudioCache: memcpy(0xaf024000, 0xb57c6000, 4096)
08-25 21:50:29.782   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.782   310  7134 V AudioCache: memcpy(0xaf025000, 0xb57c6000, 4096)
08-25 21:50:29.782   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.782   310  7134 V AudioCache: memcpy(0xaf026000, 0xb57c6000, 4096)
08-25 21:50:29.782   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.782   310  7134 V AudioCache: memcpy(0xaf027000, 0xb57c6000, 4096)
08-25 21:50:29.783   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.783   310  7134 V AudioCache: memcpy(0xaf028000, 0xb57c6000, 4096)
08-25 21:50:29.783   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.783   310  7134 V AudioCache: memcpy(0xaf029000, 0xb57c6000, 4096)
08-25 21:50:29.783   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.783   310  7134 V AudioCache: memcpy(0xaf02a000, 0xb57c6000, 4096)
08-25 21:50:29.783   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.783   310  7134 V AudioCache: memcpy(0xaf02b000, 0xb57c6000, 4096)
08-25 21:50:29.784   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.784   310  7134 V AudioCache: memcpy(0xaf02c000, 0xb57c6000, 4096)
08-25 21:50:29.784   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.784   310  7134 V AudioCache: memcpy(0xaf02d000, 0xb57c6000, 4096)
08-25 21:50:29.785   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.785   310  7134 V AudioCache: memcpy(0xaf02e000, 0xb57c6000, 4096)
08-25 21:50:29.785   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.785   310  7134 V AudioCache: memcpy(0xaf02f000, 0xb57c6000, 4096)
,08-25 21:50:29.786   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.786   310  7134 V AudioCache: memcpy(0xaf030000, 0xb57c6000, 4096)
08-25 21:50:29.786   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.786   310  7134 V AudioCache: memcpy(0xaf031000, 0xb57c6000, 4096)
08-25 21:50:29.786   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.786   310  7134 V AudioCache: memcpy(0xaf032000, 0xb57c6000, 4096)
08-25 21:50:29.787   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.787   310  7134 V AudioCache: memcpy(0xaf033000, 0xb57c6000, 4096)
08-25 21:50:29.787   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.787   310  7134 V AudioCache: memcpy(0xaf034000, 0xb57c6000, 4096)
08-25 21:50:29.787   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.787   310  7134 V AudioCache: memcpy(0xaf035000, 0xb57c6000, 4096)
08-25 21:50:29.788   310  7134 V AudioCache: write(0xb57c6000, 4096)
,08-25 21:50:29.788   310  7134 V AudioCache: memcpy(0xaf036000, 0xb57c6000, 4096)
08-25 21:50:29.788   310  7134 V AudioCache: write(0xb57c6000, 4096)
08-25 21:50:29.788   310  7134 V AudioCache: memcpy(0xaf037000, 0xb57c6000, 4096)
08-25 21:50:29.788   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 21:50:29.788   310  7134 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 21:50:29.788   310  7134 V AwesomePlayer: postAudioEOS() 
08-25 21:50:29.789   310  7134 V AudioCache: write(0xb57c6000, 280)
08-25 21:50:29.789   310  7134 V AudioCache: memcpy(0xaf038000, 0xb57c6000, 280)
08-25 21:50:29.790   310  7131 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 21:50:29.790   310  7131 V AwesomePlayer: onStreamDone
08-25 21:50:29.790   310  7131 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 21:50:29.790   310  7131 V AudioCache: notify(0xb0409540, 2, 0, 0)
08-25 21:50:29.790   310  7131 V AudioCache: playback complete
08-25 21:50:29.790   310  7131 V AwesomePlayer: pause_l() 
08-25 21:50:29.790   310  7131 V AudioCache: notify(0xb0409540, 7, 0, 0)
08-25 21:50:29.790   310  7131 V AudioCache: ignored
08-25 21:50:29.790   310  7131 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:29.790   310  1382 V AudioCache: wait - success
08-25 21:50:29.791   310  1382 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 21:50:29.791   310  7131 D AudioPlayer: Pause Playback at 1068125
08-25 21:50:29.791   310  1382 V AwesomePlayer: reset_l() 
08-25 21:50:29.791   310  1382 V AudioCache: notify(0xb0409540, 8, 0, 0)
08-25 21:50:29.791   310  1382 V AudioCache: ignored
08-25 21:50:29.791   310  1382 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:29.791   310  1382 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 21:50:29.791   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 21:50:29.791   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 21:50:29.791   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 21:50:29.791   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
,08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14341a0 on port 1
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:29.792   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 21:50:29.793   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 21:50:29.793   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 21:50:29.793   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 21:50:29.793   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 21:50:29.793   310  7133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 21:50:29.793   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 21:50:29.793   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 21:50:29.793   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 21:50:29.794   310  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 21:50:29.794   310  1382 D AudioPlayer: AudioPlayer releasing audio source
08-25 21:50:29.794   310  1382 D AudioPlayer: AudioPlayer done releasing audio source
08-25 21:50:29.794   310  1382 V AwesomePlayer: reset_l() 
08-25 21:50:29.794   310  1382 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:29.794   310  1382 V AwesomePlayer: ~AwesomePlayer call
08-25 21:50:29.795   310  1382 V AwesomePlayer: reset_l() 
08-25 21:50:29.795   310  1382 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:29.795  7025  7129 V SoundPool: close(30)
08-25 21:50:29.795  7025  7129 V SoundPool: pointer = 0xa002f000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 21:50:29.800  7094  7094 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:29.802  7094  7094 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 21:50:29.803  7094  7094 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 21:50:29.803  7094  7094 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 21:50:29.804  7094  7094 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:29.805  7094  7094 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-25 21:50:29.812  7045  7045 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 21:50:29.815  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 21:50:29.816  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 21:50:29.818  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2697
,08-25 21:50:30.020  6789  6789 I UEI.SmartControl: Supports setup maps: true
,08-25 21:50:30.023  6789  6789 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 21:50:30.023  6789  6789 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-25 21:50:30.023  6789  6789 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 21:50:30.023  6789  6789 I UEI.SmartControl: ### init IR Blaster...
08-25 21:50:30.026  6789  6789 D serial_port: Configuring serial port
08-25 21:50:30.027  6789  6789 E UEI.SmartControl: UEIBLaster setting for 616
08-25 21:50:30.027  6789  6789 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 21:50:30.027  6789  6789 I UEI.SmartControl: configuring settings for MAXQ616
08-25 21:50:30.027  6789  6789 I UEI.SmartControl: Get version...
08-25 21:50:30.046  6789  7136 D UEI.SmartControl: serial port data available: 21
,08-25 21:50:30.072  6789  6789 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-25 21:50:30.072  6789  6789 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 21:50:30.072  6789  6789 I UEI.SmartControl: QS saving settings...
08-25 21:50:30.075  6789  6789 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 21:50:30.093  6789  7136 D UEI.SmartControl: serial port data available: 4
,08-25 21:50:30.127  6789  7142 I UEI.SmartControl: Device manager: loading config....
,08-25 21:50:30.129  6789  6789 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 21:50:30.131  6789  7142 D UEI.SmartControl: ----------- loading internal config...
08-25 21:50:30.134  6789  6789 E UEI.SmartControl: Services init done
08-25 21:50:30.134  6789  6789 D UEI.SmartControl: QS Service init finished
,08-25 21:50:30.136  6789  6789 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 21:50:30.137  6789  6789 D UEI.SmartControl: QS Service version code: 201091
08-25 21:50:30.137  6789  6789 D UEI.SmartControl: Service requested: Control
08-25 21:50:30.150  6789  6789 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-25 21:50:30.155  7025  7025 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 21:50:30.157  6789  6805 I UEI.SmartControl: ------ IControl API: 11
08-25 21:50:30.157  6789  6805 D UEI.SmartControl: File observer start...
08-25 21:50:30.157  6789  6789 D UEI.SmartControl: Internal service binding...
08-25 21:50:30.158  6789  6805 E UEI.SmartControl: IR Port is disabled: false
08-25 21:50:30.158  6789  6805 D UEI.SmartControl: Starting file observer...
08-25 21:50:30.158  6789  7142 E UEI.SmartControl: Loading SETTINGS...
08-25 21:50:30.158  6789  6805 I UEI.SmartControl: Registering callback...
08-25 21:50:30.158  6789  6804 I UEI.SmartControl: ------ IControl API: 19
08-25 21:50:30.160  6789  6804 I UEI.SmartControl: Registering Services Ready callback...
08-25 21:50:30.166  6789  7142 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-25 21:50:30.171  6789  7141 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 21:50:30.171  6789  7141 D UEI.SmartControl: -----service ready thread exits
08-25 21:50:30.171  7025  7043 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 21:50:30.173  7025  7127 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 21:50:30.173  7025  7127 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 21:50:30.174  7025  7025 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 21:50:30.174  7025  7025 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 21:50:30.175  6789  6805 I UEI.SmartControl: ------ IControl API: 8
08-25 21:50:30.176  7025  7025 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 21:50:30.177  7025  7025 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 21:50:30.177  7025  7025 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 21:50:30.177  7025  7025 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 21:50:30.178  7025  7025 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 21:50:30.178  7025  7025 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-25 21:50:30.182  7025  7025 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 21:50:30.183  7025  7025 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 21:50:30.184  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 21:50:30.185  7025  7025 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 21:50:30.185  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 21:50:30.186  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 21:50:30.187  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-25 21:50:30.188  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 21:50:30.189  7025  7025 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472154630188]
08-25 21:50:30.193  7025  7025 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-25 21:50:30.194  1034  2031 I ActivityManager: Killing 6196:com.android.gallery3d/u0a27 (adj 15): empty #17
08-25 21:50:30.217  7025  7147 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-25 21:50:30.234  1034  2031 I ActivityManager: Killing 6646:com.lge.email/u0a23 (adj 15): empty #18
,08-25 21:50:30.264  1034  1977 W libprocessgroup: failed to open /acct/uid_10027/pid_6196/cgroup.procs: No such file or directory
,08-25 21:50:30.269  1034  1923 W libprocessgroup: failed to open /acct/uid_10023/pid_6646/cgroup.procs: No such file or directory
08-25 21:50:30.276  7025  7025 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-25 21:50:30.277  7025  7025 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 21:50:30.277  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-25 21:50:30.278  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 21:50:30.278  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 21:50:30.278  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 21:50:30.279  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-25 21:50:30.290  7025  7025 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-25 21:50:31.123  1034  1922 D WifiServiceImplEx: setWifiEnabled: true pid=6856, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-25 21:50:31.132  1034  1922 D WifiService: setWifiEnabled: true pid=6856, uid=10118
08-25 21:50:31.132  1034  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 21:50:31.153  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 21:50:31.153  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-25 21:50:31.156  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 21:50:31.158  1034  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 21:50:31.158  1034  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 21:50:31.160  1034  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 21:50:31.160  1034  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 21:50:31.160  1034  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 21:50:31.161  1034  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 21:50:31.161  1034  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 21:50:31.161  1034  1536 E WifiHW  : unknown target_country: EU , set to default
08-25 21:50:31.161  1034  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 21:50:31.161  1034  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 21:50:31.161  1034  1536 I WifiUtil: gEnableBmps=1
08-25 21:50:31.206  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:31.226  1034  1096 D Tethering: MasterInitialState.processMessage what=3
,08-25 21:50:31.240  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:31.245  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:31.247  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:31.247  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:31.249  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 21:50:31.252  6571  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 21:50:31.264  1034  1096 D Tethering: MasterInitialState.processMessage what=3
,08-25 21:50:31.274  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:31.277  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:31.282  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 21:50:31.292  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 21:50:31.321  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:31.365  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:31.409  1034  1904 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7166 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 21:50:31.417  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:31.418  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 21:50:31.508  7166  7166 I AppUp4:AppBoxCP: onCreate
08-25 21:50:31.509  7166  7166 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-25 21:50:31.520  7166  7166 I AppUp4:DB:  setFingerPrint start
08-25 21:50:31.520  7166  7166 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-25 21:50:31.529  7166  7166 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-25 21:50:31.529  7166  7166 I AppUp4:DB:  SDK version = 21
08-25 21:50:31.529  7166  7166 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-25 21:50:31.531  7166  7166 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-25 21:50:31.533  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 21:50:31.533  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:31.535  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 21:50:31.536  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 21:50:31.542  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 21:50:31.587  7166  7166 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:31.587  7166  7166 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 21:50:31.599  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@53aacac
08-25 21:50:31.600  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 21:50:31.600  7166  7166 D AppUp4:CustFacade: isPhone : true
08-25 21:50:31.601  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-25 21:50:31.602  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-25 21:50:31.603  7166  7166 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-25 21:50:31.604  7166  7185 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-25 21:50:31.605  7166  7185 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,08-25 21:50:31.605  7166  7185 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-25 21:50:31.609  1034  1904 I ActivityManager: Killing 6696:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-25 21:50:31.668  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:31.668  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 21:50:31.670  1034  1923 W libprocessgroup: failed to open /acct/uid_10061/pid_6696/cgroup.procs: No such file or directory
,08-25 21:50:31.679  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:31.684  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:31.701  4386  7192 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 21:50:31.701  4386  7193 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:31.702  4386  7193 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 21:50:31.762  1034  2031 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7199 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 21:50:31.826  7199  7199 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 21:50:31.827  7199  7199 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 21:50:31.829  7199  7199 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-25 21:50:31.829  7199  7199 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 21:50:31.923  7199  7199 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 21:50:31.935  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 21:50:31.935  1034  1096 D Tethering: InitialState.processMessage what=4
08-25 21:50:31.939  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 21:50:31.943   304   894 D SoftapController: Softap fwReload - Ok
08-25 21:50:31.943  1034  1536 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (777ms)
08-25 21:50:31.947   304   894 D CommandListener: Setting iface cfg
08-25 21:50:31.947  7199  7199 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-25 21:50:31.947   304   894 D CommandListener: Trying to bring down wlan0
,08-25 21:50:31.954  1034  1423 D PowerManagerServiceEx: acquireWakeLockInternal: lock=390834456, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
08-25 21:50:31.955  1034  1423 V AlarmManager: ELAPSED_WAKEUP set : Alarm{36a9e7f3 type 2 when 188531 com.google.android.gms} when 188531
08-25 21:50:31.959   304   894 D CommandListener: Clearing all IP addresses on wlan0
08-25 21:50:31.961  1034  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-25 21:50:31.961  7219  7219 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:31.961  7219  7219 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:31.987  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,08-25 21:50:31.989  7219  7219 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 21:50:32.023  7219  7219 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 21:50:32.023  7219  7219 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 21:50:32.029  7199  7199 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 21:50:32.059  7199  7199 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 21:50:32.059  7199  7199 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 21:50:32.061  1034  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 21:50:32.061  1034  1536 E WifiStateMachine: useWiFiOffloading() : false
08-25 21:50:32.061  1034  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 21:50:32.061  1034  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-25 21:50:32.062  1034  1536 D WifiMonitor: connecting to supplicant
,08-25 21:50:32.063  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:32.066  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 21:50:32.072  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:32.074  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:32.076  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-25 21:50:32.103  7219  7219 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 21:50:32.146  7219  7219 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 21:50:32.151  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-25 21:50:32.152  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 21:50:32.153  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 21:50:32.153  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 21:50:32.154  1034  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 21:50:32.154  1034  7228 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 21:50:32.154  1034  7228 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 21:50:32.154  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-25 21:50:32.154  1034  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:32.155  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:32.155  1034  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:32.156  1034  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 21:50:32.156  1034  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 21:50:32.157  1034  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 21:50:32.157  1034  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 21:50:32.157  1034  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 21:50:32.157  1034  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 21:50:32.157  1034  1536 E WifiStateMachine: useWiFiOffloading() : false
08-25 21:50:32.157  1034  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 21:50:32.158  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.158  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.158  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.158  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.158  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 21:50:32.159  1034  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 21:50:32.160  1034  1536 D WifiNative-wlan0: SET update_config 1: returned true
08-25 21:50:32.160  1034  1536 D WifiConfigStore: Loading config and enabling all networks 
08-25 21:50:32.160  1034  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 21:50:32.160  1034  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	,NG700	any	
08-25 21:50:32.161  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:32.164  1942  1942 D WfdService: Waiting for WifiP2p enabling
,08-25 21:50:32.164  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 21:50:32.165  1034  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 21:50:32.165  7219  7219 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-25 21:50:32.165  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 21:50:32.165  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 21:50:32.165  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,08-25 21:50:32.165  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 21:50:32.165  1034  7228 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 21:50:32.166  1034  7228 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-25 21:50:32.166  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:32.167  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:32.167  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:32.167  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,08-25 21:50:32.167  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:32.167  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:32.167  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:32.167  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
,08-25 21:50:32.167  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:32.167  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:32.167  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:32.168  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:50:32.168  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:32.168  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:32.168  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:32.168  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:32.168  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:32.168  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:32.168  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:32.168  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:50:32.168  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:32.168  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:32.168  1034  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 21:50:32.178  1034  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 21:50:32.179  1034  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 21:50:32.179  1034  1536 D WifiStateMachine: enableVerboseLogging : level 2
08-25 21:50:32.179  1034  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-25 21:50:32.180  1034  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 21:50:32.180  1034  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-25 21:50:32.180  1034  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 21:50:32.181  1034  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 21:50:32.181  1034  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 21:50:32.181  1034  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 21:50:32.181  1034  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 21:50:32.181  1034  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 21:50:32.182  1034  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 21:50:32.182  1034  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 21:50:32.182  1034  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 21:50:32.182  1034  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 21:50:32.183  1034  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 21:50:32.185  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-25 21:50:32.185  1034  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 21:50:32.185  1034  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 21:50:32.186  1942  2341 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 21:50:32.186  1034  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 21:50:32.186  1942  2341 D WfdsService: Set the WFDS Monitor: true
08-25 21:50:32.186  1034  1536 D WifiNative-HAL: Setting external_sim to 1
08-25 21:50:32.186  1942  2341 D WfdsMonitor: WfdsMonitorThread create
08-25 21:50:32.186  1942  2341 D WfdsMonitor: WFDS Monitor is created and started
08-25 21:50:32.186  1942  2341 D WfdsService: WiFi: Supplicant connection re-established
08-25 21:50:32.187  1034  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 21:50:32.187  1034  1536 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 21:50:32.187  1034  1536 I WifiNative-HAL: startHal
08-25 21:50:32.187  1034  1536 D wifi    : setting scan oui 0x957a3580
08-25 21:50:32.188  1034  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 21:50:32.188  1942  7229 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 21:50:32.188  1034  1536 I WifiNative-HAL: startHal
08-25 21:50:32.188  1034  1536 D wifi    : setting scan oui 0x957a3580
08-25 21:50:32.188  1034  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 21:50:32.188  1942  7229 E CtrlSupplicant: Succeed to open control connection
08-25 21:50:32.188  1034  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 21:50:32.188  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 21:50:32.188  1942  7229 E CtrlSupplicant: Succeed to open monitor connection
08-25 21:50:32.189  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 21:50:32.189  1942  7229 D WfdsMonitor: Supplicant connection established
08-25 21:50:32.189  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 21:50:32.189  1942  2341 D WfdsService: Connected to the supplicant for wfds
08-25 21:50:32.189  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 21:50:32.190  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 21:50:32.190  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 21:50:32.190  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 21:50:32.190  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 21:50:32.191  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 21:50:32.191  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-25 21:50:32.191  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 21:50:32.191  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 21:50:32.191  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 21:50:32.192  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-25 21:50:32.192  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 21:50:32.192  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 21:50:32.192  7219  7219 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 21:50:32.193  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 21:50:32.193  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 21:50:32.193  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-25 21:50:32.193  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 21:50:32.194  1034  1536 E WifiNative: : [188,777,573 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 21:50:32.194  1034  1536 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 21:50:32.195  1034  1536 D WifiNative-wlan0: RECONNECT: returned true
08-25 21:50:32.195  1034  1536 D WifiNative-wlan0: doString: [STATUS]
08-25 21:50:32.195  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,08-25 21:50:32.195  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 21:50:32.196  1034  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 21:50:32.196  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 21:50:32.196  1034  1536 D WifiNative-wlan0: SET ps 1: returned true
08-25 21:50:32.197  1034  1535 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.198   304   894 D CommandListener: Setting iface cfg
,08-25 21:50:32.198   304   894 D CommandListener: Trying to bring up p2p0
08-25 21:50:32.199  1034  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 21:50:32.199  1034  1535 D LGWifiP2pService: P2pEnablingState
08-25 21:50:32.199  1034  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.199  1034  1535 D LGWifiP2pService: P2p socket connection successful
08-25 21:50:32.199  1034  1535 D LGWifiP2pService: P2pEnabledState
08-25 21:50:32.200  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 21:50:32.200  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 21:50:32.200  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-25 21:50:32.201  1034  1535 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 21:50:32.201  1942  1942 D WfdsService: WifiP2pState is changed : true
08-25 21:50:32.201  1034  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.201  1034  1554 I WifiNative-HAL: startHal
08-25 21:50:32.201  1034  1554 D wifi    : getting scan capabilities on interface[1] = 0x957a3580
08-25 21:50:32.201  1034  1554 D wifi    : failed to get capabilities : -3
08-25 21:50:32.201  1034  1554 E WifiScanningService: could not get scan capabilities
08-25 21:50:32.202  1034  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 21:50:32.202  1034  1555 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.203  1034  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 21:50:32.203  1942  2341 D WfdsService: Receive the WFDS_ENABLE Method
08-25 21:50:32.203  1942  2341 D WfdsService: Set the WFDS Monitor: true
08-25 21:50:32.203  1034  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 21:50:32.203  1942  2341 D WfdsService: Connected to the supplicant for wfds
08-25 21:50:32.203  1942  2341 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 21:50:32.203  7219  7219 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 21:50:32.203  1942  2341 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-25 21:50:32.204  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 21:50:32.204  7219  7219 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-25 21:50:32.204  1942  2341 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-25 21:50:32.204  1034  1535 D WifiNative-p2p0: SET device_name G3: returned true
08-25 21:50:32.204  1942  2341 D WfdsService: selectPreferredScanChannel [36]
08-25 21:50:32.204  1034  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 21:50:32.204  1942  2341 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 21:50:32.204  1034  1535 D LGWifiP2pService: before postfix = G3
08-25 21:50:32.204  1942  1942 D WfdsService: isConnected: false
08-25 21:50:32.204  1034  1535 D WifiServerServiceExt: postfix byte check : 2
08-25 21:50:32.204  1034  1535 D LGWifiP2pService: after postfix = G3
08-25 21:50:32.204  1034  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 21:50:32.205  1034  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 21:50:32.205  1034  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 21:50:32.205  1034  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 21:50:32.205  1034  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 21:50:32.205  1034  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 21:50:32.205  1034  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 21:50:32.206  1034  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 21:50:32.206  1034  1536 E WifiState,Machine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 21:50:32.206  1034  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 21:50:32.206  1034  1535 D WifiNative-HAL: p2pGetDeviceAddress
08-25 21:50:32.206  1034  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 21:50:32.206  1034  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 21:50:32.207  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 21:50:32.207  1034  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 21:50:32.208  1034  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 21:50:32.208  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 21:50:32.208  1034  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 21:50:32.208  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 21:50:32.208  1942  1942 D WfdsService: Update P2p Interface State: 3
08-25 21:50:32.208  1034  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 21:50:32.208  1034  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 21:50:32.209  1034  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 21:50:32.209  1034  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 21:50:32.209  1034  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 21:50:32.209  1034  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 21:50:32.210  1034  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 21:50:32.210  1034  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 21:50:32.211  1034  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 21:50:32.211  1034  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-25 21:50:32.219  7219  7219 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-25 21:50:32.219  1034  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 21:50:32.219  1034  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 21:50:32.219  1034  1535 D LGWifiP2pService: InactiveState
08-25 21:50:32.220  1034  1535 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.220  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.220  1034  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 21:50:32.220  1034  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 21:50:32.220  1034  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 21:50:32.220  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 21:50:32.220  1034  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 21:50:32.221  1034  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 21:50:32.222  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:32.222  1034  7228 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 21:50:32.222  1034  7228 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:32.222  1034  7228 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-25 21:50:32.222  1034  7228 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:32.222  1942  7229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 21:50:32.222  7219  7219 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 21:50:32.222  7219  7219 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 21:50:32.223  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.223  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.223  1034  7228 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:32.224  1034  7228 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.224  1034  7228 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.224  1034  7228 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.224  1942  7229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:32.224  1942  7229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:32.224  1034  7228 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:32.224  1034  7228 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.224  1034  7228 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.224  1034  7228 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-25 21:50:32.225  1034  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 21:50:32.225  1034  1535 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.225  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.225  1034  1535 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.226  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=188809  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 21:50:32.226  1034  1535 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.227  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.227  1034  1535 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.227  1034  1535 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.227  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.227  1034  1535 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.227  1034  1535 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.227  1942  2341 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 21:50:32.227  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.227  1034  1535 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.228  1034  1034 E WifiServerServiceExt: No p2p device connected
08-25 21:50:32.228  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:32.228  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:32.229  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.229  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.229  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 21:50:32.230  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=188814  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 21:50:32.230  1034  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 21:50:32.230  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:32.230  1034  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 21:50:32.231  1034  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 21:50:32.231  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 21:50:32.231  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 21:50:32.232  7219  7219 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:32.232  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=U,SER type=COUNTRY alpha2=CZ]
08-25 21:50:32.232  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:32.232  1034  7228 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:32.232  1034  7228 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:32.233  7219  7219 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 21:50:32.233  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.233  1034  7228 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:32.233  1034  7228 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.233  1942  7229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:32.233  1034  7228 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.233  1034  7228 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.233  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.233  1034  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 21:50:32.234  1034  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 21:50:32.234  1034  7228 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:32.234  1034  7228 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.234  1034  7228 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.234  1034  7228 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:32.234  1034  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 21:50:32.235  1942  7229 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:32.235  1034  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 21:50:32.235  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 21:50:32.235  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 21:50:32.235  7219  7219 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 21:50:32.236  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,08-25 21:50:32.236  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 21:50:32.236  1034  7228 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 21:50:32.236  1034  7228 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 21:50:32.236  1034  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.236  1034  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 21:50:32.236  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:32.236  1034  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 21:50:32.237  1034  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,08-25 21:50:32.237  1034  1536 D WifiNative-wlan0: doBoolean: SCAN
08-25 21:50:32.237  1034  1536 D WifiNative-wlan0: SCAN: returned false
08-25 21:50:32.237  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=188821  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-25 21:50:32.241  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=188825  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 21:50:32.242  1034  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:32.242  1034  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:32.242  1034  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:32.243  1034  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:32.243  1034  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:32.244  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.244  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.244  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 21:50:32.246  7199  7199 I HubEmail: JNI_OnLoad()
08-25 21:50:32.246  7199  7199 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 21:50:32.246  7199  7199 I HubEmail: registerNatives()
08-25 21:50:32.246  7199  7199 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 21:50:32.246  7199  7199 I HubEmail: registerNativeMethods()
08-25 21:50:32.246  7199  7199 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 21:50:32.247  7199  7199 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-25 21:50:32.248  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 21:50:32.248  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:32.248  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 21:50:32.251  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:32.251  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 21:50:32.254  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:32.256  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:32.256  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 21:50:32.257  7199  7235 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.303  1034  1885 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7236 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-25 21:50:32.309  7065  7233 W FormManager: Network not available. Please check & try again.
,08-25 21:50:32.309  7065  7234 V FormManager: Network unavailable.
08-25 21:50:32.312  7065  7234 V FormManager: Network unavailable.
08-25 21:50:32.324  1034  1923 I ActivityManager: Killing 6261:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-25 21:50:32.354  1034  1730 W libprocessgroup: failed to open /acct/uid_10080/pid_6261/cgroup.procs: No such file or directory
,08-25 21:50:32.435  7236  7236 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:32.436  7236  7236 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 21:50:32.440  7236  7236 D PhoneMonitor: Register our PhoneStateListener
,08-25 21:50:32.462  7236  7236 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 21:50:32.466  7236  7236 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 21:50:32.497  7236  7236 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-25 21:50:32.499  7236  7236 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 21:50:32.500  7236  7236 D TelephonyAutoProfiling: [parse] Load xml
08-25 21:50:32.507  7236  7236 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-25 21:50:32.507  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-25 21:50:32.507  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-25 21:50:32.507  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 21:50:32.508  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 21:50:32.509  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 21:50:32.509  7236  7236 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 21:50:32.509  7236  7236 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-25 21:50:32.536  1034  1730 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7255 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 21:50:32.536  7236  7236 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-25 21:50:32.536  1034  1730 I ActivityManager: Killing 6039:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-25 21:50:32.585  1034  1573 W libprocessgroup: failed to open /acct/uid_10097/pid_6039/cgroup.procs: No such file or directory
,08-25 21:50:32.808  1034  1730 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7276 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-25 21:50:32.811  1034  1730 I ActivityManager: Killing 6732:com.lge.eula/1000 (adj 15): empty #17
,08-25 21:50:32.827  7219  7219 E wpa_supplicant: USIM:  scard_init function
08-25 21:50:32.827  7219  7219 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 21:50:32.830  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 21:50:32.830  1034  7228 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 21:50:32.830  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 21:50:32.830  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-25 21:50:32.830  1034  7228 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 21:50:32.830  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 21:50:32.830  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-25 21:50:32.833  1034  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 21:50:32.833  1034  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 21:50:32.834  1034  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 21:50:32.834  1034  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 21:50:32.834  1034  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 21:50:32.841   341   341 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 32.809ms
08-25 21:50:32.864   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 20.380ms
,08-25 21:50:32.886   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 502us total 20.466ms
,08-25 21:50:32.896  1034  1573 W libprocessgroup: failed to open /acct/uid_1000/pid_6732/cgroup.procs: No such file or directory
08-25 21:50:32.897  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=189481  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 21:50:32.909  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=189493  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 21:50:32.913  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 21:50:32.914  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:32.917  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:32.920  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.920  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.920  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-25 21:50:32.920  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:32.920  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 21:50:32.936  7219  7219 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 21:50:32.941  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,08-25 21:50:32.941  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 21:50:32.942  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 21:50:32.942  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 21:50:32.942  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 21:50:32.943  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:32.943  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 21:50:32.945  7219  7219 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 21:50:32.945  7219  7219 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 21:50:32.947  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:32.947  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 21:50:32.947  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 21:50:32.947  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 21:50:32.947  1034  7228 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 21:50:32.947  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 21:50:32.947  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 21:50:32.947  1034  7228 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 21:50:32.947  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:32.947  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 21:50:32.949  1034  1536 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:32.953  1034  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-25 21:50:32.954  1034  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:32.954  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:32.955  1034  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:32.955  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=189539  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 21:50:32.956  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=189540  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 21:50:32.957  1034  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=189540
08-25 21:50:32.957  1034  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=189541
08-25 21:50:32.957  1034  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=189541
08-25 21:50:32.958  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=189542
08-25 21:50:32.958  1034  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=189542
08-25 21:50:32.959  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=189543  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 21:50:32.961  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:32.961  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:32.963  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.963  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.963  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 21:50:32.963  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:32.965  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=189549  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 21:50:32.966  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=189550  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 21:50:32.967  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=189551  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 21:50:32.967  1034  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=189551
08-25 21:50:32.968  1034  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=189552
08-25 21:50:32.968  1034  1536 D WifiNative-wlan0: doString: [STATUS]
08-25 21:50:32.969  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:32.969  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 21:50:32.971  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.971  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:32.971,  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-25 21:50:32.973  1034  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 21:50:32.976  1034  1536 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 21:50:32.983  1034  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 21:50:32.983  1034  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-25 21:50:32.989  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:32.989  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:32.990  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.039  1034  1886 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7297 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 21:50:33.042  1034  1886 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
08-25 21:50:33.048  1034  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 21:50:33.049  1034  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 21:50:33.049  1034  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 21:50:33.049  1034  1543 D ConnectivityService: Got NetworkAgent Messenger
08-25 21:50:33.049  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 21:50:33.049  1034  1543 D ConnectivityService: NetworkAgent connected
08-25 21:50:33.050  1034  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 21:50:33.050  1034  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-25 21:50:33.057  1034  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 21:50:33.057  1034  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 21:50:33.057  1034  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 21:50:33.058  1034  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 21:50:33.058  1034  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 21:50:33.064  1034  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 21:50:33.067   304   894 D CommandListener: Setting iface cfg
08-25 21:50:33.075   310  1754 V AudioFlinger: 2127 died, releasing its sessions
08-25 21:50:33.075   310  1754 V AudioFlinger:  pid 1851 @ 0
08-25 21:50:33.075   310  1754 V AudioFlinger:  pid 3460 @ 1
08-25 21:50:33.075   310  1754 V AudioFlinger:  pid 3460 @ 2
,08-25 21:50:33.105  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:33.105  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 21:50:33.107  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.107  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.107  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.107  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 21:50:33.109  1034  1904 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
08-25 21:50:33.109  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.109  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.109  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 21:50:33.122  1034  1536 E WifiStateMachine: Start Dhcp Watchdog 2
08-25 21:50:33.122  1034  7316 D DhcpStateMachine: StoppedState
08-25 21:50:33.123  1034  7316 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.123  1034  7316 D DhcpStateMachine: WaitBeforeStartState
08-25 21:50:33.123  1034  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=189707  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:33.124  1034  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=189708  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-25 21:50:33.125  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=189709  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:33.127  1034  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=189711  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:33.128  1034  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=189712  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:33.129  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=189712  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:33.129  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:33.129  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:33.130  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:143701] from screen [on:0 period:-1019149398] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 21:50:33.130  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.131  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1019149397] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 21:50:33.132  1034  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 21:50:33.137  1034  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-25 21:50:33.138  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:33.138  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:33.139  1034  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:33.139  1034  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:33.140  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:33.140  1034  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:33.141  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 21:50:33.142  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=97,0,0
08-25 21:50:33.143  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=97,0,0
08-25 21:50:33.143  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 21:50:33.144  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 21:50:33.144  1034  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 21:50:33.144  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 21:50:33.144  1034  1536 D WifiNative-wlan0: SET ps 0: returned true
08-25 21:50:33.145  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 21:50:33.145  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 21:50:33.145  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 21:50:33.145  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10157758 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.145  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10157758 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.146  1034  7316 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.146  1034  7316 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 21:50:33.146  1034  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 21:50:33.146  1034  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 21:50:33.147  1034  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 21:50:33.147   304   894 D CommandListener: Setting iface cfg
08-25 21:50:33.148   304   894 D CommandListener: Trying to bring up wlan0
08-25 21:50:33.149  1034  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 21:50:33.151  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-25 21:50:33.151  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-25 21:50:33.151  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 21:50:33.151  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.152  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 21:50:33.152  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 21:50:33.152  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 21:50:33.152  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.152  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 21:50:33.153  1034  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 21:50:33.1,53  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 1
,08-25 21:50:33.154  7297  7297 I art     : Almond Protected OAT
08-25 21:50:33.172  1034  1536 D WifiNative-wlan0: SET ps 1: returned true
08-25 21:50:33.172  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 21:50:33.173  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:33.173  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:33.174  1034  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 21:50:33.174  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:33.174  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 21:50:33.174  1034  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:33.175  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:33.175  1034  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:33.176  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 21:50:33.176  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.176  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 21:50:33.177  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 21:50:33.177  1034  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 21:50:33.178  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
08-25 21:50:33.182  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:33.182  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:33.182  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.183  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.183  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 21:50:33.183  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.184  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 21:50:33.185  1034  1543 D ConnectivityService: Adding iface wlan0 to network 101
,08-25 21:50:33.190  1034  1535 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.190  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.190  1034  1535 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 21:50:33.190  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.190  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.190  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 21:50:33.192  1034  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 21:50:33.192  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 21:50:33.198  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-25 21:50:33.199  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.200  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.200  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 21:50:33.200  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 21:50:33.205  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:33.205  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:33.206  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.206  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:33.207  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 21:50:33.207  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.210  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:33.211  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 21:50:33.211  1034  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 21:50:33.211  1034  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-25 21:50:33.212  1034  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 21:50:33.212  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 21:50:33.212  1034  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-25 21:50:33.213  1034  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 21:50:33.213  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 21:50:33.214  1034  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 21:50:33.214  1034  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 21:50:33.215   304   894 E Netd    : netlink response contains error (File exists)
08-25 21:50:33.215  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.215  1034  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-25 21:50:33.216  1034  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 21:50:33.216  1034  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-25 21:50:33.216  1034  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-25 21:50:33.218  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 21:50:33.218  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 21:50:33.218  1034  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 21:50:33.218  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 21:50:33.218  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:33.218  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.218  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 21:50:33.218  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:33.218  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-25 21:50:33.218  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:33.218  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:33.218  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 21:50:33.218  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 21:50:33.218  1034  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-25 21:50:33.218  1034  1543 D ConnectivityService:    accepting network in place of null
08-25 21:50:33.218  1034  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:33.219  1034  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:33.219  1034  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:33.220   304  7321 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 21:50:33.226  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:33.226  1034  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 21:50:33.226  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 21:50:33.226  1034  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 21:50:33.226  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 21:50:33.226  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.228  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:33.228  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-25 21:50:33.235  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:33.235  1034  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 21:50:33.237  1034  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 21:50:33.237  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 21:50:33.237  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 21:50:33.238  1034  1543 D ConnectivityService: validation of new default Network = false
08-25 21:50:33.238  1034  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 21:50:33.238  1034  1543 D DSQN    : enableDataServiceNotify 
08-25 21:50:33.238  1034  1543 D DSQN    : start dsqn bin
08-25 21:50:33.238  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 21:50:33.238  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-25 21:50:33.244  7297  7297 D WeatherApplication: removeAccount
08-25 21:50:33.245  7297  7297 D WeatherApplication: Account.length = 0
08-25 21:50:33.245  7297  7297 E WeatherApplication: OPERATOR:OPEN
08-25 21:50:33.246  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 21:50:33.246  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:33.246  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:33.246  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:33.247  1600  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 21:50:33.241  7322  7322 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:33.241  7322  7322 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:33.263  7322  7322 E DSQN    : DSQN ssw
,08-25 21:50:33.264  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:33
08-25 21:50:33.265  1034  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 21:50:33.269  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 21:50:33.270  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
,08-25 21:50:33.275  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 21:50:33.276  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 21:50:33.277  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-25 21:50:33.283   304  7321 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 21:50:33.284  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 21:50:33.284  1815  7324 I CheckinService: active receiver: enabled
08-25 21:50:33.284  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.285  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:33.295  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 21:50:33.296  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 21:50:33.296  1815  7324 I CheckinService: Preparing to send checkin request
08-25 21:50:33.296  1815  7324 I EventLogService: Accumulating logs since 1472154500853
,08-25 21:50:33.296  7297  7297 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-25 21:50:33.306  1815  7324 W EventLogAggregator: Unknown tag: snet_gcore
08-25 21:50:33.306  1815  7324 W EventLogAggregator: Unknown tag: snet_launch_service
,08-25 21:50:33.317  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-25 21:50:33.317  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:33
08-25 21:50:33.324   304  7321 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-25 21:50:33.347  1034  7316 D DhcpStateMachine: DHCPV4 request on wlan0
,08-25 21:50:33.348  1034  7316 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 21:50:33.349  1034  7316 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 21:50:33.341  7329  7329 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:33.341  7329  7329 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:33.356   304   893 D LGDataListener: argv[0]=dsqncommand
08-25 21:50:33.356   304   893 D LGDataListener: argv[1]=wlan0
08-25 21:50:33.356   304   893 D LGDataListener: argv[2]=1
08-25 21:50:33.356   304   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 21:50:33.357  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 21:50:33.357  1034  1094 D DSQN    : start to monitor internet connection
08-25 21:50:33.364  7329  7329 I dhcpcd  : version 5.5.6 starting
08-25 21:50:33.367  7329  7329 E dhcpcd  : get_duid: m
08-25 21:50:33.367  7329  7329 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 21:50:33.367  7329  7329 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-25 21:50:33.372  1034  1959 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7332 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 21:50:33.374  1034  1959 I ActivityManager: Killing 6750:com.lge.bnr/1000 (adj 15): empty #17
08-25 21:50:33.399  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 19:50:33 GMT], X-Android-Received-Millis=[1472154633398], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472154633355]}
08-25 21:50:33.399  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 21:50:33.399  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 21:50:33.399  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 21:50:33.399  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 21:50:33.399  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:33.399  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:33.399  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 21:50:33.399  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,08-25 21:50:33.399  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 21:50:33.400  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:33.400  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:33.400  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:33.401  1034  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:33.401  1600  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 21:50:33.401  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 21:50:33.401  1034  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:33.401  1034  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:33.402  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:33.402  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 21:50:33.436  1034  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6750/cgroup.procs: No such file or directory
08-25 21:50:33.437  7329  7329 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 21:50:33.437  7329  7329 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 21:50:33.437  7329  7329 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 21:50:33.438  7329  7329 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 21:50:33.438  7329  7329 D dhcpcd  : wlan0: sending REQUEST (xid 0xf9ef772a), next in 4.53 seconds
,08-25 21:50:33.450  1815  7324 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-25 21:50:33.462  7329  7329 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-25 21:50:33.468  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 21:50:33.469  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:33.470  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:33.484  7329  7329 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 21:50:33.484  7329  7329 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 21:50:33.484  7329  7329 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 21:50:33.484  7329  7329 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 21:50:33.484  7329  7329 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 21:50:33.485  7329  7329 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 21:50:33.485  7329  7329 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 21:50:33.485  7329  7329 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 21:50:33.565   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 21:50:33.565   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-25 21:50:33.565   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 21:50:33.567  7332  7362 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 21:50:33.569   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 21:50:33.569   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 21:50:33.569   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 21:50:33.569  7332  7362 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 21:50:33.580  1034  2210 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7366 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-25 21:50:33.595   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 21:50:33.595   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-25 21:50:33.595   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 21:50:33.596  7332  7367 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-25 21:50:33.599   278   434 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 21:50:33.599   278   434 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,08-25 21:50:33.600   278   434 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 21:50:33.600  7332  7367 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-25 21:50:33.637  7366  7366 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-25 21:50:33.637  7366  7366 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 21:50:33.659  7366  7366 I MultiDex: VM with version 2.1.0 has multidex support
08-25 21:50:33.659  7366  7366 I MultiDex: install
08-25 21:50:33.659  7366  7366 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 21:50:33.668  7366  7366 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-25 21:50:33.752  1034  7316 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 21:50:33.752  1034  7316 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 21:50:33.752  1034  7316 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 21:50:33.753  1034  7316 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 21:50:33.753  1034  7316 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 21:50:33.753  1034  7316 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 21:50:33.753  1034  7316 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 21:50:33.753  1034  7316 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 21:50:33.753  1034  7316 D DhcpStateMachine: RunningState
08-25 21:50:33.780  7332  7332 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 21:50:33.790  7332  7332 I LibraryLoader: Loading: webviewchromium
08-25 21:50:33.793  7332  7332 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 386-390)
,08-25 21:50:33.794  7332  7332 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 21:50:33.799  7332  7332 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c3b347}
08-25 21:50:33.800  7332  7332 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 21:50:33.801  7332  7332 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 21:50:33.812  7332  7332 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 21:50:33.813  7332  7332 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 21:50:33.827  1034  1923 I art     : Explicit concurrent mark sweep GC freed 103958(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 3.905ms total 80.252ms
,08-25 21:50:33.833   310  1383 V AudioPolicyService: registerClient() client 0xb54eadc0, uid 10093
08-25 21:50:33.834  7332  7418 W AudioManagerAndroid: Requires BLUETOOTH permission
08-25 21:50:33.846  7332  7332 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 21:50:33.848  7332  7332 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-25 21:50:33.848  7332  7332 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-25 21:50:33.859  7332  7332 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 21:50:33.859  7332  7332 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 21:50:33.859  7332  7332 I Adreno-EGL: Build Date: 12/12/14 금
08-25 21:50:33.859  7332  7332 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 21:50:33.859  7332  7332 I Adreno-EGL: Remote Branch: 
08-25 21:50:33.859  7332  7332 I Adreno-EGL: Local Patches: 
08-25 21:50:33.859  7332  7332 I Adreno-EGL: Reconstruct Branch: 
,08-25 21:50:33.902  7332  7332 I NSApplication: Starting up...
,08-25 21:50:33.968  1034  1923 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7431 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-25 21:50:33.971  1034  1941 I ActivityManager: Killing 6223:com.android.vending/u0a44 (adj 15): empty #17
08-25 21:50:34.068  1034  1904 W libprocessgroup: failed to open /acct/uid_10044/pid_6223/cgroup.procs: No such file or directory
,08-25 21:50:34.094  7366  7386 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:34.094  7366  7386 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 21:50:34.106  7431  7431 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:50:34.160  1034  1941 D WifiServiceImplEx: setWifiEnabled: false pid=6856, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 21:50:34.160  1034  1941 D WifiService: setWifiEnabled: false pid=6856, uid=10118
,08-25 21:50:34.160  1034  1941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 21:50:34.170  1034  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:34.170  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:34.171  1034  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:34.171  1034  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:34.171  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 21:50:34.171  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 21:50:34.171  1034  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 21:50:34.172  1034  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 21:50:34.172  1034  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 21:50:34.172  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 21:50:34.172  1034  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 21:50:34.172  1034  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 21:50:34.172  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 21:50:34.177  1034  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 21:50:34.177  1034  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.177  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.177  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 21:50:34.177  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 21:50:34.177  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 21:50:34.177  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 21:50:34.178  1034  1536 D WifiNative-wlan0: SET ps 1: returned true
08-25 21:50:34.178  1034  7316 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.182   304   894 D CommandListener: Clearing all IP addresses on wlan0
,08-25 21:50:34.202  7448  7448 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-25 21:50:34.207  1034  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:34.207  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:34.207  1034  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:34.207  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 21:50:34.208  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
08-25 21:50:34.208  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-25 21:50:34.211  1034  1535 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.211  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.211  1034  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@23f5112a
08-25 21:50:34.211  1034  1535 D LGWifiP2pService: P2pDisablingState
08-25 21:50:34.212  1034  1535 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.212  1034  1535 D LGWifiP2pService: p2p socket connection lost
08-25 21:50:34.212  1034  1535 D LGWifiP2pService: P2pDisabledState
08-25 21:50:34.212  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 21:50:34.213  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:34.213  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:34.213  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 21:50:34.213  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 21:50:34.213  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:34.213  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:34.213  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 21:50:34.213  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
,08-25 21:50:34.213  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-25 21:50:34.213  1034  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.214  1034  1555 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.214  1034  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 21:50:34.214  1034  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 21:50:34.214  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 21:50:34.214  7219  7219 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 21:50:34.215  1034  1535 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 21:50:34.215  1034  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.215  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 21:50:34.215  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 21:50:34.216  1034  1536 D WifiNative-wlan0: SET ps 1: returned true
08-25 21:50:34.218  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:34.218  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:34.219  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 21:50:34.221  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 21:50:34.222  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:34.226  1942  1942 D WfdsService: WifiP2pState is changed : false
08-25 21:50:34.226  1942  2341 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 21:50:34.226  1942  2341 D WfdsService: Set the WFDS Monitor: false
08-25 21:50:34.227  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:34.227  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:34.229  1942  2341 D WfdsMonitor: WFDS Monitor is stopped
08-25 21:50:34.229  1942  2341 D WfdsService: STATE : WfdsDisabledState - enter
08-25 21:50:34.229  1942  7229 D CtrlSupplicant: Received on exit socket, terminate
08-25 21:50:34.229  1942  7229 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 21:50:34.229  1942  7229 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 21:50:34.229  1942  7229 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 21:50:34.230  1942  2351 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 21:50:34.230  1942  2341 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 21:50:34.230  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:34.256   304   894 D CommandListener: Clearing all IP addresses on wlan0
08-25 21:50:34.257  1034  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 21:50:34.257  1034  1543 D DSQN    : disableDataServiceNotify
08-25 21:50:34.257  1034  1543 D DSQN    : stop dsqn bin
,08-25 21:50:34.258  1034  1536 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 21:50:34.259  1034  1536 D WifiNative-p2p0: TERMINATE: returned true
08-25 21:50:34.259  1034  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 21:50:34.259  1034  1536 E WifiStateMachine: useWiFiOffloading() : false
08-25 21:50:34.259  1034  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 21:50:34.259  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-25 21:50:34.259  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 21:50:34.259  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:34.261  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:34.261  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:34.261  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 21:50:34.262  1034  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 21:50:34.262  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:34.262  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:34.262  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:34.262  1034  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:34.262  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 21:50:34.262  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.262  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.262  1034  7311 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 21:50:34.263  1034  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 21:50:34.263  1034  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 21:50:34.263  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 21:50:34.263  1600  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 21:50:34.264  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 21:50:34.264  7448  7448 I dex2oat : dex2oat took 61.744ms (threads: 4)
,08-25 21:50:34.276  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:34.276  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:34.276  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:34.276  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:34.276  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:34.276  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:34.276  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:34.276  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:34.276  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:34.276  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:34.276  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:34.277  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:34.277  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:34.277  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:34.277  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:34.277  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:34.277  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:34.277  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:34.277  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:34.277  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:34.277  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:34.277  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:34.278  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:34.278  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 21:50:34.278  1034  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 21:50:34.279  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 21:50:34.279  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:34.279  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:34.279  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 21:50:34.279  1034  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:34.279  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 21:50:,34.279  1034  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:34.279  1034  1543 D NetworkManagementService: Removing idletimer
08-25 21:50:34.279  1034  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:34.279  7366  7386 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 21:50:34.279  7366  7386 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 21:50:34.279  7366  7386 I Adreno-EGL: Build Date: 12/12/14 금
08-25 21:50:34.279  7366  7386 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 21:50:34.279  7366  7386 I Adreno-EGL: Remote Branch: 
08-25 21:50:34.279  7366  7386 I Adreno-EGL: Local Patches: 
08-25 21:50:34.279  7366  7386 I Adreno-EGL: Reconstruct Branch: 
08-25 21:50:34.279  1034  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-25 21:50:34.280  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 21:50:34.280  1034  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:34.280  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 21:50:34.280  1034  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:34.280  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 21:50:34.280  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:34.280  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 21:50:34.281  1034  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 21:50:34.281  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 21:50:34.282  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 21:50:34.282  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 21:50:34.282  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 21:50:34.282  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:34.298  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 21:50:34.299  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:34.300  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:34.312  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-25 21:50:34.313  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:34.313  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:34.355  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 21:50:34.355  7219  7219 I wpa_supplicant: monitor socket send errors count : 1
08-25 21:50:34.355  7219  7219 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
08-25 21:50:34.356  1034  7228 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 21:50:34.356  1034  7228 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-25 21:50:34.377  7219  7219 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 21:50:34.378  7219  7219 W wpa_supplicant: USIM:  scard_deinit function
,08-25 21:50:34.378  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 21:50:34.378  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 21:50:34.378  1034  7228 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 21:50:34.378  1034  7228 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 21:50:34.379  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:34.379  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 21:50:34.379  1034  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=190963
08-25 21:50:34.379  1034  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=190963
08-25 21:50:34.380  1034  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=190963  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 21:50:34.380  1034  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=190964  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 21:50:34.382  1034  1096 D Tethering: InitialState.processMessage what=4
08-25 21:50:34.382  1034  7316 D DhcpStateMachine: StoppedState
08-25 21:50:34.382  1034  7316 D DhcpStateMachine: StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:34.383  1034  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 21:50:34.383  1034  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-25 21:50:34.386  1034  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:34.386  1034  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:34.389  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 21:50:34.403  7366  7386 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 21:50:34.403  7366  7386 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 21:50:34.403  7366  7386 I Adreno-EGL: Build Date: 12/12/14 금
08-25 21:50:34.403  7366  7386 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 21:50:34.403  7366  7386 I Adreno-EGL: Remote Branch: 
08-25 21:50:34.403  7366  7386 I Adreno-EGL: Local Patches: 
08-25 21:50:34.403  7366  7386 I Adreno-EGL: Reconstruct Branch: 
08-25 21:50:34.406  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 21:50:34.407  6571  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 21:50:34.419  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:34.426  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 21:50:34.426  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:34.426  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 21:50:34.426  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 21:50:34.434  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 21:50:34.438  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@53aacac
08-25 21:50:34.438  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 21:50:34.438  7166  7166 D AppUp4:CustFacade: isPhone : true
08-25 21:50:34.439  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-25 21:50:34.440  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 21:50:34.445  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:34.445  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 21:50:34.447  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 21:50:34.449  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:34.455  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 21:50:34.457  4386  7472 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 21:50:34.465  4386  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:34.465  4386  7473 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 21:50:34.466  7366  7386 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 21:50:34.466  7366  7386 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 21:50:34.466  7366  7386 I Adreno-EGL: Build Date: 12/12/14 금
08-25 21:50:34.466  7366  7386 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 21:50:34.466  7366  7386 I Adreno-EGL: Remote Branch: 
08-25 21:50:34.466  7366  7386 I Adreno-EGL: Local Patches: 
08-25 21:50:34.466  7366  7386 I Adreno-EGL: Reconstruct Branch: 
08-25 21:50:34.477  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 21:50:34.477  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:34.477  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-25 21:50:34.479  7199  7475 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:34.482  7236  7236 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 21:50:34.482  7236  7236 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 21:50:34.489  7065  7476 W FormManager: Network not available. Please check & try again.
08-25 21:50:34.489  7065  7477 V FormManager: Network unavailable.
,08-25 21:50:34.495  7219  7219 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 21:50:34.496  1034  7228 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 21:50:34.496  1034  7228 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 21:50:34.496  1034  7228 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 21:50:34.496  1034  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-25 21:50:34.497  7065  7477 V FormManager: Network unavailable.
08-25 21:50:34.501  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:34
,08-25 21:50:34.505  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-25 21:50:34.505  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
08-25 21:50:34.505  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 21:50:34.505  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 21:50:34.506  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@21a4610a
08-25 21:50:34.506  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 21:50:34.506  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 21:50:34.506  7297  7297 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 21:50:34.507  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 21:50:34.507  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:34
08-25 21:50:34.536  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 21:50:34.536  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-25 21:50:34.536  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 21:50:34.536  6975  6975 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 21:50:34.536  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 21:50:34.538  6975  6975 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 21:50:34.538  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 21:50:34.538  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 21:50:34.538  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 21:50:34.538  6975  6975 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 21:50:34.538  6975  6975 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 21:50:34.541  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=390834456 [*alarm*], flags=0x0
08-25 21:50:34.543   304  7480 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 21:50:34.543  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 21:50:34.546  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:34.551  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:50:34.552  7065  7482 W FormManager: Network not available. Please check & try again.
08-25 21:50:34.555  7065  7483 V FormManager: Network unavailable.
08-25 21:50:34.557  7065  7483 V FormManager: Network unavailable.
,08-25 21:50:34.565  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:34.567   304  7485 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 21:50:34.567  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 21:50:34.568  1815  7324 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-25 21:50:34.577  1815  7324 I CheckinService: active receiver: disabled
,08-25 21:50:34.591  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:34.594  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 21:50:34.596  7065  7487 W FormManager: Network not available. Please check & try again.
08-25 21:50:34.597  1034  1536 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 21:50:34.597  1034  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 21:50:34.597  1034  1536 E WifiStateMachine: useWiFiOffloading() : false
08-25 21:50:34.597  1034  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 21:50:34.598  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-25 21:50:34.598  1942  2341 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 21:50:34.598  1942  2341 D WfdsService: Set the WFDS Monitor: false
08-25 21:50:34.598  1942  2341 D WfdsMonitor: WFDS Monitor is stopped
08-25 21:50:34.598  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:34.599  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 21:50:34.599  1034  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 21:50:34.599  1034  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 21:50:34.599  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:34.599  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-25 21:50:34.601  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:50:34.601  2482  2482 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:34.601  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:34.601  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:34.601  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:34.601  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:34.601  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
08-25 21:50:34.601  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:34.601  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:34.601  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:34.602  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:34.602  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:34.602  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:34.602  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:34.602  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:34.602  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:34.602  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:34.602  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:34.602  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:34.611  7065  7488 V FormManager: Network unavailable.
,08-25 21:50:34.612  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 21:50:34.612  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 21:50:34.613  7065  7488 V FormManager: Network unavailable.
08-25 21:50:34.614  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:34.615  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:34.619  4386  7489 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 21:50:34.620  4386  7490 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 21:50:34.620  4386  7490 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 21:50:34.675  1034  1941 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7491 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 21:50:34.789  7491  7491 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 21:50:34.789  7491  7491 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 21:50:34.799  7491  7491 V [BNRBootReceiver]: Boot Receiver Return
08-25 21:50:34.799  7491  7491 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 21:50:34.806  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:34.818  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:34.826  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:34.842  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:34.842  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:34.844  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 21:50:34.849  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:34.868  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:34.881  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:34.893  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 21:50:34.894  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:34.896  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 21:50:34.903  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 21:50:34.908  6975  6975 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-25 21:50:34.916  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:34.925  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:34.932  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:34.944  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:34.945  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:34.946  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:34.950  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:34.963  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:34.970  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:34.983  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:34.984  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:34.985  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 21:50:34.991  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:35.008  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:35.021  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 21:50:35.034  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:35.035  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:35.036  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 21:50:35.043  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:35.063  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:35.078  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 21:50:35.090  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:35.091  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:35.092  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:35.097  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:35.113  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:35.123  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:35.127  6789  7143 D UEI.SmartControl: Internal timer expired: 2
08-25 21:50:35.127  6789  7143 D UEI.SmartControl: unbind internal service
08-25 21:50:35.137  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:35.138  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 21:50:35.139  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:35.153  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:35.173  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:35.185  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:35.199  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:35.200  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 21:50:35.208  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:35.217  6789  7137 D serial_port: close(fd = 24)
,08-25 21:50:35.217  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:35.223  6789  7137 I UEI.SmartControl: Serial port is closed.
08-25 21:50:35.237  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:35.246  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 21:50:35.257  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:35.257  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:35.259  7025  7025 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 21:50:35.266  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:35.272  6997  6997 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 21:50:35.286  1034  1541 D WifiService: New client listening to asynchronous messages
,08-25 21:50:35.286  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:35.293  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:35.304  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:35.318  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 21:50:35.319  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:35.321  7025  7025 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 21:50:35.323  7025  7025 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 21:50:35.324  7025  7025 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 21:50:35.338  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:35.350  6997  6997 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 21:50:35.354  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:35.357  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 21:50:35.365  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:35.372  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:35.373  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:35.373  7025  7025 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 21:50:35.374  7025  7025 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 21:50:35.375  7025  7025 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-25 21:50:35.377  1034  2031 I ActivityManager: Killing 6954:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-25 21:50:35.418  1034  1051 W libprocessgroup: failed to open /acct/uid_10037/pid_6954/cgroup.procs: No such file or directory
,08-25 21:50:35.424  2186  2186 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-25 21:50:35.441  2186  2186 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-25 21:50:35.442  2186  2186 D c       : Getting all permits...
08-25 21:50:35.442  2186  2186 D a       : Opening database...
08-25 21:50:35.452  2186  2186 D a       : Opening database auth.proximity.permit_store...
08-25 21:50:35.454  2186  2186 D a       : Closing database...
,08-25 21:50:35.474  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:35.481  6997  6997 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 21:50:35.482  6997  6997 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 21:50:35.482  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:35.485  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:35.495  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 21:50:35.504  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:35.504  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 21:50:35.507  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 21:50:35.512  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:35.518  6997  6997 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 21:50:35.518  6997  6997 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 21:50:35.518  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:35.523  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:35.531  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:35.539  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:35.542  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 21:50:35.544  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 21:50:35.549  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:35.555  6997  6997 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 21:50:35.555  6997  6997 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 21:50:35.555  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 21:50:35.565  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:35.577  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:35.589  7025  7025 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 21:50:35.590  7025  7025 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:35.592  7025  7025 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 21:50:35.612  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 21:50:35.619  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 21:50:35.626  7065  7516 W FormManager: Network not available. Please check & try again.
08-25 21:50:35.628  7065  7517 V FormManager: Network unavailable.
,08-25 21:50:35.631  7065  7517 V FormManager: Network unavailable.
08-25 21:50:35.636  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:35.655  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 21:50:35.655  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 21:50:35.657  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 21:50:35.662  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:35.669  4386  7518 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 21:50:35.673  4386  7519 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-25 21:50:35.673  4386  7519 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 21:50:35.677  6997  6997 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 21:50:35.677  6997  6997 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-25 21:50:35.677  6997  6997 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:35.685  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 21:50:35.685  7065  7521 W FormManager: Network not available. Please check & try again.
,08-25 21:50:35.697  7065  7522 V FormManager: Network unavailable.
08-25 21:50:35.698  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:35.704  7065  7522 V FormManager: Network unavailable.
,08-25 21:50:35.732  2186  2186 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-25 21:50:36.139  1034  1536 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1019146389] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 21:50:36.142  1034  1536 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1019146387] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 21:50:36.237  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:36.257  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:36.257  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-25 21:50:36.262  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:36.267  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:36.274  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 21:50:36.276  6571  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 21:50:36.291  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 21:50:36.315  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:36.344  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 21:50:36.344  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:36.344  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 21:50:36.345  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 21:50:36.351  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
08-25 21:50:36.355  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@53aacac
08-25 21:50:36.355  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 21:50:36.355  7166  7166 D AppUp4:CustFacade: isPhone : true
08-25 21:50:36.355  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-25 21:50:36.355  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 21:50:36.361  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:36.361  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 21:50:36.363  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 21:50:36.374  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:36.382  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 21:50:36.410  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 21:50:36.416  4386  7529 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 21:50:36.424  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 21:50:36.424  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:36.424  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = true
08-25 21:50:36.424  3460  3460 D PhoneState: setPdpRejectCasuse : false
08-25 21:50:36.424  4386  7548 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:36.424  4386  7548 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 21:50:36.429  7236  7236 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 21:50:36.429  7236  7236 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 21:50:36.433  7065  7543 W FormManager: Network not available. Please check & try again.
08-25 21:50:36.439  7199  7547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 21:50:36.443  7065  7545 V FormManager: Network unavailable.
,08-25 21:50:36.446  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:36
08-25 21:50:36.448  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 21:50:36.448  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
08-25 21:50:36.449  7065  7545 V FormManager: Network unavailable.
08-25 21:50:36.449  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 21:50:36.449  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 21:50:36.449  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@21a4610a
,08-25 21:50:36.450  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 21:50:36.450  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 21:50:36.450  7297  7297 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 21:50:36.450  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 21:50:36.450  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:36
08-25 21:50:37.172  1034  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:37.173  1034  1941 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 21:50:37.205  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 21:50:37.206  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 21:50:37.206  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 21:50:37.207  1034  1096 D BluetoothManagerService: Message: 1
08-25 21:50:37.207  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 21:50:37.233  1034  1096 D BluetoothManagerService: Message: 20
08-25 21:50:37.234  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e5f1671:true
,08-25 21:50:37.238  7094  7094 D BluetoothAdapterState: make
08-25 21:50:37.243  7094  7094 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 21:50:37.244  7094  7094 I bluedroid-qcom: init
08-25 21:50:37.245  7094  7562 I BluetoothAdapterState: Entering OffState
08-25 21:50:37.245  7094  7094 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 21:50:37.246  7094  7094 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 21:50:37.246  7094  7094 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 21:50:37.246  7094  7094 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 21:50:37.246  7094  7094 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 21:50:37.248  7094  7094 I bluedroid-qcom: get_profile_interface socket
08-25 21:50:37.248  7094  7094 I bluedroid-qcom: get_profile_interface map_client
,08-25 21:50:37.251  7565  7565 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:37.255  7094  7566 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 21:50:37.257  7094  7566 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 21:50:37.251  7565  7565 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:37.266  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 21:50:37.267  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-25 21:50:37.271  7094  7566 D BluetoothAdapterProperties: Name is: G3
08-25 21:50:37.272  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 21:50:37.272  1034  1096 D BluetoothManagerService: Message: 40
08-25 21:50:37.272  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 21:50:37.273  7094  7111 I bluedroid-qcom: config_hci_snoop_log
08-25 21:50:37.275  7565  7565 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 21:50:37.276  7565  7565 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 21:50:37.276  7565  7565 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 21:50:37.277  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 21:50:37.277  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 21:50:37.278  7565  7565 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 21:50:37.280  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:37.285  7565  7565 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 21:50:37.285  7565  7565 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 21:50:37.291  7094  7562 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 21:50:37.291  7094  7562 D BluetoothAdapterProperties: Setting state to 11
08-25 21:50:37.292  7094  7562 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 21:50:37.293  7094  7562 I LGBluetoothServiceJni: classInitNative: succeeds
,08-25 21:50:37.297  1034  1096 D BluetoothManagerService: Message: 60
08-25 21:50:37.297  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 21:50:37.297  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 21:50:37.299  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.308  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:37.322  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:37.330  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:37.333  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:37.338  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:37.346  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-25 21:50:37.346  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-25 21:50:37.348  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 21:50:37.349  7094  7562 D BluetoothBondStateMachine: make
08-25 21:50:37.351  6571  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 21:50:37.352  7094  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.352  7094  7581 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 21:50:37.352  7094  7562 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 21:50:37.352  7094  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.352  7094  7562 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 21:50:37.353  7094  7562 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 21:50:37.355  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 21:50:37.356  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:50:37.358  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 21:50:37.360  6975  6975 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 21:50:37.360  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:37.365  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:37.370  7094  7562 E BluetoothAdapterService: File transfer profiles supported!!
08-25 21:50:37.379  5782  5782 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 21:50:37.385  7094  7562 E BluetoothAdapterService: File transfer profiles supported!!
08-25 21:50:37.388  7094  7094 D HeadsetService: Received start request. Starting profile...
08-25 21:50:37.389  7094  7094 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 21:50:37.389  7094  7094 D LGBluetoothHfpAdapter: Version 1.6
08-25 21:50:37.392  7094  7094 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 21:50:37.393  7094  7094 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 21:50:37.394  7094  7094 D HeadsetStateMachine: make
08-25 21:50:37.394  7094  7562 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 21:50:37.395  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.395  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:37.395  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:37.407  7094  7562 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 21:50:37.415  7094  7562 E BluetoothAdapterService: File transfer profiles supported!!
08-25 21:50:37.416  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.422  7094  7562 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 21:50:37.430  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 21:50:37.430  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.430  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 21:50:37.430  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 21:50:37.430  7094  7094 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:37.431  7094  7094 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 21:50:37.433  7094  7562 E BluetoothAdapterService: File transfer profiles supported!!
08-25 21:50:37.436  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 21:50:37.438  7094  7094 D HeadsetStateMachine: max_hf_connections = 1
08-25 21:50:37.438  7094  7094 I bluedroid-qcom: get_profile_interface handsfree
08-25 21:50:37.440  7094  7094 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 21:50:37.440   310  1754 V AudioPolicyService: registerClient() client 0xb57f58e0, uid 1002
08-25 21:50:37.441   310  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 21:50:37.441   310  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 21:50:37.441   310  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 21:50:37.441  7094  7094 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 21:50:37.441   310   310 V AudioFlinger: registerClient() client 0xb54ebb08, pid 7094
08-25 21:50:37.442   310  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:37.442   310  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:37.442  1034  2033 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:37.442  1034  2033 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:37.442  1600  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:37.442  1600  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:37.442  3460  3476 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:37.442  3460  3476 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:37.442  1851  3552 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:37.442  1851  3552 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:37.442  7094  7094 V ToneGenerator: Create Track: 0xb4928080
08-25 21:50:37.442  7094  7094 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 21:50:37.442   310  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:37.442  7094  7094 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 21:50:37.442   310  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:37.442   310  1754 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 21:50:37.442   310  1754 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 21:50:37.442   310  1754 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 21:50:37.442   310  1754 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 21:50:37.442  7094  7094 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 21:50:37.443  1034  1923 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:37.443  1034  1923 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:37.443  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:37.443  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:37.443  3460  3475 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:37.443  7094  7572 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:37.443  3460  3475 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:37.443  7094  7572 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 21:50:37.443   310  1382 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 21:50:37.443  7094  7572 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:37.443  7094  7572 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 21:50:37.443  1600  2097 V AudioSystem: ioConfigChanged() event 0, i,oHandle 2
08-25 21:50:37.443   310  1754 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 21:50:37.443  1600  2097 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:37.443   310  1754 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 21:50:37.443   310  1754 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 21:50:37.443   310  1754 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 21:50:37.443  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@53aacac
08-25 21:50:37.443  7094  7094 V AudioSystem: getLatency() output 2, latency 50
08-25 21:50:37.443  7094  7094 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 21:50:37.443  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 21:50:37.443  7094  7094 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 21:50:37.443  7166  7166 D AppUp4:CustFacade: isPhone : true
08-25 21:50:37.443   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 21:50:37.443   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 21:50:37.443   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 21:50:37.443   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 21:50:37.443   310   310 V AudioFlinger: createTrack() lSessionId: 22
08-25 21:50:37.444  7094  7094 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 21:50:37.444  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-25 21:50:37.444   310  1383 V AudioFlinger: acquiring 22 from 7094, for 7094
08-25 21:50:37.444   310  1383 V AudioFlinger:  added new entry for 22
08-25 21:50:37.444  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 21:50:37.444  7094  7094 V ToneGenerator: ToneGenerator INIT OK, time: 194041
08-25 21:50:37.445  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.445  7094  7585 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 21:50:37.445  7094  7585 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 21:50:37.445  7094  7585 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 21:50:37.446  7094  7585 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 21:50:37.446   310  1382 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7094
08-25 21:50:37.446   310  1382 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 21:50:37.446   310  1382 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 21:50:37.446   310  1382 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 21:50:37.446   310  1382 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 21:50:37.446   310  1382 V voice   : voice_set_parameters: exit with code(0)
08-25 21:50:37.446   310  1382 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 21:50:37.446   310  1382 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
,08-25 21:50:37.446   310  1382 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 21:50:37.446   310  1382 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 21:50:37.446   310  1382 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 21:50:37.446   310  1382 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 21:50:37.447  7094  7585 V ToneGenerator: ToneGenerator destructor
08-25 21:50:37.447  7094  7585 V ToneGenerator: stopTone
08-25 21:50:37.447  7094  7585 V ToneGenerator: Delete Track: 0xb4928080
08-25 21:50:37.447  7094  7585 V AudioTrack: ~AudioTrack, releasing session id from 7094 on behalf of 7094
08-25 21:50:37.447  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.447   310  1754 V AudioFlinger: releasing 22 from 7094 for 7094
08-25 21:50:37.447   310  1754 V AudioFlinger:  decremented refcount to 0
08-25 21:50:37.447   310  1754 V AudioFlinger: purging stale effects
08-25 21:50:37.447   310  1754 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 21:50:37.447   310  1754 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
,08-25 21:50:37.447   310  1754 V AudioFlinger: PlaybackThread::Track destructor
08-25 21:50:37.447   310  1258 V AudioPolicyService: AudioCommandThread() waking up
08-25 21:50:37.447   310  1754 V AudioFlinger: removeClient_l() pid 7094, calling pid 310
08-25 21:50:37.447   310  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 21:50:37.447   310  1258 V AudioPolicyManager: releaseOutput() 2
08-25 21:50:37.447   310  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 21:50:37.448  7094  7094 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 21:50:37.448  7094  7094 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:37.448  7094  7094 V BluetoothPbapReceiver: ***********state = 11
08-25 21:50:37.449  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.449  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 21:50:37.450  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 21:50:37.451  7094  7094 D A2dpService: Received start request. Starting profile...
08-25 21:50:37.451  7094  7094 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 21:50:37.452  7094  7094 V Avrcp   : make
08-25 21:50:37.452  7094  7094 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 21:50:37.452  7094  7094 I bluedroid-qcom: get_profile_interface avrcp
08-25 21:50:37.453  1034  1050 W Process : Unable to open /proc/7588/status
,08-25 21:50:37.459  7094  7094 V AudioManager: registerRemoteController: size of Media player list: 0
08-25 21:50:37.461  7094  7094 E AudioManager: No RCC entry present to update
08-25 21:50:37.461  7094  7094 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 21:50:37.462  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:37.463  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:50:37.464  7094  7562 V LGMDMManager: Create singleton instance
08-25 21:50:37.464  7094  7094 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 21:50:37.465  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 21:50:37.465  7094  7094 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 21:50:37.466  7094  7562 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-25 21:50:37.471  4386  7591 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 21:50:37.472  4386  7592 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.472  4386  7592 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 21:50:37.490  1034  1977 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7593 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 21:50:37.495  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-25 21:50:37.532  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 21:50:37.551  7199  7610 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 21:50:37.556  7065  7613 W FormManager: Network not available. Please check & try again.
,08-25 21:50:37.557  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 21:50:37.557  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.557  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 21:50:37.559  7236  7236 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 21:50:37.559  7236  7236 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 21:50:37.569  7065  7614 V FormManager: Network unavailable.
,08-25 21:50:37.573  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:37
08-25 21:50:37.574  7065  7614 V FormManager: Network unavailable.
08-25 21:50:37.574  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 21:50:37.574  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
08-25 21:50:37.575  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 21:50:37.575  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 21:50:37.575  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@21a4610a
08-25 21:50:37.576  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 21:50:37.576  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 21:50:37.576  7297  7297 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 21:50:37.576  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 21:50:37.576  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:37
08-25 21:50:37.577  1034  1959 V SIM_STK : Menu title from STK is T-Mobile
08-25 21:50:37.577  1034  1959 V SIM_STK : Menu title from STK is T-Mobile
08-25 21:50:37.589  7593  7593 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 21:50:37.590  7593  7593 W LG Account v2.2: No ProfileInfo entries
08-25 21:50:37.590  7593  7593 I LG Account v2.2: isEnabled: false
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]Country: EU
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]Operator: OPEN
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]Ranking support: false
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]Comfort support: false
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]Accessory: true
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]Health device: true
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]Extra Pedometer: false
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]Blood glucose device: false
08-25 21:50:37.590  7593  7593 I Feature : [Lifetracker]Device Number: 3
,08-25 21:50:37.599  6975  6975 D BluetoothPermissionRequest: onReceive
08-25 21:50:37.600  6571  6571 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 21:50:37.602  6975  6975 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 21:50:37.604  6571  6995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-25 21:50:37.614  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:50:37.623  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 21:50:37.623  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.624  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 21:50:37.624  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 21:50:37.625  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
08-25 21:50:37.627  1034  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 21:50:37.628  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@53aacac
08-25 21:50:37.628  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 21:50:37.628  7166  7166 D AppUp4:CustFacade: isPhone : true
,08-25 21:50:37.628  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-25 21:50:37.628  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 21:50:37.631  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.631  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 21:50:37.632  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 21:50:37.633  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:37.634  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:37.635  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-25 21:50:37.635  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 21:50:37.635  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-25 21:50:37.635  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 21:50:37.635  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 21:50:37.636  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 21:50:37.636  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 21:50:37.636  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 21:50:37.636  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 21:50:37.636  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 21:50:37.636  7094  7094 I BluetoothA2dpServiceJni: classInitNative
08-25 21:50:37.636  7094  7094 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 21:50:37.636  7094  7094 D A2dpStateMachine: make
08-25 21:50:37.637  7094  7094 I bluedroid-qcom: get_profile_interface a2dp
08-25 21:50:37.637  7094  7618 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 21:50:37.639  7094  7094 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 21:50:37.639  7094  7094 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 21:50:37.639  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.640  7094  7094 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 21:50:37.641  7094  7617 D A2dpStateMachine: Enter Disconnected: -2
08-25 21:50:37.641  7094  7094 D HidService: Received start request. Starting profile...
08-25 21:50:37.641  7094  7094 I bluedroid-qcom: get_profile_interface hidhost
08-25 21:50:37.641  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.642  7094  7094 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 21:50:37.642  4386  7620 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 21:50:37.642  4386  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.642  4386  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 21:50:37.643  7094  7094 D HealthService: Received start request. Starting profile...
08-25 21:50:37.644  7094  7094 I bluedroid-qcom: get_profile_interface health
08-25 21:50:37.644  7094  7094 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 21:50:37.644  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.645  7094  7094 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 21:50:37.645  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 21:50:37.646  7094  7094 D PanService: Received start request. Starting profile...
08-25 21:50:37.646  7094  7094 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 21:50:37.646  7094  7094 I bluedroid-qcom: get_profile_interface pan
,08-25 21:50:37.651  7094  7094 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 21:50:37.651  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.652  7094  7094 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 21:50:37.655  7094  7094 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 21:50:37.656  7094  7094 D BtGatt.GattService: Received start request. Starting profile...
08-25 21:50:37.656  7094  7094 D BtGatt.GattService: start()
08-25 21:50:37.656  7094  7094 I bluedroid-qcom: get_profile_interface gatt
08-25 21:50:37.656  7094  7094 D BtGatt.AdvertiseManager: advertise manager created
08-25 21:50:37.660  7065  7627 W FormManager: Network not available. Please check & try again.
,08-25 21:50:37.660  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.661  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.661  7094  7094 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 21:50:37.662  7094  7094 V BluetoothMapService: BluetoothMapBinder()
08-25 21:50:37.662  7094  7094 D BluetoothMapService: Received start request. Starting profile...
08-25 21:50:37.662  7094  7094 D BluetoothMapService: start()
08-25 21:50:37.666  7065  7628 V FormManager: Network unavailable.
08-25 21:50:37.666  7199  7625 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:37.667  7094  7094 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 21:50:37.667  7094  7094 D BluetoothMapEmailAppObserver: createReceiver()
08-25 21:50:37.670  7094  7094 D BluetoothMapEmailAppObserver: initObservers()
08-25 21:50:37.670  7094  7094 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 21:50:37.670  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 21:50:37.670  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:37.670  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 21:50:37.670  7065  7628 V FormManager: Network unavailable.
08-25 21:50:37.673  7236  7236 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 21:50:37.674  7236  7236 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 21:50:37.676  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:37.676  7094  7094 D HeadsetStateMachine: Proxy object connected
08-25 21:50:37.676  7094  7094 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 21:50:37.677  7094  7094 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 21:50:37.679  7094  7094 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 21:50:37.680  7094  7585 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 21:50:37.680  7094  7585 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 21:50:37.680  7094  7585 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 21:50:37.683  7094  7094 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 21:50:37.685  7094  7094 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 21:50:37.688  7094  7094 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 21:50:37.688  7094  7094 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 21:50:37.691  7094  7094 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 21:50:37.691  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:37
08-25 21:50:37.692  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 21:50:37.692  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
08-25 21:50:37.693  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 21:50:37.693  7094  7094 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-25 21:50:37.693  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 21:50:37.693  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@21a4610a
08-25 21:50:37.693  7094  7094 V BluetoothMapService: Handler(): got msg=1
08-25 21:50:37.694  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 21:50:37.694  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 21:50:37.694  7297  7297 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 21:50:37.694  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 21:50:37.694  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:50:37
08-25 21:50:37.694  7094  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 21:50:37.694  7094  7562 I bluedroid-qcom: enable
08-25 21:50:37.695  7094  7632 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 21:50:37.695  7094  7562 I bt_hci_bdroid: init
08-25 21:50:37.695  7094  7562 I bt_vendor: bt-vendor : init
08-25 21:50:37.695  7094  7562 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 21:50:37.695  7094  7562 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 21:50:37.695  7094  7562 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 21:50:37.695  7094  7562 D bt_userial_mct: userial_init
08-25 21:50:37.695  7094  7562 D bt_hci_bdroid: set_power 1
08-25 21:50:37.695  7094  7562 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 21:50:37.696  7094  7562 I bt_vendor: Starting hciattach daemon
08-25 21:50:37.696  7094  7562 I bt_vendor: try to set true
08-25 21:50:37.696  7094  7632 I bt-btu  : btu_task pending for preload complete event
08-25 21:50:37.691  7635  7635 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:37.698  7094  7094 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:37.691  7635  7635 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 21:50:37.701  7094  7094 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 21:50:37.701  7094  7094 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 21:50:37.701  7094  7094 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 21:50:37.701  7094  7094 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:37.701  7094  7094 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 21:50:37.712  7636  7636 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 21:50:37.760  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 21:50:37.769  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 21:50:37.786  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 21:50:37.800  7646  7646 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 21:50:37.816  7647  7647 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 21:50:37.836  7648  7648 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 21:50:37.862  7650  7650 I libmdmdetect: ESOC framework not supported
08-25 21:50:37.863  7650  7650 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 21:50:37.872  7650  7650 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-25 21:50:37.872  7650  7650 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 21:50:37.872  7650  7650 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 21:50:37.872  7650  7650 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 21:50:37.872  7650  7650 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 21:50:37.872  7650  7650 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 21:50:37.872  7650  7650 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 21:50:37.915  7650  7651 E QC-QMI  : qmi_client [7650] 14: failed to locate client data
08-25 21:50:37.916   473   473 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 21:50:37.917   473   473 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-25 21:50:37.999  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 21:50:38.026  7656  7656 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 21:50:38.049  7094  7562 I bt_vendor: bluetooth satus is on
,08-25 21:50:38.049  7094  7562 D bt_hci_bdroid: preload
08-25 21:50:38.050  7094  7634 D bt_userial_mct: userial_open(port:0)
08-25 21:50:38.050  7094  7634 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 21:50:38.054  7094  7634 I bt_vendor: Done intiailizing UART
08-25 21:50:38.058  7094  7634 I bt_vendor: Done intiailizing UART
08-25 21:50:38.058  7094  7634 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 21:50:38.059  7094  7634 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 21:50:38.059  7094  7661 D bt_userial_mct: Entering userial_read_thread()
08-25 21:50:38.060  7094  7632 I bt-btu  : btu_task received preload complete event
,08-25 21:50:38.061  7094  7632 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 21:50:38.061  7094  7632 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 21:50:38.067  7094  7632 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 21:50:38.074  7094  7632 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 21:50:38.165  7094  7632 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 21:50:38.165  7094  7632 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa023d061 
08-25 21:50:38.165  7094  7632 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa023d061 
,08-25 21:50:38.184  7094  7566 E bt-btif : Calling BTA_HhEnable
08-25 21:50:38.184  7094  7566 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 21:50:38.184  7094  7566 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 21:50:38.188  7094  7632 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 21:50:38.188  7094  7632 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 21:50:38.188  7094  7632 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 21:50:38.189  7094  7632 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 21:50:38.189  7094  7632 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 21:50:38.190  7094  7566 D BluetoothAdapterProperties: Name is: G3
08-25 21:50:38.191  7094  7566 D BluetoothAdapterProperties: Scan Mode:20
08-25 21:50:38.191  7094  7566 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 21:50:38.191  7094  7566 D bt_hci_bdroid: postload
08-25 21:50:38.192  7094  7634 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 21:50:38.192  7094  7634 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 21:50:38.193  7094  7632 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 21:50:38.193  7094  7634 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 21:50:38.193  7094  7634 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 21:50:38.194  7094  7566 D bte_conf: Device ID record 1 : primary
08-25 21:50:38.194  7094  7634 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 21:50:38.195  7094  7566 D bte_conf:   vendorId            = 00c4
08-25 21:50:38.195  7094  7566 D bte_conf:   vendorIdSource      = 0001
08-25 21:50:38.195  7094  7566 D bte_conf:   product             = 13a1
08-25 21:50:38.195  7094  7566 D bte_conf:   version             = 1000
08-25 21:50:38.195  7094  7566 D bte_conf:   clientExecutableURL = 
08-25 21:50:38.195  7094  7566 D bte_conf:   serviceDescription  = 
08-25 21:50:38.195  7094  7566 D bte_conf:   documentationURL    = 
08-25 21:50:38.195  7094  7566 D bte_conf: bte_load_did_conf no section named DID2.
08-25 21:50:38.195  7094  7661 E bt_mct  : hci lib postload completed
08-25 21:50:38.199  7094  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 21:50:38.199  7094  7562 D BluetoothAdapterProperties: ScanMode =  20
08-25 21:50:38.199  7094  7562 D BluetoothAdapterProperties: State =  11
08-25 21:50:38.199  7094  7562 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 21:50:38.199  7094  7562 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 21:50:38.199  7094  7562 D BluetoothAdapterProperties: Setting state to 12
08-25 21:50:38.199  7094  7562 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 21:50:38.206  7094  7566 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 21:50:38.206  7094  7566 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 21:50:38.201  7666  7666 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:38.209  1034  1096 D BluetoothManagerService: Message: 60
08-25 21:50:38.209  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 21:50:38.209  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-25 21:50:38.209  7094  7632 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 21:50:38.209  7094  7632 W bt-smp  : Plain text(LSB ~ MSB) = 1d be 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 21:50:38.209  7094  7632 W bt-smp  : Encrypted text(LSB ~ MSB) = 32 ec d5 f3 ac d9 56 4c 48 cd 6c a0 dc ae bd 4a 
08-25 21:50:38.210  7094  7632 W bt-btm  : Stopping oneshot timer
08-25 21:50:38.201  7666  7666 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:38.227  7094  7562 I BluetoothAdapterState: Entering On State
,08-25 21:50:38.234  7094  7562 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 21:50:38.234  7094  7562 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 21:50:38.234  7094  7562 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 21:50:38.237  7094  7562 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 21:50:38.272  7094  7566 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 21:50:38.272  7094  7566 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-25 21:50:38.286  7094  7562 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-25 21:50:38.289  7094  7632 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 21:50:38.289  7094  7632 W bt-smp  : Plain text(LSB ~ MSB) = ac 0a 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 21:50:38.289  7094  7632 W bt-smp  : Encrypted text(LSB ~ MSB) = f7 82 f6 29 78 cf 34 8c fd 8f b4 db fc db 33 2e 
08-25 21:50:38.289  7094  7632 W bt-btm  : Stopping oneshot timer
08-25 21:50:38.302  7671  7671 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-25 21:50:38.317  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7568
08-25 21:50:38.317  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7569
,08-25 21:50:38.320  7094  7632 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 21:50:38.320  7094  7632 W bt-smp  : Plain text(LSB ~ MSB) = a5 6e 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 21:50:38.320  7094  7632 W bt-smp  : Encrypted text(LSB ~ MSB) = 56 23 6a 6a f7 72 4a 5e f2 2c cb 43 36 bf 8e 31 
08-25 21:50:38.320  7094  7632 W bt-btm  : Stopping oneshot timer
08-25 21:50:38.321  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7580
08-25 21:50:38.321  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7584
,08-25 21:50:38.323  1034  1092 W ProcessCpuTracker: Skipping unknown process pid 7662
08-25 21:50:38.327  6975  6992 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 21:50:38.338  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 21:50:38.339  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 21:50:38.341  7094  7632 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-25 21:50:38.341  7094  7632 W bt-smp  : Plain text(LSB ~ MSB) = dc 7b 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 21:50:38.341  7094  7632 W bt-smp  : Encrypted text(LSB ~ MSB) = 76 56 be 44 8e bd d7 d5 c9 68 e8 3a 42 2c 9a a6 
08-25 21:50:38.341  7094  7632 W bt-btm  : Stopping oneshot timer
08-25 21:50:38.344  6975  6991 D BluetoothMap: onBluetoothStateChange: up=true
08-25 21:50:38.349  6975  6975 D BluetoothInputDevice: Proxy object connected
08-25 21:50:38.349  6975  6975 D HidProfile: Bluetooth service connected
08-25 21:50:38.350  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:38.350  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:38.350  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:38.350  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:38.350  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:38.350  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:38.350  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:38.350  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:38.352  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:38.354  7094  7632 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 21:50:38.354  7094  7632 W bt-smp  : Plain text(LSB ~ MSB) = d9 09 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 21:50:38.354  7094  7632 W bt-smp  : Encrypted text(LSB ~ MSB) = 2d 8d 2c 9a a9 6b 2f 65 29 c5 b4 d6 b6 ae 54 47 
08-25 21:50:38.354  7094  7632 W bt-btm  : Stopping oneshot timer
,08-25 21:50:38.356  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:38.356  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:38.356  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:38.356  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:38.356  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:38.356  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:38.356  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:38.356  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:38.359  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:38.362  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 21:50:38.364  1851  3550 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:50:38.365  1034  1034 D BluetoothA2dp: Proxy object connected
08-25 21:50:38.368  6975  6975 D BluetoothMap: Proxy object connected
,08-25 21:50:38.368  6975  6975 D MapProfile: Bluetooth service connected
08-25 21:50:38.368  6975  6975 D BluetoothMap: getConnectedDevices()
08-25 21:50:38.368  1851  2395 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:50:38.371  1851  1851 D BluetoothHeadset: Proxy object connected
08-25 21:50:38.371  1851  1851 D BluetoothHeadset: Proxy object connected
08-25 21:50:38.372  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:50:38.372  7094  7112 V BluetoothMapService: getConnectedDevices()
08-25 21:50:38.374  1851  1851 D BluetoothHeadset: Proxy object connected
08-25 21:50:38.375  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:50:38.376  1034  1034 D BluetoothHeadset: Proxy object connected
08-25 21:50:38.381  6975  7681 D BluetoothPan: onBluetoothStateChange on: true
08-25 21:50:38.381  6975  7681 D BluetoothPan: onBluetoothStateChange call bindService
,08-25 21:50:38.384  6975  6992 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 21:50:38.384  6975  6975 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:50:38.384  6975  6975 D PanProfile: Bluetooth service connected
08-25 21:50:38.388  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 21:50:38.388  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 21:50:38.389  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 21:50:38.390  1034  1096 D BluetoothManagerService: Message: 40
08-25 21:50:38.390  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 21:50:38.390  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 21:50:38.392  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:38.393  1942  2137 D LGBluetoothAPIService: Message: 1
08-25 21:50:38.393  1942  2137 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-25 21:50:38.397  6856  6856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 21:50:38.400  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:38.403  1942  2137 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-25 21:50:38.405  6975  6975 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 21:50:38.405  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:38.405  7094  7094 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:38.405  7094  7094 D BluetoothMapService: STATE_ON
08-25 21:50:38.407  1034  1096 D BluetoothManagerService: Message: 30
08-25 21:50:38.409  7094  7094 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 21:50:38.409  7094  7094 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 21:50:38.410  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 21:50:38.411  1942  2137 D LGBluetoothAPIService: Message: 100
08-25 21:50:38.411  1942  2137 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-25 21:50:38.413  6975  6975 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-25 21:50:38.416  1034  1096 D BluetoothManagerService: Message: 30
08-25 21:50:38.420  6975  6975 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 21:50:38.423  6975  6975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 21:50:38.429  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:38.429  7094  7094 V BluetoothPbapService: Pbap Service onCreate
08-25 21:50:38.429  7094  7094 V BluetoothPbapService: Starting PBAP service
08-25 21:50:38.430  7094  7094 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 21:50:38.430  7094  7094 V BluetoothPbapService: Pbap Service onBind
08-25 21:50:38.429  6975  6975 D BluetoothA2dp: Proxy object connected
08-25 21:50:38.431  7094  7094 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:38.431  7094  7094 V BluetoothPbapService: state: 12
08-25 21:50:38.432  7094  7094 V BluetoothMapService: Handler(): got msg=1
08-25 21:50:38.432  7094  7094 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 21:50:38.433  7094  7094 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 21:50:38.433  7094  7094 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:38.433  7094  7094 V BluetoothPbapReceiver: ***********state = 12
08-25 21:50:38.433  7094  7691 D BluetoothMapMasInstance: MAS initSocket()
08-25 21:50:38.434  6975  6975 D A2dpProfile: Bluetooth service connected
08-25 21:50:38.434  7094  7691 D BluetoothMapMasInstance:   masId = 00
08-25 21:50:38.434  7094  7691 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 21:50:38.434  7094  7691 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 21:50:38.434  7094  7691 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 21:50:38.434  7094  7094 V BluetoothPbapService: Handler(): got msg=1
08-25 21:50:38.435  7094  7094 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-25 21:50:38.436  7094  7692 V BluetoothPbapService: Pbap Service initSocket
08-25 21:50:38.438  1034  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:38.438  1034  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:38.438  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:50:38.438  6975  6975 D BluetoothHeadset: Proxy object connected
08-25 21:50:38.439  2186  2186 D c       : Getting all permits...
08-25 21:50:38.439  2186  2186 D a       : Opening database...
08-25 21:50:38.439  6975  6975 D HeadsetProfile: Bluetooth service connected
08-25 21:50:38.442  7094  7691 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:50:38.442  7094  7692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:50:38.442  2186  2186 D a       : Opening database auth.proximity.permit_store...
08-25 21:50:38.443  2186  2186 D a       : Closing database...
08-25 21:50:38.445  7094  7692 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-25 21:50:38.445  7094  7692 V BluetoothPbapService: Succeed to create listening socket 
08-25 21:50:38.445  7094  7692 V BluetoothPbapService: Accepting socket connection...
,08-25 21:50:38.445  7094  7566 D BluetoothAdapterProperties: Scan Mode:21
08-25 21:50:38.445  7094  7691 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 21:50:38.445  7094  7691 D BluetoothMapMasInstance: Accepting socket connection...
08-25 21:50:38.445  7094  7566 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 21:50:38.454  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:38.456  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:38.459  6975  6975 D DockEventReceiver: finishStartingService: stopping service
08-25 21:50:38.459  6975  6975 D BluetoothPbap: Proxy object connected
08-25 21:50:38.460  6975  6975 D PbapServerProfile: Bluetooth service connected
,08-25 21:50:38.465  6975  6975 D BluetoothPermissionRequest: onReceive
08-25 21:50:38.467  6975  6975 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 21:50:38.469  6975  6975 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 21:50:38.472  7094  7094 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-25 21:50:38.474  7094  7094 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 21:50:38.482  7094  7094 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-25 21:50:38.506  7094  7094 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 21:50:38.507  7094  7094 V BtOppService: onCreate
08-25 21:50:38.511  7094  7094 V BluetoothOppNotification: send message
08-25 21:50:38.514  7094  7094 V BtOppService: Starting RfcommListener
08-25 21:50:38.518  7094  7094 D BluetoothOppPreference: Dumping Names:  
08-25 21:50:38.518  7094  7094 D BluetoothOppPreference: {}
,08-25 21:50:38.518  7094  7094 D BluetoothOppPreference: Dumping Channels:  
08-25 21:50:38.518  7094  7094 D BluetoothOppPreference: {}
08-25 21:50:38.519  7094  7094 V BtOppService: onStartCommand
08-25 21:50:38.520  7094  7699 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 21:50:38.523  7094  7094 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:38.524  7094  7094 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 21:50:38.525  7094  7699 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 21:50:38.525  7094  7696 V BtOppService: Deleted complete outbound shares, number =  0
08-25 21:50:38.527  7094  7094 V BluetoothOppNotification: new notify threadi!
08-25 21:50:38.528  7094  7094 V BluetoothOppNotification: send delay message
08-25 21:50:38.528  7094  7696 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 21:50:38.529  7094  7696 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-25 21:50:38.530  7094  7094 V BtOppService: start RfcommListener
08-25 21:50:38.530  7094  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-25 21:50:38.532  7094  7696 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@168c6127 on behalf of 
08-25 21:50:38.532  7094  7699 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a896fd4 on behalf of 
08-25 21:50:38.533  7094  7094 V BtOppService: RfcommListener started
08-25 21:50:38.534  7094  7094 V BtOppService: ContentObserver received notification
08-25 21:50:38.537  7094  7701 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 21:50:38.538  7094  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e8f657d on behalf of 
08-25 21:50:38.538  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:38.539  7094  7701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:50:38.540  7094  7701 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=75
08-25 21:50:38.540  7094  7701 V BtOppRfcommListener: Started RFCOMM listener....
08-25 21:50:38.540  7094  7701 I BtOppRfcommListener: Accept thread started.
08-25 21:50:38.541  7094  7701 V BtOppRfcommListener: Accepting connection...
,08-25 21:50:38.545  7094  7700 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 21:50:38.545  7094  7699 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 21:50:38.545  7094  7699 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 21:50:38.547  7094  7699 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fa87c72 on behalf of 
08-25 21:50:38.547  7094  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 21:50:38.548  7094  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d3e8c3 on behalf of 
08-25 21:50:38.548  7094  7699 V BluetoothOppNotification: update too frequent, put in queue
08-25 21:50:38.549  7094  7700 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 21:50:38.550  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:38.550  7094  7699 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-25 21:50:38.550  7094  7094 V BluetoothFtpService: Ftp Service onCreate
08-25 21:50:38.550  7094  7094 I BluetoothFtpService: Ftp Service onCreate
08-25 21:50:38.551  7094  7094 V BluetoothFtpService: Ftp Service onStartCommand
08-25 21:50:38.551  7094  7094 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:38.551  7094  7094 V BluetoothFtpService: Starting Listening on sockets
08-25 21:50:38.551  7094  7094 V BtOppService: ContentObserver received notification
08-25 21:50:38.551  7094  7700 V BluetoothOppNotification: outbound notification was removed.
08-25 21:50:38.551  7094  7094 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 21:50:38.552  7094  7094 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 21:50:38.552  7094  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 21:50:38.552  7094  7094 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 21:50:38.552  7094  7094 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:38.552  7094  7094 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 21:50:38.552  7094  7094 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 21:50:38.553  7094  7702 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 21:50:38.553  7094  7702 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 21:50:38.555  7094  7094 V BluetoothFtpService: Handler(): got msg=1
,08-25 21:50:38.559  7094  7094 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 21:50:38.559  7094  7094 V BluetoothFtpService: Ftp Service initSocket
08-25 21:50:38.564  7094  7702 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@831dc79 on behalf of 
08-25 21:50:38.564  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:38.564  7094  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2cfdedbe on behalf of 
08-25 21:50:38.564  7094  7702 V BluetoothOppNotification: update too frequent, put in queue
08-25 21:50:38.565  7094  7094 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:50:38.566  7094  7702 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 21:50:38.566  7094  7094 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-25 21:50:38.566  7094  7094 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 21:50:38.567  7094  7700 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 21:50:38.568  7094  7703 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-25 21:50:38.570  7094  7700 V BluetoothOppNotification: inbound notification was removed.
08-25 21:50:38.570  7094  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 21:50:38.584  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
,08-25 21:50:38.584  7094  7094 V BluetoothSapService: Sap Service onCreate
08-25 21:50:38.698  1034  1923 I art     : Explicit concurrent mark sweep GC freed 93828(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.901ms total 124.559ms
08-25 21:50:38.698  7094  7094 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:38.698  7094  7094 V BluetoothSapService: state: 12
08-25 21:50:38.698  7094  7094 V BluetoothSapService: Starting SAP server process
,08-25 21:50:38.700  7094  7094 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 21:50:38.701  7332  7369 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-25 21:50:38.702  7094  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a727ca on behalf of 
08-25 21:50:38.705  7094  7706 V BluetoothSapService: Sap Service initRfcommSocket
08-25 21:50:38.706  1034  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:38.701  7707  7707 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:38.701  7707  7707 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:38.708  7094  7706 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:50:38.714  7094  7706 V BluetoothSapService: Succeed to create listening socket 
08-25 21:50:38.715  7094  7706 V BluetoothSapService: Accepting socket connection...
,08-25 21:50:38.728  7707  7707 V BT_SAP  : Event pipe created
08-25 21:50:38.728  7707  7707 V BT_SAP  : create_server_socket qcom.sap.server
08-25 21:50:38.728  7707  7707 V BT_SAP  : created socket fd 6
,08-25 21:50:39.216  1034  1535 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 21:50:39.216  1034  1535 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 21:50:39.265  1034  1536 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 21:50:39.266  1034  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 21:50:39.428  1034  1923 I ActivityManager: Killing 7491:com.lge.bnr/1000 (adj 15): empty #17
,08-25 21:50:39.460  1034  1977 W libprocessgroup: failed to open /acct/uid_1000/pid_7491/cgroup.procs: No such file or directory
,08-25 21:50:39.530  7094  7094 V BluetoothOppNotification: new notify threadi!
,08-25 21:50:39.530  7094  7094 V BluetoothOppNotification: send delay message
,08-25 21:50:39.551  1034  1885 I ActivityManager: Killing 6789:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-25 21:50:39.561  7094  7718 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 21:50:39.569  7094  7718 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f87ad3b on behalf of 
08-25 21:50:39.570  7094  7718 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 21:50:39.579  7025  7025 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-25 21:50:39.579  7025  7025 W System.err: android.os.DeadObjectException
08-25 21:50:39.580  7025  7025 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 21:50:39.580  7025  7025 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 21:50:39.580  7025  7025 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-25 21:50:39.580  7025  7025 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-25 21:50:39.580  7025  7025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 21:50:39.580  7025  7025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 21:50:39.580  7025  7025 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 21:50:39.580  7025  7025 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 21:50:39.580  7025  7025 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 21:50:39.580  7025  7025 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 21:50:39.580  7025  7025 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:50:39.580  7025  7025 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:50:39.580  7025  7025 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 21:50:39.580  7025  7025 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 21:50:39.581  7025  7025 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-25 21:50:39.581  7025  7025 W System.err: android.os.DeadObjectException
08-25 21:50:39.581  7025  7025 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 21:50:39.581  7025  7025 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 21:50:39.581  7025  7025 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-25 21:50:39.581  7025  7025 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-25 21:50:39.582  7025  7025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 21:50:39.582  7025  7025 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 21:50:39.582  7025  7025 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 21:50:39.582  7025  7025 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 21:50:39.582  7025  7025 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 21:50:39.582  7025  7025 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 21:50:39.582  7025  7025 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:50:39.583  7025  7025 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:50:39.583  7025  7025 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 21:50:39.583  7025  7025 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 21:50:39.583  7025  7025 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-25 21:50:39.583  7025  7025 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-25 21:50:39.589  7094  7718 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 21:50:39.591  7094  7718 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a2eec58 on behalf of 
08-25 21:50:39.592  7094  7718 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 21:50:39.593  7094  7718 V BluetoothOppNotification: outbound notification was removed.
08-25 21:50:39.595  7094  7718 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 21:50:39.596  7094  7718 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@360da1b1 on behalf of 
08-25 21:50:39.596  7094  7718 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 21:50:39.600  7094  7718 V BluetoothOppNotification: inbound notification was removed.
08-25 21:50:39.601  7094  7718 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 21:50:39.602  7094  7718 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2af7f696 on behalf of 
08-25 21:50:39.605  1034  1922 W libprocessgroup: failed to open /acct/uid_1000/pid_6789/cgroup.procs: No such file or directory
08-25 21:50:39.605  1034  1922 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-25 21:50:39.609  7025  7025 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-25 21:50:39.609  7025  7025 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 21:50:39.649  1034  1730 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7719 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 21:50:39.649  7025  7025 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-25 21:50:39.742  7719  7719 D UEI.SmartControl: Quickset Services start...
,08-25 21:50:39.747  7719  7719 I UEI.SmartControl: Manufacture = LGE
,08-25 21:50:39.747  7719  7719 D UEI.SmartControl: Id = LGNevo
08-25 21:50:39.749  7719  7719 D UEI.SmartControl: File observer start...
08-25 21:50:39.749  7719  7719 E UEI.SmartControl: IR Port is disabled: false
08-25 21:50:39.750  7719  7719 D UEI.SmartControl: Starting file observer...
08-25 21:50:39.750  7719  7719 D UEI.SmartControl: Extracting JNI libs...
08-25 21:50:39.750  7719  7719 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-25 21:50:39.849  7719  7719 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-25 21:50:39.849  7719  7719 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-25 21:50:39.849  7719  7719 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-25 21:50:39.892  7719  7719 I UEI.SmartControl: --- Selecting new region: 6
,08-25 21:50:39.896  7719  7719 I UEI.SmartControl: Model = LG-D855
,08-25 21:50:39.898  7719  7719 D UEI.SmartControl: QS Service created
08-25 21:50:39.916  7719  7719 I UEI.SmartControl: Service initServices...
,08-25 21:50:39.923  7719  7719 D UEI.SmartControl: QS start get config
08-25 21:50:40.000  7719  7719 D UEI.SmartControl: Loading JNI Libs...
,08-25 21:50:40.227  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:40.227  1034  1050 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@12938950 mBinding = false
,08-25 21:50:40.254  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 21:50:40.255  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 21:50:40.255  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 21:50:40.256  1034  1096 D BluetoothManagerService: Message: 2
08-25 21:50:40.257  1034  1096 D BluetoothManagerService: Sending off request.
08-25 21:50:40.257  7094  7689 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 21:50:40.258  7094  7562 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 21:50:40.258  7094  7562 D BluetoothAdapterProperties: Setting state to 13
08-25 21:50:40.258  7094  7562 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 21:50:40.259  7094  7562 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 21:50:40.259  7094  7562 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 21:50:40.260  1034  1096 D BluetoothManagerService: Message: 60
08-25 21:50:40.260  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 21:50:40.260  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 21:50:40.261  7094  7566 D BluetoothAdapterProperties: Scan Mode:20
08-25 21:50:40.261  7094  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 21:50:40.262  7094  7562 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 21:50:40.263  7094  7691 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 21:50:40.263  7094  7691 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:40.263  7094  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 21:50:40.263  7094  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 21:50:40.263  7094  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 21:50:40.263  7094  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 21:50:40.263  7094  7691 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 21:50:40.263  7094  7691 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 21:50:40.264  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 21:50:40.264  7094  7632 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 21:50:40.266  7094  7692 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:40.266  7094  7701 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:40.267  7094  7703 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:40.267  7094  7706 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:50:40.275  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 21:50:40.276  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 21:50:40.276  7094  7632 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 21:50:40.279  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is ,disabled - will return stored value
08-25 21:50:40.279  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:40.279  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:40.279  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:40.279  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:40.279  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:40.279  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:40.279  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:40.279  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:40.280  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:40.280  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:40.282  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:40.282  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:40.282  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:40.282  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:40.282  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:40.282  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:50:40.282  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:40.282  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:40.282  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:40.283  6856  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:50:40.283  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:50:40.288  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:40.291  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 21:50:40.292  7094  7094 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:40.292  7094  7094 D BluetoothMapService: STATE_TURNING_OFF
08-25 21:50:40.292  7094  7094 V BluetoothMapService: Handler(): got msg=4
08-25 21:50:40.292  7094  7094 D BluetoothMapService: MAP Service closeService in
08-25 21:50:40.292  7094  7094 D BluetoothMapMasInstance: MAP Service shutdown
08-25 21:50:40.292  7094  7094 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 21:50:40.292  7094  7094 V BluetoothMapService: MAP Service closeService out
08-25 21:50:40.294  6975  6975 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-25 21:50:40.294  7094  7094 V BtOppService: Receiver DISABLED_ACTION 
08-25 21:50:40.294  7094  7094 I BtOppRfcommListener: stopping Accept Thread
08-25 21:50:40.294  7094  7094 V BtOppRfcommListener: close mBtServerSocket
08-25 21:50:40.294  7094  7094 V BtOppRfcommListener: waiting for thread to terminate
08-25 21:50:40.294  7094  7701 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 21:50:40.295  7094  7094 V BtOppRfcommListener: done waiting for thread to terminate
08-25 21:50:40.297  7094  7094 V BtOppService: onDestroy
,08-25 21:50:40.299  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:40.300  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:40.300  7094  7094 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 21:50:40.307  6975  6975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 21:50:40.313  7094  7094 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 21:50:40.313  7094  7094 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:40.313  7094  7094 V BluetoothPbapReceiver: ***********state = 13
08-25 21:50:40.317  7094  7094 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-25 21:50:40.318  7094  7094 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:40.318  7094  7094 V BluetoothPbapService: state: 13
08-25 21:50:40.318  7094  7094 V BluetoothPbapService: Pbap Service closeService in
,08-25 21:50:40.322  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:50:40.323  6975  6975 D DockEventReceiver: finishStartingService: stopping service
08-25 21:50:40.323  7094  7094 V BluetoothPbapService: successfully stopped pbap service
08-25 21:50:40.323  7094  7094 V BluetoothPbapService: Pbap Service closeService out
08-25 21:50:40.324  7094  7094 V BluetoothPbapService: Pbap Service onDestroy
08-25 21:50:40.324  7094  7094 V BluetoothPbapService: Pbap Service closeService in
08-25 21:50:40.324  7094  7094 V BluetoothPbapService: Pbap Service closeService out
08-25 21:50:40.324  7094  7094 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 21:50:40.324  6975  6975 D BluetoothPbap: Proxy object disconnected
08-25 21:50:40.324  6975  6975 D PbapServerProfile: Bluetooth service disconnected
,08-25 21:50:40.337  6975  6975 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 21:50:40.341  6975  6975 D BluetoothPermissionRequest: onReceive
,08-25 21:50:40.341  6975  6975 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 21:50:40.345  6975  6975 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 21:50:40.350  7094  7094 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 21:50:40.350  7094  7094 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 21:50:40.351  7094  7094 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-25 21:50:40.357  7094  7094 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:40.357  7094  7094 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 21:50:40.358  7094  7094 V BluetoothFtpService: Ftp Service onStartCommand
08-25 21:50:40.358  7094  7094 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:40.358  7094  7094 V BluetoothFtpService: Ftp Service closeService
08-25 21:50:40.358  7094  7094 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 21:50:40.360  7094  7094 V BluetoothFtpService: successfully stopped ftp service
08-25 21:50:40.360  7094  7094 V BluetoothFtpService: Ftp Service onDestroy
08-25 21:50:40.360  7094  7094 V BluetoothFtpService: Ftp Service closeService
08-25 21:50:40.362  7094  7094 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 21:50:40.362  7094  7094 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 21:50:40.362  7094  7094 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 21:50:40.362  7094  7094 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:40.362  7094  7094 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 21:50:40.362  7094  7094 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 21:50:40.365  7094  7094 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:40.365  7094  7094 V BluetoothSapService: state: 13
08-25 21:50:40.365  7094  7094 V BluetoothSapService: Stopping SAP server process
08-25 21:50:40.366  7094  7094 V BluetoothSapService: Sap Service closeSapService in
08-25 21:50:40.366  7094  7094 V BluetoothSapService: Close listen Socket : 
08-25 21:50:40.367  7094  7094 V BluetoothSapService: Close rfcomm Socket : 
08-25 21:50:40.367  7094  7094 V BluetoothSapService: Close sapd  Socket : 
,08-25 21:50:40.371  7094  7094 V BluetoothSapService: Sap Service closeSapService out
08-25 21:50:40.372  7094  7094 V BluetoothSapService: Sap Service onDestroy
08-25 21:50:40.372  7094  7094 V BluetoothSapService: Sap Service closeSapService in
08-25 21:50:40.372  7094  7094 V BluetoothSapService: Close listen Socket : 
08-25 21:50:40.372  7094  7094 V BluetoothSapService: Close rfcomm Socket : 
08-25 21:50:40.372  7094  7094 V BluetoothSapService: Close sapd  Socket : 
08-25 21:50:40.372  7094  7094 V BluetoothSapService: Sap Service closeSapService out
08-25 21:50:40.436  7719  7719 I UEI.SmartControl: Supports setup maps: true
,08-25 21:50:40.441  7719  7719 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 21:50:40.441  7719  7719 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 21:50:40.441  7719  7719 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 21:50:40.441  7719  7719 I UEI.SmartControl: ### init IR Blaster...
08-25 21:50:40.449  7719  7719 D serial_port: Configuring serial port
,08-25 21:50:40.452  7719  7719 E UEI.SmartControl: UEIBLaster setting for 616
,08-25 21:50:40.452  7719  7719 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 21:50:40.453  7719  7719 I UEI.SmartControl: configuring settings for MAXQ616
08-25 21:50:40.453  7719  7719 I UEI.SmartControl: Get version...
08-25 21:50:40.470  7719  7764 D UEI.SmartControl: serial port data available: 21
,08-25 21:50:40.499  7719  7719 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 21:50:40.499  7719  7719 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 21:50:40.500  7719  7719 I UEI.SmartControl: QS saving settings...
08-25 21:50:40.502  7719  7719 D UEI.SmartControl: IR Blaster version: 25672567
08-25 21:50:40.519  7719  7764 D UEI.SmartControl: serial port data available: 4
,08-25 21:50:40.561  7719  7767 I UEI.SmartControl: Device manager: loading config....
08-25 21:50:40.563  7719  7767 D UEI.SmartControl: ----------- loading internal config...
,08-25 21:50:40.565  7719  7719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 21:50:40.569  7719  7719 E UEI.SmartControl: Services init done
08-25 21:50:40.569  7719  7719 D UEI.SmartControl: QS Service init finished
08-25 21:50:40.572  7719  7719 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 21:50:40.572  7719  7719 D UEI.SmartControl: QS Service version code: 201091
08-25 21:50:40.573  7719  7719 D UEI.SmartControl: Service requested: Control
08-25 21:50:40.582  7719  7767 E UEI.SmartControl: Loading SETTINGS...
,08-25 21:50:40.585  7719  7719 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 21:50:40.590  7025  7025 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 21:50:40.591  1034  1995 I ActivityManager: Killing 7025:com.lge.qremote/u0a112 (adj 15): empty #17
08-25 21:50:40.591  7719  7735 I UEI.SmartControl: ------ IControl API: 11
08-25 21:50:40.593  7719  7735 I UEI.SmartControl: Registering callback...
08-25 21:50:40.595  7719  7767 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 21:50:40.616  7719  7766 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 21:50:40.616  7719  7766 D UEI.SmartControl: -----service ready thread exits
,08-25 21:50:40.655  1034  2033 W libprocessgroup: failed to open /acct/uid_10112/pid_7025/cgroup.procs: No such file or directory
,08-25 21:50:40.657  7719  7719 D UEI.SmartControl: Internal service binding...
,08-25 21:50:41.175  7094  7566 D bt_hci_bdroid: cleanup
,08-25 21:50:41.181  7094  7634 I bt_lpm  : LPM is already off!!!
08-25 21:50:41.181  7094  7661 I bt_userial_mct: exiting userial_read_thread
08-25 21:50:41.181  7094  7661 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 21:50:41.182  7094  7632 W bt-btif : ag scb idx 1 not allocated
08-25 21:50:41.183  7094  7632 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 21:50:41.183  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:41.183  7094  7632 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:50:41.183  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:41.183  7094  7632 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:50:41.183  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:41.183  7094  7632 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:50:41.183  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:41.183  7094  7632 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:50:41.183  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:41.186  7094  7566 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 21:50:41.187  7094  7634 I bt_vendor: hw_epilog_process
08-25 21:50:41.187  7094  7566 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 21:50:41.187  7094  7566 D bt_userial_mct: userial_close
08-25 21:50:41.187  7094  7566 E bt_userial_mct: pthread_join() FAILED result:3
08-25 21:50:41.187  7094  7566 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 21:50:41.187  7094  7632 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:50:41.187  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:41.187  7094  7632 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:50:41.187  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 21:50:41.187  7094  7632 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:50:41.187  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 21:50:41.187  7094  7632 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:50:41.187  7094  7632 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 21:50:41.188  7094  7632 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 21:50:41.188  7094  7632 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 21:50:41.195  7094  7566 D bt_hci_bdroid: set_power 0
08-25 21:50:41.195  7094  7566 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 21:50:41.195  7094  7566 I bt_vendor: bluetooth satus is on
08-25 21:50:41.195  7094  7566 I bt_vendor: bt-vendor : resetting BT status
08-25 21:50:41.195  7094  7566 I bt_vendor: Starting hciattach daemon
08-25 21:50:41.195  7094  7566 I bt_vendor: try to set false
,08-25 21:50:41.202  7094  7566 I bt_vendor: Starting hciattach daemon
08-25 21:50:41.202  7094  7566 I bt_vendor: try to set false
08-25 21:50:41.203  7094  7566 I bt_vendor: cleanup
08-25 21:50:41.204  7094  7632 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 21:50:41.204  7094  7566 I GKI_LINUX: GKI_exit_task 0 done
08-25 21:50:41.204  7094  7566 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 21:50:41.206  7094  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 21:50:41.211  7094  7094 D HeadsetService: Received stop request...Stopping profile...
,08-25 21:50:41.215  7094  7094 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 21:50:41.215  7094  7094 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 21:50:41.216  7094  7585 D HeadsetStateMachine: Exit Disconnected: -1
08-25 21:50:41.218  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:41.221  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-25 21:50:41.221  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-25 21:50:41.221  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-25 21:50:41.222  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-25 21:50:41.222  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 21:50:41.224  7094  7562 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-25 21:50:41.229  7094  7094 D A2dpService: Received stop request...Stopping profile...
08-25 21:50:41.229  7094  7617 D A2dpStateMachine: Exit Disconnected: -1
08-25 21:50:41.231  7094  7094 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 21:50:41.232  7094  7094 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 21:50:41.232  7094  7094 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 21:50:41.232  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:41.234  7094  7094 D HidService: Received stop request...Stopping profile...
08-25 21:50:41.234  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:41.237  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-25 21:50:41.237  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-25 21:50:41.240  7094  7094 D HealthService: Received stop request...Stopping profile...
08-25 21:50:41.240  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:41.242  7094  7094 D PanService: Received stop request...Stopping profile...
08-25 21:50:41.243  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:41.244  7094  7094 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 21:50:41.245  7094  7094 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 21:50:41.245  7094  7094 D BtGatt.GattService: stop()
08-25 21:50:41.245  7094  7094 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 21:50:41.246  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:41.247  7094  7094 D HeadsetStateMachine: Unbinding service...
08-25 21:50:41.248  7094  7094 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 21:50:41.248  7094  7094 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 21:50:41.248  7094  7094 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 21:50:41.248  7094  7094 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 21:50:41.248  7094  7094 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 21:50:41.248  7094  7094 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 21:50:41.248  7094  7094 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 21:50:41.250  7094  7094 D BluetoothMapService: Received stop request...Stopping profile...
08-25 21:50:41.250  7094  7094 D BluetoothMapService: stop()
,08-25 21:50:41.254  7094  7094 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 21:50:41.254  7094  7094 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 21:50:41.255  7094  7094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21a4610a
08-25 21:50:41.256  7094  7094 V BluetoothMapService: Handler(): got msg=4
08-25 21:50:41.256  7094  7094 D BluetoothMapService: MAP Service closeService in
08-25 21:50:41.256  7094  7094 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 21:50:41.256  7094  7094 V BluetoothMapService: MAP Service closeService out
08-25 21:50:41.256  7094  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 21:50:41.256  7094  7562 D BluetoothAdapterProperties: Setting state to 10
08-25 21:50:41.256  7094  7562 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 21:50:41.257  1034  1096 D BluetoothManagerService: Message: 60
08-25 21:50:41.257  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 21:50:41.257  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-25 21:50:41.258  7094  7562 I BluetoothAdapterState: Entering OffState
08-25 21:50:41.258  6975  7681 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 21:50:41.259  6975  7681 D BluetoothMap: onBluetoothStateChange: up=false
08-25 21:50:41.259  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 21:50:41.260  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:50:41.260  1851  3552 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:50:41.261  6975  7681 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 21:50:41.262  1851  3550 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 21:50:41.266  7094  7094 I BluetoothA2dpServiceJni: cleanupNative
08-25 21:50:41.266  7094  7618 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 21:50:41.267  7094  7094 I GKI_LINUX: GKI_exit_task 2 done
08-25 21:50:41.267  7094  7094 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 21:50:41.268  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:50:41.268  6975  7681 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:50:41.269  7094  7094 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 21:50:41.269  7094  7094 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 21:50:41.270  6975  7681 D BluetoothPan: onBluetoothStateChange on: false
08-25 21:50:41.270  7094  7094 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 21:50:41.272  7094  7094 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 21:50:41.272  7094  7094 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 21:50:41.274  6975  7681 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 21:50:41.276  7094  7094 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 21:50:41.276  7094  7094 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 21:50:41.280  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 21:50:41.280  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 21:50:41.282  7094  7094 D BluetoothMapService: cleanup()
08-25 21:50:41.282  7094  7094 D BluetoothMapService: MAP Service closeService in
08-25 21:50:41.282  7094  7094 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 21:50:41.282  7094  7094 V BluetoothMapService: MAP Service closeService out
08-25 21:50:41.284  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 21:50:41.284  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 21:50:41.284  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@12938950 mBinding = false
08-25 21:50:41.285  1034  1096 D BluetoothManagerService: Sending unbind request.
08-25 21:50:41.289  7094  7566 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 21:50:41.292  7094  7094 I GKI_LINUX: GKI_exit_task 1 done
08-25 21:50:41.292  7094  7094 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 21:50:41.292  7094  7094 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 21:50:41.293  7094  7094 I art     : --- WEIRD: removing null entry 248
08-25 21:50:41.293  7094  7094 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-25 21:50:41.293  7094  7094 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 21:50:41.294  7094  7094 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 21:50:41.295  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 21:50:41.297  7094  7094 I art     : System.exit called, status: 0
08-25 21:50:41.297  7094  7094 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 21:50:41.317   310  1383 V AudioFlinger: 7094 died, releasing its sessions
08-25 21:50:41.317   310  1383 V AudioFlinger:  pid 1851 @ 0
08-25 21:50:41.317   310  1383 V AudioFlinger:  pid 3460 @ 1
08-25 21:50:41.317   310  1383 V AudioFlinger:  pid 3460 @ 2
,08-25 21:50:41.321  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-25 21:50:41.321  1942  2137 D LGBluetoothAPIService: Message: 101
08-25 21:50:41.321  1942  2137 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-25 21:50:41.321  1942  2137 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-25 21:50:41.322  1942  2137 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-25 21:50:41.328  6975  6975 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-25 21:50:41.374  1034  1051 I ActivityManager: Process com.android.bluetooth (pid 7094) has died
,08-25 21:50:41.376  1034  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-25 21:50:41.376  1034  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-25 21:50:41.381  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 21:50:41.381  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:41.382  1942  2137 D LGBluetoothAPIService: Message: 2
08-25 21:50:41.382  1942  2137 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-25 21:50:41.383  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:41.384  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:41.385  6975  6975 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 21:50:41.386  6975  6975 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-25 21:50:41.391  6975  6975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 21:50:41.394  1600  1600 D BluetoothAdapter: 327454893: getState() :  mService = null. Returning STATE_OFF
08-25 21:50:41.394  1600  1600 D BluetoothAdapter: 327454893: getState() :  mService = null. Returning STATE_OFF
08-25 21:50:41.440  1034  1050 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7797 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-25 21:50:41.442  6975  6975 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:50:41.509  7797  7797 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 21:50:41.510  7797  7797 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 21:50:41.510  7797  7797 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-25 21:50:41.511  7797  7797 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 21:50:41.549  7797  7797 D BluetoothAdapterApp: Loading JNI Library
,08-25 21:50:41.586  7797  7797 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3214cdb2 Instance Count = 1
,08-25 21:50:41.592  7797  7797 D BluetoothAdapterApp: onCreate
,08-25 21:50:41.619  7797  7797 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 21:50:41.620  7797  7797 D ProfileConfigQcom: Adding HeadsetService
,08-25 21:50:41.620  7797  7797 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 21:50:41.620  7797  7797 D ProfileConfigQcom: Adding A2dpService
08-25 21:50:41.620  7797  7797 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 21:50:41.621  7797  7797 D ProfileConfigQcom: Adding HidService
08-25 21:50:41.621  7797  7797 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 21:50:41.621  7797  7797 D ProfileConfigQcom: Adding HealthService
08-25 21:50:41.621  7797  7797 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 21:50:41.623  7797  7797 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 21:50:41.623  7797  7797 D ProfileConfigQcom: Adding PanService
08-25 21:50:41.623  7797  7797 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 21:50:41.624  7797  7797 D ProfileConfigQcom: Adding GattService
08-25 21:50:41.624  7797  7797 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 21:50:41.624  7797  7797 D ProfileConfigQcom: Adding BluetoothMapService
08-25 21:50:41.625  7797  7797 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 21:50:41.626  7797  7797 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 21:50:41.627  7797  7797 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:41.627  7797  7797 V BluetoothPbapReceiver: ***********state = 10
08-25 21:50:41.629  7797  7797 V LGMDMManagerInternal: Create singleton instance
08-25 21:50:41.721  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:50:41.725  7797  7797 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 21:50:41.725  7797  7797 D LGBluetoothAPIServer: [BTUI] onBind()
,08-25 21:50:41.729  6975  6975 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 21:50:41.730  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 21:50:41.730  1942  2137 D LGBluetoothAPIService: Message: 100
08-25 21:50:41.730  1942  2137 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 21:50:41.741  6975  6975 D BluetoothPermissionRequest: onReceive
,08-25 21:50:41.746  6975  6975 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 21:50:41.746  6975  6975 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 21:50:41.748  6975  6975 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 21:50:41.753  7797  7797 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 21:50:41.757  7797  7797 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:50:41.760  7797  7797 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-25 21:50:41.761  7797  7797 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 21:50:41.761  7797  7797 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 21:50:41.762  7797  7797 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:41.762  7797  7797 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 21:50:41.766  7045  7045 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 21:50:43.277  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:43.277  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:43.382  1600  1600 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-25 21:50:43.433  1034  1471 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 21:50:43.479  1034  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7826 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 21:50:43.486  1600  1600 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-25 21:50:43.494  1600  1600 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-25 21:50:43.520  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 21:50:43.546  1034  1034 D administrator: Handling package changes for user 0
,08-25 21:50:43.584  7826  7826 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 21:50:43.593  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 21:50:43.674  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-25 21:50:43.674  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 21:50:43.678  7826  7826 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:43.679  7826  7826 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 21:50:43.762  7826  7870 I Babel   : MmsConfig: mnc/mcc: 0/0
08-25 21:50:43.762  7826  7870 I Babel   : MmsConfig.loadMmsSettings
08-25 21:50:43.762  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 21:50:43.770  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 21:50:43.779  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 21:50:43.781  2482  2482 V GmsNetworkLocationProvi: DISABLE
,08-25 21:50:43.782  7826  7870 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 21:50:43.782  7826  7870 I Babel   : MmsConfig.loadFromDatabase
,08-25 21:50:43.804  7826  7870 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-25 21:50:43.804  7826  7870 I Babel   : MmsConfig.loadFromResources
08-25 21:50:43.807  7826  7870 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-25 21:50:43.808  7826  7870 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 21:50:43.811  2482  2482 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-25 21:50:43.831  7826  7826 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 21:50:43.839  7826  7869 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 21:50:43.841  7826  7869 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 21:50:43.842  7826  7869 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-25 21:50:43.852  7826  7869 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-25 21:50:43.853  7826  7869 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 21:50:43.857  7826  7869 W AudioCapabilities: Unsupported mime audio/evrc
08-25 21:50:43.858  1815  7875 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-25 21:50:43.858  1815  7875 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-25 21:50:43.862  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 21:50:43.867  1815  4824 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-25 21:50:43.871  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@53aacac
08-25 21:50:43.871  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 21:50:43.872  7166  7166 D AppUp4:CustFacade: isPhone : true
08-25 21:50:43.872  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-25 21:50:43.872  7166  7166 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-25 21:50:43.894  7826  7869 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-25 21:50:43.896  7826  7869 W VideoCapabilities: Unsupported mime video/divx
08-25 21:50:43.897  7826  7869 W VideoCapabilities: Unsupported mime video/divx311
08-25 21:50:43.899  7826  7869 W VideoCapabilities: Unsupported mime video/divx4
08-25 21:50:43.904  7826  7869 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-25 21:50:43.906  1034  1922 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7878 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-25 21:50:43.910  1034  1885 I ActivityManager: Killing 6997:com.lge.sync/1000 (adj 15): empty #17
08-25 21:50:43.922  7826  7869 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 21:50:43.926  7826  7869 W AudioCapabilities: Unsupported mime audio/eac3
08-25 21:50:43.927  7826  7869 W AudioCapabilities: Unsupported mime audio/ac3
08-25 21:50:43.928  7826  7869 W AudioCapabilities: Unsupported mime audio/g726
08-25 21:50:43.931  7826  7869 W AudioCapabilities: Unsupported mime audio/wma-voice
08-25 21:50:43.932  7826  7869 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-25 21:50:43.932  7826  7869 W AudioCapabilities: Unsupported mime audio/adpcm
08-25 21:50:43.934  7826  7869 W VideoCapabilities: Unsupported mime video/theora
,08-25 21:50:43.936  1034  1541 D WifiService: Client connection lost with reason: 4
08-25 21:50:43.936  7826  7869 W VideoCapabilities: Unsupported mime video/mjpg
,08-25 21:50:44.045  1034  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6997/cgroup.procs: No such file or directory
08-25 21:50:44.051  1034  1091 D LocationProviderProxy: applying state to connected service
,08-25 21:50:44.078  7878  7878 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:50:44.078  7878  7878 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 21:50:44.079  7878  7878 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 21:50:44.080  7878  7878 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-25 21:50:44.080  7878  7878 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-25 21:50:44.156  7878  7878 I SystemConfig: BUILD Country: EU
08-25 21:50:44.156  7878  7878 I SystemConfig: BUILD Operator: OPEN
,08-25 21:50:44.223  1034  1573 I ActivityManager: Killing 7199:com.lge.email/u0a23 (adj 15): empty #17
,08-25 21:50:44.313  1034  1923 W libprocessgroup: failed to open /acct/uid_10023/pid_7199/cgroup.procs: No such file or directory
,08-25 21:50:44.332  7878  7896 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-25 21:50:44.332  7878  7896 I SystemConfig: existFile = false
08-25 21:50:44.332  7878  7896 I SystemConfig: canReadFile = false
08-25 21:50:44.332  7878  7896 I SystemConfig: systemFeature RCS result false
08-25 21:50:44.332  7878  7896 D SystemConfig: refreshRcsSupport() :false
,08-25 21:50:44.384  1034  1573 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7898 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-25 21:50:44.412   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 33.080ms
,08-25 21:50:44.433   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 20.049ms
08-25 21:50:44.451   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 372us total 17.437ms
,08-25 21:50:44.452  7898  7898 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:50:44.452  7898  7898 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 21:50:44.453  7898  7898 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 21:50:44.453  7898  7898 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 21:50:44.569  7898  7898 I AppConfig: Total System Memory = 2995761152
,08-25 21:50:44.581  7898  7898 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-25 21:50:44.671  1034  1995 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7920 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 21:50:44.672  1034  1995 I ActivityManager: Killing 7065:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-25 21:50:44.731  1034  1730 W libprocessgroup: failed to open /acct/uid_10026/pid_7065/cgroup.procs: No such file or directory
,08-25 21:50:44.912  7920  7920 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-25 21:50:45.010  7920  7920 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 21:50:45.010  7920  7920 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 21:50:45.064  7920  7920 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-25 21:50:45.084  7920  7920 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 21:50:45.085  7920  7920 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 21:50:45.100  7920  7920 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-25 21:50:45.101  7920  7920 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-25 21:50:45.125  1034  1995 I ActivityManager: Killing 6571:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-25 21:50:45.157  1034  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_6571/cgroup.procs: No such file or directory
,08-25 21:50:45.161  3500  4014 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-25 21:50:45.163  3500  4014 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@9c22810 on behalf of 7920
08-25 21:50:45.167  4646  7960 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-25 21:50:45.202  1034  2210 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7961 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-25 21:50:45.277  7920  7920 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-25 21:50:45.296  7920  7920 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-25 21:50:45.316  7961  7961 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-25 21:50:45.345  7961  7961 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-25 21:50:45.345  7961  7961 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-25 21:50:45.345  7961  7961 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-25 21:50:45.345  7961  7961 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-25 21:50:45.345  7961  7961 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,08-25 21:50:45.345  7961  7961 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-25 21:50:45.365  1034  1573 I ActivityManager: Killing 7236:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-25 21:50:45.423  1034  1977 W libprocessgroup: failed to open /acct/uid_10046/pid_7236/cgroup.procs: No such file or directory
,08-25 21:50:45.559  7719  7768 D UEI.SmartControl: Internal timer expired: 1
08-25 21:50:45.560  7719  7768 D UEI.SmartControl: unbind internal service
,08-25 21:50:45.569  7719  7719 D UEI.SmartControl: Service.onUnbind: IControl
08-25 21:50:45.571  7719  7719 D UEI.SmartControl: Service.onDestroy
08-25 21:50:45.571  7719  7719 D UEI.SmartControl: Lock is in USE false
08-25 21:50:45.571  7719  7719 D UEI.SmartControl: unbind internal service
08-25 21:50:45.575  7719  7719 D serial_port: close(fd = 25)
,08-25 21:50:45.582  7719  7719 I UEI.SmartControl: Serial port is closed.
08-25 21:50:45.582  7719  7719 I UEI.SmartControl: Serial port is closed.
08-25 21:50:45.583  7719  7719 D UEI.SmartControl: Blaster closed
08-25 21:50:45.583  7719  7719 D UEI.SmartControl: Shut down QS...
08-25 21:50:45.584  7719  7719 D UEI.SmartControl: Stopping QS lib
08-25 21:50:45.585  7719  7719 D UEI.SmartControl: QS lib stop result = true
08-25 21:50:45.585  7719  7719 D UEI.SmartControl: Stopped QS lib
08-25 21:50:45.585  7719  7719 D UEI.SmartControl: Stopped file observer...
08-25 21:50:45.585  7719  7719 D UEI.SmartControl: QS shutdown complete
08-25 21:50:45.659  1034  1959 V SIM_STK : Menu title from STK is T-Mobile
,08-25 21:50:45.699  4646  7960 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 532 ms] updated apps [took 532 ms] 
,08-25 21:50:46.295  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:50:46.295  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9229c5e added. We now have 6 listener(s)
08-25 21:50:46.295  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:50:46.306  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:46.307  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e15683f added. We now have 7 listener(s)
08-25 21:50:46.307  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:46.307  6856  6926 I System.out: IsBluetoothEnabled
08-25 21:50:46.308  1034  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:46.308  1034  1886 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-25 21:50:46.309  1034  1096 D BluetoothManagerService: Message: 2
08-25 21:50:46.313  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:46.316  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:46.316  1034  2031 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 21:50:46.336  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 21:50:46.336  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 21:50:46.336  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 21:50:46.337  1034  1096 D BluetoothManagerService: Message: 1
08-25 21:50:46.337  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 21:50:46.362  1034  1096 D BluetoothManagerService: Message: 20
08-25 21:50:46.362  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37a102c9:true
,08-25 21:50:46.366  7797  7797 D BluetoothAdapterState: make
08-25 21:50:46.371  7797  7797 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 21:50:46.371  7797  7797 I bluedroid-qcom: init
08-25 21:50:46.372  7797  8006 I BluetoothAdapterState: Entering OffState
08-25 21:50:46.372  7797  7797 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 21:50:46.373  7797  7797 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 21:50:46.373  7797  7797 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 21:50:46.373  7797  7797 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 21:50:46.373  7797  7797 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 21:50:46.375  7797  7797 I bluedroid-qcom: get_profile_interface socket
08-25 21:50:46.375  7797  7797 I bluedroid-qcom: get_profile_interface map_client
,08-25 21:50:46.379  7797  8010 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 21:50:46.371  8009  8009 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:46.371  8009  8009 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:46.389  7797  8010 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 21:50:46.397  8009  8009 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 21:50:46.397  8009  8009 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 21:50:46.397  8009  8009 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 21:50:46.399  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 21:50:46.399  1034  1096 D BluetoothManagerService: Message: 40
08-25 21:50:46.399  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 21:50:46.401  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 21:50:46.401  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 21:50:46.401  7797  7812 I bluedroid-qcom: config_hci_snoop_log
,08-25 21:50:46.404  8009  8009 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 21:50:46.406  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 21:50:46.406  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 21:50:46.409  7797  8010 D BluetoothAdapterProperties: Name is: G3
08-25 21:50:46.413  8009  8009 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 21:50:46.413  8009  8009 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-25 21:50:46.419  7797  8006 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 21:50:46.419  7797  8006 D BluetoothAdapterProperties: Setting state to 11
08-25 21:50:46.419  7797  8006 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 21:50:46.421  1034  1096 D BluetoothManagerService: Message: 60
08-25 21:50:46.421  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 21:50:46.421  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 21:50:46.423  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:50:46.428  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 21:50:46.429  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:46.433  6975  6975 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 21:50:46.440  7797  7797 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 21:50:46.440  7797  7797 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:46.440  7797  7797 V BluetoothPbapReceiver: ***********state = 11
,08-25 21:50:46.448  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:50:46.457  7797  8006 I LGBluetoothServiceJni: classInitNative: succeeds
,08-25 21:50:46.463  7797  8006 D BluetoothBondStateMachine: make
08-25 21:50:46.468  7797  8006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.468  7797  8006 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 21:50:46.468  7797  8006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.468  7797  8006 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 21:50:46.469  7797  8006 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-25 21:50:46.471  7797  8024 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 21:50:46.472  7797  8006 E BluetoothAdapterService: File transfer profiles supported!!
08-25 21:50:46.481  6975  6975 D BluetoothPermissionRequest: onReceive
08-25 21:50:46.483  7797  8006 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 21:50:46.484  7797  7797 D HeadsetService: Received start request. Starting profile...
08-25 21:50:46.485  7797  7797 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 21:50:46.485  7797  7797 D LGBluetoothHfpAdapter: Version 1.6
08-25 21:50:46.489  7797  7797 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 21:50:46.490  7797  7797 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 21:50:46.490  7797  8006 E BluetoothAdapterService: File transfer profiles supported!!
08-25 21:50:46.490  7797  7797 D HeadsetStateMachine: make
08-25 21:50:46.492  6975  6975 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 21:50:46.506  7797  8006 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 21:50:46.512  7797  8006 E BluetoothAdapterService: File transfer profiles supported!!
08-25 21:50:46.518  7797  8006 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 21:50:46.524  7797  8006 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 21:50:46.533  7797  7797 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:46.534  7797  7797 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 21:50:46.540  7797  7797 D HeadsetStateMachine: max_hf_connections = 1
08-25 21:50:46.540  7797  7797 I bluedroid-qcom: get_profile_interface handsfree
08-25 21:50:46.541  7797  8006 V LGMDMManager: Create singleton instance
08-25 21:50:46.542  7797  7797 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-25 21:50:46.543   310  1382 V AudioPolicyService: registerClient() client 0xb54eae80, uid 1002
08-25 21:50:46.543   310  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 21:50:46.544   310  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 21:50:46.544   310  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 21:50:46.544  7797  7797 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 21:50:46.544   310  1754 V AudioFlinger: registerClient() client 0xb55815b0, pid 7797
08-25 21:50:46.544  7797  8006 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 21:50:46.545   310  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:46.545   310  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:46.545  1600  2097 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:46.545  1600  2097 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:46.545  1851  3550 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:46.545  1851  3550 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:46.546   310  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:46.546   310  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:46.546  1600  2702 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:46.546  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:46.546  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:46.546  1600  2702 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:46.547  1034  1573 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:46.547  1034  1573 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:46.547  1034  1573 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:46.547  1034  1573 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:46.547  3460  3476 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:46.547  3460  3476 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 21:50:46.547  3460  3476 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:46.547  3460  3476 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 21:50:46.547  7797  7812 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 21:50:46.548  7797  7812 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 21:50:46.548  7797  7797 V ToneGenerator: Create Track: 0xb4928a80
08-25 21:50:46.548  7797  7812 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 21:50:46.548  7797  7812 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 21:50:46.548  7797  7797 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 21:50:46.548  7797  7797 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 21:50:46.548   310  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 21:50:46.548   310  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 21:50:46.548   310  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 21:50:46.548   310  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 21:50:46.548   310  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 21:50:46.549   310  1754 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 21:50:46.549   310 , 1754 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 21:50:46.549   310  1754 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 21:50:46.549   310  1754 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 21:50:46.549  7797  7797 V AudioSystem: getLatency() output 2, latency 50
08-25 21:50:46.549  7797  7797 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 21:50:46.549  7797  7797 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 21:50:46.549   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 21:50:46.549   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 21:50:46.549   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 21:50:46.549   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 21:50:46.549   310   310 V AudioFlinger: createTrack() lSessionId: 23
08-25 21:50:46.550  7797  7797 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 21:50:46.551   310  1382 V AudioFlinger: acquiring 23 from 7797, for 7797
08-25 21:50:46.551   310  1382 V AudioFlinger:  added new entry for 23
08-25 21:50:46.551  7797  7797 V ToneGenerator: ToneGenerator INIT OK, time: 203147
08-25 21:50:46.551  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.552  7797  8028 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 21:50:46.552  7797  8028 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 21:50:46.553  7797  8028 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-25 21:50:46.553  7797  8028 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 21:50:46.553   310  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7797
08-25 21:50:46.554   310  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 21:50:46.554   310  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 21:50:46.554   310  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 21:50:46.554   310  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 21:50:46.554   310  1383 V voice   : voice_set_parameters: exit with code(0)
08-25 21:50:46.554   310  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 21:50:46.554   310  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 21:50:46.554  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.554   310  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 21:50:46.554   310  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 21:50:46.554   310  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 21:50:46.554   310  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 21:50:46.554  7797  8028 V ToneGenerator: ToneGenerator destructor
08-25 21:50:46.554  7797  8028 V ToneGenerator: stopTone
08-25 21:50:46.554  7797  8028 V ToneGenerator: Delete Track: 0xb4928a80
08-25 21:50:46.557  7797  7797 D A2dpService: Received start request. Starting profile...
08-25 21:50:46.557  7797  8028 V AudioTrack: ~AudioTrack, releasing session id from 7797 on behalf of 7797
08-25 21:50:46.558   310  1382 V AudioFlinger: releasing 23 from 7797 for 7797
08-25 21:50:46.558  1034  1730 W Process : Unable to open /proc/8031/status
08-25 21:50:46.558   310  1382 V AudioFlinger:  decremented refcount to 0
08-25 21:50:46.558   310   310 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 21:50:46.558   310  1382 V AudioFlinger: purging stale effects
08-25 21:50:46.558   310   310 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 21:50:46.558   310   310 V AudioFlinger: PlaybackThread::Track destructor
08-25 21:50:46.558   310  1258 V AudioPolicyService: AudioCommandThread() waking up
08-25 21:50:46.558   310  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 21:50:46.558   310   310 V AudioFlinger: removeClient_l() pid 7797, calling pid 310
08-25 21:50:46.558   310  1258 V AudioPolicyManager: releaseOutput() 2
08-25 21:50:46.558   310  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 21:50:46.558  7797  7797 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 21:50:46.560  7797  7797 V Avrcp   : make
08-25 21:50:46.561  7797  7797 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 21:50:46.561  7797  7797 I bluedroid-qcom: get_profile_interface avrcp
08-25 21:50:46.575  7797  7797 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 21:50:46.579  7797  7797 E AudioManager: No RCC entry present to update
08-25 21:50:46.579  7797  7797 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 21:50:46.584  7797  7797 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 21:50:46.586  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 21:50:46.586  7797  7797 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 21:50:46.592  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-25 21:50:46.724  1034  1977 V SIM_STK : Menu title from STK is T-Mobile
08-25 21:50:46.724  1034  1977 V SIM_STK : Menu title from STK is T-Mobile
,08-25 21:50:46.887  1034  2031 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 21:50:46.898  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 21:50:46.903  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-25 21:50:46.904  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 21:50:46.904  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 21:50:46.904  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 21:50:46.904  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 21:50:46.904  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 21:50:46.905  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 21:50:46.905  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 21:50:46.905  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 21:50:46.905  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 21:50:46.905  7797  7797 I BluetoothA2dpServiceJni: classInitNative
08-25 21:50:46.905  7797  7797 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 21:50:46.906  7797  7797 D A2dpStateMachine: make
08-25 21:50:46.908  7797  7797 I bluedroid-qcom: get_profile_interface a2dp
08-25 21:50:46.908  7797  8041 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 21:50:46.911  7797  7797 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 21:50:46.911  7797  7797 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 21:50:46.913  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.913  7797  8040 D A2dpStateMachine: Enter Disconnected: -2
08-25 21:50:46.916  7797  7797 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 21:50:46.921  7797  7797 D HidService: Received start request. Starting profile...
08-25 21:50:46.922  7797  7797 I bluedroid-qcom: get_profile_interface hidhost
08-25 21:50:46.922  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.924  7797  7797 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 21:50:46.926  7797  7797 D HealthService: Received start request. Starting profile...
08-25 21:50:46.928  7797  7797 I bluedroid-qcom: get_profile_interface health
08-25 21:50:46.928  7797  7797 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 21:50:46.928  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.929  7797  7797 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 21:50:46.932  7797  7797 D PanService: Received start request. Starting profile...
08-25 21:50:46.932  7797  7797 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 21:50:46.932  7797  7797 I bluedroid-qcom: get_profile_interface pan
08-25 21:50:46.942  7797  7797 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 21:50:46.942  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.944  7797  7797 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-25 21:50:46.953  7797  7797 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 21:50:46.954  7797  7797 D BtGatt.GattService: Received start request. Starting profile...
08-25 21:50:46.954  7797  7797 D BtGatt.GattService: start()
08-25 21:50:46.954  7797  7797 I bluedroid-qcom: get_profile_interface gatt
08-25 21:50:46.955  7797  7797 D BtGatt.AdvertiseManager: advertise manager created
08-25 21:50:46.963  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
,08-25 21:50:46.965  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.966  7797  7797 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 21:50:46.968  7797  7797 V BluetoothMapService: BluetoothMapBinder()
08-25 21:50:46.969  7797  7797 D BluetoothMapService: Received start request. Starting profile...
08-25 21:50:46.969  7797  7797 D BluetoothMapService: start()
08-25 21:50:46.973  7797  7797 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 21:50:46.974  7797  7797 D BluetoothMapEmailAppObserver: createReceiver()
08-25 21:50:46.975  7797  7797 D BluetoothMapEmailAppObserver: initObservers()
,08-25 21:50:46.976  7797  7797 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 21:50:46.989  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:46.989  7797  7797 D HeadsetStateMachine: Proxy object connected
,08-25 21:50:46.990  7797  7797 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 21:50:46.990  7797  7797 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 21:50:46.993  7797  8028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 21:50:46.994  7797  8028 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 21:50:46.994  7797  8028 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 21:50:46.997  7797  7797 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 21:50:47.000  7797  7797 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 21:50:47.003  7797  7797 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 21:50:47.005  7797  7797 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:47.011  7797  7797 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 21:50:47.011  7797  7797 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 21:50:47.014  7797  7797 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 21:50:47.019  7797  7797 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 21:50:47.019  7797  7797 V BluetoothMapService: Handler(): got msg=1
,08-25 21:50:47.020  7797  7797 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 21:50:47.020  7797  7797 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 21:50:47.020  7797  7797 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 21:50:47.020  7797  7797 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:47.020  7797  7797 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 21:50:47.021  7797  8006 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 21:50:47.021  7797  8006 I bluedroid-qcom: enable
08-25 21:50:47.022  7797  8006 I bt_hci_bdroid: init
08-25 21:50:47.023  7797  8006 I bt_vendor: bt-vendor : init
08-25 21:50:47.023  7797  8006 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 21:50:47.023  7797  8006 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 21:50:47.023  7797  8006 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 21:50:47.024  7797  8006 D bt_userial_mct: userial_init
08-25 21:50:47.024  7797  8006 D bt_hci_bdroid: set_power 1
08-25 21:50:47.024  7797  8006 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 21:50:47.024  7797  8006 I bt_vendor: Starting hciattach daemon
08-25 21:50:47.024  7797  8006 I bt_vendor: try to set true
08-25 21:50:47.025  7797  8048 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 21:50:47.025  7797  8048 I bt-btu  : btu_task pending for preload complete event
08-25 21:50:47.021  8051  8051 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:47.021  8051  8051 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:47.061  8052  8052 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 21:50:47.139  8058  8058 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 21:50:47.153  8059  8059 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 21:50:47.187  8061  8061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 21:50:47.198  8062  8062 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-25 21:50:47.210  8063  8063 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 21:50:47.222  8064  8064 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-25 21:50:47.247  8066  8066 I libmdmdetect: ESOC framework not supported
08-25 21:50:47.248  8066  8066 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 21:50:47.256  8066  8066 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 21:50:47.256  8066  8066 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 21:50:47.256  8066  8066 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 21:50:47.256  8066  8066 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 21:50:47.256  8066  8066 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 21:50:47.256  8066  8066 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 21:50:47.256  8066  8066 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 21:50:47.291  8066  8067 E QC-QMI  : qmi_client [8066] 15: failed to locate client data
,08-25 21:50:47.292   473   473 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 21:50:47.293   473   473 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-25 21:50:47.335  8068  8068 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 21:50:47.351  8069  8069 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 21:50:47.376  7797  8006 I bt_vendor: bluetooth satus is on
08-25 21:50:47.376  7797  8006 D bt_hci_bdroid: preload
,08-25 21:50:47.376  7797  8050 D bt_userial_mct: userial_open(port:0)
,08-25 21:50:47.376  7797  8050 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 21:50:47.381  7797  8050 I bt_vendor: Done intiailizing UART
08-25 21:50:47.382  7797  8050 I bt_vendor: Done intiailizing UART
08-25 21:50:47.382  7797  8050 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 21:50:47.382  7797  8050 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 21:50:47.382  7797  8048 I bt-btu  : btu_task received preload complete event
08-25 21:50:47.383  7797  8048 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 21:50:47.383  7797  8048 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-25 21:50:47.383  7797  8071 D bt_userial_mct: Entering userial_read_thread()
08-25 21:50:47.385  7797  8048 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_HCI,
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_A2D,
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_GAP,
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_SDP,
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_SMP
,08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-25 21:50:47.388  7797  8048 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 21:50:47.487  7797  8048 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-25 21:50:47.488  7797  8048 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa023d061 ,
,08-25 21:50:47.488  7797  8048 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa023d061 ,
,08-25 21:50:47.537  7797  8010 E bt-btif : Calling BTA_HhEnable
08-25 21:50:47.537  7797  8010 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 21:50:47.537  7797  8010 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 21:50:47.540  7797  8048 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 21:50:47.540  7797  8048 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 21:50:47.540  7797  8048 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 21:50:47.541  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 21:50:47.542  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 21:50:47.542  7797  8048 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 21:50:47.542  7797  8048 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 21:50:47.542  7797  8010 D BluetoothAdapterProperties: Name is: G3
08-25 21:50:47.544  7797  8010 D BluetoothAdapterProperties: Scan Mode:20
08-25 21:50:47.544  7797  8010 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 21:50:47.544  7797  8010 D bt_hci_bdroid: postload
08-25 21:50:47.544  7797  8050 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 21:50:47.545  7797  8010 D bte_conf: Device ID record 1 : primary
08-25 21:50:47.545  7797  8010 D bte_conf:   vendorId            = 00c4
08-25 21:50:47.545  7797  8010 D bte_conf:   vendorIdSource      = 0001
08-25 21:50:47.545  7797  8010 D bte_conf:   product             = 13a1
08-25 21:50:47.545  7797  8010 D bte_conf:   version             = 1000
08-25 21:50:47.545  7797  8010 D bte_conf:   clientExecutableURL = 
08-25 21:50:47.545  7797  8010 D bte_conf:   serviceDescription  = 
08-25 21:50:47.545  7797  8010 D bte_conf:   documentationURL    = 
08-25 21:50:47.545  7797  8010 D bte_conf: bte_load_did_conf no section named DID2.
08-25 21:50:47.546  7797  8048 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 21:50:47.546  7797  8050 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 21:50:47.548  7797  8050 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 21:50:47.541  8076  8076 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 21:50:47.559  7797  8050 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 21:50:47.560  7797  8006 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 21:50:47.560  7797  8006 D BluetoothAdapterProperties: ScanMode =  20
08-25 21:50:47.560  7797  8006 D BluetoothAdapterProperties: State =  11
08-25 21:50:47.560  7797  8006 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 21:50:47.560  7797  8006 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 21:50:47.560  7797  8006 D BluetoothAdapterProperties: Setting state to 12
08-25 21:50:47.561  7797  8006 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 21:50:47.561  7797  8010 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 21:50:47.561  7797  8010 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 21:50:47.551  8076  8076 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:47.568  7797  8071 E bt_mct  : hci lib postload completed
,08-25 21:50:47.572  1034  1096 D BluetoothManagerService: Message: 60
08-25 21:50:47.572  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 21:50:47.573  7797  8006 I BluetoothAdapterState: Entering On State
08-25 21:50:47.577  7797  8048 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 21:50:47.577  7797  8048 W bt-smp  : Plain text(LSB ~ MSB) = d0 8e 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 21:50:47.577  7797  8048 W bt-smp  : Encrypted text(LSB ~ MSB) = 2f ba cf fe 73 e1 f3 75 35 b5 4d 39 ee 5e f5 ad 
08-25 21:50:47.578  7797  8048 W bt-btm  : Stopping oneshot timer
08-25 21:50:47.583  7797  8006 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 21:50:47.584  7797  8006 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 21:50:47.584  7797  8006 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-25 21:50:47.588  7797  8006 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 21:50:47.610  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-25 21:50:47.620  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:47.620  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:47.620  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:47.620  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:47.620  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:47.620  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:47.620  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:47.620  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:47.621  7797  8010 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 21:50:47.621  7797  8010 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 21:50:47.624  7797  8006 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-25 21:50:47.626  7797  8048 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 21:50:47.626  7797  8048 W bt-smp  : Plain text(LSB ~ MSB) = 95 87 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 21:50:47.626  7797  8048 W bt-smp  : Encrypted text(LSB ~ MSB) = 2a d1 74 d1 cf 20 10 19 88 b4 f0 99 f6 70 e8 04 
08-25 21:50:47.627  7797  8048 W bt-btm  : Stopping oneshot timer
08-25 21:50:47.635  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:47.644  6975  6992 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 21:50:47.658  7797  8048 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 21:50:47.658  7797  8048 W bt-smp  : Plain text(LSB ~ MSB) = cf 44 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 21:50:47.658  7797  8048 W bt-smp  : Encrypted text(LSB ~ MSB) = 18 1e e4 a0 c8 c7 8d cd 70 61 51 03 b7 e8 13 d2 
08-25 21:50:47.658  7797  8048 W bt-btm  : Stopping oneshot timer
,08-25 21:50:47.667  6975  6975 D BluetoothInputDevice: Proxy object connected
08-25 21:50:47.667  6975  6975 D HidProfile: Bluetooth service connected
08-25 21:50:47.671  7797  8048 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 21:50:47.671  7797  8048 W bt-smp  : Plain text(LSB ~ MSB) = 07 ac 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 21:50:47.671  7797  8048 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 6c 11 24 00 d9 90 bb e6 d4 8b 14 88 af 5a 24 
08-25 21:50:47.671  7797  8048 W bt-btm  : Stopping oneshot timer
08-25 21:50:47.673  6975  6992 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 21:50:47.676  8090  8090 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 21:50:47.679  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 21:50:47.680  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:50:47.681  6975  6975 D BluetoothMap: Proxy object connected
08-25 21:50:47.682  1034  1034 D BluetoothA2dp: Proxy object connected
08-25 21:50:47.682  6975  6975 D MapProfile: Bluetooth service connected
08-25 21:50:47.682  6975  6975 D BluetoothMap: getConnectedDevices()
08-25 21:50:47.684  1851  3552 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:50:47.684  1851  1851 D BluetoothHeadset: Proxy object connected
08-25 21:50:47.686  7797  7813 V BluetoothMapService: getConnectedDevices()
,08-25 21:50:47.689  7797  8048 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 21:50:47.689  7797  8048 W bt-smp  : Plain text(LSB ~ MSB) = 77 ba 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-25 21:50:47.689  7797  8048 W bt-smp  : Encrypted text(LSB ~ MSB) = 38 12 49 1f 73 6e 5d e3 3b 52 9a bd 4d 0f 7f 3e 
08-25 21:50:47.689  7797  8048 W bt-btm  : Stopping oneshot timer
08-25 21:50:47.689  1851  1851 D BluetoothHeadset: Proxy object connected
08-25 21:50:47.689  6975  6992 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 21:50:47.691  6975  6975 D BluetoothA2dp: Proxy object connected
08-25 21:50:47.691  6975  6975 D A2dpProfile: Bluetooth service connected
,08-25 21:50:47.691  1851  2395 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:50:47.694  1851  1851 D BluetoothHeadset: Proxy object connected
08-25 21:50:47.694  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:50:47.695  1034  1034 D BluetoothHeadset: Proxy object connected
08-25 21:50:47.697  6975  6991 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:50:47.699  6975  6975 D BluetoothHeadset: Proxy object connected
08-25 21:50:47.699  6975  6975 D HeadsetProfile: Bluetooth service connected
08-25 21:50:47.699  6975  6992 D BluetoothPan: onBluetoothStateChange on: true
08-25 21:50:47.699  6975  6992 D BluetoothPan: onBluetoothStateChange call bindService
,08-25 21:50:47.707  6975  6991 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 21:50:47.709  6975  6975 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:50:47.709  6975  6975 D PanProfile: Bluetooth service connected
08-25 21:50:47.709  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 21:50:47.709  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 21:50:47.711  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:47.711  1942  2137 D LGBluetoothAPIService: Message: 1
08-25 21:50:47.711  1942  2137 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 21:50:47.711  1942  2137 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-25 21:50:47.711  1942  2137 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-25 21:50:47.713  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-25 21:50:47.714  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:47.720  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 21:50:47.720  1034  1096 D BluetoothManagerService: Message: 40
08-25 21:50:47.720  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-25 21:50:47.852  1034  1922 I art     : Explicit concurrent mark sweep GC freed 27508(1361KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.646ms total 128.194ms
08-25 21:50:47.853  7797  7797 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:47.853  7797  7797 D BluetoothMapService: STATE_ON
08-25 21:50:47.853  7797  7797 V BluetoothMapService: Handler(): got msg=1
,08-25 21:50:47.856  7797  7797 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 21:50:47.858  6975  6975 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-25 21:50:47.861  6975  6975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 21:50:47.864  7797  8101 D BluetoothMapMasInstance: MAS initSocket()
08-25 21:50:47.864  7797  8101 D BluetoothMapMasInstance:   masId = 00
08-25 21:50:47.864  7797  8101 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 21:50:47.864  7797  8101 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 21:50:47.864  7797  8101 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 21:50:47.870  1034  1730 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:47.873  7797  8101 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:50:47.874  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:47.874  7797  7797 V BluetoothPbapService: Pbap Service onCreate
08-25 21:50:47.874  7797  7797 V BluetoothPbapService: Starting PBAP service
08-25 21:50:47.874  6975  6975 D DockEventReceiver: finishStartingService: stopping service
08-25 21:50:47.875  7797  7797 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 21:50:47.875  7797  7797 V BluetoothPbapService: Pbap Service onBind
08-25 21:50:47.877  7797  7797 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:47.877  6975  6975 D BluetoothPbap: Proxy object connected
08-25 21:50:47.877  6975  6975 D PbapServerProfile: Bluetooth service connected
08-25 21:50:47.877  7797  7797 V BluetoothPbapService: state: 12
08-25 21:50:47.877  7797  8101 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 21:50:47.877  7797  7797 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 21:50:47.877  7797  7797 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:47.878  7797  7797 V BluetoothPbapReceiver: ***********state = 12
,08-25 21:50:47.878  7797  8101 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 21:50:47.878  7797  8101 D BluetoothMapMasInstance: Accepting socket connection...
08-25 21:50:47.878  7797  8010 D BluetoothAdapterProperties: Scan Mode:21
08-25 21:50:47.878  7797  8010 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 21:50:47.879  7797  7797 V BluetoothPbapService: Handler(): got msg=1
08-25 21:50:47.879  7797  7797 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 21:50:47.880  7797  8103 V BluetoothPbapService: Pbap Service initSocket
08-25 21:50:47.881  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:47.882  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:47.883  7797  8103 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:50:47.884  7797  8103 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 21:50:47.884  7797  8103 V BluetoothPbapService: Succeed to create listening socket 
08-25 21:50:47.884  7797  8103 V BluetoothPbapService: Accepting socket connection...
08-25 21:50:47.885  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:50:47.886  2186  2186 D c       : Getting all permits...
,08-25 21:50:47.886  2186  2186 D a       : Opening database...
,08-25 21:50:47.889  2186  2186 D a       : Opening database auth.proximity.permit_store...
08-25 21:50:47.890  2186  2186 D a       : Closing database...
08-25 21:50:47.899  6975  6975 D BluetoothPermissionRequest: onReceive
,08-25 21:50:47.901  6975  6975 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 21:50:47.902  6975  6975 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 21:50:47.905  7797  7797 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 21:50:47.906  7797  7797 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 21:50:47.910  7797  7797 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 21:50:47.928  7797  7797 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 21:50:47.928  7797  7797 V BtOppService: onCreate
,08-25 21:50:47.933  7797  7797 V BluetoothOppNotification: send message
08-25 21:50:47.936  7797  7797 V BtOppService: Starting RfcommListener
08-25 21:50:47.941  7797  7797 D BluetoothOppPreference: Dumping Names:  
,08-25 21:50:47.941  7797  7797 D BluetoothOppPreference: {}
08-25 21:50:47.941  7797  7797 D BluetoothOppPreference: Dumping Channels:  
,08-25 21:50:47.941  7797  7797 D BluetoothOppPreference: {}
08-25 21:50:47.942  7797  7797 V BtOppService: onStartCommand
08-25 21:50:47.945  7797  7797 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 21:50:47.946  7797  7797 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 21:50:47.946  7797  8110 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 21:50:47.947  7797  8110 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 21:50:47.948  7797  8107 V BtOppService: Deleted complete outbound shares, number =  0
08-25 21:50:47.948  7797  7797 V BluetoothOppNotification: new notify threadi!
08-25 21:50:47.949  7797  7797 V BluetoothOppNotification: send delay message
08-25 21:50:47.949  7797  7797 V BtOppService: start RfcommListener
08-25 21:50:47.950  7797  8107 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 21:50:47.950  7797  8107 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 21:50:47.951  7797  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@168c6127 on behalf of 
08-25 21:50:47.952  7797  8110 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a896fd4 on behalf of 
08-25 21:50:47.952  7797  7797 V BtOppService: RfcommListener started
08-25 21:50:47.953  7797  7797 V BtOppService: ContentObserver received notification
08-25 21:50:47.954  7797  8111 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-25 21:50:47.956  7797  8112 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 21:50:47.958  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:47.959  7797  8111 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e8f657d on behalf of 
08-25 21:50:47.959  7797  8112 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:50:47.959  7797  8111 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 21:50:47.960  7797  8110 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 21:50:47.960  7797  8110 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 21:50:47.960  7797  8111 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 21:50:47.960  7797  8112 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-25 21:50:47.961  7797  8112 V BtOppRfcommListener: Started RFCOMM listener....
08-25 21:50:47.961  7797  8112 I BtOppRfcommListener: Accept thread started.
08-25 21:50:47.961  7797  8110 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fa87c72 on behalf of 
08-25 21:50:47.961  7797  8112 V BtOppRfcommListener: Accepting connection...
08-25 21:50:47.961  7797  8111 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d3e8c3 on behalf of 
08-25 21:50:47.962  7797  8110 V BluetoothOppNotification: update too frequent, put in queue
08-25 21:50:47.962  7797  8111 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 21:50:47.963  7797  8110 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 21:50:47.964  7797  8111 V BluetoothOppNotification: outbound notification was removed.
08-25 21:50:47.964  7797  8111 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 21:50:47.965  7797  8111 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ef7b540 on behalf of 
08-25 21:50:47.966  7797  8111 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 21:50:47.967  7797  8111 V BluetoothOppNotification: inbound notification was removed.
08-25 21:50:47.967  7797  8111 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 21:50:47.968  7797  8111 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@831dc79 on behalf of 
08-25 21:50:47.971  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:47.971  7797  7797 V BluetoothFtpService: Ftp Service onCreate
08-25 21:50:47.971  7797  7797 I BluetoothFtpService: Ftp Service onCreate
08-25 21:50:47.971  7797  7797 V BluetoothFtpService: Ftp Service onStartCommand
08-25 21:50:47.971  7797  7797 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:47.972  7797  7797 V BluetoothFtpService: Starting Listening on sockets
08-25 21:50:47.972  7797  7797 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 21:50:47.972  7797  7797 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 21:50:47.972  7797  7797 V BluetoothSapReceiver: SapReceiver onReceive 
,08-25 21:50:47.972  7797  7797 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:47.972  7797  7797 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 21:50:47.972  7797  7797 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 21:50:47.976  7797  7797 V BtOppService: ContentObserver received notification
08-25 21:50:47.976  7797  7797 V BluetoothFtpService: Handler(): got msg=1
08-25 21:50:47.977  7797  7797 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 21:50:47.977  7797  7797 V BluetoothFtpService: Ftp Service initSocket
,08-25 21:50:47.980  7797  8113 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 21:50:47.980  7797  8113 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 21:50:47.982  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:47.983  7797  8113 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25824e1f on behalf of 
08-25 21:50:47.983  7797  7797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:50:47.984  7797  8113 V BluetoothOppNotification: update too frequent, put in queue
08-25 21:50:47.984  7797  8113 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 21:50:47.985  7797  7797 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-25 21:50:47.985  7797  7797 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 21:50:47.987  7797  8114 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 21:50:48.012  7797  7797 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a8d7b
08-25 21:50:48.012  7797  7797 V BluetoothSapService: Sap Service onCreate
,08-25 21:50:48.014  7797  7797 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:50:48.014  7797  7797 V BluetoothSapService: state: 12
08-25 21:50:48.015  7797  7797 V BluetoothSapService: Starting SAP server process
08-25 21:50:48.011  8115  8115 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:48.011  8115  8115 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:48.020  7797  7797 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 21:50:48.021  7797  8116 V BluetoothSapService: Sap Service initRfcommSocket
08-25 21:50:48.024  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:48.024  7797  8116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:50:48.026  7797  8116 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-25 21:50:48.026  7797  8116 V BluetoothSapService: Succeed to create listening socket 
08-25 21:50:48.026  7797  8116 V BluetoothSapService: Accepting socket connection...
,08-25 21:50:48.029  8115  8115 V BT_SAP  : Event pipe created
,08-25 21:50:48.029  8115  8115 V BT_SAP  : create_server_socket qcom.sap.server
08-25 21:50:48.029  8115  8115 V BT_SAP  : created socket fd 6
08-25 21:50:48.370  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:48.370  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:48.370  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:48.370  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:50:48.370  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:48.370  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:48.370  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:48.370  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:50:48.385  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:48.396  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:48.396  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@149ac50c added. We now have 8 listener(s)
08-25 21:50:48.396  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:50:48.401  1034  2031 D WifiServiceImplEx: setWifiEnabled: false pid=6856, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 21:50:48.404  1034  2031 D WifiService: setWifiEnabled: false pid=6856, uid=10118
08-25 21:50:48.404  1034  2031 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 21:50:48.408  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:48.412  1034  1886 D WifiServiceImplEx: setWifiEnabled: true pid=6856, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 21:50:48.412  1034  1886 D WifiService: setWifiEnabled: true pid=6856, uid=10118
08-25 21:50:48.412  1034  1886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 21:50:48.428  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 21:50:48.428  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 21:50:48.428  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-25 21:50:48.430  1034  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 21:50:48.430  1034  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 21:50:48.433  1034  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 21:50:48.433  1034  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 21:50:48.433  1034  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 21:50:48.433  1034  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 21:50:48.433  1034  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 21:50:48.433  1034  1536 E WifiHW  : unknown target_country: EU , set to default
08-25 21:50:48.433  1034  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 21:50:48.433  1034  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 21:50:48.433  1034  1536 I WifiUtil: gEnableBmps=1
08-25 21:50:48.957  7797  7797 V BluetoothOppNotification: new notify threadi!
,08-25 21:50:48.962  7797  7797 V BluetoothOppNotification: send delay message
08-25 21:50:48.970  7797  8129 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-25 21:50:48.979  7797  8129 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f87ad3b on behalf of 
08-25 21:50:48.980  7797  8129 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 21:50:48.991  7797  8129 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-25 21:50:49.000  7797  8129 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a2eec58 on behalf of 
08-25 21:50:49.001  7797  8129 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 21:50:49.003  7797  8129 V BluetoothOppNotification: outbound notification was removed.
08-25 21:50:49.003  7797  8129 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 21:50:49.006  7797  8129 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@360da1b1 on behalf of 
08-25 21:50:49.007  7797  8129 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 21:50:49.010  7797  8129 V BluetoothOppNotification: inbound notification was removed.
08-25 21:50:49.010  7797  8129 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 21:50:49.011  7797  8129 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2af7f696 on behalf of 
08-25 21:50:49.194   304   894 D SoftapController: Softap fwReload - Ok
,08-25 21:50:49.201  1034  1536 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (740ms)
08-25 21:50:49.203   304   894 D CommandListener: Setting iface cfg
08-25 21:50:49.203   304   894 D CommandListener: Trying to bring down wlan0
08-25 21:50:49.210  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 21:50:49.210  1034  1096 D Tethering: InitialState.processMessage what=4
,08-25 21:50:49.222   304   894 D CommandListener: Clearing all IP addresses on wlan0
,08-25 21:50:49.236  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 21:50:49.240  1034  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-25 21:50:49.241  8137  8137 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 21:50:49.257  1034  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 21:50:49.257  1034  1536 E WifiStateMachine: useWiFiOffloading() : false
08-25 21:50:49.257  1034  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 21:50:49.251  8137  8137 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:49.267  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:49.284  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-25 21:50:49.300  1034  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 21:50:49.300  1034  1536 D WifiMonitor: connecting to supplicant
08-25 21:50:49.303  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 21:50:49.303  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 21:50:49.304  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 21:50:49.304  6975  6975 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 21:50:49.309  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 21:50:49.311  8137  8137 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 21:50:49.313  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:49.318  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 21:50:49.318  6975  6975 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 21:50:49.319  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 21:50:49.319  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 21:50:49.319  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-25 21:50:49.319  6975  6975 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 21:50:49.319  6975  6975 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 21:50:49.321  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 21:50:49.321  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 21:50:49.321  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 21:50:49.321  6975  6975 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 21:50:49.321  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 21:50:49.322  6975  6975 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 21:50:49.322  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 21:50:49.322  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 21:50:49.322  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 21:50:49.322  6975  6975 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 21:50:49.322  6975  6975 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 21:50:49.351  8137  8137 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 21:50:49.351  8137  8137 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 21:50:49.365  1034  1573 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8155 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 21:50:49.421  8137  8137 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 21:50:49.468  1034  2033 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8176 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 21:50:49.468  8137  8137 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 21:50:49.473  8155  8174 W FormManager: Network not available. Please check & try again.
08-25 21:50:49.476  8137  8137 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 21:50:49.477  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 21:50:49.477  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 21:50:49.478  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 21:50:49.478  1034  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 21:50:49.478  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 21:50:49.478  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 21:50:49.478  1034  8193 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 21:50:49.478  1034  8193 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 21:50:49.478  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:49.479  1034  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:49.479  1034  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:49.479  1034  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:49.480  1034  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 21:50:49.480  1034  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 21:50:49.480  1034  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 21:50:49.480  1034  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 21:50:49.480  1034  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-25 21:50:49.481  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:49.481  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:49.481  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:49.481  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:49.481  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 21:50:49.482  1034  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 21:50:49.482  1034  1536 E WifiStateMachine: useWiFiOffloading() : false
08-25 21:50:49.482  1034  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 21:50:49.484  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-25 21:50:49.484  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:49.485  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 21:50:49.485  1034  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 21:50:49.486  1034  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 21:50:49.486  1034  1536 D WifiNative-wlan0: SET update_config 1: returned true
08-25 21:50:49.486  1034  1536 D WifiConfigStore: Loading config and enabling all networks 
08-25 21:50:49.486  1034  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 21:50:49.487  1034  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 21:50:49.487  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:49.487  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:49.487  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:49.487  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:49.487  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:49.487  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:50:49.487  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:50:49.487  6856  6856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:50:49.489  6856  6856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:50:49.490  8155  8175 V FormManager: Network unavailable.
08-25 21:50:49.495  8155  8175 V FormManager: Network unavailable.
,08-25 21:50:49.495  1034  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 21:50:49.504  1034  1923 I ActivityManager: Killing 7255:com.android.chrome/u0a57 (adj 15): empty #17
08-25 21:50:49.507  1034  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 21:50:49.508  1034  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 21:50:49.519  8176  8176 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 21:50:49.535  1034  1977 W libprocessgroup: failed to open /acct/uid_10057/pid_7255/cgroup.procs: No such file or directory
,08-25 21:50:49.536  1034  1536 D WifiStateMachine: enableVerboseLogging : level 2
08-25 21:50:49.536  1034  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 21:50:49.537  1034  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 21:50:49.537  1034  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 21:50:49.537  1034  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 21:50:49.537  1034  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 21:50:49.537  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 21:50:49.538  1034  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 21:50:49.538  1034  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 21:50:49.539  1034  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 21:50:49.539  1034  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 21:50:49.539  1034  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 21:50:49.539  1034  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 21:50:49.540  1034  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 21:50:49.540  1034  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 21:50:49.540  1034  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 21:50:49.541  1034  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 21:50:49.541  1034  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 21:50:49.541  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-25 21:50:49.541  1942  2341 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 21:50:49.541  1942  2341 D WfdsService: Set the WFDS Monitor: true
08-25 21:50:49.541  1942  2341 D WfdsMonitor: WfdsMonitorThread create
08-25 21:50:49.541  7826  7826 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:49.541  1942  2341 D WfdsMonitor: WFDS Monitor is created and started
08-25 21:50:49.541  1942  2341 D WfdsService: WiFi: Supplicant connection re-established
08-25 21:50:49.541  1034  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 21:50:49.541  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:49.541  1034  1536 D WifiNative-HAL: Setting external_sim to 1
08-25 21:50:49.541  1034  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 21:50:49.542  1034  1536 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 21:50:49.542  1034  1536 I WifiNative-HAL: startHal
08-25 21:50:49.542  1034  1536 D wifi    : setting scan oui 0x957a3580
08-25 21:50:49.542  1942  8198 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 21:50:49.542  1034  1536 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 21:50:49.542  1034  1536 I WifiNative-HAL: startHal
08-25 21:50:49.542  1034  1885 I ActivityManager: Killing 7276:com.lge.drmservice/u0a62 (adj 15): empty #17
08-25 21:50:49.542  1034  1536 D wifi    : setting scan oui 0x957a3580
08-25 21:50:49.543  1942  8198 E CtrlSupplicant: Succeed to open control connection
08-25 21:50:49.543  1942  8198 E CtrlSupplicant: Succeed to open monitor connection
08-25 21:50:49.543  1034  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 21:50:49.543  1942  8198 D WfdsMonitor: Supplicant connection established
08-25 21:50:49.543  1942  2341 D WfdsService: Connected to the supplicant for wfds
08-25 21:50:49.543  1034  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 21:50:49.543  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 21:50:49.543  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 21:50:49.544  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true,
08-25 21:50:49.544  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 21:50:49.544  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 21:50:49.544  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 21:50:49.544  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 21:50:49.544  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 21:50:49.544  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 21:50:49.544  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 21:50:49.544  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 21:50:49.545  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 21:50:49.545  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 21:50:49.545  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 21:50:49.545  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 21:50:49.545  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 21:50:49.545  8137  8137 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 21:50:49.545  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 21:50:49.545  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 21:50:49.545  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 21:50:49.545  1034  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 21:50:49.546  1034  1536 E WifiNative: : [206,129,952 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 21:50:49.546  1034  1536 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 21:50:49.546  1034  1536 D WifiNative-wlan0: RECONNECT: returned true
08-25 21:50:49.546  1034  1536 D WifiNative-wlan0: doString: [STATUS]
08-25 21:50:49.547  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 21:50:49.547  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 21:50:49.547  1034  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 21:50:49.547  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 21:50:49.547  1034  1536 D WifiNative-wlan0: SET ps 1: returned true
08-25 21:50:49.547  1034  1535 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.548   304   894 D CommandListener: Setting iface cfg
08-25 21:50:49.548   304   894 D CommandListener: Trying to bring up p2p0
08-25 21:50:49.549  1034  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 21:50:49.549  1034  1535 D LGWifiP2pService: P2pEnablingState
08-25 21:50:49.549  1034  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.549  1034  1535 D LGWifiP2pService: P2p socket connection successful
08-25 21:50:49.549  1034  1535 D LGWifiP2pService: P2pEnabledState
,08-25 21:50:49.567  1034  1535 D LGWifiP2pService: sending p2p connection changed broadcast
,08-25 21:50:49.568  1034  1959 W libprocessgroup: failed to open /acct/uid_10062/pid_7276/cgroup.procs: No such file or directory
08-25 21:50:49.569  1034  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 21:50:49.569  1034  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 21:50:49.570  1034  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 21:50:49.570  1034  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 21:50:49.570  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 21:50:49.571  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-25 21:50:49.571  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 21:50:49.571  1034  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.571  1034  1554 I WifiNative-HAL: startHal
08-25 21:50:49.571  1034  1554 D wifi    : getting scan capabilities on interface[1] = 0x957a3580
08-25 21:50:49.571  1034  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 21:50:49.571  1034  1554 D wifi    : failed to get capabilities : -3
08-25 21:50:49.571  1034  1554 E WifiScanningService: could not get scan capabilities
08-25 21:50:49.571  1034  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.571  1034  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 21:50:49.571  1034  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 21:50:49.572  1034  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 21:50:49.572  1034  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 21:50:49.572  8137  8137 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 21:50:49.573  1034  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 21:50:49.573  1034  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 21:50:49.573  1942  1942 D WfdsService: WifiP2pState is changed : true
08-25 21:50:49.573  1942  2341 D WfdsService: Receive the WFDS_ENABLE Method
08-25 21:50:49.573  1942  2341 D WfdsService: Set the WFDS Monitor: true
08-25 21:50:49.573  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 21:50:49.573  1942  2341 D WfdsService: Connected to the supplicant for wfds
08-25 21:50:49.573  1942  2341 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 21:50:49.573  1034  1535 D WifiNative-p2p0: SET device_name G3: returned true
08-25 21:50:49.573  8137  8137 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 21:50:49.573  1034  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 21:50:49.573  1942  2341 D WfdsService: selectPreferredScanChannel [36]
08-25 21:50:49.573  1942  2341 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 21:50:49.573  1942  1942 D WfdsService: isConnected: false
08-25 21:50:49.573  1034  1535 D LGWifiP2pService: before postfix = G3
08-25 21:50:49.573  1034  1535 D WifiServerServiceExt: postfix byte check : 2
08-25 21:50:49.574  1034  1535 D LGWifiP2pService: after postfix = G3
08-25 21:50:49.574  1034  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 21:50:49.574  1034  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 21:50:49.574  1034  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 21:50:49.574  1034  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 21:50:49.574  1034  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 21:50:49.574  1034  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 21:50:49.574  1034  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 21:50:49.574  1034  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 21:50:49.574  1034  1536 I WifiServerServiceEx,t: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 21:50:49.575  8137  8137 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 21:50:49.575  1034  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 21:50:49.575  1034  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 21:50:49.575  1034  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 21:50:49.576  1034  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 21:50:49.576  1034  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 21:50:49.576  1034  1535 D WifiNative-HAL: p2pGetDeviceAddress
08-25 21:50:49.576  1034  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 21:50:49.576  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 21:50:49.578  1034  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 21:50:49.579  1034  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 21:50:49.579  1034  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 21:50:49.579  1034  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 21:50:49.580  1034  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-25 21:50:49.580  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 21:50:49.580  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 21:50:49.580  1942  1942 D WfdsService: Update P2p Interface State: 3
08-25 21:50:49.582  1034  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 21:50:49.582  1034  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 21:50:49.583  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 21:50:49.584  8137  8137 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:49.584  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 21:50:49.584  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:49.584  1034  8193 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:49.584  1034  8193 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:49.584  8137  8137 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 21:50:49.584  8137  8137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.584  1034  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 21:50:49.584  8137  8137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.585  1034  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 21:50:49.585  1942  8198 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:49.585  1942  8198 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:49.585  1034  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 21:50:49.585  1034  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 21:50:49.585  1034  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 21:50:49.586  1034  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 21:50:49.586  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 21:50:49.586  1034  8193 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:49.586  1034  8193 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.586  1034  8193 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.586  1034  8193 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.586  1034  8193 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:49.586  1034  8193 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.587  1034  8193 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.587  1034  8193 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.589  8176  8176 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:49.593  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 21:50:49.596  8155  8200 W FormManager: Network not available. Please check & try again.
08-25 21:50:49.601  8155  8201 V FormManager: Network unavailable.
08-25 21:50:49.602  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:49.604  1034  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 21:50:49.604  1034  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 21:50:49.604  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 21:50:49.604  8137  8137 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 21:50:49.605  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 21:50:49.605  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 21:50:49.605  1034  8193 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 21:50:49.605  1034  8193 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 21:50:49.605  1034  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 21:50:49.605  1034  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-25 21:50:49.606  1034  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 21:50:49.606  1034  1536 D WifiNative-wlan0: doBoolean: SCAN
,08-25 21:50:49.606  1034  1536 D WifiNative-wlan0: SCAN: returned false
08-25 21:50:49.607  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=206191  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 21:50:49.607  1034  1535 D LGWifiP2pService: InactiveState
08-25 21:50:49.608  1034  1535 D LGWifiP2pService: InactiveState{ when=-26ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.608  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.608  1034  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 21:50:49.608  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 21:50:49.609  8155  8201 V FormManager: Network unavailable.
08-25 21:50:49.609  8137  8137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:49.609  1942  8198 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 21:50:49.609  1034  8193 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 21:50:49.609  1034  8193 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:49.609  8137  8137 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 21:50:49.609  1034  8193 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:49.609  1034  8193 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 21:50:49.609  8137  8137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.610  8137  8137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.610  1034  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 21:50:49.610  1034  1535 D LGWifiP2pService: InactiveState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.610  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.610  1034  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.610  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.610  1942  8198 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:49.610  1034  1535 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.610  1942  8198 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:49.610  1034  8193 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:49.610  1034  8193 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.610  1034  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.610  1034  8193 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.610  1034  8193 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.610  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.610  1034  8193 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 21:50:49.610  1034  8193 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.610  1034  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=1392,85 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.610  1034  8193 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.610  1034  8193 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 21:50:49.610  1034  1535 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.611  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.611  1034  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.611  1034  1535 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.611  1942  2341 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 21:50:49.611  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.611  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=206192  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 21:50:49.611  1034  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:49.611  1034  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:49.611  1034  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:49.612  1034  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:49.612  1034  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:49.612  1034  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 21:50:49.612  1034  1034 E WifiServerServiceExt: No p2p device connected
08-25 21:50:49.615  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:49.615  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:49.616  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:49.616  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:49.616  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:49.617  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 21:50:49.617  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:49.617  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 21:50:49.622  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 21:50:49.623  4386  4386 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 21:50:49.625  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:49.628  4386  4386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 21:50:49.636  4386  8202 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 21:50:49.637  4386  8203 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 21:50:49.637  4386  8203 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 21:50:49.673  1034  1730 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8204 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 21:50:49.797  8204  8204 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 21:50:49.798  8204  8204 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 21:50:49.809  8204  8204 V [BNRBootReceiver]: Boot Receiver Return
08-25 21:50:49.810  8204  8204 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 21:50:49.892  1034  1573 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8222 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 21:50:49.897  1034  1573 I ActivityManager: Killing 7297:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-25 21:50:49.962  1034  1941 W libprocessgroup: failed to open /acct/uid_10085/pid_7297/cgroup.procs: No such file or directory
,08-25 21:50:49.989  8222  8222 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 21:50:50.012  8222  8222 D PluginManager: init()
,08-25 21:50:50.091  8137  8137 E wpa_supplicant: USIM:  scard_init function
,08-25 21:50:50.092  8137  8137 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 21:50:50.094  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 21:50:50.094  1034  8193 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 21:50:50.095  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 21:50:50.095  1034  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 21:50:50.096  1034  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-25 21:50:50.096  1034  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 21:50:50.097  1034  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 21:50:50.097  1034  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 21:50:50.097  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-25 21:50:50.097  1034  8193 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 21:50:50.097  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 21:50:50.097  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 21:50:50.109  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=206693  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 21:50:50.118  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.118  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.118  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 21:50:50.119  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:50.120  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:50.121  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:50.131  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.131  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.131  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 21:50:50.131  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=206715  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 21:50:50.132  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:50.132  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 21:50:50.143  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:50.143  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:50.144  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:50.215  8137  8137 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-25 21:50:50.215  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 21:50:50.215  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 21:50:50.216  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 21:50:50.216  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 21:50:50.216  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:50.216  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 21:50:50.224  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=206808  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 21:50:50.226  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=206809  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 21:50:50.227  1034  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206811
08-25 21:50:50.227  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:50.227  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 21:50:50.227  8137  8137 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 21:50:50.228  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 21:50:50.228  8137  8137 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 21:50:50.228  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 21:50:50.228  1034  8193 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 21:50:50.228  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 21:50:50.228  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 21:50:50.228  1034  8193 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 21:50:50.228  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:50.228  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 21:50:50.236  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 21:50:50.237  1034  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206821
08-25 21:50:50.237  1034  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206821
08-25 21:50:50.238  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206822
08-25 21:50:50.238  1034  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206822
08-25 21:50:50.239  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=206823  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-25 21:50:50.245  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=206828  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 21:50:50.246  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:50.246  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:50.246  1034  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=206829  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 21:50:50.246  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=206830  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 21:50:50.247  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:50.247  1034  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206831
08-25 21:50:50.247  1034  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206831
08-25 21:50:50.248  1034  1536 D WifiNative-wlan0: doString: [STATUS]
08-25 21:50:50.249  1034  8193 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 21:50:50.249  1034  8193 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 21:50:50.249  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.249  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.250  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 21:50:50.250  1034  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 21:50:50.253  1034  1536 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 21:50:50.254  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.254  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.254  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-25 21:50:50.255  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:50.255  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 21:50:50.264  1034  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 21:50:50.264  1034  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-25 21:50:50.267  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:50.267  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 21:50:50.272  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.272  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.272  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 21:50:50.273  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.273  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.273  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 21:50:50.276  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:50.276  1034  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 21:50:50.276  1034  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 21:50:50.276  1034  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 21:50:50.277  1034  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 21:50:50.277  1034  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 21:50:50.277  1034  1543 D ConnectivityService: Got NetworkAgent Messenger
08-25 21:50:50.277  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 21:50:50.277  1034  1543 D ConnectivityService: NetworkAgent connected
08-25 21:50:50.278  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:50.279  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:50.280  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:50.281  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:50.281  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:50.282  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:50.289  1034  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 21:50:50.289  1034  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 21:50:50.289  1034  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 21:50:50.290  1034  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 21:50:50.290  1034  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 21:50:50.297  1034  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 21:50:50.298   304   894 D CommandListener: Setting iface cfg
08-25 21:50:50.301  1034  1536 E WifiStateMachine: Start Dhcp Watchdog 3
08-25 21:50:50.301  1034  8243 D DhcpStateMachine: StoppedState
08-25 21:50:50.301  1034  8243 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:50.301  1034  8243 D DhcpStateMachine: WaitBeforeStartState
08-25 21:50:50.301  1034  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=206885  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:50.302  1034  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=206886  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:50.302  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=206886  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:50.303  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,08-25 21:50:50.309  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:50.309  1034  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:50.310  1034  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:50.310  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:50.310  1034  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 21:50:50.312  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:50.313  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 21:50:50.315  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:50.315  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 21:50:50.316  1034  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=206899  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:50.316  1034  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=206900  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:50.317  1034  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=206900  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 21:50:50.318  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14176] from screen [on:0 period:-1019132210] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 21:50:50.319  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1019132209] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 21:50:50.319  1034  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 21:50:50.323  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:50.323  1034  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-25 21:50:50.324  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.324  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.325  1034  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.325  1034  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.326  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.326  1034  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.327  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 21:50:50.327  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
08-25 21:50:50.328  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
08-25 21:50:50.328  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 21:50:50.328  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 21:50:50.329  1034  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 21:50:50.329  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 21:50:50.329  1034  1536 D WifiNative-wlan0: SET ps 0: returned true
08-25 21:50:50.329  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 21:50:50.330  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 21:50:50.330  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 21:50:50.331  1034  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@33f7ab76 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:50.331  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@33f7ab76 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:50.331  1034  8243 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:50.331  1034  8243 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 21:50:50.332  1034  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 21:50:50.332  1034  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 21:50:50.332  1034  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 21:50:50.333   304   894 D CommandListener: Setting iface cfg
08-25 21:50:50.334   304   894 D CommandListener: Trying to bring up wlan0
08-25 21:50:50.334  1034  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 21:50:50.335  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 21:50:50.335  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-25 21:50:50.337  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-25 21:50:50.337  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 21:50:50.339  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.339  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.340  1034  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.340  1034  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.341  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.341  1034  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 21:50:50.341  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 21:50:50.342  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 21:50:50.342  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 21:50:50.342  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 21:50:50.342  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 21:50:50.342  1034  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:50.343  1034  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 21:50:50.343  1034  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 21:50:50.343  1034  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:50.343  8137  8137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 21:50:50.344  1034  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 21:50:50.345  1034  1536 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 21:50:50.360  1034  1536 D WifiNative-wlan0: SET ps 1: returned true
08-25 21:50:50.361  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 21:50:50.361  1034  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-25 21:50:50.362  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 21:50:50.362  1034  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 21:50:50.363  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
08-25 21:50:50.367  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:50.367  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:50.369  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.369  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.369  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 21:50:50.369  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 21:50:50.370  1034  1543 D ConnectivityService: Adding iface wlan0 to network 102
08-25 21:50:50.371  1034  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 21:50:50.371  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:50.378  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.378  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.378  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 21:50:50.379  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 21:50:50.381  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 21:50:50.383  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.383  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.384  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 21:50:50.385  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 21:50:50.393  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 21:50:50.393  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 21:50:50.396  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.397  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:50:50.397  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 21:50:50.397  1034  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 21:50:50.397  1034  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-25 21:50:50.397  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:50.398  1034  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-25 21:50:50.399   304   894 E Netd    : netlink response contains error (File exists)
08-25 21:50:50.400  1034  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 21:50:50.400  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:50.400  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 21:50:50.400  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:50.400  1034  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 21:50:50.400  1034  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-25 21:50:50.401  1034  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-25 21:50:50.402  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 21:50:50.404  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 21:50:50.404  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 21:50:50.404  1034  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 21:50:50.404  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 21:50:50.404  1034  8242 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:50.404  1034  8242 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 21:50:50.404  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:50.404  1034  8242 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 21:50:50.404  1034  8242 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 21:50:50.406  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 21:50:50.407  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:50.407  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:50.407  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 21:50:50.408  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:50.408  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 21:50:50.408  1034  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-25 21:50:50.408  1034  1543 D ConnectivityService:    accepting network in place of null
08-25 21:50:50.408  1034  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 21:50:50.408  1034  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:50.408  1034  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:50.409  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:50.409  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 21:50:50.410  1034  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 21:50:50.410  1034  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 21:50:50.411  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 21:50:50.412  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 21:50:50.412  1034  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 21:50:50.413  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 21:50:50.413  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 21:50:50.413  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 21:50:50.413  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 21:50:50.414   304  8252 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 21:50:50.417  1034  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 21:50:50.418  1034  1543 D ConnectivityService: validation of new default Network = false
08-25 21:50:50.418  1034  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 21:50:50.418  1034  1543 D DSQN    : enableDataServiceNotify 
08-25 21:50:50.418  1034  1543 D DSQN    : start dsqn bin
,08-25 21:50:50.424  1034  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 21:50:50.429  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 21:50:50.429  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:50.429  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:50.429  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:50.430  1600  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 21:50:50.421  8253  8253 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:50.421  8253  8253 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 21:50:50.439  8253  8253 E DSQN    : DSQN ssw
08-25 21:50:50.446  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:50:50.446  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:50.446  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:50.446  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:50.446  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:50.446  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:50.446  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:50.446  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:50:50.447  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:50.447  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 21:50:50.448  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:50.449  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:50.451  6856  6926 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 21:50:50.452  6856  6926 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 21:50:50.453  6856  6926 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@115337ae Bundle[{}]
08-25 21:50:50.454  6856  6926 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 21:50:50.454  6856  6926 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 21:50:50.455  6856  6926 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 21:50:50.455  6856  6926 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 21:50:50.456  6856  6926 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 21:50:50.457  6856  6926 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 21:50:50.462  6856  6926 I System.out: Running OutgoingSocketThread
,08-25 21:50:50.463  6856  8257 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 881)
08-25 21:50:50.464  6856  8257 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 36761
08-25 21:50:50.464  6856  8257 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-25 21:50:50.475   304  8252 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-25 21:50:50.508   304  8252 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 21:50:50.524  8222  8222 W ExternalStrings: load override strings
08-25 21:50:50.524  8222  8222 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 21:50:50.524  8222  8222 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-25 21:50:50.526  8222  8222 D StatusProvider: onCreate
,08-25 21:50:50.534  1034  8243 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 21:50:50.535  1034  8243 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 21:50:50.535  1034  8243 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 21:50:50.531  8258  8258 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 21:50:50.531  8258  8258 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 21:50:50.547   304   893 D LGDataListener: argv[0]=dsqncommand
08-25 21:50:50.547   304   893 D LGDataListener: argv[1]=wlan0
08-25 21:50:50.547   304   893 D LGDataListener: argv[2]=1
08-25 21:50:50.547   304   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 21:50:50.548  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 21:50:50.548  1034  1094 D DSQN    : start to monitor internet connection
08-25 21:50:50.562  8258  8258 I dhcpcd  : version 5.5.6 starting
,08-25 21:50:50.568  8258  8258 E dhcpcd  : get_duid: m
08-25 21:50:50.568  8258  8258 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 21:50:50.568  8258  8258 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 21:50:50.585  1034  8242 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 19:50:50 GMT], X-Android-Received-Millis=[1472154650584], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472154650546]}
08-25 21:50:50.585  1034  8242 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 21:50:50.585  1034  8242 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 21:50:50.586  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-25 21:50:50.586  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 21:50:50.586  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:50.586  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:50.587  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-25 21:50:50.587  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,08-25 21:50:50.587  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 21:50:50.587  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:50.587  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:50.588  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:50.589  1600  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 21:50:50.591  1034  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:50.592  1034  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:50.592  1034  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 21:50:50.594  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 21:50:50.595  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:50.595  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 21:50:50.618  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 21:50:50.620  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:50.621  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 21:50:50.626  8222  8222 V Signer  : override build config not found
08-25 21:50:50.626  8222  8222 D Signer  : value of property debug is false
08-25 21:50:50.660  8258  8258 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 21:50:50.660  8258  8258 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 21:50:50.660  8258  8258 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-25 21:50:50.661  8258  8258 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 21:50:50.661  8258  8258 D dhcpcd  : wlan0: sending REQUEST (xid 0x7970c398), next in 3.96 seconds
,08-25 21:50:50.667  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-25 21:50:50.667  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-25 21:50:50.667  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-25 21:50:50.667  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-25 21:50:50.667  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-25 21:50:50.668  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-25 21:50:50.668  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-25 21:50:50.668  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-25 21:50:50.668  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-25 21:50:50.668  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-25 21:50:50.669  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-25 21:50:50.669  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-25 21:50:50.669  8222  8222 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-25 21:50:50.679  8222  8222 V LGMDMManager: Create singleton instance
,08-25 21:50:50.694  8258  8258 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-25 21:50:50.724  8222  8222 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-25 21:50:50.733  8258  8258 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 21:50:50.734  8258  8258 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 21:50:50.734  8258  8258 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 21:50:50.735  8258  8258 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 21:50:50.735  8258  8258 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 21:50:50.736  8258  8258 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 21:50:50.736  8258  8258 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 21:50:50.736  8258  8258 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 21:50:50.809  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-25 21:50:50.812  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:50.832  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:50.839  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:50.888  1034  1995 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8285 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-25 21:50:50.889  1034  1995 I ActivityManager: Killing 7332:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-25 21:50:50.973  8222  8273 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 21:50:51.138  1034  8243 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 21:50:51.141  1034  8243 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 21:50:51.142  1034  8243 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 21:50:51.142  1034  8243 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 21:50:51.142  1034  8243 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 21:50:51.143  1034  8243 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 21:50:51.143  1034  8243 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 21:50:51.143  1034  8243 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 21:50:51.145  1034  8243 D DhcpStateMachine: RunningState
,08-25 21:50:51.158  1034  1886 W libprocessgroup: failed to open /acct/uid_10093/pid_7332/cgroup.procs: No such file or directory
,08-25 21:50:51.187  8285  8285 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 21:50:51.225  8285  8285 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-25 21:50:51.258  8285  8285 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-25 21:50:51.259  8285  8285 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 21:50:51.259  8285  8285 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 21:50:51.260  8285  8285 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 21:50:51.260  8285  8285 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 21:50:51.262  8285  8285 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 21:50:51.268  8285  8285 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 21:50:51.274  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 21:50:51.285  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.294  8222  8273 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:51.295  8222  8273 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 21:50:51.305  8285  8285 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 21:50:51.308  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-25 21:50:51.312  8285  8285 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-25 21:50:51.314  6975  6975 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 21:50:51.317  8285  8285 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 21:50:51.319  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:51.319  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.332  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:51.339  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:51.348  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:51.348  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.349  8285  8285 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 21:50:51.352  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.353  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.360  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:51.369  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:51.375  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:51.375  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.376  8285  8285 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:51.379  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 21:50:51.379  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 21:50:51.379  6975  6975 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 21:50:51.379  6975  6975 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 21:50:51.379  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 21:50:51.380  6975  6975 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 21:50:51.380  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 21:50:51.380  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 21:50:51.380  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 21:50:51.380  6975  6975 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 21:50:51.381  6975  6975 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 21:50:51.381  6975  6975 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 21:50:51.385  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:51.386  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.393  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:51.405  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:51.412  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 21:50:51.412  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.413  8285  8285 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:51.416  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.416  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.421  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:51.428  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:51.435  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:51.435  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.436  8285  8285 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 21:50:51.438  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.439  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.443  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 21:50:51.448  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 21:50:51.455  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 21:50:51.455  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.456  8285  8285 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:51.459  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.459  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.464  6856  6926 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 882)
08-25 21:50:51.464  6856  6926 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 882)
08-25 21:50:51.467  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:51.468  6856  6926 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 887)
08-25 21:50:51.470  6856  6926 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 21:50:51.470  6856  6926 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 888)
08-25 21:50:51.474  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.474  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2137be55 added. We now have 2 listener(s)
08-25 21:50:51.475  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:51.477  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.477  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.477  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.477  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.478  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b78206a added. We now have 9 listener(s)
08-25 21:50:51.478  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:51.478  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 21:50:51.480  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:50:51.485  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:51.485  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:51.485  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:51.485  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:51.485  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:51.485  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.485  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:51.485  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:51.485  8222  8273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-25 21:50:51.487  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.487  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:51.488  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.488  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b525f8 added. We now have 3 listener(s)
08-25 21:50:51.488  1034  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:51.490  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:51.491  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:51.493  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.494  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.494  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:51.494  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.494  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.494  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82ead1 added. We now have 10 listener(s)
08-25 21:50:51.494  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:51.494  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:51.494  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:51.494  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:51.494  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.494  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothM,anager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.494  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:51.494  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.495  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2137be55 removed from the list
08-25 21:50:51.495  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.495  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b78206a removed from the list
08-25 21:50:51.495  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:51.495  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:51.504  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:51.504  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.504  8285  8285 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:51.505  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.505  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.506  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.506  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.506  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.506  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b78206a not in the list
08-25 21:50:51.506  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.506  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.506  8222  8273 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-25 21:50:51.507  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.507  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.507  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.507  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e82ead1 removed from the list
08-25 21:50:51.507  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.507  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.507  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.507  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.507  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b525f8 removed from the list
08-25 21:50:51.508  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.508  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fefd936 added. We now have 2 listener(s)
08-25 21:50:51.509  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 21:50:51.511  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.511  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.511  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.511  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.511  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23122037 added. We now have 9 listener(s)
08-25 21:50:51.511  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:51.512  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 21:50:51.515  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:51.517  8222  8273 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-25 21:50:51.518  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.519  8222  8273 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 21:50:51.519  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.520  8222  8273 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 21:50:51.521  8222  8273 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-25 21:50:51.521  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:51.521  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:51.521  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:51.521  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:51.521  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:51.521  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.521  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:51.521  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:51.522  8222  8273 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-25 21:50:51.524  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.524  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:51.525  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.525  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e7a630d added. We now have 3 listener(s)
08-25 21:50:51.525  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:51.526  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:51.528  8222  8273 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-25 21:50:51.528  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.528  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:51.528  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.528  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.528  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.529  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5852c2 added. We now have 10 listener(s)
08-25 21:50:51.529  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:51.529  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:50:51.529  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:50:51.529  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:50:51.529  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:51.529  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 21:50:51.531  8222  8273 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-25 21:50:51.532  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 21:50:51.534  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 21:50:51.535  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:51.541  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 21:50:51.541  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:51.542  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 21:50:51.544  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 21:50:51.544  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:50:51.548  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 21:50:51.549  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.549  6856  6926 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 21:50:51.549  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:51.549  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:51.551  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:51.551  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:51.551  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:51.551  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.551  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.551  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:51.551  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.552  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fefd936 removed from the list
08-25 21:50:51.552  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.552  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23122037 removed from the list
08-25 21:50:51.552  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:51.552  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.552  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.552  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.553  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.553  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.553  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.553  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23122037 not in the list
08-25 21:50:51.553  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.553  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.554  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.555  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:51.555  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:51.555  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.555  6856  6926 I org.thaliproject.p2p.b,tconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.555  8285  8285 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:51.555  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5852c2 removed from the list
08-25 21:50:51.555  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.555  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.555  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.555  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.555  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e7a630d removed from the list
08-25 21:50:51.556  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.556  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf72309 added. We now have 2 listener(s)
08-25 21:50:51.558  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 21:50:51.560  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.560  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.561  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.561  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.561  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dcd90e added. We now have 9 listener(s)
08-25 21:50:51.561  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:51.561  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:50:51.563  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:51.564  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.564  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.568  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:51.568  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:51.568  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:51.568  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:51.568  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:51.568  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.568  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:51.568  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:51.570  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.570  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:51.571  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.571  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35df893c added. We now have 3 listener(s)
,08-25 21:50:51.572  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:51.575  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:51.576  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 21:50:51.577  1034  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:51.580  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.580  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.580  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.580  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.580  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c65e6c5 added. We now have 10 listener(s)
08-25 21:50:51.580  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:50:51.580  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:50:51.581  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:50:51.581  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:50:51.581  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:50:51.581  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:51.581  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 21:50:51.584  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 21:50:51.584  1034  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 21:50:51.589  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 21:50:51.589  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 21:50:51.589  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:51.592  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 21:50:51.593  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:51.595  6856  6926 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 21:50:51.595  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:51.595  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:51.596  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 21:50:51.596  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.596  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.596  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:51.596  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.596  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf72309 removed from the list
08-25 21:50:51.596  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.596  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dcd90e removed from the list
08-25 21:50:51.596  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:51.596  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.598  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.598  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.599  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:51.599  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.599  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.599  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.599  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.599  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dcd90e not in the list
08-25 21:50:51.599  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.600  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:51.600  8285  8285 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 21:50:51.601  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.602  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:51.602  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:51.602  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.602  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.602  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c65e6c5 removed from the list
08-25 21:50:51.602  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.602  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.602  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.602  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.602  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35df893c removed from the list
08-25 21:50:51.603  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.603  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb9fd28 added. We now have 2 listener(s)
08-25 21:50:51.605  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 21:50:51.607  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.607  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.607  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.607  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.608  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25432a41 added. We now have 9 listener(s)
,08-25 21:50:51.608  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:51.608  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 21:50:51.608  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.609  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.613  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:51.615  8176  8176 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 21:50:51.618  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:51.618  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:51.618  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:51.618  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:51.618  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:51.618  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.618  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:51.618  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:51.619  8176  8176 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:51.621  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.621  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:51.622  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.622  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f58527 added. We now have 3 listener(s)
08-25 21:50:51.623  1034  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:51.623  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 21:50:51.623  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:51.625  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:51.627  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.627  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.627  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.627  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.627  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3445c3d4 added. We now have 10 listener(s)
08-25 21:50:51.627  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:51.627  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:50:51.627  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:50:51.627  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:50:51.627  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:50:51.627  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 21:50:51.631  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 21:50:51.631  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:51.633  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:51.636  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:50:51.640  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 21:50:51.642  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:51.642  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 21:50:51.642  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.642  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:51.644  8285  8285 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 21:50:51.644  6856  6926 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 21:50:51.645  8285  8285 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 21:50:51.646  8285  8285 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 21:50:51.646  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:51.646  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:51.646  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:51.647  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.647  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.647  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:51.647  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.647  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb9fd28 removed from the list
08-25 21:50:51.647  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.647  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25432a41 removed from the list
08-25 21:50:51.647  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:51.647  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:50:51.651  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.652  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.653  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.653  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.653  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.653  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25432a41 not in the list
08-25 21:50:51.653  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.653  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.653  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.654  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.655  6856  6926 D BluetoothLeScanner: could not find callback wrapper
08-25 21:50:51.655  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:50:51.655  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.655  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.655  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3445c3d4 removed from the list
08-25 21:50:51.655  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.655  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.655  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.655  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.655  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f58527 removed from the list
08-25 21:50:51.656  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.656  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ab4cc3 added. We now have 2 listener(s)
08-25 21:50:51.656  8222  8274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 21:50:51.656  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:51.659  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.659  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.659  6856  6926 D org.thaliproject.p2p.btc,onnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.659  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.659  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a254940 added. We now have 9 listener(s)
08-25 21:50:51.659  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:51.659  8176  8176 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 21:50:51.660  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 21:50:51.660  8176  8176 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 21:50:51.662  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:50:51.665  6975  6975 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 21:50:51.667  6856  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:50:51.667  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:50:51.667  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 21:50:51.667  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:50:51.667  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:50:51.667  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.667  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:50:51.667  6856  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:50:51.670  6856  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:50:51.670  6856  6926 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:50:51.670  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:50:51.671  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15b7a1be added. We now have 3 listener(s)
08-25 21:50:51.671  1034  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 21:50:51.673  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:50:51.674  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 21:50:51.674  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:50:51.674  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:50:51.675  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:50:51.675  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96bf21f added. We now have 10 listener(s)
08-25 21:50:51.675  6856  6926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:50:51.675  6975  6975 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 21:50:51.675  6856  6926 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:50:51.675  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:51.675  6856  6926 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:50:51.675  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.675  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.675  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:50:51.676  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.676  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ab4cc3 removed from the list
08-25 21:50:51.676  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.676  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a254940 removed from the list
08-25 21:50:51.676  6856  6856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:50:51.676  6856  6926 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:50:51.676  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.678  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.678  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.679  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.679  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.679  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.680  6856  6926 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a254940 not in the list
08-25 21:50:51.680  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - proba,bly already removed
08-25 21:50:51.680  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.681  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:50:51.681  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:50:51.681  6856  6926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:50:51.681  6856  6926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96bf21f removed from the list
08-25 21:50:51.681  6856  6926 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:50:51.681  6856  6926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:50:51.681  6856  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:50:51.681  6856  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:50:51.681  6856  6926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15b7a1be removed from the list
08-25 21:50:51.683  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 21:50:51.683  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 21:50:51.683  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 21:50:51.683  8285  8285 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 21:50:51.683  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:50:51.683  8285  8285 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 21:50:51.684  8285  8285 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 21:50:51.684  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 21:50:51.685  6856  6926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 21:50:51.685  8285  8285 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 21:50:51.685  8285  8285 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-25 21:50:51.689  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.697  6856  8335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 895, name: My test thread name)
08-25 21:50:51.698  6856  8335 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 895, thread name: My test thread name)
08-25 21:50:51.698  6856  8335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 895, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 21:50:51.701  6856  8337 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 897, name: My test thread name)
08-25 21:50:51.701  6856  8337 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 897, thread name: My test thread name)
08-25 21:50:51.701  6856  8337 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 897, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 21:50:51.703  6856  6926 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 21:50:51.703  6856  6926 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 21:50:51.703  6856  6926 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 21:50:51.703  6856  6926 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 21:50:51.703  6856  6926 D com.test.thalitest.ThaliTestRunner: Total duration: 23914 ms
08-25 21:50:51.705  6856  6926 I jxcore-log: *Native tests were executed*
08-25 21:50:51.705  6856  6926 I jxcore-log: 
,08-25 21:50:51.705  6856  6926 I jxcore-log: Total number of executed tests:  80
08-25 21:50:51.705  6856  6926 I jxcore-log: 
08-25 21:50:51.705  6856  6926 I jxcore-log: Number of passed tests:  80
08-25 21:50:51.705  6856  6926 I jxcore-log: 
08-25 21:50:51.706  6856  6926 I jxcore-log: Number of failed tests:  0
08-25 21:50:51.706  6856  6926 I jxcore-log: 
08-25 21:50:51.706  6856  6926 I jxcore-log: Number of ignored tests:  0
08-25 21:50:51.706  6856  6926 I jxcore-log: 
08-25 21:50:51.706  6856  6926 I jxcore-log: Total duration:  23914
08-25 21:50:51.706  6856  6926 I jxcore-log: 
08-25 21:50:51.707  6856  6926 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 21:50:51.707  6856  6926 I jxcore-log: 
08-25 21:50:51.710  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.710  6856  6926 I jxcore-log: 
08-25 21:50:51.713  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.713  6856  6926 I jxcore-log: 
08-25 21:50:51.715  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.715  6856  6926 I jxcore-log: 
,08-25 21:50:51.716  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.716  6856  6926 I jxcore-log: 
08-25 21:50:51.717  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.717  6856  6926 I jxcore-log: 
08-25 21:50:51.719  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:50:51.719  6856  6926 I jxcore-log: 
08-25 21:50:51.723  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:50:51.723  6856  6926 I jxcore-log: 
08-25 21:50:51.724  6856  6856 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 21:50:51.725  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.725  6856  6926 I jxcore-log: 
08-25 21:50:51.727  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.727  6856  6926 I jxcore-log: 
08-25 21:50:51.728  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.728  6856  6926 I jxcore-log: 
08-25 21:50:51.729  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 21:50:51.729  6856  6926 I jxcore-log: 
08-25 21:50:51.730  8285  8285 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 21:50:51.731  8285  8285 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 21:50:51.731  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:50:51.731  6856  6926 I jxcore-log: 
,08-25 21:50:51.731  8285  8285 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 21:50:51.732  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:50:51.732  6856  6926 I jxcore-log: 
08-25 21:50:51.733  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.733  6856  6926 I jxcore-log: 
08-25 21:50:51.734  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.734  6856  6926 I jxcore-log: 
08-25 21:50:51.735  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.735  6856  6926 I jxcore-log: 
08-25 21:50:51.736  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.736  6856  6926 I jxcore-log: 
08-25 21:50:51.737  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.737  6856  6926 I jxcore-log: 
08-25 21:50:51.738  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.738  6856  6926 I jxcore-log: 
08-25 21:50:51.739  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.739  6856  6926 I jxcore-log: 
08-25 21:50:51.739  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:50:51.739  6856  6926 I jxcore-log: 
08-25 21:50:51.740  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 21:50:51.740  6856  6926 I jxcore-log: 
08-25 21:50:51.741  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.741  6856  6926 I jxcore-log: 
08-25 21:50:51.742  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.742  6856  6926 I jxcore-log: 
08-25 21:50:51.743  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.743  6856  6926 I jxcore-log: 
08-25 21:50:51.744  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.744  6856  6926 I jxcore-log: 
08-25 21:50:51.745  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.745  6856  6926 I jxcore-log: 
,08-25 21:50:51.746  6856  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:50:51.746  6856  6926 I jxcore-log: 
,08-25 21:50:51.767  8285  8285 D LgDataFeature: LgDataFeature() Constructor: none
08-25 21:50:51.768  8285  8285 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 21:50:51.775  8285  8285 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 21:50:51.776  8285  8285 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 21:50:51.776  8285  8285 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 21:50:51.776  8285  8285 V SoundPool: doLoad: loading sample sampleID=1
08-25 21:50:51.777  8285  8285 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 21:50:51.779  8285  8340 V SoundPool: Start decode
08-25 21:50:51.779  8285  8340 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 21:50:51.780   310  1754 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 21:50:51.780   310  1754 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 21:50:51.780   310  1754 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 21:50:51.780   310  1754 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 21:50:51.781   310  1754 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 21:50:51.781   310  1754 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 21:50:51.781   310  1754 V MediaPlayerService: player type = 3
08-25 21:50:51.781   310  1754 V AwesomePlayer: AwesomePlayer create()
08-25 21:50:51.781  7719  7719 D UEI.SmartControl: QS Service created
08-25 21:50:51.781  8285  8285 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 21:50:51.782   310  1754 V AwesomePlayer: reset_l() 
08-25 21:50:51.782   310  1754 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:51.782   310  1754 V AwesomePlayer: setAudioSink() 
08-25 21:50:51.782   310  1754 V AwesomePlayer: reset_l() 
08-25 21:50:51.782   310  1754 V AudioCache: notify(0xb5474d40, 8, 0, 0)
08-25 21:50:51.782   310  1754 V AudioCache: ignored
08-25 21:50:51.782   310  1754 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:51.783  8285  8285 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 21:50:51.783   310  1754 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 21:50:51.783  8285  8285 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 21:50:51.783   310  1754 V AwesomePlayer: setDataSource_l dataSource
08-25 21:50:51.783   310  1754 V LGParserOSAL: SniffLGParser start
08-25 21:50:51.783   310  1754 V LGParserOSAL: MainType:5, SubType=0
08-25 21:50:51.783   310  1754 V LGParserOSAL: #### check Mime : application/ogg
08-25 21:50:51.783   310  1754 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 21:50:51.784   310  1754 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 21:50:51.802  8285  8285 V LGMDMManager: Create singleton instance
,08-25 21:50:51.828  7719  7719 I UEI.SmartControl: Service initServices...
08-25 21:50:51.828  7719  7719 D UEI.SmartControl: QS start get config
,08-25 21:50:51.833   310  1754 V LGParserOSAL: supported mime: application/ogg
08-25 21:50:51.833   310  1754 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,08-25 21:50:51.833   310  1754 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 21:50:51.833   310  1754 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 21:50:51.833   310  1754 V AwesomePlayer: AudioTrack Setting
08-25 21:50:51.833   310  1754 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 21:50:51.833   310  1754 V AwesomePlayer: setAudioSource() 
08-25 21:50:51.833   310  1754 V MediaPlayerService: prepare
08-25 21:50:51.833   310  1754 V AwesomePlayer: prepareAsync_l() 
08-25 21:50:51.834   310  1754 V MediaPlayerService: wait for prepare
08-25 21:50:51.834   310  8343 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 21:50:51.834   310  8343 V AwesomePlayer: initAudioDecoder() 
08-25 21:50:51.834   310  8343 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 21:50:51.834   310  8343 V AudioSystem: isOffloadSupported()
08-25 21:50:51.834   310  8343 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 21:50:51.834   310  8343 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 21:50:51.834   310  8343 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 21:50:51.834   310  8343 V AwesomePlayer: getUseOffload() = 0 
08-25 21:50:51.834   310  8343 V OMXCodec: OMXCodec::Create
08-25 21:50:51.834   310  8343 V OMXCodec: findMatchingCodecs()
,08-25 21:50:51.834   310  8343 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 21:50:51.835   310  8343 V OMXCodec: matchingCodecs.size()=1
08-25 21:50:51.835   310  8343 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 21:50:51.836   310  8343 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 21:50:51.836   310  8343 V LGCodecAdapter: LG Codec Adapter start
08-25 21:50:51.836   310  8343 V OMXCodec: OMXCodec Createtor
08-25 21:50:51.836   310  8343 V OMXCodec: setComponentRole
08-25 21:50:51.836   310  8343 V OMXCodec: configureCodec protected=0
08-25 21:50:51.836   310  8343 V LGCodecAdapter: called getLGCodecSpecificData
08-25 21:50:51.836   310  8343 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 21:50:51.836   310  8343 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 21:50:51.836   310  8343 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 21:50:51.836   310  8343 V LGCodecOSAL: Not support LGCodec
08-25 21:50:51.836   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 21:50:51.836   310  8343 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 21:50:51.836   310  8343 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 21:50:51.836   310  8343 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 21:50:51.836   310  8343 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 21:50:51.836   310  8343 V AudioSystem: isOffloadSupported()
08-25 21:50:51.836   310  8343 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 21:50:51.836   310  8343 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 21:50:51.836   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 21:50:51.836   310  8343 V OMXCodec: init()
08-25 21:50:51.836   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 21:50:51.836   310  8343 V OMXCodec: allocateBuffers
08-25 21:50:51.837   310  8343 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-25 21:50:51.837   310  8343 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-25 21:50:51.837   310  8343 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-25 21:50:51.837   310  8343 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 21:50:51.839   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 21:50:51.839   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 21:50:51.839   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-2,5 21:50:51.839   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 21:50:51.839   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 21:50:51.839   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 21:50:51.839   310  8343 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 21:50:51.839   310  8343 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 21:50:51.839   310  8343 V AudioCache: notify(0xb5474d40, 5, 0, 0)
08-25 21:50:51.839   310  8343 V AudioCache: ignored
08-25 21:50:51.839   310  8343 V AudioCache: notify(0xb5474d40, 1, 0, 0)
08-25 21:50:51.839   310  8343 V AudioCache: prepared
08-25 21:50:51.839   310  1754 V AudioCache: wait - success
08-25 21:50:51.839   310  1754 V MediaPlayerService: start
08-25 21:50:51.839   310  1754 V AwesomePlayer: play_l() 
08-25 21:50:51.839   310  1754 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 21:50:51.839   310  1754 V AwesomePlayer: createAudioPlayer_l
08-25 21:50:51.839   310  1754 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 21:50:51.839   310  1754 V AwesomePlayer: startAudioPlayer_l() 
08-25 21:50:51.839   310  1754 D AudioPlayer: start of Playback, useOffload 0
08-25 21:50:51.839   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 21:50:51.839   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
,08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:51.842   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 21:50:51.843   310  8345 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
,08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c08d0 on output port
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 21:50:51.843   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 21:50:51.844   310  1754 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 21:50:51.844   310  1754 V AudioCache: notify(0xb5474d40, 6, 0, 0)
08-25 21:50:51.844   310  1754 V AudioCache: ignored
08-25 21:50:51.844   310  1754 V MediaPlayerService: wait for playback complete
08-25 21:50:51.845   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.845   310  8346 V AudioCache: memcpy(0xaf006000, 0xb1027000, 4096)
08-25 21:50:51.847   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.847   310  8346 V AudioCache: memcpy(0xaf007000, 0xb1027000, 4096)
08-25 21:50:51.848   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.848   310  8346 V AudioCache: memcpy(0xaf008000, 0xb1027000, 4096)
08-25 21:50:51.848   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.848   310  8346 V AudioCache: memcpy(0xaf009000, 0xb1027000, 4096)
08-25 21:50:51.849   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.849   310  8346 V AudioCache: memcpy(0xaf00a000, 0xb1027000, 4096)
08-25 21:50:51.849   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.849   310  8346 V AudioCache: memcpy(0xaf00b000, 0xb1027000, 4096)
08-25 21:50:51.850   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.850   310  8346 V AudioCache: memcpy(0xaf00c000, 0xb1027000, 4096)
08-25 21:50:51.851   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.851   310  8346 V AudioCache: memcpy(0xaf00d000, 0xb1027000, 4096)
08-25 21:50:51.852   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.852   310  8346 V AudioCache: memcpy(0xaf00e000, 0xb1027000, 4096)
08-25 21:50:51.852   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.852   310  8346 V AudioCache: memcpy(0xaf00f000, 0xb1027000, 4096)
08-25 21:50:51.853   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.853   310  8346 V AudioCache: memcpy(0xaf010000, 0xb1027000, 4096)
08-25 21:50:51.854   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.854   310  8346 V AudioCache: memcpy(0xaf011000, 0xb1027000, 4096)
08-25 21:50:51.855   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.855   310  8346 V AudioCache: memcpy(0xaf012000, 0xb1027000, 4096)
08-25 21:50:51.855   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.856   310  8346 V AudioCache: memcpy(0xaf013000, 0xb1027000, 4096)
08-25 21:50:51.856   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.856   310  8346 V AudioCache: memcpy(0xaf014000, 0xb1027000, 4096)
08-25 21:50:51.857   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.857   310  8346 V AudioCache: memcpy(0xaf015000, 0xb1027000, 4096)
08-25 21:50:51.858   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.858   310  8346 V AudioCache: memcpy(0xaf016000, 0xb1027000, 4096)
08-25 21:50:51.858   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.859   310  8346 V AudioCache: memcpy(0xaf017000, 0xb1027000, 4096)
08-25 21:50:51.859   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.859   310  8346 V AudioCache: memcpy(0xaf018000, 0xb1027000, 4096)
,08-25 21:50:51.860   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.860   310  8346 V AudioCache: memcpy(0xaf019000, 0xb1027000, 4096)
08-25 21:50:51.861   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.861   310  8346 V AudioCache: memcpy(0xaf01a000, 0xb1027000, 4096)
08-25 21:50:51.862   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.862   310  8346 V AudioCache: memcpy(0xaf01b000, 0xb1027000, 4096)
08-25 21:50:51.863   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.863   310  8346 V AudioCache: memcpy(0xaf01c000, 0xb1027000, 4096)
08-25 21:50:51.873   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.873   310  8346 V AudioCache: memcpy(0xaf01d000, 0xb1027000, 4096)
,08-25 21:50:51.876   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.876   310  8346 V AudioCache: memcpy(0xaf01e000, 0xb1027000, 4096)
08-25 21:50:51.876   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.876   310  8346 V AudioCache: memcpy(0xaf01f000, 0xb1027000, 4096)
08-25 21:50:51.876   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.876   310  8346 V AudioCache: memcpy(0xaf020000, 0xb1027000, 4096)
08-25 21:50:51.877   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.877   310  8346 V AudioCache: memcpy(0xaf021000, 0xb1027000, 4096)
08-25 21:50:51.877   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.877   310  8346 V AudioCache: memcpy(0xaf022000, 0xb1027000, 4096)
08-25 21:50:51.878   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.878   310  8346 V AudioCache: memcpy(0xaf023000, 0xb1027000, 4096)
08-25 21:50:51.878   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.878   310  8346 V AudioCache: memcpy(0xaf024000, 0xb1027000, 4096)
08-25 21:50:51.879   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.879   310  8346 V AudioCache: memcpy(0xaf025000, 0xb1027000, 4096)
08-25 21:50:51.879   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.879   310  8346 V AudioCache: memcpy(0xaf026000, 0xb1027000, 4096)
08-25 21:50:51.880   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.880   310  8346 V AudioCache: memcpy(0xaf027000, 0xb1027000, 4096)
08-25 21:50:51.880   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.880   310  8346 V AudioCache: memcpy(0xaf028000, 0xb1027000, 4096)
08-25 21:50:51.880   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.880   310  8346 V AudioCache: memcpy(0xaf029000, 0xb1027000, 4096)
08-25 21:50:51.881  8285  8285 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 21:50:51.881   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.881   310  8346 V AudioCache: memcpy(0xaf02a000, 0xb1027000, 4096)
08-25 21:50:51.881  8285  8285 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 21:50:51.883  8285  8285 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6157
08-25 21:50:51.884   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.884   310  8346 V AudioCache: memcpy(0xaf02b000, 0xb1027000, 4096)
08-25 21:50:51.885   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.885   310  8346 V AudioCache: memcpy(0xaf02c000, 0xb1027000, 4096)
08-25 21:50:51.885   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.885   310  8346 V AudioCache: memcpy(0xaf02d000, 0xb1027000, 4096)
08-25 21:50:51.886   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.886   310  8346 V AudioCache: memcpy(0xaf02e000, 0xb1027000, 4096)
08-25 21:50:51.887   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.887   310  8346 V AudioCache: memcpy(0xaf02f000, 0xb1027000, 4096)
,08-25 21:50:51.887   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.887   310  8346 V AudioCache: memcpy(0xaf030000, 0xb1027000, 4096)
08-25 21:50:51.888   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.888   310  8346 V AudioCache: memcpy(0xaf031000, 0xb1027000, 4096)
08-25 21:50:51.888  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.889   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.889   310  8346 V AudioCache: memcpy(0xaf032000, 0xb1027000, 4096)
08-25 21:50:51.889   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.889   310  8346 V AudioCache: memcpy(0xaf033000, 0xb1027000, 4096)
08-25 21:50:51.890   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.890   310  8346 V AudioCache: memcpy(0xaf034000, 0xb1027000, 4096)
08-25 21:50:51.890  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.891   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.891   310  8346 V AudioCache: memcpy(0xaf035000, 0xb1027000, 4096)
08-25 21:50:51.891   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.891   310  8346 V AudioCache: memcpy(0xaf036000, 0xb1027000, 4096)
08-25 21:50:51.892   310  8346 V AudioCache: write(0xb1027000, 4096)
08-25 21:50:51.892   310  8346 V AudioCache: memcpy(0xaf037000, 0xb1027000, 4096)
08-25 21:50:51.892  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.892   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 21:50:51.892   310  8346 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 21:50:51.892   310  8346 V AwesomePlayer: postAudioEOS() 
08-25 21:50:51.892   310  8346 V AudioCache: write(0xb1027000, 280)
08-25 21:50:51.892   310  8346 V AudioCache: memcpy(0xaf038000, 0xb1027000, 280)
08-25 21:50:51.894   310  8343 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 21:50:51.894   310  8343 V AwesomePlayer: onStreamDone
08-25 21:50:51.894   310  8343 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 21:50:51.894   310  8343 V AudioCache: notify(0xb5474d40, 2, 0, 0)
08-25 21:50:51.894   310  8343 V AudioCache: playback complete
08-25 21:50:51.894  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.894   310  8343 V AwesomePlayer: pause_l() 
08-25 21:50:51.894   310  8343 V AudioCache: notify(0xb5474d40, 7, 0, 0)
08-25 21:50:51.894   310  8343 V AudioCache: ignored
08-25 21:50:51.894   310  8343 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:51.894   310  8343 D AudioPlayer: Pause Playback at 1068125
08-25 21:50:51.894   310  1754 V AudioCache: wait - success
08-25 21:50:51.894   310  1754 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 21:50:51.894   310  1754 V AwesomePlayer: reset_l() 
08-25 21:50:51.894   310  1754 V AudioCache: notify(0xb5474d40, 8, 0, 0)
08-25 21:50:51.894   310  1754 V AudioCache: ignored
08-25 21:50:51.894   310  1754 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:51.894   310  1754 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 21:50:51.894   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 21:50:51.894   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 21:50:51.894   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 21:50:51.895   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 21:50:51.895   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 21:5,0:51.895   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 21:50:51.895   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 21:50:51.895   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-25 21:50:51.895   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c08d0 on port 1
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 21:50:51.895  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 21:50:51.896   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 21:50:51.896   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 21:50:51.896   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 21:50:51.897   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 21:50:51.897   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 21:50:51.897   310  8345 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 21:50:51.897   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 21:50:51.897   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 21:50:51.897   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 21:50:51.897  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.898   310  1754 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 21:50:51.898   310  1754 D AudioPlayer: AudioPlayer releasing audio source
08-25 21:50:51.898   310  1754 D AudioPlayer: AudioPlayer done releasing audio source
08-25 21:50:51.898   310  1754 V AwesomePlayer: reset_l() 
08-25 21:50:51.898   310  1754 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:51.898   310  1754 V AwesomePlayer: ~AwesomePlayer call
08-25 21:50:51.899   310  1754 V AwesomePlayer: reset_l() 
08-25 21:50:51.899   310  1754 V AwesomePlayer: cancelPlayerEvents
08-25 21:50:51.899  8285  8340 V SoundPool: close(31)
08-25 21:50:51.899  8285  8340 V SoundPool: pointer = 0xa002f000, size = 205080, sampleRate = 48000, numChannels = 2
,08-25 21:50:51.905  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.907  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.909  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 21:50:51.911  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 21:50:51.979  8341  8341 D AndroidRuntime: 
08-25 21:50:51.979  8341  8341 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 21:50:51.983  8341  8341 D AndroidRuntime: CheckJNI is OFF
08-25 21:50:52.116  1034  1536 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 21:50:52.117  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:52.119  1034  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:52.120  1034  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:52.121  1034  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:52.122  1034  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 21:50:52.123  8341  8341 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-25 21:50:52.123  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-25 21:50:52.124  1034  1543 D ConnectivityService: identical MTU - not setting
08-25 21:50:52.124  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 21:50:52.124  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 21:50:52.124  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 21:50:52.124  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:52.126  1034  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 21:50:52.131  1600  1830 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-25 21:50:52.135  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-25 21:50:52.135  1034  1092 I ActivityManager: Killing 6856:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-25 21:50:52.197  1034  1922 I WindowState: WIN DEATH: Window{158ccaa8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 21:50:52.198  1034  1541 D WifiService: Client connection lost with reason: 4
,08-25 21:50:52.212  1034  1922 D InputDispatcher: Window went away: Window{158ccaa8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 21:50:52.238  7719  7719 I UEI.SmartControl: Supports setup maps: true
,08-25 21:50:52.241  7719  7719 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 21:50:52.241  7719  7719 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 21:50:52.241  7719  7719 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 21:50:52.241  7719  7719 I UEI.SmartControl: ### init IR Blaster...
,08-25 21:50:52.244  7719  7719 D serial_port: Configuring serial port
08-25 21:50:52.244  7719  7719 E UEI.SmartControl: UEIBLaster setting for 616
08-25 21:50:52.244  7719  7719 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 21:50:52.244  7719  7719 I UEI.SmartControl: configuring settings for MAXQ616
08-25 21:50:52.244  7719  7719 I UEI.SmartControl: Get version...
08-25 21:50:52.261  7719  8362 D UEI.SmartControl: serial port data available: 21
,08-25 21:50:52.287  7719  7719 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-25 21:50:52.287  7719  7719 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 21:50:52.287  7719  7719 I UEI.SmartControl: QS saving settings...
08-25 21:50:52.289  7719  7719 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 21:50:52.307  7719  8362 D UEI.SmartControl: serial port data available: 4
,08-25 21:50:52.336  7719  8365 I UEI.SmartControl: Device manager: loading config....
08-25 21:50:52.336  7719  8365 D UEI.SmartControl: ----------- loading internal config...
,08-25 21:50:52.337  7719  7719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 21:50:52.346  7719  8365 E UEI.SmartControl: Loading SETTINGS...
08-25 21:50:52.357  7719  8365 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-25 21:50:52.366  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{3512501d u0 com.test.thalitest/.MainActivity t6}
,08-25 21:50:52.375  7719  8364 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 21:50:52.375  7719  8364 D UEI.SmartControl: -----service ready thread exits
,08-25 21:50:52.402   337   342 E GBMv2   : DFP En is all cleared set to be enabled
,08-25 21:50:52.409  1034  2031 W ActivityManager: Spurious death for ProcessRecord{1b357c8 6856:com.test.thalitest/u0a118}, curProc for 6856: null
08-25 21:50:52.409  1034  1117 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-25 21:50:52.411  1034  1117 I ActivityManager:   Force finishing activity ActivityRecord{3512501d u0 com.test.thalitest/.MainActivity t6 f}
08-25 21:50:52.411  1034  1117 W ActivityManager: Duplicate finish request for ActivityRecord{3512501d u0 com.test.thalitest/.MainActivity t6 f}
,08-25 21:50:52.434  7719  7719 E UEI.SmartControl: Services init done
08-25 21:50:52.435  7719  7719 D UEI.SmartControl: QS Service init finished
08-25 21:50:52.435  7719  7719 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 21:50:52.436  7719  7719 D UEI.SmartControl: QS Service version code: 201091
08-25 21:50:52.438  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-25 21:50:52.438  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-25 21:50:52.439  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3b6ccb0b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-25 21:50:52.442  1942  3139 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-25 21:50:52.442  1942  3139 D SplitWindowPolicy: topRunningActivity=ActivityInfo{8b1fde8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 21:50:52.445  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-25 21:50:52.447  7719  7719 D UEI.SmartControl: Service requested: Control
,08-25 21:50:52.455  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-25 21:50:52.455  2034  2126 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-25 21:50:52.461  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 21:50:52.461  3881  3881 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-25 21:50:52.464  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-25 21:50:52.466  2482  2669 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 21:50:52.468  7797  7797 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-25 21:50:52.468  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 21:50:52.474  4550  4550 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-25 21:50:52.474  4550  4550 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-25 21:50:52.474  4550  4550 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-25 21:50:52.474  4550  4550 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-25 21:50:52.474  4550  4550 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 21:50:52.475  4550  4550 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 21:50:52.475  4550  4550 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 21:50:52.475  4550  4550 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 21:50:52.475  4550  4550 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:50:52.475  4550  4550 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:50:52.475  4550  4550 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 21:50:52.475  4550  4550 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-25 21:50:52.478  1034  1471 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 21:50:52.504  4646  4646 I art     : Explicit concurrent mark sweep GC freed 8370(476KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 4.620ms total 84.320ms
,08-25 21:50:52.514  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-25 21:50:52.518  1034  2031 V SIM_STK : Menu title from STK is T-Mobile
,08-25 21:50:52.533  1034  1034 D administrator: Handling package changes for user 0
,08-25 21:50:52.554  8222  8222 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-25 21:50:52.559  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-25 21:50:52.560  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-25 21:50:52.560  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-25 21:50:52.561  3881  4538 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-25 21:50:52.563  7719  7719 D UEI.SmartControl: Internal service binding...
08-25 21:50:52.563  8285  8285 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 21:50:52.565  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-25 21:50:52.566  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-25 21:50:52.567  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-25 21:50:52.567  1600  1600 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-25 21:50:52.571  7719  7734 I UEI.SmartControl: ------ IControl API: 11
08-25 21:50:52.571  7719  7734 D UEI.SmartControl: File observer start...
08-25 21:50:52.571  7719  7734 E UEI.SmartControl: IR Port is disabled: false
08-25 21:50:52.571  7719  7734 D UEI.SmartControl: Starting file observer...
08-25 21:50:52.571  7719  7734 I UEI.SmartControl: Registering callback...
08-25 21:50:52.573  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-25 21:50:52.574  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-25 21:50:52.574  3881  4538 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-25 21:50:52.575  2186  2186 I ConfigService: onCreate
08-25 21:50:52.576  2186  2186 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-25 21:50:52.577  7719  7735 I UEI.SmartControl: ------ IControl API: 19
08-25 21:50:52.578  7719  7735 I UEI.SmartControl: Registering Services Ready callback...
,08-25 21:50:52.580  7719  7735 I UEI.SmartControl: Notify client services are ready...
08-25 21:50:52.581  8285  8302 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 21:50:52.584  2186  2186 I ConfigService: onBind returning update interface
08-25 21:50:52.584  8285  8338 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 21:50:52.585  3881  3897 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 21:50:52.586  8285  8338 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , display: false
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , animation: false }
08-25 21:50:52.589  2186  2186 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-25 21:50:52.589  2186  2186 I ConfigService: onBind returning config service
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , display: false
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , animation: false }
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , create_time: 1471602816196
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , display: false
08-25 21:50:52.589  2034  2034 I GBoardWebViewUtils: , animation: false }
08-25 21:50:52.589  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-25 21:50:52.593  8285  8285 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 21:50:52.595  8285  8285 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 21:50:52.595  2034  8373 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-25 21:50:52.596  7719  7734 I UEI.SmartControl: ------ IControl API: 8
08-25 21:50:52.597  8285  8285 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 21:50:52.597  8285  8285 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 21:50:52.598  8285  8285 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 21:50:52.598  8285  8285 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 21:50:52.600  1815  1815 I ConfigFetchService: service connected
08-25 21:50:52.600  1815  1815 I ConfigClient: service connected
08-25 21:50:52.600  1600  1600 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-25 21:50:52.600  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-25 21:50:52.614  1034  1941 V SIM_STK : Menu title from STK is T-Mobile
08-25 21:50:52.614  1034  1941 V SIM_STK : Menu title from STK is T-Mobile
,08-25 21:50:52.621  8285  8285 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 21:50:52.621  8285  8285 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-25 21:50:52.640  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-25 21:50:52.640  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-25 21:50:52.651  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-25 21:50:52.651  1868  1868 D SplitUIService: removed split : 
,08-25 21:50:52.677  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-25 21:50:52.677  1868  1868 I SplitUIService: split app #11
,08-25 21:50:52.685  1034  1730 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 21:50:52.686  7797  7797 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 21:50:52.687  2186  2186 I ConfigService: onDestroy
,08-25 21:50:52.691  8285  8285 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 21:50:52.692  1600  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 21:50:52.692  1600  1654 D KeyguardModel: createShortcutInfo...
08-25 21:50:52.693  8285  8285 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-25 21:50:52.693  1815  8377 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-25 21:50:52.697  1600  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 21:50:52.697  1600  1654 D KeyguardModel: createShortcutInfo...
08-25 21:50:52.701  1600  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 21:50:52.701  1600  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:50:52.701  1600  1654 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 21:50:52.702  1600  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 21:50:52.704  1600  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 21:50:52.704  1600  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 21:50:52.705  1600  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 21:50:52.705  1600  1654 D KeyguardModel: createShortcutInfo...
08-25 21:50:52.706  1034  1573 V SIM_STK : Menu title from STK is T-Mobile
08-25 21:50:52.709  1600  1654 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 21:50:52.709  1600  1654 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 21:50:52.711  1600  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 21:50:52.711  1600  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 21:50:52.712  1600  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 21:50:52.712  1600  1654 D KeyguardModel: createShortcutInfo...
08-25 21:50:52.713  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-25 21:50:52.716  1600  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:50:52.716  1600  1654 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 21:50:52.716  1600  1654 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 21:50:52.716  1600  1654 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 21:50:52.721  1600  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 21:50:52.721  1600  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 21:50:52.724  1600  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 21:50:52.724  1600  1654 D KeyguardModel: createShortcutInfo...
08-25 21:50:52.727  1600  1600 D KeyguardModel: handleShortcutListChanged...
08-25 21:50:52.727  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-25 21:50:52.730  6088  8382 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-25 21:50:52.735  1600  1654 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 21:50:52.735  1600  1654 D KeyguardModel: createShortcutInfo...
08-25 21:50:52.738  1600  1654 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 21:50:52.738  1600  1654 D KeyguardModel: createShortcutInfo...
08-25 21:50:52.739  1600  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 21:50:52.739  1600  1654 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 21:50:52.740  1600  1654 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 21:50:52.740  1600  1654 D KeyguardModel: createShortcutInfo...
08-25 21:50:52.741  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-25 21:50:52.741  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 21:50:52.741  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-25 21:50:52.741  1600  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 21:50:52.741  1600  1654 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 21:50:52.742  1034  1575 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-25 21:50:52.743  1600  1654 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 21:50:52.743  1600  1654 D KeyguardModel: createShortcutInfo...
08-25 21:50:52.747  1600  1654 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 21:50:52.747  1600  1654 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 21:50:52.748  1815  8384 I PeopleContactsSync: CP2 sync disabled
08-25 21:50:52.749  1600  1654 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 21:50:52.749  1600  1654 D KeyguardModel: createShortcutInfo...
,08-25 21:50:52.756  1815  4824 I Icing   : doRemovePackageData com.test.thalitest
08-25 21:50:52.763  7166  7166 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-25 21:50:52.765  1815  8383 W GmsApplication: Using Auth Proxy for data requests.
08-25 21:50:52.781  2342  8385 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 21:50:52.806  1034  1904 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8387 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 21:50:52.811  1034  1923 I ActivityManager: Killing 7366:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-25 21:50:52.822  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-25 21:50:52.825  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 21:50:52.826  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-25 21:50:52.828  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-25 21:50:52.829  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-25 21:50:52.830  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-25 21:50:52.848   319   404 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-25 21:50:52.848  3199  8406 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-25 21:50:52.850  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-25 21:50:52.850  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 21:50:52.850  2034  2209 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-25 21:50:52.850  2034  2209 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-25 21:50:52.865  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-25 21:50:52.866  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 21:50:52.866  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 21:50:52.874  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-25 21:50:52.874  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:50:52.877  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-25 21:50:52.901  1034  1117 I art     : Explicit concurrent mark sweep GC freed 88005(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.626ms total 301.075ms
,08-25 21:50:52.914  1600  1600 D KeyguardModel: handleShortcutListChanged...
08-25 21:50:52.914  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-25 21:50:52.915  1815  8383 W GmsApplication: Using Auth Proxy for data requests.
08-25 21:50:52.920  1034  1977 W libprocessgroup: failed to open /acct/uid_10005/pid_7366/cgroup.procs: No such file or directory
08-25 21:50:52.923  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35ebd492 u0 com.lge.launcher2/.Launcher t5} time:209519
08-25 21:50:52.927  2034  2034 D [Concierge]WidgetView: change position of spinner
,08-25 21:50:52.927  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1472154652927
08-25 21:50:52.929  2610  2610 D [Concierge]Service: onStartCommand(). Type : 8
08-25 21:50:52.929  2610  2610 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-25 21:50:52.933  2610  2610 D [Concierge]Service: Update widget ID : 11
08-25 21:50:52.933  2610  2610 D [Concierge]Service: onStartCommand(). Type : 0
08-25 21:50:52.934  8341  8341 D AndroidRuntime: Shutting down VM
08-25 21:50:52.975  8387  8387 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 21:50:52.976  8387  8387 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 21:50:52.976  8387  8387 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 21:50:52.977  8387  8387 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 21:50:52.980  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 84287491
08-25 21:50:52.981  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-25 21:50:52.981  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 21:50:52.983  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@26c1af83
08-25 21:50:52.984  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-25 21:50:52.985  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 21:50:52.986  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 21:50:52.991  2186  4135 I art     : Explicit concurrent mark sweep GC freed 5986(361KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.061ms total 17.261ms
08-25 21:50:52.992  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-25 21:50:52.993  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 21:50:52.994  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 21:50:52.995  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472154472191, New one : 1472154652927
08-25 21:50:52.995  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-25 21:50:52.995  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-25 21:50:52.995  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-25 21:50:52.996  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 21:50:52.998  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-25 21:50:52.999  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-25 21:50:53.000  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-25 21:50:53.001  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-25 21:50:53.002  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-25 21:50:53.003  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 21:50:53.003  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 21:50:53.030  1815  1826 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-25 21:50:53.031  1815  1826 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-25 21:50:53.031  1815  1826 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-25 21:50:53.036  1815  8379 I art     : Explicit concurrent mark sweep GC freed 24692(1657KB) AllocSpace objects, 16(256KB) LOS objects, 51% free, 29MB/61MB, paused 1.796ms total 32.177ms
08-25 21:50:53.048  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-25 21:50:53.056  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-25 21:50:53.056  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-25 21:50:53.057  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 21:50:53.058  8387  8387 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-25 21:50:53.074  8387  8387 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 21:50:53.078  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e80819c time:209674
08-25 21:50:53.110  8387  8387 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 21:50:53.128  8387  8387 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 21:50:53.128  8387  8387 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 21:50:53.176  1034  1117 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8413 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-25 21:50:53.204  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-25 21:50:53.213  8387  8387 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-25 21:50:53.218  1034  1730 I ActivityManager: Killing 7826:com.google.android.talk/u0a72 (adj 15): empty #17
08-25 21:50:53.252  2034  2921 I GBoardtInterface: onReloaded()
,08-25 21:50:53.255  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-25 21:50:53.274  1034  1051 W libprocessgroup: failed to open /acct/uid_10072/pid_7826/cgroup.procs: No such file or directory
,08-25 21:50:53.276  1034  1730 I ActivityManager: Killing 7920:com.android.vending/u0a44 (adj 15): empty #17
08-25 21:50:53.277  3881  3897 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 21:50:53.315  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 21:50:53.315  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-25 21:50:53.316  1034  1959 W libprocessgroup: failed to open /acct/uid_10044/pid_7920/cgroup.procs: No such file or directory
,08-25 21:50:53.317  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-25 21:50:53.318  3881  3896 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 21:50:53.324  8222  8222 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 21:50:53.324  1034  1536 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2412 sc=60 link=72 tx=53.0, 0.0, 0.0  rx=56.0 bcn=0 [on:0 tx:0 ,rx:0 period:3002] from screen [on:0 period:-1019129204] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 21:50:53.324  1034  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2412 sc=60 link=72 tx=53.0, 0.0, 0.0  rx=56.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1019129204] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 21:50:53.324  1034  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 21:50:53.326  8222  8222 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-25 21:50:53.327  1905  1905 D ActionManagerService: notifyUserLog: 1000001
,08-25 21:50:53.330  3881  4538 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 21:50:53.330  3881  4538 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 21:50:53.331  7593  7593 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-25 21:50:53.332  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-25 21:50:53.333  3881  3896 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 21:50:53.334  3881  4538 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 21:50:53.334  3881  4538 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 21:50:53.334  3881  4538 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-25 21:50:53.334  3881  4538 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-25 21:50:53.335  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 21:50:53.336  6975  6975 D PackageIntentReceiver: Not supported Hotkey customization function 
08-25 21:50:53.337  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-25 21:50:53.337  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-25 21:50:53.339  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-25 21:50:53.339  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]

```
