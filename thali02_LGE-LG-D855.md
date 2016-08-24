#### Test 79763830e108614_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-24 13:24:28.791  1035  2077 I art     : Explicit concurrent mark sweep GC freed 33815(1602KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 3.152ms total 161.937ms
,08-24 13:24:38.895  6772  6772 D AndroidRuntime: 
08-24 13:24:38.895  6772  6772 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 13:24:38.901  6772  6772 D AndroidRuntime: CheckJNI is OFF
08-24 13:24:39.102  6772  6772 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 13:24:39.113  1035  1956 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 13:24:39.128  1973  1990 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-24 13:24:39.134  1035  1956 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-24 13:24:39.135  1035  1956 D ActivityManager: setTaskToReturnTo : TaskRecord{39725e98 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 13:24:39.135  1035  1956 D ActivityManager: setTaskToReturnTo : TaskRecord{39725e98 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 13:24:39.137  1035  1956 D WindowStateEx: AppWindowTokenEx init.. 
08-24 13:24:39.138   339   362 E GBMv2   : DFP En is all cleared set to be enabled
08-24 13:24:39.166  1035  1956 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6787 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 13:24:39.169  6772  6772 D AndroidRuntime: Shutting down VM
08-24 13:24:39.224  1973  1991 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-24 13:24:39.224  1973  1991 D SplitWindowPolicy: topRunningActivity=ActivityInfo{f0953f0 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 13:24:39.226  1973  3963 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-24 13:24:39.227  1973  3963 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1a2c0d69 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 13:24:39.292  6787  6787 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-24 13:24:39.409  6787  6787 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 13:24:39.419  6787  6787 I LibraryLoader: Loading: webviewchromium
08-24 13:24:39.422  6787  6787 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1611-1615)
,08-24 13:24:39.422  6787  6787 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 13:24:39.459  6787  6787 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {18c66f1e}
08-24 13:24:39.460  6787  6787 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 13:24:39.461  6787  6787 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 13:24:39.473  6787  6787 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 13:24:39.475  6787  6787 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:24:39.489  6787  6787 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-24 13:24:39.490  6787  6787 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-24 13:24:39.491  6787  6787 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-24 13:24:39.493   316  1385 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-24 13:24:39.499  1035  1111 D BluetoothManagerService: Message: 20
08-24 13:24:39.500  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1322c662:true
08-24 13:24:39.516  6787  6787 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 13:24:39.516  6787  6787 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 13:24:39.516  6787  6787 I Adreno-EGL: Build Date: 12/12/14 금
08-24 13:24:39.516  6787  6787 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-24 13:24:39.516  6787  6787 I Adreno-EGL: Remote Branch: 
08-24 13:24:39.516  6787  6787 I Adreno-EGL: Local Patches: 
08-24 13:24:39.516  6787  6787 I Adreno-EGL: Reconstruct Branch: 
,08-24 13:24:39.603  6787  6826 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-24 13:24:39.609  6787  6787 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-24 13:24:39.631  6787  6787 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 13:24:39.636  6787  6787 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 13:24:39.639  6787  6787 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 13:24:39.642  6787  6787 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-24 13:24:39.642  6787  6787 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-24 13:24:39.654  6787  6787 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-24 13:24:39.661  6787  6787 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:24:39.661  6787  6787 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 13:24:39.700  6787  6842 D OpenGLRenderer: Render dirty regions requested: true
08-24 13:24:39.701  6787  6842 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 13:24:39.720  1035  1092 W ActivityManager: Activity pause timeout for ActivityRecord{1014c6f1 u0 com.test.thalitest/.MainActivity t6}
,08-24 13:24:39.722  6787  6842 D OpenGLRenderer: Enabling debug mode 0
08-24 13:24:39.733  6787  6787 D Atlas   : Validating map...
,08-24 13:24:39.743  1035  1986 D SplitWindow: check instance of lgWin Window{2b5e780c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 13:24:39.778  6787  6840 D LgDataFeature: LgDataFeature() Constructor: none
08-24 13:24:39.778  6787  6840 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 13:24:39.855  1035  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +636ms (total +716ms)
08-24 13:24:39.855  6787  6787 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5e2d885 time:162048
,08-24 13:24:39.858  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1014c6f1 u0 com.test.thalitest/.MainActivity t6} time:162051
08-24 13:24:39.957  6787  6787 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 13:24:39.990  6787  6787 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-24 13:24:39.990  6787  6787 I chromium: 
,08-24 13:24:40.009  6787  6840 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-24 13:24:40.009  6787  6840 I chromium: 
,08-24 13:24:40.136  6787  6852 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,08-24 13:24:40.152  6787  6852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 13:24:40.152  6787  6852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 13:24:40.152  6787  6852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 13:24:40.152  6787  6852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 13:24:40.152  6787  6852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 13:24:40.152  6787  6852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d302639 added. We now have 1 listener(s)
,08-24 13:24:40.159  1035  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 13:24:40.162  6787  6852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-24 13:24:40.164  6787  6852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-24 13:24:40.167  6787  6852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 13:24:40.167  6787  6852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-24 13:24:40.178  6787  6852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff60a2c added. We now have 1 listener(s)
08-24 13:24:40.178  6787  6852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 13:24:40.185  1035  1544 D WifiService: New client listening to asynchronous messages
,08-24 13:24:40.191  6787  6852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 13:24:40.191  6787  6852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 13:24:40.191  6787  6852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 13:24:40.192  6787  6852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 13:24:40.192  6787  6852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 13:24:40.196  6787  6852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 13:24:40.198  1035  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-24 13:24:40.202  6787  6852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-24 13:24:40.213  6787  6852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 13:24:40.214  6787  6852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:24:40.214  6787  6852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:24:40.214  6787  6852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 13:24:40.214  6787  6852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:24:40.214  6787  6852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:24:40.214  6787  6852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:24:40.214  6787  6852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:24:40.214  6787  6852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 13:24:40.215  6787  6852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 13:24:40.215  6787  6852 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 13:24:40.218  6787  6852 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 13:24:40.219  6787  6787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 13:24:40.221  6787  6787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 13:24:40.261  6787  6787 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 13:24:40.654   339   364 E GBMv2   : DFP En is all cleared set to be enabled
08-24 13:24:40.654   339   364 E GBMv2   : Set value is all cleared set the max
08-24 13:24:40.654   339   364 I GBMv2   : DFP Enabled. Ignore VFP set
,08-24 13:24:41.301  6787  6855 W jxcore-log: Initializing JXcore engine
08-24 13:24:41.301  6787  6855 W jxcore-log: JXcore engine is ready
,08-24 13:24:41.377  6855  6855 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10395]" dev="sockfs" ino=10395 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 13:24:41.377  6855  6855 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-24 13:24:41.377  6855  6855 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10589]" dev="sockfs" ino=10589 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 13:24:41.377  6855  6855 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-24 13:24:41.377  6855  6855 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33353]" dev="sockfs" ino=33353 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-24 13:24:41.415  6787  6855 W jxcore-log: Starting JXcore engine
,08-24 13:24:41.596  6787  6855 W jxcore-log: Platform android
08-24 13:24:41.596  6787  6855 W jxcore-log: 
08-24 13:24:41.596  6787  6855 W jxcore-log: Process ARCH arm
08-24 13:24:41.596  6787  6855 W jxcore-log: 
,08-24 13:24:41.998  6787  6855 I jxcore-log: JXcore Cordova bridge is ready!
08-24 13:24:41.998  6787  6855 I jxcore-log: 
08-24 13:24:41.998  6787  6855 W jxcore-log: JXcore engine is started
,08-24 13:24:42.009  6787  6852 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 13:24:42.014  6787  6787 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 13:24:52.673  6787  6855 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 13:24:52.673  6787  6855 I jxcore-log: 
,08-24 13:24:52.676  6787  6855 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 13:24:52.676  6787  6855 I jxcore-log: 
08-24 13:24:52.681  6787  6855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:24:52.681  6787  6855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:24:52.681  6787  6855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 13:24:52.681  6787  6855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:24:52.681  6787  6855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:24:52.681  6787  6855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:24:52.681  6787  6855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:24:52.681  6787  6855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 13:24:52.684  6787  6855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 13:24:52.687  6787  6855 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 13:24:52.687  6787  6855 I jxcore-log: 
,08-24 13:24:52.688  6787  6855 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 13:24:52.688  6787  6855 I jxcore-log: 
08-24 13:24:53.193  6787  6855 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-24 13:24:53.193  6787  6855 I jxcore-log: Failed to execute UT.
08-24 13:24:53.193  6787  6855 I jxcore-log: 
,08-24 13:24:53.195  6787  6855 I jxcore-log: Unit Test app is loaded
08-24 13:24:53.195  6787  6855 I jxcore-log: 
08-24 13:24:53.204  6787  6787 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 13:24:53.209  6787  6855 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 13:24:53.209  6787  6855 I jxcore-log: 
,08-24 13:24:53.218  6787  6855 I jxcore-log: My device name is: LGE-LG-D855
08-24 13:24:53.218  6787  6855 I jxcore-log: 
08-24 13:25:00.049  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:25:00.049  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:25:00.049  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:25:00.050  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
08-24 13:25:00.055  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:25:00.055  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:25:00.056  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
,08-24 13:25:00.058  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:25:00.436  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 13:25:00.436  6787  6855 I jxcore-log: 
,08-24 13:25:01.338  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 13:25:01.338  6787  6855 I jxcore-log: 
,08-24 13:25:01.363  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 13:25:01.363  6787  6855 I jxcore-log: 
,08-24 13:25:01.368  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 13:25:01.368  6787  6855 I jxcore-log: 
,08-24 13:25:01.383  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 13:25:01.383  6787  6855 I jxcore-log: 
,08-24 13:25:01.387  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 13:25:01.387  6787  6855 I jxcore-log: 
08-24 13:25:04.493  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 13:25:04.493  6787  6855 I jxcore-log: 
,08-24 13:25:04.507  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 13:25:04.507  6787  6855 I jxcore-log: 
,08-24 13:25:04.516  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 13:25:04.516  6787  6855 I jxcore-log: 
,08-24 13:25:04.671  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 13:25:04.671  6787  6855 I jxcore-log: 
,08-24 13:25:05.470  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 13:25:05.470  6787  6855 I jxcore-log: 
,08-24 13:25:05.714  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 13:25:05.714  6787  6855 I jxcore-log: 
,08-24 13:25:05.721  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 13:25:05.721  6787  6855 I jxcore-log: 
,08-24 13:25:05.907  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 13:25:05.907  6787  6855 I jxcore-log: 
,08-24 13:25:05.929  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 13:25:05.929  6787  6855 I jxcore-log: 
,08-24 13:25:05.934  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 13:25:05.934  6787  6855 I jxcore-log: 
,08-24 13:25:05.940  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 13:25:05.940  6787  6855 I jxcore-log: 
,08-24 13:25:05.954  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 13:25:05.954  6787  6855 I jxcore-log: 
,08-24 13:25:05.972  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 13:25:05.972  6787  6855 I jxcore-log: 
,08-24 13:25:06.052  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 13:25:06.052  6787  6855 I jxcore-log: 
,08-24 13:25:06.058  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 13:25:06.058  6787  6855 I jxcore-log: 
,08-24 13:25:06.083  6787  6855 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 13:25:06.083  6787  6855 I jxcore-log: 
,08-24 13:25:06.094  6787  6855 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-24 13:25:06.096  6787  6855 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-24 13:25:06.096  6787  6855 I jxcore-log: 
08-24 13:25:25.672  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:25:25.697  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1bcd1dc2 type 2 when 207850 com.google.android.gms} when 207850
,08-24 13:25:25.737  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:25:25.767  1842  1842 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-24 13:25:25.772  2239  2239 I ConfigService: onCreate
08-24 13:25:25.773  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 13:25:25.784  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
,08-24 13:25:25.792  1842  6887 I ConfigFetchService: running network task: configservice_periodic
08-24 13:25:25.794  1842  6887 I ConfigFetchService: launchTask
08-24 13:25:25.799  2239  2239 I ConfigService: onBind returning update interface
,08-24 13:25:25.802  1842  1842 I ConfigFetchService: service connected
08-24 13:25:25.802  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 13:25:25.802  2239  2239 I ConfigService: onBind returning config service
08-24 13:25:25.803  1842  1842 I ConfigClient: service connected
08-24 13:25:25.884  1035  1052 V SIM_STK : Menu title from STK is T-Mobile
,08-24 13:25:25.897  1842  2386 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-24 13:25:25.901   310  6906 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-24 13:25:25.901   310  6906 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-24 13:25:25.901   310  6906 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-24 13:25:26.248  1842  2386 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-24 13:25:26.253  1842  1842 I ConfigFetchService: fetch service done; releasing wakelock
08-24 13:25:26.258  1842  1842 I ConfigFetchService: stopping self
08-24 13:25:26.267  2239  2239 I ConfigService: onDestroy
,08-24 13:25:49.787  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{27b8007d type 2 when 224280 android} when 224280
,08-24 13:26:00.042  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:26:00.042  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:26:00.042  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:26:00.043  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:26:00.054  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:26:00.054  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:26:00.056  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:26:00.059  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:26:06.327  1601  1601 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:26:06.327  1601  1601 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:26:06.338  1973  2139 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:26:06.339  1973  2139 D LEDHandler: Battery Level Remaining: 100%
08-24 13:26:06.339  1973  2139 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-24 13:26:06.339  1601  1601 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
,08-24 13:26:06.342  1035  1544 D WifiController: battery changed pluggedType: 2
08-24 13:26:06.342  1601  1601 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:26:06.347  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:26:06.347  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:26:06.348  3870  3978 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:26:06.349  1601  1601 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:26:06.355  6635  6635 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 13:27:00.051  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:27:00.051  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:27:00.052  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:27:00.052  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:27:00.063  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:27:00.063  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:27:00.066  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:27:00.069  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:27:26.274  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:27:26.287  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{172c7b72 type 2 when 328452 com.google.android.gms} when 328452
,08-24 13:27:26.346  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:27:26.371  1842  1842 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-24 13:27:26.378  2239  2239 I ConfigService: onCreate
08-24 13:27:26.378  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 13:27:26.389  2239  2239 I ConfigService: onBind returning update interface
,08-24 13:27:26.392  1842  1842 I ConfigFetchService: service connected
08-24 13:27:26.392  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 13:27:26.392  2239  2239 I ConfigService: onBind returning config service
08-24 13:27:26.394  1842  1842 I ConfigClient: service connected
08-24 13:27:26.395  1842  6917 I ConfigFetchService: running network task: configservice_periodic
08-24 13:27:26.406  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
,08-24 13:27:26.411  1842  6917 I ConfigFetchService: launchTask
08-24 13:27:26.496  1035  1739 V SIM_STK : Menu title from STK is T-Mobile
,08-24 13:27:26.509  1842  4001 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-24 13:27:26.514   310  6936 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-24 13:27:26.515   310  6936 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-24 13:27:26.559   310  6936 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-24 13:27:26.799  1842  4001 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-24 13:27:26.803  1842  1842 I ConfigFetchService: fetch service done; releasing wakelock
08-24 13:27:26.806  1842  1842 I ConfigFetchService: stopping self
08-24 13:27:26.862  2239  2239 I ConfigService: onDestroy
,08-24 13:27:32.526  1035  3519 I LocationManagerService: remove 1c425493
08-24 13:27:32.528  1035  3519 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,08-24 13:27:32.534  1035  3519 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 13:27:32.535  1035  3519 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-24 13:27:32.539  1035  3519 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-24 13:27:32.541  1035  3519 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-24 13:28:00.004  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:28:00.053  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:28:00.069  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:28:00.070  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:28:00.070  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-24 13:28:00.073  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
08-24 13:28:00.075  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:28:00.075  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:28:00.076  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:28:00.078  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:28:00.125  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
,08-24 13:29:00.071  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:29:00.072  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:29:00.072  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:29:00.072  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:29:00.083  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:29:00.084  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:29:00.086  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:29:00.089  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:30:00.089  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:30:00.090  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:30:00.090  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:30:00.090  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:30:00.101  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:30:00.102  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:30:00.104  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:30:00.106  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:30:01.230  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:30:01.297  1035  1092 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6959 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-24 13:30:01.330  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:30:01.451  6959  6959 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-24 13:30:01.456  6959  6959 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@17faa0a3
08-24 13:30:01.457  1035  1999 I ActivityManager: Killing 6228:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-24 13:30:01.457  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
08-24 13:30:01.521  1035  2023 W libprocessgroup: failed to open /acct/uid_10014/pid_6228/cgroup.procs: No such file or directory
,08-24 13:31:00.107  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:31:00.107  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:31:00.107  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:31:00.107  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:31:00.112  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:31:00.113  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:31:00.114  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:31:00.114  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:31:07.131  1601  1601 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:31:07.132  1601  1601 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:31:07.156  1601  1601 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-24 13:31:07.156  1601  1601 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-24 13:31:07.159  1973  2139 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:31:07.159  1973  2139 D LEDHandler: Battery Level Remaining: 100%
08-24 13:31:07.159  1973  2139 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-24 13:31:07.160  1035  1544 D WifiController: battery changed pluggedType: 2
08-24 13:31:07.161  1601  1601 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:31:07.164  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:31:07.164  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:31:07.165  3870  3978 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:31:07.170  6635  6635 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 13:31:26.824  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:31:26.837  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{6af02ed type 2 when 569002 com.google.android.gms} when 569002
08-24 13:31:26.880  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:31:26.907  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
,08-24 13:31:26.944  1842  1842 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-24 13:31:26.950  2239  2239 I ConfigService: onCreate
08-24 13:31:26.951  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 13:31:26.954  1842  7003 I ConfigFetchService: running network task: configservice_periodic
08-24 13:31:26.957  1842  7003 I ConfigFetchService: launchTask
,08-24 13:31:26.968  2239  2239 I ConfigService: onBind returning update interface
08-24 13:31:26.969  1842  1842 I ConfigFetchService: service connected
,08-24 13:31:26.971  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 13:31:26.971  2239  2239 I ConfigService: onBind returning config service
08-24 13:31:26.973  1842  1842 I ConfigClient: service connected
08-24 13:31:27.062  1035  1741 V SIM_STK : Menu title from STK is T-Mobile
,08-24 13:31:27.075  1842  6506 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-24 13:31:27.081   310  7022 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-24 13:31:27.081   310  7022 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-24 13:31:27.082   310  7022 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-24 13:31:27.341  1842  6506 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-24 13:31:27.353  1842  1842 I ConfigFetchService: fetch service done; releasing wakelock
,08-24 13:31:27.355  1842  1842 I ConfigFetchService: stopping self
08-24 13:31:27.384  2239  2239 I ConfigService: onDestroy
,08-24 13:32:00.040  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:32:00.041  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:32:00.041  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:32:00.041  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:32:00.053  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:32:00.053  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:32:00.055  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:32:00.058  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:33:00.051  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:33:00.051  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:33:00.051  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:33:00.052  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:33:00.063  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:33:00.064  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:33:00.066  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:33:00.069  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:33:27.761  1601  1601 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:33:27.761  1601  1601 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:33:27.775  1035  1544 D WifiController: battery changed pluggedType: 2
,08-24 13:33:27.780  1973  2139 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:33:27.780  1973  2139 D LEDHandler: Battery Level Remaining: 100%
08-24 13:33:27.780  1973  2139 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
08-24 13:33:27.781  1601  1601 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
08-24 13:33:27.781  1601  1601 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:33:27.782  1601  1601 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:33:27.785  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:33:27.785  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:33:27.786  3870  3978 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:33:27.793  6635  6635 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:33:47.360  1035  1739 I ActivityManager: Killing 6340:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-24 13:33:47.393  1035  1625 W libprocessgroup: failed to open /acct/uid_10004/pid_6340/cgroup.procs: No such file or directory
,08-24 13:34:00.051  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:34:00.051  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:34:00.052  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:34:00.052  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:34:00.063  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:34:00.063  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:34:00.065  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:34:00.068  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:34:00.383  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:34:00.399  1035  1386 V AlarmManager: RTC_WAKEUP set : Alarm{3eaf0f34 type 0 when 1472038407407 com.google.android.gms} when 1472038407407
,08-24 13:34:00.425  1842  6703 I EventLogService: Aggregate from 1472037776755 (log), 1472036607303 (data)
,08-24 13:34:00.440  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:34:00.471  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
,08-24 13:35:00.051  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:35:00.051  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:35:00.051  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:35:00.052  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:35:00.063  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:35:00.063  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:35:00.065  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:35:00.068  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:35:51.894  1601  1601 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:35:51.894  1601  1601 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:35:51.911  1973  2139 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:35:51.911  1973  2139 D LEDHandler: Battery Level Remaining: 100%
08-24 13:35:51.911  1973  2139 D LEDHandler: Battery Temp: 282, mChargingStatus=5, mChargingStop=false
,08-24 13:35:51.914  1601  1601 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
08-24 13:35:51.914  1601  1601 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:35:51.915  1035  1544 D WifiController: battery changed pluggedType: 2
08-24 13:35:51.920  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:35:51.920  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:35:51.921  3870  3978 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:35:51.922  1601  1601 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:35:51.928  6635  6635 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 13:36:00.051  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:36:00.051  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:36:00.052  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:36:00.052  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:36:00.063  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:36:00.064  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:36:00.066  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:36:00.070  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:37:00.052  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:37:00.053  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:37:00.053  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:37:00.053  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:37:00.064  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:37:00.065  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:37:00.068  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:37:00.073  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:37:40.097  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:37:40.127  3870  4019 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-24 13:37:40.127  3870  4019 W bt-smp  : Plain text(LSB ~ MSB) = f6 e4 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 13:37:40.127  3870  4019 W bt-smp  : Encrypted text(LSB ~ MSB) = b2 52 06 81 ef c6 d3 e2 e8 6b 6f 70 69 86 12 6d 
,08-24 13:37:40.129  3870  4019 W bt-btm  : Stopping oneshot timer
08-24 13:37:40.130  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1fb69ad2 type 2 when 942275 com.android.bluetooth} when 942275
08-24 13:37:40.164  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:37:40.192  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
,08-24 13:38:00.056  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:38:00.056  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:38:00.056  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-24 13:38:00.063  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
08-24 13:38:00.070  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:38:00.070  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:38:00.072  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:38:00.074  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:38:50.256  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:38:50.272  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{345817a3 type 2 when 986694 com.google.android.gms} when 986694
,08-24 13:38:50.312  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:38:50.340  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
,08-24 13:38:50.357  2239  6261 D GCM     : Message class com.google.e.a.a.h
,08-24 13:39:00.052  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:39:00.052  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:39:00.052  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:39:00.053  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:39:00.064  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:39:00.064  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:39:00.067  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:39:00.072  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:39:27.367  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:39:27.382  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{bc7eaa0 type 2 when 1049545 com.google.android.gms} when 1049545
,08-24 13:39:27.427  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:39:27.455  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
,08-24 13:39:27.484  1842  1842 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-24 13:39:27.489  2239  2239 I ConfigService: onCreate
08-24 13:39:27.490  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 13:39:27.491  1842  7061 I ConfigFetchService: running network task: configservice_periodic
08-24 13:39:27.493  1842  7061 I ConfigFetchService: launchTask
08-24 13:39:27.501  2239  2239 I ConfigService: onBind returning update interface
,08-24 13:39:27.504  1842  1842 I ConfigFetchService: service connected
,08-24 13:39:27.504  2239  2239 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 13:39:27.504  2239  2239 I ConfigService: onBind returning config service
08-24 13:39:27.506  1842  1842 I ConfigClient: service connected
08-24 13:39:37.565  1035  2077 V SIM_STK : Menu title from STK is T-Mobile
,08-24 13:39:37.582  1842  2347 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-24 13:39:37.589   310  7073 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-24 13:39:37.590   310  7073 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-24 13:39:37.639   310  7073 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-24 13:39:37.910  1842  2347 W ConfigFetchTask: bad response from server: 401 Unauthorized
,08-24 13:39:37.919  1842  1842 I ConfigFetchService: fetch service done; releasing wakelock
08-24 13:39:37.922  1842  1842 I ConfigFetchService: stopping self
08-24 13:39:37.966  2239  2239 I ConfigService: onDestroy
,08-24 13:40:00.053  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:40:00.053  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:40:00.054  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:40:00.054  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:40:00.065  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:40:00.066  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:40:00.068  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:40:00.070  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:41:00.051  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:41:00.051  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:41:00.052  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:41:00.052  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:41:00.064  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:41:00.065  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:41:00.068  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
,08-24 13:41:00.075  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:42:00.058  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:42:00.058  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:42:00.059  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:42:00.059  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:42:00.071  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:42:00.071  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:42:00.073  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:42:00.075  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:42:17.895  1035  1091 I UsageStatsService: User[0] Flushing usage stats to disk
,08-24 13:43:00.051  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:43:00.051  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:43:00.052  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:43:00.052  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:43:00.064  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:43:00.064  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:43:00.066  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:43:00.070  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:44:00.053  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:44:00.053  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:44:00.053  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:44:00.054  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:44:00.065  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:44:00.065  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:44:00.068  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:44:00.070  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:45:00.052  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:45:00.052  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:45:00.052  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:45:00.053  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:45:00.065  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:45:00.065  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:45:00.068  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
,08-24 13:45:00.075  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:45:01.455  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=10570600, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-24 13:45:01.479  6959  6959 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-24 13:45:01.488  6959  6959 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@17faa0a3
08-24 13:45:01.519  2633  2633 D [Concierge]Service: onStartCommand(). Type : 9
,08-24 13:45:01.545  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=10570600 [*alarm*], flags=0x0
,08-24 13:46:00.057  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:46:00.057  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:46:00.057  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:46:00.058  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:46:00.069  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:46:00.070  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:46:00.072  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:46:00.074  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:47:00.050  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:47:00.050  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:47:00.051  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:47:00.051  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:47:00.063  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
,08-24 13:47:00.063  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:47:00.066  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:47:00.069  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:48:00.054  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:48:00.054  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:48:00.054  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-24 13:48:00.055  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
