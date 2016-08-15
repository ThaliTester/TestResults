#### Test 81321942665e562_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-15 17:20:00.089  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-15 17:20:18.725  6693  6693 D AndroidRuntime: 
08-15 17:20:18.725  6693  6693 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-15 17:20:18.733  6693  6693 D AndroidRuntime: CheckJNI is OFF
08-15 17:20:18.934  6693  6693 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-15 17:20:18.944  1036  2032 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-15 17:20:18.961  1941  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-15 17:20:18.967  1036  2032 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-15 17:20:18.968  1036  2032 D ActivityManager: setTaskToReturnTo : TaskRecord{3fe7c5b9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-15 17:20:18.968  1036  2032 D ActivityManager: setTaskToReturnTo : TaskRecord{3fe7c5b9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-15 17:20:18.970  1036  2032 D WindowStateEx: AppWindowTokenEx init.. 
08-15 17:20:18.971   341   358 E GBMv2   : DFP En is all cleared set to be enabled
08-15 17:20:18.999  1036  2032 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6708 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-15 17:20:19.002  6693  6693 D AndroidRuntime: Shutting down VM
08-15 17:20:19.057  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-15 17:20:19.057  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{334f204f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-15 17:20:19.058  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-15 17:20:19.058  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{a303dc co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-15 17:20:19.128  6708  6708 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-15 17:20:19.230  6708  6708 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-15 17:20:19.239  6708  6708 I LibraryLoader: Loading: webviewchromium
08-15 17:20:19.242  6708  6708 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6181-6186)
,08-15 17:20:19.243  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 17:20:19.279  6708  6708 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c24f5d5}
,08-15 17:20:19.280  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 17:20:19.281  6708  6708 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-15 17:20:19.293  6708  6708 I BrowserStartupController: Initializing chromium process, renderers=0
,08-15 17:20:19.295  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-15 17:20:19.310  6708  6708 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-15 17:20:19.311  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-15 17:20:19.311  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-15 17:20:19.318   313   313 V AudioPolicyService: registerClient() client 0xb558a540, uid 10118
08-15 17:20:19.327  1036  1118 D BluetoothManagerService: Message: 20
08-15 17:20:19.327  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14bc4c7b:true
08-15 17:20:19.329  6708  6708 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 17:20:19.329  6708  6708 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 17:20:19.329  6708  6708 I Adreno-EGL: Build Date: 12/12/14 금
08-15 17:20:19.329  6708  6708 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 17:20:19.329  6708  6708 I Adreno-EGL: Remote Branch: 
08-15 17:20:19.329  6708  6708 I Adreno-EGL: Local Patches: 
08-15 17:20:19.329  6708  6708 I Adreno-EGL: Reconstruct Branch: 
,08-15 17:20:19.417  6708  6748 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-15 17:20:19.425  6708  6708 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-15 17:20:19.442  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-15 17:20:19.447  6708  6708 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-15 17:20:19.451  6708  6708 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-15 17:20:19.454  6708  6708 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-15 17:20:19.454  6708  6708 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-15 17:20:19.469  6708  6708 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-15 17:20:19.476  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-15 17:20:19.476  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-15 17:20:19.506  6708  6763 D OpenGLRenderer: Render dirty regions requested: true
08-15 17:20:19.507  6708  6763 I OpenGLRenderer: Initialized EGL, version 1.4
08-15 17:20:19.513  6708  6763 D OpenGLRenderer: Enabling debug mode 0
,08-15 17:20:19.521  6708  6708 D Atlas   : Validating map...
08-15 17:20:19.525  1036  1898 D SplitWindow: check instance of lgWin Window{2972db9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-15 17:20:19.572  6708  6761 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 17:20:19.572  6708  6761 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 17:20:19.670  6708  6708 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@367e9aa8 time:306614
08-15 17:20:19.670  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +615ms (total +699ms)
08-15 17:20:19.671  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a03bdfe u0 com.test.thalitest/.MainActivity t6} time:306614
,08-15 17:20:19.792  6708  6708 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-15 17:20:19.792  6708  6708 I chromium: 
,08-15 17:20:19.826  6708  6708 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-15 17:20:20.023  6708  6773 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435056640
,08-15 17:20:20.040  6708  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-15 17:20:20.040  6708  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-15 17:20:20.040  6708  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-15 17:20:20.040  6708  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-15 17:20:20.040  6708  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-15 17:20:20.040  6708  6773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@245fdeec added. We now have 1 listener(s)
,08-15 17:20:20.046  1036  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:20.052  6708  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-15 17:20:20.055  6708  6773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:20:20.058  6708  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:20:20.059  6708  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-15 17:20:20.071  6708  6773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fbe14bb added. We now have 1 listener(s)
08-15 17:20:20.071  6708  6773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 17:20:20.076  1036  1498 D WifiService: New client listening to asynchronous messages
08-15 17:20:20.080  6708  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 17:20:20.080  6708  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-15 17:20:20.081  6708  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-15 17:20:20.081  6708  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-15 17:20:20.081  6708  6773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-15 17:20:20.084  6708  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 17:20:20.085  1036  1876 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:20.087  6708  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-15 17:20:20.096  6708  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-15 17:20:20.096  6708  6773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:20:20.096  6708  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:20.096  6708  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:20.096  6708  6773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:20.096  6708  6773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:20:20.096  6708  6773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:20.096  6708  6773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:20:20.096  6708  6773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:20.096  6708  6773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-15 17:20:20.096  6708  6773 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 17:20:20.100  6708  6773 I io.jxcore.node.LifeCycleMonitor: start: OK
08-15 17:20:20.100  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:20.102  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 17:20:20.149  6708  6761 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-15 17:20:20.149  6708  6761 I chromium: 
,08-15 17:20:20.209  6708  6708 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-15 17:20:20.961   341   360 E GBMv2   : DFP En is all cleared set to be enabled
08-15 17:20:20.962   341   360 E GBMv2   : Set value is all cleared set the max
08-15 17:20:20.962   341   360 I GBMv2   : DFP Enabled. Ignore VFP set
,08-15 17:20:21.426  6708  6776 W jxcore-log: Initializing JXcore engine
08-15 17:20:21.426  6708  6776 W jxcore-log: JXcore engine is ready
,08-15 17:20:21.488  6776  6776 W Thread-766: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8611]" dev="sockfs" ino=8611 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-15 17:20:21.488  6776  6776 W Thread-766: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-15 17:20:21.488  6776  6776 W Thread-766: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7455]" dev="sockfs" ino=7455 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-15 17:20:21.488  6776  6776 W Thread-766: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-15 17:20:21.498  6776  6776 W Thread-766: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32565]" dev="sockfs" ino=32565 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-15 17:20:21.539  6708  6776 W jxcore-log: Starting JXcore engine
,08-15 17:20:21.711  6708  6776 W jxcore-log: Platform android
08-15 17:20:21.711  6708  6776 W jxcore-log: 
08-15 17:20:21.711  6708  6776 W jxcore-log: Process ARCH arm
08-15 17:20:21.711  6708  6776 W jxcore-log: 
,08-15 17:20:21.969  6708  6776 I jxcore-log: JXcore Cordova bridge is ready!
08-15 17:20:21.969  6708  6776 I jxcore-log: 
08-15 17:20:21.970  6708  6776 W jxcore-log: JXcore engine is started
,08-15 17:20:21.981  6708  6773 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-15 17:20:21.988  6708  6708 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-15 17:20:45.765  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-15 17:20:45.765  6708  6776 I jxcore-log: 
,08-15 17:20:45.772  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-15 17:20:45.772  6708  6776 I jxcore-log: 
08-15 17:20:45.777  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:20:45.777  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:45.777  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:45.777  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:45.777  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:20:45.777  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:45.777  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:20:45.777  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:45.780  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 17:20:45.785  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-15 17:20:45.785  6708  6776 I jxcore-log: 
08-15 17:20:45.788  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-15 17:20:45.788  6708  6776 I jxcore-log: 
08-15 17:20:46.454  6708  6776 D ExecuteNativeTests: Running unit tests
,08-15 17:20:46.592  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:20:46.592  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac added. We now have 2 listener(s)
,08-15 17:20:46.595  1036  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:46.598  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:20:46.598  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:20:46.598  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:20:46.598  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:20:46.598  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 added. We now have 2 listener(s)
08-15 17:20:46.598  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:20:46.599  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 17:20:46.602  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:20:46.606  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:20:46.606  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:46.606  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:46.606  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:46.606  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:20:46.606  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:46.606  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:20:46.606  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 17:20:46.611  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:46.611  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 17:20:46.613  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:46.615  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:46.618  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-15 17:20:46.623  6708  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 17:20:46.623  6708  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 17:20:46.628  6708  6776 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-15 17:20:46.629  6708  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-15 17:20:46.629  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-15 17:20:46.629  6708  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-15 17:20:46.629  6708  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-15 17:20:46.630  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.630  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.631  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.631  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.632  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.632  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:20:46.632  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:20:46.632  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac removed from the list
08-15 17:20:46.632  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.632  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 removed from the list
08-15 17:20:46.632  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.632  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-15 17:20:46.636  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.636  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.638  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.638  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.638  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.638  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.644  6708  6776 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-15 17:20:46.644  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-15 17:20:46.646  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.646  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.647  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.647  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.647  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.647  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.647  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.647  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.647  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.647  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.647  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.647  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.647  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.649  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.649  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.649  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.650  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.657  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-15 17:20:46.657  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-15 17:20:46.657  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-15 17:20:46.657  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-15 17:20:46.658  6708  6776 D io.jxcore.node,.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-15 17:20:46.658  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-15 17:20:46.659  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-15 17:20:46.659  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-15 17:20:46.659  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-15 17:20:46.659  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-15 17:20:46.659  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.659  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.659  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-15 17:20:46.665  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.665  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.665  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.665  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.665  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.666  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.666  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.666  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.666  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.666  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.666  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.667  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.667  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.667  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.667  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.668  6708  6776 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-15 17:20:46.672  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 17:20:46.677  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:20:46.677  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:46.677  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:46.677  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:46.677  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:20:46.677  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:46.677  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:20:46.677  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:46.679  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:46.679  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 17:20:46.680  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:46.683  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 17:20:46.684  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 17:20:46.684  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 17:20:46.685  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 17:20:46.685  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:20:46.685  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 17:20:46.690  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 17:20:46.690  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:46.696  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-15 17:20:46.705  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-15 17:20:46.707  6708  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-15 17:20:46.709  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 17:20:46.710  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:20:46.712  6708  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 17:20:46.712  6708  6776 I io.jxcore.node.ConnectionHelper: start: OK
08-15 17:20:46.715  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.715  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.715  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-15 17:20:46.718  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.718  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.718  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:20:46.719  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.719  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.719  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.719  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.719  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.720  6708  6776 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-15 17:20:46.722  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:20:46.726  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:20:46.726  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:46.726  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:46.726  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:46.726  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:20:46.726  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:46.726  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:20:46.726  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:46.728  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:46.728  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 17:20:46.732  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:46.734  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:46.734  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 17:20:46.734  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 17:20:46.734  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 17:20:46.734  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:20:46.734  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 17:20:46.740  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-15 17:20:46.742  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:20:46.743  6708  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 17:20:46.744  6708  6776 I io.jxcore.node.ConnectionHelper: start: OK
08-15 17:20:46.745  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.746  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.746  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.746  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.746  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.746  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:20:46.746  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.746  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.746  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.746  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.746  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.747  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.747  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.748  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.748  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.750  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.750  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.750  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.750  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.751  6708  6776 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-15 17:20:46.753  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 17:20:46.759  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:20:46.759  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:46.759  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:46.759  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:46.759  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:20:46.759  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:46.759  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:20:46.759  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:46.761  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:46.761  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 17:20:46.763  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:46.765  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:46.765  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 17:20:46.765  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 17:20:46.765  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 17:20:46.765  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:20:46.765  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-15 17:20:46.772  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 17:20:46.772  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:20:46.774  6708  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 17:20:46.774  6708  6776 I io.jxcore.node.ConnectionHelper: start: OK
08-15 17:20:46.774  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.774  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.774  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.775  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.776  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.776  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.778  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.779  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.779  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:20:46.779  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.779  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.779  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.779  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.779  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.781  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.781  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.784  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.784  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 17:20:46.785  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.785  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.785  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.785  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.788  6708  6776 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-15 17:20:46.788  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.788  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.789  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.789  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.789  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.789  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.789  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.789  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.789  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.789  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.789  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.789  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.790  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.790  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.793  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.793  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.795  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.795  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.795  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.795  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.798  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-15 17:20:46.798  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.798  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.798  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: ,The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.799  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.799  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.799  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.799  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.799  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.799  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.799  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.799  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.799  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.799  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.799  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.800  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.800  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.801  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.801  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.801  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.801  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.802  6708  6776 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-15 17:20:46.802  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.802  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.803  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.803  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.803  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.803  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.803  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.803  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.803  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.803  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.803  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.803  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.803  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.804  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.805  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.805  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.805  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.805  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.806  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.806  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.807  6708  6776 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-15 17:20:46.807  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.807  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.807  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.807  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.807  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.808  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.808  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.808  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.808  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.808  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.808  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.808  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.808  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.808  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.810  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.810  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.811  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.811  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.811  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.811  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.812  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-15 17:20:46.812  6708  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 17:20:46.812  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-15 17:20:46.812  6708  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-15 17:20:46.813  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-15 17:20:46.813  6708  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-15 17:20:46.813  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.813  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.813  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.814  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.814  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.814  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.814  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.814  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.814  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.814  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.814  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.814  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.814  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.814  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.816  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.816  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.817  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.817  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.817  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.817  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.818  6708  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 17:20:46.818  6708  6776 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-15 17:20:46.818  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-15 17:20:46.823  6708  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 17:20:46.824  6708  6776 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-15 17:20:46.824  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-15 17:20:46.825  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-15 17:20:46.825  6708  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-15 17:20:46.825  6708  6776 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-15 17:20:46.826  6708  6776 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-15 17:20:46.826  6708  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 17:20:46.826  6708  6776 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-15 17:20:46.826  6708  6776 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-15 17:20:46.826  6708  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 17:20:46.826  6708  6776 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-15 17:20:46.826  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-15 17:20:46.828  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-15 17:20:46.830  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-15 17:20:46.830  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-15 17:20:46.831  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-15 17:20:46.831  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-15 17:20:46.831  6708  6776 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-15 17:20:46.831  6708  6776 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-15 17:20:46.832  6708  6776 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-15 17:20:46.832  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.832  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.832  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.833  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.833  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.833  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.833  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-15 17:20:46.834  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.834  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.834  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.834  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.834  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.834  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.834  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.834  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.837  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.837  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.838  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.838  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.838  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.838  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.840  6708  6776 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-15 17:20:46.841  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.841  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.841  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.842  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.842  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.842  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.842  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.842  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.843  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.843  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.843  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.843  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.843  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.843  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.844  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.844  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.845  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.845  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.845  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.846  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.847  6708  6776 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-15 17:20:46.850  6708  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 830)
08-15 17:20:46.850  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.850  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.850  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.851  6708  6801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 830
08-15 17:20:46.852  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.852  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.852  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.852  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.853  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.853  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.853  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.853  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.853  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.853  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.853  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.860  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.860  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.862  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.862  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.862  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.862  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.863  6708  6776 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-15 17:20:46.863  6708  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-15 17:20:46.863  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-15 17:20:46.863  6708  6776 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-15 17:20:46.864  6708  6776 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-15 17:20:46.864  6708  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-15 17:20:46.864  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-15 17:20:46.864  6708  6776 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-15 17:20:46.864  6708  6776 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-15 17:20:46.864  6708  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-15 17:20:46.864  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-15 17:20:46.864  6708  6776 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-15 17:20:46.864  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.864  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.864  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.866  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.866  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.867  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.867  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.867  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.867  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.867  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.867  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.867  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.867  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.867  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.868  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:46.868  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:46.869  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.869  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.869  6708  6776 ,I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.869  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.870  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.870  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.870  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.870  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.870  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.870  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.870  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop,
08-15 17:20:46.870  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.870  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.870  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 17:20:46.870  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.870  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.871  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.871  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-15 17:20:46.871  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.871  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.871  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-15 17:20:46.871  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.872  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.872  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 17:20:46.872  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.872  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.872  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-15 17:20:46.872  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.872  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.872  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-15 17:20:46.872  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.872  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.872  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.878  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-15 17:20:46.878  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-15 17:20:46.888  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.888  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.888  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.888  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.898  6708  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-15 17:20:46.898  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 17:20:46.900  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-15 17:20:46.902  6708  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-15 17:20:46.902  6708  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-15 17:20:46.902  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-15 17:20:46.903  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-15 17:20:46.903  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-15 17:20:46.904  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.904  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-15 17:20:46.904  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-15 17:20:46.904  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:46.904  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-15 17:20:46.904  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.904  6708  6776 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-15 17:20:46.905  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-15 17:20:46.905  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.905  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.905  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-15 17:20:46.905  6708  6776 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-15 17:20:46.906  6708  6812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:20:46.906  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-15 17:20:46.907  3831  3850 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-15 17:20:46.908  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-15 17:20:46.908  6708  6812 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-15 17:20:46.908  6708  6812 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-15 17:20:46.908  6708  6812 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-15 17:20:46.909  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:46.909  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:46.909  6708  6776 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-15 17:20:46.909  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.909  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.910  6708  6776 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 17:20:46.910  6708  6776 E org.thaliproject,.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.911  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 17:20:46.911  6708  6708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:20:46.911  6708  6708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 17:20:46.911  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:46.911  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:46.911  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:46.911  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:46.911  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.911  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:20:46.911  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:46.911  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:46.911  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:46.911  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:46.911  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.911  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-15 17:20:46.915  6708  6708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 17:20:46.915  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:46.919  6708  6708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 17:20:46.920  6708  6708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-15 17:20:46.920  6708  6708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 17:20:46.921  6708  6708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.922  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:46.922  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:46.923  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-15 17:20:46.923  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-15 17:20:46.923  6708  6708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:20:46.923  6708  6708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-15 17:20:46.958  6708  6800 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-15 17:20:46.958  6708  6800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:20:46.959  3831  3847 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-15 17:20:46.960  3831  4113 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
08-15 17:20:47.070  1036  1898 I art     : Explicit concurrent mark sweep GC freed 25664(1266KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.347ms total 144.573ms
,08-15 17:20:47.074  6708  6708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 17:20:47.075  6708  6708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.084  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:47.085  6708  6708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-15 17:20:47.085  6708  6708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-15 17:20:47.087  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:47.087  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:47.087  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:47.087  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:47.088  6708  6776 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-15 17:20:47.088  6708  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-15 17:20:47.088  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-15 17:20:47.089  6708  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-15 17:20:47.089  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:47.089  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:47.089  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:47.089  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:47.089  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:47.089  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.089  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:47.089  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:47.089  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:47.089  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:47.089  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:47.089  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.089  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:47.089  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.091  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:47.091  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:47.097  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:47.097  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:47.097  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:47.098  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSetting,s: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
,08-15 17:20:47.100  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:47.102  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-15 17:20:47.104  1036  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-15 17:20:47.104  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:47.105  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:47.105  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:47.105  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:47.105  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:47.105  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.105  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:47.105  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:47.106  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:47.106  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:47.106  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:47.106  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.106  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:47.106  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.107  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:47.107  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:47.107  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:47.108  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:20:47.108  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:47.108  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:47.109  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:20:47.109  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:20:47.109  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:20:47.109  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:20:47.109  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:47.109  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.109  6708  6776 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36c61aac not in the list
08-15 17:20:47.109  6708  6776 I org.thaliproject.p2p.btconne,ctorlib.DiscoveryManager: dispose
08-15 17:20:47.109  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
08-15 17:20:47.109  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:20:47.109  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:47.109  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.110  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:20:47.110  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:20:47.110  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:20:47.111  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:20:47.111  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:20:47.111  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-15 17:20:47.111  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:20:47.111  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b81f375 not in the list
,08-15 17:20:47.114  6708  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-15 17:20:47.114  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-15 17:20:47.114  6708  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-15 17:20:47.114  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-15 17:20:47.114  6708  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-15 17:20:47.114  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-15 17:20:47.117  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-15 17:20:47.117  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-15 17:20:47.118  6708  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-15 17:20:47.119  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-15 17:20:47.119  6708  6776 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-15 17:20:47.119  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-15 17:20:47.119  6708  6776 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-15 17:20:47.119  6708  6776 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-15 17:20:47.120  6708  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-15 17:20:47.120  6708  6776 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-15 17:20:47.121  6708  6776 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-15 17:20:47.123  6708  6776 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-15 17:20:47.123  6708  6776 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-15 17:20:47.123  6708  6776 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-15 17:20:47.125  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-15 17:20:47.125  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13814e29 added. We now have 2 listener(s)
08-15 17:20:47.125  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 17:20:47.126  6708  6776 D BluetoothAdapter: enable(): BT is already enabled..!
08-15 17:20:47.128  1036  1902 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 17:20:47.129  1036  1902 D WifiService: setWifiEnabled: true pid=6708, uid=10118
,08-15 17:20:47.129  1036  1902 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-15 17:20:47.131  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:20:47.131  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1094f5ae added. We now have 3 listener(s)
08-15 17:20:47.131  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 17:20:47.136  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:20:47.136  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24dbcf4f added. We now have 4 listener(s)
08-15 17:20:47.136  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 17:20:47.139  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-15 17:20:47.139  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10db86dc added. We now have 5 listener(s)
08-15 17:20:47.139  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:20:47.142  1036  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-15 17:20:47.143  1036  1051 D WifiService: setWifiEnabled: false pid=6708, uid=10118
08-15 17:20:47.143  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 17:20:47.166  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network],
08-15 17:20:47.166  1036  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0,
08-15 17:20:47.167  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-15 17:20:47.167  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 17:20:47.167  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-15 17:20:47.167  1036  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-15 17:20:47.169  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:47.169  1036  2032 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@302698be mBinding = false
08-15 17:20:47.171  1036  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-15 17:20:47.171  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
,08-15 17:20:47.172  1036  1440 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-15 17:20:47.172  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 17:20:47.172  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 17:20:47.173  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-15 17:20:47.173  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 17:20:47.183  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-15 17:20:47.183  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 17:20:47.184  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.184  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 17:20:47.184  2723  2723 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 17:20:47.185  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-15 17:20:47.185  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
,08-15 17:20:47.188  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-15 17:20:47.189  1036  2863 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 17:20:47.191  1036  1118 D BluetoothManagerService: Message: 2
08-15 17:20:47.191   308   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 17:20:47.193  1036  1118 D BluetoothManagerService: Sending off request.
08-15 17:20:47.194  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 17:20:47.195  3831  3847 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-15 17:20:47.195  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 17:20:47.195  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 17:20:47.196  3831  3920 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-15 17:20:47.196  3831  3920 D BluetoothAdapterProperties: Setting state to 13
08-15 17:20:47.196  3831  3920 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-15 17:20:47.199  3831  3920 D BluetoothAdapterProperties: onBluetoothDisable()
08-15 17:20:47.199  3831  3920 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-15 17:20:47.206  3831  3927 D BluetoothAdapterProperties: Scan Mode:20
08-15 17:20:47.207  3831  3920 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-15 17:20:47.208  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:20:47.208  3831  4347 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:47.208  3831  3920 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-15 17:20:47.208  6708  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 830)
08-15 17:20:47.209  1036  1118 D BluetoothManagerService: Message: 60
08-15 17:20:47.209  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-15 17:20:47.209  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-15 17:20:47.210  3831  4276 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-15 17:20:47.210  3831  4276 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:47.210  3831  4276 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-15 17:20:47.210  3831  4276 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-15 17:20:47.210  3831  4276 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-15 17:20:47.210  3831  4276 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-15 17:20:47.210  3831  4276 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-15 17:20:47.210  3831  4276 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-15 17:20:47.211  3831  4287 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:47.212  3831  4344 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:47.212  3831  4345 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:47.213  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-15 17:20:47.213  3831  4113 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-15 17:20:47.214  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.214  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:20:47.214  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:47.214  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:47.214  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:47.214  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:47.214  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:47.214  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:20:47.214  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:20:47.214  3831  ,4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-15 17:20:47.214  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-15 17:20:47.215  3831  4113 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-15 17:20:47.216  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.216  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:47.217  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 17:20:47.219  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:47.221  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:47.224  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.224  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:47.224  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:47.224  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:47.224  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:47.224  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:47.224  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:47.224  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:20:47.224  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:47.224  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.224  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:20:47.227  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 17:20:47.234  1036  1519 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-15 17:20:47.235  1036  1519 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-15 17:20:47.235  1036  1940 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-15 17:20:47.236  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.236  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.236  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-15 17:20:47.236  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.236  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-15 17:20:47.260  1036  1104 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6821 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-15 17:20:47.264  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 17:20:47.265  3831  3831 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:47.265  3831  3831 D BluetoothMapService: STATE_TURNING_OFF
08-15 17:20:47.265  3831  3831 V BtOppService: Receiver DISABLED_ACTION 
08-15 17:20:47.265  3831  3831 V BluetoothMapService: Handler(): got msg=4
08-15 17:20:47.265  3831  3831 D BluetoothMapService: MAP Service closeService in
08-15 17:20:47.265  3831  3831 D BluetoothMapMasInstance: MAP Service shutdown
08-15 17:20:47.266  3831  3831 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 17:20:47.266  3831  3831 V BluetoothMapService: MAP Service closeService out
08-15 17:20:47.266  3831  3831 I BtOppRfcommListener: stopping Accept Thread
08-15 17:20:47.266  3831  3831 V BtOppRfcommListener: close mBtServerSocket
08-15 17:20:47.266  3831  4344 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-15 17:20:47.268  3831  3831 V BtOppRfcommListener: waiting for thread to terminate
08-15 17:20:47.268  3831  3831 V BtOppRfcommListener: done waiting for thread to terminate
08-15 17:20:47.269  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:47.271  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.271  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:47.271  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:47.271  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:47.271  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:47.271  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:47.271  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:47.271  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:47.271  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:47.272  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.272  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:20:47.273  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.273  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:47.273  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:47.273  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:47.273  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:47.273  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:47.273  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:47.273  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:47.273  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 17:20:47.276  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.276  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:20:47.308  1036  1519 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-15 17:20:47.308  1036  1519 D DSQN    : disableDataServiceNotify
08-15 17:20:47.308  1036  1519 D DSQN    : stop dsqn bin
08-15 17:20:47.309   308  6844 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-15 17:20:47.310  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-15 17:20:47.310  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-15 17:20:47.310  1036  1104 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6840 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-15 17:20:47.311  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-15 17:20:47.313  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 17:20:47.313  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:47.313  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:47.313  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 17:20:47.314  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 17:20:47.314  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:47.314  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:47.314  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 17:20:47.314  3831  3831 V BtOppService: onDestroy
08-15 17:20:47.318  3831  3831 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-15 17:20:47.318  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-15 17:20:47.318  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-15 17:20:47.318  1036  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.318  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.319  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.319  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.319  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:47.319  1036  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@62e5a7b
08-15 17:20:47.319  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:47.320  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:47.320  1036  1391 D LGWifiP2pService: P2pDisablingState
08-15 17:20:47.320  1036  1391 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.320  1036  1391 D LGWifiP2pService: p2p socket connection lost
08-15 17:20:47.320  1036  1391 D LGWifiP2pService: P2pDisabledState
08-15 17:20:47.320  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:47.320  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:47.322  1036  1519 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-15 17:20:47.322  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:47.322  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:47.322  1036  1519 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:47.322  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-15 17:20:47.322  1,941  1941 D WfdsService: WifiP2pState is changed : false
08-15 17:20:47.322  1036  1519 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-15 17:20:47.322  1941  2295 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-15 17:20:47.322  1941  2295 D WfdsService: Set the WFDS Monitor: false
08-15 17:20:47.323  1036  1519 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-15 17:20:47.323  1036  1519 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-15 17:20:47.323  1941  2295 D WfdsMonitor: WFDS Monitor is stopped
08-15 17:20:47.323  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 17:20:47.323  1941  2295 D WfdsService: STATE : WfdsDisabledState - enter
08-15 17:20:47.323  1941  2768 D CtrlSupplicant: Received on exit socket, terminate
08-15 17:20:47.323  1941  2768 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-15 17:20:47.323  1941  2768 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-15 17:20:47.323  1941  2768 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-15 17:20:47.323  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.323  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.323  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-15 17:20:47.323  1941  2295 W WfdsService: DefaultState - msg [9445378] is not handled
08-15 17:20:47.324  1941  2297 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-15 17:20:47.324  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-15 17:20:47.325  1036  1519 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:47.325  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 17:20:47.325  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:47.326  1036  1440 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-15 17:20:47.326  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-15 17:20:47.326  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-15 17:20:47.326  1036  1519 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:47.327  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 17:20:47.327  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 17:20:47.327  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 17:20:47.327  1036  1519 D C,onnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:47.327  1036  1519 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:47.328  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:47.328  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 17:20:47.328  1036  1519 D NetworkManagementService: Removing idletimer
08-15 17:20:47.328  1036  1519 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:47.328  1036  1519 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-15 17:20:47.329  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-15 17:20:47.329  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-15 17:20:47.329  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:47.329  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 17:20:47.329  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 17:20:47.329  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 17:20:47.329  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:47.329  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:47.330  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-15 17:20:47.330  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 17:20:47.330  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.330  2723  2723 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 17:20:47.330  1036  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.330  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 17:20:47.330  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 17:20:47.331  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-15 17:20:47.331   308   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 17:20:47.334  1036  1440 D WifiNative-p2p0: doBoolean: TERMINATE
08-15 17:20:47.335  1036  1440 D WifiNative-p2p0: TERMINATE: returned true
08-15 17:20:47.335  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 17:20:47.335  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-15 17:20:47.335  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 17:20:47.335  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 17:20:47.335  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:47.335  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:47.335  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 17:20:47.335  1036  1440 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:47.335  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:20:47.338  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-15 17:20:47.338  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-15 17:20:47.338  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:20:47.338  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-15 17:20:47.339  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.339  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:47.339  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:47.339  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:47.339  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:47.339  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:47.339  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:47.339  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:47.339  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:47.339  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.339  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:20:47.341  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.341  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:47.341  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:47.341  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:47.341  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:47.341  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:47.341  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:47.341  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:47.341  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:47.341  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:47.341  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:47.341  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:47.341  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:20:47.342  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 17:20:47.366  6840  6840 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 17:20:47.366  6840  6840 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-15 17:20:47.367  6840  6840 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 17:20:47.367  6840  6840 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-15 17:20:47.368  6840  6840 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-15 17:20:47.368  6840  6840 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-15 17:20:47.373  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:47.373  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:47.374  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:47.389  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 17:20:47.389  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:47.390  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 17:20:47.401  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 17:20:47.401  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:47.402  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:47.405  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-15 17:20:47.405  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:47.405  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:47.407  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:47.410  6821  6821 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-15 17:20:47.410  6821  6821 W LG Account v2.2: No ProfileInfo entries
08-15 17:20:47.410  6821  6821 I LG Account v2.2: isEnabled: false
08-15 17:20:47.410  6821  6821 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-15 17:20:47.411  6821  6821 I Feature : [Lifetracker]Country: EU
08-15 17:20:47.411  6821  6821 I Feature : [Lifetracker]Operator: OPEN
08-15 17:20:47.411  6821  6821 I Feature : [Lifetracker]Ranking support: false
08-15 17:20:47.411  6821  6821 I Feature : [Lifetracker]Comfort support: false
08-15 17:20:47.411  6821  6821 I Feature : [Lifetracker]Accessory: true
08-15 17:20:47.411  6821  6821 I Feature : [Lifetracker]Health device: true
08-15 17:20:47.411  6821  6821 I Feature : [Lifetracker]Extra Pedometer: false
08-15 17:20:47.411  6821  6821 I Feature : [Lifetracker]Blood glucose device: false
08-15 17:20:47.411  6821  6821 I Feature : [Lifetracker]Device Number: 3
08-15 17:20:47.417  2723  2723 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-15 17:20:47.417  2723  2723 I wpa_supplicant: monitor socket send errors count : 1
08-15 17:20:47.417  2723  2723 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
,08-15 17:20:47.418  1036  2762 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-15 17:20:47.418  1036  2762 D WifiMonitor: Dropping event because (p2p0) is stopped
08-15 17:20:47.421  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:47.424  1036  2863 D DhcpStateMachine: StoppedState
08-15 17:20:47.424  1036  2863 D DhcpStateMachine: StoppedState{ when=-94ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:47.452  1036  2032 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6861 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-15 17:20:47.452  1036  2032 I ActivityManager: Killing 6165:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-15 17:20:47.454  6840  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-15 17:20:47.478  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-15 17:20:47.478  1036  1440 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-15 17:20:47.479  1036  1876 W libprocessgroup: failed to open /acct/uid_10014/pid_6165/cgroup.procs: No such file or directory
08-15 17:20:47.486  3831  3831 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 17:20:47.486  3831  3831 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:47.486  3831  3831 V BluetoothPbapReceiver: ***********state = 13
08-15 17:20:47.487  1036  1118 D BluetoothManagerService: Message: 20
08-15 17:20:47.487  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c49f8b1:true
08-15 17:20:47.488  3831  3831 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-15 17:20:47.489  3831  3831 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:47.489  3831  3831 V BluetoothPbapService: state: 13
08-15 17:20:47.489  3831  3831 V BluetoothPbapService: Pbap Service closeService in
08-15 17:20:47.491  3831  3831 V BluetoothPbapService: successfully stopped pbap service
08-15 17:20:47.491  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 17:20:47.491  3831  3831 V BluetoothPbapService: Pbap Service closeService out
08-15 17:20:47.491  3831  3831 V BluetoothPbapService: Pbap Service onDestroy
08-15 17:20:47.491  3831  3831 V BluetoothPbapService: Pbap Service closeService in
08-15 17:20:47.491  3831  3831 V BluetoothPbapService: Pbap Service closeService out
08-15 17:20:47.492  3831  3831 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-15 17:20:47.506  1036  1118 D BluetoothManagerService: Message: 30
,08-15 17:20:47.511  1036  1118 D BluetoothManagerService: Message: 30
08-15 17:20:47.513  6840  6840 D LocalBluetoothProfileManager: Adding local MAP profile
08-15 17:20:47.514  6840  6840 D BluetoothMap: Create BluetoothMap proxy object
08-15 17:20:47.515  1036  1118 D BluetoothManagerService: Message: 30
08-15 17:20:47.517  2723  2723 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 17:20:47.518  2723  2723 W wpa_supplicant: USIM:  scard_deinit function
,08-15 17:20:47.518  1036  1118 D Tethering: InitialState.processMessage what=4
08-15 17:20:47.518  1036  2762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-15 17:20:47.518  1036  2762 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 17:20:47.518  1036  2762 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 17:20:47.519  1036  2762 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-15 17:20:47.519  1036  2762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:20:47.519  1036  2762 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:20:47.519  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-15 17:20:47.519  1036  1440 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=334450
08-15 17:20:47.520  1036  1440 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=334451
08-15 17:20:47.520  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=334451  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-15 17:20:47.521  1036  1440 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=334452  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-15 17:20:47.521  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:47.522  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:47.524  1036  1118 D BluetoothManagerService: Message: 30
08-15 17:20:47.526  6840  6840 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-15 17:20:47.527  6840  6840 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-15 17:20:47.532  6861  6861 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-15 17:20:47.538  6840  6840 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-15 17:20:47.538  6861  6861 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-15 17:20:47.538  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:20:47.540  1036  1991 I ActivityManager: Killing 2121:com.lge.music/u0a34 (adj 15): empty #17
08-15 17:20:47.541  6840  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-15 17:20:47.559   313  2148 V AudioFlinger: 2121 died, releasing its sessions
08-15 17:20:47.559   313  2148 V AudioFlinger:  pid 1851 @ 0
08-15 17:20:47.559   313  2148 V AudioFlinger:  pid 3396 @ 1
08-15 17:20:47.559   313  2148 V AudioFlinger:  pid 3396 @ 2
,08-15 17:20:47.573  1036  1051 W libprocessgroup: failed to open /acct/uid_10034/pid_2121/cgroup.procs: No such file or directory
,08-15 17:20:47.579  6840  6840 D DockEventReceiver: finishStartingService: stopping service
,08-15 17:20:47.586  6708  6708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-15 17:20:47.588  6840  6840 D BluetoothInputDevice: Proxy object connected
,08-15 17:20:47.589  6840  6840 D HidProfile: Bluetooth service connected
08-15 17:20:47.590  6840  6840 D BluetoothPan: BluetoothPAN Proxy object connected
08-15 17:20:47.591  6840  6840 D PanProfile: Bluetooth service connected
08-15 17:20:47.592  6840  6840 D BluetoothMap: Proxy object connected
08-15 17:20:47.593  6840  6840 D MapProfile: Bluetooth service connected
08-15 17:20:47.593  6840  6840 D BluetoothMap: getConnectedDevices()
08-15 17:20:47.594  6840  6840 D BluetoothMap: Bluetooth is Not enabled
08-15 17:20:47.599  2723  2723 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-15 17:20:47.599  1036  2762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-15 17:20:47.599  1036  2762 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-15 17:20:47.600  1036  2762 D WifiMonitor: Disconnecting from the supplicant, no more events
08-15 17:20:47.600  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-15 17:20:47.609  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 17:20:47.646  6840  6840 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:20:47.646  6840  6840 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:20:47.657  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 17:20:47.658  6840  6840 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-15 17:20:47.660  6840  6840 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-15 17:20:47.667  6840  6840 D BluetoothPermissionRequest: onReceive
08-15 17:20:47.670  6840  6840 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-15 17:20:47.683  6840  6840 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 17:20:47.684  1036  1576 I ActivityManager: Killing 6289:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-15 17:20:47.792  3831  3831 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-15 17:20:47.792  3831  3831 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-15 17:20:47.794  3831  3831 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-15 17:20:47.797  1036  1905 W libprocessgroup: failed to open /acct/uid_10004/pid_6289/cgroup.procs: No such file or directory
08-15 17:20:47.811  1036  1440 D WifiOffDelayIfNotUsed: stopMonitoring
08-15 17:20:47.811  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 17:20:47.811  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-15 17:20:47.811  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-15 17:20:47.815  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-15 17:20:47.816  1941  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-15 17:20:47.817  1941  2295 D WfdsService: Set the WFDS Monitor: false
08-15 17:20:47.817  1941  2295 D WfdsMonitor: WFDS Monitor is stopped
08-15 17:20:47.842  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-15 17:20:47.842  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:47.848  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-15 17:20:47.848  3831  3831 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:47.849  3831  3831 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-15 17:20:47.849  1036  1470 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-15 17:20:47.849  1036  1470 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-15 17:20:47.850  3831  3831 V BluetoothFtpService: Ftp Service onStartCommand
08-15 17:20:47.850  3831  3831 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:47.851  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:47.851  2502  2502 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:47.851  3831  3831 V BluetoothFtpService: Ftp Service closeService
08-15 17:20:47.851  3831  3831 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-15 17:20:47.853  3831  3831 V BluetoothFtpService: successfully stopped ftp service
08-15 17:20:47.853  3831  3831 V BluetoothFtpService: Ftp Service onDestroy
08-15 17:20:47.853  3831  3831 V BluetoothFtpService: Ftp Service closeService
08-15 17:20:47.854  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:47.910  1036  1576 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6892 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-15 17:20:47.913  3831  3831 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 17:20:47.913  3831  3831 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 17:20:47.913  3831  3831 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 17:20:47.913  3831  3831 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:47.913  3831  3831 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-15 17:20:47.913  3831  3831 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-15 17:20:47.915  3831  3831 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:47.915  3831  3831 V BluetoothSapService: state: 13
08-15 17:20:47.915  3831  3831 V BluetoothSapService: Stopping SAP server process
08-15 17:20:47.917  3831  3831 V BluetoothSapService: Sap Service closeSapService in
08-15 17:20:47.917  3831  3831 V BluetoothSapService: Close listen Socket : 
08-15 17:20:47.917  3831  3831 V BluetoothSapService: Close rfcomm Socket : 
08-15 17:20:47.918  3831  3831 V BluetoothSapService: Close sapd  Socket : 
08-15 17:20:47.920  3831  3831 V BluetoothSapService: Sap Service closeSapService out
08-15 17:20:47.920  3831  3831 V BluetoothSapService: Sap Service onDestroy
08-15 17:20:47.920  3831  3831 V BluetoothSapService: Sap Service closeSapService in
08-15 17:20:47.920  3831  3831 V BluetoothSapService: Close listen Socket : 
08-15 17:20:47.920  3831  3831 V BluetoothSapService: Close rfcomm Socket : 
08-15 17:20:47.920  3831  3831 V BluetoothSapService: Close sapd  Socket : 
08-15 17:20:47.921  3831  3831 V BluetoothSapService: Sap Service closeSapService out
08-15 17:20:47.972  1036  1576 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6909 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-15 17:20:47.996   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 21.877ms
,08-15 17:20:48.012  6892  6892 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-15 17:20:48.017   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 20.409ms
08-15 17:20:48.038  6909  6909 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-15 17:20:48.042   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 21.274ms
08-15 17:20:48.054  6892  6892 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-15 17:20:48.056  1036  1052 I ActivityManager: Killing 6456:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-15 17:20:48.109  1036  1956 W libprocessgroup: failed to open /acct/uid_10008/pid_6456/cgroup.procs: No such file or directory
,08-15 17:20:48.166  6892  6892 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-15 17:20:48.168  6892  6892 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-15 17:20:48.168  6892  6892 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-15 17:20:48.169  6892  6892 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-15 17:20:48.169  6892  6892 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-15 17:20:48.171  6892  6892 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-15 17:20:48.178  6892  6892 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-15 17:20:48.192  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 17:20:48.193  1036  3500 I LocationManagerService: remove 23857e89
,08-15 17:20:48.194  1036  3500 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-15 17:20:48.195  1036  3500 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 17:20:48.196  1036  3500 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-15 17:20:48.198  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:48.198  1036  3500 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-15 17:20:48.200  1036  3500 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-15 17:20:48.218  3831  3927 D bt_hci_bdroid: cleanup
08-15 17:20:48.218  3831  4116 I bt_lpm  : LPM is already off!!!
08-15 17:20:48.219  3831  4249 I bt_userial_mct: exiting userial_read_thread
08-15 17:20:48.219  3831  4249 D bt_userial_mct: Leaving userial_evt_read_thread()
08-15 17:20:48.219  3831  4113 W bt-btif : ag scb idx 1 not allocated
08-15 17:20:48.219  3831  4113 E bt-btif : BTA AG is already disabled, ignoring ...
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 17:20:48.219  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 17:20:48.220  3831  4113 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 17:20:48.220  3831  4113 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:20:48.220  3831  4113 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 17:20:48.220  3831  4113 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-15 17:20:48.220  3831  3927 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-15 17:20:48.220  3831  4116 I bt_vendor: hw_epilog_process
,08-15 17:20:48.220  3831  3927 D bt_hci_bdroid: cleanup Finalizing cleanup
08-15 17:20:48.220  3831  3927 D bt_userial_mct: userial_close
08-15 17:20:48.220  3831  3927 E bt_userial_mct: pthread_join() FAILED result:3
08-15 17:20:48.220  3831  3927 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-15 17:20:48.237  6892  6892 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-15 17:20:48.242  6892  6892 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-15 17:20:48.242  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:48.245  6892  6892 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-15 17:20:48.249  6861  6861 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 17:20:48.249  6861  6861 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 17:20:48.249  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:20:48.257  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:48.267  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:48.280  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 17:20:48.282  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:48.285  6892  6892 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 17:20:48.290  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:48.296  6861  6861 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 17:20:48.296  6861  6861 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 17:20:48.296  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 17:20:48.297  3831  3927 D bt_hci_bdroid: set_power 0
08-15 17:20:48.297  3831  3927 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-15 17:20:48.297  3831  3927 I bt_vendor: bluetooth satus is on
08-15 17:20:48.297  3831  3927 I bt_vendor: bt-vendor : resetting BT status
08-15 17:20:48.297  3831  3927 I bt_vendor: Starting hciattach daemon
08-15 17:20:48.297  3831  3927 I bt_vendor: try to set false
08-15 17:20:48.299  3831  3927 I bt_vendor: Starting hciattach daemon
08-15 17:20:48.299  3831  3927 I bt_vendor: try to set false
08-15 17:20:48.300  3831  3927 I bt_vendor: cleanup
08-15 17:20:48.302  3831  4113 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-15 17:20:48.303  3831  3927 I GKI_LINUX: GKI_exit_task 0 done
08-15 17:20:48.303  3831  3927 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-15 17:20:48.305  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 17:20:48.307  3831  3920 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-15 17:20:48.314  3831  3831 D HeadsetService: Received stop request...Stopping profile...
08-15 17:20:48.321  3831  3831 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-15 17:20:48.321  3831  3831 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 17:20:48.321  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3661c1ea
08-15 17:20:48.322  3831  3968 D HeadsetStateMachine: Exit Disconnected: -1
,08-15 17:20:48.326  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-15 17:20:48.326  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-15 17:20:48.326  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-15 17:20:48.326  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-15 17:20:48.328  3831  3920 D BluetoothAdapterState: Stopping profile services that were post enabled
08-15 17:20:48.328  3831  3831 D A2dpService: Received stop request...Stopping profile...
08-15 17:20:48.329  3831  4062 D A2dpStateMachine: Exit Disconnected: -1
08-15 17:20:48.329  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-15 17:20:48.330  3831  3831 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-15 17:20:48.333  3831  3831 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-15 17:20:48.333  3831  3831 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 17:20:48.333  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3661c1ea
08-15 17:20:48.334  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-15 17:20:48.334  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:48.334  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-15 17:20:48.337  3831  3831 D HidService: Received stop request...Stopping profile...
08-15 17:20:48.337  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3661c1ea
08-15 17:20:48.340  3831  3831 D HealthService: Received stop request...Stopping profile...
08-15 17:20:48.340  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3661c1ea
08-15 17:20:48.342  6840  6840 D BluetoothInputDevice: Proxy object disconnected
08-15 17:20:48.342  6840  6840 D HidProfile: Bluetooth service disconnected
08-15 17:20:48.342  3831  3831 D PanService: Received stop request...Stopping profile...
08-15 17:20:48.343  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3661c1ea
08-15 17:20:48.347  6840  6840 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-15 17:20:48.347  6840  6840 D PanProfile: Bluetooth service disconnected
,08-15 17:20:48.349  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:48.350  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:48.350  3831  3831 D BtGatt.DebugUtils: handleDebugAction() action=null
08-15 17:20:48.351  3831  3831 D BtGatt.GattService: Received stop request...Stopping profile...
08-15 17:20:48.351  3831  3831 D BtGatt.GattService: stop()
08-15 17:20:48.351  3831  3831 D BtGatt.AdvertiseManager: advertise clients cleared
08-15 17:20:48.352  6892  6892 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 17:20:48.353  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3661c1ea
08-15 17:20:48.426  1036  1876 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6938 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-15 17:20:48.427  3831  3831 D HeadsetStateMachine: Unbinding service...
08-15 17:20:48.430  3831  3831 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 17:20:48.430  3831  3831 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 17:20:48.430  3831  3831 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 17:20:48.431  3831  3831 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 17:20:48.431  3831  3831 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-15 17:20:48.431  3831  3831 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 17:20:48.431  3831  3831 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-15 17:20:48.431  3831  3831 D BluetoothMapService: Received stop request...Stopping profile...
08-15 17:20:48.431  3831  3831 D BluetoothMapService: stop()
08-15 17:20:48.432  3831  3831 D BluetoothMapEmailAppObserver: deinitObservers()
08-15 17:20:48.432  3831  3831 D BluetoothMapEmailAppObserver: removeReceiver()
08-15 17:20:48.433  3831  3831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3661c1ea
08-15 17:20:48.435  3831  3831 I BluetoothA2dpServiceJni: cleanupNative
08-15 17:20:48.435  3831  4063 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-15 17:20:48.435  3831  3831 I GKI_LINUX: GKI_exit_task 2 done
08-15 17:20:48.435  3831  3831 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-15 17:20:48.436  3831  3831 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-15 17:20:48.436  3831  3831 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-15 17:20:48.436  3831  3831 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-15 17:20:48.436  3831  3831 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-15 17:20:48.436  3831  3831 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-15 17:20:48.436  6840  6840 D BluetoothMap: Proxy object disconnected
08-15 17:20:48.436  3831  3831 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-15 17:20:48.436  3831  3831 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-15 17:20:48.436  6840  6840 D MapProfile: Bluetooth service disconnected
08-15 17:20:48.438  3831  3831 V BluetoothMapService: Handler(): got msg=4
08-15 17:20:48.438  3831  3831 D BluetoothMapService: MAP Service closeService in
08-15 17:20:48.438  3831  3831 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 17:20:48.438  3831  3831 V BluetoothMapService: MAP Service closeService out
,08-15 17:20:48.439  3831  3920 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-15 17:20:48.440  3831  3920 D BluetoothAdapterProperties: Setting state to 10
08-15 17:20:48.440  3831  3920 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-15 17:20:48.440  1036  1118 D BluetoothManagerService: Message: 60
08-15 17:20:48.440  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-15 17:20:48.440  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-15 17:20:48.440  3831  3831 D BluetoothMapService: cleanup()
08-15 17:20:48.440  3831  3831 D BluetoothMapService: MAP Service closeService in
08-15 17:20:48.440  3831  3831 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 17:20:48.440  3831  3831 V BluetoothMapService: MAP Service closeService out
08-15 17:20:48.441  3831  3920 I BluetoothAdapterState: Entering OffState
08-15 17:20:48.441  6840  6857 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-15 17:20:48.442  6840  6856 D BluetoothMap: onBluetoothStateChange: up=false
08-15 17:20:48.442  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 17:20:48.443  6840  6857 D BluetoothPbap: onBluetoothStateChange: up=false
08-15 17:20:48.443  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 17:20:48.444  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 17:20:48.444  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 17:20:48.445  6840  6856 D BluetoothPan: onBluetoothStateChange on: false
08-15 17:20:48.446  1851  2446 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 17:20:48.450  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-15 17:20:48.450  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-15 17:20:48.453  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-15 17:20:48.453  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-15 17:20:48.453  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@302698be mBinding = false
08-15 17:20:48.454  1036  1118 D BluetoothManagerService: Sending unbind request.
08-15 17:20:48.457  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-15 17:20:48.468  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 17:20:48.472  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:48.472  1941  2137 D LGBluetoothAPIService: Message: 2
08-15 17:20:48.472  1941  2137 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@8bddce5 mBinding = false
08-15 17:20:48.472  1941  2137 D LGBluetoothAPIService: Sending unbind request.
08-15 17:20:48.474  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:48.474  3831  3927 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-15 17:20:48.474  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:48.475  3831  3831 I GKI_LINUX: GKI_exit_task 1 done
08-15 17:20:48.475  3831  3831 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-15 17:20:48.477  1604  1604 D BluetoothAdapter: 414211266: getState() :  mService = null. Returning STATE_OFF
08-15 17:20:48.477  3831  3831 I BluetoothServiceJni: cleanupNative: return from cleanup
08-15 17:20:48.477  1604  1604 D BluetoothAdapter: 414211266: getState() :  mService = null. Returning STATE_OFF
08-15 17:20:48.477  3831  3831 I art     : --- WEIRD: removing null entry 246
08-15 17:20:48.477  3831  3831 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-15 17:20:48.477  3831  3831 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-15 17:20:48.478  6840  6840 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-15 17:20:48.478  3831  3831 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-15 17:20:48.479  6840  6840 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-15 17:20:48.479  6840  6840 D LGBluetoothEventManager: [BTUI] clear device connection state
08-15 17:20:48.480  6840  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-15 17:20:48.481  3831  3831 I art     : System.exit called, status: 0
08-15 17:20:48.481  3831  3831 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-15 17:20:48.488  6840  6840 D DockEventReceiver: finishStartingService: stopping service
08-15 17:20:48.502   313   313 V AudioFlinger: 3831 died, releasing its sessions
08-15 17:20:48.502   313   313 V AudioFlinger:  pid 1851 @ 0
08-15 17:20:48.502   313   313 V AudioFlinger:  pid 3396 @ 1
08-15 17:20:48.502   313   313 V AudioFlinger:  pid 3396 @ 2
08-15 17:20:48.503  6840  6840 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-15 17:20:48.577  1036  1976 I ActivityManager: Process com.android.bluetooth (pid 3831) has died
08-15 17:20:48.577  1036  1976 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-15 17:20:48.600  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-15 17:20:48.621  6840  6840 D BluetoothPermissionRequest: onReceive
,08-15 17:20:48.624  6840  6840 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-15 17:20:48.625  6840  6840 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-15 17:20:48.628  6840  6840 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 17:20:48.712  1036  2032 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6957 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-15 17:20:48.723  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:20:48.727  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 17:20:48.740  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:48.771  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-15 17:20:48.771  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-15 17:20:48.771  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 17:20:48.771  6840  6840 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-15 17:20:48.773  6938  6976 W FormManager: Network not available. Please check & try again.
08-15 17:20:48.773  6957  6957 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-15 17:20:48.773  6957  6957 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 17:20:48.774  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 17:20:48.774  6957  6957 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-15 17:20:48.775  6957  6957 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-15 17:20:48.784  6938  6977 V FormManager: Network unavailable.
08-15 17:20:48.784  6840  6840 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-15 17:20:48.786  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-15 17:20:48.786  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 17:20:48.786  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 17:20:48.786  6840  6840 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 17:20:48.787  6840  6840 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-15 17:20:48.791  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 17:20:48.792  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 17:20:48.793  6938  6977 V FormManager: Network unavailable.
08-15 17:20:48.794  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 17:20:48.797  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:48.800  6957  6957 D BluetoothAdapterApp: Loading JNI Library
08-15 17:20:48.805  6861  6861 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-15 17:20:48.805  6861  6861 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 17:20:48.805  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:20:48.807  4291  6980 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 17:20:48.808  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 17:20:48.816  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:48.828  4291  6981 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 17:20:48.828  4291  6981 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-15 17:20:48.833  6938  6983 V FormManager: Network unavailable.
08-15 17:20:48.837  6938  6983 V FormManager: Network unavailable.
08-15 17:20:48.839  6892  6892 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-15 17:20:48.840  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-15 17:20:48.840  6892  6892 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-15 17:20:48.842  6938  6982 W FormManager: Network not available. Please check & try again.
,08-15 17:20:48.845  1036  1876 I ActivityManager: Killing 5976:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-15 17:20:48.846  6957  6957 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3e4b7463 Instance Count = 1
08-15 17:20:48.878  6892  6892 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 17:20:48.879  6892  6892 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 17:20:48.886  6892  6892 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-15 17:20:48.887  6892  6892 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-15 17:20:48.887  6892  6892 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-15 17:20:48.887  6892  6892 V SoundPool: doLoad: loading sample sampleID=1
08-15 17:20:48.888  6892  6892 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-15 17:20:48.890  6892  6991 V SoundPool: Start decode
08-15 17:20:48.890  6892  6991 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-15 17:20:48.891   313  2147 V MediaPlayerService: decode(23, 10857164, 17813)
08-15 17:20:48.891   313  2147 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,08-15 17:20:48.891   313  2147 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-15 17:20:48.891   313  2147 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-15 17:20:48.891   313  2147 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-15 17:20:48.891   313  2147 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-15 17:20:48.891   313  2147 V MediaPlayerService: player type = 3
08-15 17:20:48.891   313  2147 V AwesomePlayer: AwesomePlayer create()
08-15 17:20:48.891   313  2147 V AwesomePlayer: reset_l() 
08-15 17:20:48.891   313  2147 V AwesomePlayer: cancelPlayerEvents
08-15 17:20:48.891   313  2147 V AwesomePlayer: setAudioSink() 
08-15 17:20:48.891   313  2147 V AwesomePlayer: reset_l() 
08-15 17:20:48.891   313  2147 V AudioCache: notify(0xb5474a40, 8, 0, 0)
08-15 17:20:48.891   313  2147 V AudioCache: ignored
08-15 17:20:48.891   313  2147 V AwesomePlayer: cancelPlayerEvents
08-15 17:20:48.892   313  2147 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-15 17:20:48.892   313  2147 V AwesomePlayer: setDataSource_l dataSource
08-15 17:20:48.892   313  2147 V LGParserOSAL: SniffLGParser start
08-15 17:20:48.892   313  2147 V LGParserOSAL: MainType:5, SubType=0
08-15 17:20:48.892   313  2147 V LGParserOSAL: #### check Mime : application/ogg
08-15 17:20:48.892   313  2147 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-15 17:20:48.892   313  2147 E MediaExtractor: Use LGExtractor :application/ogg 
08-15 17:20:48.909  1036  1905 W libprocessgroup: failed to open /acct/uid_10011/pid_5976/cgroup.procs: No such file or directory
,08-15 17:20:48.909  6957  6957 D BluetoothAdapterApp: onCreate
08-15 17:20:48.913  6640  6640 D UEI.SmartControl: QS Service created
08-15 17:20:48.918  6892  6892 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-15 17:20:48.921  6892  6892 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-15 17:20:48.922  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-15 17:20:48.927  6640  6640 I UEI.SmartControl: Service initServices...
08-15 17:20:48.927  6640  6640 D UEI.SmartControl: QS start get config
,08-15 17:20:48.943  6957  6957 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-15 17:20:48.943  6957  6957 D ProfileConfigQcom: Adding HeadsetService
08-15 17:20:48.943  6957  6957 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-15 17:20:48.943  6957  6957 D ProfileConfigQcom: Adding A2dpService
08-15 17:20:48.943  6957  6957 D ProfileConfigQcom: [BTUI] HidService is supported
08-15 17:20:48.944  6957  6957 D ProfileConfigQcom: Adding HidService
08-15 17:20:48.944  6957  6957 D ProfileConfigQcom: [BTUI] HealthService is supported
08-15 17:20:48.944  6957  6957 D ProfileConfigQcom: Adding HealthService
08-15 17:20:48.944  6957  6957 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-15 17:20:48.945  6957  6957 D ProfileConfigQcom: [BTUI] PanService is supported
08-15 17:20:48.945  6957  6957 D ProfileConfigQcom: Adding PanService
08-15 17:20:48.946  6957  6957 D ProfileConfigQcom: [BTUI] GattService is supported
,08-15 17:20:48.946  6957  6957 D ProfileConfigQcom: Adding GattService
08-15 17:20:48.947  6957  6957 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-15 17:20:48.947  6957  6957 D ProfileConfigQcom: Adding BluetoothMapService
08-15 17:20:48.947  6892  6892 V LGMDMManager: Create singleton instance
08-15 17:20:48.947  6957  6957 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-15 17:20:48.948   313  2147 V LGParserOSAL: supported mime: application/ogg
08-15 17:20:48.948   313  2147 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-15 17:20:48.948   313  2147 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-15 17:20:48.948   313  2147 V AwesomePlayer: mBitrate = -1 bits/sec
08-15 17:20:48.948   313  2147 V AwesomePlayer: AudioTrack Setting
08-15 17:20:48.948   313  2147 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-15 17:20:48.948   313  2147 V AwesomePlayer: setAudioSource() 
08-15 17:20:48.948   313  2147 V MediaPlayerService: prepare
08-15 17:20:48.948   313  2147 V AwesomePlayer: prepareAsync_l() 
08-15 17:20:48.948   313  2147 V MediaPlayerService: wait for prepare
08-15 17:20:48.948   313  6993 V AwesomePlayer: onPrepareAsyncEvent() 
08-15 17:20:48.948   313  6993 V AwesomePlayer: initAudioDecoder() 
08-15 17:20:48.948   313  6993 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-15 17:20:48.948   313  6993 V AudioSystem: isOffloadSupported()
08-15 17:20:48.948   313  6993 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-15 17:20:48.948   313  6993 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-15 17:20:48.949   313  6993 I AudioFlinger: isAudioPlaybackHookOn() false
08-15 17:20:48.949   313  6993 V AwesomePlayer: getUseOffload() = 0 
08-15 17:20:48.949   313  6993 V OMXCodec: OMXCodec::Create
08-15 17:20:48.949   313  6993 V OMXCodec: findMatchingCodecs()
08-15 17:20:48.949   313  6993 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-15 17:20:48.949   313  6993 V OMXCodec: matchingCodecs.size()=1
08-15 17:20:48.949   313  6993 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-15 17:20:48.949  6957  6957 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-15 17:20:48.951   313  6993 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-15 17:20:48.951   313  6993 V LGCodecAdapter: LG Codec Adapter start
08-15 17:20:48.951   313  6993 V OMXCodec: OMXCodec Createtor
08-15 17:20:48.951   313  6993 V OMXCodec: setComponentRole
08-15 17:20:48.951   313  6993 V OMXCodec: configureCodec protected=0
08-15 17:20:48.951   313  6993 V LGCodecAdapter: called getLGCodecSpecificData
08-15 17:20:48.951   313  6993 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-15 17:20:48.951   313  6993 V LGCodecOSAL: Called LGconfigureCodecMETA
08-15 17:20:48.951   313  6993 V LGCodecOSAL: Called LGconfigureCodecMSG
08-15 17:20:48.951   313  6993 V LGCodecOSAL: Not support LGCodec
08-15 17:20:48.951   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-15 17:20:48.951   313  6993 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-15 17:20:48.951   313  6993 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-15 17:20:48.952   313  6993 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-15 17:20:48.952   313  6993 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-15 17:20:48.952   313  6993 V AudioSystem:, isOffloadSupported()
08-15 17:20:48.952   313  6993 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-15 17:20:48.952   313  6993 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-15 17:20:48.952   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-15 17:20:48.952   313  6993 V OMXCodec: init()
08-15 17:20:48.952   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-15 17:20:48.952   313  6993 V OMXCodec: allocateBuffers
08-15 17:20:48.952   313  6993 V OMXCodec: allocateBuffersOnPort portIndex=0
08-15 17:20:48.952   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-15 17:20:48.952   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-15 17:20:48.952   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-15 17:20:48.952   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-15 17:20:48.952   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-15 17:20:48.952   313  6993 V OMXCodec: allocateBuffersOnPort portIndex=1
08-15 17:20:48.952   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-15 17:20:48.953   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-15 17:20:48.953   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-15 17:20:48.953   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-15 17:20:48.953   313  6993 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1100 on output port
08-15 17:20:48.953   313  6993 V OMXCodec: init() mAsyncCompletion wait!!! 
08-15 17:20:48.953   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-15 17:20:48.953   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-15 17:20:48.953   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-15 17:20:48.953   313  6993 V OMXCodec: init() mAsyncCompletion wait!!! 
08-15 17:20:48.953   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-15 17:20:48.953   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-15 17:20:48.953   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-15 17:20:48.954   313  6993 V OMXCodec: init() mAsyncCompletion wait free! 
08-15 17:20:48.954   313  6993 V AwesomePlayer: finishAsyncPrepare_l() 
08-15 17:20:48.954   313  6993 V AudioCache: notify(0xb5474a40, 5, 0, 0)
08-15 17:20:48.954   313  6993 V AudioCache: ignored
08-15 17:20:48.954   313  6993 V AudioCache: notify(0xb5474a40, 1, 0, 0)
08-15 17:20:48.954   313  6993 V AudioCache: prepared
08-15 17:20:48.954   313  2147 V AudioCache: wait - success
08-15 17:20:48.954   313  2147 V MediaPlayerService: start
08-15 17:20:48.954   313  2147 V AwesomePlayer: play_l() 
,08-15 17:20:48.954   313  2147 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-15 17:20:48.954   313  2147 V AwesomePlayer: createAudioPlayer_l
08-15 17:20:48.954   313  2147 V AwesomePlayer: seekAudioIfNecessary_l() 
08-15 17:20:48.954   313  2147 V AwesomePlayer: startAudioPlayer_l() 
08-15 17:20:48.954   313  2147 D AudioPlayer: start of Playback, useOffload 0
08-15 17:20:48.954   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-15 17:20:48.954   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-15 17:20:48.954  6840  6840 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-15 17:20:48.957  6957  6957 V LGMDMManagerInternal: Create singleton instance
08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
,08-15 17:20:48.957   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044806912
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-15 17:20:48.958   313  6995 V OMXCodec: allocateBuffersOnPort portIndex=1
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port,
,08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-15 17:20:48.958   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-15 17:20:48.960   313  2147 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-15 17:20:48.960   313  2147 V AudioCache: notify(0xb5474a40, 6, 0, 0)
08-15 17:20:48.960   313  2147 V AudioCache: ignored
08-15 17:20:48.960   313  2147 V MediaPlayerService: wait for playback complete
08-15 17:20:48.961   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.961   313  6996 V AudioCache: memcpy(0xac300000, 0xb16f7000, 4096)
08-15 17:20:48.967   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.967   313  6996 V AudioCache: memcpy(0xac301000, 0xb16f7000, 4096)
08-15 17:20:48.967   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.967   313  6996 V AudioCache: memcpy(0xac302000, 0xb16f7000, 4096)
08-15 17:20:48.968   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.968   313  6996 V AudioCache: memcpy(0xac303000, 0xb16f7000, 4096)
08-15 17:20:48.968   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.968   313  6996 V AudioCache: memcpy(0xac304000, 0xb16f7000, 4096)
08-15 17:20:48.968   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.968   313  6996 V AudioCache: memcpy(0xac305000, 0xb16f7000, 4096)
08-15 17:20:48.968   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.968   313  6996 V AudioCache: memcpy(0xac306000, 0xb16f7000, 4096)
08-15 17:20:48.969   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.969   313  6996 V AudioCache: memcpy(0xac307000, 0xb16f7000, 4096)
08-15 17:20:48.969   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.969   313  6996 V AudioCache: memcpy(0xac308000, 0xb16f7000, 4096)
,08-15 17:20:48.969   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.969   313  6996 V AudioCache: memcpy(0xac309000, 0xb16f7000, 4096)
08-15 17:20:48.970   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.970   313  6996 V AudioCache: memcpy(0xac30a000, 0xb16f7000, 4096)
08-15 17:20:48.970   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.970   313  6996 V AudioCache: memcpy(0xac30b000, 0xb16f7000, 4096)
08-15 17:20:48.970   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.970   313  6996 V AudioCache: memcpy(0xac30c000, 0xb16f7000, 4096)
08-15 17:20:48.970   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.970   313  6996 V AudioCache: memcpy(0xac30d000, 0xb16f7000, 4096)
,08-15 17:20:48.971   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.971   313  6996 V AudioCache: memcpy(0xac30e000, 0xb16f7000, 4096)
08-15 17:20:48.971   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.971   313  6996 V AudioCache: memcpy(0xac30f000, 0xb16f7000, 4096)
08-15 17:20:48.971   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.971   313  6996 V AudioCache: memcpy(0xac310000, 0xb16f7000, 4096)
08-15 17:20:48.972   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.972   313  6996 V AudioCache: memcpy(0xac311000, 0xb16f7000, 4096)
08-15 17:20:48.972   313  6996 V AudioCache: write(0xb16f7000, 4096)
,08-15 17:20:48.972   313  6996 V AudioCache: memcpy(0xac312000, 0xb16f7000, 4096)
08-15 17:20:48.972   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.972   313  6996 V AudioCache: memcpy(0xac313000, 0xb16f7000, 4096)
08-15 17:20:48.972   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.972   313  6996 V AudioCache: memcpy(0xac314000, 0xb16f7000, 4096)
08-15 17:20:48.973   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.973   313  6996 V AudioCache: memcpy(0xac315000, 0xb16f7000, 4096)
08-15 17:20:48.973   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.973   313  6996 V AudioCache: memcpy(0xac316000, 0xb16f7000, 4096)
,08-15 17:20:48.973   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.973   313  6996 V AudioCache: memcpy(0xac317000, 0xb16f7000, 4096)
08-15 17:20:48.974   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.974   313  6996 V AudioCache: memcpy(0xac318000, 0xb16f7000, 4096)
08-15 17:20:48.974   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.974   313  6996 V AudioCache: memcpy(0xac319000, 0xb16f7000, 4096)
08-15 17:20:48.974   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.974   313  6996 V AudioCache: memcpy(0xac31a000, 0xb16f7000, 4096)
,08-15 17:20:48.975   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.975   313  6996 V AudioCache: memcpy(0xac31b000, 0xb16f7000, 4096)
08-15 17:20:48.975   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.975   313  6996 V AudioCache: memcpy(0xac31c000, 0xb16f7000, 4096)
08-15 17:20:48.975   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.975   313  6996 V AudioCache: memcpy(0xac31d000, 0xb16f7000, 4096)
,08-15 17:20:48.976   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.976   313  6996 V AudioCache: memcpy(0xac31e000, 0xb16f7000, 4096)
08-15 17:20:48.976   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.976   313  6996 V AudioCache: memcpy(0xac31f000, 0xb16f7000, 4096)
08-15 17:20:48.976   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.976   313  6996 V AudioCache: memcpy(0xac320000, 0xb16f7000, 4096)
08-15 17:20:48.977   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.977   313  6996 V AudioCache: memcpy(0xac321000, 0xb16f7000, 4096)
08-15 17:20:48.977   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.977   313  6996 V AudioCache: memcpy(0xac322000, 0xb16f7000, 4096)
08-15 17:20:48.978   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.978   313  6996 V AudioCache: memcpy(0xac323000, 0xb16f7000, 4096)
08-15 17:20:48.979   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.979   313  6996 V AudioCache: memcpy(0xac324000, 0xb16f7000, 4096)
08-15 17:20:48.979   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.979   313  6996 V AudioCache: memcpy(0xac325000, 0xb16f7000, 4096)
08-15 17:20:48.980   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.980   313  6996 V AudioCache: memcpy(0xac326000, 0xb16f7000, 4096)
08-15 17:20:48.980   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.980   313  6996 V AudioCache: memcpy(0xac327000, 0xb16f7000, 4096)
08-15 17:20:48.981   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.981   313  6996 V AudioCache: memcpy(0xac328000, 0xb16f7000, 4096)
08-15 17:20:48.981   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.981   313  6996 V AudioCache: memcpy(0xac329000, 0xb16f7000, 4096)
08-15 17:20:48.982   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.982   313  6996 V AudioCache: memcpy(0xac32a000, 0xb16f7000, 4096)
08-15 17:20:48.982   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.982   313  6996 V AudioCache: memcpy(0xac32b000, 0xb16f7000, 4096)
08-15 17:20:48.983   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.983   313  6996 V AudioCache: memcpy(0xac32c000, 0xb16f7000, 4096)
08-15 17:20:48.984   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.984   313  6996 V AudioCache: memcpy(0xac32d000, 0xb16f7000, 4096)
08-15 17:20:48.984   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.984   313  6996 V AudioCache: memcpy(0xac32e000, 0xb16f7000, 4096)
08-15 17:20:48.985   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.985   313  6996 V AudioCache: memcpy(0xac32f000, 0xb16f7000, 4096)
08-15 17:20:48.985   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.985   313  6996 V AudioCache: memcpy(0xac330000, 0xb16f7000, 4096)
08-15 17:20:48.986   313  6996 V AudioCache: write(0xb16f7000, 4096)
08-15 17:20:48.986   313  6996 V AudioCache: memcpy(0xac331000, 0xb16f7000, 4096)
08-15 17:20:48.986   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-15 17:20:48.986   313  6996 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-15 17:20:48.986   313  6996 V AwesomePlayer: postAudioEOS() 
08-15 17:20:48.986   313  6996 V AudioCache: write(0xb16f7000, 280)
08-15 17:20:48.986   313  6996 V AudioCache: memcpy(0xac332000, 0xb16f7000, 280)
08-15 17:20:48.996   313  6993 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-15 17:20:48.996   313  6993 V AwesomePlayer: onStreamDone
08-15 17:20:48.996   313  6993 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-15 17:20:48.996   313  6993 V AudioCache: notify(0xb5474a40, 2, 0, 0)
08-15 17:20:48.996   313  6993 V AudioCache: playback complete
08-15 17:20:48.996   313  6993 V AwesomePlayer: pause_l() 
08-15 17:20:48.996   313  6993 V AudioCache: notify(0xb5474a40, 7, 0, 0)
08-15 17:20:48.996   313  6993 V AudioCache: ignored
,08-15 17:20:48.996   313  6993 V AwesomePlayer: cancelPlayerEvents
08-15 17:20:48.996   313  2147 V AudioCache: wait - success
08-15 17:20:48.996   313  2147 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-15 17:20:48.996   313  6993 D AudioPlayer: Pause Playback at 1068125
08-15 17:20:48.997   313  2147 V AwesomePlayer: reset_l() 
08-15 17:20:48.997   313  2147 V AudioCache: notify(0xb5474a40, 8, 0, 0)
08-15 17:20:48.997   313  2147 V AudioCache: ignored
08-15 17:20:48.997   313  2147 V AwesomePlayer: cancelPlayerEvents
08-15 17:20:48.997   313  2147 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-15 17:20:48.997   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-15 17:20:48.997   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-15 17:20:48.997   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-15 17:20:48.997   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-15 17:20:48.997   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-15 17:20:48.997   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-15 17:20:48.997   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-15 17:20:48.998   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-15 17:20:48.998   313  6995 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-15 17:20:48.998   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-15 17:20:48.998   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-15 17:20:48.998   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-15 17:20:48.998   313  2147 V OMXCodec: [OMX.google.vorbis.decoder] setState mStat,e=1 , newState=0
08-15 17:20:48.998   313  2147 D AudioPlayer: AudioPlayer releasing audio source
08-15 17:20:48.998   313  2147 D AudioPlayer: AudioPlayer done releasing audio source
08-15 17:20:48.999   313  2147 V AwesomePlayer: reset_l() 
08-15 17:20:48.999   313  2147 V AwesomePlayer: cancelPlayerEvents
08-15 17:20:48.999   313  2147 V AwesomePlayer: ~AwesomePlayer call
08-15 17:20:48.999   313  2147 V AwesomePlayer: reset_l() 
08-15 17:20:48.999   313  2147 V AwesomePlayer: cancelPlayerEvents
08-15 17:20:48.999  6892  6991 V SoundPool: close(31)
08-15 17:20:48.999  6892  6991 V SoundPool: pointer = 0x9fe89000, size = 205080, sampleRate = 48000, numChannels = 2
08-15 17:20:49.025  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:49.025  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-15 17:20:49.027  6957  6957 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-15 17:20:49.027  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting,
08-15 17:20:49.028  6957  6957 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 17:20:49.028  6957  6957 V BluetoothSapReceiver: SapReceiver onReceive 
,08-15 17:20:49.029  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7777
08-15 17:20:49.029  6957  6957 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-15 17:20:49.029  6957  6957 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-15 17:20:49.035  6909  6909 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-15 17:20:49.232  6640  6640 I UEI.SmartControl: Supports setup maps: true
,08-15 17:20:49.235  6640  6640 D UEI.SmartControl: QS start statue = true Error code = 0
08-15 17:20:49.235  6640  6640 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-15 17:20:49.235  6640  6640 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-15 17:20:49.235  6640  6640 I UEI.SmartControl: ### init IR Blaster...
08-15 17:20:49.239  6640  6640 D serial_port: Configuring serial port
,08-15 17:20:49.239  6640  6640 E UEI.SmartControl: UEIBLaster setting for 616,
,08-15 17:20:49.239  6640  6640 I UEI.SmartControl: Setting serial record hearder size = 2
,08-15 17:20:49.239  6640  6640 I UEI.SmartControl: configuring settings for MAXQ616
,08-15 17:20:49.239  6640  6640 I UEI.SmartControl: Get version...
,08-15 17:20:49.258  6640  6999 D UEI.SmartControl: serial port data available: 21
,08-15 17:20:49.285  6640  6640 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-15 17:20:49.285  6640  6640 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-15 17:20:49.285  6640  6640 I UEI.SmartControl: QS saving settings...
08-15 17:20:49.289  6640  6640 D UEI.SmartControl: IR Blaster version: 25672567
,08-15 17:20:49.306  6640  6999 D UEI.SmartControl: serial port data available: 4
,08-15 17:20:49.338  6640  7005 I UEI.SmartControl: Device manager: loading config....
,08-15 17:20:49.346  6640  6640 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-15 17:20:49.347  6640  7005 D UEI.SmartControl: ----------- loading internal config...
08-15 17:20:49.353  6640  6640 E UEI.SmartControl: Services init done
08-15 17:20:49.353  6640  6640 D UEI.SmartControl: QS Service init finished
08-15 17:20:49.354  6640  6640 D UEI.SmartControl: QS Service version name: 2.1.91
08-15 17:20:49.354  6640  6640 D UEI.SmartControl: QS Service version code: 201091
08-15 17:20:49.354  6640  6640 D UEI.SmartControl: Service requested: Control
08-15 17:20:49.357  6640  7005 E UEI.SmartControl: Loading SETTINGS...
08-15 17:20:49.359  6640  6640 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-15 17:20:49.362  6640  7005 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-15 17:20:49.362  6640  6640 D UEI.SmartControl: Internal service binding...
08-15 17:20:49.362  6892  6892 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-15 17:20:49.363  6640  6655 I UEI.SmartControl: ------ IControl API: 11
08-15 17:20:49.363  6640  6655 D UEI.SmartControl: File observer start...
,08-15 17:20:49.364  6640  6655 E UEI.SmartControl: IR Port is disabled: false
08-15 17:20:49.364  6640  6655 D UEI.SmartControl: Starting file observer...
08-15 17:20:49.365  6640  6655 I UEI.SmartControl: Registering callback...
08-15 17:20:49.365  6640  6656 I UEI.SmartControl: ------ IControl API: 19
08-15 17:20:49.366  6640  6656 I UEI.SmartControl: Registering Services Ready callback...
08-15 17:20:49.376  6640  7004 I UEI.SmartControl: Notify AllClients services are ready: 0
08-15 17:20:49.376  6640  7004 D UEI.SmartControl: -----service ready thread exits
08-15 17:20:49.377  6892  6908 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-15 17:20:49.377  6892  6989 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-15 17:20:49.377  6892  6989 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-15 17:20:49.378  6892  6892 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-15 17:20:49.379  6892  6892 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-15 17:20:49.379  6640  6655 I UEI.SmartControl: ------ IControl API: 8
08-15 17:20:49.381  6892  6892 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-15 17:20:49.381  6892  6892 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-15 17:20:49.381  6892  6892 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-15 17:20:49.382  6892  6892 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-15 17:20:49.383  6892  6892 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-15 17:20:49.383  6892  6892 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-15 17:20:49.386  6892  6892 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-15 17:20:49.388  6892  6892 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-15 17:20:49.388  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-15 17:20:49.389  6892  6892 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-15 17:20:49.389  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-15 17:20:49.391  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-15 17:20:49.392  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-15 17:20:49.392  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-15 17:20:49.393  6892  6892 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471274449393]
08-15 17:20:49.394  6892  6892 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-15 17:20:49.397  1036  1052 I ActivityManager: Killing 6507:com.lge.email/u0a23 (adj 15): empty #17
08-15 17:20:49.419  6892  7010 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-15 17:20:49.506  1036  1052 I ActivityManager: Killing 6000:com.android.contacts/u0a19 (adj 15): empty #18
,08-15 17:20:49.591  1036  1902 W libprocessgroup: failed to open /acct/uid_10023/pid_6507/cgroup.procs: No such file or directory
,08-15 17:20:49.606  1036  2025 W libprocessgroup: failed to open /acct/uid_10019/pid_6000/cgroup.procs: No such file or directory
08-15 17:20:49.618  6892  6892 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-15 17:20:49.621  6892  6892 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-15 17:20:49.622  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-15 17:20:49.622  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-15 17:20:49.622  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-15 17:20:49.623  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-15 17:20:49.623  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-15 17:20:49.634  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-15 17:20:50.223  1036  2032 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 17:20:50.224  1036  2032 D WifiService: setWifiEnabled: true pid=6708, uid=10118
08-15 17:20:50.225  1036  2032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 17:20:50.260  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 17:20:50.260  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 17:20:50.260  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 17:20:50.262  1036  1440 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-15 17:20:50.262  1036  1440 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-15 17:20:50.266  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-15 17:20:50.266  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-15 17:20:50.266  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-15 17:20:50.266  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-15 17:20:50.266  1036  1440 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-15 17:20:50.266  1036  1440 E WifiHW  : unknown target_country: EU , set to default
08-15 17:20:50.267  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-15 17:20:50.267  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-15 17:20:50.267  1036  1440 I WifiUtil: gEnableBmps=1
08-15 17:20:50.327  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 17:20:50.345  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-15 17:20:50.362  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 17:20:50.368  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:50.370  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:50.372  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-15 17:20:50.387  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 17:20:50.391  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:50.392  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:50.394  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-15 17:20:50.407  5274  5274 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-15 17:20:50.414  5274  5274 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-15 17:20:50.415  6423  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-15 17:20:50.442  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-15 17:20:50.480  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-15 17:20:50.522  1036  1976 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7015 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-15 17:20:50.528  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:50.528  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-15 17:20:50.611  7015  7015 I AppUp4:AppBoxCP: onCreate
,08-15 17:20:50.612  7015  7015 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-15 17:20:50.622  7015  7015 I AppUp4:DB:  setFingerPrint start
08-15 17:20:50.622  7015  7015 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-15 17:20:50.631  7015  7015 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-15 17:20:50.631  7015  7015 I AppUp4:DB:  SDK version = 21
08-15 17:20:50.631  7015  7015 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-15 17:20:50.632  7015  7015 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-15 17:20:50.634  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 17:20:50.634  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:50.637  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 17:20:50.637  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-15 17:20:50.645  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
,08-15 17:20:50.689  7015  7015 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 17:20:50.690  7015  7015 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:20:50.698  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c24f5d5
08-15 17:20:50.698  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 17:20:50.698  7015  7015 D AppUp4:CustFacade: isPhone : true
08-15 17:20:50.699  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
08-15 17:20:50.700  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-15 17:20:50.700  7015  7015 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-15 17:20:50.701  7015  7049 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-15 17:20:50.701  7015  7049 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-15 17:20:50.701  7015  7049 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-15 17:20:50.705  1036  2032 I ActivityManager: Killing 6026:com.android.gallery3d/u0a27 (adj 15): empty #17
08-15 17:20:50.770  1036  1876 W libprocessgroup: failed to open /acct/uid_10027/pid_6026/cgroup.procs: No such file or directory
08-15 17:20:50.772  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:50.773  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-15 17:20:50.780  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:50.785  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:50.796  4291  7058 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-15 17:20:50.805  4291  7059 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:50.805  4291  7059 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 17:20:50.851  1036  1898 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7060 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-15 17:20:50.943  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-15 17:20:50.943  1036  1118 D Tethering: InitialState.processMessage what=4
,08-15 17:20:50.946  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-15 17:20:50.950   308   894 D SoftapController: Softap fwReload - Ok
08-15 17:20:50.951  1036  1440 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (678ms)
08-15 17:20:50.953   308   894 D CommandListener: Setting iface cfg
08-15 17:20:50.954   308   894 D CommandListener: Trying to bring down wlan0
08-15 17:20:50.955   308   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 17:20:50.958  1036  1440 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-15 17:20:50.959  7060  7060 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 17:20:50.959  7060  7060 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 17:20:50.961  7060  7060 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-15 17:20:50.961  7060  7060 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-15 17:20:50.948  7078  7078 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:50.958  7078  7078 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:50.988  7078  7078 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-15 17:20:51.012  7078  7078 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-15 17:20:51.012  7078  7078 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-15 17:20:51.040  7060  7060 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-15 17:20:51.054  7060  7060 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-15 17:20:51.060  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 17:20:51.060  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-15 17:20:51.060  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-15 17:20:51.062  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-15 17:20:51.062  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-15 17:20:51.062  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:51.062  1036  1440 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-15 17:20:51.062  1036  1440 D WifiMonitor: connecting to supplicant
08-15 17:20:51.064  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:51.064  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:51.107  7078  7078 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-15 17:20:51.112  7060  7060 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 17:20:51.150  7060  7060 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:20:51.150  7060  7060 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:20:51.173  7078  7078 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-15 17:20:51.182  7078  7078 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-15 17:20:51.183  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-15 17:20:51.184  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-15 17:20:51.184  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-15 17:20:51.185  1036  1440 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-15 17:20:51.185  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:51.186  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:51.186  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-15 17:20:51.186  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-15 17:20:51.186  1036  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-15 17:20:51.186  1036  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-15 17:20:51.187  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:51.187  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:51.188  1036  1440 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-15 17:20:51.188  1036  1440 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-15 17:20:51.189  1036  1440 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-15 17:20:51.189  1036  1440 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-15 17:20:51.189  1036  1440 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-15 17:20:51.190  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.190  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.190  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.190  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.191  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 17:20:51.191  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 17:20:51.191  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-15 17:20:51.191  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 17:20:51.194  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-15 17:20:51.194  1036  1470 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-15 17:20:51.194  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-15 17:20:51.195  1036  1440 D WifiNative-wlan0: doBoolean: SET update_config 1
08-15 17:20:51.195  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:51.195  1036  1440 D WifiNative-wlan0: SET update_config 1: returned true
08-15 17:20:51.195  1036  1440 D WifiConfigStore: Loading config and enabling all networks 
08-15 17:20:51.195  1036  1440 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-15 17:20:51.196  1036  1440 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-15 17:20:51.200  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:51.200  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:51.200  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:51.200  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:51.200  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:51.200  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:51.200  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:51.200  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:51.200  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:51.200  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:51.200  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:20:51.201  1036  1440 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-15 17:20:51.203  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:51.203  6708  6708 V io.jx,core.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:51.203  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:51.203  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:51.203  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:20:51.203  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:51.203  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:51.203  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:51.203  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:51.203  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:51.203  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-15 17:20:51.209  1036  1440 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-15 17:20:51.209  1036  1440 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-15 17:20:51.210  1036  1440 D WifiStateMachine: enableVerboseLogging : level 2
08-15 17:20:51.210  1036  1440 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-15 17:20:51.211  1036  1440 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-15 17:20:51.211  1036  1440 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-15 17:20:51.211  1036  1440 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-15 17:20:51.211  1036  1440 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-15 17:20:51.212  1036  1440 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-15 17:20:51.212  1036  1440 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-15 17:20:51.212  1036  1440 D WifiNative-wlan0: SET model_number LG-D855: returned true
,08-15 17:20:51.212  1036  1440 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-15 17:20:51.212  1036  1440 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-15 17:20:51.213  1036  1440 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-15 17:20:51.213  1036  1440 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-15 17:20:51.213  1036  1440 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-15 17:20:51.213  1036  1440 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-15 17:20:51.214  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-15 17:20:51.214  1036  1440 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-15 17:20:51.214  1036  1440 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-15 17:20:51.214  1036  1440 D WifiNative-HAL: Setting external_sim to 1
08-15 17:20:51.214  1036  1440 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-15 17:20:51.215  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-15 17:20:51.215  1941  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-15 17:20:51.215  1941  2295 D WfdsService: Set the WFDS Monitor: true
08-15 17:20:51.215  1941  2295 D WfdsMonitor: WfdsMonitorThread create
08-15 17:20:51.215  1036  1440 D WifiNative-wlan0: SET external_sim 1: returned true
08-15 17:20:51.215  1036  1440 I WifiNative-HAL: startHal
08-15 17:20:51.215  1036  1440 D wifi    : setting scan oui 0x952792c0
08-15 17:20:51.215  1941  2295 D WfdsMonitor: WFDS Monitor is created and started
08-15 17:20:51.215  1941  2295 D WfdsService: WiFi: Supplicant connection re-established
08-15 17:20:51.216  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-15 17:20:51.216  1036  1440 I WifiNative-HAL: startHal
08-15 17:20:51.216  1036  1440 D wifi    : setting scan oui 0x952792c0
08-15 17:20:51.216  1036  1440 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-15 17:20:51.217  1036  1440 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-15 17:20:51.217  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-15 17:20:51.217  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-15 17:20:51.218  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-15 17:20:51.218  1941  7084 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-15 17:20:51.218  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-15 17:20:51.218  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-15 17:20:51.218  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-15 17:20:51.218  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-15 17:20:51.218  1941  7084 E CtrlSupplicant: Succeed to open control connection
08-15 17:20:51.218  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-15 17:20:51.219  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-15 17:20:51.219  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-15 17:20:51.219  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-15 17:20:51.219  1941  7084 E CtrlSupplicant: Succeed to open monitor connection
08-15 17:20:51.219  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-15 17:20:51.219  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-15 17:20:51.219  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-15 17:20:51.220  1941  7084 D WfdsMonitor: Supplicant connection established
08-15 17:20:51.220  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-15 17:20:51.220  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-15 17:20:51.221  7078  7078 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-15 17:20:51.221  1941  2295 D WfdsService: Connected to the supplicant for w,fds
08-15 17:20:51.221  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-15 17:20:51.222  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-15 17:20:51.222  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-15 17:20:51.222  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-15 17:20:51.224  1036  1440 E WifiNative: : [338,153,995 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
,08-15 17:20:51.224  1036  1440 D WifiNative-wlan0: doBoolean: RECONNECT
08-15 17:20:51.225  1036  1440 D WifiNative-wlan0: RECONNECT: returned true
08-15 17:20:51.225  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-15 17:20:51.226  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-15 17:20:51.226  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-15 17:20:51.227  1036  1440 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-15 17:20:51.227  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
,08-15 17:20:51.227  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-15 17:20:51.227  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.228  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-15 17:20:51.228  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.228  1036  1557 I WifiNative-HAL: startHal
08-15 17:20:51.228  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0x952792c0
08-15 17:20:51.228  1036  1557 D wifi    : failed to get capabilities : -3
08-15 17:20:51.228  1036  1557 E WifiScanningService: could not get scan capabilities
08-15 17:20:51.228  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-15 17:20:51.229  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.229   308   894 D CommandListener: Setting iface cfg
08-15 17:20:51.229   308   894 D CommandListener: Trying to bring up p2p0
08-15 17:20:51.229  1036  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-15 17:20:51.230  1036  1391 D LGWifiP2pService: P2pEnablingState
08-15 17:20:51.230  1036  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.230  1036  1391 D LGWifiP2pService: P2p socket connection successful
08-15 17:20:51.230  1036  1391 D LGWifiP2pService: P2pEnabledState
08-15 17:20:51.230  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-15 17:20:51.230  1036  1391 D LGWifiP2pService: sending p2p connection changed broadcast
08-15 17:20:51.230  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-15 17:20:51.231  1941  1941 D WfdsService: WifiP2pState is changed : true
08-15 17:20:51.231  1036  1440 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-15 17:20:51.231  1941  2295 D WfdsService: Receive the WFDS_ENABLE Method
08-15 17:20:51.231  1941  2295 D WfdsService: Set the WFDS Monitor: true
08-15 17:20:51.231  1941  2295 D WfdsService: Connected to the supplicant for wfds
08-15 17:20:51.231  1941  2295 D WfdsJNI : doCommand: WFDS_SET TRUE
08-15 17:20:51.231  1036  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-15 17:20:51.231  7078  7078 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-15 17:20:51.231  1036  1440 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-15 17:20:51.231  1941  2295 D WfdsService: selectPreferredScanChannel [36]
08-15 17:20:51.231  1941  2295 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-15 17:20:51.232  1036  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-15 17:20:51.232  1036  1440 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-15 17:20:51.232  1036  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
08-15 17:20:51.232  1036  1440 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-15 17:20:51.232  1036  1391 D WifiNative-p2p0: SET device_name G3: returned true
08-15 17:20:51.232  1036  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-15 17:20:51.232  1036  1391 D LGWifiP2pService: before postfix = G3
08-15 17:20:51.232  1036  1391 D WifiServerServiceExt: postfix byte check : 2
08-15 17:20:51.232  1036  1391 D LGWifiP2pService: after postfix = G3
08-15 17:20:51.232  1036  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-15 17:20:51.232  1036  1440 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-15 17:20:51.232  1036  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-15 17:20:51.233  1036  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-15 17:20:51.233  1036  1440 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-15 17:20:51.233  1036  1391 D WifiNative-p2p0: SET device_type 10-0050,F204-5: returned true
08-15 17:20:51.233  1036  1440 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-15 17:20:51.233  1036  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-15 17:20:51.233  7078  7078 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-15 17:20:51.233  1036  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-15 17:20:51.233  1036  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-15 17:20:51.233  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-15 17:20:51.233  1036  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-15 17:20:51.233  1036  1391 D WifiNative-HAL: p2pGetDeviceAddress
08-15 17:20:51.234  1036  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-15 17:20:51.234  1941  1941 D WfdsService: isConnected: false
08-15 17:20:51.234  1036  1391 D LGWifiP2pService: DeviceAddress: 
08-15 17:20:51.234  1036  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-15 17:20:51.234  1036  1391 D WifiNative-p2p0: P2P_FLUSH: returned false
08-15 17:20:51.234  1036  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-15 17:20:51.234  1036  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-15 17:20:51.235  1036  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-15 17:20:51.235  1036  1440 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-15 17:20:51.235  1036  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-15 17:20:51.235  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-15 17:20:51.235  1036  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-15 17:20:51.235  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-15 17:20:51.235  1941  1941 D WfdsService: Update P2p Interface State: 3
08-15 17:20:51.235  1036  1440 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-15 17:20:51.235  1036  1440 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-15 17:20:51.236  1036  1440 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-15 17:20:51.244  7078  7078 E wpa_supplicant: disconnect_rssi_lvl: -100
08-15 17:20:51.244  1036  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-15 17:20:51.244  1036  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-15 17:20:51.244  1036  1391 D LGWifiP2pService: InactiveState
08-15 17:20:51.245  1036  1391 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.245  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.245  1036  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-15 17:20:51.245  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-15 17:20:51.245  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-15 17:20:51.246  7078  7078 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:20:51.246  1036  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 17:20:51.246  1036  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:20:51.246  1036  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-15 17:20:51.246  1036  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:20:51.246  7078  7078 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-15 17:20:51.246  1941  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 17:20:51.247  7078  7078 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.247  1036  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-15 17:20:51.247  1941  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1036  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:20:51.247  1036  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.247  1036  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.247  1036  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  7078  7078 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1941  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:20:51.247  1036  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1036  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.247  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.247  1036  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.248  1036  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.248  1036  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.248  1036  1036 E WifiServerServiceExt: No p2p device connected
08-15 17:20:51.248  1941  2295 W WfdsService: DefaultState - msg [9441285] is not handled
08-15 17:20:51.248  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-15 17:20:51.249  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-15 17:20:51.249  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-15 1,7:20:51.249  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-15 17:20:51.250  7078  7078 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:20:51.250  7078  7078 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-15 17:20:51.250  7078  7078 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.251  7078  7078 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.251  1036  1440 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-15 17:20:51.251  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-15 17:20:51.252  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 17:20:51.252  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:20:51.252  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-15 17:20:51.252  1941  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:20:51.252  1036  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:20:51.252  1036  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:20:51.252  1941  7084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:20:51.252  1036  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:20:51.252  1036  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.252  1036  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.252  1036  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.252  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-15 17:20:51.252  1036  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:20:51.252  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-15 17:20:51.252  1036  7081 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.252  1036  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.252  1036  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:20:51.252  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-15 17:20:51.252  7078  7078 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 17:20:51.252  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-15 17:20:51.253  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 17:20:51.253  1036  7081 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-15 17:20:51.253  1036  7081 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 17:20:51.253  1036  1440 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-15 17:20:51.253  1036  1440 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-15 17:20:51.254  1036  1440 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-15 17:20:51.254  1036  1440 D WifiNative-wlan0: doBoolean: SCAN
08-15 17:20:51.254  1036  1440 D WifiNative-wlan0: SCAN: returned false
,08-15 17:20:51.254  1036  1391 D LGWifiP2pService: InactiveState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.254  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:51.254  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=338185  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-15 17:20:51.255  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=338186  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-15 17:20:51.256  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:51.256  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:51.256  1036  1440 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:20:51.256  1036  1440 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:20:51.257  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.257  1036  1440 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:20:51.257  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.257  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-15 17:20:51.257  1036  1440 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:20:51.258  1036  1440 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:20:51.258  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:51.258  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:20:51.259  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-15 17:20:51.275  7060  7060 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-15 17:20:51.299  7060  7060 I HubEmail: JNI_OnLoad()
08-15 17:20:51.299  7060  7060 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-15 17:20:51.299  7060  7060 I HubEmail: registerNatives()
,08-15 17:20:51.299  7060  7060 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-15 17:20:51.299  7060  7060 I HubEmail: registerNativeMethods()
08-15 17:20:51.299  7060  7060 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-15 17:20:51.299  7060  7060 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-15 17:20:51.301  3396  3396 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-15 17:20:51.301  3396  3396 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:51.301  3396  3396 I LgeMiscReceiver: networkInfo.isConnected() = false
08-15 17:20:51.304  6938  7087 W FormManager: Network not available. Please check & try again.
08-15 17:20:51.371  1036  1576 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7090 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-15 17:20:51.385  6938  7088 V FormManager: Network unavailable.
08-15 17:20:51.388  7060  7089 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-15 17:20:51.393  6938  7088 V FormManager: Network unavailable.
08-15 17:20:51.403  1036  1576 I ActivityManager: Killing 6087:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-15 17:20:51.465  1036  1051 W libprocessgroup: failed to open /acct/uid_10080/pid_6087/cgroup.procs: No such file or directory
08-15 17:20:51.553  7090  7090 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:20:51.554  7090  7090 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 17:20:51.557  7090  7090 D PhoneMonitor: Register our PhoneStateListener
,08-15 17:20:51.584  7090  7090 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-15 17:20:51.588  7090  7090 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-15 17:20:51.624  7090  7090 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-15 17:20:51.626  7090  7090 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-15 17:20:51.627  7090  7090 D TelephonyAutoProfiling: [parse] Load xml
08-15 17:20:51.634  7090  7090 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-15 17:20:51.634  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-15 17:20:51.634  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-15 17:20:51.634  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-15 17:20:51.634  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-15 17:20:51.634  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-15 17:20:51.634  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-15 17:20:51.635  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-15 17:20:51.635  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-15 17:20:51.635  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-15 17:20:51.635  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-15 17:20:51.635  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-15 17:20:51.635  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-15 17:20:51.635  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-15 17:20:51.635  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-15 17:20:51.635  7090  7090 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-15 17:20:51.635  7090  7090 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-15 17:20:51.647  7090  7090 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-15 17:20:51.660  1036  2012 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7109 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-15 17:20:51.661  1036  2012 I ActivityManager: Killing 6542:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-15 17:20:51.718  1036  1898 W libprocessgroup: failed to open /acct/uid_10061/pid_6542/cgroup.procs: No such file or directory
,08-15 17:20:51.793  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-15 17:20:51.793  1036  7081 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-15 17:20:51.793  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-15 17:20:51.793  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-15 17:20:51.793  1036  7081 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-15 17:20:51.793  7078  7078 E wpa_supplicant: USIM:  scard_init function
08-15 17:20:51.794  1036  1440 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-15 17:20:51.794  1036  1440 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-15 17:20:51.794  7078  7078 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-15 17:20:51.795  1036  1440 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-15 17:20:51.795  1036  1440 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-15 17:20:51.795  1036  1440 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-15 17:20:51.796  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-15 17:20:51.796  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-15 17:20:51.812  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=338743  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-15 17:20:51.819  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.819  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.819  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-15 17:20:51.819  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:51.819  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:51.821  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:51.824  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.824  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:51.824  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-15 17:20:51.825  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=338756  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-15 17:20:51.826  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:20:51.826  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-15 17:20:51.845  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-15 17:20:51.845  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-15 17:20:51.846  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:51.911  7078  7078 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-15 17:20:51.914  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-15 17:20:51.914  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-15 17:20:51.914  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-15 17:20:51.915  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-15 17:20:51.915  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:20:51.915  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:20:51.917  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=338848  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-15 17:20:51.918  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=338849  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-15 17:20:51.919  1036  1440 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338850
08-15 17:20:51.919  1036  1440 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338850
08-15 17:20:51.920  1036  1440 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338851
08-15 17:20:51.920  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338851
08-15 17:20:51.920  1036  1440 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338851
08-15 17:20:51.921  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=338852  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-15 17:20:51.928  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:20:51.928  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:20:51.928  7078  7078 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 17:20:51.928  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-15 17:20:51.928  7078  7078 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 17:20:51.928  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 17:20:51.928  1036  7081 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-15 17:20:51.929  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-15 17:20:51.934  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 17:20:51.934  1036  7081 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 17:20:51.935  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:20:51.935  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:20:51.960  1036  2032 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7127 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-15 17:20:51.961  1036  2032 I ActivityManager: Killing 6115:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-15 17:20:52.011  1036  1576 W libprocessgroup: failed to open /acct/uid_10097/pid_6115/cgroup.procs: No such file or directory
,08-15 17:20:52.014  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=338943  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-15 17:20:52.016  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:52.016  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:52.018  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.019  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.019  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.019  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-15 17:20:52.024  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-15 17:20:52.024  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.024  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.025  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-15 17:20:52.033  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:20:52.033  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-15 17:20:52.034  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=338964  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-15 17:20:52.036  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=338967  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-15 17:20:52.038  1036  1440 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=338969
08-15 17:20:52.038  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:52.038  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:52.039  1036  1440 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=338970
08-15 17:20:52.039  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 17:20:52.041  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-15 17:20:52.042  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:20:52.042  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:20:52.044  1036  1440 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-15 17:20:52.047  1036  1440 I WifiServiceExtension: setVHTCapabilityType  : false
08-15 17:20:52.053  1036  1440 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-15 17:20:52.053  1036  1440 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-15 17:20:52.056  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.056  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.056  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-15 17:20:52.060  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.060  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.060  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-15 17:20:52.060  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:52.060  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:52.061  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.063  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:52.063  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:52.064  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.065  1036  1440 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-15 17:20:52.065  1036  1519 D ConnectivityService: Got NetworkAgent Messenger
08-15 17:20:52.065  1036  1519 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-15 17:20:52.065  1036  1519 D ConnectivityService: NetworkAgent connected
08-15 17:20:52.065  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 17:20:52.065  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 17:20:52.066  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 17:20:52.067  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-15 17:20:52.071  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-15 17:20:52.072  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 17:20:52.072  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-15 17:20:52.072  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 17:20:52.072  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 17:20:52.077  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-15 17:20:52.078   308   894 D CommandListener: Setting iface cfg
,08-15 17:20:52.099  1036  1051 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7146 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-15 17:20:52.100  1036  1051 I ActivityManager: Killing 6590:com.lge.eula/1000 (adj 15): empty #17
,08-15 17:20:52.288  1036  1905 W libprocessgroup: failed to open /acct/uid_1000/pid_6590/cgroup.procs: No such file or directory
,08-15 17:20:52.299  1036  1440 E WifiStateMachine: Start Dhcp Watchdog 2
08-15 17:20:52.299  1036  7145 D DhcpStateMachine: StoppedState
08-15 17:20:52.299  1036  7145 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:52.299  1036  7145 D DhcpStateMachine: WaitBeforeStartState
08-15 17:20:52.301  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=339232  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:20:52.304  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=339234  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:20:52.305  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=339236  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:20:52.308  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:20:52.308  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,08-15 17:20:52.308  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-15 17:20:52.309  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:52.310  1036  1440 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-15 17:20:52.312  1036  1440 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:52.313  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:52.314  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:52.316  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=339247  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:20:52.316  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:20:52.316  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-15 17:20:52.319  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=339249  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:20:52.320  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=339251  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:20:52.320  1036  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:52.320  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:52.320  1036  1391 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 17:20:52.323  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:293209] from screen [on:0 period:-1899330205] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-15 17:20:52.329  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1899330202] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-15 17:20:52.329  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-15 17:20:52.333  1036  1519 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-15 17:20:52.333  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:52.334  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:52.334  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:52.335  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:52.335  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:52.335  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:52.336  1036  1519 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-15 17:20:52.337  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=141,0,0
08-15 17:20:52.337  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.337  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=141,0,0
08-15 17:20:52.338  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-15 17:20:52.338  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-15 17:20:52.338  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-15 17:20:52.338  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 0
08-15 17:20:52.339  1036  1440 D WifiNative-wlan0: SET ps 0: returned true
08-15 17:20:52.339  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-15 17:20:52.339  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-15 17:20:52.339  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-15 17:20:52.339  1036  1440 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-15 17:20:52.340  1036  1440 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-15 17:20:52.340  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b9b5189 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:52.340  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b9b5189 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:52.340  1036  1440 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-15 17:20:52.340  1036  7145 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:52.340  1036  7145 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-15 17:20:52.341   308   894 D CommandListener: Setting iface cfg
08-15 17:20:52.341   308   894 D CommandListener: Trying to bring up wlan0
08-15 17:20:52.342  1036  1440 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-15 17:20:52.343  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:20:52.343  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-15 17:20:52.344  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:20:52.344  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-15 17:20:52.347  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 17:20:52.348  7146  7146 I art     : Almond Protected OAT
08-15 17:20:52.348  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 17:20:52.349  1036  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-15 17:20:52.351  1036  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 17:20:52.353  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 17:20:52.354  1036  1440 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-15 17:20:52.356  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-15 17:20:52.360  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-15 17:20:52.360  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 17:20:52.360  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 17:20:52.360  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 17:20:52.360  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-15 17:20:52.361  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-15 17:20:52.361  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 17:20:52.361  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:52.361  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-15 17:20:52.361  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 17:20:52.377  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-15 17:20:52.378  1036  1519 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-15 17:20:52.378  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:52.379  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:52.379  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:52.380  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:52.381  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:52.381  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:52.382  1036  1519 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-15 17:20:52.382  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-15 17:20:52.382  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-15 17:20:52.382  1036  1440 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-15 17:20:52.386  1036  1519 D ConnectivityService: ignoring duplicate network state non-change
08-15 17:20:52.389  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:52.389  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:52.390  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.391  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.391  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.391  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-15 17:20:52.392  1036  1519 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-15 17:20:52.393  1036  1519 D ConnectivityService: Adding iface wlan0 to network 101
08-15 17:20:52.397  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.397  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.397  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-15 17:20:52.399  1036  1440 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-15 17:20:52.399  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-15 17:20:52.400  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-15 17:20:52.405  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.405  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.405  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-15 17:20:52.411  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:52.411  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:20:52.411  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-15 17:20:52.418  1036  1519 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-15 17:20:52.418  1036  1519 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-15 17:20:52.418  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 17:20:52.420  1036  1519 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-15 17:20:52.420   308   894 E Netd    : netlink response contains error (File exists)
08-15 17:20:52.421  1036  1519 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-15 17:20:52.422  1036  1519 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-15 17:20:52.422  1036  1519 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-15 17:20:52.422  1036  1519 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-15 17:20:52.424  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.424  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:52.424  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-15 17:20:52.425  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:52.425  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-15 17:20:52.426  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.426  1036  1519 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-15 17:20:52.426  1036  1519 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-15 17:20:52.426  1036  1519 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-15 17:20:52.426  1036  1519 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-15 17:20:52.426  1036  1519 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:20:52.426  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:52.426  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-15 17:20:52.426  1036  1519 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:52.426  1036  1519 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-15 17:20:52.426  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:52.426  1036  1519 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:52.427  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-15 17:20:52.427  1036  1519 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-15 17:20:52.427  1036  1519 D ConnectivityService: currentScore = 0, newScore = 20
08-15 17:20:52.427  1036  1519 D ConnectivityService:    accepting network in place of null
08-15 17:20:52.427  1036  1519 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:52.428  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:52.429  1036  1,519 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-15 17:20:52.429  1036  1519 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-15 17:20:52.429  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 17:20:52.429  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 17:20:52.429  1036  1440 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:52.429  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:20:52.430   308  7169 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-15 17:20:52.431  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:52.431  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-15 17:20:52.431  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 17:20:52.440  1036  1519 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:52.440  1036  1519 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-15 17:20:52.441  1036  1519 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-15 17:20:52.442  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-15 17:20:52.443  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 17:20:52.443  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 17:20:52.443  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 17:20:52.445  1036  1519 D ConnectivityService: validation of new default Network = false
08-15 17:20:52.445  1036  1519 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-15 17:20:52.445  1036  1519 D DSQN    : enableDataServiceNotify 
08-15 17:20:52.445  1036  1519 D DSQN    : start dsqn bin
,08-15 17:20:52.454  1036  1519 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,08-15 17:20:52.454  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:52.454  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:52.438  7176  7176 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:52.455  1036  1519 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:52.455  7146  7146 D WeatherApplication: removeAccount
08-15 17:20:52.438  7176  7176 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:52.455  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-15 17:20:52.458  7146  7146 D WeatherApplication: Account.length = 0
08-15 17:20:52.459  7146  7146 E WeatherApplication: OPERATOR:OPEN
08-15 17:20:52.471  7176  7176 E DSQN    : DSQN ssw
,08-15 17:20:52.468  7146  7146 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:52
08-15 17:20:52.478  1036  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-15 17:20:52.482  1816  7178 I CheckinService: active receiver: enabled
08-15 17:20:52.489   308  7169 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-15 17:20:52.494  7146  7146 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 17:20:52.494  7146  7146 D Weather.Utils: 2 : All the weather widget is gone.
08-15 17:20:52.495  1816  7178 I CheckinService: Preparing to send checkin request
08-15 17:20:52.495  1816  7178 I EventLogService: Accumulating logs since 1471274172099
08-15 17:20:52.497  7146  7146 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 17:20:52.501  7146  7146 D WeatherAncestor: connectivity changed - connection : true
08-15 17:20:52.502  7146  7146 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-15 17:20:52.504  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 17:20:52.505  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.506  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.511  7146  7146 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 17:20:52.511  7146  7146 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 17:20:52.511  7146  7146 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-15 17:20:52.520   308  7169 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-15 17:20:52.532  1816  7178 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-15 17:20:52.535  7146  7146 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 17:20:52.535  7146  7146 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:52
08-15 17:20:52.543  1036  7145 D DhcpStateMachine: DHCPV4 request on wlan0
,08-15 17:20:52.544  1036  7145 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-15 17:20:52.544  1036  7145 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-15 17:20:52.538  7183  7183 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:52.538  7183  7183 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:52.552   308   893 D LGDataListener: argv[0]=dsqncommand
08-15 17:20:52.552   308   893 D LGDataListener: argv[1]=wlan0
08-15 17:20:52.552   308   893 D LGDataListener: argv[2]=1
08-15 17:20:52.552   308   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-15 17:20:52.553  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-15 17:20:52.553  1036  1116 D DSQN    : start to monitor internet connection
08-15 17:20:52.556  7183  7183 I dhcpcd  : version 5.5.6 starting
08-15 17:20:52.559  7183  7183 E dhcpcd  : get_duid: m
08-15 17:20:52.559  7183  7183 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-15 17:20:52.559  7183  7183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-15 17:20:52.583  1036  1956 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7188 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-15 17:20:52.585  1036  1956 I ActivityManager: Killing 6611:com.lge.bnr/1000 (adj 15): empty #17
08-15 17:20:52.585  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 15 Aug 2016 15:20:52 GMT], X-Android-Received-Millis=[1471274452585], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471274452551]}
08-15 17:20:52.585  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-15 17:20:52.585  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-15 17:20:52.585  1036  1519 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-15 17:20:52.585  1036  1519 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-15 17:20:52.586  1036  1519 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:20:52.586  1036  1519 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:52.586  1036  1519 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-15 17:20:52.586  1036  1519 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-15 17:20:52.586  1036  1519 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-15 17:20:52.586  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:52.586  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:52.587  1036  1519 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:52.587  1036  1519 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:52.587  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-15 17:20:52.587  1036  1440 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:52.587  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:20:52.588  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-15 17:20:52.589  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:52.589  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 17:20:52.629  7183  7183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-15 17:20:52.629  7183  7183 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-15 17:20:52.629  7183  7183 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-15 17:20:52.629  7183  7183 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-15 17:20:52.629  7183  7183 D dhcpcd  : wlan0: sending REQUEST (xid 0x7677dd74), next in 4.53 seconds
,08-15 17:20:52.638  1036  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_6611/cgroup.procs: No such file or directory
,08-15 17:20:52.663  7183  7183 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-15 17:20:52.684  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 17:20:52.686  7183  7183 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-15 17:20:52.686  7183  7183 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-15 17:20:52.687  7183  7183 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-15 17:20:52.687  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.687  7183  7183 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-15 17:20:52.687  7183  7183 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-15 17:20:52.688  7183  7183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-15 17:20:52.688  7183  7183 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-15 17:20:52.688  7183  7183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-15 17:20:52.690  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:52.779   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 17:20:52.779   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-15 17:20:52.779   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
,08-15 17:20:52.781  1036  1876 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7217 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-15 17:20:52.784  7188  7216 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-15 17:20:52.786   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 17:20:52.786   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-15 17:20:52.786   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
08-15 17:20:52.786  7188  7216 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-15 17:20:52.813   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 17:20:52.813   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-15 17:20:52.813   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
08-15 17:20:52.813  7188  7231 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-15 17:20:52.828   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 17:20:52.828   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-15 17:20:52.828   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
,08-15 17:20:52.836  7217  7217 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-15 17:20:52.836  7188  7231 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-15 17:20:52.836  7217  7217 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-15 17:20:52.860  7217  7217 I MultiDex: VM with version 2.1.0 has multidex support
08-15 17:20:52.860  7217  7217 I MultiDex: install
08-15 17:20:52.860  7217  7217 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-15 17:20:52.873  7217  7217 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-15 17:20:52.947  1036  7145 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-15 17:20:52.949  1036  7145 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-15 17:20:52.949  1036  7145 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-15 17:20:52.949  1036  7145 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-15 17:20:52.949  1036  7145 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-15 17:20:52.949  1036  7145 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-15 17:20:52.949  1036  7145 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-15 17:20:52.949  1036  7145 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-15 17:20:52.950  1036  7145 D DhcpStateMachine: RunningState
,08-15 17:20:52.994  7188  7188 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-15 17:20:53.001  7188  7188 I LibraryLoader: Loading: webviewchromium
08-15 17:20:53.004  7188  7188 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9944-9947)
08-15 17:20:53.004  7188  7188 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 17:20:53.009  7188  7188 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1376b954}
,08-15 17:20:53.013  7188  7188 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 17:20:53.014  7188  7188 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-15 17:20:53.048  7188  7188 I BrowserStartupController: Initializing chromium process, renderers=0
08-15 17:20:53.049  7188  7188 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-15 17:20:53.058  7188  7188 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-15 17:20:53.059  7188  7188 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-15 17:20:53.059  7188  7188 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-15 17:20:53.064   313  2148 V AudioPolicyService: registerClient() client 0xb558a900, uid 10093
,08-15 17:20:53.066  7188  7273 W AudioManagerAndroid: Requires BLUETOOTH permission
08-15 17:20:53.076  7188  7188 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 17:20:53.076  7188  7188 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 17:20:53.076  7188  7188 I Adreno-EGL: Build Date: 12/12/14 금
08-15 17:20:53.076  7188  7188 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 17:20:53.076  7188  7188 I Adreno-EGL: Remote Branch: 
08-15 17:20:53.076  7188  7188 I Adreno-EGL: Local Patches: 
08-15 17:20:53.076  7188  7188 I Adreno-EGL: Reconstruct Branch: 
,08-15 17:20:53.158  7281  7281 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-15 17:20:53.175  7188  7188 I NSApplication: Starting up...
,08-15 17:20:53.226  7281  7281 I dex2oat : dex2oat took 67.902ms (threads: 4)
,08-15 17:20:53.233  1036  2025 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7292 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-15 17:20:53.235  1036  2025 I ActivityManager: Killing 6049:com.android.vending/u0a44 (adj 15): empty #17
08-15 17:20:53.243  7217  7236 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 17:20:53.243  7217  7236 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 17:20:53.243  7217  7236 I Adreno-EGL: Build Date: 12/12/14 금
08-15 17:20:53.243  7217  7236 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 17:20:53.243  7217  7236 I Adreno-EGL: Remote Branch: 
08-15 17:20:53.243  7217  7236 I Adreno-EGL: Local Patches: 
08-15 17:20:53.243  7217  7236 I Adreno-EGL: Reconstruct Branch: 
,08-15 17:20:53.249  1036  1440 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:53.249   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 303us total 16.972ms
08-15 17:20:53.249  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:53.250  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:53.250  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:53.251  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:53.251  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:20:53.252  1036  1519 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-15 17:20:53.252  1036  1519 D ConnectivityService: identical MTU - not setting
08-15 17:20:53.252  1036  1519 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-15 17:20:53.252  1036  1519 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-15 17:20:53.252  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:53.252  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:53.253  1036  1519 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:53.253  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-15 17:20:53.263   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 12.697ms
,08-15 17:20:53.276   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 11.719ms
,08-15 17:20:53.357  1036  2032 I art     : Explicit concurrent mark sweep GC freed 105637(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.405ms total 87.024ms
,08-15 17:20:53.360  1036  1603 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 17:20:53.360  1036  1940 W libprocessgroup: failed to open /acct/uid_10044/pid_6049/cgroup.procs: No such file or directory
08-15 17:20:53.360  1036  1603 D WifiService: setWifiEnabled: false pid=6708, uid=10118
08-15 17:20:53.360  1036  1603 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-15 17:20:53.374  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 17:20:53.375  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 17:20:53.375  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 17:20:53.376  1036  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-15 17:20:53.376  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-15 17:20:53.377  1036  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-15 17:20:53.377  1036  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,08-15 17:20:53.377  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-15 17:20:53.377  1036  1440 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-15 17:20:53.377  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 17:20:53.377  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 17:20:53.378  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 17:20:53.378  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 17:20:53.386  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-15 17:20:53.386  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 17:20:53.386  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 17:20:53.386  1036  1391 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.386  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.387  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 17:20:53.387  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 17:20:53.388  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-15 17:20:53.388   308   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 17:20:53.388  1036  7145 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.393  7217  7236 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:20:53.393  7217  7236 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:20:53.414  1036  1519 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-15 17:20:53.414  1036  1519 D ConnectivityService: ignoring duplicate network state non-change
08-15 17:20:53.414  1036  1519 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-15 17:20:53.415  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 17:20:53.417  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-15 17:20:53.419  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:53.419  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:53.419  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 17:20:53.420  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:53.420  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:53.420  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:53.421  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-15 17:20:53.421  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-15 17:20:53.421  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:20:53.421  1036  1440 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-15 17:20:53.421  1036  1391 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.421  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.421  1036  1391 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@62e5a7b
08-15 17:20:53.422  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:53.422  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-15 17:20:53.422  1036  1391 D LGWifiP2pService: P2pDisablingState
08-15 17:20:53.422  1036  1391 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.422  1036  1391 D LGWifiP2pService: p2p socket connection lost
08-15 17:20:53.422  1036  1391 D LGWifiP2pService: P2pDisabledState
08-15 17:20:53.423  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:53.425  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-15 17:20:53.425  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.425  1036  1391 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.425  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 17:20:53.426  7078  7078 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-15 17:20:53.427  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-15 17:20:53.427  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 17:20:53.427  1941  1941 D WfdsService: WifiP2pState is changed : false
08-15 17:20:53.427  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:53.428  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:53.428  1941  2295 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-15 17:20:53.428  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 17:20:53.428  1941  2295 D WfdsService: Set the WFDS Monitor: false
08-15 17:20:53.428  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-15 17:20:53.428  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-15 17:20:53.428  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.428  1036  1558 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.429  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 17:20:53.429  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 17:20:53.429  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-15 17:20:53.430  1941  2295 D WfdsMonitor: WFDS Monitor is stopped
08-15 17:20:53.430  1941  2295 D WfdsService: STATE : WfdsDisabledState - enter
08-15 17:20:53.432  1941  2297 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-15 17:20:53.436  1941  7084 D CtrlSupplicant: Received on exit socket, terminate
08-15 17:20:53.436  1941  7084 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-15 17:20:53.437  1941  7084 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-15 17:20:53.437  1941  7084 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-15 17:20:53.437  1941  2295 W WfdsService: DefaultState - msg [9445378] is not handled
08-15 17:20:53.448  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:53.448  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-15 17:20:53.450  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:53.451  7292  7292 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 17:20:53.453   308   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 17:20:53.454  1036  1519 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-15 17:20:53.454  1036  1519 D DSQN    : disableDataServiceNotify
08-15 17:20:53.454  1036  1519 D DSQN    : stop dsqn bin
08-15 17:20:53.455  1036  1440 D WifiNative-p2p0: doBoolean: TERMINATE
08-15 17:20:53.455  1036  1440 D WifiNative-p2p0: TERMINATE: returned true
08-15 17:20:53.455  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-15 17:20:53.455  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 17:20:53.455  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-15 17:20:53.455  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 17:20:53.456  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:53.456  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:53.456  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 17:20:53.457  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-15 17:20:53.457  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-15 17:20:53.458  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:53.458  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:53.458  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:53.458  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:53.458  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:53.458  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:53.458  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:53.458  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:53.458  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:53.458  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:53.458  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-15 17:20:53.459  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:20:53.459  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-15 17:20:53.460  1036  1519 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-15 17:20:53.460  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:53.460  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:53.461  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:53.461  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:53.461  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:53.461  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:53.461  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:53.461  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:53.461  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:53.461  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:53.461  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:20:53.461  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:53.461  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:20:53.461  1036  1519 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:20:53.461  1036  1519 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-15 17:20:53.461  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-15 17:20:53.461  1036  1519 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-15 17:20:53.461  1036  1519 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-15 17:20:53.461  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.462  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.462  1036  7144 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-15 17:20:53.462  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 17:20:53.462  1036  1519 D ,ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:53.462  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 17:20:53.462  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-15 17:20:53.463  1036  1519 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:53.463  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-15 17:20:53.463  1036  1519 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:53.463  1036  1519 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:53.463  1036  1519 D NetworkManagementService: Removing idletimer
08-15 17:20:53.463  1036  1519 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:53.463  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 17:20:53.463  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 17:20:53.463  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 17:20:53.463  1036  1519 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-15 17:20:53.464  1036  1440 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:53.464  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:20:53.465  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:20:53.465  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 17:20:53.465  1036  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-15 17:20:53.466  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-15 17:20:53.466  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 17:20:53.466  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 17:20:53.466  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 17:20:53.469  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-15 17:20:53.469  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-15 17:20:53.470  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:53.472  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 17:20:53.489  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 17:20:53.491  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:53.492  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 17:20:53.504  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-15 17:20:53.507  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:53.507  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:53.579  7078  7078 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-15 17:20:53.579  7078  7078 I wpa_supplicant: monitor socket send errors count : 1
08-15 17:20:53.579  7078  7078 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-15 17:20:53.581  1036  7081 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-15 17:20:53.581  1036  7081 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-15 17:20:53.593  1036  7145 D DhcpStateMachine: StoppedState
08-15 17:20:53.593  1036  7145 D DhcpStateMachine: StoppedState{ when=-164ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:53.594  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-15 17:20:53.594  1036  1440 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-15 17:20:53.603  7078  7078 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 17:20:53.603  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-15 17:20:53.603  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-15 17:20:53.604  7078  7078 W wpa_supplicant: USIM:  scard_deinit function
08-15 17:20:53.604  1036  7081 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-15 17:20:53.605  1036  7081 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-15 17:20:53.605  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:20:53.605  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:20:53.605  1036  1440 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=340536
08-15 17:20:53.605  1036  1440 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=340536
08-15 17:20:53.606  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=340537  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-15 17:20:53.606  1036  1440 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=340537  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-15 17:20:53.607  1036  1118 D Tethering: InitialState.processMessage what=4
08-15 17:20:53.607  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-15 17:20:53.608  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:53.608  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:20:53.653  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-15 17:20:53.657  6423  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-15 17:20:53.663  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:53.671  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-15 17:20:53.671  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:53.671  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 17:20:53.671  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-15 17:20:53.673  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
08-15 17:20:53.676  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c24f5d5
08-15 17:20:53.676  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 17:20:53.676  7015  7015 D AppUp4:CustFacade: isPhone : true
08-15 17:20:53.677  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
08-15 17:20:53.677  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-15 17:20:53.680  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:53.680  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 17:20:53.681  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:53.683  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 17:20:53.689  7060  7060 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-15 17:20:53.690  4291  7326 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:53.690  4291  7326 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 17:20:53.691  4291  7325 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 17:20:53.697  7060  7327 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-15 17:20:53.707  7078  7078 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-15 17:20:53.707  1036  7081 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-15 17:20:53.707  1036  7081 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-15 17:20:53.707  1036  7081 D WifiMonitor: Disconnecting from the supplicant, no more events
08-15 17:20:53.708  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-15 17:20:53.710  3396  3396 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-15 17:20:53.710  3396  3396 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:53.711  3396  3396 I LgeMiscReceiver: networkInfo.isConnected() = false
08-15 17:20:53.713  7090  7090 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-15 17:20:53.713  7090  7090 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-15 17:20:53.721  7146  7146 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:53
,08-15 17:20:53.723  7146  7146 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 17:20:53.723  7146  7146 D Weather.Utils: 2 : All the weather widget is gone.
08-15 17:20:53.723  7146  7146 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 17:20:53.723  7146  7146 D WeatherAncestor: connectivity changed - connection : true
08-15 17:20:53.723  7146  7146 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15b10cdb
08-15 17:20:53.724  7146  7146 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 17:20:53.724  7146  7146 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 17:20:53.724  7146  7146 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-15 17:20:53.724  7146  7146 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 17:20:53.724  7146  7146 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:53
08-15 17:20:53.724  6938  7333 W FormManager: Network not available. Please check & try again.
08-15 17:20:53.727  6938  7334 V FormManager: Network unavailable.
08-15 17:20:53.733  6938  7334 V FormManager: Network unavailable.
,08-15 17:20:53.743  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-15 17:20:53.743  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-15 17:20:53.744  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 17:20:53.744  6840  6840 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-15 17:20:53.744  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 17:20:53.745  6840  6840 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-15 17:20:53.745  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-15 17:20:53.745  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 17:20:53.745  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 17:20:53.745  6840  6840 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 17:20:53.745  6840  6840 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-15 17:20:53.752  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 17:20:53.755  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 17:20:53.769  6938  7336 W FormManager: Network not available. Please check & try again.
08-15 17:20:53.771  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:53.777  6938  7337 V FormManager: Network unavailable.
,08-15 17:20:53.778  7217  7236 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 17:20:53.778  7217  7236 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 17:20:53.778  7217  7236 I Adreno-EGL: Build Date: 12/12/14 금
08-15 17:20:53.778  7217  7236 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 17:20:53.778  7217  7236 I Adreno-EGL: Remote Branch: 
08-15 17:20:53.778  7217  7236 I Adreno-EGL: Local Patches: 
08-15 17:20:53.778  7217  7236 I Adreno-EGL: Reconstruct Branch: 
08-15 17:20:53.779  6938  7337 V FormManager: Network unavailable.
08-15 17:20:53.790  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 17:20:53.796  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-15 17:20:53.798  6938  7339 W FormManager: Network not available. Please check & try again.
08-15 17:20:53.801  6938  7340 V FormManager: Network unavailable.
,08-15 17:20:53.803  6938  7340 V FormManager: Network unavailable.
08-15 17:20:53.803  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:53.809  1036  1440 D WifiOffDelayIfNotUsed: stopMonitoring
08-15 17:20:53.809  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 17:20:53.809  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-15 17:20:53.809  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 17:20:53.810  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-15 17:20:53.810  1941  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-15 17:20:53.810  1941  2295 D WfdsService: Set the WFDS Monitor: false
08-15 17:20:53.810  1941  2295 D WfdsMonitor: WFDS Monitor is stopped
08-15 17:20:53.811  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:20:53.812  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-15 17:20:53.812  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-15 17:20:53.812  1036  1470 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-15 17:20:53.812  1036  1470 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-15 17:20:53.812  2502  2502 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-15 17:20:53.820  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:53.821  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:53.821  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:53.823  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 17:20:53.824  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-15 17:20:53.826  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:53.827  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:53.828  7217  7236 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 17:20:53.828  7217  7236 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 17:20:53.828  7217  7236 I Adreno-EGL: Build Date: 12/12/14 금
08-15 17:20:53.828  7217  7236 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 17:20:53.828  7217  7236 I Adreno-EGL: Remote Branch: 
08-15 17:20:53.828  7217  7236 I Adreno-EGL: Local Patches: 
08-15 17:20:53.828  7217  7236 I Adreno-EGL: Reconstruct Branch: 
08-15 17:20:53.833  4291  7341 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 17:20:53.837  4291  7342 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 17:20:53.837  4291  7342 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-15 17:20:53.882  1036  1991 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7343 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-15 17:20:53.900   308  7361 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-15 17:20:53.901  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-15 17:20:53.901  1816  7178 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-15 17:20:53.909  1816  7178 I CheckinService: active receiver: disabled
,08-15 17:20:53.993  7343  7343 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-15 17:20:53.994  7343  7343 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-15 17:20:54.004  7343  7343 V [BNRBootReceiver]: Boot Receiver Return
08-15 17:20:54.007  7343  7343 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-15 17:20:54.008  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 17:20:54.015  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.022  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.030  1036  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=868469593, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-15 17:20:54.041  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 17:20:54.041  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:54.043  6892  6892 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 17:20:54.051  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-15 17:20:54.054  6840  6840 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-15 17:20:54.061  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:54.069  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.083  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.089  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
08-15 17:20:54.101  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.103  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 17:20:54.105  6892  6892 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 17:20:54.110  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:54.124  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.135  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.142  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.142  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:54.142  6892  6892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-15 17:20:54.146  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:54.155  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.163  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.172  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.172  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:54.173  6892  6892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-15 17:20:54.183  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 17:20:54.190  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.197  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 17:20:54.204  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.205  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:54.205  6892  6892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-15 17:20:54.209  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:54.218  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.226  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.233  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.233  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 17:20:54.234  6892  6892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:20:54.239  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:54.248  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.260  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 17:20:54.272  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 17:20:54.273  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:54.274  6892  6892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:20:54.289  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:54.313  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.327  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.345  6640  7009 D UEI.SmartControl: Internal timer expired: 2
08-15 17:20:54.345  6640  7009 D UEI.SmartControl: unbind internal service
,08-15 17:20:54.348  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.351  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:54.358  6892  6892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:20:54.369  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 17:20:54.386  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.389  6640  7003 D serial_port: close(fd = 24)
,08-15 17:20:54.394  6640  7003 I UEI.SmartControl: Serial port is closed.
,08-15 17:20:54.397  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.405  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.406  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 17:20:54.408  6892  6892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:20:54.413  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:54.421  6861  6861 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-15 17:20:54.434  1036  1498 D WifiService: New client listening to asynchronous messages
,08-15 17:20:54.436  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:20:54.447  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.463  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.478  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.479  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:54.481  6892  6892 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-15 17:20:54.483  6892  6892 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-15 17:20:54.484  6892  6892 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-15 17:20:54.497  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:54.503  6861  6861 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-15 17:20:54.506  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 17:20:54.512  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.520  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.531  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.532  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 17:20:54.534  6892  6892 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-15 17:20:54.538  6892  6892 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-15 17:20:54.543  6892  6892 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-15 17:20:54.549  1036  1991 I ActivityManager: Killing 6821:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-15 17:20:54.663  1036  1898 W libprocessgroup: failed to open /acct/uid_10037/pid_6821/cgroup.procs: No such file or directory
,08-15 17:20:54.675  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-15 17:20:54.694  2175  2175 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-15 17:20:54.695  2175  2175 D c       : Getting all permits...
08-15 17:20:54.695  2175  2175 D a       : Opening database...
08-15 17:20:54.707  2175  2175 D a       : Opening database auth.proximity.permit_store...
08-15 17:20:54.707  2175  2175 D a       : Closing database...
08-15 17:20:54.725  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 17:20:54.733  6861  6861 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 17:20:54.734  6861  6861 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 17:20:54.734  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:20:54.737  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.743  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.753  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.753  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:54.757  6892  6892 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-15 17:20:54.764  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:20:54.771  6861  6861 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 17:20:54.771  6861  6861 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-15 17:20:54.771  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 17:20:54.777  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 17:20:54.783  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.791  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.791  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 17:20:54.794  6892  6892 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-15 17:20:54.799  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 17:20:54.805  6861  6861 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-15 17:20:54.805  6861  6861 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-15 17:20:54.805  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:20:54.812  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:20:54.818  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.828  6892  6892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:20:54.829  6892  6892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:20:54.831  6892  6892 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-15 17:20:54.842  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:20:54.849  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 17:20:54.859  6938  7370 W FormManager: Network not available. Please check & try again.
08-15 17:20:54.862  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 17:20:54.871  6938  7371 V FormManager: Network unavailable.
08-15 17:20:54.879  6938  7371 V FormManager: Network unavailable.
,08-15 17:20:54.896  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 17:20:54.896  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 17:20:54.899  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 17:20:54.902  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:54.909  4291  7372 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 17:20:54.911  4291  7373 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 17:20:54.912  4291  7373 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 17:20:54.926  6861  6861 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-15 17:20:54.926  6861  6861 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-15 17:20:54.927  6861  6861 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 17:20:54.936  6938  7375 W FormManager: Network not available. Please check & try again.
08-15 17:20:54.939  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 17:20:54.942  6938  7376 V FormManager: Network unavailable.
08-15 17:20:54.945  6938  7376 V FormManager: Network unavailable.
08-15 17:20:54.948  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:20:54.969  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-15 17:20:54.988  6892  6892 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-15 17:20:54.988  6892  6892 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7777
,08-15 17:20:54.989  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=868469593 [*alarm*], flags=0x0
,08-15 17:20:55.336  1036  1440 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1899327192] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-15 17:20:55.338  1036  1440 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1899327190] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-15 17:20:55.443  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 17:20:55.461  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:55.463  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-15 17:20:55.469  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:55.471  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:55.477  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-15 17:20:55.483  6423  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-15 17:20:55.493  5274  5274 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-15 17:20:55.517  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-15 17:20:55.611  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-15 17:20:55.618  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 17:20:55.618  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:55.618  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 17:20:55.618  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-15 17:20:55.620  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
08-15 17:20:55.624  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c24f5d5
08-15 17:20:55.624  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 17:20:55.624  7015  7015 D AppUp4:CustFacade: isPhone : true
08-15 17:20:55.625  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
08-15 17:20:55.625  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-15 17:20:55.629  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:55.630  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-15 17:20:55.631  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:55.634  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:55.639  4291  7398 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 17:20:55.640  7060  7060 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-15 17:20:55.642  4291  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:55.642  4291  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-15 17:20:55.656  7060  7400 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:55.662  6938  7402 W FormManager: Network not available. Please check & try again.
,08-15 17:20:55.665  3396  3396 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-15 17:20:55.665  3396  3396 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:55.666  3396  3396 I LgeMiscReceiver: networkInfo.isConnected() = true
08-15 17:20:55.666  3396  3396 D PhoneState: setPdpRejectCasuse : false
08-15 17:20:55.669  7090  7090 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-15 17:20:55.669  7090  7090 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-15 17:20:55.680  7146  7146 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:55
08-15 17:20:55.683  6938  7403 V FormManager: Network unavailable.
,08-15 17:20:55.683  7146  7146 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-15 17:20:55.683  7146  7146 D Weather.Utils: 2 : All the weather widget is gone.
08-15 17:20:55.684  7146  7146 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 17:20:55.684  7146  7146 D WeatherAncestor: connectivity changed - connection : true
08-15 17:20:55.684  7146  7146 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15b10cdb
08-15 17:20:55.685  7146  7146 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 17:20:55.685  7146  7146 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-15 17:20:55.685  7146  7146 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-15 17:20:55.685  7146  7146 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 17:20:55.685  6938  7403 V FormManager: Network unavailable.
08-15 17:20:55.685  7146  7146 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:55
08-15 17:20:56.382  1036  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:56.383  1036  1898 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-15 17:20:56.418  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 17:20:56.418  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 17:20:56.418  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 17:20:56.419  1036  1118 D BluetoothManagerService: Message: 1
08-15 17:20:56.419  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-15 17:20:56.446  1036  1118 D BluetoothManagerService: Message: 20
08-15 17:20:56.447  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@150c904e:true
,08-15 17:20:56.452  6957  6957 D BluetoothAdapterState: make
08-15 17:20:56.457  6957  6957 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-15 17:20:56.458  6957  6957 I bluedroid-qcom: init
08-15 17:20:56.459  6957  7416 I BluetoothAdapterState: Entering OffState
08-15 17:20:56.459  6957  6957 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-15 17:20:56.460  6957  6957 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-15 17:20:56.460  6957  6957 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-15 17:20:56.460  6957  6957 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-15 17:20:56.460  6957  6957 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-15 17:20:56.464  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-15 17:20:56.458  7419  7419 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:56.458  7419  7419 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:56.471  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-15 17:20:56.483  7419  7419 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-15 17:20:56.483  7419  7419 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-15 17:20:56.483  7419  7419 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-15 17:20:56.488  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:56.491  7419  7419 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-15 17:20:56.493  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:56.494  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.498  7419  7419 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-15 17:20:56.498  7419  7419 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-15 17:20:56.504  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-15 17:20:56.510  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:56.511  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:56.516  6957  6957 I bluedroid-qcom: get_profile_interface socket
08-15 17:20:56.516  6957  6957 I bluedroid-qcom: get_profile_interface map_client
,08-15 17:20:56.522  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-15 17:20:56.522  1036  1118 D BluetoothManagerService: Message: 40
08-15 17:20:56.522  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-15 17:20:56.523  6957  6974 I bluedroid-qcom: config_hci_snoop_log
08-15 17:20:56.527  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-15 17:20:56.527  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-15 17:20:56.532  6957  7416 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-15 17:20:56.532  6957  7416 D BluetoothAdapterProperties: Setting state to 11
08-15 17:20:56.533  6957  7416 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-15 17:20:56.536  1036  1118 D BluetoothManagerService: Message: 60
08-15 17:20:56.536  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,08-15 17:20:56.536  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-15 17:20:56.540  6957  7416 I LGBluetoothServiceJni: classInitNative: succeeds
,08-15 17:20:56.550  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.552  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-15 17:20:56.553  6957  7420 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-15 17:20:56.556  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:56.558  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:56.558  6957  7420 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-15 17:20:56.558  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 17:20:56.563  6840  6840 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-15 17:20:56.569  6423  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-15 17:20:56.572  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 17:20:56.578  6957  7420 D BluetoothAdapterProperties: Name is: G3
08-15 17:20:56.580  6957  7416 D BluetoothBondStateMachine: make
08-15 17:20:56.585  6957  7416 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.585  6957  7416 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-15 17:20:56.585  6957  7416 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.585  6957  7416 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-15 17:20:56.585  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-15 17:20:56.585  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-15 17:20:56.585  6957  7416 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-15 17:20:56.588  6957  7433 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-15 17:20:56.591  6957  7416 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:20:56.592  5274  5274 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-15 17:20:56.603  6957  6957 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 17:20:56.604  6957  6957 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:56.604  6957  6957 V BluetoothPbapReceiver: ***********state = 11
,08-15 17:20:56.612  6957  6957 D HeadsetService: Received start request. Starting profile...
08-15 17:20:56.613  6957  6957 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-15 17:20:56.613  6957  7416 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:20:56.613  6957  6957 D LGBluetoothHfpAdapter: Version 1.6
08-15 17:20:56.616  5274  5274 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-15 17:20:56.618  6957  6957 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-15 17:20:56.618  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 17:20:56.619  6957  6957 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-15 17:20:56.620  6957  6957 D HeadsetStateMachine: make
,08-15 17:20:56.622  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.623  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:56.624  6957  7416 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:20:56.628  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:20:56.633  6957  7416 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:20:56.662  6957  6957 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:20:56.662  6957  6957 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:20:56.681  1036  2012 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7442 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-15 17:20:56.684  6957  6957 D HeadsetStateMachine: max_hf_connections = 1
08-15 17:20:56.684  6957  6957 I bluedroid-qcom: get_profile_interface handsfree
08-15 17:20:56.687  6957  6957 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-15 17:20:56.687  6957  7416 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:20:56.688   313   313 V AudioPolicyService: registerClient() client 0xb0410480, uid 1002
08-15 17:20:56.688   313  2147 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-15 17:20:56.688   313  2147 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 17:20:56.688   313  2147 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 17:20:56.689  6957  6957 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-15 17:20:56.694   313  1398 V AudioFlinger: registerClient() client 0xb1025c28, pid 6957
08-15 17:20:56.695   313  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:20:56.695   313  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 17:20:56.696  1604  3236 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:20:56.696  1604  3236 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 17:20:56.696  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:20:56.696  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-15 17:20:56.696  3396  3411 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:20:56.696  3396  3411 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 17:20:56.696  6957  6973 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:20:56.696  1036  2032 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:20:56.696  1036  2032 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 17:20:56.696   313  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:20:56.696   313  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:20:56.697  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:20:56.697  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:20:56.697  1604  2149 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:20:56.697  1604  2149 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:20:56.697  1851  4405 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:20:56.697  1851  4405 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:20:56.698  3396  3411 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:20:56.698  3396  3411 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:20:56.699  6957  6973 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-15 17:20:56.699  6957  6973 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:20:56.699  6957  6973 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-15 17:20:56.699  6957  6957 V ToneGenerator: Create Track: 0xb4928080
08-15 17:20:56.699  6957  6957 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-15 17:20:56.699  6957  6957 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-15 17:20:56.699   313  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-15 17:20:56.699   313  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-15 17:20:56.700  6957  7416 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:20:56.700   313  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 17:20:56.700   313  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 17:20:56.701   313   313 I AudioFlinger: isAudioPlaybackHookOn() false
08-15 17:20:56.703   313  2147 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-15 17:20:56.703   313  2147 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-15 17:20:56.703   313  2147 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 17:20:56.703   313  2147 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 17:20:56.703  6957  6957 V AudioSystem: getLatency() output 2, latency 50
08-15 17:20:56.703  6957  6957 V AudioSystem: getFrameCount() output 2, frameCount 960
08-15 17:20:56.704  6957  6957 V AudioTrack: createTrack_l() output 2 afLatency 50
08-15 17:20:56.704   313  1398 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-15 17:20:56.704   313  1398 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-15 17:20:56.704   313  1398 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-15 17:20:56.704   313  1398 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-15 17:20:56.705   313  1398 V AudioFlinger: createTrack() lSessionId: 22
08-15 17:20:56.707  6957  6957 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-15 17:20:56.707   313  1398 V AudioFlinger:, acquiring 22 from 6957, for 6957
08-15 17:20:56.707   313  1398 V AudioFlinger:  added new entry for 22
08-15 17:20:56.708  6957  6957 V ToneGenerator: ToneGenerator INIT OK, time: 343651
08-15 17:20:56.708  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.708  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.708  6957  7438 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-15 17:20:56.709  6957  7438 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 17:20:56.709  6957  7438 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 17:20:56.709  6957  7438 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-15 17:20:56.709   313  2147 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6957
08-15 17:20:56.710   313  2147 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-15 17:20:56.710  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.710   313  2147 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-15 17:20:56.710   313  2147 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-15 17:20:56.710   313  2147 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-15 17:20:56.710   313  2147 V voice   : voice_set_parameters: exit with code(0)
08-15 17:20:56.710   313  2147 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-15 17:20:56.711   313  2147 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-15 17:20:56.711   313  2147 V msm8974_platform: platform_set_parameters: exit with code(0)
08-15 17:20:56.711   313  2147 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
,08-15 17:20:56.711   313  2147 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-15 17:20:56.711   313  2147 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-15 17:20:56.711  6957  7438 V ToneGenerator: ToneGenerator destructor
08-15 17:20:56.711  6957  7438 V ToneGenerator: stopTone
08-15 17:20:56.711  6957  7438 V ToneGenerator: Delete Track: 0xb4928080
08-15 17:20:56.712  6957  7438 V AudioTrack: ~AudioTrack, releasing session id from 6957 on behalf of 6957
08-15 17:20:56.712   313   313 V AudioFlinger: releasing 22 from 6957 for 6957
08-15 17:20:56.712   313   313 V AudioFlinger:  decremented refcount to 0
08-15 17:20:56.712   313   313 V AudioFlinger: purging stale effects
08-15 17:20:56.712   313   313 V AudioPolicyService: AudioCommandThread() adding release output 2
08-15 17:20:56.712   313   313 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-15 17:20:56.712   313   313 V AudioFlinger: PlaybackThread::Track destructor
08-15 17:20:56.712   313  1274 V AudioPolicyService: AudioCommandThread() waking up
08-15 17:20:56.712   313  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-15 17:20:56.712   313   313 V AudioFlinger: removeClient_l() pid 6957, calling pid 313
08-15 17:20:56.712   313  1274 V AudioPolicyManager: releaseOutput() 2
08-15 17:20:56.712   313  1274 V AudioPolicyService: AudioCommandThread() going to sleep
08-15 17:20:56.719  6957  6957 D A2dpService: Received start request. Starting profile...
08-15 17:20:56.721  6957  6957 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-15 17:20:56.722  6957  6957 V Avrcp   : make
08-15 17:20:56.723  6957  6957 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-15 17:20:56.724  6957  6957 I bluedroid-qcom: get_profile_interface avrcp
08-15 17:20:56.730  6957  7416 E BluetoothAdapterService: File transfer profiles supported!!
,08-15 17:20:56.736  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 17:20:56.736  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.737  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 17:20:56.737  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-15 17:20:56.737  6957  6957 V AudioManager: registerRemoteController: size of Media player list: 0
08-15 17:20:56.739  6957  6957 E AudioManager: No RCC entry present to update
08-15 17:20:56.739  6957  6957 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-15 17:20:56.740  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
08-15 17:20:56.743  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c24f5d5
08-15 17:20:56.743  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 17:20:56.743  7015  7015 D AppUp4:CustFacade: isPhone : true
08-15 17:20:56.743  6957  6957 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-15 17:20:56.743  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
08-15 17:20:56.743  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-15 17:20:56.744  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-15 17:20:56.744  6957  6957 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-15 17:20:56.747  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.748  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-15 17:20:56.750  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:56.752  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-15 17:20:56.755  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:56.765  6957  7416 V LGMDMManager: Create singleton instance
08-15 17:20:56.767  6957  7416 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-15 17:20:56.812  4291  7462 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 17:20:56.812  7060  7060 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-15 17:20:56.817  4291  7463 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.818  4291  7463 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 17:20:56.833  3396  3396 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-15 17:20:56.833  3396  3396 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.833  3396  3396 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-15 17:20:56.838  7060  7465 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:56.839  6938  7467 W FormManager: Network not available. Please check & try again.
08-15 17:20:56.842  7090  7090 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-15 17:20:56.842  7090  7090 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-15 17:20:56.850  6938  7468 V FormManager: Network unavailable.
,08-15 17:20:56.859  1036  2032 V SIM_STK : Menu title from STK is T-Mobile
08-15 17:20:56.859  1036  2032 V SIM_STK : Menu title from STK is T-Mobile
08-15 17:20:56.860  7146  7146 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:56
08-15 17:20:56.863  6938  7468 V FormManager: Network unavailable.
,08-15 17:20:56.867  7146  7146 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 17:20:56.867  7146  7146 D Weather.Utils: 2 : All the weather widget is gone.
08-15 17:20:56.868  7146  7146 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 17:20:56.868  7442  7442 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-15 17:20:56.868  7146  7146 D WeatherAncestor: connectivity changed - connection : true
08-15 17:20:56.868  7146  7146 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15b10cdb
08-15 17:20:56.869  7442  7442 W LG Account v2.2: No ProfileInfo entries
08-15 17:20:56.869  7442  7442 I LG Account v2.2: isEnabled: false
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]Country: EU
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]Operator: OPEN
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]Ranking support: false
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]Comfort support: false
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]Accessory: true
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]Health device: true
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]Extra Pedometer: false
08-15 17:20:56.869  7146  7146 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]Blood glucose device: false
08-15 17:20:56.869  7146  7146 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 17:20:56.869  7442  7442 I Feature : [Lifetracker]Device Number: 3
08-15 17:20:56.869  7146  7146 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-15 17:20:56.869  7146  7146 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 17:20:56.869  7146  7146 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:56
08-15 17:20:56.882  6840  6840 D BluetoothPermissionRequest: onReceive
,08-15 17:20:56.892  6840  6840 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 17:20:56.900  6423  6423 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-15 17:20:56.900  6423  6860 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-15 17:20:56.909  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.917  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 17:20:56.917  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-15 17:20:56.919  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 17:20:56.919  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-15 17:20:56.920  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
08-15 17:20:56.923  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c24f5d5
08-15 17:20:56.923  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 17:20:56.923  7015  7015 D AppUp4:CustFacade: isPhone : true
08-15 17:20:56.924  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
08-15 17:20:56.924  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-15 17:20:56.926  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.926  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 17:20:56.928  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:56.931  1036  2025 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-15 17:20:56.936  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:20:56.937  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-15 17:20:56.940  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-15 17:20:56.940  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-15 17:20:56.940  7060  7060 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-15 17:20:56.940  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-15 17:20:56.940  4291  7471 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 17:20:56.940  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-15 17:20:56.940  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 17:20:56.941  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-15 17:20:56.941  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-15 17:20:56.941  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-15 17:20:56.941  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 17:20:56.941  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-15 17:20:56.941  6957  6957 I BluetoothA2dpServiceJni: classInitNative
08-15 17:20:56.941  6957  6957 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-15 17:20:56.941  6957  6957 D A2dpStateMachine: make
08-15 17:20:56.942  6957  6957 I bluedroid-qcom: get_profile_interface a2dp
08-15 17:20:56.942  6957  7474 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-15 17:20:56.944  6957  6957 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-15 17:20:56.944  6957  6957 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-15 17:20:56.944  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.945  6957  6957 I BluetoothHidServiceJni: classInitNative: succeeds
08-15 17:20:56.946  6957  6957 D HidService: Received start request. Starting profile...
08-15 17:20:56.946  6957  6957 I bluedroid-qcom: get_profile_interface hidhost
08-15 17:20:56.946  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.946  4291  7472 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.946  6957  6957 D HeadsetStateMachine: Proxy object connected
08-15 17:20:56.947  4291  7472 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 17:20:56.947  6957  7473 D A2dpStateMachine: Enter Disconnected: -2
08-15 17:20:56.947  6957  6957 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-15 17:20:56.947  6957  6957 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-15 17:20:56.948  6957  6957 I BluetoothHealthServiceJni: classInitNative: succeeds
08-15 17:20:56.949  6957  6957 D HealthService: Received start request. Starting profile...
08-15 17:20:56.951  6957  6957 I bluedroid-qcom: get_profile_interface health
08-15 17:20:56.951  6957  6957 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-15 17:20:56.951  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.952  6957  6957 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-15 17:20:56.952  7060  7476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:20:56.953  6957  6957 D PanService: Received start request. Starting profile...
08-15 17:20:56.953  6957  6957 D BluetoothPanServiceJni: initializeNative(L110): pan
08-15 17:20:56.953  6957  6957 I bluedroid-qcom: get_profile_interface pan
,08-15 17:20:56.957  6957  6957 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-15 17:20:56.957  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.957  3396  3396 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-15 17:20:56.957  3396  3396 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 17:20:56.957  3396  3396 I LgeMiscReceiver: networkInfo.isConnected() = false
08-15 17:20:56.959  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 17:20:56.959  6957  7438 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-15 17:20:56.960  6957  6957 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-15 17:20:56.960  6957  7438 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-15 17:20:56.960  7090  7090 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-15 17:20:56.960  7090  7090 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-15 17:20:56.960  6957  7438 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-15 17:20:56.961  6938  7482 W FormManager: Network not available. Please check & try again.
08-15 17:20:56.963  6957  6957 D BtGatt.DebugUtils: handleDebugAction() action=null
08-15 17:20:56.963  6957  6957 D BtGatt.GattService: Received start request. Starting profile...
08-15 17:20:56.963  6957  6957 D BtGatt.GattService: start()
08-15 17:20:56.963  6957  6957 I bluedroid-qcom: get_profile_interface gatt
08-15 17:20:56.963  6957  6957 D BtGatt.AdvertiseManager: advertise manager created
08-15 17:20:56.965  7146  7146 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:56
08-15 17:20:56.968  7146  7146 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 17:20:56.968  6938  7483 V FormManager: Network unavailable.
08-15 17:20:56.968  7146  7146 D Weather.Utils: 2 : All the weather widget is gone.
08-15 17:20:56.968  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.969  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.969  6957  6957 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-15 17:20:56.970  6938  7483 V FormManager: Network unavailable.
08-15 17:20:56.970  6957  6957 V BluetoothMapService: BluetoothMapBinder()
08-15 17:20:56.970  6957  6957 D BluetoothMapService: Received start request. Starting profile...
08-15 17:20:56.970  6957  6957 D BluetoothMapService: start()
08-15 17:20:56.972  7146  7146 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 17:20:56.972  7146  7146 D WeatherAncestor: connectivity changed - connection : true
08-15 17:20:56.972  7146  7146 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15b10cdb
08-15 17:20:56.972  6957  6957 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-15 17:20:56.972  6957  6957 D BluetoothMapEmailAppObserver: createReceiver()
08-15 17:20:56.972  7146  7146 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 17:20:56.972  7146  7146 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 17:20:56.972  7146  7146 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-15 17:20:56.973  7146  7146 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 17:20:56.973  6957  6957 D BluetoothMapEmailAppObserver: initObservers()
08-15 17:20:56.973  6957  6957 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-15 17:20:56.973  7146  7146 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:20:56
08-15 17:20:56.978  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:56.981  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-15 17:20:56.985  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-15 17:20:56.987  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 17:20:56.987  6957  6957 V PanService: [BTUI] SIM Extra State :ABSENT
08-15 17:20:56.988  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 17:20:56.990  6957  6957 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-15 17:20:56.990  6957  6957 V BluetoothMapService: Handler(): got msg=1
08-15 17:20:56.991  6957  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-15 17:20:56.991  6957  7416 I bluedroid-qcom: enable
08-15 17:20:56.991  6957  7486 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-15 17:20:56.991  6957  7416 I bt_hci_bdroid: init
08-15 17:20:56.991  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:56.992  6957  7416 I bt_vendor: bt-vendor : init
08-15 17:20:56.992  6957  7416 I bt_vendor: bt-vendor : get_bt_soc_type
08-15 17:20:56.992  6957  7416 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-15 17:20:56.992  6957  7416 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-15 17:20:56.992  6957  7416 D bt_userial_mct: userial_init
08-15 17:20:56.992  6957  7486 I bt-btu  : btu_task pending for preload complete event
08-15 17:20:56.992  6957  7416 D bt_hci_bdroid: set_power 1
08-15 17:20:56.992  6957  7416 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-15 17:20:56.992  6957  7416 I bt_vendor: Starting hciattach daemon
08-15 17:20:56.992  6957  7416 I bt_vendor: try to set true
08-15 17:20:56.993  6957  6957 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 17:20:56.993  6957  6957 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 17:20:56.993  6957  6957 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 17:20:56.993  6957  6957 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:56.993  6957  6957 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-15 17:20:56.978  7489  7489 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:56.978  7489  7489 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:57.004  7490  7490 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-15 17:20:57.049  7496  7496 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-15 17:20:57.055  7497  7497 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-15 17:20:57.076  7499  7499 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-15 17:20:57.091  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-15 17:20:57.105  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-15 17:20:57.118  7502  7502 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-15 17:20:57.156  7504  7504 I libmdmdetect: ESOC framework not supported
08-15 17:20:57.158  7504  7504 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-15 17:20:57.169  7504  7504 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-15 17:20:57.169  7504  7504 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-15 17:20:57.170  7504  7504 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-15 17:20:57.170  7504  7504 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-15 17:20:57.170  7504  7504 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-15 17:20:57.170  7504  7504 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-15 17:20:57.170  7504  7504 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-15 17:20:57.217  7504  7505 E QC-QMI  : qmi_client [7504] 14: failed to locate client data
,08-15 17:20:57.220   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-15 17:20:57.220   470   470 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-15 17:20:57.261  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-15 17:20:57.278  7507  7507 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-15 17:20:57.344  6957  7416 I bt_vendor: bluetooth satus is on
08-15 17:20:57.344  6957  7416 D bt_hci_bdroid: preload
08-15 17:20:57.345  6957  7488 D bt_userial_mct: userial_open(port:0)
08-15 17:20:57.345  6957  7488 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-15 17:20:57.348  6957  7488 I bt_vendor: Done intiailizing UART
,08-15 17:20:57.349  6957  7488 I bt_vendor: Done intiailizing UART
08-15 17:20:57.349  6957  7488 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-15 17:20:57.349  6957  7488 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-15 17:20:57.350  6957  7486 I bt-btu  : btu_task received preload complete event
08-15 17:20:57.350  6957  7512 D bt_userial_mct: Entering userial_read_thread()
08-15 17:20:57.351  6957  7486 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-15 17:20:57.351  6957  7486 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-15 17:20:57.355  6957  7486 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_HCI
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_AVDT
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_AVRC
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_A2D
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_BNEP
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_BTM
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_GAP
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_PAN
,08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_SDP,
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_GATT
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_SMP
,08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-15 17:20:57.360  6957  7486 I         : BTE_InitTraceLevels -- TRC_BTIF
08-15 17:20:57.413  6957  7486 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-15 17:20:57.413  6957  7486 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 
08-15 17:20:57.413  6957  7486 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
08-15 17:20:57.415  1036  1104 W ProcessCpuTracker: Skipping unknown process pid 7435
,08-15 17:20:57.416  1036  1104 W ProcessCpuTracker: Skipping unknown process pid 7436
,08-15 17:20:57.416  1036  1104 W ProcessCpuTracker: Skipping unknown process pid 7439
08-15 17:20:57.417  1036  1104 W ProcessCpuTracker: Skipping unknown process pid 7440
08-15 17:20:57.418  1036  1104 W ProcessCpuTracker: Skipping unknown process pid 7509
,08-15 17:20:57.444  6957  7420 E bt-btif : Calling BTA_HhEnable
,08-15 17:20:57.444  6957  7420 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-15 17:20:57.444  6957  7486 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-15 17:20:57.444  6957  7486 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-15 17:20:57.444  6957  7486 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-15 17:20:57.444  6957  7486 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-15 17:20:57.444  6957  7486 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-15 17:20:57.444  6957  7420 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-15 17:20:57.446  6957  7420 D BluetoothAdapterProperties: Name is: G3
08-15 17:20:57.446  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-15 17:20:57.447  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-15 17:20:57.447  6957  7420 D BluetoothAdapterProperties: Scan Mode:20
08-15 17:20:57.448  6957  7420 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 17:20:57.448  6957  7420 D bt_hci_bdroid: postload
08-15 17:20:57.448  6957  7488 D bt_hci_bdroid: Used up Tx Cmd credits
,08-15 17:20:57.449  6957  7420 D bte_conf: Device ID record 1 : primary
08-15 17:20:57.449  6957  7420 D bte_conf:   vendorId            = 00c4
08-15 17:20:57.449  6957  7420 D bte_conf:   vendorIdSource      = 0001
08-15 17:20:57.449  6957  7420 D bte_conf:   product             = 13a1
08-15 17:20:57.449  6957  7420 D bte_conf:   version             = 1000
08-15 17:20:57.449  6957  7420 D bte_conf:   clientExecutableURL = 
08-15 17:20:57.449  6957  7420 D bte_conf:   serviceDescription  = 
08-15 17:20:57.449  6957  7420 D bte_conf:   documentationURL    = 
08-15 17:20:57.449  6957  7420 D bte_conf: bte_load_did_conf no section named DID2.
08-15 17:20:57.451  6957  7486 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-15 17:20:57.451  6957  7488 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 17:20:57.452  6957  7420 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-15 17:20:57.452  6957  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-15 17:20:57.453  6957  7416 D BluetoothAdapterProperties: ScanMode =  20
08-15 17:20:57.453  6957  7416 D BluetoothAdapterProperties: State =  11
08-15 17:20:57.453  6957  7416 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-15 17:20:57.453  6957  7416 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-15 17:20:57.453  6957  7416 D BluetoothAdapterProperties: Setting state to 12
08-15 17:20:57.453  6957  7416 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-15 17:20:57.454  6957  7488 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 17:20:57.454  6957  7488 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 17:20:57.454  1036  1118 D BluetoothManagerService: Message: 60
08-15 17:20:57.454  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-15 17:20:57.454  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-15 17:20:57.454  6957  7416 I BluetoothAdapterState: Entering On State
08-15 17:20:57.438  7514  7514 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:57.455  6957  7488 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 17:20:57.438  7514  7514 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:57.457  6957  7420 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-15 17:20:57.458  6840  6856 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-15 17:20:57.459  6957  7512 E bt_mct  : hci lib postload completed
08-15 17:20:57.462  6957  7416 D LGBluetoothServiceAdapter: [BTUI] OnState
08-15 17:20:57.462  6957  7416 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-15 17:20:57.462  6957  7416 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-15 17:20:57.463  6957  7416 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-15 17:20:57.470  6957  7486 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:20:57.470  6957  7486 W bt-smp  : Plain text(LSB ~ MSB) = b0 6c 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 17:20:57.471  6957  7486 W bt-smp  : Encrypted text(LSB ~ MSB) = 01 34 c9 07 df 1c 0a f9 94 9d d3 04 96 db 19 5a 
08-15 17:20:57.472  6840  6857 D BluetoothMap: onBluetoothStateChange: up=true
08-15 17:20:57.473  6957  7486 W bt-btm  : Stopping oneshot timer
08-15 17:20:57.482  6957  7420 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 17:20:57.483  6957  7420 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-15 17:20:57.483  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 17:20:57.483  6840  6856 D BluetoothPbap: onBluetoothStateChange: up=true
08-15 17:20:57.486  6840  6840 D BluetoothInputDevice: Proxy object connected
08-15 17:20:57.486  6840  6840 D HidProfile: Bluetooth service connected
,08-15 17:20:57.489  1036  1036 D BluetoothHeadset: Proxy object connected
08-15 17:20:57.490  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:57.490  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:57.490  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:57.490  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:57.490  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:20:57.490  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:57.490  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:57.490  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:57.491  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 17:20:57.495  1851  1851 D BluetoothHeadset: Proxy object connected
08-15 17:20:57.495  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-15 17:20:57.496  1851  4405 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 17:20:57.497  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:20:57.498  1036  1036 D BluetoothA2dp: Proxy object connected
,08-15 17:20:57.499  6957  7486 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:20:57.500  6957  7486 W bt-smp  : Plain text(LSB ~ MSB) = 02 30 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 17:20:57.500  6957  7486 W bt-smp  : Encrypted text(LSB ~ MSB) = ae 08 2c 65 f8 90 51 3e 8b b2 80 c7 2c 3a ed 6e 
08-15 17:20:57.500  6957  7486 W bt-btm  : Stopping oneshot timer
08-15 17:20:57.501  6840  6840 D BluetoothMap: Proxy object connected
08-15 17:20:57.502  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:57.502  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:57.502  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:57.502  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:57.502  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:20:57.502  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:57.502  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:57.502  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:57.504  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:20:57.504  6957  7416 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-15 17:20:57.501  6840  6840 D MapProfile: Bluetooth service connected
08-15 17:20:57.506  6840  6840 D BluetoothMap: getConnectedDevices()
08-15 17:20:57.507  1851  1851 D BluetoothHeadset: Proxy object connected
08-15 17:20:57.509  6957  6973 V BluetoothMapService: getConnectedDevices()
,08-15 17:20:57.510  6840  7516 D BluetoothPan: onBluetoothStateChange on: true
08-15 17:20:57.510  6840  7516 D BluetoothPan: onBluetoothStateChange call bindService
08-15 17:20:57.514  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 17:20:57.514  6840  6840 D BluetoothPan: BluetoothPAN Proxy object connected
08-15 17:20:57.514  6840  6840 D PanProfile: Bluetooth service connected
08-15 17:20:57.516  1851  1851 D BluetoothHeadset: Proxy object connected
08-15 17:20:57.516  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-15 17:20:57.516  6957  7486 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:20:57.516  6957  7486 W bt-smp  : Plain text(LSB ~ MSB) = a6 c2 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 17:20:57.516  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-15 17:20:57.516  6957  7486 W bt-smp  : Encrypted text(LSB ~ MSB) = ba 72 09 b1 20 33 66 49 46 8b 46 73 76 dc a8 f1 
08-15 17:20:57.517  6957  7486 W bt-btm  : Stopping oneshot timer
08-15 17:20:57.518  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-15 17:20:57.519  1036  1118 D BluetoothManagerService: Message: 40
08-15 17:20:57.519  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-15 17:20:57.519  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 17:20:57.522  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:57.522  1941  2137 D LGBluetoothAPIService: Message: 1
08-15 17:20:57.522  1941  2137 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-15 17:20:57.530  6708  6708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-15 17:20:57.531  7521  7521 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-15 17:20:57.533  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:57.535  6957  7486 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:20:57.535  6957  7486 W bt-smp  : Plain text(LSB ~ MSB) = d4 58 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 17:20:57.535  6957  7486 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d c4 9f 94 21 46 53 f2 51 26 7d 2d ec a7 a5 7c 
08-15 17:20:57.535  6957  7486 W bt-btm  : Stopping oneshot timer
08-15 17:20:57.537  6840  6840 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-15 17:20:57.540  1036  1118 D BluetoothManagerService: Message: 30
08-15 17:20:57.540  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:57.541  1941  2137 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-15 17:20:57.543  6957  6957 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:57.543  6957  6957 D BluetoothMapService: STATE_ON
08-15 17:20:57.544  6840  6840 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-15 17:20:57.545  6957  6957 D LGBluetoothAPIServer: [BTUI] onCreate()
08-15 17:20:57.545  6957  6957 D LGBluetoothAPIServer: [BTUI] onBind()
08-15 17:20:57.546  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-15 17:20:57.547  1941  2137 D LGBluetoothAPIService: Message: 100
08-15 17:20:57.547  1941  2137 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-15 17:20:57.548  6957  7486 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:20:57.548  6957  7486 W bt-smp  : Plain text(LSB ~ MSB) = be 7d 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 17:20:57.548  6957  7486 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f 53 7f f9 94 0a 5e d0 3c ea d4 e7 f3 72 2b 17 
08-15 17:20:57.548  6957  7486 W bt-btm  : Stopping oneshot timer
08-15 17:20:57.548  1036  1118 D BluetoothManagerService: Message: 30
08-15 17:20:57.553  6840  6840 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-15 17:20:57.555  6840  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-15 17:20:57.560  6840  6840 D BluetoothA2dp: Proxy object connected
08-15 17:20:57.561  6840  6840 D A2dpProfile: Bluetooth service connected
08-15 17:20:57.563  6840  6840 D BluetoothHeadset: Proxy object connected
08-15 17:20:57.565  6840  6840 D HeadsetProfile: Bluetooth service connected
08-15 17:20:57.571  6840  6840 D DockEventReceiver: finishStartingService: stopping service
,08-15 17:20:57.572  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:57.572  6957  6957 V BluetoothPbapService: Pbap Service onCreate
08-15 17:20:57.572  6957  6957 V BluetoothPbapService: Starting PBAP service
08-15 17:20:57.574  6957  6957 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-15 17:20:57.575  6957  6957 V BluetoothPbapService: Pbap Service onBind
08-15 17:20:57.577  6957  6957 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:57.577  6840  6840 D BluetoothPbap: Proxy object connected
08-15 17:20:57.577  6957  6957 V BluetoothPbapService: state: 12
08-15 17:20:57.577  6957  6957 V BluetoothMapService: Handler(): got msg=1
08-15 17:20:57.578  6840  6840 D PbapServerProfile: Bluetooth service connected
08-15 17:20:57.578  6957  6957 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-15 17:20:57.578  6957  6957 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 17:20:57.578  6957  6957 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:57.579  6957  6957 V BluetoothPbapReceiver: ***********state = 12
08-15 17:20:57.579  6957  7528 D BluetoothMapMasInstance: MAS initSocket()
08-15 17:20:57.580  6957  7528 D BluetoothMapMasInstance:   masId = 00
08-15 17:20:57.580  6957  7528 D BluetoothMapMasInstance:   msgTypes = 0e
08-15 17:20:57.580  6957  7528 D BluetoothMapMasInstance:   masName = SMS/MMS
08-15 17:20:57.580  6957  7528 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-15 17:20:57.581  1036  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:57.582  6957  6957 V BluetoothPbapService: Handler(): got msg=1
08-15 17:20:57.583  6957  6957 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-15 17:20:57.584  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 17:20:57.584  2175  2175 D c       : Getting all permits...
,08-15 17:20:57.584  2175  2175 D a       : Opening database...
08-15 17:20:57.586  6957  7528 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:20:57.587  6957  7529 V BluetoothPbapService: Pbap Service initSocket
08-15 17:20:57.587  1036  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:57.588  6957  7528 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-15 17:20:57.588  6957  7528 V BluetoothMapMasInstance: Succeed to create listening socket 
08-15 17:20:57.588  6957  7528 D BluetoothMapMasInstance: Accepting socket connection...
08-15 17:20:57.588  6957  7420 D BluetoothAdapterProperties: Scan Mode:21
08-15 17:20:57.588  6957  7420 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-15 17:20:57.589  2175  2175 D a       : Opening database auth.proximity.permit_store...
08-15 17:20:57.590  2175  2175 D a       : Closing database...
08-15 17:20:57.590  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:57.592  6957  7529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:20:57.592  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:57.593  6957  7529 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-15 17:20:57.594  6957  7529 V BluetoothPbapService: Succeed to create listening socket 
08-15 17:20:57.594  6957  7529 V BluetoothPbapService: Accepting socket connection...
08-15 17:20:57.603  6840  6840 D BluetoothPermissionRequest: onReceive
,08-15 17:20:57.605  6840  6840 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-15 17:20:57.607  6840  6840 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 17:20:57.611  6957  6957 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-15 17:20:57.612  6957  6957 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-15 17:20:57.619  6957  6957 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-15 17:20:57.643  6957  6957 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-15 17:20:57.643  6957  6957 V BtOppService: onCreate
,08-15 17:20:57.648  6957  6957 V BluetoothOppNotification: send message
,08-15 17:20:57.655  6957  6957 V BtOppService: Starting RfcommListener
08-15 17:20:57.661  6957  6957 D BluetoothOppPreference: Dumping Names:  
08-15 17:20:57.661  6957  6957 D BluetoothOppPreference: {}
08-15 17:20:57.661  6957  6957 D BluetoothOppPreference: Dumping Channels:  
08-15 17:20:57.661  6957  6957 D BluetoothOppPreference: {}
08-15 17:20:57.662  6957  6957 V BtOppService: onStartCommand
08-15 17:20:57.663  6957  7535 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-15 17:20:57.670  6957  7535 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 17:20:57.671  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:57.671  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-15 17:20:57.672  6957  7532 V BtOppService: Deleted complete outbound shares, number =  0
08-15 17:20:57.675  6957  7532 V BtOppService: Deleted complete inbound failed shares, number = 0
08-15 17:20:57.675  6957  7532 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-15 17:20:57.677  6957  6957 V BluetoothOppNotification: new notify threadi!
08-15 17:20:57.677  6957  6957 V BluetoothOppNotification: send delay message
,08-15 17:20:57.679  6957  7536 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-15 17:20:57.679  6957  7535 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@229171b4 on behalf of 
08-15 17:20:57.679  6957  7532 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dca71dd on behalf of 
,08-15 17:20:57.679  6957  6957 V BtOppService: start RfcommListener
08-15 17:20:57.698  6957  7535 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-15 17:20:57.699  6957  7535 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 17:20:57.699  6957  6957 V BtOppService: RfcommListener started
08-15 17:20:57.700  6957  6957 V BtOppService: ContentObserver received notification
,08-15 17:20:57.700  6957  7537 V BtOppRfcommListener: Starting RFCOMM listener....
08-15 17:20:57.701  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:57.702  6957  7535 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bd20152 on behalf of 
08-15 17:20:57.702  6957  7537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:20:57.702  6957  7535 V BluetoothOppNotification: update too frequent, put in queue
08-15 17:20:57.703  6957  7536 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c3dbc23 on behalf of 
08-15 17:20:57.703  6957  7537 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-15 17:20:57.704  6957  7537 V BtOppRfcommListener: Started RFCOMM listener....
08-15 17:20:57.704  6957  7537 I BtOppRfcommListener: Accept thread started.
08-15 17:20:57.704  6957  7537 V BtOppRfcommListener: Accepting connection...
08-15 17:20:57.704  6957  7536 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-15 17:20:57.706  6957  7536 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-15 17:20:57.706  6957  7535 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-15 17:20:57.706  6957  7535 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 17:20:57.709  6957  7535 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@badf520 on behalf of 
08-15 17:20:57.710  6957  7536 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30814ed9 on behalf of 
08-15 17:20:57.710  6957  7535 V BluetoothOppNotification: update too frequent, put in queue
08-15 17:20:57.711  6957  7536 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-15 17:20:57.712  6957  7535 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-15 17:20:57.715  6957  7536 V BluetoothOppNotification: outbound notification was removed.
08-15 17:20:57.716  6957  7536 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-15 17:20:57.717  6957  7536 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21eae09e on behalf of 
08-15 17:20:57.718  6957  7536 V BluetoothOppNotification: inbound: succ-0  fail-0
08-15 17:20:57.720  6957  7536 V BluetoothOppNotification: inbound notification was removed.
08-15 17:20:57.720  6957  7536 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-15 17:20:57.722  6957  7536 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19a5f77f on behalf of 
08-15 17:20:57.732  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:57.732  6957  6957 V BluetoothFtpService: Ftp Service onCreate
08-15 17:20:57.732  6957  6957 I BluetoothFtpService: Ftp Service onCreate
08-15 17:20:57.732  6957  6957 V BtOppService: ContentObserver received notification
08-15 17:20:57.733  6957  6957 V BluetoothFtpService: Ftp Service onStartCommand
08-15 17:20:57.733  6957  6957 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:57.733  6957  6957 V BluetoothFtpService: Starting Listening on sockets
08-15 17:20:57.733  6957  6957 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 17:20:57.733  6957  6957 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 17:20:57.733  6957  6957 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 17:20:57.734  6957  6957 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:57.734  6957  6957 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-15 17:20:57.734  6957  6957 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-15 17:20:57.735  6957  7538 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-15 17:20:57.735  6957  7538 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-15 17:20:57.737  6957  6957 V BluetoothFtpService: Handler(): got msg=1
08-15 17:20:57.738  6957  6957 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-15 17:20:57.738  6957  6957 V BluetoothFtpService: Ftp Service initSocket
08-15 17:20:57.740  6957  7538 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c2eff95 on behalf of 
08-15 17:20:57.741  6957  7538 V BluetoothOppNotification: update too frequent, put in queue
08-15 17:20:57.742  6957  7538 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-15 17:20:57.743  1036  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:57.744  6957  6957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:20:57.745  6957  6957 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-15 17:20:57.747  6957  7539 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-15 17:20:57.761  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:20:57.761  6957  6957 V BluetoothSapService: Sap Service onCreate
08-15 17:20:57.763  6957  6957 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-15 17:20:57.763  6957  6957 V BluetoothSapService: state: 12
,08-15 17:20:57.763  6957  6957 V BluetoothSapService: Starting SAP server process
08-15 17:20:57.764  6957  6957 V BluetoothSapService: SAP Service startRfcommListenerThread
08-15 17:20:57.766  6957  7541 V BluetoothSapService: Sap Service initRfcommSocket
08-15 17:20:57.748  7540  7540 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:57.758  7540  7540 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:20:57.768  1036  1603 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:57.770  6957  7541 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:20:57.772  6957  7541 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-15 17:20:57.772  6957  7541 V BluetoothSapService: Succeed to create listening socket 
08-15 17:20:57.772  6957  7541 V BluetoothSapService: Accepting socket connection...
08-15 17:20:57.780  7540  7540 V BT_SAP  : Event pipe created
08-15 17:20:57.780  7540  7540 V BT_SAP  : create_server_socket qcom.sap.server
08-15 17:20:57.780  7540  7540 V BT_SAP  : created socket fd 6
,08-15 17:20:57.816  7188  7239 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-15 17:20:58.426  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:20:58.426  1036  1391 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 17:20:58.459  1036  1440 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-15 17:20:58.460  1036  1440 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-15 17:20:58.674  1036  1603 I ActivityManager: Killing 7343:com.lge.bnr/1000 (adj 15): empty #17
,08-15 17:20:58.680  6957  6957 V BluetoothOppNotification: new notify threadi!,
08-15 17:20:58.681  6957  6957 V BluetoothOppNotification: send delay message
08-15 17:20:58.690  6957  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-15 17:20:58.747  1036  1902 W libprocessgroup: failed to open /acct/uid_1000/pid_7343/cgroup.procs: No such file or directory
,08-15 17:20:58.876  1036  1940 I art     : Explicit concurrent mark sweep GC freed 94489(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.135ms total 157.200ms
,08-15 17:20:58.880  1036  1991 I ActivityManager: Killing 6861:com.lge.sync/1000 (adj 15): empty #17
08-15 17:20:58.886  6957  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39cd0011 on behalf of 
08-15 17:20:58.887  6957  7554 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-15 17:20:58.896  1036  1498 D WifiService: Client connection lost with reason: 4
,08-15 17:20:58.899  6957  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-15 17:20:58.900  6957  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30746576 on behalf of 
08-15 17:20:58.901  6957  7554 V BluetoothOppNotification: outbound: succ-0  fail-0
08-15 17:20:58.902  6957  7554 V BluetoothOppNotification: outbound notification was removed.
08-15 17:20:58.903  6957  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-15 17:20:58.903  6957  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7bd5777 on behalf of 
08-15 17:20:58.904  6957  7554 V BluetoothOppNotification: inbound: succ-0  fail-0
08-15 17:20:58.905  6957  7554 V BluetoothOppNotification: inbound notification was removed.
08-15 17:20:58.905  6957  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-15 17:20:58.908  6957  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@194eafe4 on behalf of 
,08-15 17:20:58.913  1036  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_6861/cgroup.procs: No such file or directory
,08-15 17:20:59.440  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:20:59.440  1036  1956 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@24798d7a mBinding = false
,08-15 17:20:59.473  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 17:20:59.474  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 17:20:59.474  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 17:20:59.475  1036  1118 D BluetoothManagerService: Message: 2
08-15 17:20:59.475  1036  1118 D BluetoothManagerService: Sending off request.
08-15 17:20:59.476  6957  6974 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-15 17:20:59.477  6957  7416 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-15 17:20:59.477  6957  7416 D BluetoothAdapterProperties: Setting state to 13
08-15 17:20:59.477  6957  7416 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-15 17:20:59.478  6957  7416 D BluetoothAdapterProperties: onBluetoothDisable()
08-15 17:20:59.478  6957  7416 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-15 17:20:59.480  6957  7420 D BluetoothAdapterProperties: Scan Mode:20
08-15 17:20:59.482  6957  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-15 17:20:59.485  6957  7416 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-15 17:20:59.490  6957  7529 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:59.490  6957  7537 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:59.491  6957  7539 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:59.492  6957  7541 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:59.492  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-15 17:20:59.492  6957  7486 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-15 17:20:59.494  6957  7528 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-15 17:20:59.494  6957  7528 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-15 17:20:59.494  6957  7528 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-15 17:20:59.494  6957  7528 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-15 17:20:59.494  6957  7528 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-15 17:20:59.494  6957  7528 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-15 17:20:59.494  6957  7528 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-15 17:20:59.494  6957  7528 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-15 17:20:59.498  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-15 17:20:59.498  6957  7486 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-15 17:20:59.509  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:59.509  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:59.509  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:59.509  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:59.509  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:59.509  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:59.509  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:59.509  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:59.509  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:59.513  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:59.513  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-15 17:20:59.518  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:59.518  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:20:59.518  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:20:59.518  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:20:59.518  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:20:59.518  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-15 17:20:59.518  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:20:59.518  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:20:59.518  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:20:59.520  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-15 17:20:59.520  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:20:59.522  1036  1118 D BluetoothManagerService: Message: 60
08-15 17:20:59.522  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-15 17:20:59.523  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-15 17:20:59.528  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:59.530  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 17:20:59.534  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:59.535  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:20:59.538  6957  6957 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:59.538  6957  6957 D BluetoothMapService: STATE_TURNING_OFF
08-15 17:20:59.538  6957  6957 V BluetoothMapService: Handler(): got msg=4
08-15 17:20:59.539  6957  6957 D BluetoothMapService: MAP Service closeService in
08-15 17:20:59.539  6957  6957 D BluetoothMapMasInstance: MAP Service shutdown
08-15 17:20:59.539  6957  6957 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 17:20:59.539  6957  6957 V BluetoothMapService: MAP Service closeService out
,08-15 17:20:59.542  6957  6957 V BtOppService: Receiver DISABLED_ACTION 
08-15 17:20:59.542  6957  6957 I BtOppRfcommListener: stopping Accept Thread
08-15 17:20:59.542  6957  6957 V BtOppRfcommListener: close mBtServerSocket
08-15 17:20:59.543  6957  7537 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-15 17:20:59.543  6957  6957 V BtOppRfcommListener: waiting for thread to terminate
08-15 17:20:59.543  6957  6957 V BtOppRfcommListener: done waiting for thread to terminate
08-15 17:20:59.546  6840  6840 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-15 17:20:59.556  6840  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-15 17:20:59.560  6957  6957 V BtOppService: onDestroy
08-15 17:20:59.562  6957  6957 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-15 17:20:59.566  6957  6957 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 17:20:59.566  6957  6957 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:59.566  6957  6957 V BluetoothPbapReceiver: ***********state = 13
08-15 17:20:59.568  6957  6957 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-15 17:20:59.570  6957  6957 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:59.570  6957  6957 V BluetoothPbapService: state: 13
08-15 17:20:59.571  6957  6957 V BluetoothPbapService: Pbap Service closeService in
,08-15 17:20:59.575  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 17:20:59.577  6957  6957 V BluetoothPbapService: successfully stopped pbap service
08-15 17:20:59.577  6957  6957 V BluetoothPbapService: Pbap Service closeService out
08-15 17:20:59.578  6957  6957 V BluetoothPbapService: Pbap Service onDestroy
08-15 17:20:59.578  6957  6957 V BluetoothPbapService: Pbap Service closeService in
08-15 17:20:59.578  6957  6957 V BluetoothPbapService: Pbap Service closeService out
08-15 17:20:59.578  6957  6957 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-15 17:20:59.598  6840  6840 D DockEventReceiver: finishStartingService: stopping service
,08-15 17:20:59.608  6840  6840 D BluetoothPbap: Proxy object disconnected
08-15 17:20:59.608  6840  6840 D PbapServerProfile: Bluetooth service disconnected
08-15 17:20:59.614  6840  6840 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-15 17:20:59.621  6840  6840 D BluetoothPermissionRequest: onReceive
08-15 17:20:59.621  6840  6840 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-15 17:20:59.629  6840  6840 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-15 17:20:59.633  6957  6957 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-15 17:20:59.634  6957  6957 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-15 17:20:59.634  6957  6957 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-15 17:20:59.639  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:59.639  6957  6957 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-15 17:20:59.640  6957  6957 V BluetoothFtpService: Ftp Service onStartCommand
08-15 17:20:59.640  6957  6957 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:59.641  6957  6957 V BluetoothFtpService: Ftp Service closeService
08-15 17:20:59.641  6957  6957 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-15 17:20:59.642  6957  6957 V BluetoothFtpService: successfully stopped ftp service
08-15 17:20:59.643  6957  6957 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 17:20:59.643  6957  6957 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 17:20:59.643  6957  6957 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 17:20:59.643  6957  6957 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:59.643  6957  6957 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-15 17:20:59.643  6957  6957 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-15 17:20:59.646  6957  6957 V BluetoothFtpService: Ftp Service onDestroy
08-15 17:20:59.646  6957  6957 V BluetoothFtpService: Ftp Service closeService
08-15 17:20:59.650  6957  6957 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:20:59.650  6957  6957 V BluetoothSapService: state: 13
08-15 17:20:59.650  6957  6957 V BluetoothSapService: Stopping SAP server process
08-15 17:20:59.653  6957  6957 V BluetoothSapService: Sap Service closeSapService in
08-15 17:20:59.653  6957  6957 V BluetoothSapService: Close listen Socket : 
08-15 17:20:59.653  6957  6957 V BluetoothSapService: Close rfcomm Socket : 
08-15 17:20:59.653  6957  6957 V BluetoothSapService: Close sapd  Socket : 
08-15 17:20:59.654  6957  6957 V BluetoothSapService: Sap Service closeSapService out
08-15 17:20:59.654  6957  6957 V BluetoothSapService: Sap Service onDestroy
08-15 17:20:59.654  6957  6957 V BluetoothSapService: Sap Service closeSapService in
08-15 17:20:59.654  6957  6957 V BluetoothSapService: Close listen Socket : 
08-15 17:20:59.654  6957  6957 V BluetoothSapService: Close rfcomm Socket : 
08-15 17:20:59.654  6957  6957 V BluetoothSapService: Close sapd  Socket : 
,08-15 17:20:59.658  6957  6957 V BluetoothSapService: Sap Service closeSapService out
,08-15 17:21:00.001  1036  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=868469593, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-15 17:21:00.047  2610  2610 D [Concierge]Service: onStartCommand(). Type : 9
,08-15 17:21:00.065  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-15 17:21:00.065  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-15 17:21:00.065  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-15 17:21:00.065  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-15 17:21:00.072  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-15 17:21:00.072  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-15 17:21:00.072  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-15 17:21:00.075  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-15 17:21:00.119  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=868469593 [*alarm*], flags=0x0
,08-15 17:21:00.397  6957  7420 D bt_hci_bdroid: cleanup
,08-15 17:21:00.400  6957  7488 I bt_lpm  : LPM is already off!!!
08-15 17:21:00.401  6957  7486 W bt-btif : ag scb idx 1 not allocated
08-15 17:21:00.401  6957  7486 E bt-btif : BTA AG is already disabled, ignoring ...
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-15 17:21:00.401  6957  7486 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-15 17:21:00.401  6957  7486 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-15 17:21:00.402  6957  7512 I bt_userial_mct: exiting userial_read_thread
08-15 17:21:00.402  6957  7512 D bt_userial_mct: Leaving userial_evt_read_thread()
08-15 17:21:00.403  6957  7420 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-15 17:21:00.403  6957  7488 I bt_vendor: hw_epilog_process
08-15 17:21:00.403  6957  7420 D bt_hci_bdroid: cleanup Finalizing cleanup
08-15 17:21:00.403  6957  7420 D bt_userial_mct: userial_close
08-15 17:21:00.403  6957  7420 E bt_userial_mct: pthread_join() FAILED result:3
08-15 17:21:00.403  6957  7420 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-15 17:21:00.407  6957  7420 D bt_hci_bdroid: set_power 0
08-15 17:21:00.407  6957  7420 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-15 17:21:00.407  6957  7420 I bt_vendor: bluetooth satus is on
08-15 17:21:00.407  6957  7420 I bt_vendor: bt-vendor : resetting BT status
08-15 17:21:00.408  6957  7420 I bt_vendor: Starting hciattach daemon
08-15 17:21:00.408  6957  7420 I bt_vendor: try to set false
08-15 17:21:00.409  6957  7420 I bt_vendor: Starting hciattach daemon
08-15 17:21:00.409  6957  7420 I bt_vendor: try to set false
08-15 17:21:00.410  6957  7420 I bt_vendor: cleanup
08-15 17:21:00.412  6957  7486 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-15 17:21:00.415  6957  7420 I GKI_LINUX: GKI_exit_task 0 done
08-15 17:21:00.415  6957  7420 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-15 17:21:00.418  6957  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-15 17:21:00.421  6957  6957 D HeadsetService: Received stop request...Stopping profile...
08-15 17:21:00.423  6957  6957 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-15 17:21:00.423  6957  6957 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 17:21:00.424  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
,08-15 17:21:00.429  6957  6957 D A2dpService: Received stop request...Stopping profile...
08-15 17:21:00.430  6957  7438 D HeadsetStateMachine: Exit Disconnected: -1
08-15 17:21:00.431  6957  6957 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-15 17:21:00.431  6957  7473 D A2dpStateMachine: Exit Disconnected: -1
08-15 17:21:00.432  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-15 17:21:00.432  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-15 17:21:00.433  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-15 17:21:00.433  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-15 17:21:00.433  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-15 17:21:00.438  6957  6957 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-15 17:21:00.438  6957  6957 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 17:21:00.438  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
,08-15 17:21:00.442  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-15 17:21:00.442  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-15 17:21:00.443  6957  7416 D BluetoothAdapterState: Stopping profile services that were post enabled
08-15 17:21:00.445  6957  6957 D HidService: Received stop request...Stopping profile...
08-15 17:21:00.445  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:00.446  6957  6957 D HeadsetStateMachine: Unbinding service...
08-15 17:21:00.448  6957  6957 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 17:21:00.448  6957  6957 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 17:21:00.448  6957  6957 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 17:21:00.448  6957  6957 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 17:21:00.448  6957  6957 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-15 17:21:00.448  6957  6957 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-15 17:21:00.448  6957  6957 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-15 17:21:00.449  6957  6957 D HealthService: Received stop request...Stopping profile...
08-15 17:21:00.449  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:00.451  6957  6957 D PanService: Received stop request...Stopping profile...
,08-15 17:21:00.455  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:00.456  6957  6957 D BtGatt.DebugUtils: handleDebugAction() action=null
08-15 17:21:00.457  6957  6957 D BtGatt.GattService: Received stop request...Stopping profile...
08-15 17:21:00.457  6957  6957 D BtGatt.GattService: stop()
08-15 17:21:00.457  6957  6957 D BtGatt.AdvertiseManager: advertise clients cleared
08-15 17:21:00.458  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:00.460  6957  6957 D BluetoothMapService: Received stop request...Stopping profile...
08-15 17:21:00.460  6957  6957 D BluetoothMapService: stop()
08-15 17:21:00.460  6957  6957 D BluetoothMapEmailAppObserver: deinitObservers()
08-15 17:21:00.460  6957  6957 D BluetoothMapEmailAppObserver: removeReceiver()
08-15 17:21:00.461  6957  6957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:00.462  6957  6957 I BluetoothA2dpServiceJni: cleanupNative
08-15 17:21:00.463  6957  7474 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-15 17:21:00.465  6957  6957 I GKI_LINUX: GKI_exit_task 2 done
08-15 17:21:00.465  6957  6957 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-15 17:21:00.466  6957  6957 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-15 17:21:00.466  6957  6957 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-15 17:21:00.467  6957  6957 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-15 17:21:00.467  6957  6957 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-15 17:21:00.467  6957  6957 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-15 17:21:00.467  6957  6957 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-15 17:21:00.467  6957  6957 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-15 17:21:00.470  6957  6957 V BluetoothMapService: Handler(): got msg=4
08-15 17:21:00.470  6957  6957 D BluetoothMapService: MAP Service closeService in
08-15 17:21:00.470  6957  6957 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 17:21:00.470  6957  6957 V BluetoothMapService: MAP Service closeService out
08-15 17:21:00.471  6957  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-15 17:21:00.471  6957  7416 D BluetoothAdapterProperties: Setting state to 10
08-15 17:21:00.471  6957  7416 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-15 17:21:00.471  6957  6957 D BluetoothMapService: cleanup()
08-15 17:21:00.471  6957  6957 D BluetoothMapService: MAP Service closeService in
08-15 17:21:00.471  6957  6957 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-15 17:21:00.471  6957  6957 V BluetoothMapService: MAP Service closeService out
08-15 17:21:00.472  1036  1118 D BluetoothManagerService: Message: 60
08-15 17:21:00.472  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-15 17:21:00.472  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-15 17:21:00.473  6957  7416 I BluetoothAdapterState: Entering OffState
08-15 17:21:00.473  6840  6857 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 17:21:00.474  6840  6857 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 17:21:00.476  6840  6857 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-15 17:21:00.479  6840  6857 D BluetoothMap: onBluetoothStateChange: up=false
08-15 17:21:00.480  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 17:21:00.480  6840  6857 D BluetoothPbap: onBluetoothStateChange: up=false
08-15 17:21:00.481  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 17:21:00.481  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-15 17:21:00.481  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 17:21:00.482  6840  6857 D BluetoothPan: onBluetoothStateChange on: false
08-15 17:21:00.483  1851  4405 D BluetoothHeadset: onBluetoothStateChange: up=false
08-15 17:21:00.484  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-15 17:21:00.484  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-15 17:21:00.485  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-15 17:21:00.485  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-15 17:21:00.486  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@24798d7a mBinding = false
08-15 17:21:00.488  1036  1118 D BluetoothManagerService: Sending unbind request.
,08-15 17:21:00.495  6957  7420 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-15 17:21:00.497  6957  7418 E BluetoothAdapterService(363924699): Repeated wake lock release; aborting release: bluedroid_timer
08-15 17:21:00.497  6957  7418 E GKI_LINUX: alarm_service_reschedule unable to release wake lock with no timers: 1
08-15 17:21:00.498  6957  6957 I GKI_LINUX: GKI_exit_task 1 done
08-15 17:21:00.498  6957  6957 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-15 17:21:00.499  6957  6957 I BluetoothServiceJni: cleanupNative: return from cleanup
08-15 17:21:00.499  6957  6957 I art     : --- WEIRD: removing null entry 248
08-15 17:21:00.499  6957  6957 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-15 17:21:00.499  6957  6957 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-15 17:21:00.500  6957  6957 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-15 17:21:00.503  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-15 17:21:00.505  6957  6957 I art     : System.exit called, status: 0
08-15 17:21:00.505  6957  6957 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-15 17:21:00.517  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:00.517  1941  2137 D LGBluetoothAPIService: Message: 2
08-15 17:21:00.517  1941  2137 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@104303ba mBinding = false
08-15 17:21:00.517  1941  2137 D LGBluetoothAPIService: Sending unbind request.
,08-15 17:21:00.520  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 17:21:00.527  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:00.528  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 17:21:00.533  6840  6840 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-15 17:21:00.533  6840  6840 D LGBluetoothEventManager: [BTUI] clear device connection state
08-15 17:21:00.533  1036  1603 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-15 17:21:00.534  1036  1603 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-15 17:21:00.535  1036  1603 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
08-15 17:21:00.535  1036  1603 W ActivityManager: android.os.TransactionTooLargeException
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-15 17:21:00.535  1036  1603 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-15 17:21:00.535   313  2147 V AudioFlinger: 6957 died, releasing its sessions
08-15 17:21:00.535   313  2147 V AudioFlinger:  pid 1851 @ 0
08-15 17:21:00.535   313  2147 V AudioFlinger:  pid 3396 @ 1
08-15 17:21:00.535   313  2147 V AudioFlinger:  pid 3396 @ 2
08-15 17:21:00.537  6840  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-15 17:21:00.540  1604  1604 D BluetoothAdapter: 414211266: getState() :  mService = null. Returning STATE_OFF
08-15 17:21:00.540  1604  1604 D BluetoothAdapter: 414211266: getState() :  mService = null. Returning STATE_OFF
08-15 17:21:00.586  1036  1956 I ActivityManager: Process com.android.bluetooth (pid 6957) has died
08-15 17:21:00.587  1036  1956 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-15 17:21:00.592  6840  6840 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-15 17:21:00.648  1036  1956 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7603 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-15 17:21:00.651  6840  6840 D DockEventReceiver: finishStartingService: stopping service
,08-15 17:21:00.719  7603  7603 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-15 17:21:00.720  7603  7603 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 17:21:00.721  7603  7603 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-15 17:21:00.722  7603  7603 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-15 17:21:00.749  7603  7603 D BluetoothAdapterApp: Loading JNI Library
,08-15 17:21:00.784  7603  7603 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3e4b7463 Instance Count = 1
,08-15 17:21:00.790  7603  7603 D BluetoothAdapterApp: onCreate
08-15 17:21:00.812  7603  7603 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-15 17:21:00.813  7603  7603 D ProfileConfigQcom: Adding HeadsetService
08-15 17:21:00.815  7603  7603 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-15 17:21:00.815  7603  7603 D ProfileConfigQcom: Adding A2dpService
08-15 17:21:00.816  7603  7603 D ProfileConfigQcom: [BTUI] HidService is supported
08-15 17:21:00.816  7603  7603 D ProfileConfigQcom: Adding HidService
08-15 17:21:00.816  7603  7603 D ProfileConfigQcom: [BTUI] HealthService is supported
08-15 17:21:00.816  7603  7603 D ProfileConfigQcom: Adding HealthService
,08-15 17:21:00.817  7603  7603 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-15 17:21:00.817  7603  7603 D ProfileConfigQcom: [BTUI] PanService is supported
08-15 17:21:00.818  7603  7603 D ProfileConfigQcom: Adding PanService
08-15 17:21:00.818  7603  7603 D ProfileConfigQcom: [BTUI] GattService is supported
08-15 17:21:00.818  7603  7603 D ProfileConfigQcom: Adding GattService
08-15 17:21:00.818  7603  7603 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-15 17:21:00.818  7603  7603 D ProfileConfigQcom: Adding BluetoothMapService
08-15 17:21:00.819  7603  7603 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-15 17:21:00.820  7603  7603 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 17:21:00.821  7603  7603 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:00.821  7603  7603 V BluetoothPbapReceiver: ***********state = 10
08-15 17:21:00.823  7603  7603 V LGMDMManagerInternal: Create singleton instance
08-15 17:21:00.889  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-15 17:21:00.893  1036  1905 I ActivityManager: Killing 6640:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-15 17:21:00.893  6840  6840 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-15 17:21:00.909  6892  6892 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-15 17:21:00.910  6892  6892 W System.err: android.os.DeadObjectException
08-15 17:21:00.911  6892  6892 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-15 17:21:00.911  6892  6892 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-15 17:21:00.911  6892  6892 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-15 17:21:00.911  6892  6892 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-15 17:21:00.911  6892  6892 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-15 17:21:00.911  6892  6892 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-15 17:21:00.911  6892  6892 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 17:21:00.912  6892  6892 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 17:21:00.912  6892  6892 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:00.912  6892  6892 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:00.912  6892  6892 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:00.912  6892  6892 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:00.912  6892  6892 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:00.912  6892  6892 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:00.913  6892  6892 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-15 17:21:00.913  6892  6892 W System.err: android.os.DeadObjectException
08-15 17:21:00.913  6892  6892 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-15 17:21:00.914  6892  6892 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-15 17:21:00.914  6892  6892 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-15 17:21:00.914  6892  6892 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-15 17:21:00.914  6892  6892 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-15 17:21:00.914  6892  6892 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-15 17:21:00.914  6892  6892 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 17:21:00.914  6892  6892 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 17:21:00.914  6892  6892 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:00.914  6892  6892 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:00.915  6892  6892 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:00.915  6892  6892 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:00.915  6892  6892 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:00.915  6892  6892 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:00.915  6892  6892 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,08-15 17:21:00.916  6892  6892 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-15 17:21:01.001  1036  1940 W libprocessgroup: failed to open /acct/uid_1000/pid_6640/cgroup.procs: No such file or directory
08-15 17:21:01.002  1036  1940 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-15 17:21:01.013  6892  6892 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,08-15 17:21:01.014  6892  6892 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-15 17:21:01.084  1036  1976 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7631 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-15 17:21:01.090  6892  6892 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-15 17:21:01.101  6840  6840 D BluetoothPermissionRequest: onReceive
08-15 17:21:01.103  6840  6840 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-15 17:21:01.103  6840  6840 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-15 17:21:01.106  6840  6840 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 17:21:01.113  7603  7603 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-15 17:21:01.117  7603  7603 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-15 17:21:01.123  7603  7603 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 17:21:01.123  7603  7603 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 17:21:01.123  7603  7603 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 17:21:01.125  7603  7603 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:01.125  7603  7603 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-15 17:21:01.130  6909  6909 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-15 17:21:01.169  7631  7631 D UEI.SmartControl: Quickset Services start...
,08-15 17:21:01.172  7631  7631 I UEI.SmartControl: Manufacture = LGE
08-15 17:21:01.172  7631  7631 D UEI.SmartControl: Id = LGNevo
08-15 17:21:01.173  7631  7631 D UEI.SmartControl: File observer start...
08-15 17:21:01.174  7631  7631 E UEI.SmartControl: IR Port is disabled: false
08-15 17:21:01.174  7631  7631 D UEI.SmartControl: Starting file observer...
08-15 17:21:01.174  7631  7631 D UEI.SmartControl: Extracting JNI libs...
08-15 17:21:01.175  7631  7631 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-15 17:21:01.292  7631  7631 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-15 17:21:01.292  7631  7631 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-15 17:21:01.292  7631  7631 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-15 17:21:01.333  7631  7631 I UEI.SmartControl: --- Selecting new region: 6
,08-15 17:21:01.335  7631  7631 I UEI.SmartControl: Model = LG-D855
08-15 17:21:01.338  7631  7631 D UEI.SmartControl: QS Service created
08-15 17:21:01.354  7631  7631 I UEI.SmartControl: Service initServices...
,08-15 17:21:01.365  7631  7631 D UEI.SmartControl: QS start get config
,08-15 17:21:01.436  7631  7631 D UEI.SmartControl: Loading JNI Libs...
,08-15 17:21:01.739  7631  7631 I UEI.SmartControl: Supports setup maps: true
,08-15 17:21:01.742  7631  7631 D UEI.SmartControl: QS start statue = true Error code = 0
,08-15 17:21:01.743  7631  7631 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-15 17:21:01.743  7631  7631 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-15 17:21:01.743  7631  7631 I UEI.SmartControl: ### init IR Blaster...
08-15 17:21:01.748  7631  7631 D serial_port: Configuring serial port
08-15 17:21:01.752  7631  7631 E UEI.SmartControl: UEIBLaster setting for 616
08-15 17:21:01.752  7631  7631 I UEI.SmartControl: Setting serial record hearder size = 2
08-15 17:21:01.752  7631  7631 I UEI.SmartControl: configuring settings for MAXQ616
08-15 17:21:01.752  7631  7631 I UEI.SmartControl: Get version...
08-15 17:21:01.769  7631  7652 D UEI.SmartControl: serial port data available: 21
,08-15 17:21:01.795  7631  7631 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-15 17:21:01.795  7631  7631 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-15 17:21:01.795  7631  7631 I UEI.SmartControl: QS saving settings...
08-15 17:21:01.796  7631  7631 D UEI.SmartControl: IR Blaster version: 25672567
,08-15 17:21:01.811  7631  7652 D UEI.SmartControl: serial port data available: 4
,08-15 17:21:01.849  7631  7655 I UEI.SmartControl: Device manager: loading config....
,08-15 17:21:01.857  7631  7655 D UEI.SmartControl: ----------- loading internal config...
08-15 17:21:01.858  7631  7631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-15 17:21:01.863  7631  7631 E UEI.SmartControl: Services init done
08-15 17:21:01.863  7631  7631 D UEI.SmartControl: QS Service init finished
08-15 17:21:01.865  7631  7631 D UEI.SmartControl: QS Service version name: 2.1.91
08-15 17:21:01.865  7631  7631 D UEI.SmartControl: QS Service version code: 201091
08-15 17:21:01.867  7631  7631 D UEI.SmartControl: Service requested: Control
,08-15 17:21:01.878  7631  7655 E UEI.SmartControl: Loading SETTINGS...
,08-15 17:21:01.878  7631  7631 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-15 17:21:01.888  6892  6892 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-15 17:21:01.888  7631  7646 I UEI.SmartControl: ------ IControl API: 11
08-15 17:21:01.890  7631  7646 I UEI.SmartControl: Registering callback...
08-15 17:21:01.892  7631  7647 I UEI.SmartControl: ------ IControl API: 19
08-15 17:21:01.892  1036  2032 I ActivityManager: Killing 6892:com.lge.qremote/u0a112 (adj 15): empty #17
08-15 17:21:01.894  7631  7647 I UEI.SmartControl: Registering Services Ready callback...
08-15 17:21:01.898  7631  7655 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-15 17:21:01.908  7631  7654 I UEI.SmartControl: Notify AllClients services are ready: 0
08-15 17:21:01.908  7631  7654 D UEI.SmartControl: -----service ready thread exits
08-15 17:21:01.927  7631  7631 D UEI.SmartControl: Internal service binding...
08-15 17:21:01.927  1036  1603 W libprocessgroup: failed to open /acct/uid_10112/pid_6892/cgroup.procs: No such file or directory
,08-15 17:21:02.544  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-15 17:21:02.547  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:21:02.547  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:02.597  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-15 17:21:02.644  1036  1104 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7660 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-15 17:21:02.651  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-15 17:21:02.652  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-15 17:21:02.682  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-15 17:21:02.701  1036  1036 D administrator: Handling package changes for user 0
,08-15 17:21:02.711  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 17:21:02.739  7660  7660 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-15 17:21:02.827  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-15 17:21:02.827  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-15 17:21:02.843  7660  7660 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:21:02.844  7660  7660 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:21:02.881  1036  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-15 17:21:02.887  1036  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-15 17:21:02.894  2502  2502 V GmsNetworkLocationProvi: DISABLE
08-15 17:21:02.895  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-15 17:21:02.920  1036  1101 D LocationProviderProxy: applying state to connected service
,08-15 17:21:02.924  2502  2502 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-15 17:21:02.971  7660  7705 I Babel   : MmsConfig: mnc/mcc: 0/0
08-15 17:21:02.972  7660  7705 I Babel   : MmsConfig.loadMmsSettings
08-15 17:21:02.978  7660  7705 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-15 17:21:02.978  7660  7705 I Babel   : MmsConfig.loadFromDatabase
08-15 17:21:02.993  7660  7703 W AudioCapabilities: Unsupported mime audio/evrc
,08-15 17:21:02.994  7660  7703 W AudioCapabilities: Unsupported mime audio/qcelp
,08-15 17:21:02.995  7660  7703 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-15 17:21:03.003  7660  7703 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-15 17:21:03.005  7660  7703 W AudioCapabilities: Unsupported mime audio/qcelp
08-15 17:21:03.008  7660  7705 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-15 17:21:03.008  7660  7705 I Babel   : MmsConfig.loadFromResources
08-15 17:21:03.008  7660  7703 W AudioCapabilities: Unsupported mime audio/evrc
,08-15 17:21:03.017  7660  7705 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-15 17:21:03.017  7660  7705 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-15 17:21:03.024  7660  7660 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-15 17:21:03.038  7660  7703 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-15 17:21:03.041  7660  7703 W VideoCapabilities: Unsupported mime video/divx
08-15 17:21:03.043  7660  7703 W VideoCapabilities: Unsupported mime video/divx311
08-15 17:21:03.045  7660  7703 W VideoCapabilities: Unsupported mime video/divx4
08-15 17:21:03.046  1816  7707 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-15 17:21:03.046  1816  7707 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-15 17:21:03.049  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
,08-15 17:21:03.055  7660  7703 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-15 17:21:03.056  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c24f5d5
08-15 17:21:03.056  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 17:21:03.056  7015  7015 D AppUp4:CustFacade: isPhone : true
08-15 17:21:03.057  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
08-15 17:21:03.057  7015  7015 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-15 17:21:03.057  1816  4751 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-15 17:21:03.089  7660  7703 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-15 17:21:03.093  7660  7703 W AudioCapabilities: Unsupported mime audio/eac3
,08-15 17:21:03.094  7660  7703 W AudioCapabilities: Unsupported mime audio/ac3
08-15 17:21:03.095  7660  7703 W AudioCapabilities: Unsupported mime audio/g726
08-15 17:21:03.096  7660  7703 W AudioCapabilities: Unsupported mime audio/wma-voice
08-15 17:21:03.097  7660  7703 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-15 17:21:03.098  7660  7703 W AudioCapabilities: Unsupported mime audio/adpcm
08-15 17:21:03.100  7660  7703 W VideoCapabilities: Unsupported mime video/theora
08-15 17:21:03.102  7660  7703 W VideoCapabilities: Unsupported mime video/mjpg
08-15 17:21:03.107  1036  1976 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7711 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-15 17:21:03.152  1036  1905 I ActivityManager: Killing 7060:com.lge.email/u0a23 (adj 15): empty #17
,08-15 17:21:03.154  7711  7711 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 17:21:03.154  7711  7711 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 17:21:03.154  7711  7711 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-15 17:21:03.155  7711  7711 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-15 17:21:03.156  7711  7711 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-15 17:21:03.230  1036  1902 W libprocessgroup: failed to open /acct/uid_10023/pid_7060/cgroup.procs: No such file or directory
,08-15 17:21:03.277  7711  7711 I SystemConfig: BUILD Country: EU
08-15 17:21:03.277  7711  7711 I SystemConfig: BUILD Operator: OPEN
,08-15 17:21:03.329  1036  1052 I ActivityManager: Killing 6938:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-15 17:21:03.437  7711  7729 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-15 17:21:03.437  7711  7729 I SystemConfig: existFile = false
,08-15 17:21:03.437  7711  7729 I SystemConfig: canReadFile = false
08-15 17:21:03.437  7711  7729 I SystemConfig: systemFeature RCS result false
08-15 17:21:03.437  7711  7729 D SystemConfig: refreshRcsSupport() :false
08-15 17:21:03.465  1036  1956 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7738 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-15 17:21:03.467  1036  1905 W libprocessgroup: failed to open /acct/uid_10026/pid_6938/cgroup.procs: No such file or directory
,08-15 17:21:03.502  7738  7738 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 17:21:03.502  7738  7738 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-15 17:21:03.502  7738  7738 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-15 17:21:03.502  7738  7738 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-15 17:21:03.551  7738  7738 I AppConfig: Total System Memory = 2995761152
,08-15 17:21:03.559  7738  7738 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-15 17:21:03.615  1036  2025 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7761 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-15 17:21:03.616  1036  2025 I ActivityManager: Killing 6423:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-15 17:21:03.729  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6423/cgroup.procs: No such file or directory
,08-15 17:21:03.971  7761  7761 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-15 17:21:04.049  7761  7761 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:21:04.050  7761  7761 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:21:04.110  7761  7761 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-15 17:21:04.132  7761  7761 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-15 17:21:04.133  7761  7761 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-15 17:21:04.151  7761  7761 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-15 17:21:04.151  7761  7761 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-15 17:21:04.175  1036  2012 I ActivityManager: Killing 7090:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-15 17:21:04.237  1036  2032 W libprocessgroup: failed to open /acct/uid_10046/pid_7090/cgroup.procs: No such file or directory
,08-15 17:21:04.244  4570  7800 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-15 17:21:04.254  2842  2862 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-15 17:21:04.257  2842  2862 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@22d6aff0 on behalf of 7761
,08-15 17:21:04.288  1036  1052 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7801 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-15 17:21:04.301  7761  7761 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-15 17:21:04.336  7761  7761 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-15 17:21:04.384  7801  7801 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-15 17:21:04.412  7801  7801 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-15 17:21:04.412  7801  7801 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-15 17:21:04.412  7801  7801 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-15 17:21:04.412  7801  7801 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,08-15 17:21:04.412  7801  7801 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-15 17:21:04.412  7801  7801 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-15 17:21:04.432  1036  1976 I ActivityManager: Killing 7109:com.android.chrome/u0a57 (adj 15): empty #17
,08-15 17:21:04.463  1036  1051 W libprocessgroup: failed to open /acct/uid_10057/pid_7109/cgroup.procs: No such file or directory
,08-15 17:21:04.680  1036  1876 V SIM_STK : Menu title from STK is T-Mobile
,08-15 17:21:04.719  4570  7800 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 475 ms] updated apps [took 475 ms] 
,08-15 17:21:05.256  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2be7bafa type 2 when 352179 com.google.android.gms} when 352179
,08-15 17:21:05.273   308  7829 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-15 17:21:05.280  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-15 17:21:05.653  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:05.653  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c3ebeba added. We now have 6 listener(s)
08-15 17:21:05.653  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 17:21:05.668  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:05.668  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22b0116b added. We now have 7 listener(s)
08-15 17:21:05.668  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:05.669  6708  6776 I System.out: IsBluetoothEnabled
08-15 17:21:05.670  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:05.670  1036  1956 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-15 17:21:05.671  1036  1118 D BluetoothManagerService: Message: 2
,08-15 17:21:05.676  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:05.678  1036  1603 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:05.678  1036  1603 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-15 17:21:05.707  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 17:21:05.708  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 17:21:05.708  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-15 17:21:05.711  1036  1118 D BluetoothManagerService: Message: 1
08-15 17:21:05.711  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-15 17:21:05.778  1036  1118 D BluetoothManagerService: Message: 20
08-15 17:21:05.778  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5b27487:true
,08-15 17:21:05.781  7603  7603 D BluetoothAdapterState: make
08-15 17:21:05.786  7603  7603 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-15 17:21:05.786  7603  7833 I BluetoothAdapterState: Entering OffState
08-15 17:21:05.786  7603  7603 I bluedroid-qcom: init
08-15 17:21:05.787  7603  7603 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-15 17:21:05.788  7603  7603 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-15 17:21:05.788  7603  7603 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-15 17:21:05.788  7603  7603 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-15 17:21:05.788  7603  7603 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-15 17:21:05.790  7603  7603 I bluedroid-qcom: get_profile_interface socket
08-15 17:21:05.790  7603  7603 I bluedroid-qcom: get_profile_interface map_client
,08-15 17:21:05.793  7603  7837 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-15 17:21:05.778  7836  7836 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:05.788  7836  7836 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:05.805  7836  7836 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-15 17:21:05.805  7836  7836 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-15 17:21:05.805  7836  7836 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-15 17:21:05.811  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-15 17:21:05.812  1036  1118 D BluetoothManagerService: Message: 40
08-15 17:21:05.812  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-15 17:21:05.814  7603  7620 I bluedroid-qcom: config_hci_snoop_log
08-15 17:21:05.818  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-15 17:21:05.819  7836  7836 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-15 17:21:05.818  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-15 17:21:05.825  7603  7837 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-15 17:21:05.826  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-15 17:21:05.826  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-15 17:21:05.827  7603  7837 D BluetoothAdapterProperties: Name is: G3
08-15 17:21:05.827  7836  7836 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-15 17:21:05.827  7836  7836 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-15 17:21:05.828  7603  7833 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-15 17:21:05.828  7603  7833 D BluetoothAdapterProperties: Setting state to 11
08-15 17:21:05.828  7603  7833 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-15 17:21:05.829  7603  7833 I LGBluetoothServiceJni: classInitNative: succeeds
08-15 17:21:05.831  1036  1118 D BluetoothManagerService: Message: 60
08-15 17:21:05.831  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,08-15 17:21:05.831  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-15 17:21:05.832  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:05.832  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-15 17:21:05.835  6840  6840 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-15 17:21:05.836  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:05.836  7603  7833 D BluetoothBondStateMachine: make
08-15 17:21:05.839  7603  7603 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 17:21:05.839  7603  7603 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:05.839  7603  7603 V BluetoothPbapReceiver: ***********state = 11
08-15 17:21:05.839  7603  7833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:05.839  7603  7833 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-15 17:21:05.839  7603  7833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:05.839  7603  7833 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-15 17:21:05.840  7603  7833 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-15 17:21:05.842  7603  7855 I BluetoothBondStateMachine: StableState(): Entering Off State
08-15 17:21:05.842  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 17:21:05.843  7603  7833 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:21:05.853  7603  7833 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:21:05.853  7603  7603 D HeadsetService: Received start request. Starting profile...
,08-15 17:21:05.853  7603  7603 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-15 17:21:05.854  7603  7603 D LGBluetoothHfpAdapter: Version 1.6
08-15 17:21:05.855  7603  7603 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-15 17:21:05.856  7603  7603 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-15 17:21:05.856  7603  7603 D HeadsetStateMachine: make
08-15 17:21:05.859  6840  6840 D BluetoothPermissionRequest: onReceive
08-15 17:21:05.863  6840  6840 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-15 17:21:05.865  7603  7833 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:21:05.869  7603  7833 E BluetoothAdapterService: File transfer profiles supported!!
,08-15 17:21:05.875  7603  7833 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:21:05.877  7603  7603 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:21:05.877  7603  7603 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 17:21:05.880  7603  7603 D HeadsetStateMachine: max_hf_connections = 1
08-15 17:21:05.880  7603  7603 I bluedroid-qcom: get_profile_interface handsfree
08-15 17:21:05.880  7603  7833 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:21:05.881  7603  7603 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-15 17:21:05.881   313  1397 V AudioPolicyService: registerClient() client 0xb558a4a0, uid 1002
08-15 17:21:05.881   313  1397 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-15 17:21:05.881   313  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 17:21:05.881   313  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 17:21:05.882  7603  7603 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-15 17:21:05.882   313   313 V AudioFlinger: registerClient() client 0xb55815e0, pid 7603
08-15 17:21:05.883   313  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:21:05.883   313  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:21:05.883  1604  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:21:05.883  1604  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:21:05.883  3396  3412 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:21:05.883  3396  3412 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:21:05.884  1036  2032 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:21:05.884  1036  2032 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:21:05.884  7603  7853 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:21:05.884  1851  2446 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-15 17:21:05.884  1851  2446 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-15 17:21:05.884   313  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:21:05.884   313  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 17:21:05.884  1036  1876 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:21:05.884  1036  1876 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 17:21:05.884  3396  3411 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:21:05.884  3396  3411 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 17:21:05.884  1604  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:21:05.884  1604  1624 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 17:21:05.884  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:21:05.884  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-15 17:21:05.885  7603  7853 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-15 17:21:05.885  7603  7853 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-15 17:21:05.885  7603  7853 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-15 17:21:05.885  7603  7603 V ToneGenerator: Create Track: 0xb4928080
08-15 17:21:05.885  7603  7603 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-15 17:21:05.885  7603  7603 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-15 17:21:05.885   313  2147 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-15 17:21:05.885   313  2147 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-15 17:21:05.885   313  2147 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 17:21:05.885   313  2147 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 17:21:05.886   313  1397 I AudioFlinger: isAudioPlaybackHookOn() false
08-15 17:21:05.887   313  2148 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-15 17:21:05.887   313  2148 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-15 17:21:05.887   313  2148 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-15 17:21:05.887   313  2148 V AudioPolicyManagerEx: getOutput() returns output 2
08-15 17:21:05.887  7603  7603 V AudioSystem: getLatency() output 2, latency 50
08-15 17:21:05.887  7603  7603 V AudioSystem: getFrameCount() output 2, frameCount 960
08-15 17:21:05.887  7603  7603 V AudioTrack: createTrack_l() output 2 afLatency 50
08-15 17:21:05.887   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-15 17,:21:05.887   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-15 17:21:05.887   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-15 17:21:05.887   313   313 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-15 17:21:05.887   313   313 V AudioFlinger: createTrack() lSessionId: 23
08-15 17:21:05.888  7603  7603 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-15 17:21:05.889   313   313 V AudioFlinger: acquiring 23 from 7603, for 7603
08-15 17:21:05.889   313   313 V AudioFlinger:  added new entry for 23
08-15 17:21:05.889  7603  7833 E BluetoothAdapterService: File transfer profiles supported!!
08-15 17:21:05.889  7603  7603 V ToneGenerator: ToneGenerator INIT OK, time: 352832
08-15 17:21:05.889  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:05.891  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:05.891  7603  7856 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-15 17:21:05.892  7603  7856 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-15 17:21:05.892  7603  7856 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-15 17:21:05.892  7603  7856 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-15 17:21:05.892   313  1398 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7603
,08-15 17:21:05.892   313  1398 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000,
08-15 17:21:05.892   313  1398 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-15 17:21:05.892   313  1398 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
,08-15 17:21:05.892   313  1398 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-15 17:21:05.892   313  1398 V voice   : voice_set_parameters: exit with code(0)
08-15 17:21:05.892   313  1398 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-15 17:21:05.892   313  1398 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
,08-15 17:21:05.893   313  1398 V msm8974_platform: platform_set_parameters: exit with code(0)
08-15 17:21:05.893   313  1398 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-15 17:21:05.893   313  1398 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-15 17:21:05.893   313  1398 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-15 17:21:05.894  7603  7603 D A2dpService: Received start request. Starting profile...
08-15 17:21:05.896  7603  7603 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-15 17:21:05.897  7603  7603 V Avrcp   : make
08-15 17:21:05.897  7603  7603 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-15 17:21:05.897  7603  7603 I bluedroid-qcom: get_profile_interface avrcp
08-15 17:21:05.898  7603  7856 V ToneGenerator: ToneGenerator destructor
08-15 17:21:05.898  7603  7856 V ToneGenerator: stopTone
08-15 17:21:05.898  7603  7856 V ToneGenerator: Delete Track: 0xb4928080
,08-15 17:21:05.899  7603  7856 V AudioTrack: ~AudioTrack, releasing session id from 7603 on behalf of 7603
08-15 17:21:05.899   313  2148 V AudioPolicyService: AudioCommandThread() adding release output 2
08-15 17:21:05.899   313  2148 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-15 17:21:05.899   313  1274 V AudioPolicyService: AudioCommandThread() waking up
08-15 17:21:05.899   313  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
08-15 17:21:05.899   313  1274 V AudioPolicyManager: releaseOutput() 2
08-15 17:21:05.899   313  1274 V AudioPolicyService: AudioCommandThread() going to sleep
,08-15 17:21:05.899   313  1397 V AudioFlinger: releasing 23 from 7603 for 7603
08-15 17:21:05.899   313  1397 V AudioFlinger:  decremented refcount to 0
08-15 17:21:05.899   313  2148 V AudioFlinger: PlaybackThread::Track destructor
08-15 17:21:05.899   313  1397 V AudioFlinger: purging stale effects
08-15 17:21:05.899   313  2148 V AudioFlinger: removeClient_l() pid 7603, calling pid 313
08-15 17:21:05.903  7603  7603 V AudioManager: registerRemoteController: size of Media player list: 0
08-15 17:21:05.904  7603  7833 V LGMDMManager: Create singleton instance
,08-15 17:21:05.905  7603  7603 E AudioManager: No RCC entry present to update
08-15 17:21:05.905  7603  7603 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-15 17:21:05.906  7603  7833 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-15 17:21:05.907  7603  7603 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-15 17:21:05.907  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-15 17:21:05.907  7603  7603 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-15 17:21:05.911  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-15 17:21:06.022  1036  2032 V SIM_STK : Menu title from STK is T-Mobile
08-15 17:21:06.022  1036  2032 V SIM_STK : Menu title from STK is T-Mobile
,08-15 17:21:06.147  1036  1956 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-15 17:21:06.158  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 17:21:06.164  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-15 17:21:06.165  7603  7603 I BluetoothA2dpServiceJni: classInitNative
08-15 17:21:06.165  7603  7603 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-15 17:21:06.165  7603  7603 D A2dpStateMachine: make
08-15 17:21:06.166  7603  7603 I bluedroid-qcom: get_profile_interface a2dp
08-15 17:21:06.166  7603  7865 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-15 17:21:06.168  7603  7603 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-15 17:21:06.168  7603  7603 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-15 17:21:06.169  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:06.169  7603  7864 D A2dpStateMachine: Enter Disconnected: -2
08-15 17:21:06.171  7603  7603 I BluetoothHidServiceJni: classInitNative: succeeds
08-15 17:21:06.172  7603  7603 D HidService: Received start request. Starting profile...
08-15 17:21:06.172  7603  7603 I bluedroid-qcom: get_profile_interface hidhost
08-15 17:21:06.172  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:06.173  7603  7603 I BluetoothHealthServiceJni: classInitNative: succeeds
08-15 17:21:06.174  7603  7603 D HealthService: Received start request. Starting profile...
08-15 17:21:06.176  7603  7603 I bluedroid-qcom: get_profile_interface health
08-15 17:21:06.176  7603  7603 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-15 17:21:06.176  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:06.177  7603  7603 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-15 17:21:06.182  7603  7603 D PanService: Received start request. Starting profile...
08-15 17:21:06.182  7603  7603 D BluetoothPanServiceJni: initializeNative(L110): pan
08-15 17:21:06.182  7603  7603 I bluedroid-qcom: get_profile_interface pan
08-15 17:21:06.186  7603  7603 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-15 17:21:06.186  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:06.187  7603  7603 D HeadsetStateMachine: Proxy object connected
08-15 17:21:06.187  7603  7603 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-15 17:21:06.187  7603  7603 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-15 17:21:06.188  7603  7603 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-15 17:21:06.193  7603  7603 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-15 17:21:06.193  7603  7603 D BtGatt.GattService: Received start request. Starting profile...,
08-15 17:21:06.193  7603  7603 D BtGatt.GattService: start()
08-15 17:21:06.193  7603  7603 I bluedroid-qcom: get_profile_interface gatt
08-15 17:21:06.194  7603  7603 D BtGatt.AdvertiseManager: advertise manager created
08-15 17:21:06.198  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:06.198  7603  7856 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-15 17:21:06.199  7603  7856 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-15 17:21:06.199  7603  7856 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-15 17:21:06.201  7603  7603 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 17:21:06.202  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:06.203  7603  7603 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-15 17:21:06.203  7603  7603 V BluetoothMapService: BluetoothMapBinder()
08-15 17:21:06.205  7603  7603 D BluetoothMapService: Received start request. Starting profile...
08-15 17:21:06.205  7603  7603 D BluetoothMapService: start()
,08-15 17:21:06.208  7603  7603 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-15 17:21:06.208  7603  7603 D BluetoothMapEmailAppObserver: createReceiver()
08-15 17:21:06.209  7603  7603 D BluetoothMapEmailAppObserver: initObservers()
08-15 17:21:06.209  7603  7603 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-15 17:21:06.218  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
,08-15 17:21:06.220  7603  7603 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-15 17:21:06.221  7603  7603 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:06.224  7603  7603 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 17:21:06.226  7603  7603 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 17:21:06.226  7603  7603 V PanService: [BTUI] SIM Extra State :ABSENT
08-15 17:21:06.229  7603  7603 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-15 17:21:06.230  7603  7603 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-15 17:21:06.231  7603  7603 V BluetoothMapService: Handler(): got msg=1
,08-15 17:21:06.231  7603  7833 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-15 17:21:06.231  7603  7833 I bluedroid-qcom: enable
08-15 17:21:06.232  7603  7833 I bt_hci_bdroid: init
08-15 17:21:06.232  7603  7603 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 17:21:06.232  7603  7603 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 17:21:06.232  7603  7603 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 17:21:06.232  7603  7603 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:06.232  7603  7603 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-15 17:21:06.232  7603  7833 I bt_vendor: bt-vendor : init
08-15 17:21:06.233  7603  7833 I bt_vendor: bt-vendor : get_bt_soc_type
08-15 17:21:06.233  7603  7833 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-15 17:21:06.233  7603  7833 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-15 17:21:06.233  7603  7833 D bt_userial_mct: userial_init
08-15 17:21:06.233  7603  7872 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-15 17:21:06.233  7603  7872 I bt-btu  : btu_task pending for preload complete event
08-15 17:21:06.236  7603  7833 D bt_hci_bdroid: set_power 1
08-15 17:21:06.236  7603  7833 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-15 17:21:06.236  7603  7833 I bt_vendor: Starting hciattach daemon
08-15 17:21:06.236  7603  7833 I bt_vendor: try to set true
08-15 17:21:06.228  7875  7875 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:06.228  7875  7875 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:06.259  7876  7876 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-15 17:21:06.356  7883  7883 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-15 17:21:06.370  7884  7884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-15 17:21:06.397  7886  7886 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-15 17:21:06.419  7887  7887 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-15 17:21:06.437  7888  7888 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-15 17:21:06.454  7889  7889 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-15 17:21:06.486  7894  7894 I libmdmdetect: ESOC framework not supported
,08-15 17:21:06.488  7894  7894 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-15 17:21:06.499  7894  7894 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-15 17:21:06.499  7894  7894 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-15 17:21:06.499  7894  7894 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-15 17:21:06.499  7894  7894 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-15 17:21:06.499  7894  7894 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-15 17:21:06.499  7894  7894 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-15 17:21:06.499  7894  7894 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-15 17:21:06.546  7894  7895 E QC-QMI  : qmi_client [7894] 15: failed to locate client data
,08-15 17:21:06.547   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-15 17:21:06.547   470   470 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-15 17:21:06.592  7899  7899 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-15 17:21:06.607  7900  7900 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-15 17:21:06.638  7603  7833 I bt_vendor: bluetooth satus is on
08-15 17:21:06.638  7603  7833 D bt_hci_bdroid: preload
,08-15 17:21:06.642  7603  7874 D bt_userial_mct: userial_open(port:0)
08-15 17:21:06.642  7603  7874 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-15 17:21:06.646  7603  7874 I bt_vendor: Done intiailizing UART
08-15 17:21:06.647  7603  7874 I bt_vendor: Done intiailizing UART
08-15 17:21:06.647  7603  7874 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-15 17:21:06.647  7603  7874 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-15 17:21:06.648  7603  7872 I bt-btu  : btu_task received preload complete event
08-15 17:21:06.648  7603  7872 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-15 17:21:06.648  7603  7872 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-15 17:21:06.651  7603  7872 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-15 17:21:06.653  7603  7902 D bt_userial_mct: Entering userial_read_thread()
,08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_HCI
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_AVDT
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_AVRC
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_A2D
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_BNEP
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_BTM
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_GAP
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_PAN
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_SDP
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_GATT
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_SMP
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-15 17:21:06.664  7603  7872 I         : BTE_InitTraceLevels -- TRC_BTIF
08-15 17:21:06.728  7603  7872 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-15 17:21:06.728  7603  7872 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 
08-15 17:21:06.728  7603  7872 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
,08-15 17:21:06.763  7603  7837 E bt-btif : Calling BTA_HhEnable
08-15 17:21:06.764  7603  7837 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-15 17:21:06.764  7603  7837 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-15 17:21:06.773  7603  7872 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-15 17:21:06.773  7603  7872 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-15 17:21:06.773  7603  7872 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-15 17:21:06.774  7603  7872 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-15 17:21:06.774  7603  7872 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-15 17:21:06.780  7603  7837 D BluetoothAdapterProperties: Name is: G3
,08-15 17:21:06.790  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-15 17:21:06.790  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-15 17:21:06.792  7603  7837 D BluetoothAdapterProperties: Scan Mode:20
08-15 17:21:06.793  7603  7837 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 17:21:06.793  7603  7837 D bt_hci_bdroid: postload
08-15 17:21:06.794  7603  7874 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 17:21:06.797  7603  7872 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-15 17:21:06.801  7603  7872 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:21:06.801  7603  7872 W bt-smp  : Plain text(LSB ~ MSB) = a1 90 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 17:21:06.801  7603  7872 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 93 e0 c7 b4 ae 09 76 a0 0a 5b b6 4e e1 5b 83 
08-15 17:21:06.802  7603  7874 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 17:21:06.802  7603  7872 W bt-btm  : Stopping oneshot timer
08-15 17:21:06.803  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:06.803  7603  7837 D bte_conf: Device ID record 1 : primary
08-15 17:21:06.803  7603  7837 D bte_conf:   vendorId            = 00c4
08-15 17:21:06.803  7603  7837 D bte_conf:   vendorIdSource      = 0001
08-15 17:21:06.803  7603  7837 D bte_conf:   product             = 13a1
08-15 17:21:06.803  7603  7837 D bte_conf:   version             = 1000
08-15 17:21:06.803  7603  7837 D bte_conf:   clientExecutableURL = 
08-15 17:21:06.803  7603  7837 D bte_conf:   serviceDescription  = 
08-15 17:21:06.803  7603  7837 D bte_conf:   documentationURL    = 
08-15 17:21:06.803  7603  7837 D bte_conf: bte_load_did_conf no section named DID2.
08-15 17:21:06.805  7603  7874 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 17:21:06.806  7603  7874 D bt_hci_bdroid: Used up Tx Cmd credits
08-15 17:21:06.807  7603  7902 E bt_mct  : hci lib postload completed
08-15 17:21:06.810  7603  7833 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-15 17:21:06.810  7603  7833 D BluetoothAdapterProperties: ScanMode =  20
08-15 17:21:06.810  7603  7833 D BluetoothAdapterProperties: State =  11
08-15 17:21:06.810  7603  7833 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-15 17:21:06.810  7603  7833 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-15 17:21:06.811  7603  7833 D BluetoothAdapterProperties: Setting state to 12
08-15 17:21:06.811  7603  7833 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-15 17:21:06.814  7603  7837 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-15 17:21:06.815  7603  7837 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-15 17:21:06.808  7904  7904 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:06.808  7904  7904 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:06.827  1036  1118 D BluetoothManagerService: Message: 60
08-15 17:21:06.827  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-15 17:21:06.827  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-15 17:21:06.836  7603  7833 I BluetoothAdapterState: Entering On State
08-15 17:21:06.846  7603  7837 D BluetoothAdapterProperties: Discoverable Timeout:120
08-15 17:21:06.846  7603  7837 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-15 17:21:06.857  7603  7872 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:21:06.857  7603  7872 W bt-smp  : Plain text(LSB ~ MSB) = 48 c2 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 17:21:06.857  7603  7872 W bt-smp  : Encrypted text(LSB ~ MSB) = c6 13 cf 6d 7b d3 3f a2 16 3a 78 d9 df ef ef 6f 
08-15 17:21:06.858  7603  7872 W bt-btm  : Stopping oneshot timer
08-15 17:21:06.858  7603  7833 D LGBluetoothServiceAdapter: [BTUI] OnState
08-15 17:21:06.859  7603  7833 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-15 17:21:06.859  7603  7833 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-15 17:21:06.862  7603  7833 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-15 17:21:06.866  6840  7516 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 17:21:06.873  6840  7516 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-15 17:21:06.884  7603  7872 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:21:06.884  7603  7872 W bt-smp  : Plain text(LSB ~ MSB) = 9b df 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 17:21:06.884  7603  7872 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 4a 38 eb bd 67 0e ce 31 d3 d8 d9 aa dc e0 4b 
08-15 17:21:06.885  7603  7872 W bt-btm  : Stopping oneshot timer
08-15 17:21:06.886  7603  7833 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-15 17:21:06.891  6840  6856 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-15 17:21:06.896  7603  7872 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:21:06.896  7603  7872 W bt-smp  : Plain text(LSB ~ MSB) = 6a 6a 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-15 17:21:06.896  7603  7872 W bt-smp  : Encrypted text(LSB ~ MSB) = 47 4a 8c 0f 2c 8b e5 f3 ef 7f 5b cb ef ab d9 0a 
08-15 17:21:06.898  7603  7872 W bt-btm  : Stopping oneshot timer
,08-15 17:21:06.914  7631  7656 D UEI.SmartControl: Internal timer expired: 1
08-15 17:21:06.914  7631  7656 D UEI.SmartControl: unbind internal service
,08-15 17:21:06.940  7603  7872 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-15 17:21:06.940  7603  7872 W bt-smp  : Plain text(LSB ~ MSB) = 6b fb 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-15 17:21:06.941  7603  7872 W bt-smp  : Encrypted text(LSB ~ MSB) = c3 a6 39 5c 31 75 2e 3f da 0e c6 0e 1e 17 c4 64 
,08-15 17:21:06.941  7603  7872 W bt-btm  : Stopping oneshot timer
08-15 17:21:06.950  6840  6840 D BluetoothHeadset: Proxy object connected
08-15 17:21:06.950  6840  6840 D HeadsetProfile: Bluetooth service connected
,08-15 17:21:06.955  6840  6840 D BluetoothA2dp: Proxy object connected
,08-15 17:21:06.955  6840  6840 D A2dpProfile: Bluetooth service connected
08-15 17:21:06.960  7918  7918 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-15 17:21:07.067  1036  1118 I art     : Explicit concurrent mark sweep GC freed 27878(1377KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.520ms total 170.866ms
08-15 17:21:07.069  7631  7631 D UEI.SmartControl: Service.onUnbind: IControl
08-15 17:21:07.070  7631  7631 D UEI.SmartControl: Service.onDestroy
08-15 17:21:07.070  7631  7631 D UEI.SmartControl: Lock is in USE false
08-15 17:21:07.070  7631  7631 D UEI.SmartControl: unbind internal service
08-15 17:21:07.070  7631  7631 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@13cc1a51
08-15 17:21:07.070  6840  6857 D BluetoothMap: onBluetoothStateChange: up=true
,08-15 17:21:07.071  7631  7631 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-15 17:21:07.071  7631  7631 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-15 17:21:07.071  7631  7631 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-15 17:21:07.071  7631  7631 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-15 17:21:07.071  7631  7631 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-15 17:21:07.071  7631  7631 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-15 17:21:07.071  7631  7631 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-15 17:21:07.071  7631  7631 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-15 17:21:07.071  7631  7631 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-15 17:21:07.071  7631  7631 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:07.071  7631  7631 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:07.072  7631  7631 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:07.072  7631  7631 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:07.072  7631  7631 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:07.072  7631  7631 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:07.072  7631  7631 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@13cc1a51
08-15 17:21:07.072  7631  7631 D serial_port: close(fd = 25)
08-15 17:21:07.073  6840  6840 D BluetoothInputDevice: Proxy object connected
08-15 17:21:07.073  6840  6840 D HidProfile: Bluetooth service connected
08-15 17:21:07.074  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 17:21:07.075  1036  1036 D BluetoothHeadset: Proxy object connected
08-15 17:21:07.076  7631  7631 I UEI.SmartControl: Serial port is closed.
08-15 17:21:07.076  7631  7631 I UEI.SmartControl: Serial port is closed.
08-15 17:21:07.076  7631  7631 D UEI.SmartControl: Blaster closed
08-15 17:21:07.076  7631  7631 D UEI.SmartControl: Shut down QS...
08-15 17:21:07.076  6840  7516 D BluetoothPbap: onBluetoothStateChange: up=true
08-15 17:21:07.076  7631  7631 D UEI.SmartControl: Stopping QS lib
08-15 17:21:07.077  7631  7631 D UEI.SmartControl: QS lib stop result = true
08-15 17:21:07.077  7631  7631 D UEI.SmartControl: Stopped QS lib
08-15 17:21:07.077  7631  7631 D UEI.SmartControl: Stopped file observer...
08-15 17:21:07.077  7631  7631 D UEI.SmartControl: QS shutdown complete
08-15 17:21:07.080  1851  4405 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 17:21:07.081  1851  1851 D BluetoothHeadset: Proxy object connected
08-15 17:21:07.081  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-15 17:21:07.083  1036  1036 D BluetoothA2dp: Proxy object connected
08-15 17:21:07.083  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 17:21:07.083  6840  6840 D BluetoothMap: Proxy object connected
08-15 17:21:07.083  6840  6840 D MapProfile: Bluetooth service connected
08-15 17:21:07.084  6840  6840 D BluetoothMap: getConnectedDevices()
,08-15 17:21:07.087  7603  7621 V BluetoothMapService: getConnectedDevices()
08-15 17:21:07.088  1851  1851 D BluetoothHeadset: Proxy object connected
08-15 17:21:07.088  6840  6857 D BluetoothPan: onBluetoothStateChange on: true
08-15 17:21:07.088  6840  6857 D BluetoothPan: onBluetoothStateChange call bindService
08-15 17:21:07.090  1851  2446 D BluetoothHeadset: onBluetoothStateChange: up=true
08-15 17:21:07.090  6840  6840 D BluetoothPan: BluetoothPAN Proxy object connected
08-15 17:21:07.090  6840  6840 D PanProfile: Bluetooth service connected
08-15 17:21:07.092  1851  1851 D BluetoothHeadset: Proxy object connected
08-15 17:21:07.093  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-15 17:21:07.093  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-15 17:21:07.094  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-15 17:21:07.094  1036  1118 D BluetoothManagerService: Message: 40
08-15 17:21:07.095  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-15 17:21:07.097  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:07.097  1941  2137 D LGBluetoothAPIService: Message: 1
08-15 17:21:07.097  1941  2137 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-15 17:21:07.094  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-15 17:21:07.102  1941  2137 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-15 17:21:07.103  7603  7603 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:07.103  7603  7603 D BluetoothMapService: STATE_ON
08-15 17:21:07.103  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:21:07.103  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:07.103  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:07.103  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:21:07.103  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:07.103  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:21:07.103  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:21:07.103  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:21:07.104  7603  7603 D LGBluetoothAPIServer: [BTUI] onCreate()
08-15 17:21:07.105  7603  7603 D LGBluetoothAPIServer: [BTUI] onBind()
08-15 17:21:07.106  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-15 17:21:07.106  1941  2137 D LGBluetoothAPIService: Message: 100
08-15 17:21:07.106  1941  2137 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-15 17:21:07.106  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:21:07.108  6840  6840 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-15 17:21:07.109  6840  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-15 17:21:07.114  6840  6840 D DockEventReceiver: finishStartingService: stopping service
08-15 17:21:07.121  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:07.121  7603  7603 V BluetoothPbapService: Pbap Service onCreate
,08-15 17:21:07.121  7603  7603 V BluetoothPbapService: Starting PBAP service
08-15 17:21:07.122  7603  7603 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-15 17:21:07.122  7603  7603 V BluetoothMapService: Handler(): got msg=1
08-15 17:21:07.122  7603  7603 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-15 17:21:07.123  7603  7603 V BluetoothPbapService: Pbap Service onBind
08-15 17:21:07.124  6840  6840 D BluetoothPbap: Proxy object connected
08-15 17:21:07.124  6840  6840 D PbapServerProfile: Bluetooth service connected
08-15 17:21:07.124  7603  7603 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:07.124  7603  7603 V BluetoothPbapService: state: 12
08-15 17:21:07.124  7603  7603 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-15 17:21:07.124  7603  7603 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:07.124  7603  7603 V BluetoothPbapReceiver: ***********state = 12
08-15 17:21:07.124  7603  7930 D BluetoothMapMasInstance: MAS initSocket()
08-15 17:21:07.125  7603  7930 D BluetoothMapMasInstance:   masId = 00
08-15 17:21:07.125  7603  7930 D BluetoothMapMasInstance:   msgTypes = 0e
08-15 17:21:07.125  7603  7930 D BluetoothMapMasInstance:   masName = SMS/MMS
08-15 17:21:07.125  7603  7930 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-15 17:21:07.125  7603  7603 V BluetoothPbapService: Handler(): got msg=1
08-15 17:21:07.126  7603  7603 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-15 17:21:07.126  1036  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:07.127  2175  2175 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-15 17:21:07.127  7603  7931 V BluetoothPbapService: Pbap Service initSocket
08-15 17:21:07.127  1036  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:07.128  2175  2175 D c       : Getting all permits...
08-15 17:21:07.128  2175  2175 D a       : Opening database...
08-15 17:21:07.131  2175  2175 D a       : Opening database auth.proximity.permit_store...
08-15 17:21:07.132  2175  2175 D a       : Closing database...
08-15 17:21:07.133  7603  7930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:21:07.134  7603  7931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:21:07.136  7603  7930 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-15 17:21:07.136  7603  7930 V BluetoothMapMasInstance: Succeed to create listening socket 
08-15 17:21:07.136  7603  7930 D BluetoothMapMasInstance: Accepting socket connection...
,08-15 17:21:07.138  7603  7837 D BluetoothAdapterProperties: Scan Mode:21
08-15 17:21:07.138  7603  7837 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-15 17:21:07.139  7603  7931 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-15 17:21:07.139  7603  7931 V BluetoothPbapService: Succeed to create listening socket 
08-15 17:21:07.139  7603  7931 V BluetoothPbapService: Accepting socket connection...
08-15 17:21:07.142  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-15 17:21:07.143  6840  6840 D BluetoothPermissionRequest: onReceive
08-15 17:21:07.146  6840  6840 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-15 17:21:07.148  6840  6840 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-15 17:21:07.152  7603  7603 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-15 17:21:07.153  7603  7603 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-15 17:21:07.159  7603  7603 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-15 17:21:07.183  7603  7603 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-15 17:21:07.183  7603  7603 V BtOppService: onCreate
,08-15 17:21:07.186  7603  7603 V BluetoothOppNotification: send message
08-15 17:21:07.192  7603  7603 V BtOppService: Starting RfcommListener
08-15 17:21:07.200  7603  7603 D BluetoothOppPreference: Dumping Names:  
,08-15 17:21:07.200  7603  7603 D BluetoothOppPreference: {}
08-15 17:21:07.200  7603  7603 D BluetoothOppPreference: Dumping Channels:  
,08-15 17:21:07.200  7603  7603 D BluetoothOppPreference: {}
08-15 17:21:07.201  7603  7603 V BtOppService: onStartCommand
08-15 17:21:07.205  7603  7937 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-15 17:21:07.209  7603  7603 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:07.209  7603  7603 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-15 17:21:07.209  7603  7934 V BtOppService: Deleted complete outbound shares, number =  0
08-15 17:21:07.211  7603  7937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 17:21:07.212  7603  7603 V BluetoothOppNotification: new notify threadi!
08-15 17:21:07.215  7603  7603 V BluetoothOppNotification: send delay message
,08-15 17:21:07.215  7603  7934 V BtOppService: Deleted complete inbound failed shares, number = 0
08-15 17:21:07.215  7603  7937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@229171b4 on behalf of 
08-15 17:21:07.217  7603  7603 V BtOppService: start RfcommListener
08-15 17:21:07.217  7603  7937 V BluetoothOppNotification: update too frequent, put in queue
08-15 17:21:07.219  7603  7937 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-15 17:21:07.220  7603  7603 V BtOppService: RfcommListener started
08-15 17:21:07.221  7603  7603 V BtOppService: ContentObserver received notification
08-15 17:21:07.221  7603  7934 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-15 17:21:07.221  7603  7938 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-15 17:21:07.222  7603  7934 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dca71dd on behalf of 
08-15 17:21:07.223  7603  7939 V BtOppRfcommListener: Starting RFCOMM listener....
08-15 17:21:07.223  1036  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-15 17:21:07.224  7603  7939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:21:07.225  7603  7940 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-15 17:21:07.226  7603  7940 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 17:21:07.226  7603  7939 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-15 17:21:07.227  7603  7939 V BtOppRfcommListener: Started RFCOMM listener....
08-15 17:21:07.227  7603  7938 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bd20152 on behalf of 
08-15 17:21:07.227  7603  7939 I BtOppRfcommListener: Accept thread started.
08-15 17:21:07.227  7603  7939 V BtOppRfcommListener: Accepting connection...
08-15 17:21:07.227  7603  7938 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-15 17:21:07.228  7603  7940 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c3dbc23 on behalf of 
08-15 17:21:07.229  7603  7938 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-15 17:21:07.231  7603  7938 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@badf520 on behalf of 
08-15 17:21:07.231  7603  7938 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-15 17:21:07.233  7603  7938 V BluetoothOppNotification: outbound notification was removed.
08-15 17:21:07.234  7603  7938 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-15 17:21:07.235  7603  7940 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-15 17:21:07.236  7603  7938 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30814ed9 on behalf of 
08-15 17:21:07.239  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
08-15 17:21:07.239  7603  7603 V BluetoothFtpService: Ftp Service onCreate
08-15 17:21:07.239  7603  7603 I BluetoothFtpService: Ftp Service onCreate
08-15 17:21:07.239  7603  7938 V BluetoothOppNotification: inbound: succ-0  fail-0
08-15 17:21:07.240  7603  7603 V BluetoothFtpService: Ftp Service onStartCommand
08-15 17:21:07.240  7603  7603 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:07.240  7603  7603 V BluetoothFtpService: Starting Listening on sockets
08-15 17:21:07.240  7603  7603 V BtOppService: ContentObserver received notification
08-15 17:21:07.240  7603  7603 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-15 17:21:07.240  7603  7603 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-15 17:21:07.240  7603  7603 V BluetoothSapReceiver: SapReceiver onReceive 
08-15 17:21:07.241  7603  7603 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:07.241  7603  7603 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-15 17:21:07.241  7603  7603 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-15 17:21:07.241  7603  7938 V BluetoothOppNotification: inbound notification was removed.
08-15 17:21:07.242  7603  7938 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-15 17:21:07.242  7603  7941 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-15 17:21:07.243  7603  7603 V BluetoothFtpService: Handler(): got msg=1
08-15 17:21:07.243  7603  7941 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-15 17:21:07.243  7603  7603 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,08-15 17:21:07.243  7603  7603 V BluetoothFtpService: Ftp Service initSocket
08-15 17:21:07.246  1036  1603 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:07.247  7603  7941 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19a5f77f on behalf of 
08-15 17:21:07.247  7603  7938 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@284d434c on behalf of 
08-15 17:21:07.250  7603  7603 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-15 17:21:07.251  7603  7603 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
08-15 17:21:07.251  7603  7941 V BluetoothOppNotification: update too frequent, put in queue
08-15 17:21:07.251  7603  7603 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-15 17:21:07.253  7603  7942 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-15 17:21:07.255  7603  7941 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-15 17:21:07.282  7603  7603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15b10cdb
,08-15 17:21:07.283  7603  7603 V BluetoothSapService: Sap Service onCreate
,08-15 17:21:07.285  7603  7603 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-15 17:21:07.285  7603  7603 V BluetoothSapService: state: 12
08-15 17:21:07.285  7603  7603 V BluetoothSapService: Starting SAP server process
08-15 17:21:07.288  7603  7603 V BluetoothSapService: SAP Service startRfcommListenerThread
08-15 17:21:07.278  7943  7943 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:07.278  7943  7943 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:07.292  7603  7944 V BluetoothSapService: Sap Service initRfcommSocket
08-15 17:21:07.293  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:07.295  7603  7944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-15 17:21:07.298  7603  7944 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-15 17:21:07.298  7603  7944 V BluetoothSapService: Succeed to create listening socket 
08-15 17:21:07.298  7603  7944 V BluetoothSapService: Accepting socket connection...
08-15 17:21:07.312  7943  7943 V BT_SAP  : Event pipe created
08-15 17:21:07.312  7943  7943 V BT_SAP  : create_server_socket qcom.sap.server
08-15 17:21:07.312  7943  7943 V BT_SAP  : created socket fd 6
,08-15 17:21:07.747  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:21:07.747  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:07.747  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:07.747  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-15 17:21:07.747  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:07.747  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:21:07.747  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:21:07.747  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 17:21:07.752  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:21:07.754  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:07.754  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e0834c8 added. We now have 8 listener(s)
08-15 17:21:07.754  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:07.761  1036  1976 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 17:21:07.762  1036  1976 D WifiService: setWifiEnabled: false pid=6708, uid=10118
08-15 17:21:07.762  1036  1976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-15 17:21:07.769  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:07.770  1036  1940 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-15 17:21:07.771  1036  1940 D WifiService: setWifiEnabled: true pid=6708, uid=10118
08-15 17:21:07.771  1036  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-15 17:21:07.787  1036  1440 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-15 17:21:07.787  1036  1440 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-15 17:21:07.791  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-15 17:21:07.791  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-15 17:21:07.792  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-15 17:21:07.792  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-15 17:21:07.792  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-15 17:21:07.792  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-15 17:21:07.792  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-15 17:21:07.792  1036  1440 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-15 17:21:07.792  1036  1440 E WifiHW  : unknown target_country: EU , set to default
08-15 17:21:07.792  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-15 17:21:07.792  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-15 17:21:07.792  1036  1440 I WifiUtil: gEnableBmps=1
08-15 17:21:08.218  7603  7603 V BluetoothOppNotification: new notify threadi!
08-15 17:21:08.219  7603  7603 V BluetoothOppNotification: send delay message
,08-15 17:21:08.225  7603  7963 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-15 17:21:08.226  7603  7963 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13b14838 on behalf of 
08-15 17:21:08.227  7603  7963 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-15 17:21:08.228  7603  7963 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-15 17:21:08.229  7603  7963 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39cd0011 on behalf of 
08-15 17:21:08.230  7603  7963 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-15 17:21:08.234  7603  7963 V BluetoothOppNotification: outbound notification was removed.
08-15 17:21:08.234  7603  7963 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-15 17:21:08.236  7603  7963 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30746576 on behalf of 
08-15 17:21:08.236  7603  7963 V BluetoothOppNotification: inbound: succ-0  fail-0
08-15 17:21:08.238  7603  7963 V BluetoothOppNotification: inbound notification was removed.
08-15 17:21:08.238  7603  7963 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-15 17:21:08.239  7603  7963 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7bd5777 on behalf of 
08-15 17:21:08.404   308   894 D SoftapController: Softap fwReload - Ok
,08-15 17:21:08.416  1036  1440 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (620ms)
08-15 17:21:08.426   308   894 D CommandListener: Setting iface cfg
08-15 17:21:08.427   308   894 D CommandListener: Trying to bring down wlan0
,08-15 17:21:08.447  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-15 17:21:08.447  1036  1118 D Tethering: InitialState.processMessage what=4
,08-15 17:21:08.451   308   894 D CommandListener: Clearing all IP addresses on wlan0
08-15 17:21:08.452  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-15 17:21:08.455  1036  1440 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-15 17:21:08.458  7965  7965 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:08.468  7965  7965 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-15 17:21:08.480  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 17:21:08.480  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-15 17:21:08.480  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 17:21:08.497  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-15 17:21:08.518  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:08.520  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-15 17:21:08.521  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:08.524  1036  1440 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-15 17:21:08.524  1036  1440 D WifiMonitor: connecting to supplicant
08-15 17:21:08.541  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-15 17:21:08.541  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-15 17:21:08.541  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 17:21:08.541  6840  6840 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-15 17:21:08.542  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 17:21:08.542  6840  6840 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-15 17:21:08.543  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-15 17:21:08.543  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 17:21:08.543  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 17:21:08.543  6840  6840 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 17:21:08.543  6840  6840 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-15 17:21:08.545  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-15 17:21:08.545  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-15 17:21:08.546  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 17:21:08.546  6840  6840 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-15 17:21:08.546  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 17:21:08.547  6840  6840 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-15 17:21:08.547  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-15 17:21:08.547  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 17:21:08.547  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 17:21:08.547  6840  6840 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 17:21:08.547  6840  6840 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-15 17:21:08.552  7965  7965 I wpa_supplicant: Successfully initialized wpa_supplicant
08-15 17:21:08.600  7965  7965 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-15 17:21:08.601  7965  7965 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-15 17:21:08.605  1036  1052 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7983 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-15 17:21:08.666  7965  7965 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-15 17:21:08.723  1036  1976 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8004 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-15 17:21:08.727  7965  7965 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-15 17:21:08.731  7983  8002 W FormManager: Network not available. Please check & try again.
08-15 17:21:08.734  7965  7965 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-15 17:21:08.735  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-15 17:21:08.735  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-15 17:21:08.735  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-15 17:21:08.736  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-15 17:21:08.736  1036  8017 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-15 17:21:08.736  1036  8017 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-15 17:21:08.736  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-15 17:21:08.737  1036  1440 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-15 17:21:08.737  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:08.738  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:08.738  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:08.738  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:08.739  1036  1440 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-15 17:21:08.739  1036  1440 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-15 17:21:08.740  1036  1440 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-15 17:21:08.740  1036  1440 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-15 17:21:08.740  1036  1440 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-15 17:21:08.741  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-15 17:21:08.741  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-15 17:21:08.741  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-15 17:21:08.741  1036  1440 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-15 17:21:08.742  1036  1440 D WifiNative-wlan0: SET update_config 1: returned true
08-15 17:21:08.742  1036  1440 D WifiConfigStore: Loading config and enabling all networks 
08-15 17:21:08.742  1036  1440 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-15 17:21:08.743  1036  1440 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-15 17:21:08.744  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:08.744  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:08.744  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:08.744  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:08.744  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-15 17:21:08.747  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-15 17:21:08.749  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-15 17:21:08.750  1036  1440 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-15 17:21:08.751  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:08.756  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:21:08.756  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:08.756  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:08.756  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:21:08.756  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:08.756  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:21:08.756  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:21:08.756  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-15 17:21:08.756  1036  1470 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-15 17:21:08.758  7983  8003 V FormManager: Network unavailable.
08-15 17:21:08.758  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:21:08.759  1036  1440 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-15 17:21:08.759  1036  1440 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-15 17:21:08.760  1036  1440 D WifiStateMachine: enableVerboseLogging : level 2
08-15 17:21:08.760  1036  1440 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-15 17:21:08.760  1036  1440 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-15 17:21:08.760  1036  1440 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-15 17:21:08.761  1036  1440 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-15 17:21:08.761  1036  1440 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-15 17:21:08.761   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 460us total 38.643ms
08-15 17:21:08.761  1036  1440 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-15 17:21:08.761  1036  1440 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-15 17:21:08.762  7983  8003 V FormManager: Network unavailable.
08-15 17:21:08.762  1036  1440 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-15 17:21:08.762  1036  1440 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-15 17:21:08.762  1036  1440 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-15 17:21:08.763  1036  1440 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-15 17:21:08.763  1036  1440 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-15 17:21:08.763  1036  1440 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-15 17:21:08.764  1036  1440 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-15 17:21:08.764  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-15 17:21:08.764  1036  1440 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-15 17:21:08.765  1036  1440 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-15 17:21:08.765  1036  1440 D WifiNative-HAL: Setting external_sim to 1
08-15 17:21:08.765  1036  1440 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-15 17:21:08.765  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-15 17:21:08.765  1036  1440 D WifiNative-wlan0: SET external_sim 1: returned true
08-15 17:21:08.765  1941  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-15 17:21:08.765  1036  1440 I WifiNative-HAL: startHal
08-15 17:21:08.765  1941  2295 D WfdsService: Set the WFDS Monitor: true
08-15 17:21:08.765  1941  2295 D WfdsMonitor: WfdsMonitorThread create
08-15 17:21:08.765  1036  1440 D wifi    : setting scan oui 0x952792c0
08-15 17:21:08.765  1941  2295 D WfdsMonitor: WFDS Monitor is created and started
08-15 17:21:08.766  1941  2295 D WfdsService: WiFi: Supplicant connection re-established
08-15 17:21:08.766  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-15 17:21:08.766  1036  1440 I WifiNative-HAL: startHal
08-15 17:21:08.766  1036  1440 D wifi    : setting scan oui 0x952792c0
08-15 17:21:08.767  1036  1440 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-15 17:21:08.767  1036  1440 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-15 17:21:08.767  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-15 17:21:08.768  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-15 17:21:08.768  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-15 17:21,:08.768  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-15 17:21:08.768  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-15 17:21:08.769  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-15 17:21:08.769  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-15 17:21:08.769  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-15 17:21:08.769  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-15 17:21:08.769  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-15 17:21:08.769  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-15 17:21:08.770  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-15 17:21:08.770  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-15 17:21:08.770  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-15 17:21:08.770  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-15 17:21:08.770  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-15 17:21:08.770  7965  7965 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-15 17:21:08.770  1941  8022 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-15 17:21:08.771  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-15 17:21:08.771  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-15 17:21:08.771  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-15 17:21:08.771  1941  8022 E CtrlSupplicant: Succeed to open control connection
08-15 17:21:08.771  1941  8022 E CtrlSupplicant: Succeed to open monitor connection
08-15 17:21:08.771  1941  8022 D WfdsMonitor: Supplicant connection established
08-15 17:21:08.771  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-15 17:21:08.771  1941  2295 D WfdsService: Connected to the supplicant for wfds
08-15 17:21:08.771  7660  7660 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:08.772  1036  1440 E WifiNative: : [355,702,779 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-15 17:21:08.772  1036  1440 D WifiNative-wlan0: doBoolean: RECONNECT
08-15 17:21:08.773  1036  1440 D WifiNative-wlan0: RECONNECT: returned true
08-15 17:21:08.773  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-15 17:21:08.773  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-15 17:21:08.773  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-15 17:21:08.773  1036  1440 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-15 17:21:08.773  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-15 17:21:08.773  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-15 17:21:08.774  1036  1391 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.774  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-15 17:21:08.774  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-15 17:21:08.774  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.774  1036  1557 I WifiNative-HAL: startHal
08-15 17:21:08.774  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0x952792c0
08-15 17:21:08.774  1036  1557 D wifi    : failed to get capabilities : -3
08-15 17:21:08.774  1036  1557 E WifiScanningService: could not get scan capabilities
08-15 17:21:08.774  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-15 17:21:08.775   308   894 D CommandListener: Setting iface cfg
08-15 17:21:08.775  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-15 17:21:08.775   308   894 D CommandListener: Trying to bring up p2p0
08-15 17:21:08.775  1036  1440 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-15 17:21:08.775  1036  1391 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-15 17:21:08.776  1036  1391 D LGWifiP2pService: P2pEnablingState
08-15 17:21:08.776  1036  1391 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.776  1036  1391 D LGWifiP2pService: P2p socket connection successful
08-15 17:21:08.776  1036  1391 D LGWifiP2pService: P2pEnabledState
08-15 17:21:08.776  1036  1440 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-15 17:21:08.776  1036  1391 D LGWifiP2pService: sending p2p connection changed broadcast
08-15 17:21:08.776  1036  1440 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-15 17:21:08.777  1036  1440 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-15 17:21:08.777  1036  1440 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-15 17:21:08.777  1036  1440 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-15 17:21:08.777  1036  1440 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-15 17:21:08.778  7965  7965 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-15 17:21:08.778  1036  1440 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-15 17:21:08.778  1036  1440 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-15 17:21:08.778  1036  1440 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-15 17:21:08.779  1036  1440 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-15 17:21:08.779  7965  7965 E wpa_supplicant: disconnect_rssi_lvl: -100
08-15 17:21:08.780  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-15 17:21:08.780  1941  1941 D WfdsService: WifiP2pState is changed : true
08-15 17:21:08.780  1941  2295 D WfdsService: Receive the WFDS_ENABLE Method
08-15 17:21:08.780  1941  2295 D WfdsService: Set the WFDS Monitor: true
08-15 17:21:08.780  1941  2295 D WfdsService: Connected to the supplicant for wfds
08-15 17:21:08.780  1941  2295 D WfdsJNI : doCommand: WFDS_SET TRUE
08-15 17:21:08.780  7965  7965 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-15 17:21:08.782  1941  2295 D WfdsService: selectPreferredScanChannel [36]
08-15 17:21:08.782  1941  2295 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-15 17:21:08.785  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-15 17:21:08.785  1941  1941 D WfdsService: isConnected: false
08-15 17:21:08.785   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 402us total 23.088ms
08-15 17:21:08.787  1036  1391 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-15 17:21:08.787  1036  1391 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-15 17:21:08.787  1036  1391 D WifiNative-p2p0: doBoolean: SET device_name G3
08-15 17:21:08.788  1036  1391 D WifiNative-p2p0: SET device_name G3: returned true
08-15 17:21:08.788  1036  1391 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-15 17:21:08.788  1036  1391 D LGWifiP2pService: before postfix = G3
08-15 17:21:08.788  1036  1391 D WifiServerServiceExt: postfix byte check : 2
08-15 17:21:08.788  1036  1391 D LGWifiP2pService: after postfix = G3
08-15 17:21:08.788  1036  1391 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-15 17:21:08.788  1036  1391 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-15 17:21:08.788  1036  1391 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-15 17:21:08.789  1036  1391 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-15 17:21:08.789  1036  1391 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-15 17:21:08.789  1036  1391 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-15 17:21:08.789  1036  1391 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-15 17:21:08.789  1036  1391 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-15 17:21:08.789  1036  1391 D WifiNative-HAL: p2pGetDeviceAddress
08-15 17:21:08.789  1036  1391 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-15 17:21:08.790  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-15 17:21:08.790  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-15 17:21:08.791  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-15 17:21:08.791  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-15 17:21:08.791  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-15 17:21:08.792  7965  7965 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:21:08.792  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 17:21:08.792  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:21:08.792  1036  8017 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:21:08.792  1036  8017 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:21:08.792  7965  7965 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-15 17:21:08.792  7965  7965 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.792  1036  1440 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-15 17:21:08.793  7965  7965 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.793  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-15 17:21:08.793  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,08-15 17:21:08.793  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-15 17:21:08.793  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-15 17:21:08.793  1941  1941 D WfdsService: Update P2p Interface State: 3
08-15 17:21:08.794  1036  1391 D LGWifiP2pService: DeviceAddress: 
08-15 17:21:08.794  1036  1391 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-15 17:21:08.795  1036  1391 D WifiNative-p2p0: P2P_FLUSH: returned true
08-15 17:21:08.795  1036  1391 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-15 17:21:08.795  1036  1391 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-15 17:21:08.795  1036  1391 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-15 17:21:08.795  1036  1391 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-15 17:21:08.795  1036  1391 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-15 17:21:08.797  1036  8017 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:21:08.797  1036  8017 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.797  1036  8017 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.797  1036  8017 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.797  1036  8017 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:21:08.797  1036  8017 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.797  1036  8017 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.797  1036  8017 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.797  1941  8022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:21:08.797  1941  8022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:21:08.797  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-15 17:21:08.797  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-15 17:21:08.803   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 357us total 16.377ms
08-15 17:21:08.804  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:21:08.804  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:08.804  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:08.804  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:21:08.804  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:08.804  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-15 17:21:08.804  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-15 17:21:08.804  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-15 17:21:08.805  1036  1391 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-15 17:21:08.805  1036  1391 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-15 17:21:08.805  1036  1391 D LGWifiP2pService: InactiveState
08-15 17:21:08.805  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-15 17:21:08.805  7965  7965 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 17:21:08.805  1036  1391 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.805  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-15 17:21:08.805  1036  1391 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-15 17:21:08.806  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-15 17:21:08.806  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-15 17:21:08.807  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 17:21:08.807  1036  8017 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 17:21:08.807  1036  8017 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-15 17:21:08.807  1036  1440 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-15 17:21:08.807  1036  1440 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-15 17:21:08.807  1036  1440 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-15 17:21:08.807  1036  1440 D WifiNative-wlan0: doBoolean: SCAN
08-15 17:21:08.807  1036  1440 D WifiNative-wlan0: SCAN: returned false
08-15 17:21:08.808  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=355739  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-15 17:21:08.808  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-15 17:21:08.809  7965  7965 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:21:08.810  7965  7965 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-15 17:21:08.810  7965  7965 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.810  1036  1391 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-15 17:21:08.810  7965  7965 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.810  1036  1391 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.810  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.810  1036  1391 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.810  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.810  1036  1391 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  1391 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  1391 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  1391 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  1391 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  8017 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 17:21:08.811  1036  8017 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:21:08.811  1036  1391 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  8017 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:21:08.811  1036  8017 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-15 17:21:08.811  1941  8022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-15 17:21:08.811  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  8017 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:21:08.811  1941  8022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:21:08.811  1036  1391 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:08.811  1036  8017 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.811  1941  8022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:21:08.811  1036  8017 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.811  1036  8017 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.811  1036  1036 E WifiServerServiceExt: No p2p device connected
08-15 17:21:08.811  1036  8017 D WifiMoni,tor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-15 17:21:08.811  1036  8017 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.811  1036  8017 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.811  1036  8017 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-15 17:21:08.812  1941  2295 W WfdsService: DefaultState - msg [9441285] is not handled
08-15 17:21:08.813  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:08.813  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:21:08.813  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:08.813  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:08.813  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-15 17:21:08.813  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=355744  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-15 17:21:08.814  1036  1440 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:21:08.814  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:08.814  1036  1440 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:21:08.814  1036  1440 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:21:08.814  6708  6776 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-15 17:21:08.815  1036  1440 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:21:08.815  1036  1440 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-15 17:21:08.815  6708  6776 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-15 17:21:08.815  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:21:08.816  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-15 17:21:08.817  6708  6776 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2a9a4aaf Bundle[{}]
08-15 17:21:08.817  6708  6776 I io.jxcore.node.LifeCycleMonitor: start: OK
08-15 17:21:08.817  6708  6776 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-15 17:21:08.818  6708  6776 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-15 17:21:08.818  6708  6776 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-15 17:21:08.819  6708  6776 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-15 17:21:08.819  6708  6776 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-15 17:21:08.823  6708  6776 I System.out: Running OutgoingSocketThread
,08-15 17:21:08.829  6708  8025 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 860)
08-15 17:21:08.830  6708  8025 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49428
08-15 17:21:08.830  6708  8025 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-15 17:21:08.831  8004  8004 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:21:08.833  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 17:21:08.837  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:08.839  1036  1991 I ActivityManager: Killing 7127:com.lge.drmservice/u0a62 (adj 15): empty #17
08-15 17:21:08.894  1036  2012 W libprocessgroup: failed to open /acct/uid_10062/pid_7127/cgroup.procs: No such file or directory
,08-15 17:21:08.922  8004  8004 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-15 17:21:08.934  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-15 17:21:08.945  7983  8028 W FormManager: Network not available. Please check & try again.
08-15 17:21:08.949  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:08.969  7983  8029 V FormManager: Network unavailable.
,08-15 17:21:08.978  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-15 17:21:08.979  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 17:21:08.981  7983  8029 V FormManager: Network unavailable.
08-15 17:21:08.983  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-15 17:21:08.993  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:21:09.003  4291  8030 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-15 17:21:09.008  4291  8031 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-15 17:21:09.009  4291  8031 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 17:21:09.062  1036  1876 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8032 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-15 17:21:09.184  8032  8032 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-15 17:21:09.184  8032  8032 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-15 17:21:09.197  8032  8032 V [BNRBootReceiver]: Boot Receiver Return
08-15 17:21:09.197  8032  8032 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-15 17:21:09.266  1036  1991 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8050 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-15 17:21:09.267  1036  1991 I ActivityManager: Killing 7146:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-15 17:21:09.338  1036  2032 W libprocessgroup: failed to open /acct/uid_10085/pid_7146/cgroup.procs: No such file or directory
,08-15 17:21:09.369  8050  8050 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-15 17:21:09.389  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-15 17:21:09.389  7965  7965 E wpa_supplicant: USIM:  scard_init function
08-15 17:21:09.389  1036  8017 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-15 17:21:09.389  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-15 17:21:09.389  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-15 17:21:09.389  1036  8017 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-15 17:21:09.390  7965  7965 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-15 17:21:09.390  1036  1440 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-15 17:21:09.391  1036  1440 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-15 17:21:09.392  1036  1440 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-15 17:21:09.392  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-15 17:21:09.392  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-15 17:21:09.392  1036  1440 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-15 17:21:09.392  1036  1440 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-15 17:21:09.397  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=356329  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-15 17:21:09.400  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.400  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:21:09.401  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.403  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.403  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.403  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-15 17:21:09.407  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=356338  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-15 17:21:09.411  8050  8050 D PluginManager: init()
08-15 17:21:09.414  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.414  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.414  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-15 17:21:09.414  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:21:09.414  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-15 17:21:09.422  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.422  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:21:09.423  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 17:21:09.499  7965  7965 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-15 17:21:09.499  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,08-15 17:21:09.507  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-15 17:21:09.508  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-15 17:21:09.508  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-15 17:21:09.508  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:21:09.508  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:21:09.509  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=356440  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-15 17:21:09.510  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=356441  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-15 17:21:09.512  1036  1440 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356443
08-15 17:21:09.513  7965  7965 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 17:21:09.513  7965  7965 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 17:21:09.513  1036  1440 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356444
08-15 17:21:09.514  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:21:09.514  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:21:09.514  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-15 17:21:09.514  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 17:21:09.514  1036  8017 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-15 17:21:09.515  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-15 17:21:09.515  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-15 17:21:09.515  1036  8017 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-15 17:21:09.515  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:21:09.515  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:21:09.516  1036  1440 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356448
08-15 17:21:09.517  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356448
08-15 17:21:09.517  1036  1440 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356448
08-15 17:21:09.518  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=356449  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-15 17:21:09.519  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-15 17:21:09.523  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.523  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:21:09.524  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.524  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.524  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-15 17:21:09.525  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.530  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.531  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.531  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-15 17:21:09.532  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=356463  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-15 17:21:09.534  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:21:09.534  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-15 17:21:09.535  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=356466  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-15 17:21:09.535  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=356466  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-15 17:21:09.536  1036  1440 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=356467
08-15 17:21:09.536  1036  1440 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=356468
08-15 17:21:09.537  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-15 17:21:09.538  1036  8017 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-15 17:21:09.538  1036  8017 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-15 17:21:09.538  1036  1440 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-15 17:21:09.540  1036  1440 I WifiServiceExtension: setVHTCapabilityType  : false
08-15 17:21:09.547  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.547  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-15 17:21:09.550  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.551  1036  1440 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-15 17:21:09.551  1036  1440 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-15 17:21:09.560  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.560  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.560  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-15 17:21:09.562  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.562  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.562  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-15 17:21:09.563  1036  1440 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-15 17:21:09.563  1036  1519 D ConnectivityService: Got NetworkAgent Messenger
08-15 17:21:09.564  1036  1519 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-15 17:21:09.564  1036  1519 D ConnectivityService: NetworkAgent connected
08-15 17:21:09.564  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 17:21:09.564  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 17:21:09.565  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 17:21:09.565  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 17:21:09.569  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-15 17:21:09.570  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-15 17:21:09.570  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-15 17:21:09.570  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-15 17:21:09.570  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-15 17:21:09.571  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.572  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:21:09.573  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.574  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-15 17:21:09.576   308   894 D CommandListener: Setting iface cfg
08-15 17:21:09.577  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.577  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-15 17:21:09.579  1036  1440 E WifiStateMachine: Start Dhcp Watchdog 3
08-15 17:21:09.584  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=356515  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:21:09.585  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=356516  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:21:09.585  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=356516  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:21:09.586  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:09.586  1036  8071 D DhcpStateMachine: StoppedState
08-15 17:21:09.586  1036  8071 D DhcpStateMachine: StoppedState{ when=-7ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:09.586  1036  8071 D DhcpStateMachine: WaitBeforeStartState
08-15 17:21:09.587  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:09.587  1036  1440 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:09.588  1036  1440 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:09.588  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.588  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:09.588  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-15 17:21:09.589  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=356520  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:21:09.590  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=356521  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:21:09.591  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=356522  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-15 17:21:09.592  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14253] from screen [on:0 period:-1899312936] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 17:21:09.593  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1899312935] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 17:21:09.593  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-15 17:21:09.593  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:21:09.593  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-15 17:21:09.598  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.599  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.600  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.600  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.600  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.601  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.601  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.602  1036  1519 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-15 17:21:09.602  1036  1519 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-15 17:21:09.603  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:21:09.603  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-15 17:21:09.603  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=151,0,0
08-15 17:21:09.604  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=151,0,0
08-15 17:21:09.604  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-15 17:21:09.604  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-15 17:21:09.605  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-15 17:21:09.605  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 0
08-15 17:21:09.605  1036  1440 D WifiNative-wlan0: SET ps 0: returned true
08-15 17:21:09.605  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-15 17:21:09.605  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-15 17:21:09.606  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-15 17:21:09.606  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@229c582b target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:09.606  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@229c582b target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:09.606  1036  8071 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:09.607  1036  8071 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-15 17:21:09.608  1036  1440 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-15 17:21:09.608  1036  1440 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-15 17:21:09.608  1036  1440 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-15 17:21:09.609   308   894 D CommandListener: Setting iface cfg
08-15 17:21:09.609   308   894 D CommandListener: Trying to bring up wlan0
08-15 17:21:09.610  1036  1440 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-15 17:21:09.612  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-15 17:21:09.612  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-15 17:21:09.613  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.613  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.614  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.614  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.615  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.615  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-15 17:21:09.616  1036  1519 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-15 17:21:09.616  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-15 17:21:09.617  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-15 17:21:09.617  1036  1391 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:09.617  1036  1391 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:09.617  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-15 17:21:09.617  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-15 17:21:09.618  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-15 17:21:09.618  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-15 17:21:09.618  7965  7965 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-15 17:21:09.618  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-15 17:21:09.618  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
,08-15 17:21:09.634  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
,08-15 17:21:09.635  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-15 17:21:09.635  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-15 17:21:09.636  1036  1440 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-15 17:21:09.636  1036  1519 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-15 17:21:09.636  1036  1519 D ConnectivityService: ignoring duplicate network state non-change
08-15 17:21:09.639  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.639  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:21:09.640  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.641  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.641  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.641  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-15 17:21:09.642  1036  1519 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-15 17:21:09.642  1036  1519 D ConnectivityService: Adding iface wlan0 to network 102
08-15 17:21:09.647  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.647  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.648  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-15 17:21:09.648  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-15 17:21:09.650  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-15 17:21:09.652  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.652  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.652  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-15 17:21:09.654  1036  1440 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-15 17:21:09.659  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-15 17:21:09.661  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.661  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-15 17:21:09.662  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.666  1036  1519 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-15 17:21:09.666  1036  1519 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-15 17:21:09.667  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.667  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:09.667  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-15 17:21:09.668  1036  1519 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-15 17:21:09.668  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.668  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-15 17:21:09.669  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.669   308   894 E Netd    : netlink response contains error (File exists)
08-15 17:21:09.670  1036  1519 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-15 17:21:09.671  1036  1519 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-15 17:21:09.671  1036  1519 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-15 17:21:09.671  1036  1519 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-15 17:21:09.671  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:09.671  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-15 17:21:09.671  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.672  1036  1519 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-15 17:21:09.672  1036  1519 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-15 17:21:09.672  1036  1519 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-15 17:21:09.672  1036  1519 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-15 17:21:09.672  1036  1519 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:21:09.672  1036  1519 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:21:09.672  1036  1519 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-15 17:21:09.672  1036  1519 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:09.673  1036  1519 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-15 17:21:09.673  1036  1519 D ConnectivityService: currentScore = 0, newScore = 20
08-15 17:21:09.673  1036  1519 D ConnectivityService:    accepting network in place of null
08-15 17:21:09.673  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:09.673  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-15 17:21:09.673  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:09.673  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-15 17:21:09.675  1036  1519 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:09.676  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:,09.676  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-15 17:21:09.677  1036  1440 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:09.678  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:21:09.678   308  8081 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-15 17:21:09.678  1036  1519 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-15 17:21:09.678  1036  1519 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-15 17:21:09.678   308  8081 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-15 17:21:09.679  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-15 17:21:09.679   308  8081 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
08-15 17:21:09.679  1036  1519 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-15 17:21:09.679  1036  1519 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-15 17:21:09.680   308  8081 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
08-15 17:21:09.680  1036  1519 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-15 17:21:09.682  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-15 17:21:09.682  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-15 17:21:09.683  1036  1519 D ConnectivityService: validation of new default Network = false
08-15 17:21:09.683  1036  1519 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-15 17:21:09.683  1036  1519 D DSQN    : enableDataServiceNotify 
08-15 17:21:09.683  1036  1519 D DSQN    : start dsqn bin
08-15 17:21:09.685  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-15 17:21:09.685  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-15 17:21:09.685  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-15 17:21:09.685  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-15 17:21:09.691  1036  1519 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-15 17:21:09.691  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:09.691  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-15 17:21:09.691  1036  1519 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:21:09.678  8082  8082 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:09.678  8082  8082 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:09.694  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-15 17:21:09.698  1036  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-15 17:21:09.706  8082  8082 E DSQN    : DSQN ssw
,08-15 17:21:09.715  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-15 17:21:09.716  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.717  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:09.809  1036  8071 D DhcpStateMachine: DHCPV4 request on wlan0
,08-15 17:21:09.811  1036  8071 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-15 17:21:09.811  1036  8071 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-15 17:21:09.808  8086  8086 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:09.808  8086  8086 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-15 17:21:09.829  6708  6776 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 861)
08-15 17:21:09.830  6708  6776 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 861)
08-15 17:21:09.834  8086  8086 I dhcpcd  : version 5.5.6 starting
08-15 17:21:09.837  8086  8086 E dhcpcd  : get_duid: m
08-15 17:21:09.837  8086  8086 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
,08-15 17:21:09.837  8086  8086 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-15 17:21:09.840  6708  6776 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 866)
08-15 17:21:09.843  6708  6776 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-15 17:21:09.843  6708  6776 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
08-15 17:21:09.849  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.849  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14439961 added. We now have 2 listener(s)
08-15 17:21:09.850  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.853  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.853  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.853  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.853  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.853  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b8a0c86 added. We now have 9 listener(s)
08-15 17:21:09.853  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-15 17:21:09.856  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 17:21:09.860  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:21:09.869  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:21:09.869  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:09.869  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:09.869  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:21:09.869  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:09.869  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:09.869  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:21:09.869  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 17:21:09.871  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:09.871  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 17:21:09.871  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.871  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfd574 added. We now have 3 listener(s)
08-15 17:21:09.872  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.873  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.875  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.878  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.878  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.878  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.879  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.879  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e3f6a9d added. We now have 10 listener(s)
08-15 17:21:09.879  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:09.879  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:21:09.879  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:21:09.879  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:21:09.880  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.880  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.880  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:21:09.880  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.880  8086  8086 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-15 17:21:09.880  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14439961 removed from the list
08-15 17:21:09.880  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.880  8086  8086 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-15 17:21:09.880  8086  8086 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-15 17:21:09.880  8086  8086 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-15 17:21:09.880  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b8a0c86 removed from the list,
08-15 17:21:09.880  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:21:09.880  8086  8086 D dhcpcd  : wlan0: sending REQUEST (xid 0x547f36e), next in 3.03 seconds
08-15 17:21:09.880  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.881  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.881  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.882  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-15 17:21:09.882  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.882  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.883  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b8a0c86 not in the list
08-15 17:21:09.883  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.883  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.884  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.884  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:21:09.884  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.884  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e3f6a9d removed from the list
08-15 17:21:09.884  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.884  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.884  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.884  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.885  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfd574 removed from the list
08-15 17:21:09.887  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.887  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25ea6b12 added. We now have 2 listener(s)
08-15 17:21:09.887  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.889  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.889  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.889  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.889  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.889  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@335b42e3 added. We now have 9 listener(s)
08-15 17:21:09.889  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:09.889  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 17:21:09.891  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:21:09.894  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:21:09.894  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:09.894  6708  6776 V io.jxcore.n,ode.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:09.894  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:21:09.894  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:09.894  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:09.894  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:21:09.894  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 17:21:09.895  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-15 17:21:09.895  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 17:21:09.895  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.895  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242d1399 added. We now have 3 listener(s)
08-15 17:21:09.896  1036  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.897  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.898  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.899  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.899  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.899  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.899  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.900  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2480265e added. We now have 10 listener(s)
08-15 17:21:09.900  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:09.900  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 17:21:09.900  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 17:21:09.900  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 17:21:09.900  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:21:09.900  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 17:21:09.902  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 17:21:09.902  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.905  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 17:21:09.906  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-15 17:21:09.907  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 17:21:09.907  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-15 17:21:09.909  6708  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 17:21:09.909  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:21:09.909  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:21:09.910  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:21:09.910  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:21:09.910  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:21:09.911  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.911  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.911  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:21:09.911  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.911  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25ea6b12 removed from the list
08-15 17:21:09.911  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.911  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@335b42e3 removed from the list
,08-15 17:21:09.911  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:21:09.911  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.911  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.911  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.912  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:21:09.912  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.912  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.912  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@335b42e3 not in the list
08-15 17:21:09.912  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.912  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.913  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.913  8050  8050 W ExternalStrings: load override strings
08-15 17:21:09.913  8050  8050 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:09.913  8050  8050 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:09.913  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:21:09.913  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:21:09.913  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:21:09.913  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.913  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryM,anager@2480265e removed from the list
08-15 17:21:09.913  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.913  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.913  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.914  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.914  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242d1399 removed from the list
08-15 17:21:09.914  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.914  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db25055 added. We now have 2 listener(s)
08-15 17:21:09.915  1036  1902 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.916  8050  8050 D StatusProvider: onCreate
08-15 17:21:09.916  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.917  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.917  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.917  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.917  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20244a6a added. We now have 9 listener(s)
08-15 17:21:09.917  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:09.917  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-15 17:21:09.919  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:21:09.921  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:21:09.921  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:09.921  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:09.921  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:21:09.921  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:09.921  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:09.921  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:21:09.921  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-15 17:21:09.922  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:09.923  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 17:21:09.923  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.923  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2965ff8 added. We now have 3 listener(s)
08-15 17:21:09.923  1036  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.924  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.925  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.925  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.925  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.925  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.926  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.926  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d149cd1 added. We now have 10 listener(s)
08-15 17:21:09.926  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:09.926  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-15 17:21:09.926  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 17:21:09.927  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 17:21:09.927  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 17:21:09.927  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:21:09.927  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 17:21:09.928  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 17:21:09.928  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.931  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 17:21:09.932  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-15 17:21:09.933  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-15 17:21:09.933  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:21:09.934  6708  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 17:21:09.935  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:21:09.935  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:21:09.935  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:21:09.935  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.935  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.935  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:21:09.935  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.935  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db25055 removed from the list
08-15 17:21:09.935  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.935  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20244a6a removed from the list
08-15 17:21:09.935  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:21:09.935  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.936  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.936  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.937  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:21:09.937  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.937  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.937  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20244a6a not in the list
08-15 17:21:09.937  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.937  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.938  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.938  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:21:09.938  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:21:09.938  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:21:09.938  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.938  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d149cd1 removed from the list
08-15 17:21:09.938  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.938  6708  6776 W org.thaliproject.p2p.btc,onnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.938  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.938  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.938  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2965ff8 removed from the list
08-15 17:21:09.939  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.939  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bcd83a4 added. We now have 2 listener(s)
08-15 17:21:09.939  1036  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.941  8086  8086 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-15 17:21:09.941  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.941  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.941  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.941  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.941  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3975350d added. We now have 9 listener(s)
08-15 17:21:09.941  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:09.941  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 17:21:09.943  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-15 17:21:09.945  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:21:09.945  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:09.945  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:09.945  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:21:09.945  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:09.945  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:09.945  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:21:09.945  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 17:21:09.946  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:09.947  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-15 17:21:09.947  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.947  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1312aad3 added. We now have 3 listener(s)
08-15 17:21:09.947  1036  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.949  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.950  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.951  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.951  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.951  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.951  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.951  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1313610 added. We now have 10 listener(s)
08-15 17:21:09.951  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:09.951  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 17:21:09.951  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-15 17:21:09.951  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-15 17:21:09.951  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:21:09.951  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-15 17:21:09.953  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-15 17:21:09.954  1036  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.957  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-15 17:21:09.958  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-15 17:21:09.959  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-15 17:21:09.959  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-15 17:21:09.960  6708  6776 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-15 17:21:09.961  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:21:09.961  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:21:09.961  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:21:09.961  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.961  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.961  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:21:09.962  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.962  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bcd83a4 removed from the list
08-15 17:21:09.962  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.962  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3975350d removed from the list
08-15 17:21:09.962  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:21:09.962  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.962  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.962  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.963  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:21:09.963  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.963  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.963  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3975350d not in the list
08-15 17:21:09.963  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.963  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.964  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.964  6708  6776 D BluetoothLeScanner: could not find callback wrapper
08-15 17:21:09.964  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-15 17:21:09.964  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:21:09.964  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.964  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1313610 removed from the list
08-15 17:21:09.964  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.964  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-,15 17:21:09.964  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.964  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.964  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1312aad3 removed from the list
08-15 17:21:09.965  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.965  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853212f added. We now have 2 listener(s)
08-15 17:21:09.965  1036  2012 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.966  8086  8086 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-15 17:21:09.966  8086  8086 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-15 17:21:09.967  8086  8086 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-15 17:21:09.967  8086  8086 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-15 17:21:09.967  8086  8086 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-15 17:21:09.967  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.967  8086  8086 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-15 17:21:09.967  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.967  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.967  8086  8086 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-15 17:21:09.967  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.967  8086  8086 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-15 17:21:09.967  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38dba33c added. We now have 9 listener(s)
08-15 17:21:09.967  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:09.968  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-15 17:21:09.971  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-15 17:21:09.974  6708  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-15 17:21:09.974  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:09.974  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:09.974  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:21:09.974  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:09.974  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:09.974  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:21:09.974  6708  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 17:21:09.975  6708  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:09.975  6708  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
08-15 17:21:09.976  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.978  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-15 17:21:09.978  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-15 17:21:09.978  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1c221a added. We now have 3 listener(s)
08-15 17:21:09.978  1036  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-15 17:21:09.980  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-15 17:21:09.980  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-15 17:21:09.980  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-15 17:21:09.980  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-15 17:21:09.980  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a7aa14b added. We now have 10 listener(s)
08-15 17:21:09.980  6708  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-15 17:21:09.980  6708  6776 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-15 17:21:09.980  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-15 17:21:09.980  6708  6776 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-15 17:21:09.981  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.981  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.981  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-15 17:21:09.981  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.981  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853212f removed from the list
08-15 17:21:09.981  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.981  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38dba33c removed from the list
08-15 17:21:09.981  6708  6776 D io.jxcore.node.ConnectivityMonitor: stop
08-15 17:21:09.981  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.981  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.981  6708  6776 D org.thal,iproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.982  8050  8050 V Signer  : override build config not found
08-15 17:21:09.982  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:21:09.982  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.982  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.982  6708  6776 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38dba33c not in the list
08-15 17:21:09.982  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.982  8050  8050 D Signer  : value of property debug is false
08-15 17:21:09.982  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.982  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-15 17:21:09.982  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-15 17:21:09.982  6708  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-15 17:21:09.982  6708  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a7aa14b removed from the list
08-15 17:21:09.983  6708  6776 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-15 17:21:09.983  6708  6776 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-15 17:21:09.983  6708  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-15 17:21:09.983  6708  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-15 17:21:09.983  6708  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1c221a removed from the list
08-15 17:21:09.983  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-15 17:21:09.983  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-15 17:21:09.984  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-15 17:21:09.984  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-15 17:21:09.984  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-15 17:21:09.984  6708  6776 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-15 17:21:09.994  6708  8096 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 874, name: My test thread name)
08-15 17:21:09.994  6708  8096 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 874, thread name: My test thread name)
08-15 17:21:09.994  6708  8096 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 874, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-15 17:21:09.997  6708  8097 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 876, name: My test thread name)
08-15 17:21:09.997  6708  8097 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 876, thread name: My test thread name)
08-15 17:21:09.997  6708  8097 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 876, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-15 17:21:09.999  6708  6776 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-15 17:21:09.999  6708  6776 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-15 17:21:09.999  6708  6776 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-15 17:21:09.999  6708  6776 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-15 17:21:09.999  6708  6776 D com.test.thalitest.ThaliTestRunner: Total duration: 23411 ms
08-15 17:21:10.000  6708  6776 I jxcore-log: Total number of executed tests:  80
08-15 17:21:10.000  6708  6776 I jxcore-log: 
08-15 17:21:10.001  6708  6776 I jxcore-log: Number of passed tests:  80
08-15 17:21:10.001  6708  6776 I jxcore-log: 
08-15 17:21:10.001  6708  6776 I jxcore-log: Number of failed tests:  0
08-15 17:21:10.001  6708  6776 I jxcore-log: 
08-15 17:21:10.001  6708  6776 I jxcore-log: Number of ignored tests:  0
08-15 17:21:10.001  6708  6776 I jxcore-log: 
08-15 17:21:10.001  6708  6776 I jxcore-log: Total duration:  23411
08-15 17:21:10.001  6708  6776 I jxcore-log: 
08-15 17:21:10.003  6708  6776 I jxcore-log: Unit Test app is loaded
08-15 17:21:10.003  6708  6776 I jxcore-log: 
08-15 17:21:10.008  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.008  6708  6776 I jxcore-log: 
,08-15 17:21:10.016  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.016  6708  6776 I jxcore-log: 
08-15 17:21:10.017  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.017  6708  6776 I jxcore-log: 
08-15 17:21:10.017  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.017  6708  6776 I jxcore-log: 
08-15 17:21:10.018  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.018  6708  6776 I jxcore-log: 
08-15 17:21:10.019  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.019  6708  6776 I jxcore-log: 
,08-15 17:21:10.021  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.021  6708  6776 I jxcore-log: 
08-15 17:21:10.022  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 17:21:10.022  6708  6776 I jxcore-log: 
08-15 17:21:10.023  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 17:21:10.023  6708  6776 I jxcore-log: 
08-15 17:21:10.024  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.024  6708  6776 I jxcore-log: 
08-15 17:21:10.024  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.024  6708  6776 I jxcore-log: 
08-15 17:21:10.025  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-15 17:21:10.025  6708  6776 I jxcore-log: 
08-15 17:21:10.026  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 17:21:10.026  6708  6776 I jxcore-log: 
08-15 17:21:10.027  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-15 17:21:10.027  6708  6776 I jxcore-log: 
08-15 17:21:10.027  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.027  6708  6776 I jxcore-log: 
08-15 17:21:10.028  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.028  6708  6776 I jxcore-log: 
08-15 17:21:10.028  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.028  6708  6776 I jxcore-log: 
08-15 17:21:10.028  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.028  6708  6776 I jxcore-log: 
08-15 17:21:10.029  6708  6708 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-15 17:21:10.029  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.029  6708  6776 I jxcore-log: 
08-15 17:21:10.029  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.029  6708  6776 I jxcore-log: 
08-15 17:21:10.030  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.030  6708  6776 I jxcore-log: 
08-15 17:21:10.030  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-15 17:21:10.030  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-15 17:21:10.030  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-15 17:21:10.030  6708  6776 I jxcore-log: 
08-15 17:21:10.031  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LG,MDMWrapper$HardReset'.
08-15 17:21:10.031  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-15 17:21:10.031  6708  6776 I jxcore-log: 
08-15 17:21:10.031  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-15 17:21:10.031  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-15 17:21:10.031  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-15 17:21:10.031  6708  6776 I jxcore-log: 
08-15 17:21:10.031  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-15 17:21:10.031  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-15 17:21:10.032  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.032  6708  6776 I jxcore-log: 
08-15 17:21:10.032  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-15 17:21:10.032  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-15 17:21:10.032  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.032  6708  6776 I jxcore-log: 
08-15 17:21:10.032  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-15 17:21:10.032  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-15 17:21:10.033  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.033  6708  6776 I jxcore-log: 
08-15 17:21:10.033  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-15 17:21:10.033  8050  8050 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-15 17:21:10.033  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.033  6708  6776 I jxcore-log: 
08-15 17:21:10.033  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:10.033  6708  6776 I jxcore-log: 
08-15 17:21:10.035  6708  6776 I jxcore-log: My device name is: LGE-LG-D855
08-15 17:21:10.035  6708  6776 I jxcore-log: 
08-15 17:21:10.036  6708  6776 I jxcore-log: WARN testUtils: myNameCallback not set!
08-15 17:21:10.036  6708  6776 I jxcore-log: 
,08-15 17:21:10.048  8050  8050 V LGMDMManager: Create singleton instance
,08-15 17:21:10.124  8050  8050 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-15 17:21:10.171  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.171  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-15 17:21:10.179  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:21:10.187  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:10.217  1036  8071 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-15 17:21:10.218  1036  8071 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-15 17:21:10.218  1036  8071 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-15 17:21:10.218  1036  8071 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-15 17:21:10.218  1036  8071 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-15 17:21:10.218  1036  8071 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-15 17:21:10.218  1036  8071 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-15 17:21:10.218  1036  8071 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-15 17:21:10.219  1036  8071 D DhcpStateMachine: RunningState
08-15 17:21:10.220  1036  2025 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8120 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-15 17:21:10.221  1036  2025 I ActivityManager: Killing 7188:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-15 17:21:10.310  8050  8115 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-15 17:21:10.547  1036  1905 W libprocessgroup: failed to open /acct/uid_10093/pid_7188/cgroup.procs: No such file or directory
,08-15 17:21:10.593  8120  8120 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-15 17:21:10.618  8120  8120 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-15 17:21:10.654  8120  8120 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-15 17:21:10.654  8120  8120 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-15 17:21:10.655  8120  8120 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-15 17:21:10.655  8120  8120 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-15 17:21:10.655  8120  8120 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-15 17:21:10.657  8120  8120 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-15 17:21:10.663  8120  8120 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-15 17:21:10.679  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 17:21:10.683  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:21:10.690  8050  8115 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:21:10.690  8050  8115 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:21:10.707  8120  8120 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-15 17:21:10.710  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-15 17:21:10.712  8120  8120 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-15 17:21:10.713  6840  6840 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-15 17:21:10.717  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.718  8120  8120 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-15 17:21:10.720  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 17:21:10.727  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:21:10.732  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:10.742  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:21:10.743  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 17:21:10.745  8120  8120 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-15 17:21:10.748  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.750  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 17:21:10.758  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:21:10.763  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:10.769  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:21:10.770  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:21:10.770  8120  8120 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:21:10.772  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.773  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-15 17:21:10.779  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 17:21:10.784  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 17:21:10.789  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:21:10.789  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:21:10.790  8120  8120 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:21:10.793  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-15 17:21:10.793  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-15 17:21:10.793  6840  6840 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-15 17:21:10.793  6840  6840 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-15 17:21:10.794  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-15 17:21:10.795  6840  6840 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-15 17:21:10.795  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-15 17:21:10.795  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-15 17:21:10.795  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-15 17:21:10.795  6840  6840 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-15 17:21:10.795  6840  6840 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-15 17:21:10.795  6840  6840 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-15 17:21:10.798  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.799  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-15 17:21:10.804  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:21:10.811  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:10.818  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:21:10.819  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:21:10.819  8120  8120 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:21:10.821  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.822  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-15 17:21:10.829  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-15 17:21:10.834  8050  8115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-15 17:21:10.836  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:10.840  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-15 17:21:10.841  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:21:10.841  8120  8120 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:21:10.843  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.844  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 17:21:10.849  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:21:10.855  8050  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-15 17:21:10.855  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:10.861  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:21:10.861  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:21:10.862  8120  8120 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:21:10.866  8050  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-15 17:21:10.867  8050  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-15 17:21:10.867  8050  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-15 17:21:10.868  8050  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-15 17:21:10.868  8050  8115 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-15 17:21:10.873  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 17:21:10.874  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.875  8050  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-15 17:21:10.877  8050  8115 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-15 17:21:10.885  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:21:10.890  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 17:21:10.897  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:21:10.897  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-15 17:21:10.902  8120  8120 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:21:10.905  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.905  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 17:21:10.911  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:21:10.915  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:10.921  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:21:10.921  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:21:10.922  8120  8120 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-15 17:21:10.924  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:10.925  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 17:21:10.928  8004  8004 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-15 17:21:10.933  8004  8004 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:21:10.936  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:21:10.942  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-15 17:21:10.948  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:21:10.948  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:21:10.949  8120  8120 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-15 17:21:10.950  8120  8120 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-15 17:21:10.951  8120  8120 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-15 17:21:10.955  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 17:21:10.956  8050  8116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-15 17:21:10.961  8004  8004 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-15 17:21:10.962  8004  8004 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-15 17:21:10.964  6840  6840 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-15 17:21:10.971  6840  6840 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-15 17:21:10.978  8120  8120 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-15 17:21:10.978  8120  8120 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-15 17:21:10.979  8120  8120 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-15 17:21:10.980  8120  8120 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-15 17:21:10.980  8120  8120 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-15 17:21:10.983  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-15 17:21:10.989  8120  8120 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-15 17:21:10.990  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-15 17:21:10.990  8120  8120 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-15 17:21:11.025  8120  8120 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:21:11.025  8120  8120 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:21:11.031  8120  8120 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-15 17:21:11.033  8120  8120 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-15 17:21:11.033  8120  8120 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-15 17:21:11.033  8120  8120 V SoundPool: doLoad: loading sample sampleID=1
08-15 17:21:11.033  8120  8164 V SoundPool: Start decode
08-15 17:21:11.033  8120  8120 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-15 17:21:11.033  8120  8164 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-15 17:21:11.034   313  1397 V MediaPlayerService: decode(23, 10857164, 17813)
08-15 17:21:11.034   313  1397 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-15 17:21:11.034   313  1397 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-15 17:21:11.034   313  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-15 17:21:11.034   313  1397 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-15 17:21:11.034   313  1397 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-15 17:21:11.034   313  1397 V MediaPlayerService: player type = 3
08-15 17:21:11.034   313  1397 V AwesomePlayer: AwesomePlayer create()
08-15 17:21:11.037   313  1397 V AwesomePlayer: reset_l() 
08-15 17:21:11.037   313  1397 V AwesomePlayer: cancelPlayerEvents
08-15 17:21:11.037   313  1397 V AwesomePlayer: setAudioSink() 
08-15 17:21:11.037   313  1397 V AwesomePlayer: reset_l() 
08-15 17:21:11.037   313  1397 V AudioCache: notify(0xb54748c0, 8, 0, 0)
08-15 17:21:11.037   313  1397 V AudioCache: ignored
08-15 17:21:11.037   313  1397 V AwesomePlayer: cancelPlayerEvents
,08-15 17:21:11.037   313  1397 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-15 17:21:11.037   313  1397 V AwesomePlayer: setDataSource_l dataSource
08-15 17:21:11.037   313  1397 V LGParserOSAL: SniffLGParser start
08-15 17:21:11.037   313  1397 V LGParserOSAL: MainType:5, SubType=0
08-15 17:21:11.037   313  1397 V LGParserOSAL: #### check Mime : application/ogg
08-15 17:21:11.037   313  1397 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-15 17:21:11.037   313  1397 E MediaExtractor: Use LGExtractor :application/ogg 
08-15 17:21:11.037  1036  1440 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:21:11.038  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:21:11.038  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:21:11.039  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:21:11.039  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:21:11.039  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-15 17:21:11.040  7631  7631 D UEI.SmartControl: QS Service created
08-15 17:21:11.040  1036  1519 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-15 17:21:11.040  1036  1519 D ConnectivityService: identical MTU - not setting
08-15 17:21:11.040  1036  1519 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-15 17:21:11.040  1036  1519 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-15 17:21:11.041  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:11.041  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:21:11.041  1036  1519 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:21:11.041  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-15 17:21:11.045  8120  8120 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-15 17:21:11.047  8120  8120 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-15 17:21:11.047  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-15 17:21:11.063  8120  8120 V LGMDMManager: Create singleton instance
08-15 17:21:11.064  7631  7631 I UEI.SmartControl: Service initServices...
08-15 17:21:11.064  7631  7631 D UEI.SmartControl: QS start get config
08-15 17:21:11.075   313  1397 V LGParserOSAL: supported mime: application/ogg
08-15 17:21:11.075   313  1397 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-15 17:21:11.075   313  1397 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-15 17:21:11.075   313  1397 V AwesomePlayer: mBitrate = -1 bits/sec
08-15 17:21:11.075   313  1397 V AwesomePlayer: AudioTrack Setting
08-15 17:21:11.075   313  1397 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-15 17:21:11.075   313  1397 V AwesomePlayer: setAudioSource() 
08-15 17:21:11.075   313  1397 V MediaPlayerService: prepare
,08-15 17:21:11.075   313  1397 V AwesomePlayer: prepareAsync_l() 
08-15 17:21:11.075   313  1397 V MediaPlayerService: wait for prepare
08-15 17:21:11.075   313  8165 V AwesomePlayer: onPrepareAsyncEvent() 
08-15 17:21:11.075   313  8165 V AwesomePlayer: initAudioDecoder() 
08-15 17:21:11.075   313  8165 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-15 17:21:11.075   313  8165 V AudioSystem: isOffloadSupported()
08-15 17:21:11.075   313  8165 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-15 17:21:11.075   313  8165 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-15 17:21:11.075   313  8165 I AudioFlinger: isAudioPlaybackHookOn() false
08-15 17:21:11.075   313  8165 V AwesomePlayer: getUseOffload() = 0 
08-15 17:21:11.075   313  8165 V OMXCodec: OMXCodec::Create
08-15 17:21:11.075   313  8165 V OMXCodec: findMatchingCodecs()
08-15 17:21:11.075   313  8165 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-15 17:21:11.075   313  8165 V OMXCodec: matchingCodecs.size()=1
08-15 17:21:11.075   313  8165 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-15 17:21:11.077   313  8165 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-15 17:21:11.077   313  8165 V LGCodecAdapter: LG Codec Adapter start
08-15 17:21:11.077   313  8165 V OMXCodec: OMXCodec Createtor
08-15 17:21:11.077   313  8165 V OMXCodec: setComponentRole
,08-15 17:21:11.077   313  8165 V OMXCodec: configureCodec protected=0
08-15 17:21:11.077   313  8165 V LGCodecAdapter: called getLGCodecSpecificData
08-15 17:21:11.077   313  8165 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-15 17:21:11.077   313  8165 V LGCodecOSAL: Called LGconfigureCodecMETA
08-15 17:21:11.077   313  8165 V LGCodecOSAL: Called LGconfigureCodecMSG
,08-15 17:21:11.077   313  8165 V LGCodecOSAL: Not support LGCodec
08-15 17:21:11.077   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-15 17:21:11.077   313  8165 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-15 17:21:11.077   313  8165 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-15 17:21:11.077   313  8165 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-15 17:21:11.077   313  8165 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-15 17:21:11.077   313  8165 V AudioSystem: isOffloadSupported()
08-15 17:21:11.077   313  8165 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-15 17:21:11.077   313  8165 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-15 17:21:11.077   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-15 17:21:11.077   313  8165 V OMXCodec: init()
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
,08-15 17:21:11.078   313  8165 V OMXCodec: allocateBuffers
08-15 17:21:11.078   313  8165 V OMXCodec: allocateBuffersOnPort portIndex=0
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-15 17:21:11.078   313  8165 V OMXCodec: allocateBuffersOnPort portIndex=1
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
,08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-15 17:21:11.078   313  8165 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-15 17:21:11.078   313  8165 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-15 17:21:11.078   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-15 17:21:11.078   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-15 17:21:11.078   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-15 17:21:11.078   313  8165 V OMXCodec: init() mAsyncCompletion wait!!! 
08-15 17:21:11.078   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-15 17:21:11.078   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-15 17:21:11.078   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-15 17:21:11.079   313  8165 V OMXCodec: init() mAsyncCompletion wait free! 
08-15 17:21:11.079   313  8165 V AwesomePlayer: finishAsyncPrepare_l() 
08-15 17:21:11.079   313  8165 V AudioCache: notify(0xb54748c0, 5, 0, 0)
08-15 17:21:11.079   313  8165 V AudioCache: ignored
08-15 17:21:11.079   313  8165 V AudioCache: notify(0xb54748c0, 1, 0, 0)
08-15 17:21:11.079   313  8165 V AudioCache: prepared
08-15 17:21:11.079   313  1397 V AudioCache: wait - success
08-15 17:21:11.079   313  1397 V MediaPlayerService: start
08-15 17:21:11.079   313  1397 V AwesomePlayer: play_l() 
08-15 17:21:11.079   313  1397 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-15 17:21:11.079   313  1397 V AwesomePlayer: createAudioPlayer_l
08-15 17:21:11.079   313  1397 V AwesomePlayer: seekAudioIfNecessary_l() 
08-15 17:21:11.079   313  1397 V AwesomePlayer: startAudioPlayer_l() 
08-15 17:21:11.079   313  1397 D AudioPlayer: start of Playback, useOffload 0
08-15 17:21:11.079   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-15 17:21:11.079   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:21:11.082   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-15 17:21:11.083   313  8167 V OMXCodec: allocateBuffersOnPort portIndex=1
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-15 17:21:11.083   313  8167 V OMXCod,ec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1290 on output port
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-15 17:21:11.083   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-15 17:21:11.085   313  1397 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-15 17:21:11.086   313  1397 V AudioCache: notify(0xb54748c0, 6, 0, 0)
08-15 17:21:11.086   313  1397 V AudioCache: ignored
08-15 17:21:11.086   313  1397 V MediaPlayerService: wait for playback complete
08-15 17:21:11.087   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.087   313  8168 V AudioCache: memcpy(0xac300000, 0xb040d000, 4096)
08-15 17:21:11.089   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.089   313  8168 V AudioCache: memcpy(0xac301000, 0xb040d000, 4096)
08-15 17:21:11.092   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.092   313  8168 V AudioCache: memcpy(0xac302000, 0xb040d000, 4096)
08-15 17:21:11.093   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.093   313  8168 V AudioCache: memcpy(0xac303000, 0xb040d000, 4096)
08-15 17:21:11.094   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.094   313  8168 V AudioCache: memcpy(0xac304000, 0xb040d000, 4096)
08-15 17:21:11.094   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.094   313  8168 V AudioCache: memcpy(0xac305000, 0xb040d000, 4096)
08-15 17:21:11.095   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.095   313  8168 V AudioCache: memcpy(0xac306000, 0xb040d000, 4096)
08-15 17:21:11.096   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.096   313  8168 V AudioCache: memcpy(0xac307000, 0xb040d000, 4096)
08-15 17:21:11.096   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.096   313  8168 V AudioCache: memcpy(0xac308000, 0xb040d000, 4096)
,08-15 17:21:11.097   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.097   313  8168 V AudioCache: memcpy(0xac309000, 0xb040d000, 4096)
08-15 17:21:11.098   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.098   313  8168 V AudioCache: memcpy(0xac30a000, 0xb040d000, 4096)
08-15 17:21:11.098   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.098   313  8168 V AudioCache: memcpy(0xac30b000, 0xb040d000, 4096)
08-15 17:21:11.099   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.099   313  8168 V AudioCache: memcpy(0xac30c000, 0xb040d000, 4096)
08-15 17:21:11.099   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.099   313  8168 V AudioCache: memcpy(0xac30d000, 0xb040d000, 4096)
08-15 17:21:11.099   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.099   313  8168 V AudioCache: memcpy(0xac30e000, 0xb040d000, 4096)
08-15 17:21:11.099   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.099   313  8168 V AudioCache: memcpy(0xac30f000, 0xb040d000, 4096)
08-15 17:21:11.101   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.101   313  8168 V AudioCache: memcpy(0xac310000, 0xb040d000, 4096)
08-15 17:21:11.101   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.101   313  8168 V AudioCache: memcpy(0xac311000, 0xb040d000, 4096)
08-15 17:21:11.102   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.102   313  8168 V AudioCache: memcpy(0xac312000, 0xb040d000, 4096)
08-15 17:21:11.102   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.102   313  8168 V AudioCache: memcpy(0xac313000, 0xb040d000, 4096)
08-15 17:21:11.105   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.105   313  8168 V AudioCache: memcpy(0xac314000, 0xb040d000, 4096)
08-15 17:21:11.105   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.105   313  8168 V AudioCache: memcpy(0xac315000, 0xb040d000, 4096)
08-15 17:21:11.105   313  8168 V AudioCache: write(0xb040d000, 4096)
,08-15 17:21:11.105   313  8168 V AudioCache: memcpy(0xac316000, 0xb040d000, 4096)
08-15 17:21:11.105   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.105   313  8168 V AudioCache: memcpy(0xac317000, 0xb040d000, 4096)
08-15 17:21:11.107   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.107   313  8168 V AudioCache: memcpy(0xac318000, 0xb040d000, 4096)
08-15 17:21:11.107   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.107   313  8168 V AudioCache: memcpy(0xac319000, 0xb040d000, 4096)
08-15 17:21:11.108   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.108   313  8168 V AudioCache: memcpy(0xac31a000, 0xb040d000, 4096)
08-15 17:21:11.108   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.108   313  8168 V AudioCache: memcpy(0xac31b000, 0xb040d000, 4096)
08-15 17:21:11.109   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.109   313  8168 V AudioCache: memcpy(0xac31c000, 0xb040d000, 4096)
08-15 17:21:11.110   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.110   313  8168 V AudioCache: memcpy(0xac31d000, 0xb040d000, 4096)
08-15 17:21:11.110   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.110   313  8168 V AudioCache: memcpy(0xac31e000, 0xb040d000, 4096)
08-15 17:21:11.111   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.111   313  8168 V AudioCache: memcpy(0xac31f000, 0xb040d000, 4096)
08-15 17:21:11.111   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.111   313  8168 V AudioCache: memcpy(0xac320000, 0xb040d000, 4096)
08-15 17:21:11.112   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.112   313  8168 V AudioCache: memcpy(0xac321000, 0xb040d000, 4096)
08-15 17:21:11.112   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.112   313  8168 V AudioCache: memcpy(0xac322000, 0xb040d000, 4096)
08-15 17:21:11.113   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.113   313  8168 V AudioCache: memcpy(0xac323000, 0xb040d000, 4096)
08-15 17:21:11.113   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.113   313  8168 V AudioCache: memcpy(0xac324000, 0xb040d000, 4096)
08-15 17:21:11.114   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.114   313  8168 V AudioCache: memcpy(0xac325000, 0xb040d000, 4096)
08-15 17:21:11.115   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.115   313  8168 V AudioCache: memcpy(0xac326000, 0xb040d000, 4096)
08-15 17:21:11.115   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.115   313  8168 V AudioCache: memcpy(0xac327000, 0xb040d000, 4096)
08-15 17:21:11.116   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.116   313  8168 V AudioCache: memcpy(0xac328000, 0xb040d000, 4096)
08-15 17:21:11.117   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.117   313  8168 V AudioCache: memcpy(0xac329000, 0xb040d000, 4096)
08-15 17:21:11.118   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.118   313  8168 V AudioCache: memcpy(0xac32a000, 0xb040d000, 4096)
08-15 17:21:11.118   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.119   313  8168 V AudioCache: memcpy(0xac32b000, 0xb040d000, 4096)
08-15 17:21:11.119   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.119   313  8168 V AudioCache: memcpy(0xac32c000, 0xb040d000, 4096)
08-15 17:21:11.120   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.120   313  8168 V AudioCache: memcpy(0xac32d000, 0xb040d000, 4096)
08-15 17:21:11.120   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.120   313  8168 V AudioCache: memcpy(0xac32e000, 0xb040d000, 4096)
08-15 17:21:11.121   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.121   313  8168 V AudioCache: memcpy(0xac32f000, 0xb040d000, 4096)
08-15 17:21:11.122   313  8168 V AudioCache: write(0xb040d000, 4096)
08-15 17:21:11.122   313  8168 V AudioCache: memcpy(0xac330000, 0xb040d000, 4096)
08-15 17:21:11.122   313  8168 V Au,dioCache: write(0xb040d000, 4096)
08-15 17:21:11.122   313  8168 V AudioCache: memcpy(0xac331000, 0xb040d000, 4096)
08-15 17:21:11.122   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-15 17:21:11.123   313  8168 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-15 17:21:11.123   313  8168 V AwesomePlayer: postAudioEOS() 
08-15 17:21:11.123   313  8168 V AudioCache: write(0xb040d000, 280)
08-15 17:21:11.123   313  8168 V AudioCache: memcpy(0xac332000, 0xb040d000, 280)
08-15 17:21:11.124   313  8165 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-15 17:21:11.124   313  8165 V AwesomePlayer: onStreamDone
08-15 17:21:11.124   313  8165 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-15 17:21:11.124   313  8165 V AudioCache: notify(0xb54748c0, 2, 0, 0)
08-15 17:21:11.124   313  8165 V AudioCache: playback complete
08-15 17:21:11.124   313  8165 V AwesomePlayer: pause_l() 
08-15 17:21:11.124   313  8165 V AudioCache: notify(0xb54748c0, 7, 0, 0)
08-15 17:21:11.124   313  8165 V AudioCache: ignored
08-15 17:21:11.124   313  8165 V AwesomePlayer: cancelPlayerEvents
08-15 17:21:11.124   313  8165 D AudioPlayer: Pause Playback at 1068125
08-15 17:21:11.124   313  1397 V AudioCache: wait - success
08-15 17:21:11.124   313  1397 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-15 17:21:11.125   313  1397 V AwesomePlayer: reset_l() 
08-15 17:21:11.125   313  1397 V AudioCache: notify(0xb54748c0, 8, 0, 0)
08-15 17:21:11.125   313  1397 V AudioCache: ignored
08-15 17:21:11.125   313  1397 V AwesomePlayer: cancelPlayerEvents
08-15 17:21:11.125   313  1397 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-15 17:21:11.125   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-15 17:21:11.125   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-15 17:21:11.125   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-15 17:21:11.125   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-15 17:21:11.125   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1290 on port 1
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
,08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-15 17:21:11.126   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
,08-15 17:21:11.127   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-15 17:21:11.127   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-15 17:21:11.127   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-15 17:21:11.127   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-15 17:21:11.127   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-15 17:21:11.127   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-15 17:21:11.127   313  8167 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-15 17:21:11.127   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-15 17:21:11.127   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-15 17:21:11.127   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-15 17:21:11.128   313  1397 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-15 17:21:11.128   313  1397 D AudioPlayer: AudioPlayer releasing audio source
08-15 17:21:11.128   313  1397 D AudioPlayer: AudioPlayer done releasing audio source
08-15 17:21:11.128   313  1397 V AwesomePlayer: reset_l() 
08-15 17:21:11.128   313  1397 V AwesomePlayer: cancelPlayerEvents
08-15 17:21:11.128   313  1397 V AwesomePlayer: ~AwesomePlayer call
08-15 17:21:11.128   313  1397 V AwesomePlayer: reset_l() 
08-15 17:21:11.128   313  1397 V AwesomePlayer: cancelPlayerEvents
08-15 17:21:11.129  8120  8164 V SoundPool: close(31)
08-15 17:21:11.129  8120  8164 V SoundPool: pointer = 0x9fe7f000, size = 205080, sampleRate = 48000, numChannels = 2
08-15 17:21:11.140  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-15 17:21:11.141  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-15 17:21:11.143  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6745
,08-15 17:21:11.146  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:11.170  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 17:21:11.172  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:11.174  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:11.175  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:11.177  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:11.179  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:11.181  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:11.183  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-15 17:21:11.185  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-15 17:21:11.336  7631  7631 I UEI.SmartControl: Supports setup maps: true
,08-15 17:21:11.339  7631  7631 D UEI.SmartControl: QS start statue = true Error code = 0
,08-15 17:21:11.339  7631  7631 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-15 17:21:11.339  7631  7631 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-15 17:21:11.339  7631  7631 I UEI.SmartControl: ### init IR Blaster...
08-15 17:21:11.343  7631  7631 D serial_port: Configuring serial port
08-15 17:21:11.343  7631  7631 E UEI.SmartControl: UEIBLaster setting for 616
08-15 17:21:11.343  7631  7631 I UEI.SmartControl: Setting serial record hearder size = 2
08-15 17:21:11.343  7631  7631 I UEI.SmartControl: configuring settings for MAXQ616
08-15 17:21:11.343  7631  7631 I UEI.SmartControl: Get version...
08-15 17:21:11.361  7631  8170 D UEI.SmartControl: serial port data available: 21
,08-15 17:21:11.388  7631  7631 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-15 17:21:11.388  7631  7631 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-15 17:21:11.388  7631  7631 I UEI.SmartControl: QS saving settings...
08-15 17:21:11.390  7631  7631 D UEI.SmartControl: IR Blaster version: 25672567
,08-15 17:21:11.408  7631  8170 D UEI.SmartControl: serial port data available: 4
,08-15 17:21:11.439  7631  8176 I UEI.SmartControl: Device manager: loading config....
08-15 17:21:11.439  7631  8176 D UEI.SmartControl: ----------- loading internal config...
08-15 17:21:11.440  7631  7631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-15 17:21:11.443  7631  7631 E UEI.SmartControl: Services init done
08-15 17:21:11.443  7631  7631 D UEI.SmartControl: QS Service init finished
08-15 17:21:11.447  7631  7631 D UEI.SmartControl: QS Service version name: 2.1.91
08-15 17:21:11.447  7631  7631 D UEI.SmartControl: QS Service version code: 201091
08-15 17:21:11.448  7631  7631 D UEI.SmartControl: Service requested: Control
08-15 17:21:11.454  7631  7631 D UEI.SmartControl: Request IControl service: devices are loaded...
08-15 17:21:11.454  7631  8176 E UEI.SmartControl: Loading SETTINGS...
08-15 17:21:11.457  8120  8120 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-15 17:21:11.463  7631  7631 D UEI.SmartControl: Internal service binding...
08-15 17:21:11.464  7631  7646 I UEI.SmartControl: ------ IControl API: 11
08-15 17:21:11.464  7631  7646 D UEI.SmartControl: File observer start...
08-15 17:21:11.465  7631  7646 E UEI.SmartControl: IR Port is disabled: false
08-15 17:21:11.465  7631  7646 D UEI.SmartControl: Starting file observer...
,08-15 17:21:11.466  7631  7646 I UEI.SmartControl: Registering callback...
08-15 17:21:11.467  7631  7646 I UEI.SmartControl: ------ IControl API: 19
08-15 17:21:11.467  7631  7646 I UEI.SmartControl: Registering Services Ready callback...
08-15 17:21:11.469  7631  8176 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-15 17:21:11.483  7631  8175 I UEI.SmartControl: Notify AllClients services are ready: 0
08-15 17:21:11.485  8120  8135 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-15 17:21:11.486  7631  8175 D UEI.SmartControl: -----service ready thread exits
08-15 17:21:11.487  8120  8162 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-15 17:21:11.488  8120  8162 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-15 17:21:11.489  8120  8120 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-15 17:21:11.490  8120  8120 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-15 17:21:11.490  7631  7647 I UEI.SmartControl: ------ IControl API: 8
08-15 17:21:11.493  8120  8120 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-15 17:21:11.493  8120  8120 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-15 17:21:11.494  8120  8120 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-15 17:21:11.494  8120  8120 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-15 17:21:11.496  8120  8120 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-15 17:21:11.498  8120  8120 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-15 17:21:11.501  8120  8120 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-15 17:21:11.506  8120  8120 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-15 17:21:11.508  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-15 17:21:11.510  8120  8120 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-15 17:21:11.510  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-15 17:21:11.512  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-15 17:21:11.515  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-15 17:21:11.517  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-15 17:21:11.519  8120  8120 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471274471518]
08-15 17:21:11.521  8120  8120 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-15 17:21:11.526  1036  2025 I ActivityManager: Killing 7217:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-15 17:21:11.554  8120  8178 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-15 17:21:11.663  1036  1905 W libprocessgroup: failed to open /acct/uid_10005/pid_7217/cgroup.procs: No such file or directory
,08-15 17:21:11.665  8120  8120 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-15 17:21:11.666  8120  8120 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-15 17:21:11.669  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-15 17:21:11.670  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-15 17:21:11.670  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-15 17:21:11.671  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-15 17:21:11.672  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-15 17:21:11.697  8120  8120 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-15 17:21:12.554  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-15 17:21:12.554  6708  6776 I jxcore-log: 
,08-15 17:21:12.602  1036  1440 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=75.5, 0.0, 0.0  rx=72.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1899309926] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 17:21:12.605  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=75.5, 0.0, 0.0  rx=72.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1899309924] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 17:21:12.605  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-15 17:21:12.624  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-15 17:21:12.651  1036  1467 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-15 17:21:12.681  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
08-15 17:21:12.686  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-15 17:21:12.687  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-15 17:21:12.698  8050  8146 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-15 17:21:12.703  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-15 17:21:12.707  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-15 17:21:12.712  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-15 17:21:12.712  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-15 17:21:12.712  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-15 17:21:12.712  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-15 17:21:12.712  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-15 17:21:12.712  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:12.712  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-15 17:21:12.712  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-15 17:21:12.713  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-15 17:21:12.727  5274  5274 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-15 17:21:12.761  2175  2175 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-15 17:21:12.771  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-15 17:21:12.771  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:21:12.771  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-15 17:21:12.771  7015  7015 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-15 17:21:12.773   308  8192 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-15 17:21:12.773   308  8192 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-15 17:21:12.774  1036  1991 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-15 17:21:12.776  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:12.781  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
08-15 17:21:12.784  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c24f5d5
08-15 17:21:12.784  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 17:21:12.784  7015  7015 D AppUp4:CustFacade: isPhone : true
08-15 17:21:12.784  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
08-15 17:21:12.784  7015  7015 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-15 17:21:12.791  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-15 17:21:12.791  4291  4291 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-15 17:21:12.792  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:21:12.794  4291  4291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-15 17:21:12.797  2842  2842 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-15 17:21:12.799  2842  2842 V DownloadManager: DownloadService onCreate
08-15 17:21:12.800  4291  8201 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-15 17:21:12.802  2842  8203 I DownloadManager: in removeSpuriousFiles
08-15 17:21:12.802  2842  8203 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-15 17:21:12.803  2842  8203 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2a43969 on behalf of 2842
08-15 17:21:12.803  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-15 17:21:12.803  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-15 17:21:12.803  4291  8201 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-15 17:21:12.804  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-15 17:21:12.804  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-15 17:21:12.804  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-15 17:21:12.804  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-15 17:21:12.804  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-15 17:21:12.804  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-15 17:21:12.804  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-15 17:21:12.804  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-15 17:21:12.804  2842  8203 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-15 17:21:12.804  2842  8203 I DownloadManager: in trimDatabase
08-15 17:21:12.805  2842  8203 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null;, sort is lastmod.
08-15 17:21:12.805  2842  8203 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@39a09fee on behalf of 2842
,08-15 17:21:12.809  4291  8202 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-15 17:21:12.809  4291  8202 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-15 17:21:12.812   308  8192 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-15 17:21:12.843  1036  1991 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8208 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-15 17:21:12.847  2842  2842 V DownloadManager: DownloadService onStartCommand
08-15 17:21:12.852   308   893 D LGDataListener: argv[0]=dsqncommand
08-15 17:21:12.852   308   893 D LGDataListener: argv[1]=wlan0
08-15 17:21:12.852   308   893 D LGDataListener: argv[2]=1
08-15 17:21:12.852   308   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-15 17:21:12.853  4291  8201 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-15 17:21:12.853  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-15 17:21:12.853  1036  1116 D DSQN    : start to monitor internet connection
08-15 17:21:12.856  2842  8204 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,08-15 17:21:12.870  4291  4291 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-15 17:21:12.871  4291  4291 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-15 17:21:12.871  4291  4291 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-15 17:21:12.873  4291  4291 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-15 17:21:12.877  4291  4291 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-15 17:21:12.878  2842  8204 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@323e0325 on behalf of 2842
08-15 17:21:12.881  2842  8204 V DownloadManager: processing inserted download 1
08-15 17:21:12.882  2842  8204 V DownloadManager: processing inserted download 4
08-15 17:21:12.884  2842  8204 V DownloadManager: processing inserted download 7
08-15 17:21:12.885  2842  8204 V DownloadManager: processing inserted download 8
08-15 17:21:12.886  2842  8204 V DownloadManager: processing inserted download 9
,08-15 17:21:12.892  2842  8204 V DownloadManager: processing inserted download 10
08-15 17:21:12.894  2842  8204 V DownloadManager: processing inserted download 11
08-15 17:21:12.896  2842  8204 V DownloadManager: processing inserted download 12
08-15 17:21:12.897  2842  8204 V DownloadManager: processing inserted download 13
08-15 17:21:12.899  2842  8204 V DownloadManager: processing inserted download 14
08-15 17:21:12.900  2842  8204 V DownloadManager: processing inserted download 16
08-15 17:21:12.902  8208  8208 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 17:21:12.902  8208  8208 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 17:21:12.903  2842  2842 V DownloadManager: DownloadService onDestroy
08-15 17:21:12.903  8208  8208 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-15 17:21:12.903  8208  8208 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-15 17:21:12.962  8208  8208 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-15 17:21:12.991  8208  8208 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-15 17:21:13.032  8208  8208 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-15 17:21:13.069  8208  8208 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:21:13.069  8208  8208 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:21:13.201  8208  8208 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-15 17:21:13.234  8208  8208 I HubEmail: JNI_OnLoad()
08-15 17:21:13.234  8208  8208 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-15 17:21:13.234  8208  8208 I HubEmail: registerNatives()
,08-15 17:21:13.234  8208  8208 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-15 17:21:13.234  8208  8208 I HubEmail: registerNativeMethods()
08-15 17:21:13.234  8208  8208 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-15 17:21:13.234  8208  8208 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-15 17:21:13.249  8208  8241 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-15 17:21:13.268  3396  3396 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-15 17:21:13.268  3396  3396 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-15 17:21:13.268  3396  3396 I LgeMiscReceiver: networkInfo.isConnected() = true
08-15 17:21:13.268  3396  3396 D PhoneState: setPdpRejectCasuse : false
,08-15 17:21:13.276   308  8244 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-15 17:21:13.276   308  8244 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-15 17:21:13.304  1036  2025 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8245 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-15 17:21:13.325   308  8244 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-15 17:21:13.367  7983  8240 V FormManager: There are no updated forms. The schedule will be deleted.
,08-15 17:21:13.371  7983  8240 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-15 17:21:13.387  1036  2032 I ActivityManager: Killing 7660:com.google.android.talk/u0a72 (adj 15): empty #17
,08-15 17:21:13.389  8245  8245 D LgDataFeature: LgDataFeature() Constructor: none
,08-15 17:21:13.389  8245  8245 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 17:21:13.391  8245  8245 D PhoneMonitor: Register our PhoneStateListener
08-15 17:21:13.416  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-15 17:21:13.416  6708  6776 I jxcore-log: 
,08-15 17:21:13.441  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-15 17:21:13.441  6708  6776 I jxcore-log: 
,08-15 17:21:13.560  1036  1051 W libprocessgroup: failed to open /acct/uid_10072/pid_7660/cgroup.procs: No such file or directory
,08-15 17:21:13.586  8245  8245 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-15 17:21:13.588  8245  8245 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-15 17:21:13.631  8245  8245 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-15 17:21:13.632  8245  8245 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-15 17:21:13.632  8245  8245 D TelephonyAutoProfiling: [parse] Load xml
08-15 17:21:13.635  8245  8245 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-15 17:21:13.635  8245  8245 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-15 17:21:13.635  8245  8245 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-15 17:21:13.644  8245  8245 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-15 17:21:13.647  1036  1956 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8270 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-15 17:21:13.648  1036  1956 I ActivityManager: Killing 7711:com.android.contacts/u0a19 (adj 15): empty #17
,08-15 17:21:13.739  1036  1379 V AlarmManager: RTC_WAKEUP set : Alarm{2b8e9478 type 0 when 1471274463901 com.google.android.gms} when 1471274463901
,08-15 17:21:13.751  1036  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{9c1f751 type 2 when 360527 com.google.android.gms} when 360527
08-15 17:21:13.751  1036  1052 W libprocessgroup: failed to open /acct/uid_10019/pid_7711/cgroup.procs: No such file or directory
,08-15 17:21:13.778  1816  8287 I CheckinService: active receiver: enabled
,08-15 17:21:13.792  1816  8287 I CheckinService: Preparing to send checkin request
08-15 17:21:13.792  1816  8287 I EventLogService: Accumulating logs since 1471274452495
08-15 17:21:13.831  1816  8287 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-15 17:21:13.863   308  8290 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-15 17:21:13.863   308  8290 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-15 17:21:13.895   308  8290 D libc-netbsd: res_queryN name = www.google.com succeed
,08-15 17:21:13.897  1036  1603 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8291 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-15 17:21:13.899  1036  1603 I ActivityManager: Killing 7738:com.android.gallery3d/u0a27 (adj 15): empty #17
08-15 17:21:13.903   308  8305 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-15 17:21:13.903   308  8305 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-15 17:21:13.933   308  8305 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-15 17:21:13.995  1036  1468 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-15 17:21:14.009  1036  1905 W libprocessgroup: failed to open /acct/uid_10027/pid_7738/cgroup.procs: No such file or directory
,08-15 17:21:14.121  1036  1976 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8310 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-15 17:21:14.168  1036  1576 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8327 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-15 17:21:14.169  1036  1576 I ActivityManager: Killing 7761:com.android.vending/u0a44 (adj 15): empty #17
,08-15 17:21:14.342  1036  1051 W libprocessgroup: failed to open /acct/uid_10044/pid_7761/cgroup.procs: No such file or directory
,08-15 17:21:14.378  8310  8310 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-15 17:21:14.378  8310  8310 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-15 17:21:14.395  8327  8327 I art     : Almond Protected OAT
,08-15 17:21:14.413  8310  8310 I MultiDex: VM with version 2.1.0 has multidex support
08-15 17:21:14.413  8310  8310 I MultiDex: install
08-15 17:21:14.413  8310  8310 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-15 17:21:14.428  8310  8310 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-15 17:21:14.563  1036  2025 I art     : Explicit concurrent mark sweep GC freed 74088(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 3.184ms total 143.216ms
,08-15 17:21:14.566  8327  8327 D WeatherApplication: removeAccount
08-15 17:21:14.568  8327  8327 D WeatherApplication: Account.length = 0
08-15 17:21:14.568  8327  8327 E WeatherApplication: OPERATOR:OPEN
08-15 17:21:14.577  8327  8327 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:14
,08-15 17:21:14.592  8327  8327 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-15 17:21:14.592  8327  8327 D Weather.Utils: 2 : All the weather widget is gone.
,08-15 17:21:14.595  8327  8327 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-15 17:21:14.598  8327  8327 D WeatherAncestor: connectivity changed - connection : true
08-15 17:21:14.599  8327  8327 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-15 17:21:14.606  8327  8327 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-15 17:21:14.606  8327  8327 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-15 17:21:14.606  8327  8327 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-15 17:21:14.624  8327  8327 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-15 17:21:14.624  8327  8327 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:21:14
08-15 17:21:14.667  1036  1051 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8346 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-15 17:21:14.668  1036  1051 I ActivityManager: Killing 7801:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-15 17:21:14.685  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-15 17:21:14.685  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-15 17:21:14.690   308  8357 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-15 17:21:14.690   308  8357 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-15 17:21:14.690   308  8357 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-15 17:21:14.759  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 15 Aug 2016 15:21:14 GMT], X-Android-Received-Millis=[1471274474759], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471274474727]}
08-15 17:21:14.759  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-15 17:21:14.759  1036  8070 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-15 17:21:14.759  1036  1519 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-15 17:21:14.760  1036  1519 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-15 17:21:14.760  1036  1519 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:21:14.760  1036  1519 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-15 17:21:14.760  1036  1519 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-15 17:21:14.760  1036  1519 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-15 17:21:14.760  1036  1519 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-15 17:21:14.760  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:14.760  1036  1519 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:21:14.760  1036  1519 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-15 17:21:14.760  1036  1519 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:14.760  1036  1519 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-15 17:21:14.761  1604  2070 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-15 17:21:14.761  1036  1440 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:14.761  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-15 17:21:14.761  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-15 17:21:14.762  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-15 17:21:14.850  8364  8364 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-15 17:21:14.852  1036  1905 W libprocessgroup: failed to open /acct/uid_10080/pid_7801/cgroup.procs: No such file or directory
,08-15 17:21:14.901  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-15 17:21:14.904  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:14.906  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-15 17:21:14.913  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-15 17:21:14.913  6708  6776 I jxcore-log: 
,08-15 17:21:14.923  8364  8364 I dex2oat : dex2oat took 72.449ms (threads: 4)
08-15 17:21:14.937  8310  8325 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 17:21:14.937  8310  8325 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 17:21:14.937  8310  8325 I Adreno-EGL: Build Date: 12/12/14 금
08-15 17:21:14.937  8310  8325 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 17:21:14.937  8310  8325 I Adreno-EGL: Remote Branch: 
08-15 17:21:14.937  8310  8325 I Adreno-EGL: Local Patches: 
08-15 17:21:14.937  8310  8325 I Adreno-EGL: Reconstruct Branch: 
,08-15 17:21:14.972   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 17:21:14.972   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-15 17:21:14.972   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
,08-15 17:21:14.973  8346  8371 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-15 17:21:14.975   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 17:21:14.975   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-15 17:21:14.975   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
08-15 17:21:14.975  8346  8371 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-15 17:21:14.985   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 17:21:14.985   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-15 17:21:14.985   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
,08-15 17:21:14.991  8346  8374 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-15 17:21:14.997   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-15 17:21:14.997   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-15 17:21:14.997   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
,08-15 17:21:15.000  8346  8374 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-15 17:21:15.078  8310  8325 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:21:15.078  8310  8325 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:21:15.151  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-15 17:21:15.151  6708  6776 I jxcore-log: 
,08-15 17:21:15.155  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-15 17:21:15.155  6708  6776 I jxcore-log: 
,08-15 17:21:15.171  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-15 17:21:15.171  6708  6776 I jxcore-log: 
,08-15 17:21:15.175  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-15 17:21:15.175  6708  6776 I jxcore-log: 
08-15 17:21:15.195  8346  8346 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-15 17:21:15.206  8346  8346 I LibraryLoader: Loading: webviewchromium
,08-15 17:21:15.209  8346  8346 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2149-2152)
08-15 17:21:15.209  8346  8346 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-15 17:21:15.215  8346  8346 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1376b954}
08-15 17:21:15.216  8346  8346 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-15 17:21:15.217  8346  8346 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-15 17:21:15.226  8346  8346 I BrowserStartupController: Initializing chromium process, renderers=0
,08-15 17:21:15.227  8346  8346 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-15 17:21:15.236  8346  8346 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-15 17:21:15.238  8346  8346 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-15 17:21:15.239  8346  8346 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-15 17:21:15.251   313  2148 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10093
,08-15 17:21:15.257  8346  8396 W AudioManagerAndroid: Requires BLUETOOTH permission
08-15 17:21:15.258  8346  8346 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 17:21:15.258  8346  8346 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 17:21:15.258  8346  8346 I Adreno-EGL: Build Date: 12/12/14 금
08-15 17:21:15.258  8346  8346 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 17:21:15.258  8346  8346 I Adreno-EGL: Remote Branch: 
08-15 17:21:15.258  8346  8346 I Adreno-EGL: Local Patches: 
08-15 17:21:15.258  8346  8346 I Adreno-EGL: Reconstruct Branch: 
08-15 17:21:15.315  8346  8346 I NSApplication: Starting up...
,08-15 17:21:15.333  1036  1905 I ActivityManager: Killing 7442:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-15 17:21:15.452  1036  1576 W libprocessgroup: failed to open /acct/uid_10037/pid_7442/cgroup.procs: No such file or directory
,08-15 17:21:15.489  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-15 17:21:15.492   308  8411 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-15 17:21:15.493   308  8411 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-15 17:21:15.493   308  8411 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-15 17:21:15.505  2175  2175 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-15 17:21:15.506  2175  2175 D c       : Getting all permits...
08-15 17:21:15.506  2175  2175 D a       : Opening database...
08-15 17:21:15.509  2175  2175 D a       : Opening database auth.proximity.permit_store...
08-15 17:21:15.510  2175  2175 D a       : Closing database...
,08-15 17:21:15.583  8310  8325 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 17:21:15.583  8310  8325 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 17:21:15.583  8310  8325 I Adreno-EGL: Build Date: 12/12/14 금
08-15 17:21:15.583  8310  8325 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 17:21:15.583  8310  8325 I Adreno-EGL: Remote Branch: 
08-15 17:21:15.583  8310  8325 I Adreno-EGL: Local Patches: 
08-15 17:21:15.583  8310  8325 I Adreno-EGL: Reconstruct Branch: 
,08-15 17:21:15.632  1036  1440 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=40.2, 0.0, 0.0  rx=37.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1899306896] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 17:21:15.633  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=40.2, 0.0, 0.0  rx=37.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1899306895] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-15 17:21:15.633  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-15 17:21:15.659  8310  8325 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-15 17:21:15.659  8310  8325 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-15 17:21:15.659  8310  8325 I Adreno-EGL: Build Date: 12/12/14 금
08-15 17:21:15.659  8310  8325 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-15 17:21:15.659  8310  8325 I Adreno-EGL: Remote Branch: 
08-15 17:21:15.659  8310  8325 I Adreno-EGL: Local Patches: 
08-15 17:21:15.659  8310  8325 I Adreno-EGL: Reconstruct Branch: 
,08-15 17:21:15.748  2175  8415 D GCM     : Connected
,08-15 17:21:15.761   308  8417 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-15 17:21:15.761   308  8417 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-15 17:21:15.776  2175  8415 D GCM     : Message class com.google.e.a.a.q
,08-15 17:21:15.798   308  8417 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-15 17:21:15.878  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-15 17:21:15.878  6708  6776 I jxcore-log: 
,08-15 17:21:15.902  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-15 17:21:15.902  6708  6776 I jxcore-log: 
,08-15 17:21:15.912  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
,08-15 17:21:15.912  6708  6776 I jxcore-log: 
08-15 17:21:15.923  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-15 17:21:15.923  6708  6776 I jxcore-log: 
,08-15 17:21:15.997  1816  8287 I CheckinTask: Sending checkin request (9960 bytes)
,08-15 17:21:16.004  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-15 17:21:16.004  6708  6776 I jxcore-log: 
08-15 17:21:16.083  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-15 17:21:16.083  6708  6776 I jxcore-log: 
,08-15 17:21:16.113  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-15 17:21:16.113  6708  6776 I jxcore-log: 
,08-15 17:21:16.235  1816  8287 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-15 17:21:16.243  1816  8287 I CheckinService: active receiver: disabled
,08-15 17:21:16.270  1816  8424 I CheckinService: active receiver: disabled
,08-15 17:21:16.283  2175  2175 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-15 17:21:16.294  2175  2175 I GCM     : GCM config loaded
,08-15 17:21:16.307  8245  8245 V SetupWizard: Connected to Gservices successfully
,08-15 17:21:16.393  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-15 17:21:16.393  6708  6776 I jxcore-log: 
,08-15 17:21:16.418  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-15 17:21:16.418  6708  6776 I jxcore-log: 
,08-15 17:21:16.423  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-15 17:21:16.423  6708  6776 I jxcore-log: 
08-15 17:21:16.429  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-15 17:21:16.429  6708  6776 I jxcore-log: 
08-15 17:21:16.439  7631  8177 D UEI.SmartControl: Internal timer expired: 2
08-15 17:21:16.439  7631  8177 D UEI.SmartControl: unbind internal service
,08-15 17:21:16.447  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-15 17:21:16.447  6708  6776 I jxcore-log: 
08-15 17:21:16.469  7631  8171 D serial_port: close(fd = 24)
,08-15 17:21:16.475  7631  8171 I UEI.SmartControl: Serial port is closed.
,08-15 17:21:16.528  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-15 17:21:16.528  6708  6776 I jxcore-log: 
,08-15 17:21:16.540  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js,
08-15 17:21:16.540  6708  6776 I jxcore-log: 
,08-15 17:21:16.567  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-15 17:21:16.567  6708  6776 I jxcore-log: 
,08-15 17:21:16.580  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-15 17:21:16.580  6708  6776 I jxcore-log: 
,08-15 17:21:16.601  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-15 17:21:16.601  6708  6776 I jxcore-log: 
,08-15 17:21:16.635  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-15 17:21:16.635  6708  6776 I jxcore-log: 
,08-15 17:21:16.640  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-15 17:21:16.640  6708  6776 I jxcore-log: 
08-15 17:21:16.975  6708  6776 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-15 17:21:16.975  6708  6776 I jxcore-log: 
,08-15 17:21:16.986  6708  6776 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-15 17:21:16.987  6708  6776 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-15 17:21:16.987  6708  6776 I jxcore-log: 
08-15 17:21:17.055  6708  6776 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-15 17:21:17.055  6708  6776 I jxcore-log: 
,08-15 17:21:18.641  1036  1440 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=34.6, 0.0, 0.0  rx=29.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1899303888] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-15 17:21:18.644  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=34.6, 0.0, 0.0  rx=29.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1899303885] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 17:21:18.644  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-15 17:21:20.026  8346  8375 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-15 17:21:20.739  1036  2032 I ActivityManager: Killing 6909:com.lge.settings.easy/1000 (adj 15): empty #17
,08-15 17:21:20.770  1036  1940 W libprocessgroup: failed to open /acct/uid_1000/pid_6909/cgroup.procs: No such file or directory
,08-15 17:21:21.666  1036  1440 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=33.8, 0.0, 0.0  rx=28.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1899300862] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-15 17:21:21.678  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=33.8, 0.0, 0.0  rx=28.2 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1899300850] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 17:21:21.679  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-15 17:21:21.897  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-15 17:21:21.897  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-15 17:21:21.911  1941  2085 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-15 17:21:21.911  1941  2085 D LEDHandler: Battery Level Remaining: 100%
08-15 17:21:21.911  1941  2085 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
,08-15 17:21:21.914  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
08-15 17:21:21.914  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-15 17:21:21.915  1036  1498 D WifiController: battery changed pluggedType: 2
08-15 17:21:21.920  7603  7856 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-15 17:21:21.920  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-15 17:21:21.922  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:21.922  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:21.925  8032  8032 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-15 17:21:23.820  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-15 17:21:23.862  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-15 17:21:23.927  1036  1104 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8456 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-15 17:21:23.931  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-15 17:21:23.946   346   346 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 29.649ms
,08-15 17:21:23.968  1036  1036 D administrator: Handling package changes for user 0
,08-15 17:21:23.992   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.763ms total 41.344ms
,08-15 17:21:24.000  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-15 17:21:24.003  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-15 17:21:24.013  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-15 17:21:24.024   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 26.072ms
,08-15 17:21:24.065  8456  8456 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-15 17:21:24.083  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-15 17:21:24.083  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-15 17:21:24.136  8456  8456 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:21:24.136  8456  8456 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-15 17:21:24.150  1036  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-15 17:21:24.155  1036  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-15 17:21:24.163  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-15 17:21:24.165  2502  2502 V GmsNetworkLocationProvi: DISABLE
,08-15 17:21:24.198  1036  1101 D LocationProviderProxy: applying state to connected service
08-15 17:21:24.200  2502  2502 E GCoreFlp: Bound FusedProviderService with LocationManager
08-15 17:21:24.229  2175  2198 I art     : Explicit concurrent mark sweep GC freed 7269(470KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 1.208ms total 33.414ms
,08-15 17:21:24.253  8456  8502 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-15 17:21:24.253  8456  8502 I Babel   : MmsConfig.loadMmsSettings
08-15 17:21:24.255  8456  8502 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-15 17:21:24.255  8456  8502 I Babel   : MmsConfig.loadFromDatabase
,08-15 17:21:24.278  8456  8502 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-15 17:21:24.278  8456  8502 I Babel   : MmsConfig.loadFromResources
08-15 17:21:24.280  8456  8502 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-15 17:21:24.280  8456  8502 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-15 17:21:24.282  8456  8456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-15 17:21:24.286  8456  8500 W AudioCapabilities: Unsupported mime audio/evrc
,08-15 17:21:24.289  8456  8500 W AudioCapabilities: Unsupported mime audio/qcelp
08-15 17:21:24.291  8456  8500 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-15 17:21:24.304  8456  8500 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-15 17:21:24.309  1816  8503 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-15 17:21:24.309  1816  8503 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-15 17:21:24.309  8456  8500 W AudioCapabilities: Unsupported mime audio/qcelp
08-15 17:21:24.310  8456  8500 W AudioCapabilities: Unsupported mime audio/evrc
08-15 17:21:24.316  7015  7015 I AppUp4:CustModeStarterReceiver: onReceive
08-15 17:21:24.321  7015  7015 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c24f5d5
08-15 17:21:24.321  7015  7015 D AppUp4:CustFacade: isCustomizationCompleted : false
08-15 17:21:24.321  7015  7015 D AppUp4:CustFacade: isPhone : true
08-15 17:21:24.321  7015  7015 D AppUp4:CustModeStarterReceiver: begin check event
08-15 17:21:24.321  7015  7015 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-15 17:21:24.324  1816  4751 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-15 17:21:24.333  8456  8500 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-15 17:21:24.338  8456  8500 W VideoCapabilities: Unsupported mime video/divx
08-15 17:21:24.343  8456  8500 W VideoCapabilities: Unsupported mime video/divx311
08-15 17:21:24.345  8456  8500 W VideoCapabilities: Unsupported mime video/divx4
08-15 17:21:24.352  8456  8500 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-15 17:21:24.355  1036  2012 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8507 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-15 17:21:24.358  1036  1940 I ActivityManager: Killing 8032:com.lge.bnr/1000 (adj 15): empty #17
08-15 17:21:24.387  8456  8500 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-15 17:21:24.392  8456  8500 W AudioCapabilities: Unsupported mime audio/eac3
08-15 17:21:24.393  8456  8500 W AudioCapabilities: Unsupported mime audio/ac3
08-15 17:21:24.393  8456  8500 W AudioCapabilities: Unsupported mime audio/g726
08-15 17:21:24.394  8456  8500 W AudioCapabilities: Unsupported mime audio/wma-voice
08-15 17:21:24.395  8456  8500 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-15 17:21:24.396  8456  8500 W AudioCapabilities: Unsupported mime audio/adpcm
08-15 17:21:24.398  8456  8500 W VideoCapabilities: Unsupported mime video/theora
08-15 17:21:24.400  8456  8500 W VideoCapabilities: Unsupported mime video/mjpg
,08-15 17:21:24.428  1036  1956 W libprocessgroup: failed to open /acct/uid_1000/pid_8032/cgroup.procs: No such file or directory
,08-15 17:21:24.472  8507  8507 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-15 17:21:24.473  8507  8507 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 17:21:24.473  8507  8507 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-15 17:21:24.477  8507  8507 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-15 17:21:24.478  8507  8507 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-15 17:21:24.559  8507  8507 I SystemConfig: BUILD Country: EU
08-15 17:21:24.560  8507  8507 I SystemConfig: BUILD Operator: OPEN
,08-15 17:21:24.610  1036  1576 I ActivityManager: Killing 8004:com.lge.sync/1000 (adj 15): empty #17
,08-15 17:21:24.691  1036  1940 W libprocessgroup: failed to open /acct/uid_1000/pid_8004/cgroup.procs: No such file or directory
,08-15 17:21:24.699  1036  1440 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=17.4, 0.0, 0.0  rx=14.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1899297830] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 17:21:24.701  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=17.4, 0.0, 0.0  rx=14.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1899297827] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-15 17:21:24.701  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-15 17:21:24.709  8507  8525 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-15 17:21:24.709  8507  8525 I SystemConfig: existFile = false
08-15 17:21:24.710  8507  8525 I SystemConfig: canReadFile = false
08-15 17:21:24.710  8507  8525 I SystemConfig: systemFeature RCS result false
08-15 17:21:24.710  8507  8525 D SystemConfig: refreshRcsSupport() :false
08-15 17:21:24.738  1036  1576 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8530 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-15 17:21:24.792  8530  8530 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 17:21:24.792  8530  8530 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-15 17:21:24.793  8530  8530 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-15 17:21:24.793  8530  8530 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-15 17:21:24.846  6708  6776 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-15 17:21:24.846  6708  6776 I jxcore-log: 
,08-15 17:21:24.855  8530  8530 I AppConfig: Total System Memory = 2995761152
08-15 17:21:24.862  8530  8530 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-15 17:21:24.919  1036  2025 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8549 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-15 17:21:24.920  1036  2025 I ActivityManager: Killing 6840:com.android.settings/1000 (adj 15): empty #17
,08-15 17:21:25.007  1036  1940 W libprocessgroup: failed to open /acct/uid_1000/pid_6840/cgroup.procs: No such file or directory
,08-15 17:21:25.152  8552  8552 D AndroidRuntime: 
08-15 17:21:25.152  8552  8552 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-15 17:21:25.155  8552  8552 D AndroidRuntime: CheckJNI is OFF
08-15 17:21:25.207  8549  8549 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-15 17:21:25.286  8552  8552 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-15 17:21:25.297  1036  1104 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-15 17:21:25.297  1036  1104 I ActivityManager: Killing 6708:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-15 17:21:25.335  1036  1902 I WindowState: WIN DEATH: Window{2972db9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-15 17:21:25.336  8549  8549 D LgDataFeature: LgDataFeature() Constructor: none
08-15 17:21:25.336  8549  8549 D LgDataFeature: LgDataFeature() Constructor Done, null
08-15 17:21:25.337  1036  1498 D WifiService: Client connection lost with reason: 4
,08-15 17:21:25.344  1036  1902 D InputDispatcher: Window went away: Window{2972db9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-15 17:21:25.410  1036  1104 I ActivityManager:   Force finishing activity ActivityRecord{3a03bdfe u0 com.test.thalitest/.MainActivity t6}
,08-15 17:21:25.474   341   358 E GBMv2   : DFP En is all cleared set to be enabled
,08-15 17:21:25.479  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-15 17:21:25.481  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{3a03bdfe u0 com.test.thalitest/.MainActivity t6 f}
08-15 17:21:25.481  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{3a03bdfe u0 com.test.thalitest/.MainActivity t6 f}
,08-15 17:21:25.511  8549  8549 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-15 17:21:25.529  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-15 17:21:25.529  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ca8ca47 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-15 17:21:25.531  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-15 17:21:25.531  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b69f274 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-15 17:21:25.536  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-15 17:21:25.541  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-15 17:21:25.543  8549  8549 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-15 17:21:25.544  8549  8549 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-15 17:21:25.552  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-15 17:21:25.554  1036  1101 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-15 17:21:25.555  2502  2658 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-15 17:21:25.555  3774  3774 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-15 17:21:25.565  1036  2032 W ActivityManager: Spurious death for ProcessRecord{1fa0013c 6708:com.test.thalitest/u0a118}, curProc for 6708: null
08-15 17:21:25.570  7603  7603 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-15 17:21:25.570  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-15 17:21:25.572  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-15 17:21:25.572  4468  4468 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-15 17:21:25.572  4468  4468 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-15 17:21:25.572  4468  4468 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-15 17:21:25.573  4468  4468 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-15 17:21:25.573  4468  4468 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 17:21:25.573  4468  4468 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 17:21:25.573  4468  4468 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:25.573  4468  4468 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:25.573  4468  4468 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:25.573  4468  4468 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:25.573  4468  4468 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:25.573  4468  4468 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:25.578  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-15 17:21:25.591  4570  4570 I art     : Explicit concurrent mark sweep GC freed 8321(476KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 614us total 86.223ms
08-15 17:21:25.631  8549  8549 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-15 17:21:25.632  8549  8549 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-15 17:21:25.648  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-15 17:21:25.649  1868  1868 D SplitUIService: removed split : 
,08-15 17:21:25.664  1036  1991 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8606 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-15 17:21:25.670  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-15 17:21:25.671  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-15 17:21:25.671  2033  2141 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-15 17:21:25.675  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-15 17:21:25.675  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-15 17:21:25.675  3774  4462 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-15 17:21:25.677  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-15 17:21:25.679  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-15 17:21:25.683  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-15 17:21:25.687  1906  1906 D ActionManagerService: notifyUserLog: 1000004
,08-15 17:21:25.688  3774  4462 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-15 17:21:25.688  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-15 17:21:25.688  1868  1868 I SplitUIService: split app #11
08-15 17:21:25.689  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-15 17:21:25.691  1036  1603 I ActivityManager: Killing 7631:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-15 17:21:25.692  1036  2025 V SIM_STK : Menu title from STK is T-Mobile
08-15 17:21:25.692  3774  3789 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-15 17:21:25.693  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-15 17:21:25.693  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-15 17:21:25.727  8120  8120 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-15 17:21:25.727  8120  8120 W System.err: android.os.DeadObjectException
08-15 17:21:25.727  8120  8120 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-15 17:21:25.727  8120  8120 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-15 17:21:25.727  8120  8120 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-15 17:21:25.727  8120  8120 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-15 17:21:25.727  8120  8120 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-15 17:21:25.727  8120  8120 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-15 17:21:25.727  8120  8120 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 17:21:25.727  8120  8120 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 17:21:25.727  8120  8120 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:25.727  8120  8120 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:25.727  8120  8120 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:25.727  8120  8120 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:25.727  8120  8120 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:25.727  8120  8120 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:25.727  8120  8120 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-15 17:21:25.728  8120  8120 W System.err: android.os.DeadObjectException
08-15 17:21:25.728  8120  8120 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-15 17:21:25.728  8120  8120 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-15 17:21:25.728  8120  8120 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-15 17:21:25.728  8120  8120 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-15 17:21:25.728  8120  8120 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-15 17:21:25.728  8120  8120 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-15 17:21:25.728  8120  8120 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-15 17:21:25.728  8120  8120 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-15 17:21:25.728  8120  8120 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:25.728  8120  812,0 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:25.728  8120  8120 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:25.728  8120  8120 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:25.728  8120  8120 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:25.728  8120  8120 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:25.728  8120  8120 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-15 17:21:25.728  8120  8120 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-15 17:21:25.770  1036  1036 I art     : Explicit concurrent mark sweep GC freed 46453(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.931ms total 250.157ms
,08-15 17:21:25.770  1036  1124 I art     : WaitForGcToComplete blocked for 241.619ms for cause Explicit
,08-15 17:21:25.794  1036  1905 V SIM_STK : Menu title from STK is T-Mobile
08-15 17:21:25.794  1036  1905 V SIM_STK : Menu title from STK is T-Mobile
,08-15 17:21:25.824  1036  1036 D administrator: Handling package changes for user 0
,08-15 17:21:25.831  1036  2012 V SIM_STK : Menu title from STK is T-Mobile
,08-15 17:21:25.896  1036  1124 I art     : Explicit concurrent mark sweep GC freed 6088(325KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.376ms total 123.892ms
,08-15 17:21:25.923  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-15 17:21:25.923  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-15 17:21:25.923  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-15 17:21:25.942  1036  1902 W libprocessgroup: failed to open /acct/uid_1000/pid_7631/cgroup.procs: No such file or directory
,08-15 17:21:25.942  1036  1902 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-15 17:21:25.948  1036  1956 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-15 17:21:25.949  8120  8120 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-15 17:21:25.950  8120  8120 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-15 17:21:25.950  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-15 17:21:25.950  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-15 17:21:25.950  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-15 17:21:25.950  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-15 17:21:25.950  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-15 17:21:25.951  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 17:21:25.951  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-15 17:21:25.951  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-15 17:21:25.951  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-15 17:21:25.951  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-15 17:21:25.951  7603  7603 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-15 17:21:25.953  4570  8625 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-15 17:21:25.958  1036  1104 W ActivityManager: Activity pause timeout for ActivityRecord{1ef057d1 u0 com.lge.launcher2/.Launcher t5}
08-15 17:21:25.983  8606  8606 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,08-15 17:21:25.991  1036  1576 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8626 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-15 17:21:25.991  8120  8120 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-15 17:21:25.992  1036  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-15 17:21:25.993  2842  2858 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , display: false
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , animation: false }
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , display: false
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , animation: false }
,08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , create_time: 1471007226523
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , display: false
08-15 17:21:25.996  2033  2033 I GBoardWebViewUtils: , animation: false }
,08-15 17:21:25.998  2842  2858 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@499a2ab on behalf of 8549
08-15 17:21:26.002  2033  8641 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-15 17:21:26.014  1604  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-15 17:21:26.014  1604  1653 D KeyguardModel: createShortcutInfo...
,08-15 17:21:26.019  1604  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-15 17:21:26.019  1604  1653 D KeyguardModel: createShortcutInfo...
08-15 17:21:26.021  8606  8606 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-15 17:21:26.021  8606  8606 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-15 17:21:26.021  8606  8606 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-15 17:21:26.021  8606  8606 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-15 17:21:26.021  8606  8606 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-15 17:21:26.021  8606  8606 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-15 17:21:26.021  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-15 17:21:26.022  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-15 17:21:26.024  1604  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-15 17:21:26.025  1604  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 17:21:26.025  1604  1653 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-15 17:21:26.027  1604  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-15 17:21:26.029  1604  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 17:21:26.030  1604  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-15 17:21:26.030  8549  8549 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-15 17:21:26.037  1604  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-15 17:21:26.037  1604  1653 D KeyguardModel: createShortcutInfo...
08-15 17:21:26.040  8050  8050 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-15 17:21:26.041  1604  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-15 17:21:26.041  1604  1653 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-15 17:21:26.042  1604  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 17:21:26.042  1604  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-15 17:21:26.042  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-15 17:21:26.043  1604  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-15 17:21:26.043  1604  1653 D KeyguardModel: createShortcutInfo...
08-15 17:21:26.048  2175  2175 I ConfigService: onCreate
08-15 17:21:26.049  2175  2175 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-15 17:21:26.049  1604  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-15 17:21:26.049  1604  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-15 17:21:26.050  1604  1653 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-15 17:21:26.050  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-15 17:21:26.050  1604  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-15 17:21:26.052  1604  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 17:21:26.052  1604  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-15 17:21:26.052  2175  2175 I ConfigService: onBind returning update interface
08-15 17:21:26.053  1604  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-15 17:21:26.053  1604  1653 D KeyguardModel: createShortcutInfo...
,08-15 17:21:26.055  2175  2175 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-15 17:21:26.055  2175  2175 I ConfigService: onBind returning config service
08-15 17:21:26.058  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-15 17:21:26.058  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-15 17:21:26.067  2175  2175 I ConfigService: onDestroy
,08-15 17:21:26.071  1604  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-15 17:21:26.071  1604  1653 D KeyguardModel: createShortcutInfo...
08-15 17:21:26.074  1604  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-15 17:21:26.074  1604  1653 D KeyguardModel: createShortcutInfo...
08-15 17:21:26.076  1604  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 17:21:26.076  1604  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-15 17:21:26.078  1604  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-15 17:21:26.078  1604  1653 D KeyguardModel: createShortcutInfo...
08-15 17:21:26.079  1604  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 17:21:26.079  1604  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-15 17:21:26.083  1604  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-15 17:21:26.083  1604  1653 D KeyguardModel: createShortcutInfo...
08-15 17:21:26.086  1816  8651 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-15 17:21:26.087  8626  8626 D UEI.SmartControl: Quickset Services start...
08-15 17:21:26.089  1604  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-15 17:21:26.090  1604  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-15 17:21:26.091  1604  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-15 17:21:26.091  1604  1653 D KeyguardModel: createShortcutInfo...
08-15 17:21:26.093  8549  8549 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-15 17:21:26.093  8626  8626 I UEI.SmartControl: Manufacture = LGE
08-15 17:21:26.093  8626  8626 D UEI.SmartControl: Id = LGNevo
,08-15 17:21:26.094  8626  8626 D UEI.SmartControl: File observer start...
08-15 17:21:26.094  8626  8626 E UEI.SmartControl: IR Port is disabled: false
08-15 17:21:26.094  8626  8626 D UEI.SmartControl: Starting file observer...
08-15 17:21:26.094  8626  8626 D UEI.SmartControl: Extracting JNI libs...
08-15 17:21:26.094  8626  8626 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-15 17:21:26.110  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-15 17:21:26.110  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-15 17:21:26.119  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-15 17:21:26.133  1816  8660 I PeopleContactsSync: CP2 sync disabled
,08-15 17:21:26.135  7015  7015 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-15 17:21:26.141  5909  8658 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-15 17:21:26.142  1036  1991 I ActivityManager: Killing 8120:com.lge.qremote/u0a112 (adj 15): empty #17
08-15 17:21:26.151  8552  8552 D AndroidRuntime: Shutting down VM
,08-15 17:21:26.186  1036  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-15 17:21:26.192  1036  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-15 17:21:26.200  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-15 17:21:26.202  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 17:21:26.204  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-15 17:21:26.205  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-15 17:21:26.206  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,08-15 17:21:26.207  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-15 17:21:26.223  1036  1898 W libprocessgroup: failed to open /acct/uid_10112/pid_8120/cgroup.procs: No such file or directory
08-15 17:21:26.228  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,08-15 17:21:26.228  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 17:21:26.229  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ef057d1 u0 com.lge.launcher2/.Launcher t5} time:373173
08-15 17:21:26.231  2033  2223 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-15 17:21:26.231  2033  2223 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-15 17:21:26.232  8626  8626 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-15 17:21:26.232  8626  8626 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-15 17:21:26.232  8626  8626 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-15 17:21:26.237  1816  4751 I Icing   : doRemovePackageData com.test.thalitest
08-15 17:21:26.245  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-15 17:21:26.246  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-15 17:21:26.246  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 17:21:26.260  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-15 17:21:26.261  8626  8626 I UEI.SmartControl: --- Selecting new region: 6
08-15 17:21:26.263  8626  8626 I UEI.SmartControl: Model = LG-D855
08-15 17:21:26.264  8626  8626 D UEI.SmartControl: QS Service created
08-15 17:21:26.272  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8665 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-15 17:21:26.276  2610  2610 D [Concierge]Service: onStartCommand(). Type : 8
,08-15 17:21:26.276  2610  2610 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-15 17:21:26.278  2610  2610 D [Concierge]Service: Update widget ID : 11
08-15 17:21:26.278  2033  2033 D [Concierge]WidgetView: change position of spinner
08-15 17:21:26.284  2610  2610 D [Concierge]Service: onStartCommand(). Type : 0
,08-15 17:21:26.285  8208  8208 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-15 17:21:26.285  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1471274486285
08-15 17:21:26.289  2300  8678 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-15 17:21:26.296  1816  8659 W GmsApplication: Using Auth Proxy for data requests.
,08-15 17:21:26.300  1816  8659 W GmsApplication: Using Auth Proxy for data requests.
08-15 17:21:26.301  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 907641380
08-15 17:21:26.301  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-15 17:21:26.301  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-15 17:21:26.305  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2eb874e0
08-15 17:21:26.305  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-15 17:21:26.308  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-15 17:21:26.308  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 17:21:26.310  1995  1995 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-15 17:21:26.310  1995  1995 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-15 17:21:26.312  8626  8626 I UEI.SmartControl: Service initServices...
08-15 17:21:26.312  1995  1995 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-15 17:21:26.315  8626  8626 D UEI.SmartControl: QS start get config
08-15 17:21:26.317  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-15 17:21:26.317  8050  8050 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-15 17:21:26.317  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-15 17:21:26.323  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-15 17:21:26.323  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-15 17:21:26.325  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471274141874, New one : 1471274486285
,08-15 17:21:26.326  2033  2033 D [Concierge]WidgetView: Unregister all receivers
08-15 17:21:26.326  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-15 17:21:26.327  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 17:21:26.329  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-15 17:21:26.331  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-15 17:21:26.332  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-15 17:21:26.334  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-15 17:21:26.336  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-15 17:21:26.337  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 17:21:26.338  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-15 17:21:26.355  8626  8626 D UEI.SmartControl: Loading JNI Libs...
,08-15 17:21:26.362  1036  1976 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8685 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-15 17:21:26.370  1036  1576 I ActivityManager: Killing 7983:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-15 17:21:26.405  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-15 17:21:26.414  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-15 17:21:26.414  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-15 17:21:26.417  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-15 17:21:26.436  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@354ff805 time:373379
,08-15 17:21:26.447  1036  1956 W libprocessgroup: failed to open /acct/uid_10026/pid_7983/cgroup.procs: No such file or directory
,08-15 17:21:26.483  8626  8626 E UEI.SmartControl: unzip: java.io.IOException: write failed: EBADF (Bad file number)
,08-15 17:21:26.485  1816  4751 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-15 17:21:26.485  1816  4751 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
08-15 17:21:26.485  1816  4751 E Icing   : Could not init tag ds.tag.corpusid-1
08-15 17:21:26.485  1816  4751 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
08-15 17:21:26.486  1816  4751 E Icing   : Could not init tag ds.tag.corpusid-13
08-15 17:21:26.486  1816  4751 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
08-15 17:21:26.486  1816  4751 E Icing   : Could not init tag ds.tag.corpusid-7
08-15 17:21:26.486  1816  4751 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
08-15 17:21:26.486  1816  4751 E Icing   : Could not init tag ds.tag.corpusid-8
08-15 17:21:26.486  1816  4751 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
08-15 17:21:26.486  1816  4751 E Icing   : Could not init tag ds.tag.corpusid-9
08-15 17:21:26.487  1816  4751 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
08-15 17:21:26.487  1816  4751 E Icing   : Could not init tag ds.tag.deleted
08-15 17:21:26.487  1816  4751 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
08-15 17:21:26.487  1816  4751 E Icing   : Writing status failed
08-15 17:21:26.487  8626  8626 I UEI.SmartControl: Specific region DB is not found, use default...
08-15 17:21:26.489  1816  4751 E Icing   : Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
08-15 17:21:26.492  1816  8704 E SQLiteLog: (3850) statement aborts at 125: [DELETE FROM FileContent40 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
08-15 17:21:26.494  1816  8704 E DocListDatabase: Failed to delete from FileContent40
08-15 17:21:26.494  1816  8704 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:393)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at com.google.android.gms.drive.database.d.a(SourceFile:1017)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at com.google.android.gms.drive.b.c.run(SourceFile:58)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at com.google.android.gms.drive.g.an.run(SourceFile:51)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-15 17:21:26.494  18,16  8704 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-15 17:21:26.494  1816  8704 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
08-15 17:21:26.495  1816  8704 E AndroidRuntime: FATAL EXCEPTION: pool-29-thread-1
08-15 17:21:26.495  1816  8704 E AndroidRuntime: Process: com.google.android.gms, PID: 1816
08-15 17:21:26.495  1816  8704 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:393)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.a(SourceFile:1017)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at com.google.android.gms.drive.b.c.run(SourceFile:58)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at com.google.android.gms.drive.g.an.run(SourceFile:51)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-15 17:21:26.495  1816  8704 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-15 17:21:26.500  1816  8704 I Process : Sending signal. PID: 1816 SIG: 9
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: Can't write: system_app_crash
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-15 17:21:26.501  1036  8706 E DropBoxManagerService: 	... 5 more
,08-15 17:21:26.510  8685  8685 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:26.510  8685  8685 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: Unable to open database for writing.
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-15 17:21:26.511  8685  8685 E Lifetra,ckerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:26.511  8685  8685 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-15 17:21:26.518  8626  8626 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)
08-15 17:21:26.519  8626  8626 I UEI.SmartControl: Supports setup maps: true
08-15 17:21:26.519  8626  8626 W System.err: java.lang.NullPointerException: Attempt to get length of null array
08-15 17:21:26.520  8626  8626 W System.err: 	at com.uei.control.core.ab.b(Unknown Source)
08-15 17:21:26.520  8626  8626 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
08-15 17:21:26.520  8626  8626 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
08-15 17:21:26.520  8626  8626 W System.err: 	at com.uei.control.Service.a(Unknown Source)
08-15 17:21:26.520  8626  8626 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
08-15 17:21:26.520  8626  8626 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-15 17:21:26.520  8626  8626 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-15 17:21:26.520  8626  8626 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-15 17:21:26.520  8626  8626 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 17:21:26.520  8626  8626 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:26.520  8626  8626 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:26.520  8626  8626 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:26.520  8626  8626 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:26.520  8626  8626 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:26.520  8626  8626 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-15 17:21,:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-15 17:21:26.520  8626  8626 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-15 17:21:26.521  8626  8626 I UEI.SmartControl: ### init IR Blaster...
08-15 17:21:26.527  1036  1498 D WifiService: Client connection lost with reason: 4
08-15 17:21:26.528  8626  8626 D serial_port: Configuring serial port
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: Register corpus failed.
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: android.os.DeadObjectException
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at android.os.BinderProxy.transactNative(Native Method)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at android.os.BinderProxy.transact(Binder.java:496)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at bkp.b(Unknown Source)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at bbt.a(Unknown Source)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at bbt.e(Unknown Source)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at bef.call(PG:156)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at beg.a(PG:299)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at bed.a(PG:171)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.b(PG:415)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.k(PG:369)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:286)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at cuw.Tg(PG:368)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at cuy.ub(PG:301)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:26.532  4570  8625 E AppDataSearchClient: 	at android.os.HandlerThread.run(HandlerThread.java:61),
08-15 17:21:26.535  8626  8626 E UEI.SmartControl: UEIBLaster setting for 616
08-15 17:21:26.535  8626  8626 I UEI.SmartControl: Setting serial record hearder size = 2
08-15 17:21:26.536  8626  8626 I UEI.SmartControl: configuring settings for MAXQ616
08-15 17:21:26.536  8626  8626 I UEI.SmartControl: Get version...
08-15 17:21:26.539  4468  4514 E SQLiteLog: (2570) os_unix.c:31441: (30) unlink(/mpt/MPT_CommonData.db-journal) - 
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: Error inserting f004=20 f005=1816 f002=1471274486517 f003= f006=-1
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-15 17:21:26.540  4468  4514 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
08-15 17:21:26.551  8626  8713 D UEI.SmartControl: serial port data available: 21
08-15 17:21:26.563  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)

```
