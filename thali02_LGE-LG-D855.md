#### Test 80761374304f7b9_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 11:24:00.073  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 11:24:05.007  6777  6777 D AndroidRuntime: 
08-16 11:24:05.007  6777  6777 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 11:24:05.011  6777  6777 D AndroidRuntime: CheckJNI is OFF
08-16 11:24:05.216  6777  6777 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 11:24:05.227  1034  1574 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 11:24:05.243  1940  2533 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 11:24:05.249  1034  1574 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 11:24:05.250  1034  1574 D ActivityManager: setTaskToReturnTo : TaskRecord{172c6de5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 11:24:05.251  1034  1574 D ActivityManager: setTaskToReturnTo : TaskRecord{172c6de5 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 11:24:05.252  1034  1574 D WindowStateEx: AppWindowTokenEx init.. 
08-16 11:24:05.253   348   369 E GBMv2   : DFP En is all cleared set to be enabled
08-16 11:24:05.281  1034  1574 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6792 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 11:24:05.284  6777  6777 D AndroidRuntime: Shutting down VM
08-16 11:24:05.335  1940  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 11:24:05.335  1940  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{36076d26 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 11:24:05.336  1940  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 11:24:05.336  1940  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15cf3d67 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 11:24:05.397  6792  6792 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-16 11:24:05.505  6792  6792 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 11:24:05.513  6792  6792 I LibraryLoader: Loading: webviewchromium
08-16 11:24:05.517  6792  6792 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5169-5173)
,08-16 11:24:05.517  6792  6792 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 11:24:05.534  6792  6792 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3cb52bc4}
,08-16 11:24:05.535  6792  6792 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 11:24:05.535  6792  6792 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 11:24:05.544  6792  6792 I BrowserStartupController: Initializing chromium process, renderers=0
,08-16 11:24:05.545  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 11:24:05.556  6792  6792 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 11:24:05.560  6792  6792 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 11:24:05.560  6792  6792 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 11:24:05.563   320  1383 V AudioPolicyService: registerClient() client 0xb558a840, uid 10118
08-16 11:24:05.567  1034  1110 D BluetoothManagerService: Message: 20
08-16 11:24:05.567  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@157ad347:true
08-16 11:24:05.580  6792  6792 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:24:05.580  6792  6792 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:24:05.580  6792  6792 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:24:05.580  6792  6792 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:24:05.580  6792  6792 I Adreno-EGL: Remote Branch: 
08-16 11:24:05.580  6792  6792 I Adreno-EGL: Local Patches: 
08-16 11:24:05.580  6792  6792 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:24:05.687  6792  6827 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 11:24:05.694  6792  6792 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 11:24:05.710  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 11:24:05.714  6792  6792 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 11:24:05.717  6792  6792 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 11:24:05.720  6792  6792 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 11:24:05.720  6792  6792 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-16 11:24:05.733  6792  6792 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 11:24:05.739  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 11:24:05.739  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 11:24:05.778  6792  6839 D OpenGLRenderer: Render dirty regions requested: true
08-16 11:24:05.779  6792  6839 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 11:24:05.798  6792  6839 D OpenGLRenderer: Enabling debug mode 0
,08-16 11:24:05.805  6792  6792 D Atlas   : Validating map...
08-16 11:24:05.809  1034  2013 D SplitWindow: check instance of lgWin Window{18063f09 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 11:24:05.842  6792  6837 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:24:05.842  6792  6837 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:24:05.942  1034  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +608ms (total +688ms)
,08-16 11:24:05.944  1034  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b84c0ba u0 com.test.thalitest/.MainActivity t6} time:305600
08-16 11:24:05.956  6792  6792 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1f23563 time:305613
,08-16 11:24:06.059  6792  6792 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 11:24:06.089  6792  6792 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 11:24:06.089  6792  6792 I chromium: 
,08-16 11:24:06.186  6792  6850 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435157504
,08-16 11:24:06.202  6792  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 11:24:06.202  6792  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 11:24:06.202  6792  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 11:24:06.202  6792  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 11:24:06.202  6792  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 11:24:06.202  6792  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dc48cb7 added. We now have 1 listener(s)
08-16 11:24:06.208  1034  1850 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:24:06.212  6792  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 11:24:06.221  6792  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 11:24:06.226  6792  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:24:06.226  6792  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 11:24:06.234  6792  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fad0942 added. We now have 1 listener(s)
08-16 11:24:06.235  6792  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:24:06.240  1034  1542 D WifiService: New client listening to asynchronous messages
08-16 11:24:06.243  6792  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:24:06.244  6792  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 11:24:06.244  6792  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 11:24:06.244  6792  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 11:24:06.245  6792  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 11:24:06.249  6792  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:24:06.250  1034  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:24:06.252  6792  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 11:24:06.268  6792  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 11:24:06.268  6792  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:24:06.268  6792  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:24:06.268  6792  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:24:06.268  6792  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:24:06.268  6792  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:24:06.268  6792  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:06.268  6792  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:24:06.268  6792  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:24:06.269  6792  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 11:24:06.269  6792  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:24:06.272  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:24:06.274  6792  6850 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 11:24:06.274  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:24:06.312  6792  6837 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 11:24:06.312  6792  6837 I chromium: 
,08-16 11:24:06.408  6792  6792 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 11:24:07.197   348   371 E GBMv2   : DFP En is all cleared set to be enabled
08-16 11:24:07.197   348   371 E GBMv2   : Set value is all cleared set the max
08-16 11:24:07.197   348   371 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 11:24:07.591  6792  6853 W jxcore-log: Initializing JXcore engine
08-16 11:24:07.591  6792  6853 W jxcore-log: JXcore engine is ready
,08-16 11:24:07.655  6853  6853 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9801]" dev="sockfs" ino=9801 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-16 11:24:07.655  6853  6853 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 11:24:07.655  6853  6853 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9919]" dev="sockfs" ino=9919 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 11:24:07.655  6853  6853 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 11:24:07.655  6853  6853 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32240]" dev="sockfs" ino=32240 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 11:24:07.690  6792  6853 W jxcore-log: Starting JXcore engine
,08-16 11:24:07.868  6792  6853 W jxcore-log: Platform android
08-16 11:24:07.868  6792  6853 W jxcore-log: 
,08-16 11:24:07.868  6792  6853 W jxcore-log: Process ARCH arm
08-16 11:24:07.868  6792  6853 W jxcore-log: 
,08-16 11:24:08.143  6792  6853 I jxcore-log: JXcore Cordova bridge is ready!
08-16 11:24:08.143  6792  6853 I jxcore-log: 
08-16 11:24:08.143  6792  6853 W jxcore-log: JXcore engine is started
,08-16 11:24:08.151  6792  6850 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 11:24:08.153  6792  6792 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 11:24:23.769  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 11:24:23.769  6792  6853 I jxcore-log: 
,08-16 11:24:23.772  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 11:24:23.772  6792  6853 I jxcore-log: 
08-16 11:24:23.778  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:24:23.778  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:24:23.778  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:24:23.778  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:24:23.778  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:24:23.778  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:23.778  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:24:23.778  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:24:23.781  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:23.785  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 11:24:23.785  6792  6853 I jxcore-log: 
,08-16 11:24:23.786  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 11:24:23.786  6792  6853 I jxcore-log: 
08-16 11:24:24.122  6792  6853 I jxcore-log: Running unit tests
08-16 11:24:24.122  6792  6853 I jxcore-log: 
,08-16 11:24:24.123  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:24:24.123  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d458ed9 added. We now have 2 listener(s)
08-16 11:24:24.124  1034  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:24:24.125  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 11:24:24.125  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:24:24.125  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:24:24.125  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:24:24.125  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cfa209e added. We now have 2 listener(s)
08-16 11:24:24.125  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:24:24.126  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:24:24.128  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:24:24.130  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:24:24.130  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:24:24.130  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:24:24.130  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:24:24.130  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:24:24.130  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:24.130  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:24:24.130  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:24:24.131  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:24.131  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:24:24.132  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:24:24.133  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:24:24.134  6792  6853 D ExecuteNativeTests: Running unit tests
08-16 11:24:29.221  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:24:29.221  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c added. We now have 3 listener(s)
,08-16 11:24:29.232  1034  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:24:29.237  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 11:24:29.237  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:24:29.237  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:24:29.237  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 11:24:29.237  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 added. We now have 3 listener(s)
08-16 11:24:29.237  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:24:29.241  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:24:29.245  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:24:29.248  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:24:29.248  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:24:29.248  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:24:29.248  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:24:29.248  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:24:29.248  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:29.248  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:24:29.248  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:24:29.250  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:29.250  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:24:29.253  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:24:29.256  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:24:29.261  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 11:24:29.263  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 11:24:29.265  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 11:24:29.265  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 11:24:29.271  6792  6853 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 11:24:29.273  6792  6853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 11:24:29.273  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 11:24:29.276  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:24:29.276  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:24:29.276  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:24:29.278  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:24:29.281  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:29.281  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:29.282  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:29.282  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:29.282  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:24:29.282  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:24:29.282  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c removed from the list
08-16 11:24:29.282  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:29.283  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 removed from the list
08-16 11:24:29.283  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:29.283  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:29.284  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:29.284  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:29.285  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:29.285  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:29.285  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:29.285  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:29.287  6792  6853 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 11:24:29.288  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:29.288  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:29.288  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:29.288  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:29.288  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:29.289  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:29.289  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:29.289  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:29.289  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not i,n the list
08-16 11:24:29.289  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:29.289  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:29.289  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:29.289  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:29.289  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:29.291  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:29.291  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:29.291  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:29.291  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
,08-16 11:24:29.302  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 11:24:29.302  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 11:24:29.302  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 11:24:29.302  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 11:24:29.302  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 11:24:29.302  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 11:24:29.302  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 11:24:29.302  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 11:24:29.302  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 11:24:29.303  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 11:24:29.305  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 11:24:29.305  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:29.305  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:29.305  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:24:29.309  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:29.309  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:29.309  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:29.309  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:29.309  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:29.309  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:29.309  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:29.309  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:29.309  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:29.309  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:29.309  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:29.311  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:29.311  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:29.311  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:29.311  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:29.312  6792  6853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 11:24:29.314  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:24:29.318  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:24:29.318  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:24:29.318  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:24:29.318  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:24:29.318  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:24:29.318  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:29.318  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:24:29.318  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:24:29.322  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:29.322  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:24:29.324  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:24:29.326  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:24:29.326  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:24:29.327  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 11:24:29.327  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 11:24:29.327  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:24:29.327  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:24:29.331  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 11:24:29.334  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:24:29.340  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 11:24:29.347  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 11:24:29.351  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 11:24:29.353  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 11:24:29.354  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:24:29.356  6792  6853 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 11:24:29.356  6792  6853 I io.jxcore.node.ConnectionHelper: start: OK
08-16 11:24:34.367  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:24:34.374  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:34.375  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:34.376  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:34.376  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:34.376  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:24:34.376  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:34.376  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:34.377  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:34.377  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:34.377  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:35.511  1034  3565 I LocationManagerService: remove 2aaefd06
08-16 11:24:35.512  1034  3565 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-16 11:24:35.512  1034  3565 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 11:24:35.521  1034  3565 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-16 11:24:35.523  1034  3565 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-16 11:24:35.525  1034  3565 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-16 11:24:39.379  6792  6853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 11:24:39.392  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:24:39.398  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:24:39.398  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:24:39.398  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:24:39.398  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:24:39.398  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:24:39.398  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:39.398  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:24:39.398  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:24:39.402  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:39.402  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:24:39.404  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:24:39.406  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:24:39.406  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:24:39.406  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 11:24:39.407  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 11:24:39.407  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:24:39.407  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:24:39.413  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 11:24:39.416  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:24:39.417  6792  6853 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 11:24:39.418  6792  6853 I io.jxcore.node.ConnectionHelper: start: OK
08-16 11:24:39.420  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:39.420  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:39.420  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:39.420  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:39.420  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:39.420  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:24:39.420  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:39.420  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:39.421  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:39.421  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:39.421  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:39.421  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:39.421  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:39.422  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:39.422  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:39.425  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:39.425  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:39.425  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:39.425  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:39.426  6792  6853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 11:24:39.432  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:24:39.436  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:24:39.436  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:24:39.436  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:24:39.436  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:24:39.436  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:24:39.436  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:39.436  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:24:39.436  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:24:39.437  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:24:39.438  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:24:39.439  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:24:39.444  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 11:24:39.444  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:24:39.444  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 11:24:39.445  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 11:24:39.445  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:24:39.445  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:24:39.450  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 11:24:39.450  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:24:39.452  6792  6853 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 11:24:39.455  6792  6853 I io.jxcore.node.ConnectionHelper: start: OK
08-16 11:24:44.456  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:44.456  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:44.456  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:24:46.495  1034  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=492664873, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-16 11:24:46.564  2578  2578 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 11:24:46.591  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=492664873 [*alarm*], flags=0x0
,08-16 11:24:46.980  1034  1050 I art     : Explicit concurrent mark sweep GC freed 29564(1403KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.450ms total 138.183ms
,08-16 11:24:49.466  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.466  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:49.467  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:24:49.473  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.473  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.473  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:24:49.476  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.476  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.476  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.476  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.476  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.477  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.477  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.478  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:49.478  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:49.479  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.479  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.479  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.479  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.480  6792  6853 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 11:24:49.480  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.480  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:49.480  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:49.481  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.481  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.481  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.481  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.481  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.481  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.481  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.481  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.481  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.481  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.481  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:24:49.487  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:49.487  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:49.488  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.488  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.488  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.488  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.489  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 11:24:49.489  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.490  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:49.490  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:49.490  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.490  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.490  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.490  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.490  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.490  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.490  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.490  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.490  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.490  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.491  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.492  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:49.492  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:49.493  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.493  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.493  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.493  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.494  6792  6853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 11:24:49.494  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.494  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:49.494  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:49.495  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.495  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.495  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.496  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.496  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.496  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.496  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.496  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.496  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.496  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.496  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:24:49.501  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:49.501  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:49.502  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.502  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.502  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.502  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.503  6792  6853 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 11:24:49.503  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.504  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:49.504  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:49.504  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.504  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.504  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.504  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.504  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.504  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.504  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.504  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.505  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.505  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.505  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.506  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:49.506  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:49.507  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.507  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.507  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.508  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.508  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 11:24:49.514  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 11:24:49.514  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 11:24:49.514  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 11:24:49.514  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:24:49.514  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:24:49.515  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 11:24:49.515  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 11:24:49.515  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 11:24:49.516  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.516  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:49.516  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:49.517  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.517  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.517  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.517  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.518  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.518  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.518  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.518  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.518  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.518  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.518  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.521  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:49.521  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:24:49.527  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.527  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.527  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.527  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.531  6792  6853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 11:24:49.531  6792  6853 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 11:24:49.531  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 11:24:49.536  6792  6853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 11:24:49.537  6792  6853 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 11:24:49.537  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 11:24:49.538  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 11:24:49.538  6792  6853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 11:24:49.538  6792  6853 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 11:24:49.538  6792  6853 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 11:24:49.539  6792  6853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 11:24:49.539  6792  6853 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 11:24:49.539  6792  6853 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 11:24:49.539  6792  6853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 11:24:49.539  6792  6853 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 11:24:49.539  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 11:24:49.548  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 11:24:49.549  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 11:24:49.549  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 11:24:49.550  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 11:24:49.550  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 11:24:49.550  6792  6853 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 11:24:49.550  6792  6853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 11:24:49.550  6792  6853 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 11:24:49.551  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.551  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:49.551  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:49.555  6792  6890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
,08-16 11:24:49.566  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.566  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.566  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.566  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 11:24:49.568  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.568  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.568  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.568  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.568  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.568  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.568  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.568  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.569  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:49.569  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:49.570  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.570  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.570  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.570  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.571  6792  6853 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 11:24:49.571  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.571  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:49.571  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:49.572  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.572  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.572  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.572  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.572  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.572  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.572  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.572  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.572  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.572  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.572  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.573  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:49.573  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:49.574  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.574  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.574  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.574  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.575  6792  6853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 11:24:49.576  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.576  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:24:49.576  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:49.578  6792  6891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-16 11:24:49.578  6792  6891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-16 11:24:49.578  6792  6891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
,08-16 11:24:49.584  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.584  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.584  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.584  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.584  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.584  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.584  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.584  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.584  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.584  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.585  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.586  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:49.586  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:49.587  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.587  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.587  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.587  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.588  6792  6853 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 11:24:49.588  6792  6853 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 11:24:49.588  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 11:24:49.588  6792  6853 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 11:24:49.588  6792  6853 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 11:24:49.589  6792  6853 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 11:24:49.589  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 11:24:49.589  6792  6853 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 11:24:49.589  6792  6853 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 11:24:49.589  6792  6853 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 11:24:49.589  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 11:24:49.589  6792  6853 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 11:24:49.589  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:49.589  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:49.589  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:49.590  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.590  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.590  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.590  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.590  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.590  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.590  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.590  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.590  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.590  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.590  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:24:49.597  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:24:49.597  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:49.599  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:49.599  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:49.599  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.599  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.599  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:49.600  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.600  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.600  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:49.600  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:49.600  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:49.600  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:49.600  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:49.600  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:49.707  6792  6890 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 11:24:49.708  6792  6890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
,08-16 11:24:54.601  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.601  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:54.602  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:54.602  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.602  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.602  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:54.602  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:54.602  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:54.603  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:24:54.612  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:54.612  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.612  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.612  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:54.613  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.613  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
,08-16 11:24:54.613  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:54.613  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.613  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.613  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.613  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.617  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:54.617  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:54.619  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:54.619  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:54.619  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.619  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
,08-16 11:24:54.625  6792  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 11:24:54.625  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:24:54.626  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 11:24:54.627  6792  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 11:24:54.627  6792  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 11:24:54.628  6792  6792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 11:24:54.628  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 11:24:54.628  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 11:24:54.630  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:54.630  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 11:24:54.630  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 11:24:54.630  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 11:24:54.630  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.630  6792  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 11:24:54.633  6792  6916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 11:24:54.633  6792  6916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 11:24:54.636  6792  6792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 11:24:54.636  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:54.636  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.636  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 11:24:54.636  6792  6853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 11:24:54.637  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 11:24:54.638  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 11:24:54.640  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:24:54.640  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:24:54.640  6792  6853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 11:24:54.640  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.640  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.641  6792  6853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:24:54.642  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 11:24:54.642  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 11:24:54.642  6792  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 11:24:54.642  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:24:54.643  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:54.643  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:54.644  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:54.644  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:54.644  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:54.644  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.644  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.644  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:54.644  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.644  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:54.644  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:54.644  6792 , 6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.644  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.644  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.644  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.646  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:54.646  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:54.646  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.646  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:54.647  6792  6853 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 11:24:54.651  6792  6853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 11:24:54.651  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 11:24:54.654  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:24:54.656  6792  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:24:54.656  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:54.657  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:54.657  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:54.657  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:54.658  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.658  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.658  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:54.658  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.658  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:54.659  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:54.659  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.659  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.659  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.659  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:24:54.665  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:54.665  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:54.665  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.665  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:54.667  1034  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:24:54.669  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:24:54.670  1034  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 11:24:54.672  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:54.672  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:54.672  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:54.673  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:54.673  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.673  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.673  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:54.673  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.673  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:54.673  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:54.673  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.673  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.673  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.673  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.675  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:54.675  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:54.675  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.675  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:54.676  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:24:54.676  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:24:54.676  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:24:54.677  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:24:54.677  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.677  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.677  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27df577c not in the list
08-16 11:24:54.677  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:24:54.677  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
,08-16 11:24:54.677  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:24:54.677  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.677  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:24:54.677  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:24:54.677  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:24:54.678  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:24:54.678  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:24:54.678  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:24:54.678  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca83805 not in the list
08-16 11:24:55.143  6792  6792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-16 11:24:59.683  6792  6853 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-16 11:24:59.689  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 11:24:59.691  6792  6853 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 11:24:59.691  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 11:24:59.691  6792  6853 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 11:24:59.691  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 11:24:59.700  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 11:24:59.700  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 11:24:59.703  6792  6853 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-16 11:24:59.707  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 11:24:59.707  6792  6853 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 11:24:59.707  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 11:24:59.707  6792  6853 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 11:24:59.707  6792  6853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 11:24:59.708  6792  6853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 11:24:59.709  6792  6853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 11:24:59.709  6792  6853 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 11:24:59.710  6792  6853 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 11:24:59.710  6792  6853 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 11:24:59.710  6792  6853 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 11:25:00.061  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 11:25:00.061  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 11:25:00.061  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 11:25:00.062  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-16 11:25:00.077  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 11:25:00.077  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
,08-16 11:25:00.081  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-16 11:25:00.082  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 11:25:04.712  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:25:04.712  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f0fd0b2 added. We now have 3 listener(s)
08-16 11:25:04.712  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:25:04.725  6792  6853 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 11:25:04.727  1034  1649 D WifiServiceImplEx: setWifiEnabled: true pid=6792, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 11:25:04.729  1034  1649 D WifiService: setWifiEnabled: true pid=6792, uid=10118
08-16 11:25:04.729  1034  1649 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:25:09.735  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:25:09.735  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16fe4803 added. We now have 4 listener(s)
08-16 11:25:09.735  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:25:09.755  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:25:09.755  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16fe4803 removed from the list
08-16 11:25:09.755  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:25:09.755  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:25:09.755  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:25:09.756  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:25:09.756  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3987c380 added. We now have 4 listener(s)
08-16 11:25:09.756  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:25:09.761  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:25:09.761  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3987c380 removed from the list
08-16 11:25:09.761  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:25:09.761  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:25:09.761  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:25:09.761  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:25:09.762  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@115f6db9 added. We now have 4 listener(s)
08-16 11:25:09.762  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:25:09.765  1034  1953 D WifiServiceImplEx: setWifiEnabled: false pid=6792, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 11:25:09.766  1034  1953 D WifiService: setWifiEnabled: false pid=6792, uid=10118
08-16 11:25:09.766  1034  1953 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:25:09.789  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 11:25:09.789  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 11:25:09.790  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-16 11:25:09.791  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:09.791  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:09.792  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:09.792  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:09.793  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:09.793  1034  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 11:25:09.793  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 11:25:09.793  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 11:25:09.794  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 11:25:09.794  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 11:25:09.796  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:09.797  1034  2031 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@31741d0f mBinding = false
,08-16 11:25:09.805  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 11:25:09.805  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:09.805  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:09.805  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 11:25:09.806  2727  2727 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 11:25:09.807  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 11:25:09.807  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 11:25:09.808  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-16 11:25:09.808  1034  2864 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:09.816  1034  1110 D BluetoothManagerService: Message: 2
,08-16 11:25:09.820  1034  1110 D BluetoothManagerService: Sending off request.
08-16 11:25:09.820  3897  6854 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 11:25:09.821  3897  3972 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 11:25:09.821  3897  3972 D BluetoothAdapterProperties: Setting state to 13
08-16 11:25:09.821  3897  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 11:25:09.822  3897  3972 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 11:25:09.822  3897  3972 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 11:25:09.827  3897  3975 D BluetoothAdapterProperties: Scan Mode:20
08-16 11:25:09.827  3897  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 11:25:09.830  3897  4256 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 11:25:09.830  3897  4256 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:09.830  3897  4256 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 11:25:09.830  3897  4256 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 11:25:09.830  3897  4256 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 11:25:09.830  3897  4256 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 11:25:09.830  3897  4256 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 11:25:09.830  3897  4256 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-16 11:25:09.833  3897  4258 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:09.833  3897  4292 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:09.834  3897  4297 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:09.834  3897  4293 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:09.835  3897  3972 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 11:25:09.837  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 11:25:09.837  3897  4100 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 11:25:09.839  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 11:25:09.839  3897  4100 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 11:25:09.866  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.866  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:09.866  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:09.866  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:09.866  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:09.866  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:09.866  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:09.866  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:25:09.866  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:25:09.870  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.870  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:09.874  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.874  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:09.874  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:09.874  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:09.874  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:09.874  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:09.874  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:09.874  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:25:09.874  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:09.875  1034  1110 D BluetoothManagerService: Message: 60
08-16 11:25:09.875  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 11:25:09.875  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 11:25:09.875  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.875  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:09.877   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 11:25:09.933  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 11:25:09.934  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 11:25:09.935  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-16 11:25:09.948  1034  1091 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6932 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-16 11:25:09.953  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:25:09.956  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:09.958  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 11:25:09.965  3897  3897 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:09.965  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 11:25:09.965  3897  3897 D BluetoothMapService: STATE_TURNING_OFF
08-16 11:25:09.965  3897  3897 V BluetoothMapService: Handler(): got msg=4
08-16 11:25:09.965  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 11:25:09.965  3897  3897 D BluetoothMapService: MAP Service closeService in
08-16 11:25:09.965  3897  3897 D BluetoothMapMasInstance: MAP Service shutdown
08-16 11:25:09.966  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 11:25:09.966  3897  3897 V BluetoothMapService: MAP Service closeService out
08-16 11:25:09.966  3897  3897 V BtOppService: Receiver DISABLED_ACTION 
08-16 11:25:09.966  3897  3897 I BtOppRfcommListener: stopping Accept Thread
08-16 11:25:09.966  3897  3897 V BtOppRfcommListener: close mBtServerSocket
08-16 11:25:09.967  3897  3897 V BtOppRfcommListener: waiting for thread to terminate
08-16 11:25:09.967  3897  4292 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 11:25:09.967  3897  3897 V BtOppRfcommListener: done waiting for thread to terminate
,08-16 11:25:09.974  1034  2031 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-16 11:25:09.980  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.980  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:25:09.980  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:09.980  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:09.980  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:09.980  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:09.980  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:09.980  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:25:09.980  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:25:09.982  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.982  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:09.982  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:09.982  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:09.982  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:09.982  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:09.982  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:09.982  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:09.982  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:09.987  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-13ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:09.987  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-13ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:09.987  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 11:25:09.987  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:09.987  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 11:25:09.992  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.992  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:09.992  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:25:09.993  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.993  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:25:09.996  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.996  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:09.996  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:09.996  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:09.996  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:09.996  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:09.996  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:09.996  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:09.996  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:09.997  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.997  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:09.999  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.999  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:09.999  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:09.999  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:09.999  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:09.999  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:09.999  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:09.999  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:09.999  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:09.999  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:09.999  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:10.028  1034  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6956 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 11:25:10.030  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:10.031  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.031  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:10.031  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.031  1034  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@35134602
08-16 11:25:10.031  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:10.031  1034  1536 D LGWifiP2pService: P2pDisablingState
08-16 11:25:10.032  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:10.032  1034  1536 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.032  1034  1536 D LGWifiP2pService: p2p socket connection lost
08-16 11:25:10.032  1034  1536 D LGWifiP2pService: P2pDisabledState
08-16 11:25:10.032  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:10.032  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:10.033  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:10.033  1034  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 11:25:10.033  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:10.034  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:10.034  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:10.034  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:10.033  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-16 11:25:10.035  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 11:25:10.035  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:10.035  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:10.035  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 11:25:10.038  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 11:25:10.040  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-16 11:25:10.040  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.040  1034  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.041  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 11:25:10.041  2727  2727 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-16 11:25:10.041  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 11:25:10.041  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 11:25:10.042  1034  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 11:25:10.042  1034  1543 D DSQN    : disableDataServiceNotify
08-16 11:25:10.042  1034  1543 D DSQN    : stop dsqn bin
08-16 11:25:10.043  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-16 11:25:10.043   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 11:25:10.043   315  6968 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 11:25:10.044  1034  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 11:25:10.045  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 11:25:10.046  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:10.046  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:10.046  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 11:25:10.046  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 11:25:10.047  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-16 11:25:10.047  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 11:25:10.047  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.047  1034  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.047  1940  1940 D WfdsService: WifiP2pState is changed : false
08-16 11:25:10.048  1940  2327 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 11:25:10.048  1940  2327 D WfdsService: Set the WFDS Monitor: false
08-16 11:25:10.048  3897  3897 V BtOppService: onDestroy
08-16 11:25:10.048  1034  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 11:25:10.049  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-16 11:25:10.049  1034  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 11:25:10.049  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:10.049  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:10.049  1034  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:10.049  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 11:25:10.050  1034  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 11:25:10.050  1034  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
0,8-16 11:25:10.050  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 11:25:10.050  3897  3897 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 11:25:10.050  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:10.050  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 11:25:10.051  1034  1537 D WifiNative-p2p0: TERMINATE: returned true
08-16 11:25:10.051  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.051  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.051  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 11:25:10.051  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-16 11:25:10.051  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 11:25:10.051  1034  2863 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 11:25:10.051  1940  2327 D WfdsMonitor: WFDS Monitor is stopped
08-16 11:25:10.051  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 11:25:10.051  1940  2766 D CtrlSupplicant: Received on exit socket, terminate
08-16 11:25:10.051  1940  2766 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 11:25:10.051  1940  2327 D WfdsService: STATE : WfdsDisabledState - enter
08-16 11:25:10.051  1940  2766 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 11:25:10.051  1940  2766 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,08-16 11:25:10.051  1940  2327 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 11:25:10.051  1940  2333 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-16 11:25:10.052  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:10.052  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:10.052  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 11:25:10.053  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 11:25:10.053  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 11:25:10.053  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 11:25:10.059  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:10.059  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:10.061  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:10.061  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:10.061  1034  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:10.061  1034  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:10.061  1034  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:10.061  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:10.062  1034  1543 D NetworkManagementService: Removing idletimer
08-16 11:25:10.062  1034  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:10.063  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:10.063  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 11:25:10.063  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 11:25:10.063  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 11:25:10.063  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 11:25:10.063  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 11:25:10.063  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 11:25:10.064  1034  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 11:25:10.064  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:10.064  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 11:25:10.064  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 11:25:10.064  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 11:25:10.064  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unsp,ecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 11:25:10.064  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 11:25:10.065  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:10.065  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:10.065  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:10.065  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:10.065  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:10.065  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:10.065  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:10.065  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:10.065  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:10.066  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:10.066  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:10.067  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:10.067  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:10.067  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:10.067  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:10.067  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:10.067  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:10.067  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:10.067  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:10.067  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:10.068  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:10.068  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:10.070  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:10.070  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:10.070  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:10.070  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:10.070  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:10.070  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:10.070  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:10.070  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:10.070  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:10.070  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:10.070  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:10.095  6956  6956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 11:25:10.095  6956  6956 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-16 11:25:10.095  6956  6956 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 11:25:10.096  6956  6956 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 11:25:10.096  6956  6956 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 11:25:10.097  6956  6956 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 11:25:10.097  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:10.098  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:10.098  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:10.099  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 11:25:10.099  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:10.100  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:10.111  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 11:25:10.112  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:10.112  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:10.113  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:10.124  2727  2727 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 11:25:10.124  2727  2727 I wpa_supplicant: monitor socket send errors count : 1
08-16 11:25:10.125  2727  2727 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-2\x00 that cannot receive messages
,08-16 11:25:10.126  1034  2763 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-16 11:25:10.126  1034  2763 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 11:25:10.135  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 11:25:10.136  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:10.136  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:10.147  6932  6932 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 11:25:10.147  6932  6932 W LG Account v2.2: No ProfileInfo entries
08-16 11:25:10.147  6932  6932 I LG Account v2.2: isEnabled: false
08-16 11:25:10.147  6932  6932 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 11:25:10.147  6932  6932 I Feature : [Lifetracker]Country: EU
08-16 11:25:10.147  6932  6932 I Feature : [Lifetracker]Operator: OPEN
08-16 11:25:10.148  6932  6932 I Feature : [Lifetracker]Ranking support: false
08-16 11:25:10.148  6932  6932 I Feature : [Lifetracker]Comfort support: false
08-16 11:25:10.148  6932  6932 I Feature : [Lifetracker]Accessory: true
08-16 11:25:10.148  6932  6932 I Feature : [Lifetracker]Health device: true
08-16 11:25:10.148  6932  6932 I Feature : [Lifetracker]Extra Pedometer: false
08-16 11:25:10.148  6932  6932 I Feature : [Lifetracker]Blood glucose device: false
08-16 11:25:10.148  6932  6932 I Feature : [Lifetracker]Device Number: 3
,08-16 11:25:10.151  1034  2864 D DhcpStateMachine: StoppedState
08-16 11:25:10.151  1034  2864 D DhcpStateMachine: StoppedState{ when=-108ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:10.152  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 11:25:10.152  1034  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 11:25:10.157  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:10.163  2727  2727 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 11:25:10.164  2727  2727 W wpa_supplicant: USIM:  scard_deinit function
08-16 11:25:10.164  1034  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 11:25:10.164  1034  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 11:25:10.165  1034  2763 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 11:25:10.165  1034  2763 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 11:25:10.165  1034  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:10.165  1034  1110 D Tethering: InitialState.processMessage what=4
08-16 11:25:10.165  1034  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:10.165  1034  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=369812
08-16 11:25:10.166  1034  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=369812
08-16 11:25:10.167  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=369813  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 11:25:10.167  1034  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=369814  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 11:25:10.188  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 11:25:10.202  1034  2013 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6980 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 11:25:10.205  1034  2013 I ActivityManager: Killing 6220:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-16 11:25:10.266  2727  2727 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 11:25:10.267  1034  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 11:25:10.267  1034  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 11:25:10.267  1034  2763 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 11:25:10.268  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-16 11:25:10.272  3897  3897 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 11:25:10.272  3897  3897 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:10.272  3897  3897 V BluetoothPbapReceiver: ***********state = 13
08-16 11:25:10.273  3897  3897 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 11:25:10.277  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 11:25:10.277  1034  1574 W libprocessgroup: failed to open /acct/uid_10014/pid_6220/cgroup.procs: No such file or directory
08-16 11:25:10.281  3897  3897 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:10.281  3897  3897 V BluetoothPbapService: state: 13
08-16 11:25:10.281  3897  3897 V BluetoothPbapService: Pbap Service closeService in
08-16 11:25:10.282  1034  1110 D BluetoothManagerService: Message: 20
08-16 11:25:10.282  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3478d146:true
,08-16 11:25:10.286  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 11:25:10.286  3897  3897 V BluetoothPbapService: successfully stopped pbap service
08-16 11:25:10.286  3897  3897 V BluetoothPbapService: Pbap Service closeService out
08-16 11:25:10.287  3897  3897 V BluetoothPbapService: Pbap Service onDestroy
08-16 11:25:10.287  3897  3897 V BluetoothPbapService: Pbap Service closeService in
08-16 11:25:10.287  3897  3897 V BluetoothPbapService: Pbap Service closeService out
08-16 11:25:10.287  3897  3897 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 11:25:10.304  1034  1110 D BluetoothManagerService: Message: 30
,08-16 11:25:10.309  1034  1110 D BluetoothManagerService: Message: 30
08-16 11:25:10.312  6956  6956 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 11:25:10.314  6956  6956 D BluetoothMap: Create BluetoothMap proxy object
08-16 11:25:10.316  1034  1110 D BluetoothManagerService: Message: 30
08-16 11:25:10.323  1034  1110 D BluetoothManagerService: Message: 30
,08-16 11:25:10.325  6956  6956 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 11:25:10.327  6956  6956 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 11:25:10.331  6980  6980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 11:25:10.336  6980  6980 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 11:25:10.336  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:10.338  1034  1850 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
08-16 11:25:10.357   320  2151 V AudioFlinger: 2127 died, releasing its sessions
08-16 11:25:10.357   320  2151 V AudioFlinger:  pid 1851 @ 0
08-16 11:25:10.357   320  2151 V AudioFlinger:  pid 3483 @ 1
08-16 11:25:10.357   320  2151 V AudioFlinger:  pid 3483 @ 2
,08-16 11:25:10.377  1034  1649 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
08-16 11:25:10.378  6956  6956 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-16 11:25:10.381  1034  1537 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 11:25:10.381  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 11:25:10.381  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-16 11:25:10.381  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 11:25:10.382  1940  1940 D WfdsService: Supplicant Connection state is changed : false
08-16 11:25:10.382  1940  2327 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 11:25:10.382  1940  2327 D WfdsService: Set the WFDS Monitor: false
08-16 11:25:10.382  1940  2327 D WfdsMonitor: WFDS Monitor is stopped
08-16 11:25:10.383  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 11:25:10.384  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:10.385  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 11:25:10.385  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 11:25:10.385  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 11:25:10.385  2461  2461 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:10.385  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-16 11:25:10.389  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:10.389  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:10.389  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:10.389  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:10.389  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:10.389  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:10.389  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:10.389  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:10.389  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:10.391  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:25:10.393  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:10.400  6956  6956 D DockEventReceiver: finishStartingService: stopping service
08-16 11:25:10.413  6956  6956 D BluetoothInputDevice: Proxy object connected
08-16 11:25:10.414  6956  6956 D HidProfile: Bluetooth service connected
,08-16 11:25:10.416  6956  6956 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 11:25:10.417  6956  6956 D PanProfile: Bluetooth service connected
08-16 11:25:10.418  6956  6956 D BluetoothMap: Proxy object connected
08-16 11:25:10.419  6956  6956 D MapProfile: Bluetooth service connected
08-16 11:25:10.419  6956  6956 D BluetoothMap: getConnectedDevices()
08-16 11:25:10.420  6956  6956 D BluetoothMap: Bluetooth is Not enabled
08-16 11:25:10.435  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:10.472  6956  6956 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:10.472  6956  6956 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:10.485  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:10.485  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 11:25:10.487  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 11:25:10.493  6956  6956 D BluetoothPermissionRequest: onReceive
08-16 11:25:10.497  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 11:25:10.507  1034  2049 I ActivityManager: Killing 6404:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-16 11:25:10.508  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 11:25:10.567  3897  3897 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 11:25:10.567  3897  3897 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 11:25:10.568  1034  1050 W libprocessgroup: failed to open /acct/uid_10004/pid_6404/cgroup.procs: No such file or directory
08-16 11:25:10.569  3897  3897 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-16 11:25:10.584  1034  1537 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
,08-16 11:25:10.585  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 11:25:10.654  1034  1894 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7009 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 11:25:10.659  3897  3897 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:10.659  3897  3897 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 11:25:10.663  3897  3897 V BluetoothFtpService: Ftp Service onStartCommand
08-16 11:25:10.663  3897  3897 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:10.663  3897  3897 V BluetoothFtpService: Ftp Service closeService
08-16 11:25:10.664  3897  3897 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 11:25:10.666  3897  3897 V BluetoothFtpService: successfully stopped ftp service
08-16 11:25:10.666  3897  3897 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 11:25:10.667  3897  3897 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 11:25:10.667  3897  3897 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 11:25:10.667  3897  3897 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:10.670  3897  3897 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 11:25:10.670  3897  3897 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 11:25:10.672  3897  3897 V BluetoothFtpService: Ftp Service onDestroy
08-16 11:25:10.672  3897  3897 V BluetoothFtpService: Ftp Service closeService
08-16 11:25:10.697   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.591ms total 44.954ms
,08-16 11:25:10.720   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 20.586ms
,08-16 11:25:10.742   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 20.646ms
,08-16 11:25:10.788  1034  1051 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7029 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 11:25:10.806  3897  3897 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:10.806  3897  3897 V BluetoothSapService: state: 13
08-16 11:25:10.806  3897  3897 V BluetoothSapService: Stopping SAP server process
,08-16 11:25:10.808  3897  3897 V BluetoothSapService: Sap Service closeSapService in
08-16 11:25:10.808  3897  3897 V BluetoothSapService: Close listen Socket : 
08-16 11:25:10.808  3897  3897 V BluetoothSapService: Close rfcomm Socket : 
08-16 11:25:10.808  3897  3897 V BluetoothSapService: Close sapd  Socket : 
08-16 11:25:10.810  3897  3897 V BluetoothSapService: Sap Service closeSapService out
08-16 11:25:10.810  3897  3897 V BluetoothSapService: Sap Service onDestroy
08-16 11:25:10.810  3897  3897 V BluetoothSapService: Sap Service closeSapService in
08-16 11:25:10.810  3897  3897 V BluetoothSapService: Close listen Socket : 
08-16 11:25:10.810  3897  3897 V BluetoothSapService: Close rfcomm Socket : 
08-16 11:25:10.810  3897  3897 V BluetoothSapService: Close sapd  Socket : 
08-16 11:25:10.811  3897  3897 V BluetoothSapService: Sap Service closeSapService out
,08-16 11:25:10.835  7009  7009 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 11:25:10.846  3897  4100 W bt-btif : ag scb idx 1 not allocated
08-16 11:25:10.846  3897  3975 D bt_hci_bdroid: cleanup
,08-16 11:25:10.846  3897  4100 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:25:10.846  3897  4103 I bt_lpm  : LPM is already off!!!
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 11:25:10.846  3897  4232 I bt_userial_mct: exiting userial_read_thread
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:10.846  3897  4232 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:25:10.846  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:10.847  3897  4100 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:25:10.847  3897  4100 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:10.847  3897  4100 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 11:25:10.847  3897  4100 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 11:25:10.847  3897  3975 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 11:25:10.848  3897  4103 I bt_vendor: hw_epilog_process
08-16 11:25:10.848  3897  3975 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 11:25:10.848  3897  3975 D bt_userial_mct: userial_close
08-16 11:25:10.848  3897  3975 E bt_userial_mct: pthread_join() FAILED result:3
08-16 11:25:10.848  3897  3975 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 11:25:10.852  7029  7029 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 11:25:10.868  1034  1953 I ActivityManager: Killing 6540:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-16 11:25:10.894  3897  3975 D bt_hci_bdroid: set_power 0
,08-16 11:25:10.894  3897  3975 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 11:25:10.894  3897  3975 I bt_vendor: bluetooth satus is on
08-16 11:25:10.894  3897  3975 I bt_vendor: bt-vendor : resetting BT status
08-16 11:25:10.894  3897  3975 I bt_vendor: Starting hciattach daemon
08-16 11:25:10.894  3897  3975 I bt_vendor: try to set false
08-16 11:25:10.895  3897  3975 I bt_vendor: Starting hciattach daemon
08-16 11:25:10.895  3897  3975 I bt_vendor: try to set false
08-16 11:25:10.895  3897  3975 I bt_vendor: cleanup
08-16 11:25:10.896  3897  4100 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 11:25:10.896  3897  3975 I GKI_LINUX: GKI_exit_task 0 done
08-16 11:25:10.896  3897  3975 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 11:25:10.898  3897  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 11:25:10.959  1034  1894 W libprocessgroup: failed to open /acct/uid_10008/pid_6540/cgroup.procs: No such file or directory
,08-16 11:25:10.965  7009  7009 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 11:25:10.973  3897  3897 D HeadsetService: Received stop request...Stopping profile...
08-16 11:25:10.978  3897  3897 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 11:25:10.978  3897  3897 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 11:25:10.978  3897  4009 D HeadsetStateMachine: Exit Disconnected: -1
08-16 11:25:10.978  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a118aad
,08-16 11:25:10.984  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 11:25:10.985  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 11:25:10.985  3897  3897 D A2dpService: Received stop request...Stopping profile...
08-16 11:25:10.985  3897  4067 D A2dpStateMachine: Exit Disconnected: -1
08-16 11:25:10.987  3897  3897 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 11:25:10.985  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-16 11:25:10.987  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 11:25:10.989  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 11:25:10.992  3897  3897 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 11:25:10.992  3897  3897 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 11:25:10.993  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a118aad
,08-16 11:25:10.993  3897  3972 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 11:25:10.995  3897  3897 D HeadsetStateMachine: Unbinding service...
08-16 11:25:10.996  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-16 11:25:10.996  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 11:25:10.998  3897  3897 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 11:25:10.998  3897  3897 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 11:25:10.998  3897  3897 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 11:25:10.998  3897  3897 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-16 11:25:10.998  3897  3897 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 11:25:10.998  3897  3897 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 11:25:10.998  3897  3897 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 11:25:10.999  3897  3897 D HidService: Received stop request...Stopping profile...
08-16 11:25:11.000  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a118aad
08-16 11:25:11.001  3897  3897 D HealthService: Received stop request...Stopping profile...
08-16 11:25:11.002  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a118aad
08-16 11:25:11.003  6956  6956 D BluetoothInputDevice: Proxy object disconnected
08-16 11:25:11.003  6956  6956 D HidProfile: Bluetooth service disconnected
08-16 11:25:11.005  3897  3897 D PanService: Received stop request...Stopping profile...
08-16 11:25:11.005  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a118aad
,08-16 11:25:11.007  3897  3897 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 11:25:11.007  3897  3897 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 11:25:11.008  3897  3897 D BtGatt.GattService: stop()
08-16 11:25:11.008  3897  3897 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 11:25:11.009  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a118aad
08-16 11:25:11.009  6956  6956 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 11:25:11.009  6956  6956 D PanProfile: Bluetooth service disconnected
08-16 11:25:11.010  3897  3897 D BluetoothMapService: Received stop request...Stopping profile...
08-16 11:25:11.010  3897  3897 D BluetoothMapService: stop()
08-16 11:25:11.010  3897  3897 D BluetoothMapEmailAppObserver: deinitObservers()
,08-16 11:25:11.010  3897  3897 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 11:25:11.011  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a118aad
08-16 11:25:11.012  3897  3897 I BluetoothA2dpServiceJni: cleanupNative
08-16 11:25:11.012  3897  4068 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 11:25:11.012  3897  3897 I GKI_LINUX: GKI_exit_task 2 done
08-16 11:25:11.012  3897  3897 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 11:25:11.012  6956  6956 D BluetoothMap: Proxy object disconnected
08-16 11:25:11.012  6956  6956 D MapProfile: Bluetooth service disconnected
08-16 11:25:11.012  3897  3897 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 11:25:11.012  3897  3897 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 11:25:11.013  3897  3897 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 11:25:11.013  3897  3897 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 11:25:11.013  3897  3897 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 11:25:11.014  3897  3897 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 11:25:11.014  3897  3897 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 11:25:11.015  3897  3897 V BluetoothMapService: Handler(): got msg=4
08-16 11:25:11.015  3897  3897 D BluetoothMapService: MAP Service closeService in
08-16 11:25:11.015  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 11:25:11.015  3897  3897 V BluetoothMapService: MAP Service closeService out
08-16 11:25:11.015  3897  3897 D BluetoothMapService: cleanup()
08-16 11:25:11.015  3897  3897 D BluetoothMapService: MAP Service closeService in
08-16 11:25:11.015  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 11:25:11.015  3897  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 11:25:11.015  3897  3897 V BluetoothMapService: MAP Service closeService out
08-16 11:25:11.015  3897  3972 D BluetoothAdapterProperties: Setting state to 10
08-16 11:25:11.015  3897  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 11:25:11.016  1034  1110 D BluetoothManagerService: Message: 60
08-16 11:25:11.016  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 11:25:11.016  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 11:25:11.017  3897  3972 I BluetoothAdapterState: Entering OffState
08-16 11:25:11.017  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:25:11.017  1034  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 11:25:11.018  6956  6976 D BluetoothPan: onBluetoothStateChange on: false
08-16 11:25:11.018  6956  6975 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 11:25:11.019  6956  6976 D BluetoothPbap: onBluetoothStateChange: up=false,
08-16 11:25:11.020  1851  2375 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:25:11.020  1851  2668 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:25:11.021  6956  6975 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 11:25:11.021  1034  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:25:11.022  1034  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 11:25:11.022  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 11:25:11.025  1034  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 11:25:11.025  1034  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 11:25:11.025  1034  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@31741d0f mBinding = false
08-16 11:25:11.026  1034  1110 D BluetoothManagerService: Sending unbind request.
08-16 11:25:11.027  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 11:25:11.030  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:11.030  1940  2124 D LGBluetoothAPIService: Message: 2
08-16 11:25:11.031  1940  2124 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@129cb714 mBinding = false
,08-16 11:25:11.031  1940  2124 D LGBluetoothAPIService: Sending unbind request.
,08-16 11:25:11.033  3897  3975 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 11:25:11.034  3897  3897 I GKI_LINUX: GKI_exit_task 1 done
08-16 11:25:11.034  3897  3897 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 11:25:11.034  3897  3897 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 11:25:11.034  3897  3897 I art     : --- WEIRD: removing null entry 246
08-16 11:25:11.034  3897  3897 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 11:25:11.034  3897  3897 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 11:25:11.035  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:11.035  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:11.036  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:11.036  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 11:25:11.042  6956  6956 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 11:25:11.043  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 11:25:11.043  6956  6956 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-16 11:25:11.045  3897  3897 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 11:25:11.047  1601  1601 D BluetoothAdapter: 185590748: getState() :  mService = null. Returning STATE_OFF
08-16 11:25:11.047  1601  1601 D BluetoothAdapter: 185590748: getState() :  mService = null. Returning STATE_OFF
08-16 11:25:11.047  3897  3897 I art     : System.exit called, status: 0
08-16 11:25:11.047  3897  3897 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 11:25:11.048  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 11:25:11.053  7009  7009 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 11:25:11.054  6956  6956 D DockEventReceiver: finishStartingService: stopping service
08-16 11:25:11.054  7009  7009 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 11:25:11.057  7009  7009 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 11:25:11.058  7009  7009 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 11:25:11.058  7009  7009 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 11:25:11.060  7009  7009 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-16 11:25:11.066  7009  7009 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 11:25:11.069   320  2150 V AudioFlinger: 3897 died, releasing its sessions
08-16 11:25:11.069   320  2150 V AudioFlinger:  pid 1851 @ 0
08-16 11:25:11.069   320  2150 V AudioFlinger:  pid 3483 @ 1
08-16 11:25:11.069   320  2150 V AudioFlinger:  pid 3483 @ 2
08-16 11:25:11.070  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 11:25:11.075  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 11:25:11.078  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:11.104  1034  1925 I ActivityManager: Process com.android.bluetooth (pid 3897) has died
08-16 11:25:11.104  1034  1925 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 11:25:11.108  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 11:25:11.109  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 11:25:11.110  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:11.114  7009  7009 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 11:25:11.115  6980  6980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 11:25:11.115  6980  6980 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 11:25:11.115  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:11.117  7009  7009 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-16 11:25:11.125  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:11.132  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 11:25:11.136  6956  6956 D BluetoothPermissionRequest: onReceive
08-16 11:25:11.138  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 11:25:11.139  6956  6956 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 11:25:11.140  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 11:25:11.203  1034  2049 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7058 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 11:25:11.213  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:11.214  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:11.217  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 11:25:11.222  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:11.231  6980  6980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 11:25:11.231  6980  6980 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 11:25:11.232  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 11:25:11.239  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:11.246  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:11.253  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:11.254  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:11.259  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 11:25:11.276  7058  7058 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 11:25:11.277  7058  7058 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 11:25:11.277  7058  7058 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 11:25:11.278  7058  7058 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 11:25:11.299  7058  7058 D BluetoothAdapterApp: Loading JNI Library
,08-16 11:25:11.319  1034  1987 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7075 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 11:25:11.336  7058  7058 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@a5a7b8a Instance Count = 1
,08-16 11:25:11.342  7058  7058 D BluetoothAdapterApp: onCreate
,08-16 11:25:11.370  7058  7058 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 11:25:11.370  7058  7058 D ProfileConfigQcom: Adding HeadsetService
08-16 11:25:11.370  7058  7058 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 11:25:11.370  7058  7058 D ProfileConfigQcom: Adding A2dpService
08-16 11:25:11.371  7058  7058 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 11:25:11.371  7058  7058 D ProfileConfigQcom: Adding HidService
08-16 11:25:11.371  7058  7058 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 11:25:11.371  7058  7058 D ProfileConfigQcom: Adding HealthService
08-16 11:25:11.372  7058  7058 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 11:25:11.373  7058  7058 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 11:25:11.373  7058  7058 D ProfileConfigQcom: Adding PanService
08-16 11:25:11.373  7058  7058 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 11:25:11.373  7058  7058 D ProfileConfigQcom: Adding GattService
08-16 11:25:11.374  7058  7058 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 11:25:11.374  7058  7058 D ProfileConfigQcom: Adding BluetoothMapService
08-16 11:25:11.374  7058  7058 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 11:25:11.376  7058  7058 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 11:25:11.381  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 11:25:11.383  7058  7058 V LGMDMManagerInternal: Create singleton instance
08-16 11:25:11.412  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 11:25:11.415  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 11:25:11.425  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 11:25:11.450  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 11:25:11.450  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 11:25:11.450  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-16 11:25:11.450  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 11:25:11.453  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 11:25:11.454  7075  7095 W FormManager: Network not available. Please check & try again.
08-16 11:25:11.466  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 11:25:11.467  7075  7096 V FormManager: Network unavailable.
08-16 11:25:11.467  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 11:25:11.467  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 11:25:11.467  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 11:25:11.468  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,08-16 11:25:11.470  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 11:25:11.470  7075  7096 V FormManager: Network unavailable.
08-16 11:25:11.478  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 11:25:11.478  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 11:25:11.478  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:11.480  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:11.485  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 11:25:11.485  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 11:25:11.485  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 11:25:11.486  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:11.487  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:11.487  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 11:25:11.493  4324  7099 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 11:25:11.496  7029  7029 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 11:25:11.498  4324  7100 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 11:25:11.498  4324  7100 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 11:25:11.502  1034  1918 I ActivityManager: Killing 6034:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 11:25:11.537  1034  1850 W libprocessgroup: failed to open /acct/uid_10011/pid_6034/cgroup.procs: No such file or directory
,08-16 11:25:11.541  7075  7103 W FormManager: Network not available. Please check & try again.
08-16 11:25:11.544  6980  6980 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 11:25:11.545  6980  6980 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 11:25:11.545  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:11.546  7075  7104 V FormManager: Network unavailable.
08-16 11:25:11.552  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 11:25:11.553  7075  7104 V FormManager: Network unavailable.
,08-16 11:25:11.566  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:11.568  1034  2049 I ActivityManager: Killing 6056:com.android.contacts/u0a19 (adj 15): empty #17
,08-16 11:25:11.604  1034  2013 W libprocessgroup: failed to open /acct/uid_10019/pid_6056/cgroup.procs: No such file or directory
,08-16 11:25:11.641  7009  7009 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 11:25:11.646  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-16 11:25:11.648  7009  7009 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 11:25:11.698  7009  7009 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:11.698  7009  7009 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:11.709  7009  7009 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 11:25:11.712  7009  7009 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 11:25:11.712  7009  7009 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 11:25:11.712  7009  7009 V SoundPool: doLoad: loading sample sampleID=1
08-16 11:25:11.714  7009  7009 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 11:25:11.716  7009  7107 V SoundPool: Start decode
,08-16 11:25:11.716  7009  7107 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-16 11:25:11.724   320  2151 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 11:25:11.724   320  2151 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 11:25:11.724   320  2151 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 11:25:11.725   320  2151 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 11:25:11.725   320  2151 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 11:25:11.725   320  2151 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 11:25:11.725   320  2151 V MediaPlayerService: player type = 3
08-16 11:25:11.725   320  2151 V AwesomePlayer: AwesomePlayer create()
08-16 11:25:11.726  6693  6693 D UEI.SmartControl: QS Service created
08-16 11:25:11.726  7009  7009 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 11:25:11.726   320  2151 V AwesomePlayer: reset_l() 
,08-16 11:25:11.727   320  2151 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:11.727   320  2151 V AwesomePlayer: setAudioSink() 
08-16 11:25:11.727   320  2151 V AwesomePlayer: reset_l() 
08-16 11:25:11.727   320  2151 V AudioCache: notify(0xb1432380, 8, 0, 0)
08-16 11:25:11.727   320  2151 V AudioCache: ignored
08-16 11:25:11.727   320  2151 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:11.727   320  2151 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 11:25:11.728   320  2151 V AwesomePlayer: setDataSource_l dataSource
08-16 11:25:11.728   320  2151 V LGParserOSAL: SniffLGParser start
08-16 11:25:11.728   320  2151 V LGParserOSAL: MainType:5, SubType=0
08-16 11:25:11.728   320  2151 V LGParserOSAL: #### check Mime : application/ogg
08-16 11:25:11.728   320  2151 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 11:25:11.728   320  2151 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 11:25:11.731  7009  7009 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 11:25:11.732  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 11:25:11.754  7009  7009 V LGMDMManager: Create singleton instance
,08-16 11:25:11.755  6693  6693 I UEI.SmartControl: Service initServices...
08-16 11:25:11.756  6693  6693 D UEI.SmartControl: QS start get config
08-16 11:25:11.799   320  2151 V LGParserOSAL: supported mime: application/ogg
,08-16 11:25:11.799   320  2151 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 11:25:11.799   320  2151 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 11:25:11.799   320  2151 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 11:25:11.799   320  2151 V AwesomePlayer: AudioTrack Setting
08-16 11:25:11.799   320  2151 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 11:25:11.799   320  2151 V AwesomePlayer: setAudioSource() 
08-16 11:25:11.800   320  2151 V MediaPlayerService: prepare
08-16 11:25:11.800   320  2151 V AwesomePlayer: prepareAsync_l() 
08-16 11:25:11.800   320  2151 V MediaPlayerService: wait for prepare
,08-16 11:25:11.802   320  7108 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 11:25:11.803   320  7108 V AwesomePlayer: initAudioDecoder() 
08-16 11:25:11.803   320  7108 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 11:25:11.803   320  7108 V AudioSystem: isOffloadSupported()
08-16 11:25:11.803   320  7108 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 11:25:11.803   320  7108 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 11:25:11.803   320  7108 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 11:25:11.803   320  7108 V AwesomePlayer: getUseOffload() = 0 
08-16 11:25:11.803   320  7108 V OMXCodec: OMXCodec::Create
08-16 11:25:11.803   320  7108 V OMXCodec: findMatchingCodecs()
08-16 11:25:11.803   320  7108 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 11:25:11.804   320  7108 V OMXCodec: matchingCodecs.size()=1
08-16 11:25:11.804   320  7108 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 11:25:11.808   320  7108 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 11:25:11.808   320  7108 V LGCodecAdapter: LG Codec Adapter start
08-16 11:25:11.808   320  7108 V OMXCodec: OMXCodec Createtor
08-16 11:25:11.808   320  7108 V OMXCodec: setComponentRole
08-16 11:25:11.808   320  7108 V OMXCodec: configureCodec protected=0
08-16 11:25:11.808   320  7108 V LGCodecAdapter: called getLGCodecSpecificData
08-16 11:25:11.809   320  7108 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 11:25:11.809   320  7108 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 11:25:11.809   320  7108 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 11:25:11.809   320  7108 V LGCodecOSAL: Not support LGCodec
08-16 11:25:11.809   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 11:25:11.809   320  7108 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 11:25:11.809   320  7108 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 11:25:11.809   320  7108 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 11:25:11.809   320  7108 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 11:25:11.809   320  7108 V AudioSystem: isOffloadSupported()
08-16 11:25:11.810   320  7108 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 11:25:11.810   320  7108 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 11:25:11.810   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 11:25:11.810   320  7108 V OMXCodec: init()
08-16 11:25:11.810   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 11:25:11.810   320  7108 V OMXCodec: allocateBuffers
08-16 11:25:11.810   320  7108 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 11:25:11.810   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 11:25:11.811   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-16 11:25:11.811   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-16 11:25:11.811   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-16 11:25:11.811   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-16 11:25:11.811   32,0  7108 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 11:25:11.811   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 11:25:11.811   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-16 11:25:11.812   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-16 11:25:11.812   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-16 11:25:11.812   320  7108 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9060 on output port
08-16 11:25:11.812   320  7108 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 11:25:11.812   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 11:25:11.812   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 11:25:11.812   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 11:25:11.812   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 11:25:11.812   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 11:25:11.812   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 11:25:11.812   320  7108 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 11:25:11.812   320  7108 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 11:25:11.812   320  7108 V AudioCache: notify(0xb1432380, 5, 0, 0)
08-16 11:25:11.812   320  7108 V AudioCache: ignored
08-16 11:25:11.812   320  7108 V AudioCache: notify(0xb1432380, 1, 0, 0)
08-16 11:25:11.812   320  7108 V AudioCache: prepared
08-16 11:25:11.812   320  2151 V AudioCache: wait - success
08-16 11:25:11.812   320  2151 V MediaPlayerService: start
08-16 11:25:11.813   320  2151 V AwesomePlayer: play_l() 
08-16 11:25:11.813   320  2151 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 11:25:11.813   320  2151 V AwesomePlayer: createAudioPlayer_l
08-16 11:25:11.813   320  2151 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 11:25:11.813   320  2151 V AwesomePlayer: startAudioPlayer_l() 
08-16 11:25:11.813   320  2151 D AudioPlayer: start of Playback, useOffload 0
08-16 11:25:11.813   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 11:25:11.813   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-16 11:25:11.824   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 11:25:11.824   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 11:25:11.824   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 11:25:11.824   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 11:25:11.824   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 11:25:11.824   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 11:25:11.824   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-16 11:25:11.824   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045036128
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 11:25:11.825   320  7110 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 11:25:11.825   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 11:25:11.826   320  2151 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 11:25:11.827   320  2151 V AudioCache: notify(0xb1432380, 6, 0, 0)
08-16 11:25:11.827   320  2151 V AudioCache: ignored
08-16 11:25:11.827   320  2151 V MediaPlayerService: wait for playback complete
08-16 11:25:11.828   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.829   320  7111 V AudioCache: memcpy(0xaf006000, 0xb16e3000, 4096)
,08-16 11:25:11.831   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.831   320  7111 V AudioCache: memcpy(0xaf007000, 0xb16e3000, 4096)
08-16 11:25:11.832   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.832   320  7111 V AudioCache: memcpy(0xaf008000, 0xb16e3000, 4096)
08-16 11:25:11.833   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.833   320  7111 V AudioCache: memcpy(0xaf009000, 0xb16e3000, 4096)
08-16 11:25:11.834   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.834   320  7111 V AudioCache: memcpy(0xaf00a000, 0xb16e3000, 4096)
08-16 11:25:11.834   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.834   320  7111 V AudioCache: memcpy(0xaf00b000, 0xb16e3000, 4096)
08-16 11:25:11.834   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.834   320  7111 V AudioCache: memcpy(0xaf00c000, 0xb16e3000, 4096)
,08-16 11:25:11.834   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.834   320  7111 V AudioCache: memcpy(0xaf00d000, 0xb16e3000, 4096)
,08-16 11:25:11.836   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.836   320  7111 V AudioCache: memcpy(0xaf00e000, 0xb16e3000, 4096)
08-16 11:25:11.836   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.836   320  7111 V AudioCache: memcpy(0xaf00f000, 0xb16e3000, 4096)
08-16 11:25:11.836   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.836   320  7111 V AudioCache: memcpy(0xaf010000, 0xb16e3000, 4096)
,08-16 11:25:11.836   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.836   320  7111 V AudioCache: memcpy(0xaf011000, 0xb16e3000, 4096)
08-16 11:25:11.837   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.837   320  7111 V AudioCache: memcpy(0xaf012000, 0xb16e3000, 4096)
08-16 11:25:11.837   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.837   320  7111 V AudioCache: memcpy(0xaf013000, 0xb16e3000, 4096)
08-16 11:25:11.838   320  7111 V AudioCache: write(0xb16e3000, 4096)
,08-16 11:25:11.838   320  7111 V AudioCache: memcpy(0xaf014000, 0xb16e3000, 4096)
08-16 11:25:11.838   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.838   320  7111 V AudioCache: memcpy(0xaf015000, 0xb16e3000, 4096)
08-16 11:25:11.839   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.839   320  7111 V AudioCache: memcpy(0xaf016000, 0xb16e3000, 4096)
08-16 11:25:11.840   320  7111 V AudioCache: write(0xb16e3000, 4096)
,08-16 11:25:11.840   320  7111 V AudioCache: memcpy(0xaf017000, 0xb16e3000, 4096)
08-16 11:25:11.840   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.840   320  7111 V AudioCache: memcpy(0xaf018000, 0xb16e3000, 4096)
08-16 11:25:11.841   320  7111 V AudioCache: write(0xb16e3000, 4096)
,08-16 11:25:11.841   320  7111 V AudioCache: memcpy(0xaf019000, 0xb16e3000, 4096),
08-16 11:25:11.842   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.842   320  7111 V AudioCache: memcpy(0xaf01a000, 0xb16e3000, 4096)
,08-16 11:25:11.843   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.843  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 11:25:11.843   320  7111 V AudioCache: memcpy(0xaf01b000, 0xb16e3000, 4096)
08-16 11:25:11.844  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 11:25:11.845   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.845   320  7111 V AudioCache: memcpy(0xaf01c000, 0xb16e3000, 4096)
,08-16 11:25:11.846   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.846   320  7111 V AudioCache: memcpy(0xaf01d000, 0xb16e3000, 4096)
08-16 11:25:11.847  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9614
08-16 11:25:11.848   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.848   320  7111 V AudioCache: memcpy(0xaf01e000, 0xb16e3000, 4096)
08-16 11:25:11.848   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.849   320  7111 V AudioCache: memcpy(0xaf01f000, 0xb16e3000, 4096)
,08-16 11:25:11.849   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.849   320  7111 V AudioCache: memcpy(0xaf020000, 0xb16e3000, 4096)
08-16 11:25:11.850   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.850   320  7111 V AudioCache: memcpy(0xaf021000, 0xb16e3000, 4096)
08-16 11:25:11.851   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.851   320  7111 V AudioCache: memcpy(0xaf022000, 0xb16e3000, 4096)
08-16 11:25:11.851   320  7111 V AudioCache: write(0xb16e3000, 4096)
,08-16 11:25:11.851   320  7111 V AudioCache: memcpy(0xaf023000, 0xb16e3000, 4096)
08-16 11:25:11.852   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.852   320  7111 V AudioCache: memcpy(0xaf024000, 0xb16e3000, 4096)
08-16 11:25:11.853   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.853   320  7111 V AudioCache: memcpy(0xaf025000, 0xb16e3000, 4096)
08-16 11:25:11.853   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.853   320  7111 V AudioCache: memcpy(0xaf026000, 0xb16e3000, 4096)
,08-16 11:25:11.854   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.854   320  7111 V AudioCache: memcpy(0xaf027000, 0xb16e3000, 4096)
08-16 11:25:11.855   320  7111 V AudioCache: write(0xb16e3000, 4096)
,08-16 11:25:11.855   320  7111 V AudioCache: memcpy(0xaf028000, 0xb16e3000, 4096)
08-16 11:25:11.856   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.856   320  7111 V AudioCache: memcpy(0xaf029000, 0xb16e3000, 4096)
08-16 11:25:11.857   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.857   320  7111 V AudioCache: memcpy(0xaf02a000, 0xb16e3000, 4096)
08-16 11:25:11.858   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.858   320  7111 V AudioCache: memcpy(0xaf02b000, 0xb16e3000, 4096)
,08-16 11:25:11.858   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.858   320  7111 V AudioCache: memcpy(0xaf02c000, 0xb16e3000, 4096)
08-16 11:25:11.859   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.859   320  7111 V AudioCache: memcpy(0xaf02d000, 0xb16e3000, 4096)
08-16 11:25:11.860   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.860   320  7111 V AudioCache: memcpy(0xaf02e000, 0xb16e3000, 4096)
08-16 11:25:11.860   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.861   320  7111 V AudioCache: memcpy(0xaf02f000, 0xb16e3000, 4096)
08-16 11:25:11.861   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.861   320  7111 V AudioCache: memcpy(0xaf030000, 0xb16e3000, 4096)
,08-16 11:25:11.862   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.862   320  7111 V AudioCache: memcpy(0xaf031000, 0xb16e3000, 4096)
08-16 11:25:11.863   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.863   320  7111 V AudioCache: memcpy(0xaf032000, 0xb16e3000, 4096)
08-16 11:25:11.863   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.863   320  7111 V AudioCache: memcpy(0xaf033000, 0xb16e3000, 4096)
08-16 11:25:11.864   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.864   320  7111 V AudioCache: memcpy(0xaf034000, 0xb16e3000, 4096)
08-16 11:25:11.865   320  7111 V AudioCache: write(0xb16e3000, 4096)
,08-16 11:25:11.865   320  7111 V AudioCache: memcpy(0xaf035000, 0xb16e3000, 4096)
08-16 11:25:11.865   320  7111 V AudioCache: write(0xb16e3000, 4096)
08-16 11:25:11.865   320  7111 V AudioCache: memcpy(0xaf036000, 0xb16e3000, 4096)
,08-16 11:25:11.866   320  7111 V AudioCache: write(0xb16e3000, 4096)
,08-16 11:25:11.866   320  7111 V AudioCache: memcpy(0xaf037000, 0xb16e3000, 4096)
,08-16 11:25:11.866   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 11:25:11.866   320  7111 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 11:25:11.866   320  7111 V AwesomePlayer: postAudioEOS() 
08-16 11:25:11.866   320  7111 V AudioCache: write(0xb16e3000, 280)
08-16 11:25:11.866   320  7111 V AudioCache: memcpy(0xaf038000, 0xb16e3000, 280)
,08-16 11:25:11.868   320  7108 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 11:25:11.868   320  7108 V AwesomePlayer: onStreamDone
,08-16 11:25:11.868   320  7108 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 11:25:11.868   320  7108 V AudioCache: notify(0xb1432380, 2, 0, 0)
08-16 11:25:11.868   320  7108 V AudioCache: playback complete
,08-16 11:25:11.868   320  7108 V AwesomePlayer: pause_l() 
08-16 11:25:11.868   320  7108 V AudioCache: notify(0xb1432380, 7, 0, 0)
08-16 11:25:11.868   320  2151 V AudioCache: wait - success
08-16 11:25:11.868   320  7108 V AudioCache: ignored
08-16 11:25:11.868   320  7108 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:11.868   320  2151 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 11:25:11.869   320  7108 D AudioPlayer: Pause Playback at 1068125
08-16 11:25:11.869   320  2151 V AwesomePlayer: reset_l() 
08-16 11:25:11.869   320  2151 V AudioCache: notify(0xb1432380, 8, 0, 0)
08-16 11:25:11.869   320  2151 V AudioCache: ignored
08-16 11:25:11.869   320  2151 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:11.869   320  2151 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 11:25:11.869   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 11:25:11.869   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 11:25:11.869   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 11:25:11.869   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
,08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 11:25:11.870   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
08-16 11:25:11.871   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:11.871   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 11:25:11.871   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 11:25:11.871   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 11:25:11.871   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 11:25:11.871   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 11:25:11.871   320  7110 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 11:25:11.871   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 11:25:11.871   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 11:25:11.871   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 11:25:11.872   320  2151 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 11:25:11.872   320  2151 D AudioPlayer: AudioPlayer releasing audio source
08-16 11:25:11.872   320  2151 D AudioPlayer: AudioPlayer done releasing audio source
08-16 11:25:11.872   320  2151 V AwesomePlayer: reset_l() 
08-16 11:25:11.873   320  2151 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:11.873   320  2151 V AwesomePlayer: ~AwesomePlayer call
08-16 11:25:11.873   320  2151 V AwesomePlayer: reset_l() 
08-16 11:25:11.873   320  2151 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:11.873  7009  7107 V SoundPool: close(31)
08-16 11:25:11.873  7009  7107 V SoundPool: pointer = 0x9fe8c000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 11:25:12.104  6693  6693 I UEI.SmartControl: Supports setup maps: true
08-16 11:25:12.107  6693  6693 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 11:25:12.107  6693  6693 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 11:25:12.107  6693  6693 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 11:25:12.107  6693  6693 I UEI.SmartControl: ### init IR Blaster...
08-16 11:25:12.110  6693  6693 D serial_port: Configuring serial port
08-16 11:25:12.111  6693  6693 E UEI.SmartControl: UEIBLaster setting for 616
08-16 11:25:12.111  6693  6693 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 11:25:12.111  6693  6693 I UEI.SmartControl: configuring settings for MAXQ616
08-16 11:25:12.111  6693  6693 I UEI.SmartControl: Get version...
,08-16 11:25:12.129  6693  7112 D UEI.SmartControl: serial port data available: 21,
,08-16 11:25:12.155  6693  6693 D UEI.SmartControl: MAXQ616 A2-X4 software.,
08-16 11:25:12.155  6693  6693 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 11:25:12.155  6693  6693 I UEI.SmartControl: QS saving settings...
08-16 11:25:12.156  6693  6693 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 11:25:12.170  6693  7112 D UEI.SmartControl: serial port data available: 4
08-16 11:25:12.203  6693  6693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 11:25:12.215  6693  6693 E UEI.SmartControl: Services init done
08-16 11:25:12.215  6693  6693 D UEI.SmartControl: QS Service init finished
08-16 11:25:12.216  6693  7121 I UEI.SmartControl: Device manager: loading config....
08-16 11:25:12.216  6693  7121 D UEI.SmartControl: ----------- loading internal config...
08-16 11:25:12.217  6693  6693 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 11:25:12.217  6693  6693 D UEI.SmartControl: QS Service version code: 201091
08-16 11:25:12.219  6693  6693 D UEI.SmartControl: Service requested: Control
08-16 11:25:12.222  6693  7121 E UEI.SmartControl: Loading SETTINGS...
,08-16 11:25:12.226  6693  6693 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 11:25:12.228  6693  7121 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 11:25:12.231  7009  7009 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 11:25:12.232  6693  6693 D UEI.SmartControl: Internal service binding...
,08-16 11:25:12.233  6693  6709 I UEI.SmartControl: ------ IControl API: 11
08-16 11:25:12.233  6693  6709 D UEI.SmartControl: File observer start...
08-16 11:25:12.234  6693  6709 E UEI.SmartControl: IR Port is disabled: false
08-16 11:25:12.235  6693  6709 D UEI.SmartControl: Starting file observer...
08-16 11:25:12.235  6693  7120 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 11:25:12.236  6693  7120 D UEI.SmartControl: -----service ready thread exits
,08-16 11:25:12.239  6693  6709 I UEI.SmartControl: Registering callback...
08-16 11:25:12.240  6693  6708 I UEI.SmartControl: ------ IControl API: 19
08-16 11:25:12.242  6693  6708 I UEI.SmartControl: Registering Services Ready callback...
08-16 11:25:12.242  6693  6708 I UEI.SmartControl: Notify client services are ready...
08-16 11:25:12.244  7009  7027 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 11:25:12.244  7009  7105 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 11:25:12.245  7009  7105 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 11:25:12.245  7009  7009 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 11:25:12.246  7009  7009 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 11:25:12.246  6693  6709 I UEI.SmartControl: ------ IControl API: 8
08-16 11:25:12.247  7009  7009 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 11:25:12.248  7009  7009 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 11:25:12.248  7009  7009 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 11:25:12.248  7009  7009 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-16 11:25:12.249  7009  7009 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 11:25:12.249  7009  7009 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 11:25:12.252  7009  7009 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 11:25:12.254  7009  7009 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 11:25:12.255  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 11:25:12.255  7009  7009 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 11:25:12.256  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 11:25:12.257  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 11:25:12.259  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 11:25:12.259  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 11:25:12.261  7009  7009 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471339512260]
08-16 11:25:12.262  7009  7009 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 11:25:12.264  1034  1850 I ActivityManager: Killing 6579:com.lge.email/u0a23 (adj 15): empty #17
,08-16 11:25:12.287  7009  7123 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 11:25:12.305  1034  1574 W libprocessgroup: failed to open /acct/uid_10023/pid_6579/cgroup.procs: No such file or directory
,08-16 11:25:12.311  7009  7009 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 11:25:12.313  7009  7009 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 11:25:12.313  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 11:25:12.314  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 11:25:12.315  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 11:25:12.315  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 11:25:12.316  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 11:25:12.329  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 11:25:12.362  1034  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=492664873, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-16 11:25:12.363  1034  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c9a287e type 2 when 372008 com.google.android.gms} when 372008
08-16 11:25:12.375   315  7125 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 11:25:12.375  1034  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 11:25:12.399  2578  2578 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 11:25:12.418  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=492664873 [*alarm*], flags=0x0
,08-16 11:25:13.054  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:13.070  1034  1110 D Tethering: MasterInitialState.processMessage what=3
08-16 11:25:13.086  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:13.090  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:13.092  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:13.094  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:13.095  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:13.099  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 11:25:13.105  6486  6979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 11:25:13.115  1034  1110 D Tethering: MasterInitialState.processMessage what=3
,08-16 11:25:13.119  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:13.121  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:13.122  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:13.131  5780  5780 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 11:25:13.142  5780  5780 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 11:25:13.165  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:13.195  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:13.242  1034  1925 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7137 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 11:25:13.246  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:13.247  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 11:25:13.321  7137  7137 I AppUp4:AppBoxCP: onCreate
,08-16 11:25:13.322  7137  7137 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 11:25:13.332  7137  7137 I AppUp4:DB:  setFingerPrint start
08-16 11:25:13.333  7137  7137 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-16 11:25:13.342  7137  7137 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-16 11:25:13.342  7137  7137 I AppUp4:DB:  SDK version = 21
08-16 11:25:13.342  7137  7137 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-16 11:25:13.346  7137  7137 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-16 11:25:13.348  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 11:25:13.348  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:13.350  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 11:25:13.351  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 11:25:13.359  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 11:25:13.401  7137  7137 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 11:25:13.401  7137  7137 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:13.410  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cb52bc4
,08-16 11:25:13.410  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 11:25:13.410  7137  7137 D AppUp4:CustFacade: isPhone : true
,08-16 11:25:13.411  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-16 11:25:13.412  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 11:25:13.412  7137  7137 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-16 11:25:13.413  7137  7157 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 11:25:13.414  7137  7157 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 11:25:13.415  7137  7157 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 11:25:13.416  1034  1925 I ActivityManager: Killing 6087:com.android.gallery3d/u0a27 (adj 15): empty #17
08-16 11:25:13.473  1034  1649 W libprocessgroup: failed to open /acct/uid_10027/pid_6087/cgroup.procs: No such file or directory
,08-16 11:25:13.480  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:13.481  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 11:25:13.485  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:13.490  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 11:25:13.504  4324  7160 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 11:25:13.507  4324  7161 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:13.508  4324  7161 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 11:25:13.574  1034  1850 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7162 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 11:25:13.670  7162  7162 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 11:25:13.671  7162  7162 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 11:25:13.672  7162  7162 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 11:25:13.673  7162  7162 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 11:25:13.769  7162  7162 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 11:25:13.784  7162  7162 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 11:25:13.837  7162  7162 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 11:25:13.889  7162  7162 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 11:25:13.889  7162  7162 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:14.024  7162  7162 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 11:25:14.078  3483  3483 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 11:25:14.079  3483  3483 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:14.083  7075  7188 V FormManager: Network unavailable.
08-16 11:25:14.084  3483  3483 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 11:25:14.094  7162  7162 I HubEmail: JNI_OnLoad()
08-16 11:25:14.094  7162  7162 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 11:25:14.094  7162  7162 I HubEmail: registerNatives()
08-16 11:25:14.094  7162  7162 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 11:25:14.094  7162  7162 I HubEmail: registerNativeMethods()
08-16 11:25:14.094  7162  7162 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-16 11:25:14.094  7162  7162 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 11:25:14.146  1034  1574 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7191 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 11:25:14.150  7075  7187 W FormManager: Network not available. Please check & try again.
,08-16 11:25:14.152  7075  7188 V FormManager: Network unavailable.
,08-16 11:25:14.159  7162  7190 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:14.173  1034  1051 I ActivityManager: Killing 6151:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 11:25:14.245  1034  2031 W libprocessgroup: failed to open /acct/uid_10080/pid_6151/cgroup.procs: No such file or directory
,08-16 11:25:14.333  7191  7191 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:14.333  7191  7191 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:14.336  7191  7191 D PhoneMonitor: Register our PhoneStateListener
,08-16 11:25:14.353  7191  7191 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 11:25:14.356  7191  7191 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 11:25:14.380  7191  7191 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 11:25:14.381  7191  7191 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 11:25:14.382  7191  7191 D TelephonyAutoProfiling: [parse] Load xml
08-16 11:25:14.385  7191  7191 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 11:25:14.385  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 11:25:14.386  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 11:25:14.386  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 11:25:14.386  7191  7191 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 11:25:14.386  7191  7191 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 11:25:14.394  7191  7191 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 11:25:14.429  1034  2031 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7221 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 11:25:14.431  1034  2031 I ActivityManager: Killing 6614:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-16 11:25:14.496  1034  2049 W libprocessgroup: failed to open /acct/uid_10061/pid_6614/cgroup.procs: No such file or directory
,08-16 11:25:14.710  1034  2031 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7247 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-16 11:25:14.711  1034  2031 I ActivityManager: Killing 6176:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-16 11:25:14.795  1034  1918 W libprocessgroup: failed to open /acct/uid_10097/pid_6176/cgroup.procs: No such file or directory
,08-16 11:25:14.929  1034  1050 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7264 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 11:25:14.930  1034  1050 I ActivityManager: Killing 6655:com.lge.eula/1000 (adj 15): empty #17
08-16 11:25:14.985  1034  1649 W libprocessgroup: failed to open /acct/uid_1000/pid_6655/cgroup.procs: No such file or directory
,08-16 11:25:15.003  1034  1987 D WifiServiceImplEx: setWifiEnabled: true pid=6792, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 11:25:15.005  1034  1987 D WifiService: setWifiEnabled: true pid=6792, uid=10118
08-16 11:25:15.005  1034  1987 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 11:25:15.020  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 11:25:15.020  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 11:25:15.020  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-16 11:25:15.022  1034  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 11:25:15.022  1034  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 11:25:15.023  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 11:25:15.023  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 11:25:15.024  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 11:25:15.024  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 11:25:15.024  1034  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 11:25:15.024  1034  1537 E WifiHW  : unknown target_country: EU , set to default
08-16 11:25:15.024  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 11:25:15.024  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 11:25:15.024  1034  1537 I WifiUtil: gEnableBmps=1
08-16 11:25:15.034  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:15.034  1034  1536 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 11:25:15.039  7264  7264 I art     : Almond Protected OAT
08-16 11:25:15.097  7264  7264 D WeatherApplication: removeAccount
08-16 11:25:15.098  7264  7264 D WeatherApplication: Account.length = 0
08-16 11:25:15.098  7264  7264 E WeatherApplication: OPERATOR:OPEN
08-16 11:25:15.107  7264  7264 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:15
,08-16 11:25:15.110  7264  7264 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 11:25:15.110  7264  7264 D Weather.Utils: 2 : All the weather widget is gone.
08-16 11:25:15.115  7264  7264 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 11:25:15.117  7264  7264 D WeatherAncestor: connectivity changed - connection : true
08-16 11:25:15.119  7264  7264 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-16 11:25:15.129  7264  7264 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 11:25:15.129  7264  7264 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 11:25:15.129  7264  7264 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 11:25:15.150  7264  7264 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-16 11:25:15.150  7264  7264 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:15
08-16 11:25:15.186  1034  2031 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7283 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 11:25:15.189  1034  2031 I ActivityManager: Killing 6672:com.lge.bnr/1000 (adj 15): empty #17
08-16 11:25:15.245  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6672/cgroup.procs: No such file or directory
,08-16 11:25:15.315   277   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 11:25:15.315   277   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 11:25:15.315   277   383 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 11:25:15.315  7283  7301 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 11:25:15.316   277   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 11:25:15.316   277   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 11:25:15.316   277   383 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 11:25:15.317  7283  7301 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 11:25:15.327   277   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 11:25:15.327   277   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 11:25:15.327   277   383 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 11:25:15.332  7283  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 11:25:15.344   277   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 11:25:15.344   277   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 11:25:15.344   277   383 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 11:25:15.346  7283  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 11:25:15.595  7283  7283 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 11:25:15.611  7283  7283 I LibraryLoader: Loading: webviewchromium
,08-16 11:25:15.619  7283  7283 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 5266-5275)
08-16 11:25:15.620  7283  7283 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 11:25:15.630  7283  7283 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22f78a19}
08-16 11:25:15.633  7283  7283 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 11:25:15.634  7283  7283 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 11:25:15.656  7283  7283 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 11:25:15.657  7283  7283 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 11:25:15.681  1034  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 11:25:15.693  7283  7283 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 11:25:15.694   315   893 D SoftapController: Softap fwReload - Ok
,08-16 11:25:15.695  1034  1537 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (666ms)
08-16 11:25:15.704   315   893 D CommandListener: Setting iface cfg
08-16 11:25:15.704   315   893 D CommandListener: Trying to bring down wlan0
08-16 11:25:15.705   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 11:25:15.708   320  2150 V AudioPolicyService: registerClient() client 0xb558a880, uid 10093
,08-16 11:25:15.712  7283  7331 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 11:25:15.714  7283  7283 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 11:25:15.714  1034  1110 D Tethering: InitialState.processMessage what=4
08-16 11:25:15.714  7283  7283 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 11:25:15.715  1034  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 11:25:15.724  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 11:25:15.715  7333  7333 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:15.715  7333  7333 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 11:25:15.762  7333  7333 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 11:25:15.763  7283  7283 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:25:15.763  7283  7283 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:25:15.763  7283  7283 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:25:15.763  7283  7283 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:25:15.763  7283  7283 I Adreno-EGL: Remote Branch: 
08-16 11:25:15.763  7283  7283 I Adreno-EGL: Local Patches: 
08-16 11:25:15.763  7283  7283 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:25:15.800  7333  7333 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 11:25:15.801  7333  7333 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 11:25:15.816  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 11:25:15.816  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-16 11:25:15.816  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 11:25:15.817  1034  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 11:25:15.817  1034  1537 D WifiMonitor: connecting to supplicant
08-16 11:25:15.818  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 11:25:15.821  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:15.825  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 11:25:15.827  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:15.827  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:15.828  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:25:15.844  7283  7283 I NSApplication: Starting up...
08-16 11:25:15.870  7333  7333 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 11:25:15.890  1034  1953 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7358 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 11:25:15.891  1034  1918 I ActivityManager: Killing 6112:com.android.vending/u0a44 (adj 15): empty #17
,08-16 11:25:15.907   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 306us total 16.232ms
,08-16 11:25:15.921   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 13.225ms
,08-16 11:25:15.933   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 253us total 12.178ms
,08-16 11:25:15.936  7333  7333 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 11:25:15.939  7333  7333 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 11:25:15.939  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 11:25:15.940  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 11:25:15.940  1034  7375 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 11:25:15.940  1034  7375 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 11:25:15.940  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 11:25:15.940  1034  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 11:25:15.941  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 11:25:15.941  1034  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 11:25:15.941  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:15.941  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:15.942  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:15.942  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:15.942  1034  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 11:25:15.942  1034  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 11:25:15.943  1034  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 11:25:15.943  1034  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 11:25:15.943  1034  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 11:25:15.945  7333  7333 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 11:25:15.945  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 11:25:15.945  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 11:25:15.945  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 11:25:15.945  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 11:25:15.945  1034  7375 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 11:25:15.945  1034  7375 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 11:25:15.946  1034  2049 W libprocessgroup: failed to open /acct/uid_10044/pid_6112/cgroup.procs: No such file or directory
,08-16 11:25:15.956  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 11:25:15.956  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-16 11:25:15.956  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 11:25:15.957  1034  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 11:25:15.958  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:15.958  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:15.958  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:15.958  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:15.958  1034  1537 D WifiNative-wlan0: SET update_config 1: returned true
08-16 11:25:15.958  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 11:25:15.958  1034  1537 D WifiConfigStore: Loading config and enabling all networks 
08-16 11:25:15.958  1034  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 11:25:15.959  1940  1940 D WfdService: Waiting for WifiP2p enabling
08-16 11:25:15.959  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:15.960  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 11:25:15.960  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:15.961  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:15.961  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:15.961  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:15.961  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:15.961  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:15.961  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:15.961  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:15.961  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:15.961  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:15.961  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:15.961  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 11:25:15.961  1034  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 11:25:15.962  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:15.962  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:15.962  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:15.962  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:15.962  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:15.962  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:15.962  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:15.965  1034  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 11:25:15.970  1034  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 11:25:15.970  1034  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 11:25:15.971  1034  1537 D WifiStateMachine: enableVerboseLogging : level 2
08-16 11:25:15.971  1034  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-16 11:25:15.971  1034  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 11:25:15.971  1034  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 11:25:15.972  1034  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 11:25:15.972  1034  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 11:25:15.972  1034  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 11:25:15.972  1034  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 11:25:15.972  1034  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 11:25:15.972  1034  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 11:25:15.972  1034  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 11:25:15.972  1034  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 11:25:15.973  1034  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 11:25:15.973  1034  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 11:25:15.973  1034  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 11:25:15.973  7358  7358 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 11:25:15.974  1940  1940 D WfdsService: Supplicant Connection state is changed : true
08-16 11:25:15.974  1940  2327 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 11:25:15.974  1940  2327 D WfdsService: Set the WFDS Monitor: true
08-16 11:25:15.974  1940  2327 D WfdsMonitor: WfdsMonitorThread create
08-16 11:25:15.974  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 11:25:15.974  1034  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 11:25:15.974  1940  2327 D WfdsMonitor: WFDS Monitor is created and started
08-16 11:25:15.974  1940  2327 D WfdsService: WiFi: Supplicant connection re-established
08-16 11:25:15.975  1034  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 11:25:15.975  1034  1537 D WifiNative-HAL: Setting external_sim to 1
08-16 11:25:15.975  1034  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 11:25:15.975  1034  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 11:25:15.975  1034  1537 I WifiNative-HAL: startHal
08-16 11:25:15.975  1034  1537 D wifi    : setting scan oui 0xaf72c300
08-16 11:25:15.975  1940  7376 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 11:25:15.975  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 11:25:15.975  1034  1537 I WifiNative-HAL: startHal
08-16 11:25:15.975  1034  1537 D wifi    : setting scan oui 0xaf72c300
08-16 11:25:15.975  1034  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 11:25:15.976  1940  7376 E CtrlSupplicant: Succeed to open control connection
08-16 11:25:15.976  1940  7376 E CtrlSupplicant: Succeed to open monitor connection
08-16 11:25:15.976  1034  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 11:25:15.976  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 11:25:15.976  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 11:25:15.976  1940  7376 D WfdsMonitor: Supplicant connection established
08-16 11:25:15.977  1940  2327 D WfdsService: Connected to the supplicant for wfds
08-16 11:25:15.977  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 11:25:15.977  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 11:25:15.977  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 11:25:15.977  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 11:25:15.977  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 11:25:15.978  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 11:25:15.978  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 11:25:15.981  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 11:25:15.981  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 11:25:15.981  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 11:25:15.981  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 11:25:15.981  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 11:25:15.981  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 11:25:15.981  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 11:25:15.982  7333  7333 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 11:25:15.982  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 11:25:15.982  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 11:25:15.982  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 11:25:15.982  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 11:25:15.983  1034  1537 E WifiNative: : [375,629,151 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 11:25:15.983  1034  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 11:25:15.984  1034  1537 D WifiNative-wlan0: RECONNECT: returned true
08-16 11:25:15.984  1034  1537 D WifiNative-wlan0: doString: [STATUS]
08-16 11:25:15.984  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 11:25:15.984  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 11:25:15.985  1034  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 11:25:15.985  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 11:25:15.985  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-16 11:25:15.986  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:15.987   315   893 D CommandListener: Setting iface cfg
08-16 11:25:15.987   315   893 D CommandListener: Trying to bring up p2p0
08-16 11:25:15.988  1034  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 11:25:15.988  1034  1536 D LGWifiP2pService: P2pEnablingState
08-16 11:25:15.988  1034  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:15.988  1034  1536 D LGWifiP2pService: P2p socket connection successful
08-16 11:25:15.988  1034  1536 D LGWifiP2pService: P2pEnabledState
08-16 11:25:15.989  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 11:25:15.989  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-16 11:25:15.990  1034  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:15.990  1034  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:15.990  1034  1555 I WifiNative-HAL: startHal
08-16 11:25:15.990  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf72c300
08-16 11:25:15.990  1034  1555 D wifi    : failed to get capabilities : -3
08-16 11:25:15.990  1034  1555 E WifiScanningService: could not get scan capabilities
08-16 11:25:15.991  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 11:25:15.991  1034  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 11:25:15.991  1034  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 11:25:15.992  1034  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 11:25:15.992  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 11:25:15.992  1940  1940 D WfdsService: WifiP2pState is changed : true
08-16 11:25:15.992  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=375638  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 11:25:15.992  1034  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 11:25:15.992  1940  2327 D WfdsService: Receive the WFDS_ENABLE Method
08-16 11:25:15.992  1940  2327 D WfdsService: Set the WFDS Monitor: true
08-16 11:25:15.992  1940  2327 D WfdsService: Connected to the supplicant for wfds
08-16 11:25:15.992  1940  2327 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 11:25:15.992  7333  7333 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 11:25:15.992  1940  2327 D WfdsService: selectPreferredScanChannel [36]
08-16 11:25:15.993  1940  2327 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 11:25:15.994  1034  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 11:25:15.994  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=375641  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 11:25:15.994  1034  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 11:25:15.995  1034  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 11:25:15.995  1034  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 11:25:15.995  1034  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 11:25:15.995  1034  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 11:25:15.995  1034  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 11:25:15.995  1034  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-16 11:25:15.995  7333  7333 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 11:25:15.995  1034  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 11:25:15.995  1034  1536 D LGWifiP2pService: before postfix = G3
08-16 11:25:15.995  1034  1536 D WifiServerServiceExt: postfix byte check : 2
08-16 11:25:15.995  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 11:25:15.995  1034  1536 D LGWifiP2pService: after postfix = G3
08-16 11:25:15.995  1034  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 11:25:15.996  1940  1940 D WfdsService: isConnected: false
08-16 11:25:15.996  1034  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 11:25:15.996  1034  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 11:25:15.996  1034  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 11:25:15.996  1034  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 11:25:15.996  1034  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 11:25:15.996  1034  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 11:25:15.996  1034  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 11:25:15.996  1034  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 11:25:15.996  7333  7333 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 11:25:15.997  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 11:25:15.997  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 11:25:15.997  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 11:25:15.997  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 11:25:15.997  1034  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 11:25:15.997  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 11:25:15.998  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:15.998  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:15.998  1034  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 11:25:15.998  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-16 11:25:15.998  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 11:25:15.998  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:15.998  7333  7333 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:15.998  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 11:25:15.999  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:15.999  7333  7333 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 11:25:15.999  1034  7375 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:15.999  1034  7375 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:15.999  7333  7333 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:15.999  1034  7375 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:15.999  1034  7375 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:15.999  1034  7375 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:15.999  1034  7375 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:15.999  7333  7333 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:15.999  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:15.999  1034  7375 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:15.999  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:15.999  1034  7375 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:15.999  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 11:25:15.999  1034  7375 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:15.999  1034  7375 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:16.000  1034  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 11:25:16.000  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 11:25:16.001  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 11:25:16.001  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 11:25:16.001  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 11:25:16.001  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 11:25:16.001  7333  7333 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 11:25:16.001  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 11:25:16.001  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 11:25:16.001  1034  7375 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 11:25:16.001  1034  7375 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 11:25:16.001  1940  7376 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:16.002  1940  7376 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:16.002  1034  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 11:25:16.002  1034  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 11:25:16.002  1034  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 11:25:16.002  1034  1537 D WifiNative-wlan0: doBoolean: SCAN
08-16 11:25:16.002  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 11:25:16.002  1034  1537 D WifiNative-wlan0: SCAN: returned false
08-16 11:25:16.003  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=375649  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 11:25:16.003  1034  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 11:25:16.003  1034  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 11:25:16.003  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=375650  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 11:25:16.004  1034  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:16.004  1034  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:16.004  1034  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 11:25:16.004  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 11:25:16.004  1034  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:16.005  1034  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:16.005  1034  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:16.005  1034  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 11:25:16.005  1034  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 11:25:16.005  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 11:25:16.005  1034  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 11:25:16.005  1034  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 11:25:16.007  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 11:25:16.007  1940  1940 D WfdsService: Update P2p Interface State: 3
08-16 11:25:16.009  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.009  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.009  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 11:25:16.009  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:16.009  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 11:25:16.014  1034  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 11:25:16.014  1034  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 11:25:16.014  1034  1536 D LGWifiP2pService: InactiveState
08-16 11:25:16.014  1034  1536 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.014  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.014  1034  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 11:25:16.015  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 11:25:16.015  7333  7333 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:16.015  7333  7333 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 11:25:16.015  7333  7333 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:16.016  7333  7333 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:16.016  1940  7376 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 11:25:16.016  1940  7376 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:16.016  1940  7376 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:16.016  1034  7375 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 11:25:16.017  1034  7375 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:16.017  1034  7375 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:16.017  1034  7375 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:16.017  1034  7375 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:16.017  1034  7375 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:16.017  1034  7375 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:16.017  1034  7375 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:16.017  1034  7375 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:16.017  1034  7375 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:16.017  1034  7375 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:16.017  1034  7375 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:16.017  1034  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 11:25:16.017  1034  1536 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.017  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.017  1034  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.017  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.017  1034  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1034  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1034  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1034  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1034  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.018  1940  2327 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 11:25:16.018  1034  1034 E WifiServerServiceExt: No p2p device connected
08-16 11:25:16.020  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:16.020  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:16.021  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:16.117  1034  1918 I art     : Explicit concurrent mark sweep GC freed 71229(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.357ms total 76.273ms
,08-16 11:25:16.215  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 11:25:16.217  6486  6979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 11:25:16.250  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:16.272  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 11:25:16.272  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:16.272  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 11:25:16.272  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 11:25:16.275  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 11:25:16.282  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cb52bc4
08-16 11:25:16.282  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 11:25:16.282  7137  7137 D AppUp4:CustFacade: isPhone : true
08-16 11:25:16.283  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-16 11:25:16.284  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 11:25:16.288  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:16.289  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 11:25:16.291  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 11:25:16.295  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:16.300  4324  7388 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 11:25:16.302  4324  7389 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:16.302  4324  7389 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 11:25:16.307  7162  7162 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 11:25:16.333  7162  7393 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 11:25:16.345  3483  3483 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 11:25:16.345  3483  3483 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:16.346  3483  3483 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 11:25:16.351  7191  7191 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 11:25:16.351  7191  7191 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 11:25:16.354  7075  7396 V FormManager: Network unavailable.
08-16 11:25:16.358  7075  7395 W FormManager: Network not available. Please check & try again.
,08-16 11:25:16.364  7075  7396 V FormManager: Network unavailable.
08-16 11:25:16.368  7264  7264 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:16
08-16 11:25:16.370  7264  7264 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 11:25:16.370  7264  7264 D Weather.Utils: 2 : All the weather widget is gone.
,08-16 11:25:16.371  7264  7264 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 11:25:16.371  7264  7264 D WeatherAncestor: connectivity changed - connection : true
08-16 11:25:16.371  7264  7264 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3086f1e2
08-16 11:25:16.374  7264  7264 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 11:25:16.374  7264  7264 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 11:25:16.374  7264  7264 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 11:25:16.374  7264  7264 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 11:25:16.375  7264  7264 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:16
08-16 11:25:16.404  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 11:25:16.404  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 11:25:16.404  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 11:25:16.404  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 11:25:16.404  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 11:25:16.405  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 11:25:16.405  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 11:25:16.405  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 11:25:16.405  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 11:25:16.405  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 11:25:16.405  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 11:25:16.412  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:16.415  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 11:25:16.421  7075  7399 W FormManager: Network not available. Please check & try again.
,08-16 11:25:16.423  7075  7400 V FormManager: Network unavailable.
08-16 11:25:16.426  7075  7400 V FormManager: Network unavailable.
08-16 11:25:16.426  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:16.443  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 11:25:16.446  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 11:25:16.449  7075  7402 W FormManager: Network not available. Please check & try again.
08-16 11:25:16.452  7075  7403 V FormManager: Network unavailable.
,08-16 11:25:16.455  7075  7403 V FormManager: Network unavailable.
08-16 11:25:16.455  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:16.468  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 11:25:16.469  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 11:25:16.470  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 11:25:16.472  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:16.477  4324  7404 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 11:25:16.479  4324  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 11:25:16.479  4324  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 11:25:16.521  1034  2049 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7406 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-16 11:25:16.578  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 11:25:16.578  7333  7333 E wpa_supplicant: USIM:  scard_init function
08-16 11:25:16.578  1034  7375 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 11:25:16.578  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 11:25:16.579  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
,08-16 11:25:16.579  1034  7375 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 11:25:16.579  7333  7333 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 11:25:16.581  1034  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 11:25:16.582  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 11:25:16.582  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 11:25:16.582  1034  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 11:25:16.584  1034  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 11:25:16.585  1034  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 11:25:16.585  1034  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 11:25:16.600  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=376246  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 11:25:16.605  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 11:25:16.605  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=376251  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 11:25:16.605  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:16.606  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.606  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.607  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 11:25:16.607  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:16.607  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 11:25:16.609  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:16.646  7406  7406 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 11:25:16.646  7406  7406 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 11:25:16.653  7406  7406 V [BNRBootReceiver]: Boot Receiver Return
08-16 11:25:16.653  7406  7406 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 11:25:16.660  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:16.672  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:16.678  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:16.692  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 11:25:16.693  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:16.697  7333  7333 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 11:25:16.698  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 11:25:16.698  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 11:25:16.698  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 11:25:16.699  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 11:25:16.699  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 11:25:16.699  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:16.699  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:16.701  1034  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 11:25:16.702  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:16.702  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=376348  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 11:25:16.704  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=376349  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-16 11:25:16.705  1034  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=376351
08-16 11:25:16.705  1034  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=376351
08-16 11:25:16.706  1034  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=376352
08-16 11:25:16.706  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=376352
08-16 11:25:16.707  1034  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=376353
08-16 11:25:16.707  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=376354  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 11:25:16.711  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:16.711  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:16.712  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.713  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.713  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 11:25:16.713  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:16.713  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:16.713  7333  7333 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 11:25:16.714  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=376360  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 11:25:16.714  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:16.714  7333  7333 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 11:25:16.715  1034  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:16.715  1034  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:16.715  1034  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:16.716  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 11:25:16.716  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 11:25:16.716  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:16.716  1034  7375 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 11:25:16.716  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 11:25:16.716  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 11:25:16.716  1034  7375 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 11:25:16.716  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:16.716  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EV,ENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:16.716  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:16.719  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:16.719  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:16.719  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.720  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.720  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 11:25:16.720  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=376366  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 11:25:16.720  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:16.720  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-16 11:25:16.723  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:16.723  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=376369  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 11:25:16.727  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:16.728  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:16.728  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 11:25:16.728  1034  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=376375
08-16 11:25:16.729  1034  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=376375
08-16 11:25:16.729  1034  1537 D WifiNative-wlan0: doString: [STATUS]
08-16 11:25:16.730  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:16.730  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:16.730  1034  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-16 11:25:16.732  1034  1537 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 11:25:16.737  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:16.740  1034  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 11:25:16.740  1034  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 11:25:16.743  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.743  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.743  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 11:25:16.747  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.747  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.747  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 11:25:16.751  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:16.752  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:16.752  1034  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 11:25:16.752  1034  1543 D ConnectivityService: Got NetworkAgent Messenger
08-16 11:25:16.752  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 11:25:16.752  1034  1543 D ConnectivityService: NetworkAgent connected
08-16 11:25:16.753  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 11:25:16.753  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 11:25:16.753  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 11:25:16.753  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 11:25:16.754  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 11:25:16.757  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 11:25:16.757  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 11:25:16.757  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 11:25:16.758  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 11:25:16.758  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 11:25:16.759  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:16.759  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 11:25:16.761  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 11:25:16.761  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:16.764  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 11:25:16.764  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:16.764  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:16.765  6956  6956 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 11:25:16.765  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:16.767   315   893 D CommandListener: Setting iface cfg
08-16 11:25:16.769  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:16.773  1034  1537 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 11:25:16.774  1034  7425 D DhcpStateMachine: StoppedState
08-16 11:25:16.774  1034  7425 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.774  1034  7425 D DhcpStateMachine: WaitBeforeStartState
08-16 11:25:16.774  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=376420  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:16.775  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=376421  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 11:25:16.775  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=376422  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:16.777  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:16.777  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:16.777  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 11:25:16.779  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=376425  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:16.780  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=376426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:16.780  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=376426  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:16.781  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:330918] from screen [on:0 period:-1834265747] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:25:16.782  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1834265746] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:25:16.782  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 11:25:16.782  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:16.787  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:16.789  1034  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 11:25:16.790  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:16.790  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:16.791  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 11:25:16.791  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:16.791  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:16.792  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:16.792  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:16.793  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:16.793  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:16.793  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 11:25:16.797  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 11:25:16.797  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 11:25:16.797  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 11:25:16.797  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 11:25:16.798  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=105,0,0
08-16 11:25:16.798  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=105,0,0
08-16 11:25:16.798  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 11:25:16.799  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 11:25:16.799  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 11:25:16.799  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 11:25:16.799  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 11:25:16.799  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 11:25:16.800  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 11:25:16.800  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 11:25:16.800  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 11:25:16.800  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 11:25:16.800  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 11:25:16.801  1034  1537 D WifiNative-wlan0: SET ps 0: returned true
08-16 11:25:16.801  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 11:25:16.801  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 11:25:16.801  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 11:25:16.803  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 11:25:16.803  1034  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 11:25:16.803  1034  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 11:25:16.803  1034  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 11:25:16.804  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26d207e4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.804  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26d207e4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.804  1034  7425 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.804  1034  7425 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 11:25:16.804  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:16.805   315   893 D CommandListener: Setting iface cfg
08-16 11:25:16.805   315   893 D CommandListener: Trying to bring up wlan0
08-16 11:25:16.806  1034  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 11:25:16.807  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:16.807  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 11:25:16.807  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 11:25:16.808  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 11:25:16.808  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.808  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.808  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 11:25:16.809  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 11:25:16.809  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 11:25:16.809  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 11:25:16.809  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 11:25:16.810  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 11:25:16.810  1034  1537 D WifiNative,-wlan0: doBoolean: SET ps 1
,08-16 11:25:16.813  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:16.818  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:16.825  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 11:25:16.825  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:16.826  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 11:25:16.827  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-16 11:25:16.828  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 11:25:16.828  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:16.829  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:16.829  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:16.830  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:16.830  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:16.831  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:16.831  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 11:25:16.831  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:16.831  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 11:25:16.832  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 11:25:16.832  1034  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 11:25:16.832  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
08-16 11:25:16.837  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:16.837  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 11:25:16.840  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.840  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.840  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 11:25:16.840  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:16.844  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 11:25:16.845  1034  1543 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 11:25:16.851  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.851  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.851  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 11:25:16.854  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 11:25:16.854  1034  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 11:25:16.856  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.856  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.856  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 11:25:16.856  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 11:25:16.857  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 11:25:16.863  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.863  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:16.863  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 11:25:16.863  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:16.863  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 11:25:16.866  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:16.869  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:16.870  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:16.871  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 11:25:16.871  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:16.874  1034  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 11:25:16.874  1034  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 11:25:16.875  1034  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 11:25:16.876   315   893 E Netd    : netlink response contains error (File exists)
08-16 11:25:16.876  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:16.876  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 11:25:16.876  1034  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 11:25:16.876  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:16.877  1034  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 11:25:16.877  1034  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 11:25:16.878  1034  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 11:25:16.879  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 11:25:16.879  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 11:25:16.879  1034  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 11:25:16.879  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 11:25:16.879  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:16.879  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:16.879  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 11:25:16.879  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:16.879  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 11:25:16.880  1034  1543 D ConnectivityService: currentScore = 0, newScore = 20
,08-16 11:25:16.880  1034  1543 D ConnectivityService:    accepting network in place of null
08-16 11:25:16.880  1034  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:16.881  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.881  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 11:25:16.881  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:16.881  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:16.881  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 11:25:16.881  1034  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 11:25:16.881  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 11:25:16.881  1034  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 11:25:16.884  1034  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:16.884  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:16.885  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 11:25:16.885  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:16.885   315  7429 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 11:25:16.885  1034  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 11:25:16.886  1034  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 11:25:16.887  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 11:25:16.887  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 11:25:16.887  1034  1034 D LocSvc_java: ,updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 11:25:16.887  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 11:25:16.889  1034  1543 D ConnectivityService: validation of new default Network = false
08-16 11:25:16.889  1034  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 11:25:16.889  1034  1543 D DSQN    : enableDataServiceNotify 
08-16 11:25:16.889  1034  1543 D DSQN    : start dsqn bin
,08-16 11:25:16.885  7430  7430 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:16.885  7430  7430 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:16.900  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 11:25:16.900  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:16.900  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:16.901  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 11:25:16.902  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 11:25:16.907  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:16.911  1034  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-16 11:25:16.915  7430  7430 E DSQN    : DSQN ssw
08-16 11:25:16.924  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:16.924  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:16.924  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 11:25:16.929  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:16.934  1815  7434 I CheckinService: active receiver: enabled
08-16 11:25:16.939   315  7429 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 11:25:16.945  1815  7434 I CheckinService: Preparing to send checkin request
08-16 11:25:16.945  1815  7434 I EventLogService: Accumulating logs since 1471339198193
08-16 11:25:16.948  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:16.957  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:16.960  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 11:25:16.961  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:16.961  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:16.965  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:16.965  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:16.966  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 11:25:16.968  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:16.972   315  7429 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 11:25:16.974  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:16.979  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:16.984  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:16.985  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:16.986  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 11:25:16.986  1815  7434 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-16 11:25:16.993  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 11:25:17.005   315   892 D LGDataListener: argv[0]=dsqncommand
,08-16 11:25:17.005   315   892 D LGDataListener: argv[1]=wlan0
,08-16 11:25:17.005   315   892 D LGDataListener: argv[2]=1
08-16 11:25:17.005   315   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 11:25:17.006  1034  7425 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 11:25:17.006  1034  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 11:25:17.006  1034  1108 D DSQN    : start to monitor internet connection
08-16 11:25:17.007  1034  7425 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 11:25:17.007  1034  7425 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 11:25:17.008  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:16.995  7438  7438 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:16.995  7438  7438 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:17.013  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 11:25:17.023  7438  7438 I dhcpcd  : version 5.5.6 starting
08-16 11:25:17.025  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:17.025  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:17.025  7438  7438 E dhcpcd  : get_duid: m
08-16 11:25:17.025  7438  7438 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 11:25:17.025  7438  7438 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 11:25:17.030  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 11:25:17.037  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:17.039  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 09:25:17 GMT], X-Android-Received-Millis=[1471339517038], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471339517005]}
08-16 11:25:17.039  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 11:25:17.039  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 11:25:17.039  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 11:25:17.039  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 11:25:17.039  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:17.039  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:17.039  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 11:25:17.039  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 11:25:17.039  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 11:25:17.040  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:17.040  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:17.040  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:17.040  1034  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:17.040  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 11:25:17.040  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 11:25:17.040  1034  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:17.041  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:17.041  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:17.042  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-16 11:25:17.046  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:17.053  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:17.060  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:17.060  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:17.061  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 11:25:17.064  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 11:25:17.065  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:17.066  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:17.067  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:17.068  6980  6980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 11:25:17.072  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:17.076  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:17.081  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:17.085  7438  7438 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 11:25:17.085  7438  7438 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 11:25:17.085  7438  7438 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 11:25:17.085  7438  7438 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 11:25:17.085  7438  7438 D dhcpcd  : wlan0: sending REQUEST (xid 0x5f0de511), next in 3.67 seconds
08-16 11:25:17.087  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:17.087  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:17.088  7009  7009 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 11:25:17.089  7009  7009 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 11:25:17.090  7009  7009 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 11:25:17.096  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:17.099  6980  6980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 11:25:17.099  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:17.112  7438  7438 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 11:25:17.152  7438  7438 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 11:25:17.152  7438  7438 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,08-16 11:25:17.153  7438  7438 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 11:25:17.153  7438  7438 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 11:25:17.153  7438  7438 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 11:25:17.154  7438  7438 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 11:25:17.154  7438  7438 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 11:25:17.154  7438  7438 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 11:25:17.159  1034  1918 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7445 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-16 11:25:17.167  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:17.174  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:17.181  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:17.181  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:17.182  7009  7009 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 11:25:17.183  7009  7009 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 11:25:17.183  7009  7009 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 11:25:17.188  1034  1050 I ActivityManager: Killing 6932:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 11:25:17.204  6693  7122 D UEI.SmartControl: Internal timer expired: 2
08-16 11:25:17.204  6693  7122 D UEI.SmartControl: unbind internal service
,08-16 11:25:17.254  1034  1987 W libprocessgroup: failed to open /acct/uid_10037/pid_6932/cgroup.procs: No such file or directory
,08-16 11:25:17.286  6693  7116 D serial_port: close(fd = 24)
,08-16 11:25:17.291  6693  7116 I UEI.SmartControl: Serial port is closed.
08-16 11:25:17.294  7445  7445 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 11:25:17.294  7445  7445 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 11:25:17.324  7445  7445 I MultiDex: VM with version 2.1.0 has multidex support
08-16 11:25:17.325  7445  7445 I MultiDex: install
08-16 11:25:17.325  7445  7445 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 11:25:17.336  7445  7445 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 11:25:17.340  2211  2211 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 11:25:17.362  2211  2211 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 11:25:17.364  2211  2211 D c       : Getting all permits...
08-16 11:25:17.364  2211  2211 D a       : Opening database...
08-16 11:25:17.370  2211  2211 D a       : Opening database auth.proximity.permit_store...
08-16 11:25:17.371  2211  2211 D a       : Closing database...
08-16 11:25:17.612  1034  7425 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 11:25:17.616  1034  7425 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 11:25:17.616  1034  7425 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 11:25:17.617  1034  7425 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 11:25:17.617  1034  7425 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 11:25:17.617  1034  7425 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 11:25:17.617  1034  7425 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 11:25:17.617  1034  7425 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 11:25:17.618  1034  7425 D DhcpStateMachine: RunningState
,08-16 11:25:17.672  7445  7464 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:17.672  7445  7464 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:17.898  1034  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 11:25:17.970  7491  7491 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 11:25:18.046  7491  7491 I dex2oat : dex2oat took 75.999ms (threads: 4)
,08-16 11:25:18.068  7445  7464 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:25:18.068  7445  7464 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:25:18.068  7445  7464 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:25:18.068  7445  7464 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:25:18.068  7445  7464 I Adreno-EGL: Remote Branch: 
08-16 11:25:18.068  7445  7464 I Adreno-EGL: Local Patches: 
08-16 11:25:18.068  7445  7464 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:25:18.348  7445  7464 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:25:18.348  7445  7464 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:25:18.348  7445  7464 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:25:18.348  7445  7464 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:25:18.348  7445  7464 I Adreno-EGL: Remote Branch: 
08-16 11:25:18.348  7445  7464 I Adreno-EGL: Local Patches: 
08-16 11:25:18.348  7445  7464 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:25:18.405  7445  7464 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:25:18.405  7445  7464 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:25:18.405  7445  7464 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:25:18.405  7445  7464 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:25:18.405  7445  7464 I Adreno-EGL: Remote Branch: 
08-16 11:25:18.405  7445  7464 I Adreno-EGL: Local Patches: 
08-16 11:25:18.405  7445  7464 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:25:18.498   315  7499 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 11:25:18.500   315  7499 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 11:25:18.544   315  7499 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 11:25:18.630  1034  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:18.631  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:18.632  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:18.633  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:18.635  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:18.636  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 11:25:18.640  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-16 11:25:18.640  1034  1543 D ConnectivityService: identical MTU - not setting
08-16 11:25:18.640  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 11:25:18.640  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 11:25:18.640  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:18.641  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:18.642  1034  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:18.644  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 11:25:18.743  1815  7434 I CheckinTask: Sending checkin request (7890 bytes)
,08-16 11:25:19.037  1815  7434 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 11:25:19.053  1815  7434 I CheckinService: active receiver: disabled
,08-16 11:25:19.078  2211  2211 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-16 11:25:19.095  2211  2211 I GCM     : GCM config loaded
,08-16 11:25:19.118   315  7506 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 11:25:19.121   315  7506 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 11:25:19.127  7191  7191 V SetupWizard: Connected to Gservices successfully
08-16 11:25:19.153   315  7506 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 11:25:19.453  2211  7514 D GCM     : Connected
,08-16 11:25:19.498  2211  7514 D GCM     : Message class com.google.e.a.a.q
,08-16 11:25:19.796  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=52.5, 0.0, 0.0  rx=49.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1834262733] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:25:19.798  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=52.5, 0.0, 0.0  rx=49.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834262730] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:25:19.799  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:25:19.824  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:19.858  1034  1538 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 11:25:19.886  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:19.894  1034  1110 D Tethering: MasterInitialState.processMessage what=3
08-16 11:25:19.904  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:19.904  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:19.904  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:19.904  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:19.904  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:19.904  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:19.904  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:19.904  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:25:19.904  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:19.904  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:19.905  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:25:19.911  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:19.911  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:19.911  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:19.911  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:19.911  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:19.911  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:19.911  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:19.911  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:25:19.911  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:19.911  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:19.912  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:19.917  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:19.917  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:19.917  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:19.917  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:19.917  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:19.917  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:19.917  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:19.917  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:25:19.917  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:19.917  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:19.917  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:19.922  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:19.929  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 11:25:19.930  6486  6979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 11:25:19.941  5780  5780 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 11:25:19.961  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:19.977  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 11:25:19.977  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:19.977  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 11:25:19.977  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 11:25:19.987  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-16 11:25:19.992  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cb52bc4
08-16 11:25:19.992  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 11:25:19.992  7137  7137 D AppUp4:CustFacade: isPhone : true
,08-16 11:25:19.994  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-16 11:25:19.994  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 11:25:19.999  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:19.999  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 11:25:20.001  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:20.029  1034  2031 D WifiServiceImplEx: setWifiEnabled: false pid=6792, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 11:25:20.030  1034  2031 D WifiService: setWifiEnabled: false pid=6792, uid=10118
08-16 11:25:20.030  1034  2031 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:25:20.036  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:20.037  1034  1883 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-16 11:25:20.037  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.037  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.037  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 11:25:20.038  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.038  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 11:25:20.039  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:20.044  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 11:25:20.044  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 11:25:20.044  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-16 11:25:20.045  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:20.046  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:20.046  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:20.046  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:20.050  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 11:25:20.050  1034  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 11:25:20.050  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 11:25:20.050  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-16 11:25:20.052  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 11:25:20.052  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 11:25:20.052  3531  3531 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:20.057  3531  3531 V DownloadManager: DownloadService onCreate
08-16 11:25:20.058  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 11:25:20.058  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 11:25:20.058  3531  7537 I DownloadManager: in removeSpuriousFiles
08-16 11:25:20.058  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 11:25:20.059  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.059  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.059  3531  7537 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-16 11:25:20.059  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 11:25:20.059  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 11:25:20.059  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-16 11:25:20.060  3531  7537 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f12a7a8 on behalf of 3531
08-16 11:25:20.060  1034  7425 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-16 11:25:20.062  3531  7537 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-16 11:25:20.063  3531  7537 I DownloadManager: in trimDatabase
08-16 11:25:20.064  3531  7537 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-16 11:25:20.064  3531  7537 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@df6c2c1 on behalf of 3531
08-16 11:25:20.065   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 11:25:20.071  7162  7162 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 11:25:20.072  3531  3531 V DownloadManager: DownloadService onStartCommand
08-16 11:25:20.075  3531  7538 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-16 11:25:20.076  3531  7538 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@15be9654 on behalf of 3531
08-16 11:25:20.079  3531  7538 V DownloadManager: processing inserted download 1
,08-16 11:25:20.080  3531  7538 V DownloadManager: processing inserted download 4
08-16 11:25:20.082  3531  7538 V DownloadManager: processing inserted download 7
08-16 11:25:20.083  3531  7538 V DownloadManager: processing inserted download 8
08-16 11:25:20.084   315  7541 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 11:25:20.085  3531  7538 V DownloadManager: processing inserted download 9
08-16 11:25:20.086  3531  7538 V DownloadManager: processing inserted download 10
08-16 11:25:20.087  3531  7538 V DownloadManager: processing inserted download 11
08-16 11:25:20.088  3531  7538 V DownloadManager: processing inserted download 12
08-16 11:25:20.088  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 11:25:20.089  1034  1108 D DSQN    : Dns fail occured do internet check.
08-16 11:25:20.089  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-16 11:25:20.089  1034  1034 D DSQN    : try Internet connection check
08-16 11:25:20.089  3531  7538 V DownloadManager: processing inserted download 13
08-16 11:25:20.090  3531  7538 V DownloadManager: processing inserted download 14
08-16 11:25:20.091  3531  7538 V DownloadManager: processing inserted download 16
08-16 11:25:20.097  4324  7535 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 11:25:20.098  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 11:25:20.098  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-16 11:25:20.100   315  7545 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 11:25:20.101  1034  7544 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-16 11:25:20.101  1034  7542 D DSQN    : ThreadInternetCheck internet check NOK 
08-16 11:25:20.102  1034  7542 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-16 11:25:20.102  1034  7542 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-16 11:25:20.102  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:20.102  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:20.103  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:20.103  1034  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 11:25:20.104  1034  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.104  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.104  1034  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@35134602
08-16 11:25:20.104  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:20.105  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:20.105  1034  1108 D DSQN    : Dns timeout INTERNET_CHECK already in progress ignore!
08-16 11:25:20.106  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:20.108  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 11:25:20.111  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-16 11:25:20.111  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:20.111  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:20.111  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 11:25:20.111  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-16 11:25:20.111  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:20.111  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:20.111  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 11:25:20.112  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 11:25:20.112  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-16 11:25:20.112  1034  1034 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-16 11:25:20.113  1034  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.113  1034  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.113  1034  1536 D LGWifiP2pService: P2pDisablingState
08-16 11:25:20.113  1034  1536 D LGWifiP2pService: P2pDisablingState{ when=-9ms what=147458 target=com.andr,oid.internal.util.StateMachine$SmHandler }
08-16 11:25:20.114  1034  1536 D LGWifiP2pService: p2p socket connection lost
,08-16 11:25:20.117  1034  1536 D LGWifiP2pService: P2pDisabledState
08-16 11:25:20.117  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 11:25:20.117  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 11:25:20.117  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.117  7333  7333 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 11:25:20.117  1034  1536 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.118  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 11:25:20.118  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 11:25:20.118  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-16 11:25:20.119  3483  3483 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 11:25:20.119  3483  3483 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:20.119  3483  3483 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 11:25:20.119  3483  3483 D PhoneState: setPdpRejectCasuse : false
08-16 11:25:20.122  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 11:25:20.122  1940  1940 D WfdsService: WifiP2pState is changed : false
08-16 11:25:20.124  1940  2327 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 11:25:20.124  1940  2327 D WfdsService: Set the WFDS Monitor: false
08-16 11:25:20.126  1940  1957 D WifiServiceExtension: isInternetCheckAvailable return false
08-16 11:25:20.127  4324  7540 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:20.127  4324  7540 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 11:25:20.130  7162  7547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:20.131  1940  2327 D WfdsMonitor: WFDS Monitor is stopped
08-16 11:25:20.131  1940  2327 D WfdsService: STATE : WfdsDisabledState - enter
08-16 11:25:20.132  1940  7376 D CtrlSupplicant: Received on exit socket, terminate
08-16 11:25:20.132  1940  7376 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 11:25:20.132  1940  7376 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 11:25:20.132  1940  7376 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 11:25:20.132  1940  2327 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 11:25:20.133  1940  2333 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 11:25:20.134  7191  7191 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 11:25:20.134  7191  7191 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 11:25:20.138  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:20.138  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:20.139  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:20.141  7075  7554 W FormManager: Network not available. Please check & try again.
08-16 11:25:20.141  3531  3531 V DownloadManager: DownloadService onDestroy
08-16 11:25:20.144   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 11:25:20.145  1034  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 11:25:20.145  1034  1543 D DSQN    : disableDataServiceNotify
08-16 11:25:20.145  1034  1543 D DSQN    : stop dsqn bin
08-16 11:25:20.147  1034  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 11:25:20.147  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-16 11:25:20.147  1034  1537 D WifiNative-p2p0: TERMINATE: returned true
08-16 11:25:20.147  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 11:25:20.147  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-16 11:25:20.147  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 11:25:20.148  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:20.148  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:20.148  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 11:25:20.149  7075  7555 V FormManager: Network unavailable.
08-16 11:25:20.150  1034  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 11:25:20.150  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:20.150  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:20.150  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 11:25:20.150  1034  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:20.150  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 11:25:20.150  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.150  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.150  1034  7424 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 11:25:20.150  1034  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 11:25:20.150  1034  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 11:25:20.151  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 11:25:20.151  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-16 11:25:20.154  7264  7264 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:20
08-16 11:25:20.154  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 11:25:20.155  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:20.155  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 11:25:20.156  7075  7555 V FormManager: Network unavailable.
08-16 11:25:20.156  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:20.156  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:20.156  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:20.156  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:20.156  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:20.156  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:20.156  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:20.156  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:20.156  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:20.156  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:20.156  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:20.156  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 11:25:20.157  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:20.157  1034  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:20.157  1034  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:20.158  1034  1543 D NetworkManagementService: Removing idletimer
08-16 11:25:20.158  1034  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:20.158  1034  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 11:25:20.158  1034  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:20.158  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:20.158  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 11:25:20.159  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:20.159  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 11:25:20.159  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0,
08-16 11:25:20.159  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 11:25:20.159  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 11:25:20.159  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:20.159  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 11:25:20.159  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 11:25:20.159  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 11:25:20.159  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 11:25:20.161  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:20.161  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:20.161  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:20.161  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:20.161  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:20.161  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:20.161  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:20.161  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:20.161  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:25:20.161  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:20.161  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:20.162  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:20.162  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:20.162  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:20.162  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:20.162  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:20.162  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:20.162  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:20.162  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:20.162  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:20.162  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:20.162  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:20.162  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 11:25:20.162  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 11:25:20.162  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 11:25:20.162  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 11:25:20.163  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:20.166  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:20.168  7264  7264 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 11:25:20.168  7264  7264 D Weather.Utils: 2 : All the weather widget is gone.
08-16 11:25:20.169  7264  7264 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 11:25:20.169  7264  7264 D WeatherAncestor: connectivity changed - connection : true
08-16 11:25:20.169  7264  7264 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3086f1e2
08-16 11:25:20.169  7264  7264 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 11:25:20.169  7264  7264 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 11:25:20.169  7264  7264 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 11:25:20.169  7264  7264 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 11:25:20.170  7264  7264 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:20
08-16 11:25:20.177  7333  7333 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 11:25:20.177  7333  7333 I wpa_supplicant: monitor socket send errors count : 1
08-16 11:25:20.177  7333  7333 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-4\x00 that cannot receive messages
08-16 11:25:20.179  1034  7375 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 11:25:20.179  1034  7375 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 11:25:20.194  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 11:25:20.197  6980  6980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 11:25:20.197  6980  6980 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 11:25:20.197  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:20.200  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 11:25:20.201  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:20.201  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:20.202  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:20.202  7333  7333 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 11:25:20.203  7333  7333 W wpa_supplicant: USIM:  scard_deinit function
08-16 11:25:20.204  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 11:25:20.204  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 11:25:20.204  1034  7375 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 11:25:20.204  1034  7375 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 11:25:20.204  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:20.204  1034  1110 D Tethering: InitialState.processMessage what=4
08-16 11:25:20.205  1034  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=379851
08-16 11:25:20.205  1034  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=379851
08-16 11:25:20.205  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 11:25:20.205  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:20.206  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=379852  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 11:25:20.206  1034  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=379852  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 11:25:20.206  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:20.207  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:20.212  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:20.218  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:20.218  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:20.222  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 11:25:20.224  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 11:25:20.225  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:20.225  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:20.226  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:20.229  6980  6980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 11:25:20.229  6980  6980 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 11:25:20.229  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:20.231  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:20.236  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:20.240  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:20.240  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:20.241  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 11:25:20.244  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:20.246  6980  6980 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 11:25:20.246  6980  6980 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 11:25:20.246  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:20.250  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:20.254  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:20.258  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:20.258  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:20.259  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 11:25:20.264  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 11:25:20.266  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 11:25:20.268  1034  7425 D DhcpStateMachine: StoppedState
08-16 11:25:20.268  1034  7425 D DhcpStateMachine: StoppedState{ when=-150ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:20.269  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 11:25:20.269  1034  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 11:25:20.271  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:20.275  7075  7557 W FormManager: Network not available. Please check & try again.
08-16 11:25:20.281  7075  7558 V FormManager: Network unavailable.
08-16 11:25:20.283  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 11:25:20.283  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 11:25:20.283  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 11:25:20.283  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 11:25:20.284  7333  7333 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 11:25:20.285  7075  7558 V FormManager: Network unavailable.
08-16 11:25:20.286  1034  7375 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 11:25:20.286  1034  7375 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 11:25:20.286  1034  7375 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 11:25:20.287  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-16 11:25:20.288  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 11:25:20.289  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 11:25:20.289  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 11:25:20.289  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 11:25:20.289  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 11:25:20.289  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 11:25:20.289  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 11:25:20.332  7283  7304 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 11:25:20.388  1034  1537 D WifiOffDelayIfNotUsed: stopMonitoring
,08-16 11:25:20.388  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 11:25:20.388  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-16 11:25:20.388  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 11:25:20.393  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:20.393  1940  1940 D WfdsService: Supplicant Connection state is changed : false
,08-16 11:25:20.393  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 11:25:20.394  1940  2327 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 11:25:20.394  1940  2327 D WfdsService: Set the WFDS Monitor: false
08-16 11:25:20.394  1940  2327 D WfdsMonitor: WFDS Monitor is stopped
08-16 11:25:20.395  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 11:25:20.395  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 11:25:20.395  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 11:25:20.395  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 11:25:20.396  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 11:25:20.396  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:20.396  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:20.396  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:20.396  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:20.396  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:20.396  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:20.396  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:20.396  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:20.396  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:20.397  2461  2461 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:20.398  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:20.398  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:20.398  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:20.398  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:20.398  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:20.398  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:20.398  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:20.398  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:20.398  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:20.398  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:20.401  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:20.402  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDe,viceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 11:25:20.410  6980  6980 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 11:25:20.411  6980  6980 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 11:25:20.411  6980  6980 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:20.414  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 11:25:20.415  4324  7561 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 11:25:20.418  4324  7563 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 11:25:20.418  4324  7563 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 11:25:20.424  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:20.424  7075  7564 W FormManager: Network not available. Please check & try again.
08-16 11:25:20.437  7075  7565 V FormManager: Network unavailable.
,08-16 11:25:20.446  7075  7565 V FormManager: Network unavailable.
,08-16 11:25:20.749  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7523
,08-16 11:25:20.750  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7526
,08-16 11:25:20.755  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7552
,08-16 11:25:20.755  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7566
08-16 11:25:21.218  1034  1883 I ActivityManager: Killing 7029:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 11:25:21.250  1034  1918 W libprocessgroup: failed to open /acct/uid_1000/pid_7029/cgroup.procs: No such file or directory
,08-16 11:25:22.827  1034  1537 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1834259701] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 11:25:22.829  1034  1537 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1834259699] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 11:25:23.158  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:23.172  1034  1110 D Tethering: MasterInitialState.processMessage what=3
08-16 11:25:23.186  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:25:23.191  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:23.192  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:23.195  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.197  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.200  1034  1110 D Tethering: MasterInitialState.processMessage what=3
,08-16 11:25:23.212  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:23.214  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:25:23.217  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:23.219  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 11:25:23.221  6486  6979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 11:25:23.232  5780  5780 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 11:25:23.243  5780  5780 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 11:25:23.257  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:23.276  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 11:25:23.276  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.277  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 11:25:23.277  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 11:25:23.281  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-16 11:25:23.284  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cb52bc4
08-16 11:25:23.284  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 11:25:23.284  7137  7137 D AppUp4:CustFacade: isPhone : true
08-16 11:25:23.285  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-16 11:25:23.285  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 11:25:23.290  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.290  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 11:25:23.292  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 11:25:23.297  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:23.304  7162  7162 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 11:25:23.327  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.327  4324  7588 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 11:25:23.333  7162  7587 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:23.336  4324  7590 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.336  4324  7590 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 11:25:23.337  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:23.338  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:23.341  3483  3483 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-16 11:25:23.341  3483  3483 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.341  3483  3483 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 11:25:23.344  7191  7191 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 11:25:23.344  7191  7191 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 11:25:23.355  7264  7264 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:23
,08-16 11:25:23.358  7075  7594 W FormManager: Network not available. Please check & try again.
08-16 11:25:23.359  7264  7264 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 11:25:23.359  7264  7264 D Weather.Utils: 2 : All the weather widget is gone.
08-16 11:25:23.359  7264  7264 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 11:25:23.360  7264  7264 D WeatherAncestor: connectivity changed - connection : true
08-16 11:25:23.360  7264  7264 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3086f1e2
08-16 11:25:23.360  7264  7264 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 11:25:23.361  7264  7264 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 11:25:23.361  7264  7264 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 11:25:23.361  7264  7264 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 11:25:23.361  7264  7264 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:23
08-16 11:25:23.365  7075  7596 V FormManager: Network unavailable.
08-16 11:25:23.371  7075  7596 V FormManager: Network unavailable.,
,08-16 11:25:23.389  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 11:25:23.391  6486  6979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 11:25:23.409  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:23.419  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 11:25:23.419  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.419  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 11:25:23.419  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 11:25:23.421  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 11:25:23.425  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cb52bc4
08-16 11:25:23.425  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 11:25:23.425  7137  7137 D AppUp4:CustFacade: isPhone : true
08-16 11:25:23.426  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-16 11:25:23.426  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 11:25:23.430  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.430  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 11:25:23.432  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:23.435  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:23.443  4324  7599 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 11:25:23.444  7162  7162 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 11:25:23.447  4324  7600 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:23.448  4324  7600 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 11:25:23.469  7162  7601 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 11:25:23.474  7075  7603 W FormManager: Network not available. Please check & try again.
08-16 11:25:23.481  3483  3483 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 11:25:23.481  3483  3483 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:23.482  3483  3483 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 11:25:23.489  7191  7191 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 11:25:23.489  7191  7191 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 11:25:23.492  7075  7604 V FormManager: Network unavailable.
08-16 11:25:23.505  7075  7604 V FormManager: Network unavailable.
,08-16 11:25:23.508  7264  7264 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:23
08-16 11:25:23.514  7264  7264 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 11:25:23.514  7264  7264 D Weather.Utils: 2 : All the weather widget is gone.
08-16 11:25:23.514  7264  7264 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 11:25:23.515  7264  7264 D WeatherAncestor: connectivity changed - connection : true
08-16 11:25:23.515  7264  7264 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3086f1e2
08-16 11:25:23.516  7264  7264 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 11:25:23.516  7264  7264 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 11:25:23.517  7264  7264 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 11:25:23.517  7264  7264 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-16 11:25:23.517  7264  7264 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:23
08-16 11:25:23.535  1034  2049 I ActivityManager: Killing 7406:com.lge.bnr/1000 (adj 15): empty #17
,08-16 11:25:23.631  1034  1850 W libprocessgroup: failed to open /acct/uid_1000/pid_7406/cgroup.procs: No such file or directory
,08-16 11:25:25.046  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 11:25:25.047  1034  1051 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 11:25:25.071  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 11:25:25.072  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 11:25:25.072  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-16 11:25:25.072  1034  1110 D BluetoothManagerService: Message: 1
08-16 11:25:25.072  1034  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 11:25:25.099  1034  1110 D BluetoothManagerService: Message: 20
08-16 11:25:25.099  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@175c8247:true
,08-16 11:25:25.103  7058  7058 D BluetoothAdapterState: make
08-16 11:25:25.108  7058  7058 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 11:25:25.109  7058  7058 I bluedroid-qcom: init
08-16 11:25:25.110  7058  7617 I BluetoothAdapterState: Entering OffState
08-16 11:25:25.110  7058  7058 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 11:25:25.111  7058  7058 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 11:25:25.111  7058  7058 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 11:25:25.111  7058  7058 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 11:25:25.111  7058  7058 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 11:25:25.113  7058  7058 I bluedroid-qcom: get_profile_interface socket
08-16 11:25:25.113  7058  7058 I bluedroid-qcom: get_profile_interface map_client
,08-16 11:25:25.116  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:25.116  1034  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:25.118  7058  7621 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 11:25:25.120  7058  7621 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 11:25:25.105  7620  7620 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:25.105  7620  7620 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:25.132  7620  7620 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 11:25:25.132  7620  7620 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 11:25:25.133  7620  7620 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 11:25:25.136  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 11:25:25.137  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 11:25:25.138  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 11:25:25.139  1034  1110 D BluetoothManagerService: Message: 40
08-16 11:25:25.139  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 11:25:25.139  7058  7073 I bluedroid-qcom: config_hci_snoop_log
08-16 11:25:25.141  1034  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 11:25:25.141  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 11:25:25.142  7620  7620 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 11:25:25.149  7620  7620 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 11:25:25.149  7620  7620 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-16 11:25:25.154  1034  1537 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 11:25:25.154  1034  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 11:25:25.155  7058  7617 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 11:25:25.156  7058  7621 D BluetoothAdapterProperties: Name is: G3
08-16 11:25:25.156  7058  7617 D BluetoothAdapterProperties: Setting state to 11
08-16 11:25:25.156  7058  7617 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 11:25:25.157  1034  1110 D BluetoothManagerService: Message: 60
08-16 11:25:25.157  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 11:25:25.157  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 11:25:25.161  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 11:25:25.164  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 11:25:25.169  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 11:25:25.171  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:25.172  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:25.174  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:25:25.182  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 11:25:25.183  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:25.183  7058  7058 V BluetoothPbapReceiver: ***********state = 11
08-16 11:25:25.189  7058  7617 I LGBluetoothServiceJni: classInitNative: succeeds
,08-16 11:25:25.196  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 11:25:25.218  7058  7617 D BluetoothBondStateMachine: make
,08-16 11:25:25.225  7058  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.225  7058  7617 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 11:25:25.225  7058  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.225  7058  7634 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 11:25:25.225  7058  7617 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 11:25:25.226  7058  7617 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 11:25:25.230  7058  7617 E BluetoothAdapterService: File transfer profiles supported!!
08-16 11:25:25.252  1034  1925 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7638 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 11:25:25.258  7058  7617 E BluetoothAdapterService: File transfer profiles supported!!
08-16 11:25:25.260  7058  7058 D HeadsetService: Received start request. Starting profile...
08-16 11:25:25.260  7058  7058 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 11:25:25.260  7058  7058 D LGBluetoothHfpAdapter: Version 1.6
08-16 11:25:25.264  7058  7058 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 11:25:25.265  7058  7058 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 11:25:25.265  7058  7058 D HeadsetStateMachine: make
08-16 11:25:25.267  7058  7617 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 11:25:25.273  7058  7617 E BluetoothAdapterService: File transfer profiles supported!!
08-16 11:25:25.280  7058  7617 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 11:25:25.286  7058  7617 E BluetoothAdapterService: File transfer profiles supported!!
08-16 11:25:25.293  7058  7617 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 11:25:25.304  7058  7058 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:25.304  7058  7058 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 11:25:25.310  7058  7617 V LGMDMManager: Create singleton instance
08-16 11:25:25.311  7058  7058 D HeadsetStateMachine: max_hf_connections = 1
08-16 11:25:25.311  7058  7058 I bluedroid-qcom: get_profile_interface handsfree
08-16 11:25:25.313  7058  7058 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 11:25:25.313  7058  7617 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 11:25:25.314   320  1384 V AudioPolicyService: registerClient() client 0xb558a580, uid 1002
,08-16 11:25:25.314   320  2151 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 11:25:25.314   320  2151 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 11:25:25.315   320  2151 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 11:25:25.315  7058  7058 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 11:25:25.315   320  2150 V AudioFlinger: registerClient() client 0xb14330a0, pid 7058
,08-16 11:25:25.316   320  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:25.316   320  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 11:25:25.316  1851  1866 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:25.316  1851  1866 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 11:25:25.316  1601  2565 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:25.316  1601  2565 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 11:25:25.316  3483  3499 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:25.316  3483  3499 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 11:25:25.317   320  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:25.317   320  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:25.317  1851  2375 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:25.317  1851  2375 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:25.317  1601  2078 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:25.317  1601  2078 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:25.317  3483  3498 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:25.318  3483  3498 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:25.318  7058  7074 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:25.318  7058  7074 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 11:25:25.318  7058  7074 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:25.318  7058  7074 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 11:25:25.318  7058  7058 V ToneGenerator: Create Track: 0xb4928a80
08-16 11:25:25.318  7058  7058 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 11:25:25.318  7058  7058 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 11:25:25.319   320   320 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 11:25:25.319   320   320 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 11:25:25.319   320   320 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 11:25:25.319   320   320 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 11:25:25.319  1034  2031 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:25.319  1034  2031 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 11:25:25.319   320  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 11:25:25.319  1034  2031 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:25.319  1034  2031 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:25.320   320  2151 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 11:25:25.320   320  2151 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 11:25:25.320   320  2151 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 11:25:25.320   320  2151 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 11:25:25.320  7058  7058 V AudioSystem: getLatency() output 2, latency 50
08-16 11:25:25.320  7058  7058 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 11:25:25.320  7058  7058 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 11:25:25.320   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 11:25:25.321   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), ,curLvl = 31 
08-16 11:25:25.321   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 11:25:25.321   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 11:25:25.321   320   320 V AudioFlinger: createTrack() lSessionId: 22
08-16 11:25:25.322  7058  7058 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 11:25:25.322   320  2151 V AudioFlinger: acquiring 22 from 7058, for 7058
08-16 11:25:25.322   320  2151 V AudioFlinger:  added new entry for 22
08-16 11:25:25.322  7058  7058 V ToneGenerator: ToneGenerator INIT OK, time: 384979
08-16 11:25:25.322  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.323  7058  7654 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 11:25:25.324  7058  7654 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 11:25:25.324  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.325  7058  7654 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 11:25:25.326  7058  7058 D A2dpService: Received start request. Starting profile...
08-16 11:25:25.326  7058  7058 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 11:25:25.327  7058  7058 V Avrcp   : make
08-16 11:25:25.328  7058  7058 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 11:25:25.328  7058  7058 I bluedroid-qcom: get_profile_interface avrcp
08-16 11:25:25.329  7058  7654 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 11:25:25.329   320  2150 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7058
,08-16 11:25:25.329   320  2150 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 11:25:25.330   320  2150 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 11:25:25.330   320  2150 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 11:25:25.330   320  2150 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 11:25:25.330   320  2150 V voice   : voice_set_parameters: exit with code(0)
08-16 11:25:25.330   320  2150 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 11:25:25.330   320  2150 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 11:25:25.330   320  2150 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 11:25:25.330   320  2150 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 11:25:25.330   320  2150 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 11:25:25.330   320  2150 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 11:25:25.330  7058  7654 V ToneGenerator: ToneGenerator destructor
08-16 11:25:25.330  7058  7654 V ToneGenerator: stopTone
08-16 11:25:25.330  7058  7654 V ToneGenerator: Delete Track: 0xb4928a80
08-16 11:25:25.331  7058  7654 V AudioTrack: ~AudioTrack, releasing session id from 7058 on behalf of 7058
08-16 11:25:25.331   320   320 V AudioFlinger: releasing 22 from 7058 for 7058
08-16 11:25:25.331   320   320 V AudioFlinger:  decremented refcount to 0
08-16 11:25:25.331   320   320 V AudioFlinger: purging stale effects
08-16 11:25:25.331   320  1383 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 11:25:25.331   320  1383 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 11:25:25.331   320  1258 V AudioPolicyService: AudioCommandThread() waking up
08-16 11:25:25.331   320  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 11:25:25.331   320  1258 V AudioPolicyManager: releaseOutput() 2
08-16 11:25:25.331   320  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 11:25:25.331   320  1383 V AudioFlinger: PlaybackThread::Track destructor
08-16 11:25:25.331   320  1383 V AudioFlinger: removeClient_l() pid 7058, calling pid 320
08-16 11:25:25.336  7058  7058 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 11:25:25.337  7058  7058 E AudioManager: No RCC entry present to update
08-16 11:25:25.337  7058  7058 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 11:25:25.341  7058  7058 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 11:25:25.341  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 11:25:25.341  7058  7058 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-16 11:25:25.347  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 11:25:25.385  7638  7638 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 11:25:25.385  7638  7638 W LG Account v2.2: No ProfileInfo entries
08-16 11:25:25.385  7638  7638 I LG Account v2.2: isEnabled: false
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]Country: EU
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]Operator: OPEN
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]Ranking support: false
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]Comfort support: false
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]Accessory: true
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]Health device: true
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]Extra Pedometer: false
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]Blood glucose device: false
08-16 11:25:25.386  7638  7638 I Feature : [Lifetracker]Device Number: 3
,08-16 11:25:25.396  6956  6956 D BluetoothPermissionRequest: onReceive
08-16 11:25:25.399  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 11:25:25.456  1034  2013 V SIM_STK : Menu title from STK is T-Mobile
08-16 11:25:25.456  1034  2013 V SIM_STK : Menu title from STK is T-Mobile
,08-16 11:25:25.534  1034  1994 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 11:25:25.542  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 11:25:25.546  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 11:25:25.547  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 11:25:25.547  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 11:25:25.547  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 11:25:25.547  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 11:25:25.547  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 11:25:25.547  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 11:25:25.547  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 11:25:25.547  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 11:25:25.547  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 11:25:25.547  7058  7058 I BluetoothA2dpServiceJni: classInitNative
08-16 11:25:25.548  7058  7058 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 11:25:25.548  7058  7058 D A2dpStateMachine: make
08-16 11:25:25.551  7058  7058 I bluedroid-qcom: get_profile_interface a2dp
,08-16 11:25:25.551  7058  7665 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting,
08-16 11:25:25.560  7058  7058 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 11:25:25.560  7058  7058 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 11:25:25.564  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.564  7058  7664 D A2dpStateMachine: Enter Disconnected: -2
,08-16 11:25:25.568  7058  7058 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 11:25:25.572  7058  7058 D HidService: Received start request. Starting profile...
08-16 11:25:25.572  7058  7058 I bluedroid-qcom: get_profile_interface hidhost
08-16 11:25:25.572  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.574  7058  7058 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 11:25:25.578  7058  7058 D HealthService: Received start request. Starting profile...
,08-16 11:25:25.583  7058  7058 I bluedroid-qcom: get_profile_interface health
08-16 11:25:25.584  7058  7058 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 11:25:25.584  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.586  7058  7058 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 11:25:25.592  7058  7058 D PanService: Received start request. Starting profile...
,08-16 11:25:25.592  7058  7058 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 11:25:25.592  7058  7058 I bluedroid-qcom: get_profile_interface pan
,08-16 11:25:25.608  7058  7058 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-16 11:25:25.608  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
,08-16 11:25:25.610  7058  7058 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 11:25:25.625  7058  7058 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 11:25:25.625  7058  7058 D BtGatt.GattService: Received start request. Starting profile...
08-16 11:25:25.625  7058  7058 D BtGatt.GattService: start()
08-16 11:25:25.625  7058  7058 I bluedroid-qcom: get_profile_interface gatt
08-16 11:25:25.626  7058  7058 D BtGatt.AdvertiseManager: advertise manager created
08-16 11:25:25.635  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.637  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.638  7058  7058 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 11:25:25.639  7058  7058 V BluetoothMapService: BluetoothMapBinder()
08-16 11:25:25.640  7058  7058 D BluetoothMapService: Received start request. Starting profile...
08-16 11:25:25.640  7058  7058 D BluetoothMapService: start()
,08-16 11:25:25.643  7058  7058 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 11:25:25.644  7058  7058 D BluetoothMapEmailAppObserver: createReceiver()
08-16 11:25:25.645  7058  7058 D BluetoothMapEmailAppObserver: initObservers()
08-16 11:25:25.646  7058  7058 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-16 11:25:25.655  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:25.656  7058  7058 D HeadsetStateMachine: Proxy object connected
08-16 11:25:25.657  7058  7058 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 11:25:25.657  7058  7058 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-16 11:25:25.662  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 11:25:25.664  7058  7654 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 11:25:25.664  7058  7654 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 11:25:25.665  7058  7654 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 11:25:25.670  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 11:25:25.675  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 11:25:25.680  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 11:25:25.680  7058  7058 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 11:25:25.684  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 11:25:25.687  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 11:25:25.687  7058  7058 V BluetoothMapService: Handler(): got msg=1
,08-16 11:25:25.690  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:25.691  7058  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 11:25:25.691  7058  7617 I bluedroid-qcom: enable
08-16 11:25:25.692  7058  7617 I bt_hci_bdroid: init
08-16 11:25:25.692  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 11:25:25.692  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 11:25:25.692  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 11:25:25.692  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:25.692  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 11:25:25.694  7058  7678 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 11:25:25.694  7058  7678 I bt-btu  : btu_task pending for preload complete event
08-16 11:25:25.696  7058  7617 I bt_vendor: bt-vendor : init
08-16 11:25:25.696  7058  7617 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 11:25:25.696  7058  7617 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 11:25:25.696  7058  7617 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 11:25:25.696  7058  7617 D bt_userial_mct: userial_init
08-16 11:25:25.700  7058  7617 D bt_hci_bdroid: set_power 1
08-16 11:25:25.700  7058  7617 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 11:25:25.700  7058  7617 I bt_vendor: Starting hciattach daemon
08-16 11:25:25.700  7058  7617 I bt_vendor: try to set true
,08-16 11:25:25.695  7681  7681 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:25.695  7681  7681 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:25.728  7682  7682 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 11:25:25.747  1034  1574 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7684 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 11:25:25.816  7714  7714 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 11:25:25.831  7715  7715 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 11:25:25.843  7684  7684 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 11:25:25.854  7719  7719 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 11:25:25.859  1034  1649 I ActivityManager: Killing 6693:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 11:25:25.865  7720  7720 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 11:25:25.876  7009  7009 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-16 11:25:25.876  7009  7009 W System.err: android.os.DeadObjectException
,08-16 11:25:25.877  7009  7009 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 11:25:25.877  7009  7009 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 11:25:25.877  7009  7009 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 11:25:25.877  7009  7009 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 11:25:25.877  7009  7009 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 11:25:25.877  7009  7009 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 11:25:25.877  7009  7009 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 11:25:25.877  7009  7009 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 11:25:25.877  7009  7009 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 11:25:25.877  7722  7722 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 11:25:25.877  7009  7009 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 11:25:25.877  7009  7009 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:25:25.877  7009  7009 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 11:25:25.877  7009  7009 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 11:25:25.877  7009  7009 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 11:25:25.878  7009  7009 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 11:25:25.878  7009  7009 W System.err: android.os.DeadObjectException
08-16 11:25:25.878  7009  7009 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 11:25:25.878  7009  7009 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 11:25:25.878  7009  7009 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 11:25:25.878  7009  7009 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 11:25:25.878  7009  7009 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 11:25:25.878  7009  7009 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 11:25:25.878  7009  7009 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 11:25:25.879  7009  7009 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 11:25:25.879  7009  7009 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 11:25:25.879  7009  7009 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 11:25:25.879  7009  7009 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:25:25.879  7009  7009 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 11:25:25.879  7009  7009 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 11:25:25.879  7009  7009 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 11:25:25.879  7009  7009 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 11:25:25.880  7009  7009 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 11:25:25.902  7724  7724 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 11:25:25.924  7726  7726 I libmdmdetect: ESOC framework not supported
,08-16 11:25:25.926  7726  7726 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 11:25:25.934  7726  7726 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 11:25:25.934  7726  7726 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 11:25:25.934  7726  7726 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 11:25:25.934  7726  7726 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 11:25:25.934  7726  7726 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 11:25:25.934  7726  7726 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 11:25:25.935  7726  7726 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 11:25:25.969  1034  1883 W libprocessgroup: failed to open /acct/uid_1000/pid_6693/cgroup.procs: No such file or directory
08-16 11:25:25.969  1034  1883 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 11:25:25.976  7726  7727 E QC-QMI  : qmi_client [7726] 14: failed to locate client data
08-16 11:25:25.976   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 11:25:25.976   481   481 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 11:25:25.980  7009  7009 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 11:25:25.980  7009  7009 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 11:25:26.059  7728  7728 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
08-16 11:25:26.059  1034  1850 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7729 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 11:25:26.060  7009  7009 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 11:25:26.075  7738  7738 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 11:25:26.115  7058  7617 I bt_vendor: bluetooth satus is on
08-16 11:25:26.115  7058  7617 D bt_hci_bdroid: preload
08-16 11:25:26.115  7058  7680 D bt_userial_mct: userial_open(port:0)
08-16 11:25:26.115  7058  7680 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 11:25:26.119  7058  7680 I bt_vendor: Done intiailizing UART
08-16 11:25:26.120  7058  7680 I bt_vendor: Done intiailizing UART
08-16 11:25:26.120  7058  7680 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 11:25:26.120  7058  7680 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 11:25:26.120  7058  7748 D bt_userial_mct: Entering userial_read_thread()
08-16 11:25:26.120  7058  7678 I bt-btu  : btu_task received preload complete event
08-16 11:25:26.121  7058  7678 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 11:25:26.121  7058  7678 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 11:25:26.123  7058  7678 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 11:25:26.126  7058  7678 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 11:25:26.161  7729  7729 D UEI.SmartControl: Quickset Services start...
,08-16 11:25:26.164  7729  7729 I UEI.SmartControl: Manufacture = LGE
08-16 11:25:26.164  7729  7729 D UEI.SmartControl: Id = LGNevo
08-16 11:25:26.165  7729  7729 D UEI.SmartControl: File observer start...
,08-16 11:25:26.166  7729  7729 E UEI.SmartControl: IR Port is disabled: false
08-16 11:25:26.166  7729  7729 D UEI.SmartControl: Starting file observer...
08-16 11:25:26.166  7729  7729 D UEI.SmartControl: Extracting JNI libs...
08-16 11:25:26.167  7729  7729 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 11:25:26.213  7058  7678 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 11:25:26.213  7058  7678 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a2061 
08-16 11:25:26.213  7058  7678 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a2061 
,08-16 11:25:26.247  7729  7729 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-16 11:25:26.247  7729  7729 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 11:25:26.247  7729  7729 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 11:25:26.257  7058  7621 E bt-btif : Calling BTA_HhEnable
,08-16 11:25:26.257  7058  7621 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 11:25:26.258  7058  7621 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 11:25:26.259  7058  7678 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 11:25:26.259  7058  7678 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-16 11:25:26.259  7058  7678 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 11:25:26.259  7058  7678 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 11:25:26.259  7058  7678 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 11:25:26.261  7058  7621 D BluetoothAdapterProperties: Name is: G3
08-16 11:25:26.261  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 11:25:26.262  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 11:25:26.262  7058  7621 D BluetoothAdapterProperties: Scan Mode:20
08-16 11:25:26.264  7058  7621 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 11:25:26.265  7058  7621 D bt_hci_bdroid: postload
,08-16 11:25:26.265  7058  7680 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:26.266  7058  7678 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 11:25:26.267  7058  7621 D bte_conf: Device ID record 1 : primary
08-16 11:25:26.267  7058  7621 D bte_conf:   vendorId            = 00c4
08-16 11:25:26.267  7058  7621 D bte_conf:   vendorIdSource      = 0001
08-16 11:25:26.267  7058  7621 D bte_conf:   product             = 13a1
08-16 11:25:26.267  7058  7621 D bte_conf:   version             = 1000
08-16 11:25:26.267  7058  7621 D bte_conf:   clientExecutableURL = 
08-16 11:25:26.267  7058  7621 D bte_conf:   serviceDescription  = 
08-16 11:25:26.267  7058  7621 D bte_conf:   documentationURL    = 
08-16 11:25:26.267  7058  7621 D bte_conf: bte_load_did_conf no section named DID2.
08-16 11:25:26.269  7058  7680 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:26.269  7058  7680 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:26.270  7058  7680 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:26.270  7058  7680 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 11:25:26.265  7751  7751 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:26.275  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:26.265  7751  7751 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:26.276  7058  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 11:25:26.276  7058  7617 D BluetoothAdapterProperties: ScanMode =  20
08-16 11:25:26.276  7058  7617 D BluetoothAdapterProperties: State =  11
08-16 11:25:26.276  7058  7678 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:26.276  7058  7678 W bt-smp  : Plain text(LSB ~ MSB) = 45 f0 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:26.276  7058  7678 W bt-smp  : Encrypted text(LSB ~ MSB) = 03 40 08 e1 ff 88 79 a6 78 87 29 74 bc 9d 6c 31 
08-16 11:25:26.276  7058  7678 W bt-btm  : Stopping oneshot timer
08-16 11:25:26.276  7058  7617 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 11:25:26.276  7058  7680 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:26.276  7058  7680 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:26.277  7058  7617 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 11:25:26.277  7058  7617 D BluetoothAdapterProperties: Setting state to 12
08-16 11:25:26.277  7058  7617 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 11:25:26.278  1034  1110 D BluetoothManagerService: Message: 60
08-16 11:25:26.278  7058  7621 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 11:25:26.278  7058  7617 I BluetoothAdapterState: Entering On State
08-16 11:25:26.279  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 11:25:26.279  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 11:25:26.281  7058  7621 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 11:25:26.281  7058  7748 E bt_mct  : hci lib postload completed
08-16 11:25:26.282  1851  2668 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:25:26.282  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:26.282  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:26.282  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:26.282  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:26.282  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:26.282  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:26.282  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:26.282  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:25:26.286  7058  7617 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 11:25:26.286  7058  7617 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 11:25:26.286  7058  7617 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 11:25:26.287  7058  7617 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 11:25:26.289  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:26.289  1034  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 11:25:26.291  6956  6975 D BluetoothPan: onBluetoothStateChange on: true
08-16 11:25:26.291  6956  6975 D BluetoothPan: onBluetoothStateChange call bindService
08-16 11:25:26.294  1851  1851 D BluetoothHeadset: Proxy object connected
,08-16 11:25:26.296  1034  1034 D BluetoothA2dp: Proxy object connected
08-16 11:25:26.298  7058  7678 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:26.298  7058  7678 W bt-smp  : Plain text(LSB ~ MSB) = af 74 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:26.298  7058  7678 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 4d 36 5b 28 44 34 12 e7 79 5f 55 17 2f 0a dd 
08-16 11:25:26.298  7058  7678 W bt-btm  : Stopping oneshot timer
08-16 11:25:26.298  6956  6976 D BluetoothMap: onBluetoothStateChange: up=true
08-16 11:25:26.300  6956  6956 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 11:25:26.300  6956  6956 D PanProfile: Bluetooth service connected
08-16 11:25:26.301  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:26.301  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:26.301  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:26.301  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:26.301  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:26.301  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:26.301  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:26.301  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:26.303  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:26.304  7058  7621 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 11:25:26.304  7058  7621 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 11:25:26.310  7758  7758 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 11:25:26.311  7058  7678 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:26.311  7058  7678 W bt-smp  : Plain text(LSB ~ MSB) = 7e 99 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:26.311  7058  7678 W bt-smp  : Encrypted text(LSB ~ MSB) = 1c 2d 52 ca 23 5e 60 b3 f0 3d e1 2b 59 05 39 a9 
08-16 11:25:26.311  7058  7678 W bt-btm  : Stopping oneshot timer
,08-16 11:25:26.320  7058  7678 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:26.320  7058  7678 W bt-smp  : Plain text(LSB ~ MSB) = 96 20 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:26.320  7058  7678 W bt-smp  : Encrypted text(LSB ~ MSB) = 40 e5 c4 0f af d6 f6 72 02 25 f9 f2 df a4 8a 68 
08-16 11:25:26.320  7729  7729 I UEI.SmartControl: --- Selecting new region: 6
08-16 11:25:26.320  7058  7678 W bt-btm  : Stopping oneshot timer
08-16 11:25:26.322  7729  7729 I UEI.SmartControl: Model = LG-D855
,08-16 11:25:26.324  7729  7729 D UEI.SmartControl: QS Service created
08-16 11:25:26.328  7058  7617 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 11:25:26.330  7058  7678 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:26.330  7058  7678 W bt-smp  : Plain text(LSB ~ MSB) = 6e cb 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:26.330  7058  7678 W bt-smp  : Encrypted text(LSB ~ MSB) = 6a 5e 3f 0f 7d 3e 1a 21 1f 16 e7 30 7c 3a 11 30 
08-16 11:25:26.330  7058  7678 W bt-btm  : Stopping oneshot timer
08-16 11:25:26.389  1034  1110 I art     : Explicit concurrent mark sweep GC freed 128618(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.493ms total 88.246ms
08-16 11:25:26.391  6956  6975 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 11:25:26.393  1851  2375 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:25:26.394  6956  6956 D BluetoothMap: Proxy object connected
08-16 11:25:26.394  6956  6956 D MapProfile: Bluetooth service connected
08-16 11:25:26.394  6956  6956 D BluetoothMap: getConnectedDevices()
,08-16 11:25:26.395  1851  1851 D BluetoothHeadset: Proxy object connected
08-16 11:25:26.399  1851  2668 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:25:26.400  7058  7755 V BluetoothMapService: getConnectedDevices()
08-16 11:25:26.400  1851  1851 D BluetoothHeadset: Proxy object connected
08-16 11:25:26.400  6956  6976 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 11:25:26.401  1034  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:25:26.402  1034  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 11:25:26.402  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 11:25:26.402  1034  1034 D BluetoothHeadset: Proxy object connected
08-16 11:25:26.403  6956  6956 D BluetoothInputDevice: Proxy object connected
08-16 11:25:26.403  6956  6956 D HidProfile: Bluetooth service connected
,08-16 11:25:26.406  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 11:25:26.409  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:26.409  1940  2124 D LGBluetoothAPIService: Message: 1
08-16 11:25:26.409  1940  2124 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-16 11:25:26.412  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 11:25:26.412  1034  1110 D BluetoothManagerService: Message: 40
08-16 11:25:26.413  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 11:25:26.416  6792  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 11:25:26.417  1940  2124 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 11:25:26.419  7729  7729 I UEI.SmartControl: Service initServices...
,08-16 11:25:26.420  7058  7058 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:26.420  7058  7058 D BluetoothMapService: STATE_ON
08-16 11:25:26.421  7058  7058 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 11:25:26.421  7058  7058 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 11:25:26.423  6956  6956 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 11:25:26.425  1034  1110 D BluetoothManagerService: Message: 30
08-16 11:25:26.425  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 11:25:26.425  1940  2124 D LGBluetoothAPIService: Message: 100
08-16 11:25:26.425  1940  2124 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 11:25:26.426  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:26.426  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:26.426  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:26.426  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:26.426  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:26.426  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:26.426  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:26.426  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:26.427  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:26.428  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:26.429  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:26.430  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:26.430  7058  7058 V BluetoothPbapService: Pbap Service onCreate
08-16 11:25:26.430  6956  6956 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 11:25:26.430  7058  7058 V BluetoothPbapService: Starting PBAP service
,08-16 11:25:26.433  1034  1110 D BluetoothManagerService: Message: 30
08-16 11:25:26.433  7058  7058 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 11:25:26.433  7058  7058 V BluetoothMapService: Handler(): got msg=1
08-16 11:25:26.434  7058  7058 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 11:25:26.434  7729  7729 D UEI.SmartControl: QS start get config
08-16 11:25:26.434  7058  7058 V BluetoothPbapService: Pbap Service onBind
08-16 11:25:26.435  7058  7058 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:26.435  7058  7058 V BluetoothPbapService: state: 12
08-16 11:25:26.435  7058  7759 D BluetoothMapMasInstance: MAS initSocket()
08-16 11:25:26.435  7058  7058 V BluetoothPbapService: Handler(): got msg=1
08-16 11:25:26.435  7058  7759 D BluetoothMapMasInstance:   masId = 00
08-16 11:25:26.435  7058  7759 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 11:25:26.435  7058  7759 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 11:25:26.435  7058  7759 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 11:25:26.435  7058  7058 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 11:25:26.436  1034  2031 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:26.436  7058  7760 V BluetoothPbapService: Pbap Service initSocket
08-16 11:25:26.437  1034  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 11:25:26.437  7058  7759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:25:26.438  7058  7760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:25:26.438  7058  7759 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 11:25:26.438  7058  7759 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 11:25:26.438  7058  7759 D BluetoothMapMasInstance: Accepting socket connection...
08-16 11:25:26.439  7058  7760 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 11:25:26.439  7058  7760 V BluetoothPbapService: Succeed to create listening socket 
08-16 11:25:26.439  7058  7760 V BluetoothPbapService: Accepting socket connection...
08-16 11:25:26.440  7058  7621 D BluetoothAdapterProperties: Scan Mode:21
08-16 11:25:26.440  7058  7621 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 11:25:26.441  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 11:25:26.441  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:25:26.443  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:26.443  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 11:25:26.444  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:26.447  6956  6956 D BluetoothA2dp: Proxy object connected
08-16 11:25:26.447  6956  6956 D A2dpProfile: Bluetooth service connected
08-16 11:25:26.448  6956  6956 D BluetoothPbap: Proxy object connected
08-16 11:25:26.448  6956  6956 D PbapServerProfile: Bluetooth service connected
08-16 11:25:26.448  6956  6956 D BluetoothHeadset: Proxy object connected
08-16 11:25:26.449  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 11:25:26.449  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:26.449  7058  7058 V BluetoothPbapReceiver: ***********state = 12
08-16 11:25:26.450  6956  6956 D HeadsetProfile: Bluetooth service connected
08-16 11:25:26.451  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 11:25:26.452  2211  2211 D c       : Getting all permits...
08-16 11:25:26.452  2211  2211 D a       : Opening database...
08-16 11:25:26.454  6956  6956 D DockEventReceiver: finishStartingService: stopping service
08-16 11:25:26.457  2211  2211 D a       : Opening database auth.proximity.permit_store...
08-16 11:25:26.458  2211  2211 D a       : Closing database...
08-16 11:25:26.465  6956  6956 D BluetoothPermissionRequest: onReceive
,08-16 11:25:26.467  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 11:25:26.468  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 11:25:26.471  7058  7058 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 11:25:26.471  7058  7058 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 11:25:26.475  7058  7058 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-16 11:25:26.492  7058  7058 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 11:25:26.492  7058  7058 V BtOppService: onCreate
08-16 11:25:26.497  7058  7058 V BluetoothOppNotification: send message
08-16 11:25:26.500  7058  7058 V BtOppService: Starting RfcommListener
08-16 11:25:26.505  7058  7058 D BluetoothOppPreference: Dumping Names:  
,08-16 11:25:26.505  7058  7058 D BluetoothOppPreference: {}
08-16 11:25:26.505  7058  7058 D BluetoothOppPreference: Dumping Channels:  
08-16 11:25:26.505  7058  7058 D BluetoothOppPreference: {}
08-16 11:25:26.506  7058  7058 V BtOppService: onStartCommand
08-16 11:25:26.509  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:26.509  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 11:25:26.510  7058  7764 V BtOppService: Deleted complete outbound shares, number =  0
08-16 11:25:26.512  7058  7764 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 11:25:26.512  7058  7058 V BluetoothOppNotification: new notify threadi!
08-16 11:25:26.513  7058  7058 V BluetoothOppNotification: send delay message
08-16 11:25:26.514  7058  7764 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 11:25:26.514  7058  7058 V BtOppService: start RfcommListener
08-16 11:25:26.515  7058  7767 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 11:25:26.515  7058  7764 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31878e9f on behalf of 
08-16 11:25:26.516  7058  7767 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 11:25:26.518  7058  7058 V BtOppService: RfcommListener started
08-16 11:25:26.518  7058  7767 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12265bec on behalf of 
08-16 11:25:26.518  7058  7058 V BtOppService: ContentObserver received notification
08-16 11:25:26.519  7058  7768 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 11:25:26.519  7729  7729 D UEI.SmartControl: Loading JNI Libs...
08-16 11:25:26.520  7058  7769 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 11:25:26.521  1034  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:26.521  7058  7767 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 11:25:26.521  7058  7767 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 11:25:26.522  7058  7769 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:25:26.522  7058  7767 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2edf3bb5 on behalf of 
08-16 11:25:26.523  7058  7767 V BluetoothOppNotification: update too frequent, put in queue
08-16 11:25:26.523  7058  7769 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 11:25:26.524  7058  7769 V BtOppRfcommListener: Started RFCOMM listener....
08-16 11:25:26.524  7058  7769 I BtOppRfcommListener: Accept thread started.
08-16 11:25:26.524  7058  7767 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 11:25:26.524  7058  7769 V BtOppRfcommListener: Accepting connection...
,08-16 11:25:26.524  7058  7768 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c3bc24a on behalf of 
08-16 11:25:26.525  7058  7768 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 11:25:26.527  7058  7768 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 11:25:26.528  7058  7768 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9e075bb on behalf of 
08-16 11:25:26.529  7058  7768 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 11:25:26.530  7058  7768 V BluetoothOppNotification: outbound notification was removed.
08-16 11:25:26.530  7058  7768 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 11:25:26.531  7058  7768 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22134ad8 on behalf of 
08-16 11:25:26.532  7058  7768 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 11:25:26.532  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:26.532  7058  7058 V BluetoothFtpService: Ftp Service onCreate
08-16 11:25:26.532  7058  7058 I BluetoothFtpService: Ftp Service onCreate
08-16 11:25:26.533  7058  7058 V BluetoothFtpService: Ftp Service onStartCommand
08-16 11:25:26.533  7058  7058 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:26.533  7058  7058 V BluetoothFtpService: Starting Listening on sockets
08-16 11:25:26.533  7058  7058 V BtOppService: ContentObserver received notification
08-16 11:25:26.533  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 11:25:26.533  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 11:25:26.533  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 11:25:26.533  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:26.534  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 11:25:26.534  7058  7058 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 11:25:26.535  7058  7770 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 11:25:26.535  7058  7770 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 11:25:26.536  7058  7058 V BluetoothFtpService: Handler(): got msg=1
,08-16 11:25:26.539  7058  7058 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 11:25:26.539  7058  7058 V BluetoothFtpService: Ftp Service initSocket
08-16 11:25:26.540  7058  7770 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@357bb916 on behalf of 
08-16 11:25:26.542  1034  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:26.542  7058  7770 V BluetoothOppNotification: update too frequent, put in queue
08-16 11:25:26.543  7058  7768 V BluetoothOppNotification: inbound notification was removed.
08-16 11:25:26.543  7058  7058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:25:26.543  7058  7768 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 11:25:26.543  7058  7058 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-16 11:25:26.543  7058  7058 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 11:25:26.544  7058  7770 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 11:25:26.544  7058  7768 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3516b297 on behalf of 
08-16 11:25:26.547  7058  7771 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 11:25:26.559  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:26.559  7058  7058 V BluetoothSapService: Sap Service onCreate
08-16 11:25:26.560  7058  7058 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:26.560  7058  7058 V BluetoothSapService: state: 12
08-16 11:25:26.561  7058  7058 V BluetoothSapService: Starting SAP server process
,08-16 11:25:26.545  7772  7772 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:26.563  7058  7058 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 11:25:26.545  7772  7772 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:26.564  7058  7773 V BluetoothSapService: Sap Service initRfcommSocket
08-16 11:25:26.565  1034  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:26.565  7058  7773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:25:26.567  7058  7773 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-16 11:25:26.567  7058  7773 V BluetoothSapService: Succeed to create listening socket 
08-16 11:25:26.567  7058  7773 V BluetoothSapService: Accepting socket connection...
08-16 11:25:26.574  7772  7772 V BT_SAP  : Event pipe created
08-16 11:25:26.574  7772  7772 V BT_SAP  : create_server_socket qcom.sap.server
08-16 11:25:26.574  7772  7772 V BT_SAP  : created socket fd 6
,08-16 11:25:26.781  7729  7729 I UEI.SmartControl: Supports setup maps: true
,08-16 11:25:26.785  7729  7729 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 11:25:26.785  7729  7729 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-16 11:25:26.785  7729  7729 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 11:25:26.785  7729  7729 I UEI.SmartControl: ### init IR Blaster...
08-16 11:25:26.791  7729  7729 D serial_port: Configuring serial port
08-16 11:25:26.794  7729  7729 E UEI.SmartControl: UEIBLaster setting for 616
08-16 11:25:26.794  7729  7729 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 11:25:26.795  7729  7729 I UEI.SmartControl: configuring settings for MAXQ616
08-16 11:25:26.795  7729  7729 I UEI.SmartControl: Get version...
08-16 11:25:26.812  7729  7774 D UEI.SmartControl: serial port data available: 21
,08-16 11:25:26.842  7729  7729 D UEI.SmartControl: MAXQ616 A2-X4 software.,
,08-16 11:25:26.842  7729  7729 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 11:25:26.843  7729  7729 I UEI.SmartControl: QS saving settings...
08-16 11:25:26.846  7729  7729 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 11:25:26.865  7729  7774 D UEI.SmartControl: serial port data available: 4
,08-16 11:25:26.912  7729  7783 I UEI.SmartControl: Device manager: loading config....
08-16 11:25:26.913  7729  7783 D UEI.SmartControl: ----------- loading internal config...
,08-16 11:25:26.915  7729  7729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 11:25:26.921  7729  7729 E UEI.SmartControl: Services init done
08-16 11:25:26.922  7729  7729 D UEI.SmartControl: QS Service init finished
08-16 11:25:26.924  7729  7729 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 11:25:26.924  7729  7729 D UEI.SmartControl: QS Service version code: 201091
08-16 11:25:26.926  7729  7729 D UEI.SmartControl: Service requested: Control
08-16 11:25:26.930  7729  7783 E UEI.SmartControl: Loading SETTINGS...
,08-16 11:25:26.931  7729  7729 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 11:25:26.938  1034  2031 I ActivityManager: Killing 7009:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 11:25:26.938  7729  7783 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 11:25:26.949  7729  7782 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 11:25:26.949  7729  7782 D UEI.SmartControl: -----service ready thread exits
,08-16 11:25:26.975  1034  2013 W libprocessgroup: failed to open /acct/uid_10112/pid_7009/cgroup.procs: No such file or directory
,08-16 11:25:26.979  7729  7729 D UEI.SmartControl: Internal service binding...
08-16 11:25:27.006  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 11:25:27.029  1034  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 11:25:27.051  1034  1034 D administrator: Handling package changes for user 0
,08-16 11:25:27.065  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 11:25:27.080  1034  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7785 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 11:25:27.098  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 11:25:27.099  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-16 11:25:27.122  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 11:25:27.142  7785  7785 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 11:25:27.166  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 11:25:27.166  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 11:25:27.234  1034  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 11:25:27.241  7785  7785 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:27.241  1034  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 11:25:27.241  7785  7785 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 11:25:27.249  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 11:25:27.249  2461  2461 V GmsNetworkLocationProvi: DISABLE
,08-16 11:25:27.278  1034  1090 D LocationProviderProxy: applying state to connected service
,08-16 11:25:27.278  2461  2461 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 11:25:27.372  7785  7824 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 11:25:27.372  7785  7824 I Babel   : MmsConfig.loadMmsSettings
,08-16 11:25:27.380  7785  7824 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 11:25:27.380  7785  7824 I Babel   : MmsConfig.loadFromDatabase
,08-16 11:25:27.398  7785  7824 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 11:25:27.399  7785  7824 I Babel   : MmsConfig.loadFromResources
08-16 11:25:27.401  7785  7824 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 11:25:27.401  7785  7824 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 11:25:27.420  7785  7785 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 11:25:27.446  7785  7822 W AudioCapabilities: Unsupported mime audio/evrc
08-16 11:25:27.449  7785  7822 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 11:25:27.450  1815  7827 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 11:25:27.451  1815  7827 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 11:25:27.451  7785  7822 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 11:25:27.459  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 11:25:27.467  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cb52bc4
08-16 11:25:27.467  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 11:25:27.467  7137  7137 D AppUp4:CustFacade: isPhone : true
08-16 11:25:27.468  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-16 11:25:27.468  7137  7137 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 11:25:27.471  1815  4754 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 11:25:27.483  7785  7822 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-16 11:25:27.490  7785  7822 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 11:25:27.491  7785  7822 W AudioCapabilities: Unsupported mime audio/evrc
08-16 11:25:27.500  7785  7822 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 11:25:27.502  7785  7822 W VideoCapabilities: Unsupported mime video/divx
08-16 11:25:27.504  7785  7822 W VideoCapabilities: Unsupported mime video/divx311
08-16 11:25:27.506  7785  7822 W VideoCapabilities: Unsupported mime video/divx4
08-16 11:25:27.510  1034  2031 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7830 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 11:25:27.512  7785  7822 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 11:25:27.514  7058  7058 V BluetoothOppNotification: new notify threadi!
08-16 11:25:27.514  7058  7058 V BluetoothOppNotification: send delay message
08-16 11:25:27.515  7058  7836 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 11:25:27.517  1034  1883 I ActivityManager: Killing 6980:com.lge.sync/1000 (adj 15): empty #17
08-16 11:25:27.518  7058  7836 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3109e133 on behalf of 
08-16 11:25:27.519  7058  7836 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 11:25:27.519  7058  7836 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 11:25:27.525  7058  7836 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4449cf0 on behalf of 
,08-16 11:25:27.528  7058  7836 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 11:25:27.541  7785  7822 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 11:25:27.543  7058  7836 V BluetoothOppNotification: outbound notification was removed.
08-16 11:25:27.544  7058  7836 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 11:25:27.546  7058  7836 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@aa82269 on behalf of 
08-16 11:25:27.546  7785  7822 W AudioCapabilities: Unsupported mime audio/eac3
08-16 11:25:27.547  7785  7822 W AudioCapabilities: Unsupported mime audio/ac3
08-16 11:25:27.548  7785  7822 W AudioCapabilities: Unsupported mime audio/g726
08-16 11:25:27.549  7785  7822 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 11:25:27.550  7785  7822 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 11:25:27.551  7785  7822 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 11:25:27.551  7058  7836 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 11:25:27.553  7058  7836 V BluetoothOppNotification: inbound notification was removed.
08-16 11:25:27.553  7058  7836 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 11:25:27.553  7785  7822 W VideoCapabilities: Unsupported mime video/theora
08-16 11:25:27.553  7058  7836 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a48d4ee on behalf of 
,08-16 11:25:27.555  7785  7822 W VideoCapabilities: Unsupported mime video/mjpg
,08-16 11:25:27.618  1034  2031 W libprocessgroup: failed to open /acct/uid_1000/pid_6980/cgroup.procs: No such file or directory
,08-16 11:25:27.663  7830  7830 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 11:25:27.665  7830  7830 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 11:25:27.665  7830  7830 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 11:25:27.667  7830  7830 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 11:25:27.667  7830  7830 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 11:25:27.740  7830  7830 I SystemConfig: BUILD Country: EU
08-16 11:25:27.741  7830  7830 I SystemConfig: BUILD Operator: OPEN
,08-16 11:25:27.784  1034  1850 I ActivityManager: Killing 7162:com.lge.email/u0a23 (adj 15): empty #17
,08-16 11:25:27.862  1034  1050 W libprocessgroup: failed to open /acct/uid_10023/pid_7162/cgroup.procs: No such file or directory
,08-16 11:25:27.867  7830  7849 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 11:25:27.867  7830  7849 I SystemConfig: existFile = false
08-16 11:25:27.868  7830  7849 I SystemConfig: canReadFile = false
08-16 11:25:27.869  7830  7849 I SystemConfig: systemFeature RCS result false
08-16 11:25:27.870  7830  7849 D SystemConfig: refreshRcsSupport() :false
08-16 11:25:27.905  1034  1850 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7851 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 11:25:27.967  7851  7851 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 11:25:27.967  7851  7851 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 11:25:27.967  7851  7851 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 11:25:27.968  7851  7851 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 11:25:28.078  7851  7851 I AppConfig: Total System Memory = 2995761152
,08-16 11:25:28.089  7851  7851 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 11:25:28.214  1034  1918 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7876 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 11:25:28.225  1034  1918 I ActivityManager: Killing 7075:com.lge.formmanager/u0a26 (adj 15): empty #17
08-16 11:25:28.284  1034  2049 W libprocessgroup: failed to open /acct/uid_10026/pid_7075/cgroup.procs: No such file or directory
,08-16 11:25:28.349  1034  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3f12561c type 2 when 387995 com.google.android.gms} when 387995
,08-16 11:25:28.509  7876  7876 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 11:25:28.598  7876  7876 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 11:25:28.599  7876  7876 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:28.641  7876  7876 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 11:25:28.674  7876  7876 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 11:25:28.675  7876  7876 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 11:25:28.710  7876  7876 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-16 11:25:28.711  7876  7876 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 11:25:28.733  1034  1883 I ActivityManager: Killing 6486:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 11:25:28.786  1034  1960 W libprocessgroup: failed to open /acct/uid_1000/pid_6486/cgroup.procs: No such file or directory
,08-16 11:25:28.802  4607  7919 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-16 11:25:28.809  3531  3546 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 11:25:28.811  3531  3546 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2e9e46f2 on behalf of 7876
08-16 11:25:28.877  1034  1925 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7920 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 11:25:28.911  7876  7876 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 11:25:28.934  7876  7876 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-16 11:25:28.966  7920  7920 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 11:25:28.993  7920  7920 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-16 11:25:28.994  7920  7920 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 11:25:28.994  7920  7920 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 11:25:28.994  7920  7920 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 11:25:28.994  7920  7920 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 11:25:28.994  7920  7920 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-16 11:25:29.018   315  7942 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 11:25:29.021  1034  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 11:25:29.051  1034  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7943 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 11:25:29.058  1034  2031 I ActivityManager: Killing 7445:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-16 11:25:29.075   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 457us total 21.490ms
,08-16 11:25:29.096   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 508us total 20.485ms
,08-16 11:25:29.117   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 19.662ms
,08-16 11:25:29.128  1034  1649 W libprocessgroup: failed to open /acct/uid_10005/pid_7445/cgroup.procs: No such file or directory
,08-16 11:25:29.152  7943  7943 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 11:25:29.187  7943  7943 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 11:25:29.231  7943  7943 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-16 11:25:29.232  7943  7943 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 11:25:29.232  7943  7943 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 11:25:29.232  7943  7943 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 11:25:29.233  7943  7943 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 11:25:29.235  7943  7943 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 11:25:29.240  7943  7943 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 11:25:29.247  7943  7943 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 11:25:29.248  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9614
,08-16 11:25:29.252  7943  7943 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 11:25:29.255  7943  7943 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 11:25:29.256  7943  7943 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 11:25:29.256  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 11:25:29.257  7943  7943 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-16 11:25:29.271  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-16 11:25:29.296  4607  7919 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 494 ms] updated apps [took 494 ms] 
,08-16 11:25:29.296  7943  7943 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:29.296  7943  7943 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 11:25:29.305  7943  7943 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-16 11:25:29.308  7943  7943 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
08-16 11:25:29.308  7943  7943 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
,08-16 11:25:29.308  7943  7943 V SoundPool: doLoad: loading sample sampleID=1
08-16 11:25:29.309  7943  7963 V SoundPool: Start decode
08-16 11:25:29.309  7943  7963 V MediaPlayer[Native]: decode(30, 10857164, 17813)
08-16 11:25:29.310   320  1384 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 11:25:29.310   320  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 11:25:29.310   320  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 11:25:29.310   320  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 11:25:29.310   320  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 11:25:29.310   320  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 11:25:29.310   320  1384 V MediaPlayerService: player type = 3
08-16 11:25:29.310   320  1384 V AwesomePlayer: AwesomePlayer create()
08-16 11:25:29.311   320  1384 V AwesomePlayer: reset_l() 
08-16 11:25:29.311   320  1384 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:29.311   320  1384 V AwesomePlayer: setAudioSink() 
08-16 11:25:29.311   320  1384 V AwesomePlayer: reset_l() 
08-16 11:25:29.311   320  1384 V AudioCache: notify(0xb5474500, 8, 0, 0)
08-16 11:25:29.311   320  1384 V AudioCache: ignored
08-16 11:25:29.311   320  1384 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:29.311   320  1384 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 11:25:29.311   320  1384 V AwesomePlayer: setDataSource_l dataSource
08-16 11:25:29.312   320  1384 V LGParserOSAL: SniffLGParser start
08-16 11:25:29.312   320  1384 V LGParserOSAL: MainType:5, SubType=0
08-16 11:25:29.312   320  1384 V LGParserOSAL: #### check Mime : application/ogg
08-16 11:25:29.312   320  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 11:25:29.312   320  1384 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 11:25:29.312  7943  7943 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 11:25:29.316  7943  7943 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 11:25:29.318  7943  7943 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-16 11:25:29.318  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-16 11:25:29.333  7943  7943 V LGMDMManager: Create singleton instance,
08-16 11:25:29.364   320  1384 V LGParserOSAL: supported mime: application/ogg
08-16 11:25:29.364   320  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 11:25:29.364   320  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 11:25:29.364   320  1384 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 11:25:29.364   320  1384 V AwesomePlayer: AudioTrack Setting
08-16 11:25:29.364   320  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 11:25:29.364   320  1384 V AwesomePlayer: setAudioSource() 
08-16 11:25:29.364   320  1384 V MediaPlayerService: prepare
08-16 11:25:29.364   320  1384 V AwesomePlayer: prepareAsync_l() 
08-16 11:25:29.364   320  1384 V MediaPlayerService: wait for prepare
,08-16 11:25:29.366   320  7964 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 11:25:29.366   320  7964 V AwesomePlayer: initAudioDecoder() 
08-16 11:25:29.366   320  7964 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 11:25:29.366   320  7964 V AudioSystem: isOffloadSupported()
08-16 11:25:29.366   320  7964 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 11:25:29.366   320  7964 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 11:25:29.366   320  7964 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 11:25:29.366   320  7964 V AwesomePlayer: getUseOffload() = 0 
08-16 11:25:29.367   320  7964 V OMXCodec: OMXCodec::Create
08-16 11:25:29.367   320  7964 V OMXCodec: findMatchingCodecs()
08-16 11:25:29.367   320  7964 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 11:25:29.367   320  7964 V OMXCodec: matchingCodecs.size()=1
08-16 11:25:29.367   320  7964 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 11:25:29.371   320  7964 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 11:25:29.371   320  7964 V LGCodecAdapter: LG Codec Adapter start
08-16 11:25:29.371   320  7964 V OMXCodec: OMXCodec Createtor
08-16 11:25:29.371   320  7964 V OMXCodec: setComponentRole
08-16 11:25:29.372   320  7964 V OMXCodec: configureCodec protected=0
08-16 11:25:29.372   320  7964 V LGCodecAdapter: called getLGCodecSpecificData
08-16 11:25:29.372   320  7964 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 11:25:29.372   320  7964 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 11:25:29.372   320  7964 V LGCodecOSAL: Called LGconfigureCodecMSG
,08-16 11:25:29.372   320  7964 V LGCodecOSAL: Not support LGCodec
08-16 11:25:29.372   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 11:25:29.372   320  7964 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 11:25:29.372   320  7964 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
,08-16 11:25:29.372   320  7964 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 11:25:29.373   320  7964 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 11:25:29.373   320  7964 V AudioSystem: isOffloadSupported()
08-16 11:25:29.373   320  7964 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 11:25:29.373   320  7964 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 11:25:29.373   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
,08-16 11:25:29.373   320  7964 V OMXCodec: init()
08-16 11:25:29.373   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 11:25:29.373   320  7964 V OMXCodec: allocateBuffers
08-16 11:25:29.373   320  7964 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 11:25:29.373   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 11:25:29.374   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
,08-16 11:25:29.374   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-16 11:25:29.374   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-16 11:25:29.374   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on input port
08-16 11:25:29.374   320  7964 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 11:25:29.374   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 11:25:29.375   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9150 on output port
08-16 11:25:29.375   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f92e0 on output port
08-16 11:25:29.375   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9740 on output port
,08-16 11:25:29.375   320  7964 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9790 on output port
08-16 11:25:29.375   320  7964 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 11:25:29.375   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 11:25:29.375   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 11:25:29.375   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,08-16 11:25:29.375   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 11:25:29.375   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 11:25:29.375   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 11:25:29.375   320  7964 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 11:25:29.375   320  7964 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 11:25:29.375   320  7964 V AudioCache: notify(0xb5474500, 5, 0, 0)
08-16 11:25:29.376   320  7964 V AudioCache: ignored
08-16 11:25:29.376   320  7964 V AudioCache: notify(0xb5474500, 1, 0, 0)
,08-16 11:25:29.376   320  7964 V AudioCache: prepared
08-16 11:25:29.376   320  1384 V AudioCache: wait - success
08-16 11:25:29.376   320  1384 V MediaPlayerService: start
08-16 11:25:29.376   320  1384 V AwesomePlayer: play_l() 
08-16 11:25:29.376   320  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 11:25:29.376   320  1384 V AwesomePlayer: createAudioPlayer_l
08-16 11:25:29.376   320  1384 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 11:25:29.376   320  1384 V AwesomePlayer: startAudioPlayer_l() 
,08-16 11:25:29.376   320  1384 D AudioPlayer: start of Playback, useOffload 0
08-16 11:25:29.376   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 11:25:29.376   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 11:25:29.379   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 11:25:29.379   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 11:25:29.379   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 11:25:29.381   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 11:25:29.381   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 11:25:29.381   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-16 11:25:29.382   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045036368
08-16 11:25:29.382   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:29.382   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045036768
08-16 11:25:29.382   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:29.383   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045037888
08-16 11:25:29.383   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:29.383   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045037968
08-16 11:25:29.383   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:29.383   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,08-16 11:25:29.383   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 11:25:29.383   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 11:25:29.383   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 11:25:29.383   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,08-16 11:25:29.385   320  7966 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 11:25:29.385   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 11:25:29.385   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9740 on output port
08-16 11:25:29.385   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f92e0 on output port
08-16 11:25:29.385   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9150 on output port
08-16 11:25:29.385   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-16 11:25:29.385   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 11:25:29.385   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 11:25:29.387   320  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 11:25:29.387   320  1384 V AudioCache: notify(0xb5474500, 6, 0, 0)
08-16 11:25:29.387   320  1384 V AudioCache: ignored
08-16 11:25:29.388   320  1384 V MediaPlayerService: wait for playback complete
08-16 11:25:29.389   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.389   320  7967 V AudioCache: memcpy(0xaf006000, 0xb16f8000, 4096)
08-16 11:25:29.391   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.391   320  7967 V AudioCache: memcpy(0xaf007000, 0xb16f8000, 4096)
08-16 11:25:29.392   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.392   320  7967 V AudioCache: memcpy(0xaf008000, 0xb16f8000, 4096)
08-16 11:25:29.393   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.393   320  7967 V AudioCache: memcpy(0xaf009000, 0xb16f8000, 4096)
08-16 11:25:29.394   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.394   320  7967 V AudioCache: memcpy(0xaf00a000, 0xb16f8000, 4096)
08-16 11:25:29.395   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.395   320  7967 V AudioCache: memcpy(0xaf00b000, 0xb16f8000, 4096)
08-16 11:25:29.395   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.395   320  7967 V AudioCache: memcpy(0xaf00c000, 0xb16f8000, 4096)
08-16 11:25:29.396   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.396   320  7967 V AudioCache: memcpy(0xaf00d000, 0xb16f8000, 4096)
08-16 11:25:29.397   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.397   320  7967 V AudioCache: memcpy(0xaf00e000, 0xb16f8000, 4096)
08-16 11:25:29.397   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.397   320  7967 V AudioCache: memcpy(0xaf00f000, 0xb16f8000, 4096)
08-16 11:25:29.397   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.397   320  7967 V AudioCache: memcpy(0xaf010000, 0xb16f8000, 4096)
08-16 11:25:29.399   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.399   320  7967 V AudioCache: memcpy(0xaf011000, 0xb16f8000, 4096)
08-16 11:25:29.400   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.400   320  7967 V AudioCache: memcpy(0xaf012000, 0xb16f8000, 4096)
08-16 11:25:29.400   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.400   320  7967 V AudioCache: memcpy(0xaf013000, 0xb16f8000, 4096)
08-16 11:25:29.400   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.400   320  7967 V AudioCache: memcpy(0xaf014000, 0xb16f8000, 4096)
08-16 11:25:29.402   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.402   320  7967 V AudioCache: memcpy(0xaf015000, 0xb16f8000, 4096)
08-16 11:25:29.402   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.402   320  7967 V AudioCache: memcpy(0xaf016000, 0xb16f8000, 4096)
08-16 11:25:29.403   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.403   320  7967 V AudioCache: memcpy(0xaf017000, 0xb16f8000, 4096)
08-16 11:25:29.403   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.403   320  7967 V AudioCache: memcpy(0xaf018000, 0xb16f8000, 4096)
08-16 11:25:29.404   320  7967 V AudioCache: write(0xb16f,8000, 4096)
08-16 11:25:29.404   320  7967 V AudioCache: memcpy(0xaf019000, 0xb16f8000, 4096)
08-16 11:25:29.405   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.405   320  7967 V AudioCache: memcpy(0xaf01a000, 0xb16f8000, 4096)
08-16 11:25:29.406   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.406   320  7967 V AudioCache: memcpy(0xaf01b000, 0xb16f8000, 4096)
08-16 11:25:29.407   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.407   320  7967 V AudioCache: memcpy(0xaf01c000, 0xb16f8000, 4096)
08-16 11:25:29.407   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.408   320  7967 V AudioCache: memcpy(0xaf01d000, 0xb16f8000, 4096)
08-16 11:25:29.408   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.408   320  7967 V AudioCache: memcpy(0xaf01e000, 0xb16f8000, 4096)
08-16 11:25:29.409   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.409   320  7967 V AudioCache: memcpy(0xaf01f000, 0xb16f8000, 4096)
08-16 11:25:29.410   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.410   320  7967 V AudioCache: memcpy(0xaf020000, 0xb16f8000, 4096)
08-16 11:25:29.411   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.411   320  7967 V AudioCache: memcpy(0xaf021000, 0xb16f8000, 4096)
08-16 11:25:29.411   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.412   320  7967 V AudioCache: memcpy(0xaf022000, 0xb16f8000, 4096)
08-16 11:25:29.412   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.412   320  7967 V AudioCache: memcpy(0xaf023000, 0xb16f8000, 4096)
08-16 11:25:29.413   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.413   320  7967 V AudioCache: memcpy(0xaf024000, 0xb16f8000, 4096)
08-16 11:25:29.414   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.414   320  7967 V AudioCache: memcpy(0xaf025000, 0xb16f8000, 4096)
08-16 11:25:29.415   320  7967 V AudioCache: write(0xb16f8000, 4096)
,08-16 11:25:29.415   320  7967 V AudioCache: memcpy(0xaf026000, 0xb16f8000, 4096)
,08-16 11:25:29.416   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.416   320  7967 V AudioCache: memcpy(0xaf027000, 0xb16f8000, 4096)
08-16 11:25:29.416   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.416   320  7967 V AudioCache: memcpy(0xaf028000, 0xb16f8000, 4096)
08-16 11:25:29.417   320  7967 V AudioCache: write(0xb16f8000, 4096)
,08-16 11:25:29.417   320  7967 V AudioCache: memcpy(0xaf029000, 0xb16f8000, 4096)
08-16 11:25:29.418   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.418   320  7967 V AudioCache: memcpy(0xaf02a000, 0xb16f8000, 4096)
08-16 11:25:29.419   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.419   320  7967 V AudioCache: memcpy(0xaf02b000, 0xb16f8000, 4096)
08-16 11:25:29.420   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.420   320  7967 V AudioCache: memcpy(0xaf02c000, 0xb16f8000, 4096)
08-16 11:25:29.420   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.420   320  7967 V AudioCache: memcpy(0xaf02d000, 0xb16f8000, 4096)
08-16 11:25:29.421   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.421   320  7967 V AudioCache: memcpy(0xaf02e000, 0xb16f8000, 4096)
08-16 11:25:29.422   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.422   320  7967 V AudioCache: memcpy(0xaf02f000, 0xb16f8000, 4096)
08-16 11:25:29.423   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.423   320  7967 V AudioCache: memcpy(0xaf030000, 0xb16f8000, 4096)
08-16 11:25:29.424   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.424   320  7967 V AudioCache: memcpy(0xaf031000, 0xb16f8000, 4096)
08-16 11:25:29.424   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.424   320  7967 V AudioCache: memcpy(0xaf032000, 0xb16f8000, 4096)
08-16 11:25:29.425   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.425   320  7967 V AudioCache: memcpy(0xaf033000, 0xb16f8000, 4096)
08-16 11:25:29.426  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 11:25:29.426   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.426   320  7967 V AudioCache: memcpy(0xaf034000, 0xb16f8000, 4096)
08-16 11:25:29.427  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 11:25:29.428   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.428   320  7967 V AudioCache: memcpy(0xaf035000, 0xb16f8000, 4096)
08-16 11:25:29.428   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.428   320  7967 V AudioCache: memcpy(0xaf036000, 0xb16f8000, 4096)
,08-16 11:25:29.429   320  7967 V AudioCache: write(0xb16f8000, 4096)
08-16 11:25:29.429   320  7967 V AudioCache: memcpy(0xaf037000, 0xb16f8000, 4096)
08-16 11:25:29.429   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 11:25:29.429   320  7967 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 11:25:29.429   320  7967 V AwesomePlayer: postAudioEOS() 
08-16 11:25:29.429   320  7967 V AudioCache: write(0xb16f8000, 280)
08-16 11:25:29.429   320  7967 V AudioCache: memcpy(0xaf038000, 0xb16f8000, 280)
08-16 11:25:29.431  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4775
08-16 11:25:29.432   320  7964 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 11:25:29.432   320  7964 V AwesomePlayer: onStreamDone
08-16 11:25:29.432   320  7964 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 11:25:29.432   320  7964 V AudioCache: notify(0xb5474500, 2, 0, 0)
08-16 11:25:29.432   320  7964 V AudioCache: playback complete
08-16 11:25:29.432   320  7964 V AwesomePlayer: pause_l() 
08-16 11:25:29.432   320  7964 V AudioCache: notify(0xb5474500, 7, 0, 0)
08-16 11:25:29.432   320  7964 V AudioCache: ignored
08-16 11:25:29.432   320  7964 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:29.432   320  1384 V AudioCache: wait - success
08-16 11:25:29.432   320  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 11:25:29.432   320  7964 D AudioPlayer: Pause Playback at 1068125
08-16 11:25:29.435   320  1384 V AwesomePlayer: reset_l() 
08-16 11:25:29.435   320  1384 V AudioCache: notify(0xb5474500, 8, 0, 0)
08-16 11:25:29.435   320  1384 V AudioCache: ignored
08-16 11:25:29.435   320  1384 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:29.435   320  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 11:25:29.435   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 11:25:29.435   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 11:25:29.435   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 11:25:29.435   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 0
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 11:25:29.435   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
,08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f9150 on port 1
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f92e0 on port 1
,08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f9740 on port 1
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 11:25:29.436   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 11:25:29.436   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 11:25:29.436   320  7966 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 11:25:29.436   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 11:25:29.436   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 11:25:29.436   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 11:25:29.437  7943  7943 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start,
08-16 11:25:29.438   320  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 11:25:29.438   320  1384 D AudioPlayer: AudioPlayer releasing audio source
,08-16 11:25:29.438   320  1384 D AudioPlayer: AudioPlayer done releasing audio source
08-16 11:25:29.438   320  1384 V AwesomePlayer: reset_l() 
08-16 11:25:29.438   320  1384 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:29.438   320  1384 V AwesomePlayer: ~AwesomePlayer call
08-16 11:25:29.438  7729  7747 I UEI.SmartControl: ------ IControl API: 11
08-16 11:25:29.438   320  1384 V AwesomePlayer: reset_l() 
08-16 11:25:29.438   320  1384 V AwesomePlayer: cancelPlayerEvents
08-16 11:25:29.439  7943  7963 V SoundPool: close(30)
08-16 11:25:29.439  7943  7963 V SoundPool: pointer = 0x9fe89000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 11:25:29.439  7729  7747 I UEI.SmartControl: Registering callback...
,08-16 11:25:29.444  7729  7746 I UEI.SmartControl: ------ IControl API: 19,
08-16 11:25:29.445  7729  7746 I UEI.SmartControl: Registering Services Ready callback...
08-16 11:25:29.445  7729  7746 I UEI.SmartControl: Notify client services are ready...
08-16 11:25:29.446  7943  7958 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 11:25:29.447  7943  7961 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,08-16 11:25:29.447  7943  7961 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 11:25:29.448  7943  7943 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 11:25:29.449  7943  7943 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 11:25:29.449  7729  7747 I UEI.SmartControl: ------ IControl API: 8
08-16 11:25:29.450  7943  7943 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-16 11:25:29.451  7943  7943 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 11:25:29.451  7943  7943 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 11:25:29.451  7943  7943 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 11:25:29.452  7943  7943 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,08-16 11:25:29.452  7943  7943 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 11:25:29.454  7943  7943 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 11:25:29.456  7943  7943 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 11:25:29.457  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 11:25:29.458  7943  7943 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 11:25:29.458  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 11:25:29.459  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 11:25:29.460  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 11:25:29.461  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 11:25:29.462  7943  7943 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471339529461]
08-16 11:25:29.464  7943  7943 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-16 11:25:29.467  1034  1883 I ActivityManager: Killing 7191:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-16 11:25:29.490  7943  7968 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 11:25:29.566  1034  1574 W libprocessgroup: failed to open /acct/uid_10046/pid_7191/cgroup.procs: No such file or directory
,08-16 11:25:29.580  7943  7943 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-16 11:25:29.582  7943  7943 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-16 11:25:29.584  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 11:25:29.585  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 11:25:29.586  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 11:25:29.587  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 11:25:29.588  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 11:25:29.616  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 11:25:30.087  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 11:25:30.087  1034  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1e378f49 mBinding = false
,08-16 11:25:30.119  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 11:25:30.119  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 11:25:30.119  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-16 11:25:30.122  1034  1110 D BluetoothManagerService: Message: 2
08-16 11:25:30.123  1034  1110 D BluetoothManagerService: Sending off request.
08-16 11:25:30.124  7058  7074 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 11:25:30.125  7058  7617 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 11:25:30.125  7058  7617 D BluetoothAdapterProperties: Setting state to 13
08-16 11:25:30.125  7058  7617 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 11:25:30.126  7058  7617 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 11:25:30.126  7058  7617 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 11:25:30.130  7058  7621 D BluetoothAdapterProperties: Scan Mode:20
08-16 11:25:30.131  7058  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 11:25:30.135  7058  7617 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 11:25:30.139  7058  7759 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 11:25:30.139  7058  7759 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:30.139  7058  7759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 11:25:30.139  7058  7759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 11:25:30.139  7058  7759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 11:25:30.139  7058  7759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 11:25:30.139  7058  7759 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 11:25:30.139  7058  7759 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 11:25:30.140  7058  7760 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:30.140  7058  7769 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:30.140  7058  7771 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:30.141  7058  7773 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:25:30.141  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 11:25:30.141  7058  7678 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 11:25:30.151  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 11:25:30.151  7058  7678 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-16 11:25:30.159  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:30.159  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:30.159  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:30.159  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:30.159  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:30.159  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:30.159  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:30.159  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:30.159  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:30.161  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:30.161  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:30.164  1034  1543 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-16 11:25:30.168  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:30.168  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:30.168  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:30.168  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:30.168  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:30.168  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:30.168  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:30.168  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:30.168  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:30.169  1034  1110 D BluetoothManagerService: Message: 60
08-16 11:25:30.169  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 11:25:30.169  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 11:25:30.170  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:30.170  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:30.173  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:30.173  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:30.173  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:30.173  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:30.173  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:30.173  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:25:30.173  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:30.173  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:30.173  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:30.173  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:25:30.174  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:30.176  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 11:25:30.180  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 11:25:30.184  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:30.186  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:30.188  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:30.194  7058  7058 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:30.194  7058  7058 D BluetoothMapService: STATE_TURNING_OFF
08-16 11:25:30.195  7058  7058 V BluetoothMapService: Handler(): got msg=4
08-16 11:25:30.195  7058  7058 D BluetoothMapService: MAP Service closeService in
08-16 11:25:30.195  7058  7058 D BluetoothMapMasInstance: MAP Service shutdown
08-16 11:25:30.195  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 11:25:30.195  7058  7058 V BluetoothMapService: MAP Service closeService out
,08-16 11:25:30.202  7058  7058 V BtOppService: Receiver DISABLED_ACTION 
08-16 11:25:30.202  7058  7058 I BtOppRfcommListener: stopping Accept Thread
08-16 11:25:30.203  7058  7058 V BtOppRfcommListener: close mBtServerSocket
08-16 11:25:30.205  7058  7769 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 11:25:30.205  7058  7058 V BtOppRfcommListener: waiting for thread to terminate
08-16 11:25:30.205  7058  7058 V BtOppRfcommListener: done waiting for thread to terminate
,08-16 11:25:30.216  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 11:25:30.219  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 11:25:30.222  7058  7058 V BtOppService: onDestroy
08-16 11:25:30.224  7058  7058 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 11:25:30.226  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 11:25:30.226  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:30.226  7058  7058 V BluetoothPbapReceiver: ***********state = 13
,08-16 11:25:30.231  7058  7058 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 11:25:30.234  7058  7058 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:30.234  7058  7058 V BluetoothPbapService: state: 13
08-16 11:25:30.234  7058  7058 V BluetoothPbapService: Pbap Service closeService in
08-16 11:25:30.237  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 11:25:30.238  7058  7058 V BluetoothPbapService: successfully stopped pbap service
08-16 11:25:30.238  7058  7058 V BluetoothPbapService: Pbap Service closeService out
,08-16 11:25:30.241  7058  7058 V BluetoothPbapService: Pbap Service onDestroy
08-16 11:25:30.241  7058  7058 V BluetoothPbapService: Pbap Service closeService in
08-16 11:25:30.241  7058  7058 V BluetoothPbapService: Pbap Service closeService out
08-16 11:25:30.241  7058  7058 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 11:25:30.265  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,08-16 11:25:30.266  6956  6956 D BluetoothPbap: Proxy object disconnected
08-16 11:25:30.266  6956  6956 D PbapServerProfile: Bluetooth service disconnected
08-16 11:25:30.276  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 11:25:30.281  6956  6956 D BluetoothPermissionRequest: onReceive
,08-16 11:25:30.281  6956  6956 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 11:25:30.287  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 11:25:30.290  7058  7058 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 11:25:30.290  7058  7058 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 11:25:30.291  7058  7058 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-16 11:25:30.295  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:30.295  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 11:25:30.296  7058  7058 V BluetoothFtpService: Ftp Service onStartCommand
08-16 11:25:30.296  7058  7058 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:30.297  7058  7058 V BluetoothFtpService: Ftp Service closeService
08-16 11:25:30.297  7058  7058 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 11:25:30.299  7058  7058 V BluetoothFtpService: successfully stopped ftp service
08-16 11:25:30.299  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 11:25:30.299  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 11:25:30.299  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 11:25:30.299  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:30.299  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 11:25:30.299  7058  7058 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 11:25:30.301  7058  7058 V BluetoothFtpService: Ftp Service onDestroy
08-16 11:25:30.301  7058  7058 V BluetoothFtpService: Ftp Service closeService
08-16 11:25:30.303  7058  7058 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:30.303  7058  7058 V BluetoothSapService: state: 13
08-16 11:25:30.303  7058  7058 V BluetoothSapService: Stopping SAP server process
,08-16 11:25:30.306  7058  7058 V BluetoothSapService: Sap Service closeSapService in
08-16 11:25:30.306  7058  7058 V BluetoothSapService: Close listen Socket : 
08-16 11:25:30.306  7058  7058 V BluetoothSapService: Close rfcomm Socket : 
08-16 11:25:30.307  7058  7058 V BluetoothSapService: Close sapd  Socket : 
08-16 11:25:30.308  7058  7058 V BluetoothSapService: Sap Service closeSapService out
08-16 11:25:30.308  7058  7058 V BluetoothSapService: Sap Service onDestroy
08-16 11:25:30.308  7058  7058 V BluetoothSapService: Sap Service closeSapService in
08-16 11:25:30.308  7058  7058 V BluetoothSapService: Close listen Socket : 
08-16 11:25:30.308  7058  7058 V BluetoothSapService: Close rfcomm Socket : 
08-16 11:25:30.308  7058  7058 V BluetoothSapService: Close sapd  Socket : 
08-16 11:25:30.309  7058  7058 V BluetoothSapService: Sap Service closeSapService out
08-16 11:25:31.135  7058  7621 D bt_hci_bdroid: cleanup
,08-16 11:25:31.139  7058  7680 I bt_lpm  : LPM is already off!!!
08-16 11:25:31.140  7058  7748 I bt_userial_mct: exiting userial_read_thread
08-16 11:25:31.140  7058  7748 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 11:25:31.140  7058  7678 W bt-btif : ag scb idx 1 not allocated
08-16 11:25:31.140  7058  7678 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 11:25:31.140  7058  7678 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 11:25:31.141  7058  7678 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 11:25:31.141  7058  7621 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 11:25:31.142  7058  7680 I bt_vendor: hw_epilog_process
08-16 11:25:31.142  7058  7621 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 11:25:31.142  7058  7621 D bt_userial_mct: userial_close
08-16 11:25:31.142  7058  7621 E bt_userial_mct: pthread_join() FAILED result:3
08-16 11:25:31.142  7058  7621 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 11:25:31.164  7058  7621 D bt_hci_bdroid: set_power 0
08-16 11:25:31.164  7058  7621 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 11:25:31.165  7058  7621 I bt_vendor: bluetooth satus is on
08-16 11:25:31.165  7058  7621 I bt_vendor: bt-vendor : resetting BT status
08-16 11:25:31.165  7058  7621 I bt_vendor: Starting hciattach daemon
,08-16 11:25:31.171  7058  7621 I bt_vendor: try to set false
08-16 11:25:31.173  7058  7621 I bt_vendor: Starting hciattach daemon
08-16 11:25:31.173  7058  7621 I bt_vendor: try to set false
08-16 11:25:31.174  7058  7621 I bt_vendor: cleanup
08-16 11:25:31.175  7058  7678 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 11:25:31.175  7058  7621 I GKI_LINUX: GKI_exit_task 0 done
08-16 11:25:31.175  7058  7621 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 11:25:31.177  7058  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 11:25:31.181  7058  7058 D HeadsetService: Received stop request...Stopping profile...
,08-16 11:25:31.185  7058  7058 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 11:25:31.186  7058  7058 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 11:25:31.186  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:31.188  7058  7654 D HeadsetStateMachine: Exit Disconnected: -1
08-16 11:25:31.191  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 11:25:31.191  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 11:25:31.191  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-16 11:25:31.192  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-16 11:25:31.192  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 11:25:31.195  7058  7058 D A2dpService: Received stop request...Stopping profile...
,08-16 11:25:31.198  7058  7664 D A2dpStateMachine: Exit Disconnected: -1
08-16 11:25:31.200  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 11:25:31.200  7058  7617 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 11:25:31.202  7058  7058 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 11:25:31.202  7058  7058 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 11:25:31.202  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:31.203  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-16 11:25:31.203  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 11:25:31.204  7058  7058 D HidService: Received stop request...Stopping profile...
08-16 11:25:31.205  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:31.207  7058  7058 D HealthService: Received stop request...Stopping profile...
08-16 11:25:31.207  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:31.210  7058  7058 D HeadsetStateMachine: Unbinding service...
,08-16 11:25:31.214  7058  7058 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 11:25:31.214  7058  7058 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 11:25:31.214  7058  7058 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 11:25:31.214  7058  7058 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 11:25:31.214  7058  7058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 11:25:31.214  7058  7058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 11:25:31.214  7058  7058 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 11:25:31.216  7058  7058 D PanService: Received stop request...Stopping profile...
08-16 11:25:31.216  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:31.217  7058  7058 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 11:25:31.218  7058  7058 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 11:25:31.218  7058  7058 D BtGatt.GattService: stop()
08-16 11:25:31.218  7058  7058 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 11:25:31.219  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:31.221  7058  7058 D BluetoothMapService: Received stop request...Stopping profile...
08-16 11:25:31.221  7058  7058 D BluetoothMapService: stop()
,08-16 11:25:31.224  7058  7058 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 11:25:31.225  7058  7058 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 11:25:31.225  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:31.226  7058  7058 I BluetoothA2dpServiceJni: cleanupNative
08-16 11:25:31.226  7058  7665 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 11:25:31.227  7058  7058 I GKI_LINUX: GKI_exit_task 2 done
08-16 11:25:31.227  7058  7058 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 11:25:31.227  7058  7058 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 11:25:31.227  7058  7058 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 11:25:31.228  7058  7058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 11:25:31.228  7058  7058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 11:25:31.228  7058  7058 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 11:25:31.228  7058  7058 V BluetoothMapService: Handler(): got msg=4
08-16 11:25:31.228  7058  7058 D BluetoothMapService: MAP Service closeService in
08-16 11:25:31.228  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 11:25:31.228  7058  7058 V BluetoothMapService: MAP Service closeService out
08-16 11:25:31.229  7058  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 11:25:31.229  7058  7617 D BluetoothAdapterProperties: Setting state to 10
08-16 11:25:31.229  7058  7617 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 11:25:31.232  1034  1110 D BluetoothManagerService: Message: 60
08-16 11:25:31.232  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 11:25:31.232  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 11:25:31.235  7058  7058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 11:25:31.235  7058  7058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 11:25:31.239  7058  7058 D BluetoothMapService: cleanup()
08-16 11:25:31.239  7058  7058 D BluetoothMapService: MAP Service closeService in
08-16 11:25:31.239  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 11:25:31.239  7058  7058 V BluetoothMapService: MAP Service closeService out
08-16 11:25:31.240  1851  2375 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:25:31.241  7058  7617 I BluetoothAdapterState: Entering OffState
08-16 11:25:31.241  1034  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 11:25:31.241  6956  6976 D BluetoothPan: onBluetoothStateChange on: false
08-16 11:25:31.242  6956  6976 D BluetoothMap: onBluetoothStateChange: up=false
08-16 11:25:31.243  6956  6976 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:25:31.245  6956  6976 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 11:25:31.246  1851  2668 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:25:31.246  6956  6976 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 11:25:31.249  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:25:31.249  6956  6976 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 11:25:31.250  1034  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:25:31.250  1034  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 11:25:31.250  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 11:25:31.253  1034  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 11:25:31.253  1034  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 11:25:31.253  1034  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1e378f49 mBinding = false
08-16 11:25:31.254  1034  1110 D BluetoothManagerService: Sending unbind request.
08-16 11:25:31.259  7058  7621 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 11:25:31.261  7058  7058 I GKI_LINUX: GKI_exit_task 1 done
08-16 11:25:31.261  7058  7058 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 11:25:31.262  7058  7058 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 11:25:31.263  7058  7058 I art     : --- WEIRD: removing null entry 248
08-16 11:25:31.263  7058  7058 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 11:25:31.263  7058  7058 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 11:25:31.264  7058  7058 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 11:25:31.265  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 11:25:31.267  7058  7058 I art     : System.exit called, status: 0
08-16 11:25:31.267  7058  7058 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 11:25:31.288  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 11:25:31.289  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:31.289  1940  2124 D LGBluetoothAPIService: Message: 2
08-16 11:25:31.289  1940  2124 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@b084903 mBinding = false
08-16 11:25:31.289  1940  2124 D LGBluetoothAPIService: Sending unbind request.
08-16 11:25:31.296  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 11:25:31.296  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:31.297  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:31.297  1601  1601 D BluetoothAdapter: 185590748: getState() :  mService = null. Returning STATE_OFF
08-16 11:25:31.297  1601  1601 D BluetoothAdapter: 185590748: getState() :  mService = null. Returning STATE_OFF
,08-16 11:25:31.300  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 11:25:31.300   320  1383 V AudioFlinger: 7058 died, releasing its sessions
08-16 11:25:31.300  6956  6956 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 11:25:31.300   320  1383 V AudioFlinger:  pid 1851 @ 0
08-16 11:25:31.300   320  1383 V AudioFlinger:  pid 3483 @ 1
08-16 11:25:31.300   320  1383 V AudioFlinger:  pid 3483 @ 2
08-16 11:25:31.300  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-16 11:25:31.304  1034  1050 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
08-16 11:25:31.304  1034  1050 W ActivityManager: android.os.DeadObjectException
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-16 11:25:31.304  1034  1050 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 11:25:31.305  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 11:25:31.386  1034  2031 I ActivityManager: Process com.android.bluetooth (pid 7058) has died
08-16 11:25:31.386  1034  2031 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-16 11:25:31.480  1034  1987 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8039 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 11:25:31.482  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,08-16 11:25:31.556  8039  8039 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 11:25:31.557  8039  8039 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 11:25:31.557  8039  8039 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-16 11:25:31.558  8039  8039 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 11:25:31.578  8039  8039 D BluetoothAdapterApp: Loading JNI Library
,08-16 11:25:31.616  8039  8039 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@a5a7b8a Instance Count = 1
,08-16 11:25:31.622  8039  8039 D BluetoothAdapterApp: onCreate
,08-16 11:25:31.650  8039  8039 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 11:25:31.650  8039  8039 D ProfileConfigQcom: Adding HeadsetService
08-16 11:25:31.650  8039  8039 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 11:25:31.650  8039  8039 D ProfileConfigQcom: Adding A2dpService
,08-16 11:25:31.651  8039  8039 D ProfileConfigQcom: [BTUI] HidService is supported
,08-16 11:25:31.651  8039  8039 D ProfileConfigQcom: Adding HidService
,08-16 11:25:31.651  8039  8039 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 11:25:31.651  8039  8039 D ProfileConfigQcom: Adding HealthService
,08-16 11:25:31.652  8039  8039 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-16 11:25:31.653  8039  8039 D ProfileConfigQcom: [BTUI] PanService is supported
,08-16 11:25:31.653  8039  8039 D ProfileConfigQcom: Adding PanService
08-16 11:25:31.653  8039  8039 D ProfileConfigQcom: [BTUI] GattService is supported,
08-16 11:25:31.653  8039  8039 D ProfileConfigQcom: Adding GattService
,08-16 11:25:31.654  8039  8039 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 11:25:31.654  8039  8039 D ProfileConfigQcom: Adding BluetoothMapService
,08-16 11:25:31.654  8039  8039 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 11:25:31.655  8039  8039 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 11:25:31.656  8039  8039 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:31.657  8039  8039 V BluetoothPbapReceiver: ***********state = 10
,08-16 11:25:31.659  8039  8039 V LGMDMManagerInternal: Create singleton instance,
,08-16 11:25:31.760  6956  6956 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 11:25:31.760  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 11:25:31.764  1034  1051 I ActivityManager: Killing 7221:com.android.chrome/u0a57 (adj 15): empty #17
08-16 11:25:31.821  1034  1918 W libprocessgroup: failed to open /acct/uid_10057/pid_7221/cgroup.procs: No such file or directory
,08-16 11:25:31.852  6956  6956 D BluetoothPermissionRequest: onReceive
,08-16 11:25:31.857  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 11:25:31.857  6956  6956 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 11:25:31.860  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 11:25:31.866  8039  8039 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-16 11:25:31.872  8039  8039 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:31.876  8039  8039 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 11:25:31.876  8039  8039 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 11:25:31.877  8039  8039 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 11:25:31.878  8039  8039 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:31.878  8039  8039 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 11:25:31.894  7684  7684 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 11:25:31.913  7729  7784 D UEI.SmartControl: Internal timer expired: 1
08-16 11:25:31.913  7729  7784 D UEI.SmartControl: unbind internal service
,08-16 11:25:32.198  7729  7778 D serial_port: close(fd = 25)
,08-16 11:25:32.204  7729  7778 I UEI.SmartControl: Serial port is closed.
,08-16 11:25:35.219  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 11:25:35.220  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:25:38.893  1034  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{82b127c type 2 when 398525 com.google.android.gms} when 398525
,08-16 11:25:38.905  7943  7943 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 11:25:38.905  7943  7943 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4775
08-16 11:25:38.910   315  8068 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 11:25:38.914  1034  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 11:25:40.233  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:25:40.240  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@115f6db9 removed from the list
08-16 11:25:40.240  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:25:40.242  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:25:40.242  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:25:40.246  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:25:40.246  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d13615f added. We now have 4 listener(s)
08-16 11:25:40.246  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:25:40.247  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:25:40.247  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d13615f removed from the list
08-16 11:25:40.247  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:25:40.247  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:25:40.248  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:25:40.248  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:25:40.248  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@176597ac added. We now have 4 listener(s)
08-16 11:25:40.248  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:25:40.250  1034  1894 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:40.250  1034  1894 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-16 11:25:40.253  1034  1110 D BluetoothManagerService: Message: 2
,08-16 11:25:42.256  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:25:42.265  1034  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:42.265  1034  1883 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-16 11:25:42.285  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 11:25:42.286  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 11:25:42.286  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-16 11:25:42.289  1034  1110 D BluetoothManagerService: Message: 1
08-16 11:25:42.289  1034  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 11:25:42.316  1034  1110 D BluetoothManagerService: Message: 20
08-16 11:25:42.317  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@111cde81:true
,08-16 11:25:42.320  8039  8039 D BluetoothAdapterState: make
08-16 11:25:42.325  8039  8039 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 11:25:42.325  8039  8039 I bluedroid-qcom: init
08-16 11:25:42.327  8039  8070 I BluetoothAdapterState: Entering OffState
08-16 11:25:42.327  8039  8039 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 11:25:42.327  8039  8039 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 11:25:42.327  8039  8039 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 11:25:42.327  8039  8039 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 11:25:42.327  8039  8039 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 11:25:42.329  8039  8039 I bluedroid-qcom: get_profile_interface socket
08-16 11:25:42.329  8039  8039 I bluedroid-qcom: get_profile_interface map_client
,08-16 11:25:42.335  8039  8074 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 11:25:42.337  8039  8074 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 11:25:42.325  8073  8073 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:42.325  8073  8073 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:42.346  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 11:25:42.347  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 11:25:42.355  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 11:25:42.355  1034  1110 D BluetoothManagerService: Message: 40
08-16 11:25:42.355  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 11:25:42.356  8039  8054 I bluedroid-qcom: config_hci_snoop_log
08-16 11:25:42.357  1034  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 11:25:42.357  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 11:25:42.358  8073  8073 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 11:25:42.358  8073  8073 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 11:25:42.358  8073  8073 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 11:25:42.360  8039  8074 D BluetoothAdapterProperties: Name is: G3
,08-16 11:25:42.362  8073  8073 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 11:25:42.367  8073  8073 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 11:25:42.367  8073  8073 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 11:25:42.371  8039  8070 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 11:25:42.371  8039  8070 D BluetoothAdapterProperties: Setting state to 11
08-16 11:25:42.371  8039  8070 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 11:25:42.373  1034  1110 D BluetoothManagerService: Message: 60
,08-16 11:25:42.373  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 11:25:42.375  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-16 11:25:42.377  8039  8070 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 11:25:42.383  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 11:25:42.388  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 11:25:42.390  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:42.391  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:42.394  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 11:25:42.401  8039  8039 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 11:25:42.401  8039  8039 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:42.401  8039  8039 V BluetoothPbapReceiver: ***********state = 11
,08-16 11:25:42.408  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 11:25:42.429  8039  8070 D BluetoothBondStateMachine: make
,08-16 11:25:42.438  8039  8070 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
,08-16 11:25:42.438  8039  8070 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 11:25:42.438  8039  8070 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:42.438  8039  8070 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 11:25:42.440  8039  8070 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 11:25:42.441  8039  8087 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 11:25:42.448  6956  6956 D BluetoothPermissionRequest: onReceive
08-16 11:25:42.462  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 11:25:42.469  8039  8039 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:42.471  8039  8039 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 11:25:42.471  8039  8039 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 11:25:42.471  8039  8039 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 11:25:42.471  8039  8039 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:42.471  8039  8039 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 11:25:42.585  1034  1894 I art     : Explicit concurrent mark sweep GC freed 28134(1345KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.823ms total 141.752ms
,08-16 11:25:42.591  8039  8070 E BluetoothAdapterService: File transfer profiles supported!!
08-16 11:25:42.600  8039  8070 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 11:25:42.605  8039  8070 E BluetoothAdapterService: File transfer profiles supported!!
08-16 11:25:42.609  8039  8039 D HeadsetService: Received start request. Starting profile...
08-16 11:25:42.610  8039  8039 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 11:25:42.611  8039  8039 D LGBluetoothHfpAdapter: Version 1.6
,08-16 11:25:42.615  8039  8070 E BluetoothAdapterService: File transfer profiles supported!!
08-16 11:25:42.618  8039  8039 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 11:25:42.620  8039  8039 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 11:25:42.621  8039  8039 D HeadsetStateMachine: make
,08-16 11:25:42.627  8039  8070 E BluetoothAdapterService: File transfer profiles supported!!
08-16 11:25:42.638  8039  8070 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 11:25:42.645  8039  8070 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 11:25:42.659  8039  8039 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:42.659  8039  8039 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:42.664  8039  8039 D HeadsetStateMachine: max_hf_connections = 1
08-16 11:25:42.664  8039  8039 I bluedroid-qcom: get_profile_interface handsfree
08-16 11:25:42.666  8039  8070 V LGMDMManager: Create singleton instance
08-16 11:25:42.666  8039  8039 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 11:25:42.667   320  2150 V AudioPolicyService: registerClient() client 0xb558ae00, uid 1002
08-16 11:25:42.667   320   320 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,08-16 11:25:42.667   320   320 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 11:25:42.667   320   320 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 11:25:42.668  8039  8039 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 11:25:42.668   320  1383 V AudioFlinger: registerClient() client 0xb55817f0, pid 8039
08-16 11:25:42.668   320  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:42.668   320  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:42.669  8039  8039 V ToneGenerator: Create Track: 0xb4928080
08-16 11:25:42.669  8039  8039 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 11:25:42.669  8039  8039 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 11:25:42.669  1601  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:42.669  1601  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:42.669  1851  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:42.669  1851  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:42.669  3483  3499 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:42.669  3483  3499 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:42.669  1034  1960 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:42.669  1034  1960 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 11:25:42.669   320  2151 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 11:25:42.670   320  2151 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 11:25:42.670   320  2151 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 11:25:42.670   320  2151 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 11:25:42.670  8039  8055 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 11:25:42.670  8039  8055 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 11:25:42.670  8039  8039 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 11:25:42.670   320  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:42.670   320  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 11:25:42.670  1034  1649 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:42.670  1034  1649 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 11:25:42.670   320  2151 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 11:25:42.670  1601  2078 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:42.670  1601  2078 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 11:25:42.671  1851  1866 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:42.671  1851  1866 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 11:25:42.671   320   320 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 11:25:42.671   320   320 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 11:25:42.671   320   320 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 11:25:42.671   320   320 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 11:25:42.671  8039  8055 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:42.671  8039  8055 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 11:25:42.671  3483  3498 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 11:25:42.671  3483  3498 V AudioSystem: ioConfigChan,ged() opening already existing output! 2
08-16 11:25:42.671  8039  8039 V AudioSystem: getLatency() output 2, latency 50
08-16 11:25:42.671  8039  8039 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 11:25:42.671  8039  8039 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 11:25:42.671   320  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 11:25:42.671   320  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 11:25:42.671   320  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 11:25:42.671   320  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 11:25:42.671   320  1384 V AudioFlinger: createTrack() lSessionId: 23
08-16 11:25:42.671  8039  8070 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 11:25:42.672  8039  8039 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 11:25:42.673   320  1384 V AudioFlinger: acquiring 23 from 8039, for 8039
08-16 11:25:42.673   320  1384 V AudioFlinger:  added new entry for 23
08-16 11:25:42.674  8039  8039 V ToneGenerator: ToneGenerator INIT OK, time: 402330
08-16 11:25:42.674  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:42.675  8039  8093 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 11:25:42.676  8039  8093 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 11:25:42.676  8039  8093 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 11:25:42.676  8039  8093 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-16 11:25:42.676   320  2150 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 8039
08-16 11:25:42.677   320  2150 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 11:25:42.677   320  2150 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 11:25:42.677   320  2150 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 11:25:42.677   320  2150 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 11:25:42.677   320  2150 V voice   : voice_set_parameters: exit with code(0)
08-16 11:25:42.677   320  2150 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 11:25:42.677   320  2150 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 11:25:42.677   320  2150 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 11:25:42.677   320  2150 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 11:25:42.677   320  2150 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 11:25:42.677   320  2150 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 11:25:42.677  8039  8093 V ToneGenerator: ToneGenerator destructor
08-16 11:25:42.677  8039  8093 V ToneGenerator: stopTone
08-16 11:25:42.677  8039  8093 V ToneGenerator: Delete Track: 0xb4928080
08-16 11:25:42.678  8039  8093 V AudioTrack: ~AudioTrack, releasing session id from 8039 on behalf of 8039
08-16 11:25:42.679   320  1383 V AudioFlinger: releasing 23 from 8039 for 8039
08-16 11:25:42.679   320  1383 V AudioFlinger:  decremented refcount to 0
08-16 11:25:42.679   320  1383 V AudioFlinger: purging stale effects
08-16 11:25:42.679   320  1383 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 11:25:42.679   320  1383 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 11:25:42.679   320  1258 V AudioPolicyService: AudioCommandThread() waking up
08-16 11:25:42.679   320  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 11:25:42.679   320  1258 V AudioPolicyManager: releaseOutput() 2
08-16 11:25:42.679   320  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 11:25:42.679   320  1383 V AudioFlinger: PlaybackThread::Track destructor
08-16 11:25:42.679   320  1383 V AudioFlinger: removeClient_l() pid 8039, calling pid 320
08-16 11:25:42.679  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:42.681  1034  1925 W Process : Unable to open /proc/8094/status
08-16 11:25:42.681  8039  8039 D A2dpService: Received start request. Starting profile...
08-16 11:25:42.682  8039  8039 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 11:25:42.684  8039  8039 V Avrcp   : make
08-16 11:25:42.684  8039  8039 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 11:25:42.685  8039  8039 I bluedroid-qcom: get_profile_interface avrcp
08-16 11:25:42.699  8039  8039 V AudioManager: registerRemoteController: size of Media player list: 0
,08-16 11:25:42.701  8039  8039 E AudioManager: No RCC entry present to update
08-16 11:25:42.701  8039  8039 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 11:25:42.705  8039  8039 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 11:25:42.707  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 11:25:42.707  8039  8039 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 11:25:42.712  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 11:25:42.838  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-16 11:25:42.838  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-16 11:25:42.911  1034  1883 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 11:25:42.929  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-16 11:25:42.936  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 11:25:42.936  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 11:25:42.936  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 11:25:42.937  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 11:25:42.937  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 11:25:42.937  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 11:25:42.937  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 11:25:42.937  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 11:25:42.937  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 11:25:42.937  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 11:25:42.938  8039  8039 I BluetoothA2dpServiceJni: classInitNative
08-16 11:25:42.938  8039  8039 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 11:25:42.938  8039  8039 D A2dpStateMachine: make
08-16 11:25:42.941  8039  8039 I bluedroid-qcom: get_profile_interface a2dp
08-16 11:25:42.942  8039  8099 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 11:25:42.945  8039  8039 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 11:25:42.946  8039  8039 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 11:25:42.947  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:42.947  8039  8098 D A2dpStateMachine: Enter Disconnected: -2
08-16 11:25:42.949  8039  8039 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 11:25:42.951  8039  8039 D HidService: Received start request. Starting profile...
08-16 11:25:42.951  8039  8039 I bluedroid-qcom: get_profile_interface hidhost
08-16 11:25:42.952  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:42.952  8039  8039 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 11:25:42.954  8039  8039 D HealthService: Received start request. Starting profile...
08-16 11:25:42.958  8039  8039 I bluedroid-qcom: get_profile_interface health
08-16 11:25:42.958  8039  8039 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 11:25:42.958  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:42.960  8039  8039 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 11:25:42.962  8039  8039 D PanService: Received start request. Starting profile...
08-16 11:25:42.962  8039  8039 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 11:25:42.962  8039  8039 I bluedroid-qcom: get_profile_interface pan
08-16 11:25:42.975  8039  8039 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 11:25:42.975  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:42.977  8039  8039 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-16 11:25:42.984  8039  8039 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 11:25:42.985  8039  8039 D BtGatt.GattService: Received start request. Starting profile...
08-16 11:25:42.985  8039  8039 D BtGatt.GattService: start()
08-16 11:25:42.985  8039  8039 I bluedroid-qcom: get_profile_interface gatt
08-16 11:25:42.985  8039  8039 D BtGatt.AdvertiseManager: advertise manager created
08-16 11:25:42.996  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
,08-16 11:25:42.998  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
,08-16 11:25:42.998  8039  8039 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 11:25:42.999  8039  8039 V BluetoothMapService: BluetoothMapBinder()
08-16 11:25:43.000  8039  8039 D BluetoothMapService: Received start request. Starting profile...
08-16 11:25:43.000  8039  8039 D BluetoothMapService: start()
08-16 11:25:43.004  8039  8039 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 11:25:43.004  8039  8039 D BluetoothMapEmailAppObserver: createReceiver()
08-16 11:25:43.006  8039  8039 D BluetoothMapEmailAppObserver: initObservers()
08-16 11:25:43.006  8039  8039 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 11:25:43.015  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:43.015  8039  8039 D HeadsetStateMachine: Proxy object connected
08-16 11:25:43.016  8039  8039 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 11:25:43.016  8039  8039 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-16 11:25:43.021  8039  8093 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 11:25:43.022  8039  8093 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 11:25:43.022  8039  8093 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 11:25:43.030  8039  8039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 11:25:43.034  8039  8039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 11:25:43.038  8039  8039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 11:25:43.042  8039  8039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 11:25:43.046  8039  8039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 11:25:43.046  8039  8039 V PanService: [BTUI] SIM Extra State :ABSENT
,08-16 11:25:43.054  8039  8039 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 11:25:43.055  8039  8039 V BluetoothMapService: Handler(): got msg=1
08-16 11:25:43.057  8039  8070 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 11:25:43.057  8039  8070 I bluedroid-qcom: enable
08-16 11:25:43.058  8039  8112 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 11:25:43.058  8039  8070 I bt_hci_bdroid: init
08-16 11:25:43.060  8039  8070 I bt_vendor: bt-vendor : init
08-16 11:25:43.060  8039  8070 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 11:25:43.060  8039  8070 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 11:25:43.060  8039  8070 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 11:25:43.060  8039  8070 D bt_userial_mct: userial_init
,08-16 11:25:43.061  8039  8070 D bt_hci_bdroid: set_power 1
08-16 11:25:43.061  8039  8070 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 11:25:43.061  8039  8070 I bt_vendor: Starting hciattach daemon
08-16 11:25:43.061  8039  8070 I bt_vendor: try to set true
08-16 11:25:43.064  8039  8112 I bt-btu  : btu_task pending for preload complete event
08-16 11:25:43.055  8115  8115 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:43.055  8115  8115 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:43.088  8116  8116 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 11:25:43.163  8122  8122 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 11:25:43.176  8123  8123 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 11:25:43.202  8125  8125 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 11:25:43.226  8126  8126 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 11:25:43.238  8127  8127 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 11:25:43.251  8128  8128 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 11:25:43.283  8130  8130 I libmdmdetect: ESOC framework not supported
,08-16 11:25:43.286  8130  8130 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-16 11:25:43.298  8130  8130 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 11:25:43.298  8130  8130 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 11:25:43.298  8130  8130 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 11:25:43.298  8130  8130 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 11:25:43.298  8130  8130 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 11:25:43.298  8130  8130 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 11:25:43.299  8130  8130 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-16 11:25:43.348  8130  8131 E QC-QMI  : qmi_client [8130] 15: failed to locate client data
08-16 11:25:43.349   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 11:25:43.350   481   481 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 11:25:43.410  8132  8132 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 11:25:43.439  8133  8133 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 11:25:43.465  8039  8070 I bt_vendor: bluetooth satus is on
08-16 11:25:43.465  8039  8070 D bt_hci_bdroid: preload
,08-16 11:25:43.467  8039  8114 D bt_userial_mct: userial_open(port:0)
08-16 11:25:43.467  8039  8114 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 11:25:43.471  8039  8114 I bt_vendor: Done intiailizing UART
08-16 11:25:43.472  8039  8114 I bt_vendor: Done intiailizing UART
08-16 11:25:43.472  8039  8114 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 11:25:43.472  8039  8114 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 11:25:43.473  8039  8112 I bt-btu  : btu_task received preload complete event
08-16 11:25:43.473  8039  8112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 11:25:43.474  8039  8112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 11:25:43.476  8039  8112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 11:25:43.478  8039  8138 D bt_userial_mct: Entering userial_read_thread()
,08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 11:25:43.484  8039  8112 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 11:25:43.485  8039  8112 I         : BTE_InitTraceLevels -- TRC_BTIF,
08-16 11:25:43.570  8039  8112 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-16 11:25:43.570  8039  8112 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a2061 ,
08-16 11:25:43.570  8039  8112 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a2061 
,08-16 11:25:43.619  8039  8074 E bt-btif : Calling BTA_HhEnable
08-16 11:25:43.619  8039  8074 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 11:25:43.619  8039  8074 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 11:25:43.624  8039  8112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 11:25:43.625  8039  8112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 11:25:43.626  8039  8112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 11:25:43.626  8039  8112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 11:25:43.626  8039  8112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 11:25:43.628  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 11:25:43.629  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 11:25:43.630  8039  8074 D BluetoothAdapterProperties: Name is: G3
08-16 11:25:43.633  8039  8074 D BluetoothAdapterProperties: Scan Mode:20
08-16 11:25:43.636  8039  8074 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 11:25:43.636  8039  8074 D bt_hci_bdroid: postload
,08-16 11:25:43.640  8039  8114 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:43.642  8039  8114 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:43.643  8039  8112 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 11:25:43.644  8039  8074 D bte_conf: Device ID record 1 : primary
08-16 11:25:43.644  8039  8074 D bte_conf:   vendorId            = 00c4
08-16 11:25:43.644  8039  8074 D bte_conf:   vendorIdSource      = 0001
08-16 11:25:43.644  8039  8074 D bte_conf:   product             = 13a1
08-16 11:25:43.644  8039  8074 D bte_conf:   version             = 1000
08-16 11:25:43.644  8039  8074 D bte_conf:   clientExecutableURL = 
08-16 11:25:43.644  8039  8074 D bte_conf:   serviceDescription  = 
08-16 11:25:43.644  8039  8074 D bte_conf:   documentationURL    = 
08-16 11:25:43.644  8039  8074 D bte_conf: bte_load_did_conf no section named DID2.
08-16 11:25:43.647  8039  8114 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:43.650  8039  8070 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 11:25:43.650  8039  8070 D BluetoothAdapterProperties: ScanMode =  20
08-16 11:25:43.650  8039  8070 D BluetoothAdapterProperties: State =  11
08-16 11:25:43.651  8039  8070 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 11:25:43.651  8039  8070 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 11:25:43.651  8039  8070 D BluetoothAdapterProperties: Setting state to 12
08-16 11:25:43.651  8039  8070 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 11:25:43.654  8039  8074 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 11:25:43.655  8039  8074 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 11:25:43.645  8140  8140 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:43.645  8140  8140 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:43.664  1034  1110 D BluetoothManagerService: Message: 60
08-16 11:25:43.664  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 11:25:43.664  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-16 11:25:43.667  8039  8112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:43.667  8039  8112 W bt-smp  : Plain text(LSB ~ MSB) = fc ce 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:43.667  8039  8112 W bt-smp  : Encrypted text(LSB ~ MSB) = c5 91 fe c4 52 f3 86 b5 60 be 3d 2a ca 36 99 81 
08-16 11:25:43.667  8039  8114 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 11:25:43.667  8039  8112 W bt-btm  : Stopping oneshot timer
08-16 11:25:43.668  8039  8138 E bt_mct  : hci lib postload completed
08-16 11:25:43.694  8039  8112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:43.694  8039  8112 W bt-smp  : Plain text(LSB ~ MSB) = be 4b 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:43.694  8039  8112 W bt-smp  : Encrypted text(LSB ~ MSB) = cd 26 16 ad 21 09 b3 74 05 45 2e 97 54 c3 b1 a9 
,08-16 11:25:43.697  8039  8112 W bt-btm  : Stopping oneshot timer
08-16 11:25:43.698  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:43.698  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:43.698  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:43.698  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:43.698  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:43.698  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:43.698  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:43.698  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:43.700  8039  8070 I BluetoothAdapterState: Entering On State
08-16 11:25:43.701  1851  2668 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:25:43.705  8039  8074 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 11:25:43.705  8039  8074 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 11:25:43.709  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:25:43.720  8039  8112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:43.720  8039  8112 W bt-smp  : Plain text(LSB ~ MSB) = bd f9 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:43.720  8039  8112 W bt-smp  : Encrypted text(LSB ~ MSB) = 34 71 2a 8c 95 87 e8 9b 54 bf 85 2a fc 7b 1b d4 
08-16 11:25:43.720  8039  8112 W bt-btm  : Stopping oneshot timer
08-16 11:25:43.727  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:43.727  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:43.727  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:43.727  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:43.727  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:43.727  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:43.727  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:43.727  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:25:43.733  8039  8112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:43.733  8039  8112 W bt-smp  : Plain text(LSB ~ MSB) = 91 82 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:43.733  8039  8112 W bt-smp  : Encrypted text(LSB ~ MSB) = 8b 72 fd f8 c0 1d 6c 5c b8 e7 cd 95 5e 44 00 88 
08-16 11:25:43.734  8039  8112 W bt-btm  : Stopping oneshot timer
08-16 11:25:43.736  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:43.750  8039  8070 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 11:25:43.750  8039  8070 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 11:25:43.750  8039  8070 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 11:25:43.754  8039  8070 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 11:25:43.755  8039  8070 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 11:25:43.764  1851  1851 D BluetoothHeadset: Proxy object connected
,08-16 11:25:43.767  1034  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 11:25:43.773  1034  1034 D BluetoothA2dp: Proxy object connected
,08-16 11:25:43.775  8039  8112 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 11:25:43.775  8039  8112 W bt-smp  : Plain text(LSB ~ MSB) = eb b0 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 11:25:43.775  8039  8112 W bt-smp  : Encrypted text(LSB ~ MSB) = 9f 4e aa 01 29 6e 60 15 b2 fb 5d 19 34 3a e5 49 
08-16 11:25:43.775  8039  8112 W bt-btm  : Stopping oneshot timer
08-16 11:25:43.787  6956  6975 D BluetoothPan: onBluetoothStateChange on: true
08-16 11:25:43.787  6956  6975 D BluetoothPan: onBluetoothStateChange call bindService
,08-16 11:25:43.801  8145  8145 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 11:25:43.805  6956  6956 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 11:25:43.805  6956  6956 D PanProfile: Bluetooth service connected
08-16 11:25:43.805  6956  6976 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 11:25:43.810  6956  7381 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:25:43.810  6956  6956 D BluetoothMap: Proxy object connected
08-16 11:25:43.810  6956  6956 D MapProfile: Bluetooth service connected
08-16 11:25:43.811  6956  6956 D BluetoothMap: getConnectedDevices()
08-16 11:25:43.812  8039  8054 V BluetoothMapService: getConnectedDevices()
08-16 11:25:43.813  6956  6975 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 11:25:43.814  6956  6956 D BluetoothHeadset: Proxy object connected
08-16 11:25:43.814  6956  6956 D HeadsetProfile: Bluetooth service connected
08-16 11:25:43.816  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:25:43.818  1851  1851 D BluetoothHeadset: Proxy object connected
,08-16 11:25:43.820  6956  6976 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 11:25:43.822  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:25:43.823  6956  6956 D BluetoothA2dp: Proxy object connected
08-16 11:25:43.823  6956  6956 D A2dpProfile: Bluetooth service connected
08-16 11:25:43.824  1851  1851 D BluetoothHeadset: Proxy object connected
08-16 11:25:43.825  6956  6975 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 11:25:43.827  1034  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:25:43.828  1034  1034 D BluetoothHeadset: Proxy object connected
08-16 11:25:43.829  1034  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 11:25:43.829  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 11:25:43.830  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:43.830  1940  2124 D LGBluetoothAPIService: Message: 1
08-16 11:25:43.830  1940  2124 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-16 11:25:43.832  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 11:25:43.836  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:43.837  6956  6956 D BluetoothInputDevice: Proxy object connected
08-16 11:25:43.837  6956  6956 D HidProfile: Bluetooth service connected
08-16 11:25:43.838  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:43.839  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 11:25:43.840  1034  1110 D BluetoothManagerService: Message: 40
08-16 11:25:43.840  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 11:25:43.840  1940  2124 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 11:25:43.843  8039  8039 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:43.843  8039  8039 D BluetoothMapService: STATE_ON
,08-16 11:25:43.845  8039  8039 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 11:25:43.845  8039  8039 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 11:25:43.846  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 11:25:43.846  1940  2124 D LGBluetoothAPIService: Message: 100
08-16 11:25:43.846  1940  2124 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 11:25:43.848  6956  6956 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 11:25:43.849  6956  6956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 11:25:43.858  6956  6956 D DockEventReceiver: finishStartingService: stopping service
,08-16 11:25:43.862  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:43.863  8039  8039 V BluetoothPbapService: Pbap Service onCreate
08-16 11:25:43.863  8039  8039 V BluetoothPbapService: Starting PBAP service
08-16 11:25:43.864  8039  8039 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 11:25:43.864  8039  8039 V BluetoothPbapService: Pbap Service onBind
08-16 11:25:43.865  8039  8039 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:43.865  8039  8039 V BluetoothPbapService: state: 12
08-16 11:25:43.865  8039  8039 V BluetoothMapService: Handler(): got msg=1
08-16 11:25:43.866  8039  8039 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 11:25:43.867  8039  8039 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 11:25:43.867  8039  8039 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:43.867  8039  8039 V BluetoothPbapReceiver: ***********state = 12
08-16 11:25:43.867  6956  6956 D BluetoothPbap: Proxy object connected
08-16 11:25:43.867  6956  6956 D PbapServerProfile: Bluetooth service connected
08-16 11:25:43.868  8039  8165 D BluetoothMapMasInstance: MAS initSocket()
08-16 11:25:43.868  8039  8039 V BluetoothPbapService: Handler(): got msg=1
08-16 11:25:43.869  8039  8165 D BluetoothMapMasInstance:   masId = 00
08-16 11:25:43.869  8039  8165 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 11:25:43.869  8039  8165 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 11:25:43.869  8039  8165 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 11:25:43.870  8039  8039 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-16 11:25:43.870  1034  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:43.871  2211  2211 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 11:25:43.871  2211  2211 D c       : Getting all permits...
08-16 11:25:43.871  2211  2211 D a       : Opening database...
08-16 11:25:43.875  8039  8166 V BluetoothPbapService: Pbap Service initSocket
08-16 11:25:43.875  8039  8165 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 11:25:43.875  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:43.876  8039  8165 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 11:25:43.877  8039  8165 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 11:25:43.877  8039  8165 D BluetoothMapMasInstance: Accepting socket connection...
08-16 11:25:43.877  8039  8074 D BluetoothAdapterProperties: Scan Mode:21
08-16 11:25:43.877  8039  8074 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 11:25:43.878  8039  8166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:25:43.879  2211  2211 D a       : Opening database auth.proximity.permit_store...
08-16 11:25:43.880  2211  2211 D a       : Closing database...
08-16 11:25:43.881  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:43.882  8039  8166 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 11:25:43.882  8039  8166 V BluetoothPbapService: Succeed to create listening socket 
08-16 11:25:43.882  8039  8166 V BluetoothPbapService: Accepting socket connection...
08-16 11:25:43.882  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:25:43.892  6956  6956 D BluetoothPermissionRequest: onReceive
08-16 11:25:43.893  6956  6956 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 11:25:43.895  6956  6956 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 11:25:43.898  8039  8039 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-16 11:25:43.899  8039  8039 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 11:25:43.904  8039  8039 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-16 11:25:43.922  8039  8039 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 11:25:43.922  8039  8039 V BtOppService: onCreate
,08-16 11:25:43.927  8039  8039 V BluetoothOppNotification: send message
08-16 11:25:43.930  8039  8039 V BtOppService: Starting RfcommListener
08-16 11:25:43.935  8039  8039 D BluetoothOppPreference: Dumping Names:  
08-16 11:25:43.935  8039  8039 D BluetoothOppPreference: {}
08-16 11:25:43.935  8039  8039 D BluetoothOppPreference: Dumping Channels:  
08-16 11:25:43.935  8039  8039 D BluetoothOppPreference: {}
08-16 11:25:43.936  8039  8039 V BtOppService: onStartCommand
08-16 11:25:43.936  8039  8170 V BtOppService: Deleted complete outbound shares, number =  0
,08-16 11:25:43.938  8039  8170 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-16 11:25:43.939  8039  8170 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 11:25:43.939  8039  8173 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 11:25:43.940  8039  8170 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31878e9f on behalf of 
08-16 11:25:43.940  8039  8173 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 11:25:43.941  8039  8039 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 11:25:43.941  8039  8039 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 11:25:43.944  8039  8039 V BluetoothOppNotification: new notify threadi!
08-16 11:25:43.944  8039  8173 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12265bec on behalf of 
08-16 11:25:43.945  8039  8039 V BluetoothOppNotification: send delay message
08-16 11:25:43.945  8039  8173 V BluetoothOppNotification: update too frequent, put in queue
08-16 11:25:43.945  8039  8039 V BtOppService: start RfcommListener
08-16 11:25:43.945  8039  8173 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 11:25:43.946  8039  8173 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 11:25:43.946  8039  8174 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 11:25:43.947  8039  8173 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2edf3bb5 on behalf of 
08-16 11:25:43.947  8039  8174 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c3bc24a on behalf of 
08-16 11:25:43.948  8039  8174 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 11:25:43.948  8039  8039 V BtOppService: RfcommListener started
08-16 11:25:43.949  8039  8039 V BtOppService: ContentObserver received notification
08-16 11:25:43.949  8039  8039 V BtOppService: ContentObserver received notification
08-16 11:25:43.949  8039  8173 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 11:25:43.949  8039  8174 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-16 11:25:43.951  8039  8174 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9e075bb on behalf of 
08-16 11:25:43.951  8039  8173 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-16 11:25:43.953  8039  8174 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 11:25:43.954  8039  8173 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22134ad8 on behalf of 
08-16 11:25:43.955  8039  8175 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 11:25:43.955  8039  8173 V BluetoothOppNotification: update too frequent, put in queue
08-16 11:25:43.956  1034  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:43.956  8039  8173 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 11:25:43.957  8039  8175 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:25:43.957  8039  8175 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-16 11:25:43.958  8039  8175 V BtOppRfcommListener: Started RFCOMM listener....
08-16 11:25:43.958  8039  8175 I BtOppRfcommListener: Accept thread started.
08-16 11:25:43.958  8039  8175 V BtOppRfcommListener: Accepting connection...
08-16 11:25:43.958  8039  8174 V BluetoothOppNotification: outbound notification was removed.
08-16 11:25:43.959  8039  8174 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-16 11:25:43.960  8039  8174 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e14de31 on behalf of 
08-16 11:25:43.960  8039  8174 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 11:25:43.965  8039  8174 V BluetoothOppNotification: inbound notification was removed.
08-16 11:25:43.965  8039  8174 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 11:25:43.967  8039  8174 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@357bb916 on behalf of 
08-16 11:25:43.968  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:43.968  8039  8039 V BluetoothFtpService: Ftp Service onCreate
08-16 11:25:43.968  8039  8039 I BluetoothFtpService: Ftp Service onCreate
08-16 11:25:43.968  8039  8039 V BluetoothFtpService: Ftp Service onStartCommand
08-16 11:25:43.968  8039  8039 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:43.968  8039  8039 V BluetoothFtpService: Starting Listening on sockets
08-16 11:25:43.969  8039  8039 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 11:25:43.969  8039  8039 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 11:25:43.969  8039  8039 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 11:25:43.969  8039  8039 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:43.969  8039  8039 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 11:25:43.969  8039  8039 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 11:25:43.971  8039  8039 V BluetoothFtpService: Handler(): got msg=1
08-16 11:25:43.971  8039  8039 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 11:25:43.971  8039  8039 V BluetoothFtpService: Ftp Service initSocket
08-16 11:25:43.974  1034  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:43.974  8039  8039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:25:43.979  8039  8039 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-16 11:25:43.979  8039  8039 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-16 11:25:43.983  8039  8176 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 11:25:43.994  8039  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3086f1e2
08-16 11:25:43.994  8039  8039 V BluetoothSapService: Sap Service onCreate
,08-16 11:25:43.996  8039  8039 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:25:43.996  8039  8039 V BluetoothSapService: state: 12
08-16 11:25:43.996  8039  8039 V BluetoothSapService: Starting SAP server process
08-16 11:25:43.998  8039  8039 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 11:25:43.999  8039  8178 V BluetoothSapService: Sap Service initRfcommSocket
08-16 11:25:43.985  8177  8177 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:44.000  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:25:43.985  8177  8177 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:44.001  8039  8178 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:25:44.002  8039  8178 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 11:25:44.002  8039  8178 V BluetoothSapService: Succeed to create listening socket 
08-16 11:25:44.002  8039  8178 V BluetoothSapService: Accepting socket connection...
08-16 11:25:44.017  8177  8177 V BT_SAP  : Event pipe created
08-16 11:25:44.017  8177  8177 V BT_SAP  : create_server_socket qcom.sap.server
08-16 11:25:44.017  8177  8177 V BT_SAP  : created socket fd 6
,08-16 11:25:44.302  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:44.302  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:44.302  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:44.302  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:25:44.302  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-16 11:25:44.302  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:44.302  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:44.302  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:25:44.321  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:25:44.326  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:25:44.327  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@176597ac removed from the list
08-16 11:25:44.327  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:25:44.327  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:25:44.327  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:25:44.329  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:25:44.329  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25802c75 added. We now have 4 listener(s)
08-16 11:25:44.329  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:25:44.332  1034  1918 D WifiServiceImplEx: setWifiEnabled: false pid=6792, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 11:25:44.332  1034  1918 D WifiService: setWifiEnabled: false pid=6792, uid=10118
08-16 11:25:44.332  1034  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 11:25:44.336  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:25:44.340  1034  1050 D WifiServiceImplEx: setWifiEnabled: true pid=6792, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 11:25:44.341  1034  1050 D WifiService: setWifiEnabled: true pid=6792, uid=10118
08-16 11:25:44.341  1034  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:25:44.355  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 11:25:44.355  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 11:25:44.355  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-16 11:25:44.357  1034  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 11:25:44.357  1034  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 11:25:44.359  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 11:25:44.359  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 11:25:44.359  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 11:25:44.359  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 11:25:44.359  1034  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 11:25:44.360  1034  1537 E WifiHW  : unknown target_country: EU , set to default
08-16 11:25:44.360  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 11:25:44.360  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 11:25:44.360  1034  1537 I WifiUtil: gEnableBmps=1
08-16 11:25:44.940   315   893 D SoftapController: Softap fwReload - Ok
,08-16 11:25:44.947  8039  8039 V BluetoothOppNotification: new notify threadi!
08-16 11:25:44.947  8039  8039 V BluetoothOppNotification: send delay message
08-16 11:25:44.949  1034  1537 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (585ms)
08-16 11:25:44.954   315   893 D CommandListener: Setting iface cfg
08-16 11:25:44.954   315   893 D CommandListener: Trying to bring down wlan0
,08-16 11:25:44.959   315   893 D CommandListener: Clearing all IP addresses on wlan0
08-16 11:25:44.966  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 11:25:44.966  1034  1110 D Tethering: InitialState.processMessage what=4
08-16 11:25:44.966  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 11:25:44.981  1034  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-16 11:25:44.985  8199  8199 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:44.985  8199  8199 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 11:25:45.004  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 11:25:45.004  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-16 11:25:45.004  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 11:25:45.049  8199  8199 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 11:25:45.059  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 11:25:45.060  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 11:25:45.061  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 11:25:45.061  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 11:25:45.065  8039  8198 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 11:25:45.070  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:45.072  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 11:25:45.075  1034  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 11:25:45.075  1034  1537 D WifiMonitor: connecting to supplicant
08-16 11:25:45.075  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:45.076  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 11:25:45.076  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 11:25:45.074  8039  8198 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3109e133 on behalf of 
08-16 11:25:45.077  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:25:45.077  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 11:25:45.077  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-16 11:25:45.077  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 11:25:45.077  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 11:25:45.077  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 11:25:45.078  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 11:25:45.078  8039  8198 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 11:25:45.080  8039  8198 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 11:25:45.082  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 11:25:45.082  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 11:25:45.082  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 11:25:45.082  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 11:25:45.085  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 11:25:45.086  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 11:25:45.086  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 11:25:45.086  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 11:25:45.086  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 11:25:45.086  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 11:25:45.086  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 11:25:45.090  8039  8198 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4449cf0 on behalf of 
08-16 11:25:45.091  8039  8198 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 11:25:45.095  8039  8198 V BluetoothOppNotification: outbound notification was removed.
08-16 11:25:45.095  8039  8198 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 11:25:45.097  8039  8198 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@aa82269 on behalf of 
08-16 11:25:45.098  8039  8198 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 11:25:45.101  8199  8199 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 11:25:45.101  8199  8199 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 11:25:45.101  8039  8198 V BluetoothOppNotification: inbound notification was removed.
08-16 11:25:45.102  8039  8198 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 11:25:45.105  8039  8198 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a48d4ee on behalf of 
08-16 11:25:45.142  1034  1960 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8216 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 11:25:45.173  8199  8199 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 11:25:45.227  8199  8199 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 11:25:45.232  8199  8199 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 11:25:45.233  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 11:25:45.233  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 11:25:45.233  1034  8238 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 11:25:45.233  1034  8238 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 11:25:45.234  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 11:25:45.234  1034  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 11:25:45.235  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:45.235  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 11:25:45.235  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 11:25:45.236  8199  8199 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 11:25:45.236  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:45.236  1034  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 11:25:45.236  1034  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 11:25:45.237  1034  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 11:25:45.237  1034  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 11:25:45.237  1034  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 11:25:45.238  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 11:25:45.238  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 11:25:45.238  1034  8238 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 11:25:45.239  1034  8238 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 11:25:45.246  1034  1883 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8240 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 11:25:45.249  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 11:25:45.249  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-16 11:25:45.249  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 11:25:45.249  1034  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 11:25:45.250  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.250  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.250  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.250  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.250  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 11:25:45.251  1940  1940 D WfdService: Waiting for WifiP2p enabling
08-16 11:25:45.252  1034  1537 D WifiNative-wlan0: SET update_config 1: returned true
08-16 11:25:45.252  1034  1537 D WifiConfigStore: Loading config and enabling all networks 
08-16 11:25:45.252  1034  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 11:25:45.252  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:45.253  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 11:25:45.254  1034  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 11:25:45.254  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 11:25:45.254  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:45.254  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:45.254  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:45.254  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:45.254  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:45.254  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:45.254  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:45.254  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:45.256  8216  8237 W FormManager: Network not available. Please check & try again.
08-16 11:25:45.256  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:25:45.258  1034  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 11:25:45.259  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:45.259  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:45.259  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:45.259  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:45.259  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:45.259  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:25:45.259  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:25:45.259  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:25:45.2,61  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:25:45.266  1034  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 11:25:45.266  1034  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 11:25:45.267  1034  1537 D WifiStateMachine: enableVerboseLogging : level 2
08-16 11:25:45.267  8216  8239 V FormManager: Network unavailable.
08-16 11:25:45.267  1034  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 11:25:45.267  1034  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 11:25:45.268  1034  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 11:25:45.268  1034  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 11:25:45.268  1034  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 11:25:45.268  1034  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 11:25:45.268  1034  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 11:25:45.268  1034  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 11:25:45.268  1034  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 11:25:45.269  1034  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 11:25:45.269  1034  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 11:25:45.269  1034  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 11:25:45.269  1034  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 11:25:45.269  1034  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 11:25:45.270  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 11:25:45.270  1034  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 11:25:45.270  1034  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 11:25:45.270  1034  1537 D WifiNative-HAL: Setting external_sim to 1
08-16 11:25:45.270  1034  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 11:25:45.270  1034  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 11:25:45.270  1034  1537 I WifiNative-HAL: startHal
08-16 11:25:45.271  1940  1940 D WfdsService: Supplicant Connection state is changed : true
08-16 11:25:45.271  1940  2327 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 11:25:45.271  1034  1537 D wifi    : setting scan oui 0xaf72c300
08-16 11:25:45.271  1940  2327 D WfdsService: Set the WFDS Monitor: true
08-16 11:25:45.271  1940  2327 D WfdsMonitor: WfdsMonitorThread create
08-16 11:25:45.271  1940  2327 D WfdsMonitor: WFDS Monitor is created and started
08-16 11:25:45.271  1940  2327 D WfdsService: WiFi: Supplicant connection re-established
08-16 11:25:45.271  7785  7785 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.271  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 11:25:45.271  1034  1537 I WifiNative-HAL: startHal
08-16 11:25:45.271  1034  1537 D wifi    : setting scan oui 0xaf72c300
08-16 11:25:45.271  1034  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 11:25:45.272  1034  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 11:25:45.272  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 11:25:45.272  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 11:25:45.272  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 11:25:45.272  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 11:25:45.272  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 11:25:45.272  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 11:25:45.272  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 11:25:45.272  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 11:25:45.272  1940  8258 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 11:25:45.273  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 11:25:45.273 , 1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 11:25:45.273  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 11:25:45.273  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 11:25:45.273  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 11:25:45.273  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 11:25:45.273  1940  8258 E CtrlSupplicant: Succeed to open control connection
08-16 11:25:45.273  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 11:25:45.273  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 11:25:45.273  8199  8199 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 11:25:45.273  1940  8258 E CtrlSupplicant: Succeed to open monitor connection
08-16 11:25:45.274  1940  8258 D WfdsMonitor: Supplicant connection established
08-16 11:25:45.274  1940  2327 D WfdsService: Connected to the supplicant for wfds
,08-16 11:25:45.274  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 11:25:45.274  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 11:25:45.275  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 11:25:45.275  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 11:25:45.275  1034  1537 E WifiNative: : [404,921,834 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 11:25:45.275  1034  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 11:25:45.276  1034  1537 D WifiNative-wlan0: RECONNECT: returned true
08-16 11:25:45.276  1034  1537 D WifiNative-wlan0: doString: [STATUS]
08-16 11:25:45.276  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 11:25:45.276  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-16 11:25:45.277  1034  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 11:25:45.277  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 11:25:45.277  8216  8239 V FormManager: Network unavailable.
08-16 11:25:45.277  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-16 11:25:45.277  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.279   315   893 D CommandListener: Setting iface cfg
08-16 11:25:45.279   315   893 D CommandListener: Trying to bring up p2p0
08-16 11:25:45.280  1034  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 11:25:45.280  1034  1536 D LGWifiP2pService: P2pEnablingState
08-16 11:25:45.280  1034  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.280  1034  1536 D LGWifiP2pService: P2p socket connection successful
08-16 11:25:45.280  1034  1536 D LGWifiP2pService: P2pEnabledState
08-16 11:25:45.280  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 11:25:45.280  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-16 11:25:45.281  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 11:25:45.282  1034  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 11:25:45.282  1034  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 11:25:45.282  1034  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 11:25:45.283  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=404929  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 11:25:45.284  1034  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 11:25:45.284  1034  1555 D WifiScanningService: DefaultState got{ when=-4ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.284  1034  1555 I WifiNative-HAL: startHal
08-16 11:25:45.284  1034  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf72c300
08-16 11:25:45.284  1034  1555 D wifi    : failed to get capabilities : -3
08-16 11:25:45.284  1034  1555 E WifiScanningService: could not get scan capabilities
08-16 11:25:45.284  1034  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 11:25:45.284  1034  1556 D RttService: DefaultState got{ when=-4ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.284  1034  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 11:25:45.284  1034  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 11:25:45.285  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 11:25:45.285  1940  1940 D WfdsService: WifiP2pState is changed : true
08-16 11:25:45.285  1940  2327 D WfdsService: Receive the WFDS_ENABLE Method
08-16 11:25:45.285  1940  2327 D WfdsService: Set the WFDS Monitor: true
08-16 11:25:45.285  1940  2327 D WfdsService: Connected to the supplicant for wfds
08-16 11:25:45.285  1940  2327 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 11:25:45.286  8199  8199 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 11:25:45.286  1940  2327 D WfdsService: selectPreferredScanChannel [36]
08-16 11:25:45.286  1940  2327 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 11:25:45.286  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 11:25:45.287  1034  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-16 11:25:45.287  1034  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 11:25:45.287  1034  1536 D LGWifiP2pService: before postfix = G3
08-16 11:25:45.287  1034  1536 D WifiServerServiceExt: postfix byte check : 2
08-16 11:25:45.287  1034  1536 D LGWifiP2pService: after postfix = G3
08-16 11:25:,45.287  1034  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 11:25:45.287  1940  1940 D WfdsService: isConnected: false
,08-16 11:25:45.287  1034  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 11:25:45.287  1034  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 11:25:45.287  1034  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 11:25:45.287  1034  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 11:25:45.287  1034  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 11:25:45.287  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 11:25:45.288  1034  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 11:25:45.288  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-16 11:25:45.288  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 11:25:45.288  1034  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 11:25:45.288  1034  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 11:25:45.289  1034  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 11:25:45.289  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 11:25:45.290  1034  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 11:25:45.290  1034  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 11:25:45.290  1034  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 11:25:45.290  1034  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-16 11:25:45.292  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 11:25:45.292  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 11:25:45.292  1940  1940 D WfdsService: Update P2p Interface State: 3
08-16 11:25:45.293  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=404939  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 11:25:45.293  1034  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 11:25:45.293  1034  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 11:25:45.294  1034  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 11:25:45.294  1034  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 11:25:45.295  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:45.295  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:45.296  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:45.297  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.297  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.297  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 11:25:45.298  8199  8199 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 11:25:45.298  1034  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 11:25:45.298  1034  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 11:25:45.298  1034  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 11:25:45.298  1034  1536 D LGWifiP2pService: InactiveState
08-16 11:25:45.299  1034  1536 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.299  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.299  1034  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 11:25:45.299  1034  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 11:25:45.299  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 11:25:45.299  1034  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 11:25:45.299  1034  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 11:25:45.299  8199  8199 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:45.300  1034  8238 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 11:25:45.300  1034  8238 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 11:25:45.300  1034  8238 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:45.300  1034  8238 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:45.300  8199  8199 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 11:25:45.300  8199  8199 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 11:25:45.300  8199  8199 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.300  8199  8199 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.300  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 11:25:45.301  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 11:25:45.301  1940  8258 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 11:25:45.301  1034  8238 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:45.301  1034  8238 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.301  1940  8258 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:45.301  1940  8258 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:45.301  1034  8238 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.301  1034  8238 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.301  1034  8238 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:45.301  1034  8238 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.301  1034  8238 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.301  1034  8238 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.301  1034  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 11:25:45.302  1034  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.302  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.302  1034  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.302  1034  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.302  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-16 11:25:45.302  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 11:25:45.303  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-16 11:25:45.303  8199  8199 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 11:25:45.303  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 11:25:45.303  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:45.303  1034  8238 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:45.303  1034  8238 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 11:25:45.304  8199  8199 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 11:25:45.304  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.304  1034  1536 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.304  8199  8199 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.304  1034  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 11:25:45.304  1940  2327 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 11:25:45.305  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 11:25:45.305  8199  8199 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.305  1034  8238 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:45.305  1034  8238 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.305  1034  8238 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.305  1034  8238 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.305  1034  8238 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:45.305  1034  8238 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.305  1034  8238 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.305  1034  8238 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 11:25:45.305  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 11:25:45.305  1940  8258 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:45.305  1940  8258 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 11:25:45.305  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 11:25:45.305  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 11:25:45.305  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 11:25:45.305  8199  8199 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 11:25:45.305  1034  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.306  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 11:25:45.306  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.306  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 11:25:45.306  1034  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.306  1034  8238 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 11:25:45.306  1034  8238 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 11:25:45.306  1034  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 ,arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.306  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.306  1034  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.306  1034  1536 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.306  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:45.306  1034  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 11:25:45.306  1034  1034 E WifiServerServiceExt: No p2p device connected
08-16 11:25:45.306  1034  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 11:25:45.306  1034  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 11:25:45.306  1034  1537 D WifiNative-wlan0: doBoolean: SCAN
08-16 11:25:45.306  1034  1537 D WifiNative-wlan0: SCAN: returned false
08-16 11:25:45.307  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=404953  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 11:25:45.307  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=404954  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 11:25:45.308  1034  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:45.308  1034  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:45.308  1034  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:45.309  1034  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:45.309  1034  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 11:25:45.310  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.310  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.310  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 11:25:45.310  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:45.310  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 11:25:45.316  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:45.316  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:45.317  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:45.327  8240  8240 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:45.329  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 11:25:45.335  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:45.336  1034  1918 I ActivityManager: Killing 7247:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 11:25:45.365  1034  1051 W libprocessgroup: failed to open /acct/uid_10062/pid_7247/cgroup.procs: No such file or directory
,08-16 11:25:45.378  8240  8240 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 11:25:45.385  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 11:25:45.389  8216  8262 W FormManager: Network not available. Please check & try again.
,08-16 11:25:45.391  8216  8263 V FormManager: Network unavailable.
08-16 11:25:45.394  8216  8263 V FormManager: Network unavailable.
08-16 11:25:45.396  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:45.411  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 11:25:45.411  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 11:25:45.413  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:45.416  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 11:25:45.424  4324  8264 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 11:25:45.429  4324  8265 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 11:25:45.429  4324  8265 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 11:25:45.471  1034  1883 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8266 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 11:25:45.616  8266  8266 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 11:25:45.617  8266  8266 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 11:25:45.628  8266  8266 V [BNRBootReceiver]: Boot Receiver Return
08-16 11:25:45.629  8266  8266 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 11:25:45.692  1034  1918 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8287 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 11:25:45.701  1034  1918 I ActivityManager: Killing 7264:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 11:25:45.739  1034  1994 W libprocessgroup: failed to open /acct/uid_10085/pid_7264/cgroup.procs: No such file or directory
,08-16 11:25:45.762  8287  8287 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 11:25:45.791  8287  8287 D PluginManager: init()
,08-16 11:25:45.871  8199  8199 E wpa_supplicant: USIM:  scard_init function
08-16 11:25:45.872  8199  8199 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 11:25:45.880  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 11:25:45.884  1034  8238 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 11:25:45.884  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 11:25:45.884  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-16 11:25:45.884  1034  8238 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 11:25:45.884  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 11:25:45.884  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 11:25:45.887  1034  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 11:25:45.888  1034  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 11:25:45.889  1034  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 11:25:45.891  1034  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 11:25:45.891  1034  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 11:25:45.897  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=405544  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 11:25:45.898  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=405545  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 11:25:45.904  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:45.904  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:45.905  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.905  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:45.905  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 11:25:45.905  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:45.905  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 11:25:45.907  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:45.997  8199  8199 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 11:25:45.998  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 11:25:45.999  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 11:25:45.999  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 11:25:45.999  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 11:25:45.999  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:45.999  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:46.000  1034  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 11:25:46.001  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=405647  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 11:25:46.002  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=405648  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 11:25:46.002  1034  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=405648
08-16 11:25:46.002  1034  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=405649
08-16 11:25:46.003  1034  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=405649
08-16 11:25:46.003  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=405649
08-16 11:25:46.003  1034  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=405650
08-16 11:25:46.008  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=405654  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 11:25:46.013  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.013  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.013  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-16 11:25:46.015  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=405661  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 11:25:46.016  1034  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:46.016  1034  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:46.016  1034  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:46.016  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:46.016  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:46.016  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:46.017  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 11:25:46.017  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:46.017  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:46.018  8199  8199 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 11:25:46.018  8199  8199 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 11:25:46.019  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.021  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 11:25:46.021  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 11:25:46.021  1034  8238 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 11:25:46.021  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 11:25:46.022  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 11:25:46.022  1034  8238 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 11:25:46.022  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:46.022  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:46.023  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.023  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.023  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 11:25:46.023  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:46.023  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 11:25:46.024  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=405671  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 11:25:46.025  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=405671  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 11:25:46.025  1034  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=405672
08-16 11:25:46.025  1034  1537 E, WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=405672
08-16 11:25:46.026  1034  1537 D WifiNative-wlan0: doString: [STATUS]
08-16 11:25:46.026  1034  8238 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 11:25:46.026  1034  8238 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 11:25:46.026  1034  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 11:25:46.027  1034  1537 I WifiServiceExtension: setVHTCapabilityType  : false
,08-16 11:25:46.033  1034  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 11:25:46.033  1034  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 11:25:46.035  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.035  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.035  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 11:25:46.039  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.039  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.039  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 11:25:46.039  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:46.039  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 11:25:46.041  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.043  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:46.043  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:46.044  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.045  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:46.045  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:46.047  1034  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 11:25:46.047  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.047  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 11:25:46.047  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 11:25:46.048  1034  1543 D ConnectivityService: Got NetworkAgent Messenger
08-16 11:25:46.048  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 11:25:46.048  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 11:25:46.048  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 11:25:46.048  1034  1543 D ConnectivityService: NetworkAgent connected
08-16 11:25:46.053  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 11:25:46.053  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 11:25:46.053  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 11:25:46.054  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 11:25:46.054  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 11:25:46.060  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 11:25:46.061   315   893 D CommandListener: Setting iface cfg
08-16 11:25:46.065  1034  1537 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 11:25:46.065  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=405711  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:46.066  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=405712  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:46.066  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=405712  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:46.067  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:46.067  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 11:25:46.067  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=405713  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:46.068  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=405714  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:46.068  1034  8305 D DhcpStateMachine: StoppedState
08-16 11:25:46.068  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=405714  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 11:25:46.068  1034  8305 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:46.068  1034  8305 D DhcpStateMachine: WaitBeforeStartState
08-16 11:25:46.069  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:23239] from screen [on:0 period:-1834236459] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:25:46.070  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1834236458] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:25:46.070  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 11:25:46.074  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.075  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.076  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.076  1034  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-16 11:25:46.076  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 11:25:46.077  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.077  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.077  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.077  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 11:25:46.078  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:46.078  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 11:25:46.079  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 11:25:46.079  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 11:25:46.080  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-16 11:25:46.080  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-16 11:25:46.080  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 11:25:46.080  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 11:25:46.081  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 11:25:46.081  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 11:25:46.081  1034  1537 D WifiNative-wlan0: SET ps 0: returned true
08-16 11:25:46.081  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 11:25:46.081  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 11:25:46.081  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 11:25:46.082  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2de0a85 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:46.082  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2de0a85 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:46.082  1034  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 11:25:46.082  1034  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 11:25:46.082  1034  8305 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:46.082  1034  8305 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 11:25:46.082  1034  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 11:25:46.083   315   893 D CommandListener: Setting iface cfg
08-16 11:25:46.083   315   893 D CommandListener: Trying to bring up wlan0
08-16 11:25:46.084  1034  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 11:25:46.086  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.087  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.088  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.089  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.090  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.091  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 11:25:46.091  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 11:25:46.092  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 11:25:46.093  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 11:25:46.093  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms wh,at=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:46.093  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 11:25:46.094  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:46.094  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 11:25:46.095  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 11:25:46.095  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-16 11:25:46.095  8199  8199 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 11:25:46.096  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 11:25:46.096  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 11:25:46.113  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
,08-16 11:25:46.115  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 11:25:46.116  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 11:25:46.117  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 11:25:46.117  1034  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 11:25:46.119  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
08-16 11:25:46.122  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:46.122  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:46.123  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.123  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.124  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 11:25:46.124  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.125  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 11:25:46.127  1034  1543 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 11:25:46.131  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 11:25:46.131  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.131  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 11:25:46.133  1034  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 11:25:46.135  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 11:25:46.140  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-16 11:25:46.141  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.141  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.141  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 11:25:46.143  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 11:25:46.147  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.147  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:46.147  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 11:25:46.147  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:46.147  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 11:25:46.148  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.151  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:46.151  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 11:25:46.151  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.154  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 11:25:46.154  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 11:25:46.154  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.167  1034  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 11:25:46.167  1034  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 11:25:46.169  1034  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 11:25:46.170   315   893 E Netd    : netlink response contains error (File exists)
08-16 11:25:46.170  1034  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 11:25:46.171  1034  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 11:25:46.171  1034  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 11:25:46.171  1034  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 11:25:46.172  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 11:25:46.172  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 11:25:46.172  1034  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 11:25:46.173  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:46.173  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 11:25:46.173  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:46.173  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 11:25:46.174  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 11:25:46.174  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:46.174  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:46.174  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 11:25:46.175  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:46.175  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 11:25:46.175  1034  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-16 11:25:46.175  1034  1543 D ConnectivityService:    accepting network in place of null
08-16 11:25:46.175  1034  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:46.175  1034  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:46.176  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:46.176  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:46.176  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 11:25:46.176  1034  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnecte,dToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 11:25:46.176  1034  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 11:25:46.176  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 11:25:46.177   315  8315 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-16 11:25:46.182  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 11:25:46.183  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 11:25:46.183  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 11:25:46.183  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 11:25:46.185  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:46.185  1034  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 11:25:46.185  1034  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 11:25:46.186  1034  1543 D ConnectivityService: validation of new default Network = false
08-16 11:25:46.186  1034  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 11:25:46.186  1034  1543 D DSQN    : enableDataServiceNotify 
08-16 11:25:46.186  1034  1543 D DSQN    : start dsqn bin
08-16 11:25:46.192  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 11:25:46.192  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:46.192  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:46.192  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:46.193  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 11:25:46.185  8316  8316 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:46.185  8316  8316 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 11:25:46.200  1034  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 11:25:46.209  8316  8316 E DSQN    : DSQN ssw
08-16 11:25:46.221  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 11:25:46.222  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.222  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.225   315  8315 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 11:25:46.256   315  8315 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 11:25:46.285  1034  8305 D DhcpStateMachine: DHCPV4 request on wlan0
,08-16 11:25:46.286  1034  8305 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-16 11:25:46.287  1034  8305 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 11:25:46.290   315   892 D LGDataListener: argv[0]=dsqncommand
08-16 11:25:46.290   315   892 D LGDataListener: argv[1]=wlan0
08-16 11:25:46.290   315   892 D LGDataListener: argv[2]=1
08-16 11:25:46.290   315   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 11:25:46.291  1034  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 11:25:46.291  1034  1108 D DSQN    : start to monitor internet connection
08-16 11:25:46.285  8321  8321 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:46.285  8321  8321 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 11:25:46.315  8321  8321 I dhcpcd  : version 5.5.6 starting
,08-16 11:25:46.318  8321  8321 E dhcpcd  : get_duid: m
08-16 11:25:46.318  8321  8321 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 11:25:46.318  8321  8321 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 11:25:46.324  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 09:25:46 GMT], X-Android-Received-Millis=[1471339546323], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471339546289]}
08-16 11:25:46.324  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 11:25:46.324  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 11:25:46.325  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 11:25:46.325  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 11:25:46.325  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:46.325  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:46.325  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 11:25:46.326  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 11:25:46.326  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 11:25:46.326  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:46.326  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:46.327  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:46.328  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 11:25:46.330  1034  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:46.331  1034  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:46.331  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:46.332  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:46.332  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 11:25:46.332  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 11:25:46.357  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 11:25:46.358  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 11:25:46.359  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:46.368  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:46.368  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:46.368  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:46.368  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:46.368  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:46.368  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:46.368  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:25:46.368  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:25:46.370  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:46.370  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:25:46.370  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25802c75 removed from the list
08-16 11:25:46.370  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:25:46.370  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:25:46.370  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:25:46.387  8321  8321 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 11:25:46.388  8321  8321 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 11:25:46.388  8321  8321 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 11:25:46.388  8321  8321 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 11:25:46.388  8321  8321 D dhcpcd  : wlan0: sending REQUEST (xid 0x10b87fbe), next in 3.14 seconds
,08-16 11:25:46.433  8321  8321 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 11:25:46.440  8287  8287 W ExternalStrings: load override strings
08-16 11:25:46.440  8287  8287 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 11:25:46.440  8287  8287 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 11:25:46.443  8287  8287 D StatusProvider: onCreate
08-16 11:25:46.444  8321  8321 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 11:25:46.444  8321  8321 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 11:25:46.445  8321  8321 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 11:25:46.445  8321  8321 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-16 11:25:46.445  8321  8321 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 11:25:46.446  8321  8321 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 11:25:46.446  8321  8321 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 11:25:46.446  8321  8321 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 11:25:46.518  8287  8287 V Signer  : override build config not found
08-16 11:25:46.518  8287  8287 D Signer  : value of property debug is false
,08-16 11:25:46.565  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-16 11:25:46.565  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 11:25:46.565  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 11:25:46.566  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 11:25:46.566  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 11:25:46.566  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 11:25:46.566  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 11:25:46.567  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 11:25:46.567  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 11:25:46.567  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 11:25:46.567  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 11:25:46.568  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,08-16 11:25:46.568  8287  8287 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 11:25:46.580  8287  8287 V LGMDMManager: Create singleton instance
08-16 11:25:46.627  8287  8287 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 11:25:46.682  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 11:25:46.683  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:46.691  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:46.697  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:46.704  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:46.706  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 11:25:46.715  7943  7943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 11:25:46.718  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:46.719  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 11:25:46.722  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:46.728  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:46.733  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:46.733  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:46.735  7943  7943 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 11:25:46.738  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 11:25:46.742  6956  6956 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 11:25:46.836  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:46.837  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 11:25:46.845  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:46.846  8287  8347 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-16 11:25:46.851  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:46.859  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:46.860  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 11:25:46.861  7943  7943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 11:25:46.867  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 11:25:46.867  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 11:25:46.867  6956  6956 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 11:25:46.867  6956  6956 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 11:25:46.867  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 11:25:46.868  6956  6956 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 11:25:46.868  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 11:25:46.868  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 11:25:46.868  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 11:25:46.868  6956  6956 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 11:25:46.868  6956  6956 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 11:25:46.868  6956  6956 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 11:25:46.872  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:46.872  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 11:25:46.878  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:46.885  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:46.892  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:46.892  1034  8305 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 11:25:46.892  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:46.893  1034  8305 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 11:25:46.893  1034  8305 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 11:25:46.894  1034  8305 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
,08-16 11:25:46.894  1034  8305 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 11:25:46.893  7943  7943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 11:25:46.894  1034  8305 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 11:25:46.894  1034  8305 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
,08-16 11:25:46.894  1034  8305 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 11:25:46.894  1034  8305 D DhcpStateMachine: RunningState
08-16 11:25:46.905  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:46.905  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 11:25:46.913  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:46.918  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 11:25:46.926  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:46.926  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 11:25:46.926  7943  7943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 11:25:46.929  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:46.929  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 11:25:46.936  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:46.942  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:46.953  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 11:25:46.956  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:46.957  7943  7943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 11:25:46.962  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:46.963  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 11:25:46.968  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:46.972  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:46.977  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:46.978  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:46.978  7943  7943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 11:25:46.986  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 11:25:46.987  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 11:25:46.996  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:47.000  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:47.007  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:47.007  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:47.012  7943  7943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 11:25:47.017  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:47.018  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 11:25:47.024  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:47.029  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:47.037  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 11:25:47.037  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:47.039  7943  7943 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 11:25:47.042  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:47.044  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 11:25:47.046  8240  8240 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 11:25:47.050  8240  8240 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 11:25:47.054  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 11:25:47.060  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:47.071  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 11:25:47.072  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:47.073  7943  7943 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 11:25:47.074  7943  7943 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 11:25:47.075  7943  7943 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 11:25:47.080  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 11:25:47.080  8287  8349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 11:25:47.083  8240  8240 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 11:25:47.084  8240  8240 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 11:25:47.086  6956  6956 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 11:25:47.097  6956  6956 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 11:25:47.102  7943  7943 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 11:25:47.102  7943  7943 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 11:25:47.103  7943  7943 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 11:25:47.104  7943  7943 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 11:25:47.104  7943  7943 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 11:25:47.108  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 11:25:47.110  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 11:25:47.112  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 11:25:47.115  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 11:25:47.117  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 11:25:47.118  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 11:25:47.120  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 11:25:47.121  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 11:25:47.123  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 11:25:47.125  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 11:25:47.127  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 11:25:47.128  1034  2031 I ActivityManager: Killing 7283:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-16 11:25:47.149  8287  8347 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:47.150  8287  8347 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:47.264  8287  8347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-16 11:25:47.342  1034  1649 W libprocessgroup: failed to open /acct/uid_10093/pid_7283/cgroup.procs: No such file or directory
,08-16 11:25:47.386  1034  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 11:25:47.386  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:47.387  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:47.387  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:47.388  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:47.388  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 11:25:47.389  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 11:25:47.389  1034  1543 D ConnectivityService: identical MTU - not setting
08-16 11:25:47.389  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 11:25:47.390  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 11:25:47.390  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:47.390  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:47.391  1034  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:47.391  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 11:25:47.398  8287  8347 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-16 11:25:47.409  8287  8347 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 11:25:47.410  8287  8347 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-16 11:25:47.412  8287  8347 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 11:25:47.414  8287  8347 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 11:25:47.415  8287  8347 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 11:25:47.419  8287  8347 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 11:25:47.423  8287  8347 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-16 11:25:49.080  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=72.0, 0.0, 0.0  rx=64.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1834233448] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 11:25:49.083  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=72.0, 0.0, 0.0  rx=64.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834233445] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:25:49.083  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:25:49.107  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 11:25:49.138  1034  1538 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 11:25:49.187  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:49.202  1034  1110 D Tethering: MasterInitialState.processMessage what=3
08-16 11:25:49.218  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:49.218  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:49.218  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:49.218  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:49.218  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:49.218  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:49.218  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:25:49.218  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:25:49.223  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:49.234  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:25:49.234  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:25:49.234  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:25:49.234  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:25:49.234  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:25:49.234  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:49.234  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:25:49.234  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:25:49.239  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:25:49.245  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:49.247  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 11:25:49.257  5780  5780 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-16 11:25:49.297  8287  8347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 11:25:49.313  2211  2211 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:25:49.330  1034  1574 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-16 11:25:49.332  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:49.332  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:49.332  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 11:25:49.333  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:25:49.333  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 11:25:49.346  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 11:25:49.346  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:49.346  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 11:25:49.347  7137  7137 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 11:25:49.353   315  8389 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 11:25:49.353   315  8389 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-16 11:25:49.362  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-16 11:25:49.367  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cb52bc4
08-16 11:25:49.367  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 11:25:49.367  7137  7137 D AppUp4:CustFacade: isPhone : true
08-16 11:25:49.367  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-16 11:25:49.368  7137  7137 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-16 11:25:49.375  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 09:25:49 GMT], X-Android-Received-Millis=[1471339549375], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471339549336]}
08-16 11:25:49.376  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 11:25:49.376  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 11:25:49.376  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 11:25:49.377  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 11:25:49.377  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:25:49.377  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:49.377  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 11:25:49.377  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 11:25:49.377  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 11:25:49.377  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:25:49.377  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:49.377  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:25:49.379  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 11:25:49.379  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:49.380  4324  4324 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 11:25:49.382  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 11:25:49.385  4324  4324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 11:25:49.389  3531  3531 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:49.393  3531  3531 V DownloadManager: DownloadService onCreate
08-16 11:25:49.399  3531  8402 I DownloadManager: in removeSpuriousFiles
08-16 11:25:49.400  3531  8402 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-16 11:25:49.400  4324  8404 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 11:25:49.401  3531  8402 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@242e2143 on behalf of 3531
08-16 11:25:49.401  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-16 11:25:49.401  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-16 11:25:49.401  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-16 11:25:49.402  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-16 11:25:49.402  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-16 11:25:49.402  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-16 11:25:49.402  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-16 11:25:49.402  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-16 11:25:49.402  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-16 11:25:49.402  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-16 11:25:49.402  3531  8402 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,08-16 11:25:49.403  4324  8404 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-16 11:25:49.406  3531  8402 I DownloadManager: in trimDatabase
08-16 11:25:49.406  3531  8402 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-16 11:25:49.410  4324  8406 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:49.410  4324  8406 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 11:25:49.413  3531  8402 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d3008f9 on behalf of 3531
,08-16 11:25:49.441  1034  1883 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8407 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 11:25:49.446  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 11:25:49.455  3531  3531 V DownloadManager: DownloadService onStartCommand
,08-16 11:25:49.457  4324  8404 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-16 11:25:49.458  3531  8403 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-16 11:25:49.460  3531  8403 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@31878e9f on behalf of 3531
08-16 11:25:49.462  4324  4324 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-16 11:25:49.463  4324  4324 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-16 11:25:49.464  4324  4324 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-16 11:25:49.466  4324  4324 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-16 11:25:49.469  4324  4324 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-16 11:25:49.471  3531  8403 V DownloadManager: processing inserted download 1
08-16 11:25:49.472  3531  8403 V DownloadManager: processing inserted download 4
08-16 11:25:49.474  3531  8403 V DownloadManager: processing inserted download 7
08-16 11:25:49.476  3531  8403 V DownloadManager: processing inserted download 8
08-16 11:25:49.478  3531  8403 V DownloadManager: processing inserted download 9
08-16 11:25:49.479  3531  8403 V DownloadManager: processing inserted download 10
,08-16 11:25:49.480  3531  8403 V DownloadManager: processing inserted download 11
,08-16 11:25:49.481  3531  8403 V DownloadManager: processing inserted download 12
08-16 11:25:49.482  3531  8403 V DownloadManager: processing inserted download 13
08-16 11:25:49.483  3531  8403 V DownloadManager: processing inserted download 14
08-16 11:25:49.485  3531  8403 V DownloadManager: processing inserted download 16
08-16 11:25:49.488  3531  3531 V DownloadManager: DownloadService onDestroy
,08-16 11:25:49.522  8407  8407 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 11:25:49.523  8407  8407 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 11:25:49.524  8407  8407 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 11:25:49.525  8407  8407 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 11:25:49.619  8407  8407 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 11:25:49.648  8407  8407 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 11:25:49.710  8407  8407 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 11:25:49.758  8407  8407 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 11:25:49.758  8407  8407 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:49.919  8407  8407 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 11:25:49.969  8407  8407 I HubEmail: JNI_OnLoad()
08-16 11:25:49.969  8407  8407 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 11:25:49.969  8407  8407 I HubEmail: registerNatives()
08-16 11:25:49.969  8407  8407 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 11:25:49.969  8407  8407 I HubEmail: registerNativeMethods()
08-16 11:25:49.969  8407  8407 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 11:25:49.970  8407  8407 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-16 11:25:50.017  3483  3483 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-16 11:25:50.017  3483  3483 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 11:25:50.017  3483  3483 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 11:25:50.017  3483  3483 D PhoneState: setPdpRejectCasuse : false
,08-16 11:25:50.054   315  8453 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 11:25:50.055   315  8453 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-16 11:25:50.060  1034  1925 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8452 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-16 11:25:50.061  8407  8443 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:25:50.065   315  8389 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 11:25:50.125   315  8453 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-16 11:25:50.162  8216  8442 V FormManager: There are no updated forms. The schedule will be deleted.
,08-16 11:25:50.169  8216  8442 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-16 11:25:50.183  8452  8452 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:50.183  8452  8452 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 11:25:50.186  8452  8452 D PhoneMonitor: Register our PhoneStateListener
,08-16 11:25:50.200  8452  8452 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 11:25:50.201  8452  8452 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 11:25:50.232  8452  8452 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 11:25:50.233  8452  8452 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-16 11:25:50.235  8452  8452 D TelephonyAutoProfiling: [parse] Load xml
08-16 11:25:50.238  8452  8452 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 11:25:50.238  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 11:25:50.239  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 11:25:50.239  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 11:25:50.239  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 11:25:50.239  8452  8452 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 11:25:50.239  8452  8452 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 11:25:50.245  8452  8452 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 11:25:50.250  1034  1883 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8478 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 11:25:50.251  1034  1883 I ActivityManager: Killing 7785:com.google.android.talk/u0a72 (adj 15): empty #17
,08-16 11:25:50.312  1034  1953 W libprocessgroup: failed to open /acct/uid_10072/pid_7785/cgroup.procs: No such file or directory
,08-16 11:25:50.318  1034  2013 I ActivityManager: Killing 7830:com.android.contacts/u0a19 (adj 15): empty #17
08-16 11:25:50.352   315  8496 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 11:25:50.353   315  8496 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-16 11:25:50.376  1034  2049 W libprocessgroup: failed to open /acct/uid_10019/pid_7830/cgroup.procs: No such file or directory
,08-16 11:25:50.388   315  8496 D libc-netbsd: res_queryN name = www.google.com succeed
,08-16 11:25:50.392   315  8500 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 11:25:50.392   315  8500 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 11:25:50.392   315  8500 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 11:25:50.398  1815  8498 I CheckinService: active receiver: enabled
08-16 11:25:50.411  1815  8498 I CheckinService: Preparing to send checkin request
08-16 11:25:50.411  1815  8498 I EventLogService: Accumulating logs since 1471339516945
,08-16 11:25:50.454  1034  1539 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-16 11:25:50.518  1034  2049 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8502 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 11:25:50.524  1034  2049 I ActivityManager: Killing 7851:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 11:25:50.575  1815  8498 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-16 11:25:50.575  1034  1894 W libprocessgroup: failed to open /acct/uid_10027/pid_7851/cgroup.procs: No such file or directory
,08-16 11:25:50.675  1034  1574 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8522 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 11:25:50.679  1034  1574 I ActivityManager: Killing 7876:com.android.vending/u0a44 (adj 15): empty #17
08-16 11:25:50.739  1034  1953 I art     : Explicit concurrent mark sweep GC freed 77594(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.425ms total 149.963ms
,08-16 11:25:50.795  1034  1994 W libprocessgroup: failed to open /acct/uid_10044/pid_7876/cgroup.procs: No such file or directory
,08-16 11:25:50.837  8522  8522 I art     : Almond Protected OAT
08-16 11:25:50.926  1034  2049 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8539 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 11:25:50.939  8522  8522 D WeatherApplication: removeAccount
08-16 11:25:50.940  8522  8522 D WeatherApplication: Account.length = 0
08-16 11:25:50.941  8522  8522 E WeatherApplication: OPERATOR:OPEN
08-16 11:25:50.949   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 24.270ms
,08-16 11:25:50.951  8522  8522 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:50
08-16 11:25:50.961  8522  8522 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 11:25:50.962  8522  8522 D Weather.Utils: 2 : All the weather widget is gone.
08-16 11:25:50.972   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 21.001ms
08-16 11:25:50.974  8522  8522 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-16 11:25:50.984  8522  8522 D WeatherAncestor: connectivity changed - connection : true
08-16 11:25:50.985  8539  8539 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 11:25:50.985  8522  8522 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 11:25:50.986  8539  8539 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 11:25:50.995  8522  8522 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 11:25:50.995  8522  8522 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 11:25:50.996  8522  8522 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 11:25:50.998   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 20.148ms
,08-16 11:25:51.015  8522  8522 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 11:25:51.016  8522  8522 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:25:51
08-16 11:25:51.016  8539  8539 I MultiDex: VM with version 2.1.0 has multidex support
08-16 11:25:51.016  8539  8539 I MultiDex: install
08-16 11:25:51.017  8539  8539 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 11:25:51.069  1034  1649 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8558 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 11:25:51.070  1034  1649 I ActivityManager: Killing 7920:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 11:25:51.168  1034  1994 W libprocessgroup: failed to open /acct/uid_10080/pid_7920/cgroup.procs: No such file or directory
,08-16 11:25:51.194  8539  8539 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-16 11:25:51.308   277   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 11:25:51.308   277   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 11:25:51.308   277   383 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 11:25:51.313  8558  8577 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 11:25:51.316   277   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 11:25:51.316   277   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 11:25:51.316   277   383 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 11:25:51.319  8558  8577 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 11:25:51.337   277   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 11:25:51.337   277   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 11:25:51.337   277   383 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 11:25:51.338  8558  8581 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 11:25:51.343   277   383 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 11:25:51.343   277   383 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 11:25:51.343   277   383 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 11:25:51.343  8558  8581 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 11:25:51.375  6792  8583 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 11:25:51.375  6792  8583 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 11:25:51.509  8539  8555 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:25:51.509  8539  8555 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:25:51.539  8558  8558 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 11:25:51.550  8558  8558 I LibraryLoader: Loading: webviewchromium
08-16 11:25:51.554  8558  8558 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 1205-1210)
08-16 11:25:51.554  8558  8558 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 11:25:51.559  8558  8558 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a48c4bf}
08-16 11:25:51.560  8558  8558 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 11:25:51.561  8558  8558 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 11:25:51.572  8558  8558 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 11:25:51.573  8558  8558 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 11:25:51.592   320  1384 V AudioPolicyService: registerClient() client 0xb558ae20, uid 10093
,08-16 11:25:51.596  8558  8558 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 11:25:51.597  8558  8558 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 11:25:51.597  8558  8558 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 11:25:51.597  8558  8602 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 11:25:51.615  8558  8558 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:25:51.615  8558  8558 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:25:51.615  8558  8558 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:25:51.615  8558  8558 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:25:51.615  8558  8558 I Adreno-EGL: Remote Branch: 
08-16 11:25:51.615  8558  8558 I Adreno-EGL: Local Patches: 
08-16 11:25:51.615  8558  8558 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:25:51.667  8610  8610 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 11:25:51.694  8558  8558 I NSApplication: Starting up...
,08-16 11:25:51.718  8610  8610 I dex2oat : dex2oat took 51.319ms (threads: 4)
,08-16 11:25:51.719  1034  2013 I ActivityManager: Killing 7638:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 11:25:51.733  8539  8555 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:25:51.733  8539  8555 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:25:51.733  8539  8555 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:25:51.733  8539  8555 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:25:51.733  8539  8555 I Adreno-EGL: Remote Branch: 
08-16 11:25:51.733  8539  8555 I Adreno-EGL: Local Patches: 
08-16 11:25:51.733  8539  8555 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:25:51.804  1034  1894 W libprocessgroup: failed to open /acct/uid_10037/pid_7638/cgroup.procs: No such file or directory
,08-16 11:25:51.831  2211  2211 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 11:25:51.842  2211  2211 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 11:25:51.843  2211  2211 D c       : Getting all permits...
08-16 11:25:51.843  2211  2211 D a       : Opening database...
08-16 11:25:51.847  2211  2211 D a       : Opening database auth.proximity.permit_store...
08-16 11:25:51.848  2211  2211 D a       : Closing database...
,08-16 11:25:52.058  8539  8555 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:25:52.058  8539  8555 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:25:52.058  8539  8555 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:25:52.058  8539  8555 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:25:52.058  8539  8555 I Adreno-EGL: Remote Branch: 
08-16 11:25:52.058  8539  8555 I Adreno-EGL: Local Patches: 
08-16 11:25:52.058  8539  8555 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:25:52.118  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=40.5, 0.0, 0.0  rx=35.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1834230410] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 11:25:52.121  8539  8555 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:25:52.121  8539  8555 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:25:52.121  8539  8555 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:25:52.121  8539  8555 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:25:52.121  8539  8555 I Adreno-EGL: Remote Branch: 
08-16 11:25:52.121  8539  8555 I Adreno-EGL: Local Patches: 
08-16 11:25:52.121  8539  8555 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:25:52.121  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=40.5, 0.0, 0.0  rx=35.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834230407] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:25:52.121  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:25:52.259   315  8629 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 11:25:52.259   315  8629 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 11:25:52.301   315  8629 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 11:25:52.505  1815  8498 I CheckinTask: Sending checkin request (7891 bytes)
,08-16 11:25:52.740  2211  2227 I art     : Explicit concurrent mark sweep GC freed 7287(477KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.620ms total 38.831ms
,08-16 11:25:52.758  1815  8498 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 11:25:52.771  1815  8498 I CheckinService: active receiver: disabled
,08-16 11:25:52.796  2211  2211 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 11:25:52.816  2211  2211 I GCM     : GCM config loaded
,08-16 11:25:52.834   315  8635 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 11:25:52.836   315  8635 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 11:25:52.837   315  8635 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-16 11:25:52.852  8452  8452 V SetupWizard: Connected to Gservices successfully
,08-16 11:25:53.084  2211  8649 D GCM     : Connected
,08-16 11:25:53.129  2211  8649 D GCM     : Message class com.google.e.a.a.q
,08-16 11:25:54.387  6792  8583 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-16 11:25:54.387  6792  8583 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-16 11:25:54.391  6792  8583 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:25:54.391  6792  8583 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:25:54.392  6792  8583 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 11:25:54.393  6792  8656 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-16 11:25:54.393  6792  8656 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 11:25:54.393  6792  8656 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:25:54.394  6792  8656 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:25:54.394  6792  8656 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 11:25:54.396  6792  8659 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: OutgoingSocketThread/Receiver)
08-16 11:25:54.397  6792  8659 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: OutgoingSocketThread/Receiver)
08-16 11:25:54.397  6792  8659 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 11:25:54.397  6792  8659 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 11:25:54.399  6792  8658 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 864, name: OutgoingSocketThread/Sender)
08-16 11:25:54.402  6792  8661 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: IncomingSocketThread/Receiver)
08-16 11:25:54.403  6792  8661 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: IncomingSocketThread/Receiver)
08-16 11:25:54.403  6792  8661 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 11:25:54.403  6792  8661 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 11:25:54.408  6792  8660 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: IncomingSocketThread/Sender)
08-16 11:25:55.138  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=30.8, 0.0, 0.0  rx=25.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1834227390] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:25:55.139  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2447 sc=60 link=72 tx=30.8, 0.0, 0.0  rx=25.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1834227389] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:25:55.139  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:25:56.331  8558  8579 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 11:25:56.777  1034  1537 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 11:25:56.779  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 11:25:56.780  1034  1537 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 11:25:56.781  1034  1537 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 11:25:56.782  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 11:25:56.794  1034  1537 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 11:25:57.262  1034  1894 I ActivityManager: Killing 7684:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 11:25:57.299  1034  2031 W libprocessgroup: failed to open /acct/uid_1000/pid_7684/cgroup.procs: No such file or directory
,08-16 11:25:58.150  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=28.9, 0.0, 0.0  rx=24.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1834224378] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 11:25:58.160  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=28.9, 0.0, 0.0  rx=24.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834224375] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 11:25:58.160  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:00.065  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 11:26:00.066  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 11:26:00.066  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 11:26:00.066  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-16 11:26:00.082  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 11:26:00.083  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-16 11:26:00.087  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-16 11:26:00.088  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 11:26:00.472  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 11:26:00.540  1034  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 11:26:00.574  1034  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8664 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 11:26:00.582  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 11:26:00.583  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 11:26:00.594  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 11:26:00.629  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 11:26:00.654  1034  1034 D administrator: Handling package changes for user 0
08-16 11:26:00.671  8664  8664 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 11:26:00.761  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-16 11:26:00.762  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-16 11:26:00.768  8664  8664 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:26:00.768  8664  8664 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 11:26:00.799  1034  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 11:26:00.805  1034  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 11:26:00.812  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 11:26:00.813  2461  2461 V GmsNetworkLocationProvi: DISABLE
08-16 11:26:00.838  2461  2461 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 11:26:00.876  1034  1090 D LocationProviderProxy: applying state to connected service
,08-16 11:26:00.902  8664  8708 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 11:26:00.902  8664  8708 I Babel   : MmsConfig.loadMmsSettings
08-16 11:26:00.904  8664  8708 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 11:26:00.904  8664  8708 I Babel   : MmsConfig.loadFromDatabase
,08-16 11:26:00.920  8664  8708 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 11:26:00.921  8664  8708 I Babel   : MmsConfig.loadFromResources
08-16 11:26:00.923  8664  8708 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 11:26:00.924  8664  8708 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 11:26:00.936  8664  8664 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:26:00.943  8664  8706 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 11:26:00.944  8664  8706 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 11:26:00.958  8664  8706 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 11:26:00.972  1815  8712 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 11:26:00.972  1815  8712 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-16 11:26:00.978  7137  7137 I AppUp4:CustModeStarterReceiver: onReceive
08-16 11:26:00.981  8664  8706 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 11:26:00.983  8664  8706 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 11:26:00.985  8664  8706 W AudioCapabilities: Unsupported mime audio/evrc
08-16 11:26:00.987  7137  7137 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3cb52bc4
08-16 11:26:00.987  7137  7137 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 11:26:00.987  7137  7137 D AppUp4:CustFacade: isPhone : true
08-16 11:26:00.987  7137  7137 D AppUp4:CustModeStarterReceiver: begin check event
08-16 11:26:00.988  7137  7137 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 11:26:00.994  1815  4754 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 11:26:01.014  8664  8706 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 11:26:01.015  8664  8706 W VideoCapabilities: Unsupported mime video/divx
,08-16 11:26:01.024  8664  8706 W VideoCapabilities: Unsupported mime video/divx311
08-16 11:26:01.025  8664  8706 W VideoCapabilities: Unsupported mime video/divx4
08-16 11:26:01.029  8664  8706 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 11:26:01.033  1034  2049 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8715 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 11:26:01.037  1034  2013 I ActivityManager: Killing 8266:com.lge.bnr/1000 (adj 15): empty #17
08-16 11:26:01.055  8664  8706 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 11:26:01.059  8664  8706 W AudioCapabilities: Unsupported mime audio/eac3
08-16 11:26:01.060  8664  8706 W AudioCapabilities: Unsupported mime audio/ac3
08-16 11:26:01.061  8664  8706 W AudioCapabilities: Unsupported mime audio/g726
08-16 11:26:01.061  8664  8706 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 11:26:01.062  8664  8706 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 11:26:01.063  8664  8706 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 11:26:01.065  8664  8706 W VideoCapabilities: Unsupported mime video/theora
08-16 11:26:01.067  8664  8706 W VideoCapabilities: Unsupported mime video/mjpg
,08-16 11:26:01.094  1034  1953 W libprocessgroup: failed to open /acct/uid_1000/pid_8266/cgroup.procs: No such file or directory
,08-16 11:26:01.113  8715  8715 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 11:26:01.114  8715  8715 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 11:26:01.114  8715  8715 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 11:26:01.115  8715  8715 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 11:26:01.115  8715  8715 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 11:26:01.180  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=14.9, 0.0, 0.0  rx=12.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1834221348] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:26:01.182  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=14.9, 0.0, 0.0  rx=12.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1834221346] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:26:01.182  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:01.231  8715  8715 I SystemConfig: BUILD Country: EU
,08-16 11:26:01.231  8715  8715 I SystemConfig: BUILD Operator: OPEN
,08-16 11:26:01.285  1034  1649 I ActivityManager: Killing 8240:com.lge.sync/1000 (adj 15): empty #17
,08-16 11:26:01.370  1034  1574 W libprocessgroup: failed to open /acct/uid_1000/pid_8240/cgroup.procs: No such file or directory
,08-16 11:26:01.381  8715  8733 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 11:26:01.382  8715  8733 I SystemConfig: existFile = false
08-16 11:26:01.384  8715  8733 I SystemConfig: canReadFile = false
08-16 11:26:01.384  8715  8733 I SystemConfig: systemFeature RCS result false
08-16 11:26:01.384  8715  8733 D SystemConfig: refreshRcsSupport() :false
,08-16 11:26:01.425  1034  1649 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8735 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 11:26:01.471  8735  8735 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 11:26:01.471  8735  8735 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 11:26:01.472  8735  8735 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 11:26:01.472  8735  8735 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 11:26:01.555  8735  8735 I AppConfig: Total System Memory = 2995761152
,08-16 11:26:01.566  8735  8735 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 11:26:01.672  1034  1960 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8754 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 11:26:01.676  1034  1960 I ActivityManager: Killing 7729:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 11:26:01.696  7943  7943 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 11:26:01.697  7943  7943 W System.err: android.os.DeadObjectException
08-16 11:26:01.697  7943  7943 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 11:26:01.697  7943  7943 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 11:26:01.697  7943  7943 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 11:26:01.697  7943  7943 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 11:26:01.697  7943  7943 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 11:26:01.697  7943  7943 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 11:26:01.697  7943  7943 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 11:26:01.697  7943  7943 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 11:26:01.697  7943  7943 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 11:26:01.697  7943  7943 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 11:26:01.697  7943  7943 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:26:01.698  7943  7943 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 11:26:01.698  7943  7943 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 11:26:01.698  7943  7943 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 11:26:01.698  7943  7943 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-16 11:26:01.698  7943  7943 W System.err: android.os.DeadObjectException
,08-16 11:26:01.698  7943  7943 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-16 11:26:01.698  7943  7943 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 11:26:01.698  7943  7943 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 11:26:01.698  7943  7943 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-16 11:26:01.698  7943  7943 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 11:26:01.699  7943  7943 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 11:26:01.699  7943  7943 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 11:26:01.699  7943  7943 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 11:26:01.699  7943  7943 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 11:26:01.699  7943  7943 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 11:26:01.699  7943  7943 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:26:01.699  7943  7943 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 11:26:01.699  7943  7943 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 11:26:01.699  7943  7943 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 11:26:01.699  7943  7943 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 11:26:01.701  7943  7943 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 11:26:01.913  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_7729/cgroup.procs: No such file or directory
08-16 11:26:01.914  1034  1050 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 11:26:01.935  7943  7943 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 11:26:01.935  7943  7943 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 11:26:02.014  1034  1918 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8785 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 11:26:02.017  7943  7943 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 11:26:02.093  8785  8785 D UEI.SmartControl: Quickset Services start...
,08-16 11:26:02.101  8785  8785 I UEI.SmartControl: Manufacture = LGE
08-16 11:26:02.101  8785  8785 D UEI.SmartControl: Id = LGNevo
08-16 11:26:02.105  8785  8785 D UEI.SmartControl: File observer start...
08-16 11:26:02.106  8785  8785 E UEI.SmartControl: IR Port is disabled: false
08-16 11:26:02.106  8785  8785 D UEI.SmartControl: Starting file observer...
08-16 11:26:02.106  8785  8785 D UEI.SmartControl: Extracting JNI libs...
08-16 11:26:02.106  8785  8785 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-16 11:26:02.181  8754  8754 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 11:26:02.206  8785  8785 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-16 11:26:02.206  8785  8785 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 11:26:02.206  8785  8785 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-16 11:26:02.242  8785  8785 I UEI.SmartControl: --- Selecting new region: 6
,08-16 11:26:02.244  8785  8785 I UEI.SmartControl: Model = LG-D855
08-16 11:26:02.246  8785  8785 D UEI.SmartControl: QS Service created
08-16 11:26:02.260  8785  8785 I UEI.SmartControl: Service initServices...
,08-16 11:26:02.264  8785  8785 D UEI.SmartControl: QS start get config
08-16 11:26:02.283  8754  8754 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 11:26:02.284  8754  8754 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 11:26:02.310  8785  8785 D UEI.SmartControl: Loading JNI Libs...
,08-16 11:26:02.328  8754  8754 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 11:26:02.348  8754  8754 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 11:26:02.351  8754  8754 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 11:26:02.369  8754  8754 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-16 11:26:02.369  8754  8754 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 11:26:02.394  6792  6853 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 11:26:02.395  6792  6853 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 11:26:02.399  1034  1953 I ActivityManager: Killing 6956:com.android.settings/1000 (adj 15): empty #17
08-16 11:26:02.400  6792  6853 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e17106 Bundle[{}]
,08-16 11:26:02.402  6792  6853 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 11:26:02.402  6792  6853 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 11:26:02.404  6792  6853 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 11:26:02.405  6792  6853 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 11:26:02.406  6792  6853 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 11:26:02.406  6792  6853 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 11:26:02.572  1034  1850 W libprocessgroup: failed to open /acct/uid_1000/pid_6956/cgroup.procs: No such file or directory
,08-16 11:26:02.589  4607  8835 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-16 11:26:02.597  8785  8785 I UEI.SmartControl: Supports setup maps: true
08-16 11:26:02.600  8785  8785 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 11:26:02.600  8785  8785 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 11:26:02.600  8785  8785 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 11:26:02.600  8785  8785 I UEI.SmartControl: ### init IR Blaster...
08-16 11:26:02.604  8785  8785 D serial_port: Configuring serial port
08-16 11:26:02.615  8785  8785 E UEI.SmartControl: UEIBLaster setting for 616
08-16 11:26:02.615  8785  8785 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 11:26:02.615  8785  8785 I UEI.SmartControl: configuring settings for MAXQ616
08-16 11:26:02.615  8785  8785 I UEI.SmartControl: Get version...
,08-16 11:26:02.632  8785  8837 D UEI.SmartControl: serial port data available: 21
,08-16 11:26:02.661  8785  8785 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 11:26:02.661  8785  8785 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 11:26:02.662  8785  8785 I UEI.SmartControl: QS saving settings...
,08-16 11:26:02.666  8785  8785 D UEI.SmartControl: IR Blaster version: 25672567
08-16 11:26:02.674  1034  1649 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8839 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-16 11:26:02.680  3531  6255 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-16 11:26:02.682  8785  8837 D UEI.SmartControl: serial port data available: 4
,08-16 11:26:02.685  3531  6255 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2edf3bb5 on behalf of 8754
08-16 11:26:02.712  8754  8754 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 11:26:02.724  8785  8860 I UEI.SmartControl: Device manager: loading config....
,08-16 11:26:02.730  8785  8860 D UEI.SmartControl: ----------- loading internal config...
08-16 11:26:02.734  8785  8785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 11:26:02.736  8785  8785 E UEI.SmartControl: Services init done
08-16 11:26:02.736  8785  8785 D UEI.SmartControl: QS Service init finished
08-16 11:26:02.736  8754  8754 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-16 11:26:02.738  8785  8785 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 11:26:02.738  8785  8785 D UEI.SmartControl: QS Service version code: 201091
08-16 11:26:02.739  8785  8785 D UEI.SmartControl: Service requested: Control
08-16 11:26:02.744  8785  8860 E UEI.SmartControl: Loading SETTINGS...
08-16 11:26:02.744  8785  8785 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 11:26:02.746  1034  1574 I ActivityManager: Killing 7943:com.lge.qremote/u0a112 (adj 15): empty #17
,08-16 11:26:02.754  8785  8860 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 11:26:02.772  8839  8839 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 11:26:02.777  8785  8858 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 11:26:02.777  8785  8858 D UEI.SmartControl: -----service ready thread exits
08-16 11:26:02.786  8785  8785 D UEI.SmartControl: Internal service binding...
,08-16 11:26:02.786  1034  1953 W libprocessgroup: failed to open /acct/uid_10112/pid_7943/cgroup.procs: No such file or directory
08-16 11:26:02.800  8839  8839 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 11:26:02.800  8839  8839 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 11:26:02.800  8839  8839 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-16 11:26:02.800  8839  8839 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 11:26:02.800  8839  8839 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 11:26:02.800  8839  8839 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-16 11:26:02.816  1034  1994 I ActivityManager: Killing 8407:com.lge.email/u0a23 (adj 15): empty #17
,08-16 11:26:02.856  1034  1987 W libprocessgroup: failed to open /acct/uid_10023/pid_8407/cgroup.procs: No such file or directory
,08-16 11:26:03.088  1034  1960 V SIM_STK : Menu title from STK is T-Mobile
,08-16 11:26:03.101  4607  8835 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 512 ms] updated apps [took 512 ms] 
,08-16 11:26:04.202  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=6.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1834218326] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 11:26:04.216  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=6.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1834218312] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:26:04.216  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 11:26:07.235  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1834215293] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:07.238  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834215290] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:07.238  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:07.737  8785  8862 D UEI.SmartControl: Internal timer expired: 1
08-16 11:26:07.737  8785  8862 D UEI.SmartControl: unbind internal service
,08-16 11:26:07.758  8785  8785 D UEI.SmartControl: Service.onUnbind: IControl
,08-16 11:26:07.761  8785  8785 D UEI.SmartControl: Service.onDestroy
08-16 11:26:07.761  8785  8785 D UEI.SmartControl: Lock is in USE false
08-16 11:26:07.761  8785  8785 D UEI.SmartControl: unbind internal service
08-16 11:26:07.762  8785  8785 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3dbb4030
08-16 11:26:07.763  8785  8785 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 11:26:07.763  8785  8785 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 11:26:07.763  8785  8785 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 11:26:07.763  8785  8785 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 11:26:07.763  8785  8785 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 11:26:07.763  8785  8785 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 11:26:07.763  8785  8785 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 11:26:07.763  8785  8785 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 11:26:07.763  8785  8785 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:26:07.763  8785  8785 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 11:26:07.763  8785  8785 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 11:26:07.763  8785  8785 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:26:07.763  8785  8785 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 11:26:07.763  8785  8785 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 11:26:07.763  8785  8785 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 11:26:07.763  8785  8785 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3dbb4030
08-16 11:26:07.766  8785  8785 D serial_port: close(fd = 25)
08-16 11:26:07.769  8785  8785 I UEI.SmartControl: Serial port is closed.
08-16 11:26:07.769  8785  8785 I UEI.SmartControl: Serial port is closed.
08-16 11:26:07.769  8785  8785 D UEI.SmartControl: Blaster closed
08-16 11:26:07.769  8785  8785 D UEI.SmartControl: Shut down QS...
08-16 11:26:07.769  8785  8785 D UEI.SmartControl: Stopping QS lib
08-16 11:26:07.770  8785  8785 D UEI.SmartControl: QS lib stop result = true
08-16 11:26:07.770  8785  8785 D UEI.SmartControl: Stopped QS lib
08-16 11:26:07.772  8785  8785 D UEI.SmartControl: Stopped file observer...
08-16 11:26:07.772  8785  8785 D UEI.SmartControl: QS shutdown complete
,08-16 11:26:10.227  1034  1050 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-16 11:26:10.230  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:26:10.230  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:26:10.230  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 11:26:10.230  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 11:26:10.230  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 11:26:10.263  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1834212265] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 11:26:10.268  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1834212260] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:10.268  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 11:26:10.274  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 09:26:10 GMT], X-Android-Received-Millis=[1471339570273], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471339570242]}
08-16 11:26:10.274  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 11:26:10.274  1034  8304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 11:26:10.275  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 11:26:10.275  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 11:26:10.275  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 11:26:10.275  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:26:10.275  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 11:26:10.275  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 11:26:10.275  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 11:26:10.275  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 11:26:10.275  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:26:10.276  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 11:26:10.277  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 11:26:12.429  6792  6853 I System.out: Running OutgoingSocketThread
,08-16 11:26:12.442  6792  8873 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-16 11:26:12.442  6792  8873 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 11:26:13.278  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1834209250] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:13.281  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834209247] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:13.281  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:14.373  1034  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=492664873, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-16 11:26:14.388  1034  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{31898ca type 2 when 434014 com.google.android.gms} when 434014
08-16 11:26:14.396   315  8875 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 11:26:14.398   315  8875 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 11:26:14.423  2578  2578 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 11:26:14.437   315  8875 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 11:26:14.454  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=492664873 [*alarm*], flags=0x0
,08-16 11:26:14.780  2211  8876 D GCM     : Connected
,08-16 11:26:14.954  1034  1925 I art     : Explicit concurrent mark sweep GC freed 39421(1950KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 3.220ms total 148.820ms
,08-16 11:26:14.968  2211  8876 D GCM     : Message class com.google.e.a.a.q
,08-16 11:26:15.445  6792  8873 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 11:26:15.445  6792  8873 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 11:26:15.446  6792  8873 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:26:15.446  6792  8873 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:26:15.446  6792  8873 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 11:26:15.451  6792  8877 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-16 11:26:15.451  6792  8877 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 11:26:15.451  6792  8877 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 11:26:15.451  6792  8877 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:26:15.453  6792  8880 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: OutgoingSocketThread/Receiver)
08-16 11:26:15.451  6792  8877 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 11:26:15.455  6792  8879 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 876, name: OutgoingSocketThread/Sender)
08-16 11:26:15.456  6792  8881 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 878, name: IncomingSocketThread/Sender)
08-16 11:26:15.458  6792  8882 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 879, name: IncomingSocketThread/Receiver)
08-16 11:26:15.458  6792  8882 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 879, thread name: IncomingSocketThread/Receiver)
08-16 11:26:15.458  6792  8882 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 11:26:15.458  6792  8882 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 879, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 11:26:15.459  6792  8880 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: OutgoingSocketThread/Receiver)
08-16 11:26:15.459  6792  8880 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 11:26:15.459  6792  8880 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 11:26:16.308  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1834206220] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:16.311  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834206217] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:16.312  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:19.336  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1834203193] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:26:19.339  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=5.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1834203189] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 11:26:19.339  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:22.365  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1834200164] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 11:26:22.368  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1834200160] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:22.368  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:23.451  6792  6853 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 888)
,08-16 11:26:23.458  6792  6853 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 11:26:23.459  6792  6853 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 889)
08-16 11:26:25.394  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1834197135] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:25.397  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834197132] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:25.397  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:26.067  1034  1537 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 11:26:26.068  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-16 11:26:26.070  1034  1537 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 11:26:26.071  1034  1537 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 11:26:26.072  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-16 11:26:26.073  1034  1537 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 11:26:28.417  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1834194111] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:28.421  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834194108] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:28.421  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:28.463  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:26:28.463  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c9cc40a added. We now have 3 listener(s)
,08-16 11:26:28.466  1034  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:26:28.469  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 11:26:28.469  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:26:28.469  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:26:28.469  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:26:28.469  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c36b47b added. We now have 4 listener(s)
08-16 11:26:28.469  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:26:28.470  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:26:28.474  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:26:28.478  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:26:28.478  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:26:28.478  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:26:28.478  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:26:28.478  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:26:28.478  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:28.478  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:26:28.478  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:26:28.484  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:28.484  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:26:28.486  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:26:28.488  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:26:28.489  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:26:28.489  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:26:28.489  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:26:28.489  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:26:28.489  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:28.489  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:26:28.489  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:26:28.489  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c9cc40a removed from the list
08-16 11:26:28.489  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:28.489  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c36b47b removed from the list
08-16 11:26:28.489  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:26:28.489  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:28.490  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:28.490  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:26:28.496  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:26:28.496  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:26:28.496  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:28.496  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c36b47b not in the list
08-16 11:26:28.496  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:28.496  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:28.497  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:26:28.497  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:26:28.497  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:28.498  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c36b47b not in the list
08-16 11:26:28.498  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:26:28.498  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:28.498  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:28.498  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c9cc40a not in the list
08-16 11:26:28.499  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:26:28.499  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab41af1 added. We now have 3 listener(s)
08-16 11:26:28.500  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:26:28.502  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 11:26:28.502  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:26:28.502  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:26:28.503  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:26:28.503  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264b16d6 added. We now have 4 listener(s)
08-16 11:26:28.503  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:26:28.505  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 11:26:28.511  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:26:28.515  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:26:28.515  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:26:28.515  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:26:28.515  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:26:28.515  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:26:28.515  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:28.515  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:26:28.515  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:26:28.517  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:28.518  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 11:26:28.521  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:26:28.523  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:26:28.523  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:26:28.523  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 11:26:28.523  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 11:26:28.523  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:26:28.523  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:26:28.527  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 11:26:28.528  1034  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:26:28.532  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 11:26:28.535  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 11:26:28.536  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 11:26:28.537  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:26:28.538  6792  6853 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 11:26:28.540  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:26:28.540  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:26:31.445  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1834191084] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:31.448  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1834191080] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:31.448  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:31.542  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:26:31.542  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:26:31.542  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:26:31.553  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:26:31.553  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:31.555  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:26:31.555  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:26:31.555  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab41af1 removed from the list
08-16 11:26:31.555  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:31.555  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264b16d6 removed from the list
08-16 11:26:31.555  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:26:31.555  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:31.556  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:31.556  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:31.559  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:26:31.559  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:26:31.560  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:26:31.560  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:26:31.560  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:31.560  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264b16d6 not in the list
08-16 11:26:31.560  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:31.560  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:31.562  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:26:31.565  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:26:31.565  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:26:31.565  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:26:31.565  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:31.565  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264b16d6 not in the list
08-16 11:26:31.565  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:26:31.565  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:31.565  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:31.565  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab41af1 not in the list
08-16 11:26:31.567  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:26:31.567  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1eb9ca62 added. We now have 3 listener(s)
08-16 11:26:31.567  1034  2049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:26:31.570  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 11:26:31.570  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:26:31.570  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:26:31.570  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:26:31.570  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9137f3 added. We now have 4 listener(s)
08-16 11:26:31.570  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:26:31.572  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:26:31.576  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:26:31.583  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:26:31.583  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:26:31.583  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:26:31.583  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:26:31.583  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:26:31.583  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:31.583  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:26:31.583  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:26:31.586  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:31.586  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:26:31.588  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:26:31.592  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:26:31.593  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 11:26:31.594  6792  6853 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 11:26:31.595  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 11:26:31.598  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 11:26:31.598  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 11:26:31.598  6792  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 11:26:31.598  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:26:31.600  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 11:26:31.603  6792  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 11:26:31.603  6792  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 11:26:31.604  6792  6792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 11:26:31.605  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 11:26:31.605  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 11:26:31.606  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:26:31.606  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:26:31.610  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 11:26:31.612  1034  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:26:31.616  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 11:26:31.620  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 11:26:31.621  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 11:26:31.622  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 11:26:31.625  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:26:31.626  6792  6853 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 11:26:31.628  6792  8883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 11:26:31.631  8039  8055 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
,08-16 11:26:31.632  6792  8883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 11:26:34.473  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1834188056] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 11:26:34.486  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1834188042] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 11:26:34.486  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 11:26:34.632  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:26:34.633  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:26:34.642  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 11:26:34.642  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 11:26:34.642  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 11:26:34.642  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 11:26:34.646  6792  8883 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 11:26:34.646  6792  8883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 11:26:34.646  6792  8883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 11:26:34.646  6792  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 11:26:34.648  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:26:34.648  6792  6853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 11:26:34.649  6792  6792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 11:26:34.650  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 11:26:34.650  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:34.650  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:26:34.652  6792  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:26:34.652  6792  6792 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 11:26:34.655  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:26:34.655  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:34.655  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:26:34.655  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:26:34.655  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1eb9ca62 removed from the list
08-16 11:26:34.655  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:34.655  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9137f3 removed from the list
08-16 11:26:34.655  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:26:34.655  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:34.656  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:34.656  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:34.657  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:26:34.657  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:26:34.658  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:26:34.658  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:26:34.658  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:34.658  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9137f3 not in the list
08-16 11:26:34.658  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:34.658  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:34.659  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:26:34.662  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:26:34.662  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:26:34.662  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:26:34.662  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:34.662  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9137f3 not in the list
08-16 11:26:34.662  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:26:34.662  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:34.662  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:34.662  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1eb9ca62 not in the list
08-16 11:26:34.663  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:26:34.663  679,2  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7d604f added. We now have 3 listener(s)
,08-16 11:26:34.669  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:26:34.672  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 11:26:34.672  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:26:34.672  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:26:34.672  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:26:34.672  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ad443dc added. We now have 4 listener(s)
08-16 11:26:34.673  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:26:34.674  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:26:34.677  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:26:34.685  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:26:34.685  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:26:34.685  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:26:34.685  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:26:34.685  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:26:34.685  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:34.685  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:26:34.685  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:26:34.686  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:34.686  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:26:34.688  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:26:34.690  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:26:34.693  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:26:34.693  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 11:26:34.693  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 11:26:34.693  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:26:34.693  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:26:34.697  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 11:26:34.697  1034  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:26:34.701  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 11:26:34.702  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 11:26:34.705  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 11:26:34.707  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:26:34.709  6792  6853 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 11:26:37.506  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1834185022] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:37.509  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834185019] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:37.510  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:37.716  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:26:37.716  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:26:37.716  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:26:37.724  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 11:26:37.725  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:37.725  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:26:37.726  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:26:37.726  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7d604f removed from the list
08-16 11:26:37.726  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:37.726  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ad443dc removed from the list
08-16 11:26:37.726  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:26:37.726  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:37.730  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:37.730  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:37.735  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:26:37.735  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:26:37.745  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:26:37.745  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:26:37.745  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:37.745  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ad443dc not in the list
08-16 11:26:37.745  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:37.745  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:37.747  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:26:37.748  6792  6853 D BluetoothLeScanner: could not find callback wrapper
08-16 11:26:37.748  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:26:37.748  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:26:37.748  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:37.748  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ad443dc not in the list
08-16 11:26:37.748  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:26:37.748  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:37.748  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:37.748  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7d604f not in the list
08-16 11:26:37.749  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:26:37.749  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b4fc1c8 added. We now have 3 listener(s)
08-16 11:26:37.750  1034  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:26:37.753  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 11:26:37.753  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:26:37.753  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:26:37.753  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:26:37.753  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b0a261 added. We now have 4 listener(s)
08-16 11:26:37.753  6792  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:26:37.757  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:26:37.762  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:26:37.766  6792  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:26:37.766  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:26:37.766  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:26:37.766  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:26:37.766  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:26:37.766  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:37.766  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:26:37.766  6792  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:26:37.770  6792  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:26:37.770  6792  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:26:37.774  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:26:37.776  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:26:37.777  6792  6853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:26:37.777  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:26:37.777  6792  6853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:26:37.777  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:26:37.777  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:37.777  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:26:37.777  6792  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:26:37.777  6792  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b4fc1c8 removed from the list
08-16 11:26:37.777  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:37.778  6792  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b0a261 removed from the list
08-16 11:26:37.778  6792  6853 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:26:37.778  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:37.778  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:37.779  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:26:37.782  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:26:37.782  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:26:37.784  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:37.785  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b0a261 not in the list
08-16 11:26:37.785  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:37.785  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:37.786  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:26:37.787  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:26:37.787  6792  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:26:37.787  6792  6853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b0a261 not in the list
,08-16 11:26:37.787  6792  6853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:26:37.787  6792  6853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:26:37.787  6792  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:26:37.788  6792  6853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b4fc1c8 not in the list,
08-16 11:26:40.538  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1834181990] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:40.541  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834181987] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:40.541  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:42.791  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 11:26:42.791  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 11:26:42.792  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 11:26:42.792  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:26:42.793  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-16 11:26:42.793  6792  6853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:26:43.565  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1834178964] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:43.568  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1834178961] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:43.568  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:46.592  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1834175936] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 11:26:46.603  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1834175926] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 11:26:46.603  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 11:26:49.624  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1834172905] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:49.627  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1834172901] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:49.628  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:49.829  6792  8884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 898, name: My test thread name)
,08-16 11:26:51.825  6792  6853 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 898
,08-16 11:26:51.826  6792  6853 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 898, name: My test thread name)
,08-16 11:26:51.838  6792  8884 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 898, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
08-16 11:26:51.845  6792  8885 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 899, name: My test thread name)
08-16 11:26:51.845  6792  8885 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 899, thread name: My test thread name)
08-16 11:26:51.845  6792  8885 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 899, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-16 11:26:51.848  6792  6853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 11:26:51.854  6792  8886 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 903, name: My test thread name)
08-16 11:26:51.854  6792  8886 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 903, thread name: My test thread name): Test exception.
08-16 11:26:51.854  6792  8886 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 903, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-16 11:26:51.858  6792  6853 I jxcore-log: Total number of executed tests:  82
08-16 11:26:51.858  6792  6853 I jxcore-log: 
08-16 11:26:51.858  6792  6853 I jxcore-log: Number of passed tests:  82
08-16 11:26:51.858  6792  6853 I jxcore-log: 
08-16 11:26:51.858  6792  6853 I jxcore-log: Number of failed tests:  0
08-16 11:26:51.858  6792  6853 I jxcore-log: 
08-16 11:26:51.858  6792  6853 I jxcore-log: Number of ignored tests:  0
08-16 11:26:51.858  6792  6853 I jxcore-log: 
08-16 11:26:51.859  6792  6853 I jxcore-log: Total duration:  147637
08-16 11:26:51.859  6792  6853 I jxcore-log: 
08-16 11:26:51.859  6792  6853 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 11:26:51.859  6792  6853 I jxcore-log: 
08-16 11:26:51.875  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.875  6792  6853 I jxcore-log: 
08-16 11:26:51.878  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.878  6792  6853 I jxcore-log: 
08-16 11:26:51.880  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.880  6792  6853 I jxcore-log: 
08-16 11:26:51.881  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.881  6792  6853 I jxcore-log: 
08-16 11:26:51.882  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.882  6792  6853 I jxcore-log: 
,08-16 11:26:51.897  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.897  6792  6853 I jxcore-log: 
08-16 11:26:51.901  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 11:26:51.901  6792  6853 I jxcore-log: 
08-16 11:26:51.903  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.903  6792  6853 I jxcore-log: 
,08-16 11:26:51.906  6792  6792 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 11:26:51.908  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.908  6792  6853 I jxcore-log: 
08-16 11:26:51.909  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:26:51.909  6792  6853 I jxcore-log: 
08-16 11:26:51.910  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:26:51.910  6792  6853 I jxcore-log: 
08-16 11:26:51.911  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:26:51.911  6792  6853 I jxcore-log: 
08-16 11:26:51.912  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.912  6792  6853 I jxcore-log: 
08-16 11:26:51.913  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.913  6792  6853 I jxcore-log: 
08-16 11:26:51.914  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.914  6792  6853 I jxcore-log: 
08-16 11:26:51.915  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.915  6792  6853 I jxcore-log: 
08-16 11:26:51.916  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:26:51.916  6792  6853 I jxcore-log: 
08-16 11:26:51.917  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:26:51.917  6792  6853 I jxcore-log: 
08-16 11:26:51.918  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:26:51.918  6792  6853 I jxcore-log: 
08-16 11:26:51.919  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.919  6792  6853 I jxcore-log: 
08-16 11:26:51.919  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.919  6792  6853 I jxcore-log: 
08-16 11:26:51.920  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.920  6792  6853 I jxcore-log: 
08-16 11:26:51.921  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.921  6792  6853 I jxcore-log: 
08-16 11:26:51.922  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.922  6792  6853 I jxcore-log: 
08-16 11:26:51.923  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi",:"off","cellular":"doNotCare"}
08-16 11:26:51.923  6792  6853 I jxcore-log: 
08-16 11:26:51.926  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.926  6792  6853 I jxcore-log: 
08-16 11:26:51.927  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.927  6792  6853 I jxcore-log: 
08-16 11:26:51.928  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.928  6792  6853 I jxcore-log: 
08-16 11:26:51.929  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.929  6792  6853 I jxcore-log: 
08-16 11:26:51.930  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.930  6792  6853 I jxcore-log: 
08-16 11:26:51.930  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.930  6792  6853 I jxcore-log: 
08-16 11:26:51.931  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.931  6792  6853 I jxcore-log: 
08-16 11:26:51.932  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.932  6792  6853 I jxcore-log: 
08-16 11:26:51.933  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:26:51.933  6792  6853 I jxcore-log: 
08-16 11:26:51.933  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 11:26:51.933  6792  6853 I jxcore-log: 
,08-16 11:26:51.940  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 11:26:51.940  6792  6853 I jxcore-log: 
08-16 11:26:51.941  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.941  6792  6853 I jxcore-log: 
08-16 11:26:51.941  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.941  6792  6853 I jxcore-log: 
08-16 11:26:51.942  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.942  6792  6853 I jxcore-log: 
08-16 11:26:51.943  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.943  6792  6853 I jxcore-log: 
08-16 11:26:51.944  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.944  6792  6853 I jxcore-log: 
08-16 11:26:51.945  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.945  6792  6853 I jxcore-log: 
08-16 11:26:51.946  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.946  6792  6853 I jxcore-log: 
08-16 11:26:51.946  6792  6853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:26:51.946  6792  6853 I jxcore-log: 
08-16 11:26:52.209  8887  8887 D AndroidRuntime: 
08-16 11:26:52.209  8887  8887 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 11:26:52.218  8887  8887 D AndroidRuntime: CheckJNI is OFF
08-16 11:26:52.426  8887  8887 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 11:26:52.445  1034  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 11:26:52.445  1034  1091 I ActivityManager: Killing 6792:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-16 11:26:52.513  1034  1894 I WindowState: WIN DEATH: Window{18063f09 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 11:26:52.518  1034  1542 D WifiService: Client connection lost with reason: 4
08-16 11:26:52.523  1034  1894 D InputDispatcher: Window went away: Window{18063f09 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 11:26:52.575  1034  1091 I ActivityManager:   Force finishing activity ActivityRecord{b84c0ba u0 com.test.thalitest/.MainActivity t6}
,08-16 11:26:52.649  1034  1537 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1834169879] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:52.650  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1834169878] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 11:26:52.650  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 11:26:52.666   348   369 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 11:26:52.676  1034  1987 W ActivityManager: Spurious death for ProcessRecord{36f801a3 6792:com.test.thalitest/u0a118}, curProc for 6792: null
08-16 11:26:52.679  1034  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 11:26:52.681  1940  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 11:26:52.681  1940  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ff4fafe co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-16 11:26:52.684  1940  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 11:26:52.685  1940  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e3c725f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 11:26:52.690  1034  1123 I ActivityManager:   Force finishing activity ActivityRecord{b84c0ba u0 com.test.thalitest/.MainActivity t6 f}
08-16 11:26:52.691  1034  1123 W ActivityManager: Duplicate finish request for ActivityRecord{b84c0ba u0 com.test.thalitest/.MainActivity t6 f}
,08-16 11:26:52.728  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-16 11:26:52.730  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 11:26:52.732  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 11:26:52.733  2032  2126 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-16 11:26:52.736  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 11:26:52.746  1034  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 11:26:52.750  2461  2677 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 11:26:52.752  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 11:26:52.752  3840  3840 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-16 11:26:52.756  8039  8039 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 11:26:52.756  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 11:26:52.768  4607  4607 I art     : Explicit concurrent mark sweep GC freed 15442(886KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 425us total 73.703ms
08-16 11:26:52.770  8287  8287 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 11:26:52.822  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-16 11:26:52.824  1904  1904 D ActionManagerService: notifyUserLog: 1000003
08-16 11:26:52.825  3840  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 11:26:52.830  4499  4499 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 11:26:52.830  4499  4499 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 11:26:52.830  4499  4499 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 11:26:52.830  4499  4499 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 11:26:52.830  4499  4499 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 11:26:52.830  4499  4499 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 11:26:52.830  4499  4499 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 11:26:52.830  4499  4499 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 11:26:52.830  4499  4499 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:26:52.830  4499  4499 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 11:26:52.831  4499  4499 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 11:26:52.831  4499  4499 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 11:26:52.835  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-16 11:26:52.839  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 11:26:52.841  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 11:26:52.842  1601  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 11:26:52.842  1601  1663 D KeyguardModel: createShortcutInfo...
08-16 11:26:52.842  1034  1953 V SIM_STK : Menu title from STK is T-Mobile
08-16 11:26:52.848  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 11:26:52.851  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-16 11:26:52.853  1601  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 11:26:52.853  1601  1663 D KeyguardModel: createShortcutInfo...
08-16 11:26:52.856  2211  2211 I ConfigService: onCreate
08-16 11:26:52.858  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 11:26:52.863  1601  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 11:26:52.863  1601  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 11:26:52.863  1601  1663 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-16 11:26:52.866  2211  2211 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 11:26:52.870  1601  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 11:26:52.872  1601  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 11:26:52.874  1601  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 11:26:52.874  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 11:26:52.874  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 11:26:52.875  2211  2211 I ConfigService: onBind returning update interface
08-16 11:26:52.876  1034  1034 I art     : Explicit concurrent mark sweep GC freed 22719(1392KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.626ms total 167.421ms
,08-16 11:26:52.877  1034  1123 I art     : WaitForGcToComplete blocked for 148.815ms for cause Explicit
08-16 11:26:52.884  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 11:26:52.885  1904  1904 D ActionManagerService: notifyUserLog: 1000004
08-16 11:26:52.885  3840  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 11:26:52.891  1601  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 11:26:52.891  1601  1663 D KeyguardModel: createShortcutInfo...
,08-16 11:26:52.892  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-16 11:26:52.893  1868  1868 D SplitUIService: removed split : 
08-16 11:26:52.894  3840  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 11:26:52.896  1601  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 11:26:52.896  1601  1663 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 11:26:52.898  2211  2211 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 11:26:52.898  2211  2211 I ConfigService: onBind returning config service
08-16 11:26:52.900  1601  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 11:26:52.900  1601  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 11:26:52.903  1601  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 11:26:52.903  1601  1663 D KeyguardModel: createShortcutInfo...
,08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , display: false
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , animation: false }
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , display: false
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , animation: false }
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , display: false
08-16 11:26:52.905  2032  2032 I GBoardWebViewUtils: , animation: false }
08-16 11:26:52.905  2211  2211 I ConfigService: onDestroy
08-16 11:26:52.907  1601  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 11:26:52.907  1601  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 11:26:52.909  1601  1663 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 11:26:52.909  1601  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 11:26:52.914  2032  8922 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-16 11:26:52.914  1601  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 11:26:52.914  1601  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-16 11:26:52.923  1601  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
,08-16 11:26:52.923  1601  1663 D KeyguardModel: createShortcutInfo...
08-16 11:26:52.925  1034  1918 V SIM_STK : Menu title from STK is T-Mobile
08-16 11:26:52.926  1034  1918 V SIM_STK : Menu title from STK is T-Mobile
,08-16 11:26:52.930  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-16 11:26:52.930  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 11:26:52.934  1034  1034 D administrator: Handling package changes for user 0
08-16 11:26:52.937  1601  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 11:26:52.937  1601  1663 D KeyguardModel: createShortcutInfo...
08-16 11:26:52.939  1601  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 11:26:52.939  1601  1663 D KeyguardModel: createShortcutInfo...
,08-16 11:26:52.939  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 11:26:52.939  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 11:26:52.940  1601  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 11:26:52.940  1601  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 11:26:52.941  1601  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 11:26:52.941  1601  1663 D KeyguardModel: createShortcutInfo...
08-16 11:26:52.942  1601  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 11:26:52.942  1601  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 11:26:52.943  1601  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 11:26:52.943  1601  1663 D KeyguardModel: createShortcutInfo...
08-16 11:26:52.945  1601  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 11:26:52.946  1601  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 11:26:52.946  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-16 11:26:52.946  1868  1868 I SplitUIService: split app #11
08-16 11:26:52.948  1601  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 11:26:52.948  1601  1663 D KeyguardModel: createShortcutInfo...
08-16 11:26:52.970  1815  8923 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-16 11:26:52.987  1034  1960 V SIM_STK : Menu title from STK is T-Mobile
,08-16 11:26:53.000  1034  1918 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 11:26:53.001  8039  8039 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 11:26:53.008  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-16 11:26:53.008  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 11:26:53.028  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-16 11:26:53.045  5955  8932 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-16 11:26:53.051  1815  8933 I PeopleContactsSync: CP2 sync disabled
08-16 11:26:53.058  1815  8931 W GmsApplication: Using Auth Proxy for data requests.
,08-16 11:26:53.061  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 11:26:53.061  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 11:26:53.061  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 11:26:53.064  1034  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 11:26:53.065  1815  4754 I Icing   : doRemovePackageData com.test.thalitest
08-16 11:26:53.067  1815  8931 W GmsApplication: Using Auth Proxy for data requests.
08-16 11:26:53.140  7137  7137 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-16 11:26:53.144  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-16 11:26:53.147  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 11:26:53.148  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 11:26:53.149  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 11:26:53.150  2342  8936 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-16 11:26:53.150  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 11:26:53.152  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-16 11:26:53.168  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 11:26:53.168  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 11:26:53.169  2032  2180 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 11:26:53.169  2032  2180 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 11:26:53.183  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-16 11:26:53.183  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 11:26:53.183  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 11:26:53.184  1034  1894 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8938 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 11:26:53.186  1034  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b7c35d6 u0 com.lge.launcher2/.Launcher t5} time:472842
08-16 11:26:53.191  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 11:26:53.194  2578  2578 D [Concierge]Service: onStartCommand(). Type : 8
08-16 11:26:53.194  2578  2578 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-16 11:26:53.195  2578  2578 D [Concierge]Service: Update widget ID : 11
08-16 11:26:53.195  2032  2032 D [Concierge]WidgetView: change position of spinner
08-16 11:26:53.197  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1471339613197
08-16 11:26:53.203  2578  2578 D [Concierge]Service: onStartCommand(). Type : 0
08-16 11:26:53.206  1034  1123 I art     : Explicit concurrent mark sweep GC freed 9314(646KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.919ms total 322.940ms
08-16 11:26:53.207  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 854578427
08-16 11:26:53.207  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 11:26:53.208  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 11:26:53.210  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2b7937ac
08-16 11:26:53.210  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-16 11:26:53.212  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 11:26:53.213  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 11:26:53.218  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 11:26:53.218  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 11:26:53.218  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 11:26:53.219  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471339168525, New one : 1471339613197
08-16 11:26:53.219  2032  2032 D [Concierge]WidgetView: Unregister all receivers
08-16 11:26:53.219  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 11:26:53.220  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 11:26:53.221  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 11:26:53.223  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 11:26:53.225  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 11:26:53.225  8938  8938 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 11:26:53.226  8938  8938 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 11:26:53.226  8938  8938 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 11:26:53.227  8938  8938 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 11:26:53.227  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 11:26:53.229  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 11:26:53.229  1815  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 11:26:53.229  1815  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 11:26:53.229  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 11:26:53.230  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 11:26:53.230  1815  1827 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 11:26:53.234  1815  8935 I art     : Explicit concurrent mark sweep GC freed 44753(2MB) AllocSpace objects, 29(456KB) LOS objects, 51% free, 30MB/62MB, paused 874us total 35.065ms
08-16 11:26:53.261  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 11:26:53.269  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 11:26:53.269  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 11:26:53.270  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 11:26:53.290  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1c0bceb4 time:472946
,08-16 11:26:53.299  8887  8887 D AndroidRuntime: Shutting down VM
08-16 11:26:53.301  8938  8938 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 11:26:53.310  8938  8938 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 11:26:53.330  8938  8938 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 11:26:53.346  1034  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8957 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 11:26:53.383  8938  8938 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:26:53.383  8938  8938 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 11:26:53.409  1034  1987 I ActivityManager: Killing 8216:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 11:26:53.448  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 11:26:53.474  1034  1994 W libprocessgroup: failed to open /acct/uid_10026/pid_8216/cgroup.procs: No such file or directory
,08-16 11:26:53.487  2032  2946 I GBoardtInterface: onReloaded()
,08-16 11:26:53.489  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 11:26:53.490  3840  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 11:26:53.494  3840  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 11:26:53.499  1034  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-16 11:26:53.502  1904  1904 D ActionManagerService: notifyUserLog: 1000001
08-16 11:26:53.504  3840  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 11:26:53.504  3840  4490 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 11:26:53.510  1904  1904 D ActionManagerService: notifyUserLog: 1000001
08-16 11:26:53.512  3840  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 11:26:53.514  3840  4490 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 11:26:53.514  3840  4490 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 11:26:53.514  3840  4490 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 11:26:53.514  3840  4490 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 11:26:53.517  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 11:26:53.517  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 11:26:53.519  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 11:26:53.519  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 11:26:53.522  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 11:26:53.522  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-16 11:26:53.565  8938  8938 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-16 11:26:53.589  1034  1994 I ActivityManager: Killing 8478:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 11:26:53.656  1995  1995 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 11:26:53.656  1995  1995 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...

```
