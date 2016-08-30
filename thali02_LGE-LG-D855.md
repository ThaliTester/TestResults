#### Test 828833411848cab_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 22:55:00.787  2247  2247 I ConfigService: onDestroy
,08-30 22:55:17.545  6845  6845 D AndroidRuntime: 
08-30 22:55:17.545  6845  6845 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 22:55:17.548  6845  6845 D AndroidRuntime: CheckJNI is OFF
08-30 22:55:17.668  6845  6845 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 22:55:17.672  1037  1952 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 22:55:17.702  1954  4424 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 22:55:17.706  1037  1952 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 22:55:17.707  1037  1952 D ActivityManager: setTaskToReturnTo : TaskRecord{3a6836f8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 22:55:17.707  1037  1952 D ActivityManager: setTaskToReturnTo : TaskRecord{3a6836f8 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 22:55:17.708  1037  1952 D WindowStateEx: AppWindowTokenEx init.. 
08-30 22:55:17.709   341   352 E GBMv2   : DFP En is all cleared set to be enabled
08-30 22:55:17.730  1037  1952 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6865 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 22:55:17.731  6845  6845 D AndroidRuntime: Shutting down VM
08-30 22:55:17.775  1954  4424 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 22:55:17.775  1954  4424 D SplitWindowPolicy: topRunningActivity=ActivityInfo{e6df8d9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 22:55:17.776  1954  1970 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 22:55:17.776  1954  1970 D SplitWindowPolicy: topRunningActivity=ActivityInfo{377b429e co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 22:55:17.833  6865  6865 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 22:55:17.891  6865  6865 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 22:55:17.898  6865  6865 I LibraryLoader: Loading: webviewchromium
08-30 22:55:17.900  6865  6865 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2503-2505)
08-30 22:55:17.900  6865  6865 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 22:55:17.917  6865  6865 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a20d0ef}
,08-30 22:55:17.918  6865  6865 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 22:55:17.919  6865  6865 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 22:55:17.931  6865  6865 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 22:55:17.932  6865  6865 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 22:55:17.945  6865  6865 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 22:55:17.950  6865  6865 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 22:55:17.950  6865  6865 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 22:55:17.952   316   316 V AudioPolicyService: registerClient() client 0xb1427180, uid 10118
08-30 22:55:17.957  1037  1119 D BluetoothManagerService: Message: 20
,08-30 22:55:17.957  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@214adbc2:true
08-30 22:55:17.968  6865  6865 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 22:55:17.968  6865  6865 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 22:55:17.968  6865  6865 I Adreno-EGL: Build Date: 12/12/14 금
08-30 22:55:17.968  6865  6865 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 22:55:17.968  6865  6865 I Adreno-EGL: Remote Branch: 
08-30 22:55:17.968  6865  6865 I Adreno-EGL: Local Patches: 
08-30 22:55:17.968  6865  6865 I Adreno-EGL: Reconstruct Branch: 
,08-30 22:55:18.048  6865  6895 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-30 22:55:18.049  6865  6865 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-30 22:55:18.070  6865  6865 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 22:55:18.075  6865  6865 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 22:55:18.079  6865  6865 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 22:55:18.082  6865  6865 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 22:55:18.082  6865  6865 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 22:55:18.094  6865  6865 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 22:55:18.101  6865  6865 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 22:55:18.101  6865  6865 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 22:55:18.147  6865  6907 D OpenGLRenderer: Render dirty regions requested: true
08-30 22:55:18.147  6865  6907 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 22:55:18.167  6865  6907 D OpenGLRenderer: Enabling debug mode 0
,08-30 22:55:18.177  6865  6865 D Atlas   : Validating map...
08-30 22:55:18.181  1037  2021 D SplitWindow: check instance of lgWin Window{7be3a6c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 22:55:18.244  6865  6905 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:55:18.245  6865  6905 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:55:18.306  1037  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +532ms (total +597ms)
08-30 22:55:18.307  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1aef27d1 u0 com.test.thalitest/.MainActivity t6} time:162912
,08-30 22:55:18.311  6865  6865 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a05b88a time:162916
08-30 22:55:18.461  6865  6865 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 22:55:18.628  6865  6918 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435056640
,08-30 22:55:18.663  6865  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 22:55:18.663  6865  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 22:55:18.663  6865  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 22:55:18.663  6865  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 22:55:18.663  6865  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 22:55:18.663  6865  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2adcf72e added. We now have 1 listener(s)
,08-30 22:55:18.671  1037  1636 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:55:18.674  6865  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 22:55:18.678  6865  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 22:55:18.683  6865  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:55:18.683  6865  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 22:55:18.692  6865  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c3ab365 added. We now have 1 listener(s)
08-30 22:55:18.692  6865  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:55:18.699  1037  1531 D WifiService: New client listening to asynchronous messages
08-30 22:55:18.703  6865  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:55:18.704  6865  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 22:55:18.706  6865  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 22:55:18.706  6865  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 22:55:18.706  6865  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 22:55:18.716  6865  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:18.717  1037  2077 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:55:18.720  6865  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-30 22:55:18.735  6865  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 22:55:18.738  6865  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:55:18.738  6865  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:55:18.738  6865  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:55:18.738  6865  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:55:18.738  6865  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:55:18.738  6865  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:18.738  6865  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:55:18.738  6865  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:55:18.739  6865  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 22:55:18.739  6865  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:55:18.741  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:18.743  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:18.745  6865  6918 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 22:55:18.796  6865  6905 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 22:55:18.796  6865  6905 I chromium: 
,08-30 22:55:18.885  6865  6865 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 22:55:18.954  6865  6865 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 22:55:18.954  6865  6865 I chromium: 
,08-30 22:55:19.206   341   354 E GBMv2   : DFP En is all cleared set to be enabled
08-30 22:55:19.206   341   354 E GBMv2   : Set value is all cleared set the max
08-30 22:55:19.206   341   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 22:55:19.559  6865  6924 W jxcore-log: Initializing JXcore engine
08-30 22:55:19.559  6865  6924 W jxcore-log: JXcore engine is ready
,08-30 22:55:19.643  6924  6924 W Thread-807: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10326]" dev="sockfs" ino=10326 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 22:55:19.653  6924  6924 W Thread-807: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 22:55:19.653  6924  6924 W Thread-807: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10002]" dev="sockfs" ino=10002 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 22:55:19.653  6924  6924 W Thread-807: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 22:55:19.653  6924  6924 W Thread-807: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33361]" dev="sockfs" ino=33361 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 22:55:19.680  6865  6924 W jxcore-log: Starting JXcore engine
,08-30 22:55:19.805  6865  6924 W jxcore-log: Platform android
08-30 22:55:19.805  6865  6924 W jxcore-log: 
08-30 22:55:19.805  6865  6924 W jxcore-log: Process ARCH arm
08-30 22:55:19.805  6865  6924 W jxcore-log: 
,08-30 22:55:20.018  6865  6924 I jxcore-log: JXcore Cordova bridge is ready!
08-30 22:55:20.018  6865  6924 I jxcore-log: 
08-30 22:55:20.019  6865  6924 W jxcore-log: JXcore engine is started
,08-30 22:55:20.029  6865  6918 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 22:55:20.032  6865  6865 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 22:55:29.700  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 22:55:29.700  6865  6924 I jxcore-log: 
,08-30 22:55:29.703  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 22:55:29.703  6865  6924 I jxcore-log: 
,08-30 22:55:29.708  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:55:29.708  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:55:29.708  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:55:29.708  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:55:29.708  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:55:29.708  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:29.708  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:55:29.708  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:55:29.711  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:29.714  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 22:55:29.714  6865  6924 I jxcore-log: 
,08-30 22:55:29.717  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 22:55:29.717  6865  6924 I jxcore-log: 
08-30 22:55:30.227  6865  6924 I jxcore-log: Unit Test app is loaded
08-30 22:55:30.227  6865  6924 I jxcore-log: 
08-30 22:55:30.231  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:55:30.231  6865  6924 I jxcore-log: 
,08-30 22:55:30.239  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:55:30.239  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bd74ef added. We now have 2 listener(s)
08-30 22:55:30.239  1037  2342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:55:30.242  6865  6865 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 22:55:30.246  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 22:55:30.246  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:55:30.246  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:55:30.246  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:55:30.247  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f25cbfc added. We now have 2 listener(s)
08-30 22:55:30.247  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:55:30.248  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:55:30.252  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:30.256  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:55:30.256  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:55:30.256  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:55:30.256  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:55:30.256  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:55:30.256  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:30.256  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:55:30.256  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:55:30.258  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:30.258  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 22:55:30.260  6865  6924 D ExecuteNativeTests: Running unit tests
08-30 22:55:30.262  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:30.266  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:30.342  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:55:30.343  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a added. We now have 3 listener(s)
08-30 22:55:30.343  1037  1985 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 22:55:30.347  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 22:55:30.347  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:55:30.347  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:55:30.347  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:55:30.347  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb added. We now have 3 listener(s)
08-30 22:55:30.347  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:55:30.347  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:55:30.350  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:30.352  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:55:30.352  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:55:30.352  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:55:30.352  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:55:30.352  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:55:30.352  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:30.352  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:55:30.352  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:55:30.354  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:30.354  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:55:30.357  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:55:30.360  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:30.360  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 22:55:30.360  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:55:30.360  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:55:30.360  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:55:30.362  6865  6924 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 22:55:30.363  6865  6924 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 22:55:30.363  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 22:55:30.363  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:55:30.363  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:55:30.363  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:55:30.363  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:30.363  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:30.363  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:55:30.364  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:55:30.364  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a removed from the list
08-30 22:55:30.364  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:30.364  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb removed from the list
08-30 22:55:30.364  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:30.364  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:30.366  6865  6924 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 22:55:30.367  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:30.367  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:30.367  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:30.367  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:30.367  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:30.367  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:30.367  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:,55:30.367  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:30.367  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 22:55:30.373  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 22:55:30.374  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 22:55:30.374  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 22:55:30.374  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 22:55:30.374  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 22:55:30.374  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 22:55:30.374  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 22:55:30.374  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 22:55:30.374  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 22:55:30.374  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:30.374  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:30.374  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:30.374  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:30.374  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:30.374  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:30.374  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:30.374  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the lis,t - probably already removed
08-30 22:55:30.374  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:30.377  6865  6924 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 22:55:30.378  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:30.380  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:55:30.380  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:55:30.380  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:55:30.380  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:55:30.380  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:55:30.380  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:30.380  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:55:30.380  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:55:30.381  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:30.382  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:55:30.383  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:55:30.386  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:30.387  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:55:30.387  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:55:30.387  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:55:30.387  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:30.387  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 22:55:30.390  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 22:55:30.390  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:55:30.395  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 22:55:30.399  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 22:55:30.401  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 22:55:30.401  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 22:55:30.402  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:55:30.403  6865  6924 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 22:55:30.403  6865  6924 I io.jxcore.node.ConnectionHelper: start: OK
08-30 22:55:35.418  6865  6924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:55:35.418  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:55:35.418  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 22:55:40.427  6865  6924 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 22:55:40.427  6865  6924 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-30 22:55:40.428  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:55:40.428  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:55:40.428  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:55:40.428  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:40.428  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 22:55:40.452  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 22:55:40.456  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:55:40.458  6865  6924 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 22:55:40.458  6865  6924 I io.jxcore.node.ConnectionHelper: start: OK
08-30 22:55:43.756  1590  1590 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-30 22:55:43.762  1590  1590 I [SystemUI]LGPowerUI: On Skip Timer : true
08-30 22:55:43.783  1590  1590 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
08-30 22:55:43.783  1590  1590 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-30 22:55:43.787  1954  2150 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 22:55:43.787  1954  2150 D LEDHandler: Battery Level Remaining: 100%
08-30 22:55:43.787  1954  2150 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
08-30 22:55:43.787  1037  1531 D WifiController: battery changed pluggedType: 2
08-30 22:55:43.788  1590  1590 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 22:55:43.791  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:55:43.791  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:55:43.792  4281  4411 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 22:55:43.798  6717  6717 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 22:55:45.467  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 22:55:45.474  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:45.476  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:55:45.476  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:45.476  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:45.476  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:45.476  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:45.476  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:45.478  6865  6924 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 22:55:45.480  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:45.484  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:55:45.484  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:55:45.484  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:55:45.484  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:55:45.484  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:55:45.484  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:45.484  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:55:45.484  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 22:55:45.489  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:45.489  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:55:45.491  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:45.493  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:45.493  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:55:45.493  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:55:45.493  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:55:45.493  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:45.493  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 22:55:45.499  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 22:55:45.502  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:55:45.503  6865  6924 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 22:55:45.504  6865  6924 I io.jxcore.node.ConnectionHelper: start: OK
08-30 22:55:50.505  6865  6924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:55:50.505  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:55:50.505  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 22:55:55.515  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.515  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.515  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:55:55.516  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.516  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.516  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.516  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.516  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:55:55.527  6865  6924 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 22:55:55.528  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.528  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.528  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.528  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.528  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.528  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.528  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.528  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.528  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.529  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 22:55:55.529  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.529  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.530  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.530  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.530  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.530  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.530  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.530  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.530  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.530  6865  6924 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 22:55:55.531  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.531  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.531  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.531  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.531  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.531  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.531  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.531  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetooth,Manager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.531  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.532  6865  6924 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 22:55:55.532  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.532  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.532  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.532  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.532  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.532  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.532  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.532  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.532  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.533  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 22:55:55.537  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:55:55.537  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:55:55.537  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 22:55:55.537  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:55:55.537  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 22:55:55.537  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 22:55:55.537  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:55:55.537  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:55:55.537  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.537  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.538  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.538  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.538  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.538  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.538  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.538  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.538  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.539  6865  6924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 22:55:55.547  6865  6924 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 22:55:55.547  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 22:55:55.554  6865  6924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 22:55:55.554  6865  6924 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 22:55:55.556  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 22:55:55.556  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 22:55:55.556  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 22:55:55.556  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 22:55:55.558  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 22:55:55.559  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 22:55:55.559  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 22:55:55.559  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 22:55:55.559  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 22:55:55.559  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 22:55:55.559  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 22:55:55.559  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 22:55:55.559  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 22:55:55.559  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 22:55:55.560  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 22:55:55.561  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections:, Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 22:55:55.561  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 22:55:55.561  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 22:55:55.561  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 22:55:55.561  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 22:55:55.561  6865  6924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 22:55:55.562  6865  6924 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 22:55:55.562  6865  6924 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 22:55:55.563  6865  6924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 22:55:55.563  6865  6924 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 22:55:55.563  6865  6924 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 22:55:55.563  6865  6924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 22:55:55.563  6865  6924 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 22:55:55.563  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 22:55:55.566  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 22:55:55.567  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 22:55:55.567  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-30 22:55:55.574  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 22:55:55.574  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 22:55:55.575  6865  6924 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 22:55:55.575  6865  6924 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 22:55:55.575  6865  6924 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 22:55:55.575  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.575  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.576  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.576  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 22:55:55.576  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.577  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.577  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.577  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.577  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.577  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.578  6865  6924 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 22:55:55.578  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.578  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.578  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.578  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.578  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.578  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.578  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.578  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.578  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.579  6865  6924 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 22:55:55.580  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.580  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.580  6865  6924 D, org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.580  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.580  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.580  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.580  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.580  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.580  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.581  6865  6924 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 22:55:55.581  6865  6924 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 22:55:55.581  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 22:55:55.581  6865  6924 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 22:55:55.582  6865  6924 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 22:55:55.582  6865  6924 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 22:55:55.582  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 22:55:55.582  6865  6924 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 22:55:55.582  6865  6924 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 22:55:55.582  6865  6924 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 22:55:55.582  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 22:55:55.582  6865  6924 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-30 22:55:55.582  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:55:55.582  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.582  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:55:55.582  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:55:55.582  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:55:55.582  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:55:55.582  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:55:55.583  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:55:55.583  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:55:55.596  6865  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 871)
08-30 22:55:55.604  6865  6942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 871
08-30 22:55:55.605  6865  6942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 871)
08-30 22:55:55.605  6865  6942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 871)
,08-30 22:55:55.609  6865  6924 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 22:55:55.611  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:55.615  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:55:55.615  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:55:55.615  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:55:55.615  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:55:55.615  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:55:55.615  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:55.615  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:55:55.615  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:55:55.617  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:55:55.617  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 22:55:55.621  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:55.623  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:55:55.623  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:55:55.623  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:55:55.623  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:55:55.623  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:55:55.623  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 22:55:55.630  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 22:55:55.632  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:55:55.634  6865  6924 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 22:55:55.634  6865  6924 I io.jxcore.node.ConnectionHelper: start: OK
08-30 22:55:55.711  6865  6941 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-30 22:55:55.715  6865  6941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 871)
08-30 22:56:00.064  1590  1590 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 22:56:00.065  1590  1590 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 22:56:00.065  1590  1590 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 22:56:00.065  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
,08-30 22:56:00.077  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 22:56:00.077  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-30 22:56:00.080  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-30 22:56:00.082  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 22:56:00.635  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:56:00.635  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:00.635  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:56:00.635  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:56:00.635  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:00.635  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:56:00.636  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:00.636  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:56:00.764  1037  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=185534706, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-30 22:56:00.787  1037  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{21798d91 type 2 when 205354 com.google.android.gms} when 205354
,08-30 22:56:00.845  2666  2666 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 22:56:00.860  1826  1826 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-30 22:56:00.864  2247  2247 I ConfigService: onCreate
08-30 22:56:00.865  2247  2247 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 22:56:00.876  1826  6943 I ConfigFetchService: running network task: configservice_periodic
,08-30 22:56:00.887  1826  6943 I ConfigFetchService: launchTask
08-30 22:56:00.896  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=185534706 [*alarm*], flags=0x0
,08-30 22:56:00.900  2247  2247 I ConfigService: onBind returning update interface
08-30 22:56:00.901  1826  1826 I ConfigFetchService: service connected
08-30 22:56:00.902  2247  2247 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 22:56:00.902  2247  2247 I ConfigService: onBind returning config service
08-30 22:56:00.903  1826  1826 I ConfigClient: service connected
08-30 22:56:00.999  1037  1952 V SIM_STK : Menu title from STK is T-Mobile
,08-30 22:56:01.008  1826  2385 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 22:56:01.011   312  6963 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 22:56:01.011   312  6963 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-30 22:56:01.011   312  6963 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 22:56:01.222  1826  2385 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-30 22:56:01.228  1826  1826 I ConfigFetchService: fetch service done; releasing wakelock
,08-30 22:56:01.230  1826  1826 I ConfigFetchService: stopping self
08-30 22:56:01.267  2247  2247 I ConfigService: onDestroy
,08-30 22:56:05.647  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:05.647  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:56:05.647  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:56:05.647  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.648  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.648  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:56:05.648  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:56:05.648  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.648  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.648  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:56:05.648  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:05.649  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:56:05.649  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:05.649  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.649  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:56:05.667  6865  6924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 22:56:05.668  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:56:05.669  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 22:56:05.672  6865  6924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 22:56:05.674  6865  6924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 22:56:05.676  6865  6865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 22:56:05.676  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 22:56:05.676  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 22:56:05.678  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:56:05.678  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 22:56:05.678  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 22:56:05.678  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 22:56:05.678  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.678  6865  6924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 22:56:05.679  6865  6865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 22:56:05.679  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:56:05.679  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:05.679  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 22:56:05.679  6865  6924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 22:56:05.679  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 22:56:05.682  6865  6973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 22:56:05.682  6865  6973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 22:56:05.684  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 22:56:05.688  6865  6924 D BluetoothLeScanner: could not find callback wrapper
08-30 22:56:05.688  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 22:56:05.689  6865  6924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 22:56:05.689  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.689  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.691  6865  6924 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:56:05.691  6865  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:56:05.692  6865  6865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 22:56:05.692  6865  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:56:05.692  6865  6865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:56:05.692  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:56:05.692  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:56:05.692  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.692  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.692  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:56:05.692  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:05.692  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:56:05.692  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:05.692  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.692  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.694  6865  6924 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 22:56:05.695  6865  6924 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 22:56:05.695  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 22:56:05.701  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:56:05.701  6865  6924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:56:05.702  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:56:05.702  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.702  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.702  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:56:05.702  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:05.702  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:56:05.702  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:05.702  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.702  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.705  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:05.706  1037  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:05.708  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 22:56:05.711  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:56:05.711  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.711  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.711  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:56:05.711  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:05.711  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:56:05.711  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:05.711  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.711  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.713  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:56:05.713  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.713  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.713  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@361aac8a not in the list
08-30 22:56:05.713  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:05.713  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a9b2fb not in the list
08-30 22:56:05.713  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:05.713  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:05.713  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:05.715  6865  6924 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 22:56:05.715  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 22:56:05.716  6865  6924 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 22:56:05.716  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 22:56:05.716  6865  6924 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 22:56:05.716  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 22:56:05.718  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 22:56:05.718  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 22:56:05.719  6865  6924 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 22:56:05.720  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 22:56:05.720  6865  6924 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 22:56:05.720  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 22:56:05.720  6865  6924 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 22:56:05.720  6865  6924 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 22:56:05.721  6865  6924 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 22:56:05.721  6865  6924 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 22:56:05.722  6865  6924 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 22:56:05.722  6865  6924 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 22:56:05.722  6865  6924 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 22:56:05.722  6865  6924 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 22:56:05.723  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:56:05.723  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d769a9 added. We now have 3 listener(s)
08-30 22:56:05.723  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:56:05.726  6865  6924 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 22:56:05.733  1037  2019 D WifiServiceImplEx: setWifiEnabled: true pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 22:56:05.734  1037  2019 D WifiService: setWifiEnabled: true pid=6865, uid=10118
08-30 22:56:05.734  1037  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 22:56:06.193  6865  6865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 22:56:10.742  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:56:10.742  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@349fab2e added. We now have 4 listener(s)
08-30 22:56:10.742  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:56:10.758  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:10.758  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@349fab2e removed from the list
08-30 22:56:10.758  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:10.758  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:10.758  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:56:10.762  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:56:10.762  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21b816cf added. We now have 4 listener(s)
08-30 22:56:10.762  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:56:10.764  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:10.764  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21b816cf removed from the list
08-30 22:56:10.764  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:10.764  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:10.764  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:10.765  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:56:10.765  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@256ef85c added. We now have 4 listener(s)
08-30 22:56:10.765  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:56:10.768  1037  2019 D WifiServiceImplEx: setWifiEnabled: false pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 22:56:10.768  1037  2019 D WifiService: setWifiEnabled: false pid=6865, uid=10118
08-30 22:56:10.768  1037  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 22:56:10.790  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 22:56:10.790  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 22:56:10.790  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-30 22:56:10.792  1037  1526 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:10.792  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:10.793  1037  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:10.793  1037  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:10.793  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:10.794  1037  1526 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 22:56:10.794  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 22:56:10.794  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 22:56:10.795  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 22:56:10.795  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 22:56:10.799  1037  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 22:56:10.801  1037  1952 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@a1762e8 mBinding = false
08-30 22:56:10.804  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 22:56:10.805  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.805  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.805  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 22:56:10.806  2663  2663 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 22:56:10.807  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 22:56:10.807  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 22:56:10.808  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
08-30 22:56:10.808  1037  2808 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:56:10.819  1037  1119 D BluetoothManagerService: Message: 2
08-30 22:56:10.820  1037  1119 D BluetoothManagerService: Sending off request.
08-30 22:56:10.821  4281  4301 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 22:56:10.822  4281  4363 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 22:56:10.822  4281  4363 D BluetoothAdapterProperties: Setting state to 13
08-30 22:56:10.822  4281  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 22:56:10.823  4281  4363 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 22:56:10.823  4281  4363 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 22:56:10.828  4281  4367 D BluetoothAdapterProperties: Scan Mode:20
,08-30 22:56:10.832  4281  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 22:56:10.833  4281  4363 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 22:56:10.835  4281  4672 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:10.836  4281  4670 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 22:56:10.836  4281  4670 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:10.836  4281  4670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 22:56:10.836  4281  4670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 22:56:10.836  4281  4670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 22:56:10.836  4281  4670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 22:56:10.836  4281  4670 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 22:56:10.836  4281  4670 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 22:56:10.836  4281  4734 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:10.837  4281  4735 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:10.837  4281  4738 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:10.839  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 22:56:10.839  4281  4482 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 22:56:10.840  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 22:56:10.840  4281  4482 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-30 22:56:10.851  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.851  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:10.851  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:10.851  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:10.851  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:10.851  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:10.851  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:10.851  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:56:10.851  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:10.865  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.865  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 22:56:10.870  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.870  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:10.870  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:10.870  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:10.870  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:10.870  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:10.870  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:10.870  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:56:10.870  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:10.871  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.871  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:10.872  1037  1119 D BluetoothManagerService: Message: 60
08-30 22:56:10.872  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 22:56:10.872  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 22:56:10.885   312   895 D CommandListener: Clearing all IP addresses on wlan0
,08-30 22:56:10.913  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 22:56:10.914  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-30 22:56:10.917  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-30 22:56:10.934  1037  2021 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-30 22:56:10.937  1037  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.937  1037  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.937  1037  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 22:56:10.938  1037  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.938  1037  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 22:56:10.941  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 22:56:10.942  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 22:56:10.944   312  6997 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 22:56:10.945  1037  1117 D DSQN    : Dns fail occured do internet check.
08-30 22:56:10.949  1037  1104 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6994 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 22:56:10.962  1037  1037 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-30 22:56:10.962  1037  1037 D DSQN    : try Internet connection check
,08-30 22:56:10.965  1037  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 22:56:10.968  1037  1524 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.968  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.969  1037  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1a0a4325
08-30 22:56:10.969  1037  1524 D LGWifiP2pService: P2pDisablingState
08-30 22:56:10.969  1037  1524 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.969  1037  1524 D LGWifiP2pService: p2p socket connection lost
08-30 22:56:10.969  1037  1524 D LGWifiP2pService: P2pDisabledState
08-30 22:56:10.969  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:10.969  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:10.970  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:10.970  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:10.970  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:10.970  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 22:56:10.971  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:56:10.972  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 22:56:10.973  1954  1954 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:10.973  4281  4281 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:10.973  4281  4281 D BluetoothMapService: STATE_TURNING_OFF
08-30 22:56:10.973  4281  4281 V BluetoothMapService: Handler(): got msg=4
08-30 22:56:10.973  4281  4281 D BluetoothMapService: MAP Service closeService in
08-30 22:56:10.973  4281  4281 D BluetoothMapMasInstance: MAP Service shutdown
08-30 22:56:10.973  4281  4281 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 22:56:10.973  4281  4281 V BluetoothMapService: MAP Service closeService out
08-30 22:56:10.974  1037  1526 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 22:56:10.974  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 22:56:10.975  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 22:56:10.975  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.975  1037  1524 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:10.975  2663  2663 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-30 22:56:10.980  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 22:56:10.980  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 22:56:10.980  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
08-30 22:56:10.981  4281  4281 V BtOppService: Receiver DISABLED_ACTION 
08-30 22:56:10.981  4281  4281 I BtOppRfcommListener: stopping Accept Thread
08-30 22:56:10.981  4281  4281 V BtOppRfcommListener: close mBtServerSocket
08-30 22:56:10.982  4281  4281 V BtOppRfcommListener: waiting for thread to terminate
08-30 22:56:10.982  4281  4734 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 22:56:10.982  4281  4281 V BtOppRfcommListener: done waiting for thread to terminate
08-30 22:56:10.983  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.983  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:56:10.983  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:10.983  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:10.983  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:10.983  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:10.983  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:10.983  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:10.983  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:10.984  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.984  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:10.984  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:56:10.986  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.986  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:10.986  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:10.986  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:10.986  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:10.986  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:10.986  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:10.986  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:10.986  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:10.987  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.987  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:10.988  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.988  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:10.988  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:10.988  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:10.988  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:10.988  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:10.988  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:10.988  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:10.988  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:10.989  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:10.989  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:56:10.998   312   895 D CommandListener: Clearing all IP addresses on wlan0
08-30 22:56:10.998  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:10.999  1037  1532 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 22:56:10.999  1037  1532 D DSQN    : disableDataServiceNotify
08-30 22:56:10.999  1037  1532 D DSQN    : stop dsqn bin
08-30 22:56:11.000   312  7020 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 22:56:11.000  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 22:56:11.000  1037  7015 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-30 22:56:11.001  1037  7010 D DSQN    : ThreadInternetCheck internet check NOK 
08-30 22:56:11.001  1037  7010 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-30 22:56:11.007  1037  1532 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 22:56:11.007  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:11.007  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:11.007  1037  1532 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:11.007  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 22:56:11.008  1590  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 22:56:11.008  1037  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:11.008  1037  1532 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 22:56:11.008  1037  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:11.008  1037  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 22:56:11.008  1037  1532 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 22:56:11.008  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 22:56:11.014  1037  1104 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7021 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 22:56:11.015  4281  4281 V BtOppService: onDestroy
08-30 22:56:11.016  1037  1526 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 22:56:11.016  4281  4281 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 22:56:11.018  1037  1526 D WifiNative-p2p0: TERMINATE: returned true
08-30 22:56:11.018  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 22:56:11.018  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
08-30 22:56:11.018  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 22:56:11.021  1037  1037 D WifiHS20: hidePasspointNotification off =false
,08-30 22:56:11.022  1954  1954 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 22:56:11.022  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:56:11.022  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:11.022  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 22:56:11.023  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-30 22:56:11.024  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:11.024  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:11.024  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 22:56:11.024  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 22:56:11.025  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-30 22:56:11.025  1037  1545 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:11.025  1037  1546 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:11.027  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 22:56:11.027  1954  1954 D WfdsService: WifiP2pState is changed : false
08-30 22:56:11.027  1954  2334 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 22:56:11.027  1954  2334 D WfdsService: Set the WFDS Monitor: false
08-30 22:56:11.027  1954  2334 D WfdsMonitor: WFDS Monitor is stopped
08-30 22:56:11.027  1954  2334 D WfdsService: STATE : WfdsDisabledState - enter
08-30 22:56:11.028  1954  2335 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 22:56:11.028  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-30 22:56:11.028  1954  2735 D CtrlSupplicant: Received on exit socket, terminate
08-30 22:56:11.028  1954  2735 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 22:56:11.028  1954  2735 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 22:56:11.028  1954  2735 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 22:56:11.029  1954  2334 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 22:56:11.030  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:11.030  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:11.030  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 22:56:11.031  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:11.031  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 22:56:11.032  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:11.032  1037  1532 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:11.032  1037  1532 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:11.032  1037  1532 D NetworkManagementService: Removing idletimer
08-30 22:56:11.032  1037  1532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:11.033  1037  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 22:56:11.033  103,7  1532 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 22:56:11.033  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:11.033  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 22:56:11.033  1864  1864 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:11.033  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:11.033  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:11.033  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:11.033  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:11.033  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:11.033  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:11.033  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:11.033  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:11.033  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 22:56:11.034  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:11.034  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:11.036  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:11.037  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:11.037  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 22:56:11.039  1037  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 22:56:11.039  1037  1526 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:11.039  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:11.039  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:11.040  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 22:56:11.040  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 22:56:11.040  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 22:56:11.040  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 22:56:11.040  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 22:56:11.041  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 22:56:11.041  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 22:56:11.041  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 22:56:11.041  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:11.041  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:11.041  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:11.041  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:11.041  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:11.041  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:11.041  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:11.041  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:11.041  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:11.042  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:11.042  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:11.042  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:11.042  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:11.042  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:11.042  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:11.042  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:11.042  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:11.042  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:11.043  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:11.043  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:11.046  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:11.046  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:11.046  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:11.046  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:11.046  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:11.046  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:11.046  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:11.046  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:11.046  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:11.047  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:11.047  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:11.050  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:11.053  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:11.053  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 22:56:11.061  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:11.061  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 22:56:11.061  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:11.062  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 22:56:11.062  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:11.063  7021  7021 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:56:11.063  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:11.063  7021  7021 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 22:56:11.063  7021  7021 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 22:56:11.063  7021  7021 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 22:56:11.064  7021  7021 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 22:56:11.065  7021  7021 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 22:56:11.077  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 22:56:11.077  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:11.078  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:11.078  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:11.090  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 22:56:11.091  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:11.091  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:11.095  2663  2663 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 22:56:11.095  2663  2663 I wpa_supplicant: monitor socket send errors count : 1
08-30 22:56:11.095  2663  2663 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1954-2\x00 that cannot receive messages
08-30 22:56:11.096  1037  2730 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 22:56:11.096  1037  2730 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 22:56:11.097  6994  6994 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 22:56:11.097  6994  6994 W LG Account v2.2: No ProfileInfo entries
08-30 22:56:11.097  6994  6994 I LG Account v2.2: isEnabled: false
08-30 22:56:11.097  6994  6994 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 22:56:11.098  6994  6994 I Feature : [Lifetracker]Country: EU
08-30 22:56:11.098  6994  6994 I Feature : [Lifetracker]Operator: OPEN
08-30 22:56:11.098  6994  6994 I Feature : [Lifetracker]Ranking support: false
08-30 22:56:11.098  6994  6994 I Feature : [Lifetracker]Comfort support: false
08-30 22:56:11.098  6994  6994 I Feature : [Lifetracker]Accessory: true
08-30 22:56:11.098  6994  6994 I Feature : [Lifetracker]Health device: true
08-30 22:56:11.098  6994  6994 I Feature : [Lifetracker]Extra Pedometer: false
08-30 22:56:11.098  6994  6994 I Feature : [Lifetracker]Blood glucose device: false
08-30 22:56:11.098  6994  6994 I Feature : [Lifetracker]Device Number: 3
08-30 22:56:11.105  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:11.125  1037  2808 D DhcpStateMachine: StoppedState
08-30 22:56:11.125  1037  2808 D DhcpStateMachine: StoppedState{ when=-145ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:56:11.133  2663  2663 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 22:56:11.133  1037  2730 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 22:56:11.133  1037  2730 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 22:56:11.133  1037  2730 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 22:56:11.133  1037  2730 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 22:56:11.133  2663  2663 W wpa_supplicant: USIM:  scard_deinit function
08-30 22:56:11.134  1037  1526 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=215727
08-30 22:56:11.134  1037  1526 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=215727
08-30 22:56:11.134  1037  2730 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:11.134  1037  2730 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 22:56:11.134  1037  1119 D Tethering: InitialState.processMessage what=4
08-30 22:56:11.134  1037  1526 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=215727  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 22:56:11.135  1037  1526 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=215728  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 22:56:11.138  1037  2021 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7041 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 22:56:11.139  1037  2021 I ActivityManager: Killing 6287:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-30 22:56:11.166  1037  1526 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 22:56:11.166  1037  1526 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 22:56:11.167  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 22:56:11.167  1037  1526 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:11.167  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 22:56:11.170  1037  1052 W libprocessgroup: failed to open /acct/uid_10014/pid_6287/cgroup.procs: No such file or directory
08-30 22:56:11.199  7041  7041 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 22:56:11.203  7041  7041 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 22:56:11.204  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:11.205  2663  2663 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 22:56:11.206  1037  2730 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 22:56:11.206  1037  2730 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 22:56:11.206  1037  2730 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 22:56:11.207  1037  1526 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-30 22:56:11.209  1037  1934 I ActivityManager: Killing 6428:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 22:56:11.226  7021  7021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 22:56:11.246  1037  1953 W libprocessgroup: failed to open /acct/uid_10004/pid_6428/cgroup.procs: No such file or directory
,08-30 22:56:11.254  4281  4281 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-30 22:56:11.254  4281  4281 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:11.254  4281  4281 V BluetoothPbapReceiver: ***********state = 13
08-30 22:56:11.255  4281  4281 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 22:56:11.256  4281  4281 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:11.256  4281  4281 V BluetoothPbapService: state: 13
08-30 22:56:11.256  4281  4281 V BluetoothPbapService: Pbap Service closeService in
08-30 22:56:11.259  4281  4281 V BluetoothPbapService: successfully stopped pbap service
08-30 22:56:11.259  4281  4281 V BluetoothPbapService: Pbap Service closeService out
08-30 22:56:11.259  4281  4281 V BluetoothPbapService: Pbap Service onDestroy
08-30 22:56:11.259  4281  4281 V BluetoothPbapService: Pbap Service closeService in
08-30 22:56:11.259  4281  4281 V BluetoothPbapService: Pbap Service closeService out
08-30 22:56:11.259  4281  4281 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 22:56:11.259  2247  2247 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 22:56:11.275  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:11.310  1954  1954 D WfdsService: Supplicant Connection state is changed : false
08-30 22:56:11.310  1037  1526 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 22:56:11.310  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 22:56:11.310  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
08-30 22:56:11.310  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 22:56:11.310  1954  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-30 22:56:11.310  1954  2334 D WfdsService: Set the WFDS Monitor: false
08-30 22:56:11.310  1954  2334 D WfdsMonitor: WFDS Monitor is stopped
08-30 22:56:11.312  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:11.313  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 22:56:11.317  2455  2455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:11.322  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:11.327  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 22:56:11.327  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:11.328  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 22:56:11.328  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 22:56:11.331  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:11.335  7021  7021 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 22:56:11.335  7021  7021 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:11.347  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 22:56:11.356  1037  1119 D BluetoothManagerService: Message: 20
08-30 22:56:11.356  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@383b8983:true
08-30 22:56:11.368  1037  1119 D BluetoothManagerService: Message: 30
,08-30 22:56:11.373  1037  1119 D BluetoothManagerService: Message: 30
08-30 22:56:11.378  7021  7021 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 22:56:11.382  7021  7021 D BluetoothMap: Create BluetoothMap proxy object
,08-30 22:56:11.383  1037  1119 D BluetoothManagerService: Message: 30
08-30 22:56:11.390  1037  1119 D BluetoothManagerService: Message: 30
08-30 22:56:11.392  7021  7021 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 22:56:11.393  7021  7021 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 22:56:11.415  7021  7021 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 22:56:11.423  7021  7021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 22:56:11.445  7021  7021 D DockEventReceiver: finishStartingService: stopping service
,08-30 22:56:11.478  7021  7021 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 22:56:11.486  7021  7021 D BluetoothInputDevice: Proxy object connected
08-30 22:56:11.488  7021  7021 D HidProfile: Bluetooth service connected
08-30 22:56:11.490  7021  7021 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 22:56:11.492  7021  7021 D PanProfile: Bluetooth service connected
08-30 22:56:11.494  7021  7021 D BluetoothMap: Proxy object connected
,08-30 22:56:11.495  7021  7021 D MapProfile: Bluetooth service connected
08-30 22:56:11.496  7021  7021 D BluetoothMap: getConnectedDevices()
08-30 22:56:11.498  7021  7021 D BluetoothMap: Bluetooth is Not enabled
08-30 22:56:11.499  7021  7021 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 22:56:11.502  7021  7021 D BluetoothPermissionRequest: onReceive
08-30 22:56:11.507  7021  7021 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 22:56:11.518  7021  7021 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 22:56:11.519  1037  2342 I ActivityManager: Killing 6555:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-30 22:56:11.577  1037  1367 W libprocessgroup: failed to open /acct/uid_10008/pid_6555/cgroup.procs: No such file or directory
08-30 22:56:11.578  4281  4281 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-30 22:56:11.578  4281  4281 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 22:56:11.580  4281  4281 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 22:56:11.665  1037  2021 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7075 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 22:56:11.669  4281  4281 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:11.669  4281  4281 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 22:56:11.675  4281  4281 V BluetoothFtpService: Ftp Service onStartCommand
08-30 22:56:11.675  4281  4281 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:11.675  4281  4281 V BluetoothFtpService: Ftp Service closeService
08-30 22:56:11.675  4281  4281 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 22:56:11.676  4281  4281 V BluetoothFtpService: successfully stopped ftp service
08-30 22:56:11.677  4281  4281 V BluetoothFtpService: Ftp Service onDestroy
08-30 22:56:11.677  4281  4281 V BluetoothFtpService: Ftp Service closeService
,08-30 22:56:11.687  4281  4281 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 22:56:11.688  4281  4281 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 22:56:11.688  4281  4281 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 22:56:11.688  4281  4281 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:11.688  4281  4281 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 22:56:11.688  4281  4281 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 22:56:11.690  4281  4281 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:11.690  4281  4281 V BluetoothSapService: state: 13
08-30 22:56:11.690  4281  4281 V BluetoothSapService: Stopping SAP server process
,08-30 22:56:11.695  4281  4281 V BluetoothSapService: Sap Service closeSapService in
08-30 22:56:11.695  4281  4281 V BluetoothSapService: Close listen Socket : 
08-30 22:56:11.695  4281  4281 V BluetoothSapService: Close rfcomm Socket : 
08-30 22:56:11.695  4281  4281 V BluetoothSapService: Close sapd  Socket : 
08-30 22:56:11.729  1037  2021 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7092 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 22:56:11.740  4281  4281 V BluetoothSapService: Sap Service closeSapService out
08-30 22:56:11.740  4281  4281 V BluetoothSapService: Sap Service onDestroy
08-30 22:56:11.740  4281  4281 V BluetoothSapService: Sap Service closeSapService in
08-30 22:56:11.740  4281  4281 V BluetoothSapService: Close listen Socket : 
08-30 22:56:11.740  4281  4281 V BluetoothSapService: Close rfcomm Socket : 
08-30 22:56:11.740  4281  4281 V BluetoothSapService: Close sapd  Socket : 
08-30 22:56:11.741  4281  4281 V BluetoothSapService: Sap Service closeSapService out
08-30 22:56:11.769  7075  7075 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 22:56:11.789  7092  7092 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 22:56:11.798  7075  7075 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 22:56:11.804  1037  1052 I ActivityManager: Killing 6027:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 22:56:11.827  7075  7075 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 22:56:11.828  7075  7075 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 22:56:11.828  7075  7075 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 22:56:11.828  7075  7075 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 22:56:11.829  7075  7075 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 22:56:11.830  7075  7075 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 22:56:11.837  7075  7075 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 22:56:11.842  4281  4367 D bt_hci_bdroid: cleanup
08-30 22:56:11.842  4281  4484 I bt_lpm  : LPM is already off!!!
,08-30 22:56:11.842  4281  4660 I bt_userial_mct: exiting userial_read_thread
08-30 22:56:11.842  4281  4660 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-30 22:56:11.843  4281  4367 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 22:56:11.843  4281  4482 W bt-btif : ag scb idx 1 not allocated
08-30 22:56:11.843  4281  4482 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:11.843  4281  4484 I bt_vendor: hw_epilog_process
,08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 22:56:11.843  4281  4482 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:56:11.843  4281  4482 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-30 22:56:11.844  4281  4367 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 22:56:11.844  4281  4367 D bt_userial_mct: userial_close
08-30 22:56:11.844  4281  4367 E bt_userial_mct: pthread_join() FAILED result:3
08-30 22:56:11.844  4281  4367 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 22:56:11.865  4281  4367 D bt_hci_bdroid: set_power 0
08-30 22:56:11.865  4281  4367 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 22:56:11.865  4281  4367 I bt_vendor: bluetooth satus is on
,08-30 22:56:11.865  4281  4367 I bt_vendor: bt-vendor : resetting BT status
08-30 22:56:11.865  4281  4367 I bt_vendor: Starting hciattach daemon
08-30 22:56:11.865  4281  4367 I bt_vendor: try to set false
08-30 22:56:11.867  4281  4367 I bt_vendor: Starting hciattach daemon
08-30 22:56:11.867  4281  4367 I bt_vendor: try to set false
,08-30 22:56:11.868  4281  4367 I bt_vendor: cleanup
,08-30 22:56:11.872  4281  4482 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 22:56:11.875  4281  4367 I GKI_LINUX: GKI_exit_task 0 done
08-30 22:56:11.875  4281  4367 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 22:56:11.879  4281  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 22:56:11.885  4281  4281 D HeadsetService: Received stop request...Stopping profile...
,08-30 22:56:11.889  1037  2077 W libprocessgroup: failed to open /acct/uid_10011/pid_6027/cgroup.procs: No such file or directory
08-30 22:56:11.895  4281  4281 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 22:56:11.895  4281  4281 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 22:56:11.895  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@277bf7fc
08-30 22:56:11.895  4281  4411 D HeadsetStateMachine: Exit Disconnected: -1
08-30 22:56:11.897  1864  1864 D BluetoothHeadset: Proxy object disconnected
,08-30 22:56:11.897  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 22:56:11.900  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-30 22:56:11.900  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 22:56:11.901  4281  4281 D A2dpService: Received stop request...Stopping profile...
08-30 22:56:11.901  4281  4461 D A2dpStateMachine: Exit Disconnected: -1
08-30 22:56:11.902  4281  4281 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 22:56:11.903  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 22:56:11.905  4281  4281 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 22:56:11.905  4281  4281 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 22:56:11.905  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@277bf7fc
08-30 22:56:11.907  4281  4363 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 22:56:11.908  4281  4281 D HidService: Received stop request...Stopping profile...
,08-30 22:56:11.908  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@277bf7fc
08-30 22:56:11.911  4281  4281 D HealthService: Received stop request...Stopping profile...
08-30 22:56:11.911  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@277bf7fc
08-30 22:56:11.912  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-30 22:56:11.913  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 22:56:11.913  4281  4281 D HeadsetStateMachine: Unbinding service...
08-30 22:56:11.913  7021  7021 D BluetoothInputDevice: Proxy object disconnected
08-30 22:56:11.913  7021  7021 D HidProfile: Bluetooth service disconnected
08-30 22:56:11.914  4281  4281 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 22:56:11.914  4281  4281 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 22:56:11.914  4281  4281 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 22:56:11.914  4281  4281 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 22:56:11.914  4281  4281 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 22:56:11.914  4281  4281 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 22:56:11.914  4281  4281 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 22:56:11.915  4281  4281 D PanService: Received stop request...Stopping profile...
,08-30 22:56:11.915  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:11.916  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@277bf7fc
08-30 22:56:11.916  4281  4281 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 22:56:11.917  7021  7021 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 22:56:11.917  4281  4281 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 22:56:11.917  7021  7021 D PanProfile: Bluetooth service disconnected
08-30 22:56:11.917  4281  4281 D BtGatt.GattService: stop()
,08-30 22:56:11.917  4281  4281 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 22:56:11.918  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@277bf7fc
08-30 22:56:11.919  4281  4281 D BluetoothMapService: Received stop request...Stopping profile...
08-30 22:56:11.919  4281  4281 D BluetoothMapService: stop()
08-30 22:56:11.919  4281  4281 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 22:56:11.920  4281  4281 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 22:56:11.920  4281  4281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@277bf7fc
08-30 22:56:11.921  4281  4281 I BluetoothA2dpServiceJni: cleanupNative
08-30 22:56:11.922  4281  4462 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 22:56:11.922  4281  4281 I GKI_LINUX: GKI_exit_task 2 done
,08-30 22:56:11.922  4281  4281 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 22:56:11.923  4281  4281 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 22:56:11.923  4281  4281 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 22:56:11.923  4281  4281 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 22:56:11.923  4281  4281 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 22:56:11.923  4281  4281 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 22:56:11.923  4281  4281 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 22:56:11.923  4281  4281 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 22:56:11.925  4281  4281 V BluetoothMapService: Handler(): got msg=4
08-30 22:56:11.925  4281  4281 D BluetoothMapService: MAP Service closeService in
08-30 22:56:11.925  7021  7021 D BluetoothMap: Proxy object disconnected
08-30 22:56:11.925  4281  4281 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 22:56:11.925  4281  4281 V BluetoothMapService: MAP Service closeService out
08-30 22:56:11.925  7021  7021 D MapProfile: Bluetooth service disconnected
08-30 22:56:11.926  4281  4281 D BluetoothMapService: cleanup()
08-30 22:56:11.926  4281  4281 D BluetoothMapService: MAP Service closeService in
08-30 22:56:11.926  4281  4281 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 22:56:11.926  4281  4281 V BluetoothMapService: MAP Service closeService out
08-30 22:56:11.926  4281  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 22:56:11.926  4281  4363 D BluetoothAdapterProperties: Setting state to 10
08-30 22:56:11.926  4281  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 22:56:11.926  1037  1119 D BluetoothManagerService: Message: 60
08-30 22:56:11.926  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 22:56:11.926  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 22:56:11.926  4281  4363 I BluetoothAdapterState: Entering OffState
08-30 22:56:11.926  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 22:56:11.927  7021  7037 D BluetoothPan: onBluetoothStateChange on: false
08-30 22:56:11.927  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:11.927  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 22:56:11.928  7021  7036 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 22:56:11.928  1864  4267 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 22:56:11.929  7021  7037 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 22:56:11.930  1864  2548 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 22:56:11.930  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 22:56:11.930  7021  7036 D BluetoothMap: onBluetoothStateChange: up=false
08-30 22:56:11.931  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 22:56:11.931  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 22:56:11.934  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 22:56:11.934  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 22:56:11.934  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@a1762e8 mBinding = false
08-30 22:56:11.935  1037  1119 D BluetoothManagerService: Sending unbind request.
,08-30 22:56:11.937  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 22:56:11.940  1954  1954 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:11.940  1954  2187 D LGBluetoothAPIService: Message: 2
08-30 22:56:11.940  1954  2187 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@11fbb17f mBinding = false
08-30 22:56:11.940  1954  2187 D LGBluetoothAPIService: Sending unbind request.
08-30 22:56:11.940  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 22:56:11.946  4281  4367 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 22:56:11.947  4281  4281 I GKI_LINUX: GKI_exit_task 1 done
08-30 22:56:11.947  4281  4281 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 22:56:11.948  7021  7021 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 22:56:11.948  4281  4281 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 22:56:11.948  4281  4281 I art     : --- WEIRD: removing null entry 246
08-30 22:56:11.948  4281  4281 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 22:56:11.948  4281  4281 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 22:56:11.949  7021  7021 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 22:56:11.949  7021  7021 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-30 22:56:11.951  1590  1590 D BluetoothAdapter: 615567124: getState() :  mService = null. Returning STATE_OFF
08-30 22:56:11.951  1590  1590 D BluetoothAdapter: 615567124: getState() :  mService = null. Returning STATE_OFF
08-30 22:56:11.952  4281  4281 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 22:56:11.954  4281  4281 I art     : System.exit called, status: 0
08-30 22:56:11.955  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:11.955  4281  4281 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 22:56:11.956  7021  7021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 22:56:11.960  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:11.961  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:11.964  7075  7075 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 22:56:11.967  7075  7075 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 22:56:11.970  7075  7075 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 22:56:11.971  7021  7021 D DockEventReceiver: finishStartingService: stopping service
08-30 22:56:11.973  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:11.985  7041  7041 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 22:56:11.985  7041  7041 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 22:56:11.985  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:11.986   316  4421 V AudioFlinger: 4281 died, releasing its sessions
,08-30 22:56:11.986   316  4421 V AudioFlinger:  pid 1864 @ 0
,08-30 22:56:11.986   316  4421 V AudioFlinger:  pid 3158 @ 1
08-30 22:56:11.986   316  4421 V AudioFlinger:  pid 3158 @ 2
08-30 22:56:11.987  7021  7021 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 22:56:12.002  1037  1037 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-30 22:56:12.017  1037  2098 I ActivityManager: Process com.android.bluetooth (pid 4281) has died
08-30 22:56:12.017  1037  2098 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 22:56:12.023  2247  2247 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 22:56:12.028  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:12.038  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 22:56:12.047  7021  7021 D BluetoothPermissionRequest: onReceive
,08-30 22:56:12.051  7021  7021 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 22:56:12.052  7021  7021 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 22:56:12.054  7021  7021 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 22:56:12.130  1037  1985 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7128 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-30 22:56:12.148  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 22:56:12.149  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:12.151  7075  7075 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 22:56:12.156  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:12.161  7041  7041 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 22:56:12.161  7041  7041 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-30 22:56:12.161  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:12.175  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:12.182  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:12.192  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:12.192  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:12.194  7075  7075 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 22:56:12.216  7128  7128 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 22:56:12.217  7128  7128 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 22:56:12.217  7128  7128 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 22:56:12.218  7128  7128 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 22:56:12.237  7128  7128 D BluetoothAdapterApp: Loading JNI Library
,08-30 22:56:12.243  1037  2098 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7145 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-30 22:56:12.275  7128  7128 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2ecdd2cd Instance Count = 1
,08-30 22:56:12.281  7128  7128 D BluetoothAdapterApp: onCreate
,08-30 22:56:12.305  7128  7128 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 22:56:12.305  7128  7128 D ProfileConfigQcom: Adding HeadsetService
08-30 22:56:12.305  7128  7128 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 22:56:12.306  7128  7128 D ProfileConfigQcom: Adding A2dpService
08-30 22:56:12.306  7128  7128 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 22:56:12.306  7128  7128 D ProfileConfigQcom: Adding HidService
08-30 22:56:12.306  7128  7128 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 22:56:12.307  7128  7128 D ProfileConfigQcom: Adding HealthService
08-30 22:56:12.307  7128  7128 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-30 22:56:12.308  7128  7128 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 22:56:12.308  7128  7128 D ProfileConfigQcom: Adding PanService
08-30 22:56:12.308  7128  7128 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 22:56:12.308  7128  7128 D ProfileConfigQcom: Adding GattService
08-30 22:56:12.309  7128  7128 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 22:56:12.309  7128  7128 D ProfileConfigQcom: Adding BluetoothMapService
08-30 22:56:12.309  7128  7128 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 22:56:12.311  7128  7128 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 22:56:12.318  7021  7021 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 22:56:12.319  7128  7128 V LGMDMManagerInternal: Create singleton instance
,08-30 22:56:12.343  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 22:56:12.348  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:56:12.358  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:12.375  7145  7165 W FormManager: Network not available. Please check & try again.
08-30 22:56:12.377  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 22:56:12.378  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 22:56:12.378  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 22:56:12.379  7021  7021 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 22:56:12.379  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 22:56:12.394  7145  7166 V FormManager: Network unavailable.
,08-30 22:56:12.396  7021  7021 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 22:56:12.397  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 22:56:12.397  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 22:56:12.397  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 22:56:12.397  7021  7021 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 22:56:12.397  7021  7021 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 22:56:12.400  7145  7166 V FormManager: Network unavailable.
08-30 22:56:12.404  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 22:56:12.404  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 22:56:12.406  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:12.409  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 22:56:12.414  7128  7128 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:12.417  4747  7170 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 22:56:12.420  4747  7170 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 22:56:12.420  7128  7128 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 22:56:12.421  7128  7128 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 22:56:12.421  7128  7128 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 22:56:12.421  7041  7041 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-30 22:56:12.421  7041  7041 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 22:56:12.421  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:12.422  7128  7128 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:12.422  7128  7128 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 22:56:12.425  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:56:12.426  4747  7169 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 22:56:12.431  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:12.434  7092  7092 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 22:56:12.438  7145  7173 W FormManager: Network not available. Please check & try again.
,08-30 22:56:12.443  7145  7174 V FormManager: Network unavailable.
08-30 22:56:12.446  1037  2077 I ActivityManager: Killing 6050:com.android.contacts/u0a19 (adj 15): empty #17
08-30 22:56:12.467  1037  1367 W libprocessgroup: failed to open /acct/uid_10019/pid_6050/cgroup.procs: No such file or directory
08-30 22:56:12.467  7145  7174 V FormManager: Network unavailable.
,08-30 22:56:12.472  1037  1952 I ActivityManager: Killing 6604:com.lge.email/u0a23 (adj 15): empty #17
,08-30 22:56:12.502  1037  2019 W libprocessgroup: failed to open /acct/uid_10023/pid_6604/cgroup.procs: No such file or directory
,08-30 22:56:12.515  7075  7075 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 22:56:12.516  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 22:56:12.516  7075  7075 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 22:56:12.555  7075  7075 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:56:12.555  7075  7075 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:12.565  7075  7075 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 22:56:12.567  7075  7075 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 22:56:12.568  7075  7075 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-30 22:56:12.568  7075  7075 V SoundPool: doLoad: loading sample sampleID=1
08-30 22:56:12.569  7075  7075 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 22:56:12.570  7075  7177 V SoundPool: Start decode
08-30 22:56:12.570  7075  7177 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-30 22:56:12.570   316  4421 V MediaPlayerService: decode(22, 10857164, 17813)
08-30 22:56:12.570   316  4421 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 22:56:12.570   316  4421 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 22:56:12.571   316  4421 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 22:56:12.571   316  4421 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 22:56:12.571   316  4421 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 22:56:12.571   316  4421 V MediaPlayerService: player type = 3
08-30 22:56:12.571   316  4421 V AwesomePlayer: AwesomePlayer create()
08-30 22:56:12.573   316  4421 V AwesomePlayer: reset_l() 
08-30 22:56:12.573   316  4421 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:12.573   316  4421 V AwesomePlayer: setAudioSink() 
08-30 22:56:12.573   316  4421 V AwesomePlayer: reset_l() 
,08-30 22:56:12.573   316  4421 V AudioCache: notify(0xb5474640, 8, 0, 0)
08-30 22:56:12.573   316  4421 V AudioCache: ignored
08-30 22:56:12.573   316  4421 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:12.573   316  4421 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 22:56:12.574   316  4421 V AwesomePlayer: setDataSource_l dataSource
08-30 22:56:12.574   316  4421 V LGParserOSAL: SniffLGParser start
08-30 22:56:12.574   316  4421 V LGParserOSAL: MainType:5, SubType=0
08-30 22:56:12.574   316  4421 V LGParserOSAL: #### check Mime : application/ogg
08-30 22:56:12.574   316  4421 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 22:56:12.574   316  4421 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 22:56:12.578  7075  7075 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 22:56:12.582  7075  7075 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 22:56:12.582  6746  6746 D UEI.SmartControl: QS Service created
08-30 22:56:12.583  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 22:56:12.607  6746  6746 I UEI.SmartControl: Service initServices...
,08-30 22:56:12.607  6746  6746 D UEI.SmartControl: QS start get config
08-30 22:56:12.615   316  4421 V LGParserOSAL: supported mime: application/ogg
08-30 22:56:12.615   316  4421 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 22:56:12.615   316  4421 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 22:56:12.615   316  4421 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 22:56:12.615   316  4421 V AwesomePlayer: AudioTrack Setting
08-30 22:56:12.615   316  4421 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 22:56:12.615   316  4421 V AwesomePlayer: setAudioSource() 
08-30 22:56:12.615   316  4421 V MediaPlayerService: prepare
08-30 22:56:12.615   316  4421 V AwesomePlayer: prepareAsync_l() 
08-30 22:56:12.615   316  4421 V MediaPlayerService: wait for prepare
08-30 22:56:12.616   316  7178 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 22:56:12.616   316  7178 V AwesomePlayer: initAudioDecoder() 
08-30 22:56:12.616   316  7178 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 22:56:12.616   316  7178 V AudioSystem: isOffloadSupported()
08-30 22:56:12.616   316  7178 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 22:56:12.616   316  7178 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 22:56:12.616   316  7178 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 22:56:12.616   316  7178 V AwesomePlayer: getUseOffload() = 0 
08-30 22:56:12.616   316  7178 V OMXCodec: OMXCodec::Create
08-30 22:56:12.616   316  7178 V OMXCodec: findMatchingCodecs()
08-30 22:56:12.617   316  7178 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 22:56:12.617   316  7178 V OMXCodec: matchingCodecs.size()=1
08-30 22:56:12.617  7075  7075 V LGMDMManager: Create singleton instance
08-30 22:56:12.617   316  7178 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 22:56:12.624   316  7178 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,08-30 22:56:12.624   316  7178 V LGCodecAdapter: LG Codec Adapter start
08-30 22:56:12.624   316  7178 V OMXCodec: OMXCodec Createtor
08-30 22:56:12.624   316  7178 V OMXCodec: setComponentRole
08-30 22:56:12.624   316  7178 V OMXCodec: configureCodec protected=0
08-30 22:56:12.624   316  7178 V LGCodecAdapter: called getLGCodecSpecificData
08-30 22:56:12.624   316  7178 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 22:56:12.624   316  7178 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 22:56:12.625   316  7178 V LGCodecOSAL: Called LGconfigureCodecMSG
,08-30 22:56:12.625   316  7178 V LGCodecOSAL: Not support LGCodec
08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 22:56:12.625   316  7178 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 22:56:12.625   316  7178 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 22:56:12.625   316  7178 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 22:56:12.625   316  7178 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 22:56:12.625   316  7178 V AudioSystem: isOffloadSupported()
08-30 22:56:12.625   316  7178 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 22:56:12.625   316  7178 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 22:56:12.625   316  7178 V OMXCodec: init()
08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 22:56:12.625   316  7178 V OMXCodec: allocateBuffers
08-30 22:56:12.625   316  7178 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
,08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
08-30 22:56:12.625   316  7178 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 22:56:12.625   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-30 22:56:12.626   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-30 22:56:12.626   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fbf0 on output port
08-30 22:56:12.626   316  7178 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040ffb0 on output port
08-30 22:56:12.626   316  7178 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-30 22:56:12.626   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 22:56:12.626   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 22:56:12.626   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 22:56:12.626   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 22:56:12.626   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 22:56:12.626   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 22:56:12.626   316  7178 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 22:56:12.626   316  7178 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 22:56:12.626   316  7178 V AudioCache: notify(0xb5474640, 5, 0, 0)
,08-30 22:56:12.626   316  7178 V AudioCache: ignored
08-30 22:56:12.626   316  7178 V AudioCache: notify(0xb5474640, 1, 0, 0)
08-30 22:56:12.626   316  7178 V AudioCache: prepared
08-30 22:56:12.626   316  4421 V AudioCache: wait - success
08-30 22:56:12.626   316  4421 V MediaPlayerService: start
08-30 22:56:12.626   316  4421 V AwesomePlayer: play_l() 
08-30 22:56:12.626   316  4421 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 22:56:12.626   316  4421 V AwesomePlayer: createAudioPlayer_l
08-30 22:56:12.626   316  4421 V AwesomePlayer: seekAudioIfNecessary_l() 
,08-30 22:56:12.626   316  4421 V AwesomePlayer: startAudioPlayer_l() 
08-30 22:56:12.626   316  4421 D AudioPlayer: start of Playback, useOffload 0
08-30 22:56:12.626   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 22:56:12.626   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048816
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049776
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 22:56:12.628   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 22:56:12.629   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 22:56:12.629   316  7180 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 22:56:12.629   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 22:56:12.629   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fbf0 on output port
08-30 22:56:12.629   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-30 22:56:12.629   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
,08-30 22:56:12.629   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
08-30 22:56:12.629   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 22:56:12.629   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 22:56:12.630   316  4421 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 22:56:12.630   316  4421 V AudioCache: notify(0xb5474640, 6, 0, 0)
08-30 22:56:12.630   316  4421 V AudioCache: ignored
08-30 22:56:12.630   316  4421 V MediaPlayerService: wait for playback complete
08-30 22:56:12.631   316  7181 V AudioCache: write(0xb1006000, 4096)
,08-30 22:56:12.631   316  7181 V AudioCache: memcpy(0xaf006000, 0xb1006000, 4096)
08-30 22:56:12.633   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.633   316  7181 V AudioCache: memcpy(0xaf007000, 0xb1006000, 4096)
08-30 22:56:12.633   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.633   316  7181 V AudioCache: memcpy(0xaf008000, 0xb1006000, 4096)
08-30 22:56:12.634   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.634   316  7181 V AudioCache: memcpy(0xaf009000, 0xb1006000, 4096)
08-30 22:56:12.634   316  7181 V AudioCache: write(0xb1006000, 4096)
,08-30 22:56:12.635   316  7181 V AudioCache: memcpy(0xaf00a000, 0xb1006000, 4096)
08-30 22:56:12.635   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.635   316  7181 V AudioCache: memcpy(0xaf00b000, 0xb1006000, 4096)
08-30 22:56:12.636   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.636   316  7181 V AudioCache: memcpy(0xaf00c000, 0xb1006000, 4096)
08-30 22:56:12.637   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.637   316  7181 V AudioCache: memcpy(0xaf00d000, 0xb1006000, 4096)
08-30 22:56:12.637   316  7181 V AudioCache: write(0xb1006000, 4096)
,08-30 22:56:12.637   316  7181 V AudioCache: memcpy(0xaf00e000, 0xb1006000, 4096)
08-30 22:56:12.638   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.638   316  7181 V AudioCache: memcpy(0xaf00f000, 0xb1006000, 4096)
08-30 22:56:12.639   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.639   316  7181 V AudioCache: memcpy(0xaf010000, 0xb1006000, 4096)
08-30 22:56:12.639   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.639   316  7181 V AudioCache: memcpy(0xaf011000, 0xb1006000, 4096)
08-30 22:56:12.640   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.640   316  7181 V AudioCache: memcpy(0xaf012000, 0xb1006000, 4096)
08-30 22:56:12.640   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.640   316  7181 V AudioCache: memcpy(0xaf013000, 0xb1006000, 4096)
08-30 22:56:12.641   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.641   316  7181 V AudioCache: memcpy(0xaf014000, 0xb1006000, 4096)
08-30 22:56:12.641   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.641   316  7181 V AudioCache: memcpy(0xaf015000, 0xb1006000, 4096)
08-30 22:56:12.642   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.642   316  7181 V AudioCache: memcpy(0xaf016000, 0xb1006000, 4096)
08-30 22:56:12.642   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.642   316  7181 V AudioCache: memcpy(0xaf017000, 0xb1006000, 4096)
08-30 22:56:12.643   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.643   316  7181 V AudioCache: memcpy(0xaf018000, 0xb1006000, 4096)
08-30 22:56:12.643   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.643   316  7181 V AudioCache: memcpy(0xaf019000, 0xb1006000, 4096)
08-30 22:56:12.644   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.644   316  7181 V AudioCache: memcpy(0xaf01a000, 0xb1006000, 4096)
08-30 22:56:12.644   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.644   316  7181 V AudioCache: memcpy(0xaf01b000, 0xb1006000, 4096)
08-30 22:56:12.645   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.645   316  7181 V AudioCache: memcpy(0xaf01c000, 0xb1006000, 4096)
08-30 22:56:12.645   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.645   316  7181 V AudioCache: memcpy(0xaf01d000, 0xb1006000, 4096)
08-30 22:56:12.645   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.646   316  7181 V AudioCache: memcpy(0xaf01e000, 0xb1006000, 4096)
08-30 22:56:12.647   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.647   316  7181 V AudioCache: memcpy(0xaf01f000, 0xb1006000, 4096)
08-30 22:56:12.648   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.648   316  7181 V AudioCache: memcpy(0xaf020000, 0xb1006000, 4096)
08-30 22:56:12.649   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.649   316  7181 V AudioCache: memcpy(0xaf021000, 0xb1006000, 4096)
08-30 22:56:12.649   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.649   316  7181 V AudioCache: memcpy(0xaf022000, 0xb1006000, 4096)
08-30 22:56:12.650   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.650   316  7181 V AudioCache: memcpy(0xaf023000, 0xb1006000, 4096)
08-30 22:56:12.651   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.651   316  7181 V AudioCache: memcpy(0xaf024000, 0xb1006000, 4096)
08-30 22:56:12.651   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.651   316  7181 V AudioCache: memcpy(0xaf025000, 0xb1006000, 4096)
08-30 22:56:12.652   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.652   316  7181 V AudioCache: memcpy(0xaf026000, 0xb1006000, 4096)
08-30 22:56:12.652   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.652   316  7181 V AudioCache: memcpy(0xaf027000, 0xb1006000, 4096)
08-30 22:56:12.653   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.653   316  7181 V AudioCache: memcpy(0xaf028000, 0xb1006000, 4096)
08-30 22:56:12.653   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.653   316  7181 V AudioCache: memcpy(0xaf029000, 0xb1006000, 4096)
08-30 22:56:12.654   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.654   316  7181 V AudioCache: memcpy(0xaf02a000, 0xb1006000, 4096)
08-30 22:56:12.654   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.654   316  7181 V AudioCache: memcpy(0xaf02b000, 0xb1006000, 4096)
08-30 22:56:12.655   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.655   316  7181 V AudioCache: memcpy(0xaf02c000, 0xb1006000, 4096)
08-30 22:56:12.655   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.655   316  7181 V AudioCache: memcpy(0xaf02d000, 0xb1006000, 4096)
08-30 22:56:12.655   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.655   316  7181 V AudioCache: memcpy(0xaf02e000, 0xb1006000, 4096)
08-30 22:56:12.656   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.656   316  7181 V AudioCache: memcpy(0xaf02f000, 0xb1006000, 4096)
,08-30 22:56:12.656   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.656   316  7181 V AudioCache: memcpy(0xaf030000, 0xb1006000, 4096)
08-30 22:56:12.656   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.656   316  7181 V AudioCache: memcpy(0xaf031000, 0xb1006000, 4096)
08-30 22:56:12.656   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.656   316  7181 V AudioCache: memcpy(0xaf032000, 0xb1006000, 4096)
08-30 22:56:12.657   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.657   316  7181 V AudioCache: memcpy(0xaf033000, 0xb1006000, 4096)
08-30 22:56:12.658   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.658   316  7181 V AudioCache: memcpy(0xaf034000, 0xb1006000, 4096)
08-30 22:56:12.658   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.658   316  7181 V AudioCache: memcpy(0xaf035000, 0xb1006000, 4096)
08-30 22:56:12.658   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.658   316  7181 V AudioCache: memcpy(0xaf036000, 0xb1006000, 4096)
08-30 22:56:12.659   316  7181 V AudioCache: write(0xb1006000, 4096)
08-30 22:56:12.659   316  7181 V AudioCache: memcpy(0xaf037000, 0xb1006000, 4096)
08-30 22:56:12.659   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 22:56:12.659   316  7181 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 22:56:12.659   316  7181 V AwesomePlayer: postAudioEOS() 
08-30 22:56:12.659   316  7181 V AudioCache: write(0xb1006000, 280)
08-30 22:56:12.659   316  7181 V AudioCache: memcpy(0xaf038000, 0xb1006000, 280)
08-30 22:56:12.661   316  7178 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 22:56:12.661   316  7178 V AwesomePlayer: onStreamDone
08-30 22:56:12.661   316  7178 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 22:56:12.661   316  7178 V AudioCache: notify(0xb5474640, 2, 0, 0)
08-30 22:56:12.661   316  7178 V AudioCache: playback complete
08-30 22:56:12.661   316  7178 V AwesomePlayer: pause_l() 
08-30 22:56:12.661   316  7178 V AudioCache: notify(0xb5474640, 7, 0, 0)
08-30 22:56:12.661   316  7178 V AudioCache: ignored
08-30 22:56:12.661   316  7178 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:12.661   316  4421 V AudioCache: wait - success
08-30 22:56:12.662   316  4421 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 22:56:12.662   316  7178 D AudioPlayer: Pause Playback at 1068125
08-30 22:56:12.662   316  4421 V AwesomePlayer: reset_l() 
08-30 22:56:12.662   316  4421 V AudioCache: notify(0xb5474640, 8, 0, 0)
08-30 22:56:12.662   316  4421 V AudioCache: ignored
08-30 22:56:12.662   316  4421 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:12.662   316  4421 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 22:56:12.662   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 22:56:12.662   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 22:56:12.662   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 22:56:12.662   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fbf0 on port 1
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 22:56:12.663   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 22:56:12.663   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 22:56:12.663   316  7180 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 22:56:12.664   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 22:56:12.664   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 22:56:12.664   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 22:56:12.665   316  4421 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 22:56:12.665   316  4421 D AudioPlayer: AudioPlayer releasing audio source
08-30 22:56:12.665   316  4421 D AudioPlayer: AudioPlayer done releasing audio source
08-30 22:56:12.665   316  4421 V AwesomePlayer: reset_l() 
08-30 22:56:12.665   316  4421 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:12.665   316  4421 V AwesomePlayer: ~AwesomePlayer call
08-30 22:56:12.665   316  4421 V AwesomePlayer: reset_l() 
08-30 22:56:12.665   316  4421 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:12.666  7075  7177 V SoundPool: close(32)
08-30 22:56:12.666  7075  7177 V SoundPool: pointer = 0xa0048000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 22:56:12.685  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 22:56:12.686  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-30 22:56:12.688  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:726
08-30 22:56:12.898  6746  6746 I UEI.SmartControl: Supports setup maps: true
,08-30 22:56:12.901  6746  6746 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 22:56:12.901  6746  6746 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 22:56:12.901  6746  6746 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 22:56:12.901  6746  6746 I UEI.SmartControl: ### init IR Blaster...
08-30 22:56:12.904  6746  6746 D serial_port: Configuring serial port
08-30 22:56:12.905  6746  6746 E UEI.SmartControl: UEIBLaster setting for 616
08-30 22:56:12.905  6746  6746 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 22:56:12.905  6746  6746 I UEI.SmartControl: configuring settings for MAXQ616
08-30 22:56:12.905  6746  6746 I UEI.SmartControl: Get version...
08-30 22:56:12.926  6746  7182 D UEI.SmartControl: serial port data available: 21
,08-30 22:56:12.956  6746  6746 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 22:56:12.956  6746  6746 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 22:56:12.956  6746  6746 I UEI.SmartControl: QS saving settings...
,08-30 22:56:12.959  6746  6746 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 22:56:12.976  6746  7182 D UEI.SmartControl: serial port data available: 4
,08-30 22:56:13.010  6746  7191 I UEI.SmartControl: Device manager: loading config....
,08-30 22:56:13.011  6746  7191 D UEI.SmartControl: ----------- loading internal config...
08-30 22:56:13.012  6746  6746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 22:56:13.016  6746  6746 E UEI.SmartControl: Services init done
08-30 22:56:13.016  6746  6746 D UEI.SmartControl: QS Service init finished
08-30 22:56:13.019  6746  6746 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 22:56:13.019  6746  6746 D UEI.SmartControl: QS Service version code: 201091
,08-30 22:56:13.020  6746  6746 D UEI.SmartControl: Service requested: Control
08-30 22:56:13.037  6746  7191 E UEI.SmartControl: Loading SETTINGS...
08-30 22:56:13.039  6746  6746 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 22:56:13.042  6746  6746 D UEI.SmartControl: Internal service binding...
08-30 22:56:13.043  7075  7075 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 22:56:13.052  6746  6761 I UEI.SmartControl: ------ IControl API: 11
08-30 22:56:13.052  6746  6761 D UEI.SmartControl: File observer start...
08-30 22:56:13.052  6746  6761 E UEI.SmartControl: IR Port is disabled: false
08-30 22:56:13.052  6746  6761 D UEI.SmartControl: Starting file observer...
08-30 22:56:13.054  6746  6761 I UEI.SmartControl: Registering callback...
08-30 22:56:13.058  6746  7191 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 22:56:13.065  6746  6762 I UEI.SmartControl: ------ IControl API: 19
08-30 22:56:13.066  6746  6762 I UEI.SmartControl: Registering Services Ready callback...
08-30 22:56:13.066  6746  6762 I UEI.SmartControl: Notify client services are ready...
08-30 22:56:13.067  7075  7091 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 22:56:13.067  7075  7175 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 22:56:13.068  7075  7175 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 22:56:13.068  7075  7075 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 22:56:13.069  7075  7075 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 22:56:13.069  6746  6761 I UEI.SmartControl: ------ IControl API: 8
08-30 22:56:13.070  7075  7075 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 22:56:13.071  6746  7190 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 22:56:13.071  7075  7091 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 22:56:13.071  6746  7190 D UEI.SmartControl: -----service ready thread exits
08-30 22:56:13.072  7075  7175 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 22:56:13.072  7075  7175 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 22:56:13.072  7075  7075 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 22:56:13.073  7075  7075 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 22:56:13.073  7075  7075 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 22:56:13.074  7075  7075 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,08-30 22:56:13.078  7075  7075 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 22:56:13.082  7075  7075 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 22:56:13.083  7075  7075 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-30 22:56:13.084  7075  7075 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 22:56:13.085  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 22:56:13.086  7075  7075 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 22:56:13.086  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 22:56:13.088  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-30 22:56:13.091  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 22:56:13.091  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 22:56:13.092  7075  7075 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472590573092]
08-30 22:56:13.095  7075  7075 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 22:56:13.099  1037  1636 I ActivityManager: Killing 6072:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 22:56:13.144  7075  7196 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 22:56:13.165  1037  1952 W libprocessgroup: failed to open /acct/uid_10027/pid_6072/cgroup.procs: No such file or directory
,08-30 22:56:13.172  7075  7075 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 22:56:13.172  7075  7075 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 22:56:13.173  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 22:56:13.173  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 22:56:13.173  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 22:56:13.174  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 22:56:13.174  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 22:56:13.187  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 22:56:14.035  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:14.051  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-30 22:56:14.066  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:14.071  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:14.072  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:14.075  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:14.078  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-30 22:56:14.089  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:14.092  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:14.094  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:14.095  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 22:56:14.098  6518  7040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 22:56:14.099  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:14.112  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 22:56:14.120  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 22:56:14.145  2247  2247 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:14.205  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:14.218  1037  1765 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7227 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 22:56:14.221  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:14.222  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:14.239   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 470us total 21.862ms
,08-30 22:56:14.259   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 408us total 18.897ms
,08-30 22:56:14.277   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.557ms
,08-30 22:56:14.278  7227  7227 I AppUp4:AppBoxCP: onCreate
,08-30 22:56:14.279  7227  7227 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-30 22:56:14.285  7227  7227 I AppUp4:DB:  setFingerPrint start
,08-30 22:56:14.286  7227  7227 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 22:56:14.291  7227  7227 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 22:56:14.291  7227  7227 I AppUp4:DB:  SDK version = 21
08-30 22:56:14.291  7227  7227 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-30 22:56:14.294  7227  7227 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-30 22:56:14.295  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 22:56:14.295  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:14.297  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 22:56:14.297  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 22:56:14.303  7227  7227 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 22:56:14.327  7227  7227 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:56:14.327  7227  7227 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:14.333  7227  7227 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1a20d0ef
08-30 22:56:14.333  7227  7227 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 22:56:14.333  7227  7227 D AppUp4:CustFacade: isPhone : true
08-30 22:56:14.334  7227  7227 D AppUp4:CustModeStarterReceiver: begin check event
08-30 22:56:14.334  7227  7227 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 22:56:14.335  7227  7227 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 22:56:14.335  7227  7248 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 22:56:14.336  7227  7248 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 22:56:14.336  7227  7248 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 22:56:14.339  1037  2098 I ActivityManager: Killing 6641:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-30 22:56:14.372  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:14.373  1037  1934 W libprocessgroup: failed to open /acct/uid_10061/pid_6641/cgroup.procs: No such file or directory
08-30 22:56:14.373  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 22:56:14.377  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:14.381  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:14.389  4747  7250 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 22:56:14.395  4747  7251 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:14.395  4747  7251 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 22:56:14.457  1037  1636 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7252 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 22:56:14.572  7252  7252 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:56:14.573  7252  7252 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 22:56:14.576  7252  7252 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 22:56:14.577  7252  7252 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 22:56:14.680  7252  7252 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 22:56:14.699  7252  7252 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 22:56:14.749  7252  7252 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 22:56:14.788  7252  7252 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 22:56:14.788  7252  7252 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:14.922  7252  7252 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 22:56:14.961  3158  3158 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 22:56:14.961  3158  3158 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:14.961  3158  3158 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 22:56:14.976  7252  7252 I HubEmail: JNI_OnLoad()
08-30 22:56:14.976  7252  7252 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 22:56:14.976  7252  7252 I HubEmail: registerNatives()
08-30 22:56:14.976  7252  7252 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 22:56:14.976  7252  7252 I HubEmail: registerNativeMethods()
08-30 22:56:14.976  7252  7252 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-30 22:56:14.976  7252  7252 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 22:56:15.012  1037  2098 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7284 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 22:56:15.023  7145  7281 W FormManager: Network not available. Please check & try again.
08-30 22:56:15.027  7252  7283 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:15.028  7145  7282 V FormManager: Network unavailable.
,08-30 22:56:15.031  7145  7282 V FormManager: Network unavailable.
08-30 22:56:15.041  1037  1636 I ActivityManager: Killing 6675:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-30 22:56:15.097  1037  2342 W libprocessgroup: failed to open /acct/uid_10080/pid_6675/cgroup.procs: No such file or directory
,08-30 22:56:15.183  7284  7284 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:56:15.183  7284  7284 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:15.187  7284  7284 D PhoneMonitor: Register our PhoneStateListener
08-30 22:56:15.211  7284  7284 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 22:56:15.216  7284  7284 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 22:56:15.254  7284  7284 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 22:56:15.257  7284  7284 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-30 22:56:15.258  7284  7284 D TelephonyAutoProfiling: [parse] Load xml
,08-30 22:56:15.263  7284  7284 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-30 22:56:15.263  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
,08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
,08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true,
08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true,
08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
,08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true,
08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true,
,08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 22:56:15.264  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 22:56:15.265  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 22:56:15.265  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 22:56:15.265  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 22:56:15.265  7284  7284 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 22:56:15.265  7284  7284 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-30 22:56:15.277  7284  7284 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-30 22:56:15.294  1037  2019 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7309 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 22:56:15.295  1037  2019 I ActivityManager: Killing 6174:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 22:56:15.346  1037  2021 W libprocessgroup: failed to open /acct/uid_10097/pid_6174/cgroup.procs: No such file or directory
,08-30 22:56:15.670  1037  1636 I art     : Explicit concurrent mark sweep GC freed 56896(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.403ms total 185.012ms
,08-30 22:56:15.752  1037  2019 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7331 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-30 22:56:15.752  1037  2019 I ActivityManager: Killing 6698:com.lge.eula/1000 (adj 15): empty #17
,08-30 22:56:15.810  1037  2021 W libprocessgroup: failed to open /acct/uid_1000/pid_6698/cgroup.procs: No such file or directory
,08-30 22:56:15.927  1037  2342 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7348 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 22:56:15.932  1037  2342 I ActivityManager: Killing 6717:com.lge.bnr/1000 (adj 15): empty #17
08-30 22:56:15.974  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:15.974  1037  1524 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:56:15.996  1037  1934 W libprocessgroup: failed to open /acct/uid_1000/pid_6717/cgroup.procs: No such file or directory
,08-30 22:56:16.017  1037  1765 D WifiServiceImplEx: setWifiEnabled: true pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 22:56:16.018  1037  1765 D WifiService: setWifiEnabled: true pid=6865, uid=10118
08-30 22:56:16.018  1037  1765 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 22:56:16.035  1037  1526 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 22:56:16.036  1037  1526 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 22:56:16.036  1037  1526 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 22:56:16.036  1037  1526 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 22:56:16.039  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 22:56:16.039  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-30 22:56:16.041  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-30 22:56:16.041  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 22:56:16.041  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 22:56:16.041  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 22:56:16.041  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 22:56:16.042  1037  1526 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 22:56:16.042  1037  1526 E WifiHW  : unknown target_country: EU , set to default
08-30 22:56:16.042  1037  1526 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-30 22:56:16.042  1037  1526 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 22:56:16.042  1037  1526 I WifiUtil: gEnableBmps=1
08-30 22:56:16.068  7348  7348 I art     : Almond Protected OAT
,08-30 22:56:16.123  7348  7348 D WeatherApplication: removeAccount
,08-30 22:56:16.125  7348  7348 D WeatherApplication: Account.length = 0
08-30 22:56:16.125  7348  7348 E WeatherApplication: OPERATOR:OPEN
08-30 22:56:16.131  7348  7348 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:16
08-30 22:56:16.134  7348  7348 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 22:56:16.134  7348  7348 D Weather.Utils: 2 : All the weather widget is gone.
08-30 22:56:16.136  7348  7348 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 22:56:16.139  7348  7348 D WeatherAncestor: connectivity changed - connection : true
08-30 22:56:16.141  7348  7348 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 22:56:16.151  7348  7348 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 22:56:16.151  7348  7348 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 22:56:16.151  7348  7348 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-30 22:56:16.177  7348  7348 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 22:56:16.177  7348  7348 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:16
,08-30 22:56:16.237  1037  2019 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7367 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 22:56:16.239  1037  2019 I ActivityManager: Killing 2162:com.lge.music/u0a34 (adj 15): empty #17
08-30 22:56:16.275   316  1372 V AudioFlinger: 2162 died, releasing its sessions
08-30 22:56:16.275   316  1372 V AudioFlinger:  pid 1864 @ 0
08-30 22:56:16.275   316  1372 V AudioFlinger:  pid 3158 @ 1
08-30 22:56:16.275   316  1372 V AudioFlinger:  pid 3158 @ 2
,08-30 22:56:16.305  1037  1053 W libprocessgroup: failed to open /acct/uid_10034/pid_2162/cgroup.procs: No such file or directory
,08-30 22:56:16.419   279   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 22:56:16.419   279   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 22:56:16.419   279   431 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 22:56:16.426  7367  7385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 22:56:16.429   279   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 22:56:16.429   279   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 22:56:16.429   279   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 22:56:16.430  7367  7385 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 22:56:16.445   279   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 22:56:16.445   279   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 22:56:16.445   279   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 22:56:16.446  7367  7387 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 22:56:16.456   279   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 22:56:16.456   279   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 22:56:16.456   279   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 22:56:16.456  7367  7387 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 22:56:16.668  7367  7367 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 22:56:16.689  7367  7367 I LibraryLoader: Loading: webviewchromium
08-30 22:56:16.693  7367  7367 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1294-1298)
08-30 22:56:16.693  7367  7367 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 22:56:16.705  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 22:56:16.705  1037  1119 D Tethering: InitialState.processMessage what=4
08-30 22:56:16.706  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 22:56:16.709   312   895 D SoftapController: Softap fwReload - Ok
,08-30 22:56:16.712  1037  1526 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (663ms)
08-30 22:56:16.715   312   895 D CommandListener: Setting iface cfg
08-30 22:56:16.715   312   895 D CommandListener: Trying to bring down wlan0
08-30 22:56:16.717   312   895 D CommandListener: Clearing all IP addresses on wlan0
08-30 22:56:16.719  1037  1526 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 22:56:16.723  7412  7412 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:16.723  7412  7412 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:16.728  7367  7367 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c8bcb18}
08-30 22:56:16.729  7367  7367 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 22:56:16.730  7367  7367 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 22:56:16.735  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 22:56:16.735  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
08-30 22:56:16.735  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 22:56:16.735  1037  1526 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 22:56:16.735  1037  1526 D WifiMonitor: connecting to supplicant
,08-30 22:56:16.738  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:16.739  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 22:56:16.740  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 22:56:16.743  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:16.743  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:16.744  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:16.759  7412  7412 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 22:56:16.765  7367  7367 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 22:56:16.769  7367  7367 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 22:56:16.800  7412  7412 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 22:56:16.801  7412  7412 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-30 22:56:16.801   316  1373 V AudioPolicyService: registerClient() client 0xb558ace0, uid 10093
08-30 22:56:16.802  7367  7425 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 22:56:16.808  7367  7367 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 22:56:16.808  7367  7367 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 22:56:16.809  7367  7367 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 22:56:16.824  7367  7367 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 22:56:16.824  7367  7367 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 22:56:16.824  7367  7367 I Adreno-EGL: Build Date: 12/12/14 금
08-30 22:56:16.824  7367  7367 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 22:56:16.824  7367  7367 I Adreno-EGL: Remote Branch: 
08-30 22:56:16.824  7367  7367 I Adreno-EGL: Local Patches: 
08-30 22:56:16.824  7367  7367 I Adreno-EGL: Reconstruct Branch: 
,08-30 22:56:16.885  7367  7367 I NSApplication: Starting up...
,08-30 22:56:16.900  7412  7412 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 22:56:16.984  1037  2342 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7440 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 22:56:16.986  7412  7412 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 22:56:16.989  1037  2019 I ActivityManager: Killing 6097:com.android.vending/u0a44 (adj 15): empty #17
08-30 22:56:16.992  7412  7412 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 22:56:16.992  7412  7412 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 22:56:16.995  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 22:56:16.996  1037  7452 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 22:56:16.996  1037  7452 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 22:56:16.996  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 22:56:16.996  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 22:56:16.996  1037  7452 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 22:56:16.996  1037  7452 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 22:56:16.996  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 22:56:16.998  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 22:56:16.999  1037  1526 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-30 22:56:17.000  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:17.001  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:17.003  1037  1526 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 22:56:17.003  1037  1526 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 22:56:17.004  1037  1526 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 22:56:17.004  1037  1526 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 22:56:17.004  1037  1526 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 22:56:17.037  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 22:56:17.037  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
08-30 22:56:17.037  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 22:56:17.037  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.037  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.037  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.037  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.037  1037  1526 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 22:56:17.037  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 22:56:17.038  1037  1526 D WifiNative-wlan0: SET update_config 1: returned true
08-30 22:56:17.038  1037  1526 D WifiConfigStore: Loading config and enabling all networks 
08-30 22:56:17.039  1037  1526 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 22:56:17.039  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.039  1037  1526 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-30 22:56:17.041  1954  1954 D WfdService: Waiting for WifiP2p enabling
08-30 22:56:17.045  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:17.045  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:17.045  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:17.045  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:17.045  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:17.045  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:17.045  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:17.045  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:17.045  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:17.045  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:17.045  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:17.046  1037  1526 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 22:56:17.048  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:17.048  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:17.048  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:17.048  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:17.048  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:17.048  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:17.048  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:17.048  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:17.048  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:17.048  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:17.048  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:17.051  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:17.051  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:17.051  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:17.051  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:17.051  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:17.051  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:17.051  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-30 22:56:17.051  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:17.051  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:17.051  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:17.051  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:17.051  1037  1953 W libprocessgroup: failed to open /acct/uid_10044/pid_6097/cgroup.procs: No such file or directory
08-30 22:56:17.053  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 22:56:17.053  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-30 22:56:17.056  1037  1526 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 22:56:17.056  1037  1526 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 22:56:17.057  1037  1526 D WifiStateMachine: enableVerboseLogging : level 2
08-30 22:56:17.057  1037  1526 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 22:56:17.058  1037  1526 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 22:56:17.058  1037  1526 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 22:56:17.059  1037  1526 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 22:56:17.059  1037  1526 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 22:56:17.059  1037  1526 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 22:56:17.059  1037  1526 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 22:56:17.060  1037  1526 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 22:56:17.060  1037  1526 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 22:56:17.060  1037  1526 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 22:56:17.060  1037  1526 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 22:56:17.061  1037  1526 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 22:56:17.061  1037  1526 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 22:56:17.061  1037  1526 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 22:56:17.062  1954  1954 D WfdsService: Supplicant Connection state is changed : true
08-30 22:56:17.062  1954  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 22:56:17.062  1954  2334 D WfdsService: Set the WFDS Monitor: true
08-30 22:56:17.062  1954  2334 D WfdsMonitor: WfdsMonitorThread create
08-30 22:56:17.062  1037  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 22:56:17.062  1037  1526 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-30 22:56:17.063  1954  2334 D WfdsMonitor: WFDS Monitor is created and started
08-30 22:56:17.063  1954  2334 D WfdsService: WiFi: Supplicant connection re-established
08-30 22:56:17.063  1037  1526 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 22:56:17.063  1037  1526 D WifiNative-HAL: Setting external_sim to 1
08-30 22:56:17.063  1037  1526 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 22:56:17.064  1037  1526 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 22:56:17.064  1037  1526 I WifiNative-HAL: startHal
08-30 22:56:17.064  1037  1526 D wifi    : setting scan oui 0x9c35cfe0
08-30 22:56:17.064  1954  7460 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 22:56:17.064  1037  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 22:56:17.064  1037  1526 I WifiNative-HAL: startHal
08-30 22:56:17.065  1037  1526 D wifi    : setting scan oui 0x9c35cfe0
08-30 22:56:17.065  1954  7460 E CtrlSupplicant: Succeed to open control connection
08-30 22:56:17.065  1037  1526 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 22:56:17.065  1954  7460 E CtrlSupplicant: Succeed to open monitor connection
08-30 22:56:17.065  1037  1526 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 22:56:17.065  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 22:56:17.065  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 22:56:17.065  1954  7460 D WfdsMonitor: Supplicant connection established
08-30 22:56:17.066  1954  2334 D WfdsService: Connected to the supplicant for wfds
08-30 22:56:17.066  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 22:56:17.066  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 22:56:17.066  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 22:56:17.066  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 22:56:17.066  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 22:56:17.067  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 22:56:17.067  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 22:56:17.067  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 22:56:17.068  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 22:56:17.068  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 22:56:17.068  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-30 22:56:17.068  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 22:56:17.069  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 22:56:17.069  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 22:56:17.069  7412  7412 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 22:56:17.070  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 22:56:17.070  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 22:56:17.070  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 22:56:17.070  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 22:56:17.071  1037  1526 E WifiNative: : [221,663,771 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 22:56:17.072  1037  1526 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 22:56:17.072  1037  1526 D WifiNative-wlan0: RECONNECT: returned true
08-30 22:56:17.072  1037  1526 D WifiNative-wlan0: doString: [STATUS]
,08-30 22:56:17.073  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 22:56:17.073  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 22:56:17.073  1037  1526 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 22:56:17.073  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 22:56:17.074  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
08-30 22:56:17.074  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.075  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 22:56:17.075  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-30 22:56:17.075  1037  1545 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.075  1037  1546 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.075  1037  1545 I WifiNative-HAL: startHal
08-30 22:56:17.075  1037  1545 D wifi    : getting scan capabilities on interface[1] = 0x9c35cfe0
08-30 22:56:17.075  1037  1545 D wifi    : failed to get capabilities : -3
08-30 22:56:17.075  1037  1545 E WifiScanningService: could not get scan capabilities
08-30 22:56:17.075  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 22:56:17.076  1037  1526 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 22:56:17.076   312   895 D CommandListener: Setting iface cfg
08-30 22:56:17.076   312   895 D CommandListener: Trying to bring up p2p0
08-30 22:56:17.076  1037  1526 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 22:56:17.076  1037  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 22:56:17.076  1037  1524 D LGWifiP2pService: P2pEnablingState
08-30 22:56:17.076  1037  1524 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.076  1037  1524 D LGWifiP2pService: P2p socket connection successful
08-30 22:56:17.076  1037  1524 D LGWifiP2pService: P2pEnabledState
08-30 22:56:17.077  1037  1526 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 22:56:17.077  1037  1524 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 22:56:17.077  1037  1526 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 22:56:17.077  1037  1526 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 22:56:17.078  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 22:56:17.078  1954  1954 D WfdsService: WifiP2pState is changed : true
08-30 22:56:17.078  1954  2334 D WfdsService: Receive the WFDS_ENABLE Method
08-30 22:56:17.078  1954  2334 D WfdsService: Set the WFDS Monitor: true
,08-30 22:56:17.078  1954  2334 D WfdsService: Connected to the supplicant for wfds
08-30 22:56:17.078  1954  2334 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 22:56:17.078  7412  7412 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 22:56:17.078  1037  1526 E WifiStateMachine:  DriverStartedState what:132106 1 0
,08-30 22:56:17.078  1037  1526 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 22:56:17.078  1954  2334 D WfdsService: selectPreferredScanChannel [36]
08-30 22:56:17.078  1954  2334 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 22:56:17.078  7412  7412 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 22:56:17.078  1037  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 22:56:17.079  1037  1526 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 22:56:17.079  1954  1954 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 22:56:17.079  1037  1526 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,08-30 22:56:17.079  1954  1954 D WfdsService: isConnected: false
08-30 22:56:17.080  1037  1526 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 22:56:17.080  1037  1526 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 22:56:17.080  7412  7412 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 22:56:17.080  1037  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 22:56:17.080  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 22:56:17.081  1037  1526 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 22:56:17.081  1037  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
,08-30 22:56:17.081  1037  1526 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 22:56:17.081  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 22:56:17.082  1037  1524 D WifiNative-p2p0: SET device_name G3: returned true
08-30 22:56:17.082  1037  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 22:56:17.082  1037  1524 D LGWifiP2pService: before postfix = G3
08-30 22:56:17.082  1037  1524 D WifiServerServiceExt: postfix byte check : 2
08-30 22:56:17.082  1037  1524 D LGWifiP2pService: after postfix = G3
08-30 22:56:17.082  1037  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,08-30 22:56:17.083  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 22:56:17.083  7440  7440 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:56:17.083  7412  7412 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:17.083  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 22:56:17.083  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:17.084  1037  7452 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:17.084  1037  7452 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-30 22:56:17.084  7412  7412 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 22:56:17.084  7412  7412 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.084  1954  7460 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:17.084  1037  7452 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:17.084  1037  7452 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.085  1037  7452 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.085  1037  7452 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-30 22:56:17.085  7412  7412 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.085  1954  7460 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-30 22:56:17.086  1037  7452 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:17.086  1037  7452 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.086  1037  1526 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 22:56:17.086  1037  7452 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.086  1037  7452 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.086  1037  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 22:56:17.086  1037  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 22:56:17.087  1037  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 22:56:17.087  1037  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 22:56:17.087  1037  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 22:56:17.087  1037  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 22:56:17.087  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 22:56:17.088  1037  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 22:56:17.088  1037  1524 D WifiNative-HAL: p2pGetDeviceAddress
08-30 22:56:17.088  1037  1526 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 22:56:17.088  1037  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 22:56:17.088  1037  1526 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 22:56:17.088  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 22:56:17.089  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 22:56:17.089  7412  7412 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 22:56:17.090  1037  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 22:56:17.090  1037  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 22:56:17.090  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 22:56:17.090  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 22:56:17.090  1954  1954 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 22:56:17.090  1037  7452 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 22:56:17.090  1954  1954 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 22:56:17.090  1037  7452 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 22:56:17.090  1954  1954 D WfdsService: Update P2p Interface State: 3
08-30 22:56:17.090  1037  1526 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 22:56:17.090  1037  1526 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 22:56:17.091  1037  1526 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 22:56:17.091  1037  1526 D WifiNative-wlan0: doBoolean: SCAN
08-30 22:56:17.091  1037  1526 D WifiNative-wlan0: SCAN: returned false
08-30 22:56:17.092  1037  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 22:56:17.092  1037  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 22:56:17.092  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=221685  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 22:56:17.092  1037  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 22:56:17.092  1037  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 22:56:17.093  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=221686  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 22:56:17.094  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), ex,tra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:17.094  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:17.094  1037  1526 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:17.094  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.094  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.094  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 22:56:17.095  1037  1526 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:17.095  1037  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 22:56:17.095  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.095  1037  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 22:56:17.096  1037  1526 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:17.096  1037  1526 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:17.097  1037  1526 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:17.097  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:17.097  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-30 22:56:17.109  1037  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 22:56:17.109  1037  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-30 22:56:17.109  1037  1524 D LGWifiP2pService: InactiveState
,08-30 22:56:17.109  1037  1524 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.109  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.109  1037  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 22:56:17.110  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 22:56:17.110  7412  7412 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:17.111  1037  7452 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 22:56:17.111  1037  7452 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:17.111  1037  7452 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:17.111  1037  7452 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:17.111  7412  7412 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 22:56:17.111  1954  7460 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 22:56:17.111  7412  7412 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.111  1037  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 22:56:17.111  1037  1524 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.111  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.111  1037  7452 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:17.111  1037  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.111  1037  7452 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.111  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.112  1037  7452 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.112  1037  7452 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.112  1037  1524 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.112  7412  7412 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.112  1037  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.112  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.112  1037  7452 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:17.112  1037  1524 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.112  1037  7452 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.112  1037  7452 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.112  1037  7452 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:17.112  1954  2334 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 22:56:17.112  1954  7460 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:17.112  1954  7460 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER ty,pe=WORLD]
08-30 22:56:17.113  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.113  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.113  1037  1524 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.113  1037  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.113  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.113  1037  1524 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.113  1037  1037 E WifiServerServiceExt: No p2p device connected
08-30 22:56:17.345  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 22:56:17.349  6518  7040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 22:56:17.362  2247  2247 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:17.376  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 22:56:17.376  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:17.376  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 22:56:17.376  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 22:56:17.378  7227  7227 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 22:56:17.381  7227  7227 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1a20d0ef
08-30 22:56:17.381  7227  7227 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 22:56:17.381  7227  7227 D AppUp4:CustFacade: isPhone : true
08-30 22:56:17.382  7227  7227 D AppUp4:CustModeStarterReceiver: begin check event
08-30 22:56:17.382  7227  7227 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 22:56:17.388  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:17.388  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 22:56:17.390  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 22:56:17.394  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:17.398  4747  7473 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 22:56:17.402  7252  7252 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 22:56:17.404  4747  7474 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:17.407  4747  7474 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 22:56:17.428  3158  3158 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 22:56:17.429  3158  3158 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:17.429  3158  3158 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 22:56:17.429  7252  7475 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:56:17.432  7145  7477 W FormManager: Network not available. Please check & try again.
08-30 22:56:17.432  7284  7284 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 22:56:17.433  7284  7284 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 22:56:17.442  7348  7348 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:17
,08-30 22:56:17.444  7348  7348 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 22:56:17.444  7348  7348 D Weather.Utils: 2 : All the weather widget is gone.
08-30 22:56:17.445  7145  7478 V FormManager: Network unavailable.
08-30 22:56:17.445  7348  7348 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 22:56:17.446  7348  7348 D WeatherAncestor: connectivity changed - connection : true
08-30 22:56:17.446  7348  7348 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e3f8e85
08-30 22:56:17.446  7348  7348 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 22:56:17.446  7348  7348 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 22:56:17.447  7348  7348 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 22:56:17.447  7348  7348 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 22:56:17.447  7348  7348 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:17
08-30 22:56:17.454  7145  7478 V FormManager: Network unavailable.
,08-30 22:56:17.471  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 22:56:17.472  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 22:56:17.472  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 22:56:17.472  7021  7021 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 22:56:17.472  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 22:56:17.473  7021  7021 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-30 22:56:17.473  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 22:56:17.473  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 22:56:17.473  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 22:56:17.473  7021  7021 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 22:56:17.473  7021  7021 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 22:56:17.481  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:17.484  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:56:17.488  7145  7481 W FormManager: Network not available. Please check & try again.
,08-30 22:56:17.491  7145  7482 V FormManager: Network unavailable.
08-30 22:56:17.492  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:17.498  7145  7482 V FormManager: Network unavailable.
,08-30 22:56:17.516  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 22:56:17.521  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 22:56:17.525  7145  7484 W FormManager: Network not available. Please check & try again.
08-30 22:56:17.530  7145  7485 V FormManager: Network unavailable.
08-30 22:56:17.532  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 22:56:17.545  7145  7485 V FormManager: Network unavailable.
,08-30 22:56:17.556  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 22:56:17.556  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 22:56:17.559  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:17.562  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 22:56:17.573  4747  7486 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 22:56:17.574  4747  7487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 22:56:17.574  4747  7487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 22:56:17.623  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 22:56:17.624  1037  7452 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 22:56:17.624  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 22:56:17.624  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-30 22:56:17.624  1037  7452 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 22:56:17.625  7412  7412 E wpa_supplicant: USIM:  scard_init function
08-30 22:56:17.625  1037  1526 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-30 22:56:17.625  1037  1526 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 22:56:17.626  7412  7412 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 22:56:17.626  1037  1526 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 22:56:17.626  1037  1526 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 22:56:17.626  1037  1526 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 22:56:17.630  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 22:56:17.630  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 22:56:17.641  1037  2342 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7488 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 22:56:17.645  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=222238  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 22:56:17.649  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:17.649  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:17.650  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.651  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.651  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.651  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 22:56:17.652  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=222245  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 22:56:17.656  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.656  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.656  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 22:56:17.661  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:17.661  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 22:56:17.670  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 22:56:17.670  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:17.670  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:17.740  7488  7488 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 22:56:17.740  7488  7488 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 22:56:17.747  7412  7412 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 22:56:17.748  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 22:56:17.748  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 22:56:17.748  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 22:56:17.748  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 22:56:17.749  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:17.749  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 22:56:17.750  7488  7488 V [BNRBootReceiver]: Boot Receiver Return
08-30 22:56:17.750  7488  7488 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 22:56:17.751  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=222344  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 22:56:17.752  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=222345  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 22:56:17.753  1037  1526 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222346
08-30 22:56:17.753  1037  1526 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222346
08-30 22:56:17.753  1037  1526 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222347
08-30 22:56:17.754  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222347
08-30 22:56:17.754  1037  1526 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222347
08-30 22:56:17.755  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=222348  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 22:56:17.757  7412  7412 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 22:56:17.757  7412  7412 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 22:56:17.758  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:17.758  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 22:56:17.758  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 22:56:17.758  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 22:56:17.758  1037  7452 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 22:56:17.759  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 22:56:17.759  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 22:56:17.759  1037  7452 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 22:56:17.759  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:17.759  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dis,patchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-30 22:56:17.760  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:17.761  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 22:56:17.767  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.767  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.767  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 22:56:17.769  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:17.769  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:17.772  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=222365  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 22:56:17.774  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:17.775  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.776  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.776  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 22:56:17.776  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:17.776  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 22:56:17.776  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=222369  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 22:56:17.776  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:17.777  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:17.777  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=222370  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 22:56:17.777  1037  1526 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=222370
08-30 22:56:17.778  1037  1526 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=222371
08-30 22:56:17.778  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.778  1037  1526 D WifiNative-wlan0: doString: [STATUS]
08-30 22:56:17.778  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:17.779  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 22:56:17.779  1037  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 22:56:17.780  1037  1526 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 22:56:17.784  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:17.789  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:17.791  1037  1526 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 22:56:17.791  1037  1526 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 22:56:17.795  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:17.795  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:17.796  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.796  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.796  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:56:17.796  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 22:56:17.799  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.799  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.799  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 22:56:17.800  1037  1526 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 22:56:17.800  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 22:56:17.800  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 22:56:17.800  1037  1532 D ConnectivityService: Got NetworkAgent Messenger
08-30 22:56:17.800  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 22:56:17.800  1037  1532 D ConnectivityService: NetworkAgent connected
08-30 22:56:17.800  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 22:56:17.800  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 22:56:17.809  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:17.809  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 22:56:17.811  7075  7075 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 22:56:17.814  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 22:56:17.815  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 22:56:17.815  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 22:56:17.815  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 22:56:17.816  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 22:56:17.816  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 22:56:17.816  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:17.816  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:17.817  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.819  7021  7021 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 22:56:17.823  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:17.823  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 22:56:17.824   312   895 D CommandListener: Setting iface cfg
08-30 22:56:17.832  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:17.832  1037  1526 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 22:56:17.832  1037  7507 D DhcpStateMachine: StoppedState
08-30 22:56:17.832  1037  7507 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.833  1037  7507 D DhcpStateMachine: WaitBeforeStartState
08-30 22:56:17.833  1037  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=222426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:17.833  1037  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=222426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 22:56:17.834  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=222427  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:17.835  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:17.835  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:17.835  1037  1526 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:17.836  1037  1526 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-30 22:56:17.836  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:17.837  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:17.837  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:17.837  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 22:56:17.838  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:17.840  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:17.840  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 22:56:17.841  1037  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=222434  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:17.842  1037  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=222435  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:17.843  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=222436  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:17.844  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:176087] from screen [on:0 period:-583204684] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 22:56:17.845  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-583204683] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 22:56:17.845  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 22:56:17.845  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:17.846  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:17.847  7075  7075 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 22:56:17.851  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:17.853  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.853  1037  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 22:56:17.854  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.856  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.856  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.856  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.857  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.857  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.858  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 22:56:17.858  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=123,0,0
08-30 22:56:17.859  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=123,0,0
08-30 22:56:17.859  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 22:56:17.859  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 22:56:17.860  1037  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 22:56:17.860  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 22:56:17.860  1037  1526 D WifiNative-wlan0: SET ps 0: returned true
08-30 22:56:17.860  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 22:56:17.860  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:17.860  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 22:56:17.861  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 22:56:17.861  1037  1526 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 22:56:17.861  1037  1526 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 22:56:17.861  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14ab48f3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.861  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14ab48f3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.861  1037  1526 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 22:56:17.861  1037  7507 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.861  1037  7507 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 22:56:17.862   312   895 D CommandListener: Setting iface cfg
08-30 22:56:17.863   312   895 D CommandListener: Trying to bring up wlan0
,08-30 22:56:17.865  1037  1526 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 22:56:17.866  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:17.866  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 22:56:17.868  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:17.868  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.868  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 22:56:17.868  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:17.868  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.869  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.869  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.869  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.870  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:17.870  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 22:56:17.871  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 22:56:17.871  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 22:56:17.872  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 22:56:17.872  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.872  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.872  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 22:56:17.872  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 22:56:17.872  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 22:56:17.873  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 22:56:17.873  1037  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 22:56:17.873  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 22:56:17.875  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 22:56:17.876  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:17.877  7075  7075 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 22:56:17.881  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 22:56:17.881  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 22:56:17.881  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 22:56:17.881  7021  7021 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 22:56:17.881  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 22:56:17.882  7021  7021 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 22:56:17.882  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 22:56:17.882  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 22:56:17.882  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 22:56:17.882  7021  7021 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 22:56:17.882  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 22:56:17.883  7021  7021 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 22:56:17.886  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:17.889  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
08-30 22:56:17.890  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 22:56:17.890  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 22:56:17.890  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 22:56:17.890  1037  1526 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 22:56:17.891  1037  1532 D ConnectivityService: ignoring duplicate network state non-change
08-30 22:56:17.894  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:17.894  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:17.895  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.897  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.897  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.897  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 22:56:17.898  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 22:56:17.899  1037  1532 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 22:56:17.903  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.904  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.904  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 22:56:17.908  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:17.909  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 22:56:17.910  1037  1526 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 22:56:17.914  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.914  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.915  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 22:56:17.915  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 22:56:17.915  1954  1954 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 22:56:17.917  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:17.917  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 22:56:17.919  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.923  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:17.923  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 22:56:17.923  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.925  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.925  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:17.925  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 22:56:17.926  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:17.929  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 22:56:17.929  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 22:56:17.929  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:17.935  1037  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 22:56:17.935  1037  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 22:56:17.936  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:17.936  1037  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 22:56:17.936  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:17.937   312   895 E Netd    : netlink response contains error (File exists)
08-30 22:56:17.937  7075  7075 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 22:56:17.937  1037  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 22:56:17.938  1037  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 22:56:17.938  1037  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 22:56:17.938  1037  1532 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 22:56:17.941  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:17.941  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 22:56:17.941  1037  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 22:56:17.941  1037  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 22:56:17.941  1037  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 22:56:17.941  1037  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:17.941  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:17.941  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 22:56:17.942  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:17.942  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 22:56:17.942  1037  1532 D ConnectivityService: currentScore = 0, newScore = 20
08-30 22:56:17.942  1037  1532 D ConnectivityService:    accepting network in place of null
08-30 22:56:17.942  1037  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:17.942  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.943  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 22:56:17.943  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:17.943  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 22:56:17.945  1864  1864 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:17.946  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 22:56:17.946  1037  1526 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:17.947  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:17.947   312  7511 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 22:56:17.948  1037  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 22:56:17.948  1037  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIF,I () - 101] isDefaultNetwork=true
08-30 22:56:17.948  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 22:56:17.952  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:17.952  1037  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 22:56:17.952  1037  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 22:56:17.953  1037  1532 D ConnectivityService: validation of new default Network = false
08-30 22:56:17.953  1037  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 22:56:17.953  1037  1532 D DSQN    : enableDataServiceNotify 
08-30 22:56:17.953  1037  1532 D DSQN    : start dsqn bin
,08-30 22:56:17.955  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-30 22:56:17.955  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 22:56:17.955  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 22:56:17.955  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 22:56:17.962  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:17.966  1037  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 22:56:17.966  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:17.966  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:17.967  1037  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:17.963  7512  7512 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:17.963  7512  7512 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:17.973  1037  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-30 22:56:17.975  1590  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 22:56:17.976  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:17.984  7512  7512 E DSQN    : DSQN ssw
,08-30 22:56:17.987  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:17.988  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:17.988  7075  7075 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 22:56:17.992  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:17.994   312  7511 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 22:56:17.995  1826  7516 I CheckinService: active receiver: enabled
,08-30 22:56:18.011  6746  7192 D UEI.SmartControl: Internal timer expired: 2
08-30 22:56:18.011  6746  7192 D UEI.SmartControl: unbind internal service
,08-30 22:56:18.018  1826  7516 I CheckinService: Preparing to send checkin request
08-30 22:56:18.018  1826  7516 I EventLogService: Accumulating logs since 1472590398450
08-30 22:56:18.022  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:18.027   312  7511 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 22:56:18.028  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 22:56:18.028  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:18.029  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:18.029  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:18.034  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:18.034  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:18.034  7075  7075 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 22:56:18.037  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:18.041  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:18.046  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:18.050  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:18.051  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:18.051  7075  7075 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 22:56:18.054   312   894 D LGDataListener: argv[0]=dsqncommand
08-30 22:56:18.054   312   894 D LGDataListener: argv[1]=wlan0
08-30 22:56:18.054   312   894 D LGDataListener: argv[2]=1
08-30 22:56:18.054   312   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 22:56:18.055  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 22:56:18.055  1037  1117 D DSQN    : start to monitor internet connection
08-30 22:56:18.058  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:18.063  1037  7507 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 22:56:18.064  1037  7507 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 22:56:18.064  1037  7507 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 22:56:18.063  7520  7520 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:18.063  7520  7520 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:18.069  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:18.071  1826  7516 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 22:56:18.072  7520  7520 I dhcpcd  : version 5.5.6 starting
08-30 22:56:18.073  7520  7520 E dhcpcd  : get_duid: m
08-30 22:56:18.073  7520  7520 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 22:56:18.073  7520  7520 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-30 22:56:18.078  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 20:56:18 GMT], X-Android-Received-Millis=[1472590578078], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472590578053]}
08-30 22:56:18.078  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 22:56:18.078  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 22:56:18.079  1037  1532 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-30 22:56:18.079  1037  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 22:56:18.079  1037  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:18.079  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:18.079  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 22:56:18.079  1037  1532 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-30 22:56:18.079  1037  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 22:56:18.079  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:18.079  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:18.079  1037  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:18.079  1037  1532 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:18.080  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 22:56:18.080  1037  1526 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:18.080  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:18.080  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:18.080  1590  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 22:56:18.080  1864  1864 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:18.081  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 22:56:18.089  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:18.089  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:18.092  7075  7075 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 22:56:18.095  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:18.106  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:18.109  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 22:56:18.109  6746  7186 D serial_port: close(fd = 24)
08-30 22:56:18.109  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:18.110  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:18.112  6746  7186 I UEI.SmartControl: Serial port is closed.
08-30 22:56:18.114  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:18.119  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 22:56:18.119  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:18.119  7075  7075 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 22:56:18.123  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:18.127  7041  7041 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 22:56:18.129  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:18.131  7520  7520 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 22:56:18.132  7520  7520 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 22:56:18.132  7520  7520 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-30 22:56:18.132  7520  7520 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 22:56:18.132  7520  7520 D dhcpcd  : wlan0: sending REQUEST (xid 0x8fb6f317), next in 3.50 seconds
08-30 22:56:18.133  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:18.137  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:18.141  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:18.141  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:18.142  7075  7075 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 22:56:18.143  7075  7075 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 22:56:18.143  7075  7075 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 22:56:18.146  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:18.149  7041  7041 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 22:56:18.149  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:18.152  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:18.156  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:18.163  7520  7520 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 22:56:18.174  7520  7520 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 22:56:18.174  7520  7520 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 22:56:18.174  7520  7520 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 22:56:18.175  7520  7520 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 22:56:18.175  7520  7520 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 22:56:18.175  7520  7520 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 22:56:18.175  7520  7520 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 22:56:18.175  7520  7520 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-30 22:56:18.202  1037  1934 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7528 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-30 22:56:18.210  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:18.210  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:18.211  7075  7075 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 22:56:18.212  7075  7075 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 22:56:18.212  7075  7075 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 22:56:18.214  1037  1953 I ActivityManager: Killing 6994:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 22:56:18.258  1037  2072 W libprocessgroup: failed to open /acct/uid_10037/pid_6994/cgroup.procs: No such file or directory
08-30 22:56:18.297  7528  7528 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 22:56:18.297  7528  7528 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 22:56:18.318  7528  7528 I MultiDex: VM with version 2.1.0 has multidex support
08-30 22:56:18.318  7528  7528 I MultiDex: install
08-30 22:56:18.318  7528  7528 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 22:56:18.328  7528  7528 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 22:56:18.332  2247  2247 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 22:56:18.341  2247  2247 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 22:56:18.342  2247  2247 D c       : Getting all permits...
08-30 22:56:18.342  2247  2247 D a       : Opening database...
08-30 22:56:18.346  2247  2247 D a       : Opening database auth.proximity.permit_store...
,08-30 22:56:18.347  2247  2247 D a       : Closing database...
08-30 22:56:18.468  1037  7507 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 22:56:18.471  1037  7507 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-30 22:56:18.471  1037  7507 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 22:56:18.472  1037  7507 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,08-30 22:56:18.472  1037  7507 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-30 22:56:18.472  1037  7507 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-30 22:56:18.472  1037  7507 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
,08-30 22:56:18.472  1037  7507 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-30 22:56:18.473  1037  7507 D DhcpStateMachine: RunningState
08-30 22:56:18.515  1037  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3fa19ec8 type 2 when 223106 android} when 223106
,08-30 22:56:18.524  7075  7075 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 22:56:18.525  7075  7075 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:726
08-30 22:56:18.882  7574  7574 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 22:56:18.949  7574  7574 I dex2oat : dex2oat took 66.727ms (threads: 4)
,08-30 22:56:18.965  7528  7546 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 22:56:18.965  7528  7546 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 22:56:18.965  7528  7546 I Adreno-EGL: Build Date: 12/12/14 금
08-30 22:56:18.965  7528  7546 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 22:56:18.965  7528  7546 I Adreno-EGL: Remote Branch: 
08-30 22:56:18.965  7528  7546 I Adreno-EGL: Local Patches: 
08-30 22:56:18.965  7528  7546 I Adreno-EGL: Reconstruct Branch: 
,08-30 22:56:18.970  1037  1532 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 22:56:19.080  7528  7546 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:56:19.080  7528  7546 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:19.135  7528  7546 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 22:56:19.135  7528  7546 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 22:56:19.135  7528  7546 I Adreno-EGL: Build Date: 12/12/14 금
08-30 22:56:19.135  7528  7546 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 22:56:19.135  7528  7546 I Adreno-EGL: Remote Branch: 
08-30 22:56:19.135  7528  7546 I Adreno-EGL: Local Patches: 
08-30 22:56:19.135  7528  7546 I Adreno-EGL: Reconstruct Branch: 
,08-30 22:56:19.195  7528  7546 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 22:56:19.195  7528  7546 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 22:56:19.195  7528  7546 I Adreno-EGL: Build Date: 12/12/14 금
08-30 22:56:19.195  7528  7546 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 22:56:19.195  7528  7546 I Adreno-EGL: Remote Branch: 
08-30 22:56:19.195  7528  7546 I Adreno-EGL: Local Patches: 
08-30 22:56:19.195  7528  7546 I Adreno-EGL: Reconstruct Branch: 
,08-30 22:56:19.259  1037  1526 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:19.260  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:19.262  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:19.263  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:19.264  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 22:56:19.272  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:19.273  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-30 22:56:19.273  1037  1532 D ConnectivityService: identical MTU - not setting
08-30 22:56:19.273  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 22:56:19.274  1037  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 22:56:19.274  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:19.274  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:19.276  1037  1532 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:19.277  1590  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 22:56:19.329   312  7582 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 22:56:19.329   312  7582 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 22:56:19.362   312  7582 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 22:56:19.456  1826  7516 I CheckinTask: Sending checkin request (7831 bytes)
,08-30 22:56:19.689  1826  7516 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 22:56:19.699  1826  7516 I CheckinService: active receiver: disabled
,08-30 22:56:19.731  2247  2247 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 22:56:19.751  2247  2247 I GCM     : GCM config loaded
,08-30 22:56:19.768   312  7588 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 22:56:19.771   312  7588 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 22:56:19.778  7284  7284 V SetupWizard: Connected to Gservices successfully
08-30 22:56:19.807   312  7588 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-30 22:56:20.122  2247  7591 D GCM     : Connected
,08-30 22:56:20.175  2247  7591 D GCM     : Message class com.google.e.a.a.q
,08-30 22:56:20.860  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=61.5, 0.0, 0.0  rx=65.5 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-583201668] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:56:20.861  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=61.5, 0.0, 0.0  rx=65.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-583201667] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:56:20.861  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 22:56:20.881  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:20.913  1037  1527 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-30 22:56:20.954  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:20.962  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-30 22:56:20.973  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:20.973  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:20.973  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:20.973  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:20.973  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:20.973  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:20.973  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:20.973  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:56:20.973  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:20.973  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 22:56:20.978  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:20.979  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:20.979  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:20.979  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:20.979  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:20.979  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:20.979  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:20.979  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:20.979  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:56:20.979  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:20.979  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:20.980  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:20.981  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:20.981  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:20.981  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:20.981  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:20.981  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:20.981  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:20.981  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:20.981  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:56:20.981  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:20.981  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:20.981  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:20.985  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:20.990  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 22:56:20.996  6518  7040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 22:56:21.006  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 22:56:21.040  2247  2247 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:21.049  1037  1953 D WifiServiceImplEx: setWifiEnabled: false pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 22:56:21.049  1037  1953 D WifiService: setWifiEnabled: false pid=6865, uid=10118
08-30 22:56:21.049  1037  1953 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 22:56:21.067  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 22:56:21.068  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:21.068  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 22:56:21.068  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 22:56:21.070  7227  7227 I AppUp4:CustModeStarterReceiver: onReceive
08-30 22:56:21.073  7227  7227 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1a20d0ef
08-30 22:56:21.073  7227  7227 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 22:56:21.073  7227  7227 D AppUp4:CustFacade: isPhone : true
08-30 22:56:21.074  7227  7227 D AppUp4:CustModeStarterReceiver: begin check event
08-30 22:56:21.074  7227  7227 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 22:56:21.077  1037  1526 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:21.077  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 22:56:21.077  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:21.077  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-30 22:56:21.077  1037  1526 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:21.078  1037  1526 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:21.078  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-30 22:56:21.078  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 22:56:21.078  1037  1526 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 22:56:21.078  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 22:56:21.078  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 22:56:21.079  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 22:56:21.084  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 22:56:21.085  1037  2077 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,08-30 22:56:21.086  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.086  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.086  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 22:56:21.086  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.086  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 22:56:21.090  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 22:56:21.090  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 22:56:21.090  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 22:56:21.091  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 22:56:21.091  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 22:56:21.091  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
08-30 22:56:21.091   312   895 D CommandListener: Clearing all IP addresses on wlan0
08-30 22:56:21.092  1037  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.092  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.095  1037  7507 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.098  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 22:56:21.100   312  7605 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 22:56:21.101  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 22:56:21.101  1037  1117 D DSQN    : Dns fail occured do internet check.
08-30 22:56:21.101  1037  1037 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-30 22:56:21.101  1037  1037 D DSQN    : try Internet connection check
08-30 22:56:21.106  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:21.107   312  7612 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 22:56:21.107  1037  7611 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-30 22:56:21.108  1037  1117 D DSQN    : Dns timeout INTERNET_CHECK already in progress ignore!
08-30 22:56:21.108  1037  7606 D DSQN    : ThreadInternetCheck internet check NOK 
08-30 22:56:21.108  1037  7606 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-30 22:56:21.108  1037  7606 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-30 22:56:21.109  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 22:56:21.109  1037  1037 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-30 22:56:21.111  1954  1969 D WifiServiceExtension: isInternetCheckAvailable return false
08-30 22:56:21.112  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 22:56:21.120  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:21.121  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 22:56:21.121  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-30 22:56:21.134  7252  7252 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 22:56:21.135  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:21.135  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:21.135  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:21.135  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:21.136  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:21.136  1037  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.136  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.136  1037  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1a0a4325
08-30 22:56:21.137  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-30 22:56:21.136  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:21.138  1037  1526 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 22:56:21.138  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:21.138  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:21.138  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:21.138  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 22:56:21.138  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:21.139  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:21.139  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-30 22:56:21.140  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:21.140  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:21.140  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 22:56:21.140  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 22:56:21.140  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-30 22:56:21.140  1037  1546 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.141  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:21.141  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:21.141  1954  1954 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 22:56:21.141  1037  1545 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.142  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:21.143  1037  1524 D LGWifiP2pService: P2pDisablingState
08-30 22:56:21.143  1037  1524 D LGWifiP2pService: P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.143  1037  1524 D LGWifiP2pService: p2p socket connection lost
08-30 22:56:21.143  1037  1524 D LGWifiP2pService: P2pDisabledState
08-30 22:56:21.143  1037  1526 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 22:56:21.144  1037  1526 D WifiNative,-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 22:56:21.144  7412  7412 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 22:56:21.145  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 22:56:21.145  1954  1954 D WfdsService: WifiP2pState is changed : false
08-30 22:56:21.145  1954  2334 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 22:56:21.145  1954  2334 D WfdsService: Set the WFDS Monitor: false
,08-30 22:56:21.145  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 22:56:21.145  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 22:56:21.148  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
08-30 22:56:21.148  1954  2334 D WfdsMonitor: WFDS Monitor is stopped
08-30 22:56:21.148  1954  2334 D WfdsService: STATE : WfdsDisabledState - enter
08-30 22:56:21.148  1954  7460 D CtrlSupplicant: Received on exit socket, terminate
08-30 22:56:21.148  1954  7460 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 22:56:21.148  1954  7460 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 22:56:21.148  1954  7460 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 22:56:21.149  1954  2335 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 22:56:21.149  1954  2334 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 22:56:21.149  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.149  1037  1524 D LGWifiP2pService: DefaultState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.149  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:21.149  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:21.151  4747  7617 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 22:56:21.152  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:21.155  4747  7618 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:21.159  4747  7618 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 22:56:21.162  7252  7620 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:21.169   312   895 D CommandListener: Clearing all IP addresses on wlan0
08-30 22:56:21.170  1037  1532 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 22:56:21.170  1037  1532 D DSQN    : disableDataServiceNotify
08-30 22:56:21.170  1037  1532 D DSQN    : stop dsqn bin
08-30 22:56:21.170  3158  3158 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 22:56:21.170  3158  3158 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:21.170  3158  3158 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 22:56:21.170  3158  3158 D PhoneState: setPdpRejectCasuse : false
08-30 22:56:21.170  7145  7624 W FormManager: Network not available. Please check & try again.
08-30 22:56:21.173  7284  7284 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 22:56:21.173  7284  7284 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 22:56:21.174  1037  1526 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 22:56:21.175  1037  1526 D WifiNative-p2p0: TERMINATE: returned true
08-30 22:56:21.175  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 22:56:21.175  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
08-30 22:56:21.175  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 22:56:21.175  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-30 22:56:21.175  1037  1532 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 22:56:21.175  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:21.176  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:21.176  1037  1532 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:21.176  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 22:56:21.176  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:21.177  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 22:56:21.177  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:21.177  1037  1532 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 22:56:21.177  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:21.177  1037  1532 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 22:56:21.177  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 22:56:21.177  1590  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 22:56:21.177  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 22:56:21.177  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.177  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.177  1037  7506 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 22:56:21.179  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:21.180  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 22:56:21.181  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:21.181  6865  6865 W org.th,aliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:21.181  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:21.181  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:21.181  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:21.181  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:21.181  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:21.181  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:21.181  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:21.181  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:21.182  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:21.182  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:21.182  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 22:56:21.182  1037  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 22:56:21.185  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:21.185  1037  1532 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:21.185  1037  1532 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:21.185  1037  1532 D NetworkManagementService: Removing idletimer
08-30 22:56:21.185  1037  1532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:21.185  1864  1864 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:21.185  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 22:56:21.186  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 22:56:21.186  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:21.186  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 22:56:21.186  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 22:56:21.187  1037  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 22:56:21.187  1037  1526 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:21.187  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:21.187  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:21.187  1037  1532 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 22:56:21.187  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:21.187  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:21.187  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:21.187  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:21.187  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:21.187  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:21.187  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:21.187  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:21.187  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:21.187  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:21.188  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:21.188  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:21.188  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:21.188  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:21.188  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:21.188  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:21.188  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:21.188  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:21.188  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:21.188  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:21.188  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:21.190  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 22:56:21.190  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 22:56:21.190  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 22:56:21.190  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 22:56:21.190  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 22:56:21.190  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 22:56:21.190  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 22:56:21.196  7348  7348 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:21
08-30 22:56:21.197  7348  7348 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 22:56:21.197  7348  7348 D Weather.Utils: 2 : All the weather widget is gone.
08-30 22:56:21.198  7348  7348 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 22:56:21.198  7348  7348 D WeatherAncestor: connectivity changed - connection : true
08-30 22:56:21.198  7348  7348 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e3f8e85
08-30 22:56:21.199  7348  7348 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 22:56:21.199  7348  7348 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 22:56:21.199  7348  7348 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 22:56:21.199  7348  7348 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 22:56:21.199  7348  7348 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:21
08-30 22:56:21.202  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:21.202  7145  7626 V FormManager: Network unavailable.
08-30 22:56:21.210  7145  7626 V FormManager: Network unavailable.
08-30 22:56:21.215  7412  7412 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 22:56:21.215  7412  7412 I wpa_supplicant: monitor socket send errors count : 1
,08-30 22:56:21.215  7412  7412 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1954-4\x00 that cannot receive messages
08-30 22:56:21.216  1037  7452 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 22:56:21.216  1037  7452 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 22:56:21.231  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 22:56:21.232  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:21.233  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:21.233  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:21.239  7041  7041 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 22:56:21.239  7041  7041 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 22:56:21.239  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:21.241  7412  7412 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 22:56:21.241  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 22:56:21.241  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 22:56:21.241  1037  7452 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 22:56:21.241  1037  7452 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 22:56:21.241  7412  7412 W wpa_supplicant: USIM:  scard_deinit function
08-30 22:56:21.242  1037  1526 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=225835
08-30 22:56:21.242  1037  1526 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=225835
08-30 22:56:21.242  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:21.242  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 22:56:21.242  1037  1119 D Tethering: InitialState.processMessage what=4
08-30 22:56:21.243  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:21.243  1037  1526 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=225836  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 22:56:21.244  1037  1526 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=225837  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 22:56:21.245  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 22:56:21.247  1037  1526 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:21.247  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:21.250  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:21.258  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:21.259  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:21.260  7075  7075 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 22:56:21.263  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 22:56:21.264  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:21.264  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:21.265  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:21.269  7041  7041 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 22:56:21.269  7041  7041 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 22:56:21.269  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:21.273  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:21.277  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:21.283  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:21.283  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:21.285  7075  7075 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 22:56:21.288  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:21.293  7041  7041 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 22:56:21.293  7041  7041 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 22:56:21.293  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:21.298  1037  7507 D DhcpStateMachine: StoppedState
08-30 22:56:21.298  1037  7507 D DhcpStateMachine: StoppedState{ when=-150ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:21.299  1037  1526 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 22:56:21.299  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:21.300  1037  1526 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-30 22:56:21.308  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 22:56:21.316  7412  7412 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 22:56:21.316  1037  7452 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 22:56:21.316  1037  7452 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
,08-30 22:56:21.316  1037  7452 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 22:56:21.320  1037  1526 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-30 22:56:21.323  7075  7075 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:21.323  7075  7075 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:21.326  7075  7075 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 22:56:21.338  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:21.342  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:56:21.351  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:21.359  7145  7628 W FormManager: Network not available. Please check & try again.
,08-30 22:56:21.377  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-30 22:56:21.377  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 22:56:21.377  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 22:56:21.377  7021  7021 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-30 22:56:21.379  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 22:56:21.380  7145  7629 V FormManager: Network unavailable.
08-30 22:56:21.381  7021  7021 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 22:56:21.381  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 22:56:21.381  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 22:56:21.381  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 22:56:21.381  7021  7021 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 22:56:21.381  7021  7021 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 22:56:21.386  7145  7629 V FormManager: Network unavailable.
08-30 22:56:21.422  1037  1526 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 22:56:21.422  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 22:56:21.422  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
08-30 22:56:21.422  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 22:56:21.423  1954  1954 D WfdsService: Supplicant Connection state is changed : false
08-30 22:56:21.423  1954  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 22:56:21.423  1954  2334 D WfdsService: Set the WFDS Monitor: false
08-30 22:56:21.423  1954  2334 D WfdsMonitor: WFDS Monitor is stopped
08-30 22:56:21.424  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:21.426  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-30 22:56:21.427  2455  2455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:21.431  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:21.431  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:21.431  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:21.431  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:21.431  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:21.431  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:21.431  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:21.431  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:21.431  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:56:21.432  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:21.432  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:21.432  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:21.432  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:21.432  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:21.432  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:21.432  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:21.432  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:21.432  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:21.433  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:21.435  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 22:56:21.436  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 22:56:21.436  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 22:56:21.436  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 22:56:21.436  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 22:56:21.438  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:21.441  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 22:56:21.450  4747  7630 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 22:56:21.451  7041  7041 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 22:56:21.451  7041  7041 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 22:56:21.451  7041  7041 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:21.456  4747  7633 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-30 22:56:21.456  4747  7633 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 22:56:21.459  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 22:56:21.466  7145  7634 W FormManager: Network not available. Please check & try again.
08-30 22:56:21.466  7367  7388 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-30 22:56:21.468  7145  7635 V FormManager: Network unavailable.
,08-30 22:56:21.470  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:21.472  7145  7635 V FormManager: Network unavailable.
08-30 22:56:22.346  1037  1367 I ActivityManager: Killing 7092:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 22:56:22.379  1037  1636 W libprocessgroup: failed to open /acct/uid_1000/pid_7092/cgroup.procs: No such file or directory
,08-30 22:56:23.890  1037  1526 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-583198638] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:56:23.893  1037  1526 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-583198636] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 22:56:24.185  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:24.201  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-30 22:56:24.216  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:24.222  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:24.223  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:24.226  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:24.231  1037  1119 D Tethering: MasterInitialState.processMessage what=3
,08-30 22:56:24.239  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 22:56:24.242  6518  7040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 22:56:24.255  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:24.259  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:24.260  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:24.260  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 22:56:24.264  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 22:56:24.267  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:24.285  2247  2247 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:24.304  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 22:56:24.304  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:24.305  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 22:56:24.305  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 22:56:24.312  7227  7227 I AppUp4:CustModeStarterReceiver: onReceive
08-30 22:56:24.315  7227  7227 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1a20d0ef
08-30 22:56:24.316  7227  7227 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 22:56:24.316  7227  7227 D AppUp4:CustFacade: isPhone : true
08-30 22:56:24.316  7227  7227 D AppUp4:CustModeStarterReceiver: begin check event
08-30 22:56:24.323  7227  7227 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-30 22:56:24.331  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:24.331  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 22:56:24.332  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:24.335  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 22:56:24.352  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:24.354  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:24.354  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:24.354  7252  7252 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 22:56:24.359  4747  7658 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 22:56:24.368  4747  7659 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:24.368  4747  7659 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 22:56:24.379  7252  7662 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:56:24.391  3158  3158 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 22:56:24.391  3158  3158 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:24.391  3158  3158 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 22:56:24.392  7145  7665 W FormManager: Network not available. Please check & try again.
08-30 22:56:24.396  7284  7284 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 22:56:24.397  7284  7284 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 22:56:24.407  7348  7348 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:24
,08-30 22:56:24.409  7348  7348 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 22:56:24.410  7348  7348 D Weather.Utils: 2 : All the weather widget is gone.
08-30 22:56:24.410  7348  7348 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 22:56:24.410  7348  7348 D WeatherAncestor: connectivity changed - connection : true
08-30 22:56:24.411  7348  7348 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e3f8e85
08-30 22:56:24.411  7145  7666 V FormManager: Network unavailable.
08-30 22:56:24.412  7348  7348 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 22:56:24.412  7348  7348 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 22:56:24.412  7348  7348 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 22:56:24.412  7348  7348 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 22:56:24.412  7348  7348 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:24
08-30 22:56:24.413  7145  7666 V FormManager: Network unavailable.
08-30 22:56:24.425  1037  1906 I ActivityManager: Killing 7488:com.lge.bnr/1000 (adj 15): empty #17
,08-30 22:56:24.470  1037  2019 W libprocessgroup: failed to open /acct/uid_1000/pid_7488/cgroup.procs: No such file or directory
,08-30 22:56:24.494  6518  6518 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 22:56:24.499  6518  7040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 22:56:24.518  2247  2247 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:24.535  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-30 22:56:24.535  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:24.535  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 22:56:24.535  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 22:56:24.540  7227  7227 I AppUp4:CustModeStarterReceiver: onReceive
08-30 22:56:24.546  7227  7227 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1a20d0ef
08-30 22:56:24.546  7227  7227 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 22:56:24.546  7227  7227 D AppUp4:CustFacade: isPhone : true
08-30 22:56:24.546  7227  7227 D AppUp4:CustModeStarterReceiver: begin check event
08-30 22:56:24.547  7227  7227 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 22:56:24.553  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:24.554  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 22:56:24.560  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:24.567  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:24.577  4747  7670 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 22:56:24.579  7252  7252 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 22:56:24.585  4747  7671 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:24.586  4747  7671 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 22:56:24.613  7252  7673 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:56:24.632  3158  3158 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 22:56:24.632  3158  3158 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:24.632  3158  3158 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 22:56:24.640  7145  7675 W FormManager: Network not available. Please check & try again.
08-30 22:56:24.643  7284  7284 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 22:56:24.643  7284  7284 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 22:56:24.651  7145  7676 V FormManager: Network unavailable.
,08-30 22:56:24.666  7348  7348 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:24
,08-30 22:56:24.668  7145  7676 V FormManager: Network unavailable.
08-30 22:56:24.669  7348  7348 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 22:56:24.669  7348  7348 D Weather.Utils: 2 : All the weather widget is gone.
08-30 22:56:24.669  7348  7348 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 22:56:24.669  7348  7348 D WeatherAncestor: connectivity changed - connection : true
08-30 22:56:24.669  7348  7348 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e3f8e85
08-30 22:56:24.671  7348  7348 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 22:56:24.671  7348  7348 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 22:56:24.671  7348  7348 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 22:56:24.671  7348  7348 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 22:56:24.671  7348  7348 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:24
08-30 22:56:26.079  1037  2072 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 22:56:26.080  1037  2072 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-30 22:56:26.098  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 22:56:26.099  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 22:56:26.099  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-30 22:56:26.102  1037  1119 D BluetoothManagerService: Message: 1
08-30 22:56:26.102  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 22:56:26.130  1037  1119 D BluetoothManagerService: Message: 20
08-30 22:56:26.130  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1080f927:true
,08-30 22:56:26.134  7128  7128 D BluetoothAdapterState: make
08-30 22:56:26.139  7128  7128 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 22:56:26.140  7128  7128 I bluedroid-qcom: init
08-30 22:56:26.141  7128  7688 I BluetoothAdapterState: Entering OffState
08-30 22:56:26.141  7128  7128 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 22:56:26.141  7128  7128 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 22:56:26.142  7128  7128 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 22:56:26.142  7128  7128 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 22:56:26.142  7128  7128 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 22:56:26.144  7128  7128 I bluedroid-qcom: get_profile_interface socket
08-30 22:56:26.144  7128  7128 I bluedroid-qcom: get_profile_interface map_client
,08-30 22:56:26.148  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:26.148  1037  1524 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:26.143  7691  7691 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:26.151  7128  7692 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 22:56:26.153  7128  7692 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 22:56:26.143  7691  7691 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:26.163  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-30 22:56:26.167  1037  1119 D BluetoothManagerService: Message: 40
08-30 22:56:26.167  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 22:56:26.170  7691  7691 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 22:56:26.170  7691  7691 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 22:56:26.170  7691  7691 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 22:56:26.171  7128  7143 I bluedroid-qcom: config_hci_snoop_log
08-30 22:56:26.173  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 22:56:26.173  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 22:56:26.174  7691  7691 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 22:56:26.176  1037  1526 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 22:56:26.177  1037  1526 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 22:56:26.182  7691  7691 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 22:56:26.182  7691  7691 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 22:56:26.187  7128  7688 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 22:56:26.188  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 22:56:26.189  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 22:56:26.189  7128  7692 D BluetoothAdapterProperties: Name is: G3
08-30 22:56:26.191  7128  7688 D BluetoothAdapterProperties: Setting state to 11
08-30 22:56:26.192  7128  7688 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-30 22:56:26.194  1037  1119 D BluetoothManagerService: Message: 60
08-30 22:56:26.194  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 22:56:26.194  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 22:56:26.196  7128  7688 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 22:56:26.202  1954  1954 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:56:26.206  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 22:56:26.211  7021  7021 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 22:56:26.213  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:26.214  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:26.215  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:26.224  7128  7128 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 22:56:26.225  7128  7128 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:26.225  7128  7128 V BluetoothPbapReceiver: ***********state = 11
08-30 22:56:26.233  7128  7688 D BluetoothBondStateMachine: make
,08-30 22:56:26.239  2247  2247 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 22:56:26.243  7128  7688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.243  7128  7688 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 22:56:26.243  7128  7688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.243  7128  7688 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 22:56:26.243  7128  7688 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 22:56:26.255  7128  7693 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 22:56:26.260  7128  7688 E BluetoothAdapterService: File transfer profiles supported!!
08-30 22:56:26.306  1037  2098 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7704 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 22:56:26.314  7128  7128 D HeadsetService: Received start request. Starting profile...
08-30 22:56:26.315  7128  7128 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 22:56:26.315  7128  7128 D LGBluetoothHfpAdapter: Version 1.6
08-30 22:56:26.318  7128  7688 E BluetoothAdapterService: File transfer profiles supported!!
08-30 22:56:26.318  7128  7128 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 22:56:26.319  7128  7128 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 22:56:26.320  7128  7128 D HeadsetStateMachine: make
,08-30 22:56:26.331  7128  7688 E BluetoothAdapterService: File transfer profiles supported!!
08-30 22:56:26.340  7128  7688 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 22:56:26.347  7128  7688 E BluetoothAdapterService: File transfer profiles supported!!
08-30 22:56:26.353  7128  7688 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 22:56:26.365  7128  7128 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 22:56:26.366  7128  7128 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 22:56:26.480  1037  2072 I art     : Explicit concurrent mark sweep GC freed 141854(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.104ms total 123.937ms
,08-30 22:56:26.482  7128  7688 E BluetoothAdapterService: File transfer profiles supported!!
08-30 22:56:26.488  7128  7128 D HeadsetStateMachine: max_hf_connections = 1
08-30 22:56:26.488  7128  7128 I bluedroid-qcom: get_profile_interface handsfree
08-30 22:56:26.494  7128  7128 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 22:56:26.495  7128  7688 V LGMDMManager: Create singleton instance
08-30 22:56:26.496   316  1372 V AudioPolicyService: registerClient() client 0xb558a7c0, uid 1002
08-30 22:56:26.497   316  1373 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 22:56:26.497   316  1373 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 22:56:26.497   316  1373 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 22:56:26.497  7128  7128 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 22:56:26.497   316   316 V AudioFlinger: registerClient() client 0xb55816e8, pid 7128
08-30 22:56:26.497  7128  7688 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 22:56:26.497   316  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:26.497   316  1366 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 22:56:26.498  7128  7128 V ToneGenerator: Create Track: 0xb4928a80
08-30 22:56:26.498  7128  7128 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 22:56:26.498  1037  1053 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:26.498  1037  1053 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 22:56:26.498  7128  7128 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 22:56:26.498   316  1372 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 22:56:26.498   316  1372 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
,08-30 22:56:26.498   316  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-30 22:56:26.498   316  1372 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 22:56:26.498   316  1368 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:26.498   316  1368 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:26.498  7128  7128 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 22:56:26.498  1037  1053 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:26.498  1037  1053 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:26.498  1590  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:26.498  1590  1610 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 22:56:26.498  1590  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:26.498  7128  7144 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-30 22:56:26.498  1590  1610 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:26.498  7128  7144 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 22:56:26.498  7128  7144 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:26.498  7128  7144 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 22:56:26.498  1864  1880 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:26.498  1864  1880 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 22:56:26.498   316  4421 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 22:56:26.499  1864  1880 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:26.499  1864  1880 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:26.499  3158  3173 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:26.499   316  1372 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 22:56:26.499  3158  3173 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 22:56:26.499   316  1372 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 22:56:26.499   316  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 22:56:26.499   316  1372 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 22:56:26.499  3158  3173 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:26.499  3158  3173 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:26.499  7128  7128 V AudioSystem: getLatency() output 2, latency 50
08-30 22:56:26.499  7128  7128 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 22:56:26.499  7128  7128 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 22:56:26.499   316  1373 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 22:56:26.499   316  1373 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 22:56:26.499   316  1373 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 22:56:26.499   316  1373 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 22:56:26.499   316  1373 V AudioFlinger: createTrack() lSessionId: 22
08-30 22:56:26.500  7128  7128 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 22:56:26.500   316  4421 V AudioFlinger: acquiring 22 from 7128, for 7128
08-30 22:56:26.500   316  4421 V AudioFlinger:  added new entry for 22
08-30 22:56:26.500  7128  7128 V ToneGenerator: ToneGenerator INIT OK, time: 231106
08-30 22:56:26.501  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.501  7128  7719 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 22:56:26.501  7128  7719 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 22:56:26.501  7128  7719 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 22:56:26.501  7128  7719 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 22:56:26.502   316   316 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7128
,08-30 22:56:26.502   316   316 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 22:56:26.502   316   316 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 22:56:26.502   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 22:56:26.502   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 22:56:26.502   316   316 V voice   : voice_set_parameters: exit with code(0)
,08-30 22:56:26.502   316   316 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 22:56:26.502   316   316 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 22:56:26.502   316   316 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 22:56:26.502   316   316 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 22:56:26.502   316   316 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 22:56:26.502   316   316 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 22:56:26.502  7128  7719 V ToneGenerator: ToneGenerator destructor
08-30 22:56:26.502  7128  7719 V ToneGenerator: stopTone
08-30 22:56:26.502  7128  7719 V ToneGenerator: Delete Track: 0xb4928a80
08-30 22:56:26.502  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.502  7128  7719 V AudioTrack: ~AudioTrack, releasing session id from 7128 on behalf of 7128
08-30 22:56:26.503   316  1372 V AudioFlinger: releasing 22 from 7128 for 7128
08-30 22:56:26.503   316  1372 V AudioFlinger:  decremented refcount to 0
08-30 22:56:26.503   316  1372 V AudioFlinger: purging stale effects
08-30 22:56:26.503   316  1372 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 22:56:26.503   316  1372 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 22:56:26.503   316  1275 V AudioPolicyService: AudioCommandThread() waking up
08-30 22:56:26.503   316  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 22:56:26.503   316  1275 V AudioPolicyManager: releaseOutput() 2
08-30 22:56:26.503   316  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 22:56:26.503   316  1372 V AudioFlinger: PlaybackThread::Track destructor
08-30 22:56:26.503   316  1372 V AudioFlinger: removeClient_l() pid 7128, calling pid 316
08-30 22:56:26.504  7128  7128 D A2dpService: Received start request. Starting profile...
08-30 22:56:26.505  7128  7128 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 22:56:26.506  7128  7128 V Avrcp   : make
08-30 22:56:26.506  7128  7128 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 22:56:26.506  7128  7128 I bluedroid-qcom: get_profile_interface avrcp
08-30 22:56:26.509  1037  2342 W Process : Unable to open /proc/7729/status
08-30 22:56:26.516  7128  7128 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 22:56:26.518  7128  7128 E AudioManager: No RCC entry present to update
08-30 22:56:26.518  7128  7128 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 22:56:26.521  7128  7128 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 22:56:26.522  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 22:56:26.522  7128  7128 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-30 22:56:26.526  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 22:56:26.615  7704  7704 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 22:56:26.616  7704  7704 W LG Account v2.2: No ProfileInfo entries
,08-30 22:56:26.616  7704  7704 I LG Account v2.2: isEnabled: false
08-30 22:56:26.616  7704  7704 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 22:56:26.616  7704  7704 I Feature : [Lifetracker]Country: EU
08-30 22:56:26.616  7704  7704 I Feature : [Lifetracker]Operator: OPEN
08-30 22:56:26.616  7704  7704 I Feature : [Lifetracker]Ranking support: false
08-30 22:56:26.617  7704  7704 I Feature : [Lifetracker]Comfort support: false
08-30 22:56:26.617  7704  7704 I Feature : [Lifetracker]Accessory: true
08-30 22:56:26.617  7704  7704 I Feature : [Lifetracker]Health device: true
08-30 22:56:26.617  7704  7704 I Feature : [Lifetracker]Extra Pedometer: false
08-30 22:56:26.617  7704  7704 I Feature : [Lifetracker]Blood glucose device: false
08-30 22:56:26.617  7704  7704 I Feature : [Lifetracker]Device Number: 3
08-30 22:56:26.625  7021  7021 D BluetoothPermissionRequest: onReceive
08-30 22:56:26.627  7021  7021 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 22:56:26.637  1037  2077 V SIM_STK : Menu title from STK is T-Mobile
08-30 22:56:26.637  1037  2077 V SIM_STK : Menu title from STK is T-Mobile
,08-30 22:56:26.700  1037  1985 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 22:56:26.705  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 22:56:26.709  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 22:56:26.709  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 22:56:26.709  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 22:56:26.709  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 22:56:26.709  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 22:56:26.709  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 22:56:26.710  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 22:56:26.710  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 22:56:26.710  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 22:56:26.710  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 22:56:26.710  7128  7128 I BluetoothA2dpServiceJni: classInitNative
08-30 22:56:26.710  7128  7128 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 22:56:26.710  7128  7128 D A2dpStateMachine: make
08-30 22:56:26.712  7128  7128 I bluedroid-qcom: get_profile_interface a2dp
08-30 22:56:26.712  7128  7736 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 22:56:26.714  7128  7128 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 22:56:26.714  7128  7128 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 22:56:26.715  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.715  7128  7735 D A2dpStateMachine: Enter Disconnected: -2
08-30 22:56:26.715  7128  7128 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 22:56:26.716  7128  7128 D HidService: Received start request. Starting profile...
08-30 22:56:26.716  7128  7128 I bluedroid-qcom: get_profile_interface hidhost
08-30 22:56:26.716  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.717  7128  7128 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 22:56:26.718  7128  7128 D HealthService: Received start request. Starting profile...
08-30 22:56:26.720  7128  7128 I bluedroid-qcom: get_profile_interface health
08-30 22:56:26.720  7128  7128 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 22:56:26.720  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.721  7128  7128 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 22:56:26.722  7128  7128 D PanService: Received start request. Starting profile...
08-30 22:56:26.722  7128  7128 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 22:56:26.722  7128  7128 I bluedroid-qcom: get_profile_interface pan
08-30 22:56:26.726  7128  7128 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 22:56:26.726  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.727  7128  7128 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 22:56:26.730  7128  7128 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 22:56:26.730  7128  7128 D BtGatt.GattService: Received start request. Starting profile...
08-30 22:56:26.730  7128  7128 D BtGatt.GattService: start()
08-30 22:56:26.730  7128  7128 I bluedroid-qcom: get_profile_interface gatt
08-30 22:56:26.730  7128  7128 D BtGatt.AdvertiseManager: advertise manager created
,08-30 22:56:26.734  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.734  7128  7128 D HeadsetStateMachine: Proxy object connected
08-30 22:56:26.734  7128  7128 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 22:56:26.734  7128  7128 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 22:56:26.736  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:26.736  7128  7128 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 22:56:26.737  7128  7128 V BluetoothMapService: BluetoothMapBinder()
08-30 22:56:26.737  7128  7128 D BluetoothMapService: Received start request. Starting profile...
08-30 22:56:26.737  7128  7128 D BluetoothMapService: start()
08-30 22:56:26.739  7128  7128 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 22:56:26.739  7128  7128 D BluetoothMapEmailAppObserver: createReceiver()
08-30 22:56:26.740  7128  7128 D BluetoothMapEmailAppObserver: initObservers()
08-30 22:56:26.740  7128  7128 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 22:56:26.748  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
,08-30 22:56:26.751  7128  7128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 22:56:26.752  7128  7719 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 22:56:26.753  7128  7719 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 22:56:26.753  7128  7719 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 22:56:26.754  7128  7128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 22:56:26.757  7128  7128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 22:56:26.760  7128  7128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 22:56:26.760  7128  7128 V PanService: [BTUI] SIM Extra State :ABSENT
,08-30 22:56:26.762  7128  7128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 22:56:26.765  7128  7128 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 22:56:26.765  7128  7128 V BluetoothMapService: Handler(): got msg=1
08-30 22:56:26.766  7128  7688 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 22:56:26.766  7128  7688 I bluedroid-qcom: enable
08-30 22:56:26.766  7128  7743 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 22:56:26.766  7128  7688 I bt_hci_bdroid: init
08-30 22:56:26.766  7128  7743 I bt-btu  : btu_task pending for preload complete event
08-30 22:56:26.767  7128  7688 I bt_vendor: bt-vendor : init
08-30 22:56:26.767  7128  7688 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 22:56:26.767  7128  7688 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 22:56:26.767  7128  7688 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 22:56:26.767  7128  7688 D bt_userial_mct: userial_init
08-30 22:56:26.767  7128  7688 D bt_hci_bdroid: set_power 1
08-30 22:56:26.767  7128  7688 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 22:56:26.767  7128  7688 I bt_vendor: Starting hciattach daemon
08-30 22:56:26.767  7128  7688 I bt_vendor: try to set true
08-30 22:56:26.767  7128  7128 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:26.763  7746  7746 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:26.763  7746  7746 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:26.771  7128  7128 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 22:56:26.771  7128  7128 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 22:56:26.771  7128  7128 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 22:56:26.772  7128  7128 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:26.772  7128  7128 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-30 22:56:26.789  7747  7747 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 22:56:26.849  1037  2019 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7754 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 22:56:26.869  7766  7766 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 22:56:26.878   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 841us total 29.281ms
08-30 22:56:26.880  7773  7773 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 22:56:26.898   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 367us total 19.133ms
,08-30 22:56:26.905  7776  7776 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-30 22:56:26.916   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 17.672ms
,08-30 22:56:26.918  7777  7777 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 22:56:26.929  7778  7778 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 22:56:26.933  7754  7754 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 22:56:26.940  7783  7783 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 22:56:26.947  1037  2072 I ActivityManager: Killing 6746:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 22:56:26.960  7786  7786 I libmdmdetect: ESOC framework not supported
08-30 22:56:26.960  7786  7786 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 22:56:26.963  7075  7075 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 22:56:26.963  7075  7075 W System.err: android.os.DeadObjectException
,08-30 22:56:26.963  7075  7075 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 22:56:26.964  7075  7075 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 22:56:26.964  7075  7075 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 22:56:26.964  7075  7075 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 22:56:26.964  7075  7075 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 22:56:26.964  7075  7075 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 22:56:26.964  7075  7075 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 22:56:26.964  7075  7075 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 22:56:26.964  7075  7075 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 22:56:26.964  7075  7075 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 22:56:26.964  7075  7075 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:56:26.964  7075  7075 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:56:26.964  7075  7075 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 22:56:26.964  7075  7075 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 22:56:26.965  7075  7075 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 22:56:26.965  7075  7075 W System.err: android.os.DeadObjectException
08-30 22:56:26.965  7075  7075 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 22:56:26.965  7075  7075 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 22:56:26.965  7075  7075 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 22:56:26.965  7075  7075 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 22:56:26.965  7075  7075 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 22:56:26.965  7075  7075 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 22:56:26.965  7075  7075 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 22:56:26.965  7075  7075 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 22:56:26.965  7075  7075 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 22:56:26.965  7075  7075 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 22:56:26.965  7075  7075 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:56:26.965  7075  7075 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:56:26.966  7075  7075 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 22:56:26.966  7075  7075 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 22:56:26.966  7075  7075 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 22:56:26.966  7075  7075 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 22:56:26.968  7786  7786 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 22:56:26.968  7786  7786 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 22:56:26.968  7786  7786 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 22:56:26.968  7786  7786 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 22:56:26.968  7786  7786 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 22:56:26.968  7786  7786 D b,thci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 22:56:26.968  7786  7786 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 22:56:27.003  7786  7788 E QC-QMI  : qmi_client [7786] 14: failed to locate client data
08-30 22:56:27.003   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 22:56:27.004   461   461 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-30 22:56:27.029  1037  1934 W libprocessgroup: failed to open /acct/uid_1000/pid_6746/cgroup.procs: No such file or directory
,08-30 22:56:27.030  1037  1934 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-30 22:56:27.045  7075  7075 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 22:56:27.045  7075  7075 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 22:56:27.066  7790  7790 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 22:56:27.091  7791  7791 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 22:56:27.115  1037  1053 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7793 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 22:56:27.119  7128  7688 I bt_vendor: bluetooth satus is on
08-30 22:56:27.119  7075  7075 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 22:56:27.119  7128  7688 D bt_hci_bdroid: preload
08-30 22:56:27.119  7128  7745 D bt_userial_mct: userial_open(port:0)
08-30 22:56:27.119  7128  7745 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 22:56:27.122  7128  7745 I bt_vendor: Done intiailizing UART
08-30 22:56:27.125  7128  7745 I bt_vendor: Done intiailizing UART
08-30 22:56:27.125  7128  7745 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 22:56:27.126  7128  7745 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 22:56:27.126  7128  7808 D bt_userial_mct: Entering userial_read_thread()
08-30 22:56:27.127  7128  7743 I bt-btu  : btu_task received preload complete event
,08-30 22:56:27.128  7128  7743 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 22:56:27.128  7128  7743 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 22:56:27.135  7128  7743 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 22:56:27.139  7128  7743 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 22:56:27.202  7793  7793 D UEI.SmartControl: Quickset Services start...
,08-30 22:56:27.204  7793  7793 I UEI.SmartControl: Manufacture = LGE
08-30 22:56:27.205  7793  7793 D UEI.SmartControl: Id = LGNevo
08-30 22:56:27.209  7793  7793 D UEI.SmartControl: File observer start...
08-30 22:56:27.209  7128  7743 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 22:56:27.209  7128  7743 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d1061 
08-30 22:56:27.210  7128  7743 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d1061 
08-30 22:56:27.212  7793  7793 E UEI.SmartControl: IR Port is disabled: false
08-30 22:56:27.213  7793  7793 D UEI.SmartControl: Starting file observer...
08-30 22:56:27.213  7793  7793 D UEI.SmartControl: Extracting JNI libs...
08-30 22:56:27.213  7793  7793 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 22:56:27.248  7128  7692 E bt-btif : Calling BTA_HhEnable
08-30 22:56:27.248  7128  7692 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 22:56:27.249  7128  7692 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 22:56:27.249  7128  7743 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 22:56:27.249  7128  7743 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 22:56:27.249  7128  7743 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 22:56:27.250  7128  7743 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 22:56:27.250  7128  7743 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 22:56:27.250  7128  7692 D BluetoothAdapterProperties: Name is: G3
,08-30 22:56:27.253  7128  7692 D BluetoothAdapterProperties: Scan Mode:20
08-30 22:56:27.253  7128  7692 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 22:56:27.254  7128  7692 D bt_hci_bdroid: postload
08-30 22:56:27.254  7128  7745 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 22:56:27.254  7128  7745 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 22:56:27.256  7128  7743 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 22:56:27.256  7128  7692 D bte_conf: Device ID record 1 : primary
08-30 22:56:27.256  7128  7692 D bte_conf:   vendorId            = 00c4
08-30 22:56:27.256  7128  7692 D bte_conf:   vendorIdSource      = 0001
08-30 22:56:27.256  7128  7692 D bte_conf:   product             = 13a1
08-30 22:56:27.256  7128  7692 D bte_conf:   version             = 1000
08-30 22:56:27.256  7128  7692 D bte_conf:   clientExecutableURL = 
08-30 22:56:27.256  7128  7692 D bte_conf:   serviceDescription  = 
08-30 22:56:27.256  7128  7692 D bte_conf:   documentationURL    = 
,08-30 22:56:27.257  7128  7692 D bte_conf: bte_load_did_conf no section named DID2.
08-30 22:56:27.258  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 22:56:27.259  7128  7745 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 22:56:27.259  7128  7745 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 22:56:27.259  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 22:56:27.262  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:27.263  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:27.263  7813  7813 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 22:56:27.263  7813  7813 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:27.267  7128  7745 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 22:56:27.268  7128  7808 E bt_mct  : hci lib postload completed
,08-30 22:56:27.269  7128  7688 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 22:56:27.269  7128  7688 D BluetoothAdapterProperties: ScanMode =  20
08-30 22:56:27.270  7128  7688 D BluetoothAdapterProperties: State =  11
08-30 22:56:27.270  7128  7688 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 22:56:27.271  7128  7688 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 22:56:27.271  7128  7688 D BluetoothAdapterProperties: Setting state to 12
08-30 22:56:27.271  7128  7688 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 22:56:27.272  7128  7692 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 22:56:27.273  1037  1119 D BluetoothManagerService: Message: 60
08-30 22:56:27.273  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 22:56:27.273  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 22:56:27.273  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 22:56:27.273  7128  7692 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 22:56:27.275  7128  7688 I BluetoothAdapterState: Entering On State
08-30 22:56:27.278  7128  7743 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 22:56:27.278  7128  7743 W bt-smp  : Plain text(LSB ~ MSB) = 53 bd 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 22:56:27.278  7128  7743 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a 5e 22 1a 6a e2 9d 94 40 74 94 07 fa e9 f2 02 
08-30 22:56:27.278  7128  7743 W bt-btm  : Stopping oneshot timer
,08-30 22:56:27.286  7021  7037 D BluetoothPan: onBluetoothStateChange on: true
08-30 22:56:27.286  7021  7037 D BluetoothPan: onBluetoothStateChange call bindService
08-30 22:56:27.289  1037  1037 D BluetoothHeadset: Proxy object connected
08-30 22:56:27.290  7128  7688 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 22:56:27.290  7128  7688 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 22:56:27.290  7128  7688 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 22:56:27.290  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:27.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:27.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:27.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:27.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:27.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:27.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:27.290  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:27.291  7128  7688 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 22:56:27.293  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:27.295  7128  7692 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 22:56:27.295  7128  7692 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-30 22:56:27.297  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 22:56:27.299  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 22:56:27.300  7021  7036 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 22:56:27.301  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 22:56:27.303  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 22:56:27.303  7021  7037 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 22:56:27.307  7128  7743 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 22:56:27.307  7128  7743 W bt-smp  : Plain text(LSB ~ MSB) = cd b9 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 22:56:27.307  7128  7743 W bt-smp  : Encrypted text(LSB ~ MSB) = cc d9 a3 44 39 e8 2a d9 35 f1 8d f3 49 43 d6 6b 
08-30 22:56:27.307  7128  7743 W bt-btm  : Stopping oneshot timer
08-30 22:56:27.308  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 22:56:27.310  1864  1864 D BluetoothHeadset: Proxy object connected
,08-30 22:56:27.310  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 22:56:27.311  7021  7021 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 22:56:27.311  7021  7021 D PanProfile: Bluetooth service connected
08-30 22:56:27.312  7021  7036 D BluetoothMap: onBluetoothStateChange: up=true
08-30 22:56:27.313  1037  1037 D BluetoothA2dp: Proxy object connected
08-30 22:56:27.318  7021  7021 D BluetoothInputDevice: Proxy object connected
08-30 22:56:27.318  7021  7021 D HidProfile: Bluetooth service connected
08-30 22:56:27.318  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 22:56:27.318  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 22:56:27.319  1954  1954 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:27.320  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 22:56:27.320  1954  2187 D LGBluetoothAPIService: Message: 1
08-30 22:56:27.321  1954  2187 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 22:56:27.324  7128  7688 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 22:56:27.325  1954  2187 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 22:56:27.327  6865  6865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 22:56:27.328  7128  7743 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 22:56:27.328  7128  7743 W bt-smp  : Plain text(LSB ~ MSB) = 04 d3 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 22:56:27.328  7128  7743 W bt-smp  : Encrypted text(LSB ~ MSB) = fb cd b5 06 c8 d2 15 1a 7e 19 6c 0a 7c 65 aa ba 
08-30 22:56:27.328  7128  7743 W bt-btm  : Stopping oneshot timer
08-30 22:56:27.330  7821  7821 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 22:56:27.331  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 22:56:27.331  1037  1119 D BluetoothManagerService: Message: 40
08-30 22:56:27.331  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 22:56:27.332  7021  7021 D BluetoothMap: Proxy object connected
08-30 22:56:27.332  7021  7021 D MapProfile: Bluetooth service connected
08-30 22:56:27.332  7021  7021 D BluetoothMap: getConnectedDevices()
08-30 22:56:27.334  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:27.334  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:27.334  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:27.334  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:27.334  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:27.334  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:27.334  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:27.334  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:27.337  7128  7144 V BluetoothMapService: getConnectedDevices()
08-30 22:56:27.338  7128  7128 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:27.338  7128  7128 D BluetoothMapService: STATE_ON
08-30 22:56:27.340  7128  7128 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 22:56:27.340  7128  7128 D LGBluetoothAPIServer: [BTUI] onBind()
,08-30 22:56:27.342  7128  7128 V BluetoothMapService: Handler(): got msg=1
08-30 22:56:27.342  1954  1954 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 22:56:27.342  1954  2187 D LGBluetoothAPIService: Message: 100
08-30 22:56:27.342  1954  2187 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 22:56:27.343  7128  7743 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 22:56:27.343  7128  7743 W bt-smp  : Plain text(LSB ~ MSB) = 24 22 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 22:56:27.343  7128  7743 W bt-smp  : Encrypted text(LSB ~ MSB) = 4d 85 76 a1 f4 b3 2b e0 ff 70 57 d2 c0 c9 03 e0 
08-30 22:56:27.343  7128  7743 W bt-btm  : Stopping oneshot timer
08-30 22:56:27.344  7128  7128 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 22:56:27.345  7128  7822 D BluetoothMapMasInstance: MAS initSocket()
08-30 22:56:27.346  7128  7822 D BluetoothMapMasInstance:   masId = 00
08-30 22:56:27.346  7128  7822 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 22:56:27.346  7128  7822 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 22:56:27.346  7128  7822 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 22:56:27.346  7021  7021 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 22:56:27.349  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:27.351  1037  1119 D BluetoothManagerService: Message: 30
08-30 22:56:27.352  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:27.352  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:27.352  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:27.352  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:27.352  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:27.352  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:27.352  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:27.352  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:56:27.354  7128  7743 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 22:56:27.354  7128  7743 W bt-smp  : Plain text(LSB ~ MSB) = c2 b1 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 22:56:27.354  7128  7743 W bt-smp  : Encrypted text(LSB ~ MSB) = 35 d6 3c 52 ab 1d c7 4a fe 5d 6d 5a 2f 3a f6 ca 
08-30 22:56:27.354  7128  7743 W bt-btm  : Stopping oneshot timer
08-30 22:56:27.354  1037  1636 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:27.355  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:27.355  7021  7021 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 22:56:27.356  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:27.357  1037  1119 D BluetoothManagerService: Message: 30
08-30 22:56:27.358  7128  7822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 22:56:27.359  7128  7822 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 22:56:27.359  7128  7822 V BluetoothMapMasInstance: Succeed to create listening socket 
,08-30 22:56:27.359  7128  7822 D BluetoothMapMasInstance: Accepting socket connection...
08-30 22:56:27.360  7128  7692 D BluetoothAdapterProperties: Scan Mode:21
08-30 22:56:27.360  7128  7692 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 22:56:27.360  7793  7793 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 22:56:27.360  7793  7793 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 22:56:27.361  7793  7793 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-30 22:56:27.362  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
,08-30 22:56:27.362  7128  7128 V BluetoothPbapService: Pbap Service onCreate
08-30 22:56:27.362  7128  7128 V BluetoothPbapService: Starting PBAP service
08-30 22:56:27.365  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:27.366  7128  7128 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 22:56:27.366  7128  7128 V BluetoothPbapService: Pbap Service onBind
08-30 22:56:27.366  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:27.368  7128  7128 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:27.368  7128  7128 V BluetoothPbapService: state: 12
08-30 22:56:27.368  7128  7128 V BluetoothPbapService: Handler(): got msg=1
,08-30 22:56:27.370  7128  7128 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 22:56:27.371  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:27.372  7128  7823 V BluetoothPbapService: Pbap Service initSocket
08-30 22:56:27.372  7021  7021 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 22:56:27.372  1037  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:27.373  7128  7823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 22:56:27.374  7128  7823 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 22:56:27.374  7128  7823 V BluetoothPbapService: Succeed to create listening socket 
08-30 22:56:27.375  7128  7823 V BluetoothPbapService: Accepting socket connection...
08-30 22:56:27.375  7021  7021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 22:56:27.378  7021  7021 D BluetoothA2dp: Proxy object connected
08-30 22:56:27.379  7021  7021 D A2dpProfile: Bluetooth service connected
08-30 22:56:27.379  7128  7128 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 22:56:27.379  7128  7128 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:27.379  7128  7128 V BluetoothPbapReceiver: ***********state = 12
08-30 22:56:27.380  7021  7021 D BluetoothHeadset: Proxy object connected
08-30 22:56:27.381  7021  7021 D HeadsetProfile: Bluetooth service connected
08-30 22:56:27.381  2247  2247 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 22:56:27.382  2247  2247 D c       : Getting all permits...
08-30 22:56:27.382  2247  2247 D a       : Opening database...
08-30 22:56:27.382  7021  7021 D BluetoothPbap: Proxy object connected
08-30 22:56:27.383  7021  7021 D PbapServerProfile: Bluetooth service connected
08-30 22:56:27.385  7021  7021 D DockEventReceiver: finishStartingService: stopping service
08-30 22:56:27.385  2247  2247 D a       : Opening database auth.proximity.permit_store...
08-30 22:56:27.386  2247  2247 D a       : Closing database...
,08-30 22:56:27.395  7021  7021 D BluetoothPermissionRequest: onReceive
08-30 22:56:27.397  7021  7021 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 22:56:27.398  7021  7021 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 22:56:27.401  7128  7128 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-30 22:56:27.402  7128  7128 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 22:56:27.408  7128  7128 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 22:56:27.410  7793  7793 I UEI.SmartControl: --- Selecting new region: 6
08-30 22:56:27.412  7793  7793 I UEI.SmartControl: Model = LG-D855
,08-30 22:56:27.413  7793  7793 D UEI.SmartControl: QS Service created
,08-30 22:56:27.427  7128  7128 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 22:56:27.427  7128  7128 V BtOppService: onCreate
,08-30 22:56:27.428  7793  7793 I UEI.SmartControl: Service initServices...
08-30 22:56:27.430  7128  7128 V BluetoothOppNotification: send message
08-30 22:56:27.431  7793  7793 D UEI.SmartControl: QS start get config
08-30 22:56:27.433  7128  7128 V BtOppService: Starting RfcommListener
08-30 22:56:27.448  7128  7128 D BluetoothOppPreference: Dumping Names:  
08-30 22:56:27.448  7128  7128 D BluetoothOppPreference: {}
08-30 22:56:27.448  7128  7128 D BluetoothOppPreference: Dumping Channels:  
08-30 22:56:27.448  7128  7128 D BluetoothOppPreference: {}
08-30 22:56:27.449  7128  7128 V BtOppService: onStartCommand
,08-30 22:56:27.449  7128  7830 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-30 22:56:27.454  7128  7128 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:27.454  7128  7128 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 22:56:27.456  7128  7128 V BluetoothOppNotification: new notify threadi!
08-30 22:56:27.456  7128  7827 V BtOppService: Deleted complete outbound shares, number =  0
08-30 22:56:27.457  7128  7128 V BluetoothOppNotification: send delay message
08-30 22:56:27.458  7128  7827 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 22:56:27.458  7128  7128 V BtOppService: start RfcommListener
08-30 22:56:27.458  7128  7827 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 22:56:27.459  7128  7830 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 22:56:27.459  7128  7827 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@261ab4b6 on behalf of 
08-30 22:56:27.465  7128  7128 V BtOppService: RfcommListener started
08-30 22:56:27.466  7128  7832 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 22:56:27.467  1037  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 22:56:27.468  7128  7832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 22:56:27.468  7128  7830 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@173295b7 on behalf of 
08-30 22:56:27.469  7128  7832 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-30 22:56:27.469  7128  7832 V BtOppRfcommListener: Started RFCOMM listener....
08-30 22:56:27.469  7128  7832 I BtOppRfcommListener: Accept thread started.
08-30 22:56:27.469  7128  7832 V BtOppRfcommListener: Accepting connection...
08-30 22:56:27.469  7128  7831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 22:56:27.471  7128  7831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cb1b124 on behalf of 
08-30 22:56:27.471  7128  7831 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 22:56:27.472  7128  7831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 22:56:27.473  7128  7831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3179948d on behalf of 
08-30 22:56:27.473  7128  7830 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 22:56:27.473  7128  7830 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 22:56:27.473  7128  7831 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 22:56:27.478  7128  7831 V BluetoothOppNotification: outbound notification was removed.
08-30 22:56:27.478  7128  7831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 22:56:27.479  7128  7831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e156642 on behalf of 
08-30 22:56:27.480  7128  7830 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d50d653 on behalf of 
,08-30 22:56:27.480  7128  7831 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 22:56:27.480  7128  7830 V BluetoothOppNotification: update too frequent, put in queue
08-30 22:56:27.482  7128  7830 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 22:56:27.482  7128  7831 V BluetoothOppNotification: inbound notification was removed.
08-30 22:56:27.482  7128  7831 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 22:56:27.483  7128  7831 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33eabb90 on behalf of 
08-30 22:56:27.491  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:27.491  7128  7128 V BluetoothFtpService: Ftp Service onCreate
08-30 22:56:27.492  7128  7128 I BluetoothFtpService: Ftp Service onCreate
08-30 22:56:27.492  7128  7128 V BluetoothFtpService: Ftp Service onStartCommand
08-30 22:56:27.492  7128  7128 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:27.492  7128  7128 V BluetoothFtpService: Starting Listening on sockets
08-30 22:56:27.492  7128  7128 V BtOppService: ContentObserver received notification
08-30 22:56:27.492  7128  7128 V BtOppService: ContentObserver received notification
,08-30 22:56:27.493  7128  7128 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 22:56:27.493  7128  7128 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 22:56:27.493  7128  7128 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 22:56:27.493  7128  7128 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:27.493  7128  7128 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 22:56:27.493  7128  7128 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 22:56:27.493  7128  7833 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-30 22:56:27.493  7128  7833 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 22:56:27.495  7128  7128 V BluetoothFtpService: Handler(): got msg=1
08-30 22:56:27.495  7128  7833 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2517a48e on behalf of 
,08-30 22:56:27.496  7793  7793 D UEI.SmartControl: Loading JNI Libs...
08-30 22:56:27.496  7128  7833 V BluetoothOppNotification: update too frequent, put in queue
08-30 22:56:27.496  7128  7128 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 22:56:27.496  7128  7128 V BluetoothFtpService: Ftp Service initSocket
08-30 22:56:27.497  7128  7833 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 22:56:27.501  1037  2021 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:27.502  7128  7128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 22:56:27.503  7128  7128 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-30 22:56:27.503  7128  7128 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 22:56:27.504  7128  7834 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 22:56:27.521  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:27.521  7128  7128 V BluetoothSapService: Sap Service onCreate
08-30 22:56:27.524  7128  7128 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:27.524  7128  7128 V BluetoothSapService: state: 12
08-30 22:56:27.524  7128  7128 V BluetoothSapService: Starting SAP server process
08-30 22:56:27.523  7835  7835 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:27.523  7835  7835 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:27.527  7128  7128 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 22:56:27.529  7128  7836 V BluetoothSapService: Sap Service initRfcommSocket
,08-30 22:56:27.530  1037  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:27.531  7128  7836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 22:56:27.531  7128  7836 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 22:56:27.532  7128  7836 V BluetoothSapService: Succeed to create listening socket 
,08-30 22:56:27.532  7128  7836 V BluetoothSapService: Accepting socket connection...
08-30 22:56:27.537  7835  7835 V BT_SAP  : Event pipe created
08-30 22:56:27.537  7835  7835 V BT_SAP  : create_server_socket qcom.sap.server
08-30 22:56:27.537  7835  7835 V BT_SAP  : created socket fd 6
08-30 22:56:27.777  7793  7793 I UEI.SmartControl: Supports setup maps: true
08-30 22:56:27.780  7793  7793 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 22:56:27.781  7793  7793 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 22:56:27.781  7793  7793 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 22:56:27.781  7793  7793 I UEI.SmartControl: ### init IR Blaster...
,08-30 22:56:27.791  7793  7793 D serial_port: Configuring serial port
,08-30 22:56:27.797  7793  7793 E UEI.SmartControl: UEIBLaster setting for 616
08-30 22:56:27.797  7793  7793 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 22:56:27.799  7793  7793 I UEI.SmartControl: configuring settings for MAXQ616
08-30 22:56:27.799  7793  7793 I UEI.SmartControl: Get version...
08-30 22:56:27.817  7793  7840 D UEI.SmartControl: serial port data available: 21
,08-30 22:56:27.847  7793  7793 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 22:56:27.847  7793  7793 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 22:56:27.847  7793  7793 I UEI.SmartControl: QS saving settings...
08-30 22:56:27.850  7793  7793 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 22:56:27.867  7793  7840 D UEI.SmartControl: serial port data available: 4
,08-30 22:56:27.911  7793  7846 I UEI.SmartControl: Device manager: loading config....
,08-30 22:56:27.914  7793  7846 D UEI.SmartControl: ----------- loading internal config...
,08-30 22:56:27.922  7793  7793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 22:56:27.926  7793  7793 E UEI.SmartControl: Services init done
08-30 22:56:27.927  7793  7793 D UEI.SmartControl: QS Service init finished
08-30 22:56:27.929  7793  7793 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 22:56:27.929  7793  7793 D UEI.SmartControl: QS Service version code: 201091
,08-30 22:56:27.938  7793  7793 D UEI.SmartControl: Service requested: Control
08-30 22:56:27.942  7793  7846 E UEI.SmartControl: Loading SETTINGS...
08-30 22:56:27.944  7793  7793 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 22:56:27.950  1037  1952 I ActivityManager: Killing 7075:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 22:56:27.956  7793  7846 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 22:56:27.967  7793  7845 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 22:56:27.967  7793  7845 D UEI.SmartControl: -----service ready thread exits
08-30 22:56:27.985  1037  1367 W libprocessgroup: failed to open /acct/uid_10112/pid_7075/cgroup.procs: No such file or directory
,08-30 22:56:27.988  7793  7793 D UEI.SmartControl: Internal service binding...
,08-30 22:56:28.094  1590  1590 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 22:56:28.155  1037  1413 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 22:56:28.204  1037  1104 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7851 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 22:56:28.207  2079  2079 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 22:56:28.225  1037  1037 D administrator: Handling package changes for user 0
,08-30 22:56:28.257  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 22:56:28.265  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-30 22:56:28.295  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 22:56:28.314  7851  7851 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 22:56:28.387  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 22:56:28.388  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 22:56:28.398  7851  7851 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 22:56:28.398  7851  7851 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:28.459  7128  7128 V BluetoothOppNotification: new notify threadi!
08-30 22:56:28.459  7128  7128 V BluetoothOppNotification: send delay message
08-30 22:56:28.460  7128  7892 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 22:56:28.461  7128  7892 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26ed7b9a on behalf of 
08-30 22:56:28.461  7128  7892 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 22:56:28.462  7128  7892 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 22:56:28.463  7128  7892 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21e2bccb on behalf of 
08-30 22:56:28.463  7128  7892 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 22:56:28.463  1037  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:56:28.464  7128  7892 V BluetoothOppNotification: outbound notification was removed.
08-30 22:56:28.464  7128  7892 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 22:56:28.465  7128  7892 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13126ca8 on behalf of 
08-30 22:56:28.466  7128  7892 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 22:56:28.469  7128  7892 V BluetoothOppNotification: inbound notification was removed.
08-30 22:56:28.469  7128  7892 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 22:56:28.470  7128  7892 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2de3a3c1 on behalf of 
08-30 22:56:28.471  1037  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 22:56:28.479  2079  2079 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 22:56:28.482  2455  2455 V GmsNetworkLocationProvi: DISABLE
08-30 22:56:28.500  7851  7897 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-30 22:56:28.500  7851  7897 I Babel   : MmsConfig.loadMmsSettings
,08-30 22:56:28.506  7851  7897 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 22:56:28.506  7851  7897 I Babel   : MmsConfig.loadFromDatabase
08-30 22:56:28.513  1037  1102 D LocationProviderProxy: applying state to connected service
,08-30 22:56:28.516  2455  2455 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 22:56:28.534  7851  7897 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 22:56:28.535  7851  7897 I Babel   : MmsConfig.loadFromResources
08-30 22:56:28.537  7851  7897 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 22:56:28.538  7851  7897 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 22:56:28.548  7851  7851 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:56:28.550  7851  7895 W AudioCapabilities: Unsupported mime audio/evrc
08-30 22:56:28.551  7851  7895 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 22:56:28.553  7851  7895 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 22:56:28.563  7851  7895 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 22:56:28.570  1826  7898 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 22:56:28.570  1826  7898 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 22:56:28.571  7851  7895 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 22:56:28.572  7851  7895 W AudioCapabilities: Unsupported mime audio/evrc
08-30 22:56:28.575  7227  7227 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 22:56:28.578  7227  7227 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1a20d0ef
08-30 22:56:28.578  7227  7227 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 22:56:28.578  7227  7227 D AppUp4:CustFacade: isPhone : true
08-30 22:56:28.578  7227  7227 D AppUp4:CustModeStarterReceiver: begin check event
08-30 22:56:28.578  7227  7227 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 22:56:28.586  7851  7895 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 22:56:28.590  7851  7895 W VideoCapabilities: Unsupported mime video/divx
08-30 22:56:28.591  7851  7895 W VideoCapabilities: Unsupported mime video/divx311
08-30 22:56:28.593  7851  7895 W VideoCapabilities: Unsupported mime video/divx4
08-30 22:56:28.598  7851  7895 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-30 22:56:28.601  1826  5211 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-30 22:56:28.612  1037  1934 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7902 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-30 22:56:28.615  1037  2077 I ActivityManager: Killing 7041:com.lge.sync/1000 (adj 15): empty #17
08-30 22:56:28.621  7851  7895 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-30 22:56:28.628  7851  7895 W AudioCapabilities: Unsupported mime audio/eac3
08-30 22:56:28.629  7851  7895 W AudioCapabilities: Unsupported mime audio/ac3
,08-30 22:56:28.632  7851  7895 W AudioCapabilities: Unsupported mime audio/g726
08-30 22:56:28.633  7851  7895 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 22:56:28.634  7851  7895 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 22:56:28.635  7851  7895 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 22:56:28.637  7851  7895 W VideoCapabilities: Unsupported mime video/theora
08-30 22:56:28.638  7851  7895 W VideoCapabilities: Unsupported mime video/mjpg
08-30 22:56:28.790  1037  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_7041/cgroup.procs: No such file or directory
,08-30 22:56:28.834  7902  7902 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 22:56:28.835  7902  7902 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 22:56:28.836  7902  7902 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 22:56:28.840  7902  7902 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 22:56:28.841  7902  7902 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 22:56:28.927  7902  7902 I SystemConfig: BUILD Country: EU
08-30 22:56:28.927  7902  7902 I SystemConfig: BUILD Operator: OPEN
,08-30 22:56:28.971  1037  2021 I ActivityManager: Killing 7528:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-30 22:56:29.048  1037  2342 W libprocessgroup: failed to open /acct/uid_10005/pid_7528/cgroup.procs: No such file or directory
,08-30 22:56:29.065  7902  7923 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 22:56:29.066  7902  7923 I SystemConfig: existFile = false
08-30 22:56:29.066  7902  7923 I SystemConfig: canReadFile = false
08-30 22:56:29.066  7902  7923 I SystemConfig: systemFeature RCS result false
08-30 22:56:29.066  7902  7923 D SystemConfig: refreshRcsSupport() :false
,08-30 22:56:29.135  1037  2021 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7925 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 22:56:29.226  7925  7925 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:56:29.227  7925  7925 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 22:56:29.227  7925  7925 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 22:56:29.228  7925  7925 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 22:56:29.330  7925  7925 I AppConfig: Total System Memory = 2995761152
,08-30 22:56:29.341  7925  7925 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 22:56:29.423  1037  1934 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7947 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 22:56:29.425  1037  1934 I ActivityManager: Killing 7252:com.lge.email/u0a23 (adj 15): empty #17
,08-30 22:56:29.475  1037  1053 W libprocessgroup: failed to open /acct/uid_10023/pid_7252/cgroup.procs: No such file or directory
,08-30 22:56:29.672  7947  7947 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 22:56:29.748  7947  7947 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:56:29.748  7947  7947 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:29.819  7947  7947 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 22:56:29.843  7947  7947 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 22:56:29.845  7947  7947 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 22:56:29.863  7947  7947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 22:56:29.863  7947  7947 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 22:56:29.883  1037  2019 I ActivityManager: Killing 7145:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 22:56:29.913  1037  1636 W libprocessgroup: failed to open /acct/uid_10026/pid_7145/cgroup.procs: No such file or directory
,08-30 22:56:29.919  2833  2936 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-30 22:56:29.920  2833  2936 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a7ab492 on behalf of 7947
,08-30 22:56:29.923  5031  7984 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-30 22:56:29.974  1037  1052 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7986 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 22:56:29.997  7947  7947 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 22:56:30.037  7947  7947 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 22:56:30.084  7986  7986 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 22:56:30.114  7986  7986 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 22:56:30.114  7986  7986 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-30 22:56:30.114  7986  7986 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-30 22:56:30.117  7986  7986 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 22:56:30.117  7986  7986 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 22:56:30.117  7986  7986 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-30 22:56:30.138  1037  2342 I ActivityManager: Killing 6518:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 22:56:30.198  1037  1636 W libprocessgroup: failed to open /acct/uid_1000/pid_6518/cgroup.procs: No such file or directory
,08-30 22:56:30.458  1037  1765 V SIM_STK : Menu title from STK is T-Mobile
,08-30 22:56:30.488  5031  7984 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 565 ms] updated apps [took 565 ms] 
,08-30 22:56:31.118  1037  1636 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 22:56:31.118  1037  1636 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1a53c6d6 mBinding = false
,08-30 22:56:31.149  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 22:56:31.149  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 22:56:31.149  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-30 22:56:31.150  1037  1119 D BluetoothManagerService: Message: 2
08-30 22:56:31.150  1037  1119 D BluetoothManagerService: Sending off request.
08-30 22:56:31.151  7128  7820 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 22:56:31.152  7128  7688 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 22:56:31.152  7128  7688 D BluetoothAdapterProperties: Setting state to 13
08-30 22:56:31.152  7128  7688 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 22:56:31.153  7128  7688 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 22:56:31.153  7128  7688 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 22:56:31.155  7128  7692 D BluetoothAdapterProperties: Scan Mode:20
08-30 22:56:31.158  7128  7688 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-30 22:56:31.161  7128  7688 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 22:56:31.165  7128  7823 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:31.165  7128  7832 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:31.166  7128  7836 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:31.166  7128  7834 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:31.167  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 22:56:31.167  7128  7743 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 22:56:31.168  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 22:56:31.169  7128  7743 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 22:56:31.178  7128  7822 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 22:56:31.178  7128  7822 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:56:31.178  7128  7822 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 22:56:31.178  7128  7822 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 22:56:31.178  7128  7822 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 22:56:31.178  7128  7822 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 22:56:31.178  7128  7822 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 22:56:31.178  7128  7822 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-30 22:56:31.185  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:31.185  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:31.185  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:31.185  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:31.185  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:31.185  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:31.185  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:31.185  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:31.185  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:31.187  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:31.187  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:31.192  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:31.192  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:31.192  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:31.192  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:31.192  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:31.192  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:31.192  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:31.192  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:31.192  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:56:31.195  1037  1532 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-30 22:56:31.196  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:31.196  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:31.200  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:31.200  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:31.200  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:31.200  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:31.200  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:31.200  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:56:31.200  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:31.200  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:31.200  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:31.201  6865  6865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:56:31.201  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:31.205  1037  1119 D BluetoothManagerService: Message: 60
08-30 22:56:31.205  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 22:56:31.205  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-30 22:56:31.209  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 22:56:31.212  1954  1954 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:31.221  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:31.225  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:31.226  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:31.228  7128  7128 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:31.228  7128  7128 D BluetoothMapService: STATE_TURNING_OFF
08-30 22:56:31.228  7128  7128 V BluetoothMapService: Handler(): got msg=4
08-30 22:56:31.228  7128  7128 D BluetoothMapService: MAP Service closeService in
08-30 22:56:31.228  7128  7128 D BluetoothMapMasInstance: MAP Service shutdown
08-30 22:56:31.228  7128  7128 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 22:56:31.228  7128  7128 V BluetoothMapService: MAP Service closeService out
08-30 22:56:31.233  7128  7128 V BtOppService: Receiver DISABLED_ACTION 
08-30 22:56:31.233  7128  7128 I BtOppRfcommListener: stopping Accept Thread
08-30 22:56:31.234  7128  7128 V BtOppRfcommListener: close mBtServerSocket
,08-30 22:56:31.237  7128  7832 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 22:56:31.238  7128  7128 V BtOppRfcommListener: waiting for thread to terminate
08-30 22:56:31.238  7128  7128 V BtOppRfcommListener: done waiting for thread to terminate
08-30 22:56:31.242  7021  7021 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 22:56:31.251  7128  7128 V BtOppService: onDestroy
,08-30 22:56:31.255  7128  7128 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 22:56:31.387  1037  2072 I art     : Explicit concurrent mark sweep GC freed 29966(1483KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.545ms total 144.193ms
,08-30 22:56:31.389  7021  7021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 22:56:31.397  7128  7128 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 22:56:31.397  7128  7128 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:31.397  7128  7128 V BluetoothPbapReceiver: ***********state = 13
08-30 22:56:31.399  7128  7128 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 22:56:31.399  7021  7021 D DockEventReceiver: finishStartingService: stopping service
,08-30 22:56:31.404  7128  7128 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:31.404  7128  7128 V BluetoothPbapService: state: 13
08-30 22:56:31.405  7128  7128 V BluetoothPbapService: Pbap Service closeService in
08-30 22:56:31.405  2247  2247 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 22:56:31.420  7128  7128 V BluetoothPbapService: successfully stopped pbap service
08-30 22:56:31.420  7128  7128 V BluetoothPbapService: Pbap Service closeService out
,08-30 22:56:31.420  7128  7128 V BluetoothPbapService: Pbap Service onDestroy
08-30 22:56:31.421  7128  7128 V BluetoothPbapService: Pbap Service closeService in
08-30 22:56:31.421  7128  7128 V BluetoothPbapService: Pbap Service closeService out
08-30 22:56:31.421  7128  7128 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 22:56:31.423  7021  7021 D BluetoothPbap: Proxy object disconnected
08-30 22:56:31.423  7021  7021 D PbapServerProfile: Bluetooth service disconnected
08-30 22:56:31.431  7021  7021 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 22:56:31.436  7021  7021 D BluetoothPermissionRequest: onReceive
08-30 22:56:31.436  7021  7021 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 22:56:31.444  7021  7021 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 22:56:31.453  7128  7128 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 22:56:31.453  7128  7128 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 22:56:31.454  7128  7128 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 22:56:31.458  7128  7128 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:56:31.458  7128  7128 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 22:56:31.459  7128  7128 V BluetoothFtpService: Ftp Service onStartCommand
08-30 22:56:31.459  7128  7128 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:31.459  7128  7128 V BluetoothFtpService: Ftp Service closeService
08-30 22:56:31.459  7128  7128 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 22:56:31.462  7128  7128 V BluetoothFtpService: successfully stopped ftp service
08-30 22:56:31.462  7128  7128 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 22:56:31.462  7128  7128 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 22:56:31.462  7128  7128 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 22:56:31.462  7128  7128 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:31.463  7128  7128 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 22:56:31.463  7128  7128 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 22:56:31.463  7128  7128 V BluetoothFtpService: Ftp Service onDestroy
08-30 22:56:31.463  7128  7128 V BluetoothFtpService: Ftp Service closeService
08-30 22:56:31.466  7128  7128 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:31.466  7128  7128 V BluetoothSapService: state: 13
08-30 22:56:31.466  7128  7128 V BluetoothSapService: Stopping SAP server process
08-30 22:56:31.467  7128  7128 V BluetoothSapService: Sap Service closeSapService in
08-30 22:56:31.467  7128  7128 V BluetoothSapService: Close listen Socket : 
08-30 22:56:31.467  7128  7128 V BluetoothSapService: Close rfcomm Socket : 
08-30 22:56:31.468  7128  7128 V BluetoothSapService: Close sapd  Socket : 
08-30 22:56:31.468  7128  7128 V BluetoothSapService: Sap Service closeSapService out
08-30 22:56:31.468  7128  7128 V BluetoothSapService: Sap Service onDestroy
08-30 22:56:31.468  7128  7128 V BluetoothSapService: Sap Service closeSapService in
08-30 22:56:31.468  7128  7128 V BluetoothSapService: Close listen Socket : 
08-30 22:56:31.468  7128  7128 V BluetoothSapService: Close rfcomm Socket : 
08-30 22:56:31.468  7128  7128 V BluetoothSapService: Close sapd  Socket : 
08-30 22:56:31.469  7128  7128 V BluetoothSapService: Sap Service closeSapService out
,08-30 22:56:32.150  7128  7692 D bt_hci_bdroid: cleanup
,08-30 22:56:32.157  7128  7745 I bt_lpm  : LPM is already off!!!
,08-30 22:56:32.159  7128  7808 I bt_userial_mct: exiting userial_read_thread
08-30 22:56:32.159  7128  7808 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 22:56:32.160  7128  7743 W bt-btif : ag scb idx 1 not allocated
08-30 22:56:32.160  7128  7743 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
,08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 22:56:32.160  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 22:56:32.161  7128  7743 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:56:32.161  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 22:56:32.161  7128  7743 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:56:32.161  7128  7743 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-30 22:56:32.161  7128  7743 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:56:32.161  7128  7743 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 22:56:32.164  7128  7692 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 22:56:32.167  7128  7745 I bt_vendor: hw_epilog_process
,08-30 22:56:32.179  7128  7692 D bt_hci_bdroid: cleanup Finalizing cleanup
,08-30 22:56:32.179  7128  7692 D bt_userial_mct: userial_close
08-30 22:56:32.179  7128  7692 E bt_userial_mct: pthread_join() FAILED result:3
08-30 22:56:32.179  7128  7692 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 22:56:32.215  7128  7692 D bt_hci_bdroid: set_power 0
08-30 22:56:32.215  7128  7692 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 22:56:32.215  7128  7692 I bt_vendor: bluetooth satus is on
08-30 22:56:32.215  7128  7692 I bt_vendor: bt-vendor : resetting BT status
08-30 22:56:32.215  7128  7692 I bt_vendor: Starting hciattach daemon
08-30 22:56:32.215  7128  7692 I bt_vendor: try to set false
,08-30 22:56:32.222  7128  7692 I bt_vendor: Starting hciattach daemon
08-30 22:56:32.222  7128  7692 I bt_vendor: try to set false
08-30 22:56:32.222  7128  7692 I bt_vendor: cleanup
08-30 22:56:32.223  7128  7743 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 22:56:32.224  7128  7692 I GKI_LINUX: GKI_exit_task 0 done
08-30 22:56:32.224  7128  7692 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 22:56:32.226  7128  7688 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 22:56:32.232  7128  7128 D HeadsetService: Received stop request...Stopping profile...
,08-30 22:56:32.236  7128  7128 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 22:56:32.236  7128  7128 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 22:56:32.237  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:32.237  7128  7719 D HeadsetStateMachine: Exit Disconnected: -1
08-30 22:56:32.242  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 22:56:32.242  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 22:56:32.242  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 22:56:32.243  7128  7688 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 22:56:32.243  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-30 22:56:32.243  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 22:56:32.243  7128  7128 D A2dpService: Received stop request...Stopping profile...
08-30 22:56:32.244  7128  7735 D A2dpStateMachine: Exit Disconnected: -1
08-30 22:56:32.249  7128  7128 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-30 22:56:32.253  7128  7128 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 22:56:32.253  7128  7128 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 22:56:32.253  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:32.255  7128  7128 D HidService: Received stop request...Stopping profile...
08-30 22:56:32.255  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:32.258  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-30 22:56:32.258  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 22:56:32.260  7128  7128 D HealthService: Received stop request...Stopping profile...
,08-30 22:56:32.260  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:32.264  7128  7128 D PanService: Received stop request...Stopping profile...
08-30 22:56:32.264  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:32.265  7128  7128 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 22:56:32.266  7128  7128 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 22:56:32.266  7128  7128 D BtGatt.GattService: stop()
08-30 22:56:32.266  7128  7128 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 22:56:32.268  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:32.268  7128  7128 D HeadsetStateMachine: Unbinding service...
08-30 22:56:32.269  7128  7128 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 22:56:32.269  7128  7128 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 22:56:32.269  7128  7128 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 22:56:32.269  7128  7128 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 22:56:32.269  7128  7128 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 22:56:32.269  7128  7128 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 22:56:32.269  7128  7128 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 22:56:32.271  7128  7128 D BluetoothMapService: Received stop request...Stopping profile...
08-30 22:56:32.271  7128  7128 D BluetoothMapService: stop()
08-30 22:56:32.273  7128  7128 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 22:56:32.273  7128  7128 D BluetoothMapEmailAppObserver: removeReceiver()
,08-30 22:56:32.276  7128  7128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3f8e85
08-30 22:56:32.277  7128  7128 I BluetoothA2dpServiceJni: cleanupNative
08-30 22:56:32.278  7128  7736 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 22:56:32.278  7128  7128 I GKI_LINUX: GKI_exit_task 2 done
08-30 22:56:32.278  7128  7128 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 22:56:32.278  7128  7128 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 22:56:32.278  7128  7128 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 22:56:32.279  7128  7128 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 22:56:32.279  7128  7128 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 22:56:32.279  7128  7128 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 22:56:32.279  7128  7128 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 22:56:32.279  7128  7128 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 22:56:32.282  7128  7128 V BluetoothMapService: Handler(): got msg=4
08-30 22:56:32.282  7128  7128 D BluetoothMapService: MAP Service closeService in
08-30 22:56:32.282  7128  7128 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 22:56:32.282  7128  7128 V BluetoothMapService: MAP Service closeService out
08-30 22:56:32.284  7128  7688 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,08-30 22:56:32.286  7128  7688 D BluetoothAdapterProperties: Setting state to 10
08-30 22:56:32.286  7128  7688 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 22:56:32.288  7128  7128 D BluetoothMapService: cleanup()
08-30 22:56:32.288  7128  7128 D BluetoothMapService: MAP Service closeService in
08-30 22:56:32.288  7128  7128 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 22:56:32.288  7128  7128 V BluetoothMapService: MAP Service closeService out
08-30 22:56:32.288  1037  1119 D BluetoothManagerService: Message: 60
08-30 22:56:32.288  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 22:56:32.288  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 22:56:32.288  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 22:56:32.289  7128  7688 I BluetoothAdapterState: Entering OffState
08-30 22:56:32.289  7021  7036 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 22:56:32.290  7021  7036 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 22:56:32.291  7021  7036 D BluetoothPan: onBluetoothStateChange on: false
08-30 22:56:32.291  1864  2548 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 22:56:32.292  7021  7036 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 22:56:32.293  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 22:56:32.293  7021  7036 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 22:56:32.294  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 22:56:32.296  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 22:56:32.298  7021  7036 D BluetoothMap: onBluetoothStateChange: up=false
08-30 22:56:32.299  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 22:56:32.299  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 22:56:32.301  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 22:56:32.301  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 22:56:32.301  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1a53c6d6 mBinding = false
08-30 22:56:32.302  1037  1119 D BluetoothManagerService: Sending unbind request.
08-30 22:56:32.307  7128  7692 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 22:56:32.310  7128  7128 I GKI_LINUX: GKI_exit_task 1 done
08-30 22:56:32.310  7128  7128 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 22:56:32.310  7128  7128 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 22:56:32.310  7128  7128 I art     : --- WEIRD: removing null entry 248
08-30 22:56:32.311  7128  7128 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 22:56:32.311  7128  7128 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 22:56:32.312  7128  7128 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 22:56:32.313  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 22:56:32.315  7128  7128 I art     : System.exit called, status: 0
08-30 22:56:32.315  7128  7128 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 22:56:32.337  1954  1954 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-30 22:56:32.344  1954  2187 D LGBluetoothAPIService: Message: 101
08-30 22:56:32.344  1954  2187 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 22:56:32.345  1954  2187 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-30 22:56:32.346  1954  2187 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-30 22:56:32.334   316  1372 V AudioFlinger: 7128 died, releasing its sessions
08-30 22:56:32.347   316  1372 V AudioFlinger:  pid 1864 @ 0
08-30 22:56:32.347   316  1372 V AudioFlinger:  pid 3158 @ 1
08-30 22:56:32.347   316  1372 V AudioFlinger:  pid 3158 @ 2
08-30 22:56:32.348  7021  7021 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 22:56:32.404  1037  1934 I ActivityManager: Process com.android.bluetooth (pid 7128) has died
08-30 22:56:32.405  1037  1934 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-30 22:56:32.405  1037  1934 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 13999ms
,08-30 22:56:32.412  1954  1954 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:32.412  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 22:56:32.412  1954  2187 D LGBluetoothAPIService: Message: 2
08-30 22:56:32.412  1954  2187 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 22:56:32.414  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:32.418  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:32.422  7021  7021 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 22:56:32.422  7021  7021 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 22:56:32.422  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:32.425  1590  1590 D BluetoothAdapter: 615567124: getState() :  mService = null. Returning STATE_OFF
08-30 22:56:32.425  1590  1590 D BluetoothAdapter: 615567124: getState() :  mService = null. Returning STATE_OFF
,08-30 22:56:32.428  7021  7021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 22:56:32.487  1037  1367 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8076 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 22:56:32.491  7021  7021 D DockEventReceiver: finishStartingService: stopping service
,08-30 22:56:32.568  8076  8076 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 22:56:32.569  8076  8076 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 22:56:32.569  8076  8076 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 22:56:32.570  8076  8076 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 22:56:32.591  8076  8076 D BluetoothAdapterApp: Loading JNI Library
,08-30 22:56:32.628  8076  8076 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2ecdd2cd Instance Count = 1
,08-30 22:56:32.635  8076  8076 D BluetoothAdapterApp: onCreate
08-30 22:56:32.662  8076  8076 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 22:56:32.662  8076  8076 D ProfileConfigQcom: Adding HeadsetService
08-30 22:56:32.662  8076  8076 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 22:56:32.662  8076  8076 D ProfileConfigQcom: Adding A2dpService
08-30 22:56:32.663  8076  8076 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 22:56:32.663  8076  8076 D ProfileConfigQcom: Adding HidService
08-30 22:56:32.663  8076  8076 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-30 22:56:32.663  8076  8076 D ProfileConfigQcom: Adding HealthService
08-30 22:56:32.664  8076  8076 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 22:56:32.665  8076  8076 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 22:56:32.665  8076  8076 D ProfileConfigQcom: Adding PanService
08-30 22:56:32.665  8076  8076 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 22:56:32.666  8076  8076 D ProfileConfigQcom: Adding GattService
08-30 22:56:32.666  8076  8076 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 22:56:32.666  8076  8076 D ProfileConfigQcom: Adding BluetoothMapService
08-30 22:56:32.666  8076  8076 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 22:56:32.667  8076  8076 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 22:56:32.669  8076  8076 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:32.669  8076  8076 V BluetoothPbapReceiver: ***********state = 10
08-30 22:56:32.671  8076  8076 V LGMDMManagerInternal: Create singleton instance
08-30 22:56:32.770  2247  2247 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 22:56:32.771  7021  7021 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 22:56:32.772  8076  8076 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 22:56:32.773  8076  8076 D LGBluetoothAPIServer: [BTUI] onBind()
,08-30 22:56:32.778  1954  1954 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-30 22:56:32.779  1954  2187 D LGBluetoothAPIService: Message: 100
08-30 22:56:32.779  1954  2187 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-30 22:56:32.779  1037  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{20c2e52d type 2 when 237365 com.google.android.gms} when 237365
08-30 22:56:32.784   312  8099 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 22:56:32.785  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 22:56:32.790  7021  7021 D BluetoothPermissionRequest: onReceive
,08-30 22:56:32.801  7021  7021 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 22:56:32.801  7021  7021 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 22:56:32.804  7021  7021 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 22:56:32.812  8076  8076 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 22:56:32.818  8076  8076 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:56:32.823  8076  8076 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 22:56:32.824  8076  8076 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 22:56:32.824  8076  8076 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 22:56:32.825  8076  8076 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:32.825  8076  8076 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 22:56:32.835  7754  7754 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 22:56:32.911  7793  7847 D UEI.SmartControl: Internal timer expired: 1
,08-30 22:56:32.911  7793  7847 D UEI.SmartControl: unbind internal service
,08-30 22:56:32.928  7793  7793 D UEI.SmartControl: Service.onUnbind: IControl
08-30 22:56:32.935  7793  7793 D UEI.SmartControl: Service.onDestroy
08-30 22:56:32.935  7793  7793 D UEI.SmartControl: Lock is in USE false
08-30 22:56:32.935  7793  7793 D UEI.SmartControl: unbind internal service
08-30 22:56:32.936  7793  7793 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@31d38d0b
08-30 22:56:32.936  7793  7793 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 22:56:32.936  7793  7793 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 22:56:32.936  7793  7793 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 22:56:32.936  7793  7793 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 22:56:32.936  7793  7793 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 22:56:32.936  7793  7793 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 22:56:32.936  7793  7793 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 22:56:32.936  7793  7793 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 22:56:32.936  7793  7793 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:56:32.936  7793  7793 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 22:56:32.937  7793  7793 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 22:56:32.937  7793  7793 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:56:32.937  7793  7793 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:56:32.937  7793  7793 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 22:56:32.937  7793  7793 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 22:56:32.937  7793  7793 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@31d38d0b
,08-30 22:56:32.942  7793  7793 D serial_port: close(fd = 25)
08-30 22:56:32.947  7793  7793 I UEI.SmartControl: Serial port is closed.
08-30 22:56:32.947  7793  7793 I UEI.SmartControl: Serial port is closed.
08-30 22:56:32.947  7793  7793 D UEI.SmartControl: Blaster closed
08-30 22:56:32.947  7793  7793 D UEI.SmartControl: Shut down QS...
08-30 22:56:32.947  7793  7793 D UEI.SmartControl: Stopping QS lib
08-30 22:56:32.948  7793  7793 D UEI.SmartControl: QS lib stop result = true
08-30 22:56:32.948  7793  7793 D UEI.SmartControl: Stopped QS lib
08-30 22:56:32.948  7793  7793 D UEI.SmartControl: Stopped file observer...
08-30 22:56:32.948  7793  7793 D UEI.SmartControl: QS shutdown complete
08-30 22:56:36.250  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:36.250  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:56:36.263  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:36.264  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@256ef85c removed from the list
08-30 22:56:36.264  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:36.264  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:36.266  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:36.267  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:56:36.267  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11ff4c3a added. We now have 4 listener(s)
08-30 22:56:36.267  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:56:36.269  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:36.269  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11ff4c3a removed from the list
08-30 22:56:36.269  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:36.269  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:36.269  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:36.270  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:56:36.270  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21c950eb added. We now have 4 listener(s)
08-30 22:56:36.270  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:56:36.274  1037  2342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 22:56:36.275  1037  2342 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 22:56:36.275  1037  1119 D BluetoothManagerService: Message: 2
08-30 22:56:41.281  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:41.292  1037  2077 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:41.292  1037  2077 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-30 22:56:41.311  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 22:56:41.311  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 22:56:41.312  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-30 22:56:41.315  1037  1119 D BluetoothManagerService: Message: 1
08-30 22:56:41.315  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 22:56:41.344  1037  1119 D BluetoothManagerService: Message: 20
08-30 22:56:41.344  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cdcdaae:true
,08-30 22:56:41.347  8076  8076 D BluetoothAdapterState: make
08-30 22:56:41.352  8076  8076 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 22:56:41.353  8076  8076 I bluedroid-qcom: init
08-30 22:56:41.354  8076  8110 I BluetoothAdapterState: Entering OffState
08-30 22:56:41.354  8076  8076 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 22:56:41.354  8076  8076 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 22:56:41.355  8076  8076 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 22:56:41.355  8076  8076 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 22:56:41.355  8076  8076 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 22:56:41.356  8076  8076 I bluedroid-qcom: get_profile_interface socket
08-30 22:56:41.357  8076  8076 I bluedroid-qcom: get_profile_interface map_client
,08-30 22:56:41.362  8076  8114 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 22:56:41.364  8113  8113 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:41.364  8113  8113 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:41.373  8113  8113 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 22:56:41.373  8113  8113 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 22:56:41.373  8113  8113 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 22:56:41.380  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 22:56:41.380  1037  1119 D BluetoothManagerService: Message: 40
08-30 22:56:41.380  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 22:56:41.381  8076  8091 I bluedroid-qcom: config_hci_snoop_log
08-30 22:56:41.382  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 22:56:41.382  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 22:56:41.384  8113  8113 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 22:56:41.386  8076  8114 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 22:56:41.391  8113  8113 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 22:56:41.391  8113  8113 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 22:56:41.394  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 22:56:41.394  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 22:56:41.395  8076  8114 D BluetoothAdapterProperties: Name is: G3
08-30 22:56:41.399  8076  8110 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 22:56:41.399  8076  8110 D BluetoothAdapterProperties: Setting state to 11
08-30 22:56:41.399  8076  8110 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-30 22:56:41.402  8076  8110 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 22:56:41.404  1037  1119 D BluetoothManagerService: Message: 60
08-30 22:56:41.405  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 22:56:41.405  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 22:56:41.409  1954  1954 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:41.410  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 22:56:41.413  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:41.416  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:41.421  7021  7021 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 22:56:41.425  8076  8076 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 22:56:41.425  8076  8076 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:41.426  8076  8076 V BluetoothPbapReceiver: ***********state = 11
,08-30 22:56:41.431  2247  2247 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 22:56:41.453  7021  7021 D BluetoothPermissionRequest: onReceive
,08-30 22:56:41.455  8076  8110 D BluetoothBondStateMachine: make
08-30 22:56:41.458  8076  8110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.458  8076  8110 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 22:56:41.458  8076  8110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.458  8076  8110 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 22:56:41.459  8076  8110 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 22:56:41.459  8076  8129 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 22:56:41.460  7021  7021 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 22:56:41.462  8076  8110 E BluetoothAdapterService: File transfer profiles supported!!
08-30 22:56:41.469  8076  8110 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 22:56:41.470  8076  8076 D HeadsetService: Received start request. Starting profile...
08-30 22:56:41.471  8076  8076 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 22:56:41.471  8076  8076 D LGBluetoothHfpAdapter: Version 1.6
08-30 22:56:41.474  8076  8076 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 22:56:41.475  8076  8076 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 22:56:41.476  8076  8076 D HeadsetStateMachine: make
08-30 22:56:41.476  8076  8110 E BluetoothAdapterService: File transfer profiles supported!!
08-30 22:56:41.482  8076  8110 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 22:56:41.489  8076  8110 E BluetoothAdapterService: File transfer profiles supported!!
08-30 22:56:41.494  8076  8110 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 22:56:41.499  8076  8110 E BluetoothAdapterService: File transfer profiles supported!!
08-30 22:56:41.514  8076  8110 V LGMDMManager: Create singleton instance
,08-30 22:56:41.516  8076  8076 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 22:56:41.516  8076  8076 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 22:56:41.517  8076  8110 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 22:56:41.521  8076  8076 D HeadsetStateMachine: max_hf_connections = 1
08-30 22:56:41.521  8076  8076 I bluedroid-qcom: get_profile_interface handsfree
08-30 22:56:41.523  8076  8076 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 22:56:41.524   316  1373 V AudioPolicyService: registerClient() client 0xb0410100, uid 1002
08-30 22:56:41.524   316   316 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 22:56:41.524   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 22:56:41.524   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 22:56:41.524  8076  8076 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 22:56:41.525   316  4421 V AudioFlinger: registerClient() client 0xb14330a0, pid 8076
08-30 22:56:41.525   316  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:41.525   316  1366 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-30 22:56:41.526  1037  1934 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-30 22:56:41.526  1037  1934 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 22:56:41.526  1590  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:41.526  1864  4267 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:41.526  1590  1610 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 22:56:41.526  1864  4267 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 22:56:41.526   316  1368 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:41.526   316  1368 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:41.526  3158  3174 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:41.526  3158  3174 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 22:56:41.526  8076  8092 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 22:56:41.526  1037  1953 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:41.526  1037  1953 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:41.526  1864  2548 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:41.526  1864  2548 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:41.526  1590  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:41.526  1590  1607 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:41.526  3158  4377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:41.526  3158  4377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 22:56:41.526  8076  8092 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 22:56:41.526  8076  8092 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 22:56:41.526  8076  8092 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 22:56:41.527  8076  8076 V ToneGenerator: Create Track: 0xb4928a80
08-30 22:56:41.527  8076  8076 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 22:56:41.527  8076  8076 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 22:56:41.528   316  1373 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 22:56:41.528   316  1373 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 22:56:41.528   316  1373 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-30 22:56:41.528   316  1373 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 22:56:41.528   316   316 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 22:56:41.528   316  4421 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 22:56:41.528   316  4421 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 22:56:41.528   316  4421 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 22:56:41.528   316  4421 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 22:56:41.528  8076  8076 V AudioSystem: getLatency() output 2, latency 50
08-30 22:56:41.528  8076  8076 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 22:56:41.528  8076  8076 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 22:56:41.529   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 22:56:41.529   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 22:56:41.529   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 22:56:41.529   316  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 22:56:41.529   316  1372 V AudioFlinger: createTrack() lSessionId: 23
08-30 22:56:41.530  8076  8076 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 22:56:41.530   316  1373 V AudioFlinger: acquiring 23 from 8076, for 8076
08-30 22:56:41.530   316  1373 V AudioFlinger:  added new entry for 23
08-30 22:56:41.530  8076  8076 V ToneGenerator: ToneGenerator INIT OK, time: 246136
08-30 22:56:41.530  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.531  8076  8131 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 22:56:41.532  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.532  8076  8131 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 22:56:41.533  8076  8131 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 22:56:41.533  8076  8131 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 22:56:41.533   316   316 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 8076
08-30 22:56:41.534   316   316 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 22:56:41.534   316   316 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 22:56:41.534   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 22:56:41.534   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 22:56:41.534   316   316 V voice   : voice_set_parameters: exit with code(0)
08-30 22:56:41.534   316   316 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 22:56:41.534  8076  8076 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:41.536   316   316 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 22:56:41.536   316   316 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 22:56:41.536   316   316 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 22:56:41.537   316   316 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 22:56:41.537   316   316 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 22:56:41.537  8076  8076 D A2dpService: Received start request. Starting profile...
08-30 22:56:41.537  8076  8131 V ToneGenerator: ToneGenerator destructor
08-30 22:56:41.537  8076  8131 V ToneGenerator: stopTone
08-30 22:56:41.537  8076  8131 V ToneGenerator: Delete Track: 0xb4928a80
08-30 22:56:41.539  ,8076  8076 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 22:56:41.540  8076  8076 V Avrcp   : make
08-30 22:56:41.540  8076  8076 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 22:56:41.540  8076  8076 I bluedroid-qcom: get_profile_interface avrcp
08-30 22:56:41.542   316  4421 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 22:56:41.542   316  4421 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 22:56:41.542   316  1275 V AudioPolicyService: AudioCommandThread() waking up
08-30 22:56:41.542   316  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 22:56:41.542   316  1275 V AudioPolicyManager: releaseOutput() 2
08-30 22:56:41.542   316  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 22:56:41.542   316  4421 V AudioFlinger: PlaybackThread::Track destructor
08-30 22:56:41.542  8076  8131 V AudioTrack: ~AudioTrack, releasing session id from 8076 on behalf of 8076
08-30 22:56:41.542   316  4421 V AudioFlinger: removeClient_l() pid 8076, calling pid 316
08-30 22:56:41.542   316   316 V AudioFlinger: releasing 23 from 8076 for 8076
08-30 22:56:41.542   316   316 V AudioFlinger:  decremented refcount to 0
08-30 22:56:41.542   316   316 V AudioFlinger: purging stale effects
08-30 22:56:41.551  8076  8076 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 22:56:41.552  8076  8076 E AudioManager: No RCC entry present to update
08-30 22:56:41.552  8076  8076 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 22:56:41.556  8076  8076 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 22:56:41.557  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 22:56:41.557  8076  8076 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 22:56:41.561  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 22:56:41.668  1037  2342 V SIM_STK : Menu title from STK is T-Mobile
08-30 22:56:41.668  1037  2342 V SIM_STK : Menu title from STK is T-Mobile
,08-30 22:56:41.765  1037  2077 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 22:56:41.777  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 22:56:41.783  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-30 22:56:41.785  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-30 22:56:41.785  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 22:56:41.785  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 22:56:41.785  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 22:56:41.785  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 22:56:41.785  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 22:56:41.785  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 22:56:41.786  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 22:56:41.786  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 22:56:41.787  8076  8076 I BluetoothA2dpServiceJni: classInitNative
08-30 22:56:41.787  8076  8076 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 22:56:41.787  8076  8076 D A2dpStateMachine: make
08-30 22:56:41.789  8076  8076 I bluedroid-qcom: get_profile_interface a2dp
08-30 22:56:41.790  8076  8142 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 22:56:41.801  8076  8076 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 22:56:41.801  8076  8076 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 22:56:41.802  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.804  8076  8076 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 22:56:41.807  8076  8141 D A2dpStateMachine: Enter Disconnected: -2
08-30 22:56:41.808  8076  8076 D HidService: Received start request. Starting profile...
08-30 22:56:41.808  8076  8076 I bluedroid-qcom: get_profile_interface hidhost
08-30 22:56:41.808  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.809  8076  8076 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 22:56:41.811  8076  8076 D HealthService: Received start request. Starting profile...
08-30 22:56:41.815  8076  8076 I bluedroid-qcom: get_profile_interface health
08-30 22:56:41.815  8076  8076 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 22:56:41.815  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.816  8076  8076 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 22:56:41.818  8076  8076 D PanService: Received start request. Starting profile...
08-30 22:56:41.819  8076  8076 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 22:56:41.819  8076  8076 I bluedroid-qcom: get_profile_interface pan
,08-30 22:56:41.827  8076  8076 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 22:56:41.828  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.829  8076  8076 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 22:56:41.835  8076  8076 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 22:56:41.836  8076  8076 D BtGatt.GattService: Received start request. Starting profile...
08-30 22:56:41.836  8076  8076 D BtGatt.GattService: start()
08-30 22:56:41.836  8076  8076 I bluedroid-qcom: get_profile_interface gatt
08-30 22:56:41.836  8076  8076 D BtGatt.AdvertiseManager: advertise manager created
08-30 22:56:41.844  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.846  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.846  8076  8076 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 22:56:41.847  8076  8076 V BluetoothMapService: BluetoothMapBinder()
,08-30 22:56:41.848  8076  8076 D BluetoothMapService: Received start request. Starting profile...
08-30 22:56:41.848  8076  8076 D BluetoothMapService: start()
08-30 22:56:41.852  8076  8076 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 22:56:41.852  8076  8076 D BluetoothMapEmailAppObserver: createReceiver()
08-30 22:56:41.853  8076  8076 D BluetoothMapEmailAppObserver: initObservers()
,08-30 22:56:41.854  8076  8076 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 22:56:41.863  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:41.863  8076  8076 D HeadsetStateMachine: Proxy object connected
08-30 22:56:41.864  8076  8076 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 22:56:41.864  8076  8076 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-30 22:56:41.870  8076  8076 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 22:56:41.871  8076  8131 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 22:56:41.871  8076  8076 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 22:56:41.871  8076  8076 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 22:56:41.871  8076  8131 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 22:56:41.871  8076  8076 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 22:56:41.871  8076  8076 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:41.871  8076  8131 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 22:56:41.872  8076  8076 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 22:56:41.877  8076  8076 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 22:56:41.881  8076  8076 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 22:56:41.885  8076  8076 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 22:56:41.885  8076  8076 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 22:56:41.889  8076  8076 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 22:56:41.892  8076  8076 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-30 22:56:41.892  8076  8076 V BluetoothMapService: Handler(): got msg=1
08-30 22:56:41.893  8076  8110 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 22:56:41.893  8076  8110 I bluedroid-qcom: enable
08-30 22:56:41.894  8076  8110 I bt_hci_bdroid: init
08-30 22:56:41.894  8076  8152 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 22:56:41.894  8076  8152 I bt-btu  : btu_task pending for preload complete event
08-30 22:56:41.896  8076  8110 I bt_vendor: bt-vendor : init
08-30 22:56:41.896  8076  8110 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 22:56:41.896  8076  8110 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 22:56:41.896  8076  8110 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 22:56:41.896  8076  8110 D bt_userial_mct: userial_init
08-30 22:56:41.897  8076  8110 D bt_hci_bdroid: set_power 1
08-30 22:56:41.897  8076  8110 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 22:56:41.897  8076  8110 I bt_vendor: Starting hciattach daemon
08-30 22:56:41.897  8076  8110 I bt_vendor: try to set true
08-30 22:56:41.893  8155  8155 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:41.893  8155  8155 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:41.931  8161  8161 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 22:56:42.042  8167  8167 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 22:56:42.056  8168  8168 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 22:56:42.115  8170  8170 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 22:56:42.137  8171  8171 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 22:56:42.152  8172  8172 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 22:56:42.176  8173  8173 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 22:56:42.201  8176  8176 I libmdmdetect: ESOC framework not supported
08-30 22:56:42.203  8176  8176 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 22:56:42.218  8176  8176 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 22:56:42.218  8176  8176 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 22:56:42.218  8176  8176 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 22:56:42.218  8176  8176 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 22:56:42.218  8176  8176 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 22:56:42.218  8176  8176 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 22:56:42.218  8176  8176 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-30 22:56:42.275  8176  8180 E QC-QMI  : qmi_client [8176] 15: failed to locate client data
,08-30 22:56:42.283   461   461 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 22:56:42.283   461   461 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-30 22:56:42.326  8184  8184 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 22:56:42.341  8185  8185 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 22:56:42.399  8076  8110 I bt_vendor: bluetooth satus is on
08-30 22:56:42.399  8076  8110 D bt_hci_bdroid: preload
,08-30 22:56:42.403  8076  8154 D bt_userial_mct: userial_open(port:0)
08-30 22:56:42.403  8076  8154 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 22:56:42.409  8076  8154 I bt_vendor: Done intiailizing UART
08-30 22:56:42.412  8076  8154 I bt_vendor: Done intiailizing UART
08-30 22:56:42.412  8076  8154 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 22:56:42.412  8076  8154 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 22:56:42.415  8076  8152 I bt-btu  : btu_task received preload complete event
08-30 22:56:42.415  8076  8152 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-30 22:56:42.419  8076  8152 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 22:56:42.424  8076  8152 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 22:56:42.425  8076  8187 D bt_userial_mct: Entering userial_read_thread()
08-30 22:56:42.434  8076  8152 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 22:56:42.434  8076  8152 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 22:56:42.434  8076  8152 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 22:56:42.434  8076  8152 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 22:56:42.437  8076  8152 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 22:56:42.489  8076  8152 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 22:56:42.489  8076  8152 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d1061 
08-30 22:56:42.489  8076  8152 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d1061 
,08-30 22:56:42.520  8076  8114 E bt-btif : Calling BTA_HhEnable
08-30 22:56:42.520  8076  8114 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 22:56:42.521  8076  8114 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 22:56:42.526  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 22:56:42.527  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 22:56:42.527  8076  8114 D BluetoothAdapterProperties: Name is: G3
08-30 22:56:42.529  8076  8114 D BluetoothAdapterProperties: Scan Mode:20
08-30 22:56:42.529  8076  8114 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 22:56:42.529  8076  8114 D bt_hci_bdroid: postload
08-30 22:56:42.531  8076  8114 D bte_conf: Device ID record 1 : primary
08-30 22:56:42.531  8076  8114 D bte_conf:   vendorId            = 00c4
08-30 22:56:42.531  8076  8114 D bte_conf:   vendorIdSource      = 0001
08-30 22:56:42.531  8076  8114 D bte_conf:   product             = 13a1
08-30 22:56:42.531  8076  8114 D bte_conf:   version             = 1000
08-30 22:56:42.531  8076  8114 D bte_conf:   clientExecutableURL = 
08-30 22:56:42.531  8076  8114 D bte_conf:   serviceDescription  = 
08-30 22:56:42.531  8076  8114 D bte_conf:   documentationURL    = 
08-30 22:56:42.532  8076  8154 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 22:56:42.532  8076  8114 D bte_conf: bte_load_did_conf no section named DID2.
08-30 22:56:42.534  8076  8154 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 22:56:42.539  8076  8110 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 22:56:42.539  8076  8110 D BluetoothAdapterProperties: ScanMode =  20
08-30 22:56:42.539  8076  8110 D BluetoothAdapterProperties: State =  11
08-30 22:56:42.539  8076  8110 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 22:56:42.539  8076  8110 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 22:56:42.539  8076  8110 D BluetoothAdapterProperties: Setting state to 12
08-30 22:56:42.539  8076  8110 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 22:56:42.543  8076  8114 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 22:56:42.543  8189  8189 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:42.546  1037  1119 D BluetoothManagerService: Message: 60
08-30 22:56:42.546  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 22:56:42.546  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 22:56:42.546  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 22:56:42.547  8076  8187 E bt_mct  : hci lib postload completed
08-30 22:56:42.543  8189  8189 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:42.553  8076  8110 I BluetoothAdapterState: Entering On State
,08-30 22:56:42.571  8076  8114 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 22:56:42.572  8076  8114 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-30 22:56:42.584  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:42.584  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:42.584  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:42.584  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:42.584  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:42.584  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:42.584  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:42.584  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:56:42.593  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:42.596  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:42.596  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:42.596  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:42.596  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:42.596  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:42.596  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:42.596  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:42.596  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:56:42.603  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:42.614  8076  8110 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 22:56:42.614  8076  8110 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 22:56:42.614  8076  8110 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-30 22:56:42.617  8076  8110 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 22:56:42.617  8076  8110 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 22:56:42.618  1037  1037 D BluetoothHeadset: Proxy object connected
08-30 22:56:42.623  8076  8152 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 22:56:42.623  8076  8152 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 22:56:42.623  8076  8152 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 22:56:42.623  8076  8152 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 22:56:42.623  8076  8152 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 22:56:42.623  8076  8152 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 22:56:42.624  8076  8114 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 22:56:42.629  7021  7817 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 22:56:42.646  7021  7817 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 22:56:42.654  8076  8152 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 22:56:42.654  8076  8152 W bt-smp  : Plain text(LSB ~ MSB) = aa 41 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 22:56:42.654  8076  8152 W bt-smp  : Encrypted text(LSB ~ MSB) = 20 9c 03 1c 56 7d ba ed 0e 85 90 d2 44 de 2c 03 
08-30 22:56:42.654  8076  8152 W bt-btm  : Stopping oneshot timer
08-30 22:56:42.660  7021  7037 D BluetoothPan: onBluetoothStateChange on: true
08-30 22:56:42.660  7021  7037 D BluetoothPan: onBluetoothStateChange call bindService
,08-30 22:56:42.671  8195  8195 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 22:56:42.677  7021  7021 D BluetoothA2dp: Proxy object connected
08-30 22:56:42.678  7021  7021 D A2dpProfile: Bluetooth service connected
,08-30 22:56:42.687  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 22:56:42.688  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 22:56:42.688  7021  7021 D BluetoothHeadset: Proxy object connected
08-30 22:56:42.689  7021  7021 D HeadsetProfile: Bluetooth service connected
08-30 22:56:42.692  7021  7036 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 22:56:42.693  7021  7021 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 22:56:42.693  7021  7021 D PanProfile: Bluetooth service connected
08-30 22:56:42.696  1864  2548 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 22:56:42.698  8076  8152 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 22:56:42.698  8076  8152 W bt-smp  : Plain text(LSB ~ MSB) = 5f be 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 22:56:42.698  8076  8152 W bt-smp  : Encrypted text(LSB ~ MSB) = 15 5d 28 55 cd 16 47 0d bc 70 a6 3d 77 47 4c 85 
08-30 22:56:42.698  8076  8152 W bt-btm  : Stopping oneshot timer
08-30 22:56:42.700  7021  7037 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 22:56:42.700  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 22:56:42.705  7021  7021 D BluetoothInputDevice: Proxy object connected
08-30 22:56:42.705  7021  7021 D HidProfile: Bluetooth service connected
08-30 22:56:42.706  1864  4267 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 22:56:42.708  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 22:56:42.708  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 22:56:42.709  1037  1037 D BluetoothA2dp: Proxy object connected
,08-30 22:56:42.710  8076  8152 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-30 22:56:42.710  8076  8152 W bt-smp  : Plain text(LSB ~ MSB) = 51 b1 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 ,
08-30 22:56:42.710  8076  8152 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 e0 58 98 20 17 1a 01 1f f1 43 0d 90 43 58 8a 
08-30 22:56:42.710  8076  8152 W bt-btm  : Stopping oneshot timer
08-30 22:56:42.711  7021  7036 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 22:56:42.716  7021  7021 D BluetoothMap: Proxy object connected
08-30 22:56:42.716  7021  7021 D MapProfile: Bluetooth service connected
08-30 22:56:42.716  7021  7021 D BluetoothMap: getConnectedDevices()
,08-30 22:56:42.717  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 22:56:42.717  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 22:56:42.717  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-30 22:56:42.718  8076  8091 V BluetoothMapService: getConnectedDevices()
08-30 22:56:42.720  8076  8152 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 22:56:42.720  8076  8152 W bt-smp  : Plain text(LSB ~ MSB) = e0 38 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-30 22:56:42.720  8076  8152 W bt-smp  : Encrypted text(LSB ~ MSB) = 5e 7e e1 08 e6 8c 8c d3 a5 ec 0a 21 8b 67 bc 61 
08-30 22:56:42.720  8076  8152 W bt-btm  : Stopping oneshot timer
08-30 22:56:42.723  1954  1954 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:42.723  1954  2187 D LGBluetoothAPIService: Message: 1
,08-30 22:56:42.723  1954  2187 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 22:56:42.723  1590  1590 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 22:56:42.723  1954  2187 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
,08-30 22:56:42.724  1954  2187 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 22:56:42.726  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:42.736  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:42.736  1037  1119 D BluetoothManagerService: Message: 40
08-30 22:56:42.737  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-30 22:56:42.743  8076  8076 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:42.744  8076  8076 D BluetoothMapService: STATE_ON
08-30 22:56:42.744  8076  8152 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 22:56:42.744  8076  8152 W bt-smp  : Plain text(LSB ~ MSB) = 75 34 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 22:56:42.744  8076  8152 W bt-smp  : Encrypted text(LSB ~ MSB) = 72 21 74 e8 1c 2b 5a ed 24 d9 99 d3 6f 8f 06 1c 
08-30 22:56:42.744  8076  8152 W bt-btm  : Stopping oneshot timer
08-30 22:56:42.751  7021  7021 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-30 22:56:42.753  7021  7021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 22:56:42.759  7021  7021 D DockEventReceiver: finishStartingService: stopping service
08-30 22:56:42.767  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
,08-30 22:56:42.767  8076  8076 V BluetoothPbapService: Pbap Service onCreate
08-30 22:56:42.767  8076  8076 V BluetoothPbapService: Starting PBAP service
08-30 22:56:42.769  8076  8076 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 22:56:42.769  8076  8076 V BluetoothPbapService: Pbap Service onBind
08-30 22:56:42.770  7021  7021 D BluetoothPbap: Proxy object connected
08-30 22:56:42.770  8076  8076 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:42.770  7021  7021 D PbapServerProfile: Bluetooth service connected
08-30 22:56:42.770  8076  8076 V BluetoothPbapService: state: 12
08-30 22:56:42.771  8076  8076 V BluetoothMapService: Handler(): got msg=1
08-30 22:56:42.771  8076  8076 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 22:56:42.772  8076  8076 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 22:56:42.772  8076  8076 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:42.772  8076  8076 V BluetoothPbapReceiver: ***********state = 12
08-30 22:56:42.772  8076  8215 D BluetoothMapMasInstance: MAS initSocket()
08-30 22:56:42.773  8076  8215 D BluetoothMapMasInstance:   masId = 00
08-30 22:56:42.773  8076  8215 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 22:56:42.773  8076  8215 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 22:56:42.773  8076  8215 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 22:56:42.775  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:42.776  8076  8076 V BluetoothPbapService: Handler(): got msg=1
08-30 22:56:42.777  8076  8076 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 22:56:42.778  2247  2247 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 22:56:42.778  2247  2247 D c       : Getting all permits...
,08-30 22:56:42.778  2247  2247 D a       : Opening database...
08-30 22:56:42.778  8076  8215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 22:56:42.779  8076  8215 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=74 mFd=0
08-30 22:56:42.781  8076  8114 D BluetoothAdapterProperties: Scan Mode:21
08-30 22:56:42.781  8076  8114 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 22:56:42.781  8076  8215 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 22:56:42.781  8076  8215 D BluetoothMapMasInstance: Accepting socket connection...
08-30 22:56:42.781  2247  2247 D a       : Opening database auth.proximity.permit_store...
08-30 22:56:42.784  2247  2247 D a       : Closing database...
08-30 22:56:42.784  8076  8216 V BluetoothPbapService: Pbap Service initSocket
08-30 22:56:42.788  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:42.789  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:42.791  1037  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:42.792  8076  8216 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 22:56:42.793  8076  8216 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=74
08-30 22:56:42.793  8076  8216 V BluetoothPbapService: Succeed to create listening socket 
08-30 22:56:42.793  8076  8216 V BluetoothPbapService: Accepting socket connection...
08-30 22:56:42.800  7021  7021 D BluetoothPermissionRequest: onReceive
08-30 22:56:42.801  7021  7021 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 22:56:42.802  7021  7021 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 22:56:42.805  8076  8076 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-30 22:56:42.806  8076  8076 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 22:56:42.812  8076  8076 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 22:56:42.832  8076  8076 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 22:56:42.832  8076  8076 V BtOppService: onCreate
08-30 22:56:42.837  8076  8076 V BluetoothOppNotification: send message
08-30 22:56:42.840  8076  8076 V BtOppService: Starting RfcommListener
08-30 22:56:42.845  8076  8076 D BluetoothOppPreference: Dumping Names:  
08-30 22:56:42.845  8076  8076 D BluetoothOppPreference: {}
08-30 22:56:42.845  8076  8076 D BluetoothOppPreference: Dumping Channels:  
08-30 22:56:42.845  8076  8076 D BluetoothOppPreference: {}
,08-30 22:56:42.855  8076  8076 V BtOppService: onStartCommand
08-30 22:56:42.860  8076  8222 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-30 22:56:42.861  8076  8219 V BtOppService: Deleted complete outbound shares, number =  0
08-30 22:56:42.862  8076  8222 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 22:56:42.862  8076  8076 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:42.862  8076  8076 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 22:56:42.864  8076  8222 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@261ab4b6 on behalf of 
08-30 22:56:42.865  8076  8219 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 22:56:42.866  8076  8076 V BluetoothOppNotification: new notify threadi!
08-30 22:56:42.866  8076  8076 V BluetoothOppNotification: send delay message
08-30 22:56:42.867  8076  8219 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 22:56:42.867  8076  8076 V BtOppService: start RfcommListener
08-30 22:56:42.868  8076  8223 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 22:56:42.870  8076  8076 V BtOppService: RfcommListener started
08-30 22:56:42.870  8076  8076 V BtOppService: ContentObserver received notification
08-30 22:56:42.870  8076  8076 V BtOppService: ContentObserver received notification
08-30 22:56:42.871  8076  8224 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 22:56:42.871  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:42.872  8076  8224 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 22:56:42.874  8076  8224 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
,08-30 22:56:42.875  8076  8224 V BtOppRfcommListener: Started RFCOMM listener....
08-30 22:56:42.875  8076  8224 I BtOppRfcommListener: Accept thread started.
08-30 22:56:42.875  8076  8224 V BtOppRfcommListener: Accepting connection...
08-30 22:56:42.877  8076  8219 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@173295b7 on behalf of 
08-30 22:56:42.879  8076  8222 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 22:56:42.880  8076  8222 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 22:56:42.884  8076  8222 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cb1b124 on behalf of 
08-30 22:56:42.885  8076  8223 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3179948d on behalf of 
,08-30 22:56:42.886  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:42.886  8076  8076 V BluetoothFtpService: Ftp Service onCreate
08-30 22:56:42.887  8076  8076 I BluetoothFtpService: Ftp Service onCreate
08-30 22:56:42.887  8076  8076 V BluetoothFtpService: Ftp Service onStartCommand
08-30 22:56:42.887  8076  8076 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:42.887  8076  8076 V BluetoothFtpService: Starting Listening on sockets
08-30 22:56:42.887  8076  8076 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 22:56:42.887  8076  8076 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 22:56:42.887  8076  8076 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 22:56:42.888  8076  8076 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:56:42.888  8076  8076 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 22:56:42.888  8076  8076 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 22:56:42.888  8076  8222 V BluetoothOppNotification: update too frequent, put in queue
08-30 22:56:42.889  8076  8223 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 22:56:42.891  8076  8222 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 22:56:42.891  8076  8223 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 22:56:42.893  8076  8076 V BluetoothFtpService: Handler(): got msg=1
08-30 22:56:42.894  8076  8076 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 22:56:42.894  8076  8076 V BluetoothFtpService: Ftp Service initSocket
08-30 22:56:42.894  8076  8223 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d50d653 on behalf of 
08-30 22:56:42.896  1037  1367 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:42.897  8076  8076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 22:56:42.900  8076  8223 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 22:56:42.902  8076  8223 V BluetoothOppNotification: outbound notification was removed.
08-30 22:56:42.902  8076  8223 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 22:56:42.904  8076  8223 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33eabb90 on behalf of 
08-30 22:56:42.905  8076  8223 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 22:56:42.905  8076  8076 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-30 22:56:42.905  8076  8076 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 22:56:42.906  8076  8223 V BluetoothOppNotification: inbound notification was removed.
08-30 22:56:42.906  8076  8223 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 22:56:42.907  8076  8223 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@177ec89 on behalf of 
08-30 22:56:42.915  8076  8225 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-30 22:56:42.926  8076  8076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e5a64da
08-30 22:56:42.927  8076  8076 V BluetoothSapService: Sap Service onCreate
08-30 22:56:42.929  8076  8076 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:56:42.929  8076  8076 V BluetoothSapService: state: 12
08-30 22:56:42.929  8076  8076 V BluetoothSapService: Starting SAP server process
08-30 22:56:42.931  8076  8076 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 22:56:42.932  8076  8228 V BluetoothSapService: Sap Service initRfcommSocket
08-30 22:56:42.933  1037  1367 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:56:42.923  8227  8227 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:42.935  8076  8228 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 22:56:42.923  8227  8227 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:42.936  8076  8228 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-30 22:56:42.936  8076  8228 V BluetoothSapService: Succeed to create listening socket 
08-30 22:56:42.936  8076  8228 V BluetoothSapService: Accepting socket connection...
08-30 22:56:42.958  8227  8227 V BT_SAP  : Event pipe created
08-30 22:56:42.958  8227  8227 V BT_SAP  : create_server_socket qcom.sap.server
08-30 22:56:42.958  8227  8227 V BT_SAP  : created socket fd 6
,08-30 22:56:43.868  8076  8076 V BluetoothOppNotification: new notify threadi!
,08-30 22:56:43.869  8076  8076 V BluetoothOppNotification: send delay message
,08-30 22:56:43.888  8076  8238 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 22:56:43.893  8076  8238 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16e9c845 on behalf of 
08-30 22:56:43.895  8076  8238 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 22:56:43.896  8076  8238 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 22:56:43.897  8076  8238 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26ed7b9a on behalf of 
08-30 22:56:43.898  8076  8238 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 22:56:43.899  8076  8238 V BluetoothOppNotification: outbound notification was removed.
08-30 22:56:43.899  8076  8238 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 22:56:43.900  8076  8238 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21e2bccb on behalf of 
08-30 22:56:43.901  8076  8238 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 22:56:43.906  8076  8238 V BluetoothOppNotification: inbound notification was removed.
08-30 22:56:43.906  8076  8238 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 22:56:43.908  8076  8238 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13126ca8 on behalf of 
08-30 22:56:46.345  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:46.345  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:46.345  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:46.345  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:56:46.345  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:46.345  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:46.345  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:46.345  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:56:46.351  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:56:46.352  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:46.352  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21c950eb removed from the list
08-30 22:56:46.352  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:46.352  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:46.352  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:46.353  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:56:46.353  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a213e48 added. We now have 4 listener(s)
08-30 22:56:46.353  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:56:46.355  1037  1934 D WifiServiceImplEx: setWifiEnabled: false pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 22:56:46.356  1037  1934 D WifiService: setWifiEnabled: false pid=6865, uid=10118
08-30 22:56:46.356  1037  1934 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 22:56:51.365  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:56:51.379  1037  1053 D WifiServiceImplEx: setWifiEnabled: true pid=6865, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 22:56:51.380  1037  1053 D WifiService: setWifiEnabled: true pid=6865, uid=10118
08-30 22:56:51.380  1037  1053 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 22:56:51.400  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 22:56:51.400  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 22:56:51.400  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-30 22:56:51.401  1037  1526 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 22:56:51.401  1037  1526 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 22:56:51.404  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 22:56:51.404  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 22:56:51.404  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 22:56:51.404  1037  1526 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 22:56:51.405  1037  1526 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 22:56:51.405  1037  1526 E WifiHW  : unknown target_country: EU , set to default
08-30 22:56:51.405  1037  1526 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 22:56:51.405  1037  1526 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 22:56:51.405  1037  1526 I WifiUtil: gEnableBmps=1
08-30 22:56:51.973   312   895 D SoftapController: Softap fwReload - Ok
,08-30 22:56:51.985  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 22:56:51.998  1037  1526 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (590ms)
,08-30 22:56:52.024   312   895 D CommandListener: Setting iface cfg
08-30 22:56:52.024   312   895 D CommandListener: Trying to bring down wlan0
08-30 22:56:52.035   312   895 D CommandListener: Clearing all IP addresses on wlan0
,08-30 22:56:52.039  1037  1526 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 22:56:52.033  8249  8249 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:52.045  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 22:56:52.045  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
08-30 22:56:52.045  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 22:56:52.053  8249  8249 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 22:56:52.059  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 22:56:52.059  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 22:56:52.059  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 22:56:52.059  7021  7021 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 22:56:52.099  8249  8249 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 22:56:52.125  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:52.125  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 22:56:52.128  1037  1526 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 22:56:52.128  1037  1526 D WifiMonitor: connecting to supplicant
,08-30 22:56:52.135  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:52.135  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 22:56:52.136  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:56:52.139  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 22:56:52.141  7021  7021 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 22:56:52.141  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 22:56:52.141  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 22:56:52.141  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 22:56:52.141  7021  7021 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 22:56:52.141  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 22:56:52.141  7021  7021 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 22:56:52.159  8249  8249 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 22:56:52.159  8249  8249 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 22:56:52.164  1037  1119 D Tethering: InitialState.processMessage what=4
,08-30 22:56:52.186  1037  1367 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8267 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-30 22:56:52.189  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 22:56:52.241  8249  8249 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 22:56:52.294  1037  1765 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8289 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 22:56:52.300  8267  8287 W FormManager: Network not available. Please check & try again.
,08-30 22:56:52.310  8267  8288 V FormManager: Network unavailable.
,08-30 22:56:52.312  8267  8288 V FormManager: Network unavailable.
,08-30 22:56:52.317  8249  8249 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 22:56:52.323  8249  8249 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 22:56:52.323  1037  2019 I ActivityManager: Killing 7284:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 22:56:52.324  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 22:56:52.325  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 22:56:52.325  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 22:56:52.325  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 22:56:52.325  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 22:56:52.325  1037  8307 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 22:56:52.325  1037  8307 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 22:56:52.326  1037  1526 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-30 22:56:52.326  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:52.326  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:52.327  1037  1526 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:52.327  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:52.327  1037  1526 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 22:56:52.327  1037  1526 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 22:56:52.328  1037  1526 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 22:56:52.328  1037  1526 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 22:56:52.328  1037  1526 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 22:56:52.366  1037  1765 W libprocessgroup: failed to open /acct/uid_10046/pid_7284/cgroup.procs: No such file or directory
08-30 22:56:52.366  1037  1526 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 22:56:52.366  1037  1526 E WifiStateMachine: useWiFiOffloading() : false
08-30 22:56:52.366  1037  1526 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 22:56:52.370  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.370  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.370  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.371  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.371  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 22:56:52.371  1037  1526 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 22:56:52.372  1037  1526 D WifiNative-wlan0: SET update_config 1: returned true
08-30 22:56:52.372  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 22:56:52.372  1037  1526 D WifiConfigStore: Loading config and enabling all networks 
08-30 22:56:52.373  1037  1526 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 22:56:52.373  1954  1954 D WfdService: Waiting for WifiP2p enabling
08-30 22:56:52.373  1037  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 22:56:52.374  1037  1526 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 22:56:52.375  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:52.379  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:52.379  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:52.379  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:52.379  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:52.379  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:52.379  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:52.379  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:52.379  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:56:52.385  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:56:52.389  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:52.389  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:52.389  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:52.389  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:52.389  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:52.389  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:56:52.389  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:56:52.389  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:56:52.389  1037  1526 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 22:56:52.391  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:56:52.408  1037  1526 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-30 22:56:52.408  1037  1526 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 22:56:52.409  1037  1526 D WifiStateMachine: enableVerboseLogging : level 2
08-30 22:56:52.409  1037  1526 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 22:56:52.409  1037  1526 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 22:56:52.409  1037  1526 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 22:56:52.410  1037  1526 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 22:56:52.410  1037  1526 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 22:56:52.410  1037  1526 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 22:56:52.410  1037  1526 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 22:56:52.412  1037  1526 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 22:56:52.412  1037  1526 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 22:56:52.412  1037  1526 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 22:56:52.413  1037  1526 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 22:56:52.413  1037  1526 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 22:56:52.413  1037  1526 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 22:56:52.413  8289  8289 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:52.414  1037  1526 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 22:56:52.416  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 22:56:52.416  1037  1526 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 22:56:52.416  1037  1526 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-30 22:56:52.417  1954  1954 D WfdsService: Supplicant Connection state is changed : true
,08-30 22:56:52.417  1037  1526 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 22:56:52.417  1037  1526 D WifiNative-HAL: Setting external_sim to 1
08-30 22:56:52.417  1954  2334 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 22:56:52.417  1037  1526 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 22:56:52.417  1954  2334 D WfdsService: Set the WFDS Monitor: true
08-30 22:56:52.417  1954  2334 D WfdsMonitor: WfdsMonitorThread create
08-30 22:56:52.418  1037  1526 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 22:56:52.418  1954  2334 D WfdsMonitor: WFDS Monitor is created and started
08-30 22:56:52.418  1037  1526 I WifiNative-HAL: startHal
08-30 22:56:52.418  1954  2334 D WfdsService: WiFi: Supplicant connection re-established
08-30 22:56:52.418  1037  1526 D wifi    : setting scan oui 0x9c35cfe0
08-30 22:56:52.418  1037  1526 D WifiStateMachine: Setting OUI to DA-A1-19
,08-30 22:56:52.418  1037  1526 I WifiNative-HAL: startHal
08-30 22:56:52.418  1037  1526 D wifi    : setting scan oui 0x9c35cfe0
08-30 22:56:52.418  1037  1526 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 22:56:52.419  1037  1526 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 22:56:52.419  7851  7851 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.419  1954  8310 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 22:56:52.419  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 22:56:52.419  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 22:56:52.419  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,08-30 22:56:52.419  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 22:56:52.419  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 22:56:52.419  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 22:56:52.420  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 22:56:52.420  1954  8310 E CtrlSupplicant: Succeed to open control connection
08-30 22:56:52.420  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 22:56:52.420  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 22:56:52.420  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 22:56:52.420  1954  8310 E CtrlSupplicant: Succeed to open monitor connection
08-30 22:56:52.420  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 22:56:52.420  1954  8310 D WfdsMonitor: Supplicant connection established
08-30 22:56:52.420  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 22:56:52.420  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 22:56:52.420  1954  2334 D WfdsService: Connected to the supplicant for wfds
08-30 22:56:52.420  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 22:56:52.420  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 22:56:52.420  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 22:56:52.420  8249  8249 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 22:56:52.421  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 22:56:52.421  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 22:56:52.421  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 22:56:52.421  1037  1526 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 22:56:52.422  1037  1526 E WifiNative: : [257,014,593 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 22:56:52.422  1037  1526 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 22:56:52.422  1037  1526 D WifiNative-wlan0: RECONNECT: returned true
08-30 22:56:52.422  1037  1526 D WifiNative-wlan0: doString: [STATUS]
08-30 22:56:52.422  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 22:56:52.422  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 22:56:52.422  1037  1526 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 22:56:52.422  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 22:56:52.423  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
08-30 22:56:52.423  1037  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.423  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 22:56:52.423  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-30 22:56:52.423  1037  1545 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.423  1037  1546 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.423  1037  1545 I WifiNative-HAL: startHal
08-30 22:56:52.423  1037  1545 D wifi    : getting scan capabilities on interface[1] = 0x9c35cfe0
08-30 22:56:52.424  1037  1545 D wifi    : failed to get capabilities : -3
08-30 22:56:52.424  1037  1545 E WifiScanningService: could not get scan capabilities
08-30 22:56:52.424  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 22:56:52.425  1037  1526 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 22:56:52.4,25  1037  1526 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
,08-30 22:56:52.425  1037  1526 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 22:56:52.426  1037  1526 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 22:56:52.426   312   895 D CommandListener: Setting iface cfg
08-30 22:56:52.426   312   895 D CommandListener: Trying to bring up p2p0
08-30 22:56:52.426  1037  1526 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 22:56:52.426  1037  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 22:56:52.426  1037  1524 D LGWifiP2pService: P2pEnablingState
08-30 22:56:52.426  1037  1526 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 22:56:52.426  1037  1526 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 22:56:52.426  1037  1524 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.426  1037  1524 D LGWifiP2pService: P2p socket connection successful
08-30 22:56:52.426  1037  1524 D LGWifiP2pService: P2pEnabledState
08-30 22:56:52.426  8249  8249 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 22:56:52.427  1037  1524 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 22:56:52.427  1037  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 22:56:52.428  1954  1954 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 22:56:52.428  1954  1954 D WfdsService: WifiP2pState is changed : true
08-30 22:56:52.428  1954  1954 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 22:56:52.429  1954  1954 D WfdsService: isConnected: false
08-30 22:56:52.429  1954  2334 D WfdsService: Receive the WFDS_ENABLE Method
08-30 22:56:52.429  1954  2334 D WfdsService: Set the WFDS Monitor: true
08-30 22:56:52.429  1954  2334 D WfdsService: Connected to the supplicant for wfds
08-30 22:56:52.429  1954  2334 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 22:56:52.429  8249  8249 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 22:56:52.430  1954  2334 D WfdsService: selectPreferredScanChannel [36]
08-30 22:56:52.430  1954  2334 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 22:56:52.430  1037  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 22:56:52.430  1037  1526 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 22:56:52.430  1037  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 22:56:52.430  1037  1526 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 22:56:52.430  1037  1524 D WifiNative-p2p0: SET device_name G3: returned true
08-30 22:56:52.430  1037  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 22:56:52.430  1037  1524 D LGWifiP2pService: before postfix = G3
08-30 22:56:52.430  1037  1524 D WifiServerServiceExt: postfix byte check : 2
08-30 22:56:52.430  1037  1524 D LGWifiP2pService: after postfix = G3
08-30 22:56:52.430  1037  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 22:56:52.431  1037  1526 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 22:56:52.431  1037  1526 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 22:56:52.431  1037  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 22:56:52.431  1037  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 22:56:52.431  8249  8249 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 22:56:52.431  1037  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 22:56:52.431  1037  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 22:56:52.431  1037  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 22:56:52.431  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 22:56:52.431  1037  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 22:56:52.432  1037  1524 D WifiNat,ive-p2p0: P2P_SET conc_pref p2p: returned true
08-30 22:56:52.432  1037  1524 D WifiNative-HAL: p2pGetDeviceAddress
08-30 22:56:52.432  1037  1526 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 22:56:52.432  1037  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 22:56:52.432  1037  1526 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 22:56:52.432  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 22:56:52.432  1037  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 22:56:52.432  1037  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 22:56:52.432  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 22:56:52.433  8249  8249 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:52.433  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 22:56:52.433  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:52.433  1037  8307 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:52.433  1037  8307 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:52.433  1954  1954 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 22:56:52.433  8249  8249 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 22:56:52.433  1954  1954 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 22:56:52.433  8249  8249 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.433  1954  1954 D WfdsService: Update P2p Interface State: 3
08-30 22:56:52.433  1954  8310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:52.433  1037  8307 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:52.434  1037  8307 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.434  1037  8307 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.434  1037  8307 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.434  8249  8249 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.434  1954  8310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:52.434  1037  8307 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:52.434  1037  8307 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.434  1037  8307 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.434  1037  8307 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.435  1037  1526 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 22:56:52.435  1037  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 22:56:52.435  1037  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 22:56:52.435  1037  1526 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 22:56:52.435  1037  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,08-30 22:56:52.435  1037  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 22:56:52.435  1037  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 22:56:52.435  1037  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 22:56:52.435  1037  1526 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 22:56:52.436  1037  1526 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 22:56:52.436  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-30 22:56:52.443  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null,
08-30 22:56:52.444  1037  1985 I ActivityManager: Killing 7309:com.android.chrome/u0a57 (adj 15): empty #17
08-30 22:56:52.449  1037  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 22:56:52.449  1037  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-30 22:56:52.450  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 22:56:52.450  8249  8249 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-30 22:56:52.451  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 22:56:52.451  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 22:56:52.451  1037  8307 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 22:56:52.451  1037  8307 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 22:56:52.451  1037  1526 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 22:56:52.451  1037  1526 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 22:56:52.452  1037  1526 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 22:56:52.452  1037  1526 D WifiNative-wlan0: doBoolean: SCAN
08-30 22:56:52.453  1037  1526 D WifiNative-wlan0: SCAN: returned false
08-30 22:56:52.453  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=257046  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 22:56:52.460  1037  2098 W libprocessgroup: failed to open /acct/uid_10057/pid_7309/cgroup.procs: No such file or directory
08-30 22:56:52.462  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=257056  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 22:56:52.463  1037  1526 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:52.463  1037  1526 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:52.464  1037  1526 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:52.464  1037  1524 D LGWifiP2pService: InactiveState
08-30 22:56:52.465  1037  1524 D LGWifiP2pService: InactiveState{ when=-30ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:56:52.465  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-30ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.465  1037  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 22:56:52.465  1037  1526 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:52.465  1037  1526 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 22:56:52.465  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 22:56:52.466  8249  8249 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:52.466  1954  8310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 22:56:52.466  1037  8307 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 22:56:52.466  1037  8307 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:52.466  1037  8307 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:52.466  1037  8307 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 22:56:52.467  8249  8249 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 22:56:52.467  8249  8249 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.467  1954  8310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:52.467  1037  8307 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:52.467  1037  8307 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.467  1037  8307 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.467  1037  8307 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.468  8249  8249 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.468  1954  8310 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:52.468  1037  8307 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 22:56:52.468  1037  8307 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.468  1037  8307 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.468  1037  8307 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 22:56:52.468  1037  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: InactiveState{ when=-33ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-33ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$Sm,Handler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.469  1037  1524 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.470  1954  2334 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 22:56:52.470  1037  1524 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.470  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.470  1037  1524 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:52.471  1037  1037 E WifiServerServiceExt: No p2p device connected
08-30 22:56:52.471  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:52.471  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:52.472  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.472  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.472  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:52.472  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 22:56:52.472  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:52.472  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 22:56:52.474  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 22:56:52.474  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 22:56:52.475  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 22:56:52.475  7021  7021 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 22:56:52.476  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 22:56:52.485  7021  7021 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 22:56:52.485  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 22:56:52.485  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 22:56:52.485  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 22:56:52.485  7021  7021 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 22:56:52.485  7021  7021 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 22:56:52.492  8289  8289 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 22:56:52.497  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 22:56:52.500  8267  8312 W FormManager: Network not available. Please check & try again.
08-30 22:56:52.501  8267  8313 V FormManager: Network unavailable.
08-30 22:56:52.503  8267  8313 V FormManager: Network unavailable.
,08-30 22:56:52.505  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:52.515  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 22:56:52.515  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 22:56:52.517  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:52.519  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:52.525  4747  8314 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 22:56:52.526  4747  8315 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 22:56:52.526  4747  8315 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 22:56:52.580  1037  2072 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8316 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 22:56:52.708  8316  8316 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 22:56:52.708  8316  8316 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 22:56:52.718  8316  8316 V [BNRBootReceiver]: Boot Receiver Return
,08-30 22:56:52.719  8316  8316 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 22:56:52.797  1037  1953 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8334 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 22:56:52.799  1037  1953 I ActivityManager: Killing 7331:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-30 22:56:52.821   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 21.586ms
,08-30 22:56:52.840   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 17.551ms
,08-30 22:56:52.854   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 14.562ms
,08-30 22:56:52.875  1037  1952 W libprocessgroup: failed to open /acct/uid_10062/pid_7331/cgroup.procs: No such file or directory
,08-30 22:56:52.894  8334  8334 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 22:56:52.910  8334  8334 D PluginManager: init()
,08-30 22:56:52.941  8249  8249 E wpa_supplicant: USIM:  scard_init function
08-30 22:56:52.942  8249  8249 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-30 22:56:52.945  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 22:56:52.945  1037  8307 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 22:56:52.946  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 22:56:52.946  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-30 22:56:52.947  1037  8307 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 22:56:52.947  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 22:56:52.947  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 22:56:52.948  1037  1526 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 22:56:52.949  1037  1526 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 22:56:52.950  1037  1526 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 22:56:52.951  1037  1526 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 22:56:52.951  1037  1526 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-30 22:56:52.962  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=257555  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 22:56:52.963  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=257556  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 22:56:52.965  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:52.965  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:52.967  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:52.973  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.973  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.973  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 22:56:52.974  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.974  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:52.975  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 22:56:52.975  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:52.976  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 22:56:52.990  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:52.990  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:52.991  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:53.093  8249  8249 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 22:56:53.094  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,08-30 22:56:53.101  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 22:56:53.101  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 22:56:53.102  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 22:56:53.102  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:53.102  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 22:56:53.104  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=257697  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 22:56:53.106  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=257699  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 22:56:53.107  1037  1526 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=257700
,08-30 22:56:53.107  1037  1526 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=257700
08-30 22:56:53.107  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 22:56:53.108  1037  1526 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=257701
08-30 22:56:53.109  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=257702
08-30 22:56:53.110  1037  1526 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=257703
08-30 22:56:53.110  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=257703  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 22:56:53.112  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.112  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.112  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 22:56:53.113  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:53.113  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:53.113  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:53.116  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.116  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.116  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 22:56:53.117  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=257710  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 22:56:53.118  1037  1526 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:53.118  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:53.118  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 22:56:53.118  1037  1526 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:53.118  1037  1526 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:53.119  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:53.119  1037  1526 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 22:56:53.120  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:53.120  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 22:56:53.133  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:53.133  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 22:56:53.136  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.137  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:53.138  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 22:56:53.138  8249  8249 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 22:56:53.138  8249  8249 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 22:56:53.139  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 22:56:53.139  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 22:56:53.139  1037  8307 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 22:56:53.139  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 22:56:53.139  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 22:56:53.139  1037  1526 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=257732  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 22:56:53.139  1037  8307 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 22:56:53.140  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=257733  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 22:56:53.140  1037  1526 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=257733
08-30 22:56:53.140  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:53.140  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 22:56:53.141  1037  1526 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=257734
08-30 22:56:53.141  1037  1526 D WifiNative-wlan0: doString: [STATUS]
08-30 22:56:53.141  1037  8307 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 22:56:53.142  1037  1526 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 22:56:53.142  1037  8307 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 22:56:53.143  1037  1526 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 22:56:53.150  1037  1526 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 22:56:53.150  1037  1526 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 22:56:53.155  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.155  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.155  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 22:56:53.156  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:53.156  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:53.158  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.158  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.158  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 22:56:53.159  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.160  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:53.160  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:53.161  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.162  1037  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{ba1db85 type 2 when 253869 com.google.android.gms} when 253869
08-30 22:56:53.164  1037  1526 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 22:56:53.164  1037  1532 D ConnectivityService: Got NetworkAgent Messenger
08-30 22:56:53.164  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 22:56:53.164  1037  1532 D ConnectivityService: NetworkAgent connected
,08-30 22:56:53.165  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 22:56:53.165  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-30 22:56:53.166  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 22:56:53.166  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 22:56:53.170  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 22:56:53.170  1037  1526 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 22:56:53.171  1037  1526 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 22:56:53.171  1037  1526 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 22:56:53.171  1037  1526 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 22:56:53.183  1037  1526 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 22:56:53.186   312   895 D CommandListener: Setting iface cfg
08-30 22:56:53.188  1037  1526 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 22:56:53.188  1037  8355 D DhcpStateMachine: StoppedState
08-30 22:56:53.188  1037  8355 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:53.188  1037  8355 D DhcpStateMachine: WaitBeforeStartState
08-30 22:56:53.189  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:53.189  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 22:56:53.190  1037  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=257783  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:53.190  1037  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=257783  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:53.190  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=257783  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:53.191  1037  1526 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=257784  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:53.191  1037  1526 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=257784  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:53.191  1037  1526 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=257784  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 22:56:53.192  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29299] from screen [on:0 period:-583169336] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:56:53.193  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-583169335] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:56:53.193  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 22:56:53.197  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:53.198  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.198  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.198  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.199  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.199  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.199  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.199  1037  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-30 22:56:53.200  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 22:56:53.200  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=158,0,0
08-30 22:56:53.200  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=158,0,0
08-30 22:56:53.200  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 22:56:53.200  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 22:56:53.201  1037  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 22:56:53.201  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 22:56:53.202  1037  1526 D WifiNative-wlan0: SET ps 0: returned true
,08-30 22:56:53.202  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 22:56:53.202  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 22:56:53.202  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 22:56:53.202  1037  1526 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 22:56:53.202  1037  1526 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 22:56:53.202  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d0341c4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:53.202  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d0341c4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:53.202  1037  1526 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 22:56:53.203  1037  8355 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:53.203  1037  8355 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 22:56:53.203   312   895 D CommandListener: Setting iface cfg
08-30 22:56:53.203   312   895 D CommandListener: Trying to bring up wlan0
08-30 22:56:53.204  1037  1526 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 22:56:53.205  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:53.205  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 22:56:53.206  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 22:56:53.206  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 22:56:53.206  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.207  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.207  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.207  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.207  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.208  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 22:56:53.208  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 22:56:53.208  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 22:56:53.208  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 22:56:53.208  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 22:56:53.209  1037  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:53.209  1037  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:53.209  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 22:56:53.209  1037  1526 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 22:56:53.209  1037  1526 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 22:56:53.209  8249  8249 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 22:56:53.209  1037  1526 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 22:56:53.209  1037  1526 D WifiNative-wlan0: doBoolean: SET ps 1
,08-30 22:56:53.230  1037  1526 D WifiNative-wlan0: SET ps 1: returned true
08-30 22:56:53.231  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-30 22:56:53.231  1037  1526 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 22:56:53.231  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 22:56:53.231  1037  1526 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 22:56:53.232  1037  1532 D ConnectivityService: ignoring duplicate network state non-change
08-30 22:56:53.235  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:53.235  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:53.236  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.238  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:56:53.238  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.238  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 22:56:53.241  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.241  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.241  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 22:56:53.241  1037  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 22:56:53.242  1037  1532 D ConnectivityService: Adding iface wlan0 to network 102
08-30 22:56:53.245  1037  1526 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 22:56:53.248  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 22:56:53.251  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.251  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.251  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 22:56:53.253  1954  1954 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 22:56:53.255  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 22:56:53.258  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:53.258  1590  1590 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 22:56:53.259  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:53.261  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:53.262  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-30 22:56:53.262  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.263  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.263  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 22:56:53.263  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 22:56:53.267  1590  1590 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:56:53.267  1590  1590 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-30 22:56:53.267  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.275  1037  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 22:56:53.275  1037  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 22:56:53.276  1037  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 22:56:53.276   312   895 E Netd    : netlink response contains error (File exists)
08-30 22:56:53.277  1037  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 22:56:53.277  1037  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 22:56:53.277  1037  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 22:56:53.277  1037  1532 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 22:56:53.282  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 22:56:53.282  1037  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 22:56:53.282  1037  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 22:56:53.282  1037  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 22:56:53.283  1037  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:53.283  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:53.283  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 22:56:53.283  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:53.283  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 22:56:53.283  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:56:53.283  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:53.283  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 22:56:53.283  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 22:56:53.283  1037  1532 D ConnectivityService: currentScore = 0, newScore = 20
08-30 22:56:53.283  1037  1532 D ConnectivityService:    accepting network in place of null
08-30 22:56:53.283  1037  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:53.284  1037  1526 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:53.284  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:53.284  1037  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 22:56:53.284  1037  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 22:56:53.284  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 22:56:53.284  1864  1864 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:53.284  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 22:56:53.286  1037  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:53.286  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 22:56:53.286  1037  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 22:56:53.286  1037  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 22:56:53.287  1037  1532 D ConnectivityService: validation of new default Network = false
08-30 22:56:53.287  1037  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 22:56:53.287  1037  1532 D D,SQN    : enableDataServiceNotify 
08-30 22:56:53.287  1037  1532 D DSQN    : start dsqn bin
08-30 22:56:53.289  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 22:56:53.289  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 22:56:53.289  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 22:56:53.293  1037  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 22:56:53.293  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:53.293  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:53.293  1037  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:53.293  1037  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 22:56:53.283  8360  8360 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:53.294   312  8359 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 22:56:53.294   312  8359 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 22:56:53.283  8360  8360 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:53.300  1590  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 22:56:53.308  8360  8360 E DSQN    : DSQN ssw
,08-30 22:56:53.317  8334  8334 W ExternalStrings: load override strings
08-30 22:56:53.317  8334  8334 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
,08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 22:56:53.317  8334  8334 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 22:56:53.320  8334  8334 D StatusProvider: onCreate
,08-30 22:56:53.323  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 22:56:53.324  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.325  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.350   312  8359 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 22:56:53.368  8334  8334 V Signer  : override build config not found
08-30 22:56:53.369  8334  8334 D Signer  : value of property debug is false
,08-30 22:56:53.383   312   894 D LGDataListener: argv[0]=dsqncommand
,08-30 22:56:53.383   312   894 D LGDataListener: argv[1]=wlan0
,08-30 22:56:53.383   312   894 D LGDataListener: argv[2]=1
08-30 22:56:53.383   312   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 22:56:53.384  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
,08-30 22:56:53.385  1037  1117 D DSQN    : start to monitor internet connection
08-30 22:56:53.398  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-30 22:56:53.398  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-30 22:56:53.398  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 22:56:53.399  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 22:56:53.399  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 22:56:53.399  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 22:56:53.399  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 22:56:53.399  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 22:56:53.399  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 22:56:53.400  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 22:56:53.400  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 22:56:53.400  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 22:56:53.400  8334  8334 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-30 22:56:53.407  1037  8355 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 22:56:53.408  1037  8355 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 22:56:53.408  1037  8355 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 22:56:53.409  8334  8334 V LGMDMManager: Create singleton instance
08-30 22:56:53.413  8371  8371 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 22:56:53.413  8371  8371 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 22:56:53.435  8371  8371 I dhcpcd  : version 5.5.6 starting
08-30 22:56:53.437  8371  8371 E dhcpcd  : get_duid: m
,08-30 22:56:53.437  8371  8371 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 22:56:53.438  8371  8371 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 22:56:53.449  8334  8334 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-30 22:56:53.480  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 20:56:53 GMT], X-Android-Received-Millis=[1472590613480], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472590613382]}
08-30 22:56:53.480  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-30 22:56:53.480  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 22:56:53.480  1037  1532 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 22:56:53.481  1037  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 22:56:53.481  1037  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:53.481  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:53.481  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 22:56:53.481  1037  1532 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 22:56:53.481  1037  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 22:56:53.481  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:53.481  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:53.482  1037  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:53.482  1037  1532 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:53.483  1864  1864 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:53.483  1590  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 22:56:53.483  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 22:56:53.484  1037  1526 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:53.484  1037  1526 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:53.484  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 22:56:53.504  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:53.510  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 22:56:53.514  8371  8371 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 22:56:53.514  8371  8371 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 22:56:53.514  8371  8371 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-30 22:56:53.514  8371  8371 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 22:56:53.514  8371  8371 D dhcpcd  : wlan0: sending REQUEST (xid 0x8526acbe), next in 3.43 seconds
08-30 22:56:53.523  1590  1590 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 22:56:53.524  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.525  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 22:56:53.526  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:53.530  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:53.555  8371  8371 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 22:56:53.578  1037  2342 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8384 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-30 22:56:53.578  1037  2342 I ActivityManager: Killing 7348:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 22:56:53.618  8371  8371 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 22:56:53.618  8371  8371 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-30 22:56:53.618  8371  8371 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-30 22:56:53.618  8371  8371 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 22:56:53.618  8371  8371 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 22:56:53.619  8371  8371 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 22:56:53.619  8371  8371 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 22:56:53.619  8371  8371 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 22:56:53.655  8334  8379 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 22:56:53.665  1037  2098 W libprocessgroup: failed to open /acct/uid_10085/pid_7348/cgroup.procs: No such file or directory
08-30 22:56:53.689  8384  8384 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 22:56:53.708  8384  8384 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 22:56:53.747  8384  8384 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 22:56:53.747  8384  8384 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 22:56:53.747  8384  8384 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 22:56:53.748  8384  8384 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 22:56:53.748  8384  8384 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 22:56:53.749  8384  8384 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-30 22:56:53.753  8384  8384 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 22:56:53.765  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 22:56:53.767  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 22:56:53.782  8384  8384 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 22:56:53.785  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 22:56:53.787  7021  7021 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 22:56:53.788  8384  8384 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 22:56:53.789  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:53.789  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 22:56:53.792  8384  8384 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 22:56:53.800  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:53.805  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:53.810  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:53.811  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:53.812  8384  8384 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 22:56:53.813  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:53.814  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 22:56:53.818  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:53.822  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:53.829  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:53.829  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:53.830  8384  8384 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 22:56:53.834  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 22:56:53.834  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 22:56:53.834  7021  7021 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 22:56:53.834  7021  7021 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 22:56:53.834  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 22:56:53.835  7021  7021 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 22:56:53.835  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 22:56:53.835  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 22:56:53.835  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 22:56:53.835  7021  7021 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 22:56:53.835  7021  7021 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 22:56:53.835  7021  7021 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 22:56:53.837  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:53.837  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 22:56:53.841  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:53.845  8334  8379 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:56:53.845  8334  8379 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 22:56:53.847  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:53.852  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:53.852  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:53.853  8384  8384 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 22:56:53.854  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:53.855  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 22:56:53.860  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:53.864  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:53.871  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:53.872  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:53.872  8384  8384 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 22:56:53.874  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:53.876  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 22:56:53.880  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:53.884  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:53.889  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:53.889  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:53.889  8384  8384 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 22:56:53.891  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:53.891  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 22:56:53.899  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:53.904  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:53.910  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:53.911  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:53.912  8384  8384 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 22:56:53.917   312  8434 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 22:56:53.917   312  8434 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 22:56:53.919  8334  8379 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-30 22:56:53.920  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 22:56:53.921  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:53.935  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:53.939  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:53.944  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:53.945  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:53.950  8384  8384 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 22:56:53.952  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:53.952  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 22:56:53.954  8334  8379 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-30 22:56:53.961   312  8434 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-30 22:56:53.962  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:53.966  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:53.974  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 22:56:53.975  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:53.975  8384  8384 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 22:56:53.977  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:53.978  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 22:56:53.979  8334  8379 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-30 22:56:53.982  8289  8289 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 22:56:53.983  8334  8379 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 22:56:53.984  8334  8379 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 22:56:53.985  8334  8379 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 22:56:53.985  8334  8379 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 22:56:53.985  8289  8289 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:53.987  8334  8379 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-30 22:56:53.990  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 22:56:53.991  8334  8379 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-30 22:56:53.995  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 22:56:54.000  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 22:56:54.000  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:54.001  8384  8384 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 22:56:54.002  8384  8384 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 22:56:54.002  8384  8384 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 22:56:54.006  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.006  8334  8380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 22:56:54.009  8289  8289 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 22:56:54.009  8289  8289 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 22:56:54.012  7021  7021 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 22:56:54.015  1037  8355 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 22:56:54.015  7021  7021 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 22:56:54.016  1037  8355 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 22:56:54.016  1037  8355 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 22:56:54.016  1037  8355 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 22:56:54.016  1037  8355 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 22:56:54.017  1037  8355 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 22:56:54.017  1037  8355 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 22:56:54.017  1037  8355 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 22:56:54.017  1037  8355 D DhcpStateMachine: RunningState
08-30 22:56:54.037  8384  8384 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 22:56:54.037  8384  8384 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 22:56:54.038  8384  8384 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 22:56:54.038  8384  8384 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 22:56:54.039  8384  8384 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 22:56:54.041  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 22:56:54.045  8384  8384 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 22:56:54.046  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 22:56:54.047  8384  8384 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-30 22:56:54.085  8384  8384 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 22:56:54.086  8384  8384 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 22:56:54.092  8384  8384 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 22:56:54.093  8384  8384 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 22:56:54.093  8384  8384 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 22:56:54.093  8384  8384 V SoundPool: doLoad: loading sample sampleID=1
08-30 22:56:54.094  8384  8384 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 22:56:54.095  8384  8441 V SoundPool: Start decode
08-30 22:56:54.095  8384  8441 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 22:56:54.097   316  1372 V MediaPlayerService: decode(22, 10857164, 17813)
08-30 22:56:54.097   316  1372 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 22:56:54.097   316  1372 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 22:56:54.097   316  1372 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 22:56:54.097   316  1372 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 22:56:54.097   316  1372 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 22:56:54.097   316  1372 V MediaPlayerService: player type = 3
08-30 22:56:54.097   316  1372 V AwesomePlayer: AwesomePlayer create()
08-30 22:56:54.101   316  1372 V AwesomePlayer: reset_l() 
08-30 22:56:54.101   316  1372 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:54.101   316  1372 V AwesomePlayer: setAudioSink() 
08-30 22:56:54.101   316  1372 V AwesomePlayer: reset_l() 
08-30 22:56:54.101   316  1372 V AudioCache: notify(0xb1432440, 8, 0, 0)
08-30 22:56:54.101   316  1372 V AudioCache: ignored
08-30 22:56:54.101   316  1372 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:54.101  7793  7793 D UEI.SmartControl: QS Service created
08-30 22:56:54.102   316  1372 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 22:56:54.102   316  1372 V AwesomePlayer: setDataSource_l dataSource
08-30 22:56:54.102   316  1372 V LGParserOSAL: SniffLGParser start
08-30 22:56:54.102   316  1372 V LGParserOSAL: MainType:5, SubType=0
08-30 22:56:54.102   316  1372 V LGParserOSAL: #### check Mime : application/ogg
08-30 22:56:54.102   316  1372 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 22:56:54.102   316  1372 E MediaExtractor: Use LGExtractor :application/ogg 
,08-30 22:56:54.108  8384  8384 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 22:56:54.109  8384  8384 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 22:56:54.110  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 22:56:54.122  8384  8384 V LGMDMManager: Create singleton instance
08-30 22:56:54.123  7793  7793 I UEI.SmartControl: Service initServices...
08-30 22:56:54.123  7793  7793 D UEI.SmartControl: QS start get config
08-30 22:56:54.130  2247  2247 I art     : Explicit concurrent mark sweep GC freed 10941(675KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 668us total 26.652ms
,08-30 22:56:54.149   316  1372 V LGParserOSAL: supported mime: application/ogg
08-30 22:56:54.149   316  1372 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 22:56:54.149   316  1372 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 22:56:54.149   316  1372 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 22:56:54.149   316  1372 V AwesomePlayer: AudioTrack Setting
08-30 22:56:54.149   316  1372 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 22:56:54.149   316  1372 V AwesomePlayer: setAudioSource() 
08-30 22:56:54.149   316  1372 V MediaPlayerService: prepare
08-30 22:56:54.149   316  1372 V AwesomePlayer: prepareAsync_l() 
08-30 22:56:54.149   316  1372 V MediaPlayerService: wait for prepare
08-30 22:56:54.149   316  8443 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 22:56:54.149   316  8443 V AwesomePlayer: initAudioDecoder() 
08-30 22:56:54.149   316  8443 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 22:56:54.149   316  8443 V AudioSystem: isOffloadSupported()
08-30 22:56:54.149   316  8443 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 22:56:54.149   316  8443 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 22:56:54.149   316  8443 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 22:56:54.149   316  8443 V AwesomePlayer: getUseOffload() = 0 
08-30 22:56:54.149   316  8443 V OMXCodec: OMXCodec::Create
08-30 22:56:54.149   316  8443 V OMXCodec: findMatchingCodecs()
08-30 22:56:54.149   316  8443 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 22:56:54.149   316  8443 V OMXCodec: matchingCodecs.size()=1
08-30 22:56:54.149   316  8443 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 22:56:54.151   316  8443 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 22:56:54.151   316  8443 V LGCodecAdapter: LG Codec Adapter start
08-30 22:56:54.151   316  8443 V OMXCodec: OMXCodec Createtor
08-30 22:56:54.151   316  8443 V OMXCodec: setComponentRole
08-30 22:56:54.151   316  8443 V OMXCodec: configureCodec protected=0
08-30 22:56:54.151   316  8443 V LGCodecAdapter: called getLGCodecSpecificData
08-30 22:56:54.151   316  8443 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 22:56:54.151   316  8443 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 22:56:54.151   316  8443 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 22:56:54.151   316  8443 V LGCodecOSAL: Not support LGCodec
08-30 22:56:54.151   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 22:56:54.151   316  8443 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 22:56:54.151   316  8443 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 22:56:54.151   316  8443 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 22:56:54.151   316  8443 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 22:56:54.151   316  8443 V AudioSystem: isOffloadSupported()
08-30 22:56:54.151   316  8443 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 22:56:54.151   316  8443 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 22:56:54.151   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 22:56:54.151   316  8443 V OMXCodec: init()
08-30 22:56:54.151   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 22:56:54.151   316  8443 V OMXCodec: allocateBuffers
08-30 22:56:54.151   316  8443 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 22:56:54.151   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 22:56:54.152   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
08-30 22:56:54.152   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on input port
08-30 22:56:54.152   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on input port
08-30 22:56:54.152   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on input port
08-30 22:56:54.152   316  8443 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 22:56:54.152   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 22:56:54.152   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-30 22:56:54.152   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
08-30 22:56:54.152   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on output port
08-30 22:56:54.152   316  8443 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on output port
08-30 22:56:54.152   316  8443 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 22:56:54.152   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 22:56:54.152   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 22:56:54.152   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 22:56:54.152   316  8443 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 22:56:54.152   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 22:56:54.152   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 22:56:54.152   31,6  8445 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 22:56:54.152   316  8443 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 22:56:54.152   316  8443 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 22:56:54.152   316  8443 V AudioCache: notify(0xb1432440, 5, 0, 0)
08-30 22:56:54.152   316  8443 V AudioCache: ignored
08-30 22:56:54.152   316  8443 V AudioCache: notify(0xb1432440, 1, 0, 0)
08-30 22:56:54.152   316  8443 V AudioCache: prepared
08-30 22:56:54.152   316  1372 V AudioCache: wait - success
08-30 22:56:54.152   316  1372 V MediaPlayerService: start
08-30 22:56:54.152   316  1372 V AwesomePlayer: play_l() 
08-30 22:56:54.152   316  1372 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 22:56:54.152   316  1372 V AwesomePlayer: createAudioPlayer_l
08-30 22:56:54.152   316  1372 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 22:56:54.152   316  1372 V AwesomePlayer: startAudioPlayer_l() 
08-30 22:56:54.152   316  1372 D AudioPlayer: start of Playback, useOffload 0
08-30 22:56:54.152   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 22:56:54.152   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048736
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048896
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975264
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 22:56:54.154   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975344
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 22:56:54.155   316  8445 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on output port
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fc40 on output port
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on output port
08-30 22:56:54.155   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 22:56:54.155   316  8445 V OMXCod,ec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 22:56:54.156   316  1372 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 22:56:54.156   316  1372 V AudioCache: notify(0xb1432440, 6, 0, 0)
08-30 22:56:54.156   316  1372 V AudioCache: ignored
08-30 22:56:54.157   316  1372 V MediaPlayerService: wait for playback complete
08-30 22:56:54.157   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.157   316  8446 V AudioCache: memcpy(0xaf006000, 0xb57ce000, 4096)
08-30 22:56:54.158   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.158   316  8446 V AudioCache: memcpy(0xaf007000, 0xb57ce000, 4096)
08-30 22:56:54.158   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.158   316  8446 V AudioCache: memcpy(0xaf008000, 0xb57ce000, 4096)
08-30 22:56:54.159   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.159   316  8446 V AudioCache: memcpy(0xaf009000, 0xb57ce000, 4096)
08-30 22:56:54.159   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.159   316  8446 V AudioCache: memcpy(0xaf00a000, 0xb57ce000, 4096)
08-30 22:56:54.159   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.159   316  8446 V AudioCache: memcpy(0xaf00b000, 0xb57ce000, 4096)
08-30 22:56:54.159   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.159   316  8446 V AudioCache: memcpy(0xaf00c000, 0xb57ce000, 4096)
08-30 22:56:54.160   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.160   316  8446 V AudioCache: memcpy(0xaf00d000, 0xb57ce000, 4096)
08-30 22:56:54.163   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.163   316  8446 V AudioCache: memcpy(0xaf00e000, 0xb57ce000, 4096)
08-30 22:56:54.163   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.163   316  8446 V AudioCache: memcpy(0xaf00f000, 0xb57ce000, 4096)
08-30 22:56:54.164   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.164   316  8446 V AudioCache: memcpy(0xaf010000, 0xb57ce000, 4096)
08-30 22:56:54.164   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.164   316  8446 V AudioCache: memcpy(0xaf011000, 0xb57ce000, 4096)
08-30 22:56:54.164   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.165   316  8446 V AudioCache: memcpy(0xaf012000, 0xb57ce000, 4096)
08-30 22:56:54.165   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.165   316  8446 V AudioCache: memcpy(0xaf013000, 0xb57ce000, 4096)
08-30 22:56:54.165   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.165   316  8446 V AudioCache: memcpy(0xaf014000, 0xb57ce000, 4096)
08-30 22:56:54.166   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.166   316  8446 V AudioCache: memcpy(0xaf015000, 0xb57ce000, 4096)
08-30 22:56:54.166   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.166   316  8446 V AudioCache: memcpy(0xaf016000, 0xb57ce000, 4096)
08-30 22:56:54.166   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.166   316  8446 V AudioCache: memcpy(0xaf017000, 0xb57ce000, 4096)
08-30 22:56:54.166   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.166   316  8446 V AudioCache: memcpy(0xaf018000, 0xb57ce000, 4096)
08-30 22:56:54.167   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.167   316  8446 V AudioCache: memcpy(0xaf019000, 0xb57ce000, 4096)
08-30 22:56:54.167   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.167   316  8446 V AudioCache: memcpy(0xaf01a000, 0xb57ce000, 4096)
08-30 22:56:54.167   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.167   316  8446 V AudioCache: memcpy(0xaf01b000, 0xb57ce000, 4096)
08-30 22:56:54.167   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.167   316  8446 V AudioCache: memcpy(0xaf01c000, 0xb57ce000, 4096)
08-30 22:56:54.169   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.169   316  8446 V AudioCache: memcpy(0xaf01d000, 0xb57ce000, 4096)
08-30 22:56:54.169   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.169   316  8446 V AudioCache: memcpy(0xaf01e000, 0xb57ce000, 4096)
08-30 22:56:54.169   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.169   316  8446 V AudioCache: memcpy(0xaf01f000, 0xb57ce000, 4096)
08-30 22:56:54.169   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.169   316  8446 V AudioCache: memcpy(0xaf020000, 0xb57ce000, 4096)
08-30 22:56:54.170   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.170   316  8446 V AudioCache: memcpy(0xaf021000, 0xb57ce000, 4096)
08-30 22:56:54.170   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.170   316  8446 V AudioCache: memcpy(0xaf022000, 0xb57ce000, 4096)
08-30 22:56:54.170   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.170   316  8446 V AudioCache: memcpy(0xaf023000, 0xb57ce000, 4096)
08-30 22:56:54.170   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.170   316  8446 V AudioCache: memcpy(0xaf024000, 0xb57ce000, 4096)
08-30 22:56:54.172   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.172   316  8446 V AudioCache: memcpy(0xaf025000, 0xb57ce000, 4096)
08-30 22:56:54.172   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.172   316  8446 V AudioCache: memcpy(0xaf026000, 0xb57ce000, 4096)
08-30 22:56:54.172   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.172   316  8446 V AudioCache: memcpy(0xaf027000, 0xb57ce000, 4096)
08-30 22:56:54.172   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.172   316  8446 V AudioCache: memcpy(0xaf028000, 0xb57ce000, 4096)
08-30 22:56:54.173   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.173   316  8446 V AudioCache: memcpy(0xaf029000, 0xb57ce000, 4096)
08-30 22:56:54.173   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.173   316  8446 V AudioCache: memcpy(0xaf02a000, 0xb57ce000, 4096)
08-30 22:56:54.173   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.173   316  8446 V AudioCache: memcpy(0xaf02b000, 0xb57ce000, 4096)
08-30 22:56:54.173   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.173   316  8446 V AudioCache: memcpy(0xaf02c000, 0xb57ce000, 4096)
08-30 22:56:54.175   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.175   316  8446 V AudioCache: memcpy(0xaf02d000, 0xb57ce000, 4096)
08-30 22:56:54.177   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.177   316  8446 V AudioCache: memcpy(0xaf02e000, 0xb57ce000, 4096)
08-30 22:56:54.177   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.177   316  8446 V AudioCache: memcpy(0xaf02f000, 0xb57ce000, 4096)
08-30 22:56:54.178   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.178   316  8446 V AudioCache: memcpy(0xaf030000, 0xb57ce000, 4096)
08-30 22:56:54.178   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.178   316  8446 V AudioCache: memcpy(0xaf031000, 0xb57ce000, 4096)
08-30 22:56:54.179   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.179   316  8446 V AudioCache: memcpy(0xaf032000, 0xb57ce000, 4096)
08-30 22:56:54.180   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.180   316  8446 V AudioCache: memcpy(0xaf033000, 0xb57ce000, 4096)
08-30 22:56:54.180   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.180   316  8446 V AudioCache: memcpy(0xaf034000, 0xb57ce000, 4096)
08-30 22:56:54.181   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.181   316  8446 V AudioCache: memcpy(0xaf035000, 0xb57ce000, 4096)
08-30 22:56:54.181   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.181   316  8446 V AudioCache: memcpy(0xaf036000, 0xb57ce000, 4096)
08-30 22:56:54.182   316  8446 V AudioCache: write(0xb57ce000, 4096)
08-30 22:56:54.182   316  8446 V AudioCache: memcpy(0xaf037000, 0xb57ce000, 4096)
08-30 22:56:54.182   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 22:56:54.182   316  8446 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 22:56:54.182   316  8446 V AwesomePlayer: postAudioEOS() 
08-30 22:56:54.182   316  8446 V AudioCache: write(0xb57ce000, 280)
08-30 22:56:54.182   316  8446 V AudioCache: memcpy(0xaf038000, 0xb57ce000, 280)
08-30 22:56:54.184   316  8443 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 22:56:54.184   316  8443 V AwesomePlayer: onStreamDone
08-30 22:56:54.184   316  8443 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 22:56:54.184   316  8443 V AudioCache: notify(0xb1432440, 2, 0, 0)
08-30 22:56:54.184   316  8443 V AudioCache: playback complete
08-30 22:56:54.184   316  8443 V AwesomePlayer: pause_l() 
08-30 22:56:54.184   316  8443 V AudioCache: notify(0xb1432440, 7, 0, 0)
08-30 22:56:54.184   316  8443 V AudioCache: ignored
08-30 22:56:54.184   316  8443 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:54.184   316  1372 V AudioCache: wait - success
08-30 22:56:54.184   316  8443 D AudioPlayer: Pause Playback at 1068125
08-30 22:56:54.184   316  1372 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 22:56:54.185   316  1372 V AwesomePlayer: reset_l() 
08-30 22:56:54.185   316  1372 V AudioCache: notify(0xb1432440, 8, 0, 0)
08-30 22:56:54.185   316  1372 V AudioCache: ignored
08-30 22:56:54.185   316  1372 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:54.185   316  1372 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 22:56:54.185   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 22:56:54.185   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 22:56:54.185   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 22:56:54.185   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 0
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 0
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 0
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 1
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fc40 on port 1
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 22:56:54.185   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 1
08-30 22:56:54.186   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 22:56:54.186   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 22:56:54.186   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 22:56:54.186   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 22:56:54.186   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 22:56:54.186   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 22:56:54.186   316  8445 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 22:56:54.186   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 22:56:54.186   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 22:56:54.186   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 22:56:54.187   316  1372 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 22:56:54.187   316  1372 D AudioPlayer: AudioPlayer releasing audio source
08-30 22:56:54.187   316  1372 D AudioPlayer: AudioPlayer done releasing audio source
08-30 22:56:54.187   316  1372 V AwesomePlayer: reset_l() 
08-30 22:56:54.187   316  1372 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:54.187   316  1372 V AwesomePlayer: ~AwesomePlayer call
,08-30 22:56:54.188   316  1372 V AwesomePlayer: reset_l() 
08-30 22:56:54.188   316  1372 V AwesomePlayer: cancelPlayerEvents
08-30 22:56:54.189  8384  8441 V SoundPool: close(31)
08-30 22:56:54.189  8384  8441 V SoundPool: pointer = 0xa0048000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 22:56:54.192  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 22:56:54.193  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 22:56:54.194  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9936
08-30 22:56:54.196  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.215  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.218  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.220  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.222  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.224  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.227  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 22:56:54.230  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.232  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.235  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 22:56:54.260  2247  8442 D GCM     : Connected
,08-30 22:56:54.266  1037  1526 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:54.266  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 22:56:54.267  1037  1526 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:54.267  1037  1526 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:54.267  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:54.267  1037  1526 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 22:56:54.268  1037  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 22:56:54.268  1037  1532 D ConnectivityService: identical MTU - not setting
08-30 22:56:54.268  1037  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 22:56:54.269  1037  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 22:56:54.269  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 22:56:54.269  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 22:56:54.270  1037  1532 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:54.272  1590  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 22:56:54.278  2247  8442 D GCM     : Message class com.google.e.a.a.q
08-30 22:56:54.408  7793  7793 I UEI.SmartControl: Supports setup maps: true
08-30 22:56:54.411  7793  7793 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 22:56:54.411  7793  7793 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 22:56:54.411  7793  7793 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 22:56:54.411  7793  7793 I UEI.SmartControl: ### init IR Blaster...
,08-30 22:56:54.414  7793  7793 D serial_port: Configuring serial port
08-30 22:56:54.415  7793  7793 E UEI.SmartControl: UEIBLaster setting for 616
08-30 22:56:54.415  7793  7793 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 22:56:54.415  7793  7793 I UEI.SmartControl: configuring settings for MAXQ616
,08-30 22:56:54.415  7793  7793 I UEI.SmartControl: Get version...
08-30 22:56:54.434  7793  8448 D UEI.SmartControl: serial port data available: 21
,08-30 22:56:54.460  7793  7793 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 22:56:54.460  7793  7793 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 22:56:54.460  7793  7793 I UEI.SmartControl: QS saving settings...
,08-30 22:56:54.462  7793  7793 D UEI.SmartControl: IR Blaster version: 25672567
08-30 22:56:54.479  7793  8448 D UEI.SmartControl: serial port data available: 4
,08-30 22:56:54.509  7793  8454 I UEI.SmartControl: Device manager: loading config....
,08-30 22:56:54.510  7793  7793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 22:56:54.510  7793  8454 D UEI.SmartControl: ----------- loading internal config...
08-30 22:56:54.513  7793  7793 E UEI.SmartControl: Services init done
08-30 22:56:54.513  7793  7793 D UEI.SmartControl: QS Service init finished
08-30 22:56:54.514  7793  7793 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 22:56:54.514  7793  7793 D UEI.SmartControl: QS Service version code: 201091
08-30 22:56:54.514  7793  7793 D UEI.SmartControl: Service requested: Control
,08-30 22:56:54.521  7793  8454 E UEI.SmartControl: Loading SETTINGS...
08-30 22:56:54.525  7793  7793 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 22:56:54.527  7793  7793 D UEI.SmartControl: Internal service binding...
08-30 22:56:54.528  8384  8384 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-30 22:56:54.529  7793  7810 I UEI.SmartControl: ------ IControl API: 11
08-30 22:56:54.529  7793  7810 D UEI.SmartControl: File observer start...
08-30 22:56:54.529  7793  7810 E UEI.SmartControl: IR Port is disabled: false
08-30 22:56:54.529  7793  7810 D UEI.SmartControl: Starting file observer...
08-30 22:56:54.530  7793  7810 I UEI.SmartControl: Registering callback...
08-30 22:56:54.531  7793  8454 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 22:56:54.531  7793  7809 I UEI.SmartControl: ------ IControl API: 19
08-30 22:56:54.533  7793  7809 I UEI.SmartControl: Registering Services Ready callback...
08-30 22:56:54.548  7793  8453 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 22:56:54.549  8384  8399 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-30 22:56:54.551  8384  8439 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 22:56:54.552  8384  8439 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 22:56:54.553  7793  8453 D UEI.SmartControl: -----service ready thread exits
08-30 22:56:54.554  8384  8384 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 22:56:54.555  8384  8384 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 22:56:54.555  7793  7810 I UEI.SmartControl: ------ IControl API: 8
08-30 22:56:54.558  8384  8384 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 22:56:54.558  8384  8384 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 22:56:54.559  8384  8384 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 22:56:54.559  8384  8384 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 22:56:54.561  8384  8384 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 22:56:54.561  8384  8384 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 22:56:54.567  8384  8384 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-30 22:56:54.571  8384  8384 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 22:56:54.573  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 22:56:54.575  8384  8384 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 22:56:54.576  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 22:56:54.579  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 22:56:54.581  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 22:56:54.582  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 22:56:54.585  8384  8384 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472590614583]
,08-30 22:56:54.591  8384  8384 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 22:56:54.594  1037  1934 I ActivityManager: Killing 7367:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-30 22:56:54.620  8384  8456 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 22:56:54.705  1037  1906 W libprocessgroup: failed to open /acct/uid_10093/pid_7367/cgroup.procs: No such file or directory
,08-30 22:56:54.718  8384  8384 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 22:56:54.720  8384  8384 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 22:56:54.721  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-30 22:56:54.721  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 22:56:54.722  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 22:56:54.723  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 22:56:54.724  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 22:56:54.740  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 22:56:56.202  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-59 f=2437 sc=60 link=72 tx=79.0, 0.0, 0.0  rx=80.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-583166326] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 22:56:56.213  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-59 f=2437 sc=60 link=72 tx=79.0, 0.0, 0.0  rx=80.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-583166315] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:56:56.213  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 22:56:56.229  1590  1590 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 22:56:56.250  1037  1527 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-30 22:56:56.288  1037  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:56.305  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-30 22:56:56.330  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:56.330  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:56.330  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:56.330  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:56.330  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:56.330  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:56.330  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:56:56.330  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 22:56:56.336  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:56.340  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:56.340  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:56.340  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:56.340  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:56.340  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:56.340  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:56.340  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:56:56.340  6865  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:56.342  6865  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:56.347  1037  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:56.351  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 22:56:56.360  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 22:56:56.376  2247  2247 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:56.391  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 22:56:56.391  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:56.391  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 22:56:56.391  7227  7227 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 22:56:56.400  7227  7227 I AppUp4:CustModeStarterReceiver: onReceive
08-30 22:56:56.405  7227  7227 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1a20d0ef
08-30 22:56:56.405  7227  7227 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 22:56:56.405  7227  7227 D AppUp4:CustFacade: isPhone : true
,08-30 22:56:56.406  7227  7227 D AppUp4:CustModeStarterReceiver: begin check event
08-30 22:56:56.407  7227  7227 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 22:56:56.414  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:56:56.414  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:56:56.414  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:56:56.414  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:56:56.414  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:56:56.414  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:56:56.414  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:56:56.414  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:56:56.416  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 22:56:56.418  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:56:56.419  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a213e48 removed from the list
08-30 22:56:56.419  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:56:56.419  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:56:56.419  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:56:56.424  6865  8464 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-30 22:56:56.424  6865  8464 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 22:56:56.426  8334  8427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 22:56:56.431  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:56.431  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 22:56:56.433  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 22:56:56.441  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 22:56:56.452  2833  2833 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:56:56.461  4747  8477 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 22:56:56.461  1037  1952 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
08-30 22:56:56.465  1037  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 22:56:56.466  4747  8477 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-30 22:56:56.467  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-5ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:56.467  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:56.467  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 22:56:56.467  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:56:56.467  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 22:56:56.470  4747  8478 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:56.470  4747  8478 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 22:56:56.475  2833  2833 V DownloadManager: DownloadService onCreate
08-30 22:56:56.477  2833  8483 I DownloadManager: in removeSpuriousFiles
08-30 22:56:56.478  2833  8483 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,08-30 22:56:56.479  2833  8483 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@42f8e63 on behalf of 2833
,08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-30 22:56:56.485  2833  8483 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-30 22:56:56.486  2833  8483 I DownloadManager: in trimDatabase
08-30 22:56:56.486  2833  8483 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-30 22:56:56.487  2833  8483 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@7ab0b19 on behalf of 2833
08-30 22:56:56.498  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 20:56:56 GMT], X-Android-Received-Millis=[1472590616498], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472590616470]}
08-30 22:56:56.498  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 22:56:56.498  1037  8354 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 22:56:56.498  1037  1532 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 22:56:56.498  1037  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 22:56:56.498  1037  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:56:56.499  1037  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:56.499  1037  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 22:56:56.499  1037  1532 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 22:56:56.499  1037  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 22:56:56.499  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:56:56.499  1037  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:56.499  1037  153,2 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 22:56:56.499  1590  1798 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 22:56:56.513  1037  2021 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8487 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 22:56:56.516  2833  2833 V DownloadManager: DownloadService onStartCommand
08-30 22:56:56.519  2833  8484 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-30 22:56:56.520  4747  8477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-30 22:56:56.525  2833  8484 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1582adbf on behalf of 2833
08-30 22:56:56.531  4747  4747 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,08-30 22:56:56.533  4747  4747 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-30 22:56:56.534  4747  4747 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-30 22:56:56.536  4747  4747 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-30 22:56:56.540  4747  4747 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-30 22:56:56.546  2833  8484 V DownloadManager: processing inserted download 1
08-30 22:56:56.547  2833  8484 V DownloadManager: processing inserted download 4
08-30 22:56:56.548  2833  8484 V DownloadManager: processing inserted download 7
,08-30 22:56:56.549  2833  8484 V DownloadManager: processing inserted download 8
08-30 22:56:56.550  2833  8484 V DownloadManager: processing inserted download 9
08-30 22:56:56.551  2833  8484 V DownloadManager: processing inserted download 10
08-30 22:56:56.551  2833  8484 V DownloadManager: processing inserted download 11
08-30 22:56:56.552  2833  8484 V DownloadManager: processing inserted download 12
08-30 22:56:56.553  2833  8484 V DownloadManager: processing inserted download 13
08-30 22:56:56.554  2833  8484 V DownloadManager: processing inserted download 14
08-30 22:56:56.555  2833  8484 V DownloadManager: processing inserted download 16
08-30 22:56:56.678  1037  2077 I art     : Explicit concurrent mark sweep GC freed 78098(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.751ms total 118.116ms
,08-30 22:56:56.686  2833  2833 V DownloadManager: DownloadService onDestroy
08-30 22:56:56.703  8487  8487 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:56:56.703  8487  8487 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 22:56:56.704  8487  8487 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 22:56:56.704  8487  8487 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 22:56:56.762  8487  8487 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 22:56:56.771  8487  8487 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-30 22:56:56.807  8487  8487 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 22:56:56.832  8487  8487 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 22:56:56.832  8487  8487 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:56.975  8487  8487 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 22:56:57.014  8487  8487 I HubEmail: JNI_OnLoad()
08-30 22:56:57.014  8487  8487 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-30 22:56:57.014  8487  8487 I HubEmail: registerNatives()
08-30 22:56:57.014  8487  8487 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 22:56:57.014  8487  8487 I HubEmail: registerNativeMethods()
08-30 22:56:57.014  8487  8487 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 22:56:57.018  8487  8487 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 22:56:57.031  8487  8519 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:56:57.043  3158  3158 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 22:56:57.043  3158  3158 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 22:56:57.043  3158  3158 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 22:56:57.043  3158  3158 D PhoneState: setPdpRejectCasuse : false
08-30 22:56:57.068   312  8522 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 22:56:57.071   312  8522 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-30 22:56:57.081  1037  1636 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8523 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 22:56:57.127   312  8522 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-30 22:56:57.182  8267  8518 V FormManager: There are no updated forms. The schedule will be deleted.
,08-30 22:56:57.189  8267  8518 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-30 22:56:57.203  8523  8523 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:56:57.203  8523  8523 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 22:56:57.206  8523  8523 D PhoneMonitor: Register our PhoneStateListener
,08-30 22:56:57.227  1037  1367 I ActivityManager: Killing 7851:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 22:56:57.235  8523  8523 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 22:56:57.237  8523  8523 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 22:56:57.256  8523  8523 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 22:56:57.257  8523  8523 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 22:56:57.258  8523  8523 D TelephonyAutoProfiling: [parse] Load xml
08-30 22:56:57.261  8523  8523 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 22:56:57.261  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 22:56:57.261  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 22:56:57.261  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 22:56:57.261  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 22:56:57.261  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 22:56:57.261  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 22:56:57.261  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 22:56:57.261  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 22:56:57.262  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 22:56:57.262  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 22:56:57.262  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 22:56:57.262  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 22:56:57.262  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 22:56:57.262  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 22:56:57.262  8523  8523 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 22:56:57.262  8523  8523 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 22:56:57.269  8523  8523 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-30 22:56:57.348  1037  1367 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8553 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 22:56:57.349  1037  1367 I ActivityManager: Killing 7902:com.android.contacts/u0a19 (adj 15): empty #17
,08-30 22:56:57.425  1037  2342 W libprocessgroup: failed to open /acct/uid_10072/pid_7851/cgroup.procs: No such file or directory
,08-30 22:56:57.429  1037  1953 W libprocessgroup: failed to open /acct/uid_10019/pid_7902/cgroup.procs: No such file or directory
,08-30 22:56:57.462   312  8572 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 22:56:57.462   312  8572 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-30 22:56:57.464  1826  8571 I CheckinService: active receiver: enabled
,08-30 22:56:57.479  1826  8571 I CheckinService: Preparing to send checkin request
08-30 22:56:57.480  1826  8571 I EventLogService: Accumulating logs since 1472590578018
08-30 22:56:57.497   312  8572 D libc-netbsd: res_queryN name = www.google.com succeed
08-30 22:56:57.503   312  8575 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 22:56:57.503   312  8575 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 22:56:57.503   312  8575 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 22:56:57.537  1826  8571 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 22:56:57.553  1037  1528 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-30 22:56:57.631  1037  1953 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8577 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 22:56:57.632  1037  1953 I ActivityManager: Killing 7925:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 22:56:57.815  1037  1985 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8594 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 22:56:57.816  1037  2019 W libprocessgroup: failed to open /acct/uid_10027/pid_7925/cgroup.procs: No such file or directory
,08-30 22:56:57.836  1037  1526 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-30 22:56:57.837  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 22:56:57.837  1037  1526 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 22:56:57.837  1037  1526 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 22:56:57.838  1037  1526 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 22:56:57.838  1037  1526 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-30 22:56:57.910  8594  8594 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 22:56:57.911  8594  8594 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 22:56:57.947  8594  8594 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 22:56:57.949  8594  8594 I MultiDex: install
08-30 22:56:57.949  8594  8594 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 22:56:57.952  1037  1636 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8614 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 22:56:57.953  1037  1636 I ActivityManager: Killing 7947:com.android.vending/u0a44 (adj 15): empty #17
08-30 22:56:57.997  1037  2342 W libprocessgroup: failed to open /acct/uid_10044/pid_7947/cgroup.procs: No such file or directory
,08-30 22:56:58.008  8594  8594 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 22:56:58.034  8614  8614 I art     : Almond Protected OAT
,08-30 22:56:58.090  8614  8614 D WeatherApplication: removeAccount
,08-30 22:56:58.092  8614  8614 D WeatherApplication: Account.length = 0
08-30 22:56:58.093  8614  8614 E WeatherApplication: OPERATOR:OPEN
08-30 22:56:58.105  8614  8614 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:58
08-30 22:56:58.108  8614  8614 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 22:56:58.108  8614  8614 D Weather.Utils: 2 : All the weather widget is gone.
08-30 22:56:58.110  8614  8614 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 22:56:58.113  8614  8614 D WeatherAncestor: connectivity changed - connection : true
08-30 22:56:58.114  8614  8614 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 22:56:58.125  8614  8614 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 22:56:58.125  8614  8614 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 22:56:58.126  8614  8614 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-30 22:56:58.145  8614  8614 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 22:56:58.146  8614  8614 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:56:58
,08-30 22:56:58.196  1037  1934 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8633 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 22:56:58.198  1037  1934 I ActivityManager: Killing 7986:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 22:56:58.276  1037  1053 W libprocessgroup: failed to open /acct/uid_10080/pid_7986/cgroup.procs: No such file or directory
,08-30 22:56:58.437   279   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 22:56:58.438   279   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 22:56:58.438   279   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 22:56:58.439  8633  8657 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 22:56:58.443   279   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 22:56:58.443   279   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 22:56:58.443   279   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 22:56:58.443  8633  8657 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 22:56:58.457   279   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 22:56:58.457   279   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 22:56:58.457   279   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 22:56:58.457  8633  8659 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 22:56:58.465   279   431 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 22:56:58.465   279   431 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 22:56:58.465   279   431 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 22:56:58.466  8633  8659 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 22:56:58.674  8633  8633 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 22:56:58.685  8633  8633 I LibraryLoader: Loading: webviewchromium
08-30 22:56:58.688  8633  8633 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3290-3293)
08-30 22:56:58.688  8633  8633 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 22:56:58.695  8633  8633 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {268ed356}
08-30 22:56:58.696  8633  8633 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 22:56:58.697  8633  8633 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 22:56:58.707  8633  8633 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 22:56:58.708  8633  8633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 22:56:58.717  8633  8633 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 22:56:58.717   316  1373 V AudioPolicyService: registerClient() client 0xb558aca0, uid 10093
,08-30 22:56:58.718  8633  8633 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 22:56:58.719  8633  8633 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 22:56:58.721  8633  8686 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 22:56:58.726  8680  8680 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-30 22:56:58.729  8633  8633 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 22:56:58.729  8633  8633 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 22:56:58.729  8633  8633 I Adreno-EGL: Build Date: 12/12/14 금
08-30 22:56:58.729  8633  8633 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 22:56:58.729  8633  8633 I Adreno-EGL: Remote Branch: 
08-30 22:56:58.729  8633  8633 I Adreno-EGL: Local Patches: 
08-30 22:56:58.729  8633  8633 I Adreno-EGL: Reconstruct Branch: 
08-30 22:56:58.779  8680  8680 I dex2oat : dex2oat took 53.585ms (threads: 4)
,08-30 22:56:58.795  8594  8609 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 22:56:58.795  8594  8609 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 22:56:58.795  8594  8609 I Adreno-EGL: Build Date: 12/12/14 금
08-30 22:56:58.795  8594  8609 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 22:56:58.795  8594  8609 I Adreno-EGL: Remote Branch: 
08-30 22:56:58.795  8594  8609 I Adreno-EGL: Local Patches: 
08-30 22:56:58.795  8594  8609 I Adreno-EGL: Reconstruct Branch: 
,08-30 22:56:58.811  8633  8633 I NSApplication: Starting up...
,08-30 22:56:58.836  1037  1765 I ActivityManager: Killing 7704:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 22:56:58.871  1037  1906 W libprocessgroup: failed to open /acct/uid_10037/pid_7704/cgroup.procs: No such file or directory
,08-30 22:56:58.888  2247  2247 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 22:56:58.899  2247  2247 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 22:56:58.900  2247  2247 D c       : Getting all permits...
08-30 22:56:58.900  2247  2247 D a       : Opening database...
08-30 22:56:58.907  2247  2247 D a       : Opening database auth.proximity.permit_store...
08-30 22:56:58.908  2247  2247 D a       : Closing database...
08-30 22:56:58.973  8594  8609 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:56:58.974  8594  8609 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:56:59.047  8594  8609 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 22:56:59.047  8594  8609 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 22:56:59.047  8594  8609 I Adreno-EGL: Build Date: 12/12/14 금
08-30 22:56:59.047  8594  8609 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 22:56:59.047  8594  8609 I Adreno-EGL: Remote Branch: 
08-30 22:56:59.047  8594  8609 I Adreno-EGL: Local Patches: 
08-30 22:56:59.047  8594  8609 I Adreno-EGL: Reconstruct Branch: 
,08-30 22:56:59.118  8594  8609 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 22:56:59.118  8594  8609 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 22:56:59.118  8594  8609 I Adreno-EGL: Build Date: 12/12/14 금
08-30 22:56:59.118  8594  8609 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 22:56:59.118  8594  8609 I Adreno-EGL: Remote Branch: 
08-30 22:56:59.118  8594  8609 I Adreno-EGL: Local Patches: 
08-30 22:56:59.118  8594  8609 I Adreno-EGL: Reconstruct Branch: 
,08-30 22:56:59.238  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=49.0, 0.0, 0.0  rx=47.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-583163290] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:56:59.241  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=49.0, 0.0, 0.0  rx=47.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-583163287] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:56:59.241  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 22:56:59.352   312  8711 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 22:56:59.352   312  8711 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 22:56:59.395   312  8711 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 22:56:59.440  6865  8464 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-30 22:56:59.440  6865  8464 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 22:56:59.441  6865  8464 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 22:56:59.442  6865  8464 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 22:56:59.451  6865  8464 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 22:56:59.452  6865  8712 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-30 22:56:59.452  6865  8712 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 22:56:59.453  6865  8715 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 904, name: OutgoingSocketThread/Receiver)
08-30 22:56:59.454  6865  8712 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 22:56:59.454  6865  8712 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 22:56:59.454  6865  8712 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 22:56:59.455  6865  8715 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 904, thread name: OutgoingSocketThread/Receiver)
08-30 22:56:59.455  6865  8715 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 22:56:59.455  6865  8715 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 904, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 22:56:59.456  6865  8714 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 903, name: OutgoingSocketThread/Sender)
,08-30 22:56:59.459  6865  8717 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 906, name: IncomingSocketThread/Receiver)
08-30 22:56:59.460  6865  8716 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 905, name: IncomingSocketThread/Sender)
08-30 22:56:59.461  6865  8717 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 906, thread name: IncomingSocketThread/Receiver)
08-30 22:56:59.461  6865  8717 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 22:56:59.461  6865  8717 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 906, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 22:56:59.496  1826  8571 I CheckinTask: Sending checkin request (7793 bytes)
,08-30 22:56:59.510  7793  8455 D UEI.SmartControl: Internal timer expired: 2
,08-30 22:56:59.510  7793  8455 D UEI.SmartControl: unbind internal service
,08-30 22:56:59.620  7793  8449 D serial_port: close(fd = 24)
,08-30 22:56:59.632  7793  8449 I UEI.SmartControl: Serial port is closed.
,08-30 22:56:59.765  1826  8571 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 22:56:59.783  1826  8571 I CheckinService: active receiver: disabled
,08-30 22:56:59.809  2247  2247 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 22:56:59.829  2247  2247 I GCM     : GCM config loaded
,08-30 22:56:59.847   312  8724 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 22:56:59.850   312  8724 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 22:56:59.850   312  8724 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-30 22:56:59.857  8523  8523 V SetupWizard: Connected to Gservices successfully
,08-30 22:57:00.009  1037  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=185534706, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
08-30 22:57:00.013  8384  8384 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 22:57:00.014  8384  8384 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9936
,08-30 22:57:00.066  1590  1590 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 22:57:00.066  1590  1590 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 22:57:00.066  1590  1590 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 22:57:00.066  1590  1590 I [SystemUI]Clock: called onTimeUpdated()
,08-30 22:57:00.081  2666  2666 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 22:57:00.094  1590  1590 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 22:57:00.094  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-30 22:57:00.095  1590  1590 I [SystemUI]DateView: called onTimeUpdated()
08-30 22:57:00.096  1590  1590 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 22:57:00.109  2247  8726 D GCM     : Connected
,08-30 22:57:00.136  2247  8726 D GCM     : Message class com.google.e.a.a.q
,08-30 22:57:00.166  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=185534706 [*alarm*], flags=0x0
,08-30 22:57:02.260  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=32.5, 0.0, 0.0  rx=29.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-583160268] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:57:02.262  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=32.5, 0.0, 0.0  rx=29.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-583160266] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:57:02.262  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 22:57:02.437  6865  6924 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 22:57:02.438  6865  6924 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 22:57:02.444  6865  6924 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2b0efc39 Bundle[{}]
08-30 22:57:02.445  6865  6924 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 22:57:02.446  6865  6924 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 22:57:02.446  6865  6924 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 22:57:02.447  6865  6924 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 22:57:02.448  6865  6924 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 22:57:02.448  6865  6924 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 22:57:02.455  6865  6924 I System.out: Running OutgoingSocketThread
,08-30 22:57:02.461  6865  8727 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-30 22:57:02.461  6865  8727 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 22:57:03.466  8633  8660 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 22:57:04.357  1037  1052 I ActivityManager: Killing 7754:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 22:57:04.389  1037  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_7754/cgroup.procs: No such file or directory
,08-30 22:57:05.288  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=26.8, 0.0, 0.0  rx=23.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-583157240] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 22:57:05.291  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=26.8, 0.0, 0.0  rx=23.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-583157237] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:57:05.292  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 22:57:05.478  6865  8727 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 22:57:05.478  6865  8727 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 22:57:05.478  6865  8727 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 22:57:05.479  6865  8727 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 22:57:05.479  6865  8727 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 22:57:05.487  6865  8730 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-30 22:57:05.487  6865  8730 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 22:57:05.488  6865  8730 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 22:57:05.488  6865  8730 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 22:57:05.490  6865  8733 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 916, name: OutgoingSocketThread/Receiver)
08-30 22:57:05.490  6865  8733 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 916, thread name: OutgoingSocketThread/Receiver)
08-30 22:57:05.490  6865  8733 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 22:57:05.490  6865  8733 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 916, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 22:57:05.491  6865  8730 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 22:57:05.493  6865  8732 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 915, name: OutgoingSocketThread/Sender)
08-30 22:57:05.495  6865  8734 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 917, name: IncomingSocketThread/Sender)
08-30 22:57:05.496  6865  8735 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 918, name: IncomingSocketThread/Receiver)
08-30 22:57:05.497  6865  8735 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 918, thread name: IncomingSocketThread/Receiver)
08-30 22:57:05.497  6865  8735 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 22:57:05.497  6865  8735 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 918, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 22:57:07.560  1590  1590 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 22:57:07.577  1037  1413 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 22:57:07.679  1037  1104 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8736 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 22:57:07.693  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 22:57:07.701  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 22:57:07.702  2079  2079 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 22:57:07.710  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 22:57:07.714  1037  1037 D administrator: Handling package changes for user 0
,08-30 22:57:07.752  8736  8736 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 22:57:07.826  8736  8736 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:57:07.826  8736  8736 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:57:07.835  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 22:57:07.835  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 22:57:07.875  1037  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 22:57:07.880  1037  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 22:57:07.885  2079  2079 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 22:57:07.887  2455  2455 V GmsNetworkLocationProvi: DISABLE
,08-30 22:57:07.913  1037  1102 D LocationProviderProxy: applying state to connected service
08-30 22:57:07.914  2455  2455 E GCoreFlp: Bound FusedProviderService with LocationManager
08-30 22:57:07.955  8736  8781 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 22:57:07.955  8736  8781 I Babel   : MmsConfig.loadMmsSettings
,08-30 22:57:07.959  8736  8781 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 22:57:07.959  8736  8781 I Babel   : MmsConfig.loadFromDatabase
,08-30 22:57:07.976  8736  8781 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 22:57:07.976  8736  8781 I Babel   : MmsConfig.loadFromResources
08-30 22:57:07.980  8736  8781 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 22:57:07.981  8736  8781 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 22:57:07.995  8736  8736 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:57:08.022  8736  8780 W AudioCapabilities: Unsupported mime audio/evrc
08-30 22:57:08.024  8736  8780 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 22:57:08.028  8736  8780 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 22:57:08.036  1826  8785 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 22:57:08.037  1826  8785 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-30 22:57:08.042  7227  7227 I AppUp4:CustModeStarterReceiver: onReceive
08-30 22:57:08.047  7227  7227 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1a20d0ef
08-30 22:57:08.048  7227  7227 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 22:57:08.048  7227  7227 D AppUp4:CustFacade: isPhone : true
08-30 22:57:08.048  7227  7227 D AppUp4:CustModeStarterReceiver: begin check event
08-30 22:57:08.048  7227  7227 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-30 22:57:08.059  8736  8780 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 22:57:08.061  1826  5211 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 22:57:08.063  8736  8780 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 22:57:08.065  8736  8780 W AudioCapabilities: Unsupported mime audio/evrc
08-30 22:57:08.075  8736  8780 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 22:57:08.077  8736  8780 W VideoCapabilities: Unsupported mime video/divx
,08-30 22:57:08.083  8736  8780 W VideoCapabilities: Unsupported mime video/divx311
08-30 22:57:08.085  8736  8780 W VideoCapabilities: Unsupported mime video/divx4
08-30 22:57:08.099  8736  8780 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 22:57:08.108  1037  2098 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8788 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 22:57:08.112  1037  2019 I ActivityManager: Killing 8316:com.lge.bnr/1000 (adj 15): empty #17
,08-30 22:57:08.136  8736  8780 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 22:57:08.140  8736  8780 W AudioCapabilities: Unsupported mime audio/eac3
08-30 22:57:08.141  8736  8780 W AudioCapabilities: Unsupported mime audio/ac3
08-30 22:57:08.142  8736  8780 W AudioCapabilities: Unsupported mime audio/g726
08-30 22:57:08.143  8736  8780 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 22:57:08.143  8736  8780 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 22:57:08.145  8736  8780 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 22:57:08.146  8736  8780 W VideoCapabilities: Unsupported mime video/theora
08-30 22:57:08.148  8736  8780 W VideoCapabilities: Unsupported mime video/mjpg
,08-30 22:57:08.185  1037  1952 W libprocessgroup: failed to open /acct/uid_1000/pid_8316/cgroup.procs: No such file or directory
,08-30 22:57:08.212  8788  8788 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:57:08.213  8788  8788 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 22:57:08.213  8788  8788 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 22:57:08.215  8788  8788 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 22:57:08.215  8788  8788 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 22:57:08.282  8788  8788 I SystemConfig: BUILD Country: EU
08-30 22:57:08.282  8788  8788 I SystemConfig: BUILD Operator: OPEN
,08-30 22:57:08.314  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=14.4, 0.0, 0.0  rx=12.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-583154214] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 22:57:08.314  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=14.4, 0.0, 0.0  rx=12.3 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-583154214] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:57:08.314  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 22:57:08.358  1037  2098 I ActivityManager: Killing 8289:com.lge.sync/1000 (adj 15): empty #17
,08-30 22:57:08.481  6865  6924 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 927)
08-30 22:57:08.485  6865  6924 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 22:57:08.485  6865  6924 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 928)
08-30 22:57:08.496  1037  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_8289/cgroup.procs: No such file or directory
08-30 22:57:08.503  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 22:57:08.503  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14d1a4e1 added. We now have 3 listener(s)
08-30 22:57:08.507  8788  8806 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 22:57:08.508  8788  8806 I SystemConfig: existFile = false
08-30 22:57:08.509  8788  8806 I SystemConfig: canReadFile = false
08-30 22:57:08.509  8788  8806 I SystemConfig: systemFeature RCS result false
08-30 22:57:08.509  8788  8806 D SystemConfig: refreshRcsSupport() :false
08-30 22:57:08.556  1037  1367 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8811 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 22:57:08.560  1037  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:57:08.568  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 22:57:08.568  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:57:08.568  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:57:08.568  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:57:08.569  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2485f206 added. We now have 4 listener(s)
08-30 22:57:08.569  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:57:08.569  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:57:08.575  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:57:08.581   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 473us total 23.124ms
08-30 22:57:08.588  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:57:08.588  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:57:08.588  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:57:08.588  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:57:08.588  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:57:08.588  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:08.588  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:57:08.588  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:57:08.591  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:08.591  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:57:08.592  6865  6924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:57:08.592  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:57:08.592  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:57:08.592  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:57:08.592  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:08.592  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:57:08.592  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:57:08.593  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14d1a4e1 removed from the list
08-30 22:57:08.593  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:08.593  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2485f206 removed from the list
08-30 22:57:08.596  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:57:08.600  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:57:08.600  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:57:08.600  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:08.601  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:08.601  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:08.602  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:08.602  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:57:08.602  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:08.603  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2485f206 not in the list
08-30 22:57:08.603  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:08.603  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:08.603   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 20.575ms
08-30 22:57:08.607  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:57:08.607  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:08.607  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:08.607  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2485f206 not in the list
08-30 22:57:08.607  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:57:08.607  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:08.607  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:08.607  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14d1a4e1 not in the list
08-30 22:57:08.608  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:57:08.608  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@162ff6f4 added. We now have 3 listener(s)
08-30 22:57:08.611  1037  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:57:08.615  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 22:57:08.615  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:57:08.615  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:57:08.615  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:57:08.615  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@462ae1d added. We now have 4 listener(s)
08-30 22:57:08.615  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:57:08.615  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:57:08.617  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:57:08.624   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 20.011ms
,08-30 22:57:08.627  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:57:08.627  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:57:08.627  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:57:08.627  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:57:08.627  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:57:08.627  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:08.627  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:57:08.627  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:57:08.628  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:08.629  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:57:08.629  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:57:08.629  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:57:08.629  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:57:08.629  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:57:08.629  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 22:57:08.632  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:57:08.632  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 22:57:08.633  1037  2021 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:57:08.633  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:57:08.637  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 22:57:08.638  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 22:57:08.639  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 22:57:08.640  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:57:08.641  6865  6924 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 22:57:08.641  8811  8811 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:57:08.641  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:57:08.641  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:57:08.642  8811  8811 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 22:57:08.642  8811  8811 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 22:57:08.642  8811  8811 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 22:57:08.763  8811  8811 I AppConfig: Total System Memory = 2995761152
,08-30 22:57:08.774  8811  8811 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 22:57:08.871  1037  1906 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8835 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 22:57:08.873  1037  1906 I ActivityManager: Killing 7021:com.android.settings/1000 (adj 15): empty #17
08-30 22:57:08.935  1037  1953 W libprocessgroup: failed to open /acct/uid_1000/pid_7021/cgroup.procs: No such file or directory
,08-30 22:57:09.146  8835  8835 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 22:57:09.264  8835  8835 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 22:57:09.266  8835  8835 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 22:57:09.337  8835  8835 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 22:57:09.363  8835  8835 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 22:57:09.367  8835  8835 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 22:57:09.390  8835  8835 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 22:57:09.390  8835  8835 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 22:57:09.409  1037  1906 I ActivityManager: Killing 8487:com.lge.email/u0a23 (adj 15): empty #17
,08-30 22:57:09.479  1037  1953 W libprocessgroup: failed to open /acct/uid_10023/pid_8487/cgroup.procs: No such file or directory
,08-30 22:57:09.493  5031  8882 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 22:57:09.538  1037  2021 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8885 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 22:57:09.657  1037  1985 I art     : Explicit concurrent mark sweep GC freed 38561(1964KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.548ms total 152.327ms
,08-30 22:57:09.663  2833  2936 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 22:57:09.665  2833  2936 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@33d83fd5 on behalf of 8835
08-30 22:57:09.696  8835  8835 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 22:57:09.711  8835  8835 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 22:57:09.736  8885  8885 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 22:57:09.756  8885  8885 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 22:57:09.756  8885  8885 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 22:57:09.756  8885  8885 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 22:57:09.756  8885  8885 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 22:57:09.756  8885  8885 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 22:57:09.756  8885  8885 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 22:57:09.768  1037  1053 I ActivityManager: Killing 8267:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 22:57:09.870  1037  1953 W libprocessgroup: failed to open /acct/uid_10026/pid_8267/cgroup.procs: No such file or directory
,08-30 22:57:10.133  1037  1985 V SIM_STK : Menu title from STK is T-Mobile
,08-30 22:57:10.147  5031  8882 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 654 ms] updated apps [took 654 ms] 
,08-30 22:57:11.334  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=7.2, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-583151195] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 22:57:11.346  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=7.2, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-583151184] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 22:57:11.346  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 22:57:11.643  6865  6924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:57:11.643  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:57:11.643  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 22:57:11.656  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:57:11.656  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:11.656  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:57:11.656  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:57:11.656  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@162ff6f4 removed from the list
08-30 22:57:11.656  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:11.656  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@462ae1d removed from the list
08-30 22:57:11.656  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:57:11.656  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:11.657  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:11.657  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:11.660  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:11.660  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:57:11.661  6865  6924 D BluetoothLeScanner: could not find callback wrapper
08-30 22:57:11.661  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 22:57:11.661  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:11.661  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@462ae1d not in the list
08-30 22:57:11.661  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:11.662  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:11.663  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:57:11.663  6865  6924 D BluetoothLeScanner: could not find callback wrapper
08-30 22:57:11.663  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 22:57:11.663  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:11.663  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:11.663  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@462ae1d not in the list
08-30 22:57:11.663  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:57:11.663  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:11.663  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:11.664  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@162ff6f4 not in the list
08-30 22:57:11.664  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:57:11.665  6865  ,6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20010f19 added. We now have 3 listener(s)
,08-30 22:57:11.669  1037  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:57:11.673  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 22:57:11.673  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:57:11.673  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:57:11.674  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:57:11.674  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39633bde added. We now have 4 listener(s)
08-30 22:57:11.674  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:57:11.675  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:57:11.678  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:57:11.684  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:57:11.684  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:57:11.684  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:57:11.684  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:57:11.684  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:57:11.684  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:11.684  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:57:11.684  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:57:11.687  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:11.687  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:57:11.689  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:57:11.691  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:57:11.693  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 22:57:11.695  6865  6924 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 22:57:11.695  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 22:57:11.698  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 22:57:11.698  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 22:57:11.698  6865  6924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 22:57:11.698  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:57:11.703  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 22:57:11.703  6865  6924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 22:57:11.703  6865  6924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 22:57:11.706  6865  6865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 22:57:11.708  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 22:57:11.708  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 22:57:11.708  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:57:11.708  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 22:57:11.712  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 22:57:11.714  1037  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:57:11.719  1037  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 22:57:11.723  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 22:57:11.724  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 22:57:11.725  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 22:57:11.727  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 22:57:11.728  6865  6924 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 22:57:11.730  6865  8913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 22:57:11.732  8076  8191 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
,08-30 22:57:11.734  6865  8913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 22:57:14.366  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-583148162] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:57:14.369  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-583148159] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 22:57:14.370  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 22:57:14.736  6865  6924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:57:14.736  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:57:14.736  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 22:57:14.736  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 22:57:14.736  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 22:57:14.736  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 22:57:14.744  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:57:14.744  6865  6924 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 22:57:14.745  6865  8913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 22:57:14.745  6865  8913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 22:57:14.745  6865  8913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 22:57:14.746  6865  6865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 22:57:14.748  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 22:57:14.748  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:14.748  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:57:14.752  6865  6865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:57:14.752  6865  6865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 22:57:14.752  6865  6865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 22:57:14.757  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:57:14.757  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:14.757  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:57:14.757  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:57:14.757  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20010f19 removed from the list
08-30 22:57:14.757  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:14.757  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39633bde removed from the list
08-30 22:57:14.757  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:57:14.758  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:14.759  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:14.759  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:57:14.760  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:14.760  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:57:14.761  6865  6924 D BluetoothLeScanner: could not find callback wrapper
08-30 22:57:14.761  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 22:57:14.761  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 22:57:14.761  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39633bde not in the list
08-30 22:57:14.761  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:14.761  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:14.762  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:57:14.762  6865  6924 D BluetoothLeScanner: could not find callback wrapper
08-30 22:57:14.762  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 22:57:14.763  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:14.763  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:14.763  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39633bde not in the list
08-30 22:57:14.763  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 22:57:14.763  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:14.763  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:14.763  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20010f19 not in the list
08-30 22:57:14.764  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:57:14.764  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2be337ea added. We now have 3 listener(s)
08-30 22:57:14.765  1037  2072 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:57:14.768  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 22:57:14.768  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:57:14.768  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:57:14.768  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:57:14.768  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13c44adb added. We now have 4 listener(s)
08-30 22:57:14.768  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:57:14.779  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:57:14.783  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:57:14.788  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:57:14.788  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:57:14.788  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:57:14.788  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:57:14.788  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:57:14.788  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:14.788  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:57:14.788  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 22:57:14.791  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:14.791  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:57:14.793  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:57:14.795  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:57:14.797  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:57:14.797  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:57:14.797  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:57:14.797  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:57:14.797  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 22:57:14.801  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 22:57:14.803  1037  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:57:14.808  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 22:57:14.809  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 22:57:14.811  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 22:57:14.812  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:57:14.813  6865  6924 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 22:57:17.396  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-583145132] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 22:57:17.399  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-583145129] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 22:57:17.399  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 22:57:17.822  6865  6924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 22:57:17.822  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 22:57:17.822  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 22:57:17.833  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 22:57:17.833  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:17.833  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:57:17.833  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:57:17.833  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2be337ea removed from the list
08-30 22:57:17.833  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:17.833  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13c44adb removed from the list
08-30 22:57:17.833  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:57:17.834  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:17.836  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:17.837  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:17.842  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:17.842  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 22:57:17.848  6865  6924 D BluetoothLeScanner: could not find callback wrapper
08-30 22:57:17.848  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 22:57:17.848  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:17.848  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13c44adb not in the list
08-30 22:57:17.848  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:17.848  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:17.849  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:57:17.850  6865  6924 D BluetoothLeScanner: could not find callback wrapper
08-30 22:57:17.850  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 22:57:17.850  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:17.850  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:17.850  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13c44adb not in the list
08-30 22:57:17.850  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:57:17.850  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:17.850  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:17.850  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2be337ea not in the list
08-30 22:57:17.851  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:57:17.851  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b2b9b7 added. We now have 3 listener(s)
08-30 22:57:17.853  1037  1636 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 22:57:17.856  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 22:57:17.856  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:57:17.856  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:57:17.857  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:57:17.857  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15390524 added. We now have 4 listener(s)
08-30 22:57:17.857  6865  6924 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:57:17.860  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:57:17.864  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:57:17.870  6865  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:57:17.870  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:57:17.870  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 22:57:17.870  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:57:17.870  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:57:17.870  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:17.870  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:57:17.870  6865  6924 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 22:57:17.873  6865  6924 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:57:17.873  6865  6924 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:57:17.877  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:57:17.880  6865  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:57:17.881  6865  6924 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:57:17.881  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:57:17.881  6865  6924 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 22:57:17.883  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:57:17.883  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:17.883  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:57:17.884  6865  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:57:17.884  6865  6924 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b2b9b7 removed from the list
08-30 22:57:17.884  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:17.884  6865  6924 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15390524 removed from the list
08-30 22:57:17.884  6865  6924 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:57:17.884  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:17.885  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:17.885  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:17.886  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:17.886  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:57:17.886  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:17.886  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15390524 not in the list
08-30 22:57:17.886  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:17.886  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:17.887  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:57:17.887  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:57:17.887  6865  6924 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:57:17.887  6865  6924 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15390524 not in the list
08-30 22:57:17.887  6865  6924 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:57:17.887  6865  6924 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:57:17.887  6865  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:57:17.888  6865  6924 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b2b9b7 not in the list
08-30 22:57:17.889  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 22:57:17.889  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 22:57:17.889  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity:, RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 22:57:17.889  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:57:17.889  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 22:57:17.890  6865  6924 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 22:57:19.911  6865  8914 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 937, name: My test thread name)
,08-30 22:57:20.424  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-583142105] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 22:57:20.434  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2437 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-583142095] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 22:57:20.434  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 22:57:21.907  6865  6924 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 937
08-30 22:57:21.907  6865  6924 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 937, name: My test thread name)
,08-30 22:57:21.926  6865  8915 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 938, name: My test thread name)
08-30 22:57:21.926  6865  8915 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 938, thread name: My test thread name)
08-30 22:57:21.926  6865  8915 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 938, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 22:57:21.929  6865  6924 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 22:57:21.935  6865  8916 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 942, name: My test thread name)
08-30 22:57:21.936  6865  8916 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 942, thread name: My test thread name): Test exception.
08-30 22:57:21.936  6865  8916 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 942, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-30 22:57:21.939  6865  6924 I jxcore-log: Total number of executed tests:  82
08-30 22:57:21.939  6865  6924 I jxcore-log: 
08-30 22:57:21.940  6865  6924 I jxcore-log: Number of passed tests:  82
08-30 22:57:21.940  6865  6924 I jxcore-log: 
08-30 22:57:21.940  6865  6924 I jxcore-log: Number of failed tests:  0
08-30 22:57:21.940  6865  6924 I jxcore-log: 
08-30 22:57:21.941  6865  6924 I jxcore-log: Number of ignored tests:  0
08-30 22:57:21.941  6865  6924 I jxcore-log: 
08-30 22:57:21.941  6865  6924 I jxcore-log: Total duration:  111597
08-30 22:57:21.941  6865  6924 I jxcore-log: 
08-30 22:57:21.942  6865  6924 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 22:57:21.942  6865  6924 I jxcore-log: 
08-30 22:57:21.943  6865  6924 I jxcore-log: My device name is: LGE-LG-D855
08-30 22:57:21.943  6865  6924 I jxcore-log: 
08-30 22:57:21.949  6865  6924 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 22:57:21.949  6865  6924 I jxcore-log: 
,08-30 22:57:21.964  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:21.964  6865  6924 I jxcore-log: 
,08-30 22:57:21.971  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:21.971  6865  6924 I jxcore-log: 
08-30 22:57:21.973  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:21.973  6865  6924 I jxcore-log: 
08-30 22:57:21.978  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:21.978  6865  6924 I jxcore-log: 
08-30 22:57:21.981  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:21.981  6865  6924 I jxcore-log: 
08-30 22:57:21.983  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 22:57:21.983  6865  6924 I jxcore-log: 
,08-30 22:57:21.987  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:21.987  6865  6924 I jxcore-log: 
08-30 22:57:21.989  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:21.989  6865  6924 I jxcore-log: 
08-30 22:57:21.990  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 22:57:21.990  6865  6924 I jxcore-log: 
08-30 22:57:21.990  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 22:57:21.990  6865  6924 I jxcore-log: 
08-30 22:57:21.992  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 22:57:21.992  6865  6924 I jxcore-log: 
08-30 22:57:21.993  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:57:21.993  6865  6924 I jxcore-log: 
08-30 22:57:21.994  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:57:21.994  6865  6924 I jxcore-log: 
08-30 22:57:21.995  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:57:21.995  6865  6924 I jxcore-log: 
08-30 22:57:21.996  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 22:57:21.996  6865  6924 I jxcore-log: 
08-30 22:57:21.997  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 22:57:21.997  6865  6924 I jxcore-log: 
08-30 22:57:21.998  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 22:57:21.998  6865  6924 I jxcore-log: 
08-30 22:57:21.999  6865  8914 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 937, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,08-30 22:57:22.004  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.004  6865  6924 I jxcore-log: 
08-30 22:57:22.005  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.005  6865  6924 I jxcore-log: 
08-30 22:57:22.006  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.006  6865  6924 I jxcore-log: 
08-30 22:57:22.006  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.006  6865  6924 I jxcore-log: 
08-30 22:57:22.007  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.007  6865  6924 I jxcore-log: 
08-30 22:57:22.008  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.008  6865  6924 I jxcore-log: 
08-30 22:57:22.009  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.009  6865  6924 I jxcore-log: 
08-30 22:57:22.009  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.009  6865  6924 I jxcore-log: 
08-30 22:57:22.010  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.010  6865  6924 I jxcore-log: 
08-30 22:57:22.011  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.011  6865  6924 I jxcore-log: 
08-30 22:57:22.012  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.012  6865  6924 I jxcore-log: 
08-30 22:57:22.012  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.012  6865  6924 I jxcore-log: 
08-30 22:57:22.013  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.013  6865  6924 I jxcore-log: 
08-30 22:57:22.014  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.014  6865  6924 I jxcore-log: 
08-30 22:57:22.015  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:57:22.015  6865  6924 I jxcore-log: 
08-30 22:57:22.016  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 22:57:22.016  6865  6924 I jxcore-log: 
,08-30 22:57:22.021  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 22:57:22.021  6865  6924 I jxcore-log: 
08-30 22:57:22.022  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.022  6865  6924 I jxcore-log: 
08-30 22:57:22.022  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.022  6865  6924 I jxcore-log: 
08-30 22:57:22.023  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.023  6865  6924 I jxcore-log: 
08-30 22:57:22.034  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.034  6865  6924 I jxcore-log: 
08-30 22:57:22.035  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.035  6865  6924 I jxcore-log: 
08-30 22:57:22.036  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.036  6865  6924 I jxcore-log: 
08-30 22:57:22.037  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.037  6865  6924 I jxcore-log: 
08-30 22:57:22.038  6865  6924 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:57:22.038  6865  6924 I jxcore-log: 
,08-30 22:57:22.251  8917  8917 D AndroidRuntime: 
08-30 22:57:22.251  8917  8917 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 22:57:22.254  8917  8917 D AndroidRuntime: CheckJNI is OFF
,08-30 22:57:22.377  8917  8917 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 22:57:22.386  1037  1104 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-30 22:57:22.386  1037  1104 I ActivityManager: Killing 6865:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-30 22:57:22.442  1037  1985 I WindowState: WIN DEATH: Window{7be3a6c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 22:57:22.444  1037  1531 D WifiService: Client connection lost with reason: 4
08-30 22:57:22.449  1037  1985 D InputDispatcher: Window went away: Window{7be3a6c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 22:57:22.647  1037  1104 I ActivityManager:   Force finishing activity ActivityRecord{1aef27d1 u0 com.test.thalitest/.MainActivity t6}
,08-30 22:57:22.694   341   352 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 22:57:22.700  1037  1953 W ActivityManager: Spurious death for ProcessRecord{f148201 6865:com.test.thalitest/u0a118}, curProc for 6865: null
08-30 22:57:22.701  2079  2079 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 22:57:22.703  2079  2079 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 22:57:22.705  2079  2079 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 22:57:22.708  2079  2160 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,08-30 22:57:22.716  1916  1916 D ActionManagerService: notifyUserLog: 1000003
08-30 22:57:22.717  3748  4921 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 22:57:22.718  2079  2079 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 22:57:22.719  2079  2079 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 22:57:22.721  2079  2079 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-30 22:57:22.726  2079  2079 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 22:57:22.730  1916  1916 D ActionManagerService: notifyUserLog: 1000004
08-30 22:57:22.731  3748  4921 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 22:57:22.733  2079  2079 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-30 22:57:22.736  3748  3764 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , expire_time: 0
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , display: false
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , animation: false }
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , expire_time: 0
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , display: false
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , animation: false }
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , expire_time: 0
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , display: false
08-30 22:57:22.739  2079  2079 I GBoardWebViewUtils: , animation: false }
08-30 22:57:22.746  1954  4424 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 22:57:22.746  1954  4424 D SplitWindowPolicy: topRunningActivity=ActivityInfo{166e9a38 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-30 22:57:22.750  1954  1969 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 22:57:22.750  1954  1969 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f64ea11 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 22:57:22.763  2079  8949 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-30 22:57:22.779  2079  2079 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-30 22:57:22.802  8614  8614 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 22:57:22
,08-30 22:57:22.839  8614  8614 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 22:57:22.839  8614  8614 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 22:57:22.845  8614  8614 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 22:57:22.847  1037  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 22:57:22.864  8614  8614 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 22:57:22.865  8614  8614 D Weather.Utils: 2 : All the weather widget is gone.
08-30 22:57:22.866  8614  8614 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 22:57:22
,08-30 22:57:22.904  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 22:57:22.911  1037  1413 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 22:57:22.912  2455  2601 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 22:57:22.915  2026  2026 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 22:57:22.916  3748  3748 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 22:57:22.918  8076  8076 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 22:57:22.918  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 22:57:22.922  4932  4932 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 22:57:22.923  4932  4932 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 22:57:22.923  4932  4932 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 22:57:22.923  4932  4932 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 22:57:22.924  4932  4932 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 22:57:22.924  4932  4932 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 22:57:22.924  4932  4932 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 22:57:22.924  4932  4932 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 22:57:22.926  8334  8334 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 22:57:22.927  4932  4932 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:57:22.927  4932  4932 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:57:22.927  4932  4932 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 22:57:22.927  4932  4932 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 22:57:22.938  1037  1102 W InputMethodInfo: Duplicated subtype definition found: , voice
08-30 22:57:22.939  1037  2342 V SIM_STK : Menu title from STK is T-Mobile
08-30 22:57:22.955  5031  5031 I art     : Explicit concurrent mark sweep GC freed 15416(883KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 303us total 68.110ms
,08-30 22:57:22.977  2079  2079 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-30 22:57:22.981  1590  1590 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-30 22:57:22.982  1826  1826 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 22:57:22.982  1590  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 22:57:22.982  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:22.985  1590  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 22:57:22.985  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:22.995  1590  1590 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,08-30 22:57:22.996  1590  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 22:57:22.996  1590  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:57:22.996  1590  1641 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 22:57:22.998  1590  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 22:57:23.003  1590  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 22:57:23.003  1590  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 22:57:23.006  2247  2247 I ConfigService: onCreate
08-30 22:57:23.006  2247  2247 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 22:57:23.007  1590  1590 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 22:57:23.010  1590  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 22:57:23.010  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:23.013  1826  1826 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-30 22:57:23.016  2247  2247 I ConfigService: onBind returning update interface
08-30 22:57:23.024  1590  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 22:57:23.024  1590  1641 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 22:57:23.025  1590  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 22:57:23.025  1590  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 22:57:23.025  1037  1037 I art     : Explicit concurrent mark sweep GC freed 18046(1146KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.392ms total 129.959ms
,08-30 22:57:23.032  1037  2021 V SIM_STK : Menu title from STK is T-Mobile
08-30 22:57:23.032  1037  2021 V SIM_STK : Menu title from STK is T-Mobile
08-30 22:57:23.033  2247  2247 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 22:57:23.033  2247  2247 I ConfigService: onBind returning config service
08-30 22:57:23.034  1590  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 22:57:23.034  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:23.042  1590  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:57:23.043  1590  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 22:57:23.043  1590  1641 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-30 22:57:23.043  1590  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 22:57:23.048  1881  1881 D SplitUIManager: split_name #11 / not available #0
08-30 22:57:23.049  1590  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 22:57:23.049  1590  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 22:57:23.049  1881  1881 D SplitUIService: removed split : 
08-30 22:57:23.052  1590  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 22:57:23.052  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:23.066  2247  2247 I ConfigService: onDestroy
,08-30 22:57:23.070  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-30 22:57:23.070  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 22:57:23.075  1590  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 22:57:23.075  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:23.077  1881  1881 D SplitUIManager: split_name #11 / not available #0
08-30 22:57:23.077  1881  1881 I SplitUIService: split app #11
08-30 22:57:23.078  1590  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 22:57:23.078  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:23.078  1826  8971 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 22:57:23.079  1590  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 22:57:23.079  1590  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-30 22:57:23.080  1590  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 22:57:23.080  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:23.083  2079  2079 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 22:57:23.086  1590  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 22:57:23.086  1590  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 22:57:23.087  1590  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 22:57:23.087  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:23.088  1590  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 22:57:23.088  1590  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 22:57:23.090  1037  1952 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 22:57:23.090  8076  8076 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-30 22:57:23.092  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 22:57:23.092  1590  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 22:57:23.092  1590  1641 D KeyguardModel: createShortcutInfo...
08-30 22:57:23.094  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 22:57:23.095  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 22:57:23.096  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 22:57:23.097  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-30 22:57:23.108  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b83afba u0 com.lge.launcher2/.Launcher t5} time:287714
08-30 22:57:23.110  1037  1037 D administrator: Handling package changes for user 0
08-30 22:57:23.112  2079  2079 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 22:57:23.114  2079  2079 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 22:57:23.114  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 22:57:23.117  1037  2342 V SIM_STK : Menu title from STK is T-Mobile
08-30 22:57:23.124  2079  2295 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 22:57:23.124  2079  2295 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 22:57:23.125  1590  1590 D KeyguardModel: handleShortcutListChanged...
08-30 22:57:23.125  1590  1590 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 22:57:23.130  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 22:57:23.130  2079  2079 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 22:57:23.131  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 22:57:23.138  2079  2079 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-30 22:57:23.139   325   416 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 22:57:23.140  2666  2666 D [Concierge]Service: onStartCommand(). Type : 8
08-30 22:57:23.140  2666  2666 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 22:57:23.140  3259  8980 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 22:57:23.140  2666  2666 D [Concierge]Service: Update widget ID : 11
08-30 22:57:23.143  2079  2079 D [Concierge]WidgetView: change position of spinner
08-30 22:57:23.144  2079  2079 I [Concierge]WidgetView: initWebView(). Time : 1472590643144
08-30 22:57:23.144  2666  2666 D [Concierge]Service: onStartCommand(). Type : 0
08-30 22:57:23.157  1826  8981 I PeopleContactsSync: CP2 sync disabled
,08-30 22:57:23.160  5839  8978 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 22:57:23.182  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 22:57:23.182  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 22:57:23.182  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 22:57:23.185  1037  1565 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 22:57:23.185  1826  5706 I art     : Explicit concurrent mark sweep GC freed 59684(3MB) AllocSpace objects, 26(416KB) LOS objects, 51% free, 29MB/61MB, paused 1.506ms total 49.859ms
08-30 22:57:23.190  2079  2079 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 167764610
08-30 22:57:23.191  2079  2079 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 22:57:23.191  2079  2079 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 22:57:23.192  1826  5211 I Icing   : doRemovePackageData com.test.thalitest
08-30 22:57:23.193  2079  2079 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@20b6a002
08-30 22:57:23.193  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 22:57:23.194  2079  2079 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-30 22:57:23.194  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 22:57:23.199  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 22:57:23.200  2079  2079 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 22:57:23.200  2079  2079 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472590383508, New one : 1472590643144
08-30 22:57:23.200  2079  2079 D [Concierge]WidgetView: Unregister all receivers
08-30 22:57:23.200  2079  2079 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 22:57:23.201  2079  2079 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 22:57:23.201  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 22:57:23.202  1826  8977 W GmsApplication: Using Auth Proxy for data requests.
08-30 22:57:23.202  7227  7227 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-30 22:57:23.203  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 22:57:23.205  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 22:57:23.206  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 22:57:23.207  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 22:57:23.208  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 22:57:23.209  1826  8977 W GmsApplication: Using Auth Proxy for data requests.
,08-30 22:57:23.219  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 22:57:23.219  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 22:57:23.222  2191  8984 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 22:57:23.238  1037  2077 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8985 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 22:57:23.272  2079  2079 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 22:57:23.279  2079  2079 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 22:57:23.280  2079  2079 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 22:57:23.283  2079  2079 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 22:57:23.301  2079  2079 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1de9f79f time:287907
,08-30 22:57:23.313  8985  8985 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:57:23.313  8985  8985 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 22:57:23.314  8985  8985 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 22:57:23.315  8985  8985 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 22:57:23.350  1037  1125 I art     : Explicit concurrent mark sweep GC freed 10941(737KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.832ms total 320.537ms
,08-30 22:57:23.362  8985  8985 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 22:57:23.370  8985  8985 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 22:57:23.392  8985  8985 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 22:57:23.402  1037  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:57:23.414  8917  8917 D AndroidRuntime: Shutting down VM
08-30 22:57:23.416  1037  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 22:57:23.424  8985  8985 D LgDataFeature: LgDataFeature() Constructor: none
08-30 22:57:23.424  8985  8985 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 22:57:23.433  1037  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=9005 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 22:57:23.435  2079  2079 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 22:57:23.443  2079  2079 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 22:57:23.454  1037  1526 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-583139074] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 22:57:23.455  1037  1526 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-583139073] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 22:57:23.455  1037  1526 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 22:57:23.483  1037  1906 I ActivityManager: Killing 8553:com.android.chrome/u0a57 (adj 15): empty #17
08-30 22:57:23.498  2079  2929 I GBoardtInterface: onReloaded()
,08-30 22:57:23.499  2079  2079 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 22:57:23.555  1037  1934 W libprocessgroup: failed to open /acct/uid_10057/pid_8553/cgroup.procs: No such file or directory
,08-30 22:57:23.558  3748  3763 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 22:57:23.560  3748  4029 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 22:57:23.564  8985  8985 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-30 22:57:23.566  1916  1916 D ActionManagerService: notifyUserLog: 1000001
,08-30 22:57:23.567  3748  4921 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 22:57:23.567  3748  4921 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 22:57:23.571  1916  1916 D ActionManagerService: notifyUserLog: 1000001
08-30 22:57:23.572  3748  4921 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 22:57:23.572  3748  4921 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 22:57:23.572  3748  4921 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 22:57:23.572  3748  4921 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 22:57:23.572  3748  3763 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 22:57:23.574  2079  2079 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 22:57:23.574  2079  2079 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 22:57:23.577  1037  2098 I ActivityManager: Killing 8577:com.lge.drmservice/u0a62 (adj 15): empty #17
08-30 22:57:23.577  2079  2079 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 22:57:23.577  2079  2079 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,08-30 22:57:23.579  2079  2079 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
,08-30 22:57:23.579  2079  2079 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 22:57:23.605  2026  2026 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 22:57:23.605  2026  2026 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-30 22:57:23.605  1037  2019 W libprocessgroup: failed to open /acct/uid_10062/pid_8577/cgroup.procs: No such file or directory
,08-30 22:57:23.607  2026  2026 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 22:57:23.609  8334  8334 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 22:57:23.639  1037  1367 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=9026 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 22:57:23.692  9026  9026 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 22:57:23.692  9026  9026 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: Unable to open database for writing.
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 22:57:23.693  9026  9026 E Lifetra,ckerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 22:57:23.693  9026  9026 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 22:57:23.705  9026  9026 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 22:57:23.705  9026  9026 W LG Account v2.2: No ProfileInfo entries
08-30 22:57:23.706  9026  9026 I LG Account v2.2: isEnabled: false
08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]Country: EU
,08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]Operator: OPEN
08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]Ranking support: false
08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]Comfort support: false
08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]Accessory: true
08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]Health device: true
08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]Extra Pedometer: false
08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]Blood glucose device: false
08-30 22:57:23.706  9026  9026 I Feature : [Lifetracker]Device Number: 3
08-30 22:57:23.707  9026  9026 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-30 22:57:23.735  1037  1934 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=9047 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a

```
