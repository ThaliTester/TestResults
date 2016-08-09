#### Test 79689775403ec48_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-09 17:22:20.972  6986  6986 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-09 17:22:38.537  7034  7034 D AndroidRuntime: 
08-09 17:22:38.537  7034  7034 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-09 17:22:38.542  7034  7034 D AndroidRuntime: CheckJNI is OFF
08-09 17:22:38.664  7034  7034 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-09 17:22:38.669  1037  2115 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-09 17:22:38.679  1971  4351 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-09 17:22:38.683  1037  2115 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-09 17:22:38.684  1037  2115 V ActivityStackEx: create ActivityStackEx
08-09 17:22:38.697  1037  2115 D ActivityManager: setTaskToReturnTo : TaskRecord{f6f5cf8 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-09 17:22:38.697  1037  2115 D ActivityManager: setTaskToReturnTo : TaskRecord{f6f5cf8 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-09 17:22:38.699  1037  2115 D WindowStateEx: AppWindowTokenEx init.. 
08-09 17:22:38.700   333   360 E GBMv2   : DFP En is all cleared set to be enabled
08-09 17:22:38.712  1561  1561 D QuickStatusbarLayout: Notification difference=198
08-09 17:22:38.712  1561  1561 D QuickStatusbarLayout: child = android.widget.LinearLayout{1c9d0735 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
08-09 17:22:38.725  1561  1561 D LgeAbsQuickCoverView: mCoverXPos: 0 ,mCoverYPos: 0
08-09 17:22:38.725  1561  1561 D LgeAbsQuickCoverView: mCoverWidth: 0 ,mCoverHeight: 0
08-09 17:22:38.746  1037  2115 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7054 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-09 17:22:38.754  7034  7034 D AndroidRuntime: Shutting down VM
08-09 17:22:38.787  1971  1987 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-09 17:22:38.788  1971  1987 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d4f973d co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
08-09 17:22:38.789  1971  4351 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-09 17:22:38.789  1971  4351 D SplitWindowPolicy: topRunningActivity=ActivityInfo{31262b32 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
08-09 17:22:38.821  7054  7054 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-09 17:22:38.935  7054  7054 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-09 17:22:38.944  7054  7054 I LibraryLoader: Loading: webviewchromium
,08-09 17:22:38.946  7054  7054 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6694-6698)
08-09 17:22:38.947  7054  7054 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 17:22:38.974  7054  7054 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4e5c62d}
08-09 17:22:38.975  7054  7054 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 17:22:38.975  7054  7054 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 17:22:38.985  7054  7054 I BrowserStartupController: Initializing chromium process, renderers=0
08-09 17:22:38.986  7054  7054 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 17:22:38.997  7054  7054 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-09 17:22:38.997  7054  7054 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-09 17:22:38.998  7054  7054 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-09 17:22:39.002   316  1383 V AudioPolicyService: registerClient() client 0xb1025e20, uid 10118
08-09 17:22:39.006  1037  1098 D BluetoothManagerService: Message: 20
08-09 17:22:39.006  1037  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b28d1c2:true
08-09 17:22:39.016  7054  7054 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 17:22:39.016  7054  7054 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 17:22:39.016  7054  7054 I Adreno-EGL: Build Date: 12/12/14 금
08-09 17:22:39.016  7054  7054 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 17:22:39.016  7054  7054 I Adreno-EGL: Remote Branch: 
08-09 17:22:39.016  7054  7054 I Adreno-EGL: Local Patches: 
08-09 17:22:39.016  7054  7054 I Adreno-EGL: Reconstruct Branch: 
,08-09 17:22:39.097  7054  7084 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-09 17:22:39.104  7054  7054 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-09 17:22:39.120  7054  7054 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 17:22:39.124  7054  7054 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-09 17:22:39.127  7054  7054 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-09 17:22:39.130  7054  7054 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-09 17:22:39.130  7054  7054 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-09 17:22:39.143  7054  7054 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-09 17:22:39.149  7054  7054 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 17:22:39.149  7054  7054 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 17:22:39.180  7054  7096 D OpenGLRenderer: Render dirty regions requested: true
08-09 17:22:39.180  7054  7096 I OpenGLRenderer: Initialized EGL, version 1.4
08-09 17:22:39.184  7054  7096 D OpenGLRenderer: Enabling debug mode 0
08-09 17:22:39.191  7054  7054 D Atlas   : Validating map...
,08-09 17:22:39.195  1037  1053 D SplitWindow: check instance of lgWin Window{2e5a006c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-09 17:22:39.242  7054  7094 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:22:39.242  7054  7094 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:22:39.340  1037  1099 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +556ms (total +640ms)
08-09 17:22:39.341  1037  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{208e55d1 u0 com.test.thalitest/.MainActivity t2} time:327093
,08-09 17:22:39.353  7054  7054 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@361e86e0 time:327105
,08-09 17:22:39.458  7054  7054 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-09 17:22:39.493  7054  7054 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-09 17:22:39.493  7054  7054 I chromium: 
,08-09 17:22:39.629  7054  7107 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,08-09 17:22:39.646  7054  7107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 17:22:39.646  7054  7107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 17:22:39.646  7054  7107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 17:22:39.646  7054  7107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 17:22:39.646  7054  7107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-09 17:22:39.646  7054  7107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d6e95a4 added. We now have 1 listener(s)
08-09 17:22:39.652  1037  2267 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 17:22:39.655  7054  7107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-09 17:22:39.659  7054  7107 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 17:22:39.660  7054  7107 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 17:22:39.661  7054  7107 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-09 17:22:39.669  7054  7107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2c64d3 added. We now have 1 listener(s)
08-09 17:22:39.669  7054  7107 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 17:22:39.674  1037  1547 D WifiService: New client listening to asynchronous messages
08-09 17:22:39.678  7054  7107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 17:22:39.678  7054  7107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-09 17:22:39.680  7054  7107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-09 17:22:39.680  7054  7107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-09 17:22:39.680  7054  7107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-09 17:22:39.684  7054  7107 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 17:22:39.689  1037  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:22:39.690  7054  7107 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-09 17:22:39.705  7054  7107 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-09 17:22:39.706  7054  7107 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:22:39.706  7054  7107 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:22:39.706  7054  7107 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:22:39.706  7054  7107 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:22:39.706  7054  7107 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:22:39.706  7054  7107 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:22:39.706  7054  7107 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:22:39.706  7054  7107 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:22:39.706  7054  7107 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-09 17:22:39.706  7054  7107 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 17:22:39.711  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:22:39.714  7054  7107 I io.jxcore.node.LifeCycleMonitor: start: OK
08-09 17:22:39.714  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:22:39.762  7054  7094 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-09 17:22:39.762  7054  7094 I chromium: 
,08-09 17:22:39.822  7054  7054 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 17:22:40.051   333   362 E GBMv2   : DFP En is all cleared set to be enabled
08-09 17:22:40.051   333   362 E GBMv2   : Set value is all cleared set the max
08-09 17:22:40.051   333   362 I GBMv2   : DFP Enabled. Ignore VFP set
,08-09 17:22:40.722  7054  7110 W jxcore-log: Initializing JXcore engine
08-09 17:22:40.722  7054  7110 W jxcore-log: JXcore engine is ready
,08-09 17:22:40.759  7110  7110 W Thread-837: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9513]" dev="sockfs" ino=9513 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-09 17:22:40.759  7110  7110 W Thread-837: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-09 17:22:40.759  7110  7110 W Thread-837: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8586]" dev="sockfs" ino=8586 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-09 17:22:40.759  7110  7110 W Thread-837: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-09 17:22:40.759  7110  7110 W Thread-837: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33096]" dev="sockfs" ino=33096 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-09 17:22:40.783  7054  7110 W jxcore-log: Starting JXcore engine
,08-09 17:22:40.865  7054  7110 W jxcore-log: Platform android
08-09 17:22:40.865  7054  7110 W jxcore-log: 
08-09 17:22:40.865  7054  7110 W jxcore-log: Process ARCH arm
08-09 17:22:40.865  7054  7110 W jxcore-log: 
,08-09 17:22:41.087  7054  7110 I jxcore-log: JXcore Cordova bridge is ready!
08-09 17:22:41.087  7054  7110 I jxcore-log: 
08-09 17:22:41.087  7054  7110 W jxcore-log: JXcore engine is started
,08-09 17:22:41.091  7054  7107 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-09 17:22:41.097  7054  7054 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-09 17:22:46.738  1037  3472 I LocationManagerService: remove d392cba
08-09 17:22:46.739  1037  3472 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-09 17:22:46.739  1037  3472 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 17:22:46.740  1037  3472 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-09 17:22:46.741  1037  3472 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-09 17:22:46.742  1037  3472 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-09 17:22:57.088  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-09 17:22:57.088  7054  7110 I jxcore-log: 
,08-09 17:22:57.091  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-09 17:22:57.091  7054  7110 I jxcore-log: 
,08-09 17:22:57.097  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:22:57.097  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:22:57.097  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:22:57.097  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:22:57.097  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:22:57.097  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:22:57.097  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:22:57.097  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:22:57.099  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:22:57.102  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-09 17:22:57.102  7054  7110 I jxcore-log: 
08-09 17:22:57.104  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-09 17:22:57.104  7054  7110 I jxcore-log: 
,08-09 17:22:57.443  7054  7110 I jxcore-log: Running unit tests
08-09 17:22:57.443  7054  7110 I jxcore-log: 
08-09 17:22:57.444  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 17:22:57.444  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80a4d5d added. We now have 2 listener(s)
,08-09 17:22:57.444  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 17:22:57.449  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 17:22:57.449  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 17:22:57.449  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 17:22:57.449  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:22:57.449  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e376d2 added. We now have 2 listener(s)
08-09 17:22:57.449  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:22:57.449  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 17:22:57.452  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:22:57.454  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:22:57.454  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:22:57.454  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:22:57.454  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:22:57.454  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:22:57.454  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:22:57.454  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:22:57.454  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:22:57.455  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:22:57.455  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 17:22:57.456  7054  7110 D ExecuteNativeTests: Running unit tests
,08-09 17:22:57.461  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:22:57.463  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:22:57.543  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 17:22:57.543  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 added. We now have 3 listener(s)
,08-09 17:22:57.544  1037  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:22:57.546  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 17:22:57.546  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 17:22:57.546  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 17:22:57.546  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:22:57.546  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 added. We now have 3 listener(s)
08-09 17:22:57.546  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:22:57.546  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 17:22:57.550  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:22:57.555  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:22:57.555  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:22:57.555  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:22:57.555  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:22:57.555  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:22:57.555  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:22:57.555  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:22:57.555  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:22:57.556  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:22:57.557  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 17:22:57.560  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:22:57.561  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:22:57.563  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 17:22:57.565  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 17:22:57.565  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 17:22:57.565  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 17:22:57.569  7054  7110 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-09 17:22:57.570  7054  7110 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 17:22:57.570  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 17:22:57.570  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 17:22:57.570  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 17:22:57.570  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-09 17:22:57.571  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:22:57.575  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:22:57.576  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:22:57.576  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:22:57.576  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:22:57.577  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:22:57.578  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 17:22:57.578  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 removed from the list
08-09 17:22:57.578  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:22:57.578  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 removed from the list
08-09 17:22:57.578  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:22:57.578  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:22:57.579  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:22:57.579  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:22:57.580  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:22:57.580  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:22:57.580  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:22:57.580  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:22:57.582  7054  7110 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-09 17:22:57.583  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 17:22:57.583  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:22:57.583  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:22:57.583  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:22:57.583  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:22:57.583  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:22:57.583  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
,08-09 17:22:57.583  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-09 17:22:57.583  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:22:57.583  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:22:57.583  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:22:57.583  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:22:57.584  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 17:22:57.584  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:22:57.585  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:22:57.585  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:22:57.585  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:22:57.585  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-09 17:22:57.593  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 17:22:57.594  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-09 17:22:57.594  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:22:57.594  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:22:57.594  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:22:57.595  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:22:57.595  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:22:57.595  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:22:57.595  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:22:57.596  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 17:22:57.596  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:22:57.596  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:22:57.596  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:22:57.596  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:22:57.596  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:22:57.596  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:22:57.598  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:22:57.598  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:22:57.598  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:22:57.598  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:22:57.600  7054  7110 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-09 17:22:57.603  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:22:57.606  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:22:57.606  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:22:57.606  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:22:57.606  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:22:57.606  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:22:57.606  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:22:57.606  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:22:57.606  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:22:57.608  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:22:57.609  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 17:22:57.609  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 17:22:57.609  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 17:22:57.609  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 17:22:57.609  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:22:57.609  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 17:22:57.612  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:22:57.614  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:22:57.617  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 17:22:57.617  1037  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:22:57.623  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-09 17:22:57.631  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 17:22:57.634  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-09 17:22:57.636  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-09 17:22:57.636  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:22:57.640  7054  7110 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 17:22:57.641  7054  7110 I io.jxcore.node.ConnectionHelper: start: OK
08-09 17:23:00.054  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-09 17:23:00.054  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
08-09 17:23:00.055  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-09 17:23:00.055  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,08-09 17:23:00.067  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
08-09 17:23:00.067  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-09 17:23:00.070  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-09 17:23:00.071  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,08-09 17:23:02.652  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:02.652  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:02.652  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 17:23:02.660  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:02.660  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:02.660  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:23:02.660  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:02.660  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:02.661  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:02.661  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:02.661  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:02.982  1037  1407 D PowerManagerServiceEx: acquireWakeLockInternal: lock=533154631, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-09 17:23:03.033  2650  2650 D [Concierge]Service: onStartCommand(). Type : 9
,08-09 17:23:03.065  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=533154631 [*alarm*], flags=0x0
,08-09 17:23:07.662  7054  7110 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-09 17:23:07.675  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:23:07.682  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:23:07.682  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:07.682  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:07.682  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:07.682  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:07.682  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:07.682  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:23:07.682  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 17:23:07.686  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:07.686  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 17:23:07.688  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:07.690  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:07.690  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 17:23:07.690  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 17:23:07.690  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 17:23:07.690  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:23:07.690  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 17:23:07.696  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-09 17:23:07.699  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:23:07.701  7054  7110 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 17:23:07.701  7054  7110 I io.jxcore.node.ConnectionHelper: start: OK
08-09 17:23:07.703  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:07.703  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:07.704  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:07.704  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:07.704  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:07.704  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:23:07.704  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:07.704  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:07.704  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:07.704  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:07.704  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:07.705  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:07.705  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:07.706  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:07.706  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:07.708  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:07.708  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:07.709  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:07.709  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:07.710  7054  7110 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-09 17:23:07.716  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:23:07.720  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:23:07.720  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:07.720  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:07.720  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-09 17:23:07.720  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:07.720  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:07.720  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:23:07.720  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:23:07.722  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 17:23:07.722  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 17:23:07.724  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:23:07.730  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:07.730  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 17:23:07.730  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 17:23:07.730  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 17:23:07.730  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:23:07.730  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 17:23:07.736  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-09 17:23:07.739  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:23:07.740  7054  7110 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 17:23:07.741  7054  7110 I io.jxcore.node.ConnectionHelper: start: OK
08-09 17:23:12.741  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:12.741  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:12.741  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 17:23:17.751  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.751  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.751  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 17:23:17.758  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.760  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.760  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:23:17.760  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.760  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.760  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.761  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.761  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.761  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.761  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.762  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.762  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.764  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:17.764  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.764  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.764  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.765  7054  7110 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-09 17:23:17.765  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.765  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.765  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:17.766  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.766  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.766  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.766  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.766  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.766  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.766  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.766  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.766  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.766  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.766  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:23:17.771  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.771  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.772  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:17.772  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.772  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.772  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.774  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 17:23:17.774  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.774  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.774  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:17.774  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.775  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.775  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.775  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.775  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.775  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.775  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.775  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.775  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.775  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.775  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.776  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.776  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.777  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:17.777  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.777  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.777  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.778  7054  7110 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-09 17:23:17.779  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.779  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.779  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:17.779  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.779  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.779  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.779  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.779  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.779  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.779  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.780  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.780  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.780  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.780  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:23:17.786  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.786  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.787  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:17.787  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.787  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.787  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.788  7054  7110 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-09 17:23:17.788  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.788  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.788  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:17.789  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.789  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.789  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.789  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.789  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.789  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.789  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.789  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.789  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.789  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.789  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.790  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.790  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.791  7054  7110 D BluetoothLeScanner: could not find callback wrapper
,08-09 17:23:17.791  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.791  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.791  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.792  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-09 17:23:17.795  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 17:23:17.795  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-09 17:23:17.795  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 17:23:17.795  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-09 17:23:17.801  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 17:23:17.802  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 17:23:17.802  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 17:23:17.802  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 17:23:17.802  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.803  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.803  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:17.803  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.803  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.803  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.803  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.803  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.803  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.803  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.803  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.804  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.804  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.804  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.806  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.806  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.810  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:17.810  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.810  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.810  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
,08-09 17:23:17.816  7054  7110 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 17:23:17.817  7054  7110 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 17:23:17.817  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 17:23:17.822  7054  7110 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 17:23:17.822  7054  7110 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 17:23:17.823  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 17:23:17.82,3  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-09 17:23:17.824  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 17:23:17.824  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 17:23:17.824  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 17:23:17.824  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 17:23:17.824  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 17:23:17.824  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 17:23:17.824  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 17:23:17.824  7054  7110 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-09 17:23:17.824  7054  7110 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 17:23:17.824  7054  7110 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-09 17:23:17.824  7054  7110 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 17:23:17.824  7054  7110 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 17:23:17.825  7054  7110 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-09 17:23:17.825  7054  7110 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 17:23:17.825  7054  7110 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 17:23:17.825  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-09 17:23:17.833  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-09 17:23:17.834  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-09 17:23:17.834  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-09 17:23:17.835  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-09 17:23:17.835  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-09 17:23:17.835  7054  7110 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-09 17:23:17.836  7054  7110 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 17:23:17.836  7054  7110 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-09 17:23:17.836  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.836  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.836  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:17.838  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.838  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.838  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.838  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-09 17:23:17.839  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.839  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.839  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.839  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.839  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.839  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.839  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.839  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:23:17.843  7054  7119 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 901)
08-09 17:23:17.849  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.849  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.851  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:17.851  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.851  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 17:23:17.852  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.855  7054  7110 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-09 17:23:17.855  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.855  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.855  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:17.856  7054  7120 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 901
08-09 17:23:17.856  7054  7120 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 901)
08-09 17:23:17.856  7054  7120 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 901)
08-09 17:23:17.856  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.856  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.856  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.857  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.857  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.857  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.857  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.857  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.857  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.857  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.857  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.858  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.858  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.859  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:17.859  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.859  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.859  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.860  7054  7110 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-09 17:23:17.861  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.861  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, dis,covery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.861  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:17.865  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.865  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.865  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.865  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.865  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.865  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.865  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.865  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.865  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.865  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.865  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:23:17.871  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.871  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.872  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:17.872  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.872  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.872  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.873  7054  7110 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-09 17:23:17.873  7054  7110 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-09 17:23:17.873  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 17:23:17.873  7054  7110 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-09 17:23:17.873  7054  7110 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 17:23:17.874  7054  7110 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-09 17:23:17.874  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 17:23:17.874  7054  7110 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-09 17:23:17.874  7054  7110 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 17:23:17.874  7054  7110 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 17:23:17.874  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 17:23:17.874  7054  7110 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-09 17:23:17.874  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:17.874  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:17.874  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:17.878  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.878  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.878  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.878  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.878  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.878  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the lis,t
08-09 17:23:17.878  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.878  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.878  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.879  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.879  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:23:17.883  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:17.883  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:17.884  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:17.884  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:17.884  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.884  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.885  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:17.885  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.885  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.885  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:17.885  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:17.885  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:17.885  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:17.885  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:17.885  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:17.952  7054  7119 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-09 17:23:17.954  7054  7119 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 901)
08-09 17:23:21.092  1606  1606 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-09 17:23:21.092  1606  1606 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-09 17:23:21.119  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:21.119  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 17:23:21.121  1037  1547 D WifiController: battery changed pluggedType: 2
08-09 17:23:21.123  1606  1606 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
08-09 17:23:21.123  1606  1606 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-09 17:23:21.125  1971  2146 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-09 17:23:21.125  1971  2146 D LEDHandler: Battery Level Remaining: 100%
08-09 17:23:21.125  1971  2146 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
08-09 17:23:21.127  4219  4323 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-09 17:23:21.127  1606  1606 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-09 17:23:21.133  6986  6986 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-09 17:23:22.887  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.887  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.887  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:22.887  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.887  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.887  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:22.888  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:22.888  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:22.888  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 17:23:22.897  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:22.897  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.898  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.898  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:22.898  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.900  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.900  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:22.900  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.900  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.900  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.900  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.902  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:22.902  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:22.904  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:22.904  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:22.904  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.904  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.906  7054  7110 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-09 17:23:22.907  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 17:23:22.910  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-09 17:23:22.911  7054  7110 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-09 17:23:22.911  7054  7110 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-09 17:23:22.912  7054  7054 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-09 17:23:22.912  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-09 17:23:22.913  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 17:23:22.914  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:22.914  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-09 17:23:22.914  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-09 17:23:22.914  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-09 17:23:22.914  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.914  7054  7110 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-09 17:23:22.916  7054  7138 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-09 17:23:22.916  7054  7138 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-09 17:23:22.918  7054  7054 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-09 17:23:22.920  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:22.920  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.920  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 17:23:22.921  7054  7110 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 17:23:22.921  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 17:23:22.923  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-09 17:23:22.924  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:23:22.924  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:23:22.924  7054  7110 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-09 17:23:22.924  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.924  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.925  7054  7110 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 17:23:22.926  7054  7054 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 17:23:22.926  7054  7054 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-09 17:23:22.926  7054  7054 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 17:23:22.926  7054  7054 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 17:23:22.927  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.927  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:22.927  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:22.927  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 17:23:22.927  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:22.927  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.927  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.927  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:22.927  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.927  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.927  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:22.928  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 17:23:22.928  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.928  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.928  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.929  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:22.929  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:22.929  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-09 17:23:22.929  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.930  7054  7110 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-09 17:23:22.932  7054  7110 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 17:23:22.932  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-09 17:23:22.939  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 17:23:22.939  7054  7110 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 17:23:22.940  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:22.941  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:22.941  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:22.941  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:22.941  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.941  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.941  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:22.942  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.942  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.942  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:22.943  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.943  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.943  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.944  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:23:22.949  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:22.949  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:22.949  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.949  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.952  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:22.953  1037  2115 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:22.953  1037  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:22.955  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:22.955  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:22.955  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 17:23:22.957  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:22.957  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.957  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.957  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:22.957  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.957  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.958  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:22.958  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.958  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.958  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.959  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.959  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:22.959  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:22.959  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.960  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.961  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:23:22.961  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:23:22.961  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:23:22.961  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:23:22.961  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.961  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.961  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344077d0 not in the list
08-09 17:23:22.962  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.962  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.962  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:22.962  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.962  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.962  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager:, release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.962  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.963  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:23:22.963  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:23:22.963  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.963  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed493c9 not in the list
08-09 17:23:22.965  7054  7110 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-09 17:23:22.965  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 17:23:22.965  7054  7110 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-09 17:23:22.965  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 17:23:22.965  7054  7110 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-09 17:23:22.965  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 17:23:22.967  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 17:23:22.967  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-09 17:23:22.969  7054  7110 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-09 17:23:22.969  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 17:23:22.969  7054  7110 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-09 17:23:22.969  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-09 17:23:22.969  7054  7110 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-09 17:23:22.969  7054  7110 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-09 17:23:22.970  7054  7110 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-09 17:23:22.970  7054  7110 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-09 17:23:22.971  7054  7110 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-09 17:23:22.971  7054  7110 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-09 17:23:22.971  7054  7110 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-09 17:23:22.971  7054  7110 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-09 17:23:22.973  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:23:22.973  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e18f5a6 added. We now have 3 listener(s)
08-09 17:23:22.973  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 17:23:22.982  7054  7110 D BluetoothAdapter: enable(): BT is already enabled..!
08-09 17:23:22.984  1037  2005 D WifiServiceImplEx: setWifiEnabled: true pid=7054, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 17:23:22.985  1037  2005 D WifiService: setWifiEnabled: true pid=7054, uid=10118
08-09 17:23:22.985  1037  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 17:23:22.987  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:23:22.987  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fdd5be7 added. We now have 4 listener(s)
08-09 17:23:22.987  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 17:23:22.994  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.994  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fdd5be7 removed from the list
08-09 17:23:22.994  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:22.994  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.994  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.995  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:23:22.995  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1eeab394 added. We now have 4 listener(s)
08-09 17:23:22.995  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:23:22.996  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:22.997  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1eeab394 removed from the list
08-09 17:23:22.997  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:22.997  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:22.997  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:22.997  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:23:22.997  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@251dbe3d added. We now have 4 listener(s)
08-09 17:23:22.997  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:23:23.000  1037  2005 D WifiServiceImplEx: setWifiEnabled: false pid=7054, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 17:23:23.001  1037  2005 D WifiService: setWifiEnabled: false pid=7054, uid=10118
08-09 17:23:23.001  1037  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 17:23:23.012  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 17:23:23.013  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 17:23:23.013  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-09 17:23:23.014  1037  1541 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:23.015  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:23.015  1037  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:23.015  1037  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:23.015  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:23.016  1037  1541 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-09 17:23:23.016  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 17:23:23.016  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-09 17:23:23.019  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 17:23:23.019  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-09 17:23:23.022  1037  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:23.022  1037  1969 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1a0be62a mBinding = false
08-09 17:23:23.027  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 17:23:23.027  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 17:23:23.027  2643  2643 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-09 17:23:23.027  1037  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.028  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.028  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 17:23:23.028  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
,08-09 17:23:23.033  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 17:23:23.034  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 17:23:23.034  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-09 17:23:23.034  1037  1098 D BluetoothManagerService: Message: 2
08-09 17:23:23.035  1037  1098 D BluetoothManagerService: Sending off request.
08-09 17:23:23.036  4219  4244 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-09 17:23:23.037  4219  4306 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-09 17:23:23.037  4219  4306 D BluetoothAdapterProperties: Setting state to 13
08-09 17:23:23.037  4219  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-09 17:23:23.037  4219  4306 D BluetoothAdapterProperties: onBluetoothDisable()
08-09 17:23:23.038  4219  4306 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-09 17:23:23.045  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
,08-09 17:23:23.052  1037  2795 D DhcpStateMachine: RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.059   311   896 D CommandListener: Clearing all IP addresses on wlan0
,08-09 17:23:23.063  4219  4312 D BluetoothAdapterProperties: Scan Mode:20
08-09 17:23:23.065  4219  4306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-09 17:23:23.067  4219  4632 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 17:23:23.068  4219  4672 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 17:23:23.068  4219  4667 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 17:23:23.069  4219  4631 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-09 17:23:23.069  4219  4631 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 17:23:23.069  4219  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-09 17:23:23.069  4219  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-09 17:23:23.069  4219  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-09 17:23:23.069  4219  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-09 17:23:23.069  4219  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-09 17:23:23.069  4219  4631 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-09 17:23:23.070  4219  4669 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 17:23:23.070  4219  4306 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-09 17:23:23.071  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-09 17:23:23.071  4219  4416 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-09 17:23:23.075  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:23.075  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:23.075  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:23.077  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:23.078  4219  4416 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 17:23:23.078  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:23.078  4219  4416 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 17:23:23.078  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:23.078  4219  4416 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 17:23:23.078  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-09 17:23:23.078  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-09 17:23:23.078  4219  4416 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-09 17:23:23.081  1037  1098 D BluetoothManagerService: Message: 60
08-09 17:23:23.081  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-09 17:23:23.081  1037  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-09 17:23:23.081  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:23:23.086  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.086  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:23:23.086  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:23.086  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:23.086  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:23.086  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:23.086  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:23.086  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:23:23.086  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 17:23:23.089  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.089  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:23.089  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 17:23:23.091  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:23.093  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:23.095  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.095  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:23.095  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:23.095  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:23.095  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:23.095  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:23.095  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:23.095  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:23:23.095  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:23:23.108  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-09 17:23:23.109  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-09 17:23:23.109  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 17:23:23.109  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:23.111  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.111  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:23.111  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:23.111  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:23.111  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:23.111  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:23.111  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:23.111  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:23.111  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:23:23.112  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.112  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:23.113  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.113  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:23.113  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:23.113  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:23.113  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:23.113  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:23.113  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:23.113  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:23.113  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:23:23.114  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.114  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:23.116  1037  1969 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-09 17:23:23.116  1037  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.116  1037  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.116  1037  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-09 17:23:23.116  1037  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.116  1037  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http,://clients3.google.com/generate_204 on <unknown ssid>
08-09 17:23:23.128  1037  1094 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7155 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-09 17:23:23.130  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-09 17:23:23.130  1971  1971 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:23.134  4219  4219 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:23.134  4219  4219 D BluetoothMapService: STATE_TURNING_OFF
08-09 17:23:23.134  4219  4219 V BluetoothMapService: Handler(): got msg=4
08-09 17:23:23.134  4219  4219 D BluetoothMapService: MAP Service closeService in
08-09 17:23:23.134  4219  4219 D BluetoothMapMasInstance: MAP Service shutdown
08-09 17:23:23.134  4219  4219 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 17:23:23.135  4219  4219 V BluetoothMapService: MAP Service closeService out
08-09 17:23:23.135  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.135  4219  4219 V BtOppService: Receiver DISABLED_ACTION 
08-09 17:23:23.135  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:23.135  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:23.135  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:23.135  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:23.135  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:23.135  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:23.135  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:23.135  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:23:23.135  4219  4219 I BtOppRfcommListener: stopping Accept Thread
08-09 17:23:23.135  4219  4219 V BtOppRfcommListener: close mBtServerSocket
08-09 17:23:23.135  4219  4219 V BtOppRfcommListener: waiting for thread to terminate
08-09 17:23:23.136  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.136  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:23.136  4219  4667 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-09 17:23:23.136  4219  4219 V BtOppRfcommListener: done waiting for thread to terminate
08-09 17:23:23.137  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:23.138  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:23.173  1037  1094 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7178 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-09 17:23:23.189  1037  1548 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-09 17:23:23.190  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-09 17:23:23.190  1037  1548 D DSQN    : disableDataServiceNotify
,08-09 17:23:23.190  1037  1548 D DSQN    : stop dsqn bin
08-09 17:23:23.191  4219  4219 V BtOppService: onDestroy
08-09 17:23:23.191   311  7195 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-09 17:23:23.191  1037  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-09 17:23:23.192  1037  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-09 17:23:23.194  1971  1971 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-09 17:23:23.195   337   337 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 386us total 24.001ms
08-09 17:23:23.195  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:23.195  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:23.195  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 17:23:23.197  1037  1548 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-09 17:23:23.197  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:23.197  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:23.197  4219  4219 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-09 17:23:23.197  1037  1548 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:23.198  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-09 17:23:23.198  1037  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.198  1037  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.199  1606  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-09 17:23:23.199  1037  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-09 17:23:23.199  1037  1548 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-09 17:23:23.199  1037  1548 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-09 17:23:23.199  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 17:23:23.203  1037  1540 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.203  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.203  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD,_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:23.203  1037  1540 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@38d64293
08-09 17:23:23.203  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:23.203  1037  1540 D LGWifiP2pService: P2pDisablingState
08-09 17:23:23.203  1037  1540 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.203  1037  1540 D LGWifiP2pService: p2p socket connection lost
08-09 17:23:23.203  1037  1540 D LGWifiP2pService: P2pDisabledState
08-09 17:23:23.204  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:23.204  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:23.204  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:23.204  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 17:23:23.204  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:23.204  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:23.205  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:23.205  1037  1548 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:23.205  1037  1548 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:23.206  1037  1541 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-09 17:23:23.206  1037  1548 D NetworkManagementService: Removing idletimer
08-09 17:23:23.206  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:23.206  1880  1880 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:23.206  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 17:23:23.206  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:23.207  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:23.207  1037  1548 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:23.207  1037  1548 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-09 17:23:23.208  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-09 17:23:23.209  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-09 17:23:23.210  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.210  1037  1540 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.210  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 17:23:23.210  2643  2643 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-09 17:23:23.210  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 17:23:23.211  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 17:23:23.211  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-09 17:23:23.211   311   896 D CommandListener: Clearing all IP addresses on wlan0
08-09 17:23:23.213   337   337 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 2.071ms total 17.519ms
08-09 17:23:23.214  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:23.214  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:23.214  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 17:23:23.214  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-09 17:23:23.214  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-09 17:23:23.214  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-09 17:23:23.214  1971  1971 D WfdsService: WifiP2pState is changed : false
08-09 17:23:23.214  1037  1559 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.215  1037  1560 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.215  1971  2295 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-09 17:23:23.215  1971  2295 D WfdsService: Set the WFDS Monitor: false
08-09 17:23:23.216  1037  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-09 17:23:23.216  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-09 17:23:23.216  1037  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-09 17:23:23.216  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-09 17:23:23.216  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 17:23:23.216  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 17:23:23.216  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 17:23:23.216  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 17:23:23.216  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 17:23:23.216  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 17:23:23.217  1037  1541 D WifiNative-p2p0: doBoolean: TERMINATE
08-09 17:23:23.218  1037  1541 D WifiNative-p2p0: TERMINATE: returned true
08-09 17:23:23.218  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 17:23:23.218  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-09 17:23:23.218  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 17:23:23.219  1037  1541 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:23.219  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:23.222  1971  2295 D WfdsMonitor: WFDS Monitor is stopped
08-09 17:23:23.222  1971  2295 D WfdsService: STATE : WfdsDisabledState - enter
08-09 17:23:23.222  1971  2716 D CtrlSupplicant: Received on exit socket, terminate
08-09 17:23:23.222  1971  2716 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-09 17:23:23.222  1971  2716 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-09 17:23:23.222  1971  2716 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-09 17:23:23.223  1971  2295 W WfdsService: DefaultState - msg [9445378] is not handled
08-09 17:23:23.223  1971  2296 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-09 17:23:23.225  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:23.225  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:23.226  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:23.227   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 14.451ms
08-09 17:23:23.228  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-09 17:23:23.229  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:23.229  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:23.229  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-09 17:23:23.235  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.235  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:23.235  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:23.235  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:23.235  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:23.235  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:23.235  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:23.235  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:23.235  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:23.236  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-09 17:23:23.236  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.236  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:23.238  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-09 17:23:23.239  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.239  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:23.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:23.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:23.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:23.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:23.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:23.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:23.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:23.239  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:23.239  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-09 17:23:23.239  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.239  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:23.241  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.241  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:23.241  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:23.241  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:23.241  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:23.241  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:23.241  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:23.241  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:23.241  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:23.241  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:23.242  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:23.252  7178  7178 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 17:23:23.252  7178  7178 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-09 17:23:23.252  7178  7178 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 17:23:23.252  7178  7178 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-09 17:23:23.253  7178  7178 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-09 17:23:23.254  7178  7178 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-09 17:23:23.254  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:23.254  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:23.255  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:23.267  1037  2795 D DhcpStateMachine: StoppedState
08-09 17:23:23.267  1037  2795 D DhcpStateMachine: StoppedState{ when=-56ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:23.268  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-09 17:23:23.269  1037  1541 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-09 17:23:23.269  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 17:23:23.270  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:23.271  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:23.282  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 17:23:23.282  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:23.283  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:23.283  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-09 17:23:23.283  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-09 17:23:23.284  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:23.285  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:23.294  7155  7155 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-09 17:23:23.295  7155  7155 W LG Account v2.2: No ProfileInfo entries
08-09 17:23:23.295  7155  7155 I LG Account v2.2: isEnabled: false
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]Country: EU
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]Operator: OPEN
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]Ranking support: false
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]Comfort support: false
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]Accessory: true
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]Health device: true
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]Extra Pedometer: false
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]Blood glucose device: false
08-09 17:23:23.295  7155  7155 I Feature : [Lifetracker]Device Number: 3
08-09 17:23:23.301  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 17:23:23.309  2643  2643 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-09 17:23:23.309  2643  2643 I wpa_supplicant: monitor socket send errors count : 1
08-09 17:23:23.309  2643  2643 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1971-2\x00 that cannot receive messages
08-09 17:23:23.310  1037  2697 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-09 17:23:23.310  1037  2697 D WifiMonitor: Dropping event because (p2p0) is stopped
08-09 17:23:23.331  1037  2091 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7202 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-09 17:23:23.332  1037  2091 I ActivityManager: Killing 6503:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-09 17:23:23.347  2643  2643 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-09 17:23:23.347  1037  2697 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-09 17:23:23.347  1037  2697 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 17:23:23.347  1037  2697 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 17:23:23.347  1037  2697 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-09 17:23:23.348  2643  2643 W wpa_supplicant: USIM:  scard_deinit function
08-09 17:23:23.348  1037  1541 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=371088
08-09 17:23:23.348  1037  2697 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:23.348  1037  2697 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:23.349  1037  1541 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=371088
,08-09 17:23:23.349  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=371089  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-09 17:23:23.349  1037  1541 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=371089  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-09 17:23:23.350  1037  1098 D Tethering: InitialState.processMessage what=4
08-09 17:23:23.382  1037  1052 W libprocessgroup: failed to open /acct/uid_10005/pid_6503/cgroup.procs: No such file or directory
,08-09 17:23:23.390  1037  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-09 17:23:23.391  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:23.391  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-09 17:23:23.427  7054  7054 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 17:23:23.456  7202  7202 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-09 17:23:23.456  7178  7178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-09 17:23:23.459  7202  7202 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 17:23:23.460  4219  4219 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 17:23:23.460  4219  4219 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:23.460  4219  4219 V BluetoothPbapReceiver: ***********state = 13
08-09 17:23:23.461  4219  4219 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-09 17:23:23.462  4219  4219 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:23.462  4219  4219 V BluetoothPbapService: state: 13
08-09 17:23:23.462  4219  4219 V BluetoothPbapService: Pbap Service closeService in
08-09 17:23:23.463  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:23.463  1037  1098 D BluetoothManagerService: Message: 20
08-09 17:23:23.463  1037  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@313a7fcd:true
08-09 17:23:23.465  4219  4219 V BluetoothPbapService: successfully stopped pbap service
08-09 17:23:23.465  4219  4219 V BluetoothPbapService: Pbap Service closeService out
08-09 17:23:23.465  4219  4219 V BluetoothPbapService: Pbap Service onDestroy
08-09 17:23:23.465  4219  4219 V BluetoothPbapService: Pbap Service closeService in
08-09 17:23:23.465  4219  4219 V BluetoothPbapService: Pbap Service closeService out
08-09 17:23:23.465  4219  4219 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-09 17:23:23.465  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 17:23:23.467  1037  2115 I ActivityManager: Killing 6035:com.google.android.talk/u0a72 (adj 15): empty #17
08-09 17:23:23.469  2643  2643 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-09 17:23:23.472  1037  2697 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-09 17:23:23.472  1037  2697 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
,08-09 17:23:23.472  1037  2697 D WifiMonitor: Disconnecting from the supplicant, no more events
08-09 17:23:23.473  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-09 17:23:23.556  1037  2028 W libprocessgroup: failed to open /acct/uid_10072/pid_6035/cgroup.procs: No such file or directory
,08-09 17:23:23.582  1037  1098 D BluetoothManagerService: Message: 30
,08-09 17:23:23.583  1037  1541 D WifiOffDelayIfNotUsed: stopMonitoring
08-09 17:23:23.583  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 17:23:23.583  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-09 17:23:23.583  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 17:23:23.584  1971  1971 D WfdsService: Supplicant Connection state is changed : false
08-09 17:23:23.584  1971  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-09 17:23:23.584  1971  2295 D WfdsService: Set the WFDS Monitor: false
08-09 17:23:23.584  1971  2295 D WfdsMonitor: WFDS Monitor is stopped
08-09 17:23:23.588  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:23.588  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-09 17:23:23.591  2470  2470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:23.593  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:23.595  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:23.596  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:23.597  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-09 17:23:23.597  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
,08-09 17:23:23.598  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-09 17:23:23.604  1037  1098 D BluetoothManagerService: Message: 30
08-09 17:23:23.608  7178  7178 D LocalBluetoothProfileManager: Adding local MAP profile
08-09 17:23:23.610  7178  7178 D BluetoothMap: Create BluetoothMap proxy object
08-09 17:23:23.611  1037  1098 D BluetoothManagerService: Message: 30
,08-09 17:23:23.618  1037  1098 D BluetoothManagerService: Message: 30
08-09 17:23:23.620  7178  7178 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-09 17:23:23.622  7178  7178 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-09 17:23:23.645  7178  7178 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-09 17:23:23.650  7178  7178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-09 17:23:23.669  7178  7178 D DockEventReceiver: finishStartingService: stopping service
,08-09 17:23:23.694  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:23.746  7178  7178 D LgDataFeature: LgDataFeature() Constructor: none
,08-09 17:23:23.746  7178  7178 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:23:23.759  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 17:23:23.775  7178  7178 D BluetoothInputDevice: Proxy object connected
,08-09 17:23:23.777  7178  7178 D HidProfile: Bluetooth service connected
,08-09 17:23:23.779  7178  7178 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 17:23:23.781  7178  7178 D PanProfile: Bluetooth service connected
08-09 17:23:23.782  7178  7178 D BluetoothMap: Proxy object connected
08-09 17:23:23.784  7178  7178 D MapProfile: Bluetooth service connected
08-09 17:23:23.784  7178  7178 D BluetoothMap: getConnectedDevices()
08-09 17:23:23.785  7178  7178 D BluetoothMap: Bluetooth is Not enabled
08-09 17:23:23.786  7178  7178 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-09 17:23:23.790  7178  7178 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-09 17:23:23.798  7178  7178 D BluetoothPermissionRequest: onReceive
08-09 17:23:23.802  7178  7178 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-09 17:23:23.816  1037  2115 I ActivityManager: Killing 6521:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-09 17:23:23.819  7178  7178 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-09 17:23:23.882  4219  4219 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-09 17:23:23.882  4219  4219 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-09 17:23:23.884  1037  2051 W libprocessgroup: failed to open /acct/uid_10004/pid_6521/cgroup.procs: No such file or directory
,08-09 17:23:23.887  4219  4219 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-09 17:23:23.961  1037  2115 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7237 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-09 17:23:23.973  4219  4219 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:23.973  4219  4219 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-09 17:23:23.975  4219  4219 V BluetoothFtpService: Ftp Service onStartCommand
08-09 17:23:23.975  4219  4219 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:23.975  4219  4219 V BluetoothFtpService: Ftp Service closeService
08-09 17:23:23.976  4219  4219 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-09 17:23:23.977  4219  4219 V BluetoothFtpService: successfully stopped ftp service
08-09 17:23:23.978  4219  4219 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 17:23:23.978  4219  4219 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-09 17:23:23.978  4219  4219 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 17:23:23.978  4219  4219 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:23.978  4219  4219 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-09 17:23:23.978  4219  4219 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-09 17:23:23.979  4219  4219 V BluetoothFtpService: Ftp Service onDestroy
08-09 17:23:23.980  4219  4219 V BluetoothFtpService: Ftp Service closeService
08-09 17:23:23.981  4219  4219 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:23.981  4219  4219 V BluetoothSapService: state: 13
08-09 17:23:23.981  4219  4219 V BluetoothSapService: Stopping SAP server process
08-09 17:23:23.983  4219  4219 V BluetoothSapService: Sap Service closeSapService in
08-09 17:23:23.983  4219  4219 V BluetoothSapService: Close listen Socket : 
08-09 17:23:23.983  4219  4219 V BluetoothSapService: Close rfcomm Socket : 
08-09 17:23:23.983  4219  4219 V BluetoothSapService: Close sapd  Socket : 
08-09 17:23:24.034  1037  2267 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7254 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-09 17:23:24.039  4219  4219 V BluetoothSapService: Sap Service closeSapService out
08-09 17:23:24.040  4219  4219 V BluetoothSapService: Sap Service onDestroy
08-09 17:23:24.040  4219  4219 V BluetoothSapService: Sap Service closeSapService in
08-09 17:23:24.040  4219  4219 V BluetoothSapService: Close listen Socket : 
08-09 17:23:24.040  4219  4219 V BluetoothSapService: Close rfcomm Socket : 
08-09 17:23:24.040  4219  4219 V BluetoothSapService: Close sapd  Socket : 
08-09 17:23:24.043  4219  4219 V BluetoothSapService: Sap Service closeSapService out
08-09 17:23:24.074  7237  7237 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 17:23:24.075  4219  4312 D bt_hci_bdroid: cleanup
08-09 17:23:24.075  4219  4603 I bt_userial_mct: exiting userial_read_thread
08-09 17:23:24.075  4219  4603 D bt_userial_mct: Leaving userial_evt_read_thread()
08-09 17:23:24.075  4219  4420 I bt_lpm  : LPM is already off!!!
,08-09 17:23:24.076  4219  4416 W bt-btif : ag scb idx 1 not allocated
08-09 17:23:24.076  4219  4416 E bt-btif : BTA AG is already disabled, ignoring ...
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:24.076  4219  4416 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 17:23:24.076  4219  4416 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-09 17:23:24.076  4219  4312 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-09 17:23:24.076  4219  4420 I bt_vendor: hw_epilog_process
08-09 17:23:24.077  4219  4312 D bt_hci_bdroid: cleanup Finalizing cleanup
08-09 17:23:24.077  4219  4312 D bt_userial_mct: userial_close
08-09 17:23:24.077  4219  4312 E bt_userial_mct: pthread_join() FAILED result:3
08-09 17:23:24.077  4219  4312 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-09 17:23:24.122  7254  7254 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 17:23:24.238  4219  4312 D bt_hci_bdroid: set_power 0
,08-09 17:23:24.239  4219  4312 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-09 17:23:24.239  4219  4312 I bt_vendor: bluetooth satus is on
08-09 17:23:24.239  4219  4312 I bt_vendor: bt-vendor : resetting BT status
08-09 17:23:24.239  4219  4312 I bt_vendor: Starting hciattach daemon
08-09 17:23:24.239  4219  4312 I bt_vendor: try to set false
08-09 17:23:24.240  4219  4312 I bt_vendor: Starting hciattach daemon
08-09 17:23:24.240  4219  4312 I bt_vendor: try to set false
08-09 17:23:24.241  4219  4312 I bt_vendor: cleanup
08-09 17:23:24.242  4219  4416 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-09 17:23:24.267  1037  1933 I art     : Explicit concurrent mark sweep GC freed 43718(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.920ms total 158.555ms
08-09 17:23:24.269  4219  4312 I GKI_LINUX: GKI_exit_task 0 done
08-09 17:23:24.269  4219  4312 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-09 17:23:24.270  4219  4306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-09 17:23:24.274  1037  1780 I ActivityManager: Killing 6813:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-09 17:23:24.378  1037  2115 W libprocessgroup: failed to open /acct/uid_10008/pid_6813/cgroup.procs: No such file or directory
,08-09 17:23:24.379  4219  4219 D HeadsetService: Received stop request...Stopping profile...
,08-09 17:23:24.389  4219  4219 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-09 17:23:24.389  4219  4219 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 17:23:24.390  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c054762
08-09 17:23:24.390  4219  4323 D HeadsetStateMachine: Exit Disconnected: -1
08-09 17:23:24.392  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-09 17:23:24.392  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-09 17:23:24.392  7237  7237 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-09 17:23:24.392  1880  1880 D BluetoothHeadset: Proxy object disconnected
08-09 17:23:24.393  1880  1880 D BluetoothHeadset: Proxy object disconnected
08-09 17:23:24.396  1880  1880 D BluetoothHeadset: Proxy object disconnected
,08-09 17:23:24.399  4219  4219 D A2dpService: Received stop request...Stopping profile...
08-09 17:23:24.399  4219  4390 D A2dpStateMachine: Exit Disconnected: -1
08-09 17:23:24.401  4219  4219 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-09 17:23:24.404  4219  4219 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-09 17:23:24.404  4219  4219 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 17:23:24.404  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c054762
08-09 17:23:24.404  4219  4306 D BluetoothAdapterState: Stopping profile services that were post enabled
08-09 17:23:24.406  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-09 17:23:24.406  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-09 17:23:24.408  4219  4219 D HidService: Received stop request...Stopping profile...
08-09 17:23:24.408  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c054762
,08-09 17:23:24.413  7178  7178 D BluetoothInputDevice: Proxy object disconnected
08-09 17:23:24.413  4219  4219 D HeadsetStateMachine: Unbinding service...
08-09 17:23:24.413  7178  7178 D HidProfile: Bluetooth service disconnected
08-09 17:23:24.414  4219  4219 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 17:23:24.414  4219  4219 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 17:23:24.414  4219  4219 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 17:23:24.414  4219  4219 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 17:23:24.415  4219  4219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-09 17:23:24.415  4219  4219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 17:23:24.415  4219  4219 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-09 17:23:24.415  4219  4219 D HealthService: Received stop request...Stopping profile...
08-09 17:23:24.416  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c054762
08-09 17:23:24.417  4219  4219 D PanService: Received stop request...Stopping profile...
08-09 17:23:24.418  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c054762
08-09 17:23:24.419  7178  7178 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 17:23:24.419  7178  7178 D PanProfile: Bluetooth service disconnected
08-09 17:23:24.419  4219  4219 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 17:23:24.419  4219  4219 D BtGatt.GattService: Received stop request...Stopping profile...
08-09 17:23:24.420  4219  4219 D BtGatt.GattService: stop()
08-09 17:23:24.420  4219  4219 D BtGatt.AdvertiseManager: advertise clients cleared
08-09 17:23:24.421  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c054762
08-09 17:23:24.422  4219  4219 D BluetoothMapService: Received stop request...Stopping profile...
08-09 17:23:24.422  4219  4219 D BluetoothMapService: stop()
08-09 17:23:24.423  4219  4219 D BluetoothMapEmailAppObserver: deinitObservers()
08-09 17:23:24.423  4219  4219 D BluetoothMapEmailAppObserver: removeReceiver()
08-09 17:23:24.424  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c054762
,08-09 17:23:24.425  4219  4219 I BluetoothA2dpServiceJni: cleanupNative
08-09 17:23:24.425  4219  4392 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-09 17:23:24.426  4219  4219 I GKI_LINUX: GKI_exit_task 2 done
08-09 17:23:24.426  4219  4219 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-09 17:23:24.426  4219  4219 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 17:23:24.426  4219  4219 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-09 17:23:24.426  4219  4219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 17:23:24.426  4219  4219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 17:23:24.427  4219  4219 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 17:23:24.427  4219  4219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-09 17:23:24.427  4219  4219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 17:23:24.428  7178  7178 D BluetoothMap: Proxy object disconnected
08-09 17:23:24.428  7178  7178 D MapProfile: Bluetooth service disconnected
08-09 17:23:24.429  4219  4219 V BluetoothMapService: Handler(): got msg=4
08-09 17:23:24.429  4219  4219 D BluetoothMapService: MAP Service closeService in
08-09 17:23:24.429  4219  4219 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 17:23:24.429  4219  4219 V BluetoothMapService: MAP Service closeService out
08-09 17:23:24.429  4219  4219 D BluetoothMapService: cleanup()
08-09 17:23:24.429  4219  4219 D BluetoothMapService: MAP Service closeService in
08-09 17:23:24.429  4219  4219 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 17:23:24.429  4219  4219 V BluetoothMapService: MAP Service closeService out
08-09 17:23:24.429  4219  4306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-09 17:23:24.430  4219  4306 D BluetoothAdapterProperties: Setting state to 10
08-09 17:23:24.430  4219  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-09 17:23:24.430  1037  1098 D BluetoothManagerService: Message: 60
08-09 17:23:24.431  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-09 17:23:24.431  1037  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-09 17:23:24.431  1880  4326 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 17:23:24.431  4219  4306 I BluetoothAdapterState: Entering OffState
08-09 17:23:24.432  7178  7196 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 17:23:24.433  1037  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 17:23:24.433  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 17:23:24.434  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 17:23:24.437  1037  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 17:23:24.438  7178  7197 D BluetoothPan: onBluetoothStateChange on: false
,08-09 17:23:24.439  7178  7196 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 17:23:24.440  7178  7197 D BluetoothMap: onBluetoothStateChange: up=false
,08-09 17:23:24.441  1037  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-09 17:23:24.441  1037  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-09 17:23:24.443  1037  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-09 17:23:24.443  1037  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-09 17:23:24.443  1037  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1a0be62a mBinding = false
08-09 17:23:24.444  1037  1098 D BluetoothManagerService: Sending unbind request.
08-09 17:23:24.446  1037  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-09 17:23:24.447  1971  1971 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:24.447  1971  2177 D LGBluetoothAPIService: Message: 2
,08-09 17:23:24.448  1971  2177 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2915d083 mBinding = false
08-09 17:23:24.448  1971  2177 D LGBluetoothAPIService: Sending unbind request.
08-09 17:23:24.449  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 17:23:24.455  1606  1606 D BluetoothAdapter: 329289052: getState() :  mService = null. Returning STATE_OFF
08-09 17:23:24.455  1606  1606 D BluetoothAdapter: 329289052: getState() :  mService = null. Returning STATE_OFF
08-09 17:23:24.456  4219  4312 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-09 17:23:24.457  4219  4219 I GKI_LINUX: GKI_exit_task 1 done
08-09 17:23:24.457  4219  4219 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-09 17:23:24.457  4219  4219 I BluetoothServiceJni: cleanupNative: return from cleanup
08-09 17:23:24.457  4219  4219 I art     : --- WEIRD: removing null entry 246
08-09 17:23:24.457  4219  4219 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-09 17:23:24.457  4219  4219 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-09 17:23:24.460  7178  7178 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-09 17:23:24.461  7178  7178 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-09 17:23:24.461  7178  7178 D LGBluetoothEventManager: [BTUI] clear device connection state
08-09 17:23:24.462  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:24.462  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:24.463  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:24.467  4219  4219 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-09 17:23:24.469  7178  7178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-09 17:23:24.474  4219  4219 I art     : System.exit called, status: 0
08-09 17:23:24.474  4219  4219 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-09 17:23:24.481  7178  7178 D DockEventReceiver: finishStartingService: stopping service
08-09 17:23:24.495  7237  7237 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-09 17:23:24.495  7237  7237 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-09 17:23:24.496   316  1384 V AudioFlinger: 4219 died, releasing its sessions
08-09 17:23:24.496   316  1384 V AudioFlinger:  pid 1880 @ 0
08-09 17:23:24.496   316  1384 V AudioFlinger:  pid 3307 @ 1
08-09 17:23:24.496   316  1384 V AudioFlinger:  pid 3307 @ 2
,08-09 17:23:24.497  7178  7178 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-09 17:23:24.499  7237  7237 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-09 17:23:24.499  7237  7237 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-09 17:23:24.499  7237  7237 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-09 17:23:24.501  7237  7237 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-09 17:23:24.506  7237  7237 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-09 17:23:24.608  1037  2052 I ActivityManager: Process com.android.bluetooth (pid 4219) has died
08-09 17:23:24.609  1037  2052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-09 17:23:24.623  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 17:23:24.633  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 17:23:24.640  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 17:23:24.643  7178  7178 D BluetoothPermissionRequest: onReceive
08-09 17:23:24.646  7178  7178 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-09 17:23:24.647  7178  7178 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-09 17:23:24.652  7178  7178 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 17:23:24.708  1037  2091 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7288 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-09 17:23:24.712  7237  7237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 17:23:24.715  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:24.716  7237  7237 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-09 17:23:24.719  7237  7237 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-09 17:23:24.722  7202  7202 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-09 17:23:24.722  7202  7202 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 17:23:24.722  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 17:23:24.726  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 17:23:24.733  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:24.745  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:24.745  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 17:23:24.749  7237  7237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-09 17:23:24.752  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:24.755  7202  7202 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-09 17:23:24.755  7202  7202 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 17:23:24.755  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:24.758  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:24.764  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:24.770  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 17:23:24.771  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:24.773  7237  7237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 17:23:24.836  1037  1653 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7306 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-09 17:23:24.843  1037  1407 V AlarmManager: ELAPSED_WAKEUP set : Alarm{b3e84d7 type 2 when 372560 com.google.android.gms} when 372560
08-09 17:23:24.862  7288  7288 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-09 17:23:24.863  7288  7288 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 17:23:24.863  7288  7288 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-09 17:23:24.864  7288  7288 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-09 17:23:24.885  7288  7288 D BluetoothAdapterApp: Loading JNI Library
,08-09 17:23:24.922  7288  7288 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@aa6cd7b Instance Count = 1
08-09 17:23:24.929  7288  7288 D BluetoothAdapterApp: onCreate
,08-09 17:23:24.957  7288  7288 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-09 17:23:24.957  7288  7288 D ProfileConfigQcom: Adding HeadsetService
08-09 17:23:24.957  7288  7288 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-09 17:23:24.957  7288  7288 D ProfileConfigQcom: Adding A2dpService
08-09 17:23:24.958  7288  7288 D ProfileConfigQcom: [BTUI] HidService is supported
08-09 17:23:24.958  7288  7288 D ProfileConfigQcom: Adding HidService
08-09 17:23:24.958  7288  7288 D ProfileConfigQcom: [BTUI] HealthService is supported
08-09 17:23:24.958  7288  7288 D ProfileConfigQcom: Adding HealthService
08-09 17:23:24.959  7288  7288 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-09 17:23:24.959  7288  7288 D ProfileConfigQcom: [BTUI] PanService is supported
08-09 17:23:24.960  7288  7288 D ProfileConfigQcom: Adding PanService
08-09 17:23:24.960  7288  7288 D ProfileConfigQcom: [BTUI] GattService is supported
08-09 17:23:24.960  7288  7288 D ProfileConfigQcom: Adding GattService
08-09 17:23:24.960  7288  7288 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-09 17:23:24.960  7288  7288 D ProfileConfigQcom: Adding BluetoothMapService
08-09 17:23:24.961  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:24.961  7288  7288 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-09 17:23:24.963  7288  7288 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-09 17:23:24.967  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 17:23:24.972  7288  7288 V LGMDMManagerInternal: Create singleton instance
08-09 17:23:24.975  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:24.975  7178  7178 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-09 17:23:24.990  7306  7326 W FormManager: Network not available. Please check & try again.
,08-09 17:23:25.003  7306  7327 V FormManager: Network unavailable.
08-09 17:23:25.003  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 17:23:25.004  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 17:23:25.004  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 17:23:25.004  7178  7178 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 17:23:25.005  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-09 17:23:25.008  7306  7327 V FormManager: Network unavailable.
,08-09 17:23:25.018  7178  7178 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 17:23:25.019  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-09 17:23:25.019  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 17:23:25.019  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 17:23:25.019  7178  7178 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 17:23:25.019  7178  7178 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 17:23:25.025  1037  1578 I ActivityManager: Killing 6595:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-09 17:23:25.028  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 17:23:25.029  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 17:23:25.031  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:25.159  1037  2091 W libprocessgroup: failed to open /acct/uid_10011/pid_6595/cgroup.procs: No such file or directory
,08-09 17:23:25.166  7288  7288 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:25.166  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:25.173  7288  7288 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 17:23:25.173  7288  7288 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 17:23:25.173  7288  7288 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 17:23:25.175  7288  7288 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:25.175  7288  7288 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-09 17:23:25.187  4700  7330 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-09 17:23:25.189  4700  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 17:23:25.190  4700  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-09 17:23:25.197  7254  7254 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-09 17:23:25.206  7202  7202 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-09 17:23:25.206  7202  7202 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-09 17:23:25.206  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:25.213  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 17:23:25.215  7306  7335 W FormManager: Network not available. Please check & try again.
,08-09 17:23:25.221  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:25.227  7306  7336 V FormManager: Network unavailable.
08-09 17:23:25.237  7306  7336 V FormManager: Network unavailable.
,08-09 17:23:25.243  1037  2052 I ActivityManager: Killing 6619:com.android.contacts/u0a19 (adj 15): empty #17
08-09 17:23:25.244  7237  7237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-09 17:23:25.249  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-09 17:23:25.250  7237  7237 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-09 17:23:25.294  7237  7237 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:23:25.295  7237  7237 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:23:25.303  7237  7237 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-09 17:23:25.304  7237  7237 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-09 17:23:25.305  7237  7237 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-09 17:23:25.305  7237  7237 V SoundPool: doLoad: loading sample sampleID=1
08-09 17:23:25.305  7237  7237 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-09 17:23:25.312  7237  7339 V SoundPool: Start decode
08-09 17:23:25.312  7237  7339 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-09 17:23:25.313   316  1384 V MediaPlayerService: decode(22, 10857164, 17813)
08-09 17:23:25.313   316  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-09 17:23:25.313   316  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-09 17:23:25.313   316  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-09 17:23:25.313   316  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
,08-09 17:23:25.313   316  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-09 17:23:25.313   316  1384 V MediaPlayerService: player type = 3
,08-09 17:23:25.313   316  1384 V AwesomePlayer: AwesomePlayer create()
08-09 17:23:25.314   316  1384 V AwesomePlayer: reset_l() 
08-09 17:23:25.314   316  1384 V AwesomePlayer: cancelPlayerEvents
08-09 17:23:25.315   316  1384 V AwesomePlayer: setAudioSink() 
08-09 17:23:25.315   316  1384 V AwesomePlayer: reset_l() 
08-09 17:23:25.315   316  1384 V AudioCache: notify(0xb1010240, 8, 0, 0)
08-09 17:23:25.315   316  1384 V AudioCache: ignored
08-09 17:23:25.315   316  1384 V AwesomePlayer: cancelPlayerEvents
,08-09 17:23:25.315   316  1384 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-09 17:23:25.315   316  1384 V AwesomePlayer: setDataSource_l dataSource
08-09 17:23:25.316   316  1384 V LGParserOSAL: SniffLGParser start
08-09 17:23:25.316   316  1384 V LGParserOSAL: MainType:5, SubType=0
08-09 17:23:25.316   316  1384 V LGParserOSAL: #### check Mime : application/ogg
08-09 17:23:25.316   316  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-09 17:23:25.316   316  1384 E MediaExtractor: Use LGExtractor :application/ogg 
08-09 17:23:25.331  1037  2115 W libprocessgroup: failed to open /acct/uid_10019/pid_6619/cgroup.procs: No such file or directory
,08-09 17:23:25.340  6897  6897 D UEI.SmartControl: QS Service created
08-09 17:23:25.342  7237  7237 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-09 17:23:25.344  7237  7237 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-09 17:23:25.344  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-09 17:23:25.356  6897  6897 I UEI.SmartControl: Service initServices...
,08-09 17:23:25.356  6897  6897 D UEI.SmartControl: QS start get config
,08-09 17:23:25.370  7237  7237 V LGMDMManager: Create singleton instance
,08-09 17:23:25.382   316  1384 V LGParserOSAL: supported mime: application/ogg
,08-09 17:23:25.383   316  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-09 17:23:25.383   316  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,08-09 17:23:25.383   316  1384 V AwesomePlayer: mBitrate = -1 bits/sec
08-09 17:23:25.383   316  1384 V AwesomePlayer: AudioTrack Setting
08-09 17:23:25.383   316  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-09 17:23:25.383   316  1384 V AwesomePlayer: setAudioSource() 
08-09 17:23:25.383   316  1384 V MediaPlayerService: prepare
08-09 17:23:25.383   316  1384 V AwesomePlayer: prepareAsync_l() 
08-09 17:23:25.383   316  1384 V MediaPlayerService: wait for prepare
,08-09 17:23:25.385   316  7340 V AwesomePlayer: onPrepareAsyncEvent() 
,08-09 17:23:25.385   316  7340 V AwesomePlayer: initAudioDecoder() 
08-09 17:23:25.385   316  7340 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-09 17:23:25.385   316  7340 V AudioSystem: isOffloadSupported()
08-09 17:23:25.385   316  7340 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-09 17:23:25.385   316  7340 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-09 17:23:25.385   316  7340 I AudioFlinger: isAudioPlaybackHookOn() false
08-09 17:23:25.385   316  7340 V AwesomePlayer: getUseOffload() = 0 
08-09 17:23:25.385   316  7340 V OMXCodec: OMXCodec::Create
08-09 17:23:25.385   316  7340 V OMXCodec: findMatchingCodecs()
08-09 17:23:25.385   316  7340 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-09 17:23:25.386   316  7340 V OMXCodec: matchingCodecs.size()=1
08-09 17:23:25.386   316  7340 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-09 17:23:25.390   316  7340 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-09 17:23:25.390   316  7340 V LGCodecAdapter: LG Codec Adapter start
08-09 17:23:25.390   316  7340 V OMXCodec: OMXCodec Createtor
08-09 17:23:25.390   316  7340 V OMXCodec: setComponentRole
08-09 17:23:25.390   316  7340 V OMXCodec: configureCodec protected=0
08-09 17:23:25.390   316  7340 V LGCodecAdapter: called getLGCodecSpecificData
08-09 17:23:25.390   316  7340 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-09 17:23:25.391   316  7340 V LGCodecOSAL: Called LGconfigureCodecMETA
08-09 17:23:25.391   316  7340 V LGCodecOSAL: Called LGconfigureCodecMSG
08-09 17:23:25.391   316  7340 V LGCodecOSAL: Not support LGCodec
08-09 17:23:25.391   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-09 17:23:25.391   316  7340 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-09 17:23:25.391   316  7340 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-09 17:23:25.391   316  7340 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-09 17:23:25.391   316  7340 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-09 17:23:25.391   316  7340 V AudioSystem: isOffloadSupported()
08-09 17:23:25.391   316  7340 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-09 17:23:25.392   316  7340 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-09 17:23:25.392   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-09 17:23:25.392   316  7340 V OMXCodec: init()
08-09 17:23:25.392   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-09 17:23:25.392   316  7340 V OMXCodec: allocateBuffers
08-09 17:23:25.392   316  7340 V OMXCodec: allocateBuffersOnPort portIndex=0
08-09 17:23:25.392   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-09 17:23:25.392   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
,08-09 17:23:25.393   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-09 17:23:25.393   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-09 17:23:25.393   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
08-09 17:23:25.393   316  7340 V OMXCodec: allocateBuffersOnPort portIndex=1
08-09 17:23:25.393   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-09 17:23:25.393   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-09 17:23:25.393   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-09 17:23:25.393   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd060 on output port
08-09 17:23:25.394   316  7340 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd150 on output port
,08-09 17:23:25.394   316  7340 V OMXCodec: init() mAsyncCompletion wait!!! 
08-09 17:23:25.394   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-09 17:23:25.394   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-09 17:23:25.394   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-09 17:23:25.394   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-09 17:23:25.394   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-09 17:23:25.394   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-09 17:23:25.394   316  7340 V OMXCodec: init() mAsyncCompletion wait free! 
08-09 17:23:25.394   316  7340 V AwesomePlayer: finishAsyncPrepare_l() 
08-09 17:23:25.394   316  7340 V AudioCache: notify(0xb1010240, 5, 0, 0)
08-09 17:23:25.394   316  7340 V AudioCache: ignored
08-09 17:23:25.394   316  7340 V AudioCache: notify(0xb1010240, 1, 0, 0)
08-09 17:23:25.394   316  7340 V AudioCache: prepared
08-09 17:23:25.394   316  1384 V AudioCache: wait - success
08-09 17:23:25.394   316  1384 V MediaPlayerService: start
08-09 17:23:25.394   316  1384 V AwesomePlayer: play_l() 
08-09 17:23:25.394   316  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
,08-09 17:23:25.394   316  1384 V AwesomePlayer: createAudioPlayer_l
08-09 17:23:25.394   316  1384 V AwesomePlayer: seekAudioIfNecessary_l() 
08-09 17:23:25.394   316  1384 V AwesomePlayer: startAudioPlayer_l() 
08-09 17:23:25.394   316  1384 D AudioPlayer: start of Playback, useOffload 0
08-09 17:23:25.394   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-09 17:23:25.394   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-09 17:23:25.403   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-09 17:23:25.403   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-09 17:23:25.403   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-09 17:23:25.403   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-09 17:23:25.403   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-09 17:23:25.403   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-09 17:23:25.403   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-09 17:23:25.403   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790368
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790608
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-09 17:23:25.404   316  7342 V OMXCodec: allocateBuffersOnPort portIndex=1
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd060 on output port
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-09 17:23:25.404   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-09 17:23:25.405   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-09 17:23:25.405   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-09 17:23:25.405   316  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-09 17:23:25.406   316  1384 V AudioCache: notify(0xb1010240, 6, 0, 0)
08-09 17:23:25.406   316  1384 V AudioCache: ignored
08-09 17:23:25.406   316  1384 V MediaPlayerService: wait for playback complete
08-09 17:23:25.407   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.407   316  7343 V AudioCache: memcpy(0xaf104000, 0xb17ed000, 4096)
08-09 17:23:25.408   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.409   316  7343 V AudioCache: memcpy(0xaf105000, 0xb17ed000, 4096)
08-09 17:23:25.409   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.409   316  7343 V Aud,ioCache: memcpy(0xaf106000, 0xb17ed000, 4096)
08-09 17:23:25.409   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.409   316  7343 V AudioCache: memcpy(0xaf107000, 0xb17ed000, 4096)
08-09 17:23:25.410   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.410   316  7343 V AudioCache: memcpy(0xaf108000, 0xb17ed000, 4096)
08-09 17:23:25.410   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.410   316  7343 V AudioCache: memcpy(0xaf109000, 0xb17ed000, 4096)
08-09 17:23:25.411   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.411   316  7343 V AudioCache: memcpy(0xaf10a000, 0xb17ed000, 4096)
08-09 17:23:25.412   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.412   316  7343 V AudioCache: memcpy(0xaf10b000, 0xb17ed000, 4096)
08-09 17:23:25.412   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.412   316  7343 V AudioCache: memcpy(0xaf10c000, 0xb17ed000, 4096)
08-09 17:23:25.413   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.413   316  7343 V AudioCache: memcpy(0xaf10d000, 0xb17ed000, 4096)
08-09 17:23:25.413   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.413   316  7343 V AudioCache: memcpy(0xaf10e000, 0xb17ed000, 4096)
08-09 17:23:25.414   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.414   316  7343 V AudioCache: memcpy(0xaf10f000, 0xb17ed000, 4096)
08-09 17:23:25.414   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.415   316  7343 V AudioCache: memcpy(0xaf110000, 0xb17ed000, 4096)
08-09 17:23:25.415   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.415   316  7343 V AudioCache: memcpy(0xaf111000, 0xb17ed000, 4096)
08-09 17:23:25.416   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.416   316  7343 V AudioCache: memcpy(0xaf112000, 0xb17ed000, 4096)
08-09 17:23:25.416   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.416   316  7343 V AudioCache: memcpy(0xaf113000, 0xb17ed000, 4096)
08-09 17:23:25.417   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.417   316  7343 V AudioCache: memcpy(0xaf114000, 0xb17ed000, 4096)
08-09 17:23:25.417   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.417   316  7343 V AudioCache: memcpy(0xaf115000, 0xb17ed000, 4096)
08-09 17:23:25.418   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.418   316  7343 V AudioCache: memcpy(0xaf116000, 0xb17ed000, 4096)
08-09 17:23:25.419   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.419   316  7343 V AudioCache: memcpy(0xaf117000, 0xb17ed000, 4096)
08-09 17:23:25.419   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.419   316  7343 V AudioCache: memcpy(0xaf118000, 0xb17ed000, 4096)
08-09 17:23:25.420   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.420   316  7343 V AudioCache: memcpy(0xaf119000, 0xb17ed000, 4096)
08-09 17:23:25.420   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.420   316  7343 V AudioCache: memcpy(0xaf11a000, 0xb17ed000, 4096)
08-09 17:23:25.421   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.421   316  7343 V AudioCache: memcpy(0xaf11b000, 0xb17ed000, 4096)
08-09 17:23:25.421   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.421   316  7343 V AudioCache: memcpy(0xaf11c000, 0xb17ed000, 4096)
08-09 17:23:25.422   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.422   316  7343 V AudioCache: memcpy(0xaf11d000, 0xb17ed000, 4096)
08-09 17:23:25.422   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.422   316  7343 V AudioCache: memcpy(0xaf11e000, 0xb17ed000, 4096)
,08-09 17:23:25.423   316  7343 V AudioCache: write(0xb17ed000, 4096),
08-09 17:23:25.423   316  7343 V AudioCache: memcpy(0xaf11f000, 0xb17ed000, 4096)
,08-09 17:23:25.424   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.424   316  7343 V AudioCache: memcpy(0xaf120000, 0xb17ed000, 4096)
08-09 17:23:25.424   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.424   316  7343 V AudioCache: memcpy(0xaf121000, 0xb17ed000, 4096)
08-09 17:23:25.425   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.425   316  7343 V AudioCache: memcpy(0xaf122000, 0xb17ed000, 4096)
08-09 17:23:25.425   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.425   316  7343 V AudioCache: memcpy(0xaf123000, 0xb17ed000, 4096)
08-09 17:23:25.426   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.426   316  7343 V AudioCache: memcpy(0xaf124000, 0xb17ed000, 4096)
08-09 17:23:25.427   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.427   316  7343 V AudioCache: memcpy(0xaf125000, 0xb17ed000, 4096)
08-09 17:23:25.427   316  7343 V AudioCache: write(0xb17ed000, 4096)
,08-09 17:23:25.427   316  7343 V AudioCache: memcpy(0xaf126000, 0xb17ed000, 4096)
08-09 17:23:25.428   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.428   316  7343 V AudioCache: memcpy(0xaf127000, 0xb17ed000, 4096)
08-09 17:23:25.429   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.429   316  7343 V AudioCache: memcpy(0xaf128000, 0xb17ed000, 4096)
08-09 17:23:25.429   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.429   316  7343 V AudioCache: memcpy(0xaf129000, 0xb17ed000, 4096)
08-09 17:23:25.430   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.430   316  7343 V AudioCache: memcpy(0xaf12a000, 0xb17ed000, 4096)
08-09 17:23:25.430   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.430   316  7343 V AudioCache: memcpy(0xaf12b000, 0xb17ed000, 4096)
08-09 17:23:25.430   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.431   316  7343 V AudioCache: memcpy(0xaf12c000, 0xb17ed000, 4096)
08-09 17:23:25.431   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.431   316  7343 V AudioCache: memcpy(0xaf12d000, 0xb17ed000, 4096)
08-09 17:23:25.431   316  7343 V AudioCache: write(0xb17ed000, 4096)
,08-09 17:23:25.431   316  7343 V AudioCache: memcpy(0xaf12e000, 0xb17ed000, 4096)
08-09 17:23:25.432   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.432   316  7343 V AudioCache: memcpy(0xaf12f000, 0xb17ed000, 4096)
08-09 17:23:25.432   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.432   316  7343 V AudioCache: memcpy(0xaf130000, 0xb17ed000, 4096)
08-09 17:23:25.433   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.433   316  7343 V AudioCache: memcpy(0xaf131000, 0xb17ed000, 4096)
08-09 17:23:25.433   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.433   316  7343 V AudioCache: memcpy(0xaf132000, 0xb17ed000, 4096)
08-09 17:23:25.434   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.434   316  7343 V AudioCache: memcpy(0xaf133000, 0xb17ed000, 4096)
08-09 17:23:25.434   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.434   316  7343 V AudioCache: memcpy(0xaf134000, 0xb17ed000, 4096)
08-09 17:23:25.434   316  7343 V AudioCache: write(0xb17ed000, 4096)
08-09 17:23:25.435   316  7343 V AudioCache: memcpy(0xaf135000, 0xb17ed000, 4096)
08-09 17:23:25.435   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-09 17:23:25.435   316  7343 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,08-09 17:23:25.435   316  7343 V AwesomePlayer: postAudioEOS() 
08-09 17:23:25.435   316  7343 V AudioCache: write(0xb17ed000, 280)
08-09 17:23:25.435   316  7343 V AudioCache: memcpy(0xaf136000, 0xb17ed000, 280)
08-09 17:23:25.436   316  7340 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-09 17:23:25.437   316  7340 V AwesomePlayer: onStreamDone
08-09 17:23:25.437   316  7340 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-09 17:23:25.437   316  7340 V AudioCache: notify(0xb1010240, 2, 0, 0)
08-09 17:23:25.437   316  7340 V AudioCache: playback complete
08-09 17:23:25.437   316  7340 V AwesomePlayer: pause_l() 
08-09 17:23:25.437   316  7340 V AudioCache: notify(0xb1010240, 7, 0, 0)
08-09 17:23:25.437   316  7340 V AudioCache: ignored
08-09 17:23:25.437   316  7340 V AwesomePlayer: cancelPlayerEvents
08-09 17:23:25.437   316  1384 V AudioCache: wait - success
08-09 17:23:25.437   316  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-09 17:23:25.437   316  7340 D AudioPlayer: Pause Playback at 1068125
08-09 17:23:25.438   316  1384 V AwesomePlayer: reset_l() 
08-09 17:23:25.438   316  1384 V AudioCache: notify(0xb1010240, 8, 0, 0)
08-09 17:23:25.438   316  1384 V AudioCache: ignored
08-09 17:23:25.438   316  1384 V AwesomePlayer: cancelPlayerEvents
,08-09 17:23:25.438   316  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-09 17:23:25.438   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-09 17:23:25.438   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-09 17:23:25.438   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-09 17:23:25.438   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-09 17:23:25.438   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd060 on port 1
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:25.439   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-09 17:23:25.439   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-09 17:23:25.439   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-09 17:23:25.440   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-09 17:23:25.440   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-09 17:23:25.440   316  7342 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-09 17:23:25.440   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-09 17:23:25.440   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-09 17:23:25.440   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,08-09 17:23:25.441   316  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0,
08-09 17:23:25.441   316  1384 D AudioPlayer: AudioPlayer releasing audio source
08-09 17:23:25.441   316  1384 D AudioPlayer: AudioPlayer done releasing audio source
08-09 17:23:25.441   316  1384 V AwesomePlayer: reset_l() 
08-09 17:23:25.441   316  1384 V AwesomePlayer: cancelPlayerEvents
,08-09 17:23:25.441   316  1384 V AwesomePlayer: ~AwesomePlayer call
08-09 17:23:25.441   316  1384 V AwesomePlayer: reset_l() 
08-09 17:23:25.441   316  1384 V AwesomePlayer: cancelPlayerEvents
08-09 17:23:25.441  7237  7339 V SoundPool: close(31)
08-09 17:23:25.441  7237  7339 V SoundPool: pointer = 0x9fe3f000, size = 205080, sampleRate = 48000, numChannels = 2
08-09 17:23:25.456  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-09 17:23:25.459  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-09 17:23:25.460  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9443
08-09 17:23:25.466   311  7345 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-09 17:23:25.467  1037  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-09 17:23:25.639  6897  6897 I UEI.SmartControl: Supports setup maps: true
,08-09 17:23:25.641  6897  6897 D UEI.SmartControl: QS start statue = true Error code = 0
,08-09 17:23:25.641  6897  6897 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-09 17:23:25.641  6897  6897 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-09 17:23:25.641  6897  6897 I UEI.SmartControl: ### init IR Blaster...
,08-09 17:23:25.644  6897  6897 D serial_port: Configuring serial port
08-09 17:23:25.645  6897  6897 E UEI.SmartControl: UEIBLaster setting for 616
08-09 17:23:25.645  6897  6897 I UEI.SmartControl: Setting serial record hearder size = 2
08-09 17:23:25.645  6897  6897 I UEI.SmartControl: configuring settings for MAXQ616
08-09 17:23:25.645  6897  6897 I UEI.SmartControl: Get version...
08-09 17:23:25.663  6897  7346 D UEI.SmartControl: serial port data available: 21
,08-09 17:23:25.692  6897  6897 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-09 17:23:25.692  6897  6897 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-09 17:23:25.692  6897  6897 I UEI.SmartControl: QS saving settings...
08-09 17:23:25.694  6897  6897 D UEI.SmartControl: IR Blaster version: 25672567
,08-09 17:23:25.711  6897  7346 D UEI.SmartControl: serial port data available: 4
,08-09 17:23:25.743  6897  7352 I UEI.SmartControl: Device manager: loading config....
,08-09 17:23:25.745  6897  6897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-09 17:23:25.746  6897  7352 D UEI.SmartControl: ----------- loading internal config...
08-09 17:23:25.750  6897  6897 E UEI.SmartControl: Services init done
08-09 17:23:25.750  6897  6897 D UEI.SmartControl: QS Service init finished
,08-09 17:23:25.753  6897  6897 D UEI.SmartControl: QS Service version name: 2.1.91
08-09 17:23:25.753  6897  6897 D UEI.SmartControl: QS Service version code: 201091
08-09 17:23:25.754  6897  6897 D UEI.SmartControl: Service requested: Control
08-09 17:23:25.759  6897  6897 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-09 17:23:25.765  7237  7237 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-09 17:23:25.765  6897  7352 E UEI.SmartControl: Loading SETTINGS...
08-09 17:23:25.765  6897  6897 D UEI.SmartControl: Internal service binding...
08-09 17:23:25.767  6897  6913 I UEI.SmartControl: ------ IControl API: 11
08-09 17:23:25.767  6897  6913 D UEI.SmartControl: File observer start...
08-09 17:23:25.769  6897  6913 E UEI.SmartControl: IR Port is disabled: false
08-09 17:23:25.769  6897  6913 D UEI.SmartControl: Starting file observer...
08-09 17:23:25.773  6897  6913 I UEI.SmartControl: Registering callback...
08-09 17:23:25.775  6897  6914 I UEI.SmartControl: ------ IControl API: 19
,08-09 17:23:25.778  6897  6914 I UEI.SmartControl: Registering Services Ready callback...
08-09 17:23:25.779  6897  7352 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-09 17:23:25.785  6897  7351 I UEI.SmartControl: Notify AllClients services are ready: 0
08-09 17:23:25.786  7237  7252 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-09 17:23:25.786  6897  7351 D UEI.SmartControl: -----service ready thread exits
08-09 17:23:25.787  7237  7337 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-09 17:23:25.787  7237  7337 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-09 17:23:25.788  7237  7237 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-09 17:23:25.788  7237  7237 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-09 17:23:25.788  6897  6913 I UEI.SmartControl: ------ IControl API: 8
,08-09 17:23:25.791  7237  7237 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-09 17:23:25.791  7237  7237 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-09 17:23:25.791  7237  7237 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-09 17:23:25.792  7237  7237 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-09 17:23:25.793  7237  7237 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-09 17:23:25.793  7237  7237 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-09 17:23:25.795  7237  7237 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-09 17:23:25.800  7237  7237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-09 17:23:25.801  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-09 17:23:25.802  7237  7237 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-09 17:23:25.803  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-09 17:23:25.803  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-09 17:23:25.805  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-09 17:23:25.805  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-09 17:23:25.806  7237  7237 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470756205806]
08-09 17:23:25.809  7237  7237 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-09 17:23:25.812  1037  1933 I ActivityManager: Killing 6854:com.lge.email/u0a23 (adj 15): empty #17
08-09 17:23:25.840  7237  7354 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-09 17:23:25.868  1037  1780 W libprocessgroup: failed to open /acct/uid_10023/pid_6854/cgroup.procs: No such file or directory
,08-09 17:23:25.874  7237  7237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-09 17:23:25.875  7237  7237 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-09 17:23:25.875  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-09 17:23:25.876  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-09 17:23:25.876  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-09 17:23:25.876  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-09 17:23:25.877  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-09 17:23:25.887  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-09 17:23:26.207  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-09 17:23:26.224  1037  1098 D Tethering: MasterInitialState.processMessage what=3
,08-09 17:23:26.240  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:23:26.246  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:26.248  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:26.249  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:26.254  1037  1098 D Tethering: MasterInitialState.processMessage what=3
,08-09 17:23:26.258  1037  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:26.266  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:26.269  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:23:26.271  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:26.273  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 17:23:26.277  6774  7201 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-09 17:23:26.289  5818  5818 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-09 17:23:26.307  5818  5818 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-09 17:23:26.326  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:26.366  1037  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:26.402  1037  1653 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7361 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-09 17:23:26.407  1037  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:26.407  1037  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-09 17:23:26.463  7361  7361 I AppUp4:AppBoxCP: onCreate
,08-09 17:23:26.464  7361  7361 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-09 17:23:26.471  7361  7361 I AppUp4:DB:  setFingerPrint start
08-09 17:23:26.471  7361  7361 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-09 17:23:26.477  7361  7361 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-09 17:23:26.477  7361  7361 I AppUp4:DB:  SDK version = 21
08-09 17:23:26.477  7361  7361 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-09 17:23:26.479  7361  7361 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-09 17:23:26.480  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 17:23:26.480  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:26.482  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 17:23:26.482  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-09 17:23:26.487  7361  7361 I AppUp4:CustModeStarterReceiver: onReceive
08-09 17:23:26.517  7361  7361 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:23:26.517  7361  7361 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:23:26.524  7361  7361 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e5c62d
08-09 17:23:26.524  7361  7361 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 17:23:26.524  7361  7361 D AppUp4:CustFacade: isPhone : true
08-09 17:23:26.525  7361  7361 D AppUp4:CustModeStarterReceiver: begin check event
08-09 17:23:26.525  7361  7361 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-09 17:23:26.525  7361  7361 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-09 17:23:26.526  7361  7394 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-09 17:23:26.526  7361  7394 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-09 17:23:26.527  7361  7394 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-09 17:23:26.529  1037  2267 I ActivityManager: Killing 6640:com.android.gallery3d/u0a27 (adj 15): empty #17
08-09 17:23:26.644  1037  2051 W libprocessgroup: failed to open /acct/uid_10027/pid_6640/cgroup.procs: No such file or directory
08-09 17:23:26.647  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:26.648  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-09 17:23:26.655  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:26.662  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:26.674  4700  7397 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 17:23:26.685  4700  7398 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:26.686  4700  7398 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-09 17:23:26.746  1037  1915 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7402 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-09 17:23:26.811  7402  7402 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 17:23:26.812  7402  7402 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 17:23:26.814  7402  7402 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-09 17:23:26.815  7402  7402 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-09 17:23:26.909  7402  7402 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-09 17:23:26.929  7402  7402 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-09 17:23:26.987  7402  7402 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-09 17:23:27.041  7402  7402 D LgDataFeature: LgDataFeature() Constructor: none
,08-09 17:23:27.041  7402  7402 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:23:27.206  7402  7402 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-09 17:23:27.267  3307  3307 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 17:23:27.267  3307  3307 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:27.267  3307  3307 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-09 17:23:27.272  7402  7402 I HubEmail: JNI_OnLoad()
08-09 17:23:27.272  7402  7402 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-09 17:23:27.272  7402  7402 I HubEmail: registerNatives()
08-09 17:23:27.272  7402  7402 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-09 17:23:27.272  7402  7402 I HubEmail: registerNativeMethods()
08-09 17:23:27.272  7402  7402 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-09 17:23:27.272  7402  7402 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-09 17:23:27.315  1037  2091 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7431 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-09 17:23:27.324  7306  7429 V FormManager: Network unavailable.
08-09 17:23:27.324  7306  7427 W FormManager: Network not available. Please check & try again.
08-09 17:23:27.332  7402  7430 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 17:23:27.335  7306  7429 V FormManager: Network unavailable.
08-09 17:23:27.347  1037  1915 I ActivityManager: Killing 6916:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-09 17:23:27.390  1037  2267 W libprocessgroup: failed to open /acct/uid_10061/pid_6916/cgroup.procs: No such file or directory
08-09 17:23:27.462  7431  7431 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:23:27.463  7431  7431 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:23:27.466  7431  7431 D PhoneMonitor: Register our PhoneStateListener
,08-09 17:23:27.483  7431  7431 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-09 17:23:27.485  7431  7431 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-09 17:23:27.524  7431  7431 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-09 17:23:27.524  7431  7431 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-09 17:23:27.525  7431  7431 D TelephonyAutoProfiling: [parse] Load xml
08-09 17:23:27.528  7431  7431 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-09 17:23:27.528  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-09 17:23:27.528  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-09 17:23:27.528  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-09 17:23:27.528  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-09 17:23:27.528  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-09 17:23:27.528  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-09 17:23:27.528  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-09 17:23:27.529  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-09 17:23:27.529  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-09 17:23:27.529  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-09 17:23:27.529  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-09 17:23:27.529  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-09 17:23:27.529  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-09 17:23:27.529  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-09 17:23:27.529  7431  7431 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-09 17:23:27.529  7431  7431 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-09 17:23:27.542  1037  1933 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7451 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-09 17:23:27.544  1037  1933 I ActivityManager: Killing 6717:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-09 17:23:27.547  7431  7431 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-09 17:23:27.584  1037  1052 W libprocessgroup: failed to open /acct/uid_10080/pid_6717/cgroup.procs: No such file or directory
,08-09 17:23:27.805  1037  1933 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7469 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-09 17:23:27.806  1037  1933 I ActivityManager: Killing 6747:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-09 17:23:27.849  1037  2052 W libprocessgroup: failed to open /acct/uid_10097/pid_6747/cgroup.procs: No such file or directory
,08-09 17:23:27.979  1037  1653 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7486 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-09 17:23:27.986  1037  1653 I ActivityManager: Killing 6969:com.lge.eula/1000 (adj 15): empty #17
08-09 17:23:28.010   337   337 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 34.728ms
,08-09 17:23:28.033   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 666us total 21.345ms
,08-09 17:23:28.057   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 21.394ms
,08-09 17:23:28.077  1037  1933 W libprocessgroup: failed to open /acct/uid_1000/pid_6969/cgroup.procs: No such file or directory
,08-09 17:23:28.100  1037  2005 D WifiServiceImplEx: setWifiEnabled: true pid=7054, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 17:23:28.100  1037  2005 D WifiService: setWifiEnabled: true pid=7054, uid=10118
08-09 17:23:28.100  1037  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 17:23:28.120  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 17:23:28.120  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 17:23:28.120  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-09 17:23:28.122  1037  1541 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-09 17:23:28.122  1037  1541 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-09 17:23:28.124  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-09 17:23:28.124  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-09 17:23:28.124  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-09 17:23:28.124  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-09 17:23:28.124  1037  1541 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-09 17:23:28.124  1037  1541 E WifiHW  : unknown target_country: EU , set to default
08-09 17:23:28.124  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-09 17:23:28.124  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-09 17:23:28.124  1037  1541 I WifiUtil: gEnableBmps=1
08-09 17:23:28.136  7486  7486 I art     : Almond Protected OAT
,08-09 17:23:28.191  7486  7486 D WeatherApplication: removeAccount
,08-09 17:23:28.193  7486  7486 D WeatherApplication: Account.length = 0
,08-09 17:23:28.193  7486  7486 E WeatherApplication: OPERATOR:OPEN
08-09 17:23:28.199  7486  7486 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:28
08-09 17:23:28.208  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:28.208  1037  1540 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-09 17:23:28.211  7486  7486 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-09 17:23:28.211  7486  7486 D Weather.Utils: 2 : All the weather widget is gone.
,08-09 17:23:28.214  7486  7486 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 17:23:28.216  7486  7486 D WeatherAncestor: connectivity changed - connection : true
08-09 17:23:28.217  7486  7486 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-09 17:23:28.232  7486  7486 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 17:23:28.232  7486  7486 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 17:23:28.232  7486  7486 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-09 17:23:28.256  7486  7486 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 17:23:28.256  7486  7486 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:28
,08-09 17:23:28.289  1037  2091 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7505 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-09 17:23:28.290  1037  2091 I ActivityManager: Killing 6986:com.lge.bnr/1000 (adj 15): empty #17
08-09 17:23:28.350  1037  1653 W libprocessgroup: failed to open /acct/uid_1000/pid_6986/cgroup.procs: No such file or directory
,08-09 17:23:28.463   279   388 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 17:23:28.463   279   388 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-09 17:23:28.463   279   388 W Vold    : Returning OperationFailed - no handler for errno 0
,08-09 17:23:28.464  7505  7529 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-09 17:23:28.466   279   388 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 17:23:28.466   279   388 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-09 17:23:28.466   279   388 W Vold    : Returning OperationFailed - no handler for errno 0
08-09 17:23:28.466  7505  7529 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-09 17:23:28.480   279   388 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 17:23:28.480   279   388 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-09 17:23:28.480   279   388 W Vold    : Returning OperationFailed - no handler for errno 0
08-09 17:23:28.482  7505  7531 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-09 17:23:28.485   279   388 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 17:23:28.485   279   388 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-09 17:23:28.485   279   388 W Vold    : Returning OperationFailed - no handler for errno 0
08-09 17:23:28.486  7505  7531 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-09 17:23:28.780  7505  7505 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-09 17:23:28.791  7505  7505 I LibraryLoader: Loading: webviewchromium
,08-09 17:23:28.795  7505  7505 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6542-6546)
08-09 17:23:28.796  7505  7505 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 17:23:28.806  7505  7505 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d44285e}
08-09 17:23:28.812  7505  7505 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 17:23:28.813  7505  7505 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 17:23:28.825  1037  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-09 17:23:28.833  1037  1098 D Tethering: InitialState.processMessage what=4
08-09 17:23:28.836  1037  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-09 17:23:28.841   311   896 D SoftapController: Softap fwReload - Ok
08-09 17:23:28.844  1037  1541 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (716ms)
08-09 17:23:28.846   311   896 D CommandListener: Setting iface cfg
08-09 17:23:28.847   311   896 D CommandListener: Trying to bring down wlan0
08-09 17:23:28.847   311   896 D CommandListener: Clearing all IP addresses on wlan0
,08-09 17:23:28.852  1037  1541 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-09 17:23:28.858  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 17:23:28.858  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-09 17:23:28.858  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 17:23:28.849  7556  7556 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:28.849  7556  7556 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:28.864  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-09 17:23:28.865  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 17:23:28.870  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-09 17:23:28.872  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:28.873  1037  1541 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-09 17:23:28.873  1037  1541 D WifiMonitor: connecting to supplicant
08-09 17:23:28.876  7505  7505 I BrowserStartupController: Initializing chromium process, renderers=0
08-09 17:23:28.878  7505  7505 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 17:23:28.879  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:28.885  7556  7556 I wpa_supplicant: Successfully initialized wpa_supplicant
08-09 17:23:28.889  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:23:28.903  7505  7505 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-09 17:23:28.903  7505  7505 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-09 17:23:28.904  7505  7505 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-09 17:23:28.910   316   316 V AudioPolicyService: registerClient() client 0xb558a900, uid 10093
08-09 17:23:28.911  7505  7561 W AudioManagerAndroid: Requires BLUETOOTH permission
08-09 17:23:28.921  7556  7556 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-09 17:23:28.922  7556  7556 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-09 17:23:28.929  7505  7505 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 17:23:28.929  7505  7505 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 17:23:28.929  7505  7505 I Adreno-EGL: Build Date: 12/12/14 금
08-09 17:23:28.929  7505  7505 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 17:23:28.929  7505  7505 I Adreno-EGL: Remote Branch: 
08-09 17:23:28.929  7505  7505 I Adreno-EGL: Local Patches: 
08-09 17:23:28.929  7505  7505 I Adreno-EGL: Reconstruct Branch: 
08-09 17:23:29.004  7505  7505 I NSApplication: Starting up...
08-09 17:23:29.008  7556  7556 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-09 17:23:29.062  7556  7556 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-09 17:23:29.070  7556  7556 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-09 17:23:29.071  7556  7556 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-09 17:23:29.073  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-09 17:23:29.074  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-09 17:23:29.075  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-09 17:23:29.076  1037  1541 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-09 17:23:29.077  1037  7580 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-09 17:23:29.077  1037  7580 D WifiMonitor: Dropping event because (p2p0) is stopped
08-09 17:23:29.077  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-09 17:23:29.077  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-09 17:23:29.077  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-09 17:23:29.077  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-09 17:23:29.077  1037  7580 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-09 17:23:29.077  1037  7580 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-09 17:23:29.078  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-09 17:23:29.079  1037  1541 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-09 17:23:29.079  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.080  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.080  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.081  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.081  1037  1541 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-09 17:23:29.081  1037  1541 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-09 17:23:29.082  1037  1541 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-09 17:23:29.082  1037  1541 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
,08-09 17:23:29.082  1037  1541 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-09 17:23:29.087  1037  2115 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7581 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-09 17:23:29.089  1037  2115 I ActivityManager: Killing 6671:com.android.vending/u0a44 (adj 15): empty #17
,08-09 17:23:29.140  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 17:23:29.140  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-09 17:23:29.140  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-09 17:23:29.142  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.142  1037  2005 W libprocessgroup: failed to open /acct/uid_10044/pid_6671/cgroup.procs: No such file or directory
08-09 17:23:29.142  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.142  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.142  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.142  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 17:23:29.145  1037  1541 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-09 17:23:29.145  1037  1541 D WifiNative-wlan0: SET update_config 1: returned true
08-09 17:23:29.145  1037  1541 D WifiConfigStore: Loading config and enabling all networks 
08-09 17:23:29.145  1037  1541 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-09 17:23:29.145  1037  1541 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-09 17:23:29.151  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-09 17:23:29.152  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.152  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-09 17:23:29.153  1971  1971 D WfdService: Waiting for WifiP2p enabling
08-09 17:23:29.154  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:29.154  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:29.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:29.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:29.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:29.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:29.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:29.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:29.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:29.154  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:29.154  1037  1541 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-09 17:23:29.154  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:29.155  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:29.155  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:29.155  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:29.155  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:29.155  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:29.155  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:29.155  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:29.155  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:29.155  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:29.155  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:29.155  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 17:23:29.156  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:29.156  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:29.156  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:29.156  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:29.156  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:29.156  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:29.156  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:29.156  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:29.156  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:29.156  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:29.157  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:29.164  1037  1541 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-09 17:23:29.165  1037  1541 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 17:23:29.166  1037  1541 D WifiStateMachine: enableVerboseLogging : level 2
08-09 17:23:29.166  1037  1541 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-09 17:23:29.166  1037  1541 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-09 17:23:29.166  1037  1541 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-09 17:23:29.167  1037  1541 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-09 17:23:29.167  1037  1541 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-09 17:23:29.167  1037  1541 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-09 17:23:29.167  1037  1541 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-09 17:23:29.167  1037  1541 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-09 17:23:29.167  1037  1541 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-09 17:23:29.168  1037  1541 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-09 17:23:29.168  1037  1541 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-09 17:23:29.169  1037  1541 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-09 17:23:29.169  1037  1541 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-09 17:23:29.169  1037  1541 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-09 17:23:29.171  1971  1971 D WfdsService: Supplicant Connection state is changed : true
08-09 17:23:29.171  1971  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-09 17:23:29.171  1971  2295 D WfdsService: Set the WFDS Monitor: true
08-09 17:23:29.171  1971  2295 D WfdsMonitor: WfdsMonitorThread create
08-09 17:23:29.171  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-09 17:23:29.172  1037  1541 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-09 17:23:29.172  1971  2295 D WfdsMonitor: WFDS Monitor is created and started
08-09 17:23:29.172  1971  2295 D WfdsService: WiFi: Supplicant connection re-established
08-09 17:23:29.172  1037  1541 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-09 17:23:29.172  1037  1541 D WifiNative-HAL: Setting external_sim to 1
08-09 17:23:29.172  1037  1541 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-09 17:23:29.172  1037  1541 D WifiNative-wlan0: SET external_sim 1: returned true
08-09 17:23:29.172  1037  1541 I WifiNative-HAL: startHal
08-09 17:23:29.172  1037  1541 D wifi    : setting scan oui 0xaf67f2e0
08-09 17:23:29.173  1971  7598 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-09 17:23:29.173  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-09 17:23:29.173  1037  1541 I WifiNative-HAL: startHal
08-09 17:23:29.173  1037  1541 D wifi    : setting scan oui 0xaf67f2e0
08-09 17:23:29.173  1971  7598 E CtrlSupplicant: Succeed to open control connection
08-09 17:23:29.173  1037  1541 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-09 17:23:29.173  1971  7598 E CtrlSupplicant: Succeed to open monitor connection
08-09 17:23:29.174  1971  7598 D WfdsMonitor: Supplicant connection established
08-09 17:23:29.174  1971  2295 D WfdsService: Connected to the supplicant for wfds
08-09 17:23:29.174  1037  1541 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-09 17:23:29.174  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-09 17:23:29.174  7581  7581 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 17:23:29.174  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-09 17:23:29.174  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-09 17:23:29.175  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-09 17:23:29.175  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-09 17:23:29.175  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-09 17:23:29.175  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-09 17:23:29.175  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-09 17:23:29.176  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-09 17:23:29.176  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-09 17:23:29.176  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-09 17:23:29.176  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-09 17:23:29.176  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-09 17:23:29.176  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-09 17:23:29.176  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-09 17:23:29.177  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-09 17:23:29.177  7556  7556 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-09 17:23:29.177  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-09 17:23:29.177  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-09 17:23:29.177  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-09 17:23:29.178  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-09 17:23:29.179  1037  1541 E WifiNative: : [376,917,970 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-09 17:23:29.179  1037  1541 D WifiNative-wlan0: doBoolean: RECONNECT
08-09 17:23:29.179  1037  1541 D WifiNative-wlan0: RECONNECT: returned true
08-09 17:23:29.179  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-09 17:23:29.180  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-09 17:23:29.180  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-09 17:23:29.180  1037  1541 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-09 17:23:29.180  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 17:23:29.180  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-09 17:23:29.180  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.181  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-09 17:23:29.181  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-09 17:23:29.182  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-09 17:23:29.182  1037  1559 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.182  1037  1559 I WifiNative-HAL: startHal
08-09 17:23:29.182  1037  1559 D wifi    : getting scan capabilities on interface[1] = 0xaf67f2e0
08-09 17:23:29.182  1037  1559 D wifi    : failed to get capabilities : -3
08-09 17:23:29.182  1037  1559 E WifiScanningService: could not get scan capabilities
08-09 17:23:29.182  1037  1541 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-09 17:23:29.182  1037  1560 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.182  1037  1541 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-09 17:23:29.182   311   896 D CommandListener: Setting iface cfg
08-09 17:23:29.183   311   896 D CommandListener: Trying to bring up p2p0
08-09 17:23:29.183  1037  1541 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-09 17:23:29.183  1037  1540 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-09 17:23:29.183  1037  1540 D LGWifiP2pService: P2pEnablingState
08-09 17:23:29.183  1037  1540 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.183  1037  1540 D LGWifiP2pService: P2p socket connection successful
08-09 17:23:29.183  1037  1540 D LGWifiP2pService: P2pEnabledState
08-09 17:23:29.183  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=376923  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 17:23:29.183  1037  1540 D LGWifiP2pService: sending p2p connection changed broadcast
08-09 17:23:29.184  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-09 17:23:29.185  1971  1971 D WfdsService: WifiP2pState is changed : true
08-09 17:23:29.185  1971  2295 D WfdsService: Receive the WFDS_ENABLE Method
08-09 17:23:29.185  1971  2295 D WfdsService: Set the WFDS Monitor: true
08-09 17:23:29.185  1971  2295 D WfdsService: Connected to the supplicant for wfds
08-09 17:23:29.185  1971  2295 D WfdsJNI : doCommand: WFDS_SET TRUE
08-09 17:23:29.185  7556  7556 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-09 17:23:29.186  1971  2295 D WfdsService: selectPreferredScanChannel [36]
08-09 17:23:29.186  1971  2295 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-09 17:23:29.186  1971  1971 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-09 17:23:29.187  1971  1971 D WfdsService: isConnected: false
,08-09 17:23:29.187  1037  1540 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-09 17:23:29.188  1037  1540 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-09 17:23:29.188  1037  1540 D WifiNative-p2p0: doBoolean: SET device_name G3
08-09 17:23:29.189  1037  1540 D WifiNative-p2p0: SET device_name G3: returned true
08-09 17:23:29.189  1037  1540 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-09 17:23:29.189  1037  1540 D LGWifiP2pService: before postfix = G3
08-09 17:23:29.189  1037  1540 D WifiServerServiceExt: postfix byte check : 2
08-09 17:23:29.189  1037  1540 D LGWifiP2pService: after postfix = G3
08-09 17:23:29.189  1037  1540 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-09 17:23:29.189  1037  1540 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-09 17:23:29.189  1037  1540 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-09 17:23:29.190  1037  1540 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-09 17:23:29.190  1037  1540 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-09 17:23:29.190  1037  1540 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-09 17:23:29.190  1037  1540 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-09 17:23:29.190  1037  1540 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-09 17:23:29.190  1037  1540 D WifiNative-HAL: p2pGetDeviceAddress
08-09 17:23:29.191  1037  1540 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-09 17:23:29.192  1971  1971 I WfdStateTracker: handleP2pThisDeviceChanged
08-09 17:23:29.193  1037  1540 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-09 17:23:29.193  1971  1971 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-09 17:23:29.193  1037  1540 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-09 17:23:29.193  1971  1971 D WfdsService: Update P2p Interface State: 3
08-09 17:23:29.193  1037  1540 D WifiNative-p2p0: P2P_FLUSH: returned true
08-09 17:23:29.193  1037  1540 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-09 17:23:29.194  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.194  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:29.195  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.195  1037  1540 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-09 17:23:29.195  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.195  1037  1540 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-09 17:23:29.195  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.195  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-09 17:23:29.196  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=376936  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 17:23:29.196  1037  1540 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-09 17:23:29.196  1037  1540 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-09 17:23:29.197  1037  1541 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-09 17:23:29.197  1037  1541 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-09 17:23:29.198  1037  1541 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-09 17:23:29.198  1037  1541 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-09 17:23:29.204  7556  7556 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-09 17:23:29.205  1037  1541 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-09 17:23:29.205  1037  1540 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-09 17:23:29.205  1037  1540 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-09 17:23:29.205  1037  1540 D LGWifiP2pService: InactiveState
08-09 17:23:29.205  1037  1541 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-09 17:23:29.205  1037  1540 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.205  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.206  1037  1540 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-09 17:23:29.206  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-09 17:23:29.206  1037  1541 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-09 17:23:29.207  1037  1541 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-09 17:23:29.207  7556  7556 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:29.207  1971  7598 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 17:23:29.207  1037  7580 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 17:23:29.207  1037  7580 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:29.207  1037  7580 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:29.207  1037  7580 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:29.207  7556  7556 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-09 17:23:29.207  7556  7556 E wpa_supplicant: disconnect_rssi_lvl: -100
08-09 17:23:29.207  7556  7556 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.208  1971  7598 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:29.208  1037  7580 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:29.208  1037  7580 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.208  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-09 17:23:29.208  1037  7580 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.208  1037  7580 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.208  1037  1540 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-09 17:23:29.208  1037  1540 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.208  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.208  1037  1540 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.208  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-09 17:23:29.209  1037  1540 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.209  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.209  1037  1540 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.209  1037  1540 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.209  7556  7556 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.209  1971  2295 W WfdsService: DefaultState - msg [9441285] is not handled
08-09 17:23:29.209  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-09 17:23:29.209  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-09 17:23:29.209  1037  7580 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:29.209  1037  7580 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.209  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.209  1037  7580 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.209  1037  1540 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.209  1037  7580 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.210  1971  7598 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:29.210  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-09 17:23:29.211  7556  7556 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:29.211  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 17:23:29.211  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:29.211  1037  7580 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:29.211  1037  7580 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:29.211  7556  7556 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-09 17:23:29.211  7556  7556 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.211  1037  1541 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-09 17:23:29.212  1037  7580 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:29.212  1037  7580 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.212  1037  7580 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.212  1037  7580 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.212  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-09 17:23:29.212  7556  7556 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.212  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-09 17:23:29.213  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-09 17:23:29.213  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-09 17:23:29.213  1971  7598 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:29.213  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-09 17:23:29.213  7556  7556 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 17:23:29.214  1037  1541 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-09 17:23:29.214  1037  1541 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-09 17:23:29.214  1971  7598 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:29.214  1037  7580 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:29.214  1037  7580 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.214  1037  7580 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.214  1037  7580 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:29.215  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-09 17:23:29.215  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-09 17:23:29.215  1037  7580 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 17:23:29.215  1037  7580 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 17:23:29.215  1037  1541 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,08-09 17:23:29.215  1037  1541 D WifiNative-wlan0: doBoolean: SCAN
08-09 17:23:29.215  1037  1541 D WifiNative-wlan0: SCAN: returned false
08-09 17:23:29.216  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=376956  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 17:23:29.217  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=376956  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 17:23:29.217  1037  1541 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 17:23:29.217  1037  1541 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-09 17:23:29.218  1037  1541 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 17:23:29.219  1037  1541 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 17:23:29.219  1037  1541 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 17:23:29.221  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.221  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:29.222  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.222  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.222  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-09 17:23:29.222  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-09 17:23:29.222  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-09 17:23:29.222  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.222  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:29.222  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-09 17:23:29.222  1037  1540 D LGWifiP2pService: InactiveState{ when=-17ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.223  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.223  1037  1540 D LGWifiP2pService: DefaultState{ when=-17ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.223  1037  1037 E WifiServerServiceExt: No p2p device connected
08-09 17:23:29.223  1037  1540 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.223  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.421  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 17:23:29.427  6774  7201 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-09 17:23:29.444  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:29.452  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-09 17:23:29.452  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:29.452  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 17:23:29.452  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-09 17:23:29.454  7361  7361 I AppUp4:CustModeStarterReceiver: onReceive
08-09 17:23:29.457  7361  7361 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e5c62d
,08-09 17:23:29.457  7361  7361 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-09 17:23:29.457  7361  7361 D AppUp4:CustFacade: isPhone : true
08-09 17:23:29.458  7361  7361 D AppUp4:CustModeStarterReceiver: begin check event
08-09 17:23:29.458  7361  7361 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-09 17:23:29.462  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:29.462  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 17:23:29.464  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:29.466  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:29.473  4700  7610 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-09 17:23:29.474  7402  7402 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-09 17:23:29.476  4700  7611 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:29.476  4700  7611 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-09 17:23:29.500  7402  7613 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 17:23:29.507  3307  3307 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 17:23:29.507  3307  3307 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:29.507  3307  3307 I LgeMiscReceiver: networkInfo.isConnected() = false
08-09 17:23:29.508  7306  7615 W FormManager: Network not available. Please check & try again.
08-09 17:23:29.512  7431  7431 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-09 17:23:29.512  7431  7431 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-09 17:23:29.515  7306  7616 V FormManager: Network unavailable.
,08-09 17:23:29.522  7306  7616 V FormManager: Network unavailable.
08-09 17:23:29.530  7486  7486 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:29
,08-09 17:23:29.533  7486  7486 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-09 17:23:29.533  7486  7486 D Weather.Utils: 2 : All the weather widget is gone.
08-09 17:23:29.534  7486  7486 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 17:23:29.534  7486  7486 D WeatherAncestor: connectivity changed - connection : true
08-09 17:23:29.534  7486  7486 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@11cb70f3
08-09 17:23:29.535  7486  7486 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 17:23:29.536  7486  7486 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 17:23:29.536  7486  7486 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-09 17:23:29.536  7486  7486 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 17:23:29.536  7486  7486 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:29
08-09 17:23:29.563  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 17:23:29.563  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 17:23:29.563  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 17:23:29.563  7178  7178 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 17:23:29.563  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-09 17:23:29.564  7178  7178 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 17:23:29.564  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-09 17:23:29.564  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 17:23:29.564  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 17:23:29.564  7178  7178 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 17:23:29.565  7178  7178 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-09 17:23:29.575  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:29.579  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-09 17:23:29.584  7306  7619 W FormManager: Network not available. Please check & try again.
08-09 17:23:29.590  7306  7620 V FormManager: Network unavailable.
08-09 17:23:29.590  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:29.597  7306  7620 V FormManager: Network unavailable.
,08-09 17:23:29.613  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 17:23:29.618  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 17:23:29.624  7306  7622 W FormManager: Network not available. Please check & try again.
08-09 17:23:29.626  7306  7623 V FormManager: Network unavailable.
,08-09 17:23:29.629  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:29.633  7306  7623 V FormManager: Network unavailable.
08-09 17:23:29.641  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-09 17:23:29.642  1037  7580 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-09 17:23:29.642  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-09 17:23:29.642  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-09 17:23:29.642  1037  7580 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-09 17:23:29.642  7556  7556 E wpa_supplicant: USIM:  scard_init function
08-09 17:23:29.643  1037  1541 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-09 17:23:29.643  1037  1541 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-09 17:23:29.643  7556  7556 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-09 17:23:29.644  1037  1541 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-09 17:23:29.644  1037  1541 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-09 17:23:29.644  1037  1541 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-09 17:23:29.644  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-09 17:23:29.645  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-09 17:23:29.654  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 17:23:29.654  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 17:23:29.656  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 17:23:29.660  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:29.661  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=377401  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-09 17:23:29.665  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=377405  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-09 17:23:29.666  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.666  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:29.667  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.667  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.668  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-09 17:23:29.669  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 17:23:29.677  4700  7624 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-09 17:23:29.681  4700  7625 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 17:23:29.681  4700  7625 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 17:23:29.743  1037  1052 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7626 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-09 17:23:29.748  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:29.748  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-09 17:23:29.756  7556  7556 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-09 17:23:29.756  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-09 17:23:29.756  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-09 17:23:29.756  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-09 17:23:29.756  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-09 17:23:29.756  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:29.756  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:29.757  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=377497  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-09 17:23:29.759  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=377498  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-09 17:23:29.759  1037  1541 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=377499
08-09 17:23:29.760  1037  1541 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=377500
08-09 17:23:29.760  1037  1541 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=377500
08-09 17:23:29.761  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=377500
,08-09 17:23:29.761  1037  1541 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=377501
08-09 17:23:29.762  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=377502  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-09 17:23:29.764  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:29.764  7556  7556 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 17:23:29.764  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:29.765  7556  7556 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 17:23:29.765  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-09 17:23:29.765  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 17:23:29.765  1037  7580 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 17:23:29.765  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-09 17:23:29.765  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 17:23:29.765  1037  7580 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 17:23:29.766  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:29.766  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:29.768  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.768  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:29.770  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.770  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.770  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.770  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-09 17:23:29.771  1037  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-09 17:23:29.774  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=377513  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-09 17:23:29.778  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.778  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.778  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-09 17:23:29.779  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:29.779  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-09 17:23:29.779  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=377519  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-09 17:23:29.781  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=377520  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-09 17:23:29.782  1037  1541 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=377521
08-09 17:23:29.785  1037  1541 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=377522
08-09 17:23:29.786  1037  1541 D WifiNative-wlan0: doString: [STATUS]
,08-09 17:23:29.786  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:29.786  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:29.786  1037  1541 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-09 17:23:29.789  1037  1541 I WifiServiceExtension: setVHTCapabilityType  : false
08-09 17:23:29.791  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.791  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:29.792  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.794  1037  1541 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-09 17:23:29.794  1037  1541 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-09 17:23:29.798  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.798  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.798  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-09 17:23:29.802  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.802  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.802  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-09 17:23:29.810  1037  1541 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-09 17:23:29.810  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 17:23:29.810  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 17:23:29.811  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 17:23:29.811  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-09 17:23:29.812  1037  1548 D ConnectivityService: Got NetworkAgent Messenger
08-09 17:23:29.812  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-09 17:23:29.812  1037  1548 D ConnectivityService: NetworkAgent connected
08-09 17:23:29.816  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.816  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:29.817  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 17:23:29.817  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.817  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 17:23:29.817  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 17:23:29.817  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 17:23:29.817  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-09 17:23:29.819  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.819  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:29.820  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.822  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-09 17:23:29.823   311   896 D CommandListener: Setting iface cfg
08-09 17:23:29.826  1037  1541 E WifiStateMachine: Start Dhcp Watchdog 2
08-09 17:23:29.826  1037  7644 D DhcpStateMachine: StoppedState
08-09 17:23:29.826  1037  7644 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.826  1037  7644 D DhcpStateMachine: WaitBeforeStartState
08-09 17:23:29.827  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=377566  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:29.827  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=377567  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:29.828  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=377568  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:29.829  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.830  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.830  1037  1541 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.830  1037  1541 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.831  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.831  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:29.833  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:29.833  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-09 17:23:29.834  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:29.834  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-09 17:23:29.835  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=377575  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:29.835  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=377575  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:29.836  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=377576  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:29.837  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:331119] from screen [on:0 period:1877394605] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:23:29.839  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1877394606] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:23:29.839  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-09 17:23:29.842  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.843  1037  1548 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-09 17:23:29.843  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.843  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.844  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.844  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.844  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.845  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.845  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-09 17:23:29.845  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=160,0,0
08-09 17:23:29.846  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=160,0,0
,08-09 17:23:29.846  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-09 17:23:29.846  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-09 17:23:29.847  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-09 17:23:29.847  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 0
08-09 17:23:29.849  1037  1541 D WifiNative-wlan0: SET ps 0: returned true
08-09 17:23:29.849  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-09 17:23:29.849  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-09 17:23:29.850  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-09 17:23:29.850  1037  1541 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-09 17:23:29.850  1037  1541 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-09 17:23:29.850  1037  1541 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-09 17:23:29.851   311   896 D CommandListener: Setting iface cfg
08-09 17:23:29.851   311   896 D CommandListener: Trying to bring up wlan0
08-09 17:23:29.852  1037  1540 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37444d14 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.852  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37444d14 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.852  1037  7644 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.852  1037  7644 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-09 17:23:29.853  1037  1541 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-09 17:23:29.854  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:29.854  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-09 17:23:29.854  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.855  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:29.855  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-09 17:23:29.855  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.855  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.856  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.856  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.856  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:29.857  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-09 17:23:29.857  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-09 17:23:29.858  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-09 17:23:29.859  1037  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.859  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-09 17:23:29.860  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 17:23:29.860  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-09 17:23:29.860  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 17:23:29.860  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-09 17:23:29.861  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-09 17:23:29.861  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-09 17:23:29.861  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 17:23:29.873  7626  7626 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-09 17:23:29.874  7626  7626 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-09 17:23:29.877  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-09 17:23:29.877  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-09 17:23:29.878  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-09 17:23:29.878  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-09 17:23:29.878  1037  1541 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-09 17:23:29.879  1037  1548 D ConnectivityService: ignoring duplicate network state non-change
08-09 17:23:29.881  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.881  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:29.882  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.882  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.882  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-09 17:23:29.883  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.883  7626  7626 V [BNRBootReceiver]: Boot Receiver Return
08-09 17:23:29.883  7626  7626 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-09 17:23:29.883  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-09 17:23:29.884  1037  1548 D ConnectivityService: Adding iface wlan0 to network 101
08-09 17:23:29.886  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.886  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.886  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-09 17:23:29.887  1037  1541 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-09 17:23:29.889  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-09 17:23:29.890  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.890  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:29.891  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.892  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.892  1971  1971 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-09 17:23:29.892  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.892  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-09 17:23:29.893  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-09 17:23:29.898  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.898  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:29.898  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-09 17:23:29.901  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:29.907  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:29.907  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-09 17:23:29.909  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 17:23:29.909  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.913  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-09 17:23:29.913  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-09 17:23:29.913  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.914  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:29.920  1037  1548 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-09 17:23:29.920  1037  1548 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-09 17:23:29.921  1037  1548 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-09 17:23:29.922   311   896 E Netd    : netlink response contains error (File exists)
08-09 17:23:29.922  1037  1548 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-09 17:23:29.923  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:29.923  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:29.924  1037  1548 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-09 17:23:29.924  1037  1548 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-09 17:23:29.924  1037  1548 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-09 17:23:29.924  7237  7237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 17:23:29.927  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 17:23:29.930  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-09 17:23:29.930  1037  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-09 17:23:29.930  1037  1548 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-09 17:23:29.930  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-09 17:23:29.930  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:29.930  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:29.930  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-09 17:23:29.930  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:29.930  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-09 17:23:29.930  1037  1548 D ConnectivityService: currentScore = 0, newScore = 20
08-09 17:23:29.930  1037  1548 D ConnectivityService:    accepting network in place of null
08-09 17:23:29.931  1037  1548 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:29.931  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.931  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-09 17:23:29.932  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:29.932  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-09 17:23:29.932  1880  1880 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:29.932  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 17:23:29.933  1037  1541 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:29.934  1037  1548 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-09 17:23:29.934  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:29.934  1037  1548 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-09 17:23:29.934  1037  1548 D ConnectivityService: sendStickyBroadcas,t: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 17:23:29.934   311  7649 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-09 17:23:29.935  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:29.935  1037  1548 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-09 17:23:29.936  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-09 17:23:29.936  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 17:23:29.936  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 17:23:29.936  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 17:23:29.937  1037  1548 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-09 17:23:29.939  1037  1548 D ConnectivityService: validation of new default Network = false
08-09 17:23:29.939  1037  1548 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-09 17:23:29.939  1037  1548 D DSQN    : enableDataServiceNotify 
08-09 17:23:29.939  1037  1548 D DSQN    : start dsqn bin
,08-09 17:23:29.944  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 17:23:29.945  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-09 17:23:29.945  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:29.945  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:29.945  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:29.946  1606  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-09 17:23:29.929  7650  7650 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:29.929  7650  7650 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-09 17:23:29.952  1037  1539 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-09 17:23:29.955  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:29.961  7650  7650 E DSQN    : DSQN ssw
,08-09 17:23:29.970  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:29.971  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:29.972  7237  7237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 17:23:29.976  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-09 17:23:29.979  1821  7654 I CheckinService: active receiver: enabled
08-09 17:23:29.979  7178  7178 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-09 17:23:29.988  1821  7654 I CheckinService: Preparing to send checkin request
08-09 17:23:29.988  1821  7654 I EventLogService: Accumulating logs since 1470755959529
08-09 17:23:29.988  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:29.991  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 17:23:29.993  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.994  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:29.995  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:30.000  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:30.003   311  7649 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-09 17:23:30.005  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:30.005  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:30.006  7237  7237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 17:23:30.008  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 17:23:30.013  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 17:23:30.017  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:30.023  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 17:23:30.024  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:30.025  7237  7237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 17:23:30.025  1821  7654 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-09 17:23:30.029  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 17:23:30.029  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 17:23:30.029  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 17:23:30.029  7178  7178 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 17:23:30.030  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-09 17:23:30.030  7178  7178 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 17:23:30.031  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-09 17:23:30.031  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 17:23:30.031  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 17:23:30.031  7178  7178 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 17:23:30.031  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-09 17:23:30.031  7178  7178 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 17:23:30.035  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 17:23:30.044   311  7649 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-09 17:23:30.046  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:30.052  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:30.054  1037  7644 D DhcpStateMachine: DHCPV4 request on wlan0
08-09 17:23:30.054  1037  7644 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-09 17:23:30.054  1037  7644 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-09 17:23:30.039  7656  7656 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:30.049  7656  7656 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:30.057  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:30.057  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:30.057  7237  7237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 17:23:30.062  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:30.066  7656  7656 I dhcpcd  : version 5.5.6 starting
08-09 17:23:30.068  7656  7656 E dhcpcd  : get_duid: m
,08-09 17:23:30.068  7656  7656 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-09 17:23:30.068  7656  7656 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-09 17:23:30.070  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:30.077  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:30.084  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:30.085  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:30.085  7237  7237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 17:23:30.088   311   895 D LGDataListener: argv[0]=dsqncommand
,08-09 17:23:30.088   311   895 D LGDataListener: argv[1]=wlan0
08-09 17:23:30.088   311   895 D LGDataListener: argv[2]=1
08-09 17:23:30.088   311   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-09 17:23:30.089  1037  1096 D DSQN    : DSQM DsqnNotification wlan0  1
08-09 17:23:30.089  1037  1096 D DSQN    : start to monitor internet connection
08-09 17:23:30.089  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:30.097  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:30.111  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:30.116  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:30.117  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:30.117  7237  7237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 17:23:30.122  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 17:23:30.131  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 17:23:30.131  7656  7656 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-09 17:23:30.131  7656  7656 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-09 17:23:30.131  7656  7656 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-09 17:23:30.131  7656  7656 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-09 17:23:30.132  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 15:23:30 GMT], X-Android-Received-Millis=[1470756210131], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470756210087]}
08-09 17:23:30.132  7656  7656 D dhcpcd  : wlan0: sending REQUEST (xid 0x209ab7bc), next in 3.90 seconds
08-09 17:23:30.132  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-09 17:23:30.132  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-09 17:23:30.132  1037  1548 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-09 17:23:30.132  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-09 17:23:30.132  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:30.132  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:30.132  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-09 17:23:30.132  1037  1548 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-09 17:23:30.132  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-09 17:23:30.132  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:30.132  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:30.133  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-09 17:23:30.133  1037  1548 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:30.133  1606  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-09 17:23:30.133  1037  1541 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:30.133  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:30.133  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-09 17:23:30.133  1880  1880 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:30.134  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 17:23:30.137  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:30.144  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:30.144  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:30.147  7237  7237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 17:23:30.151  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:30.152  7656  7656 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-09 17:23:30.158  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:30.163  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:30.165  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 17:23:30.166  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:30.167  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:30.170  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:30.171  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:30.171  7237  7237 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 17:23:30.172  1037  1052 I art     : Explicit concurrent mark sweep GC freed 96321(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.960ms total 139.176ms
,08-09 17:23:30.174  7656  7656 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-09 17:23:30.174  7656  7656 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-09 17:23:30.174  7656  7656 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-09 17:23:30.174  7656  7656 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-09 17:23:30.174  7656  7656 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-09 17:23:30.175  7656  7656 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-09 17:23:30.175  7656  7656 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-09 17:23:30.175  7656  7656 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-09 17:23:30.181  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:30.189  7202  7202 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-09 17:23:30.196  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:30.199  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:30.205  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:30.210  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:30.210  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:30.211  7237  7237 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-09 17:23:30.212  7237  7237 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-09 17:23:30.212  7237  7237 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-09 17:23:30.218  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 17:23:30.222  7202  7202 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-09 17:23:30.222  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:30.225  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:30.228  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:30.233  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:30.234  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:30.234  7237  7237 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-09 17:23:30.235  7237  7237 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-09 17:23:30.235  7237  7237 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-09 17:23:30.268  1037  1915 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7675 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-09 17:23:30.272  1037  2051 I ActivityManager: Killing 7155:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-09 17:23:30.316  1037  1969 W libprocessgroup: failed to open /acct/uid_10037/pid_7155/cgroup.procs: No such file or directory
,08-09 17:23:30.336  7675  7675 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-09 17:23:30.336  7675  7675 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-09 17:23:30.354  7675  7675 I MultiDex: VM with version 2.1.0 has multidex support
08-09 17:23:30.354  7675  7675 I MultiDex: install
08-09 17:23:30.354  7675  7675 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-09 17:23:30.363  7675  7675 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-09 17:23:30.367  2230  2230 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-09 17:23:30.375  2230  2230 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-09 17:23:30.375  2230  2230 D c       : Getting all permits...
08-09 17:23:30.375  2230  2230 D a       : Opening database...
08-09 17:23:30.379  2230  2230 D a       : Opening database auth.proximity.permit_store...
08-09 17:23:30.380  2230  2230 D a       : Closing database...
08-09 17:23:30.458  1037  7644 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-09 17:23:30.462  1037  7644 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-09 17:23:30.463  1037  7644 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-09 17:23:30.463  1037  7644 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-09 17:23:30.463  1037  7644 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-09 17:23:30.463  1037  7644 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-09 17:23:30.463  1037  7644 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-09 17:23:30.463  1037  7644 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-09 17:23:30.465  1037  7644 D DhcpStateMachine: RunningState
08-09 17:23:30.649  7706  7706 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-09 17:23:30.736  7706  7706 I dex2oat : dex2oat took 86.804ms (threads: 4)
,08-09 17:23:30.743  6897  7353 D UEI.SmartControl: Internal timer expired: 2
,08-09 17:23:30.743  6897  7353 D UEI.SmartControl: unbind internal service
,08-09 17:23:30.757  7675  7694 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 17:23:30.757  7675  7694 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 17:23:30.757  7675  7694 I Adreno-EGL: Build Date: 12/12/14 금
08-09 17:23:30.757  7675  7694 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 17:23:30.757  7675  7694 I Adreno-EGL: Remote Branch: 
08-09 17:23:30.757  7675  7694 I Adreno-EGL: Local Patches: 
08-09 17:23:30.757  7675  7694 I Adreno-EGL: Reconstruct Branch: 
,08-09 17:23:30.831  1037  1541 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 17:23:30.831  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-09 17:23:30.831  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-09 17:23:30.832  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 17:23:30.832  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 17:23:30.833  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 17:23:30.837  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-09 17:23:30.837  1037  1548 D ConnectivityService: identical MTU - not setting
08-09 17:23:30.838  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-09 17:23:30.838  1037  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-09 17:23:30.839  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-09 17:23:30.839  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:30.840  1037  1548 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:30.842  1606  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-09 17:23:30.871  6897  7347 D serial_port: close(fd = 24)
,08-09 17:23:30.881  6897  7347 I UEI.SmartControl: Serial port is closed.
,08-09 17:23:30.897  7675  7694 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 17:23:30.897  7675  7694 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 17:23:30.897  7675  7694 I Adreno-EGL: Build Date: 12/12/14 금
08-09 17:23:30.897  7675  7694 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 17:23:30.897  7675  7694 I Adreno-EGL: Remote Branch: 
08-09 17:23:30.897  7675  7694 I Adreno-EGL: Local Patches: 
08-09 17:23:30.897  7675  7694 I Adreno-EGL: Reconstruct Branch: 
,08-09 17:23:30.946  1037  1548 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-09 17:23:30.975  7675  7694 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 17:23:30.975  7675  7694 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 17:23:30.975  7675  7694 I Adreno-EGL: Build Date: 12/12/14 금
08-09 17:23:30.975  7675  7694 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 17:23:30.975  7675  7694 I Adreno-EGL: Remote Branch: 
08-09 17:23:30.975  7675  7694 I Adreno-EGL: Local Patches: 
08-09 17:23:30.975  7675  7694 I Adreno-EGL: Reconstruct Branch: 
,08-09 17:23:31.052  7675  7694 D LgDataFeature: LgDataFeature() Constructor: none
,08-09 17:23:31.053  7675  7694 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:23:31.328   311  7721 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-09 17:23:31.328   311  7721 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-09 17:23:31.373   311  7721 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-09 17:23:31.558  1821  7654 I CheckinTask: Sending checkin request (7828 bytes)
,08-09 17:23:31.933  1821  7654 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-09 17:23:31.952  1821  7654 I CheckinService: active receiver: disabled
,08-09 17:23:31.976  2230  2230 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-09 17:23:31.994  2230  2230 I GCM     : GCM config loaded
,08-09 17:23:32.002   311  7732 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-09 17:23:32.002   311  7732 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-09 17:23:32.011  7431  7431 V SetupWizard: Connected to Gservices successfully
,08-09 17:23:32.033   311  7732 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-09 17:23:32.338  2230  7735 D GCM     : Connected
,08-09 17:23:32.378  2230  7735 D GCM     : Message class com.google.e.a.a.q
,08-09 17:23:32.847  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=80.0, 0.0, 0.0  rx=80.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1877397615] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 17:23:32.860  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=80.0, 0.0, 0.0  rx=80.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1877397628] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 17:23:32.860  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-09 17:23:32.881  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 17:23:32.888  1037  1543 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-09 17:23:32.937  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:32.955  1037  1098 D Tethering: MasterInitialState.processMessage what=3
08-09 17:23:32.967  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:32.967  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:32.967  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:32.967  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:32.967  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:32.967  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:32.967  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:32.967  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:23:32.967  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:23:32.967  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:32.967  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 17:23:32.973  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:32.974  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:32.974  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:32.974  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:32.974  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:32.974  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:32.974  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:32.974  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:23:32.974  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:23:32.974  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:32.974  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:32.981  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:32.981  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:32.981  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:32.981  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:32.981  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:32.981  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:32.981  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:32.981  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:23:32.981  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:23:32.981  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 17:23:32.985  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:32.991  1037  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:32.993  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 17:23:32.995  6774  7201 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-09 17:23:33.006  5818  5818 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-09 17:23:33.050  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:33.065  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 17:23:33.065  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:33.066  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 17:23:33.066  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-09 17:23:33.071  7361  7361 I AppUp4:CustModeStarterReceiver: onReceive
08-09 17:23:33.074  7361  7361 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e5c62d
08-09 17:23:33.074  7361  7361 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 17:23:33.074  7361  7361 D AppUp4:CustFacade: isPhone : true
08-09 17:23:33.075  7361  7361 D AppUp4:CustModeStarterReceiver: begin check event
08-09 17:23:33.075  7361  7361 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-09 17:23:33.100  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:33.101  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 17:23:33.105  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 17:23:33.106  1037  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:33.112  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:33.118  3411  3411 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:33.122  3411  3411 V DownloadManager: DownloadService onCreate
08-09 17:23:33.126  3411  7757 I DownloadManager: in removeSpuriousFiles
08-09 17:23:33.127  1037  1780 D WifiServiceImplEx: setWifiEnabled: false pid=7054, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 17:23:33.127  1037  1970 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-09 17:23:33.127  1037  1780 D WifiService: setWifiEnabled: false pid=7054, uid=10118
08-09 17:23:33.127  1037  1780 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 17:23:33.127  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.127  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.127  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-09 17:23:33.127  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.127  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-09 17:23:33.130  7402  7402 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-09 17:23:33.130  4700  7755 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-09 17:23:33.131  3411  7757 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-09 17:23:33.133  3411  7757 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@26e107e6 on behalf of 3411
08-09 17:23:33.134  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-09 17:23:33.134  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-09 17:23:33.135  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-09 17:23:33.135  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-09 17:23:33.135  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-09 17:23:33.135  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-09 17:23:33.135  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-09 17:23:33.135  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-09 17:23:33.135  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-09 17:23:33.135  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-09 17:23:33.135  3411  7757 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-09 17:23:33.136  1037  1541 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:33.136  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:33.137  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 17:23:33.137  1037  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:33.137  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 17:23:33.137  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-09 17:23:33.137  1037  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:33.137  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-09 17:23:33.137  1037  1541 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-09 17:23:33.137  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 17:23:33.137  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 17:23:33.138  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 17:23:33.138  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-09 17:23:33.140  3411  7757 I DownloadManager: in trimDatabase
08-09 17:23:33.140  3411  7757 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-09 17:23:33.141  3411  7757 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@201ca127 on behalf of 3411
08-09, 17:23:33.142  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 17:23:33.142  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 17:23:33.142  1037  1540 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.142  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.142  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-09 17:23:33.143  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 17:23:33.143  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 17:23:33.143  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-09 17:23:33.144  1037  7644 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.144   311   896 D CommandListener: Clearing all IP addresses on wlan0
08-09 17:23:33.151  4700  7755 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-09 17:23:33.154   311  7763 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-09 17:23:33.155  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-09 17:23:33.158  4700  7761 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:33.158  4700  7761 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 17:23:33.159  1037  1096 D DSQN    : Dns fail occured do internet check.
08-09 17:23:33.159  1037  1037 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-09 17:23:33.159  1037  1037 D DSQN    : try Internet connection check
08-09 17:23:33.159  3307  3307 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 17:23:33.160  3307  3307 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:33.160  3307  3307 I LgeMiscReceiver: networkInfo.isConnected() = true
08-09 17:23:33.160  3307  3307 D PhoneState: setPdpRejectCasuse : false
08-09 17:23:33.164  7431  7431 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-09 17:23:33.164  7431  7431 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-09 17:23:33.168   311  7770 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-09 17:23:33.178  1037  1096 D DSQN    : Dns timeout INTERNET_CHECK already in progress ignore!
08-09 17:23:33.179  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-09 17:23:33.179  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-09 17:23:33.182  1037  1541 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-09 17:23:33.182  1037  1540 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.182  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.182  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:33.182  1037  1540 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@38d64293
08-09 17:23:33.183  1037  1540 D LGWifiP2pService: P2pDisablingState
08-09 17:23:33.183  1037  1540 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.183  1037  1540 D LGWifiP2pService: p2p socket connection lost
08-09 17:23:33.183  1037  1540 D LGWifiP2pService: P2pDisabledState
08-09 17:23:33.183  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:33.183  1037  7769 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-09 17:23:33.183  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:33.183  1037  7767 D DSQN    : ThreadInternetCheck internet check NOK 
08-09 17:23:33.183  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:33.184  1037  7767 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-09 17:23:33.184  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:33.184  1037  7767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-09 17:23:33.184  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-09 17:23:33.185  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-09 17:23:33.185  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 17:23:33.185  7556  7556 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-09 17:23:33.185  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.185  1037  1540 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.185  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 17:23:33.185  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 17:23:33.186  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-09 17:23:33.186  7486  7486 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:33
08-09 17:23:33.188  1971  1971 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-09 17:23:33.188  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-09 17:23:33.189  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:33.189  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:33.191  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:33.191  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:33.191  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:33.191  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 17:23:33.191  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-09 17:23:33.193  7486  7486 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-09 17:23:33.193  7486  7486 D Weather.Utils: 2 : All the weather widget is gone.
08-09 17:23:33.193  7486  7486 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 17:23:33.193  7486  7486 D WeatherAncestor: connectivity changed - connection : true
08-09 17:23:33.193  7486  7486 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@11cb70f3
08-09 17:23:33.193  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:33.194  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:33.194  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 17:23:33.194  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-09 17:23:33.194  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-09 17:23:33.194  1037  1037 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-09 17:23:33.194  7486  7486 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 17:23:33.194  7486  7486 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 17:23:33.194  7486  7486 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-09 17:23:33.194  7486  7486 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 17:23:33.194  7486  7486 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:33
08-09 17:23:33.195  1037  1559 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.195  1037  1560 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.195  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-09 17:23:33.195  1971  1971 D WfdsService: WifiP2pState, is changed : false
08-09 17:23:33.195  1971  2295 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-09 17:23:33.195  1971  2295 D WfdsService: Set the WFDS Monitor: false
08-09 17:23:33.196  1971  2295 D WfdsMonitor: WFDS Monitor is stopped
08-09 17:23:33.196  1971  2295 D WfdsService: STATE : WfdsDisabledState - enter
08-09 17:23:33.196  1971  7598 D CtrlSupplicant: Received on exit socket, terminate
08-09 17:23:33.196  1971  7598 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-09 17:23:33.196  1971  7598 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-09 17:23:33.196  1971  7598 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-09 17:23:33.196  1971  2296 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-09 17:23:33.197  1971  2295 W WfdsService: DefaultState - msg [9445378] is not handled
08-09 17:23:33.200  1971  1987 D WifiServiceExtension: isInternetCheckAvailable return false
08-09 17:23:33.200  7402  7762 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 17:23:33.204  4700  7755 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-09 17:23:33.211  4700  4700 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-09 17:23:33.211  4700  4700 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-09 17:23:33.211  4700  4700 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-09 17:23:33.212  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:33.212  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:33.212  4700  4700 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-09 17:23:33.213  3411  3411 V DownloadManager: DownloadService onStartCommand
08-09 17:23:33.213  3411  7758 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-09 17:23:33.214  7306  7773 W FormManager: Network not available. Please check & try again.
08-09 17:23:33.214  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:33.215  4700  4700 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,08-09 17:23:33.219  7306  7775 V FormManager: Network unavailable.
08-09 17:23:33.221  3411  7758 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@11a5bc72 on behalf of 3411
08-09 17:23:33.223  3411  7758 V DownloadManager: processing inserted download 1
08-09 17:23:33.224  3411  7758 V DownloadManager: processing inserted download 4
08-09 17:23:33.224  3411  7758 V DownloadManager: processing inserted download 7
08-09 17:23:33.225  3411  7758 V DownloadManager: processing inserted download 8
08-09 17:23:33.226  3411  7758 V DownloadManager: processing inserted download 9
08-09 17:23:33.226  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:33.227  3411  7758 V DownloadManager: processing inserted download 10
,08-09 17:23:33.227  3411  7758 V DownloadManager: processing inserted download 11
08-09 17:23:33.229   311   896 D CommandListener: Clearing all IP addresses on wlan0
08-09 17:23:33.229  7202  7202 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-09 17:23:33.229  7202  7202 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 17:23:33.229  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:33.229  3411  7758 V DownloadManager: processing inserted download 12
08-09 17:23:33.229  1037  1548 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-09 17:23:33.229  1037  1548 D DSQN    : disableDataServiceNotify
08-09 17:23:33.229  1037  1548 D DSQN    : stop dsqn bin
08-09 17:23:33.230  3411  7758 V DownloadManager: processing inserted download 13
08-09 17:23:33.231  3411  7758 V DownloadManager: processing inserted download 14
08-09 17:23:33.231  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 17:23:33.232  3411  7758 V DownloadManager: processing inserted download 16
08-09 17:23:33.233  1037  1541 D WifiNative-p2p0: doBoolean: TERMINATE
08-09 17:23:33.233  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-09 17:23:33.234  7306  7775 V FormManager: Network unavailable.
08-09 17:23:33.234  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-09 17:23:33.234  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:33.234  1037  1541 D WifiNative-p2p0: TERMINATE: returned true
08-09 17:23:33.234  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 17:23:33.234  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-09 17:23:33.234  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 17:23:33.235  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:33.235  1037  1548 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-09 17:23:33.235  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:33.235  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:33.235  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 17:23:33.235  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:33.235  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:33.236  1037  1548 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:33.236  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-09 17:23:33.236  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.236  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.236  1037  7643 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-09 17:23:33.236  1037  1548 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBuffe,rSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-09 17:23:33.236  1037  1548 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-09 17:23:33.236  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 17:23:33.236  1606  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-09 17:23:33.237  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-09 17:23:33.237  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:33.237  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 17:23:33.237  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:33.238  1037  1548 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:33.238  1037  1548 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:33.238  1037  1548 D NetworkManagementService: Removing idletimer
08-09 17:23:33.238  1037  1548 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:33.238  1880  1880 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:33.239  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 17:23:33.239  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:33.239  1037  1548 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-09 17:23:33.239  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:33.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:33.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:33.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:33.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:33.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:33.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:33.239  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:23:33.239  1037  1541 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:33.239  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:33.239  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:33.239  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:33.239  1037  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-09 17:23:33.242  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:33.242  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:33.242  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:33.242  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:33.242  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:33.242  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:33.242  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:33.242  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:33.242  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:33.242  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:33.242  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:33.243  1037  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-09 17:23:33.244  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:33.244  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:33.244  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:33.244  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:33.244  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:33.244  7054  7054 V io.jxco,re.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:33.244  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:33.244  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:33.244  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:33.244  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:33.244  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:33.244  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-09 17:23:33.244  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:33.244  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-09 17:23:33.244  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-09 17:23:33.245  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-09 17:23:33.245  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 17:23:33.245  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 17:23:33.245  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 17:23:33.245  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 17:23:33.245  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 17:23:33.245  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 17:23:33.248  3411  3411 V DownloadManager: DownloadService onDestroy
08-09 17:23:33.248  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:33.254  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 17:23:33.256  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:33.256  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:33.262  7237  7237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 17:23:33.264  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:33.266  7202  7202 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-09 17:23:33.266  7202  7202 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-09 17:23:33.266  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:33.269  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 17:23:33.274  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:33.278  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 17:23:33.278  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 17:23:33.278  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:33.279  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:33.279  7237  7237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 17:23:33.279  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:33.282  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:33.284  7202  7202 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-09 17:23:33.284  7202  7202 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 17:23:33.284  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:33.287  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:33.291  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:33.296  7237  7237 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:33.296  7237  7237 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:33.298  7237  7237 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 17:23:33.301  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 17:23:33.302  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 17:23:33.302  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:33.302  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:33.305  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 17:23:33.307  7306  7779 W FormManager: Network not available. Please check & try again.
08-09 17:23:33.309  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:33.311  7556  7556 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-09 17:23:33.311  7556  7556 I wpa_supplicant: monitor socket send errors count : 1
08-09 17:23:33.311  7556  7556 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1971-4\x00 that cannot receive messages
08-09 17:23:33.311  1037  7580 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-09 17:23:33.311  1037  7580 D WifiMonitor: Dropping event because (p2p0) is stopped
08-09 17:23:33.315  7306  7780 V FormManager: Network unavailable.
,08-09 17:23:33.319  7306  7780 V FormManager: Network unavailable.
08-09 17:23:33.335  7556  7556 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 17:23:33.336  7556  7556 W wpa_supplicant: USIM:  scard_deinit function
08-09 17:23:33.336  1037  1098 D Tethering: InitialState.processMessage what=4
08-09 17:23:33.336  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-09 17:23:33.336  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 17:23:33.336  1037  7580 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 17:23:33.336  1037  7580 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,08-09 17:23:33.336  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:33.336  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:33.336  1037  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-09 17:23:33.337  1037  1541 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=381076
08-09 17:23:33.337  1037  1541 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=381077
08-09 17:23:33.337  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=381077  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-09 17:23:33.337  1037  1541 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=381077  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-09 17:23:33.338  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:33.338  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:33.338  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 17:23:33.338  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 17:23:33.338  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 17:23:33.339  7178  7178 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 17:23:33.339  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-09 17:23:33.339  7178  7178 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 17:23:33.339  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-09 17:23:33.339  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 17:23:33.339  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 17:23:33.339  7178  7178 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 17:23:33.340  7178  7178 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 17:23:33.348  1037  7644 D DhcpStateMachine: StoppedState
08-09 17:23:33.348  1037  7644 D DhcpStateMachine: StoppedState{ when=-162ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:33.348  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-09 17:23:33.348  1037  1541 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-09 17:23:33.379  7556  7556 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-09 17:23:33.380  1037  7580 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-09 17:23:33.380  1037  7580 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-09 17:23:33.380  1037  7580 D WifiMonitor: Disconnecting from the supplicant, no more events
08-09 17:23:33.383  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,08-09 17:23:33.488  1971  1971 D WfdsService: Supplicant Connection state is changed : false
08-09 17:23:33.489  1971  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-09 17:23:33.489  1971  2295 D WfdsService: Set the WFDS Monitor: false
08-09 17:23:33.489  1971  2295 D WfdsMonitor: WFDS Monitor is stopped
,08-09 17:23:33.493  1037  1541 D WifiOffDelayIfNotUsed: stopMonitoring
08-09 17:23:33.493  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 17:23:33.493  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-09 17:23:33.493  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 17:23:33.494  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 17:23:33.496  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 17:23:33.498  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 17:23:33.500  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-09 17:23:33.502  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-09 17:23:33.502  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-09 17:23:33.502  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-09 17:23:33.503  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:33.503  2470  2470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:33.503  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 17:23:33.503  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:33.503  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:33.503  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:33.503  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:33.503  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:33.503  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:33.503  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:33.503  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 17:23:33.505  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:33.507  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:23:33.515  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:33.521  7505  7532 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-09 17:23:33.523  4700  7783 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 17:23:33.527  7202  7202 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-09 17:23:33.527  7202  7202 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 17:23:33.527  7202  7202 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:33.530  4700  7784 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 17:23:33.531  4700  7784 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 17:23:33.532  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-09 17:23:33.538  7306  7786 W FormManager: Network not available. Please check & try again.
08-09 17:23:33.539  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:33.547  7306  7787 V FormManager: Network unavailable.
,08-09 17:23:33.555  7306  7787 V FormManager: Network unavailable.
,08-09 17:23:33.720  1037  1407 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2a66a947 type 2 when 381457 com.google.android.gms} when 381457
,08-09 17:23:33.743  7237  7237 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-09 17:23:33.745  7237  7237 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9443
,08-09 17:23:33.885  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7744
08-09 17:23:33.887  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7747
,08-09 17:23:33.890  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7752
08-09 17:23:33.892  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7766
08-09 17:23:33.893  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7789
08-09 17:23:34.420  1037  2091 I ActivityManager: Killing 7254:com.lge.settings.easy/1000 (adj 15): empty #17
,08-09 17:23:34.453  1037  1578 W libprocessgroup: failed to open /acct/uid_1000/pid_7254/cgroup.procs: No such file or directory
,08-09 17:23:34.926  1037  1407 V AlarmManager: ELAPSED_WAKEUP set : Alarm{933e574 type 2 when 382661 com.google.android.gms} when 382661
,08-09 17:23:34.944   311  7799 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-09 17:23:34.948  1037  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-09 17:23:35.883  1037  1541 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1877400651] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 17:23:35.886  1037  1541 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1877400654] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 17:23:36.240  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:36.254  1037  1098 D Tethering: MasterInitialState.processMessage what=3
08-09 17:23:36.269  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:23:36.275  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:36.277  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:36.279  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.281  1037  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.284  1037  1098 D Tethering: MasterInitialState.processMessage what=3
,08-09 17:23:36.295  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:36.296  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:23:36.300  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:36.303  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 17:23:36.304  6774  7201 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-09 17:23:36.316  5818  5818 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-09 17:23:36.329  5818  5818 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-09 17:23:36.349  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:36.366  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 17:23:36.366  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.366  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 17:23:36.366  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-09 17:23:36.370  7361  7361 I AppUp4:CustModeStarterReceiver: onReceive
08-09 17:23:36.374  7361  7361 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e5c62d
08-09 17:23:36.374  7361  7361 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 17:23:36.374  7361  7361 D AppUp4:CustFacade: isPhone : true
08-09 17:23:36.374  7361  7361 D AppUp4:CustModeStarterReceiver: begin check event
08-09 17:23:36.374  7361  7361 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-09 17:23:36.379  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.379  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 17:23:36.381  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 17:23:36.386  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:36.394  7402  7402 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-09 17:23:36.406  4700  7800 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 17:23:36.407  1037  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.409  1037  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:36.410  1037  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:36.424  4700  7814 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:36.424  4700  7814 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 17:23:36.428  7402  7813 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:36.432  3307  3307 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 17:23:36.432  3307  3307 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.432  3307  3307 I LgeMiscReceiver: networkInfo.isConnected() = false
08-09 17:23:36.435  7306  7818 W FormManager: Network not available. Please check & try again.
08-09 17:23:36.438  7431  7431 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-09 17:23:36.438  7431  7431 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-09 17:23:36.441  7306  7820 V FormManager: Network unavailable.
08-09 17:23:36.452  7486  7486 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:36
08-09 17:23:36.454  7486  7486 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-09 17:23:36.454  7486  7486 D Weather.Utils: 2 : All the weather widget is gone.
,08-09 17:23:36.454  7486  7486 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 17:23:36.455  7486  7486 D WeatherAncestor: connectivity changed - connection : true
08-09 17:23:36.455  7486  7486 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@11cb70f3
08-09 17:23:36.455  7486  7486 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 17:23:36.455  7486  7486 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 17:23:36.455  7306  7820 V FormManager: Network unavailable.
08-09 17:23:36.455  7486  7486 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-09 17:23:36.455  7486  7486 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 17:23:36.455  7486  7486 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:36
08-09 17:23:36.470  1037  2005 I ActivityManager: Killing 7626:com.lge.bnr/1000 (adj 15): empty #17
,08-09 17:23:36.577  1037  1970 W libprocessgroup: failed to open /acct/uid_1000/pid_7626/cgroup.procs: No such file or directory
,08-09 17:23:36.610  6774  6774 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 17:23:36.613  6774  7201 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-09 17:23:36.637  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:23:36.650  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 17:23:36.650  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.651  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-09 17:23:36.651  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-09 17:23:36.654  7361  7361 I AppUp4:CustModeStarterReceiver: onReceive
08-09 17:23:36.659  7361  7361 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e5c62d
08-09 17:23:36.659  7361  7361 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 17:23:36.659  7361  7361 D AppUp4:CustFacade: isPhone : true
08-09 17:23:36.660  7361  7361 D AppUp4:CustModeStarterReceiver: begin check event
08-09 17:23:36.660  7361  7361 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-09 17:23:36.666  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.667  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 17:23:36.669  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 17:23:36.675  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:36.686  4700  7825 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 17:23:36.689  7402  7402 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-09 17:23:36.694  4700  7826 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.695  4700  7826 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 17:23:36.730  7402  7831 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 17:23:36.740  3307  3307 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-09 17:23:36.740  3307  3307 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:36.742  3307  3307 I LgeMiscReceiver: networkInfo.isConnected() = false
08-09 17:23:36.743  7306  7832 W FormManager: Network not available. Please check & try again.
08-09 17:23:36.747  7431  7431 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-09 17:23:36.747  7431  7431 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-09 17:23:36.762  7486  7486 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:36
08-09 17:23:36.763  7306  7834 V FormManager: Network unavailable.
,08-09 17:23:36.766  7486  7486 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-09 17:23:36.766  7486  7486 D Weather.Utils: 2 : All the weather widget is gone.
08-09 17:23:36.766  7306  7834 V FormManager: Network unavailable.
08-09 17:23:36.767  7486  7486 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 17:23:36.767  7486  7486 D WeatherAncestor: connectivity changed - connection : true
08-09 17:23:36.767  7486  7486 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@11cb70f3
08-09 17:23:36.769  7486  7486 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 17:23:36.769  7486  7486 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 17:23:36.769  7486  7486 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-09 17:23:36.769  7486  7486 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-09 17:23:36.769  7486  7486 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:23:36,
08-09 17:23:38.138  1037  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 17:23:38.151  1037  1933 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-09 17:23:38.162  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 17:23:38.162  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 17:23:38.162  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-09 17:23:38.166  1037  1098 D BluetoothManagerService: Message: 1
08-09 17:23:38.166  1037  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-09 17:23:38.187  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:38.187  1037  1540 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-09 17:23:38.196  1037  1098 D BluetoothManagerService: Message: 20
08-09 17:23:38.196  1037  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bb8e509:true
08-09 17:23:38.197  7288  7288 D BluetoothAdapterState: make
08-09 17:23:38.202  7288  7288 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-09 17:23:38.202  7288  7288 I bluedroid-qcom: init
,08-09 17:23:38.206  7288  7842 I BluetoothAdapterState: Entering OffState
08-09 17:23:38.206  7288  7288 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-09 17:23:38.207  7288  7288 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-09 17:23:38.207  7288  7288 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-09 17:23:38.207  7288  7288 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-09 17:23:38.207  7288  7288 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-09 17:23:38.209  7288  7288 I bluedroid-qcom: get_profile_interface socket
08-09 17:23:38.209  7288  7288 I bluedroid-qcom: get_profile_interface map_client
08-09 17:23:38.210  7288  7846 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-09 17:23:38.212  7288  7846 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-09 17:23:38.199  7845  7845 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:38.199  7845  7845 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-09 17:23:38.228  7845  7845 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-09 17:23:38.228  7845  7845 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-09 17:23:38.228  7845  7845 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-09 17:23:38.229  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-09 17:23:38.230  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-09 17:23:38.231  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-09 17:23:38.231  1037  1098 D BluetoothManagerService: Message: 40
08-09 17:23:38.231  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-09 17:23:38.232  7288  7305 I bluedroid-qcom: config_hci_snoop_log
08-09 17:23:38.233  1037  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-09 17:23:38.233  1037  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-09 17:23:38.239  7845  7845 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-09 17:23:38.241  1037  1541 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-09 17:23:38.242  1037  1541 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-09 17:23:38.243  7845  7845 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-09 17:23:38.243  7845  7845 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-09 17:23:38.248  7288  7842 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-09 17:23:38.251  7288  7846 D BluetoothAdapterProperties: Name is: G3
08-09 17:23:38.251  7288  7842 D BluetoothAdapterProperties: Setting state to 11
08-09 17:23:38.252  7288  7842 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-09 17:23:38.252  1037  1098 D BluetoothManagerService: Message: 60
08-09 17:23:38.253  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-09 17:23:38.253  1037  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-09 17:23:38.254  7288  7842 I LGBluetoothServiceJni: classInitNative: succeeds
08-09 17:23:38.259  1971  1971 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:38.259  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-09 17:23:38.267  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:38.268  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:38.269  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:38.272  7178  7178 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-09 17:23:38.277  7288  7288 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 17:23:38.279  7288  7288 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:38.279  7288  7288 V BluetoothPbapReceiver: ***********state = 11
,08-09 17:23:38.299  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 17:23:38.300  7288  7842 D BluetoothBondStateMachine: make
,08-09 17:23:38.309  7288  7842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:38.309  7288  7842 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-09 17:23:38.310  7288  7842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:38.310  7288  7842 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-09 17:23:38.310  7288  7842 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-09 17:23:38.311  7288  7859 I BluetoothBondStateMachine: StableState(): Entering Off State
08-09 17:23:38.314  7288  7842 E BluetoothAdapterService: File transfer profiles supported!!
,08-09 17:23:38.349  1037  2267 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7864 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-09 17:23:38.354  7288  7842 E BluetoothAdapterService: File transfer profiles supported!!
08-09 17:23:38.356  7288  7288 D HeadsetService: Received start request. Starting profile...
08-09 17:23:38.356  7288  7288 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 17:23:38.356  7288  7288 D LGBluetoothHfpAdapter: Version 1.6
08-09 17:23:38.359  7288  7288 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-09 17:23:38.360  7288  7288 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 17:23:38.360  7288  7288 D HeadsetStateMachine: make
08-09 17:23:38.361  7288  7842 E BluetoothAdapterService: File transfer profiles supported!!
08-09 17:23:38.367  7288  7842 E BluetoothAdapterService: File transfer profiles supported!!
,08-09 17:23:38.379  7288  7842 E BluetoothAdapterService: File transfer profiles supported!!
08-09 17:23:38.385  7288  7842 E BluetoothAdapterService: File transfer profiles supported!!
,08-09 17:23:38.391  7288  7288 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:23:38.391  7288  7288 D LgDataFeature: LgDataFeature() Constructor Done, null
08-09 17:23:38.394  7288  7288 D HeadsetStateMachine: max_hf_connections = 1
08-09 17:23:38.395  7288  7288 I bluedroid-qcom: get_profile_interface handsfree
08-09 17:23:38.395  7288  7842 E BluetoothAdapterService: File transfer profiles supported!!
08-09 17:23:38.396  7288  7288 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-09 17:23:38.397   316   316 V AudioPolicyService: registerClient() client 0xb558a520, uid 1002
08-09 17:23:38.397   316  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-09 17:23:38.397   316  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 17:23:38.397   316  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 17:23:38.398  7288  7288 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-09 17:23:38.398   316  1384 V AudioFlinger: registerClient() client 0xb55815e0, pid 7288
08-09 17:23:38.398   316  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:38.398   316  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 17:23:38.399  1880  4326 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:38.399  1880  4326 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 17:23:38.399  1606  4837 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:38.399  1606  4837 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 17:23:38.399  1037  1969 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:38.399  1037  1969 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 17:23:38.400   316  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:38.400   316  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 17:23:38.400  3307  3322 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:38.400  3307  3322 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 17:23:38.400  7288  7305 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:38.400  1606  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:38.400  1606  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 17:23:38.400  1880  1895 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:38.400  1880  1895 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 17:23:38.400  3307  3323 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:38.400  3307  3323 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 17:23:38.400  1037  1578 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:38.400  1037  1578 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 17:23:38.400  7288  7305 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-09 17:23:38.400  7288  7305 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:38.400  7288  7305 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-09 17:23:38.400  7288  7288 V ToneGenerator: Create Track: 0xb4928a80
08-09 17:23:38.400  7288  7288 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-09 17:23:38.400  7288  7288 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-09 17:23:38.401   316  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-09 17:23:38.401   316  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-09 17:23:38.401   316  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 17:23:38.401   316  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 17:23:38.401   316  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-09 17:23:38.401   316   316 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-09 17:23:38.401   316   316 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-09 17:23:38.401   31,6   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 17:23:38.401   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 17:23:38.401  7288  7288 V AudioSystem: getLatency() output 2, latency 50
08-09 17:23:38.401  7288  7288 V AudioSystem: getFrameCount() output 2, frameCount 960
08-09 17:23:38.401  7288  7288 V AudioTrack: createTrack_l() output 2 afLatency 50
08-09 17:23:38.401   316  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-09 17:23:38.401   316  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-09 17:23:38.401   316  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-09 17:23:38.401   316  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-09 17:23:38.401   316  1383 V AudioFlinger: createTrack() lSessionId: 22
08-09 17:23:38.402  7288  7288 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-09 17:23:38.402   316   316 V AudioFlinger: acquiring 22 from 7288, for 7288
08-09 17:23:38.402   316   316 V AudioFlinger:  added new entry for 22
08-09 17:23:38.403  7288  7288 V ToneGenerator: ToneGenerator INIT OK, time: 386154
08-09 17:23:38.403  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:38.403  7288  7879 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-09 17:23:38.403  7288  7879 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 17:23:38.404  7288  7879 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 17:23:38.404  7288  7879 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-09 17:23:38.404  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:38.404   316  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7288
08-09 17:23:38.404   316  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-09 17:23:38.404   316  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-09 17:23:38.405   316  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-09 17:23:38.405   316  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-09 17:23:38.405   316  1383 V voice   : voice_set_parameters: exit with code(0)
08-09 17:23:38.405   316  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-09 17:23:38.405   316  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-09 17:23:38.405   316  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-09 17:23:38.405   316  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-09 17:23:38.405   316  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-09 17:23:38.405   316  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,08-09 17:23:38.405  7288  7879 V ToneGenerator: ToneGenerator destructor
08-09 17:23:38.405  7288  7879 V ToneGenerator: stopTone
08-09 17:23:38.405  7288  7879 V ToneGenerator: Delete Track: 0xb4928a80
08-09 17:23:38.405  7288  7288 D A2dpService: Received start request. Starting profile...
08-09 17:23:38.406  7288  7288 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 17:23:38.406  7288  7288 V Avrcp   : make
08-09 17:23:38.407  7288  7288 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-09 17:23:38.407  7288  7288 I bluedroid-qcom: get_profile_interface avrcp
08-09 17:23:38.408  7288  7879 V AudioTrack: ~AudioTrack, releasing session id from 7288 on behalf of 7288
08-09 17:23:38.409   316  1383 V AudioPolicyService: AudioCommandThread() adding release output 2
08-09 17:23:38.409   316  1384 V AudioFlinger: releasing 22 from 7288 for 7288
,08-09 17:23:38.409   316  1383 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-09 17:23:38.409   316  1384 V AudioFlinger:  decremented refcount to 0
08-09 17:23:38.409   316  1383 V AudioFlinger: PlaybackThread::Track destructor
08-09 17:23:38.409   316  1384 V AudioFlinger: purging stale effects
08-09 17:23:38.409   316  1260 V AudioPolicyService: AudioCommandThread() waking up
08-09 17:23:38.409   316  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-09 17:23:38.409   316  1383 V AudioFlinger: removeClient_l() pid 7288, calling pid 316
08-09 17:23:38.409   316  1260 V AudioPolicyManager: releaseOutput() 2
08-09 17:23:38.409   316  1260 V AudioPolicyService: AudioCommandThread() going to sleep
,08-09 17:23:38.410  1037  1578 W Process : Unable to open /proc/7884/status
,08-09 17:23:38.413  7288  7288 V AudioManager: registerRemoteController: size of Media player list: 0
,08-09 17:23:38.415  7288  7288 E AudioManager: No RCC entry present to update
08-09 17:23:38.415  7288  7288 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-09 17:23:38.415  7288  7842 V LGMDMManager: Create singleton instance
08-09 17:23:38.417  7288  7842 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-09 17:23:38.417  7288  7288 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-09 17:23:38.418  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-09 17:23:38.418  7288  7288 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-09 17:23:38.422  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-09 17:23:38.538  7864  7864 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-09 17:23:38.538  7864  7864 W LG Account v2.2: No ProfileInfo entries
08-09 17:23:38.539  7864  7864 I LG Account v2.2: isEnabled: false
08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]Country: EU
08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]Operator: OPEN
08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]Ranking support: false
08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]Comfort support: false
08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]Accessory: true
08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]Health device: true
08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]Extra Pedometer: false
08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]Blood glucose device: false
08-09 17:23:38.539  7864  7864 I Feature : [Lifetracker]Device Number: 3
08-09 17:23:38.548  1037  1933 V SIM_STK : Menu title from STK is T-Mobile
08-09 17:23:38.548  1037  1933 V SIM_STK : Menu title from STK is T-Mobile
08-09 17:23:38.550  7178  7178 D BluetoothPermissionRequest: onReceive
08-09 17:23:38.553  7178  7178 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 17:23:38.617  1037  2052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-09 17:23:38.624  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-09 17:23:38.628  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-09 17:23:38.629  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-09 17:23:38.629  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-09 17:23:38.629  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-09 17:23:38.629  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 17:23:38.629  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-09 17:23:38.629  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-09 17:23:38.629  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-09 17:23:38.629  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 17:23:38.629  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-09 17:23:38.629  7288  7288 I BluetoothA2dpServiceJni: classInitNative
08-09 17:23:38.629  7288  7288 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-09 17:23:38.630  7288  7288 D A2dpStateMachine: make
08-09 17:23:38.632  7288  7288 I bluedroid-qcom: get_profile_interface a2dp
,08-09 17:23:38.633  7288  7892 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-09 17:23:38.635  7288  7288 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-09 17:23:38.635  7288  7288 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-09 17:23:38.636  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:38.636  7288  7891 D A2dpStateMachine: Enter Disconnected: -2
08-09 17:23:38.637  7288  7288 I BluetoothHidServiceJni: classInitNative: succeeds
08-09 17:23:38.644  7288  7288 D HidService: Received start request. Starting profile...
08-09 17:23:38.644  7288  7288 I bluedroid-qcom: get_profile_interface hidhost
08-09 17:23:38.644  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:38.645  7288  7288 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 17:23:38.647  7288  7288 D HealthService: Received start request. Starting profile...
,08-09 17:23:38.653  7288  7288 I bluedroid-qcom: get_profile_interface health
08-09 17:23:38.653  7288  7288 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-09 17:23:38.654  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:38.656  7288  7288 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-09 17:23:38.660  7288  7288 D PanService: Received start request. Starting profile...
,08-09 17:23:38.660  7288  7288 D BluetoothPanServiceJni: initializeNative(L110): pan
08-09 17:23:38.660  7288  7288 I bluedroid-qcom: get_profile_interface pan
08-09 17:23:38.674  7288  7288 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-09 17:23:38.674  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:38.678  7288  7288 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-09 17:23:38.691  7288  7288 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 17:23:38.691  7288  7288 D BtGatt.GattService: Received start request. Starting profile...
08-09 17:23:38.692  7288  7288 D BtGatt.GattService: start()
08-09 17:23:38.692  7288  7288 I bluedroid-qcom: get_profile_interface gatt
08-09 17:23:38.692  7288  7288 D BtGatt.AdvertiseManager: advertise manager created
08-09 17:23:38.706  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
,08-09 17:23:38.707  7288  7288 D HeadsetStateMachine: Proxy object connected
,08-09 17:23:38.709  7288  7288 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-09 17:23:38.710  7288  7288 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-09 17:23:38.715  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:38.716  7288  7288 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-09 17:23:38.718  7288  7288 V BluetoothMapService: BluetoothMapBinder()
,08-09 17:23:38.720  7288  7288 D BluetoothMapService: Received start request. Starting profile...
08-09 17:23:38.720  7288  7288 D BluetoothMapService: start()
08-09 17:23:38.727  7288  7288 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-09 17:23:38.728  7288  7288 D BluetoothMapEmailAppObserver: createReceiver()
08-09 17:23:38.729  7288  7288 D BluetoothMapEmailAppObserver: initObservers()
08-09 17:23:38.730  7288  7288 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-09 17:23:38.739  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
,08-09 17:23:38.745  7288  7288 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 17:23:38.746  7288  7879 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-09 17:23:38.747  7288  7879 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 17:23:38.748  7288  7879 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-09 17:23:38.750  7288  7288 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 17:23:38.754  7288  7288 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-09 17:23:38.759  7288  7288 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 17:23:38.759  7288  7288 V PanService: [BTUI] SIM Extra State :ABSENT
08-09 17:23:38.763  7288  7288 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 17:23:38.767  7288  7288 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-09 17:23:38.767  7288  7288 V BluetoothMapService: Handler(): got msg=1
08-09 17:23:38.768  7288  7842 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-09 17:23:38.768  7288  7842 I bluedroid-qcom: enable
08-09 17:23:38.769  7288  7842 I bt_hci_bdroid: init
08-09 17:23:38.771  7288  7902 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-09 17:23:38.771  7288  7902 I bt-btu  : btu_task pending for preload complete event
08-09 17:23:38.772  7288  7288 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:38.773  7288  7842 I bt_vendor: bt-vendor : init
08-09 17:23:38.773  7288  7842 I bt_vendor: bt-vendor : get_bt_soc_type
08-09 17:23:38.773  7288  7842 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-09 17:23:38.773  7288  7842 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-09 17:23:38.773  7288  7842 D bt_userial_mct: userial_init
08-09 17:23:38.774  7288  7842 D bt_hci_bdroid: set_power 1
08-09 17:23:38.775  7288  7842 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-09 17:23:38.775  7288  7842 I bt_vendor: Starting hciattach daemon
08-09 17:23:38.775  7288  7842 I bt_vendor: try to set true
08-09 17:23:38.775  7288  7288 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 17:23:38.775  7288  7288 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 17:23:38.775  7288  7288 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 17:23:38.775  7288  7288 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:38.775  7288  7288 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-09 17:23:38.759  7905  7905 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:38.759  7905  7905 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:38.807  7906  7906 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-09 17:23:38.855  1037  2051 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7910 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-09 17:23:38.893  7929  7929 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-09 17:23:38.905  7930  7930 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-09 17:23:38.928  7932  7932 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-09 17:23:38.939  7933  7933 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-09 17:23:38.942  7910  7910 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 17:23:38.950  7934  7934 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-09 17:23:38.961  7935  7935 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-09 17:23:38.965  1037  1970 I ActivityManager: Killing 7202:com.lge.sync/1000 (adj 15): empty #17
,08-09 17:23:38.984  7937  7937 I libmdmdetect: ESOC framework not supported
08-09 17:23:38.985  7937  7937 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-09 17:23:38.993  7937  7937 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-09 17:23:38.993  7937  7937 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-09 17:23:38.993  7937  7937 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-09 17:23:38.993  7937  7937 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-09 17:23:38.993  7937  7937 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-09 17:23:38.993  7937  7937 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-09 17:23:38.994  7937  7937 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-09 17:23:39.001  1037  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_7202/cgroup.procs: No such file or directory
,08-09 17:23:39.037  7937  7938 E QC-QMI  : qmi_client [7937] 14: failed to locate client data
08-09 17:23:39.037   480   480 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-09 17:23:39.038   480   480 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-09 17:23:39.091  7939  7939 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-09 17:23:39.119  7940  7940 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-09 17:23:39.177  7288  7842 I bt_vendor: bluetooth satus is on
08-09 17:23:39.177  7288  7842 D bt_hci_bdroid: preload
08-09 17:23:39.177  7288  7904 D bt_userial_mct: userial_open(port:0)
08-09 17:23:39.178  7288  7904 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-09 17:23:39.181  7288  7904 I bt_vendor: Done intiailizing UART
,08-09 17:23:39.183  7288  7904 I bt_vendor: Done intiailizing UART
,08-09 17:23:39.183  7288  7904 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-09 17:23:39.183  7288  7904 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-09 17:23:39.183  7288  7942 D bt_userial_mct: Entering userial_read_thread()
08-09 17:23:39.184  7288  7902 I bt-btu  : btu_task received preload complete event
08-09 17:23:39.184  7288  7902 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-09 17:23:39.184  7288  7902 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-09 17:23:39.187  7288  7902 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-09 17:23:39.191  7288  7902 I         : BTE_InitTraceLevels -- TRC_HCI
08-09 17:23:39.191  7288  7902 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_AVDT
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_AVRC
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_A2D
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 17:23:39.192  7288  7902 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 17:23:39.281  7288  7902 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-09 17:23:39.281  7288  7902 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014b061 
08-09 17:23:39.281  7288  7902 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014b061 
,08-09 17:23:39.299  7288  7846 E bt-btif : Calling BTA_HhEnable
,08-09 17:23:39.299  7288  7846 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-09 17:23:39.299  7288  7846 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-09 17:23:39.301  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-09 17:23:39.302  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-09 17:23:39.302  7288  7846 D BluetoothAdapterProperties: Name is: G3
,08-09 17:23:39.304  7288  7902 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-09 17:23:39.304  7288  7902 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-09 17:23:39.304  7288  7846 D BluetoothAdapterProperties: Scan Mode:20
08-09 17:23:39.304  7288  7902 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-09 17:23:39.304  7288  7846 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 17:23:39.305  7288  7846 D bt_hci_bdroid: postload
08-09 17:23:39.305  7288  7902 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-09 17:23:39.305  7288  7904 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 17:23:39.305  7288  7902 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-09 17:23:39.306  7288  7846 D bte_conf: Device ID record 1 : primary
08-09 17:23:39.306  7288  7846 D bte_conf:   vendorId            = 00c4
08-09 17:23:39.306  7288  7846 D bte_conf:   vendorIdSource      = 0001
08-09 17:23:39.306  7288  7846 D bte_conf:   product             = 13a1
08-09 17:23:39.306  7288  7846 D bte_conf:   version             = 1000
08-09 17:23:39.306  7288  7846 D bte_conf:   clientExecutableURL = 
08-09 17:23:39.306  7288  7846 D bte_conf:   serviceDescription  = 
08-09 17:23:39.306  7288  7846 D bte_conf:   documentationURL    = 
08-09 17:23:39.306  7288  7846 D bte_conf: bte_load_did_conf no section named DID2.
08-09 17:23:39.307  7288  7902 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-09 17:23:39.309  7288  7842 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-09 17:23:39.309  7288  7842 D BluetoothAdapterProperties: ScanMode =  20
08-09 17:23:39.309  7288  7842 D BluetoothAdapterProperties: State =  11
08-09 17:23:39.309  7288  7842 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-09 17:23:39.310  7288  7842 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-09 17:23:39.310  7288  7842 D BluetoothAdapterProperties: Setting state to 12
08-09 17:23:39.310  7288  7842 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-09 17:23:39.310  7288  7846 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-09 17:23:39.299  7947  7947 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:39.299  7947  7947 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:39.311  1037  1098 D BluetoothManagerService: Message: 60
08-09 17:23:39.311  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-09 17:23:39.312  1037  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-09 17:23:39.312  7288  7846 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-09 17:23:39.313  1880  2571 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 17:23:39.314  7288  7842 I BluetoothAdapterState: Entering On State
,08-09 17:23:39.321  7288  7842 D LGBluetoothServiceAdapter: [BTUI] OnState
08-09 17:23:39.322  7288  7842 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-09 17:23:39.322  7288  7842 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-09 17:23:39.324  7288  7842 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-09 17:23:39.332  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:39.332  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:39.332  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:39.332  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:39.332  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:39.332  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:39.332  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:39.332  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 17:23:39.337  7288  7904 D bt_hci_bdroid: Used up Tx Cmd credits
,08-09 17:23:39.338  7288  7846 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 17:23:39.338  7288  7846 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-09 17:23:39.339  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:39.342  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:39.342  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:39.342  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:39.342  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:39.342  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:39.342  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:39.342  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:39.342  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:39.344  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:39.349  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:39.349  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:39.349  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:39.349  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:39.349  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:39.349  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:39.349  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:39.349  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 17:23:39.352  7288  7904 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 17:23:39.355  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:39.355  7178  7196 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 17:23:39.357  1037  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 17:23:39.359  7288  7904 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 17:23:39.359  1880  4325 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 17:23:39.360  1037  1037 D BluetoothHeadset: Proxy object connected
08-09 17:23:39.361  1880  1880 D BluetoothHeadset: Proxy object connected
08-09 17:23:39.363  7288  7942 E bt_mct  : hci lib postload completed
,08-09 17:23:39.365  7288  7842 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-09 17:23:39.368  1880  1880 D BluetoothHeadset: Proxy object connected
08-09 17:23:39.369  1880  1896 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 17:23:39.371  1880  1880 D BluetoothHeadset: Proxy object connected
08-09 17:23:39.371  1037  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 17:23:39.372  7288  7902 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:39.372  7288  7902 W bt-smp  : Plain text(LSB ~ MSB) = 4b 1e 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:39.372  7288  7902 W bt-smp  : Encrypted text(LSB ~ MSB) = d8 ff 85 99 c8 cf 21 7c 88 88 ad 4a 03 d4 f7 ee 
08-09 17:23:39.372  7288  7902 W bt-btm  : Stopping oneshot timer
08-09 17:23:39.375  7178  7197 D BluetoothPan: onBluetoothStateChange on: true
,08-09 17:23:39.375  7178  7197 D BluetoothPan: onBluetoothStateChange call bindService
08-09 17:23:39.376  1037  1037 D BluetoothA2dp: Proxy object connected
,08-09 17:23:39.382  7178  7196 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 17:23:39.385  7178  7197 D BluetoothMap: onBluetoothStateChange: up=true
08-09 17:23:39.387  1037  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-09 17:23:39.387  1037  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-09 17:23:39.395  1971  1971 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:39.396  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 17:23:39.399  7952  7952 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-09 17:23:39.401  1971  2177 D LGBluetoothAPIService: Message: 1
08-09 17:23:39.401  1971  2177 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-09 17:23:39.402  7178  7178 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 17:23:39.402  7178  7178 D PanProfile: Bluetooth service connected
08-09 17:23:39.405  7054  7054 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-09 17:23:39.406  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:39.407  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:39.409  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:39.421  1971  2177 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-09 17:23:39.423  7288  7902 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:39.423  7288  7902 W bt-smp  : Plain text(LSB ~ MSB) = 71 6a 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:39.423  7288  7902 W bt-smp  : Encrypted text(LSB ~ MSB) = fa fe 71 70 3c 05 f4 69 e1 74 e2 c4 0f 55 3f 5f 
08-09 17:23:39.423  7288  7902 W bt-btm  : Stopping oneshot timer
08-09 17:23:39.426  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-09 17:23:39.427  1037  1098 D BluetoothManagerService: Message: 40
08-09 17:23:39.427  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-09 17:23:39.427  7178  7178 D LocalBluetoothProfileManager: Adding local A2DP profile
08-09 17:23:39.430  7288  7288 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:39.430  7288  7288 D BluetoothMapService: STATE_ON
08-09 17:23:39.430  1037  1098 D BluetoothManagerService: Message: 30
08-09 17:23:39.432  7288  7288 D LGBluetoothAPIServer: [BTUI] onCreate()
08-09 17:23:39.432  7288  7288 D LGBluetoothAPIServer: [BTUI] onBind()
,08-09 17:23:39.435  1971  1971 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-09 17:23:39.435  1971  2177 D LGBluetoothAPIService: Message: 100
08-09 17:23:39.435  1971  2177 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-09 17:23:39.435  7178  7178 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-09 17:23:39.438  1037  1098 D BluetoothManagerService: Message: 30
08-09 17:23:39.440  7288  7902 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:39.440  7288  7902 W bt-smp  : Plain text(LSB ~ MSB) = 06 ef 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:39.440  7288  7902 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f 80 21 b1 ad a5 ee 78 87 07 df 8b 21 4c ae 66 
08-09 17:23:39.440  7288  7902 W bt-btm  : Stopping oneshot timer
08-09 17:23:39.443  7178  7178 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-09 17:23:39.444  7178  7178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-09 17:23:39.447  7178  7178 D BluetoothInputDevice: Proxy object connected
08-09 17:23:39.447  7178  7178 D HidProfile: Bluetooth service connected
08-09 17:23:39.449  7288  7902 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:39.449  7288  7902 W bt-smp  : Plain text(LSB ~ MSB) = 22 f7 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:39.449  7288  7902 W bt-smp  : Encrypted text(LSB ~ MSB) = 70 88 4a f2 22 37 de a7 28 99 91 d0 e7 c5 11 99 
08-09 17:23:39.449  7288  7902 W bt-btm  : Stopping oneshot timer
08-09 17:23:39.449  7178  7178 D BluetoothMap: Proxy object connected
08-09 17:23:39.449  7178  7178 D MapProfile: Bluetooth service connected
08-09 17:23:39.449  7178  7178 D BluetoothMap: getConnectedDevices()
08-09 17:23:39.450  7288  7883 V BluetoothMapService: getConnectedDevices()
08-09 17:23:39.451  7178  7178 D BluetoothA2dp: Proxy object connected
08-09 17:23:39.452  7178  7178 D A2dpProfile: Bluetooth service connected
08-09 17:23:39.452  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:39.453  7288  7288 V BluetoothPbapService: Pbap Service onCreate
08-09 17:23:39.453  7288  7288 V BluetoothPbapService: Starting PBAP service
08-09 17:23:39.453  7178  7178 D BluetoothHeadset: Proxy object connected
08-09 17:23:39.454  7178  7178 D HeadsetProfile: Bluetooth service connected
08-09 17:23:39.454  7288  7288 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-09 17:23:39.455  7288  7288 V BluetoothPbapService: Pbap Service onBind
08-09 17:23:39.456  7288  7288 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:39.456  7288  7288 V BluetoothPbapService: state: 12
08-09 17:23:39.456  7288  7288 V BluetoothMapService: Handler(): got msg=1
08-09 17:23:39.457  7288  7288 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-09 17:23:39.457  7288  7288 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 17:23:39.457  7288  7288 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:39.457  7288  7288 V BluetoothPbapReceiver: ***********state = 12
08-09 17:23:39.458  7288  7964 D BluetoothMapMasInstance: MAS initSocket()
,08-09 17:23:39.459  7288  7964 D BluetoothMapMasInstance:   masId = 00
08-09 17:23:39.459  7288  7964 D BluetoothMapMasInstance:   msgTypes = 0e
08-09 17:23:39.459  7288  7964 D BluetoothMapMasInstance:   masName = SMS/MMS
08-09 17:23:39.459  7288  7964 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-09 17:23:39.460  1037  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:39.461  7288  7902 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:39.461  7288  7902 W bt-smp  : Plain text(LSB ~ MSB) = 38 da 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:39.461  7288  7902 W bt-smp  : Encrypted text(LSB ~ MSB) = 8b de a6 51 9a 8e 72 30 e0 98 1f e4 29 96 ba 22 
08-09 17:23:39.461  7288  7902 W bt-btm  : Stopping oneshot timer
08-09 17:23:39.461  7288  7288 V BluetoothPbapService: Handler(): got msg=1
08-09 17:23:39.462  7288  7964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 17:23:39.463  7288  7288 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-09 17:23:39.464  7288  7966 V BluetoothPbapService: Pbap Service initSocket
08-09 17:23:39.464  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 17:23:39.465  2230  2230 D c       : Getting all permits...
08-09 17:23:39.465  2230  2230 D a       : Opening database...
08-09 17:23:39.466  1037  2091 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:39.467  7288  7964 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-09 17:23:39.467  7288  7964 V BluetoothMapMasInstance: Succeed to create listening socket 
08-09 17:23:39.467  7288  7964 D BluetoothMapMasInstance: Accepting socket connection...
08-09 17:23:39.468  7288  7846 D BluetoothAdapterProperties: Scan Mode:21
08-09 17:23:39.468  7288  7846 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-09 17:23:39.468  7178  7178 D DockEventReceiver: finishStartingService: stopping service
08-09 17:23:39.469  7178  7178 D BluetoothPbap: Proxy object connected
,08-09 17:23:39.470  7178  7178 D PbapServerProfile: Bluetooth service connected
08-09 17:23:39.470  7288  7966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 17:23:39.471  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:39.472  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:39.473  2230  2230 D a       : Opening database auth.proximity.permit_store...
08-09 17:23:39.475  2230  2230 D a       : Closing database...
08-09 17:23:39.475  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:39.476  7288  7966 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-09 17:23:39.476  7288  7966 V BluetoothPbapService: Succeed to create listening socket 
,08-09 17:23:39.476  7288  7966 V BluetoothPbapService: Accepting socket connection...
08-09 17:23:39.487  7178  7178 D BluetoothPermissionRequest: onReceive
,08-09 17:23:39.490  7178  7178 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-09 17:23:39.491  7178  7178 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 17:23:39.494  7288  7288 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-09 17:23:39.495  7288  7288 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-09 17:23:39.500  7288  7288 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-09 17:23:39.518  7288  7288 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-09 17:23:39.518  7288  7288 V BtOppService: onCreate
,08-09 17:23:39.522  7288  7288 V BluetoothOppNotification: send message
08-09 17:23:39.526  7288  7288 V BtOppService: Starting RfcommListener
08-09 17:23:39.530  7288  7288 D BluetoothOppPreference: Dumping Names:  
08-09 17:23:39.530  7288  7288 D BluetoothOppPreference: {}
08-09 17:23:39.530  7288  7288 D BluetoothOppPreference: Dumping Channels:  
08-09 17:23:39.530  7288  7288 D BluetoothOppPreference: {}
08-09 17:23:39.531  7288  7288 V BtOppService: onStartCommand
08-09 17:23:39.534  7288  7288 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-09 17:23:39.536  7288  7288 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-09 17:23:39.537  7288  7972 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-09 17:23:39.539  7288  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 17:23:39.540  7288  7288 V BluetoothOppNotification: new notify threadi!
08-09 17:23:39.541  7288  7969 V BtOppService: Deleted complete outbound shares, number =  0
08-09 17:23:39.541  7288  7288 V BluetoothOppNotification: send delay message
08-09 17:23:39.542  7288  7288 V BtOppService: start RfcommListener
08-09 17:23:39.544  7288  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-09 17:23:39.550  7288  7288 V BtOppService: RfcommListener started
08-09 17:23:39.552  7288  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2756256c on behalf of 
08-09 17:23:39.552  7288  7974 V BtOppRfcommListener: Starting RFCOMM listener....
08-09 17:23:39.553  1037  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 17:23:39.554  7288  7974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 17:23:39.555  7288  7974 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-09 17:23:39.555  7288  7974 V BtOppRfcommListener: Started RFCOMM listener....
08-09 17:23:39.555  7288  7974 I BtOppRfcommListener: Accept thread started.
08-09 17:23:39.555  7288  7974 V BtOppRfcommListener: Accepting connection...
08-09 17:23:39.558  7288  7969 V BtOppService: Deleted complete inbound failed shares, number = 0
08-09 17:23:39.558  7288  7969 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-09 17:23:39.560  7288  7969 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c9d0735 on behalf of 
08-09 17:23:39.561  7288  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f0c67ca on behalf of 
08-09 17:23:39.561  7288  7973 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-09 17:23:39.561  7288  7972 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-09 17:23:39.563  7288  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-09 17:23:39.564  7288  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23ed3b on behalf of 
08-09 17:23:39.565  7288  7973 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-09 17:23:39.567  7288  7973 V BluetoothOppNotification: outbound notification was removed.
08-09 17:23:39.567  7288  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-09 17:23:39.569  7288  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38362c58 on behalf of 
08-09 17:23:39.569  7288  7973 V BluetoothOppNotification: inbound: succ-0  fail-0
08-09 17:23:39.571  7288  7973 V BluetoothOppNotification: inbound notification was removed.
08-09 17:23:39.571  7288  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-09 17:23:39.572  7288  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14a3e1b1 on behalf of 
08-09 17:23:39.577  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:39.577  7288  7288 V BluetoothFtpService: Ftp Service onCreate
08-09 17:23:39.577  7288  7288 I BluetoothFtpService: Ftp Service onCreate
08-09 17:23:39.578  7288  7288 V BluetoothFtpService: Ftp Service onStartCommand
08-09 17:23:39.578  7288  7288 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:39.578  7288  7288 V BluetoothFtpService: Starting Listening on sockets
08-09 17:23:39.578  7288  7288 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 17:23:39.578  7288  7288 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 17:23:39.578  7288  7288 V BluetoothSapReceiver: SapReceiver onReceive 
,08-09 17:23:39.578  7288  7288 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED,
08-09 17:23:39.579  7288  7288 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-09 17:23:39.579  7288  7288 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-09 17:23:39.581  7288  7288 V BtOppService: ContentObserver received notification
08-09 17:23:39.581  7288  7288 V BtOppService: ContentObserver received notification,
08-09 17:23:39.581  7288  7288 V BluetoothFtpService: Handler(): got msg=1
08-09 17:23:39.581  7288  7288 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-09 17:23:39.582  7288  7288 V BluetoothFtpService: Ftp Service initSocket
08-09 17:23:39.585  7288  7975 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true,
08-09 17:23:39.585  7288  7975 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 17:23:39.586  7288  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14da2217 on behalf of 
08-09 17:23:39.587  7288  7975 V BluetoothOppNotification: update too frequent, put in queue
08-09 17:23:39.588  7288  7975 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true,
08-09 17:23:39.589  1037  2267 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:39.589  7288  7288 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 17:23:39.590  7288  7288 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-09 17:23:39.591  7288  7288 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-09 17:23:39.592  7288  7976 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-09 17:23:39.606  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
,08-09 17:23:39.606  7288  7288 V BluetoothSapService: Sap Service onCreate
08-09 17:23:39.608  7288  7288 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:39.608  7288  7288 V BluetoothSapService: state: 12
08-09 17:23:39.609  7288  7288 V BluetoothSapService: Starting SAP server process
08-09 17:23:39.610  7288  7288 V BluetoothSapService: SAP Service startRfcommListenerThread
08-09 17:23:39.599  7977  7977 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:39.599  7977  7977 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:39.614  7288  7978 V BluetoothSapService: Sap Service initRfcommSocket
08-09 17:23:39.616  1037  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:39.619  7288  7978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 17:23:39.624  7977  7977 V BT_SAP  : Event pipe created
08-09 17:23:39.624  7977  7977 V BT_SAP  : create_server_socket qcom.sap.server
08-09 17:23:39.624  7977  7977 V BT_SAP  : created socket fd 6
08-09 17:23:39.626  7288  7978 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-09 17:23:39.626  7288  7978 V BluetoothSapService: Succeed to create listening socket 
08-09 17:23:39.626  7288  7978 V BluetoothSapService: Accepting socket connection...
08-09 17:23:39.988  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7847
08-09 17:23:39.990  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7850
08-09 17:23:39.992  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7954
08-09 17:23:39.992  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7955
,08-09 17:23:39.997  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7962
08-09 17:23:39.997  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7965
08-09 17:23:39.999  1037  1094 W ProcessCpuTracker: Skipping unknown process pid 7982
08-09 17:23:40.056  1606  1606 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-09 17:23:40.121  1037  1471 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-09 17:23:40.169  1037  1094 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7988 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-09 17:23:40.184  2092  2092 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-09 17:23:40.204  1037  1037 D administrator: Handling package changes for user 0
08-09 17:23:40.207  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-09 17:23:40.208  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-09 17:23:40.224  2092  2092 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 17:23:40.243  7988  7988 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-09 17:23:40.311  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-09 17:23:40.311  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-09 17:23:40.317  7988  7988 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:23:40.317  7988  7988 D LgDataFeature: LgDataFeature() Constructor Done, null
08-09 17:23:40.349  1037  1093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 17:23:40.355  1037  1093 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-09 17:23:40.362  2092  2092 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-09 17:23:40.363  2470  2470 V GmsNetworkLocationProvi: DISABLE
,08-09 17:23:40.390  2470  2470 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-09 17:23:40.429  7988  8033 I Babel   : MmsConfig: mnc/mcc: 0/0
08-09 17:23:40.429  7988  8033 I Babel   : MmsConfig.loadMmsSettings
,08-09 17:23:40.432  7988  8033 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-09 17:23:40.432  7988  8033 I Babel   : MmsConfig.loadFromDatabase
,08-09 17:23:40.446  7988  8033 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-09 17:23:40.446  7988  8033 I Babel   : MmsConfig.loadFromResources
08-09 17:23:40.456  7988  8033 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-09 17:23:40.456  7988  8033 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-09 17:23:40.459  1037  1037 I art     : Explicit concurrent mark sweep GC freed 83994(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.423ms total 71.725ms
08-09 17:23:40.459  1037  1093 D LocationProviderProxy: applying state to connected service
,08-09 17:23:40.474  7988  8031 W AudioCapabilities: Unsupported mime audio/evrc
08-09 17:23:40.475  7988  8031 W AudioCapabilities: Unsupported mime audio/qcelp
08-09 17:23:40.476  7988  8031 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-09 17:23:40.484  7988  7988 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:40.491  7988  8031 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-09 17:23:40.492  7988  8031 W AudioCapabilities: Unsupported mime audio/qcelp
,08-09 17:23:40.492  7988  8031 W AudioCapabilities: Unsupported mime audio/evrc
08-09 17:23:40.505  7988  8031 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-09 17:23:40.507  1821  8035 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-09 17:23:40.507  7361  7361 I AppUp4:CustModeStarterReceiver: onReceive
08-09 17:23:40.507  1821  8035 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-09 17:23:40.509  7988  8031 W VideoCapabilities: Unsupported mime video/divx
08-09 17:23:40.513  7361  7361 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e5c62d
08-09 17:23:40.513  7361  7361 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 17:23:40.513  7361  7361 D AppUp4:CustFacade: isPhone : true
08-09 17:23:40.513  7361  7361 D AppUp4:CustModeStarterReceiver: begin check event
08-09 17:23:40.513  7361  7361 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-09 17:23:40.513  7988  8031 W VideoCapabilities: Unsupported mime video/divx311
,08-09 17:23:40.522  7988  8031 W VideoCapabilities: Unsupported mime video/divx4
08-09 17:23:40.525  1821  5180 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-09 17:23:40.528  7988  8031 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-09 17:23:40.543  7288  7288 V BluetoothOppNotification: new notify threadi!
08-09 17:23:40.543  7288  7288 V BluetoothOppNotification: send delay message
08-09 17:23:40.545  7288  8038 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-09 17:23:40.545  7288  8038 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e54c8b3 on behalf of 
08-09 17:23:40.546  7288  8038 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-09 17:23:40.547  7288  8038 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-09 17:23:40.548  7988  8031 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-09 17:23:40.548  7288  8038 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2cb22e70 on behalf of 
08-09 17:23:40.551  7288  8038 V BluetoothOppNotification: outbound: succ-0  fail-0
08-09 17:23:40.552  1037  1915 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8039 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-09 17:23:40.554  7288  8038 V BluetoothOppNotification: outbound notification was removed.
08-09 17:23:40.554  7288  8038 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-09 17:23:40.559  7288  8038 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ca415e9 on behalf of 
,08-09 17:23:40.559  7288  8038 V BluetoothOppNotification: inbound: succ-0  fail-0
08-09 17:23:40.560  1037  2052 I ActivityManager: Killing 6897:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-09 17:23:40.561  7288  8038 V BluetoothOppNotification: inbound notification was removed.
08-09 17:23:40.561  7288  8038 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-09 17:23:40.565  7988  8031 W AudioCapabilities: Unsupported mime audio/eac3
08-09 17:23:40.569  7288  8038 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bc0826e on behalf of 
08-09 17:23:40.569  7988  8031 W AudioCapabilities: Unsupported mime audio/ac3
08-09 17:23:40.570  7988  8031 W AudioCapabilities: Unsupported mime audio/g726
08-09 17:23:40.570  7988  8031 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-09 17:23:40.572  7988  8031 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-09 17:23:40.573  7988  8031 W AudioCapabilities: Unsupported mime audio/adpcm
08-09 17:23:40.575  7988  8031 W VideoCapabilities: Unsupported mime video/theora
08-09 17:23:40.579  7988  8031 W VideoCapabilities: Unsupported mime video/mjpg
08-09 17:23:40.584  7237  7237 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-09 17:23:40.585  7237  7237 W System.err: android.os.DeadObjectException
08-09 17:23:40.585  7237  7237 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-09 17:23:40.585  7237  7237 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-09 17:23:40.585  7237  7237 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-09 17:23:40.585  7237  7237 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-09 17:23:40.585  7237  7237 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-09 17:23:40.585  7237  7237 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-09 17:23:40.585  7237  7237 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 17:23:40.585  7237  7237 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 17:23:40.585  7237  7237 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 17:23:40.585  7237  7237 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 17:23:40.585  7237  7237 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 17:23:40.585  7237  7237 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 17:23:40.585  7237  7237 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 17:23:40.585  7237  7237 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 17:23:40.586  7237  7237 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-09 17:23:40.586  7237  7237 W System.err: android.os.DeadObjectException
08-09 17:23:40.586  7237  7237 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-09 17:23:40.586  7237  7237 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-09 17:23:40.586  7237  7237 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-09 17:23:40.586  7237  7237 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-09 17:23:40.586  7237  7237 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-09 17:23:40.586  7237  7237 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-09 17:23:40.586  7237  7237 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 17:23:40.586  7237  7237 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 17:23:40.586  7237  7237 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 17:23:40.586  7237  7237 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 17:23:40.586  7237  7237 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 17:23:40.586  7237  7237 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 17:23:40.587  7237  7237 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 17:23:40.587  7237  7237 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 17:23:40.587  7237  7237 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-09 17:23:40.587  7237  7237 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind befor,e rebinding.
,08-09 17:23:40.752  1037  1915 W libprocessgroup: failed to open /acct/uid_1000/pid_6897/cgroup.procs: No such file or directory
,08-09 17:23:40.752  1037  1915 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-09 17:23:40.764  7237  7237 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,08-09 17:23:40.765  7237  7237 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-09 17:23:40.806  1037  2028 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8058 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-09 17:23:40.807  7237  7237 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-09 17:23:40.809  8039  8039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 17:23:40.809  8039  8039 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 17:23:40.809  8039  8039 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-09 17:23:40.810  8039  8039 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-09 17:23:40.810  8039  8039 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-09 17:23:40.852  8058  8058 D UEI.SmartControl: Quickset Services start...
08-09 17:23:40.853  8058  8058 I UEI.SmartControl: Manufacture = LGE
08-09 17:23:40.854  8058  8058 D UEI.SmartControl: Id = LGNevo
08-09 17:23:40.854  8058  8058 D UEI.SmartControl: File observer start...
,08-09 17:23:40.855  8058  8058 E UEI.SmartControl: IR Port is disabled: false
08-09 17:23:40.855  8058  8058 D UEI.SmartControl: Starting file observer...
08-09 17:23:40.855  8058  8058 D UEI.SmartControl: Extracting JNI libs...
,08-09 17:23:40.855  8058  8058 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-09 17:23:40.867  8039  8039 I SystemConfig: BUILD Country: EU
,08-09 17:23:40.867  8039  8039 I SystemConfig: BUILD Operator: OPEN
08-09 17:23:40.906  8058  8058 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-09 17:23:40.907  8058  8058 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-09 17:23:40.907  8058  8058 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-09 17:23:40.913  1037  2091 I ActivityManager: Killing 7237:com.lge.qremote/u0a112 (adj 15): empty #17
,08-09 17:23:40.927  8058  8058 I UEI.SmartControl: --- Selecting new region: 6
,08-09 17:23:40.928  8058  8058 I UEI.SmartControl: Model = LG-D855
,08-09 17:23:40.929  8058  8058 D UEI.SmartControl: QS Service created
08-09 17:23:41.016  1037  1780 W libprocessgroup: failed to open /acct/uid_10112/pid_7237/cgroup.procs: No such file or directory
,08-09 17:23:41.055  8058  8058 I UEI.SmartControl: Service initServices...
,08-09 17:23:41.061  8058  8058 D UEI.SmartControl: QS start get config
08-09 17:23:41.085  1037  2091 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8079 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-09 17:23:41.098  8039  8077 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-09 17:23:41.099  8039  8077 I SystemConfig: existFile = false
08-09 17:23:41.099  8039  8077 I SystemConfig: canReadFile = false
08-09 17:23:41.099  8039  8077 I SystemConfig: systemFeature RCS result false
08-09 17:23:41.100  8039  8077 D SystemConfig: refreshRcsSupport() :false
,08-09 17:23:41.121  8058  8058 D UEI.SmartControl: Loading JNI Libs...
,08-09 17:23:41.151  8079  8079 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 17:23:41.151  8079  8079 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-09 17:23:41.151  8079  8079 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-09 17:23:41.152  8079  8079 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-09 17:23:41.248  8079  8079 I AppConfig: Total System Memory = 2995761152
,08-09 17:23:41.258  8079  8079 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-09 17:23:41.338  1037  2115 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8098 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-09 17:23:41.339  1037  2115 I ActivityManager: Killing 7675:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-09 17:23:41.359   337   337 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 479us total 20.931ms
,08-09 17:23:41.378   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 18.340ms
,08-09 17:23:41.382  8058  8058 I UEI.SmartControl: Supports setup maps: true
08-09 17:23:41.385  8058  8058 D UEI.SmartControl: QS start statue = true Error code = 0
08-09 17:23:41.385  8058  8058 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-09 17:23:41.385  8058  8058 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-09 17:23:41.385  8058  8058 I UEI.SmartControl: ### init IR Blaster...
08-09 17:23:41.389  8058  8058 D serial_port: Configuring serial port
,08-09 17:23:41.394  8058  8058 E UEI.SmartControl: UEIBLaster setting for 616
08-09 17:23:41.395  8058  8058 I UEI.SmartControl: Setting serial record hearder size = 2
08-09 17:23:41.395   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 355us total 16.532ms
08-09 17:23:41.395  8058  8058 I UEI.SmartControl: configuring settings for MAXQ616
08-09 17:23:41.395  8058  8058 I UEI.SmartControl: Get version...
08-09 17:23:41.398  1037  1053 W libprocessgroup: failed to open /acct/uid_10005/pid_7675/cgroup.procs: No such file or directory
08-09 17:23:41.411  8058  8115 D UEI.SmartControl: serial port data available: 21
,08-09 17:23:41.440  8058  8058 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-09 17:23:41.440  8058  8058 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-09 17:23:41.440  8058  8058 I UEI.SmartControl: QS saving settings...
08-09 17:23:41.442  8058  8058 D UEI.SmartControl: IR Blaster version: 25672567
,08-09 17:23:41.459  8058  8115 D UEI.SmartControl: serial port data available: 4
,08-09 17:23:41.495  8098  8098 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-09 17:23:41.498  8058  8123 I UEI.SmartControl: Device manager: loading config....
,08-09 17:23:41.498  8058  8123 D UEI.SmartControl: ----------- loading internal config...
08-09 17:23:41.501  8058  8058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-09 17:23:41.508  8058  8058 E UEI.SmartControl: Services init done
,08-09 17:23:41.508  8058  8123 E UEI.SmartControl: Loading SETTINGS...
08-09 17:23:41.511  8058  8058 D UEI.SmartControl: QS Service init finished
08-09 17:23:41.513  8058  8058 D UEI.SmartControl: QS Service version name: 2.1.91
08-09 17:23:41.513  8058  8058 D UEI.SmartControl: QS Service version code: 201091
08-09 17:23:41.514  8058  8058 D UEI.SmartControl: Service requested: Control
08-09 17:23:41.514  8058  8123 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-09 17:23:41.515  8058  8058 D UEI.SmartControl: Service.onUnbind: IControl
08-09 17:23:41.516  8058  8058 D UEI.SmartControl: Service.onDestroy
08-09 17:23:41.516  8058  8058 D UEI.SmartControl: Lock is in USE false
08-09 17:23:41.516  8058  8058 D UEI.SmartControl: unbind internal service
08-09 17:23:41.517  8058  8058 D serial_port: close(fd = 25)
08-09 17:23:41.520  8058  8058 I UEI.SmartControl: Serial port is closed.
08-09 17:23:41.520  8058  8058 I UEI.SmartControl: Serial port is closed.
08-09 17:23:41.520  8058  8058 D UEI.SmartControl: Blaster closed
08-09 17:23:41.520  8058  8058 D UEI.SmartControl: Shut down QS...
08-09 17:23:41.520  8058  8058 D UEI.SmartControl: Stopping QS lib
08-09 17:23:41.521  8058  8058 D UEI.SmartControl: QS lib stop result = true
08-09 17:23:41.521  8058  8058 D UEI.SmartControl: Stopped QS lib
08-09 17:23:41.521  8058  8058 D UEI.SmartControl: Stopped file observer...
08-09 17:23:41.521  8058  8058 D UEI.SmartControl: QS shutdown complete
08-09 17:23:41.521  8058  8058 D UEI.SmartControl: QS Service created
08-09 17:23:41.533  8058  8058 I UEI.SmartControl: Service initServices...
,08-09 17:23:41.533  8058  8058 D UEI.SmartControl: QS start get config
08-09 17:23:41.534  8058  8122 I UEI.SmartControl: Notify AllClients services are ready: 11
08-09 17:23:41.534  8058  8122 D UEI.SmartControl: -----service ready thread exits
08-09 17:23:41.565  8098  8098 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:23:41.565  8098  8098 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:23:41.602  8098  8098 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-09 17:23:41.617  8098  8098 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-09 17:23:41.618  8098  8098 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-09 17:23:41.628  8098  8098 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-09 17:23:41.629  8098  8098 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-09 17:23:41.641  1037  1970 I ActivityManager: Killing 7402:com.lge.email/u0a23 (adj 15): empty #17
,08-09 17:23:41.744  1037  2051 W libprocessgroup: failed to open /acct/uid_10023/pid_7402/cgroup.procs: No such file or directory
,08-09 17:23:41.759  4977  8141 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-09 17:23:41.841  1037  1970 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8142 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-09 17:23:41.850  3411  5984 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-09 17:23:41.851  3411  5984 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2856f540 on behalf of 8098
08-09 17:23:41.866  8098  8098 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-09 17:23:41.888  8098  8098 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-09 17:23:41.931  8142  8142 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-09 17:23:41.936  8058  8058 I UEI.SmartControl: Supports setup maps: true
,08-09 17:23:41.940  8058  8058 D UEI.SmartControl: QS start statue = true Error code = 0
08-09 17:23:41.940  8058  8058 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-09 17:23:41.940  8058  8058 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-09 17:23:41.940  8058  8058 I UEI.SmartControl: ### init IR Blaster...
08-09 17:23:41.943  8058  8058 D serial_port: Configuring serial port
08-09 17:23:41.944  8058  8058 E UEI.SmartControl: UEIBLaster setting for 616
08-09 17:23:41.944  8058  8058 I UEI.SmartControl: Setting serial record hearder size = 2
08-09 17:23:41.944  8058  8058 I UEI.SmartControl: configuring settings for MAXQ616
08-09 17:23:41.944  8058  8058 I UEI.SmartControl: Get version...
08-09 17:23:41.951  8142  8142 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-09 17:23:41.951  8142  8142 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-09 17:23:41.951  8142  8142 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-09 17:23:41.951  8142  8142 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-09 17:23:41.951  8142  8142 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-09 17:23:41.951  8142  8142 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-09 17:23:41.963  8058  8165 D UEI.SmartControl: serial port data available: 21
,08-09 17:23:41.967  1037  2267 I ActivityManager: Killing 7306:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-09 17:23:41.989  8058  8058 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-09 17:23:41.989  8058  8058 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-09 17:23:41.989  8058  8058 I UEI.SmartControl: QS saving settings...
08-09 17:23:41.990  8058  8058 D UEI.SmartControl: IR Blaster version: 25672567
,08-09 17:23:41.990  1037  1969 W libprocessgroup: failed to open /acct/uid_10026/pid_7306/cgroup.procs: No such file or directory
08-09 17:23:42.007  8058  8165 D UEI.SmartControl: serial port data available: 4
,08-09 17:23:42.036  8058  8169 I UEI.SmartControl: Device manager: loading config....
,08-09 17:23:42.040  8058  8058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-09 17:23:42.043  8058  8169 D UEI.SmartControl: ----------- loading internal config...
08-09 17:23:42.043  8058  8058 E UEI.SmartControl: Services init done
08-09 17:23:42.043  8058  8058 D UEI.SmartControl: QS Service init finished
08-09 17:23:42.045  8058  8058 D UEI.SmartControl: QS Service version name: 2.1.91
08-09 17:23:42.045  8058  8058 D UEI.SmartControl: QS Service version code: 201091
08-09 17:23:42.045  8058  8058 D UEI.SmartControl: Service requested: Control
08-09 17:23:42.055  8058  8169 E UEI.SmartControl: Loading SETTINGS...
,08-09 17:23:42.056  8058  8058 D UEI.SmartControl: Request IControl service: devices are loaded...
08-09 17:23:42.058  1037  1933 I ActivityManager: Killing 6774:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-09 17:23:42.062  8058  8169 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-09 17:23:42.075  8058  8168 I UEI.SmartControl: Notify AllClients services are ready: 0
08-09 17:23:42.075  8058  8168 D UEI.SmartControl: -----service ready thread exits
,08-09 17:23:42.092  1037  1653 W libprocessgroup: failed to open /acct/uid_1000/pid_6774/cgroup.procs: No such file or directory
,08-09 17:23:42.093  8058  8058 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@22059829 that was originally bound here
08-09 17:23:42.093  8058  8058 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@22059829 that was originally bound here
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 17:23:42.093  8058  8058 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 17:23:42.098  8058  8058 D UEI.SmartControl: Internal service binding...
08-09 17:23:42.167  1037  2028 V SIM_STK : Menu title from STK is T-Mobile
,08-09 17:23:42.191  4977  8141 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 431 ms] updated apps [took 431 ms] 
,08-09 17:23:42.515  8058  8128 D UEI.SmartControl: Internal timer expired: 2
,08-09 17:23:43.171  1037  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 17:23:43.172  1037  2052 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@83bcbfe mBinding = false
,08-09 17:23:43.199  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 17:23:43.199  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 17:23:43.199  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-09 17:23:43.203  1037  1098 D BluetoothManagerService: Message: 2
08-09 17:23:43.204  1037  1098 D BluetoothManagerService: Sending off request.
08-09 17:23:43.205  7288  7304 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-09 17:23:43.205  7288  7842 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-09 17:23:43.205  7288  7842 D BluetoothAdapterProperties: Setting state to 13
08-09 17:23:43.205  7288  7842 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-09 17:23:43.206  7288  7842 D BluetoothAdapterProperties: onBluetoothDisable()
08-09 17:23:43.206  7288  7842 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-09 17:23:43.208  7288  7846 D BluetoothAdapterProperties: Scan Mode:20
08-09 17:23:43.210  7288  7842 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-09 17:23:43.212  7288  7964 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-09 17:23:43.212  7288  7964 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 17:23:43.212  7288  7964 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-09 17:23:43.212  7288  7964 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-09 17:23:43.212  7288  7964 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-09 17:23:43.212  7288  7964 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-09 17:23:43.212  7288  7964 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-09 17:23:43.212  7288  7964 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-09 17:23:43.214  7288  7966 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-09 17:23:43.217  7288  7974 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 17:23:43.217  7288  7978 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 17:23:43.218  7288  7976 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 17:23:43.219  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-09 17:23:43.219  7288  7902 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-09 17:23:43.220  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-09 17:23:43.220  7288  7902 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-09 17:23:43.221  7288  7842 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-09 17:23:43.227  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:43.227  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:43.227  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:43.227  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:43.227  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:43.227  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:43.227  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:43.227  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:43.227  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 17:23:43.241  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:43.241  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 17:23:43.244  1037  1548 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-09 17:23:43.247  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:43.247  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:43.247  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:43.247  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:43.247  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:43.247  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:43.247  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:43.247  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:43.247  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:43.247  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:43.247  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:43.252  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 17:23:43.252  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:43.252  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:43.252  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:43.252  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:43.252  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 17:23:43.252  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:43.252  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:43.252  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:43.253  7054  7054 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 17:23:43.255  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:43.256  1037  1098 D BluetoothManagerService: Message: 60
08-09 17:23:43.256  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-09 17:23:43.256  1037  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-09 17:23:43.258  1971  1971 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:43.259  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 17:23:43.273  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:23:43.278  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:43.280  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:43.285  7288  7288 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:43.285  7288  7288 D BluetoothMapService: STATE_TURNING_OFF
08-09 17:23:43.285  7288  7288 V BluetoothMapService: Handler(): got msg=4
08-09 17:23:43.285  7288  7288 D BluetoothMapService: MAP Service closeService in
08-09 17:23:43.285  7288  7288 D BluetoothMapMasInstance: MAP Service shutdown
08-09 17:23:43.285  7288  7288 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 17:23:43.285  7288  7288 V BluetoothMapService: MAP Service closeService out
08-09 17:23:43.288  7288  7288 V BtOppService: Receiver DISABLED_ACTION 
08-09 17:23:43.288  7288  7288 I BtOppRfcommListener: stopping Accept Thread
08-09 17:23:43.288  7288  7288 V BtOppRfcommListener: close mBtServerSocket
,08-09 17:23:43.290  7288  7974 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-09 17:23:43.291  7288  7288 V BtOppRfcommListener: waiting for thread to terminate
08-09 17:23:43.291  7288  7288 V BtOppRfcommListener: done waiting for thread to terminate
08-09 17:23:43.295  7178  7178 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-09 17:23:43.298  7178  7178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-09 17:23:43.305  7288  7288 V BtOppService: onDestroy
08-09 17:23:43.306  7288  7288 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-09 17:23:43.309  7288  7288 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 17:23:43.309  7288  7288 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:43.309  7288  7288 V BluetoothPbapReceiver: ***********state = 13
08-09 17:23:43.311  7288  7288 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-09 17:23:43.316  7288  7288 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:43.316  7288  7288 V BluetoothPbapService: state: 13
08-09 17:23:43.316  7288  7288 V BluetoothPbapService: Pbap Service closeService in
08-09 17:23:43.318  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 17:23:43.319  7288  7288 V BluetoothPbapService: successfully stopped pbap service
08-09 17:23:43.319  7288  7288 V BluetoothPbapService: Pbap Service closeService out
08-09 17:23:43.322  7288  7288 V BluetoothPbapService: Pbap Service onDestroy
08-09 17:23:43.322  7288  7288 V BluetoothPbapService: Pbap Service closeService in
08-09 17:23:43.322  7288  7288 V BluetoothPbapService: Pbap Service closeService out
08-09 17:23:43.322  7288  7288 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-09 17:23:43.342  7178  7178 D DockEventReceiver: finishStartingService: stopping service
,08-09 17:23:43.344  7178  7178 D BluetoothPbap: Proxy object disconnected
08-09 17:23:43.344  7178  7178 D PbapServerProfile: Bluetooth service disconnected
08-09 17:23:43.349  7178  7178 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-09 17:23:43.355  7178  7178 D BluetoothPermissionRequest: onReceive
08-09 17:23:43.355  7178  7178 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-09 17:23:43.361  7178  7178 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 17:23:43.364  7288  7288 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-09 17:23:43.364  7288  7288 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-09 17:23:43.365  7288  7288 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-09 17:23:43.369  7288  7288 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:43.369  7288  7288 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-09 17:23:43.370  7288  7288 V BluetoothFtpService: Ftp Service onStartCommand
08-09 17:23:43.370  7288  7288 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:43.370  7288  7288 V BluetoothFtpService: Ftp Service closeService
,08-09 17:23:43.370  7288  7288 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-09 17:23:43.373  7288  7288 V BluetoothFtpService: successfully stopped ftp service
08-09 17:23:43.373  7288  7288 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 17:23:43.373  7288  7288 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 17:23:43.373  7288  7288 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 17:23:43.373  7288  7288 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:43.373  7288  7288 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-09 17:23:43.373  7288  7288 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-09 17:23:43.374  7288  7288 V BluetoothFtpService: Ftp Service onDestroy
08-09 17:23:43.374  7288  7288 V BluetoothFtpService: Ftp Service closeService
08-09 17:23:43.378  7288  7288 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:43.378  7288  7288 V BluetoothSapService: state: 13
08-09 17:23:43.378  7288  7288 V BluetoothSapService: Stopping SAP server process
08-09 17:23:43.379  7288  7288 V BluetoothSapService: Sap Service closeSapService in
08-09 17:23:43.379  7288  7288 V BluetoothSapService: Close listen Socket : 
08-09 17:23:43.379  7288  7288 V BluetoothSapService: Close rfcomm Socket : 
08-09 17:23:43.379  7288  7288 V BluetoothSapService: Close sapd  Socket : 
08-09 17:23:43.383  7288  7288 V BluetoothSapService: Sap Service closeSapService out
08-09 17:23:43.383  7288  7288 V BluetoothSapService: Sap Service onDestroy
,08-09 17:23:43.383  7288  7288 V BluetoothSapService: Sap Service closeSapService in
08-09 17:23:43.383  7288  7288 V BluetoothSapService: Close listen Socket : 
08-09 17:23:43.383  7288  7288 V BluetoothSapService: Close rfcomm Socket : 
08-09 17:23:43.383  7288  7288 V BluetoothSapService: Close sapd  Socket : 
08-09 17:23:43.383  7288  7288 V BluetoothSapService: Sap Service closeSapService out
,08-09 17:23:44.200  7288  7846 D bt_hci_bdroid: cleanup
,08-09 17:23:44.207  7288  7904 I bt_lpm  : LPM is already off!!!
08-09 17:23:44.210  7288  7942 I bt_userial_mct: exiting userial_read_thread
08-09 17:23:44.210  7288  7942 D bt_userial_mct: Leaving userial_evt_read_thread()
08-09 17:23:44.211  7288  7902 W bt-btif : ag scb idx 1 not allocated
08-09 17:23:44.211  7288  7902 E bt-btif : BTA AG is already disabled, ignoring ...
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 17:23:44.211  7288  7902 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 17:23:44.211  7288  7902 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-09 17:23:44.212  7288  7846 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-09 17:23:44.212  7288  7904 I bt_vendor: hw_epilog_process
08-09 17:23:44.212  7288  7846 D bt_hci_bdroid: cleanup Finalizing cleanup
08-09 17:23:44.212  7288  7846 D bt_userial_mct: userial_close
08-09 17:23:44.213  7288  7846 E bt_userial_mct: pthread_join() FAILED result:3
08-09 17:23:44.213  7288  7846 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-09 17:23:44.219  7288  7846 D bt_hci_bdroid: set_power 0
08-09 17:23:44.219  7288  7846 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-09 17:23:44.219  7288  7846 I bt_vendor: bluetooth satus is on
08-09 17:23:44.219  7288  7846 I bt_vendor: bt-vendor : resetting BT status
08-09 17:23:44.219  7288  7846 I bt_vendor: Starting hciattach daemon
08-09 17:23:44.219  7288  7846 I bt_vendor: try to set false
,08-09 17:23:44.226  7288  7846 I bt_vendor: Starting hciattach daemon
08-09 17:23:44.226  7288  7846 I bt_vendor: try to set false
08-09 17:23:44.227  7288  7846 I bt_vendor: cleanup
08-09 17:23:44.228  7288  7902 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-09 17:23:44.228  7288  7846 I GKI_LINUX: GKI_exit_task 0 done
08-09 17:23:44.228  7288  7846 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-09 17:23:44.230  7288  7842 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-09 17:23:44.235  7288  7288 D HeadsetService: Received stop request...Stopping profile...
,08-09 17:23:44.239  7288  7288 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-09 17:23:44.239  7288  7288 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 17:23:44.239  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:44.240  7288  7879 D HeadsetStateMachine: Exit Disconnected: -1
08-09 17:23:44.245  7288  7842 D BluetoothAdapterState: Stopping profile services that were post enabled
08-09 17:23:44.246  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-09 17:23:44.246  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-09 17:23:44.247  1880  1880 D BluetoothHeadset: Proxy object disconnected
08-09 17:23:44.247  1880  1880 D BluetoothHeadset: Proxy object disconnected
08-09 17:23:44.247  1880  1880 D BluetoothHeadset: Proxy object disconnected
,08-09 17:23:44.251  7288  7288 D A2dpService: Received stop request...Stopping profile...
08-09 17:23:44.252  7288  7891 D A2dpStateMachine: Exit Disconnected: -1
08-09 17:23:44.254  7288  7288 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-09 17:23:44.256  7288  7288 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-09 17:23:44.256  7288  7288 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 17:23:44.257  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:44.259  7288  7288 D HidService: Received stop request...Stopping profile...
08-09 17:23:44.259  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
,08-09 17:23:44.261  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-09 17:23:44.261  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-09 17:23:44.263  7288  7288 D HeadsetStateMachine: Unbinding service...
08-09 17:23:44.265  7288  7288 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 17:23:44.265  7288  7288 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 17:23:44.265  7288  7288 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 17:23:44.265  7288  7288 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 17:23:44.265  7288  7288 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-09 17:23:44.265  7288  7288 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 17:23:44.265  7288  7288 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-09 17:23:44.267  7288  7288 D HealthService: Received stop request...Stopping profile...
08-09 17:23:44.267  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:44.269  7288  7288 D PanService: Received stop request...Stopping profile...
08-09 17:23:44.270  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:44.271  7288  7288 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 17:23:44.273  7288  7288 D BtGatt.GattService: Received stop request...Stopping profile...
08-09 17:23:44.274  7288  7288 D BtGatt.GattService: stop()
08-09 17:23:44.274  7288  7288 D BtGatt.AdvertiseManager: advertise clients cleared
08-09 17:23:44.275  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:44.277  7288  7288 D BluetoothMapService: Received stop request...Stopping profile...
08-09 17:23:44.277  7288  7288 D BluetoothMapService: stop()
08-09 17:23:44.278  7288  7288 D BluetoothMapEmailAppObserver: deinitObservers()
08-09 17:23:44.278  7288  7288 D BluetoothMapEmailAppObserver: removeReceiver()
08-09 17:23:44.279  7288  7288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cb70f3
08-09 17:23:44.280  7288  7288 I BluetoothA2dpServiceJni: cleanupNative
08-09 17:23:44.280  7288  7892 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-09 17:23:44.280  7288  7288 I GKI_LINUX: GKI_exit_task 2 done
08-09 17:23:44.280  7288  7288 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-09 17:23:44.281  7288  7288 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 17:23:44.281  7288  7288 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-09 17:23:44.281  7288  7288 V BluetoothMapService: Handler(): got msg=4
08-09 17:23:44.281  7288  7288 D BluetoothMapService: MAP Service closeService in
08-09 17:23:44.281  7288  7288 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 17:23:44.281  7288  7288 V BluetoothMapService: MAP Service closeService out
08-09 17:23:44.282  7288  7842 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-09 17:23:44.282  7288  7842 D BluetoothAdapterProperties: Setting state to 10
08-09 17:23:44.282  7288  7842 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-09 17:23:44.283  1037  1098 D BluetoothManagerService: Message: 60
08-09 17:23:44.283  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-09 17:23:44.283  1037  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-09 17:23:44.288  7288  7842 I BluetoothAdapterState: Entering OffState
08-09 17:23:44.289  1880  1896 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 17:23:44.290  7288  7288 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 17:23:44.290  7288  7288 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 17:23:44.290  7288  7288 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 17:23:44.290  7288  7288 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-09 17:23:44.290  7288  7288 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 17:23:44.292  7288  7288 D BluetoothMapService: cleanup()
08-09 17:23:44.292  7288  7288 D BluetoothMapService: MAP Service closeService in
08-09 17:23:44.292  7288  7288 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 17:23:44.292  7288  7288 V BluetoothMapService: MAP Service closeService out
08-09 17:23:44.293  7178  7197 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 17:23:44.294  1037  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 17:23:44.294  1880  4326 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 17:23:44.294  1880  4325 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 17:23:44.295  1037  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-09 17:23:44.300  7178  7197 D BluetoothPan: onBluetoothStateChange on: false
08-09 17:23:44.301  7178  7197 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 17:23:44.302  7178  7197 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 17:23:44.303  7178  7197 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 17:23:44.303  7178  7197 D BluetoothMap: onBluetoothStateChange: up=false
08-09 17:23:44.304  1037  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-09 17:23:44.304  1037  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-09 17:23:44.306  1037  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-09 17:23:44.306  1037  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-09 17:23:44.306  1037  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@83bcbfe mBinding = false
,08-09 17:23:44.309  1037  1098 D BluetoothManagerService: Sending unbind request.
08-09 17:23:44.313  7288  7846 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-09 17:23:44.315  7288  7288 I GKI_LINUX: GKI_exit_task 1 done
08-09 17:23:44.315  7288  7288 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-09 17:23:44.315  7288  7288 I BluetoothServiceJni: cleanupNative: return from cleanup
08-09 17:23:44.315  7288  7288 I art     : --- WEIRD: removing null entry 248
08-09 17:23:44.315  7288  7288 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-09 17:23:44.315  7288  7288 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-09 17:23:44.317  7288  7288 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-09 17:23:44.318  1037  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-09 17:23:44.321  7288  7288 I art     : System.exit called, status: 0
08-09 17:23:44.321  7288  7288 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-09 17:23:44.341   316  1384 V AudioFlinger: 7288 died, releasing its sessions
08-09 17:23:44.341   316  1384 V AudioFlinger:  pid 1880 @ 0
08-09 17:23:44.341   316  1384 V AudioFlinger:  pid 3307 @ 1
08-09 17:23:44.341   316  1384 V AudioFlinger:  pid 3307 @ 2
,08-09 17:23:44.344  1971  1971 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-09 17:23:44.345  1971  2177 D LGBluetoothAPIService: Message: 101
08-09 17:23:44.345  1971  2177 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-09 17:23:44.345  1971  2177 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-09 17:23:44.345  1971  2177 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-09 17:23:44.346  7178  7178 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-09 17:23:44.378  1037  1933 I ActivityManager: Process com.android.bluetooth (pid 7288) has died
,08-09 17:23:44.379  1037  1933 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-09 17:23:44.379  1037  1933 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-09 17:23:44.387  1971  1971 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:44.388  1971  2177 D LGBluetoothAPIService: Message: 2
08-09 17:23:44.388  1971  2177 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-09 17:23:44.390  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:44.390  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 17:23:44.391  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:23:44.392  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:44.394  7178  7178 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-09 17:23:44.394  7178  7178 D LGBluetoothEventManager: [BTUI] clear device connection state
08-09 17:23:44.398  7178  7178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-09 17:23:44.401  1606  1606 D BluetoothAdapter: 329289052: getState() :  mService = null. Returning STATE_OFF
08-09 17:23:44.402  1606  1606 D BluetoothAdapter: 329289052: getState() :  mService = null. Returning STATE_OFF
,08-09 17:23:44.453  1037  2028 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8226 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-09 17:23:44.453  7178  7178 D DockEventReceiver: finishStartingService: stopping service
,08-09 17:23:44.510  8226  8226 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-09 17:23:44.511  8226  8226 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 17:23:44.511  8226  8226 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-09 17:23:44.512  8226  8226 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-09 17:23:44.535  8226  8226 D BluetoothAdapterApp: Loading JNI Library
,08-09 17:23:44.572  8226  8226 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@aa6cd7b Instance Count = 1
,08-09 17:23:44.579  8226  8226 D BluetoothAdapterApp: onCreate
,08-09 17:23:44.606  8226  8226 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-09 17:23:44.606  8226  8226 D ProfileConfigQcom: Adding HeadsetService
08-09 17:23:44.606  8226  8226 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-09 17:23:44.607  8226  8226 D ProfileConfigQcom: Adding A2dpService
,08-09 17:23:44.607  8226  8226 D ProfileConfigQcom: [BTUI] HidService is supported
08-09 17:23:44.607  8226  8226 D ProfileConfigQcom: Adding HidService
08-09 17:23:44.607  8226  8226 D ProfileConfigQcom: [BTUI] HealthService is supported
08-09 17:23:44.608  8226  8226 D ProfileConfigQcom: Adding HealthService
08-09 17:23:44.608  8226  8226 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-09 17:23:44.609  8226  8226 D ProfileConfigQcom: [BTUI] PanService is supported
,08-09 17:23:44.610  8226  8226 D ProfileConfigQcom: Adding PanService
08-09 17:23:44.610  8226  8226 D ProfileConfigQcom: [BTUI] GattService is supported
08-09 17:23:44.610  8226  8226 D ProfileConfigQcom: Adding GattService
08-09 17:23:44.610  8226  8226 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-09 17:23:44.611  8226  8226 D ProfileConfigQcom: Adding BluetoothMapService
08-09 17:23:44.611  8226  8226 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-09 17:23:44.612  8226  8226 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 17:23:44.613  8226  8226 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:44.614  8226  8226 V BluetoothPbapReceiver: ***********state = 10
08-09 17:23:44.616  8226  8226 V LGMDMManagerInternal: Create singleton instance
,08-09 17:23:44.717  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 17:23:44.718  7178  7178 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-09 17:23:44.718  8226  8226 D LGBluetoothAPIServer: [BTUI] onCreate()
08-09 17:23:44.718  8226  8226 D LGBluetoothAPIServer: [BTUI] onBind()
,08-09 17:23:44.721  1971  1971 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-09 17:23:44.722  1971  2177 D LGBluetoothAPIService: Message: 100
08-09 17:23:44.722  1971  2177 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-09 17:23:44.743  7178  7178 D BluetoothPermissionRequest: onReceive
,08-09 17:23:44.748  7178  7178 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-09 17:23:44.749  7178  7178 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-09 17:23:44.752  7178  7178 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 17:23:44.761  8226  8226 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-09 17:23:44.769  8226  8226 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:44.774  8226  8226 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-09 17:23:44.775  8226  8226 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-09 17:23:44.775  8226  8226 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 17:23:44.777  8226  8226 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:44.777  8226  8226 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-09 17:23:44.796  7910  7910 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-09 17:23:45.860  8058  8070 E UEI.SmartControl: file observer is disposed!
,08-09 17:23:46.096  1037  1407 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3e1fea75 type 2 when 393831 com.google.android.gms} when 393831
,08-09 17:23:46.139   311  8256 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-09 17:23:46.142  1037  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-09 17:23:47.038  8058  8170 D UEI.SmartControl: Internal timer expired: 3
,08-09 17:23:47.038  8058  8170 D UEI.SmartControl: unbind internal service
,08-09 17:23:47.054  8058  8058 D UEI.SmartControl: Service.onUnbind: IControl
08-09 17:23:47.060  8058  8058 D UEI.SmartControl: Service.onDestroy
08-09 17:23:47.061  8058  8058 D UEI.SmartControl: Lock is in USE false
08-09 17:23:47.061  8058  8058 D UEI.SmartControl: unbind internal service
08-09 17:23:47.061  8058  8058 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@c9ba6c8
,08-09 17:23:47.063  8058  8058 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-09 17:23:47.064  8058  8058 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-09 17:23:47.064  8058  8058 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-09 17:23:47.064  8058  8058 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-09 17:23:47.064  8058  8058 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-09 17:23:47.064  8058  8058 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-09 17:23:47.064  8058  8058 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-09 17:23:47.064  8058  8058 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-09 17:23:47.064  8058  8058 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 17:23:47.064  8058  8058 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 17:23:47.064  8058  8058 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 17:23:47.064  8058  8058 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 17:23:47.064  8058  8058 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 17:23:47.064  8058  8058 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 17:23:47.064  8058  8058 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 17:23:47.065  8058  8058 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@c9ba6c8
08-09 17:23:47.067  8058  8058 D serial_port: close(fd = 24)
08-09 17:23:47.070  8058  8058 I UEI.SmartControl: Serial port is closed.
08-09 17:23:47.070  8058  8058 I UEI.SmartControl: Serial port is closed.
08-09 17:23:47.070  8058  8058 D UEI.SmartControl: Blaster closed
08-09 17:23:47.070  8058  8058 D UEI.SmartControl: Shut down QS...
08-09 17:23:47.070  8058  8058 D UEI.SmartControl: Stopping QS lib
08-09 17:23:47.070  8058  8058 D UEI.SmartControl: QS lib stop result = true
08-09 17:23:47.070  8058  8058 D UEI.SmartControl: Stopped QS lib
08-09 17:23:47.070  8058  8058 D UEI.SmartControl: QS shutdown complete
08-09 17:23:48.284  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:48.284  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:23:53.295  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:53.295  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@251dbe3d removed from the list
08-09 17:23:53.296  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:53.296  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:53.296  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:23:53.308  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:23:53.308  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e19cf83 added. We now have 4 listener(s)
08-09 17:23:53.311  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:23:53.311  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:53.312  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e19cf83 removed from the list
08-09 17:23:53.312  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:53.312  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:53.312  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:53.312  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:23:53.313  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20897500 added. We now have 4 listener(s)
08-09 17:23:53.313  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:23:53.313  7054  7110 I System.out: IsBluetoothEnabled
08-09 17:23:53.316  1037  1653 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:53.316  1037  1653 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-09 17:23:53.319  1037  1098 D BluetoothManagerService: Message: 2
08-09 17:23:53.322  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:53.322  1037  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:53.323  1037  2052 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-09 17:23:53.341  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 17:23:53.341  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 17:23:53.341  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-09 17:23:53.342  1037  1098 D BluetoothManagerService: Message: 1
08-09 17:23:53.342  1037  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-09 17:23:53.367  1037  1098 D BluetoothManagerService: Message: 20
08-09 17:23:53.367  1037  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fcb5cd6:true
,08-09 17:23:53.371  8226  8226 D BluetoothAdapterState: make
08-09 17:23:53.376  8226  8226 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-09 17:23:53.376  8226  8226 I bluedroid-qcom: init
08-09 17:23:53.378  8226  8260 I BluetoothAdapterState: Entering OffState
08-09 17:23:53.378  8226  8226 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-09 17:23:53.378  8226  8226 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-09 17:23:53.378  8226  8226 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-09 17:23:53.379  8226  8226 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-09 17:23:53.379  8226  8226 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-09 17:23:53.380  8226  8226 I bluedroid-qcom: get_profile_interface socket
08-09 17:23:53.380  8226  8226 I bluedroid-qcom: get_profile_interface map_client
,08-09 17:23:53.385  8226  8264 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-09 17:23:53.369  8263  8263 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:53.379  8263  8263 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:53.400  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-09 17:23:53.403  1037  1098 D BluetoothManagerService: Message: 40
08-09 17:23:53.403  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-09 17:23:53.404  8226  8241 I bluedroid-qcom: config_hci_snoop_log
08-09 17:23:53.405  1037  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-09 17:23:53.405  1037  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-09 17:23:53.398  8263  8263 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-09 17:23:53.407  8263  8263 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-09 17:23:53.408  8263  8263 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-09 17:23:53.410  8263  8263 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-09 17:23:53.414  8263  8263 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-09 17:23:53.414  8263  8263 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-09 17:23:53.419  8226  8260 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-09 17:23:53.420  8226  8264 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-09 17:23:53.421  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-09 17:23:53.422  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-09 17:23:53.422  8226  8264 D BluetoothAdapterProperties: Name is: G3
08-09 17:23:53.422  8226  8260 D BluetoothAdapterProperties: Setting state to 11
08-09 17:23:53.422  8226  8260 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-09 17:23:53.423  1037  1098 D BluetoothManagerService: Message: 60
08-09 17:23:53.423  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-09 17:23:53.423  1037  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-09 17:23:53.425  8226  8260 I LGBluetoothServiceJni: classInitNative: succeeds
08-09 17:23:53.431  1971  1971 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-09 17:23:53.434  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 17:23:53.436  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:53.437  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:53.445  8226  8260 D BluetoothBondStateMachine: make
,08-09 17:23:53.448  7178  7178 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-09 17:23:53.455  8226  8260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
,08-09 17:23:53.456  8226  8260 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-09 17:23:53.456  8226  8260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:53.456  8226  8260 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-09 17:23:53.457  8226  8260 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-09 17:23:53.464  8226  8265 I BluetoothBondStateMachine: StableState(): Entering Off State
08-09 17:23:53.471  8226  8226 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 17:23:53.471  8226  8226 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:53.471  8226  8226 V BluetoothPbapReceiver: ***********state = 11
,08-09 17:23:53.478  8226  8260 E BluetoothAdapterService: File transfer profiles supported!!
08-09 17:23:53.481  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 17:23:53.490  8226  8226 D HeadsetService: Received start request. Starting profile...
08-09 17:23:53.490  8226  8260 E BluetoothAdapterService: File transfer profiles supported!!
08-09 17:23:53.490  8226  8226 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 17:23:53.491  8226  8226 D LGBluetoothHfpAdapter: Version 1.6
08-09 17:23:53.493  8226  8226 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-09 17:23:53.495  8226  8226 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 17:23:53.495  8226  8226 D HeadsetStateMachine: make
,08-09 17:23:53.504  8226  8260 E BluetoothAdapterService: File transfer profiles supported!!
08-09 17:23:53.505  7178  7178 D BluetoothPermissionRequest: onReceive
08-09 17:23:53.509  7178  7178 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 17:23:53.510  8226  8260 E BluetoothAdapterService: File transfer profiles supported!!
,08-09 17:23:53.516  8226  8260 E BluetoothAdapterService: File transfer profiles supported!!
08-09 17:23:53.520  8226  8260 E BluetoothAdapterService: File transfer profiles supported!!
08-09 17:23:53.524  8226  8260 E BluetoothAdapterService: File transfer profiles supported!!
,08-09 17:23:53.534  8226  8260 V LGMDMManager: Create singleton instance
08-09 17:23:53.535  8226  8260 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-09 17:23:53.536  8226  8226 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:23:53.536  8226  8226 D LgDataFeature: LgDataFeature() Constructor Done, null
08-09 17:23:53.541  8226  8226 D HeadsetStateMachine: max_hf_connections = 1
08-09 17:23:53.541  8226  8226 I bluedroid-qcom: get_profile_interface handsfree
08-09 17:23:53.543  8226  8226 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-09 17:23:53.544   316  1384 V AudioPolicyService: registerClient() client 0xb1025e40, uid 1002
08-09 17:23:53.544   316   316 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-09 17:23:53.544   316   316 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-09 17:23:53.544   316   316 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 17:23:53.544  8226  8226 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-09 17:23:53.544   316  1383 V AudioFlinger: registerClient() client 0xb1433130, pid 8226
08-09 17:23:53.545   316  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:53.545   316  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 17:23:53.545  1037  2091 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:53.545  1037  2091 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 17:23:53.545  3307  3322 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:53.545  3307  3322 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-09 17:23:53.545  1606  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:53.545  1606  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 17:23:53.545  1880  4325 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:53.546  1880  4325 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 17:23:53.546  8226  8226 V ToneGenerator: Create Track: 0xb4928a80
08-09 17:23:53.546  8226  8241 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 17:23:53.546  8226  8226 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-09 17:23:53.546  8226  8241 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-09 17:23:53.546  8226  8226 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-09 17:23:53.546   316  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-09 17:23:53.546   316  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-09 17:23:53.546   316  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-09 17:23:53.546   316  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 17:23:53.546   316  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:53.546   316  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 17:23:53.546  8226  8241 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:53.547  8226  8241 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-09 17:23:53.547  3307  3323 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:53.547  3307  3323 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 17:23:53.547  1880  2571 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:53.547  1880  2571 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-09 17:23:53.547  1606  1627 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:53.547  1606  1627 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 17:23:53.548  1037  1969 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 17:23:53.548  1037  1969 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 17:23:53.548   316  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-09 17:23:53.549   316  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-09 17:23:53.549   316  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-09 17:23:53.549   316  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 17:23:53.549   316  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 17:23:53.549  8226  8226 V AudioSystem: getLatency() output 2, latency 50,
08-09 17:23:53.549  8226  8226 V AudioSystem: getFrameCount() output 2, frameCount 960
08-09 17:23:53.549  8226  8226 V AudioTrack: createTrack_l() output 2 afLatency 50
08-09 17:23:53.550   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-09 17:23:53.550   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-09 17:23:53.550   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-09 17:23:53.550   316   316 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-09 17:23:53.550   316   316 V AudioFlinger: createTrack() lSessionId: 23
,08-09 17:23:53.551  8226  8226 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-09 17:23:53.551   316  1384 V AudioFlinger: acquiring 23 from 8226, for 8226
08-09 17:23:53.551   316  1384 V AudioFlinger:  added new entry for 23
08-09 17:23:53.551  8226  8226 V ToneGenerator: ToneGenerator INIT OK, time: 401303
08-09 17:23:53.551  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:53.553  8226  8278 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-09 17:23:53.553  8226  8278 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 17:23:53.553  8226  8278 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 17:23:53.553  8226  8278 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-09 17:23:53.554   316   316 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 8226
08-09 17:23:53.554  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:53.554   316   316 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-09 17:23:53.554   316   316 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-09 17:23:53.554   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-09 17:23:53.554   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-09 17:23:53.554   316   316 V voice   : voice_set_parameters: exit with code(0)
08-09 17:23:53.554   316   316 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-09 17:23:53.554   316   316 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-09 17:23:53.554   316   316 V msm8974_platform: platform_set_parameters: exit with code(0)
08-09 17:23:53.554   316   316 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-09 17:23:53.554   316   316 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-09 17:23:53.554   316   316 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-09 17:23:53.554  8226  8278 V ToneGenerator: ToneGenerator destructor
08-09 17:23:53.554  8226  8278 V ToneGenerator: stopTone
08-09 17:23:53.554  8226  8278 V ToneGenerator: Delete Track: 0xb4928a80
08-09 17:23:53.555  8226  8278 V AudioTrack: ~AudioTrack, releasing session id from 8226 on behalf of 8226
08-09 17:23:53.555   316  1384 V AudioFlinger: releasing 23 from 8226 for 8226
08-09 17:23:53.555   316  1384 V AudioFlinger:  decremented refcount to 0
08-09 17:23:53.555   316  1384 V AudioFlinger: purging stale effects
08-09 17:23:53.556   316  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-09 17:23:53.556   316  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-09 17:23:53.556   316  1260 V AudioPolicyService: AudioCommandThread() waking up
08-09 17:23:53.556   316  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-09 17:23:53.556   316  1260 V AudioPolicyManager: releaseOutput() 2
08-09 17:23:53.556   316  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-09 17:23:53.556   316  1384 V AudioFlinger: PlaybackThread::Track destructor
08-09 17:23:53.556   316  1384 V AudioFlinger: removeClient_l() pid 8226, calling pid 316
08-09 17:23:53.556  8226  8226 D A2dpService: Received start request. Starting profile...
08-09 17:23:53.557  1037  1933 W Process : Unable to open /proc/8279/status
08-09 17:23:53.557  8226  8226 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 17:23:53.558  8226  8226 V Avrcp   : make
08-09 17:23:53.558  8226  8226 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-09 17:23:53.558  8226  8226 I bluedroid-qcom: get_profile_interface avrcp
08-09 17:23:53.566  8226  8226 V AudioManager: registerRemoteController: size of Media player list: 0
,08-09 17:23:53.570  8226  8226 E AudioManager: No RCC entry present to update
,08-09 17:23:53.570  8226  8226 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 17:23:53.573  8226  8226 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-09 17:23:53.574  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-09 17:23:53.575  8226  8226 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-09 17:23:53.578  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-09 17:23:53.727  1037  1970 V SIM_STK : Menu title from STK is T-Mobile
08-09 17:23:53.727  1037  1970 V SIM_STK : Menu title from STK is T-Mobile
,08-09 17:23:53.820  1037  2051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output,
,08-09 17:23:53.829  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-09 17:23:53.833  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-09 17:23:53.834  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-09 17:23:53.834  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-09 17:23:53.834  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-09 17:23:53.834  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 17:23:53.834  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
,08-09 17:23:53.834  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-09 17:23:53.834  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music,
08-09 17:23:53.834  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-09 17:23:53.834  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-09 17:23:53.835  8226  8226 I BluetoothA2dpServiceJni: classInitNative
,08-09 17:23:53.835  8226  8226 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-09 17:23:53.835  8226  8226 D A2dpStateMachine: make
08-09 17:23:53.838  8226  8226 I bluedroid-qcom: get_profile_interface a2dp
08-09 17:23:53.838  8226  8283 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-09 17:23:53.841  8226  8226 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-09 17:23:53.841  8226  8226 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-09 17:23:53.842  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:53.842  8226  8282 D A2dpStateMachine: Enter Disconnected: -2
08-09 17:23:53.843  8226  8226 I BluetoothHidServiceJni: classInitNative: succeeds
08-09 17:23:53.844  8226  8226 D HidService: Received start request. Starting profile...
08-09 17:23:53.844  8226  8226 I bluedroid-qcom: get_profile_interface hidhost
08-09 17:23:53.844  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:53.847  8226  8226 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-09 17:23:53.849  8226  8226 D HealthService: Received start request. Starting profile...
08-09 17:23:53.851  8226  8226 I bluedroid-qcom: get_profile_interface health
08-09 17:23:53.851  8226  8226 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-09 17:23:53.851  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:53.852  8226  8226 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-09 17:23:53.854  8226  8226 D PanService: Received start request. Starting profile...
08-09 17:23:53.854  8226  8226 D BluetoothPanServiceJni: initializeNative(L110): pan
08-09 17:23:53.854  8226  8226 I bluedroid-qcom: get_profile_interface pan
08-09 17:23:53.863  8226  8226 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-09 17:23:53.864  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:53.866  8226  8226 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-09 17:23:53.870  8226  8226 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 17:23:53.871  8226  8226 D BtGatt.GattService: Received start request. Starting profile...
08-09 17:23:53.871  8226  8226 D BtGatt.GattService: start()
08-09 17:23:53.871  8226  8226 I bluedroid-qcom: get_profile_interface gatt
08-09 17:23:53.871  8226  8226 D BtGatt.AdvertiseManager: advertise manager created
08-09 17:23:53.882  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
,08-09 17:23:53.887  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:53.888  8226  8226 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-09 17:23:53.890  8226  8226 V BluetoothMapService: BluetoothMapBinder()
08-09 17:23:53.891  8226  8226 D BluetoothMapService: Received start request. Starting profile...
08-09 17:23:53.891  8226  8226 D BluetoothMapService: start()
08-09 17:23:53.894  8226  8226 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-09 17:23:53.894  8226  8226 D BluetoothMapEmailAppObserver: createReceiver()
,08-09 17:23:53.896  8226  8226 D BluetoothMapEmailAppObserver: initObservers()
,08-09 17:23:53.896  8226  8226 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-09 17:23:53.904  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:53.905  8226  8226 D HeadsetStateMachine: Proxy object connected
08-09 17:23:53.906  8226  8226 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-09 17:23:53.906  8226  8226 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-09 17:23:53.909  8226  8278 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-09 17:23:53.910  8226  8278 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 17:23:53.910  8226  8278 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-09 17:23:53.914  8226  8226 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 17:23:53.920  8226  8226 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-09 17:23:53.926  8226  8226 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 17:23:53.929  8226  8226 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:53.934  8226  8226 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 17:23:53.935  8226  8226 V PanService: [BTUI] SIM Extra State :ABSENT
,08-09 17:23:53.939  8226  8226 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 17:23:53.943  8226  8226 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-09 17:23:53.943  8226  8226 V BluetoothMapService: Handler(): got msg=1
08-09 17:23:53.944  8226  8226 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 17:23:53.944  8226  8226 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 17:23:53.944  8226  8226 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 17:23:53.944  8226  8226 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:53.945  8226  8226 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-09 17:23:53.945  8226  8260 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-09 17:23:53.946  8226  8260 I bluedroid-qcom: enable
08-09 17:23:53.947  8226  8260 I bt_hci_bdroid: init
08-09 17:23:53.952  8226  8260 I bt_vendor: bt-vendor : init
,08-09 17:23:53.952  8226  8260 I bt_vendor: bt-vendor : get_bt_soc_type
08-09 17:23:53.952  8226  8260 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-09 17:23:53.952  8226  8260 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
,08-09 17:23:53.952  8226  8260 D bt_userial_mct: userial_init
08-09 17:23:53.953  8226  8290 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-09 17:23:53.953  8226  8290 I bt-btu  : btu_task pending for preload complete event
08-09 17:23:53.954  8226  8260 D bt_hci_bdroid: set_power 1
08-09 17:23:53.954  8226  8260 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-09 17:23:53.954  8226  8260 I bt_vendor: Starting hciattach daemon
08-09 17:23:53.954  8226  8260 I bt_vendor: try to set true
08-09 17:23:53.949  8293  8293 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:53.949  8293  8293 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:53.995  8294  8294 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-09 17:23:54.097  8300  8300 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-09 17:23:54.111  8301  8301 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-09 17:23:54.137  8303  8303 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-09 17:23:54.150  8304  8304 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-09 17:23:54.166  8305  8305 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-09 17:23:54.182  8306  8306 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-09 17:23:54.215  8308  8308 I libmdmdetect: ESOC framework not supported
08-09 17:23:54.216  8308  8308 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-09 17:23:54.224  8308  8308 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-09 17:23:54.224  8308  8308 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-09 17:23:54.224  8308  8308 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-09 17:23:54.224  8308  8308 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-09 17:23:54.224  8308  8308 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-09 17:23:54.224  8308  8308 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-09 17:23:54.224  8308  8308 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-09 17:23:54.263  8308  8312 E QC-QMI  : qmi_client [8308] 15: failed to locate client data
,08-09 17:23:54.270   480   480 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-09 17:23:54.270   480   480 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-09 17:23:54.294  8316  8316 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-09 17:23:54.309  8317  8317 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-09 17:23:54.365  8226  8260 I bt_vendor: bluetooth satus is on
,08-09 17:23:54.365  8226  8260 D bt_hci_bdroid: preload
,08-09 17:23:54.374  8226  8292 D bt_userial_mct: userial_open(port:0)
,08-09 17:23:54.374  8226  8292 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-09 17:23:54.379  8226  8292 I bt_vendor: Done intiailizing UART
08-09 17:23:54.383  8226  8292 I bt_vendor: Done intiailizing UART
08-09 17:23:54.383  8226  8292 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-09 17:23:54.383  8226  8292 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-09 17:23:54.385  8226  8290 I bt-btu  : btu_task received preload complete event
,08-09 17:23:54.386  8226  8290 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-09 17:23:54.386  8226  8290 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-09 17:23:54.400  8226  8319 D bt_userial_mct: Entering userial_read_thread()
08-09 17:23:54.401  8226  8290 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_HCI
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_AVDT
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_AVRC
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_A2D
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 17:23:54.409  8226  8290 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 17:23:54.520  8226  8290 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-09 17:23:54.521  8226  8290 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014b061 
08-09 17:23:54.521  8226  8290 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014b061 
,08-09 17:23:54.571  8226  8264 E bt-btif : Calling BTA_HhEnable
,08-09 17:23:54.571  8226  8264 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-09 17:23:54.572  8226  8264 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-09 17:23:54.584  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-09 17:23:54.585  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
,08-09 17:23:54.586  8226  8290 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-09 17:23:54.586  8226  8290 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017,
08-09 17:23:54.586  8226  8290 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-09 17:23:54.587  8226  8290 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-09 17:23:54.587  8226  8290 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-09 17:23:54.592  8226  8264 D BluetoothAdapterProperties: Name is: G3
,08-09 17:23:54.602  8226  8264 D BluetoothAdapterProperties: Scan Mode:20
08-09 17:23:54.602  8226  8264 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 17:23:54.602  8226  8264 D bt_hci_bdroid: postload
08-09 17:23:54.603  8226  8292 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 17:23:54.604  8226  8290 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-09 17:23:54.604  8226  8264 D bte_conf: Device ID record 1 : primary
08-09 17:23:54.604  8226  8264 D bte_conf:   vendorId            = 00c4
08-09 17:23:54.604  8226  8264 D bte_conf:   vendorIdSource      = 0001
08-09 17:23:54.605  8226  8264 D bte_conf:   product             = 13a1
08-09 17:23:54.605  8226  8264 D bte_conf:   version             = 1000
08-09 17:23:54.605  8226  8264 D bte_conf:   clientExecutableURL = 
08-09 17:23:54.605  8226  8264 D bte_conf:   serviceDescription  = 
08-09 17:23:54.605  8226  8264 D bte_conf:   documentationURL    = 
08-09 17:23:54.605  8226  8264 D bte_conf: bte_load_did_conf no section named DID2.
08-09 17:23:54.606  8226  8292 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 17:23:54.609  8226  8260 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-09 17:23:54.609  8226  8260 D BluetoothAdapterProperties: ScanMode =  20
08-09 17:23:54.609  8226  8260 D BluetoothAdapterProperties: State =  11
,08-09 17:23:54.612  8226  8260 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-09 17:23:54.613  8226  8260 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-09 17:23:54.613  8226  8260 D BluetoothAdapterProperties: Setting state to 12
08-09 17:23:54.613  8226  8260 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-09 17:23:54.613  8226  8264 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-09 17:23:54.614  8226  8264 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-09 17:23:54.609  8321  8321 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:54.609  8321  8321 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:54.629  8226  8292 D bt_hci_bdroid: Used up Tx Cmd credits
,08-09 17:23:54.638  8226  8290 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:54.638  8226  8290 W bt-smp  : Plain text(LSB ~ MSB) = 05 35 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:54.638  8226  8290 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 99 0c 32 4d 45 85 87 59 cf 46 ec 92 6a 67 75 
08-09 17:23:54.638  8226  8292 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 17:23:54.638  8226  8290 W bt-btm  : Stopping oneshot timer
08-09 17:23:54.639  8226  8319 E bt_mct  : hci lib postload completed
08-09 17:23:54.641  1037  1098 D BluetoothManagerService: Message: 60
08-09 17:23:54.641  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-09 17:23:54.641  1037  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-09 17:23:54.645  8226  8264 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 17:23:54.645  8226  8264 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-09 17:23:54.649  8226  8260 I BluetoothAdapterState: Entering On State
08-09 17:23:54.659  1880  1896 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 17:23:54.668  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:54.668  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:54.668  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:54.668  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:54.668  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:54.668  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:54.668  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:54.668  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:54.676  8226  8290 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:54.676  8226  8290 W bt-smp  : Plain text(LSB ~ MSB) = 21 14 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:54.676  8226  8290 W bt-smp  : Encrypted text(LSB ~ MSB) = 5d 12 a5 07 d3 b6 4a e2 13 dd 78 cd bb 0f 45 ae 
,08-09 17:23:54.679  8226  8290 W bt-btm  : Stopping oneshot timer
08-09 17:23:54.680  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:54.691  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:54.691  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:54.691  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:54.691  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:54.691  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:54.691  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:54.691  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:54.691  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 17:23:54.694  8226  8290 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:54.694  8226  8290 W bt-smp  : Plain text(LSB ~ MSB) = ea 67 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:54.694  8226  8290 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 f1 73 68 dc 98 00 4e 88 f1 b3 bd 7f 3b 56 37 
08-09 17:23:54.698  8226  8290 W bt-btm  : Stopping oneshot timer
08-09 17:23:54.706  8226  8290 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:54.706  8226  8290 W bt-smp  : Plain text(LSB ~ MSB) = da 4f 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:54.706  8226  8290 W bt-smp  : Encrypted text(LSB ~ MSB) = 0f f3 04 d8 24 ca 43 46 7c b7 1a ae 09 42 94 2c 
,08-09 17:23:54.709  8226  8290 W bt-btm  : Stopping oneshot timer
08-09 17:23:54.709  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:54.726  8226  8260 D LGBluetoothServiceAdapter: [BTUI] OnState
08-09 17:23:54.726  8226  8260 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-09 17:23:54.726  8226  8260 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-09 17:23:54.735  8226  8290 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 17:23:54.735  8226  8260 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-09 17:23:54.735  8226  8290 W bt-smp  : Plain text(LSB ~ MSB) = a4 96 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 17:23:54.735  8226  8290 W bt-smp  : Encrypted text(LSB ~ MSB) = de 4c 0e f7 03 f2 51 6c 3e 2e ce 32 61 2e 50 1f 
08-09 17:23:54.735  8226  8260 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-09 17:23:54.736  8226  8290 W bt-btm  : Stopping oneshot timer
08-09 17:23:54.737  7178  7197 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 17:23:54.739  1880  1880 D BluetoothHeadset: Proxy object connected
,08-09 17:23:54.743  1037  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 17:23:54.745  1037  1037 D BluetoothHeadset: Proxy object connected
08-09 17:23:54.747  1880  4325 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 17:23:54.751  1880  1880 D BluetoothHeadset: Proxy object connected
08-09 17:23:54.751  1880  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 17:23:54.753  8326  8326 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-09 17:23:54.754  1880  1880 D BluetoothHeadset: Proxy object connected
08-09 17:23:54.754  1037  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 17:23:54.756  7178  7196 D BluetoothPan: onBluetoothStateChange on: true
08-09 17:23:54.756  7178  7196 D BluetoothPan: onBluetoothStateChange call bindService
08-09 17:23:54.756  1037  1037 D BluetoothA2dp: Proxy object connected
08-09 17:23:54.759  7178  7197 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 17:23:54.760  7178  7178 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 17:23:54.760  7178  7178 D PanProfile: Bluetooth service connected
08-09 17:23:54.762  7178  7196 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 17:23:54.764  7178  7197 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 17:23:54.765  7178  7178 D BluetoothInputDevice: Proxy object connected
08-09 17:23:54.765  7178  7178 D HidProfile: Bluetooth service connected
08-09 17:23:54.766  7178  7197 D BluetoothMap: onBluetoothStateChange: up=true
08-09 17:23:54.767  7178  7178 D BluetoothA2dp: Proxy object connected
08-09 17:23:54.767  7178  7178 D A2dpProfile: Bluetooth service connected
08-09 17:23:54.769  1037  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-09 17:23:54.770  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-09 17:23:54.770  1037  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-09 17:23:54.770  7178  7178 D BluetoothHeadset: Proxy object connected
08-09 17:23:54.770  7178  7178 D HeadsetProfile: Bluetooth service connected
08-09 17:23:54.770  1037  1098 D BluetoothManagerService: Message: 40
08-09 17:23:54.770  1037  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-09 17:23:54.771  1971  1971 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:54.771  1971  2177 D LGBluetoothAPIService: Message: 1
08-09 17:23:54.771  1971  2177 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-09 17:23:54.771  1971  2177 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-09 17:23:54.772  1971  2177 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-09 17:23:54.772  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-09 17:23:54.777  8226  8226 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:54.777  8226  8226 D BluetoothMapService: STATE_ON
08-09 17:23:54.779  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:54.780  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:54.782  7178  7178 D BluetoothMap: Proxy object connected
08-09 17:23:54.782  7178  7178 D MapProfile: Bluetooth service connected
08-09 17:23:54.782  7178  7178 D BluetoothMap: getConnectedDevices()
08-09 17:23:54.783  8226  8344 V BluetoothMapService: getConnectedDevices()
08-09 17:23:54.787  7178  7178 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-09 17:23:54.788  7178  7178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-09 17:23:54.793  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:54.793  8226  8226 V BluetoothPbapService: Pbap Service onCreate
08-09 17:23:54.793  8226  8226 V BluetoothPbapService: Starting PBAP service
08-09 17:23:54.795  8226  8226 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-09 17:23:54.795  8226  8226 V BluetoothPbapService: Pbap Service onBind
08-09 17:23:54.796  8226  8226 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:54.796  8226  8226 V BluetoothPbapService: state: 12
08-09 17:23:54.796  8226  8226 V BluetoothMapService: Handler(): got msg=1
08-09 17:23:54.798  8226  8226 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-09 17:23:54.798  8226  8226 V BluetoothPbapService: Handler(): got msg=1
08-09 17:23:54.799  8226  8226 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-09 17:23:54.800  8226  8226 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 17:23:54.800  8226  8226 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:54.800  8226  8226 V BluetoothPbapReceiver: ***********state = 12
,08-09 17:23:54.800  7178  7178 D DockEventReceiver: finishStartingService: stopping service
08-09 17:23:54.801  8226  8347 V BluetoothPbapService: Pbap Service initSocket
08-09 17:23:54.801  8226  8346 D BluetoothMapMasInstance: MAS initSocket()
08-09 17:23:54.801  8226  8346 D BluetoothMapMasInstance:   masId = 00
08-09 17:23:54.801  8226  8346 D BluetoothMapMasInstance:   msgTypes = 0e
08-09 17:23:54.801  8226  8346 D BluetoothMapMasInstance:   masName = SMS/MMS
08-09 17:23:54.801  8226  8346 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-09 17:23:54.803  1037  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:54.804  7178  7178 D BluetoothPbap: Proxy object connected
08-09 17:23:54.804  7178  7178 D PbapServerProfile: Bluetooth service connected
08-09 17:23:54.805  1037  1653 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:54.806  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 17:23:54.806  2230  2230 D c       : Getting all permits...
08-09 17:23:54.806  2230  2230 D a       : Opening database...
08-09 17:23:54.807  8226  8346 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 17:23:54.809  8226  8346 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-09 17:23:54.809  8226  8264 D BluetoothAdapterProperties: Scan Mode:21
08-09 17:23:54.810  8226  8264 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-09 17:23:54.809  8226  8346 V BluetoothMapMasInstance: Succeed to create listening socket 
08-09 17:23:54.812  8226  8346 D BluetoothMapMasInstance: Accepting socket connection...
,08-09 17:23:54.813  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:54.814  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:54.814  2230  2230 D a       : Opening database auth.proximity.permit_store...
08-09 17:23:54.816  2230  2230 D a       : Closing database...
08-09 17:23:54.822  8226  8347 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 17:23:54.825  8226  8347 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,08-09 17:23:54.825  8226  8347 V BluetoothPbapService: Succeed to create listening socket 
08-09 17:23:54.825  8226  8347 V BluetoothPbapService: Accepting socket connection...
08-09 17:23:54.828  7178  7178 D BluetoothPermissionRequest: onReceive
08-09 17:23:54.829  7178  7178 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-09 17:23:54.830  7178  7178 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 17:23:54.833  8226  8226 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-09 17:23:54.834  8226  8226 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-09 17:23:54.838  8226  8226 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-09 17:23:54.852  8226  8226 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-09 17:23:54.852  8226  8226 V BtOppService: onCreate
08-09 17:23:54.855  8226  8226 V BluetoothOppNotification: send message
08-09 17:23:54.857  8226  8226 V BtOppService: Starting RfcommListener
08-09 17:23:54.865  8226  8352 V BtOppService: Deleted complete outbound shares, number =  0
,08-09 17:23:54.866  8226  8226 D BluetoothOppPreference: Dumping Names:  
08-09 17:23:54.866  8226  8226 D BluetoothOppPreference: {}
08-09 17:23:54.866  8226  8226 D BluetoothOppPreference: Dumping Channels:  
08-09 17:23:54.866  8226  8352 V BtOppService: Deleted complete inbound failed shares, number = 0
08-09 17:23:54.866  8226  8226 D BluetoothOppPreference: {}
08-09 17:23:54.867  8226  8226 V BtOppService: onStartCommand
08-09 17:23:54.868  8226  8352 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-09 17:23:54.869  8226  8352 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2756256c on behalf of 
08-09 17:23:54.871  8226  8226 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:54.871  8226  8226 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-09 17:23:54.872  8226  8355 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-09 17:23:54.873  8226  8355 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 17:23:54.874  8226  8226 V BluetoothOppNotification: new notify threadi!
08-09 17:23:54.875  8226  8226 V BluetoothOppNotification: send delay message
08-09 17:23:54.875  8226  8226 V BtOppService: start RfcommListener
08-09 17:23:54.876  8226  8355 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c9d0735 on behalf of 
08-09 17:23:54.877  8226  8226 V BtOppService: RfcommListener started
08-09 17:23:54.877  8226  8226 V BtOppService: ContentObserver received notification
08-09 17:23:54.878  8226  8226 V BtOppService: ContentObserver received notification
,08-09 17:23:54.879  8226  8356 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-09 17:23:54.883  8226  8355 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-09 17:23:54.883  8226  8355 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 17:23:54.883  8226  8357 V BtOppRfcommListener: Starting RFCOMM listener....
08-09 17:23:54.884  1037  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:54.885  8226  8357 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 17:23:54.886  8226  8357 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-09 17:23:54.886  8226  8357 V BtOppRfcommListener: Started RFCOMM listener....
08-09 17:23:54.886  8226  8357 I BtOppRfcommListener: Accept thread started.
08-09 17:23:54.886  8226  8357 V BtOppRfcommListener: Accepting connection...
08-09 17:23:54.888  8226  8355 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f0c67ca on behalf of 
08-09 17:23:54.888  8226  8356 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23ed3b on behalf of 
08-09 17:23:54.889  8226  8355 V BluetoothOppNotification: update too frequent, put in queue
08-09 17:23:54.890  8226  8355 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-09 17:23:54.890  8226  8356 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-09 17:23:54.891  8226  8356 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-09 17:23:54.893  8226  8356 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38362c58 on behalf of 
,08-09 17:23:54.895  8226  8356 V BluetoothOppNotification: outbound: succ-0  fail-0
08-09 17:23:54.897  8226  8356 V BluetoothOppNotification: outbound notification was removed.
08-09 17:23:54.897  8226  8356 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-09 17:23:54.897  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:54.897  8226  8226 V BluetoothFtpService: Ftp Service onCreate
08-09 17:23:54.897  8226  8226 I BluetoothFtpService: Ftp Service onCreate
08-09 17:23:54.898  8226  8226 V BluetoothFtpService: Ftp Service onStartCommand
08-09 17:23:54.898  8226  8226 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:54.898  8226  8226 V BluetoothFtpService: Starting Listening on sockets
08-09 17:23:54.898  8226  8356 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38713696 on behalf of 
08-09 17:23:54.899  8226  8226 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 17:23:54.899  8226  8226 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 17:23:54.899  8226  8226 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 17:23:54.899  8226  8226 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:54.899  8226  8226 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-09 17:23:54.899  8226  8226 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-09 17:23:54.900  8226  8356 V BluetoothOppNotification: inbound: succ-0  fail-0
08-09 17:23:54.902  8226  8356 V BluetoothOppNotification: inbound notification was removed.
08-09 17:23:54.902  8226  8356 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-09 17:23:54.904  8226  8226 V BluetoothFtpService: Handler(): got msg=1
08-09 17:23:54.904  8226  8356 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14da2217 on behalf of 
08-09 17:23:54.905  8226  8226 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-09 17:23:54.905  8226  8226 V BluetoothFtpService: Ftp Service initSocket
,08-09 17:23:54.910  1037  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:54.911  8226  8226 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 17:23:54.917  8226  8226 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-09 17:23:54.917  8226  8226 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-09 17:23:54.923  8226  8358 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-09 17:23:54.952  8226  8226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1efb51b0
08-09 17:23:54.952  8226  8226 V BluetoothSapService: Sap Service onCreate
,08-09 17:23:54.955  8226  8226 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 17:23:54.955  8226  8226 V BluetoothSapService: state: 12
08-09 17:23:54.955  8226  8226 V BluetoothSapService: Starting SAP server process
08-09 17:23:54.957  8226  8226 V BluetoothSapService: SAP Service startRfcommListenerThread
08-09 17:23:54.949  8359  8359 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:54.949  8359  8359 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:54.960  8226  8360 V BluetoothSapService: Sap Service initRfcommSocket
08-09 17:23:54.961  1037  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:23:54.962  8226  8360 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 17:23:54.964  8226  8360 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-09 17:23:54.964  8226  8360 V BluetoothSapService: Succeed to create listening socket 
08-09 17:23:54.964  8226  8360 V BluetoothSapService: Accepting socket connection...
,08-09 17:23:54.977  8359  8359 V BT_SAP  : Event pipe created
,08-09 17:23:54.977  8359  8359 V BT_SAP  : create_server_socket qcom.sap.server
,08-09 17:23:54.977  8359  8359 V BT_SAP  : created socket fd 6
,08-09 17:23:55.368  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:55.368  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:55.368  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:55.368  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 17:23:55.368  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:55.368  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:55.368  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:55.368  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 17:23:55.383  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:55.385  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:55.385  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20897500 removed from the list
08-09 17:23:55.385  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:55.385  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:55.386  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:55.387  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:23:55.387  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a2d0139 added. We now have 4 listener(s)
,08-09 17:23:55.389  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:23:55.392  1037  1970 D WifiServiceImplEx: setWifiEnabled: false pid=7054, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 17:23:55.393  1037  1970 D WifiService: setWifiEnabled: false pid=7054, uid=10118
08-09 17:23:55.393  1037  1970 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 17:23:55.397  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:55.401  1037  2267 D WifiServiceImplEx: setWifiEnabled: true pid=7054, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-09 17:23:55.404  1037  2267 D WifiService: setWifiEnabled: true pid=7054, uid=10118
08-09 17:23:55.404  1037  2267 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 17:23:55.421  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-09 17:23:55.422  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-09 17:23:55.422  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-09 17:23:55.423  1037  1541 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-09 17:23:55.423  1037  1541 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-09 17:23:55.426  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-09 17:23:55.426  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-09 17:23:55.426  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-09 17:23:55.426  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-09 17:23:55.426  1037  1541 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-09 17:23:55.426  1037  1541 E WifiHW  : unknown target_country: EU , set to default
,08-09 17:23:55.426  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-09 17:23:55.426  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-09 17:23:55.426  1037  1541 I WifiUtil: gEnableBmps=1
,08-09 17:23:55.877  8226  8226 V BluetoothOppNotification: new notify threadi!,
08-09 17:23:55.878  8226  8226 V BluetoothOppNotification: send delay message
,08-09 17:23:55.901  8226  8379 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-09 17:23:55.905  8226  8379 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e54c8b3 on behalf of 
08-09 17:23:55.905  8226  8379 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-09 17:23:55.907  8226  8379 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-09 17:23:55.908  8226  8379 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2cb22e70 on behalf of 
08-09 17:23:55.909  8226  8379 V BluetoothOppNotification: outbound: succ-0  fail-0
08-09 17:23:55.910  8226  8379 V BluetoothOppNotification: outbound notification was removed.
08-09 17:23:55.911  8226  8379 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-09 17:23:55.912  8226  8379 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ca415e9 on behalf of 
08-09 17:23:55.912  8226  8379 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-09 17:23:55.917  8226  8379 V BluetoothOppNotification: inbound notification was removed.
08-09 17:23:55.917  8226  8379 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-09 17:23:56.001   311   896 D SoftapController: Softap fwReload - Ok
,08-09 17:23:56.015  1037  1541 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (586ms)
,08-09 17:23:56.020  1037  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-09 17:23:56.020  1037  1098 D Tethering: InitialState.processMessage what=4
08-09 17:23:56.021  1037  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-09 17:23:56.034   311   896 D CommandListener: Setting iface cfg
08-09 17:23:56.034   311   896 D CommandListener: Trying to bring down wlan0
08-09 17:23:56.035   311   896 D CommandListener: Clearing all IP addresses on wlan0
08-09 17:23:56.043  1037  1541 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-09 17:23:56.039  8381  8381 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:56.049  8381  8381 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-09 17:23:56.095  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 17:23:56.095  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-09 17:23:56.095  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 17:23:56.095  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 17:23:56.095  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-09 17:23:56.095  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 17:23:56.095  7178  7178 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-09 17:23:56.097  1037  1541 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-09 17:23:56.097  1037  1541 D WifiMonitor: connecting to supplicant
,08-09 17:23:56.102  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-09 17:23:56.106  7178  7178 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 17:23:56.106  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-09 17:23:56.107  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 17:23:56.107  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 17:23:56.107  7178  7178 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 17:23:56.107  7178  7178 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 17:23:56.111  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 17:23:56.113  8381  8381 I wpa_supplicant: Successfully initialized wpa_supplicant
08-09 17:23:56.116  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-09 17:23:56.116  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:56.117  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:23:56.118  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-09 17:23:56.146  8381  8381 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-09 17:23:56.146  8381  8381 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-09 17:23:56.173  1037  1933 I art     : Explicit concurrent mark sweep GC freed 25062(1238KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.418ms total 252.402ms
08-09 17:23:56.174  8226  8379 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bc0826e on behalf of 
,08-09 17:23:56.177  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 17:23:56.177  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 17:23:56.177  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 17:23:56.177  7178  7178 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 17:23:56.178  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-09 17:23:56.179  7178  7178 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 17:23:56.179  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-09 17:23:56.179  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 17:23:56.179  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 17:23:56.179  7178  7178 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 17:23:56.179  7178  7178 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 17:23:56.214  8381  8381 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-09 17:23:56.232  1037  2091 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8398 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-09 17:23:56.260  8381  8381 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-09 17:23:56.263  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-09 17:23:56.264  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-09 17:23:56.264  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-09 17:23:56.264  1037  1541 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-09 17:23:56.265  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:56.265  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:56.265  1037  1541 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-09 17:23:56.265  1037  1541 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-09 17:23:56.265  1037  1541 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-09 17:23:56.266  1037  1541 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-09 17:23:56.266  1037  1541 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-09 17:23:56.266  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 17:23:56.266  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-09 17:23:56.266  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 17:23:56.266  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.266  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.266  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.266  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.266  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 17:23:56.267  1971  1971 D WfdService: Waiting for WifiP2p enabling
08-09 17:23:56.267  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:56.267  1037  1541 D WifiNative-wlan0: doBoolean: SET update_config 1
08-09 17:23:56.268  1037  1541 D WifiNative-wlan0: SET update_config 1: returned true
08-09 17:23:56.268  1037  1541 D WifiConfigStore: Loading config and enabling all networks 
08-09 17:23:56.268  1037  1541 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-09 17:23:56.268  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-09 17:23:56.268  1037  1541 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-09 17:23:56.268  1037  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-09 17:23:56.271  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:56.271  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:56.271  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:56.271  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:56.271  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:56.271  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:56.271  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:56.271  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:56.272  1037  1541 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-09 17:23:56.272  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 17:23:56.275  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:56.275  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:56.275  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:56.275  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:56.275  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:56.275  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 17:23:56.275  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 17:23:56.275  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 17:23:56.276  1037  1541 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-09 17:23:56.276  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 17:23:56.276  1037  1541 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 17:23:56.277  1037  1541 D WifiStateMachine: enableVerboseLogging : level 2
08-09 17:23:56.277  1037  1541 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-09 17:23:56.277  1037  1541 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-09 17:23:56.277  1037  1541 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-09 17:23:56.278  1037  1541 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-09 17:23:56.278  1037  1541 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-09 17:23:56.278  1037  1541 D WifiNative-wlan0: SET model_name LG-D855: returned true
,08-09 17:23:56.278  1037  1541 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-09 17:23:56.278  1037  1541 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-09 17:23:56.279  1037  1541 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-09 17:23:56.279  1037  1541 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-09 17:23:56.279  1037  1541 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-09 17:23:56.279  1037  1541 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-09 17:23:56.279  1037  1541 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-09 17:23:56.280  1037  1541 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-09 17:23:56.280  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-09 17:23:56.280  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-09 17:23:56.280  8381  8381 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-09 17:23:56.280  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-09 17:23:56.281  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-09 17:23:56.281  1037  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-09 17:23:56.281  1037  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-09 17:23:56.281  1971  1971 D WfdsService: Supplicant Connection state is changed : true
08-09 17:23:56.281  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-09 17:23:56.281  1971  2295 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-09 17:23:56.281  1971  2295 D WfdsService: Set the WFDS Monitor: true
08-09 17:23:56.281  1037  1541 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-09 17:23:56.281  1971  2295 D WfdsMonitor: WfdsMonitorThread create
08-09 17:23:56.281  1971  2295 D WfdsMonitor: WFDS Monitor is created and started
08-09 17:23:56.281  1971  2295 D WfdsService: WiFi: Supplicant connection re-established
08-09 17:23:56.281  1037  1541 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-09 17:23:56.281  1037  1541 D WifiNative-HAL: Setting external_sim to 1
08-09 17:23:56.281  1037  1541 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-09 17:23:56.281  7988  7988 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.282  1037  1541 D WifiNative-wlan0: SET external_sim 1: returned true
08-09 17:23:56.282  1037  1541 I WifiNative-HAL: startHal
08-09 17:23:56.282  1037  1541 D wifi    : setting scan oui 0xaf67f2e0
08-09 17:23:56.282  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-09 17:23:56.282  1037  1541 I WifiNative-HAL: startHal
08-09 17:23:56.282  1037  1541 D wifi    : setting scan oui 0xaf67f2e0
08-09 17:23:56.282  1971  8418 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-09 17:23:56.282  1037  1541 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-09 17:23:56.282  1971  8418 E CtrlSupplicant: Succeed to open control connection
08-09 17:23:56.282  1037  1541 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-09 17:23:56.283  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-09 17:23:56.283  1971  8418 E CtrlSupplicant: Succeed to open monitor connection
08-09 17:23:56.283  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-09 17:23:56.283  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-09 17:23:56.283  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-09 17:23:56.283  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-09 17:23:56.284  1971  8418 D WfdsMonitor: Supplicant connection established
08-09 17:23:56.284  1971  2295 D WfdsService: Connected to the s,upplicant for wfds
08-09 17:23:56.284  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-09 17:23:56.284  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-09 17:23:56.284  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-09 17:23:56.284  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-09 17:23:56.284  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-09 17:23:56.284  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-09 17:23:56.285  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-09 17:23:56.285  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-09 17:23:56.285  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-09 17:23:56.285  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-09 17:23:56.285  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-09 17:23:56.285  8381  8381 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-09 17:23:56.286  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-09 17:23:56.286  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-09 17:23:56.286  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-09 17:23:56.287  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-09 17:23:56.287  1037  1541 E WifiNative: : [404,026,893 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-09 17:23:56.287  1037  1541 D WifiNative-wlan0: doBoolean: RECONNECT
08-09 17:23:56.288  1037  1541 D WifiNative-wlan0: RECONNECT: returned true
08-09 17:23:56.288  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-09 17:23:56.288  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-09 17:23:56.288  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-09 17:23:56.289  1037  1541 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-09 17:23:56.289  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 17:23:56.289  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-09 17:23:56.289  1037  1540 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.291   311   896 D CommandListener: Setting iface cfg
08-09 17:23:56.291   311   896 D CommandListener: Trying to bring up p2p0
08-09 17:23:56.291  1037  1540 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-09 17:23:56.291  1037  1540 D LGWifiP2pService: P2pEnablingState
08-09 17:23:56.291  1037  1540 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.291  1037  1540 D LGWifiP2pService: P2p socket connection successful
08-09 17:23:56.291  1037  1540 D LGWifiP2pService: P2pEnabledState
08-09 17:23:56.292  1037  1540 D LGWifiP2pService: sending p2p connection changed broadcast
08-09 17:23:56.292  1971  1971 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-09 17:23:56.292  1971  1971 D WfdsService: WifiP2pState is changed : true
08-09 17:23:56.292  1971  2295 D WfdsService: Receive the WFDS_ENABLE Method
08-09 17:23:56.292  1971  2295 D WfdsService: Set the WFDS Monitor: true
08-09 17:23:56.292  1971  2295 D WfdsService: Connected to the supplicant for wfds
08-09 17:23:56.293  1971  2295 D WfdsJNI : doCommand: WFDS_SET TRUE
08-09 17:23:56.293  8381  8381 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-09 17:23:56.293  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-09 17:23:56.293  1971  2295 D WfdsService: selectPreferredScanChannel [36]
08-09 17:23:56.293  1971  2295 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-09 17:23:56.293  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
08-09 17:23:56.293  1037  1541 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-09 17:23:56.293  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-09 17:23:56.293  1037  1559 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.293  1037  1559 I WifiNative-HAL: startHal
08-09 17:23:56.293  1037  1541 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-09 17:23:56.293  1037  1559 D wifi    : getting scan capabilities on interface[1] = 0xaf67f2e0
08-09 17:23:56.294  1037  1541 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-09 17:23:56.294  1037  1560 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.294  1037  1541 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-09 17:23:56.294  1037  1541 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-09 17:23:56.294  1037  1559 D wifi    : failed to get capabilities : -3
08-09 17:23:56.294  1037  1559 E WifiScanningService: could not get scan capabilities
08-09 17:23:56.294  1037  1541 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-09 17:23:56.294  1037  1541 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-09 17:23:56.294  8381  8381 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-09 17:23:56.295  1037  1540 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-09 17:23:56.295  1037  1540 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-09 17:23:56.295  1037  1540 D WifiNative-p2p0: doBoolean: SET device_name G3
08-09 17:23:56.295  1037  1541 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-09 17:23:56.295  1037  1541 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-09 17:23:56.296  1971  1971 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-09 17:23:56.296  1037  1540 D WifiNative-p2p0: SET dev,ice_name G3: returned true
08-09 17:23:56.296  1037  1540 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-09 17:23:56.296  1037  1540 D LGWifiP2pService: before postfix = G3
08-09 17:23:56.296  1037  1540 D WifiServerServiceExt: postfix byte check : 2
08-09 17:23:56.296  1037  1540 D LGWifiP2pService: after postfix = G3
08-09 17:23:56.296  1037  1540 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-09 17:23:56.296  1971  1971 D WfdsService: isConnected: false
08-09 17:23:56.296  1037  1540 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-09 17:23:56.296  1037  1540 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-09 17:23:56.296  1037  1541 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-09 17:23:56.296  1037  1541 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-09 17:23:56.296  8381  8381 E wpa_supplicant: disconnect_rssi_lvl: -100
08-09 17:23:56.296  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=404036  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 17:23:56.297  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=404037  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 17:23:56.297  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-09 17:23:56.298  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-09 17:23:56.298  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-09 17:23:56.298  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-09 17:23:56.298  1037  1540 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-09 17:23:56.298  1037  1540 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-09 17:23:56.299  1037  1540 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-09 17:23:56.299  1037  1540 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-09 17:23:56.299  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:56.299  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:56.299  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.299  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.299  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-09 17:23:56.300  1037  1540 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-09 17:23:56.300  1037  1540 D WifiNative-HAL: p2pGetDeviceAddress
,08-09 17:23:56.303  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-09 17:23:56.303  8381  8381 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:56.303  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:56.303  8381  8381 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-09 17:23:56.304  8381  8381 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.304  8381  8381 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.304  1037  1541 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-09 17:23:56.305  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-09 17:23:56.305  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 17:23:56.305  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:56.305  1037  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:56.305  1037  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:56.305  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-09 17:23:56.305  1037  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:56.305  1037  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.305  1037  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.305  1037  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.305  1037  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:56.305  1037  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.305  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-09 17:23:56.305  1037  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.305  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-09 17:23:56.305  1037  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.305  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-09 17:23:56.305  8381  8381 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 17:23:56.306  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-09 17:23:56.306  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 17:23:56.306  1037  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 17:23:56.306  1037  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 17:23:56.306  1037  1541 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-09 17:23:56.306  1971  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:56.306  1971  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:56.306  1037  1541 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-09 17:23:56.306  1037  1540 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-09 17:23:56.307  1037  1541 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-09 17:23:56.307  1037  1541 D WifiNative-wlan0: doBoolean: SCAN
08-09 17:23:56.307  1037  1541 D WifiNative-wlan0: SCAN: returned false
08-09 17:23:56.307  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=404047  SSID:  BSSID: 00:0,0:00:00:00:00 nid: -1 state: SCANNING
08-09 17:23:56.309  1037  1540 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-09 17:23:56.309  1037  1540 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-09 17:23:56.309  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=404049  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 17:23:56.309  1037  1540 D WifiNative-p2p0: P2P_FLUSH: returned true
08-09 17:23:56.309  1037  1540 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-09 17:23:56.309  1037  1541 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 17:23:56.310  1037  1541 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 17:23:56.311  1037  1541 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 17:23:56.311  1037  1541 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-09 17:23:56.312  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.312  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.312  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-09 17:23:56.314  1971  1971 I WfdStateTracker: handleP2pThisDeviceChanged
08-09 17:23:56.314  1971  1971 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-09 17:23:56.314  1971  1971 D WfdsService: Update P2p Interface State: 3
08-09 17:23:56.315  1037  1540 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-09 17:23:56.315  1037  1540 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-09 17:23:56.316  1037  1540 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-09 17:23:56.316  1037  1541 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 17:23:56.316  1037  1540 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-09 17:23:56.321  1037  1540 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-09 17:23:56.321  1037  1540 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-09 17:23:56.322  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:56.322  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:56.323  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 17:23:56.352  1037  2267 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8423 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-09 17:23:56.354  1037  1540 D LGWifiP2pService: InactiveState
08-09 17:23:56.354  1037  1540 D LGWifiP2pService: InactiveState{ when=-49ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.354  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-50ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.354  1037  1540 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-09 17:23:56.355  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-09 17:23:56.355  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:56.355  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-09 17:23:56.355  8381  8381 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:56.356  1037  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 17:23:56.356  1037  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:56.356  1037  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:56.357  1037  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 17:23:56.357  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:56.357  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-09 17:23:56.358  8381  8381 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-09 17:23:56.358  1971  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 17:23:56.358  8381  8381 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.359  1037  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:56.359  1037  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.360  1037  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.360  1037  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.360  1971  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:56.360  8381  8381 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.361  1037  1540 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-09 17:23:56.361  1037  1540 D LGWifiP2pService: InactiveState{ when=-45ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.361  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-45ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.361  1037  1540 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.361  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.361  1037  1540 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.362  1971  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:56.362  1037  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 17:23:56.362  1037  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.362  1037  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.362  1037  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 17:23:56.362  8398  8421 W FormManager: Network not available. Please check & try again.
08-09 17:23:56.362  1037  1540 D LGWifi,P2pService: InactiveState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.362  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.362  1037  1540 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.363  1037  1540 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.363  1971  2295 W WfdsService: DefaultState - msg [9441285] is not handled
08-09 17:23:56.363  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.363  1037  1540 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.363  1037  1540 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.364  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.364  1037  1540 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:56.367  1037  1037 E WifiServerServiceExt: No p2p device connected
08-09 17:23:56.369  8398  8422 V FormManager: Network unavailable.
,08-09 17:23:56.373  8398  8422 V FormManager: Network unavailable.
08-09 17:23:56.388  1037  1970 I ActivityManager: Killing 7431:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-09 17:23:56.422  1037  2028 W libprocessgroup: failed to open /acct/uid_10046/pid_7431/cgroup.procs: No such file or directory
08-09 17:23:56.454  8423  8423 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 17:23:56.462  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 17:23:56.468  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:56.468  1037  1578 I ActivityManager: Killing 7451:com.android.chrome/u0a57 (adj 15): empty #17
,08-09 17:23:56.520  1037  1970 W libprocessgroup: failed to open /acct/uid_10057/pid_7451/cgroup.procs: No such file or directory
,08-09 17:23:56.536  8423  8423 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 17:23:56.539  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 17:23:56.548  8398  8444 W FormManager: Network not available. Please check & try again.
08-09 17:23:56.550  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 17:23:56.559  8398  8445 V FormManager: Network unavailable.
08-09 17:23:56.569  8398  8445 V FormManager: Network unavailable.
,08-09 17:23:56.573  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 17:23:56.574  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 17:23:56.575  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:56.577  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:23:56.590  4700  8446 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 17:23:56.592  4700  8447 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 17:23:56.593  4700  8447 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 17:23:56.648  1037  2091 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8448 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-09 17:23:56.757  8448  8448 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-09 17:23:56.757  8448  8448 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-09 17:23:56.765  8448  8448 V [BNRBootReceiver]: Boot Receiver Return
08-09 17:23:56.766  8448  8448 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-09 17:23:56.824  8381  8381 E wpa_supplicant: USIM:  scard_init function
08-09 17:23:56.825  8381  8381 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-09 17:23:56.828  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-09 17:23:56.828  1037  8417 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-09 17:23:56.828  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-09 17:23:56.828  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-09 17:23:56.828  1037  8417 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-09 17:23:56.828  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-09 17:23:56.828  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-09 17:23:56.829  1037  1541 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-09 17:23:56.830  1037  1541 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-09 17:23:56.830  1037  1541 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-09 17:23:56.830  1037  1541 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-09 17:23:56.830  1037  1541 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-09 17:23:56.833  1037  1653 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8469 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-09 17:23:56.834  1037  1653 I ActivityManager: Killing 7469:com.lge.drmservice/u0a62 (adj 15): empty #17
08-09 17:23:56.881  1037  2051 W libprocessgroup: failed to open /acct/uid_10062/pid_7469/cgroup.procs: No such file or directory
08-09 17:23:56.881  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=404621  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-09 17:23:56.895  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:56.895  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:56.897  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 17:23:56.899  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.899  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.899  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-09 17:23:56.900  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=404640  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-09 17:23:56.901  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:56.901  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-09 17:23:56.917  8469  8469 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 17:23:56.939  8381  8381 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-09 17:23:56.941  1037  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-09 17:23:56.942  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-09 17:23:56.942  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-09 17:23:56.942  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-09 17:23:56.943  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-09 17:23:56.943  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:56.943  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:56.944  1037  1541 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:56.944  1037  1541 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:56.945  1037  1541 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:56.945  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:56.945  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 17:23:56.946  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=404686  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-09 17:23:56.947  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=404686  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-09 17:23:56.948  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:56.948  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:56.948  8381  8381 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 17:23:56.948  8381  8381 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 17:23:56.948  1037  1541 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=404688
08-09 17:23:56.949  1037  1541 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=404689
08-09 17:23:56.949  1037  1541 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=404689
,08-09 17:23:56.950  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=404689
08-09 17:23:56.950  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-09 17:23:56.950  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 17:23:56.950  1037  1541 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=404690
08-09 17:23:56.951  1037  8417 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 17:23:56.951  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=404690  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-09 17:23:56.951  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-09 17:23:56.951  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 17:23:56.951  1037  8417 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 17:23:56.951  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:56.951  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:56.954  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:56.954  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:56.955  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.955  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.955  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-09 17:23:56.956  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:56.957  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=404696  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-09 17:23:56.960  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.960  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.960  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-09 17:23:56.961  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:56.961  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-09 17:23:56.961  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=404701  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-09 17:23:56.962  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=404701  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-09 17:23:56.962  1037  1541 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=404702
08-09 17:23:56.963  1037  1541 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=404703
08-09 17:23:56.963  1037  ,1541 D WifiNative-wlan0: doString: [STATUS]
08-09 17:23:56.964  1037  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 17:23:56.964  1037  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 17:23:56.964  1037  1541 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-09 17:23:56.965  8469  8469 D PluginManager: init()
08-09 17:23:56.966  1037  1541 I WifiServiceExtension: setVHTCapabilityType  : false
,08-09 17:23:56.972  1037  1541 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-09 17:23:56.972  1037  1541 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-09 17:23:56.979  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.979  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.979  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-09 17:23:56.979  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:56.979  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:56.981  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:56.984  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.984  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:56.984  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-09 17:23:56.985  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:56.985  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:56.986  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:56.990  1037  1541 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-09 17:23:56.991  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 17:23:56.991  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 17:23:56.991  1037  1548 D ConnectivityService: Got NetworkAgent Messenger
08-09 17:23:56.991  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-09 17:23:56.991  1037  1548 D ConnectivityService: NetworkAgent connected
08-09 17:23:56.991  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 17:23:56.991  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-09 17:23:56.999  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 17:23:56.999  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 17:23:56.999  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 17:23:56.999  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 17:23:56.999  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-09 17:23:57.002  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:57.002  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:57.005  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.006  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-09 17:23:57.009   311   896 D CommandListener: Setting iface cfg
08-09 17:23:57.012  1037  1541 E WifiStateMachine: Start Dhcp Watchdog 3
08-09 17:23:57.012  1037  8492 D DhcpStateMachine: StoppedState
08-09 17:23:57.012  1037  8492 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:57.012  1037  8492 D DhcpStateMachine: WaitBeforeStartState
08-09 17:23:57.013  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=404752  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:57.013  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=404753  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:57.014  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=404753  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:57.015  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:57.015  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-09 17:23:57.016  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:57.016  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-09 17:23:57.017  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=404757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:57.017  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=404757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:57.018  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=404758  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 17:23:57.019  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:21132] from screen [on:0 period:1877421787] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 17:23:57.020  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1877421788] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 17:23:57.020  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:23:57.026  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.028  1037  1548 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-09 17:23:57.029  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.029  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.029  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.030  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.030  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.031  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.031  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-09 17:23:57.031  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=195,0,0
08-09 17:23:57.032  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=195,0,0
08-09 17:23:57.032  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-09 17:23:57.032  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-09 17:23:57.033  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-09 17:23:57.033  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 0
08-09 17:23:57.034  1037  1541 D WifiNative-wlan0: SET ps 0: returned true
08-09 17:23:57.034  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-09 17:23:57.034  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-09 17:23:57.034  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-09 17:23:57.034  1037  1540 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@300276df target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:57.034  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@300276df target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:57.035  1037  1541 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-09 17:23:57.035  1037  8492 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:57.035  1037  1541 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-09 17:23:57.035  1037  8492 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-09 17:23:57.035  1037  1541 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-09 17:23:57.036   311   896 D CommandListener: Setting iface cfg
08-09 17:23:57.037   311   896 D CommandListener: Trying to bring up wlan0
08-09 17:23:57.038  1037  1541 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-09 17:23:57.039  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:57.040  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-09 17:23:57.041  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 17:23:57.041  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-09 17:23:57.042  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.042  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.043  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.043  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.043  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.044  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 17:23:57.044  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-09 17:23:57.044  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-09 17:23:57.045  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-09 17:23:57.045  1037  1540 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:57.045  1037  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:57.046  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 17:23:57.046  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-09 17:23:57.046  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 17:23:57.046  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-09 17:23:57.047  8381  8381 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-09 17:23:57.047  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-09 17:23:57.047  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 17:23:57.063  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-09 17:23:57.063  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-09 17:23:57.064  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-09 17:23:57.064  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-09 17:23:57.064  1037  1541 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-09 17:23:57.065  1037  1548 D ConnectivityService: ignoring duplicate network state non-change
08-09 17:23:57.067  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:57.067  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 17:23:57.069  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.069  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:57.069  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:57.069  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-09 17:23:57.074  1037  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-09 17:23:57.074  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:57.074  1037  1548 D ConnectivityService: Adding iface wlan0 to network 102
08-09 17:23:57.074  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:57.075  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-09 17:23:57.076  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-09 17:23:57.078  1971  1971 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-09 17:23:57.079  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:57.079  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:57.079  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-09 17:23:57.081  1037  1541 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-09 17:23:57.083  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-09 17:23:57.087  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:57.087  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:23:57.087  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-09 17:23:57.093  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:57.093  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-09 17:23:57.098  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.100  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:57.100  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-09 17:23:57.101  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.102  1037  1548 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-09 17:23:57.102  1037  1548 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-09 17:23:57.103  1037  1548 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-09 17:23:57.104   311   896 E Netd    : netlink response contains error (File exists)
08-09 17:23:57.104  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 17:23:57.104  1037  1548 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-09 17:23:57.104  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-09 17:23:57.104  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.104  1037  1548 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-09 17:23:57.104  1037  1548 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-09 17:23:57.105  1037  1548 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-09 17:23:57.105  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-09 17:23:57.105  1037  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-09 17:23:57.105  1037  1548 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-09 17:23:57.105  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-09 17:23:57.106  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:57.106  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:57.106  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-09 17:23:57.106  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:57.106  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-09 17:23:57.106  1037  1548 D ConnectivityService: currentScore = 0, newScore = 20
08-09 17:23:57.106  1037  1548 D ConnectivityService:    accepting network in place of null
08-09 17:23:57.106  1037  1548 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:57.106  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:57.106  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-09 17:23:57.106  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:23:57.107  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-09 17:23:57.109   311  8497 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-09 17:23:57.109  1037  1541 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:57.109  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:57.110  1880  1880 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:57.110  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 17:23:57.110  1037  1548 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-09 17:23:57.110  1037  1548 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-09 17:23:57.111  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 17:23:57.111  1037  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 17:23:57.111  1037  1548 D CSLegacyTypeTracker: [,e] list.add(nai) empty : false size: 1
08-09 17:23:57.111  1037  1548 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-09 17:23:57.111  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-09 17:23:57.112  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 17:23:57.112  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 17:23:57.112  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 17:23:57.112  1037  1548 D ConnectivityService: validation of new default Network = false
08-09 17:23:57.112  1037  1548 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-09 17:23:57.112  1037  1548 D DSQN    : enableDataServiceNotify 
08-09 17:23:57.112  1037  1548 D DSQN    : start dsqn bin
08-09 17:23:57.116  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-09 17:23:57.116  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:57.116  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:57.117  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:57.117  1606  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-09 17:23:57.099  8498  8498 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:57.099  8498  8498 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:57.123  1037  1539 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-09 17:23:57.129  8498  8498 E DSQN    : DSQN ssw
,08-09 17:23:57.142  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 17:23:57.143  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.144  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.157   311  8497 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-09 17:23:57.197   311  8497 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-09 17:23:57.227   311   895 D LGDataListener: argv[0]=dsqncommand
08-09 17:23:57.227   311   895 D LGDataListener: argv[1]=wlan0
08-09 17:23:57.227   311   895 D LGDataListener: argv[2]=1
08-09 17:23:57.227   311   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-09 17:23:57.228  1037  1096 D DSQN    : DSQM DsqnNotification wlan0  1
08-09 17:23:57.229  1037  1096 D DSQN    : start to monitor internet connection
08-09 17:23:57.238  1037  8492 D DhcpStateMachine: DHCPV4 request on wlan0
08-09 17:23:57.239  1037  8492 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-09 17:23:57.239  1037  8492 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-09 17:23:57.229  8504  8504 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:57.229  8504  8504 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 17:23:57.253  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 15:23:57 GMT], X-Android-Received-Millis=[1470756237252], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470756237226]}
08-09 17:23:57.253  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-09 17:23:57.253  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-09 17:23:57.254  1037  1548 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-09 17:23:57.254  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-09 17:23:57.254  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:57.254  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-09 17:23:57.255  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-09 17:23:57.255  1037  1548 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-09 17:23:57.255  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-09 17:23:57.255  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:57.255  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:57.256  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:57.257  1037  1548 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:57.257  1606  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-09 17:23:57.257  1037  1541 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:57.257  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-09 17:23:57.257  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:23:57.261  1880  1880 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:57.261  1880  1880 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 17:23:57.269  8504  8504 I dhcpcd  : version 5.5.6 starting
08-09 17:23:57.271  8504  8504 E dhcpcd  : get_duid: m
08-09 17:23:57.271  8504  8504 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-09 17:23:57.271  8504  8504 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-09 17:23:57.278  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 17:23:57.279  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.279  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:23:57.343  8504  8504 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-09 17:23:57.343  8504  8504 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-09 17:23:57.343  8504  8504 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-09 17:23:57.344  8504  8504 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-09 17:23:57.344  8504  8504 D dhcpcd  : wlan0: sending REQUEST (xid 0x688dadce), next in 4.63 seconds
08-09 17:23:57.407  8469  8469 W ExternalStrings: load override strings
08-09 17:23:57.407  8469  8469 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 17:23:57.407  8469  8469 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 17:23:57.413  8469  8469 D StatusProvider: onCreate
,08-09 17:23:57.418  8504  8504 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-09 17:23:57.436  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:23:57.436  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:23:57.436  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:23:57.436  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:23:57.436  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:23:57.436  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:57.436  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:23:57.436  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 17:23:57.438  8504  8504 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-09 17:23:57.439  8504  8504 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-09 17:23:57.439  8504  8504 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-09 17:23:57.439  8504  8504 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-09 17:23:57.439  8504  8504 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-09 17:23:57.440  8504  8504 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-09 17:23:57.440  8504  8504 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-09 17:23:57.440  8504  8504 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-09 17:23:57.441  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:23:57.442  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:23:57.442  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a2d0139 removed from the list
08-09 17:23:57.442  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:23:57.442  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:23:57.442  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:23:57.452  7054  8512 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-09 17:23:57.452  7054  8512 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-09 17:23:57.514  8469  8469 V Signer  : override build config not found
,08-09 17:23:57.514  8469  8469 D Signer  : value of property debug is false
,08-09 17:23:57.553  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-09 17:23:57.553  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-09 17:23:57.553  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-09 17:23:57.554  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-09 17:23:57.554  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-09 17:23:57.554  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-09 17:23:57.554  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-09 17:23:57.554  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-09 17:23:57.555  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-09 17:23:57.555  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-09 17:23:57.556  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-09 17:23:57.557  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-09 17:23:57.557  8469  8469 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-09 17:23:57.592  8469  8469 V LGMDMManager: Create singleton instance
,08-09 17:23:57.669  8469  8469 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-09 17:23:57.730  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 17:23:57.730  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-09 17:23:57.741  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:57.747  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:57.796  1037  2115 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8540 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-09 17:23:57.797  1037  2115 I ActivityManager: Killing 7486:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-09 17:23:57.845  1037  8492 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-09 17:23:57.846  1037  8492 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-09 17:23:57.846  1037  8492 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-09 17:23:57.846  1037  8492 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-09 17:23:57.846  1037  8492 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-09 17:23:57.846  1037  8492 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-09 17:23:57.846  1037  8492 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-09 17:23:57.846  1037  8492 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-09 17:23:57.847  1037  8492 D DhcpStateMachine: RunningState
08-09 17:23:57.859  1037  1653 W libprocessgroup: failed to open /acct/uid_10085/pid_7486/cgroup.procs: No such file or directory
,08-09 17:23:57.875  8540  8540 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 17:23:57.891  8540  8540 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-09 17:23:57.912  8540  8540 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-09 17:23:57.912  8540  8540 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-09 17:23:57.913  8540  8540 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-09 17:23:57.913  8540  8540 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-09 17:23:57.913  8540  8540 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-09 17:23:57.914  8469  8536 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-09 17:23:57.914  8540  8540 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-09 17:23:57.917  8540  8540 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-09 17:23:57.922  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:57.923  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:57.933  8540  8540 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-09 17:23:57.936  8540  8540 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-09 17:23:57.936  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:57.937  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 17:23:57.939  8540  8540 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-09 17:23:57.943  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:57.949  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:57.955  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:57.956  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 17:23:57.959  8540  8540 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 17:23:57.962  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-09 17:23:57.964  7178  7178 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-09 17:23:57.967  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:57.968  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-09 17:23:57.974  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 17:23:57.979  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 17:23:57.988  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:57.988  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:57.989  8540  8540 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 17:23:57.992  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 17:23:57.992  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 17:23:57.992  7178  7178 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-09 17:23:57.992  7178  7178 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 17:23:57.994  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-09 17:23:57.995  7178  7178 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 17:23:57.995  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-09 17:23:57.995  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 17:23:57.995  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 17:23:57.995  7178  7178 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 17:23:57.995  7178  7178 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
,08-09 17:23:57.995  7178  7178 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 17:23:57.999  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:58.000  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 17:23:58.005  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:58.011  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 17:23:58.018  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:58.018  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:58.019  8540  8540 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 17:23:58.022  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:58.026  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 17:23:58.029  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:58.036  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:58.042  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:58.042  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:58.043  8540  8540 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 17:23:58.047  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:58.048  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 17:23:58.054  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:58.059  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:58.066  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:58.067  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:58.067  8540  8540 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 17:23:58.071  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:58.071  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 17:23:58.079  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:58.087  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 17:23:58.096  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:58.096  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:58.096  8540  8540 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 17:23:58.111  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:58.111  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 17:23:58.127  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:58.133  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:58.141  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:58.141  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 17:23:58.147  8540  8540 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 17:23:58.151  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 17:23:58.151  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:58.157  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:58.163  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:58.170  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:58.170  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:58.171  8540  8540 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 17:23:58.175  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 17:23:58.176  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 17:23:58.179  8423  8423 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-09 17:23:58.183  8423  8423 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:58.187  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:58.193  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:58.199  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:58.199  1037  1541 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 17:23:58.200  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:58.200  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 17:23:58.200  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 17:23:58.201  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 17:23:58.201  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 17:23:58.201  8540  8540 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-09 17:23:58.202  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-09 17:23:58.202  8540  8540 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-09 17:23:58.202  1037  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-09 17:23:58.202  1037  1548 D ConnectivityService: identical MTU - not setting
08-09 17:23:58.203  1037  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-09 17:23:58.203  1037  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-09 17:23:58.203  8540  8540 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-09 17:23:58.203  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:23:58.203  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:58.203  1037  1548 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:23:58.204  1606  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-09 17:23:58.207  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 17:23:58.207  8469  8537 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 17:23:58.211  8423  8423 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-09 17:23:58.211  8423  8423 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-09 17:23:58.214  7178  7178 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 17:23:58.221  8469  8536 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:23:58.221  7178  7178 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 17:23:58.221  8469  8536 D LgDataFeature: LgDataFeature() Constructor Done, null
08-09 17:23:58.227  8540  8540 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 17:23:58.227  8540  8540 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 17:23:58.228  8540  8540 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-09 17:23:58.229  8540  8540 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-09 17:23:58.229  8540  8540 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-09 17:23:58.233  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.239  8540  8540 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-09 17:23:58.249  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-09 17:23:58.249  8540  8540 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-09 17:23:58.287  8540  8540 D LgDataFeature: LgDataFeature() Constructor: none
,08-09 17:23:58.287  8540  8540 D LgDataFeature: LgDataFeature() Constructor Done, null
08-09 17:23:58.294  8540  8540 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-09 17:23:58.297  8540  8540 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-09 17:23:58.297  8540  8540 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-09 17:23:58.297  8540  8540 V SoundPool: doLoad: loading sample sampleID=1
08-09 17:23:58.298  8540  8540 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-09 17:23:58.300  8540  8575 V SoundPool: Start decode
08-09 17:23:58.300  8540  8575 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-09 17:23:58.301   316   316 V MediaPlayerService: decode(22, 10857164, 17813)
08-09 17:23:58.301   316   316 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-09 17:23:58.301   316   316 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-09 17:23:58.301   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-09 17:23:58.301   316   316 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-09 17:23:58.301   316   316 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-09 17:23:58.301   316   316 V MediaPlayerService: player type = 3
08-09 17:23:58.301   316   316 V AwesomePlayer: AwesomePlayer create()
08-09 17:23:58.302   316   316 V AwesomePlayer: reset_l() 
08-09 17:23:58.302   316   316 V AwesomePlayer: cancelPlayerEvents
08-09 17:23:58.302   316   316 V AwesomePlayer: setAudioSink() 
08-09 17:23:58.302   316   316 V AwesomePlayer: reset_l() 
08-09 17:23:58.302   316   316 V AudioCache: notify(0xb1010300, 8, 0, 0)
08-09 17:23:58.303   316   316 V AudioCache: ignored
08-09 17:23:58.303  8540  8540 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-09 17:23:58.303   316   316 V AwesomePlayer: cancelPlayerEvents
08-09 17:23:58.303   316   316 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-09 17:23:58.303   316   316 V AwesomePlayer: setDataSource_l dataSource
08-09 17:23:58.303   316   316 V LGParserOSAL: SniffLGParser start
08-09 17:23:58.303   316   316 V LGParserOSAL: MainType:5, SubType=0
08-09 17:23:58.303   316   316 V LGParserOSAL: #### check Mime : application/ogg
08-09 17:23:58.303   316   316 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-09 17:23:58.303   316   316 E MediaExtractor: Use LGExtractor :application/ogg 
08-09 17:23:58.304  8058  8058 D UEI.SmartControl: QS Service created
08-09 17:23:58.304  8540  8540 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-09 17:23:58.305  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-09 17:23:58.319  8058  8058 I UEI.SmartControl: Service initServices...
08-09 17:23:58.319  8058  8058 D UEI.SmartControl: QS start get config
,08-09 17:23:58.334   316   316 V LGParserOSAL: supported mime: application/ogg
08-09 17:23:58.334   316   316 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-09 17:23:58.334   316   316 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-09 17:23:58.334   316   316 V AwesomePlayer: mBitrate = -1 bits/sec
08-09 17:23:58.334   316   316 V AwesomePlayer: AudioTrack Setting
08-09 17:23:58.334   316   316 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-09 17:23:58.334   316   316 V AwesomePlayer: setAudioSource() 
08-09 17:23:58.334   316   316 V MediaPlayerService: prepare
08-09 17:23:58.334   316   316 V AwesomePlayer: prepareAsync_l() 
08-09 17:23:58.335   316   316 V MediaPlayerService: wait for prepare
08-09 17:23:58.335   316  8576 V AwesomePlayer: onPrepareAsyncEvent() 
08-09 17:23:58.335   316  8576 V AwesomePlayer: initAudioDecoder() 
08-09 17:23:58.335   316  8576 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-09 17:23:58.335   316  8576 V AudioSystem: isOffloadSupported()
08-09 17:23:58.335   316  8576 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-09 17:23:58.335   316  8576 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-09 17:23:58.335   316  8576 I AudioFlinger: isAudioPlaybackHookOn() false
08-09 17:23:58.335   316  8576 V AwesomePlayer: getUseOffload() = 0 
08-09 17:23:58.335   316  8576 V OMXCodec: OMXCodec::Create
08-09 17:23:58.335   316  8576 V OMXCodec: findMatchingCodecs()
08-09 17:23:58.335   316  8576 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-09 17:23:58.335   316  8576 V OMXCodec: matchingCodecs.size()=1
08-09 17:23:58.335   316  8576 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-09 17:23:58.337   316  8576 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-09 17:23:58.337   316  8576 V LGCodecAdapter: LG Codec Adapter start
08-09 17:23:58.337   316  8576 V OMXCodec: OMXCodec Createtor
08-09 17:23:58.337   316  8576 V OMXCodec: setComponentRole
08-09 17:23:58.337   316  8576 V OMXCodec: configureCodec protected=0
08-09 17:23:58.337   316  8576 V LGCodecAdapter: called getLGCodecSpecificData
08-09 17:23:58.337   316  8576 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-09 17:23:58.337   316  8576 V LGCodecOSAL: Called LGconfigureCodecMETA
08-09 17:23:58.337   316  8576 V LGCodecOSAL: Called LGconfigureCodecMSG
08-09 17:23:58.337   316  8576 V LGCodecOSAL: Not support LGCodec
08-09 17:23:58.337   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-09 17:23:58.337   316  8576 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-09 17:23:58.337   316  8576 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-09 17:23:58.337   316  8576 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-09 17:23:58.337   316  8576 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-09 17:23:58.337   316  8576 V AudioSystem: isOffloadSupported()
,08-09 17:23:58.337   316  8576 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,08-09 17:23:58.337   316  8576 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-09 17:23:58.337   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-09 17:23:58.337   316  8576 V OMXCodec: init()
08-09 17:23:58.337   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-09 17:23:58.337   316  8576 V OMXCodec: allocateBuffers
08-09 17:23:58.337   316  8576 V OMXCodec: allocateBuffersOnPort portIndex=0
08-09 17:23:58.337   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-09 17:23:58.338   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-09 17:23:58.338   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-09 17:23:58.338   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-09 17:23:58.338   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
08-09 17:23:58.338   316  8576 V OMXCodec: allocateBuffersOnPort portIndex=1
08-09 17:23:58.338   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-09 17:23:58.338   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-09 17:23:58.338   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
,08-09 17:23:58.338   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd060 on output port
08-09 17:23:58.338   316  8576 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd1a0 on output port
08-09 17:23:58.338   316  8576 V OMXCodec: init() mAsyncCompletion wait!!! 
08-09 17:23:58.339  8540  8540 V LGMDMManager: Create singleton instance
08-09 17:23:58.344   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-09 17:23:58.344   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-09 17:23:58.344   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-09 17:23:58.345   316  8576 V OMXCodec: init() mAsyncCompletion wait!!! 
08-09 17:23:58.347   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-09 17:23:58.347   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-09 17:23:58.347   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-09 17:23:58.347   316  8576 V OMXCodec: init() mAsyncCompletion wait free! 
08-09 17:23:58.347   316  8576 V AwesomePlayer: finishAsyncPrepare_l() 
08-09 17:23:58.347   316  8576 V AudioCache: notify(0xb1010300, 5, 0, 0)
08-09 17:23:58.347   316  8576 V AudioCache: ignored
,08-09 17:23:58.347   316  8576 V AudioCache: notify(0xb1010300, 1, 0, 0)
08-09 17:23:58.347   316  8576 V AudioCache: prepared
08-09 17:23:58.347   316   316 V AudioCache: wait - success
08-09 17:23:58.347   316   316 V MediaPlayerService: start
08-09 17:23:58.347   316   316 V AwesomePlayer: play_l() 
08-09 17:23:58.347   316   316 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-09 17:23:58.347   316   316 V AwesomePlayer: createAudioPlayer_l
08-09 17:23:58.347   316   316 V AwesomePlayer: seekAudioIfNecessary_l() 
08-09 17:23:58.347   316   316 V AwesomePlayer: startAudioPlayer_l() 
08-09 17:23:58.347   316   316 D AudioPlayer: start of Playback, useOffload 0
08-09 17:23:58.347   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-09 17:23:58.347   316   316 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790368
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790688
08-09 17:23:58.349   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-09 17:23:58.350   316  8578 V OMXCodec: allocateBuffersOnPort portIndex=1
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd060 on output port
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-09 17:23:58.350   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd470 on output port
08-09 17:23:58.351   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-09 17:23:58.351   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-09 17:23:58.352   316   316 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-09 17:23:58.352   316   316 V AudioCache: notify(0xb1010300, 6, 0, 0)
08-09 17:23:58.352   316   316 V AudioCache: ignored
08-09 17:23:58.353   316   316 V MediaPlayerService: wait for playback complete
08-09 17:23:58.353   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.353   316  8579 V AudioCache: memcpy(0xaf006000, 0xb0406000, 4096)
08-09 17:23:58.355   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.355   316  8579 V AudioCache: memcpy(0xaf007000, 0xb0406000, 4096)
08-09 17:23:58.356   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.356   316  8579 V AudioCache: memcpy(0xaf008000, 0xb0406000, 4096)
08-09 17:23:58.356   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.356   316  8579 V AudioCache: memcpy(0xaf009000, 0xb0406000, 4096)
08-09 17:23:58.356   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.356   316  8579 V AudioCache: memcpy(0xaf00a000, 0xb0406000, 4096)
08-09 17:23:58.357   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.357   316  8579 V AudioCache: memcpy(0xaf00b000, 0xb0406000, 4096)
08-09 17:23:58.358   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.358   316  8579 V AudioCache: memcpy(0xaf00c000, 0xb0406000, 4096)
08-09 17:23:58.358   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.358   316  8579 V AudioCache: memcpy(0xaf00d000, 0xb0406000, 4096)
08-09 17:23:58.358   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.358   316  8579 V AudioCache: memcpy(0xaf00e000, 0xb0406000, 4096)
,08-09 17:23:58.359   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.359   316  8579 V AudioCache: memcpy(0xaf00f000, 0xb0406000, 4096)
08-09 17:23:58.360   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.360   316  8579 V AudioCache: memcpy(0xaf010000, 0xb0406000, 4096)
08-09 17:23:58.360   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.360   316  8579 V AudioCache: memcpy(0xaf011000, 0xb0406000, 4096)
08-09 17:23:58.361   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.361   316  8579 V AudioCache: memcpy(0xaf012000, 0xb0406000, 4096)
08-09 17:23:58.362   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.362   316  8579 V AudioCache: memcpy(0xaf013000, 0xb0406000, 4096)
08-09 17:23:58.363   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.363   316  8579 V AudioCache: memcpy(0xaf014000, 0xb0406000, 4096)
08-09 17:23:58.363   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.363   316  8579 V AudioCache: memcpy(0xaf015000, 0xb0406000, 4096)
08-09 17:23:58.364   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.364   316  8579 V AudioCache: memcpy(0xaf016000, 0xb0406000, 4096)
08-09 17:23:58.364   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.364   316  8579 V AudioCache: memcpy(0xaf017000, 0xb0406000, 4096)
,08-09 17:23:58.366   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.366   316  8579 V AudioCache: memcpy(0xaf018000, 0xb0406000, 4096)
08-09 17:23:58.368   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.368   316  8579 V AudioCache: memcpy(0xaf019000, 0xb0406000, 4096)
08-09 17:23:58.369   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.369   316  8579 V AudioCache: memcpy(0xaf01a000, 0xb0406000, 4096)
08-09 17:23:58.370   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.370   316  8579 V AudioCache: memcpy(0xaf01b000, 0xb0406000, 4096)
08-09 17:23:58.371   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.371   316  8579 V AudioCache: memcpy(0xaf01c000, 0xb0406000, 4096)
08-09 17:23:58.372   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.372   316  8579 V AudioCache: memcpy(0xaf01d000, 0xb0406000, 4096)
08-09 17:23:58.372   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.372   316  8579 V AudioCache: memcpy(0xaf01e000, 0xb0406000, 4096)
08-09 17:23:58.372  8469  8536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-09 17:23:58.373   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.373   316  8579 V AudioCache: memcpy(0xaf01f000, 0xb0406000, 4096)
08-09 17:23:58.374   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.374   316  8579 V AudioCache: memcpy(0xaf020000, 0xb0406000, 4096)
08-09 17:23:58.375   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.375   316  8579 V AudioCache: memcpy(0xaf021000, 0xb0406000, 4096)
08-09 17:23:58.375   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.375   316  8579 V AudioCache: memcpy(0xaf022000, 0xb0406000, 4096)
08-09 17:23:58.376   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.376   316  8579 V AudioCache: memcpy(0xaf023000, 0xb0406000, 4096)
08-09 17:23:58.377   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.377   316  8579 V AudioCache: memcpy(0xaf024000, 0xb0406000, 4096)
,08-09 17:23:58.378   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.378   316  8579 V AudioCache: memcpy(0xaf025000, 0xb0406000, 4096)
08-09 17:23:58.379   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.379   316  8579 V AudioCache: memcpy(0xaf026000, 0xb0406000, 4096)
08-09 17:23:58.379   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.379   316  8579 V AudioCache: memcpy(0xaf027000, 0xb0406000, 4096)
08-09 17:23:58.380   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.380   316  8579 V AudioCache: memcpy(0xaf028000, 0xb0406000, 4096)
08-09 17:23:58.381   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.381   316  8579 V AudioCache: memcpy(0xaf029000, 0xb0406000, 4096)
08-09 17:23:58.382   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.382   316  8579 V AudioCache: memcpy(0xaf02a000, 0xb0406000, 4096)
08-09 17:23:58.382   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.382   316  8579 V AudioCache: memcpy(0xaf02b000, 0xb0406000, 4096)
08-09 17:23:58.383   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.383   316  8579 V AudioCache: memcpy(0xaf02c000, 0xb0406000, 4096)
08-09 17:23:58.384   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.384   316  8579 V AudioCache: memcpy(0xaf02d000, 0xb0406000, 4096)
08-09 17:23:58.385   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.385   316  8579 V AudioCache: memcpy(0xaf02e000, 0xb0406000, 4096)
08-09 17:23:58.385   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.385   316  8579 V AudioCache: memcpy(0xaf02f000, 0xb0406000, 4096)
08-09 17:23:58.386   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.386   316  8579 V AudioCache: memcpy(0xaf030000, 0xb0406000, 4096)
08-09 17:23:58.387   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.387   316  8579 V AudioCache: memcpy(0xaf031000, 0xb0406000, 4096)
08-09 17:23:58.387   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.387   316  8579 V AudioCache: memcpy(0xaf032000, 0xb0406000, 4096)
08-09 17:23:58.387   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.387   316  8579 V AudioCache: memcpy(0xaf033000, 0xb0406000, 4096)
08-09 17:23:58.388   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.388   316  8579 V AudioCache: memcpy(0xaf034000, 0xb0406000, 4096)
08-09 17:23:58.388   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.388   316  8579 V AudioCache: memcpy(0xaf035000, 0xb0406000, 4096)
,08-09 17:23:58.389   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.389   316  8579 V AudioCache: memcpy(0xaf036000, 0xb0406000, 4096)
08-09 17:23:58.389   316  8579 V AudioCache: write(0xb0406000, 4096)
08-09 17:23:58.389   316  8579 V AudioCache: memcpy(0xaf037000, 0xb0406000, 4096)
08-09 17:23:58.390   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-09 17:23:58.390   316  8579 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-09 17:23:58.390   316  8579 V AwesomePlayer: postAudioEOS() 
08-09 17:23:58.390   316  8579 V AudioCache: write(0xb0406000, 280)
08-09 17:23:58.390   316  8579 V AudioCache: memcpy(0xaf038000, 0xb0406000, 280)
08-09 17:23:58.391   316  8576 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-09 17:23:58.391   316  8576 V AwesomePlayer: onStreamDone
08-09 17:23:58.391   316  8576 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-09 17:23:58.391   316  8576 V AudioCache: notify(0xb1010300, 2, 0, 0)
08-09 17:23:58.391   316  8576 V AudioCache: playback complete
08-09 17:23:58.391   316  8576 V AwesomePlayer: pause_l() 
08-09 17:23:58.391   316  8576 V AudioCache: notify(0xb1010300, 7, 0, 0)
08-09 17:23:58.391   316  8576 V AudioCache: ignored
08-09 17:23:58.391   316  8576 V AwesomePlayer: cancelPlayerEvents
08-09 17:23:58.391   316   316 V AudioCache: wait - success
08-09 17:23:58.391   316   316 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-09 17:23:58.391   316  8576 D AudioPlayer: Pause Playback at 1068125
08-09 17:23:58.392   316   316 V AwesomePlayer: reset_l() 
08-09 17:23:58.392   316   316 V AudioCache: notify(0xb1010300, 8, 0, 0)
08-09 17:23:58.392   316   316 V AudioCache: ignored
08-09 17:23:58.392   316   316 V AwesomePlayer: cancelPlayerEvents
08-09 17:23:58.392   316   316 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-09 17:23:58.392   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-09 17:23:58.392   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-09 17:23:58.392   316   316 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-09 17:23:58.392   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
,08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd470 on port 1
08-09 17:23:58.392   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd060 on port 1
,08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-09 17:23:58.393   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-09 17:23:58.393   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-09 17:23:58.393   316  8578 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
,08-09 17:23:58.393   316   316 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-09 17:23:58.393   316   316 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-09 17:23:58.393   316   316 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-09 17:23:58.394   316   316 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-09 17:23:58.394   316   316 D AudioPlayer: AudioPlayer releasing audio source
08-09 17:23:58.394   316   316 D AudioPlayer: AudioPlayer done releasing audio source
,08-09 17:23:58.394   316   316 V AwesomePlayer: reset_l() 
08-09 17:23:58.394   316   316 V AwesomePlayer: cancelPlayerEvents
08-09 17:23:58.394   316   316 V AwesomePlayer: ~AwesomePlayer call
08-09 17:23:58.394   316   316 V AwesomePlayer: reset_l() 
08-09 17:23:58.394   316   316 V AwesomePlayer: cancelPlayerEvents
08-09 17:23:58.395  8540  8575 V SoundPool: close(31)
08-09 17:23:58.395  8540  8575 V SoundPool: pointer = 0x9fe35000, size = 205080, sampleRate = 48000, numChannels = 2
,08-09 17:23:58.397  8469  8536 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-09 17:23:58.404  8469  8536 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-09 17:23:58.404  8469  8536 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-09 17:23:58.405  8469  8536 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-09 17:23:58.405  8469  8536 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-09 17:23:58.406  8469  8536 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-09 17:23:58.408  8469  8536 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-09 17:23:58.409  8469  8536 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-09 17:23:58.429  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-09 17:23:58.431  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-09 17:23:58.433  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9699
08-09 17:23:58.436  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.438  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.439  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.440  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.441  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.443  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.444  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.446  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.447  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-09 17:23:58.448  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-09 17:23:58.662  8058  8058 I UEI.SmartControl: Supports setup maps: true
,08-09 17:23:58.665  8058  8058 D UEI.SmartControl: QS start statue = true Error code = 0
08-09 17:23:58.665  8058  8058 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-09 17:23:58.665  8058  8058 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-09 17:23:58.665  8058  8058 I UEI.SmartControl: ### init IR Blaster...
,08-09 17:23:58.669  8058  8058 D serial_port: Configuring serial port
,08-09 17:23:58.669  8058  8058 E UEI.SmartControl: UEIBLaster setting for 616
08-09 17:23:58.669  8058  8058 I UEI.SmartControl: Setting serial record hearder size = 2
08-09 17:23:58.669  8058  8058 I UEI.SmartControl: configuring settings for MAXQ616
08-09 17:23:58.670  8058  8058 I UEI.SmartControl: Get version...
08-09 17:23:58.688  8058  8585 D UEI.SmartControl: serial port data available: 21
,08-09 17:23:58.714  8058  8058 D UEI.SmartControl: MAXQ616 A2-X4 software.,
08-09 17:23:58.714  8058  8058 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-09 17:23:58.714  8058  8058 I UEI.SmartControl: QS saving settings...
,08-09 17:23:58.716  8058  8058 D UEI.SmartControl: IR Blaster version: 25672567
,08-09 17:23:58.734  8058  8585 D UEI.SmartControl: serial port data available: 4
,08-09 17:23:58.766  8058  8591 I UEI.SmartControl: Device manager: loading config....
08-09 17:23:58.767  8058  8591 D UEI.SmartControl: ----------- loading internal config...
,08-09 17:23:58.771  8058  8058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-09 17:23:58.774  8058  8058 E UEI.SmartControl: Services init done
08-09 17:23:58.774  8058  8058 D UEI.SmartControl: QS Service init finished
08-09 17:23:58.778  8058  8058 D UEI.SmartControl: QS Service version name: 2.1.91
08-09 17:23:58.778  8058  8058 D UEI.SmartControl: QS Service version code: 201091
08-09 17:23:58.779  8058  8058 D UEI.SmartControl: Service requested: Control
08-09 17:23:58.784  8058  8591 E UEI.SmartControl: Loading SETTINGS...
,08-09 17:23:58.784  8058  8058 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-09 17:23:58.790  8540  8540 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-09 17:23:58.791  8058  8058 D UEI.SmartControl: Internal service binding...
08-09 17:23:58.794  8058  8171 I UEI.SmartControl: ------ IControl API: 11
08-09 17:23:58.794  8058  8171 D UEI.SmartControl: File observer start...
08-09 17:23:58.795  8058  8171 E UEI.SmartControl: IR Port is disabled: false
08-09 17:23:58.795  8058  8171 D UEI.SmartControl: Starting file observer...
08-09 17:23:58.799  8058  8171 I UEI.SmartControl: Registering callback...
08-09 17:23:58.807  8058  8074 I UEI.SmartControl: ------ IControl API: 19
08-09 17:23:58.814  8058  8074 I UEI.SmartControl: Registering Services Ready callback...
,08-09 17:23:58.821  8058  8591 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-09 17:23:58.825  8058  8590 I UEI.SmartControl: Notify AllClients services are ready: 0
08-09 17:23:58.826  8058  8590 D UEI.SmartControl: -----service ready thread exits
08-09 17:23:58.826  8540  8556 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-09 17:23:58.827  8540  8573 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-09 17:23:58.827  8540  8573 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-09 17:23:58.827  8540  8540 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-09 17:23:58.828  8540  8540 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-09 17:23:58.828  8058  8075 I UEI.SmartControl: ------ IControl API: 8
,08-09 17:23:58.830  8540  8540 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-09 17:23:58.830  8540  8540 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,08-09 17:23:58.831  8540  8540 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-09 17:23:58.831  8540  8540 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-09 17:23:58.832  8540  8540 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-09 17:23:58.832  8540  8540 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-09 17:23:58.833  8540  8540 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-09 17:23:58.837  8540  8540 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-09 17:23:58.838  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-09 17:23:58.840  8540  8540 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-09 17:23:58.844  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-09 17:23:58.845  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-09 17:23:58.846  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-09 17:23:58.847  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-09 17:23:58.848  8540  8540 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470756238847]
08-09 17:23:58.851  8540  8540 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-09 17:23:58.854  1037  2091 I ActivityManager: Killing 7505:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-09 17:23:58.880  8540  8596 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-09 17:23:58.974  1037  2115 W libprocessgroup: failed to open /acct/uid_10093/pid_7505/cgroup.procs: No such file or directory
,08-09 17:23:58.980  8540  8540 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-09 17:23:58.984  8540  8540 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-09 17:23:58.985  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-09 17:23:58.986  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-09 17:23:58.987  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-09 17:23:58.988  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-09 17:23:58.990  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-09 17:23:59.013  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-09 17:24:00.033  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=97.5, 0.0, 0.0  rx=93.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1877424800] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 17:24:00.036  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=97.5, 0.0, 0.0  rx=93.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1877424803] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 17:24:00.036  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:00.054  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-09 17:24:00.054  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
08-09 17:24:00.054  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-09 17:24:00.054  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
08-09 17:24:00.056  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,08-09 17:24:00.057  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-09 17:24:00.063  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-09 17:24:00.064  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 17:24:00.064  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
08-09 17:24:00.078  1037  1543 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-09 17:24:00.112  1037  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:24:00.127  1037  1098 D Tethering: MasterInitialState.processMessage what=3
08-09 17:24:00.144  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:24:00.144  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:24:00.144  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:24:00.144  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:24:00.144  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:24:00.144  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:00.144  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:24:00.144  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 17:24:00.149  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:00.154  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 17:24:00.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:24:00.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:24:00.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:24:00.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:24:00.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:00.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:24:00.154  7054  7054 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:24:00.156  7054  7054 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:00.159  1037  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:24:00.169  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 17:24:00.178  5818  5818 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-09 17:24:00.205  1037  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-09 17:24:00.212  8469  8536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-09 17:24:00.228  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:24:00.242  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 17:24:00.242  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:24:00.242  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 17:24:00.242  7361  7361 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-09 17:24:00.247  7361  7361 I AppUp4:CustModeStarterReceiver: onReceive
08-09 17:24:00.251  7361  7361 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@4e5c62d
08-09 17:24:00.251  7361  7361 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 17:24:00.251  7361  7361 D AppUp4:CustFacade: isPhone : true
08-09 17:24:00.251  7361  7361 D AppUp4:CustModeStarterReceiver: begin check event
08-09 17:24:00.251  7361  7361 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-09 17:24:00.255  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 17:24:00.256  4700  4700 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 17:24:00.257  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 17:24:00.263  4700  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 17:24:00.282  1037  1578 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-09 17:24:00.286  3411  3411 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-09 17:24:00.288  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-09 17:24:00.288  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:24:00.289  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-09 17:24:00.289  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-09 17:24:00.289  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-09 17:24:00.293  3411  3411 V DownloadManager: DownloadService onCreate
,08-09 17:24:00.298  4700  8611 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-09 17:24:00.301  3411  8621 I DownloadManager: in removeSpuriousFiles
08-09 17:24:00.302  3411  8621 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-09 17:24:00.308  4700  8623 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 17:24:00.308  4700  8623 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 17:24:00.309   311  8625 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-09 17:24:00.309   311  8625 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-09 17:24:00.309  3411  8621 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1b401c79 on behalf of 3411
08-09 17:24:00.312  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-09 17:24:00.312  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-09 17:24:00.312  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-09 17:24:00.312  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-09 17:24:00.313  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-09 17:24:00.313  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-09 17:24:00.313  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-09 17:24:00.313  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-09 17:24:00.313  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-09 17:24:00.313  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-09 17:24:00.313  3411  8621 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,08-09 17:24:00.319  4700  8611 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-09 17:24:00.323  3411  8621 I DownloadManager: in trimDatabase
08-09 17:24:00.323  3411  8621 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-09 17:24:00.324  3411  8621 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@8da8e1f on behalf of 3411
08-09 17:24:00.329  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 15:24:00 GMT], X-Android-Received-Millis=[1470756240328], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470756240295]}
08-09 17:24:00.329  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-09 17:24:00.329  1037  8486 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-09 17:24:00.329  1037  1548 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-09 17:24:00.329  1037  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-09 17:24:00.329  1037  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 17:24:00.329  1037  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:24:00.329  1037  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-09 17:24:00.329  1037  1548 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,08-09 17:24:00.329  1037  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-09 17:24:00.329  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 17:24:00.329  1037  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:24:00.330  1037  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 17:24:00.330  1606  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-09 17:24:00.339  1037  2005 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8628 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-09 17:24:00.341   311  8625 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-09 17:24:00.346  4700  8611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-09 17:24:00.346  3411  3411 V DownloadManager: DownloadService onStartCommand
08-09 17:24:00.347  3411  8622 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-09 17:24:00.349  3411  8622 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1c9d0735 on behalf of 3411
08-09 17:24:00.350  4700  4700 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-09 17:24:00.351  3411  8622 V DownloadManager: processing inserted download 1
08-09 17:24:00.352  4700  4700 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-09 17:24:00.352  3411  8622 V DownloadManager: processing inserted download 4
08-09 17:24:00.352  4700  4700 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-09 17:24:00.353  3411  8622 V DownloadManager: processing inserted download 7
08-09 17:24:00.354  4700  4700 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-09 17:24:00.355  3411  8622 V DownloadManager: processing inserted download 8
,08-09 17:24:00.359  3411  8622 V DownloadManager: processing inserted download 9
08-09 17:24:00.359  4700  4700 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-09 17:24:00.360  3411  8622 V DownloadManager: processing inserted download 10
08-09 17:24:00.361  3411  8622 V DownloadManager: processing inserted download 11
08-09 17:24:00.362  3411  8622 V DownloadManager: processing inserted download 12
08-09 17:24:00.363  3411  8622 V DownloadManager: processing inserted download 13
08-09 17:24:00.364  3411  8622 V DownloadManager: processing inserted download 14
08-09 17:24:00.365  3411  8622 V DownloadManager: processing inserted download 16
,08-09 17:24:00.380  3411  3411 V DownloadManager: DownloadService onDestroy
,08-09 17:24:00.421  8628  8628 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 17:24:00.422  8628  8628 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 17:24:00.425  8628  8628 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-09 17:24:00.426  8628  8628 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-09 17:24:00.459  7054  8512 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-09 17:24:00.460  7054  8512 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-09 17:24:00.460  7054  8512 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 17:24:00.460  7054  8512 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-09 17:24:00.460  7054  8651 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-09 17:24:00.461  7054  8651 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-09 17:24:00.461  7054  8651 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 17:24:00.462  7054  8512 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-09 17:24:00.463  7054  8653 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 931, name: OutgoingSocketThread/Sender)
08-09 17:24:00.464  7054  8651 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 17:24:00.466  7054  8654 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 932, name: OutgoingSocketThread/Receiver)
08-09 17:24:00.466  7054  8654 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 932, thread name: OutgoingSocketThread/Receiver)
08-09 17:24:00.466  7054  8654 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-09 17:24:00.467  7054  8654 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 932, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-09 17:24:00.467  7054  8655 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 933, name: IncomingSocketThread/Sender)
08-09 17:24:00.468  7054  8651 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-09 17:24:00.471  7054  8656 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 934, name: IncomingSocketThread/Receiver)
,08-09 17:24:00.472  7054  8656 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 934, thread name: IncomingSocketThread/Receiver)
08-09 17:24:00.472  7054  8656 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-09 17:24:00.472  7054  8656 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 934, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-09 17:24:00.503  8628  8628 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-09 17:24:00.514  8628  8628 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-09 17:24:00.574  8628  8628 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-09 17:24:00.614  8628  8628 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:24:00.615  8628  8628 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:24:00.800  8628  8628 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-09 17:24:00.892  3307  3307 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 17:24:00.892  3307  3307 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 17:24:00.892  3307  3307 I LgeMiscReceiver: networkInfo.isConnected() = true
08-09 17:24:00.892  3307  3307 D PhoneState: setPdpRejectCasuse : false
,08-09 17:24:00.919  8628  8628 I HubEmail: JNI_OnLoad()
08-09 17:24:00.919  8628  8628 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-09 17:24:00.919  8628  8628 I HubEmail: registerNatives()
08-09 17:24:00.919  8628  8628 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-09 17:24:00.919  8628  8628 I HubEmail: registerNativeMethods()
08-09 17:24:00.919  8628  8628 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-09 17:24:00.920  8628  8628 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-09 17:24:00.951  1037  2267 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8675 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-09 17:24:01.003  8628  8681 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 17:24:01.012   311  8704 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-09 17:24:01.012   311  8704 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-09 17:24:01.051   311  8704 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-09 17:24:01.069  8675  8675 D LgDataFeature: LgDataFeature() Constructor: none
08-09 17:24:01.069  8675  8675 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 17:24:01.073  8675  8675 D PhoneMonitor: Register our PhoneStateListener
08-09 17:24:01.098  8675  8675 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-09 17:24:01.103  8675  8675 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-09 17:24:01.125  8675  8675 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-09 17:24:01.126  8675  8675 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-09 17:24:01.127  8675  8675 D TelephonyAutoProfiling: [parse] Load xml
08-09 17:24:01.133  8675  8675 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-09 17:24:01.133  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-09 17:24:01.134  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-09 17:24:01.135  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-09 17:24:01.135  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-09 17:24:01.135  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-09 17:24:01.135  8675  8675 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-09 17:24:01.135  8675  8675 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-09 17:24:01.150  8675  8675 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-09 17:24:01.176  1037  1915 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8715 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-09 17:24:01.179  1037  1915 I ActivityManager: Killing 7988:com.google.android.talk/u0a72 (adj 15): empty #17
,08-09 17:24:01.291   311  8732 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-09 17:24:01.292   311  8732 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-09 17:24:01.302  1037  1780 W libprocessgroup: failed to open /acct/uid_10072/pid_7988/cgroup.procs: No such file or directory
,08-09 17:24:01.324   311  8732 D libc-netbsd: res_queryN name = www.google.com succeed
,08-09 17:24:01.334   311  8735 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-09 17:24:01.335   311  8735 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-09 17:24:01.335   311  8735 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-09 17:24:01.357  1821  8733 I CheckinService: active receiver: disabled
,08-09 17:24:01.387  1037  1544 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-09 17:24:01.517  1037  1970 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8737 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-09 17:24:01.519  1037  1970 I ActivityManager: Killing 8039:com.android.contacts/u0a19 (adj 15): empty #17
,08-09 17:24:01.536   337   337 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 305us total 16.089ms
,08-09 17:24:01.549  8398  8673 V FormManager: There are no updated forms. The schedule will be deleted.
,08-09 17:24:01.551   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 13.598ms
08-09 17:24:01.553  8398  8673 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-09 17:24:01.564   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 12.405ms
,08-09 17:24:01.590  1037  1653 W libprocessgroup: failed to open /acct/uid_10019/pid_8039/cgroup.procs: No such file or directory
,08-09 17:24:01.605  1037  1970 I ActivityManager: Killing 8079:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-09 17:24:01.640  1037  2051 W libprocessgroup: failed to open /acct/uid_10027/pid_8079/cgroup.procs: No such file or directory
,08-09 17:24:01.697  1037  1970 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8754 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-09 17:24:01.700  1037  1970 I ActivityManager: Killing 8098:com.android.vending/u0a44 (adj 15): empty #17
,08-09 17:24:01.759  1037  2005 W libprocessgroup: failed to open /acct/uid_10044/pid_8098/cgroup.procs: No such file or directory
,08-09 17:24:01.791  8754  8754 I art     : Almond Protected OAT
,08-09 17:24:01.843  8754  8754 D WeatherApplication: removeAccount
,08-09 17:24:01.845  8754  8754 D WeatherApplication: Account.length = 0
08-09 17:24:01.846  8754  8754 E WeatherApplication: OPERATOR:OPEN
08-09 17:24:01.857  8754  8754 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:24:1
,08-09 17:24:01.862  8754  8754 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-09 17:24:01.863  8754  8754 D Weather.Utils: 2 : All the weather widget is gone.
08-09 17:24:01.864  8754  8754 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 17:24:01.866  8754  8754 D WeatherAncestor: connectivity changed - connection : true
08-09 17:24:01.867  8754  8754 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-09 17:24:01.879  8754  8754 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-09 17:24:01.879  8754  8754 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 17:24:01.879  8754  8754 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-09 17:24:01.913  8754  8754 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 17:24:01.913  8754  8754 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:24:1
,08-09 17:24:01.970  1037  2052 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8775 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-09 17:24:01.971  1037  2052 I ActivityManager: Killing 8142:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-09 17:24:02.040  1037  1578 W libprocessgroup: failed to open /acct/uid_10080/pid_8142/cgroup.procs: No such file or directory
,08-09 17:24:02.161   279   388 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-09 17:24:02.161   279   388 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-09 17:24:02.161   279   388 W Vold    : Returning OperationFailed - no handler for errno 0
,08-09 17:24:02.163  8775  8793 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-09 17:24:02.166   279   388 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 17:24:02.166   279   388 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-09 17:24:02.166   279   388 W Vold    : Returning OperationFailed - no handler for errno 0
08-09 17:24:02.167  8775  8793 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-09 17:24:02.182   279   388 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 17:24:02.182   279   388 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-09 17:24:02.182   279   388 W Vold    : Returning OperationFailed - no handler for errno 0
08-09 17:24:02.183  8775  8796 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-09 17:24:02.189   279   388 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 17:24:02.189   279   388 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-09 17:24:02.189   279   388 W Vold    : Returning OperationFailed - no handler for errno 0
,08-09 17:24:02.194  8775  8796 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-09 17:24:02.451  8775  8775 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-09 17:24:02.463  8775  8775 I LibraryLoader: Loading: webviewchromium
08-09 17:24:02.467  8775  8775 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 213-218)
,08-09 17:24:02.467  8775  8775 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 17:24:02.473  8775  8775 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c95310c}
08-09 17:24:02.477  8775  8775 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 17:24:02.478  8775  8775 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-09 17:24:02.502  8775  8775 I BrowserStartupController: Initializing chromium process, renderers=0
08-09 17:24:02.504  8775  8775 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 17:24:02.529   316   316 V AudioPolicyService: registerClient() client 0xb1025bc0, uid 10093
,08-09 17:24:02.530  8775  8820 W AudioManagerAndroid: Requires BLUETOOTH permission
08-09 17:24:02.532  8775  8775 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-09 17:24:02.533  8775  8775 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-09 17:24:02.533  8775  8775 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-09 17:24:02.550  8775  8775 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 17:24:02.550  8775  8775 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 17:24:02.550  8775  8775 I Adreno-EGL: Build Date: 12/12/14 금
08-09 17:24:02.550  8775  8775 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 17:24:02.550  8775  8775 I Adreno-EGL: Remote Branch: 
08-09 17:24:02.550  8775  8775 I Adreno-EGL: Local Patches: 
08-09 17:24:02.550  8775  8775 I Adreno-EGL: Reconstruct Branch: 
,08-09 17:24:02.645  8775  8775 I NSApplication: Starting up...
,08-09 17:24:02.675  1037  2028 I ActivityManager: Killing 7864:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-09 17:24:02.708  1037  1653 W libprocessgroup: failed to open /acct/uid_10037/pid_7864/cgroup.procs: No such file or directory
,08-09 17:24:02.725  2230  2230 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-09 17:24:02.735  1037  1407 D PowerManagerServiceEx: acquireWakeLockInternal: lock=533154631, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
08-09 17:24:02.774  2650  2650 D [Concierge]Service: onStartCommand(). Type : 9
,08-09 17:24:02.797  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=533154631 [*alarm*], flags=0x0
,08-09 17:24:03.066  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=54.2, 0.0, 0.0  rx=51.2 bcn=0 [on:0 tx:0 rx:0 period:3012] from screen [on:0 period:1877427833] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 17:24:03.069  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=54.2, 0.0, 0.0  rx=51.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1877427837] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 17:24:03.069  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-09 17:24:03.465  7054  7110 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-09 17:24:03.468  7054  7110 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-09 17:24:03.476  7054  7110 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f33f347 Bundle[{}]
08-09 17:24:03.477  7054  7110 I io.jxcore.node.LifeCycleMonitor: start: OK
08-09 17:24:03.477  7054  7110 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-09 17:24:03.478  7054  7110 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-09 17:24:03.479  7054  7110 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-09 17:24:03.480  7054  7110 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-09 17:24:03.480  7054  7110 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-09 17:24:03.487  7054  7110 I System.out: Running OutgoingSocketThread
08-09 17:24:03.489  7054  8852 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-09 17:24:03.489  7054  8852 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-09 17:24:03.767  8058  8592 D UEI.SmartControl: Internal timer expired: 4
,08-09 17:24:03.767  8058  8592 D UEI.SmartControl: unbind internal service
,08-09 17:24:03.848  8058  8586 D serial_port: close(fd = 24)
,08-09 17:24:03.859  8058  8586 I UEI.SmartControl: Serial port is closed.
,08-09 17:24:06.086  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=37.6, 0.0, 0.0  rx=33.1 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1877430853] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 17:24:06.099  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=37.6, 0.0, 0.0  rx=33.1 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1877430867] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 17:24:06.100  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-09 17:24:06.501  7054  8852 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-09 17:24:06.501  7054  8852 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-09 17:24:06.501  7054  8852 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 17:24:06.501  7054  8852 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 17:24:06.502  7054  8852 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-09 17:24:06.507  7054  8853 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-09 17:24:06.507  7054  8853 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-09 17:24:06.507  7054  8853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 17:24:06.508  7054  8853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 17:24:06.508  7054  8853 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-09 17:24:06.513  7054  8856 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 944, name: OutgoingSocketThread/Receiver)
08-09 17:24:06.515  7054  8855 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 943, name: OutgoingSocketThread/Sender)
08-09 17:24:06.517  7054  8858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 946, name: IncomingSocketThread/Receiver)
08-09 17:24:06.517  7054  8858 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 946, thread name: IncomingSocketThread/Receiver)
08-09 17:24:06.517  7054  8858 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-09 17:24:06.517  7054  8858 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 946, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-09 17:24:06.522  7054  8857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 945, name: IncomingSocketThread/Sender)
08-09 17:24:06.523  7054  8856 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 944, thread name: OutgoingSocketThread/Receiver)
08-09 17:24:06.523  7054  8856 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-09 17:24:06.523  7054  8856 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 944, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-09 17:24:07.191  8775  8795 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-09 17:24:09.119  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=18.8, 0.0, 0.0  rx=16.6 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1877433886] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 17:24:09.122  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=18.8, 0.0, 0.0  rx=16.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1877433890] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 17:24:09.122  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:09.508  7054  7110 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 955)
,08-09 17:24:09.514  7054  7110 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-09 17:24:09.514  7054  7110 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 956)
08-09 17:24:09.517  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 17:24:09.517  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269f137e added. We now have 3 listener(s)
08-09 17:24:09.518  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:24:09.521  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 17:24:09.521  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 17:24:09.521  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 17:24:09.521  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:24:09.521  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1fe0df added. We now have 4 listener(s)
08-09 17:24:09.521  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:24:09.522  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 17:24:09.529  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:24:09.533  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:24:09.533  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:24:09.533  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:24:09.533  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:24:09.533  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:24:09.533  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:09.533  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:24:09.533  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:24:09.534  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:09.534  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 17:24:09.540  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:24:09.542  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:24:09.542  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:24:09.542  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:24:09.542  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:24:09.543  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:09.543  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:09.543  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:24:09.543  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 17:24:09.543  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269f137e removed from the list
08-09 17:24:09.543  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:09.543  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1fe0df removed from the list
08-09 17:24:09.543  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:24:09.543  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:09.544  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:09.544  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:09.545  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:09.545  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:09.545  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:09.545  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1fe0df not in the list
08-09 17:24:09.545  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:09.545  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:09.546  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:09.546  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:09.546  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:09.546  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b1fe0df not in the list
08-09 17:24:09.546  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:09.546  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-09 17:24:09.547  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:09.547  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269f137e not in the list
08-09 17:24:09.551  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 17:24:09.551  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5377f5 added. We now have 3 listener(s)
,08-09 17:24:09.556  1037  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:24:09.559  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 17:24:09.559  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 17:24:09.559  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 17:24:09.559  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:24:09.559  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a94e98a added. We now have 4 listener(s)
08-09 17:24:09.559  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:24:09.560  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 17:24:09.564  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 17:24:09.570  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:24:09.570  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:24:09.570  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:24:09.570  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:24:09.570  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:24:09.570  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:09.570  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:24:09.570  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:24:09.572  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:09.572  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 17:24:09.574  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:24:09.575  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:24:09.577  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 17:24:09.577  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 17:24:09.577  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 17:24:09.577  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:24:09.577  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-09 17:24:09.583  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 17:24:09.583  1037  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:24:09.587  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 17:24:09.590  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-09 17:24:09.593  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 17:24:09.593  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:24:09.595  7054  7110 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 17:24:09.595  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:24:09.595  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:24:09.597  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:24:09.597  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:24:09.597  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:24:09.597  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:09.597  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:09.597  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:24:09.597  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 17:24:09.598  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5377f5 removed from the list
08-09 17:24:09.598  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:09.598  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a94e98a removed from the list
08-09 17:24:09.598  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:24:09.598  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:09.599  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:09.599  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:09.600  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:09.600  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:09.602  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:24:09.602  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:24:09.602  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:09.602  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a94e98a not in the list
08-09 17:24:09.602  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:09.602  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:24:09.606  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:09.606  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:24:09.606  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:24:09.607  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:09.607  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:09.607  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a94e98a not in the list
08-09 17:24:09.607  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:09.607  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:09.607  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:09.607  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5377f5 not in the list
08-09 17:24:09.608  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 17:24:09.608  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f601456 added. We now have 3 listener(s)
08-09 17:24:09.608  1037  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:24:09.611  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 17:24:09.611  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 17:24:09.611  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 17:24:09.611  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:24:09.611  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229f0cd7 added. We now have 4 listener(s)
08-09 17:24:09.611  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:24:09.612  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 17:24:09.616  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 17:24:09.622  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:24:09.622  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:24:09.622  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:24:09.622  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:24:09.622  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:24:09.622  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:09.622  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:24:09.622  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:24:09.624  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:09.624  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 17:24:09.627  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:24:09.629  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:24:09.632  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-09 17:24:09.633  7054  7110 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-09 17:24:09.634  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-09 17:24:09.636  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-09 17:24:09.636  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-09 17:24:09.636  7054  7110 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-09 17:24:09.636  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:24:09.639  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-09 17:24:09.640  7054  7110 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-09 17:24:09.640  7054  7110 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-09 17:24:09.640  7054  7054 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-09 17:24:09.642  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-09 17:24:09.642  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-09 17:24:09.642  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:24:09.642  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-09 17:24:09.653  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-09 17:24:09.654  1037  2052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:24:09.662  1037  2091 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 17:24:09.669  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 17:24:09.670  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 17:24:09.672  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 17:24:09.672  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-09 17:24:09.673  7054  8861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 17:24:09.674  8226  8241 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-09 17:24:09.675  7054  8861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-09 17:24:09.678  7054  7110 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 17:24:09.829  1037  1541 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-09 17:24:09.831  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-09 17:24:09.832  1037  1541 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-09 17:24:09.833  1037  1541 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-09 17:24:09.834  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-09 17:24:09.836  1037  1541 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-09 17:24:12.147  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=8.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1877436914] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 17:24:12.157  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=8.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1877436925] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 17:24:12.158  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-09 17:24:14.679  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:24:14.679  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:24:14.679  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-09 17:24:14.680  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-09 17:24:14.680  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-09 17:24:14.680  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-09 17:24:14.690  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:24:14.691  7054  7110 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-09 17:24:14.692  7054  7054 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-09 17:24:14.693  7054  8861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-09 17:24:14.693  7054  8861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-09 17:24:14.693  7054  8861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-09 17:24:14.696  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 17:24:14.696  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.696  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:24:14.702  7054  7054 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:24:14.703  7054  7054 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-09 17:24:14.703  7054  7054 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-09 17:24:14.705  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:14.705  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.705  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:24:14.705  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 17:24:14.705  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f601456 removed from the list
08-09 17:24:14.705  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:14.705  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229f0cd7 removed from the list
08-09 17:24:14.705  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:24:14.705  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.707  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.707  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.708  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:14.708  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:14.708  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:24:14.708  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:24:14.709  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:14.709  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229f0cd7 not in the list
08-09 17:24:14.709  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.709  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.710  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:14.710  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:24:14.710  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:24:14.710  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:14.710  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:14.710  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229f0cd7 not in the list
08-09 17:24:14.711  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:14.711  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.711  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.711  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f601456 not in the list
08-09 17:24:14.711  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 17:24:14.712  7054 , 7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@395d9f73 added. We now have 3 listener(s)
08-09 17:24:14.712  1037  1915 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:24:14.717  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 17:24:14.717  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 17:24:14.717  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 17:24:14.717  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:24:14.718  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39641e30 added. We now have 4 listener(s)
08-09 17:24:14.718  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 17:24:14.722  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 17:24:14.727  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:24:14.732  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:24:14.732  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:24:14.732  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:24:14.732  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:24:14.732  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:24:14.732  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:14.732  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:24:14.732  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 17:24:14.735  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:14.735  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 17:24:14.737  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:24:14.740  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:24:14.741  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 17:24:14.741  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 17:24:14.742  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 17:24:14.742  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 17:24:14.742  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 17:24:14.745  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-09 17:24:14.748  1037  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 17:24:14.752  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 17:24:14.754  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 17:24:14.756  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 17:24:14.756  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:24:14.758  7054  7110 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-09 17:24:14.762  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:24:14.762  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:24:14.762  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:24:14.762  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:14.762  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.762  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:24:14.762  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 17:24:14.762  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@395d9f73 removed from the list
08-09 17:24:14.762  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:14.763  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39641e30 removed from the list
08-09 17:24:14.763  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:24:14.763  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.763  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.763  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.764  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:14.764  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:14.766  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:24:14.766  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:24:14.767  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:14.767  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39641e30 not in the list
08-09 17:24:14.767  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.767  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.768  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:14.768  7054  7110 D BluetoothLeScanner: could not find callback wrapper
08-09 17:24:14.768  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 17:24:14.769  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:14.769  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:14.769  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39641e30 not in the list
08-09 17:24:14.769  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:14.769  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listene,r does not exist in the list - probably already removed
08-09 17:24:14.769  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.769  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@395d9f73 not in the list
08-09 17:24:14.770  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 17:24:14.770  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2624ed5c added. We now have 3 listener(s)
08-09 17:24:14.770  1037  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 17:24:14.777  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 17:24:14.777  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 17:24:14.777  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 17:24:14.777  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 17:24:14.777  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f334865 added. We now have 4 listener(s)
08-09 17:24:14.777  7054  7110 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 17:24:14.780  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 17:24:14.783  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 17:24:14.789  7054  7110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 17:24:14.789  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 17:24:14.789  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 17:24:14.789  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 17:24:14.789  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 17:24:14.789  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:14.789  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 17:24:14.789  7054  7110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 17:24:14.790  7054  7110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 17:24:14.790  7054  7110 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 17:24:14.793  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 17:24:14.795  7054  7054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 17:24:14.797  7054  7110 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 17:24:14.797  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 17:24:14.798  7054  7110 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 17:24:14.798  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:14.798  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.798  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 17:24:14.798  7054  7110 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 17:24:14.798  7054  7110 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2624ed5c removed from the list
08-09 17:24:14.798  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:14.798  7054  7110 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f334865 removed from the list
08-09 17:24:14.798  7054  7110 D io.jxcore.node.ConnectivityMonitor: stop
08-09 17:24:14.798  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.799  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.799  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.800  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:14.800  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:14.800  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:14.800  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f334865 not in the list
08-09 17:24:14.800  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.800  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 17:24:14.801  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 17:24:14.801  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 17:24:14.801  7054  7110 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 17:24:14.801  7054  7110 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f334865 not in the list
08-09 17:24:14.801  7054  7110 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 17:24:14.801  7054  7110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 17:24:14.801  7054  7110 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 17:24:14.801  7054  7110 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2624ed5c not in the list
08-09 17:24:14.802  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-09 17:24:14.803  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-09 17:24:14.803  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-09 17:24:14.803  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 17:24:14.803  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-09 17:24:14.803  7054  7110 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-09 17:24:14.814  7054  8871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 965, name: My test thread name)
,08-09 17:24:15.179  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1877439946] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-09 17:24:15.182  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1877439949] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:24:15.182  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:16.813  7054  7110 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 965
,08-09 17:24:16.814  7054  7110 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 965, name: My test thread name)
,08-09 17:24:16.830  7054  8872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 966, name: My test thread name)
08-09 17:24:16.830  7054  8872 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 966, thread name: My test thread name)
08-09 17:24:16.831  7054  8872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 966, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-09 17:24:16.833  7054  7110 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 17:24:16.838  7054  8873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 970, name: My test thread name)
08-09 17:24:16.839  7054  8873 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 970, thread name: My test thread name): Test exception.
08-09 17:24:16.839  7054  8873 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 970, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-09 17:24:16.845  7054  7110 I jxcore-log: Total number of executed tests:  82
08-09 17:24:16.845  7054  7110 I jxcore-log: 
08-09 17:24:16.845  7054  7110 I jxcore-log: Number of passed tests:  82
08-09 17:24:16.845  7054  7110 I jxcore-log: 
08-09 17:24:16.845  7054  7110 I jxcore-log: Number of failed tests:  0
08-09 17:24:16.845  7054  7110 I jxcore-log: 
08-09 17:24:16.845  7054  7110 I jxcore-log: Number of ignored tests:  0
08-09 17:24:16.845  7054  7110 I jxcore-log: 
08-09 17:24:16.846  7054  7110 I jxcore-log: Total duration:  79302
08-09 17:24:16.846  7054  7110 I jxcore-log: 
08-09 17:24:16.851  7054  7110 I jxcore-log: Unit Test app is loaded
08-09 17:24:16.851  7054  7110 I jxcore-log: 
,08-09 17:24:16.873  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.873  7054  7110 I jxcore-log: 
08-09 17:24:16.877  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.877  7054  7110 I jxcore-log: 
,08-09 17:24:16.889  7054  7054 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-09 17:24:16.890  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.890  7054  7110 I jxcore-log: 
08-09 17:24:16.891  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.891  7054  7110 I jxcore-log: 
08-09 17:24:16.892  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.892  7054  7110 I jxcore-log: 
08-09 17:24:16.894  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.894  7054  7110 I jxcore-log: 
08-09 17:24:16.896  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.896  7054  7110 I jxcore-log: 
08-09 17:24:16.901  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 17:24:16.901  7054  7110 I jxcore-log: 
08-09 17:24:16.902  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 17:24:16.902  7054  7110 I jxcore-log: 
08-09 17:24:16.903  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.903  7054  7110 I jxcore-log: 
08-09 17:24:16.904  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 17:24:16.904  7054  7110 I jxcore-log: 
08-09 17:24:16.905  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.905  7054  7110 I jxcore-log: 
08-09 17:24:16.906  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.906  7054  7110 I jxcore-log: 
08-09 17:24:16.907  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.907  7054  7110 I jxcore-log: 
08-09 17:24:16.908  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 17:24:16.908  7054  7110 I jxcore-log: 
,08-09 17:24:16.912  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 17:24:16.912  7054  7110 I jxcore-log: 
08-09 17:24:16.913  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 17:24:16.913  7054  7110 I jxcore-log: 
08-09 17:24:16.913  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 17:24:16.913  7054  7110 I jxcore-log: 
08-09 17:24:16.914  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.914  7054  7110 I jxcore-log: 
08-09 17:24:16.915  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.915  7054  7110 I jxcore-log: 
08-09 17:24:16.916  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.916  7054  7110 I jxcore-log: 
08-09 17:24:16.917  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.917  7054  7110 I jxcore-log: 
08-09 17:24:16.917  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.917  7054  7110 I jxcore-log: 
08-09 17:24:16.920  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.920  7054  7110 I jxcore-log: 
08-09 17:24:16.921  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.921  7054  7110 I jxcore-log: 
08-09 17:24:16.922  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.922  7054  7110 I jxcore-log: 
08-09 17:24:16.922  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.922  7054  7110 I jxcore-log: 
08-09 17:24:16.923  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.923  7054  7110 I jxcore-log: 
08-09 17:24:16.924  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.924  7054  7110 I jxcore-log: 
08-09 17:24:16.925  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.925  7054  7110 I jxcore-log: 
08-09 17:24:16.926  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.926  7054  7110 I jxcore-log: 
08-09 17:24:16.926  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.926  7054  7110 I jxcore-log: 
08-09 17:24:16.927  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth,":"on","wifi":"off","cellular":"doNotCare"}
08-09 17:24:16.927  7054  7110 I jxcore-log: 
08-09 17:24:16.928  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 17:24:16.928  7054  7110 I jxcore-log: 
,08-09 17:24:16.932  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 17:24:16.932  7054  7110 I jxcore-log: 
08-09 17:24:16.934  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.934  7054  7110 I jxcore-log: 
08-09 17:24:16.935  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.935  7054  7110 I jxcore-log: 
08-09 17:24:16.936  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.936  7054  7110 I jxcore-log: 
08-09 17:24:16.937  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.937  7054  7110 I jxcore-log: 
08-09 17:24:16.938  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.938  7054  7110 I jxcore-log: 
08-09 17:24:16.939  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.939  7054  7110 I jxcore-log: 
08-09 17:24:16.940  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.940  7054  7110 I jxcore-log: 
08-09 17:24:16.940  7054  7110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 17:24:16.940  7054  7110 I jxcore-log: 
08-09 17:24:16.943  7054  7110 I jxcore-log: My device name is: LGE-LG-D855
08-09 17:24:16.943  7054  7110 I jxcore-log: 
08-09 17:24:16.944  7054  7110 I jxcore-log: WARN testUtils: myNameCallback not set!
08-09 17:24:16.944  7054  7110 I jxcore-log: 
08-09 17:24:16.978  7054  8871 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 965, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-09 17:24:18.208  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1877442976] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-09 17:24:18.211  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1877442979] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:24:18.211  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:19.376  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-09 17:24:19.376  7054  7110 I jxcore-log: 
,08-09 17:24:20.018  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-09 17:24:20.018  7054  7110 I jxcore-log: 
,08-09 17:24:20.044  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-09 17:24:20.044  7054  7110 I jxcore-log: 
,08-09 17:24:21.234  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1877446002] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-09 17:24:21.243  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:1877446010] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:24:21.243  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:21.385  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-09 17:24:21.385  7054  7110 I jxcore-log: 
,08-09 17:24:21.612  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-09 17:24:21.612  7054  7110 I jxcore-log: 
,08-09 17:24:21.619  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeTestMethod.js
08-09 17:24:21.619  7054  7110 I jxcore-log: 
,08-09 17:24:21.624  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-09 17:24:21.624  7054  7110 I jxcore-log: 
,08-09 17:24:21.641  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-09 17:24:21.641  7054  7110 I jxcore-log: 
,08-09 17:24:21.645  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-09 17:24:21.645  7054  7110 I jxcore-log: 
08-09 17:24:21.786  1037  1407 V AlarmManager: ELAPSED_WAKEUP set : Alarm{31fd1e4e type 2 when 422041 com.google.android.gms} when 422041
,08-09 17:24:21.807  8540  8540 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-09 17:24:21.808  8540  8540 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9699
08-09 17:24:21.817   311  8881 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-09 17:24:21.817   311  8881 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-09 17:24:21.817   311  8881 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-09 17:24:22.088  2230  8883 D GCM     : Connected
,08-09 17:24:22.120  2230  8883 D GCM     : Message class com.google.e.a.a.q
08-09 17:24:22.450  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-09 17:24:22.450  7054  7110 I jxcore-log: 
,08-09 17:24:22.464  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-09 17:24:22.464  7054  7110 I jxcore-log: 
,08-09 17:24:22.473  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-09 17:24:22.473  7054  7110 I jxcore-log: 
,08-09 17:24:22.480  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-09 17:24:22.480  7054  7110 I jxcore-log: 
,08-09 17:24:22.530  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-09 17:24:22.530  7054  7110 I jxcore-log: 
,08-09 17:24:22.586  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-09 17:24:22.586  7054  7110 I jxcore-log: 
,08-09 17:24:22.594  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-09 17:24:22.594  7054  7110 I jxcore-log: 
,08-09 17:24:22.759  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-09 17:24:22.759  7054  7110 I jxcore-log: 
,08-09 17:24:22.812  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-09 17:24:22.812  7054  7110 I jxcore-log: 
,08-09 17:24:22.827  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-09 17:24:22.827  7054  7110 I jxcore-log: 
08-09 17:24:22.845  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-09 17:24:22.845  7054  7110 I jxcore-log: 
,08-09 17:24:22.885  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-09 17:24:22.885  7054  7110 I jxcore-log: 
,08-09 17:24:23.035  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-09 17:24:23.035  7054  7110 I jxcore-log: 
,08-09 17:24:23.054  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-09 17:24:23.054  7054  7110 I jxcore-log: 
,08-09 17:24:23.092  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-09 17:24:23.092  7054  7110 I jxcore-log: 
,08-09 17:24:23.108  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-09 17:24:23.108  7054  7110 I jxcore-log: 
,08-09 17:24:23.132  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-09 17:24:23.132  7054  7110 I jxcore-log: 
,08-09 17:24:23.174  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-09 17:24:23.174  7054  7110 I jxcore-log: 
,08-09 17:24:23.363  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-09 17:24:23.363  7054  7110 I jxcore-log: 
,08-09 17:24:23.391  7054  7110 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-09 17:24:23.391  7054  7110 I jxcore-log: 
,08-09 17:24:23.399  7054  7110 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-09 17:24:23.400  7054  7110 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-09 17:24:23.400  7054  7110 I jxcore-log: 
08-09 17:24:24.261  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1877449028] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:24:24.264  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1877449031] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:24:24.264  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:27.288  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=8.8, 0.0, 0.0  rx=8.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1877452056] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 17:24:27.291  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=8.8, 0.0, 0.0  rx=8.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1877452059] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 17:24:27.291  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:30.316  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1877455084] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-09 17:24:30.327  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1877455095] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-09 17:24:30.328  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:33.349  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1877458117] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-09 17:24:33.352  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1877458120] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:24:33.352  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:36.376  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1877461144] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-09 17:24:36.387  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1877461155] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-09 17:24:36.387  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-09 17:24:37.014  1037  1541 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-09 17:24:37.015  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-09 17:24:37.016  1037  1541 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-09 17:24:37.017  1037  1541 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-09 17:24:37.029  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-09 17:24:37.031  1037  1541 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-09 17:24:37.882  7054  7110 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-09 17:24:37.882  7054  7110 I jxcore-log: 
,08-09 17:24:38.201  8895  8895 D AndroidRuntime: 
08-09 17:24:38.201  8895  8895 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-09 17:24:38.204  8895  8895 D AndroidRuntime: CheckJNI is OFF
08-09 17:24:38.423  8895  8895 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-09 17:24:38.445  1037  1094 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-09 17:24:38.445  1037  1094 I ActivityManager: Killing 7054:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-09 17:24:38.522  1037  1578 I WindowState: WIN DEATH: Window{2e5a006c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-09 17:24:38.525  1037  1547 D WifiService: Client connection lost with reason: 4
08-09 17:24:38.535  1037  1578 D InputDispatcher: Window went away: Window{2e5a006c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-09 17:24:38.664  1037  1094 I ActivityManager:   Force finishing activity ActivityRecord{208e55d1 u0 com.test.thalitest/.MainActivity t2}
,08-09 17:24:38.700   333   360 E GBMv2   : DFP En is all cleared set to be enabled
08-09 17:24:38.708  1037  2005 W ActivityManager: Spurious death for ProcessRecord{2655db6f 7054:com.test.thalitest/u0a118}, curProc for 7054: null
,08-09 17:24:38.718  1037  1119 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-09 17:24:38.719  1971  1986 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-09 17:24:38.719  1971  1986 D SplitWindowPolicy: topRunningActivity=ActivityInfo{887c87e co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
08-09 17:24:38.720  1971  4351 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-09 17:24:38.721  1971  4351 D SplitWindowPolicy: topRunningActivity=ActivityInfo{105af1df co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
08-09 17:24:38.725  1037  1119 I ActivityManager:   Force finishing activity ActivityRecord{208e55d1 u0 com.test.thalitest/.MainActivity t2 f}
08-09 17:24:38.725  1037  1119 W ActivityManager: Duplicate finish request for ActivityRecord{208e55d1 u0 com.test.thalitest/.MainActivity t2 f}
,08-09 17:24:38.768  1037  1094 D SplitWindowManager: removeStackAndNeedHomeResume ActivityStack{2244707c stackId=1, 0 tasks}
08-09 17:24:38.769  2092  2092 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-09 17:24:38.773  2092  2092 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-09 17:24:38.781  2092  2092 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-09 17:24:38.781  2092  2176 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-09 17:24:38.786  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-09 17:24:38.792  1037  1471 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-09 17:24:38.796  2470  2621 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-09 17:24:38.796  2033  2033 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-09 17:24:38.798  4977  4977 I art     : Explicit concurrent mark sweep GC freed 8416(479KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 552us total 56.674ms
08-09 17:24:38.799  3807  3807 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-09 17:24:38.801  8226  8226 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-09 17:24:38.801  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-09 17:24:38.804  8469  8469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-09 17:24:38.805  4867  4867 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-09 17:24:38.805  4867  4867 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-09 17:24:38.805  4867  4867 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-09 17:24:38.805  4867  4867 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-09 17:24:38.805  4867  4867 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 17:24:38.805  4867  4867 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 17:24:38.805  4867  4867 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 17:24:38.805  4867  4867 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 17:24:38.805  4867  4867 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 17:24:38.805  4867  4867 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 17:24:38.805  4867  4867 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 17:24:38.805  4867  4867 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 17:24:38.828  1037  1970 V SIM_STK : Menu title from STK is T-Mobile
,08-09 17:24:38.891  1037  2115 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8926 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-09 17:24:38.893  2092  2092 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-09 17:24:38.894  1934  1934 D ActionManagerService: notifyUserLog: 1000003
08-09 17:24:38.894  3807  4888 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-09 17:24:38.895  2092  2092 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-09 17:24:38.899  2092  2092 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-09 17:24:38.903  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-09 17:24:38.908  2092  2092 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-09 17:24:38.912  1934  1934 D ActionManagerService: notifyUserLog: 1000004
08-09 17:24:38.912  1821  1821 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-09 17:24:38.914  2092  2092 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-09 17:24:38.918  3807  4888 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-09 17:24:38.919  3807  3823 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , create_time: 1430832262123
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , expire_time: 0
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , display: false
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , animation: false }
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , create_time: 1430832262287
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , expire_time: 0
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , display: false
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , animation: false }
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , create_time: 1470393743569
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , expire_time: 0
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , display: false
08-09 17:24:38.921  2092  2092 I GBoardWebViewUtils: , animation: false }
08-09 17:24:38.926  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-09 17:24:38.926  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-09 17:24:38.939  1898  1898 D SplitUIManager: split_name #11 / not available #0
08-09 17:24:38.939  1898  1898 D SplitUIService: removed split : 
08-09 17:24:38.942  2230  2230 I ConfigService: onCreate
08-09 17:24:38.942  2230  2230 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-09 17:24:38.948  2092  8944 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-09 17:24:38.951  2092  2092 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-09 17:24:38.951  2092  2092 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-09 17:24:38.959  1037  1037 I art     : Explicit concurrent mark sweep GC freed 97714(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 2.278ms total 189.658ms
08-09 17:24:38.959  1037  1780 I art     : WaitForGcToComplete blocked for 91.794ms for cause Explicit
08-09 17:24:38.960  2230  2230 I ConfigService: onBind returning update interface
,08-09 17:24:38.962  2230  2230 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-09 17:24:38.962  2230  2230 I ConfigService: onBind returning config service
08-09 17:24:38.974  1821  1821 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-09 17:24:38.989  1037  1653 V SIM_STK : Menu title from STK is T-Mobile
08-09 17:24:38.989  1037  1653 V SIM_STK : Menu title from STK is T-Mobile
,08-09 17:24:38.990  1898  1898 D SplitUIManager: split_name #11 / not available #0
08-09 17:24:38.990  1898  1898 I SplitUIService: split app #11
,08-09 17:24:38.993  8926  8926 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-09 17:24:38.999  1821  1821 I ConfigFetchService: service connected
08-09 17:24:38.999  1821  1821 I ConfigClient: service connected
08-09 17:24:39.016  1606  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-09 17:24:39.016  1606  1664 D KeyguardModel: createShortcutInfo...
,08-09 17:24:39.026  1037  1037 D administrator: Handling package changes for user 0
08-09 17:24:39.028  1606  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-09 17:24:39.028  1606  1664 D KeyguardModel: createShortcutInfo...
08-09 17:24:39.028  2092  2092 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-09 17:24:39.032  1606  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-09 17:24:39.032  1606  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 17:24:39.032  1606  1664 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-09 17:24:39.033  1606  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-09 17:24:39.034  1606  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 17:24:39.034  1606  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-09 17:24:39.035  1606  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-09 17:24:39.035  1606  1664 D KeyguardModel: createShortcutInfo...
,08-09 17:24:39.041  1606  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-09 17:24:39.041  1606  1664 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 17:24:39.042  2230  2230 I ConfigService: onDestroy
08-09 17:24:39.047   325   446 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-09 17:24:39.048  3249  8949 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-09 17:24:39.049  1606  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 17:24:39.049  1606  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-09 17:24:39.051  1037  2091 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-09 17:24:39.052  1606  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-09 17:24:39.052  1606  1664 D KeyguardModel: createShortcutInfo...
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 17:24:39.053  8226  8226 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-09 17:24:39.061  1606  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 17:24:39.061  1606  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-09 17:24:39.061  1606  1664 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-09 17:24:39.061  1606  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-09 17:24:39.062  1606  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 17:24:39.063  1606  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-09 17:24:39.064  1606  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-09 17:24:39.064  1606  1664 D KeyguardModel: createShortcutInfo...
08-09 17:24:39.066  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-09 17:24:39.066  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-09 17:24:39.085  1821  8950 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-09 17:24:39.092  1606  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-09 17:24:39.092  1606  1664 D KeyguardModel: createShortcutInfo...
08-09 17:24:39.094  2092  2092 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-09 17:24:39.097  2092  2092 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 17:24:39.098  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-09 17:24:39.100  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-09 17:24:39.101  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-09 17:24:39.101  1606  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-09 17:24:39.101  1606  1664 D KeyguardModel: createShortcutInfo...
08-09 17:24:39.102  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-09 17:24:39.103  1606  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-09 17:24:39.103  1037  1780 I art     : Explicit concurrent mark sweep GC freed 8843(643KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 5.883ms total 142.429ms
08-09 17:24:39.103  1606  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-09 17:24:39.109  1037  1119 I art     : WaitForGcToComplete blocked for 211.627ms for cause Explicit
08-09 17:24:39.110  1606  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-09 17:24:39.110  1606  1664 D KeyguardModel: createShortcutInfo...
08-09 17:24:39.111  1606  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 17:24:39.111  1606  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-09 17:24:39.112  1606  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-09 17:24:39.112  1606  1664 D KeyguardModel: createShortcutInfo...
08-09 17:24:39.113  1606  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 17:24:39.113  1606  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-09 17:24:39.114  1606  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-09 17:24:39.114  1606  1664 D KeyguardModel: createShortcutInfo...
,08-09 17:24:39.124  2092  2092 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-09 17:24:39.124  2092  2092 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-09 17:24:39.129  7361  7361 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-09 17:24:39.136  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-09 17:24:39.136  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-09 17:24:39.138  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-09 17:24:39.139  2092  2092 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-09 17:24:39.139  2092  2092 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-09 17:24:39.140  1037  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17e81b90 u0 com.lge.launcher2/.Launcher t1} time:446891
08-09 17:24:39.147  2092  2092 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-09 17:24:39.147  2092  2294 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-09 17:24:39.147  2092  2294 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-09 17:24:39.159  1037  1053 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8956 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-09 17:24:39.160  1037  1053 I ActivityManager: Killing 7910:com.lge.settings.easy/1000 (adj 15): empty #17
,08-09 17:24:39.163  1037  1915 V SIM_STK : Menu title from STK is T-Mobile
08-09 17:24:39.169  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-09 17:24:39.169  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-09 17:24:39.170  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-09 17:24:39.222  1037  1119 I art     : Explicit concurrent mark sweep GC freed 3752(227KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.277ms total 109.980ms
,08-09 17:24:39.229  2650  2650 D [Concierge]Service: onStartCommand(). Type : 8
08-09 17:24:39.229  2650  2650 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-09 17:24:39.231  2650  2650 D [Concierge]Service: Update widget ID : 11
08-09 17:24:39.231  2092  2092 D [Concierge]WidgetView: change position of spinner
08-09 17:24:39.232  2650  2650 D [Concierge]Service: onStartCommand(). Type : 0
08-09 17:24:39.232  2092  2092 I [Concierge]WidgetView: initWebView(). Time : 1470756279232
08-09 17:24:39.232  1037  2091 W libprocessgroup: failed to open /acct/uid_1000/pid_7910/cgroup.procs: No such file or directory
,08-09 17:24:39.249  1037  1581 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-09 17:24:39.255  5855  8974 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-09 17:24:39.255  1821  8975 I PeopleContactsSync: CP2 sync disabled
08-09 17:24:39.260  2092  2092 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 315364364
08-09 17:24:39.260  2092  2092 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-09 17:24:39.261  2092  2092 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-09 17:24:39.263  2092  2092 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2fae8418
08-09 17:24:39.263  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-09 17:24:39.264  2092  2092 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-09 17:24:39.264  2092  2092 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 17:24:39.269  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-09 17:24:39.269  1821  5180 I Icing   : doRemovePackageData com.test.thalitest
08-09 17:24:39.270  2092  2092 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-09 17:24:39.270  2092  2092 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-09 17:24:39.271  2092  2092 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470755861036, New one : 1470756279232
08-09 17:24:39.271  2092  2092 D [Concierge]WidgetView: Unregister all receivers
08-09 17:24:39.271  2092  2092 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-09 17:24:39.271  2092  2092 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 17:24:39.273  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-09 17:24:39.274  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-09 17:24:39.275  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-09 17:24:39.276  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-09 17:24:39.277  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-09 17:24:39.280  8956  8956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 17:24:39.281  8956  8956 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 17:24:39.281  8956  8956 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-09 17:24:39.281  2092  2092 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 17:24:39.282  2092  2092 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 17:24:39.282  8956  8956 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-09 17:24:39.285  8956  8956 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-09 17:24:39.290  1821  8973 W GmsApplication: Using Auth Proxy for data requests.
08-09 17:24:39.294  1821  8973 W GmsApplication: Using Auth Proxy for data requests.
08-09 17:24:39.310  2092  2092 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-09 17:24:39.318  2092  2092 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-09 17:24:39.318  2092  2092 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-09 17:24:39.328  2092  2092 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-09 17:24:39.336  8895  8895 D AndroidRuntime: Shutting down VM
08-09 17:24:39.349  2092  2092 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e9ba65d time:447100
,08-09 17:24:39.371  1037  1119 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8979 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-09 17:24:39.400  8956  8956 I SystemConfig: BUILD Country: EU
08-09 17:24:39.400  8956  8956 I SystemConfig: BUILD Operator: OPEN
08-09 17:24:39.406  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1877464174] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:24:39.407  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1877464175] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-09 17:24:39.407  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 17:24:39.416  1037  1052 I ActivityManager: Killing 8448:com.lge.bnr/1000 (adj 15): empty #17
08-09 17:24:39.496  2092  2092 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-09 17:24:39.499  1037  1578 W libprocessgroup: failed to open /acct/uid_1000/pid_8448/cgroup.procs: No such file or directory
08-09 17:24:39.503  1037  2115 I ActivityManager: Killing 8423:com.lge.sync/1000 (adj 15): empty #17
08-09 17:24:39.533  2092  2910 I GBoardtInterface: onReloaded()
,08-09 17:24:39.534  2092  2092 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-09 17:24:39.599  1037  1915 W libprocessgroup: failed to open /acct/uid_1000/pid_8423/cgroup.procs: No such file or directory
,08-09 17:24:39.603  8956  8998 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-09 17:24:39.603  3807  3823 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 17:24:39.603  8956  8998 I SystemConfig: existFile = false
08-09 17:24:39.603  8956  8998 I SystemConfig: canReadFile = false
08-09 17:24:39.603  8956  8998 I SystemConfig: systemFeature RCS result false
08-09 17:24:39.604  8956  8998 D SystemConfig: refreshRcsSupport() :false
08-09 17:24:39.606  8628  8628 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-09 17:24:39.606  3807  4884 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 17:24:39.608  2247  9001 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-09 17:24:39.618  1037  1093 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-09 17:24:39.637  1037  2267 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=9003 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-09 17:24:39.645  1934  1934 D ActionManagerService: notifyUserLog: 1000001
08-09 17:24:39.646  3807  4888 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-09 17:24:39.646  3807  4888 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-09 17:24:39.649  1934  1934 D ActionManagerService: notifyUserLog: 1000001
,08-09 17:24:39.650  3807  4888 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-09 17:24:39.650  3807  4888 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-09 17:24:39.650  3807  4888 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-09 17:24:39.650  3807  4888 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-09 17:24:39.651  3807  3823 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 17:24:39.653  2092  2092 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-09 17:24:39.653  2092  2092 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-09 17:24:39.655  2092  2092 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-09 17:24:39.655  2092  2092 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-09 17:24:39.657  2092  2092 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-09 17:24:39.657  2092  2092 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-09 17:24:39.674  4867  4918 E SQLiteDatabase: Error inserting f004=13 f005=9003 f002=1470756279638 f003=com.android.gallery3d f006=10027
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at com.lge.mlt.MptMainLogProvider.insert(MptMainLogProvider.java:1340)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2585)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-09 17:24:39.674  4867  4918 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
08-09 17:24:39.685  9003  9003 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 17:24:39.685  9003  9003 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.

```
