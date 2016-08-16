#### Test 81418577b7b45c2_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 14:24:34.781  6660  6660 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 14:24:42.647  6765  6765 D AndroidRuntime: 
08-16 14:24:42.647  6765  6765 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 14:24:42.653  6765  6765 D AndroidRuntime: CheckJNI is OFF
08-16 14:24:42.777  6765  6765 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 14:24:42.782  1051  1066 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 14:24:42.790  1982  1998 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 14:24:42.794  1051  1066 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 14:24:42.795  1051  1066 D ActivityManager: setTaskToReturnTo : TaskRecord{160e74d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 14:24:42.796  1051  1066 D ActivityManager: setTaskToReturnTo : TaskRecord{160e74d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 14:24:42.797  1051  1066 D WindowStateEx: AppWindowTokenEx init.. 
08-16 14:24:42.797   329   351 E GBMv2   : DFP En is all cleared set to be enabled
08-16 14:24:42.830  1051  1066 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6780 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 14:24:42.833  6765  6765 D AndroidRuntime: Shutting down VM
08-16 14:24:42.888  1982  1998 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 14:24:42.888  1982  1998 D SplitWindowPolicy: topRunningActivity=ActivityInfo{f3a9420 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 14:24:42.889  1982  2806 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 14:24:42.889  1982  2806 D SplitWindowPolicy: topRunningActivity=ActivityInfo{5d301d9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 14:24:42.956  6780  6780 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-16 14:24:43.050  6780  6780 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 14:24:43.060  6780  6780 I LibraryLoader: Loading: webviewchromium
,08-16 14:24:43.063  6780  6780 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6670-6674)
,08-16 14:24:43.063  6780  6780 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:24:43.079  6780  6780 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d548ece}
08-16 14:24:43.080  6780  6780 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 14:24:43.081  6780  6780 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 14:24:43.091  6780  6780 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 14:24:43.092  6780  6780 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:24:43.103  6780  6780 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 14:24:43.103   314  1402 V AudioPolicyService: registerClient() client 0xb14b7720, uid 10118
08-16 14:24:43.104  6780  6780 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 14:24:43.105  6780  6780 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 14:24:43.108  1051  1115 D BluetoothManagerService: Message: 20
08-16 14:24:43.108  1051  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@527416f:true
08-16 14:24:43.131  6780  6780 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:24:43.131  6780  6780 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:24:43.131  6780  6780 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:24:43.131  6780  6780 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:24:43.131  6780  6780 I Adreno-EGL: Remote Branch: 
08-16 14:24:43.131  6780  6780 I Adreno-EGL: Local Patches: 
08-16 14:24:43.131  6780  6780 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:24:43.233  6780  6821 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 14:24:43.241  6780  6780 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 14:24:43.257  6780  6780 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 14:24:43.262  6780  6780 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 14:24:43.265  6780  6780 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-16 14:24:43.268  6780  6780 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 14:24:43.268  6780  6780 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-16 14:24:43.282  6780  6780 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 14:24:43.293  6780  6780 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:24:43.293  6780  6780 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 14:24:43.329  6780  6833 D OpenGLRenderer: Render dirty regions requested: true
08-16 14:24:43.329  6780  6833 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 14:24:43.345  6780  6833 D OpenGLRenderer: Enabling debug mode 0
,08-16 14:24:43.354  6780  6780 D Atlas   : Validating map...
08-16 14:24:43.361  1051  1066 D SplitWindow: check instance of lgWin Window{314a05f1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 14:24:43.459  6780  6831 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:24:43.459  6780  6831 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:24:43.473  1051  1116 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +586ms (total +675ms)
08-16 14:24:43.474  1051  1116 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f4a2202 u0 com.test.thalitest/.MainActivity t6} time:197085
08-16 14:24:43.475  6780  6780 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@18c53bf5 time:197086
08-16 14:24:43.603  6780  6780 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 14:24:43.603  6780  6780 I chromium: 
,08-16 14:24:43.617  6780  6780 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 14:24:43.683  6780  6831 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 14:24:43.683  6780  6831 I chromium: 
,08-16 14:24:43.833  6780  6844 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
,08-16 14:24:43.850  6780  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 14:24:43.850  6780  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 14:24:43.850  6780  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 14:24:43.850  6780  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 14:24:43.850  6780  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 14:24:43.851  6780  6844 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c7a2ea9 added. We now have 1 listener(s)
,08-16 14:24:43.858  1051  2125 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:24:43.862  6780  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 14:24:43.866  6780  6844 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 14:24:43.870  6780  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:24:43.871  6780  6844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 14:24:43.885  6780  6844 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c30415c added. We now have 1 listener(s)
08-16 14:24:43.886  6780  6844 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:24:43.891  1051  1560 D WifiService: New client listening to asynchronous messages
08-16 14:24:43.895  6780  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:24:43.895  6780  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 14:24:43.897  6780  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 14:24:43.897  6780  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 14:24:43.897  6780  6844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 14:24:43.907  6780  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:24:43.907  1051  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:24:43.909  6780  6844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 14:24:43.924  6780  6844 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 14:24:43.925  6780  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:24:43.925  6780  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:43.925  6780  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:43.925  6780  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:43.925  6780  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:24:43.925  6780  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:43.925  6780  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:24:43.925  6780  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:24:43.926  6780  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 14:24:43.926  6780  6844 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:24:43.930  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:43.932  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:43.933  6780  6844 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 14:24:43.968  6780  6780 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 14:24:44.142   329   354 E GBMv2   : DFP En is all cleared set to be enabled
08-16 14:24:44.142   329   354 E GBMv2   : Set value is all cleared set the max
08-16 14:24:44.142   329   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 14:24:44.598  6780  6850 W jxcore-log: Initializing JXcore engine
08-16 14:24:44.599  6780  6850 W jxcore-log: JXcore engine is ready
,08-16 14:24:44.667  6850  6850 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8348]" dev="sockfs" ino=8348 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 14:24:44.667  6850  6850 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-16 14:24:44.677  6850  6850 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[10687]" dev="sockfs" ino=10687 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 14:24:44.677  6850  6850 W Thread-772: type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 14:24:44.677  6850  6850 W Thread-772: type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[32619]" dev="sockfs" ino=32619 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 14:24:44.706  6780  6850 W jxcore-log: Starting JXcore engine
,08-16 14:24:44.809  6780  6850 W jxcore-log: Platform android
08-16 14:24:44.809  6780  6850 W jxcore-log: 
08-16 14:24:44.809  6780  6850 W jxcore-log: Process ARCH arm
08-16 14:24:44.809  6780  6850 W jxcore-log: 
,08-16 14:24:44.986  6780  6850 I jxcore-log: JXcore Cordova bridge is ready!
08-16 14:24:44.986  6780  6850 I jxcore-log: 
08-16 14:24:44.986  6780  6850 W jxcore-log: JXcore engine is started
,08-16 14:24:44.994  6780  6844 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 14:24:44.998  6780  6780 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 14:24:55.033  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 14:24:55.033  6780  6850 I jxcore-log: 
,08-16 14:24:55.035  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 14:24:55.035  6780  6850 I jxcore-log: 
08-16 14:24:55.039  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:24:55.039  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.039  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.039  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:55.039  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:24:55.039  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.039  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:24:55.039  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:24:55.041  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.044  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 14:24:55.044  6780  6850 I jxcore-log: 
08-16 14:24:55.045  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 14:24:55.045  6780  6850 I jxcore-log: 
,08-16 14:24:55.373  6780  6850 D ExecuteNativeTests: Running unit tests
,08-16 14:24:55.454  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:24:55.454  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 added. We now have 2 listener(s)
,08-16 14:24:55.455  1051  1731 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:24:55.457  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 14:24:55.457  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:24:55.457  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:24:55.457  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:24:55.457  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 added. We now have 2 listener(s)
08-16 14:24:55.457  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:24:55.458  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-16 14:24:55.461  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:24:55.463  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:24:55.463  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.463  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.463  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:55.463  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:24:55.463  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.463  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:24:55.463  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:24:55.465  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.465  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:24:55.467  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.468  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.470  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:24:55.472  6780  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:24:55.472  6780  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:24:55.473  6780  6850 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 14:24:55.474  6780  6850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 14:24:55.474  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:24:55.474  6780  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:24:55.474  6780  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:24:55.474  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:24:55.475  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.475  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.475  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.475  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.476  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:24:55.476  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:24:55.476  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 removed from the list
08-16 14:24:55.476  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.476  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 removed from the list
08-16 14:24:55.476  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.476  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.477  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.477  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.477  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.477  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.477  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:24:55.478  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list,
08-16 14:24:55.479  6780  6850 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 14:24:55.480  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-16 14:24:55.480  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.480  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.480  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.480  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.480  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.480  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
,08-16 14:24:55.480  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.480  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list,
08-16 14:24:55.480  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.480  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.480  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.480  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.480  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.481  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.481  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-16 14:24:55.481  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:24:55.481  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 14:24:55.485  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 14:24:55.486  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.486  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.486  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.486  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.486  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.486  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.486  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.486  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.486  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.486  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.486  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.486  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.486  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.486  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.487  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.487  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.487  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.487  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.488  6780  6850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:24:55.491  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:24:55.493  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:24:55.493  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.493  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.493  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:55.493  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:24:55.493  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.493  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:24:55.493  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:24:55.494  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.494  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:24:55.495  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.496  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.497  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:24:55.497  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:24:55.497  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:24:55.497  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:24:55.497  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:24:55.500  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 14:24:55.500  1051  2071 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:24:55.503  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:24:55.507  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 14:24:55.508  6780  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 14:24:55.509  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:24:55.510  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:24:55.511  6780  6850 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:24:55.511  6780  6850 I io.jxcore.node.ConnectionHelper: start: OK
08-16 14:24:55.513  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.513  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.513  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.513  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.514  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.514  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:24:55.514  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.514  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.514  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.514  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.514  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.515  6780  6850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:24:55.516  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:24:55.518  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:24:55.518  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.518  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.518  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:55.518  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:24:55.518  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.518  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:24:55.518  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:24:55.519  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.519  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:24:55.520  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.521  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.521  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:24:55.521  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:24:55.521  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:24:55.521  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:24:55.521  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:24:55.524  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:24:55.524  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:24:55.525  6780  6850 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:24:55.525  6780  6850 I io.jxcore.node.ConnectionHelper: start: OK
08-16 14:24:55.526  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.526  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.526  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.526  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.526  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.526  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:24:55.526  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.526  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.526  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.526  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.526  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.527  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.527  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.527  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.527  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.528  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.529  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.529  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.529  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.529  6780  6850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:24:55.530  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:24:55.532  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:24:55.532  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.532  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.532  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:55.532  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:24:55.532  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.532  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:24:55.532  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:24:55.533  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.533  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:24:55.534  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.535  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.535  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:24:55.535  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:24:55.535  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:24:55.535  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:24:55.535  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:24:55.606  1051  2072 I art     : Explicit concurrent mark sweep GC freed 27442(1290KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.380ms total 70.237ms
,08-16 14:24:55.610  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:24:55.610  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:24:55.612  6780  6850 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:24:55.612  6780  6850 I io.jxcore.node.ConnectionHelper: start: OK
08-16 14:24:55.612  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.612  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.612  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.613  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.613  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.613  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.613  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.613  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.613  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:24:55.613  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.613  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.613  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.613  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.613  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.615  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.615  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.616  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.616  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.616  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.616  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.616  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.616  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.616  6780  6850 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 14:24:55.617  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.617  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discov,ery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.617  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.617  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.617  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.617  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.617  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.617  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.617  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.617  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.617  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.617  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.617  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.617  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.618  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.618  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.619  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.619  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.619  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.619  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.620  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 14:24:55.620  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.620  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.620  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.620  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.620  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.620  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.620  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.620  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.620  6780  6850 E org.thaliproject.p2p.btconnectorl,ib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.620  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.620  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.620  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.620  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.620  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.627  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.627  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.628  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.628  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.628  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.629  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.630  6780  6850 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 14:24:55.630  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.630  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.630  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.630  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.630  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.630  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.630  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.630  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.631  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.631  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.631  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.631  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.631  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.631  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.632  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.632  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.633  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.633  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.633  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.634  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.634  6780  6850 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 14:24:55.635  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.635  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.635  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.635  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.635  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.635  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.635  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.635  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.635  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.635  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.635  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.635  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.635  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.635  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.636  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.636  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.637  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.637  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.637  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.637  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.638  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:24:55.640  6780  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:24:55.640  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:24:55.640  6780  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:24:55.641  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:24:55.641  6780  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:24:55.641  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.641  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.641  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.641  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.641  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.641  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.641  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.641  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.641  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.641  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.641  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.642  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.642  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.642  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.643  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.643  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.644  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.644  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.644  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.644  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.645  6780  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:24:55.647  6780  6850 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:24:55.648  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:24:55.653  6780  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:24:55.653  6780  6850 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:24:55.654  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 14:24:55.655  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 14:24:55.655  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 14:24:55.655  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:24:55.655  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:24:55.655  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 14:24:55.655  6780  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 14:24:55.655  6780  6850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:24:55.655  6780  6850 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 14:24:55.655  6780  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:24:55.655  6780  6850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:24:55.655  6780  6850 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 14:24:55.655  6780  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:24:55.655  6780  6850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:24:55.655  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 14:24:55.658  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 14:24:55.661  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 14:24:55.661  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 14:24:55.661  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 14:24:55.661  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 14:24:55.662  6780  6850 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 14:24:55.662  6780  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:24:55.662  6780  6850 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 14:24:55.663  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.663  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.663  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.663  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.663  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.663  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.663  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 14:24:55.664  6780  6852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-16 14:24:55.667  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.667  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.667  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.667  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.667  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.667  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.667  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.667  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.668  6780  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-16 14:24:55.668  6780  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-16 14:24:55.668  6780  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
08-16 14:24:55.668  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.668  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.669  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.669  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.669  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.669  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.670  6780  6850 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 14:24:55.670  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.670  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.670  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.671  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.671  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.671  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.671  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.671  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.671  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.671  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.671  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.671  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.671  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.671  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.672  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.672  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.672  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.672  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.673  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.673  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.674  6780  6850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 14:24:55.674  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.675  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.675  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.678  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.678  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.678  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.678  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.678  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.678  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.679  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.679  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.679  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.679  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.679  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.679  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.679  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.680  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.680  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.680  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.680  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.680  6780  6850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 14:24:55.680  6780  6850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 14:24:55.680  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:24:55.680  6780  6850 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 14:24:55.680  6780  6850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:24:55.681  6780  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 14:24:55.681  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:24:55.681  6780  6850 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 14:24:55.681  6780  6850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:24:55.681  6780  6850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:24:55.681  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:24:55.681  6780  6850 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 14:24:55.681  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.681  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.681  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.681  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.681  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.681  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.681  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.681  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.681  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.681  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.681  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.681  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.681  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.681  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.682  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.682  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.685  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.685  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.685  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.685  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.685  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.686  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.686  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.686  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.686  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.686  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.686  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.686  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.686  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.686  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.686  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.686  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.686  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.686  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.686  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.686  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.686  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.686  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.686  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.686  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.686  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.686  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.686  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.686  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.686  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.686  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.686  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.686  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.686  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.687  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.687  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.687  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.687  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.687  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.688  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.689  6780  6850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 14:24:55.689  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:24:55.690  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 14:24:55.690  6780  6850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 14:24:55.690  6780  6850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 14:24:55.691  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 14:24:55.691  6780  6780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 14:24:55.691  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:24:55.691  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.691  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 14:24:55.691  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 14:24:55.691  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 14:24:55.691  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.691  6780  6850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 14:24:55.691  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.692  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.692  6780  6780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 14:24:55.692  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:24:55.692  6780  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:24:55.692  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:24:55.692  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:24:55.693  6780  6854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 14:24:55.693  6780  6854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 14:24:55.698  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:24:55.698  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:24:55.698  6780  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:24:55.699  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.699  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:24:55.702  6780  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:24:55.702  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.702  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.702  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.702  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.702  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.702  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.702  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.702  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.702  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.702  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.702  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.702  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.702  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.702  6780  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:24:55.702  6780  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:24:55.703  6780  6780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 14:24:55.703  6780  6780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:24:55.704  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.704  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.704  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.704  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.704  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.704  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.705  6780  6850 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 14:24:55.706  6780  6850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 14:24:55.706  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:24:55.708  6780  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:24:55.708  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.708  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.708  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.709  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.709  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.709  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.709  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.709  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.709  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.709  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.709  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.709  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.709  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.709  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.710  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.710  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.711  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.711  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.712  1051  2125 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:24:55.713  1051  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:24:55.715  1051  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:24:55.716  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.716  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.716  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.716  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.716  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.716  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.716  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.716  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.716  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.716  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.716  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.716  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.716  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.717  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.718  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.718  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.718  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.718  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.719  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:24:55.719  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:24:55.719  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:24:55.719  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:24:55.719  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.719  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.719  6780  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181c96e7 not in the list
08-16 14:24:55.719  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.719  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.719  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:24:55.720  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.720  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.720  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:24:55.720  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:24:55.721  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:24:55.721  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:24:55.721  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:24:55.721  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d0d294 not in the list
08-16 14:24:55.722  6780  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 14:24:55.722  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:24:55.722  6780  6850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 14:24:55.722  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:24:55.723  6780  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 14:24:55.723  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:24:55.728  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 14:24:55.729  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 14:24:55.731  6780  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 14:24:55.731  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 14:24:55.732  6780  6850 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 14:24:55.732  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 14:24:55.732  6780  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 14:24:55.732  6780  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 14:24:55.734  6780  6850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 14:24:55.734  6780  6850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 14:24:55.742  6780  6850 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-16 14:24:55.742  6780  6850 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 14:24:55.743  6780  6850 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 14:24:55.744  6780  6850 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 14:24:55.745  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:24:55.745  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31d40af5 added. We now have 2 listener(s)
08-16 14:24:55.745  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:24:55.747  6780  6850 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 14:24:55.748  6780  6852 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 14:24:55.749  6780  6852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-16 14:24:55.749  1051  1593 D WifiServiceImplEx: setWifiEnabled: true pid=6780, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 14:24:55.750  1051  1593 D WifiService: setWifiEnabled: true pid=6780, uid=10118
08-16 14:24:55.750  1051  1593 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 14:24:55.752  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:24:55.752  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11d808a added. We now have 3 listener(s)
08-16 14:24:55.752  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:24:55.756  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:24:55.756  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b75f6fb added. We now have 4 listener(s)
08-16 14:24:55.756  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:24:55.759  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:24:55.759  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@339cd318 added. We now have 5 listener(s)
08-16 14:24:55.759  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:24:55.761  1051  2072 D WifiServiceImplEx: setWifiEnabled: false pid=6780, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 14:24:55.761  1051  2072 D WifiService: setWifiEnabled: false pid=6780, uid=10118
08-16 14:24:55.761  1051  2072 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:24:55.774  1051  1051 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 14:24:55.775  1051  1051 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:24:55.775  1051  1051 D Ulp_jni : JNI:system_update. Event-4
08-16 14:24:55.775  1051  1555 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 14:24:55.775  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 14:24:55.776  1051  1555 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-16 14:24:55.776  1051  1555 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 14:24:55.777  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 14:24:55.777  1051  1555 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 14:24:55.777  1051  1555 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:24:55.777  1051  1555 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:24:55.777  1051  1555 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:24:55.777  1051  1555 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:24:55.778  1051  2071 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:24:55.778  1051  2071 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1de163f8 mBinding = false
08-16 14:24:55.787  1051  1555 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 14:24:55.787  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:24:55.787  2748  2748 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:24:55.787  1051  1553 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.787  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.788  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:24:55.788  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 14:24:55.789  1051  1555 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:24:55.790  1051  1115 D BluetoothManagerService: Message: 2
08-16 14:24:55.791  1051  1051 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:24:55.792  1051  1115 D BluetoothManagerService: Sending off request.
08-16 14:24:55.792  1051  1051 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:24:55.792  1051  1051 D Ulp_jni : JNI:system_update. Event-4
08-16 14:24:55.792  3887  6851 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 14:24:55.792  1051  2878 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.793  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:24:55.793   310   910 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:24:55.793  3887  3972 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 14:24:55.793  3887  3972 D BluetoothAdapterProperties: Setting state to 13
08-16 14:24:55.794  3887  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 14:24:55.794  3887  3972 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 14:24:55.794  1051  1115 D BluetoothManagerService: Message: 60
08-16 14:24:55.794  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 14:24:55.794  3887  3972 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 14:24:55.794  1051  1115 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 14:24:55.798  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.798  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:24:55.798  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.798  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.798  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:55.798  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:24:55.798  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.798  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:24:55.798  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:24:55.802  1982  1982 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:55.803  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:24:55.805  3887  3887 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:55.805  3887  3887 D BluetoothMapService: STATE_TURNING_OFF
08-16 14:24:55.806  3887  3887 V BluetoothMapService: Handler(): got msg=4
08-16 14:24:55.806  3887  3887 D BluetoothMapService: MAP Service closeService in
08-16 14:24:55.806  3887  3887 D BluetoothMapMasInstance: MAP Service shutdown
,08-16 14:24:55.810  3887  4252 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 14:24:55.810  3887  4252 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:24:55.810  3887  4252 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 14:24:55.810  3887  4252 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 14:24:55.810  3887  4252 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 14:24:55.810  3887  4252 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 14:24:55.810  3887  4252 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 14:24:55.810  3887  4252 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 14:24:55.811  3887  3887 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:24:55.811  3887  3887 V BluetoothMapService: MAP Service closeService out
08-16 14:24:55.811  3887  3887 V BtOppService: Receiver DISABLED_ACTION 
08-16 14:24:55.812  3887  3887 I BtOppRfcommListener: stopping Accept Thread
08-16 14:24:55.812  3887  3887 V BtOppRfcommListener: close mBtServerSocket
08-16 14:24:55.812  3887  4310 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:24:55.813  3887  4310 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 14:24:55.814  3887  3887 V BtOppRfcommListener: waiting for thread to terminate
08-16 14:24:55.814  3887  3887 V BtOppRfcommListener: done waiting for thread to terminate
08-16 14:24:55.815  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.815  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:24:55.816  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:24:55.847  1051  1561 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 14:24:55.847  1051  1561 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-16 14:24:55.853  1051  1108 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6863 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 14:24:55.858  3887  3977 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:24:55.859  3887  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 14:24:55.860  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 14:24:55.860  3887  4080 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 14:24:55.860  3887  3972 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 14:24:55.861  3887  4256 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:24:55.863  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.863  3887  3887 V BtOppService: onDestroy
08-16 14:24:55.863  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:24:55.863  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.863  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.863  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:55.863  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:24:55.863  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:24:55.863  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:24:55.863  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:24:55.863  3887  4315 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:24:55.864  3887  4312 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:24:55.865  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:24:55.865  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:24:55.865  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:24:55.865  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:24:55.865  3887  4080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:24:55.865  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:24:55.866  3887  4080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:24:55.866  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:24:55.866  3887  4080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:24:55.866  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 14:24:55.866  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 14:24:55.866  3887  4080 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 14:24:55.866  1051  1051 D WifiHS20: hidePasspointNotification off =false
,08-16 14:24:55.870  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.870  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:24:55.872  1051  1986 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-16 14:24:55.872  1051  2877 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.872  1051  2877 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.872  1051  2877 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 14:24:55.872  1051  2877 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.872  1051  2877 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 14:24:55.879  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.879  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:24:55.879  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.879  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.879  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:55.879  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:24:55.879  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:24:55.879  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:24:55.879  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:24:55.884  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.884  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:24:55.884  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.884  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.884  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:55.884  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:24:55.884  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:24:55.884  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:24:55.884  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:24:55.885  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.885  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:24:55.891  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:55.891  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:55.891  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-16 14:24:55.892  1982  1982 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 14:24:55.894  1051  1561 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 14:24:55.894  1051  1561 D DSQN    : disableDataServiceNotify
08-16 14:24:55.894  1051  1561 D DSQN    : stop dsqn bin
08-16 14:24:55.894   310  6888 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 14:24:55.895  1051  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 14:24:55.895  1051  1051 D WifiHS20: hidePasspointNotification off =false
08-16 14:24:55.895  1051  2877 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 14:24:55.895  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:55.895  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:55.895  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:24:55.896  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.897  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.899  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:55.901  1051  1561 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 14:24:55.901  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:24:55.901  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:24:55.902  1051  1561 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:24:55.902  1051  1561 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 14:24:55.902  1051  2877 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.902  1051  2877 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.902  1051  2877 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 14:24:55.902  1619  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 14:24:55.903  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:24:55.903  1051  1561 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 14:24:55.903  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:24:,55.903  1051  1561 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 14:24:55.903  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 14:24:55.904  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:24:55.906  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:24:55.906  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:24:55.909  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:24:55.930  1051  1108 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6891 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-16 14:24:55.931  1051  1561 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:24:55.931  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:24:55.931  3887  3887 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 14:24:55.932  1051  1555 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 14:24:55.932  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:24:55.932  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:24:55.932  1051  1553 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.933  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.933  1051  1553 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3b6381c
08-16 14:24:55.933  1051  1555 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:24:55.933  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:24:55.934  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:24:55.934  1051  1555 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 14:24:55.934  1051  1555 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:24:55.935  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:24:55.935  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:24:55.937  1051  1561 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:24:55.937  1051  1561 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:24:55.937  1051  1051 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 14:24:55.937  1051  1561 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:24:55.937  1051  1051 D RttService: SCAN_AVAILABLE : 1
08-16 14:24:55.937  1051  1561 D NetworkManagementService: Removing idletimer
08-16 14:24:55.938  1051  1561 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:55.938  1051  1572 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.938  1893  1893 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:24:55.938  1051  1561 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 14:24:55.938  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:24:55.939  1051  1553 D LGWifiP2pService: P2pDisablingState
08-16 14:24:55.939  1051  1552 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 14:24:55.939  1051  1552 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 14:24:55.939  1051  1553 D LGWifiP2pService: P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.939  1051  1051 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 14:24:55.939  1051  1573 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.939  1051  1051 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 14:24:55.939  1051  1051 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:24:55.939  1051  1051 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:24:55.939  1051  1051 D LocSv,c_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:24:55.939  1051  1051 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:24:55.939  1051  1051 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:24:55.939  1051  1051 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:24:55.940  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 14:24:55.940  1051  1553 D LGWifiP2pService: p2p socket connection lost
08-16 14:24:55.940  1982  1982 D WfdsService: WifiP2pState is changed : false
08-16 14:24:55.940  1051  1553 D LGWifiP2pService: P2pDisabledState
08-16 14:24:55.940  1982  2375 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 14:24:55.940  1982  2375 D WfdsService: Set the WFDS Monitor: false
08-16 14:24:55.940  1051  1555 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:24:55.940  1051  1555 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:24:55.941  1982  2375 D WfdsMonitor: WFDS Monitor is stopped
08-16 14:24:55.941  1982  2375 D WfdsService: STATE : WfdsDisabledState - enter
08-16 14:24:55.942  1982  2792 D CtrlSupplicant: Received on exit socket, terminate
08-16 14:24:55.942  1982  2792 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 14:24:55.942  1982  2792 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 14:24:55.942  1982  2376 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 14:24:55.942  1982  2792 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 14:24:55.943  1982  2375 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 14:24:55.943  1051  1555 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-16 14:24:55.945  1051  1553 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.945  1051  1553 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:55.946  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:24:55.946  2748  2748 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:24:55.946  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:24:55.946  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:24:55.946  1051  1555 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:24:55.947   310   910 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:24:55.949  1051  1555 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 14:24:55.950  1051  1555 D WifiNative-p2p0: TERMINATE: returned true
08-16 14:24:55.950  1051  1051 D WifiHS20: hidePasspointNotification off =false
08-16 14:24:55.950  1051  1555 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:24:55.950  1051  1555 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:24:55.950  1051  1555 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 14:24:55.951  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:55.951  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:55.951  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:24:55.953  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 14:24:55.953  1051  1051 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 14:24:55.954  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:24:55.954  1051  1051 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 14:24:55.956  6863  6863 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:24:55.957  6863  6863 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 14:24:55.957  6863  6863 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:24:55.957  6863  6863 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 14:24:55.959  6863  6863 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 14:24:55.960  6863  6863 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 14:24:55.963  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.963  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:24:55.963  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.963  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.963  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:24:55.963  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:24:55.963  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:24:55.963  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:24:55.963  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:24:55.963  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.963  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:24:55.966  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.966  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:24:55.966  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:55.966  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:55.966  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:24:55.966  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:24:55.966  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:24:55.966  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:24:55.966  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:24:55.966  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:55.966  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:24:55.984  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:24:55.986  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:24:55.986  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:24:56.001  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:24:56.002  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:24:56.002  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:24:56.002  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 14:24:56.002  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:24:56.003  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:24:56.021  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:24:56.039  2748  2748 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 14:24:56.039  2748  2748 I wpa_supplicant: monitor socket send errors count : 1
08-16 14:24:56.039  2748  2748 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1982-2\x00 that cannot receive messages
08-16 14:24:56.040  1051  2788 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 14:24:56.040  1051  2788 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-16 14:24:56.048  6891  6891 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 14:24:56.049  6891  6891 W LG Account v2.2: No ProfileInfo entries
08-16 14:24:56.049  6891  6891 I LG Account v2.2: isEnabled: false
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]Country: EU
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]Operator: OPEN
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]Ranking support: false
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]Comfort support: false
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]Accessory: true
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]Health device: true
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]Extra Pedometer: false
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]Blood glucose device: false
08-16 14:24:56.049  6891  6891 I Feature : [Lifetracker]Device Number: 3
08-16 14:24:56.055  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:24:56.074  1051  2878 D DhcpStateMachine: StoppedState
08-16 14:24:56.074  1051  2878 D DhcpStateMachine: StoppedState{ when=-128ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:24:56.077  2748  2748 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:24:56.077  2748  2748 W wpa_supplicant: USIM:  scard_deinit function
08-16 14:24:56.077  1051  2788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 14:24:56.077  1051  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:24:56.078  1051  2788 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:24:56.078  1051  1115 D Tethering: InitialState.processMessage what=4
08-16 14:24:56.079  1051  2788 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 14:24:56.079  1051  2788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:24:56.079  1051  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:24:56.079  1051  1555 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=209677
08-16 14:24:56.080  1051  1555 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=209678
08-16 14:24:56.080  1051  1555 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=209678  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 14:24:56.081  1051  1555 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=209679  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 14:24:56.082  1051  2072 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6912 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 14:24:56.082  1051  2072 I ActivityManager: Killing 5970:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-16 14:24:56.110  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 14:24:56.119  1051  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 14:24:56.119  1051  1734 W libprocessgroup: failed to open /acct/uid_10014/pid_5970/cgroup.procs: No such file or directory
08-16 14:24:56.120  1051  1555 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 14:24:56.120  1051  1555 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 14:24:56.124  1051  1555 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:24:56.125  1051  1555 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 14:24:56.126  3887  3887 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:24:56.126  3887  3887 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:56.126  3887  3887 V BluetoothPbapReceiver: ***********state = 13
08-16 14:24:56.128  3887  3887 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 14:24:56.129  3887  3887 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:56.129  3887  3887 V BluetoothPbapService: state: 13
08-16 14:24:56.130  3887  3887 V BluetoothPbapService: Pbap Service closeService in
08-16 14:24:56.131  2258  2258 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:24:56.131  3887  3887 V BluetoothPbapService: successfully stopped pbap service
08-16 14:24:56.131  3887  3887 V BluetoothPbapService: Pbap Service closeService out
08-16 14:24:56.131  3887  3887 V BluetoothPbapService: Pbap Service onDestroy
08-16 14:24:56.131  3887  3887 V BluetoothPbapService: Pbap Service closeService in
08-16 14:24:56.131  3887  3887 V BluetoothPbapService: Pbap Service closeService out
08-16 14:24:56.132  3887  3887 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 14:24:56.135  1051  1115 D BluetoothManagerService: Message: 20
08-16 14:24:56.136  1051  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d5bed3:true
,08-16 14:24:56.149  2748  2748 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 14:24:56.149  1051  2788 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 14:24:56.150  1051  2788 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 14:24:56.150  1051  2788 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 14:24:56.150  1051  1555 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-16 14:24:56.152  1051  1115 D BluetoothManagerService: Message: 30
08-16 14:24:56.156  1051  1115 D BluetoothManagerService: Message: 30
08-16 14:24:56.158  6863  6863 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 14:24:56.159  6863  6863 D BluetoothMap: Create BluetoothMap proxy object
08-16 14:24:56.159  1051  1115 D BluetoothManagerService: Message: 30
08-16 14:24:56.162  1051  1115 D BluetoothManagerService: Message: 30
,08-16 14:24:56.164  6863  6863 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 14:24:56.165  6863  6863 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 14:24:56.173  6912  6912 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 14:24:56.178  6912  6912 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:24:56.178  6863  6863 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-16 14:24:56.186  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-16 14:24:56.187  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:24:56.189  1051  2072 I ActivityManager: Killing 6342:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-16 14:24:56.203  6780  6780 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:24:56.235  1051  2125 W libprocessgroup: failed to open /acct/uid_10004/pid_6342/cgroup.procs: No such file or directory
,08-16 14:24:56.253  1051  1555 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 14:24:56.254  1051  1555 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:24:56.254  1051  1555 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:24:56.254  1051  1555 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 14:24:56.254  1982  1982 D WfdsService: Supplicant Connection state is changed : false
08-16 14:24:56.254  1982  2375 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-16 14:24:56.254  1982  2375 D WfdsService: Set the WFDS Monitor: false
08-16 14:24:56.255  1982  2375 D WfdsMonitor: WFDS Monitor is stopped
08-16 14:24:56.258  6863  6863 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:24:56.262  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:24:56.263  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 14:24:56.265  2516  2516 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:56.273  1051  1051 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 14:24:56.273  1051  1559 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 14:24:56.273  1051  1559 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 14:24:56.277  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:24:56.280  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:56.287  6863  6863 D BluetoothInputDevice: Proxy object connected
08-16 14:24:56.289  6863  6863 D HidProfile: Bluetooth service connected
08-16 14:24:56.290  6863  6863 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:24:56.291  6863  6863 D PanProfile: Bluetooth service connected
,08-16 14:24:56.293  6863  6863 D BluetoothMap: Proxy object connected
08-16 14:24:56.294  6863  6863 D MapProfile: Bluetooth service connected
08-16 14:24:56.295  6863  6863 D BluetoothMap: getConnectedDevices()
08-16 14:24:56.296  6863  6863 D BluetoothMap: Bluetooth is Not enabled
08-16 14:24:56.316  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:24:56.355  6863  6863 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 14:24:56.355  6863  6863 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:24:56.367  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 14:24:56.369  6863  6863 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 14:24:56.376  6863  6863 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 14:24:56.382  6863  6863 D BluetoothPermissionRequest: onReceive
,08-16 14:24:56.385  6863  6863 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 14:24:56.400  1051  1066 I ActivityManager: Killing 6517:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-16 14:24:56.402  6863  6863 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 14:24:56.463  1051  1964 W libprocessgroup: failed to open /acct/uid_10008/pid_6517/cgroup.procs: No such file or directory
,08-16 14:24:56.464  3887  3887 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-16 14:24:56.464  3887  3887 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 14:24:56.466  3887  3887 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 14:24:56.478  3887  3887 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:56.478  3887  3887 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 14:24:56.481  3887  3887 V BluetoothFtpService: Ftp Service onStartCommand
,08-16 14:24:56.481  3887  3887 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:56.481  3887  3887 V BluetoothFtpService: Ftp Service closeService
08-16 14:24:56.481  3887  3887 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 14:24:56.528  1051  1726 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6940 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 14:24:56.529  3887  3887 V BluetoothFtpService: successfully stopped ftp service
08-16 14:24:56.529  3887  3887 V BluetoothFtpService: Ftp Service onDestroy
08-16 14:24:56.529  3887  3887 V BluetoothFtpService: Ftp Service closeService
08-16 14:24:56.535  3887  3887 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:24:56.535  3887  3887 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:24:56.535  3887  3887 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:24:56.536  3887  3887 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:56.536  3887  3887 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 14:24:56.536  3887  3887 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 14:24:56.538  3887  3887 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:56.538  3887  3887 V BluetoothSapService: state: 13
08-16 14:24:56.538  3887  3887 V BluetoothSapService: Stopping SAP server process
08-16 14:24:56.539  3887  3887 V BluetoothSapService: Sap Service closeSapService in
08-16 14:24:56.540  3887  3887 V BluetoothSapService: Close listen Socket : 
08-16 14:24:56.540  3887  3887 V BluetoothSapService: Close rfcomm Socket : 
08-16 14:24:56.540  3887  3887 V BluetoothSapService: Close sapd  Socket : 
08-16 14:24:56.541  3887  3887 V BluetoothSapService: Sap Service closeSapService out
08-16 14:24:56.541  3887  3887 V BluetoothSapService: Sap Service onDestroy
08-16 14:24:56.541  3887  3887 V BluetoothSapService: Sap Service closeSapService in
08-16 14:24:56.541  3887  3887 V BluetoothSapService: Close listen Socket : 
08-16 14:24:56.541  3887  3887 V BluetoothSapService: Close rfcomm Socket : 
08-16 14:24:56.542  3887  3887 V BluetoothSapService: Close sapd  Socket : 
08-16 14:24:56.542  3887  3887 V BluetoothSapService: Sap Service closeSapService out
08-16 14:24:56.549   333   333 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 19.338ms
08-16 14:24:56.566   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 300us total 15.783ms
,08-16 14:24:56.581   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 13.602ms,
,08-16 14:24:56.618  1051  1726 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6960 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 14:24:56.643  6940  6940 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:24:56.659  6940  6940 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 14:24:56.679  6960  6960 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:24:56.689  1051  1593 I ActivityManager: Killing 6087:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-16 14:24:56.700  6940  6940 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-16 14:24:56.700  6940  6940 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-16 14:24:56.700  6940  6940 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 14:24:56.701  6940  6940 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 14:24:56.701  6940  6940 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 14:24:56.703  6940  6940 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 14:24:56.708  6940  6940 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 14:24:56.720  1051  2072 W libprocessgroup: failed to open /acct/uid_10011/pid_6087/cgroup.procs: No such file or directory
,08-16 14:24:56.728  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:24:56.731  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:24:56.753  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 14:24:56.757  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:24:56.759  6940  6940 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 14:24:56.762  6912  6912 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 14:24:56.762  6940  6940 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 14:24:56.762  6912  6912 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:24:56.762  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:24:56.768  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:24:56.779  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:24:56.788  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:24:56.789  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:24:56.792  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:24:56.796  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:24:56.801  6912  6912 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 14:24:56.801  6912  6912 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:24:56.801  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:24:56.806  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:24:56.815  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:24:56.825  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:24:56.825  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:24:56.827  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 14:24:56.868  3887  3977 D bt_hci_bdroid: cleanup,
08-16 14:24:56.868  3887  4082 I bt_lpm  : LPM is already off!!!
08-16 14:24:56.870  3887  4244 I bt_userial_mct: exiting userial_read_thread
08-16 14:24:56.870  3887  4244 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-16 14:24:56.872  3887  4080 W bt-btif : ag scb idx 1 not allocated
,08-16 14:24:56.872  3887  4080 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 14:24:56.872  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:24:56.872  3887  4080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:24:56.872  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:24:56.873  3887  4080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:24:56.873  3887  4080 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 14:24:56.872  3887  3977 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 14:24:56.875  3887  4082 I bt_vendor: hw_epilog_process
08-16 14:24:56.876  3887  3977 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 14:24:56.876  3887  3977 D bt_userial_mct: userial_close
08-16 14:24:56.876  3887  3977 E bt_userial_mct: pthread_join() FAILED result:3
08-16 14:24:56.877  3887  3977 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 14:24:56.894  1051  1067 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6981 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 14:24:56.929  3887  3977 D bt_hci_bdroid: set_power 0
,08-16 14:24:56.929  3887  3977 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 14:24:56.929  3887  3977 I bt_vendor: bluetooth satus is on
08-16 14:24:56.929  3887  3977 I bt_vendor: bt-vendor : resetting BT status
08-16 14:24:56.929  3887  3977 I bt_vendor: Starting hciattach daemon
08-16 14:24:56.929  3887  3977 I bt_vendor: try to set false
08-16 14:24:56.930  3887  3977 I bt_vendor: Starting hciattach daemon
08-16 14:24:56.930  3887  3977 I bt_vendor: try to set false
08-16 14:24:56.931  3887  3977 I bt_vendor: cleanup
08-16 14:24:56.931  3887  4080 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 14:24:56.932  3887  3977 I GKI_LINUX: GKI_exit_task 0 done
08-16 14:24:56.932  3887  3977 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 14:24:56.934  3887  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 14:24:56.937  3887  3887 D HeadsetService: Received stop request...Stopping profile...
08-16 14:24:56.939  3887  4002 D HeadsetStateMachine: Exit Disconnected: -1
08-16 14:24:56.941  3887  3887 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 14:24:56.941  3887  3887 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:24:56.941  3887  3972 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 14:24:56.942  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d7c1ef
08-16 14:24:56.943  1051  1051 D BluetoothHeadset: Proxy object disconnected
08-16 14:24:56.943  1051  1051 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 14:24:56.945  1893  1893 D BluetoothHeadset: Proxy object disconnected
08-16 14:24:56.945  1893  1893 D BluetoothHeadset: Proxy object disconnected
08-16 14:24:56.945  1893  1893 D BluetoothHeadset: Proxy object disconnected
08-16 14:24:56.947  3887  3887 D A2dpService: Received stop request...Stopping profile...
08-16 14:24:56.947  3887  4058 D A2dpStateMachine: Exit Disconnected: -1
08-16 14:24:56.948  3887  3887 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 14:24:56.949  3887  3887 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 14:24:56.949  3887  3887 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:24:56.949  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d7c1ef
08-16 14:24:56.950  1051  1051 D BluetoothA2dp: Proxy object disconnected
08-16 14:24:56.950  1051  1051 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 14:24:56.951  3887  3887 D HidService: Received stop request...Stopping profile...
08-16 14:24:56.951  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d7c1ef
08-16 14:24:56.952  6863  6863 D BluetoothInputDevice: Proxy object disconnected
08-16 14:24:56.952  6863  6863 D HidProfile: Bluetooth service disconnected
08-16 14:24:56.953  3887  3887 D HealthService: Received stop request...Stopping profile...
08-16 14:24:56.953  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d7c1ef
08-16 14:24:56.954  3887  3887 D PanService: Received stop request...Stopping profile...
08-16 14:24:56.956  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d7c1ef
08-16 14:24:56.957  6863  6863 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 14:24:56.957  6863  6863 D PanProfile: Bluetooth service disconnected
08-16 14:24:56.957  3887  3887 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 14:24:56.958  3887  3887 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 14:24:56.959  3887  3887 D BtGatt.GattService: stop()
08-16 14:24:56.959  3887  3887 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 14:24:56.960  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d7c1ef
08-16 14:24:56.964  3887  3887 D BluetoothMapService: Received stop request...Stopping profile...
08-16 14:24:56.964  3887  3887 D BluetoothMapService: stop()
08-16 14:24:56.965  3887  3887 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 14:24:56.965  3887  3887 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 14:24:56.966  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31d7c1ef
08-16 14:24:56.967  3887  3887 D HeadsetStateMachine: Unbinding service...
08-16 14:24:56.969  3887  3887 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:24:56.969  3887  3887 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:24:56.969  3887  3887 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:24:56.969  6863  6863 D BluetoothMap: Proxy object disconnected
08-16 14:24:56.969  6863  6863 D MapProfile: Bluetooth service disconnected
08-16 14:24:56.969  3887  3887 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:24:56.969  3887  3887 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 14:24:56.969  3887  3887 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:24:56.969  3887  3887 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 14:24:56.969  3887  3887 I BluetoothA2dpServiceJni: cleanupNative
08-16 14:24:56.970  3887  4060 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-16 14:24:56.972  3887  3887 I GKI_LINUX: GKI_exit_task 2 done
08-16 14:24:56.972  3887  3887 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 14:24:56.972  3887  3887 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 14:24:56.972  3887  3887 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 14:24:56.972  3887  3887 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 14:24:56.972  3887  3887 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:24:56.973  3887  3887 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:24:56.973  3887  3887 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:24:56.973  3887  3887 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 14:24:56.974  3887  3887 V BluetoothMapService: Handler(): got msg=4
08-16 14:24:56.974  3887  3887 D BluetoothMapService: MAP Service closeService in
08-16 14:24:56.974  3887  3887 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:24:56.974  3887  3887 V BluetoothMapService: MAP Service closeService out
08-16 14:24:56.974  3887  3887 D BluetoothMapService: cleanup()
08-16 14:24:56.974  3887  3887 D BluetoothMapService: MAP Service closeService in
08-16 14:24:56.974  3887  3887 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:24:56.974  3887  3887 V BluetoothMapService: MAP Service closeService out
08-16 14:24:56.974  3887  3972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 14:24:56.975  3887  3972 D BluetoothAdapterProperties: Setting state to 10
08-16 14:24:56.975  3887  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 14:24:56.975  1051  1115 D BluetoothManagerService: Message: 60
08-16 14:24:56.975  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 14:24:56.975  1051  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 14:24:56.976  3887  3972 I BluetoothAdapterState: Entering OffState
08-16 14:24:56.976  6863  6889 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:24:56.976  6863  6890 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:24:56.977  6863  6889 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:24:56.977  1051  1115 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:24:56.978  1893  1909 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:24:56.978  6863  6890 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:24:56.979  1051  1115 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:24:56.979  1893  2549 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:24:56.980  1893  1908 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:24:56.981  1051  1115 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 14:24:56.981  1051  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-16 14:24:56.986  1051  1115 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 14:24:56.986  1051  1115 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 14:24:56.986  1051  1115 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1de163f8 mBinding = false
08-16 14:24:56.987  1051  1115 D BluetoothManagerService: Sending unbind request.
08-16 14:24:56.988  1051  1115 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 14:24:56.992  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:56.993  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:56.994  1982  1982 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:56.994  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:24:56.996  1982  2193 D LGBluetoothAPIService: Message: 2
08-16 14:24:56.996  1982  2193 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@c3e179e mBinding = false
08-16 14:24:56.997  1982  2193 D LGBluetoothAPIService: Sending unbind request.
,08-16 14:24:56.999  6863  6863 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 14:24:57.000  6863  6863 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 14:24:57.000  6863  6863 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 14:24:57.001  3887  3977 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 14:24:57.001  3887  3887 I GKI_LINUX: GKI_exit_task 1 done
08-16 14:24:57.001  3887  3887 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 14:24:57.001  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 14:24:57.002  3887  3887 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 14:24:57.002  3887  3887 I art     : --- WEIRD: removing null entry 246
08-16 14:24:57.002  3887  3887 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 14:24:57.002  3887  3887 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 14:24:57.004  3887  3887 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 14:24:57.007  3887  3887 I art     : System.exit called, status: 0
08-16 14:24:57.007  3887  3887 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 14:24:57.009  1619  1619 D BluetoothAdapter: 557169025: getState() :  mService = null. Returning STATE_OFF
08-16 14:24:57.009  1619  1619 D BluetoothAdapter: 557169025: getState() :  mService = null. Returning STATE_OFF
,08-16 14:24:57.014  6863  6863 D DockEventReceiver: finishStartingService: stopping service
08-16 14:24:57.027  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:24:57.030  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:24:57.032   314  4012 V AudioFlinger: 3887 died, releasing its sessions
08-16 14:24:57.032   314  4012 V AudioFlinger:  pid 1893 @ 0
08-16 14:24:57.032   314  4012 V AudioFlinger:  pid 3487 @ 1
08-16 14:24:57.032   314  4012 V AudioFlinger:  pid 3487 @ 2
08-16 14:24:57.037  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:24:57.037  6863  6863 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 14:24:57.059  1051  1593 I ActivityManager: Process com.android.bluetooth (pid 3887) has died
,08-16 14:24:57.059  1051  1593 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-16 14:24:57.068  2258  2258 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:24:57.076  6981  7006 W FormManager: Network not available. Please check & try again.
,08-16 14:24:57.091  6863  6863 D BluetoothPermissionRequest: onReceive
,08-16 14:24:57.096  6863  6863 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 14:24:57.097  6863  6863 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 14:24:57.099  6981  7007 V FormManager: Network unavailable.
,08-16 14:24:57.102  6863  6863 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:24:57.152  1051  2127 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7010 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 14:24:57.163  6981  7007 V FormManager: Network unavailable.
08-16 14:24:57.171  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 14:24:57.172  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:24:57.172  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:24:57.172  6863  6863 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:24:57.173  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:24:57.192  6863  6863 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:24:57.192  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 14:24:57.192  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:24:57.192  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-16 14:24:57.192  6863  6863 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:24:57.193  6863  6863 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 14:24:57.194  1051  2072 I ActivityManager: Killing 6109:com.android.contacts/u0a19 (adj 15): empty #17
08-16 14:24:57.295  1051  2028 W libprocessgroup: failed to open /acct/uid_10019/pid_6109/cgroup.procs: No such file or directory
,08-16 14:24:57.300  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:24:57.301  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:24:57.306  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:24:57.320  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:24:57.332  4317  7029 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:24:57.338  6912  6912 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 14:24:57.338  6912  6912 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:24:57.338  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:24:57.340  4317  7030 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 14:24:57.341  4317  7030 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:24:57.343  7010  7010 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 14:24:57.343  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:24:57.344  7010  7010 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:24:57.345  7010  7010 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 14:24:57.347  7010  7010 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 14:24:57.351  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:24:57.358  6981  7032 W FormManager: Network not available. Please check & try again.
,08-16 14:24:57.364  6981  7033 V FormManager: Network unavailable.
08-16 14:24:57.368  7010  7010 D BluetoothAdapterApp: Loading JNI Library
08-16 14:24:57.369  6981  7033 V FormManager: Network unavailable.
08-16 14:24:57.370  6940  6940 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 14:24:57.371  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-16 14:24:57.372  6940  6940 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 14:24:57.404  7010  7010 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1842fd64 Instance Count = 1
,08-16 14:24:57.410  7010  7010 D BluetoothAdapterApp: onCreate
08-16 14:24:57.410  6940  6940 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:24:57.410  6940  6940 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:24:57.419  6940  6940 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-16 14:24:57.420  6940  6940 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 14:24:57.420  6940  6940 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 14:24:57.420  6940  6940 V SoundPool: doLoad: loading sample sampleID=1
08-16 14:24:57.421  6940  6940 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 14:24:57.424  6940  7036 V SoundPool: Start decode
08-16 14:24:57.424  6940  7036 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 14:24:57.424   314  4012 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 14:24:57.424   314  4012 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 14:24:57.425   314  4012 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 14:24:57.425   314  4012 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 14:24:57.425   314  4012 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 14:24:57.425   314  4012 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 14:24:57.425   314  4012 V MediaPlayerService: player type = 3
08-16 14:24:57.425   314  4012 V AwesomePlayer: AwesomePlayer create()
08-16 14:24:57.425   314  4012 V AwesomePlayer: reset_l() 
08-16 14:24:57.425   314  4012 V AwesomePlayer: cancelPlayerEvents
08-16 14:24:57.425  6682  6682 D UEI.SmartControl: QS Service created
08-16 14:24:57.425   314  4012 V AwesomePlayer: setAudioSink() 
08-16 14:24:57.425   314  4012 V AwesomePlayer: reset_l() 
08-16 14:24:57.425   314  4012 V AudioCache: notify(0xb0409640, 8, 0, 0)
08-16 14:24:57.425   314  4012 V AudioCache: ignored
08-16 14:24:57.425   314  4012 V AwesomePlayer: cancelPlayerEvents
08-16 14:24:57.425   314  4012 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 14:24:57.425   314  4012 V AwesomePlayer: setDataSource_l dataSource
08-16 14:24:57.425   314  4012 V LGParserOSAL: SniffLGParser start
08-16 14:24:57.425   314  4012 V LGParserOSAL: MainType:5, SubType=0
08-16 14:24:57.425   314  4012 V LGParserOSAL: #### check Mime : application/ogg
08-16 14:24:57.426   314  4012 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 14:24:57.426   314  4012 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 14:24:57.430  6940  6940 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 14:24:57.439  6940  6940 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-16 14:24:57.439  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 14:24:57.454  6940  6940 V LGMDMManager: Create singleton instance
,08-16 14:24:57.461  6682  6682 I UEI.SmartControl: Service initServices...
08-16 14:24:57.461  6682  6682 D UEI.SmartControl: QS start get config
08-16 14:24:57.464  7010  7010 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 14:24:57.464  7010  7010 D ProfileConfigQcom: Adding HeadsetService
08-16 14:24:57.465  7010  7010 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 14:24:57.466  7010  7010 D ProfileConfigQcom: Adding A2dpService
08-16 14:24:57.466  7010  7010 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 14:24:57.467  7010  7010 D ProfileConfigQcom: Adding HidService
08-16 14:24:57.468  7010  7010 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 14:24:57.468  7010  7010 D ProfileConfigQcom: Adding HealthService
08-16 14:24:57.469  7010  7010 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-16 14:24:57.470   314  4012 V LGParserOSAL: supported mime: application/ogg
08-16 14:24:57.470   314  4012 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 14:24:57.470   314  4012 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 14:24:57.471   314  4012 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 14:24:57.471   314  4012 V AwesomePlayer: AudioTrack Setting
08-16 14:24:57.471   314  4012 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 14:24:57.471   314  4012 V AwesomePlayer: setAudioSource() 
08-16 14:24:57.471   314  4012 V MediaPlayerService: prepare
08-16 14:24:57.471   314  4012 V AwesomePlayer: prepareAsync_l() 
08-16 14:24:57.471   314  4012 V MediaPlayerService: wait for prepare
08-16 14:24:57.471   314  7038 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 14:24:57.471   314  7038 V AwesomePlayer: initAudioDecoder() 
08-16 14:24:57.471   314  7038 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 14:24:57.471   314  7038 V AudioSystem: isOffloadSupported()
08-16 14:24:57.471   314  7038 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 14:24:57.471   314  7038 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 14:24:57.471   314  7038 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 14:24:57.471   314  7038 V AwesomePlayer: getUseOffload() = 0 
08-16 14:24:57.471   314  7038 V OMXCodec: OMXCodec::Create
08-16 14:24:57.471   314  7038 V OMXCodec: findMatchingCodecs()
08-16 14:24:57.471   314  7038 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 14:24:57.471   314  7038 V OMXCodec: matchingCodecs.size()=1
08-16 14:24:57.471   314  7038 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 14:24:57.472  7010  7010 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 14:24:57.473  7010  7010 D ProfileConfigQcom: Adding PanService
08-16 14:24:57.473  7010  7010 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 14:24:57.474  7010  7010 D ProfileConfigQcom: Adding GattService
08-16 14:24:57.474   314  7038 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 14:24:57.474   314  7038 V LGCodecAdapter: LG Codec Adapter start
08-16 14:24:57.474   314  7038 V OMXCodec: OMXCodec Createtor
08-16 14:24:57.474   314  7038 V OMXCodec: setComponentRole
08-16 14:24:57.474   314  7038 V OMXCodec: configureCodec protected=0
08-16 14:24:57.474   314  7038 V LGCodecAdapter: called getLGCodecSpecificData
08-16 14:24:57.474   314  7038 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 14:24:57.474   314  7038 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 14:24:57.474   314  7038 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 14:24:57.474  7010  7010 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 14:24:57.474   314  7038 V LGCodecOSAL: Not support LGCodec
08-16 14:24:57.474   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 14:24:57.474   314  7038 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 14:24:57.474   314  7038 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 14:24:57.474   314  7038 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 14:24:57.475   314  7038 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 14:24:57.475   314  7038 V AudioSystem: isOffloadSupported()
08-16 14:24:57.475   314  7038 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=,0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 14:24:57.475   314  7038 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 14:24:57.475   314  7038 V OMXCodec: init()
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 14:24:57.475   314  7038 V OMXCodec: allocateBuffers
08-16 14:24:57.475  7010  7010 D ProfileConfigQcom: Adding BluetoothMapService
08-16 14:24:57.475   314  7038 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on input port
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on input port
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on input port
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8a60 on input port
08-16 14:24:57.475   314  7038 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8b50 on output port
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8d30 on output port
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8d80 on output port
08-16 14:24:57.475   314  7038 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17fc060 on output port
08-16 14:24:57.475   314  7038 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 14:24:57.476   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 14:24:57.476   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 14:24:57.476  7010  7010 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 14:24:57.476   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 14:24:57.476   314  7038 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 14:24:57.476   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 14:24:57.476   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 14:24:57.476   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 14:24:57.476   314  7038 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 14:24:57.476   314  7038 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 14:24:57.476   314  7038 V AudioCache: notify(0xb0409640, 5, 0, 0)
08-16 14:24:57.476   314  7038 V AudioCache: ignored
08-16 14:24:57.476   314  7038 V AudioCache: notify(0xb0409640, 1, 0, 0)
,08-16 14:24:57.476   314  7038 V AudioCache: prepared
08-16 14:24:57.476   314  4012 V AudioCache: wait - success
08-16 14:24:57.476   314  4012 V MediaPlayerService: start
08-16 14:24:57.476   314  4012 V AwesomePlayer: play_l() 
08-16 14:24:57.476   314  4012 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 14:24:57.476   314  4012 V AwesomePlayer: createAudioPlayer_l
08-16 14:24:57.476   314  4012 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 14:24:57.476   314  4012 V AwesomePlayer: startAudioPlayer_l() 
08-16 14:24:57.476   314  4012 D AudioPlayer: start of Playback, useOffload 0
08-16 14:24:57.476   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 14:24:57.476   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 14:24:57.479   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 14:24:57.479   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 14:24:57.479   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-16 14:24:57.479   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 14:24:57.479   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 14:24:57.479   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 14:24:57.479  7010  7010 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 14:24:57.479   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974518096
08-16 14:24:57.479   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974518576
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974518656
,08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977939552
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 14:24:57.480   314  7040 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8d80 on output port
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8d30 on output port
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8b50 on output port
08-16 14:24:57.480   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17fc1f0 on output port
08-16 14:24:57.481   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 14:24:57.481   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 14:24:57.481   314  4012 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-16 14:24:57.482   314  4012 V AudioCache: notify(0xb0409640, 6, 0, 0)
08-16 14:24:57.482   314  4012 V AudioCache: ignored
08-16 14:24:57.482   314  4012 V MediaPlayerService: wait for playback complete
08-16 14:24:57.482   314  7041 V AudioCache: write(0xb57be000, 4096)
,08-16 14:24:57.483   314  7041 V AudioCache: memcpy(0xac300000, 0xb57be000, 4096)
,08-16 14:24:57.484   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.484   314  7041 V AudioCache: memcpy(0xac301000, 0xb57be000, 4096)
08-16 14:24:57.485   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.485   314  7041 V AudioCache: memcpy(0xac302000, 0xb57be000, 4096)
08-16 14:24:57.486   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.486   314  7041 V AudioCache: memcpy(0xac303000, 0xb57be000, 4096)
08-16 14:24:57.486   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.486   314  7041 V AudioCache: memcpy(0xac304000, 0xb57be000, 4096)
08-16 14:24:57.487   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.487   314  7041 V AudioCache: memcpy(0xac305000, 0xb57be000, 4096)
,08-16 14:24:57.488   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.488   314  7041 V AudioCache: memcpy(0xac306000, 0xb57be000, 4096)
08-16 14:24:57.490   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.490   314  7041 V AudioCache: memcpy(0xac307000, 0xb57be000, 4096)
08-16 14:24:57.495   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.495   314  7041 V AudioCache: memcpy(0xac308000, 0xb57be000, 4096)
08-16 14:24:57.496  6863  6863 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 14:24:57.496   314  7041 V AudioCache: write(0xb57be000, 4096)
,08-16 14:24:57.496   314  7041 V AudioCache: memcpy(0xac309000, 0xb57be000, 4096)
08-16 14:24:57.500   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.500   314  7041 V AudioCache: memcpy(0xac30a000, 0xb57be000, 4096)
,08-16 14:24:57.501   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.501   314  7041 V AudioCache: memcpy(0xac30b000, 0xb57be000, 4096)
08-16 14:24:57.501  7010  7010 V LGMDMManagerInternal: Create singleton instance
08-16 14:24:57.502   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.502   314  7041 V AudioCache: memcpy(0xac30c000, 0xb57be000, 4096)
08-16 14:24:57.503   314  7041 V AudioCache: write(0xb57be000, 4096)
,08-16 14:24:57.503   314  7041 V AudioCache: memcpy(0xac30d000, 0xb57be000, 4096)
08-16 14:24:57.503   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.503   314  7041 V AudioCache: memcpy(0xac30e000, 0xb57be000, 4096)
08-16 14:24:57.504   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.504   314  7041 V AudioCache: memcpy(0xac30f000, 0xb57be000, 4096)
08-16 14:24:57.505   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.505   314  7041 V AudioCache: memcpy(0xac310000, 0xb57be000, 4096)
08-16 14:24:57.506   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.506   314  7041 V AudioCache: memcpy(0xac311000, 0xb57be000, 4096)
08-16 14:24:57.506   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.506   314  7041 V AudioCache: memcpy(0xac312000, 0xb57be000, 4096)
08-16 14:24:57.507   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.507   314  7041 V AudioCache: memcpy(0xac313000, 0xb57be000, 4096)
08-16 14:24:57.508   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.508   314  7041 V AudioCache: memcpy(0xac314000, 0xb57be000, 4096)
08-16 14:24:57.508   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.508   314  7041 V AudioCache: memcpy(0xac315000, 0xb57be000, 4096)
08-16 14:24:57.510   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.510   314  7041 V AudioCache: memcpy(0xac316000, 0xb57be000, 4096)
08-16 14:24:57.511   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.511   314  7041 V AudioCache: memcpy(0xac317000, 0xb57be000, 4096)
08-16 14:24:57.512   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.512   314  7041 V AudioCache: memcpy(0xac318000, 0xb57be000, 4096)
08-16 14:24:57.512   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.512   314  7041 V AudioCache: memcpy(0xac319000, 0xb57be000, 4096)
08-16 14:24:57.513   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.513   314  7041 V AudioCache: memcpy(0xac31a000, 0xb57be000, 4096)
08-16 14:24:57.513   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.513   314  7041 V AudioCache: memcpy(0xac31b000, 0xb57be000, 4096)
08-16 14:24:57.514   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.514   314  7041 V AudioCache: memcpy(0xac31c000, 0xb57be000, 4096)
08-16 14:24:57.515   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.515   314  7041 V AudioCache: memcpy(0xac31d000, 0xb57be000, 4096)
08-16 14:24:57.515   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.515   314  7041 V AudioCache: memcpy(0xac31e000, 0xb57be000, 4096)
08-16 14:24:57.516   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.516   314  7041 V AudioCache: memcpy(0xac31f000, 0xb57be000, 4096)
08-16 14:24:57.516   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.516   314  7041 V AudioCache: memcpy(0xac320000, 0xb57be000, 4096)
08-16 14:24:57.517   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.517   314  7041 V AudioCache: memcpy(0xac321000, 0xb57be000, 4096)
08-16 14:24:57.518   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.518   314  7041 V AudioCache: memcpy(0xac322000, 0xb57be000, 4096)
08-16 14:24:57.518   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.518   314  7041 V AudioCache: memcpy(0xac323000, 0xb57be000, 4096)
08-16 14:24:57.519   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.519   314  7041 V AudioCache: memcpy(0xac324000, 0xb57be000, 4096)
08-16 14:24:57.520   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.520   314  7041 V AudioCache: memcpy(0xac325000, 0xb57be000, 4096)
08-16 14:24:57.520   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.520   314  7041 V AudioCache: memcpy(0xac326000, 0xb57be000, 4096)
08-16 14:24:57.521   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.521   314  7041 V AudioCache: memcpy(0xac327000, 0xb57be000, 4096)
08-16 14:24:57.521   314  7041 V Au,dioCache: write(0xb57be000, 4096)
08-16 14:24:57.521   314  7041 V AudioCache: memcpy(0xac328000, 0xb57be000, 4096)
08-16 14:24:57.522   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.522   314  7041 V AudioCache: memcpy(0xac329000, 0xb57be000, 4096)
,08-16 14:24:57.523   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.523   314  7041 V AudioCache: memcpy(0xac32a000, 0xb57be000, 4096)
08-16 14:24:57.523   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.523   314  7041 V AudioCache: memcpy(0xac32b000, 0xb57be000, 4096)
08-16 14:24:57.524   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.524   314  7041 V AudioCache: memcpy(0xac32c000, 0xb57be000, 4096)
08-16 14:24:57.524   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.524   314  7041 V AudioCache: memcpy(0xac32d000, 0xb57be000, 4096)
,08-16 14:24:57.525   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.525   314  7041 V AudioCache: memcpy(0xac32e000, 0xb57be000, 4096)
08-16 14:24:57.526   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.526   314  7041 V AudioCache: memcpy(0xac32f000, 0xb57be000, 4096)
08-16 14:24:57.526   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.526   314  7041 V AudioCache: memcpy(0xac330000, 0xb57be000, 4096)
08-16 14:24:57.527   314  7041 V AudioCache: write(0xb57be000, 4096)
08-16 14:24:57.527   314  7041 V AudioCache: memcpy(0xac331000, 0xb57be000, 4096)
08-16 14:24:57.527   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 14:24:57.527   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,08-16 14:24:57.527   314  7041 V AwesomePlayer: postAudioEOS() 
08-16 14:24:57.527   314  7041 V AudioCache: write(0xb57be000, 280)
08-16 14:24:57.527   314  7041 V AudioCache: memcpy(0xac332000, 0xb57be000, 280)
08-16 14:24:57.529   314  7038 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 14:24:57.529   314  7038 V AwesomePlayer: onStreamDone
08-16 14:24:57.529   314  7038 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 14:24:57.529   314  7038 V AudioCache: notify(0xb0409640, 2, 0, 0)
08-16 14:24:57.529   314  7038 V AudioCache: playback complete
,08-16 14:24:57.529   314  7038 V AwesomePlayer: pause_l() 
08-16 14:24:57.529   314  7038 V AudioCache: notify(0xb0409640, 7, 0, 0)
08-16 14:24:57.529   314  7038 V AudioCache: ignored
08-16 14:24:57.529   314  7038 V AwesomePlayer: cancelPlayerEvents
08-16 14:24:57.529   314  4012 V AudioCache: wait - success
08-16 14:24:57.529   314  4012 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 14:24:57.530   314  7038 D AudioPlayer: Pause Playback at 1068125
08-16 14:24:57.530   314  4012 V AwesomePlayer: reset_l() 
08-16 14:24:57.530   314  4012 V AudioCache: notify(0xb0409640, 8, 0, 0)
,08-16 14:24:57.530   314  4012 V AudioCache: ignored
08-16 14:24:57.530   314  4012 V AwesomePlayer: cancelPlayerEvents
08-16 14:24:57.530   314  4012 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 14:24:57.530   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 14:24:57.530   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 14:24:57.530   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 14:24:57.530   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 14:24:57.530   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 14:24:57.530   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,08-16 14:24:57.530   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 14:24:57.530   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8a60 on port 0
08-16 14:24:57.530   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 14:24:57.530   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8970 on port 0
08-16 14:24:57.530   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 14:24:57.530   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b88d0 on port 0
08-16 14:24:57.530   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8240 on port 0
,08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb17fc1f0 on port 1
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8b50 on port 1
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8d30 on port 1
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8d80 on port 1
,08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 14:24:57.531   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 14:24:57.531   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 14:24:57.531   314  7040 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 14:24:57.531   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 14:24:57.531   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
,08-16 14:24:57.531   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 14:24:57.532   314  4012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 14:24:57.532   314  4012 D AudioPlayer: AudioPlayer releasing audio source
08-16 14:24:57.532   314  4012 D AudioPlayer: AudioPlayer done releasing audio source
08-16 14:24:57.532   314  4012 V AwesomePlayer: reset_l() 
08-16 14:24:57.532   314  4012 V AwesomePlayer: cancelPlayerEvents
08-16 14:24:57.532   314  4012 V AwesomePlayer: ~AwesomePlayer call
08-16 14:24:57.532   314  4012 V AwesomePlayer: reset_l() 
08-16 14:24:57.532   314  4012 V AwesomePlayer: cancelPlayerEvents
,08-16 14:24:57.532  6940  7036 V SoundPool: close(31)
08-16 14:24:57.533  6940  7036 V SoundPool: pointer = 0x9ffcc000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 14:24:57.542  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 14:24:57.543  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 14:24:57.545  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:733
,08-16 14:24:57.570  7010  7010 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED,
,08-16 14:24:57.572  7010  7010 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:24:57.573  7010  7010 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:24:57.573  7010  7010 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:24:57.574  7010  7010 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:24:57.574  7010  7010 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 14:24:57.583  6960  6960 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 14:24:57.738  6682  6682 I UEI.SmartControl: Supports setup maps: true
,08-16 14:24:57.741  6682  6682 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 14:24:57.741  6682  6682 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 14:24:57.741  6682  6682 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 14:24:57.741  6682  6682 I UEI.SmartControl: ### init IR Blaster...
,08-16 14:24:57.745  6682  6682 D serial_port: Configuring serial port
,08-16 14:24:57.745  6682  6682 E UEI.SmartControl: UEIBLaster setting for 616
08-16 14:24:57.745  6682  6682 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 14:24:57.745  6682  6682 I UEI.SmartControl: configuring settings for MAXQ616
08-16 14:24:57.745  6682  6682 I UEI.SmartControl: Get version...
08-16 14:24:57.764  6682  7043 D UEI.SmartControl: serial port data available: 21
,08-16 14:24:57.789  6682  6682 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 14:24:57.789  6682  6682 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 14:24:57.789  6682  6682 I UEI.SmartControl: QS saving settings...
08-16 14:24:57.790  6682  6682 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 14:24:57.806  6682  7043 D UEI.SmartControl: serial port data available: 4,
,08-16 14:24:57.837  6682  7049 I UEI.SmartControl: Device manager: loading config....
08-16 14:24:57.839  6682  6682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 14:24:57.839  6682  7049 D UEI.SmartControl: ----------- loading internal config...
,08-16 14:24:57.843  6682  6682 E UEI.SmartControl: Services init done
08-16 14:24:57.843  6682  6682 D UEI.SmartControl: QS Service init finished
08-16 14:24:57.844  6682  6682 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 14:24:57.845  6682  6682 D UEI.SmartControl: QS Service version code: 201091
08-16 14:24:57.845  6682  6682 D UEI.SmartControl: Service requested: Control
08-16 14:24:57.849  6682  7049 E UEI.SmartControl: Loading SETTINGS...
08-16 14:24:57.851  6682  6682 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 14:24:57.855  6940  6940 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-16 14:24:57.862  6682  6698 I UEI.SmartControl: ------ IControl API: 11
08-16 14:24:57.862  6682  6698 D UEI.SmartControl: File observer start...
08-16 14:24:57.863  6682  6698 E UEI.SmartControl: IR Port is disabled: false
08-16 14:24:57.864  6682  6698 D UEI.SmartControl: Starting file observer...
08-16 14:24:57.865  6682  6698 I UEI.SmartControl: Registering callback...
08-16 14:24:57.870  6682  6682 D UEI.SmartControl: Internal service binding...
,08-16 14:24:57.874  6682  6697 I UEI.SmartControl: ------ IControl API: 19
08-16 14:24:57.876  6682  6697 I UEI.SmartControl: Registering Services Ready callback...
08-16 14:24:57.883  6682  7049 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 14:24:57.906  6682  7048 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 14:24:57.906  6682  7048 D UEI.SmartControl: -----service ready thread exits
08-16 14:24:57.907  6940  6959 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-16 14:24:57.907  6940  7034 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 14:24:57.908  6940  7034 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 14:24:57.909  6940  6940 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 14:24:57.909  6940  6940 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 14:24:57.909  6682  6698 I UEI.SmartControl: ------ IControl API: 8
08-16 14:24:57.911  6940  6940 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 14:24:57.911  6940  6940 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 14:24:57.912  6940  6940 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 14:24:57.912  6940  6940 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 14:24:57.913  6940  6940 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 14:24:57.913  6940  6940 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 14:24:57.914  6940  6940 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 14:24:57.918  6940  6940 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 14:24:57.919  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 14:24:57.920  6940  6940 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 14:24:57.920  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 14:24:57.921  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 14:24:57.922  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 14:24:57.923  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 14:24:57.924  6940  6940 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471350297923]
08-16 14:24:57.925  6940  6940 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 14:24:57.927  1051  1067 I ActivityManager: Killing 6136:com.android.gallery3d/u0a27 (adj 15): empty #17
08-16 14:24:57.950  6940  7054 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 14:24:57.969  1051  1067 I ActivityManager: Killing 6562:com.lge.email/u0a23 (adj 15): empty #18
,08-16 14:24:58.000  1051  1066 W libprocessgroup: failed to open /acct/uid_10027/pid_6136/cgroup.procs: No such file or directory
,08-16 14:24:58.010  1051  1726 W libprocessgroup: failed to open /acct/uid_10023/pid_6562/cgroup.procs: No such file or directory
08-16 14:24:58.013  6940  6940 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 14:24:58.013  6940  6940 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 14:24:58.014  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 14:24:58.014  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 14:24:58.015  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 14:24:58.015  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 14:24:58.016  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-16 14:24:58.026  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-16 14:24:58.204  1051  1396 D PowerManagerServiceEx: acquireWakeLockInternal: lock=30001972, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,08-16 14:24:58.223  1051  1396 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3ef6352b type 2 when 211800 com.google.android.gms} when 211800
,08-16 14:24:58.232   310  7059 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 14:24:58.240  1051  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 14:24:58.275  2587  2587 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 14:24:58.305  1051  1051 D PowerManagerServiceEx: releaseWakeLockInternal: lock=30001972 [*alarm*], flags=0x0
,08-16 14:24:58.821  1051  1957 D WifiServiceImplEx: setWifiEnabled: true pid=6780, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 14:24:58.822  1051  1957 D WifiService: setWifiEnabled: true pid=6780, uid=10118
08-16 14:24:58.822  1051  1957 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:24:58.845  1051  1051 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:24:58.846  1051  1051 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:24:58.846  1051  1051 D Ulp_jni : JNI:system_update. Event-4
,08-16 14:24:58.849  1051  1555 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 14:24:58.849  1051  1555 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 14:24:58.851  1051  1555 E WifiUtil: wfc_util_ffile_check_copy(): pid[1051] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 14:24:58.851  1051  1555 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 14:24:58.851  1051  1555 E WifiUtil: wfc_util_ffile_check_copy(): pid[1051] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 14:24:58.852  1051  1555 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 14:24:58.852  1051  1555 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 14:24:58.852  1051  1555 E WifiHW  : unknown target_country: EU , set to default
08-16 14:24:58.852  1051  1555 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 14:24:58.852  1051  1555 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 14:24:58.852  1051  1555 I WifiUtil: gEnableBmps=1
08-16 14:24:58.934  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:24:58.953  1051  1115 D Tethering: MasterInitialState.processMessage what=3
08-16 14:24:58.976  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:24:58.981  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:58.983  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:24:58.985  1051  1115 D Tethering: MasterInitialState.processMessage what=3
08-16 14:24:58.999  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:24:59.003  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:59.003  1051  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 14:24:59.005  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 14:24:59.015  5815  5815 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 14:24:59.023  5815  5815 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 14:24:59.024  6477  6911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 14:24:59.051  2258  2258 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:24:59.089  1051  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:24:59.110  1051  1986 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7061 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 14:24:59.135  1051  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:24:59.136  1051  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 14:24:59.213  7061  7061 I AppUp4:AppBoxCP: onCreate
08-16 14:24:59.214  7061  7061 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 14:24:59.221  7061  7061 I AppUp4:DB:  setFingerPrint start
08-16 14:24:59.222  7061  7061 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-16 14:24:59.227  7061  7061 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 14:24:59.227  7061  7061 I AppUp4:DB:  SDK version = 21
08-16 14:24:59.227  7061  7061 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-16 14:24:59.229  7061  7061 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 14:24:59.230  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:24:59.230  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:24:59.232  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:24:59.232  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 14:24:59.239  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:24:59.269  7061  7061 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:24:59.269  7061  7061 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:24:59.276  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d548ece
08-16 14:24:59.277  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:24:59.277  7061  7061 D AppUp4:CustFacade: isPhone : true
08-16 14:24:59.277  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:24:59.278  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 14:24:59.278  7061  7061 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 14:24:59.278  7061  7095 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 14:24:59.279  7061  7095 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 14:24:59.279  7061  7095 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 14:24:59.282  1051  2028 I ActivityManager: Killing 6599:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-16 14:24:59.364  1051  2125 W libprocessgroup: failed to open /acct/uid_10061/pid_6599/cgroup.procs: No such file or directory
08-16 14:24:59.365  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:24:59.366  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:24:59.372  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:24:59.383  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:24:59.398  4317  7104 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 14:24:59.403  4317  7105 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:24:59.404  4317  7105 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 14:24:59.470  1051  1964 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7106 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 14:24:59.554  1051  1115 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 14:24:59.556  1051  1115 D Tethering: InitialState.processMessage what=4
,08-16 14:24:59.557  1051  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 14:24:59.561   310   910 D SoftapController: Softap fwReload - Ok
08-16 14:24:59.562  1051  1555 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (704ms)
08-16 14:24:59.564   310   910 D CommandListener: Setting iface cfg
08-16 14:24:59.564   310   910 D CommandListener: Trying to bring down wlan0
08-16 14:24:59.565   310   910 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:24:59.567  1051  1555 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 14:24:59.567  7124  7124 W wpa_supplicant: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:24:59.573  7106  7106 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:24:59.575  7106  7106 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:24:59.567  7124  7124 W wpa_supplicant: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:24:59.577  7106  7106 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 14:24:59.577  7106  7106 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 14:24:59.596  7124  7124 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 14:24:59.621  7124  7124 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 14:24:59.622  7124  7124 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 14:24:59.655  7106  7106 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 14:24:59.666  7106  7106 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 14:24:59.667  1051  1555 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:24:59.667  1051  1555 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:24:59.667  1051  1555 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:24:59.669  1051  1555 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 14:24:59.669  1051  1555 D WifiMonitor: connecting to supplicant
08-16 14:24:59.670  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:24:59.672  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 14:24:59.672  1051  1051 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 14:24:59.672  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:59.673  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:24:59.693  7124  7124 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 14:24:59.722  7106  7106 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 14:24:59.758  7124  7124 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 14:24:59.760  7106  7106 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:24:59.760  7106  7106 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:24:59.772  7124  7124 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 14:24:59.772  7124  7124 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 14:24:59.773  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 14:24:59.773  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 14:24:59.774  1051  7127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 14:24:59.774  1051  7127 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 14:24:59.774  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 14:24:59.774  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 14:24:59.774  1051  7127 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 14:24:59.774  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 14:24:59.774  1051  7127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 14:24:59.774  1051  1555 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 14:24:59.775  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:24:59.775  1051  1555 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:24:59.776  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:24:59.776  1051  1555 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:24:59.777  1051  1555 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 14:24:59.777  1051  1555 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 14:24:59.777  1051  1555 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 14:24:59.777  1051  1555 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 14:24:59.778  1051  1555 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 14:24:59.779  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:59.779  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:59.779  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:59.779  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:59.779  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:24:59.779  1051  1555 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:24:59.779  1051  1555 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:24:59.779  1051  1555 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:24:59.781  1982  1982 D WfdService: Waiting for WifiP2p enabling
08-16 14:24:59.781  1051  1555 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 14:24:59.783  1051  1051 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 14:24:59.783  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:24:59.783  1051  1555 D WifiNative-wlan0: SET update_config 1: returned true
08-16 14:24:59.783  1051  1555 D WifiConfigStore: Loading config and enabling all networks 
08-16 14:24:59.783  1051  1555 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 14:24:59.784  1051  1555 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 14:24:59.787  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:59.787  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:24:59.787  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:59.787  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:59.787  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:59.787  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:24:59.787  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:24:59.787  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:24:59.787  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:24:59.787  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:59.788  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:24:59.786  1051  1559 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 14:24:59.791  1051  1555 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 14:24:59.792  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:24:59.792  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:24:59.792  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:24:59.792  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:24:59.792  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:24:59.792  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:24:59.792  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:24:59.792  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:24:59.792  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:24:59.793  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:24:59.793  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:24:59.800  1051  1555 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 14:24:59.801  1051  1555 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 14:24:59.802  1051  1555 D WifiStateMachine: enableVerboseLogging : level 2
08-16 14:24:59.802  1051  1555 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 14:24:59.803  1051  1555 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 14:24:59.803  1051  1555 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 14:24:59.803  1051  1555 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 14:24:59.803  1051  1555 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 14:24:59.803  1051  1555 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 14:24:59.804  1051  1555 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 14:24:59.804  1051  1555 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 14:24:59.804  1051  1555 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 14:24:59.805  1051  1555 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
,08-16 14:24:59.805  1051  1555 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 14:24:59.805  1051  1555 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 14:24:59.805  1051  1555 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 14:24:59.806  1051  1555 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-16 14:24:59.807  1982  1982 D WfdsService: Supplicant Connection state is changed : true
08-16 14:24:59.807  1982  2375 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 14:24:59.807  1051  1555 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:24:59.807  1982  2375 D WfdsService: Set the WFDS Monitor: true
08-16 14:24:59.807  1051  1555 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 14:24:59.807  1982  2375 D WfdsMonitor: WfdsMonitorThread create
08-16 14:24:59.808  1982  2375 D WfdsMonitor: WFDS Monitor is created and started
08-16 14:24:59.808  1982  2375 D WfdsService: WiFi: Supplicant connection re-established
08-16 14:24:59.808  1051  1555 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 14:24:59.808  1051  1555 D WifiNative-HAL: Setting external_sim to 1
08-16 14:24:59.808  1051  1555 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 14:24:59.808  1051  1555 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 14:24:59.808  1051  1555 I WifiNative-HAL: startHal
08-16 14:24:59.808  1051  1555 D wifi    : setting scan oui 0xaf7a60a0
08-16 14:24:59.809  1982  7128 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 14:24:59.809  1051  1555 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:24:59.809  1051  1555 I WifiNative-HAL: startHal
08-16 14:24:59.809  1051  1555 D wifi    : setting scan oui 0xaf7a60a0
08-16 14:24:59.809  1982  7128 E CtrlSupplicant: Succeed to open control connection
08-16 14:24:59.809  1051  1555 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 14:24:59.809  1982  7128 E CtrlSupplicant: Succeed to open monitor connection
08-16 14:24:59.810  1982  7128 D WfdsMonitor: Supplicant connection established
08-16 14:24:59.810  1982  2375 D WfdsService: Connected to the supplicant for wfds
08-16 14:24:59.810  1051  1555 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 14:24:59.810  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 14:24:59.810  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 14:24:59.810  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 14:24:59.810  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 14:24:59.811  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 14:24:59.811  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 14:24:59.811  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 14:24:59.811  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 14:24:59.811  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 14:24:59.811  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 14:24:59.811  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-16 14:24:59.812  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 14:24:59.812  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 14:24:59.812  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 14:24:59.812  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 14:24:59.812  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 14:24:59.812  7124  7124 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 14:24:59.812  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 14:24:59.812  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 14:24:59.812  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-16 14:24:59.813  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 14:24:59.814  1051  1555 E WifiNative: : [213,411,298 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 14:24:59.814  1051  1555 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 14:24:59.814  1051  1555 D WifiNative-wlan0: RECONNECT: returned true
08-16 14:24:59.814  1051  1555 D WifiNative-wlan0: doString: [STATUS]
08-16 14:24:59.814  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 14:24:59.814  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 14:24:59.815  1051  1555 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 14:24:59.815  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 14:24:59.815  1051  1555 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:24:59.815  1051  1553 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.817   310   910 D CommandListener: Setting iface cfg
08-16 14:24:59.817   310   910 D CommandListener: Trying to bring up p2p0
08-16 14:24:59.817  1051  1051 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 14:24:59.817  1051  1051 D RttService: SCAN_AVAILABLE : 3
08-16 14:24:59.817  1051  1572 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.817  1051  1572 I WifiNative-HAL: startHal
,08-16 14:24:59.817  1051  1553 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 14:24:59.817  1051  1573 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.817  1051  1572 D wifi    : getting scan capabilities on interface[1] = 0xaf7a60a0
08-16 14:24:59.817  1051  1572 D wifi    : failed to get capabilities : -3
08-16 14:24:59.817  1051  1572 E WifiScanningService: could not get scan capabilities
08-16 14:24:59.817  1051  1553 D LGWifiP2pService: P2pEnablingState
08-16 14:24:59.817  1051  1553 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.817  1051  1553 D LGWifiP2pService: P2p socket connection successful
08-16 14:24:59.817  1051  1553 D LGWifiP2pService: P2pEnabledState
,08-16 14:24:59.819  1051  1555 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-16 14:24:59.819  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 14:24:59.820  1982  1982 D WfdsService: WifiP2pState is changed : true
08-16 14:24:59.820  1982  2375 D WfdsService: Receive the WFDS_ENABLE Method
08-16 14:24:59.820  1982  2375 D WfdsService: Set the WFDS Monitor: true
08-16 14:24:59.820  1982  2375 D WfdsService: Connected to the supplicant for wfds
,08-16 14:24:59.820  1982  2375 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 14:24:59.820  7124  7124 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 14:24:59.820  1982  2375 D WfdsService: selectPreferredScanChannel [36]
08-16 14:24:59.820  1982  2375 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 14:24:59.821  1051  1555 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 14:24:59.821  1051  1555 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 14:24:59.822  1051  1553 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 14:24:59.822  1051  1555 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,08-16 14:24:59.822  1051  1553 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 14:24:59.823  1051  1555 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 14:24:59.823  1051  1555 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 14:24:59.823  1051  1555 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 14:24:59.823  1051  1555 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 14:24:59.823  7124  7124 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 14:24:59.824  1051  1555 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 14:24:59.824  1051  1555 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 14:24:59.824  1982  1982 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 14:24:59.825  1051  1555 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 14:24:59.825  1051  1555 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 14:24:59.825  7124  7124 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 14:24:59.825  1982  1982 D WfdsService: isConnected: false
08-16 14:24:59.825  1051  1555 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 14:24:59.825  1051  1553 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 14:24:59.825  1051  1555 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 14:24:59.826  1051  1553 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 14:24:59.826  1051  1555 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 14:24:59.826  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 14:24:59.826  1051  1553 D WifiNative-p2p0: SET device_name G3: returned true
08-16 14:24:59.826  1051  1553 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 14:24:59.826  1051  1553 D LGWifiP2pService: before postfix = G3
08-16 14:24:59.826  1051  1553 D WifiServerServiceExt: postfix byte check : 2
08-16 14:24:59.826  1051  1553 D LGWifiP2pService: after postfix = G3
08-16 14:24:59.826  1051  1553 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 14:24:59.826  1051  1553 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 14:24:59.827  1051  1553 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 14:24:59.827  1051  1553 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 14:24:59.827  1051  1553 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 14:24:59.827  1051  1553 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 14:24:59.827  1051  1553 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 14:24:59.828  1051  1553 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 14:24:59.828  1051  1553 D WifiNative-HAL: p2pGetDeviceAddress
08-16 14:24:59.828  1051  1553 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 14:24:59.829  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 14:24:59.830  1982  1982 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 14:24:59.830  1982  1982 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 14:24:59.830  7124  7124 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:24:59.830  1982  1982 D WfdsService: Update P2p Interface State: 3
08-16 14:24:59.830  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:24:59.830  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:24:59.830  1051  7127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:24:59.830  1051  7127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:24:59.830  1051  1553 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 14:24:59.,830  1051  1553 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 14:24:59.831  7124  7124 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 14:24:59.831  7124  7124 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.831  1051  7127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:24:59.831  1051  7127 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.831  1051  7127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.831  1051  7127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.831  7124  7124 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.832  1982  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:24:59.832  1982  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:24:59.832  1051  1555 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
,08-16 14:24:59.833  1051  1553 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 14:24:59.833  1051  1553 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-16 14:24:59.833  1051  1555 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:24:59.833  1051  7127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:24:59.833  1051  1553 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 14:24:59.833  1051  1555 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:24:59.833  1051  1553 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 14:24:59.833  1051  7127 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.833  1051  7127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.833  1051  7127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.834  1051  1555 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:24:59.834  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 14:24:59.834  1051  1553 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 14:24:59.834  1051  1553 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 14:24:59.844  1051  1553 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 14:24:59.844  1051  1553 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 14:24:59.844  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 14:24:59.844  7124  7124 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-16 14:24:59.845  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,08-16 14:24:59.845  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:24:59.845  1051  7127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:24:59.845  1051  1553 D LGWifiP2pService: InactiveState
08-16 14:24:59.845  1051  7127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:24:59.845  1051  1555 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 14:24:59.845  1051  1555 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 14:24:59.845  1051  1553 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.845  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.845  1051  1553 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 14:24:59.845  1051  1555 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 14:24:59.845  1051  1555 D WifiNative-wlan0: doBoolean: SCAN
08-16 14:24:59.846  1051  1555 D WifiNative-wlan0: SCAN: returned false
08-16 14:24:59.846  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=213444  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:24:59.847  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 14:24:59.848  7124  7124 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:24:59.848  1982  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:24:59.848  1051  7127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:24:59.848  1051  7127 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:24:59.848  1051  7127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:24:59.848  1051  7127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:24:59.849  7124  7124 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 14:24:59.849  7124  7124 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.849  1982  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:24:59.849  1051  7127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:24:59.849  1051  7127 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.849  1051  7127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.849  1051  7127 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.849  7124  7124 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.849  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:59.850  1982  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:24:59.850  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:24:59.850  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 14:24:59.850  1051  7127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:24:59.850  1051  7127 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.850  1051  7127 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.850  1051  7127 E WifiMonitor: handleEvent unknown: 14 , CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:24:59.850  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:24:59.850  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:24:59.851  1051  1553 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 14:24:59.851  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=213449  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:24:59.851  1051  1553 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.851  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.851  1051  1553 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.851  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1555 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1982  2375 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1553 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:24:59.852  1051  1051 E WifiServerServiceExt: No p2p device connected
08-16 14:24:59.852  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:24:59.853  1051  1555 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:24:59.854  1051  1555 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:24:59.854  1051  1555 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:24:59.854  1051  1555 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:24:59.855  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:24:59.855  1051  1051 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 14:24:59.899  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 14:24:59.939  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:24:59.939  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:24:59.940  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 14:24:59.944  7106  7106 I HubEmail: JNI_OnLoad()
08-16 14:24:59.944  7106  7106 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 14:24:59.945  7106  7106 I HubEmail: registerNatives()
08-16 14:24:59.945  7106  7106 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 14:24:59.946  7106  7106 I HubEmail: registerNativeMethods()
08-16 14:24:59.947  7106  7106 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 14:24:59.947  7106  7106 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 14:25:00.015  1051  1734 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7136 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 14:25:00.026  6981  7133 W FormManager: Network not available. Please check & try again.
08-16 14:25:00.030  7106  7135 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.031  6981  7134 V FormManager: Network unavailable.
,08-16 14:25:00.040  6981  7134 V FormManager: Network unavailable.
08-16 14:25:00.043  1619  1619 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-16 14:25:00.043  1619  1619 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 14:25:00.043  1619  1619 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 14:25:00.043  1619  1619 I [SystemUI]Clock: called onTimeUpdated()
08-16 14:25:00.045  1619  1619 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 14:25:00.045  1619  1619 I [SystemUI]DateView: called onTimeUpdated()
08-16 14:25:00.047  1619  1619 I [SystemUI]DateView: called onTimeUpdated()
08-16 14:25:00.048  1619  1619 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 14:25:00.080  1051  2028 I ActivityManager: Killing 6195:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 14:25:00.150  7136  7136 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 14:25:00.150  7136  7136 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:25:00.154  7136  7136 D PhoneMonitor: Register our PhoneStateListener
08-16 14:25:00.163  1051  1066 W libprocessgroup: failed to open /acct/uid_10080/pid_6195/cgroup.procs: No such file or directory
08-16 14:25:00.181  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 14:25:00.183  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 14:25:00.199  7136  7136 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 14:25:00.202  7136  7136 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-16 14:25:00.203  7136  7136 D TelephonyAutoProfiling: [parse] Load xml
08-16 14:25:00.210  7136  7136 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 14:25:00.211  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 14:25:00.211  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 14:25:00.211  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 14:25:00.211  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 14:25:00.211  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 14:25:00.211  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 14:25:00.211  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 14:25:00.211  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
,08-16 14:25:00.212  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 14:25:00.212  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 14:25:00.212  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 14:25:00.212  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 14:25:00.212  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 14:25:00.212  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 14:25:00.212  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 14:25:00.212  7136  7136 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 14:25:00.220  7136  7136 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 14:25:00.259  1051  2006 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7155 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:25:00.259  1051  2006 I ActivityManager: Killing 6225:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-16 14:25:00.318  1051  2127 W libprocessgroup: failed to open /acct/uid_10097/pid_6225/cgroup.procs: No such file or directory
,08-16 14:25:00.492  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-16 14:25:00.492  1051  7127 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 14:25:00.492  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 14:25:00.492  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-16 14:25:00.492  1051  7127 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 14:25:00.493  7124  7124 E wpa_supplicant: USIM:  scard_init function
08-16 14:25:00.494  7124  7124 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 14:25:00.494  1051  1555 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 14:25:00.495  1051  1555 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 14:25:00.496  1051  1555 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 14:25:00.497  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 14:25:00.497  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 14:25:00.497  1051  1555 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 14:25:00.497  1051  1555 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 14:25:00.541  1051  2127 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7176 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-16 14:25:00.542  1051  2127 I ActivityManager: Killing 6643:com.lge.eula/1000 (adj 15): empty #17
,08-16 14:25:00.601  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=214199  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 14:25:00.602  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=214200  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 14:25:00.605  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.605  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:00.606  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:00.608  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:25:00.608  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.608  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 14:25:00.611  7124  7124 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 14:25:00.614  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 14:25:00.614  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 14:25:00.616  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 14:25:00.616  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 14:25:00.616  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:25:00.616  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:25:00.617  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=214215  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 14:25:00.618  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=214215  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 14:25:00.618  1051  1555 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214216
,08-16 14:25:00.619  1051  1555 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214217
08-16 14:25:00.622  1051  1555 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214220
08-16 14:25:00.622  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.622  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.622  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 14:25:00.622  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:00.622  1051  1051 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 14:25:00.623  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214221
08-16 14:25:00.623  1051  1555 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=214221
08-16 14:25:00.624  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:00.624  1051  1051 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 14:25:00.624  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=214222  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 14:25:00.625  1051  1115 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 14:25:00.629  7124  7124 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:25:00.629  7124  7124 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:25:00.632  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.632  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:00.633  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:25:00.633  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:25:00.633  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 14:25:00.633  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:25:00.633  1051  7127 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:25:00.633  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 14:25:00.633  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:25:00.633  1051  7127 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:25:00.634  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:25:00.634  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:25:00.634  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:25:00.637  1051  1957 W libprocessgroup: failed to open /acct/uid_1000/pid_6643/cgroup.procs: No such file or directory
,08-16 14:25:00.642  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.642  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.642  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 14:25:00.644  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=214241  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 14:25:00.646  1051  1555 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:00.646  1051  1555 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:00.646  1051  1555 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:00.647  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.647  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:25:00.647  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:00.647  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 14:25:00.647  1051  1555 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:00.648  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=214246  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 14:25:00.649  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=214247  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 14:25:00.649  1051  1555 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=214247
08-16 14:25:00.650  1051  1555 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=214248
08-16 14:25:00.655  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.655  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:00.655  1051  1555 D WifiNative-wlan0: doString: [STATUS]
08-16 14:25:00.656  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-16 14:25:00.656  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:25:00.656  1051  1555 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 14:25:00.657  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:00.658  1051  1555 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 14:25:00.660  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.660  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:00.661  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:00.665  1051  1555 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 14:25:00.665  1051  1555 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 14:25:00.669  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.669  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.669  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 14:25:00.677  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.677  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:00.679  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:00.680  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.680  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.680  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 14:25:00.682  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.682  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:00.682  1051  1555 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 14:25:00.683  1051  1561 D ConnectivityService: Got NetworkAgent Messenger
08-16 14:25:00.683  1051  1555 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:25:00.683  1051  1555 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:25:00.683  1051  1561 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 14:25:00.683  1051  1561 D ConnectivityService: NetworkAgent connected
08-16 14:25:00.683  1051  1555 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:25:00.683  1051  1555 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:25:00.687  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:25:00.693  1051  1555 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 14:25:00.693  1051  1555 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:25:00.693  1051  1555 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:25:00.693  1051  1555 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:25:00.694  1051  1555 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:25:00.699  1051  1555 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 14:25:00.700   310   910 D CommandListener: Setting iface cfg
,08-16 14:25:00.705  1051  1555 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 14:25:00.705  1051  7198 D DhcpStateMachine: StoppedState
08-16 14:25:00.705  1051  7198 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:00.705  1051  7198 D DhcpStateMachine: WaitBeforeStartState
08-16 14:25:00.705  1051  1555 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=214303  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:00.706  1051  1555 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=214304  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:00.706  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=214304  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:00.708  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:00.708  1051  1051 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 14:25:00.709  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:00.709  1051  1051 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 14:25:00.710  1051  1555 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=214307  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:00.710  1051  1555 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=214308  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:00.710  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=214308  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:00.712  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:168857] from screen [on:0 period:-1823481816] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 14:25:00.713  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1823481815] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 14:25:00.714  1051  1555 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 14:25:00.770  1051  1964 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7200 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:25:00.773  1051  1964 I ActivityManager: Killing 6660:com.lge.bnr/1000 (adj 15): empty #17
,08-16 14:25:00.777  1051  1561 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 14:25:00.778  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.779  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.780  1051  1555 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.782  1051  1555 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.783  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.784  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.785  1051  1561 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-16 14:25:00.786  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=134,0,0
08-16 14:25:00.787  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=134,0,0
08-16 14:25:00.787  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 14:25:00.788  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 14:25:00.789  1051  1555 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 14:25:00.789  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 14:25:00.790  1051  1555 D WifiNative-wlan0: SET ps 0: returned true
08-16 14:25:00.790  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 14:25:00.791  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 14:25:00.792  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 14:25:00.792  1051  1553 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e47f8e1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:25:00.793  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e47f8e1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:00.794  1051  7198 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:00.794  1051  7198 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 14:25:00.796  1051  1555 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 14:25:00.796  1051  1555 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 14:25:00.796  1051  1555 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 14:25:00.799   310   910 D CommandListener: Setting iface cfg
08-16 14:25:00.800   310   910 D CommandListener: Trying to bring up wlan0
08-16 14:25:00.802  1051  1555 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-16 14:25:00.880  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:00.892  1051  2127 W libprocessgroup: failed to open /acct/uid_1000/pid_6660/cgroup.procs: No such file or directory
,08-16 14:25:00.896  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.896  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.897  1051  1555 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.897  1051  1555 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.898  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.898  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:00.899  1051  1561 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 14:25:00.899  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 14:25:00.900  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 14:25:00.900  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:25:00.900  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:25:00.901  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:25:00.901  1051  1553 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:00.901  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 14:25:00.901  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-16 14:25:00.901  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:00.902  1051  1555 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 14:25:00.902  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:25:00.918  1051  1555 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:25:00.919  1051  1561 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 14:25:00.920  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-16 14:25:00.921  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 14:25:00.921  1051  1555 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 14:25:00.922  1051  1561 D ConnectivityService: ignoring duplicate network state non-change
08-16 14:25:00.924  1051  1561 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 14:25:00.925  7200  7200 I art     : Almond Protected OAT
08-16 14:25:00.925  1051  1561 D ConnectivityService: Adding iface wlan0 to network 101
08-16 14:25:00.928  1051  1555 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 14:25:00.932  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:00.932  1051  1051 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 14:25:00.937  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.937  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:00.939  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:00.941  1051  1553 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:25:00.942  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:00.942  1051  1553 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:00.943  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.943  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.944  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 14:25:00.951  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.951  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.951  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 14:25:00.953  1051  1051 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-16 14:25:00.956  1982  1982 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 14:25:00.960  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.960  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.960  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 14:25:00.961  1051  1051 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 14:25:00.967  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.967  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 14:25:00.967  1051  1561 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 14:25:00.967  1051  1561 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 14:25:00.968  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.968  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:00.968  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 14:25:00.969  1051  1561 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 14:25:00.970   310   910 E Netd    : netlink response contains error (File exists)
08-16 14:25:00.971  1051  1561 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 14:25:00.971  1051  1555 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 14:25:00.972  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 14:25:00.972  1051  1555 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 14:25:00.972  1051  1555 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 14:25:00.973  1051  1561 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 14:25:00.973  1051  1561 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 14:25:00.973  1051  1561 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 14:25:00.973  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 14:25:00.974  1051  1561 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 14:25:00.974  1051  1561 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 14:25:00.974  1051  1561 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 14:25:00.974  1051  1561 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 14:25:00.974  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:00.974  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 14:25:00.974  1051  1561 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:25:00.974  1051  1561 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:00.974  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:00.974  1051  1561 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 14:25:00.974  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 14:25:00.975  1051  1561 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:00.975  1051  1561 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 14:25:00.975  1051  1561 D ConnectivityService: currentScore = 0, newScore = 20
08-16 14:25:00.975  1051  1561 D ConnectivityService:    accepting network in place of null
08-16 14:25:00.976  1051  1555 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 14:25:00.976  1051  1561 D ConnectivityService: sending new Min Network Score(20),: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:00.976  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:00.977  1051  1555 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:00.977  1051  1555 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:25:00.977  1893  1893 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:00.978  1051  1561 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 14:25:00.978  1051  1561 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 14:25:00.978  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:25:00.978  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:25:00.978  1051  1561 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:00.978  1051  1561 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 14:25:00.979  1051  1561 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 14:25:00.979   310  7221 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 14:25:00.979  1051  1051 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 14:25:00.979  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.980  1051  1561 D ConnectivityService: validation of new default Network = false
08-16 14:25:00.980  1619  1619 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 14:25:00.980  1051  1561 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 14:25:00.980  1051  1561 D DSQN    : enableDataServiceNotify 
08-16 14:25:00.980  1051  1561 D DSQN    : start dsqn bin
08-16 14:25:00.980  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set, no data type icon / Roaming
08-16 14:25:00.984  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:00.984  1619  1619 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 14:25:00.984  1051  1051 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:25:00.984  1051  1051 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:25:00.984  1051  1051 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:25:00.985  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:00.977  7222  7222 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:00.977  7222  7222 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:00.990  1051  1561 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 14:25:00.991  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:00.991  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:00.991  1051  1561 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:00.992  1619  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 14:25:00.998  1051  7198 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 14:25:00.999  1051  7198 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 14:25:00.999  1051  7198 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 14:25:01.001  7222  7222 E DSQN    : DSQN ssw
08-16 14:25:00.997  7225  7225 W dhcpcd  : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:00.997  7225  7225 W dhcpcd  : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:01.009  7225  7225 I dhcpcd  : version 5.5.6 starting
08-16 14:25:01.010  7225  7225 E dhcpcd  : get_duid: m
08-16 14:25:01.010  7225  7225 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 14:25:01.010  7225  7225 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 14:25:01.013  7200  7200 D WeatherApplication: removeAccount
08-16 14:25:01.014  7200  7200 D WeatherApplication: Account.length = 0
08-16 14:25:01.015  7200  7200 E WeatherApplication: OPERATOR:OPEN
08-16 14:25:01.018  7200  7200 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:1
08-16 14:25:01.022  1051  1552 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 14:25:01.023  7200  7200 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 14:25:01.023  7200  7200 D Weather.Utils: 2 : All the weather widget is gone.
,08-16 14:25:01.029  7200  7200 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:25:01.031  7200  7200 D WeatherAncestor: connectivity changed - connection : true
08-16 14:25:01.032  7200  7200 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 14:25:01.033  1855  7230 I CheckinService: active receiver: enabled
,08-16 14:25:01.044  7200  7200 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:25:01.045  1855  7230 I CheckinService: Preparing to send checkin request
08-16 14:25:01.045  1855  7230 I EventLogService: Accumulating logs since 1471350144328
08-16 14:25:01.045  7200  7200 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:25:01.046  7200  7200 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 14:25:01.046  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:25:01.046  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:01.047  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:01.048   310  7221 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 14:25:01.050  7225  7225 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-16 14:25:01.050  7225  7225 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 14:25:01.050  7225  7225 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 14:25:01.050  7225  7225 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 14:25:01.051  7225  7225 D dhcpcd  : wlan0: sending REQUEST (xid 0xa927fea7), next in 3.47 seconds
08-16 14:25:01.058  7200  7200 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 14:25:01.058  7200  7200 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:1
08-16 14:25:01.079  7225  7225 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 14:25:01.080   310  7221 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 14:25:01.109  7225  7225 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 14:25:01.109  7225  7225 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 14:25:01.109  7225  7225 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 14:25:01.109  1051  2071 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7236 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:25:01.109  7225  7225 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 14:25:01.110  7225  7225 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 14:25:01.111  1051  2071 I ActivityManager: Killing 2195:com.lge.music/u0a34 (adj 15): empty #17
08-16 14:25:01.112  7225  7225 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 14:25:01.112  7225  7225 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 14:25:01.112  7225  7225 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 14:25:01.113   310   909 D LGDataListener: argv[0]=dsqncommand
08-16 14:25:01.113   310   909 D LGDataListener: argv[1]=wlan0
08-16 14:25:01.113   310   909 D LGDataListener: argv[2]=1
08-16 14:25:01.114   310   909 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 14:25:01.114  1051  1113 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 14:25:01.114  1051  1113 D DSQN    : start to monitor internet connection
08-16 14:25:01.143  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:25:01 GMT], X-Android-Received-Millis=[1471350301143], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471350301111]}
08-16 14:25:01.143  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 14:25:01.143  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 14:25:01.144   314   314 V AudioFlinger: 2195 died, releasing its sessions
08-16 14:25:01.144  1051  1561 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 14:25:01.144  1051  1561 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 14:25:01.145  1051  1561 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:25:01.145  1051  1561 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:01.145  1051  1561 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 14:25:01.145  1051  1561 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,08-16 14:25:01.145  1051  1561 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 14:25:01.145  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:01.145  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 14:25:01.146  1051  1561 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:01.146  1051  1561 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:01.147  1051  1555 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:01.147  1051  1555 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:25:01.148  1893  1893 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:01.148  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:25:01.149  1619  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 14:25:01.144   314   314 V AudioFlinger:  pid 1893 @ 0
08-16 14:25:01.151   314   314 V AudioFlinger:  pid 3487 @ 1
08-16 14:25:01.151   314   314 V AudioFlinger:  pid 3487 @ 2
08-16 14:25:01.151  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 14:25:01.190  1051  2127 W libprocessgroup: failed to open /acct/uid_10034/pid_2195/cgroup.procs: No such file or directory
08-16 14:25:01.190  1855  7230 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 14:25:01.226  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:25:01.227  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:01.229  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:25:01.325  1051  1726 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7275 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 14:25:01.346   333   333 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 388us total 24.688ms
,08-16 14:25:01.364   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 16.465ms
08-16 14:25:01.368   279   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:25:01.368   279   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 14:25:01.368   279   430 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:25:01.369  7236  7294 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 14:25:01.371   279   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:25:01.371   279   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 14:25:01.371   279   430 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:25:01.371  7236  7294 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 14:25:01.379   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 13.919ms
,08-16 14:25:01.382   279   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:25:01.382   279   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 14:25:01.382   279   430 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:25:01.383  7236  7296 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 14:25:01.386   279   430 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:25:01.386   279   430 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 14:25:01.386   279   430 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:25:01.386  7236  7296 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 14:25:01.402  1051  7198 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 14:25:01.405  1051  7198 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 14:25:01.405  1051  7198 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 14:25:01.405  1051  7198 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 14:25:01.405  1051  7198 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 14:25:01.405  1051  7198 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 14:25:01.405  1051  7198 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 14:25:01.406  1051  7198 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 14:25:01.406  1051  7198 D DhcpStateMachine: RunningState
08-16 14:25:01.406  7275  7275 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 14:25:01.407  7275  7275 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 14:25:01.435  7275  7275 I MultiDex: VM with version 2.1.0 has multidex support
08-16 14:25:01.435  7275  7275 I MultiDex: install
08-16 14:25:01.436  7275  7275 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 14:25:01.445  7275  7275 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 14:25:01.567  7236  7236 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 14:25:01.589  7236  7236 I LibraryLoader: Loading: webviewchromium
08-16 14:25:01.593  7236  7236 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 5198-5204)
08-16 14:25:01.593  7236  7236 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 14:25:01.598  7236  7236 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1faa271}
,08-16 14:25:01.599  7236  7236 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:25:01.599  7236  7236 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 14:25:01.608  7236  7236 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 14:25:01.609  7236  7236 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 14:25:01.633   314  1402 V AudioPolicyService: registerClient() client 0xb14b7ae0, uid 10093
,08-16 14:25:01.635  7236  7319 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 14:25:01.636  7236  7236 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 14:25:01.637  7236  7236 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 14:25:01.637  7236  7236 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 14:25:01.672  7236  7236 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:25:01.672  7236  7236 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:25:01.672  7236  7236 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:25:01.672  7236  7236 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:25:01.672  7236  7236 I Adreno-EGL: Remote Branch: 
08-16 14:25:01.672  7236  7236 I Adreno-EGL: Local Patches: 
08-16 14:25:01.672  7236  7236 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:25:01.810  1051  1555 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:01.810  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:01.810  1051  1555 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:01.810  1051  1555 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:01.811  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:01.811  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:01.811  1051  1561 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-16 14:25:01.811  1051  1561 D ConnectivityService: identical MTU - not setting
08-16 14:25:01.812  1051  1561 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 14:25:01.812  1051  1561 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 14:25:01.812  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:01.812  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:01.812  1051  1561 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:01.813  1619  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 14:25:01.834  7275  7292 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 14:25:01.834  7275  7292 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:25:01.851  1051  2127 D WifiServiceImplEx: setWifiEnabled: false pid=6780, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 14:25:01.851  1051  2127 D WifiService: setWifiEnabled: false pid=6780, uid=10118
08-16 14:25:01.851  1051  2127 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 14:25:01.863  1051  1051 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 14:25:01.863  1051  1051 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:25:01.863  1051  1051 D Ulp_jni : JNI:system_update. Event-4
08-16 14:25:01.865  1051  1555 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 14:25:01.866  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 14:25:01.866  1051  1555 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 14:25:01.867  1051  1555 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 14:25:01.867  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 14:25:01.867  1051  1555 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 14:25:01.868  1051  1555 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:25:01.868  1051  1555 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:25:01.868  1051  1555 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:25:01.869  1051  1555 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:25:01.876  1051  1555 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 14:25:01.876  1051  1553 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.876  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.876  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:25:01.876  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:25:01.878  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:25:01.878  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:25:01.878  1051  1555 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:25:01.879  1051  7198 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.879   310   910 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:25:01.909  1051  2028 I art     : Explicit concurrent mark sweep GC freed 105268(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.308ms total 173.868ms
08-16 14:25:01.910  1051  1555 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:01.910  1051  1553 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.910  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.910  1051  1553 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3b6381c
08-16 14:25:01.910  1051  1553 D LGWifiP2pService: P2pDisablingState
08-16 14:25:01.910  1051  1553 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.910  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:01.910  1051  1553 D LGWifiP2pService: p2p socket connection lost
08-16 14:25:01.910  1051  1553 D LGWifiP2pService: P2pDisabledState
08-16 14:25:01.911  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:01.911  1051  1555 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 14:25:01.911  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:25:01.912  7124  7124 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:25:01.913  1051  1561 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 14:25:01.914  1051  1561 D ConnectivityService: ignoring duplicate network state non-change
08-16 14:25:01.914  1051  1561 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-16 14:25:01.914  1051  1553 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.916  1051  1553 D LGWifiP2pService: DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.918  1051  1051 D WifiHS20: hidePasspointNotification off =false
08-16 14:25:01.921  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:25:01.921  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:25:01.922  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:01.923  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 14:25:01.924  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:01.927  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:01.928  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:01.928  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-16 14:25:01.930  1051  1555 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:25:01.931  1982  1982 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 14:25:01.932  1051  1051 D WifiHS20: hidePasspointNotification off =false
08-16 14:25:01.939  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:25:01.939  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:01.939  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:25:01.940  1051  1051 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 14:25:01.940  1051  1051 D RttService: SCAN_AVAILABLE : 1
08-16 14:25:01.940  1051  1573 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.941  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 14:25:01.942  1982  1982 D WfdsService: WifiP2pState is changed : false
08-16 14:25:01.947  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:01.947  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:01.948  1982  2375 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 14:25:01.948  1982  2375 D WfdsService: Set the WFDS Monitor: false
08-16 14:25:01.949  1051  1572 D WifiScanningService: DefaultState got{ when=-9ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.949  1982  2375 D WfdsMonitor: WFDS Monitor is stopped
08-16 14:25:01.949  1982  2375 D WfdsService: STATE : WfdsDisabledState - enter
08-16 14:25:01.950  1982  7128 D CtrlSupplicant: Received on exit socket, terminate
08-16 14:25:01.950  1982  7128 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 14:25:01.950  1982  7128 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 14:25:01.950  1982  7128 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 14:25:01.950  1982  2376 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 14:25:01.950  1982  2375 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 14:25:01.951  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:01.975  7338  7338 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-16 14:25:01.976   310   910 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:25:01.976  1051  1561 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 14:25:01.976  1051  1561 D DSQN    : disableDataServiceNotify
08-16 14:25:01.976  1051  1561 D DSQN    : stop dsqn bin
08-16 14:25:01.977  1051  1555 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 14:25:01.978  1051  1555 D WifiNative-p2p0: TERMINATE: returned true
08-16 14:25:01.978  1051  1555 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:25:01.978  1051  1555 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:25:01.978  1051  1555 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:25:01.980  1051  1555 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 14:25:01.983  1051  1051 D WifiHS20: hidePasspointNotification off =false
08-16 14:25:01.983  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:01.983  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:01.984  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:25:01.985  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 14:25:01.986  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:01.986  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:01.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:01.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:01.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:01.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:25:01.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:01.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:01.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:25:01.986  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:01.986  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:25:01.986  1051  1561 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 14:25:01.986  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:01.986  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:01.986  1051  1561 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:01.986  1051  1561 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 14:25:01.987  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:01.987  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:01.987  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:01.987  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:01.987  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:01.987  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:25:01.987  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:01.987  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:01.987  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:25:01.987  6780  6780 W org,.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:01.987  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:25:01.987  1051  1561 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 14:25:01.987  1051  1561 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 14:25:01.987  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:25:01.987  1619  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 14:25:01.987  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.987  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:01.988  1051  7193 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 14:25:01.988  1051  1051 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 14:25:01.989  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:01.989  1051  1051 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 14:25:01.990  1051  1561 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:01.990  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:25:01.990  1051  1051 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 14:25:01.990  1051  1051 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:25:01.992  1051  1051 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:25:01.992  1051  1051 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:25:01.996  1051  1552 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 14:25:01.999  1051  1561 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:01.999  1051  1561 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:01.999  1051  1561 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:02.000  1051  1561 D NetworkManagementService: Removing idletimer
08-16 14:25:02.000  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 14:25:02.000  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:02.000  1051  1561 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:02.000  1051  1561 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-16 14:25:02.000  1051  1555 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:02.000  1051  1555 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:25:02.001  1893  1893 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:02.001  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:25:02.002  1051  1552 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 14:25:02.002  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:02.002  1051  1051 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 14:25:02.003  1051  1051 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:25:02.003  1051  1051 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:25:02.003  1051  1051 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:25:02.006  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:02.025  7236  7236 I NSApplication: Starting up...
,08-16 14:25:02.031  7338  7338 I dex2oat : dex2oat took 56.164ms (threads: 4)
08-16 14:25:02.032  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:25:02.032  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:02.033  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:02.044  7275  7292 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:25:02.044  7275  7292 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:25:02.044  7275  7292 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:25:02.044  7275  7292 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:25:02.044  7275  7292 I Adreno-EGL: Remote Branch: 
08-16 14:25:02.044  7275  7292 I Adreno-EGL: Local Patches: 
08-16 14:25:02.044  7275  7292 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:25:02.076  1051  1986 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7352 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-16 14:25:02.077  1051  1986 I ActivityManager: Killing 6157:com.android.vending/u0a44 (adj 15): empty #17
08-16 14:25:02.081  7124  7124 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 14:25:02.082  7124  7124 I wpa_supplicant: monitor socket send errors count : 1
08-16 14:25:02.082  7124  7124 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1982-4\x00 that cannot receive messages
08-16 14:25:02.089  1051  7127 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-16 14:25:02.089  1051  7127 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 14:25:02.099  1051  7198 D DhcpStateMachine: StoppedState
08-16 14:25:02.099  1051  7198 D DhcpStateMachine: StoppedState{ when=-169ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:02.119  7124  7124 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 14:25:02.120  7124  7124 W wpa_supplicant: USIM:  scard_deinit function
08-16 14:25:02.120  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 14:25:02.120  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:25:02.121  1051  7127 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:25:02.121  1051  7127 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 14:25:02.121  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:25:02.121  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:25:02.121  1051  1555 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=215719
08-16 14:25:02.121  1051  1555 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=215719
08-16 14:25:02.122  1051  1555 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=215720  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 14:25:02.122  1051  1555 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=215720  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 14:25:02.122  1051  1115 D Tethering: InitialState.processMessage what=4
08-16 14:25:02.172  1051  1964 W libprocessgroup: failed to open /acct/uid_10044/pid_6157/cgroup.procs: No such file or directory
,08-16 14:25:02.194  1051  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 14:25:02.197  1051  1555 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 14:25:02.197  1051  1555 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 14:25:02.200  1051  1555 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:02.200  1051  1555 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:02.203  7275  7292 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:25:02.203  7275  7292 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:25:02.203  7275  7292 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:25:02.203  7275  7292 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:25:02.203  7275  7292 I Adreno-EGL: Remote Branch: 
08-16 14:25:02.203  7275  7292 I Adreno-EGL: Local Patches: 
08-16 14:25:02.203  7275  7292 I Adreno-EGL: Reconstruct Branch: 
08-16 14:25:02.223  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:25:02.224  7352  7352 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:25:02.225  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:02.225  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:25:02.270  7124  7124 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 14:25:02.271  1051  7127 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 14:25:02.271  1051  7127 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 14:25:02.271  1051  7127 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 14:25:02.273  1051  1555 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-16 14:25:02.285  7275  7292 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:25:02.285  7275  7292 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:25:02.285  7275  7292 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:25:02.285  7275  7292 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:25:02.285  7275  7292 I Adreno-EGL: Remote Branch: 
08-16 14:25:02.285  7275  7292 I Adreno-EGL: Local Patches: 
08-16 14:25:02.285  7275  7292 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:25:02.375  1051  1555 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 14:25:02.375  1982  1982 D WfdsService: Supplicant Connection state is changed : false
,08-16 14:25:02.375  1051  1555 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:25:02.375  1051  1555 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:25:02.375  1051  1555 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:25:02.375  1982  2375 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 14:25:02.375  1982  2375 D WfdsService: Set the WFDS Monitor: false
08-16 14:25:02.375  1982  2375 D WfdsMonitor: WFDS Monitor is stopped
08-16 14:25:02.377  1051  1051 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-16 14:25:02.377  1051  1559 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 14:25:02.377  1051  1559 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 14:25:02.378  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:02.379  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 14:25:02.380  2516  2516 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:25:02.380  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:02.380  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:02.380  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:02.380  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:02.380  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:02.380  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:25:02.380  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:02.380  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:02.380  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:25:02.381  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:02.381  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:02.381  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:02.381  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:02.381  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:02.381  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:25:02.381  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:02.381  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:02.381  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:25:02.424  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 14:25:02.426  6477  6911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 14:25:02.433  2258  2258 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:02.442  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:25:02.442  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:02.442  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:25:02.442  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 14:25:02.445  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:25:02.447  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d548ece
08-16 14:25:02.447  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:25:02.448  7061  7061 D AppUp4:CustFacade: isPhone : true
08-16 14:25:02.448  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:25:02.448  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 14:25:02.450  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:02.450  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:25:02.451  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:02.453  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:02.456  4317  7380 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 14:25:02.458  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 14:25:02.459  4317  7381 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:02.459  4317  7381 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:25:02.473  7106  7382 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:25:02.478  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:25:02.478  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:02.478  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 14:25:02.481  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 14:25:02.481  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 14:25:02.485  6981  7385 W FormManager: Network not available. Please check & try again.
08-16 14:25:02.487  7200  7200 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:2
,08-16 14:25:02.490  7200  7200 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 14:25:02.490  7200  7200 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:25:02.491  7200  7200 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:25:02.491  7200  7200 D WeatherAncestor: connectivity changed - connection : true
08-16 14:25:02.491  7200  7200 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23ce94fc
08-16 14:25:02.491  7200  7200 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:25:02.491  7200  7200 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:25:02.491  7200  7200 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 14:25:02.491  7200  7200 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 14:25:02.491  7200  7200 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:2
08-16 14:25:02.494  6981  7387 V FormManager: Network unavailable.
08-16 14:25:02.495  6981  7387 V FormManager: Network unavailable.
08-16 14:25:02.508  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 14:25:02.508  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:25:02.508  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:25:02.508  6863  6863 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:25:02.509  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:25:02.509  6863  6863 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:25:02.509  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 14:25:02.509  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:25:02.509  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:25:02.509  6863  6863 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:25:02.510  6863  6863 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 14:25:02.515  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:02.518  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:25:02.524  6981  7392 V FormManager: Network unavailable.
,08-16 14:25:02.526  6981  7391 W FormManager: Network not available. Please check & try again.
08-16 14:25:02.529  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:02.533  6981  7392 V FormManager: Network unavailable.
08-16 14:25:02.543  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:25:02.544   310  7397 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 14:25:02.545  1051  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 14:25:02.545  1855  7230 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-16 14:25:02.546  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:25:02.549  1051  1396 D PowerManagerServiceEx: acquireWakeLockInternal: lock=30001972, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
08-16 14:25:02.553  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:02.553  6981  7394 W FormManager: Network not available. Please check & try again.
,08-16 14:25:02.556  1855  7230 I CheckinService: active receiver: disabled
,08-16 14:25:02.569  6981  7395 V FormManager: Network unavailable.
08-16 14:25:02.574  6981  7395 V FormManager: Network unavailable.
08-16 14:25:02.577  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:25:02.578  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:25:02.579  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:25:02.581  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:02.584  4317  7398 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:25:02.585  4317  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:25:02.585  4317  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:25:02.614  1051  1957 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7400 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 14:25:02.625  2587  2587 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 14:25:02.711  7400  7400 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 14:25:02.712  7400  7400 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 14:25:02.722  7400  7400 V [BNRBootReceiver]: Boot Receiver Return
08-16 14:25:02.723  7400  7400 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 14:25:02.726  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:02.734  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:02.741  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:02.752  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:02.752  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:25:02.754  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:25:02.758  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 14:25:02.761  6863  6863 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 14:25:02.765  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:25:02.773  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:02.779  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:02.791  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:02.791  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:02.793  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 14:25:02.801  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:02.813  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:02.823  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:02.834  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:02.835  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:02.836  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:02.837  6682  7050 D UEI.SmartControl: Internal timer expired: 2
,08-16 14:25:02.837  6682  7050 D UEI.SmartControl: unbind internal service
08-16 14:25:02.845  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:02.858  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:02.877  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:02.891  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:02.892  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:02.893  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 14:25:02.900  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:25:02.916  6682  7044 D serial_port: close(fd = 24)
08-16 14:25:02.919  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:02.923  6682  7044 I UEI.SmartControl: Serial port is closed.
08-16 14:25:02.927  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:02.939  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:25:02.939  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:02.941  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:02.949  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:02.959  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:02.971  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:02.979  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:02.980  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:02.981  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 14:25:02.989  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:03.001  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:03.016  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 14:25:03.028  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:03.029  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:03.030  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 14:25:03.043  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:03.065  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:03.082  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:03.097  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:25:03.098  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:03.109  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:03.119  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:25:03.144  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:03.161  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 14:25:03.186  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:03.187  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:25:03.189  6940  6940 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:03.201  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:03.211  6912  6912 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 14:25:03.225  1051  1560 D WifiService: New client listening to asynchronous messages
08-16 14:25:03.229  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:25:03.233  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:25:03.239  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:03.248  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:25:03.249  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:03.250  6940  6940 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 14:25:03.252  6940  6940 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 14:25:03.252  6940  6940 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 14:25:03.257  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:03.262  6912  6912 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 14:25:03.263  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:03.266  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:25:03.273  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 14:25:03.283  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:03.283  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:03.284  6940  6940 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 14:25:03.285  6940  6940 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 14:25:03.285  6940  6940 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 14:25:03.289  1051  2028 I ActivityManager: Killing 6891:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 14:25:03.319  1051  1986 W libprocessgroup: failed to open /acct/uid_10037/pid_6891/cgroup.procs: No such file or directory
,08-16 14:25:03.324  2258  2258 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 14:25:03.339  2258  2258 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 14:25:03.339  2258  2258 D c       : Getting all permits...
08-16 14:25:03.340  2258  2258 D a       : Opening database...
08-16 14:25:03.344  2258  2258 D a       : Opening database auth.proximity.permit_store...
08-16 14:25:03.347  2258  2258 D a       : Closing database...
08-16 14:25:03.361  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:25:03.366  6912  6912 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 14:25:03.367  6912  6912 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:25:03.367  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:03.371  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:03.381  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:03.388  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:03.388  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:03.391  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 14:25:03.394  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:03.397  6912  6912 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 14:25:03.397  6912  6912 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:25:03.398  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:03.402  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:03.411  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:03.418  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:25:03.418  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:03.420  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:25:03.425  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:03.429  6912  6912 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 14:25:03.429  6912  6912 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:25:03.429  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:03.434  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:03.442  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:03.449  6940  6940 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:03.450  6940  6940 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:25:03.451  6940  6940 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:25:03.462  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:03.467  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:25:03.482  6981  7428 W FormManager: Network not available. Please check & try again.
08-16 14:25:03.485  6981  7429 V FormManager: Network unavailable.
08-16 14:25:03.487  6981  7429 V FormManager: Network unavailable.
08-16 14:25:03.490  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:03.505  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 14:25:03.505  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:25:03.507  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:03.510  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:03.514  4317  7435 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:25:03.520  4317  7436 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:25:03.521  4317  7436 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:25:03.521  6912  6912 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-16 14:25:03.521  6912  6912 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:25:03.521  6912  6912 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:03.526  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:25:03.531  6981  7438 W FormManager: Network not available. Please check & try again.
08-16 14:25:03.533  6981  7439 V FormManager: Network unavailable.
,08-16 14:25:03.534  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:03.545  6981  7439 V FormManager: Network unavailable.
08-16 14:25:03.553  6940  6940 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-16 14:25:03.553  6940  6940 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:733
,08-16 14:25:03.556  1051  1051 D PowerManagerServiceEx: releaseWakeLockInternal: lock=30001972 [*alarm*], flags=0x0
08-16 14:25:03.561  2258  2258 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-16 14:25:03.776  1051  1555 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1823478752] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:25:03.785  1051  1555 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1823478744] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:25:03.981  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:25:04.000  1051  1115 D Tethering: MasterInitialState.processMessage what=3
,08-16 14:25:04.009  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:04.013  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:25:04.019  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 14:25:04.021  6477  6911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 14:25:04.031  5815  5815 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 14:25:04.045  1051  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:25:04.056  2258  2258 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:04.075  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:25:04.075  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:04.075  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:25:04.075  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 14:25:04.081  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:25:04.084  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d548ece
08-16 14:25:04.084  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:25:04.084  7061  7061 D AppUp4:CustFacade: isPhone : true
08-16 14:25:04.085  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:25:04.085  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 14:25:04.090  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:04.090  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:25:04.092  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:25:04.098  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:04.106  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 14:25:04.135  7106  7447 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:25:04.147  4317  7451 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:25:04.148  4317  7451 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 14:25:04.154  1051  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:04.159  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:25:04.159  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:04.159  4317  7448 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:25:04.160  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 14:25:04.160  3487  3487 D PhoneState: setPdpRejectCasuse : false
08-16 14:25:04.163  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 14:25:04.163  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 14:25:04.170  6981  7449 W FormManager: Network not available. Please check & try again.
,08-16 14:25:04.178  7200  7200 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:4
08-16 14:25:04.179  7200  7200 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 14:25:04.179  7200  7200 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:25:04.180  7200  7200 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:25:04.180  7200  7200 D WeatherAncestor: connectivity changed - connection : true
08-16 14:25:04.180  7200  7200 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23ce94fc
08-16 14:25:04.181  7200  7200 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:25:04.181  7200  7200 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:25:04.181  7200  7200 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 14:25:04.181  7200  7200 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 14:25:04.181  7200  7200 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:4
08-16 14:25:04.181  6981  7450 V FormManager: Network unavailable.
08-16 14:25:04.193  6981  7450 V FormManager: Network unavailable.
,08-16 14:25:04.869  1051  1731 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:04.870  1051  1731 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 14:25:04.893  1051  1051 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:25:04.893  1051  1051 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:25:04.893  1051  1051 D Ulp_jni : JNI:system_update. Event-4
,08-16 14:25:04.897  1051  1115 D BluetoothManagerService: Message: 1
08-16 14:25:04.897  1051  1115 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 14:25:04.922  1051  1115 D BluetoothManagerService: Message: 20
08-16 14:25:04.922  1051  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@205dd8c6:true
,08-16 14:25:04.927  7010  7010 D BluetoothAdapterState: make
08-16 14:25:04.932  7010  7010 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 14:25:04.932  7010  7010 I bluedroid-qcom: init
08-16 14:25:04.933  7010  7480 I BluetoothAdapterState: Entering OffState
08-16 14:25:04.933  7010  7010 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 14:25:04.934  7010  7010 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 14:25:04.934  7010  7010 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:25:04.934  7010  7010 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 14:25:04.934  7010  7010 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 14:25:04.936  7010  7010 I bluedroid-qcom: get_profile_interface socket
08-16 14:25:04.936  7010  7010 I bluedroid-qcom: get_profile_interface map_client
,08-16 14:25:04.942  7010  7484 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 14:25:04.944  7010  7484 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 14:25:04.937  7483  7483 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:04.937  7483  7483 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:04.956  1051  1051 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 14:25:04.956  1051  1051 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 14:25:04.961  1051  1051 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 14:25:04.961  1051  1115 D BluetoothManagerService: Message: 40
08-16 14:25:04.961  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 14:25:04.962  7010  7026 I bluedroid-qcom: config_hci_snoop_log
08-16 14:25:04.965  7483  7483 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 14:25:04.965  7483  7483 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 14:25:04.965  7483  7483 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 14:25:04.965  1051  1115 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 14:25:04.965  1051  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 14:25:04.967  7483  7483 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 14:25:04.971  7483  7483 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 14:25:04.971  7483  7483 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-16 14:25:04.979  7010  7480 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 14:25:04.980  7010  7484 D BluetoothAdapterProperties: Name is: G3
08-16 14:25:04.980  7010  7480 D BluetoothAdapterProperties: Setting state to 11
08-16 14:25:04.980  7010  7480 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 14:25:04.981  1051  1115 D BluetoothManagerService: Message: 60
08-16 14:25:04.981  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 14:25:04.981  1051  1115 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 14:25:04.983  7010  7480 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 14:25:04.989  1982  1982 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:25:04.993  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:25:04.994  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:04.995  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:04.996  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:04.999  6863  6863 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 14:25:05.003  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:25:05.012  7010  7010 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:25:05.013  7010  7010 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:05.013  7010  7010 V BluetoothPbapReceiver: ***********state = 11
08-16 14:25:05.027  1051  1115 D Tethering: MasterInitialState.processMessage what=3
08-16 14:25:05.029  7010  7480 D BluetoothBondStateMachine: make
,08-16 14:25:05.033  1051  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.033  7010  7497 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 14:25:05.034  7010  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.034  7010  7480 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 14:25:05.034  7010  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.034  7010  7480 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 14:25:05.035  7010  7480 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 14:25:05.041  1051  1115 D Tethering: MasterInitialState.processMessage what=3
08-16 14:25:05.042  7010  7480 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:25:05.043  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:05.046  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:05.049  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:05.051  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:05.054  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 14:25:05.058  7010  7010 D HeadsetService: Received start request. Starting profile...
,08-16 14:25:05.059  7010  7010 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:25:05.059  7010  7010 D LGBluetoothHfpAdapter: Version 1.6
08-16 14:25:05.059  2258  2258 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:25:05.061  7010  7480 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:25:05.061  6477  6911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 14:25:05.062  5815  5815 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 14:25:05.063  7010  7010 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 14:25:05.064  7010  7010 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:25:05.064  7010  7010 D HeadsetStateMachine: make
08-16 14:25:05.100  1051  1726 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7504 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 14:25:05.104  7010  7010 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:25:05.104  7010  7010 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:25:05.105  5815  5815 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 14:25:05.110  7010  7480 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:25:05.116  7010  7480 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:25:05.121  7010  7480 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:25:05.121  7010  7010 D HeadsetStateMachine: max_hf_connections = 1
08-16 14:25:05.121  7010  7010 I bluedroid-qcom: get_profile_interface handsfree
08-16 14:25:05.123  7010  7010 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 14:25:05.123   314   314 V AudioPolicyService: registerClient() client 0xb57f9a80, uid 1002
08-16 14:25:05.124   314  1402 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 14:25:05.124   314  1402 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:25:05.124   314  1402 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:25:05.124  7010  7010 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 14:25:05.124   314  1401 V AudioFlinger: registerClient() client 0xb55814f0, pid 7010
08-16 14:25:05.124   314  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:05.124   314  1395 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:05.125  7010  7010 V ToneGenerator: Create Track: 0xb4928080
08-16 14:25:05.125  7010  7010 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 14:25:05.125  7010  7010 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 14:25:05.125  7010  7028 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:05.125  7010  7028 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 14:25:05.125  1893  1908 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:05.125  1893  1908 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:05.125   314  1397 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:05.125   314  1397 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:05.125   314  1402 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 14:25:05.125  1051  1986 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:05.125   314  1402 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 14:25:05.125  1051  1986 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:05.125   314  1402 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:25:05.125   314  1402 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:25:05.125  1051  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.125  1619  1639 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:05.125  1619  1639 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:05.125  3487  3503 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:05.125  3487  3503 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:05.125  1619  2603 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:05.125  1619  2603 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:05.126  1893  2549 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-16 14:25:05.126  1893  2549 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:05.126  1051  1593 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:05.126  1051  1593 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:05.126   314  1402 I AudioFlinger: isAudioPlaybackHookOn() false
,08-16 14:25:05.126   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 14:25:05.126   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 14:25:05.126   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:25:05.126   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:25:05.126  3487  3503 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:05.126  7010  7010 V AudioSystem: getLatency() output 2, latency 50
08-16 14:25:05.126  3487  3503 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:05.126  7010  7010 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 14:25:05.126  7010  7010 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 14:25:05.126  1051  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:05.126  7010  7026 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:05.126  7010  7026 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 14:25:05.127  1051  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:05.127   314  4012 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 14:25:05.127   314  4012 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 14:25:05.127   314  4012 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 14:25:05.127   314  4012 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
,08-16 14:25:05.127   314  4012 V AudioFlinger: createTrack() lSessionId: 22
,08-16 14:25:05.129  7010  7480 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:25:05.129  7010  7010 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,08-16 14:25:05.130   314  4012 V AudioFlinger: acquiring 22 from 7010, for 7010
08-16 14:25:05.130   314  4012 V AudioFlinger:  added new entry for 22
08-16 14:25:05.130  7010  7010 V ToneGenerator: ToneGenerator INIT OK, time: 218741
08-16 14:25:05.130  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.131  7010  7503 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 14:25:05.131  7010  7503 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:25:05.131  7010  7503 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:25:05.131  7010  7503 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 14:25:05.133   314   314 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7010
08-16 14:25:05.133   314   314 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 14:25:05.133   314   314 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 14:25:05.133   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 14:25:05.133   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 14:25:05.133   314   314 V voice   : voice_set_parameters: exit with code(0)
08-16 14:25:05.133   314   314 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 14:25:05.133   314   314 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 14:25:05.133   314   314 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 14:25:05.133   314   314 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 14:25:05.133   314   314 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 14:25:05.133   314   314 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 14:25:05.133  7010  7503 V ToneGenerator: ToneGenerator destructor
08-16 14:25:05.133  7010  7503 V ToneGenerator: stopTone
08-16 14:25:05.134  7010  7503 V ToneGenerator: Delete Track: 0xb4928080
08-16 14:25:05.134  7010  7503 V AudioTrack: ~AudioTrack, releasing session id from 7010 on behalf of 7010
08-16 14:25:05.134  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.135   314  4012 V AudioFlinger: releasing 22 from 7010 for 7010
08-16 14:25:05.135   314  4012 V AudioFlinger:  decremented refcount to 0
08-16 14:25:05.135   314  4012 V AudioFlinger: purging stale effects
08-16 14:25:05.135   314  4012 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 14:25:05.135   314  4012 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 14:25:05.135   314  1281 V AudioPolicyService: AudioCommandThread() waking up
08-16 14:25:05.135   314  1281 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 14:25:05.135   314  1281 V AudioPolicyManager: releaseOutput() 2
08-16 14:25:05.135   314  1281 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 14:25:05.135   314  4012 V AudioFlinger: PlaybackThread::Track destructor
08-16 14:25:05.135   314  4012 V AudioFlinger: removeClient_l() pid 7010, calling pid 314
08-16 14:25:05.136  1051  2028 W Process : Unable to open /proc/7521/status
08-16 14:25:05.136  2258  2258 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.136  7010  7010 D A2dpService: Received start request. Starting profile...
08-16 14:25:05.137  7010  7010 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 14:25:05.138  7010  7010 V Avrcp   : make
08-16 14:25:05.138  7010  7010 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 14:25:05.138  7010  7010 I bluedroid-qcom: get_profile_int,erface avrcp
08-16 14:25:05.143  7010  7480 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:25:05.146  7010  7010 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 14:25:05.147  7010  7010 E AudioManager: No RCC entry present to update
08-16 14:25:05.147  7010  7010 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 14:25:05.149  7010  7010 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 14:25:05.150  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 14:25:05.150  7010  7010 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 14:25:05.156  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 14:25:05.156  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:25:05.156  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.156  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:25:05.156  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 14:25:05.158  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 14:25:05.162  7010  7480 V LGMDMManager: Create singleton instance
08-16 14:25:05.164  7010  7480 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 14:25:05.168  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d548ece
08-16 14:25:05.168  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:25:05.168  7061  7061 D AppUp4:CustFacade: isPhone : true
08-16 14:25:05.185  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
,08-16 14:25:05.185  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 14:25:05.194  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.194  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:25:05.196  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:05.199  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:25:05.202  4317  7525 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:25:05.205  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 14:25:05.208  4317  7526 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.208  4317  7526 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:25:05.220  7106  7527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:25:05.223  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:25:05.223  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.223  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 14:25:05.225  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 14:25:05.225  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 14:25:05.230  1051  1986 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:25:05.230  1051  1986 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:25:05.231  6981  7529 W FormManager: Network not available. Please check & try again.
08-16 14:25:05.234  7200  7200 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:5
,08-16 14:25:05.237  6981  7532 V FormManager: Network unavailable.
,08-16 14:25:05.239  7200  7200 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 14:25:05.239  7200  7200 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:25:05.240  7200  7200 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:25:05.240  7200  7200 D WeatherAncestor: connectivity changed - connection : true
08-16 14:25:05.240  7200  7200 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23ce94fc
08-16 14:25:05.240  7504  7504 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 14:25:05.240  7504  7504 W LG Account v2.2: No ProfileInfo entries
08-16 14:25:05.240  7504  7504 I LG Account v2.2: isEnabled: false
08-16 14:25:05.240  6981  7532 V FormManager: Network unavailable.
08-16 14:25:05.240  7504  7504 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 14:25:05.240  7504  7504 I Feature : [Lifetracker]Country: EU
08-16 14:25:05.241  7504  7504 I Feature : [Lifetracker]Operator: OPEN
08-16 14:25:05.241  7504  7504 I Feature : [Lifetracker]Ranking support: false
08-16 14:25:05.241  7504  7504 I Feature : [Lifetracker]Comfort support: false
08-16 14:25:05.241  7504  7504 I Feature : [Lifetracker]Accessory: true
08-16 14:25:05.241  7504  7504 I Feature : [Lifetracker]Health device: true
08-16 14:25:05.241  7504  7504 I Feature : [Lifetracker]Extra Pedometer: false
08-16 14:25:05.241  7504  7504 I Feature : [Lifetracker]Blood glucose device: false
08-16 14:25:05.241  7200  7200 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:25:05.241  7504  7504 I Feature : [Lifetracker]Device Number: 3
08-16 14:25:05.241  7200  7200 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:25:05.241  7200  7200 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 14:25:05.241  7200  7200 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 14:25:05.241  7200  7200 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:5
08-16 14:25:05.254  6863  6863 D BluetoothPermissionRequest: onReceive
,08-16 14:25:05.262  6477  6477 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 14:25:05.262  6863  6863 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:25:05.263  6477  6911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 14:25:05.274  2258  2258 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:25:05.277  1051  2127 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 14:25:05.280  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:25:05.280  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.280  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:25:05.280  7061  7061 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 14:25:05.281  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 14:25:05.281  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 14:25:05.284  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d548ece
08-16 14:25:05.284  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:25:05.284  7061  7061 D AppUp4:CustFacade: isPhone : true
08-16 14:25:05.284  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
,08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 14:25:05.284  7061  7061 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:25:05.284  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 14:25:05.285  7010  7010 I BluetoothA2dpServiceJni: classInitNative
08-16 14:25:05.285  7010  7010 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:25:05.285  7010  7010 D A2dpStateMachine: make
08-16 14:25:05.286  7010  7010 I bluedroid-qcom: get_profile_interface a2dp
08-16 14:25:05.286  7010  7535 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 14:25:05.287  7010  7010 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:25:05.287  7010  7010 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 14:25:05.287  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.287  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:25:05.288  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.289  7010  7534 D A2dpStateMachine: Enter Disconnected: -2
08-16 14:25:05.289  7010  7010 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 14:25:05.289  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:05.290  7010  7010 D HidService: Received start request. Starting profile...
08-16 14:25:05.290  7010  7010 I bluedroid-qcom: get_profile_interface hidhost
08-16 14:25:05.290  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.290  7010  7010 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:25:05.290  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:05.291  7010  7010 D HealthService: Received start request. Starting profile...
08-16 14:25:05.292  7010  7010 I bluedroid-qcom: get_profile_interface health
08-16 14:25:05.292  7010  7010 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:25:05.292  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.292  7010  7010 D HeadsetStateMachine: Proxy object connected
08-16 14:25:05.293  7010  7010 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 14:25:05.293  7010  7010 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 14:25:05.293  4317  7539 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:25:05.294  7010  7010 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 14:25:05.295  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 14:25:05.295  7010  7010 D PanService: Received start request. Starting profile...
08-16 14:25:05.295  7010  7010 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:25:05.295  7010  7010 I bluedroid-qcom: get_profile_interface pan
08-16 14:25:05.298  4317  7541 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.298  4317  7541 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 14:25:05.300  7010  7010 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 14:25:05.300  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.301  7010  7010 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 14:25:05.305  7010  7010 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:25:05.306  7010  7010 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:25:05.306  7010  7010 D BtGatt.GattService: Received start request. Starting profile...
08-16 14:25:05.307  7010  7010 D BtGatt.GattService: start()
08-16 14:25:05.307  7010  7010 I bluedroid-qcom: get_profile_interface gatt
08-16 14:25:05.307  7010  7010 D BtGatt.AdvertiseManager: advertise manager created
08-16 14:25:05.312  6981  7545 W FormManager: Network not available. Please check & try again.
,08-16 14:25:05.313  7106  7543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:05.314  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.315  7010  7503 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 14:25:05.315  7010  7503 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:25:05.315  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.315  7010  7503 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-16 14:25:05.316  7010  7010 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 14:25:05.316  6981  7546 V FormManager: Network unavailable.
08-16 14:25:05.316  7010  7010 V BluetoothMapService: BluetoothMapBinder()
08-16 14:25:05.316  7010  7010 D BluetoothMapService: Received start request. Starting profile...
08-16 14:25:05.316  7010  7010 D BluetoothMapService: start()
08-16 14:25:05.319  3487  3487 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:25:05.319  3487  3487 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:05.319  3487  3487 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 14:25:05.322  7010  7010 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 14:25:05.322  7010  7010 D BluetoothMapEmailAppObserver: createReceiver()
08-16 14:25:05.323  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 14:25:05.323  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 14:25:05.323  7010  7010 D BluetoothMapEmailAppObserver: initObservers()
08-16 14:25:05.323  7010  7010 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 14:25:05.328  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
,08-16 14:25:05.330  7010  7010 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:25:05.330  6981  7546 V FormManager: Network unavailable.
08-16 14:25:05.332  7010  7010 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:25:05.334  7010  7010 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:25:05.335  7010  7010 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 14:25:05.336  7010  7010 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:25:05.338  7200  7200 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:5
08-16 14:25:05.339  7010  7010 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 14:25:05.339  7010  7010 V BluetoothMapService: Handler(): got msg=1
08-16 14:25:05.339  7010  7480 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 14:25:05.339  7010  7480 I bluedroid-qcom: enable
08-16 14:25:05.340  7010  7480 I bt_hci_bdroid: init
08-16 14:25:05.340  7010  7550 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 14:25:05.340  7010  7550 I bt-btu  : btu_task pending for preload complete event
,08-16 14:25:05.342  7010  7010 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:05.342  7010  7480 I bt_vendor: bt-vendor : init
08-16 14:25:05.342  7010  7480 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 14:25:05.342  7010  7480 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 14:25:05.342  7010  7480 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 14:25:05.342  7010  7480 D bt_userial_mct: userial_init
08-16 14:25:05.342  7200  7200 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 14:25:05.342  7010  7480 D bt_hci_bdroid: set_power 1
08-16 14:25:05.342  7010  7480 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 14:25:05.342  7010  7480 I bt_vendor: Starting hciattach daemon
08-16 14:25:05.342  7010  7480 I bt_vendor: try to set true
08-16 14:25:05.343  7200  7200 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:25:05.343  7010  7010 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:25:05.343  7010  7010 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:25:05.343  7010  7010 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:25:05.343  7010  7010 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:05.343  7010  7010 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 14:25:05.337  7553  7553 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:05.337  7553  7553 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:05.346  7200  7200 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:25:05.346  7200  7200 D WeatherAncestor: connectivity changed - connection : true
08-16 14:25:05.346  7200  7200 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23ce94fc
08-16 14:25:05.347  7200  7200 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:25:05.347  7200  7200 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:25:05.347  7200  7200 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 14:25:05.347  7200  7200 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 14:25:05.347  7200  7200 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:25:5
08-16 14:25:05.358  7554  7554 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 14:25:05.397  7560  7560 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 14:25:05.405  7561  7561 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 14:25:05.419  7563  7563 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 14:25:05.426  7564  7564 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 14:25:05.433  7565  7565 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 14:25:05.440  7566  7566 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 14:25:05.469  7568  7568 I libmdmdetect: ESOC framework not supported
08-16 14:25:05.469  7568  7568 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 14:25:05.475  7568  7568 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 14:25:05.475  7568  7568 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 14:25:05.475  7568  7568 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 14:25:05.475  7568  7568 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 14:25:05.476  7568  7568 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 14:25:05.476  7568  7568 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 14:25:05.476  7568  7568 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 14:25:05.514  7568  7569 E QC-QMI  : qmi_client [7568] 14: failed to locate client data
08-16 14:25:05.515   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-16 14:25:05.515   444   444 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-16 14:25:05.581  7570  7570 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 14:25:05.598  7571  7571 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 14:25:05.644  7010  7480 I bt_vendor: bluetooth satus is on
,08-16 14:25:05.644  7010  7480 D bt_hci_bdroid: preload
08-16 14:25:05.645  7010  7552 D bt_userial_mct: userial_open(port:0)
08-16 14:25:05.645  7010  7552 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 14:25:05.649  7010  7552 I bt_vendor: Done intiailizing UART
08-16 14:25:05.649  7010  7552 I bt_vendor: Done intiailizing UART
08-16 14:25:05.650  7010  7552 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 14:25:05.650  7010  7552 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 14:25:05.650  7010  7550 I bt-btu  : btu_task received preload complete event
08-16 14:25:05.651  7010  7550 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 14:25:05.651  7010  7550 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 14:25:05.656  7010  7550 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-16 14:25:05.659  7010  7576 D bt_userial_mct: Entering userial_read_thread()
08-16 14:25:05.663  7010  7550 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 14:25:05.663  7010  7550 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:25:05.664  7010  7550 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 14:25:05.720  7010  7550 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 14:25:05.720  7010  7550 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01da061 
08-16 14:25:05.720  7010  7550 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01da061 
,08-16 14:25:05.757  7010  7484 E bt-btif : Calling BTA_HhEnable
08-16 14:25:05.758  7010  7484 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 14:25:05.758  7010  7550 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-16 14:25:05.758  7010  7550 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 14:25:05.758  7010  7550 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 14:25:05.758  7010  7484 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 14:25:05.760  1051  1051 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 14:25:05.761  7010  7484 D BluetoothAdapterProperties: Name is: G3
08-16 14:25:05.762  7010  7550 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 14:25:05.762  7010  7550 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 14:25:05.764  1051  1051 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 14:25:05.765  7010  7484 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:25:05.765  7010  7484 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:25:05.766  7010  7484 D bt_hci_bdroid: postload
08-16 14:25:05.766  7010  7484 D bte_conf: Device ID record 1 : primary
08-16 14:25:05.766  7010  7484 D bte_conf:   vendorId            = 00c4
08-16 14:25:05.766  7010  7484 D bte_conf:   vendorIdSource      = 0001
08-16 14:25:05.766  7010  7484 D bte_conf:   product             = 13a1
08-16 14:25:05.766  7010  7484 D bte_conf:   version             = 1000
08-16 14:25:05.766  7010  7484 D bte_conf:   clientExecutableURL = 
08-16 14:25:05.767  7010  7484 D bte_conf:   serviceDescription  = 
08-16 14:25:05.767  7010  7484 D bte_conf:   documentationURL    = 
08-16 14:25:05.767  7010  7550 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 14:25:05.767  7010  7484 D bte_conf: bte_load_did_conf no section named DID2.
08-16 14:25:05.767  7010  7552 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:25:05.769  7010  7552 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:25:05.769  7010  7552 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:25:05.771  7010  7552 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:25:05.771  7010  7552 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 14:25:05.771  7010  7480 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 14:25:05.772  7010  7480 D BluetoothAdapterProperties: ScanMode =  20
08-16 14:25:05.772  7010  7480 D BluetoothAdapterProperties: State =  11
08-16 14:25:05.772  7010  7480 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 14:25:05.772  7010  7480 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 14:25:05.772  7010  7480 D BluetoothAdapterProperties: Setting state to 12
08-16 14:25:05.772  7010  7480 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 14:25:05.773  1051  1115 D BluetoothManagerService: Message: 60
08-16 14:25:05.773  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 14:25:05.776  7010  7480 I BluetoothAdapterState: Entering On State
08-16 14:25:05.767  7581  7581 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:05.767  7581  7581 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:05.778  7010  7576 E bt_mct  : hci lib postload completed
08-16 14:25:05.778  7010  7484 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 14:25:05.779  7010  7484 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 14:25:05.773  1051  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 14:25:05.784  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:05.784  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:05.784  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:05.784  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:05.784  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:05.784  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:05.784  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:05.784  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:25:05.786  7010  7550 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:25:05.786  7010  7550 W bt-smp  : Plain text(LSB ~ MSB) = 59 60 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:05.786  7010  7550 W bt-smp  : Encrypted text(LSB ~ MSB) = ba 4d c1 f9 12 3d 96 eb 69 de c9 b2 1c 32 83 45 
08-16 14:25:05.787  7010  7550 W bt-btm  : Stopping oneshot timer
,08-16 14:25:05.786  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:25:05.797  7010  7480 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 14:25:05.797  7010  7480 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 14:25:05.797  7010  7480 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 14:25:05.800  7010  7480 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 14:25:05.809  7010  7484 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:25:05.809  7010  7484 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 14:25:05.813  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:05.813  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:05.813  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:05.813  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:05.813  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:05.813  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:05.813  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:05.813  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:25:05.815  7010  7550 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:25:05.815  7010  7550 W bt-smp  : Plain text(LSB ~ MSB) = 8b 59 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:05.816  7010  7550 W bt-smp  : Encrypted text(LSB ~ MSB) = 42 31 07 62 c8 a8 b3 88 62 73 18 e9 6c ec 90 7e 
08-16 14:25:05.816  7010  7550 W bt-btm  : Stopping oneshot timer
08-16 14:25:05.817  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:25:05.817  6863  6889 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 14:25:05.820  6863  6890 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:25:05.825  6863  6889 D BluetoothPan: onBluetoothStateChange on: true
08-16 14:25:05.825  6863  6889 D BluetoothPan: onBluetoothStateChange call bindService
,08-16 14:25:05.828  7010  7480 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 14:25:05.832  1051  1115 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:25:05.833  7010  7550 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:25:05.833  7010  7550 W bt-smp  : Plain text(LSB ~ MSB) = b4 1a 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:05.833  7010  7550 W bt-smp  : Encrypted text(LSB ~ MSB) = 88 a6 dd e2 8f a5 08 37 e9 7d 88 51 49 c1 21 34 
08-16 14:25:05.833  7010  7550 W bt-btm  : Stopping oneshot timer
08-16 14:25:05.835  1051  1051 D BluetoothHeadset: Proxy object connected
08-16 14:25:05.837  6863  6863 D BluetoothMap: Proxy object connected
08-16 14:25:05.837  6863  6863 D MapProfile: Bluetooth service connected
08-16 14:25:05.837  6863  6863 D BluetoothMap: getConnectedDevices()
08-16 14:25:05.837  1893  1909 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:25:05.846  7010  7026 V BluetoothMapService: getConnectedDevices()
,08-16 14:25:05.850  1893  1893 D BluetoothHeadset: Proxy object connected
08-16 14:25:05.852  7010  7550 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:25:05.852  7010  7550 W bt-smp  : Plain text(LSB ~ MSB) = 5d 6a 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:05.852  7010  7550 W bt-smp  : Encrypted text(LSB ~ MSB) = c2 e3 5f 4d 9d 94 b9 eb b5 50 c3 24 03 dd 69 b6 
08-16 14:25:05.852  7010  7550 W bt-btm  : Stopping oneshot timer
08-16 14:25:05.852  6863  6890 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 14:25:05.854  6863  6863 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:25:05.854  6863  6863 D PanProfile: Bluetooth service connected
08-16 14:25:05.859  1051  1115 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:25:05.860  1893  2549 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 14:25:05.863  1051  1051 D BluetoothA2dp: Proxy object connected
08-16 14:25:05.864  1893  1893 D BluetoothHeadset: Proxy object connected
08-16 14:25:05.864  7010  7550 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:25:05.864  7010  7550 W bt-smp  : Plain text(LSB ~ MSB) = 28 f7 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:05.864  1893  2549 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:25:05.864  7010  7550 W bt-smp  : Encrypted text(LSB ~ MSB) = f7 a7 a0 8d b7 98 a2 ab 89 f0 08 c2 c6 2f c1 de 
08-16 14:25:05.864  7010  7550 W bt-btm  : Stopping oneshot timer
08-16 14:25:05.866  7595  7595 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 14:25:05.867  1893  1893 D BluetoothHeadset: Proxy object connected
08-16 14:25:05.868  6863  6863 D BluetoothInputDevice: Proxy object connected
08-16 14:25:05.868  6863  6863 D HidProfile: Bluetooth service connected
08-16 14:25:05.869  1051  1115 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 14:25:05.869  1051  1115 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 14:25:05.870  1982  1982 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:25:05.870  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:25:05.874  1982  2193 D LGBluetoothAPIService: Message: 1
08-16 14:25:05.874  1982  2193 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 14:25:05.879  1051  1051 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 14:25:05.879  1982  2193 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 14:25:05.880  6780  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 14:25:05.881  1051  1115 D BluetoothManagerService: Message: 40
08-16 14:25:05.881  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 14:25:05.882  6863  6863 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-16 14:25:05.884  7010  7010 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:05.884  7010  7010 D BluetoothMapService: STATE_ON
08-16 14:25:05.885  1051  1115 D BluetoothManagerService: Message: 30
08-16 14:25:05.885  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:05.886  7010  7010 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 14:25:05.887  7010  7010 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 14:25:05.888  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:05.888  1982  1982 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 14:25:05.893  1982  2193 D LGBluetoothAPIService: Message: 100
08-16 14:25:05.893  1982  2193 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 14:25:05.900  6863  6863 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 14:25:05.903  1051  1115 D BluetoothManagerService: Message: 30
08-16 14:25:05.905  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:05.905  7010  7010 V BluetoothPbapService: Pbap Service onCreate
08-16 14:25:05.906  7010  7010 V BluetoothPbapService: Starting PBAP service
08-16 14:25:05.907  7010  7010 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 14:25:05.907  7010  7010 V BluetoothMapService: Handler(): got msg=1
08-16 14:25:05.907  6863  6863 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 14:25:05.908  7010  7010 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 14:25:05.909  7010  7010 V BluetoothPbapService: Pbap Service onBind
08-16 14:25:05.909  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 14:25:05.910  7010  7599 D BluetoothMapMasInstance: MAS initSocket()
08-16 14:25:05.910  7010  7599 D BluetoothMapMasInstance:   masId = 00
08-16 14:25:05.910  7010  7599 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 14:25:05.910  7010  7599 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 14:25:05.910  7010  7599 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 14:25:05.911  1051  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:05.912  7010  7010 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:25:05.912  7010  7010 V BluetoothPbapService: state: 12
08-16 14:25:05.912  7010  7010 V BluetoothPbapService: Handler(): got msg=1
08-16 14:25:05.912  6863  6863 D BluetoothA2dp: Proxy object connected
08-16 14:25:05.912  6863  6863 D A2dpProfile: Bluetooth service connected
08-16 14:25:05.914  6863  6863 D BluetoothHeadset: Proxy object connected
08-16 14:25:05.914  7010  7010 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 14:25:05.915  7010  7010 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:25:05.915  7010  7010 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:05.915  7010  7010 V BluetoothPbapReceiver: ***********state = 12
08-16 14:25:05.915  6863  6863 D HeadsetProfile: Bluetooth service connected
08-16 14:25:05.915  7010  7600 V BluetoothPbapService: Pbap Service initSocket
08-16 14:25:05.916  1051  1734 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:05.916  7010  7599 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:25:05.917  7010  7600 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:25:05.919  2258  2258 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:25:05.922  7010  7600 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 14:25:05.922  7010  7599 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 14:25:05.922  7010  7599 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 14:25:05.922  7010  7599 D BluetoothMapMasInstance: Accepting socket connection...
08-16 14:25:05.922  2258  2258 D c       : Getting all permits...
08-16 14:25:05.922  2258  2258 D a       : Opening database...
08-16 14:25:05.922  7010  7600 V BluetoothPbapService: Succeed to create listening socket 
08-16 14:25:05.922  7010  7600 V BluetoothPbapService: Accepting socket connection...
08-16 14:25:05.925  7010  7484 D BluetoothAdapterProperties: Scan Mode:21
,08-16 14:25:05.925  6863  6863 D DockEventReceiver: finishStartingService: stopping service
08-16 14:25:05.925  7010  7484 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 14:25:05.925  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:05.926  2258  2258 D a       : Opening database auth.proximity.permit_store...
08-16 14:25:05.926  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:05.927  2258  2258 D a       : Closing database...
08-16 14:25:05.928  6863  6863 D BluetoothPbap: Proxy object connected
,08-16 14:25:05.929  6863  6863 D PbapServerProfile: Bluetooth service connected
08-16 14:25:05.938  6863  6863 D BluetoothPermissionRequest: onReceive
,08-16 14:25:05.940  6863  6863 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 14:25:05.942  6863  6863 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:25:05.944  7010  7010 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 14:25:05.945  7010  7010 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 14:25:05.951  7010  7010 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 14:25:05.966  7010  7010 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 14:25:05.967  7010  7010 V BtOppService: onCreate
,08-16 14:25:05.970  7010  7010 V BluetoothOppNotification: send message
08-16 14:25:05.973  7010  7010 V BtOppService: Starting RfcommListener
08-16 14:25:05.978  7010  7010 D BluetoothOppPreference: Dumping Names:  
08-16 14:25:05.978  7010  7010 D BluetoothOppPreference: {}
08-16 14:25:05.978  7010  7010 D BluetoothOppPreference: Dumping Channels:  
08-16 14:25:05.978  7010  7010 D BluetoothOppPreference: {}
,08-16 14:25:05.978  7010  7010 V BtOppService: onStartCommand
08-16 14:25:05.984  7010  7609 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 14:25:05.986  7010  7010 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:05.986  7010  7010 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 14:25:05.989  7010  7010 V BluetoothOppNotification: new notify threadi!
08-16 14:25:05.990  7010  7010 V BluetoothOppNotification: send delay message
08-16 14:25:05.991  7010  7010 V BtOppService: start RfcommListener
,08-16 14:25:05.996  7010  7611 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 14:25:05.997  7010  7606 V BtOppService: Deleted complete outbound shares, number =  0
08-16 14:25:05.997  7010  7609 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 14:25:05.997  7010  7010 V BtOppService: RfcommListener started
08-16 14:25:05.999  1051  1734 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:05.999  7010  7610 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 14:25:06.000  7010  7611 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:25:06.001  7010  7611 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-16 14:25:06.001  7010  7611 V BtOppRfcommListener: Started RFCOMM listener....
08-16 14:25:06.001  7010  7611 I BtOppRfcommListener: Accept thread started.
08-16 14:25:06.001  7010  7611 V BtOppRfcommListener: Accepting connection...
08-16 14:25:06.002  7010  7609 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3762d51 on behalf of 
08-16 14:25:06.005  7010  7610 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18c629b6 on behalf of 
08-16 14:25:06.007  7010  7606 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-16 14:25:06.007  7010  7606 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 14:25:06.008  7010  7609 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 14:25:06.008  7010  7609 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 14:25:06.009  7010  7606 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25d966b7 on behalf of 
08-16 14:25:06.010  7010  7610 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 14:25:06.012  7010  7610 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 14:25:06.014  7010  7609 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@366ae24 on behalf of 
08-16 14:25:06.014  7010  7610 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f9f4d8d on behalf of 
08-16 14:25:06.014  7010  7609 V BluetoothOppNotification: update too frequent, put in queue
08-16 14:25:06.015  7010  7609 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 14:25:06.016  7010  7610 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 14:25:06.018  7010  7610 V BluetoothOppNotification: outbound notification was removed.
08-16 14:25:06.018  7010  7610 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 14:25:06.019  7010  7610 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38832b42 on behalf of 
08-16 14:25:06.020  7010  7610 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 14:25:06.021  7010  7610 V BluetoothOppNotification: inbound notification was removed.
08-16 14:25:06.021  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:06.021  7010  7610 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 14:25:06.021  7010  7010 V BluetoothFtpService: Ftp Service onCreate
08-16 14:25:06.021  7010  7010 I BluetoothFtpService: Ftp Service onCreate
08-16 14:25:06.021  7010  7010 V BluetoothFtpService: Ftp Service onStartCommand
08-16 14:25:06.021  7010  7010 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:06.022  7010  7010 V BluetoothFtpService: Starting Listening on sockets
08-16 14:25:06.022  7010  7010 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:25:06.022  7010  7010 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:25:06.022  7010  7010 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:25:06.022  7010  7010 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:25:06.022  7010  7010 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 14:25:06.022  7010  7610 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d728890 on behalf of 
08-16 14:25:06.022  7010  7010 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 14:25:06.025  7010  7010 V BtOppService: ContentObserver received notification
08-16 14:25:06.025  7010  7010 V BtOppService: ContentObserver received notification
08-16 14:25:06.025  7010  7010 V BluetoothFtpService: Handler(): got msg=1
08-16 14:25:06.026  7010  7612 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 14:25:06.026  7010  7612 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 14:25:06.027  7010  7010 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 14:25:06.027  7010  7010 V BluetoothFtpService: Ftp Service initSocket
08-16 14:25:06.029  7010  7612 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ec03589 on behalf of 
08-16 14:25:06.030  7010  7612 V BluetoothOppNotification: update too frequent, put in queue
08-16 14:25:06.030  7010  7612 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 14:25:06.031  1051  1066 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:06.031  7010  7010 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:25:06.032  7010  7010 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-16 14:25:06.032  7010  7010 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 14:25:06.034  7010  7613 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 14:25:06.043  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
,08-16 14:25:06.043  7010  7010 V BluetoothSapService: Sap Service onCreate
08-16 14:25:06.044  7010  7010 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:06.044  7010  7010 V BluetoothSapService: state: 12
08-16 14:25:06.044  7010  7010 V BluetoothSapService: Starting SAP server process
08-16 14:25:06.045  7010  7010 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 14:25:06.047  7010  7615 V BluetoothSapService: Sap Service initRfcommSocket
08-16 14:25:06.047  1051  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:06.037  7614  7614 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:06.048  7010  7615 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:25:06.037  7614  7614 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:06.048  7010  7615 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 14:25:06.049  7010  7615 V BluetoothSapService: Succeed to create listening socket 
08-16 14:25:06.049  7010  7615 V BluetoothSapService: Accepting socket connection...
08-16 14:25:06.058  7614  7614 V BT_SAP  : Event pipe created
,08-16 14:25:06.058  7614  7614 V BT_SAP  : create_server_socket qcom.sap.server
08-16 14:25:06.058  7614  7614 V BT_SAP  : created socket fd 6
08-16 14:25:06.390  7236  7297 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 14:25:06.915  1051  1553 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:06.915  1051  1553 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:25:06.983  1051  1555 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 14:25:06.984  1051  1555 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 14:25:06.992  7010  7010 V BluetoothOppNotification: new notify threadi!
08-16 14:25:06.993  7010  7010 V BluetoothOppNotification: send delay message
08-16 14:25:06.997  7010  7627 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 14:25:07.171  1051  1734 I art     : Explicit concurrent mark sweep GC freed 94324(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.864ms total 159.574ms
,08-16 14:25:07.173  7010  7627 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@aeda145 on behalf of 
08-16 14:25:07.177  7010  7627 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 14:25:07.178  7010  7627 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 14:25:07.179  7010  7627 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@eaee09a on behalf of 
08-16 14:25:07.180  7010  7627 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 14:25:07.181  7010  7627 V BluetoothOppNotification: outbound notification was removed.
08-16 14:25:07.181  7010  7627 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 14:25:07.182  7010  7627 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a00bdcb on behalf of 
08-16 14:25:07.182  7010  7627 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 14:25:07.186  7010  7627 V BluetoothOppNotification: inbound notification was removed.
,08-16 14:25:07.186  7010  7627 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 14:25:07.187  7010  7627 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2226d9a8 on behalf of 
08-16 14:25:07.376  1051  1396 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3e8ef972 type 2 when 220967 android} when 220967
,08-16 14:25:07.440  1051  2071 I ActivityManager: Killing 7400:com.lge.bnr/1000 (adj 15): empty #17
,08-16 14:25:07.474  1051  1986 W libprocessgroup: failed to open /acct/uid_1000/pid_7400/cgroup.procs: No such file or directory
,08-16 14:25:07.550  1051  1067 I ActivityManager: Killing 6912:com.lge.sync/1000 (adj 15): empty #17
,08-16 14:25:07.572  1051  1560 D WifiService: Client connection lost with reason: 4
,08-16 14:25:07.581  1051  1593 W libprocessgroup: failed to open /acct/uid_1000/pid_6912/cgroup.procs: No such file or directory
08-16 14:25:07.911  1051  2071 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:07.912  1051  2071 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@130d21c3 mBinding = false
,08-16 14:25:07.940  1051  1051 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:25:07.941  1051  1051 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:25:07.941  1051  1051 D Ulp_jni : JNI:system_update. Event-4
,08-16 14:25:07.944  1051  1115 D BluetoothManagerService: Message: 2
08-16 14:25:07.945  1051  1115 D BluetoothManagerService: Sending off request.
08-16 14:25:07.946  7010  7028 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 14:25:07.946  7010  7480 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 14:25:07.947  7010  7480 D BluetoothAdapterProperties: Setting state to 13
08-16 14:25:07.947  7010  7480 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 14:25:07.947  7010  7480 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 14:25:07.948  7010  7480 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 14:25:07.949  7010  7484 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:25:07.951  7010  7480 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 14:25:07.953  7010  7611 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 14:25:07.956  7010  7613 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:25:07.957  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 14:25:07.958  7010  7600 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:25:07.958  7010  7550 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 14:25:07.959  7010  7480 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 14:25:07.961  7010  7599 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 14:25:07.961  7010  7599 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:25:07.961  7010  7599 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 14:25:07.961  7010  7599 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 14:25:07.961  7010  7599 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 14:25:07.961  7010  7599 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 14:25:07.961  7010  7599 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 14:25:07.961  7010  7599 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 14:25:07.965  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 14:25:07.965  7010  7550 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-16 14:25:07.978  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:07.978  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:07.978  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:07.978  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:07.978  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:07.978  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:25:07.978  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:07.978  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:07.978  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:25:07.981  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:07.981  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:25:07.986  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:07.986  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:07.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:07.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:07.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:07.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:25:07.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:07.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:07.986  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:25:07.987  6780  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:25:07.987  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:25:07.988  1051  1115 D BluetoothManagerService: Message: 60
08-16 14:25:07.988  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 14:25:07.989  1051  1115 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 14:25:07.992  1982  1982 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:25:07.995  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:25:08.001  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:08.004  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:25:08.007  7010  7010 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:08.008  7010  7010 D BluetoothMapService: STATE_TURNING_OFF
08-16 14:25:08.008  7010  7010 V BluetoothMapService: Handler(): got msg=4
08-16 14:25:08.008  7010  7010 D BluetoothMapService: MAP Service closeService in
08-16 14:25:08.008  7010  7010 D BluetoothMapMasInstance: MAP Service shutdown
08-16 14:25:08.008  7010  7010 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:25:08.008  7010  7010 V BluetoothMapService: MAP Service closeService out
08-16 14:25:08.010  7010  7010 V BtOppService: Receiver DISABLED_ACTION 
08-16 14:25:08.010  7010  7010 I BtOppRfcommListener: stopping Accept Thread
08-16 14:25:08.010  7010  7010 V BtOppRfcommListener: close mBtServerSocket
08-16 14:25:08.010  7010  7611 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 14:25:08.011  7010  7010 V BtOppRfcommListener: waiting for thread to terminate
08-16 14:25:08.011  7010  7010 V BtOppRfcommListener: done waiting for thread to terminate
08-16 14:25:08.014  6863  6863 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-16 14:25:08.024  7010  7615 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:25:08.029  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 14:25:08.031  7010  7010 V BtOppService: onDestroy
08-16 14:25:08.033  7010  7010 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 14:25:08.037  7010  7010 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:25:08.037  7010  7010 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:08.037  7010  7010 V BluetoothPbapReceiver: ***********state = 13
,08-16 14:25:08.041  7010  7010 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 14:25:08.043  7010  7010 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:08.043  7010  7010 V BluetoothPbapService: state: 13
08-16 14:25:08.043  7010  7010 V BluetoothPbapService: Pbap Service closeService in
08-16 14:25:08.046  2258  2258 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:25:08.048  7010  7010 V BluetoothPbapService: successfully stopped pbap service
08-16 14:25:08.048  7010  7010 V BluetoothPbapService: Pbap Service closeService out
08-16 14:25:08.049  7010  7010 V BluetoothPbapService: Pbap Service onDestroy
08-16 14:25:08.049  7010  7010 V BluetoothPbapService: Pbap Service closeService in
08-16 14:25:08.049  7010  7010 V BluetoothPbapService: Pbap Service closeService out
08-16 14:25:08.049  7010  7010 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-16 14:25:08.083  6863  6863 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:25:08.087  6863  6863 D BluetoothPbap: Proxy object disconnected
08-16 14:25:08.087  6863  6863 D PbapServerProfile: Bluetooth service disconnected
08-16 14:25:08.092  6863  6863 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 14:25:08.096  6863  6863 D BluetoothPermissionRequest: onReceive
08-16 14:25:08.096  6863  6863 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 14:25:08.103  6863  6863 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:25:08.107  7010  7010 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 14:25:08.107  7010  7010 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 14:25:08.109  7010  7010 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 14:25:08.115  7010  7010 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:08.115  7010  7010 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 14:25:08.117  7010  7010 V BluetoothFtpService: Ftp Service onStartCommand
08-16 14:25:08.117  7010  7010 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:08.118  7010  7010 V BluetoothFtpService: Ftp Service closeService
08-16 14:25:08.118  7010  7010 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 14:25:08.120  7010  7010 V BluetoothFtpService: successfully stopped ftp service
08-16 14:25:08.120  7010  7010 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:25:08.121  7010  7010 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:25:08.121  7010  7010 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:25:08.121  7010  7010 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:08.121  7010  7010 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 14:25:08.121  7010  7010 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 14:25:08.123  7010  7010 V BluetoothFtpService: Ftp Service onDestroy
08-16 14:25:08.123  7010  7010 V BluetoothFtpService: Ftp Service closeService
,08-16 14:25:08.129  7010  7010 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:08.129  7010  7010 V BluetoothSapService: state: 13
08-16 14:25:08.129  7010  7010 V BluetoothSapService: Stopping SAP server process
08-16 14:25:08.131  7010  7010 V BluetoothSapService: Sap Service closeSapService in
08-16 14:25:08.132  7010  7010 V BluetoothSapService: Close listen Socket : 
08-16 14:25:08.133  7010  7010 V BluetoothSapService: Close rfcomm Socket : 
08-16 14:25:08.133  7010  7010 V BluetoothSapService: Close sapd  Socket : 
08-16 14:25:08.139  7010  7010 V BluetoothSapService: Sap Service closeSapService out
,08-16 14:25:08.139  7010  7010 V BluetoothSapService: Sap Service onDestroy
,08-16 14:25:08.139  7010  7010 V BluetoothSapService: Sap Service closeSapService in
08-16 14:25:08.139  7010  7010 V BluetoothSapService: Close listen Socket : 
08-16 14:25:08.140  7010  7010 V BluetoothSapService: Close rfcomm Socket : 
08-16 14:25:08.140  7010  7010 V BluetoothSapService: Close sapd  Socket : 
08-16 14:25:08.141  7010  7010 V BluetoothSapService: Sap Service closeSapService out
08-16 14:25:08.867  7010  7484 D bt_hci_bdroid: cleanup
,08-16 14:25:08.871  7010  7552 I bt_lpm  : LPM is already off!!!
,08-16 14:25:08.880  7010  7576 I bt_userial_mct: exiting userial_read_thread
08-16 14:25:08.880  7010  7576 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 14:25:08.880  7010  7550 W bt-btif : ag scb idx 1 not allocated
08-16 14:25:08.880  7010  7550 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 14:25:08.880  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:25:08.880  7010  7550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:25:08.880  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:25:08.880  7010  7550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:25:08.881  7010  7550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:25:08.881  7010  7550 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 14:25:08.882  7010  7484 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 14:25:08.882  7010  7552 I bt_vendor: hw_epilog_process
,08-16 14:25:08.882  7010  7484 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 14:25:08.882  7010  7484 D bt_userial_mct: userial_close
08-16 14:25:08.882  7010  7484 E bt_userial_mct: pthread_join() FAILED result:3
08-16 14:25:08.882  7010  7484 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 14:25:08.889  7010  7484 D bt_hci_bdroid: set_power 0
08-16 14:25:08.889  7010  7484 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 14:25:08.889  7010  7484 I bt_vendor: bluetooth satus is on
,08-16 14:25:08.889  7010  7484 I bt_vendor: bt-vendor : resetting BT status
08-16 14:25:08.889  7010  7484 I bt_vendor: Starting hciattach daemon
08-16 14:25:08.889  7010  7484 I bt_vendor: try to set false
,08-16 14:25:08.898  7010  7484 I bt_vendor: Starting hciattach daemon
08-16 14:25:08.898  7010  7484 I bt_vendor: try to set false
08-16 14:25:08.900  7010  7484 I bt_vendor: cleanup
08-16 14:25:08.900  7010  7550 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 14:25:08.901  7010  7484 I GKI_LINUX: GKI_exit_task 0 done
08-16 14:25:08.901  7010  7484 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 14:25:08.902  7010  7480 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 14:25:08.909  7010  7010 D HeadsetService: Received stop request...Stopping profile...
,08-16 14:25:08.913  7010  7010 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 14:25:08.913  7010  7010 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:25:08.913  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:08.913  7010  7503 D HeadsetStateMachine: Exit Disconnected: -1
08-16 14:25:08.916  1051  1051 D BluetoothHeadset: Proxy object disconnected
08-16 14:25:08.916  1051  1051 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 14:25:08.916  1893  1893 D BluetoothHeadset: Proxy object disconnected
08-16 14:25:08.919  7010  7480 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 14:25:08.920  1893  1893 D BluetoothHeadset: Proxy object disconnected
08-16 14:25:08.921  1893  1893 D BluetoothHeadset: Proxy object disconnected
,08-16 14:25:08.924  7010  7010 D A2dpService: Received stop request...Stopping profile...
08-16 14:25:08.925  7010  7534 D A2dpStateMachine: Exit Disconnected: -1
08-16 14:25:08.927  7010  7010 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 14:25:08.928  7010  7010 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 14:25:08.928  7010  7010 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:25:08.928  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:08.930  7010  7010 D HidService: Received stop request...Stopping profile...
08-16 14:25:08.930  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:08.931  1051  1051 D BluetoothA2dp: Proxy object disconnected
08-16 14:25:08.931  1051  1051 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 14:25:08.934  7010  7010 D HealthService: Received stop request...Stopping profile...
08-16 14:25:08.934  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
,08-16 14:25:08.939  7010  7010 D PanService: Received stop request...Stopping profile...
08-16 14:25:08.941  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:08.942  7010  7010 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:25:08.942  7010  7010 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 14:25:08.942  7010  7010 D BtGatt.GattService: stop()
08-16 14:25:08.943  7010  7010 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 14:25:08.944  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:08.944  7010  7010 D HeadsetStateMachine: Unbinding service...
08-16 14:25:08.945  7010  7010 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:25:08.945  7010  7010 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:25:08.945  7010  7010 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:25:08.945  7010  7010 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:25:08.946  7010  7010 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 14:25:08.946  7010  7010 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:25:08.946  7010  7010 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-16 14:25:08.950  7010  7010 D BluetoothMapService: Received stop request...Stopping profile...
08-16 14:25:08.950  7010  7010 D BluetoothMapService: stop()
08-16 14:25:08.951  7010  7010 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 14:25:08.951  7010  7010 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 14:25:08.952  7010  7010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23ce94fc
08-16 14:25:08.954  7010  7010 I BluetoothA2dpServiceJni: cleanupNative
08-16 14:25:08.954  7010  7535 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 14:25:08.954  7010  7010 I GKI_LINUX: GKI_exit_task 2 done
08-16 14:25:08.954  7010  7010 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 14:25:08.955  7010  7010 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 14:25:08.955  7010  7010 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 14:25:08.955  7010  7010 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 14:25:08.955  7010  7010 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:25:08.955  7010  7010 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:25:08.956  7010  7010 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:25:08.956  7010  7010 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 14:25:08.959  7010  7010 V BluetoothMapService: Handler(): got msg=4
08-16 14:25:08.959  7010  7010 D BluetoothMapService: MAP Service closeService in
,08-16 14:25:08.959  7010  7010 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:25:08.961  7010  7010 V BluetoothMapService: MAP Service closeService out
08-16 14:25:08.962  7010  7480 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 14:25:08.962  7010  7480 D BluetoothAdapterProperties: Setting state to 10
08-16 14:25:08.962  7010  7480 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 14:25:08.965  7010  7010 D BluetoothMapService: cleanup()
08-16 14:25:08.965  7010  7010 D BluetoothMapService: MAP Service closeService in
08-16 14:25:08.965  7010  7010 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:25:08.965  7010  7010 V BluetoothMapService: MAP Service closeService out
08-16 14:25:08.966  1051  1115 D BluetoothManagerService: Message: 60
08-16 14:25:08.966  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 14:25:08.966  1051  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 14:25:08.967  7010  7480 I BluetoothAdapterState: Entering OffState
08-16 14:25:08.968  6863  7584 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:25:08.969  6863  7584 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:25:08.970  6863  7584 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:25:08.970  1051  1115 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:25:08.970  6863  7584 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 14:25:08.973  1893  1908 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:25:08.974  6863  7584 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:25:08.975  1051  1115 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:25:08.976  6863  7584 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:25:08.976  1893  1909 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:25:08.977  1893  2549 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:25:08.978  1051  1115 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 14:25:08.978  1051  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 14:25:08.980  1051  1115 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 14:25:08.980  1051  1115 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 14:25:08.980  1051  1115 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@130d21c3 mBinding = false
08-16 14:25:08.981  1051  1115 D BluetoothManagerService: Sending unbind request.
08-16 14:25:08.986  7010  7484 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 14:25:08.989  7010  7010 I GKI_LINUX: GKI_exit_task 1 done
08-16 14:25:08.989  7010  7010 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 14:25:08.989  7010  7010 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 14:25:08.989  7010  7010 I art     : --- WEIRD: removing null entry 248
08-16 14:25:08.990  7010  7010 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 14:25:08.990  7010  7010 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 14:25:08.991  7010  7010 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 14:25:08.992  1051  1115 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 14:25:08.994  7010  7010 I art     : System.exit called, status: 0
08-16 14:25:08.994  7010  7010 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 14:25:09.013   314  4012 V AudioFlinger: 7010 died, releasing its sessions
08-16 14:25:09.013   314  4012 V AudioFlinger:  pid 1893 @ 0
08-16 14:25:09.013   314  4012 V AudioFlinger:  pid 3487 @ 1
08-16 14:25:09.013   314  4012 V AudioFlinger:  pid 3487 @ 2
,08-16 14:25:09.017  1982  1982 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-16 14:25:09.017  1982  2193 D LGBluetoothAPIService: Message: 101
08-16 14:25:09.017  1982  2193 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 14:25:09.017  1982  2193 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 14:25:09.017  1982  2193 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 14:25:09.023  6863  6863 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 14:25:09.059  1051  1731 I ActivityManager: Process com.android.bluetooth (pid 7010) has died
08-16 14:25:09.059  1051  1731 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-16 14:25:09.059  1051  1731 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
08-16 14:25:09.066  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:09.067  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:09.067  1982  1982 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:09.067  1982  2193 D LGBluetoothAPIService: Message: 2
08-16 14:25:09.067  1982  2193 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,08-16 14:25:09.069  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:25:09.072  6863  6863 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 14:25:09.072  6863  6863 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 14:25:09.076  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 14:25:09.084  1619  1619 D BluetoothAdapter: 557169025: getState() :  mService = null. Returning STATE_OFF
08-16 14:25:09.084  1619  1619 D BluetoothAdapter: 557169025: getState() :  mService = null. Returning STATE_OFF
,08-16 14:25:09.139  1051  2071 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7673 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 14:25:09.141  6863  6863 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:25:09.235  7673  7673 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 14:25:09.235  7673  7673 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:25:09.236  7673  7673 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 14:25:09.237  7673  7673 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 14:25:09.257  7673  7673 D BluetoothAdapterApp: Loading JNI Library
,08-16 14:25:09.295  7673  7673 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1842fd64 Instance Count = 1
,08-16 14:25:09.302  7673  7673 D BluetoothAdapterApp: onCreate
08-16 14:25:09.330  7673  7673 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-16 14:25:09.330  7673  7673 D ProfileConfigQcom: Adding HeadsetService
08-16 14:25:09.331  7673  7673 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 14:25:09.331  7673  7673 D ProfileConfigQcom: Adding A2dpService
08-16 14:25:09.332  7673  7673 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 14:25:09.332  7673  7673 D ProfileConfigQcom: Adding HidService
08-16 14:25:09.333  7673  7673 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 14:25:09.334  7673  7673 D ProfileConfigQcom: Adding HealthService
08-16 14:25:09.335  7673  7673 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 14:25:09.337  7673  7673 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 14:25:09.338  7673  7673 D ProfileConfigQcom: Adding PanService
08-16 14:25:09.339  7673  7673 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 14:25:09.339  7673  7673 D ProfileConfigQcom: Adding GattService
08-16 14:25:09.340  7673  7673 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 14:25:09.340  7673  7673 D ProfileConfigQcom: Adding BluetoothMapService
08-16 14:25:09.341  7673  7673 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 14:25:09.343  7673  7673 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:25:09.346  7673  7673 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:25:09.347  7673  7673 V BluetoothPbapReceiver: ***********state = 10
,08-16 14:25:09.351  7673  7673 V LGMDMManagerInternal: Create singleton instance
08-16 14:25:09.467  7673  7673 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 14:25:09.467  7673  7673 D LGBluetoothAPIServer: [BTUI] onBind()
,08-16 14:25:09.473  2258  2258 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:25:09.474  1982  1982 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 14:25:09.475  1982  2193 D LGBluetoothAPIService: Message: 100
08-16 14:25:09.475  1982  2193 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 14:25:09.481  6863  6863 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 14:25:09.499  6863  6863 D BluetoothPermissionRequest: onReceive
,08-16 14:25:09.500  6863  6863 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 14:25:09.501  6863  6863 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 14:25:09.503  6863  6863 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:25:09.507  7673  7673 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 14:25:09.512  7673  7673 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:25:09.517  7673  7673 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:25:09.518  7673  7673 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:25:09.519  7673  7673 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:25:09.521  7673  7673 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:09.521  7673  7673 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 14:25:09.524  6960  6960 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 14:25:11.007  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:25:11.007  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:25:11.134  1619  1619 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 14:25:11.156  2107  2107 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 14:25:11.215  1051  1449 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 14:25:11.239  1051  1051 D administrator: Handling package changes for user 0
,08-16 14:25:11.256  1051  1108 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7703 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-16 14:25:11.265  1619  1619 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 14:25:11.266  1619  1619 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-16 14:25:11.293  2107  2107 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 14:25:11.322  7703  7703 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 14:25:11.360  1051  1051 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 14:25:11.360  1051  1051 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 14:25:11.390  7703  7703 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:25:11.390  7703  7703 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:25:11.427  1051  1107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 14:25:11.441  1051  1107 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 14:25:11.448  2107  2107 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 14:25:11.450  2516  2516 V GmsNetworkLocationProvi: DISABLE
08-16 14:25:11.474  1051  1107 D LocationProviderProxy: applying state to connected service
,08-16 14:25:11.478  2516  2516 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 14:25:11.508  7703  7748 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 14:25:11.509  7703  7748 I Babel   : MmsConfig.loadMmsSettings
08-16 14:25:11.515  7703  7748 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 14:25:11.515  7703  7748 I Babel   : MmsConfig.loadFromDatabase
,08-16 14:25:11.532  7703  7748 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 14:25:11.532  7703  7748 I Babel   : MmsConfig.loadFromResources
08-16 14:25:11.533  7703  7748 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 14:25:11.534  7703  7748 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 14:25:11.541  7703  7746 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 14:25:11.544  7703  7746 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 14:25:11.546  7703  7746 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 14:25:11.547  7703  7703 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:11.555  7703  7746 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 14:25:11.556  7703  7746 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 14:25:11.557  7703  7746 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 14:25:11.573  7703  7746 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 14:25:11.576  7703  7746 W VideoCapabilities: Unsupported mime video/divx
08-16 14:25:11.578  7703  7746 W VideoCapabilities: Unsupported mime video/divx311
08-16 14:25:11.578  1855  7750 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 14:25:11.578  1855  7750 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 14:25:11.583  7061  7061 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:25:11.585  7703  7746 W VideoCapabilities: Unsupported mime video/divx4
,08-16 14:25:11.590  7061  7061 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@d548ece
08-16 14:25:11.590  7061  7061 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:25:11.590  7061  7061 D AppUp4:CustFacade: isPhone : true
08-16 14:25:11.590  7061  7061 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:25:11.591  7061  7061 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 14:25:11.595  1855  4788 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-16 14:25:11.603  7703  7746 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 14:25:11.634  1051  1964 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7753 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 14:25:11.636  7703  7746 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 14:25:11.636  1051  2125 I ActivityManager: Killing 6682:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-16 14:25:11.647  6940  6940 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 14:25:11.647  6940  6940 W System.err: android.os.DeadObjectException
08-16 14:25:11.647  7703  7746 W AudioCapabilities: Unsupported mime audio/eac3
08-16 14:25:11.647  6940  6940 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:25:11.647  6940  6940 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:25:11.647  6940  6940 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 14:25:11.647  6940  6940 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 14:25:11.647  6940  6940 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 14:25:11.647  6940  6940 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 14:25:11.647  6940  6940 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:25:11.647  6940  6940 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:25:11.647  6940  6940 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:25:11.647  6940  6940 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:25:11.647  6940  6940 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:25:11.647  6940  6940 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:25:11.647  6940  6940 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:25:11.647  6940  6940 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:25:11.647  6940  6940 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 14:25:11.648  6940  6940 W System.err: android.os.DeadObjectException
08-16 14:25:11.648  6940  6940 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:25:11.648  6940  6940 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:25:11.648  6940  6940 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 14:25:11.648  6940  6940 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 14:25:11.648  6940  6940 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 14:25:11.648  6940  6940 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 14:25:11.648  6940  6940 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:25:11.648  6940  6940 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:25:11.648  6940  6940 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:25:11.648  6940  6940 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:25:11.648  6940  6940 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:25:11.648  6940  6940 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:25:11.648  6940  6940 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:25:11.648  6940  6940 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 14:25:11.649  6940  6940 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 14:25:11.650  6940  6940 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 14:25:11.650  7703  7746 W AudioCapabilities: Unsupported mime audio/ac3
08-16 14:25:11.651  7703  7746 W AudioCapabilities: Unsupported mime audio/g726
08-16 14:25:11.652  7703  7746 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 14:25:11.652  7703  7746 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 14:25:11.653  7703  7746 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 14:25:11.655  7703  7746 W VideoCapabilities: Unsupported mime video/theora
08-16 14:25:11.656  7703  7746 W VideoCapabilities: Unsupported mime video/mjpg
08-16 14:25:11.845  1051  2125 E libprocessgroup: failed to kill 1 processes for processgroup 6682
,08-16 14:25:11.908  1051  2071 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 14:25:11.919  6940  6940 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 14:25:11.920  6940  6940 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 14:25:11.966  7753  7753 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:25:11.966  7753  7753 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:25:11.967  7753  7753 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 14:25:11.968  7753  7753 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 14:25:11.969  7753  7753 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 14:25:11.984  1051  1986 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7773 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 14:25:11.991  6940  6940 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 14:25:12.073  7773  7773 D UEI.SmartControl: Quickset Services start...
,08-16 14:25:12.075  7773  7773 I UEI.SmartControl: Manufacture = LGE
08-16 14:25:12.075  7773  7773 D UEI.SmartControl: Id = LGNevo
08-16 14:25:12.077  7773  7773 D UEI.SmartControl: File observer start...
08-16 14:25:12.078  7773  7773 E UEI.SmartControl: IR Port is disabled: false
08-16 14:25:12.079  7773  7773 D UEI.SmartControl: Starting file observer...
08-16 14:25:12.079  7753  7753 I SystemConfig: BUILD Country: EU
08-16 14:25:12.079  7773  7773 D UEI.SmartControl: Extracting JNI libs...
08-16 14:25:12.079  7753  7753 I SystemConfig: BUILD Operator: OPEN
08-16 14:25:12.079  7773  7773 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 14:25:12.122  1051  1957 I ActivityManager: Killing 6940:com.lge.qremote/u0a112 (adj 15): empty #17
,08-16 14:25:12.156  7773  7773 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 14:25:12.156  7773  7773 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 14:25:12.156  7773  7773 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 14:25:12.179  7773  7773 I UEI.SmartControl: --- Selecting new region: 6
,08-16 14:25:12.180  7773  7773 I UEI.SmartControl: Model = LG-D855
,08-16 14:25:12.181  7773  7773 D UEI.SmartControl: QS Service created
,08-16 14:25:12.194  1051  2127 W libprocessgroup: failed to open /acct/uid_10112/pid_6940/cgroup.procs: No such file or directory
,08-16 14:25:12.211  7773  7773 I UEI.SmartControl: Service initServices...
,08-16 14:25:12.215  7773  7773 D UEI.SmartControl: QS start get config
08-16 14:25:12.236  1051  1957 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7801 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 14:25:12.240  7753  7799 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 14:25:12.240  7753  7799 I SystemConfig: existFile = false
08-16 14:25:12.240  7753  7799 I SystemConfig: canReadFile = false
08-16 14:25:12.240  7753  7799 I SystemConfig: systemFeature RCS result false
08-16 14:25:12.245  7753  7799 D SystemConfig: refreshRcsSupport() :false
08-16 14:25:12.259  7773  7773 D UEI.SmartControl: Loading JNI Libs...
,08-16 14:25:12.293  7801  7801 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:25:12.293  7801  7801 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 14:25:12.294  7801  7801 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-16 14:25:12.294  7801  7801 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 14:25:12.408  7801  7801 I AppConfig: Total System Memory = 2995761152
,08-16 14:25:12.417  7801  7801 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-16 14:25:12.513  1051  2072 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7820 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:25:12.515  1051  2072 I ActivityManager: Killing 7106:com.lge.email/u0a23 (adj 15): empty #17
,08-16 14:25:12.609  1051  2006 W libprocessgroup: failed to open /acct/uid_10023/pid_7106/cgroup.procs: No such file or directory
,08-16 14:25:12.649  7773  7773 I UEI.SmartControl: Supports setup maps: true
08-16 14:25:12.654  7773  7773 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 14:25:12.654  7773  7773 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 14:25:12.654  7773  7773 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 14:25:12.655  7773  7773 I UEI.SmartControl: ### init IR Blaster...
,08-16 14:25:12.660  7773  7773 D serial_port: Configuring serial port
08-16 14:25:12.664  7773  7773 E UEI.SmartControl: UEIBLaster setting for 616
08-16 14:25:12.664  7773  7773 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 14:25:12.665  7773  7773 I UEI.SmartControl: configuring settings for MAXQ616
08-16 14:25:12.665  7773  7773 I UEI.SmartControl: Get version...
08-16 14:25:12.681  7773  7841 D UEI.SmartControl: serial port data available: 21
,08-16 14:25:12.708  7773  7773 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 14:25:12.708  7773  7773 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 14:25:12.709  7773  7773 I UEI.SmartControl: QS saving settings...
08-16 14:25:12.710  7773  7773 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 14:25:12.727  7773  7841 D UEI.SmartControl: serial port data available: 4
,08-16 14:25:12.730  7820  7820 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-16 14:25:12.759  7773  7852 I UEI.SmartControl: Device manager: loading config....
,08-16 14:25:12.760  7773  7773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 14:25:12.762  7773  7852 D UEI.SmartControl: ----------- loading internal config...
08-16 14:25:12.768  7773  7852 E UEI.SmartControl: Loading SETTINGS...
08-16 14:25:12.772  7773  7773 E UEI.SmartControl: Services init done
08-16 14:25:12.772  7773  7773 D UEI.SmartControl: QS Service init finished
,08-16 14:25:12.776  7773  7773 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 14:25:12.776  7773  7773 D UEI.SmartControl: QS Service version code: 201091
08-16 14:25:12.776  7773  7773 D UEI.SmartControl: Service requested: Control
08-16 14:25:12.777  7773  7773 D UEI.SmartControl: Service.onUnbind: IControl
08-16 14:25:12.778  7773  7852 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 14:25:12.779  7773  7773 D UEI.SmartControl: Service.onDestroy
08-16 14:25:12.779  7773  7773 D UEI.SmartControl: Lock is in USE false
08-16 14:25:12.779  7773  7773 D UEI.SmartControl: unbind internal service
08-16 14:25:12.779  7773  7773 D serial_port: close(fd = 25)
08-16 14:25:12.783  7773  7773 I UEI.SmartControl: Serial port is closed.
08-16 14:25:12.783  7773  7773 I UEI.SmartControl: Serial port is closed.
08-16 14:25:12.783  7773  7773 D UEI.SmartControl: Blaster closed
08-16 14:25:12.784  7773  7773 D UEI.SmartControl: Shut down QS...
08-16 14:25:12.784  7773  7773 D UEI.SmartControl: Stopping QS lib
08-16 14:25:12.784  7773  7773 D UEI.SmartControl: QS lib stop result = true
08-16 14:25:12.784  7773  7773 D UEI.SmartControl: Stopped QS lib
08-16 14:25:12.785  7773  7773 D UEI.SmartControl: Stopped file observer...
08-16 14:25:12.785  7773  7773 D UEI.SmartControl: QS shutdown complete
08-16 14:25:12.786  7773  7773 D UEI.SmartControl: QS Service created
,08-16 14:25:12.799  7773  7851 I UEI.SmartControl: Notify AllClients services are ready: 11
08-16 14:25:12.799  7773  7851 D UEI.SmartControl: -----service ready thread exits
08-16 14:25:12.802  7773  7773 I UEI.SmartControl: Service initServices...
,08-16 14:25:12.802  7773  7773 D UEI.SmartControl: QS start get config
08-16 14:25:12.843  7820  7820 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:25:12.843  7820  7820 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:25:12.868  1051  1396 V AlarmManager: RTC_WAKEUP set : Alarm{2f615942 type 0 when 1471350312545 com.google.android.gms} when 1471350312545
,08-16 14:25:12.912  7820  7820 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 14:25:12.931  7820  7820 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 14:25:12.932  7820  7820 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 14:25:12.947  7820  7820 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-16 14:25:12.947  7820  7820 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 14:25:12.983  1051  2028 I ActivityManager: Killing 6981:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 14:25:13.090  1051  1593 W libprocessgroup: failed to open /acct/uid_10026/pid_6981/cgroup.procs: No such file or directory
,08-16 14:25:13.093  3537  3948 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 14:25:13.094  3537  3948 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@8bd3992 on behalf of 7820
08-16 14:25:13.100  4612  7867 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 14:25:13.141  1051  2006 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7869 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 14:25:13.154  7820  7820 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 14:25:13.161  7773  7773 I UEI.SmartControl: Supports setup maps: true
08-16 14:25:13.167  7820  7820 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 14:25:13.172  7773  7773 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 14:25:13.174  7773  7773 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 14:25:13.174  7773  7773 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 14:25:13.174  7773  7773 I UEI.SmartControl: ### init IR Blaster...
08-16 14:25:13.179  7773  7773 D serial_port: Configuring serial port
08-16 14:25:13.180  7773  7773 E UEI.SmartControl: UEIBLaster setting for 616
08-16 14:25:13.180  7773  7773 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 14:25:13.180  7773  7773 I UEI.SmartControl: configuring settings for MAXQ616
08-16 14:25:13.180  7773  7773 I UEI.SmartControl: Get version...
08-16 14:25:13.193  7869  7869 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-16 14:25:13.196  7773  7888 D UEI.SmartControl: serial port data available: 21
,08-16 14:25:13.209  7869  7869 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 14:25:13.209  7869  7869 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 14:25:13.209  7869  7869 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 14:25:13.209  7869  7869 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 14:25:13.209  7869  7869 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 14:25:13.209  7869  7869 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 14:25:13.221  7773  7773 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 14:25:13.221  7773  7773 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 14:25:13.221  7773  7773 I UEI.SmartControl: QS saving settings...
08-16 14:25:13.222  7773  7773 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 14:25:13.227  1051  2071 I ActivityManager: Killing 6477:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-16 14:25:13.238  7773  7888 D UEI.SmartControl: serial port data available: 4
,08-16 14:25:13.264  7773  7893 I UEI.SmartControl: Device manager: loading config....
,08-16 14:25:13.265  7773  7893 D UEI.SmartControl: ----------- loading internal config...
08-16 14:25:13.265  7773  7773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 14:25:13.269  7773  7893 E UEI.SmartControl: Loading SETTINGS...
08-16 14:25:13.271  7773  7893 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 14:25:13.280  1051  1067 W libprocessgroup: failed to open /acct/uid_1000/pid_6477/cgroup.procs: No such file or directory
08-16 14:25:13.280  1855  7891 I CheckinService: active receiver: enabled
,08-16 14:25:13.283  7773  7773 E UEI.SmartControl: Services init done
08-16 14:25:13.283  7773  7773 D UEI.SmartControl: QS Service init finished
08-16 14:25:13.284  7773  7892 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 14:25:13.284  7773  7892 D UEI.SmartControl: -----service ready thread exits
08-16 14:25:13.290  7773  7773 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 14:25:13.290  7773  7773 D UEI.SmartControl: QS Service version code: 201091
08-16 14:25:13.290  7773  7773 D UEI.SmartControl: Service requested: Control
08-16 14:25:13.292  1051  2125 I ActivityManager: Killing 7136:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-16 14:25:13.329  1051  1593 W libprocessgroup: failed to open /acct/uid_10046/pid_7136/cgroup.procs: No such file or directory
,08-16 14:25:13.332  7773  7773 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@8aec9da that was originally bound here
08-16 14:25:13.332  7773  7773 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@8aec9da that was originally bound here
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:25:13.332  7773  7773 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:25:13.332  7773  7773 D UEI.SmartControl: Internal service binding...
08-16 14:25:13.337  2258  2258 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 14:25:13.392  1051  1734 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7895 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-16 14:25:13.412   333   333 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 386us total 17.980ms
,08-16 14:25:13.431   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 16.783ms
,08-16 14:25:13.448   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 14.827ms
,08-16 14:25:13.495  1051  1726 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:25:13.513  7895  7895 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:25:13.513  7895  7895 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:25:13.516  7895  7895 D PhoneMonitor: Register our PhoneStateListener
08-16 14:25:13.523  4612  7867 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 423 ms] updated apps [took 423 ms] 
08-16 14:25:13.535  1051  1593 I ActivityManager: Killing 7155:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 14:25:13.547  7895  7895 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 14:25:13.548  7895  7895 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 14:25:13.548  7895  7895 D TelephonyAutoProfiling: [parse] Load xml
08-16 14:25:13.552  7895  7895 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 14:25:13.552  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 14:25:13.553  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 14:25:13.553  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 14:25:13.553  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 14:25:13.553  7895  7895 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 14:25:13.553  7895  7895 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 14:25:13.560  7895  7895 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 14:25:13.581  1051  1964 W libprocessgroup: failed to open /acct/uid_10057/pid_7155/cgroup.procs: No such file or directory
,08-16 14:25:13.779  7773  7854 D UEI.SmartControl: Internal timer expired: 2
,08-16 14:25:14.023  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:14.023  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b5b1b56 added. We now have 6 listener(s)
08-16 14:25:14.023  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:25:14.032  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:14.032  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22a307d7 added. We now have 7 listener(s)
08-16 14:25:14.032  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:14.033  6780  6850 I System.out: IsBluetoothEnabled
08-16 14:25:14.034  1051  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:14.034  1051  2006 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-16 14:25:14.034  1051  1115 D BluetoothManagerService: Message: 2
08-16 14:25:14.037  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:14.038  1051  1067 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:14.038  1051  1067 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 14:25:14.057  1051  1051 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:25:14.057  1051  1051 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:25:14.057  1051  1051 D Ulp_jni : JNI:system_update. Event-4
08-16 14:25:14.058  1051  1115 D BluetoothManagerService: Message: 1
08-16 14:25:14.058  1051  1115 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 14:25:14.082  1051  1115 D BluetoothManagerService: Message: 20
08-16 14:25:14.083  1051  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f0ea0a2:true
,08-16 14:25:14.087  7673  7673 D BluetoothAdapterState: make
08-16 14:25:14.092  7673  7673 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 14:25:14.092  7673  7673 I bluedroid-qcom: init
08-16 14:25:14.093  7673  7931 I BluetoothAdapterState: Entering OffState
08-16 14:25:14.093  7673  7673 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 14:25:14.093  7673  7673 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 14:25:14.094  7673  7673 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:25:14.094  7673  7673 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 14:25:14.094  7673  7673 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 14:25:14.095  7673  7673 I bluedroid-qcom: get_profile_interface socket
08-16 14:25:14.095  7673  7673 I bluedroid-qcom: get_profile_interface map_client
,08-16 14:25:14.101  7673  7935 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 14:25:14.103  7673  7935 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 14:25:14.097  7934  7934 W bdaddr_loader: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:14.097  7934  7934 W bdaddr_loader: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:14.111  1051  1051 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 14:25:14.112  1051  1051 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 14:25:14.118  7934  7934 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 14:25:14.118  7934  7934 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 14:25:14.118  7934  7934 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 14:25:14.120  1051  1051 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 14:25:14.120  1051  1115 D BluetoothManagerService: Message: 40
08-16 14:25:14.120  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 14:25:14.121  7673  7691 I bluedroid-qcom: config_hci_snoop_log
08-16 14:25:14.122  1051  1115 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 14:25:14.122  1051  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 14:25:14.125  7673  7935 D BluetoothAdapterProperties: Name is: G3
,08-16 14:25:14.125  7934  7934 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 14:25:14.132  7934  7934 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 14:25:14.132  7934  7934 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 14:25:14.136  7673  7931 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 14:25:14.136  7673  7931 D BluetoothAdapterProperties: Setting state to 11
08-16 14:25:14.136  7673  7931 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 14:25:14.137  1051  1115 D BluetoothManagerService: Message: 60
08-16 14:25:14.137  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 14:25:14.137  1051  1115 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 14:25:14.140  7673  7931 I LGBluetoothServiceJni: classInitNative: succeeds
,08-16 14:25:14.146  1982  1982 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:14.149  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:25:14.152  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:14.157  6863  6863 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 14:25:14.164  7673  7673 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:25:14.164  7673  7673 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:14.164  7673  7673 V BluetoothPbapReceiver: ***********state = 11
08-16 14:25:14.177  2258  2258 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:25:14.178  7673  7931 D BluetoothBondStateMachine: make
08-16 14:25:14.182  7673  7931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.182  7673  7931 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 14:25:14.182  7673  7931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.182  7673  7931 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 14:25:14.183  7673  7931 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 14:25:14.183  7673  7949 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 14:25:14.186  7673  7931 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:25:14.196  7673  7673 D HeadsetService: Received start request. Starting profile...
08-16 14:25:14.196  7673  7673 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:25:14.196  7673  7673 D LGBluetoothHfpAdapter: Version 1.6
08-16 14:25:14.196  7673  7931 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:25:14.198  7673  7673 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 14:25:14.199  7673  7673 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:25:14.200  7673  7673 D HeadsetStateMachine: make
08-16 14:25:14.204  6863  6863 D BluetoothPermissionRequest: onReceive
08-16 14:25:14.205  7673  7931 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:25:14.207  6863  6863 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:25:14.216  7673  7931 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:25:14.221  7673  7931 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:25:14.225  7673  7931 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:25:14.228  7673  7931 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:25:14.237  7673  7673 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:25:14.237  7673  7673 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:25:14.241  7673  7931 V LGMDMManager: Create singleton instance
,08-16 14:25:14.242  7673  7673 D HeadsetStateMachine: max_hf_connections = 1
08-16 14:25:14.242  7673  7673 I bluedroid-qcom: get_profile_interface handsfree
08-16 14:25:14.243  7673  7931 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 14:25:14.244  7673  7673 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 14:25:14.244   314   314 V AudioPolicyService: registerClient() client 0xb14b7820, uid 1002
08-16 14:25:14.245   314  4012 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 14:25:14.245   314  4012 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:25:14.245   314  4012 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:25:14.245  7673  7673 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 14:25:14.245   314  1401 V AudioFlinger: registerClient() client 0xb1433160, pid 7673
08-16 14:25:14.246   314  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:14.246   314  1395 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:14.246   314  1397 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:14.246   314  1397 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:14.246  7673  7673 V ToneGenerator: Create Track: 0xb4928080
08-16 14:25:14.246  3487  3502 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:14.246  7673  7673 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 14:25:14.246  3487  3502 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:14.246  7673  7673 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 14:25:14.246  3487  3502 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:14.246  3487  3502 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:14.246  7673  7936 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:14.246  7673  7936 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 14:25:14.247  7673  7936 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:14.247  7673  7936 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 14:25:14.247   314  1401 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 14:25:14.247   314  1401 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 14:25:14.247   314  1401 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:25:14.247   314  1401 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:25:14.247   314  1401 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 14:25:14.247   314  1401 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 14:25:14.247   314  1401 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 14:25:14.247   314  1401 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:25:14.247   314  1401 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:25:14.247  7673  7673 V AudioSystem: getLatency() output 2, latency 50
08-16 14:25:14.248  7673  7673 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 14:25:14.248  1051  1964 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:14.248  7673  7673 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 14:25:14.248  1051  1964 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:14.248  1051  1964 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:14.248  1051  19,64 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:14.248   314  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 14:25:14.248   314  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 14:25:14.248   314  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 14:25:14.248   314  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 14:25:14.248   314  1402 V AudioFlinger: createTrack() lSessionId: 23
08-16 14:25:14.249  1619  1955 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:14.249  1619  1955 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:14.249  1893  2549 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:25:14.249  1893  2549 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:25:14.249  1893  2549 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:14.249  1893  2549 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:14.250  1619  1955 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:25:14.250  1619  1955 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:25:14.250  7673  7673 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 14:25:14.250   314  1401 V AudioFlinger: acquiring 23 from 7673, for 7673
08-16 14:25:14.250   314  1401 V AudioFlinger:  added new entry for 23
08-16 14:25:14.251  7673  7673 V ToneGenerator: ToneGenerator INIT OK, time: 227862
08-16 14:25:14.251  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.251  7673  7953 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 14:25:14.251  7673  7953 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:25:14.252  7673  7953 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:25:14.252  7673  7953 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 14:25:14.252   314  1402 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7673
,08-16 14:25:14.254   314  1402 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 14:25:14.254   314  1402 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 14:25:14.254   314  1402 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 14:25:14.254   314  1402 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 14:25:14.254   314  1402 V voice   : voice_set_parameters: exit with code(0)
08-16 14:25:14.254   314  1402 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 14:25:14.254   314  1402 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 14:25:14.254   314  1402 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 14:25:14.254   314  1402 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 14:25:14.254   314  1402 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 14:25:14.254   314  1402 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 14:25:14.256  7673  7953 V ToneGenerator: ToneGenerator destructor
08-16 14:25:14.256  7673  7953 V ToneGenerator: stopTone
08-16 14:25:14.256  7673  7953 V ToneGenerator: Delete Track: 0xb4928080
08-16 14:25:14.258  1051  1067 W Process : Unable to open /proc/7956/status
08-16 14:25:14.258  7673  7953 V AudioTrack: ~AudioTrack, releasing session id from 7673 on behalf of 7673
08-16 14:25:14.258   314  1401 V AudioFlinger: releasing 23 from 7673 for 7673
08-16 14:25:14.258   314  4012 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 14:25:14.258   314  1401 V AudioFlinger:  decremented refcount to 0
08-16 14:25:14.258   314  1401 V AudioFlinger: purging stale effects
08-16 14:25:14.258   314  4012 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 14:25:14.258   314  4012 V AudioFlinger: PlaybackThread::Track destructor
08-16 14:25:14.258   314  1281 V AudioPolicyService: AudioCommandThread() waking up
08-16 14:25:14.258   314  1281 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 14:25:14.258   314  4012 V AudioFlinger: removeClient_l() pid 7673, calling pid 314
08-16 14:25:14.258   314  1281 V AudioPolicyManager: releaseOutput() 2
08-16 14:25:14.258   314  1281 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 14:25:14.258  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.260  7673  7673 D A2dpService: Received start request. Starting profile...
08-16 14:25:14.260  7673  7673 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 14:25:14.261  7673  7673 V Avrcp   : make
08-16 14:25:14.262  7673  7673 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 14:25:14.262  7673  7673 I bluedroid-qcom: get_profile_interface avrcp
08-16 14:25:14.269  7673  7673 V AudioManager: registerRemoteController: size of Media player list: 0
,08-16 14:25:14.270  7673  7673 E AudioManager: No RCC entry present to update
08-16 14:25:14.270  7673  7673 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 14:25:14.273  7673  7673 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 14:25:14.275  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 14:25:14.275  7673  7673 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 14:25:14.279  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 14:25:14.412  1051  2125 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:25:14.412  1051  2125 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:25:14.554  1051  1066 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 14:25:14.564  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 14:25:14.568  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 14:25:14.570  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-16 14:25:14.570  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 14:25:14.570  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 14:25:14.570  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:25:14.570  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 14:25:14.570  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 14:25:14.571  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 14:25:14.571  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-16 14:25:14.571  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 14:25:14.572  7673  7673 I BluetoothA2dpServiceJni: classInitNative
,08-16 14:25:14.572  7673  7673 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:25:14.572  7673  7673 D A2dpStateMachine: make
08-16 14:25:14.574  7673  7673 I bluedroid-qcom: get_profile_interface a2dp
08-16 14:25:14.574  7673  7964 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 14:25:14.578  7673  7673 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:25:14.578  7673  7673 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 14:25:14.579  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.581  7673  7673 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 14:25:14.581  7673  7963 D A2dpStateMachine: Enter Disconnected: -2
08-16 14:25:14.582  7673  7673 D HidService: Received start request. Starting profile...
08-16 14:25:14.583  7673  7673 I bluedroid-qcom: get_profile_interface hidhost
08-16 14:25:14.583  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.583  7673  7673 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:25:14.585  7673  7673 D HealthService: Received start request. Starting profile...
,08-16 14:25:14.588  7673  7673 I bluedroid-qcom: get_profile_interface health
08-16 14:25:14.588  7673  7673 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:25:14.588  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.589  7673  7673 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 14:25:14.591  7673  7673 D PanService: Received start request. Starting profile...
08-16 14:25:14.591  7673  7673 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:25:14.591  7673  7673 I bluedroid-qcom: get_profile_interface pan
08-16 14:25:14.598  7673  7673 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 14:25:14.598  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.599  7673  7673 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-16 14:25:14.605  7673  7673 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:25:14.605  7673  7673 D BtGatt.GattService: Received start request. Starting profile...
08-16 14:25:14.605  7673  7673 D BtGatt.GattService: start()
08-16 14:25:14.605  7673  7673 I bluedroid-qcom: get_profile_interface gatt
08-16 14:25:14.605  7673  7673 D BtGatt.AdvertiseManager: advertise manager created
08-16 14:25:14.614  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.615  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.615  7673  7673 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 14:25:14.616  7673  7673 V BluetoothMapService: BluetoothMapBinder()
,08-16 14:25:14.617  7673  7673 D BluetoothMapService: Received start request. Starting profile...
08-16 14:25:14.617  7673  7673 D BluetoothMapService: start()
08-16 14:25:14.620  7673  7673 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 14:25:14.621  7673  7673 D BluetoothMapEmailAppObserver: createReceiver()
08-16 14:25:14.621  7673  7673 D BluetoothMapEmailAppObserver: initObservers()
08-16 14:25:14.622  7673  7673 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 14:25:14.628  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:14.629  7673  7673 D HeadsetStateMachine: Proxy object connected
,08-16 14:25:14.630  7673  7673 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 14:25:14.630  7673  7673 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 14:25:14.632  7673  7953 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 14:25:14.633  7673  7953 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:25:14.633  7673  7953 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 14:25:14.638  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:25:14.640  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:25:14.641  7673  7673 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:25:14.646  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 14:25:14.648  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:25:14.648  7673  7673 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 14:25:14.651  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:25:14.653  7673  7673 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 14:25:14.654  7673  7673 V BluetoothMapService: Handler(): got msg=1
,08-16 14:25:14.655  7673  7931 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-16 14:25:14.655  7673  7931 I bluedroid-qcom: enable
08-16 14:25:14.656  7673  7673 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:25:14.656  7673  7673 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:25:14.656  7673  7931 I bt_hci_bdroid: init
08-16 14:25:14.656  7673  7673 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:25:14.656  7673  7673 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:14.656  7673  7673 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 14:25:14.657  7673  7931 I bt_vendor: bt-vendor : init
08-16 14:25:14.657  7673  7931 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 14:25:14.657  7673  7931 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 14:25:14.657  7673  7931 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 14:25:14.657  7673  7931 D bt_userial_mct: userial_init
08-16 14:25:14.657  7673  7971 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 14:25:14.658  7673  7971 I bt-btu  : btu_task pending for preload complete event
08-16 14:25:14.659  7673  7931 D bt_hci_bdroid: set_power 1
08-16 14:25:14.659  7673  7931 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 14:25:14.659  7673  7931 I bt_vendor: Starting hciattach daemon
08-16 14:25:14.659  7673  7931 I bt_vendor: try to set true
08-16 14:25:14.657  7974  7974 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:14.657  7974  7974 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:14.705  7975  7975 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 14:25:14.818  7981  7981 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 14:25:14.836  7982  7982 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 14:25:14.867  7984  7984 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 14:25:14.890  7985  7985 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 14:25:14.904  7986  7986 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 14:25:14.917  7987  7987 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 14:25:14.945  7989  7989 I libmdmdetect: ESOC framework not supported
08-16 14:25:14.946  7989  7989 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 14:25:14.954  7989  7989 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 14:25:14.954  7989  7989 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 14:25:14.954  7989  7989 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 14:25:14.954  7989  7989 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 14:25:14.954  7989  7989 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 14:25:14.954  7989  7989 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 14:25:14.954  7989  7989 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 14:25:14.993  7989  7993 E QC-QMI  : qmi_client [7989] 15: failed to locate client data
,08-16 14:25:14.997   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 14:25:14.997   444   444 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-16 14:25:15.019  7997  7997 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 14:25:15.035  7998  7998 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 14:25:15.061  7673  7931 I bt_vendor: bluetooth satus is on
08-16 14:25:15.061  7673  7931 D bt_hci_bdroid: preload
08-16 14:25:15.062  7673  7973 D bt_userial_mct: userial_open(port:0)
08-16 14:25:15.062  7673  7973 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 14:25:15.065  7673  7973 I bt_vendor: Done intiailizing UART
08-16 14:25:15.066  7673  7973 I bt_vendor: Done intiailizing UART
08-16 14:25:15.066  7673  7973 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 14:25:15.066  7673  7973 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 14:25:15.067  7673  7971 I bt-btu  : btu_task received preload complete event
08-16 14:25:15.067  7673  7971 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 14:25:15.067  7673  7971 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 14:25:15.070  7673  7971 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 14:25:15.073  7673  8000 D bt_userial_mct: Entering userial_read_thread()
08-16 14:25:15.076  7673  7971 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:25:15.077  7673  7971 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 14:25:15.133  7673  7971 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 14:25:15.134  7673  7971 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01da061 
08-16 14:25:15.134  7673  7971 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01da061 
,08-16 14:25:15.153  7673  7935 E bt-btif : Calling BTA_HhEnable
08-16 14:25:15.153  7673  7935 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 14:25:15.153  7673  7935 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 14:25:15.157  7673  7971 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 14:25:15.159  7673  7971 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 14:25:15.159  7673  7971 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 14:25:15.159  7673  7971 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 14:25:15.159  7673  7971 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 14:25:15.160  1051  1051 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 14:25:15.161  1051  1051 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 14:25:15.162  7673  7935 D BluetoothAdapterProperties: Name is: G3
08-16 14:25:15.164  7673  7935 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:25:15.164  7673  7935 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:25:15.164  7673  7935 D bt_hci_bdroid: postload
08-16 14:25:15.165  7673  7973 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:25:15.166  7673  7971 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 14:25:15.168  7673  7935 D bte_conf: Device ID record 1 : primary
,08-16 14:25:15.172  7673  7973 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:25:15.172  7673  7935 D bte_conf:   vendorId            = 00c4
08-16 14:25:15.172  7673  7935 D bte_conf:   vendorIdSource      = 0001
08-16 14:25:15.172  7673  7935 D bte_conf:   product             = 13a1
08-16 14:25:15.172  7673  7935 D bte_conf:   version             = 1000
08-16 14:25:15.172  7673  7935 D bte_conf:   clientExecutableURL = 
08-16 14:25:15.172  7673  7935 D bte_conf:   serviceDescription  = 
08-16 14:25:15.172  7673  7935 D bte_conf:   documentationURL    = 
08-16 14:25:15.172  7673  7935 D bte_conf: bte_load_did_conf no section named DID2.
08-16 14:25:15.176  7673  7973 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:25:15.177  7673  7931 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 14:25:15.177  7673  7931 D BluetoothAdapterProperties: ScanMode =  20
08-16 14:25:15.177  7673  7931 D BluetoothAdapterProperties: State =  11
08-16 14:25:15.178  7673  7931 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 14:25:15.178  7673  7931 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 14:25:15.178  7673  7931 D BluetoothAdapterProperties: Setting state to 12
08-16 14:25:15.178  7673  7931 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 14:25:15.177  8002  8002 W sh      : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 14:25:15.186  7673  7935 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 14:25:15.177  8002  8002 W sh      : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:15.189  1051  1115 D BluetoothManagerService: Message: 60
08-16 14:25:15.189  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 14:25:15.189  1051  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 14:25:15.190  7673  7971 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:25:15.190  7673  7971 W bt-smp  : Plain text(LSB ~ MSB) = 7a ae 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:15.190  7673  7971 W bt-smp  : Encrypted text(LSB ~ MSB) = 42 44 c6 c9 64 7b 49 fe 35 3a ab 97 fe 8b 23 e2 
08-16 14:25:15.190  7673  7973 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:25:15.191  7673  7971 W bt-btm  : Stopping oneshot timer
08-16 14:25:15.192  7673  7935 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 14:25:15.194  7673  8000 E bt_mct  : hci lib postload completed
,08-16 14:25:15.221  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:15.221  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:15.221  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:15.221  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:15.221  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:15.221  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:15.221  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:15.221  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:25:15.229  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:25:15.229  7673  7931 I BluetoothAdapterState: Entering On State
08-16 14:25:15.232  7673  7971 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-16 14:25:15.232  7673  7971 W bt-smp  : Plain text(LSB ~ MSB) = b9 21 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:15.232  7673  7971 W bt-smp  : Encrypted text(LSB ~ MSB) = 29 5d 79 3f 74 f9 65 fb a4 56 9a 79 e0 d8 43 79 
08-16 14:25:15.233  7673  7971 W bt-btm  : Stopping oneshot timer
08-16 14:25:15.246  7673  7931 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 14:25:15.246  7673  7931 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 14:25:15.246  7673  7931 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 14:25:15.255  7673  7931 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 14:25:15.264  7673  7971 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:25:15.265  7673  7971 W bt-smp  : Plain text(LSB ~ MSB) = fd 48 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:15.265  7673  7971 W bt-smp  : Encrypted text(LSB ~ MSB) = 78 a8 64 7b 16 a7 b4 1d db 14 ae e5 a4 71 5c 84 
,08-16 14:25:15.267  7673  7971 W bt-btm  : Stopping oneshot timer
08-16 14:25:15.268  6863  6889 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 14:25:15.269  7673  7935 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:25:15.269  7673  7935 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 14:25:15.285  7673  7931 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-16 14:25:15.287  7673  7971 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:25:15.287  7673  7971 W bt-smp  : Plain text(LSB ~ MSB) = dc 56 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:15.287  7673  7971 W bt-smp  : Encrypted text(LSB ~ MSB) = 66 3a 7a 87 2a 45 43 52 7c ca 14 77 37 00 fb 3a 
08-16 14:25:15.288  7673  7971 W bt-btm  : Stopping oneshot timer
08-16 14:25:15.289  6863  7584 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:25:15.307  7673  7971 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:25:15.307  7673  7971 W bt-smp  : Plain text(LSB ~ MSB) = 99 3f 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:25:15.307  7673  7971 W bt-smp  : Encrypted text(LSB ~ MSB) = 04 d6 4d 12 4e 0a f8 aa 9c 50 78 16 e5 a2 86 27 
08-16 14:25:15.307  7673  7971 W bt-btm  : Stopping oneshot timer
,08-16 14:25:15.315  6863  6863 D BluetoothMap: Proxy object connected
08-16 14:25:15.315  6863  6863 D MapProfile: Bluetooth service connected
08-16 14:25:15.315  6863  6863 D BluetoothMap: getConnectedDevices()
08-16 14:25:15.317  6863  6889 D BluetoothPan: onBluetoothStateChange on: true
08-16 14:25:15.317  6863  6889 D BluetoothPan: onBluetoothStateChange call bindService
,08-16 14:25:15.324  7673  7691 V BluetoothMapService: getConnectedDevices()
08-16 14:25:15.338  8007  8007 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 14:25:15.442  1051  1115 I art     : Explicit concurrent mark sweep GC freed 28702(1431KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.747ms total 122.391ms
,08-16 14:25:15.444  1051  1115 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:25:15.444  6863  6863 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:25:15.444  6863  6863 D PanProfile: Bluetooth service connected
08-16 14:25:15.444  6863  7584 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:25:15.445  1051  1051 D BluetoothHeadset: Proxy object connected
08-16 14:25:15.451  1893  1909 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:25:15.451  6863  6863 D BluetoothA2dp: Proxy object connected
08-16 14:25:15.451  6863  6863 D A2dpProfile: Bluetooth service connected
08-16 14:25:15.456  1893  1893 D BluetoothHeadset: Proxy object connected
08-16 14:25:15.456  6863  6889 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 14:25:15.460  1051  1115 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:25:15.460  6863  6863 D BluetoothInputDevice: Proxy object connected
08-16 14:25:15.460  6863  6863 D HidProfile: Bluetooth service connected
08-16 14:25:15.461  6863  7584 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:25:15.461  1051  1051 D BluetoothA2dp: Proxy object connected
,08-16 14:25:15.463  1893  1908 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 14:25:15.464  6863  6863 D BluetoothHeadset: Proxy object connected
08-16 14:25:15.464  6863  6863 D HeadsetProfile: Bluetooth service connected
08-16 14:25:15.466  1893  1909 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:25:15.467  1893  1893 D BluetoothHeadset: Proxy object connected
08-16 14:25:15.469  1893  1893 D BluetoothHeadset: Proxy object connected
08-16 14:25:15.469  1051  1115 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 14:25:15.469  1051  1115 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 14:25:15.470  1982  1982 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:15.471  1982  2193 D LGBluetoothAPIService: Message: 1
08-16 14:25:15.471  1982  2193 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 14:25:15.471  1982  2193 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 14:25:15.471  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:25:15.471  1982  2193 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 14:25:15.473  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:15.477  1051  1051 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 14:25:15.477  1051  1115 D BluetoothManagerService: Message: 40
08-16 14:25:15.477  1051  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-16 14:25:15.484  6863  6863 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 14:25:15.486  7673  7673 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:15.486  7673  7673 D BluetoothMapService: STATE_ON
08-16 14:25:15.486  6863  6863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 14:25:15.495  6863  6863 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:25:15.501  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:15.501  7673  7673 V BluetoothPbapService: Pbap Service onCreate
08-16 14:25:15.501  7673  7673 V BluetoothPbapService: Starting PBAP service
08-16 14:25:15.502  7673  7673 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 14:25:15.502  7673  7673 V BluetoothMapService: Handler(): got msg=1
08-16 14:25:15.503  7673  7673 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 14:25:15.503  7673  7673 V BluetoothPbapService: Pbap Service onBind
08-16 14:25:15.504  7673  8028 D BluetoothMapMasInstance: MAS initSocket()
08-16 14:25:15.505  7673  8028 D BluetoothMapMasInstance:   masId = 00
08-16 14:25:15.505  7673  8028 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 14:25:15.505  7673  8028 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 14:25:15.505  7673  8028 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 14:25:15.506  7673  7673 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:15.506  7673  7673 V BluetoothPbapService: state: 12
08-16 14:25:15.506  7673  7673 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:25:15.506  6863  6863 D BluetoothPbap: Proxy object connected
08-16 14:25:15.506  6863  6863 D PbapServerProfile: Bluetooth service connected
08-16 14:25:15.506  7673  7673 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:15.506  7673  7673 V BluetoothPbapReceiver: ***********state = 12
08-16 14:25:15.506  1051  2125 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:15.508  7673  7673 V BluetoothPbapService: Handler(): got msg=1
08-16 14:25:15.509  7673  8028 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:25:15.509  7673  7673 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-16 14:25:15.512  7673  8029 V BluetoothPbapService: Pbap Service initSocket
,08-16 14:25:15.512  2258  2258 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:25:15.512  1051  2127 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:15.512  2258  2258 D c       : Getting all permits...
08-16 14:25:15.512  2258  2258 D a       : Opening database...
08-16 14:25:15.513  7673  8029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:25:15.515  2258  2258 D a       : Opening database auth.proximity.permit_store...
08-16 14:25:15.516  2258  2258 D a       : Closing database...
08-16 14:25:15.517  7673  8029 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 14:25:15.517  7673  8029 V BluetoothPbapService: Succeed to create listening socket 
08-16 14:25:15.517  7673  8029 V BluetoothPbapService: Accepting socket connection...
08-16 14:25:15.518  7673  8028 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 14:25:15.518  7673  8028 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 14:25:15.518  7673  8028 D BluetoothMapMasInstance: Accepting socket connection...
08-16 14:25:15.518  7673  7935 D BluetoothAdapterProperties: Scan Mode:21
08-16 14:25:15.519  7673  7935 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 14:25:15.521  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:25:15.533  6863  6863 D BluetoothPermissionRequest: onReceive
,08-16 14:25:15.535  6863  6863 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 14:25:15.537  6863  6863 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:25:15.540  7673  7673 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 14:25:15.541  7673  7673 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 14:25:15.547  7673  7673 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 14:25:15.566  7673  7673 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 14:25:15.566  7673  7673 V BtOppService: onCreate
,08-16 14:25:15.570  7673  7673 V BluetoothOppNotification: send message
08-16 14:25:15.573  7673  7673 V BtOppService: Starting RfcommListener
08-16 14:25:15.580  7673  7673 D BluetoothOppPreference: Dumping Names:  
08-16 14:25:15.580  7673  7673 D BluetoothOppPreference: {}
08-16 14:25:15.580  7673  7673 D BluetoothOppPreference: Dumping Channels:  
08-16 14:25:15.580  7673  7673 D BluetoothOppPreference: {}
,08-16 14:25:15.581  7673  7673 V BtOppService: onStartCommand
08-16 14:25:15.584  7673  8035 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 14:25:15.585  7673  7673 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:15.586  7673  7673 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 14:25:15.589  7673  7673 V BluetoothOppNotification: new notify threadi!
08-16 14:25:15.589  7673  7673 V BluetoothOppNotification: send delay message
08-16 14:25:15.590  7673  7673 V BtOppService: start RfcommListener
08-16 14:25:15.593  7673  7673 V BtOppService: RfcommListener started
08-16 14:25:15.594  7673  8037 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 14:25:15.595  1051  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:15.596  7673  8037 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:25:15.598  7673  8037 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 14:25:15.598  7673  8037 V BtOppRfcommListener: Started RFCOMM listener....
08-16 14:25:15.598  7673  8037 I BtOppRfcommListener: Accept thread started.
08-16 14:25:15.598  7673  8037 V BtOppRfcommListener: Accepting connection...
08-16 14:25:15.601  7673  8032 V BtOppService: Deleted complete outbound shares, number =  0
08-16 14:25:15.601  7673  8035 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 14:25:15.601  7673  8036 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 14:25:15.603  7673  8032 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 14:25:15.603  7673  8032 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-16 14:25:15.605  7673  8032 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3762d51 on behalf of 
08-16 14:25:15.606  7673  8036 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18c629b6 on behalf of 
08-16 14:25:15.606  7673  8035 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25d966b7 on behalf of 
08-16 14:25:15.607  7673  8036 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-16 14:25:15.610  7673  8036 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 14:25:15.612  7673  8035 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 14:25:15.613  7673  8036 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@366ae24 on behalf of 
08-16 14:25:15.614  7673  8036 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 14:25:15.615  7673  8036 V BluetoothOppNotification: outbound notification was removed.
08-16 14:25:15.615  7673  8036 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 14:25:15.616  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:15.616  7673  7673 V BluetoothFtpService: Ftp Service onCreate
08-16 14:25:15.616  7673  7673 I BluetoothFtpService: Ftp Service onCreate
08-16 14:25:15.616  7673  8036 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38832b42 on behalf of 
08-16 14:25:15.617  7673  7673 V BluetoothFtpService: Ftp Service onStartCommand
08-16 14:25:15.617  7673  7673 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:15.617  7673  8036 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 14:25:15.617  7673  7673 V BluetoothFtpService: Starting Listening on sockets
08-16 14:25:15.618  7673  7673 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:25:15.618  7673  8036 V BluetoothOppNotification: inbound notification was removed.
08-16 14:25:15.618  7673  7673 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:25:15.618  7673  7673 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:25:15.618  7673  8036 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 14:25:15.619  7673  7673 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:25:15.619  7673  7673 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 14:25:15.619  7673  7673 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 14:25:15.620  7673  8036 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e13b753 on behalf of 
,08-16 14:25:15.624  7673  7673 V BtOppService: ContentObserver received notification
08-16 14:25:15.626  7673  7673 V BtOppService: ContentObserver received notification
08-16 14:25:15.626  7673  7673 V BluetoothFtpService: Handler(): got msg=1
08-16 14:25:15.627  7673  8038 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-16 14:25:15.627  7673  8038 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 14:25:15.628  7673  8038 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d728890 on behalf of 
08-16 14:25:15.629  7673  7673 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 14:25:15.629  7673  7673 V BluetoothFtpService: Ftp Service initSocket
08-16 14:25:15.631  7673  8038 V BluetoothOppNotification: update too frequent, put in queue
08-16 14:25:15.631  1051  1734 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:15.632  7673  8038 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 14:25:15.632  7673  7673 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:25:15.633  7673  7673 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 14:25:15.633  7673  7673 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-16 14:25:15.634  7673  8039 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 14:25:15.649  7673  7673 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27426785
08-16 14:25:15.649  7673  7673 V BluetoothSapService: Sap Service onCreate
,08-16 14:25:15.651  7673  7673 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:25:15.651  7673  7673 V BluetoothSapService: state: 12
08-16 14:25:15.651  7673  7673 V BluetoothSapService: Starting SAP server process
08-16 14:25:15.647  8040  8040 W sapd    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:15.647  8040  8040 W sapd    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:15.656  7673  7673 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 14:25:15.657  7673  8041 V BluetoothSapService: Sap Service initRfcommSocket
08-16 14:25:15.658  1051  2127 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:15.659  7673  8041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:25:15.660  7673  8041 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 14:25:15.660  7673  8041 V BluetoothSapService: Succeed to create listening socket 
08-16 14:25:15.660  7673  8041 V BluetoothSapService: Accepting socket connection...
08-16 14:25:15.666  8040  8040 V BT_SAP  : Event pipe created
08-16 14:25:15.666  8040  8040 V BT_SAP  : create_server_socket qcom.sap.server
08-16 14:25:15.666  8040  8040 V BT_SAP  : created socket fd 6
,08-16 14:25:16.095  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:16.095  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:16.095  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:16.095  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:25:16.095  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:16.095  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:16.095  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:16.095  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:25:16.103  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:25:16.105  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:16.105  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@131808c4 added. We now have 8 listener(s)
08-16 14:25:16.105  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:16.108  1051  1066 D WifiServiceImplEx: setWifiEnabled: false pid=6780, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 14:25:16.108  1051  1066 D WifiService: setWifiEnabled: false pid=6780, uid=10118
08-16 14:25:16.108  1051  1066 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 14:25:16.114  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:25:16.118  1051  1726 D WifiServiceImplEx: setWifiEnabled: true pid=6780, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 14:25:16.119  1051  1726 D WifiService: setWifiEnabled: true pid=6780, uid=10118
08-16 14:25:16.119  1051  1726 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 14:25:16.132  1051  1051 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 14:25:16.135  1051  1051 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-16 14:25:16.135  1051  1051 D Ulp_jni : JNI:system_update. Event-4
,08-16 14:25:16.137  1051  1555 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 14:25:16.137  1051  1555 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 14:25:16.139  1051  1555 E WifiUtil: wfc_util_ffile_check_copy(): pid[1051] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 14:25:16.139  1051  1555 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 14:25:16.140  1051  1555 E WifiUtil: wfc_util_ffile_check_copy(): pid[1051] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 14:25:16.140  1051  1555 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 14:25:16.140  1051  1555 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 14:25:16.140  1051  1555 E WifiHW  : unknown target_country: EU , set to default
08-16 14:25:16.140  1051  1555 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-16 14:25:16.140  1051  1555 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
08-16 14:25:16.140  1051  1555 I WifiUtil: gEnableBmps=1
,08-16 14:25:16.592  7673  7673 V BluetoothOppNotification: new notify threadi!
,08-16 14:25:16.607  7673  7673 V BluetoothOppNotification: send delay message
,08-16 14:25:16.614  7673  8060 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 14:25:16.621  7673  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@201f9dbc on behalf of 
08-16 14:25:16.622  7673  8060 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 14:25:16.625  7673  8060 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 14:25:16.626  7673  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@aeda145 on behalf of 
08-16 14:25:16.627  7673  8060 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 14:25:16.629  7673  8060 V BluetoothOppNotification: outbound notification was removed.
08-16 14:25:16.629  7673  8060 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 14:25:16.630  7673  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@eaee09a on behalf of 
08-16 14:25:16.630  7673  8060 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 14:25:16.635  7673  8060 V BluetoothOppNotification: inbound notification was removed.
08-16 14:25:16.635  7673  8060 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 14:25:16.637  7673  8060 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a00bdcb on behalf of 
08-16 14:25:16.741   310   910 D SoftapController: Softap fwReload - Ok
,08-16 14:25:16.752  1051  1555 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (607ms)
08-16 14:25:16.759   310   910 D CommandListener: Setting iface cfg
08-16 14:25:16.760   310   910 D CommandListener: Trying to bring down wlan0
,08-16 14:25:16.764  1051  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 14:25:16.765  1051  1115 D Tethering: InitialState.processMessage what=4
,08-16 14:25:16.784   310   910 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:25:16.793  1051  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 14:25:16.798  1051  1555 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 14:25:16.797  8062  8062 W wpa_supplicant: type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 14:25:16.807  8062  8062 W wpa_supplicant: type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 14:25:16.829  1051  1555 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:25:16.829  1051  1555 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:25:16.829  1051  1555 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 14:25:16.832  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:25:16.839  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-16 14:25:16.857  1051  1555 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 14:25:16.857  1051  1555 D WifiMonitor: connecting to supplicant
08-16 14:25:16.866  8062  8062 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 14:25:16.869  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:25:16.871  1051  1051 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 14:25:16.875  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 14:25:16.875  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:25:16.875  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:25:16.875  6863  6863 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:25:16.876  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:25:16.877  6863  6863 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-16 14:25:16.877  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 14:25:16.877  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:25:16.877  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:25:16.877  6863  6863 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:25:16.877  6863  6863 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 14:25:16.880  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 14:25:16.880  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:25:16.880  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:25:16.880  6863  6863 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:25:16.880  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:25:16.881  6863  6863 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:25:16.881  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 14:25:16.881  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:25:16.881  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:25:16.881  6863  6863 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:25:16.881  6863  6863 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 14:25:16.900  8062  8062 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 14:25:16.901  8062  8062 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 14:25:16.934  1051  2072 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8079 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 14:25:16.959  8062  8062 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 14:25:17.003  8062  8062 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 14:25:17.009  8062  8062 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-16 14:25:17.011  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 14:25:17.012  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 14:25:17.014  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 14:25:17.015  1051  1555 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 14:25:17.015  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.015  1051  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 14:25:17.016  1051  8101 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 14:25:17.016  1051  1555 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.017  1051  1555 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.018  1051  1555 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.019  1051  1555 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 14:25:17.019  1051  1555 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 14:25:17.020  1051  1555 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 14:25:17.020  8062  8062 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 14:25:17.020  1051  1555 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 14:25:17.020  1051  1555 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 14:25:17.020  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 14:25:17.020  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 14:25:17.021  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 14:25:17.021  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 14:25:17.021  1051  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 14:25:17.021  1051  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 14:25:17.032  1051  1964 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8103 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 14:25:17.034  1051  1555 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:25:17.034  1051  1555 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:25:17.034  1051  1555 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:25:17.035  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.035  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.035  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.036  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.036  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:25:17.037  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:17.038  1982  1982 D WfdService: Waiting for WifiP2p enabling
08-16 14:25:17.040  1051  1051 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 14:25:17.041  1051  1555 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 14:25:17.041  1051  1559 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 14:25:17.041  1051  1555 D WifiNative-wlan0: SET update_config 1: returned true
08-16 14:25:17.041  1051  1555 D WifiConfigStore: Loading config and enabling all networks 
08-16 14:25:17.041  1051  1555 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 14:25:17.042  1051  1555 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 14:25:17.046  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:17.046  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:17.046  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:17.046  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:25:17.046  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:17.046  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:17.046  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:17.046  6780  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:25:17.047  6780  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:25:17.051  1051  1555 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 14:25:17.051  8079  8102 V FormManager: Network unavailable.
08-16 14:25:17.051  8079  8100 W FormManager: Network not available. Please check & try again.
08-16 14:25:17.053  8079  8102 V FormManager: Network unavailable.
08-16 14:25:17.063  1051  1555 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 14:25:17.064  1051  1555 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 14:25:17.064  1051  1555 D WifiStateMachine: enableVerboseLogging : level 2
08-16 14:25:17.064  1051  1555 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-16 14:25:17.066  1051  1555 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 14:25:17.066  1051  1555 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 14:25:17.067  1051  1555 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 14:25:17.067  1051  1555 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 14:25:17.067  1051  1555 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 14:25:17.067  1051  1555 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 14:25:17.068  1051  1555 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 14:25:17.068  1051  2072 I ActivityManager: Killing 7176:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 14:25:17.068  1051  1555 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 14:25:17.069  1051  1555 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 14:25:17.069  1051  1555 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 14:25:17.069  1051  1555 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 14:25:17.069  1051  1555 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 14:25:17.070  1051  1555 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 14:25:17.072  7773  7784 E UEI.SmartControl: file observer is disposed!
08-16 14:25:17.099  1051  1555 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:25:17.099  1051  1555 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-16 14:25:17.101  1051  1555 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 14:25:17.101  1051  1555 D WifiNative-HAL: Setting external_sim to 1
08-16 14:25:17.101  1051  1555 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 14:25:17.102  1051  1555 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 14:25:17.102  1051  1555 I WifiNative-HAL: startHal
08-16 14:25:17.102  1051  1555 D wifi    : setting scan oui 0xaf7a60a0
08-16 14:25:17.103  1051  1555 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:25:17.103  1051  1555 I WifiNative-HAL: startHal
08-16 14:25:17.103  1051  1555 D wifi    : setting scan oui 0xaf7a60a0
08-16 14:25:17.103  1051  1555 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 14:25:17.103  1051  1593 W libprocessgroup: failed to open /acct/uid_10062/pid_7176/cgroup.procs: No such file or directory
08-16 14:25:17.104  1051  1555 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 14:25:17.104  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 14:25:17.104  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 14:25:17.104  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 14:25:17.104  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 14:25:17.105  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 14:25:17.105  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 14:25:17.105  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 14:25:17.105  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 14:25:17.105  7703  7703 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.105  1982  1982 D WfdsService: Supplicant Connection state is changed : true
08-16 14:25:17.106  1982  2375 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 14:25:17.106  1982  2375 D WfdsService: Set the WFDS Monitor: true
08-16 14:25:17.106  1982  2375 D WfdsMonitor: WfdsMonitorThread create
08-16 14:25:17.106  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 14:25:17.106  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 14:25:17.106  1982  2375 D WfdsMonitor: WFDS Monitor is created and started
08-16 14:25:17.106  1982  2375 D WfdsService: WiFi: Supplicant connection re-established
08-16 14:25:17.106  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 14:25:17.106  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 14:25:17.106  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 14:25:17.107  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 14:25:17.107  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 14:25:17.107  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 14:25:17.107  8062  8062 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 14:25:17.107  1982  8121 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 14:25:17.107  1982  8121 E CtrlSupplicant: Succeed to open control connection
08-16 14:25:17.108  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 14:25:17.108  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 14:25:17.108  1982  8121 E CtrlSupplicant: Succeed to open monitor connection
08-16 14:25:17.108  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 14:25:17.108  1982  8121 D WfdsMonitor: Supplicant connection established
08-16 14:25:17.108  1982  2375 D WfdsService: Connected to the supplicant for wfds
08-16 14:25:17.109  1051  1555 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 14:25:17.110  1051  1555 E WifiNative: : [230,707,236 us] RECONNECT  stack:logDbg - reconnect - e,nter - invokeEnterMethods - performTransitions
08-16 14:25:17.110  1051  1555 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 14:25:17.111  1051  1555 D WifiNative-wlan0: RECONNECT: returned true
08-16 14:25:17.111  1051  1555 D WifiNative-wlan0: doString: [STATUS]
,08-16 14:25:17.111  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 14:25:17.111  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 14:25:17.112  1051  1555 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 14:25:17.112  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:25:17.113  1051  1555 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:25:17.113  1051  1553 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.114   310   910 D CommandListener: Setting iface cfg
08-16 14:25:17.115   310   910 D CommandListener: Trying to bring up p2p0
08-16 14:25:17.115  1051  1051 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 14:25:17.115  1051  1051 D RttService: SCAN_AVAILABLE : 3
08-16 14:25:17.115  1051  1572 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.115  1051  1572 I WifiNative-HAL: startHal
08-16 14:25:17.115  1051  1572 D wifi    : getting scan capabilities on interface[1] = 0xaf7a60a0
08-16 14:25:17.115  1051  1573 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.115  1051  1572 D wifi    : failed to get capabilities : -3
08-16 14:25:17.115  1051  1572 E WifiScanningService: could not get scan capabilities
08-16 14:25:17.115  1051  1555 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 14:25:17.115  1051  1553 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 14:25:17.115  1051  1553 D LGWifiP2pService: P2pEnablingState
08-16 14:25:17.115  1051  1553 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.115  1051  1553 D LGWifiP2pService: P2p socket connection successful
08-16 14:25:17.115  1051  1553 D LGWifiP2pService: P2pEnabledState
08-16 14:25:17.115  1051  1553 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 14:25:17.115  1051  1555 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 14:25:17.116  1051  1553 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 14:25:17.116  1051  1553 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 14:25:17.117  1051  1553 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 14:25:17.117  1051  1553 D WifiNative-p2p0: SET device_name G3: returned true
08-16 14:25:17.117  1051  1553 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 14:25:17.117  1051  1553 D LGWifiP2pService: before postfix = G3
08-16 14:25:17.117  1051  1553 D WifiServerServiceExt: postfix byte check : 2
08-16 14:25:17.117  1051  1553 D LGWifiP2pService: after postfix = G3
08-16 14:25:17.117  1051  1553 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 14:25:17.118  1051  1553 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 14:25:17.118  1982  1982 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 14:25:17.118  1051  1553 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 14:25:17.118  1982  1982 D WfdsService: WifiP2pState is changed : true
08-16 14:25:17.119  1982  1982 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 14:25:17.119  1051  1555 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 14:25:17.119  1982  1982 D WfdsService: isConnected: false
08-16 14:25:17.119  1982  2375 D WfdsService: Receive the WFDS_ENABLE Method
08-16 14:25:17.119  1051  1553 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 14:25:17.119  1982  2375 D WfdsService: Set the WFDS Monitor: true
08-16 14:25:17.119  1051  1553 D WifiNative-p2p0: doBoolean: SET config_meth,ods virtual_push_button physical_display keypad
08-16 14:25:17.119  1982  2375 D WfdsService: Connected to the supplicant for wfds
08-16 14:25:17.119  1982  2375 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 14:25:17.120  8062  8062 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 14:25:17.120  1982  2375 D WfdsService: selectPreferredScanChannel [36]
08-16 14:25:17.120  1982  2375 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 14:25:17.120  1051  1555 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 14:25:17.121  1051  1553 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 14:25:17.121  1051  1553 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 14:25:17.121  1051  1553 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 14:25:17.121  1051  1553 D WifiNative-HAL: p2pGetDeviceAddress
08-16 14:25:17.122  1051  1553 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 14:25:17.122  1051  1553 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 14:25:17.122  1051  1553 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 14:25:17.122  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=230720  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:25:17.123  1051  1553 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 14:25:17.123  1051  1553 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-16 14:25:17.124  1982  1982 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 14:25:17.124  1982  1982 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 14:25:17.124  1982  1982 D WfdsService: Update P2p Interface State: 3
08-16 14:25:17.124  1051  1553 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 14:25:17.124  1051  1553 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 14:25:17.125  1051  1553 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 14:25:17.125  1051  1553 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 14:25:17.125  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=230723  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:25:17.125  1051  1555 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 14:25:17.126  1051  1555 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 14:25:17.126  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.126  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.126  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 14:25:17.126  1051  1555 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 14:25:17.126  1051  1555 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 14:25:17.128  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 14:25:17.128  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:17.130  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:17.136  8062  8062 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 14:25:17.136  1051  1553 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 14:25:17.137  1051  1553 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 14:25:17.137  1051  1555 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 14:25:17.137  1051  1553 D LGWifiP2pService: InactiveState
08-16 14:25:17.137  1051  1553 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.137  1051  1555 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 14:25:17.137  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.137  1051  1553 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 14:25:17.138  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 14:25:17.139  8062  8062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 14:25:17.139  8062  8062 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 14:25:17.139  8062  8062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.140  1051  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:25:17.140  1051  1553 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 14:25:17.140  1051  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:25:17.140  1051  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:25:17.140  1051  1553 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.140  1051  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:25:17.140  8062  8062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.140  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.140  1051  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:25:17.140  1051  1553 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.140  1051  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.140  1051  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.140  1051  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.140  1051  1553 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.140  1051  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:25:17.140  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.140  1051  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.140  1051  1553 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.141  1051  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.141  1051  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.141  1051  1553 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.141  1982  2375 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 14:25:17.141  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.141  1982  8121 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:25:17.141  1051  1553 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.141  1982  8121 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:25:17.141  1982  8121 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:25:17.141  1051  1553 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.141  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.141  1051  1553 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.St,ateMachine$SmHandler }
08-16 14:25:17.141  1051  1051 E WifiServerServiceExt: No p2p device connected
08-16 14:25:17.142  1051  1555 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 14:25:17.142  1051  1555 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 14:25:17.142  8062  8062 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 14:25:17.143  1051  1555 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 14:25:17.144  1051  1555 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 14:25:17.144  1051  1555 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 14:25:17.144  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 14:25:17.145  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 14:25:17.145  8062  8062 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:25:17.145  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:25:17.145  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:25:17.146  1051  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:25:17.146  1051  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:25:17.146  8062  8062 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 14:25:17.146  8062  8062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.146  1051  1555 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 14:25:17.146  1982  8121 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:25:17.146  1051  1553 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.146  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.147  8062  8062 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.147  1982  8121 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:25:17.147  1051  1555 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:25:17.147  1051  1555 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:25:17.147  1051  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:25:17.147  1051  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.147  1051  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.147  1051  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.147  1051  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:25:17.148  1051  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.148  1051  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.148  1051  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:25:17.148  1051  1555 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:25:17.148  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 14:25:17.148  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 14:25:17.148  8062  8062 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:25:17.148  8103  8103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:17.149  1051  8101 D WifiM,onitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 14:25:17.149  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:25:17.149  1051  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:25:17.149  1051  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:25:17.149  1051  1555 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 14:25:17.149  1051  1555 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 14:25:17.150  1051  1555 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 14:25:17.150  1051  1555 D WifiNative-wlan0: doBoolean: SCAN
08-16 14:25:17.150  1051  1555 D WifiNative-wlan0: SCAN: returned false
08-16 14:25:17.151  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=230749  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:25:17.151  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:25:17.151  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:17.151  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:17.151  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:25:17.151  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:17.151  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:25:17.151  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:25:17.151  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:25:17.154  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:25:17.155  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:25:17.156  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=230754  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:25:17.156  1051  1555 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:25:17.157  1051  1555 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:25:17.157  1051  1555 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:25:17.158  1051  1555 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:25:17.158  1051  1555 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:25:17.160  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:17.160  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:17.161  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.161  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.161  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 14:25:17.161  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:17.161  1051  1051 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 14:25:17.161  6780  6850 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 14:25:17.161  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:17.162  6780  6850 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 14:25:17.163  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:17.165  1051  2028 I ActivityManager: Killing 7200:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 14:25:17.165  6780  6850 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e5a8900 Bundle[{}]
08-16 14:25:17.166  6780  6850 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 14:25:17.166  6780  6850 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 14:25:17.166  6780  6850 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 14:25:17.167  6780  6850 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 14:25:17.168  6780  6850 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 14:25:17.169  6780  6850 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 14:25:17.174  6780  6850 I System.out: Running OutgoingSocketThread
08-16 14:25:17.175  6780  8124 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 866)
08-16 14:25:17.176  6780  8124 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42672
08-16 14:25:17.176  6780  8124 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 14:25:17.202  1051  2006 W libprocessgroup: failed to open /acct/uid_10085/pid_7200/cgroup.procs: No such file or directory
08-16 14:25:17.217  8103  8103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:25:17.220  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:25:17.224  8079  8126 W FormManager: Network not available. Please check & try again.
08-16 14:25:17.225  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:17.234  8079  8127 V FormManager: Network unavailable.
,08-16 14:25:17.239  8079  8127 V FormManager: Network unavailable.
08-16 14:25:17.243  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:25:17.243  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:25:17.247  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:25:17.255  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:25:17.263  4317  8128 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:25:17.265  4317  8129 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:25:17.265  4317  8129 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:25:17.317  1051  1964 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8130 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 14:25:17.455  8130  8130 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 14:25:17.455  8130  8130 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 14:25:17.466  8130  8130 V [BNRBootReceiver]: Boot Receiver Return
08-16 14:25:17.467  8130  8130 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 14:25:17.542  1051  1593 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8151 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 14:25:17.543  1051  1593 I ActivityManager: Killing 7236:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-16 14:25:17.642  8062  8062 E wpa_supplicant: USIM:  scard_init function
08-16 14:25:17.642  8062  8062 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 14:25:17.645  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 14:25:17.645  1051  8101 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 14:25:17.645  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 14:25:17.645  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-16 14:25:17.645  1051  8101 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 14:25:17.645  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 14:25:17.645  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-16 14:25:17.647  1051  1555 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-16 14:25:17.648  1051  1555 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-16 14:25:17.648  1051  1555 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-16 14:25:17.649  1051  1555 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 14:25:17.649  1051  1555 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 14:25:17.757  1051  1734 W libprocessgroup: failed to open /acct/uid_10093/pid_7236/cgroup.procs: No such file or directory
,08-16 14:25:17.790  8062  8062 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 14:25:17.799  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 14:25:17.799  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 14:25:17.799  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 14:25:17.800  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 14:25:17.800  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:25:17.800  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:25:17.802  8062  8062 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:25:17.802  8062  8062 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:25:17.808  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:25:17.808  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:25:17.808  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 14:25:17.808  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:25:17.808  1051  8101 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:25:17.808  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 14:25:17.808  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-16 14:25:17.815  1051  8101 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:25:17.815  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:25:17.815  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:25:17.820  1051  1115 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 14:25:17.826  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=231424  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 14:25:17.835  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=231433  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 14:25:17.836  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=231434  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 14:25:17.836  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=231434  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 14:25:17.837  1051  1555 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231435
08-16 14:25:17.837  1051  1555 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231435
08-16 14:25:17.838  1051  1555 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231436
08-16 14:25:17.838  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231436
08-16 14:25:17.842  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.843  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.843  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-16 14:25:17.847  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:17.847  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:17.849  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:17.852  1051  1555 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=231450
08-16 14:25:17.853  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=231451  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 14:25:17.860  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.861  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.861  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-16 14:25:17.864  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=231462  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 14:25:17.865  1051  1555 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=231463  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 14:25:17.865  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=231463  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 14:25:17.874  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.874  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.874  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-16 14:25:17.889  1051  1555 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=231487
08-16 14:25:17.889  1051  1555 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=231487
08-16 14:25:17.890  1051  1555 D WifiNative-wlan0: doString: [STATUS]
,08-16 14:25:17.893  1051  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:25:17.893  1051  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:25:17.894  1051  1555 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 14:25:17.895  1051  1555 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 14:25:17.902  1051  1555 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 14:25:17.902  1051  1555 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-16 14:25:17.920  1051  1555 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-16 14:25:17.922  1051  1561 D ConnectivityService: Got NetworkAgent Messenger
08-16 14:25:17.923  1051  1561 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 14:25:17.923  1051  1561 D ConnectivityService: NetworkAgent connected
08-16 14:25:17.923  1051  1555 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:25:17.923  1051  1555 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:25:17.924  1051  1555 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:25:17.924  1051  1555 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:25:17.930  1051  1555 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 14:25:17.930  1051  1555 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:25:17.930  1051  1555 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:25:17.931  1051  1555 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:25:17.931  1051  1555 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:25:17.934  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:17.934  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 14:25:17.942  1051  1555 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 14:25:17.944  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:17.946  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:17.946  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:17.948   310   910 D CommandListener: Setting iface cfg
,08-16 14:25:17.951  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:17.967  1051  1555 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 14:25:17.968  1051  1555 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=231566  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 14:25:17.973  1051  1555 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=231571  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:17.975  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=231572  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:17.976  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.977  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.978  1051  1555 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.979  1051  8175 D DhcpStateMachine: StoppedState
08-16 14:25:17.979  1051  8175 D DhcpStateMachine: StoppedState{ when=-12ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:17.979  1051  8175 D DhcpStateMachine: WaitBeforeStartState
08-16 14:25:17.980  1051  1555 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.980  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.981  1051  1555 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:25:17.982  1051  1555 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=231580  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:17.982  1051  1555 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=231580  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:17.983  1051  1555 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=231581  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:25:17.984  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14198] from screen [on:0 period:-1823464544] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:25:17.985  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1823464543] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:25:17.985  1051  1555 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 14:25:17.989  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.990  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.990  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 14:25:17.991  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:17.991  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:17.992  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.992  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:17.992  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 14:25:17.992  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:17.992  1051  1051 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 14:25:17.993  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:17.995  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:17.995  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:17.995  1051  1561 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 14:25:17.996  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:17.996  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:17.996  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:17.997  1051  1555 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:17.998  1051  1555 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:17.998  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 14:25:18.000  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:18.000  1051  1561 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 14:25:18.001  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:18.001  1051  1051 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 14:25:18.002  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-16 14:25:18.002  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
,08-16 14:25:18.002  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 14:25:18.003  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 14:25:18.003  1051  1555 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 14:25:18.003  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 14:25:18.003  1051  1555 D WifiNative-wlan0: SET ps 0: returned true
08-16 14:25:18.003  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 14:25:18.004  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 14:25:18.004  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 14:25:18.004  1051  1555 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 14:25:18.004  1051  1555 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 14:25:18.004  1051  1553 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f41053b target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:18.004  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f41053b target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:18.005  1051  8175 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:18.005  1051  8175 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 14:25:18.005  1051  1555 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 14:25:18.006   310   910 D CommandListener: Setting iface cfg
08-16 14:25:18.006   310   910 D CommandListener: Trying to bring up wlan0
08-16 14:25:18.007  1051  1555 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 14:25:18.008  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:18.009  1051  1051 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:25:18.009  1051  1051 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 14:25:18.011  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:18.011  1051  1555 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:18.011  1051  1555 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:18.011  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:18.012  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:25:18.012  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 14:25:18.012  1051  1561 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 14:25:18.013  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 14:25:18.013  1051  1553 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:18.013  1051  1553 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:18.013  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:25:18.013  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:25:18.014  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:18.014  1051  1555 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:25:18.014  1051  1555 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 14:25:18.014  8062  8062 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 14:25:18.016  105,1  1555 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 14:25:18.016  1051  1555 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 14:25:18.029  8151  8151 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:25:18.031  1051  1555 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:25:18.031  1051  1561 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 14:25:18.032  1051  1555 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 14:25:18.032  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 14:25:18.032  1051  1555 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 14:25:18.032  1051  1561 D ConnectivityService: ignoring duplicate network state non-change
,08-16 14:25:18.036  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:18.036  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:18.036  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 14:25:18.038  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:18.038  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:25:18.040  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:18.041  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:18.042  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 14:25:18.042  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:18.042  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:18.042  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 14:25:18.042  1051  1561 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 14:25:18.042  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:18.043  1051  1561 D ConnectivityService: Adding iface wlan0 to network 102
08-16 14:25:18.046  1051  1555 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 14:25:18.048  1051  1051 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 14:25:18.048  1982  1982 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 14:25:18.049  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:18.049  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:18.049  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 14:25:18.050  1051  1051 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-16 14:25:18.054  1051  1051 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:18.054  1051  1051 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:25:18.054  1051  1051 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 14:25:18.061  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:18.061  1619  1619 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 14:25:18.061  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:18.063  8151  8151 D PluginManager: init()
08-16 14:25:18.064  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:25:18.064  1619  1619 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 14:25:18.064  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:18.070  1051  1561 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 14:25:18.070  1051  1561 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 14:25:18.071  1051  1561 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 14:25:18.072   310   910 E Netd    : netlink response contains error (File exists)
08-16 14:25:18.072  1051  1561 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 14:25:18.073  1051  1561 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 14:25:18.073  1051  1561 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 14:25:18.073  1051  1561 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 14:25:18.074  1051  1561 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 14:25:18.074  1051  1561 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 14:25:18.074  1051  1561 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 14:25:18.074  1051  1561 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 14:25:18.074  1051  1561 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:25:18.074  1051  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:18.074  1051  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 14:25:18.074  1051  1561 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:18.074  1051  1561 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 14:25:18.074  1051  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:25:18.074  1051  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 14:25:18.074  1051  1561 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:18.074  1051  1561 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 14:25:18.074  1051  1561 D ConnectivityService: currentScore = 0, newScore = 20
08-16 14:25:18.074  1051  1561 D ConnectivityService:    accepting network in place of null
08-16 14:25:18.074  1051  1561 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:18.075  1051  1555 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:18.075  1051  1555 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:25:18.076   310  8197 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 14:25:18.077  1051  1561 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WI,FI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 14:25:18.077  1051  1561 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 14:25:18.077  1051  1561 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:25:18.077   310  8197 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 14:25:18.077  1051  1561 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:25:18.077  1051  1561 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 14:25:18.078  1051  1561 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 14:25:18.078   310  8197 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
08-16 14:25:18.079   310  8197 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
08-16 14:25:18.079  1051  1561 D ConnectivityService: validation of new default Network = false
08-16 14:25:18.079  1051  1561 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 14:25:18.079  1051  1561 D DSQN    : enableDataServiceNotify 
08-16 14:25:18.079  1051  1561 D DSQN    : start dsqn bin
08-16 14:25:18.079  1051  8174 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 14:25:18.080  1893  1893 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:18.080  1051  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 14:25:18.080  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:25:18.082  1051  1051 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-16 14:25:18.082  1051  1051 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:25:18.082  1051  1051 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:25:18.082  1051  1051 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-16 14:25:18.097  8199  8199 W dsqn    : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:18.102  1051  1561 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 14:25:18.102  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:18.102  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:18.103  1051  1561 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:18.097  8199  8199 W dsqn    : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:18.104  1619  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 14:25:18.109  1051  1552 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 14:25:18.109  1855  8198 I CheckinService: active receiver: enabled
08-16 14:25:18.113  1855  8198 I CheckinService: Preparing to send checkin request
08-16 14:25:18.113  1855  8198 I EventLogService: Accumulating logs since 1471350301045
,08-16 14:25:18.118  8199  8199 E DSQN    : DSQN ssw
08-16 14:25:18.120  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:25:18.120  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:18.121  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:25:18.152  1855  8198 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 14:25:18.175  6780  6850 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 867)
08-16 14:25:18.175  6780  6850 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 867)
08-16 14:25:18.178  6780  6850 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 872)
,08-16 14:25:18.178  6780  6850 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 14:25:18.178  6780  6850 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 873)
08-16 14:25:18.180  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.180  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7fa3ad added. We now have 2 listener(s)
08-16 14:25:18.181  1051  1734 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.183  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:25:18.183  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.183  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.183  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.183  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@320596e2 added. We now have 9 listener(s)
08-16 14:25:18.183  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.184  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:25:18.186  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:25:18.188  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:25:18.188  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:18.188  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:18.188  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:25:18.188  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:18.188  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.188  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:25:18.188  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:25:18.191  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.191  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:25:18.191  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.191  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33eeed30 added. We now have 3 listener(s)
08-16 14:25:18.192  1051  1731 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.193  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.193  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:25:18.193  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.193  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.193  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.193  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1fcda9 added. We now have 10 listener(s)
08-16 14:25:18.193  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.193  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:25:18.194  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:25:18.194  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:25:18.194  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.194  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.194  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:25:18.194  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.194  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7fa3ad removed from the list
08-16 14:25:18.194  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.194  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@320596e2 removed from the list
08-16 14:25:18.195  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.195  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:25:18.195  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.196  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.196  6780  6850 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.197  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.197  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.197  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.197  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@320596e2 not in the list
08-16 14:25:18.197  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.197  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.198  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.198  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.198  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.198  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1fcda9 removed from the list
08-16 14:25:18.198  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.198  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.198  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.198  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.198  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33eeed30 removed from the list
08-16 14:25:18.198  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.199  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13ea3f2e added. We now have 2 listener(s)
08-16 14:25:18.199  1051  1731 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.200  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 14:25:18.200  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.200  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.200  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.200  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25911acf added. We now have 9 listener(s)
08-16 14:25:18.200  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.200  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:25:18.202  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:25:18.203  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:25:18.203  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:18.203  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:18.203  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:25:18.203  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:18.203  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.203  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:25:18.203  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:25:18.204  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.204  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:25:18.204  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.205  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b7e9b65 added. We now have 3 listener(s)
08-16 14:25:18.205  1051  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.206  1051  8175 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 14:25:18.207  1051  8175 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 14:25:18.207  1051  8175 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 14:25:18.207  8204  8204 W dhcpcd  : type=1400 audit(0.0:197): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:18.207  8204  8204 W dhcpcd  : type=1400 audit(0.0:198): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:25:18.209  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.210  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:25:18.210  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.210  6780  685,0 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.210  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.210  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d5f203a added. We now have 10 listener(s)
08-16 14:25:18.210  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.210  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:25:18.210  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:25:18.210  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:25:18.210  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:25:18.210  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:25:18.213  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 14:25:18.213  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.213  1051  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.214  8204  8204 I dhcpcd  : version 5.5.6 starting
08-16 14:25:18.215  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:25:18.215  8204  8204 E dhcpcd  : get_duid: m
08-16 14:25:18.215  8204  8204 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 14:25:18.215  8204  8204 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 14:25:18.216  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 14:25:18.216  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:25:18.217  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:25:18.217  6780  6850 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:25:18.218  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:25:18.218  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:25:18.219  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:25:18.219  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:25:18.219  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:25:18.219  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.219  6780  6850 W org.thaliproject.p2p.btconnectorlib.interna,l.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.219  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:25:18.219  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.219  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13ea3f2e removed from the list
08-16 14:25:18.219  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.219  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25911acf removed from the list
08-16 14:25:18.219  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:25:18.219  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.219  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.219  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.220  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.220  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.220  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.220  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25911acf not in the list
08-16 14:25:18.220  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.220  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.220  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.221  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:25:18.221  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:25:18.221  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.221  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.221  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d5f203a removed from the list
08-16 14:25:18.221  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.221  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.221  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.221  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.221  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b7e9b65 removed from the list
08-16 14:25:18.221  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.221  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34288e1 added. We now have 2 listener(s)
08-16 14:25:18.221  1051  2125 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.223  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:25:18.223  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.223  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.223  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.223  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@280f0606 added. We now have 9 listener(s)
08-16 14:25:18.223  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.224  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:25:18.225  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:25:18.227  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:25:18.227  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:18.227  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:18.227  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:25:18.227  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:18.227  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.227  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:25:18.227  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:25:18.228  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.228  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:25:18.228  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.228  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27712af4 added. We now have 3 listener(s)
08-16 14:25:18.229  1051  2127 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.230  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:25:18.231  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.231  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.231  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.231  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32fdd21d added. We now have 10 listener(s)
08-16 14:25:18.231  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.231  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:25:18.231  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:25:18.231  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:25:18.231  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:25:18.231  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:25:18.231  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:25:18.235  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.237  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.238  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 14:25:18.238  1051  1731 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.240  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:25:18.240  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 14:25:18.241  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:25:18.241  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:25:18.242  6780  6850 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:25:18.242  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:25:18.242  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:25:18.242  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:25:18.242  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.242  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.242  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:25:18.242  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.243  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34288e1 removed from the list
08-16 14:25:18.243  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.243  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@280f0606 removed from the list
08-16 14:25:18.243  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:25:18.243  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.243  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.243  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.244  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.244  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.244  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.244  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@280f0606 not in the list
08-16 14:25:18.244  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.244  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.244  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.244  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:25:18.245  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:25:18.245  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.245  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.245  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32fdd21d removed from the list
08-16 14:25:18.245  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.245  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.245  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.245  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.245  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27712af4 removed from the list
08-16 14:25:18.245  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.245  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f00260 added. We now have 2 listener(s)
08-16 14:25:18.245  1051  2072 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.247  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:25:18.247  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.247  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.247  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.247  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a7319 added. We now have 9 listener(s)
08-16 14:25:18.247  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.247  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:25:18.250  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:25:18.252  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:25:18.252  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:18.252  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:18.252  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:25:18.252  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:18.252  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.252  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:25:18.252  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:25:18.253  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.253  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:25:18.253  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.253  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@155455bf added. We now have 3 listener(s)
08-16 14:25:18.253  1051  2071 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.254  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.255  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.260  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 14:25:18.260  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.260  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.260  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.260  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17c2e48c added. We now have 10 listener(s)
08-16 14:25:18.260  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.260  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:25:18.260  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:25:18.260  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:25:18.260  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:25:18.260  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:25:18.263  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 14:25:18.264  1051  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.265  7773  7894 D UEI.SmartControl: Internal timer expired: 3
08-16 14:25:18.265  7773  7894 D UEI.SmartControl: unbind internal service
08-16 14:25:18.266  7773  7773 D UEI.SmartControl: Service.onUnbind: IControl
08-16 14:25:18.266  7773  7773 D UEI.SmartControl: Service.onDestroy
08-16 14:25:18.266  7773  7773 D UEI.SmartControl: Lock is in USE false
08-16 14:25:18.266  7773  7773 D UEI.SmartControl: unbind internal service
08-16 14:25:18.267  7773  7773 D serial_port: close(fd = 24)
08-16 14:25:18.268  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:25:18.268  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 14:25:18.270  7773  7773 I UEI.SmartControl: Serial port is closed.
08-16 14:25:18.270  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:25:18.270  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:25:18.271  8204  8204 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 14:25:18.271  7773  7773 I UEI.SmartControl: Serial port is closed.
08-16 14:25:18.271  8204  8204 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 14:25:18.271  8204  8204 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 14:25:18.271  7773  7773 D UEI.SmartControl: Blaster closed
08-16 14:25:18.271  8204  8204 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 14:25:18.272  8204  8204 D dhcpcd  : wlan0: sending REQUEST (xid 0x50190469), next in 4.37 seconds
08-16 14:25:18.275  6780  6850 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:25:18.277  7773  7773 D UEI.SmartControl: Shut down QS...
08-16 14:25:18.277  7773  7773 D UEI.SmartControl: Stopping QS lib
08-16 14:25:18.277  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:25:18.277  7773  7773 D UEI.SmartControl: QS lib stop result = true
08-16 14:25:18.277  7773  7773 D UEI.SmartControl: Stopped QS lib
08-16 14:25:18.277  7773  7773 D UEI.SmartControl: QS shutdown complete
08-16 14:25:18.277  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:25:18.277  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:25:18.277  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.277  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.277  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:25:18.277  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.277  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f00260 removed from the list
08-16 14:25:18.277  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.278  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a7319 removed from the list
08-16 14:25:18.278  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:25:18.278  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.279  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.279  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.279  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.279  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.279  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.279  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a7319 not in the list
08-16 14:25:18.279  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.279  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.280  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.280  6780  6850 D BluetoothLeScanner: could not find callback wrapper
08-16 14:25:18.280  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:25:18.280  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.280  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.280  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17c2e48c removed from the list
08-16 14:25:18.280  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.280  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.280  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.280  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.280  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@155455bf removed from the list
08-16 14:25:18.281  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.281  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c028edb added. We now have 2 listener(s)
08-16 14:25:18.281  1051  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.283  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:25:18.283  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.283  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.283  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.283  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cffbd78 added. We now have 9 listener(s)
08-16 14:25:18.283  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.283  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:25:18.285  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:25:18.287  6780  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:25:18.287  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:25:18.287  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:25:18.287  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:25:18.287  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:25:18.287  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.287  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:25:18.287  6780  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:25:18.288  6780  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:25:18.288  6780  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:25:18.289  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:25:18.289  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26aafcb6 added. We now have 3 listener(s)
08-16 14:25:18.289  1051  2072 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:25:18.289  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.290  6780  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:25:18.291  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:25:18.291  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:25:18.291  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:25:18.291  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:25:18.291  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a913db7 added. We now have 10 listener(s)
08-16 14:25:18.291  6780  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:25:18.291  6780  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:25:18.291  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:25:18.291  6780  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:25:18.291  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.291  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.291  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:25:18.291  6780  6850 I org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.292  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c028edb removed from the list
08-16 14:25:18.292  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.292  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cffbd78 removed from the list
08-16 14:25:18.292  6780  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:25:18.292  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.292  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.292  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.292  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.292  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.292  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.292  6780  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cffbd78 not in the list
08-16 14:25:18.292  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.292  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.293  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:25:18.293  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:25:18.293  6780  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:25:18.293  6780  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a913db7 removed from the list
08-16 14:25:18.293  6780  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:25:18.293  6780  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:25:18.293  6780  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:25:18.293  6780  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:25:18.293  6780  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26aafcb6 removed from the list
08-16 14:25:18.294  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 14:25:18.294  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 14:25:18.294  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 14:25:18.294  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start ope,ration: Should affect listening to advertisements only
08-16 14:25:18.294  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 14:25:18.294  6780  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 14:25:18.300  6780  8211 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: My test thread name)
08-16 14:25:18.301  6780  8211 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: My test thread name)
08-16 14:25:18.301  6780  8211 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 14:25:18.302  6780  8212 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: My test thread name)
08-16 14:25:18.302  6780  8212 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: My test thread name)
08-16 14:25:18.302  6780  8212 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 14:25:18.306  6780  6850 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 14:25:18.306  6780  6850 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 14:25:18.306  6780  6850 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 14:25:18.306  6780  6850 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 14:25:18.306  6780  6850 D com.test.thalitest.ThaliTestRunner: Total duration: 22854 ms
08-16 14:25:18.307  6780  6850 I jxcore-log: Total number of executed tests:  80
08-16 14:25:18.307  6780  6850 I jxcore-log: 
08-16 14:25:18.307  6780  6850 I jxcore-log: Number of passed tests:  80
08-16 14:25:18.307  6780  6850 I jxcore-log: 
08-16 14:25:18.307  6780  6850 I jxcore-log: Number of failed tests:  0
08-16 14:25:18.307  6780  6850 I jxcore-log: 
08-16 14:25:18.307  6780  6850 I jxcore-log: Number of ignored tests:  0
08-16 14:25:18.307  6780  6850 I jxcore-log: 
08-16 14:25:18.308  6780  6850 I jxcore-log: Total duration:  22854
08-16 14:25:18.308  6780  6850 I jxcore-log: 
08-16 14:25:18.308  6780  6850 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 14:25:18.308  6780  6850 I jxcore-log: 
08-16 14:25:18.316  6780  6780 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 14:25:18.316  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.316  6780  6850 I jxcore-log: 
08-16 14:25:18.318  8204  8204 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 14:25:18.319  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.319  6780  6850 I jxcore-log: 
08-16 14:25:18.320  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.320  6780  6850 I jxcore-log: 
08-16 14:25:18.321  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.321  6780  6850 I jxcore-log: 
08-16 14:25:18.321  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.321  6780  6850 I jxcore-log: 
08-16 14:25:18.322  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:25:18.322  6780  6850 I jxcore-log: 
08-16 14:25:18.324  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:25:18.324  6780  6850 I jxcore-log: 
08-16 14:25:18.325  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.325  6780  6850 I jxcore-log: 
08-16 14:25:18.326  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.326  6780  6850 I jxcore-log: 
08-16 14:25:18.327  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.327  6780  6850 I jxcore-log: 
08-16 14:25:18.328  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:25:18.328  6780  6850 I jxcore-log: 
,08-16 14:25:18.329  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:25:18.329  6780  6850 I jxcore-log: 
08-16 14:25:18.330  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:25:18.330  6780  6850 I jxcore-log: 
08-16 14:25:18.330  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.330  6780  6850 I jxcore-log: 
08-16 14:25:18.331  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.331  6780  6850 I jxcore-log: 
08-16 14:25:18.331  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.331  6780  6850 I jxcore-log: 
08-16 14:25:18.332  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.332  6780  6850 I jxcore-log: 
08-16 14:25:18.332  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.332  6780  6850 I jxcore-log: 
08-16 14:25:18.333  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.333  6780  6850 I jxcore-log: 
08-16 14:25:18.333  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.333  6780  6850 I jxcore-log: 
08-16 14:25:18.334  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:25:18.334  6780  6850 I jxcore-log: 
08-16 14:25:18.334  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:25:18.334  6780  6850 I jxcore-log: 
08-16 14:25:18.335  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:25:18.335  6780  6850 I jxcore-log: 
08-16 14:25:18.335  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.335  6780  6850 I jxcore-log: 
08-16 14:25:18.336  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.336  6780  6850 I jxcore-log: 
08-16 14:25:18.336  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.336  6780  6850 I jxcore-log: 
08-16 14:25:18.337  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.337  6780  6850 I jxcore-log: 
08-16 14:25:18.337  6780  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:25:18.337  6780  6850 I jxcore-log: 
08-16 14:25:18.349  8204  8204 I dhcpcd  : wlan0: leased 192.168.1.135 for 17280,0 seconds
08-16 14:25:18.349  8204  8204 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 14:25:18.349  8204  8204 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 14:25:18.349  8204  8204 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 14:25:18.349  8204  8204 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 14:25:18.349  8204  8204 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 14:25:18.349  8204  8204 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 14:25:18.349  8204  8204 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 14:25:18.544  8218  8218 D AndroidRuntime: 
08-16 14:25:18.544  8218  8218 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 14:25:18.546  8218  8218 D AndroidRuntime: CheckJNI is OFF
,08-16 14:25:18.573  7275  7339 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:25:18.573  7275  7339 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:25:18.573  7275  7339 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:25:18.573  7275  7339 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:25:18.573  7275  7339 I Adreno-EGL: Remote Branch: 
08-16 14:25:18.573  7275  7339 I Adreno-EGL: Local Patches: 
08-16 14:25:18.573  7275  7339 I Adreno-EGL: Reconstruct Branch: 
08-16 14:25:18.606  8151  8151 W ExternalStrings: load override strings
08-16 14:25:18.606  8151  8151 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:25:18.606  8151  8151 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 14:25:18.608  8151  8151 D StatusProvider: onCreate
08-16 14:25:18.611  1051  8175 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 14:25:18.613  1051  8175 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 14:25:18.614  1051  8175 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 14:25:18.614  1051  8175 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 14:25:18.614  1051  8175 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 14:25:18.614  1051  8175 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 14:25:18.614  1051  8175 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 14:25:18.614  1051  8175 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 14:25:18.615  1051  8175 D DhcpStateMachine: RunningState
08-16 14:25:18.617  7275  7339 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:25:18.617  7275  7339 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:25:18.617  7275  7339 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:25:18.617  7275  7339 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:25:18.617  7275  7339 I Adreno-EGL: Remote Branch: 
08-16 14:25:18.617  7275  7339 I Adreno-EGL: Local Patches: 
08-16 14:25:18.617  7275  7339 I Adreno-EGL: Reconstruct Branch: 
08-16 14:25:18.656  8218  8218 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 14:25:18.659  8151  8151 V Signer  : override build config not found
08-16 14:25:18.659  8151  8151 D Signer  : value of property debug is false
08-16 14:25:18.665  1051  1108 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 14:25:18.665  1051  1108 I ActivityManager: Killing 6780:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-16 14:25:18.666  7275  7339 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:25:18.666  7275  7339 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:25:18.666  7275  7339 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:25:18.666  7275  7339 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:25:18.666  7275  7339 I Adreno-EGL: Remote Branch: 
08-16 14:25:18.666  7275  7339 I Adreno-EGL: Local Patches: 
08-16 14:25:18.666  7275  7339 I Adreno-EGL: Reconstruct Branch: 
08-16 14:25:18.683  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 14:25:18.683  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 14:25:18.683  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 14:25:18.684  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 14:25:18.684  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 14:25:18.684  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 14:25:18.684  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 14:25:18.684  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 14:25:18.684  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 14:25:18.684  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 14:25:18.684  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 14:25:18.685  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 14:25:18.685  8151  8151 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-16 14:25:18.691  8151  8151 V LGMDMManager: Create singleton instance
,08-16 14:25:18.733  8151  8151 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-16 14:25:18.739  1051  2071 I WindowState: WIN DEATH: Window{314a05f1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 14:25:18.740  1051  1560 D WifiService: Client connection lost with reason: 4
08-16 14:25:18.745  1051  2071 D InputDispatcher: Window went away: Window{314a05f1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 14:25:18.790  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:18.790  8151  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 14:25:18.875  1051  1108 E libprocessgroup: failed to kill 1 processes for processgroup 6780
,08-16 14:25:18.883  1051  1108 I ActivityManager:   Force finishing activity ActivityRecord{f4a2202 u0 com.test.thalitest/.MainActivity t6}
08-16 14:25:18.919  8151  8248 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 14:25:18.934   329   351 E GBMv2   : DFP En is all cleared set to be enabled
08-16 14:25:18.935  1051  1986 W ActivityManager: Spurious death for ProcessRecord{21f1bd1b 6780:com.test.thalitest/u0a118}, curProc for 6780: null
08-16 14:25:18.936  2107  2107 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-16 14:25:18.937  2107  2107 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 14:25:18.937  1982  1999 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 14:25:18.937  1982  1999 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3068e295 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 14:25:18.938  2107  2107 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 14:25:18.938  1982  2806 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 14:25:18.938  1982  2806 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25f00faa co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 14:25:18.938  2107  2194 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-16 14:25:18.941  1945  1945 D ActionManagerService: notifyUserLog: 1000003
08-16 14:25:18.941  2107  2107 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 14:25:18.942  3838  4503 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 14:25:18.942  2107  2107 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 14:25:18.943  2107  2107 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 14:25:18.943  2107  2107 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-16 14:25:18.946  1945  1945 D ActionManagerService: notifyUserLog: 1000004
08-16 14:25:18.946  2107  2107 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 14:25:18.947  3838  4503 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 14:25:18.947  3838  3853 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 14:25:18.947  1051  1133 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-16 14:25:18.965  1619  1619 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 14:25:18.968  2516  2687 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 14:25:18.970  7673  7673 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 14:25:18.970  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 14:25:18.971  3838  3838 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-16 14:25:18.971  2054  2054 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 14:25:18.983  1051  1449 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 14:25:18.997  1051  1986 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:25:19.002  4612  4612 I art     : Explicit concurrent mark sweep GC freed 8227(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 673us total 41.343ms
08-16 14:25:19.023  4504  4504 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-16 14:25:19.027  4504  4504 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 14:25:19.027  4504  4504 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 14:25:19.027  4504  4504 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 14:25:19.027  4504  4504 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:25:19.027  4504  4504 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:25:19.027  4504  4504 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:25:19.027  4504  4504 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:25:19.027  4504  4504 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:25:19.027  4504  4504 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:25:19.027  4504  4504 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:25:19.027  4504  4504 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:25:19.028  1051  1051 D administrator: Handling package changes for user 0
08-16 14:25:19.028  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:25:19.034  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.039  1051  1107 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , expire_time: 0
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , display: false
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , animation: false }
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , expire_time: 0
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , display: false
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , animation: false }
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , expire_time: 0
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , display: false
08-16 14:25:19.049  2107  2107 I GBoardWebViewUtils: , animation: false }
,08-16 14:25:19.065  2107  8254 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-16 14:25:19.073  1619  1670 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 14:25:19.073  1619  1670 D KeyguardModel: createShortcutInfo...
08-16 14:25:19.076  1619  1670 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 14:25:19.076  1619  1670 D KeyguardModel: createShortcutInfo...
,08-16 14:25:19.082  1619  1619 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-16 14:25:19.082  2107  2107 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 14:25:19.084  1619  1670 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 14:25:19.084  1619  1670 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:25:19.084  1619  1670 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 14:25:19.085  1619  1670 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 14:25:19.089  1619  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:25:19.089  1619  1670 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 14:25:19.091  1910  1910 D SplitUIManager: split_name #11 / not available #0
08-16 14:25:19.091  1910  1910 D SplitUIService: removed split : 
08-16 14:25:19.092  1619  1670 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 14:25:19.092  1619  1670 D KeyguardModel: createShortcutInfo...
08-16 14:25:19.096  1051  1731 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:25:19.096  1051  1731 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:25:19.096  1619  1670 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 14:25:19.096  1619  1670 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:25:19.114  1619  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:25:19.115  1619  1670 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-16 14:25:19.117  1051  1986 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8260 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 14:25:19.129  1619  1670 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 14:25:19.129  1619  1670 D KeyguardModel: createShortcutInfo...
,08-16 14:25:19.149  1051  2071 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:25:19.151  7673  7673 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 14:25:19.165  1619  1670 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:25:19.166  1619  1670 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 14:25:19.166  1619  1670 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 14:25:19.166  1619  1670 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 14:25:19.172  1619  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:25:19.172  1619  1670 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 14:25:19.172  2107  2107 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 14:25:19.174  2107  2107 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 14:25:19.179  1619  1619 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 14:25:19.179  1619  1619 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 14:25:19.183  1051  2125 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:25:19.189  1910  1910 D SplitUIManager: split_name #11 / not available #0
08-16 14:25:19.189  1910  1910 I SplitUIService: split app #11
08-16 14:25:19.193  1619  1670 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 14:25:19.193  1619  1670 D KeyguardModel: createShortcutInfo...
08-16 14:25:19.202  1619  1619 D KeyguardModel: handleShortcutListChanged...
08-16 14:25:19.202  1619  1619 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 14:25:19.206  1619  1670 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 14:25:19.206  1619  1670 D KeyguardModel: createShortcutInfo...
08-16 14:25:19.206  1051  1051 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 14:25:19.206  1051  1051 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 14:25:19.207  1051  1051 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 14:25:19.208  1051  1594 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 14:25:19.211  1619  1670 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 14:25:19.211  1619  1670 D KeyguardModel: createShortcutInfo...
08-16 14:25:19.213  1619  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:25:19.213  1619  1670 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-16 14:25:19.214  1619  1670 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 14:25:19.214  1619  1670 D KeyguardModel: createShortcutInfo...
08-16 14:25:19.214   323   396 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 14:25:19.215  1619  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:25:19.215  1619  1670 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 14:25:19.216  3232  8277 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 14:25:19.216  1619  1670 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 14:25:19.216  1619  1670 D KeyguardModel: createShortcutInfo...
08-16 14:25:19.218  1619  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:25:19.218  1619  1670 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 14:25:19.219  1619  1670 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 14:25:19.219  1619  1670 D KeyguardModel: createShortcutInfo...
08-16 14:25:19.229   310  8279 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 14:25:19.230   310  8279 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-16 14:25:19.241  8260  8260 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:25:19.242  2107  2107 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-16 14:25:19.242  1619  1619 D KeyguardModel: handleShortcutListChanged...
,08-16 14:25:19.242  1619  1619 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 14:25:19.245  2107  2107 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:25:19.247  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 14:25:19.248  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 14:25:19.249  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 14:25:19.251  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-16 14:25:19.261   310  8279 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 14:25:19.267  2107  2107 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,08-16 14:25:19.268  2107  2107 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:25:19.269  2107  2274 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 14:25:19.270  2107  2274 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-16 14:25:19.283  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 14:25:19.283  2107  2107 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 14:25:19.284  2107  2107 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:25:19.291  2107  2107 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 14:25:19.294  2587  2587 D [Concierge]Service: onStartCommand(). Type : 8
08-16 14:25:19.294  1051  1116 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{150311e5 u0 com.lge.launcher2/.Launcher t5} time:232905
08-16 14:25:19.294  2587  2587 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-16 14:25:19.294  2587  2587 D [Concierge]Service: Update widget ID : 11
08-16 14:25:19.296  2107  2107 D [Concierge]WidgetView: change position of spinner
08-16 14:25:19.297  2587  2587 D [Concierge]Service: onStartCommand(). Type : 0
08-16 14:25:19.297  2107  2107 I [Concierge]WidgetView: initWebView(). Time : 1471350319297
08-16 14:25:19.302  8260  8260 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 14:25:19.302   310   909 D LGDataListener: argv[0]=dsqncommand
08-16 14:25:19.302   310   909 D LGDataListener: argv[1]=wlan0
08-16 14:25:19.302   310   909 D LGDataListener: argv[2]=1
08-16 14:25:19.302   310   909 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 14:25:19.302  1051  1113 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 14:25:19.302  1051  1113 D DSQN    : start to monitor internet connection
08-16 14:25:19.313  2107  2107 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 51647181
08-16 14:25:19.313  2107  2107 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 14:25:19.313  2107  2107 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 14:25:19.316  2107  2107 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1b63564d
08-16 14:25:19.316  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-16 14:25:19.316  2107  2107 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 14:25:19.317  2107  2107 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 14:25:19.323  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 14:25:19.323  8151  8248 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:25:19.323  8151  8248 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:25:19.323  2107  2107 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 14:25:19.323  2107  2107 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 14:25:19.324  2107  2107 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471350114712, New one : 1471350319297
08-16 14:25:19.324  2107  2107 D [Concierge]WidgetView: Unregister all receivers
08-16 14:25:19.324  2107  2107 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 14:25:19.324  2107  2107 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:25:19.326  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 14:25:19.327  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 14:25:19.328  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 14:25:19.329  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,08-16 14:25:19.330  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 14:25:19.333  2107  2107 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:25:19.333  2107  2107 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:25:19.342  8260  8260 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 14:25:19.342  8260  8260 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 14:25:19.342  8260  8260 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 14:25:19.343  8260  8260 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 14:25:19.343  8260  8260 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 14:25:19.344  8260  8260 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 14:25:19.347  8260  8260 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-16 14:25:19.356  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:19.358  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.369  2107  2107 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-16 14:25:19.377  2107  2107 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 14:25:19.377  2107  2107 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 14:25:19.378  8260  8260 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:25:19.380  8260  8260 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 14:25:19.380  2107  2107 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:25:19.382  1051  1133 I art     : Explicit concurrent mark sweep GC freed 79914(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.144ms total 326.905ms
08-16 14:25:19.383  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:19.383  8151  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:25:19.384  8260  8260 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 14:25:19.392  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:19.396  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.401  2107  2107 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@11f0a23e time:233012
08-16 14:25:19.403  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:19.403  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.404  8260  8260 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 14:25:19.406  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 14:25:19.408  6863  6863 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 14:25:19.409  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 14:25:19.409  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:25:19.409  6863  6863 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:25:19.409  6863  6863 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:25:19.409  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:25:19.409  6863  6863 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:25:19.409  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 14:25:19.409  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:25:19.409  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:25:19.409  6863  6863 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:25:19.409  6863  6863 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 14:25:19.410  6863  6863 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 14:25:19.411  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:19.412  8151  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 14:25:19.420  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:25:19.421  8151  8248 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-16 14:25:19.423  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.427  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:19.427  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.427  8260  8260 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:19.429  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:19.429  8151  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 14:25:19.433  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:25:19.437  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.441  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:19.441  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.441  8260  8260 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:19.442  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:19.443  8151  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:25:19.443  8151  8248 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-16 14:25:19.450  8151  8248 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-16 14:25:19.451  8151  8248 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 14:25:19.452  8151  8248 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 14:25:19.452  8151  8248 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 14:25:19.453  8151  8248 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 14:25:19.454  8151  8248 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 14:25:19.455  8151  8248 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-16 14:25:19.460  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:25:19.464  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 14:25:19.468  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:19.468  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.468  8260  8260 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:19.471  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:19.471  8151  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:25:19.473  8218  8218 D AndroidRuntime: Shutting down VM
08-16 14:25:19.477  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:19.480  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.493  1855  8198 I CheckinTask: Sending checkin request (7895 bytes)
,08-16 14:25:19.501  1051  1107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:25:19.506  1051  1107 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 14:25:19.507  1051  1133 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8295 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 14:25:19.513  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:19.514  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.514  8260  8260 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:19.515  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:19.516  8151  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:25:19.526  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:19.529  2107  2107 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 14:25:19.534  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.538  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:19.539  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:25:19.539  8260  8260 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:19.546  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.,
08-16 14:25:19.548  8151  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 14:25:19.556  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:25:19.557  2107  2107 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-16 14:25:19.559  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.561  1051  1731 I ActivityManager: Killing 7703:com.google.android.talk/u0a72 (adj 15): empty #17
,08-16 14:25:19.594  2107  2909 I GBoardtInterface: onReloaded()
,08-16 14:25:19.595  2107  2107 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 14:25:19.610  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:25:19.610  1051  1734 W libprocessgroup: failed to open /acct/uid_10072/pid_7703/cgroup.procs: No such file or directory
08-16 14:25:19.611  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.612  3838  4499 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 14:25:19.614  3838  3854 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 14:25:19.616  8260  8260 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:19.619  1945  1945 D ActionManagerService: notifyUserLog: 1000001
08-16 14:25:19.620  3838  4503 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 14:25:19.620  3838  4503 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 14:25:19.621  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:19.621  8151  8249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:25:19.623  1945  1945 D ActionManagerService: notifyUserLog: 1000001
,08-16 14:25:19.625  3838  4503 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 14:25:19.625  3838  4503 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 14:25:19.625  3838  4503 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 14:25:19.625  3838  4503 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 14:25:19.626  3838  4499 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 14:25:19.627  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:25:19.628  2107  2107 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 14:25:19.628  2107  2107 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 14:25:19.630  2107  2107 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 14:25:19.630  2107  2107 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 14:25:19.630  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.632  2107  2107 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 14:25:19.632  2107  2107 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 14:25:19.633  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:19.634  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.634  8260  8260 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:25:19.636  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:25:19.649  1051  1555 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:19.649  1051  1555 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:19.650  1051  1555 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:19.650  1051  1555 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:19.650  1051  1555 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:19.650  1051  1555 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:25:19.650  1051  1561 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 14:25:19.651  1051  1561 D ConnectivityService: identical MTU - not setting
08-16 14:25:19.651  1051  1561 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 14:25:19.651  1051  1561 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 14:25:19.651  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:25:19.651  1051  1561 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:25:19.651  1051  1561 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 14:25:19.652  1619  1828 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 14:25:19.656  8103  8103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 14:25:19.658  8103  8103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:19.660  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:19.664  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.671  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:25:19.672  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.672  8260  8260 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 14:25:19.673  8260  8260 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 14:25:19.673  8260  8260 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 14:25:19.677  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:19.679  8103  8103 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 14:25:19.680  8103  8103 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:25:19.681  6863  6863 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:25:19.685  6863  6863 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:25:19.689  8260  8260 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:25:19.689  8260  8260 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:25:19.690  8260  8260 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 14:25:19.690  8260  8260 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 14:25:19.690  8260  8260 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 14:25:19.693  8151  8151 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:25:19.723  1051  2028 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8316 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:25:19.731  1855  8198 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
08-16 14:25:19.737  1855  8198 I CheckinService: active receiver: disabled
,08-16 14:25:19.769  8316  8316 I art     : Almond Protected OAT
,08-16 14:25:19.803  8316  8316 D WeatherApplication: removeAccount

```
